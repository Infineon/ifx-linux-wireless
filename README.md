Infineon Wifi Linux WiFi Solution
=================================

Description
-----------
This is the Infineon Linux WiFi solution landing repo.

### What is in this release
* [Backports driver package](https://github.com/cypresssemiconductorco/ifx-backports)
   * The backports wireless driver source (for actual cross compilation).
   * For more information about Linux backports project, see: [Linux Backports Project](https://backports.wiki.kernel.org/index.php/Main_Page)
* [Hostapd/wpa_supplicant](https://github.com/cypresssemiconductorco/ifx-hostap)
   * The tools for controling the wireless interface(s).
* [Firmware/clm_blob files](https://github.com/cypresssemiconductorco/ifx-linux-firmware)
   * The firmware alone with the country locale settings.
* [WiFi driver](https://github.com/cypresssemiconductorco/ifx-wireless-drivers)
   * The wireless driver in a full Linux source tree (for viewing the commit-by-commit history).
   * For more information about the Linux brcmfmac project, see: [brcm80211 Wireless Wiki](https://wireless.wiki.kernel.org/en/users/drivers/brcm80211)

### What is not in this release
* Nvram file
   * Board configurations.
* Customized clm_blob file
   * Regulatory settings optimized for the board.
   * A generic sample file is included which may not provide optimal performance.
* MFG tool binaries
   * Tools for mass production.

Note: Infineon's module partners provide regulatory and test support for their
Pre-Certified or Reference Certified modules. As such, customers are
recommended to work with their selected module partner to obtain the latest
configuration, firmware and test packages which are optimized for the partner
module they have selected. This would include but is not limited to the
following: NVRAM, clm_blob and MFG Binaries.



Supported Features
------------------
| Feature            | 43455 | 4373SDIO | 4373USB | 43012 | 4356PCIe | 4354 | 43362 | 4343w | 43340 | 4339 | 43570PCIe | 54591PCIe |
|--------------------|:-----:|:--------:|:-------:|:-----:|:--------:|:----:|:-----:|:-----:|:-----:|:----:|:---------:|:---------:|
| SoftAP             |   O   |     O    |    O    |   O   |     O    |   O  |   O   |   O   |   O   |   O  |     O     |     O     |
| APSTA              |   O   |          |         |       |          |      |       |       |       |      |     O     |     O     |
| P2P                |   O   |     O    |    O    |   O   |     O    |   O  |   O   |   O   |   O   |   O  |     O     |     O     |
| WoWL               |   O   |          |         |       |          |      |       |       |       |      |           |           |
| Voice Enterprise   |   O   |          |         |       |          |      |       |       |       |      |           |           |
| OKC                |   O   |          |         |       |          |      |       |       |       |      |           |           |
| WPA3-STA           |   O   |     O    |    O    |   O   |          |      |       |       |       |      |           |           |
| WPA3-AP            |   O   |     O    |    O    |       |          |      |       |       |       |      |           |           |
| Fast Roaming       |   O   |          |         |   O   |          |      |       |       |       |      |           |           |
| Thermal Throttling |   O   |          |         |       |          |      |       |   O   |       |      |           |           |
| CYNC               |       |          |         |       |          |      |       |       |       |      |           |     O     |
| DPP                |   O   |          |         |   O   |          |      |       |       |       |      |           |     O     |
| VSDB               |       |     O    |    O    |       |          |      |       |       |       |      |           |           |



Instructions
------------
The WiFi driver is developed based on Linux v5.4.18. Older kernels need
use backports package. Below are examples of how to use this package
with an older kernel or linux-stable v5.4.18.

### Using backports with an older kernel (v3.10+)

Linux kernel image and WiFi driver modules need to be built separately.
Below is the example of using with iMX Linux v4.14.78:

#### Build the kernel image
```bash
#1. Have the BSP kernel source available
   git clone https://source.codeaurora.org/external/imx/linux-imx
   cd linux-imx
   git checkout imx_4.14.78_1.0.0_ga
#2. Set up build environment and kernel configuration
   source /opt/poky/1.8/environment-setup-cortexa7hf-vfp-neon-poky-linux-gnueabi
   make imx_v7_defconfig
#3. Edit .config and build cfg80211 as module
#     CONFIG_CFG80211=m
#     CONFIG_BCMDHD=n
#4. Enable below configs in .config
#     CONFIG_ASYMMETRIC_KEY_TYPE=y
#     CONFIG_ASYMMETRIC_PUBLIC_KEY_SUBTYPE=y
#     CONFIG_X509_CERTIFICATE_PARSER=y
#     CONFIG_PKCS7_MESSAGE_PARSER=y
#5. Build the Linux kernel image
   make oldconfig
   make zImage -j 8
#6. The kernel image is available here
   arch/arm/boot/zImage
```

#### Build the WiFi driver/backports modules
```bash
#1. Download the backports package
    git clone -b latest-v5.4 https://github.com/cypresssemiconductorco/ifx-backports.git
    cd ifx-backports/v5.4.18-backports
#2. (Native) compile local tools and generate .config (in a new terminal
#   without sourcing Yoctol toolchain settings)
    bash
    MY_KERNEL=<the 4.14.78 kernel path>
    make KLIB=$MY_KERNEL KLIB_BUILD=$MY_KERNEL defconfig-brcmfmac
#3. (Cross) compile kernel modules
    source /opt/poky/1.8/environment-setup-cortexa7hf-vfp-neon-poky-linux-gnueabi
    make KLIB=$MY_KERNEL KLIB_BUILD=$MY_KERNEL modules
#4. The kernel modules are available here
#      compat/compat.ko
#      net/wireless/cfg80211.ko
#      drivers/net/wireless/broadcom/brcm80211/brcmutil/brcmutil.ko
#      drivers/net/wireless/broadcom/brcm80211/brcmfmac/brcmfmac.ko
```

#### Device tree
```bash
#1. Download Infineon devicetree package
    git clone -b latest-v5.4 https://github.com/cypresssemiconductorco/ifx-linux-wireless.git
#2. Find your board's dtb file, for example
#      ifx-linux-wireless/devicetree/iMX6SX/4.14.78/imx6sx-sdb-btwifi-fmac.dtb
```
Note: If your board's dtb is not available in the cypress devicetree
      package, please refer to the available dts/dtsi files and create
      them for your board, then compile them for the dtb file. iMX dts
      files are located in linux-imx/arch/arm/boot/dts/ folder of the
      Linux kernel tree. Below command compiles a dtb file
```bash
    make ARCH=arm <devicetree name>.dtb
```

#### Load the cypress wifi driver
```bash
#1. Copy your boards's zImage and dtb files to the target board
    bash
    TARGET_IP=<target board IP>
    scp <dtb file> root@$TARGET_IP:/run/media/mmcblk1p1/cy.dtb
    scp <zImage file> root@$TARGET_IP:/run/media/mmcblk1p1/zImage_cy
#2. Copy firmware files to the target board
    git clone -b latest-v5.4 https://github.com/cypresssemiconductorco/ifx-linux-firmware.git
    scp ifx-linux-firmware/firmware/* root@$TARGET_IP:/lib/firmware/cypress
#3. Copy your nvram file (from board vendor) to the target board and rename it
    scp <nvram file> root@$TARGET_IP:/lib/firmware/cypress/<fw name>.txt
#      (fw name is your chip's *.bin file name in the cypress firmware package)
#4. Copy cypress kernel modules to the target board
    scp <module files> root@$TARGET_IP:/lib/modules/4.14.78
#5. (iMX console) Press ctrl-c after target boot to enter u-boot and configure it
#   for the new zImage/dtb files
   env print image fdt_file
   setenv image zImage_cy
   setenv fdt_file cy.dtb
   saveenv
   env print image fdt_file
   reset
#6. (iMX console) Boot up the target board with the above zImage and insmod cypress modules
    insmod /lib/modules/4.14.78/compat.ko
    insmod /lib/modules/4.14.78/cfg80211.ko
    insmod /lib/modules/4.14.78/brcmutil.ko
    insmod /lib/modules/4.14.78/brcmfmac.ko
```
Note: More on fmac driver [firmware/nvram install](https://wireless.wiki.kernel.org/en/users/drivers/brcm80211#firmware_installation1)

### Using Linux Stable v5.4.18
```bash
#1. Download Linux kernel source
    git clone -b latest-v5.4 https://github.com/cypresssemiconductorco/ifx-wireless-drivers.git
#2. Set kernel .config and enable below options, then compile kernel image
#      CONFIG_BRCMUTIL=y
#      CONFIG_BRCMFMAC=y
#      CONFIG_BRCMFMAC_SDIO=y
#      CONFIG_BRCMFMAC_PROTO_BCDC=y
#      CONFIG_BRCMFMAC_PCIE=y
#      CONFIG_BRCMFMAC_PROTO_MSGBUF=y
#3. (optional) Backup original firmware files
    cp /lib/firmware/cypress /lib/firmware/cypress-bak -r
#4. Update firmware files in /lib/firmware/cypress
    git clone -b latest-v5.4 https://github.com/cypresssemiconductorco/ifx-linux-firmware.git
    cp ifx-linux-firmware/firmware/* /lib/firmware/cypress
#5. Boot the system with the new kernel image
```


Instructions - Hostap
---------------------
The patch files in this package are based on Hostap v2.9. Below is an example
of how to apply these files and build hostapd/wpa_supplicant binaries.

### Build the hostapd/wpa_supplicant binaries
```bash
#1. Download Hostap source
    git clone -b latest-2_9 https://github.com/cypresssemiconductorco/ifx-hostap.git
#2. (Hostapd) in hostapd root directory, set up the build configuration file,
#   .config, and build hostapd and hostapd_cli
    cd ifx-hostap/hostapd
    cp defconfig .config
    make clean
    make
#3. (Wpa_supplicant) in wpa_supplicant root directory, set up the build configuration
#   file, .config, and build wpa_supplicant and wpa_cli
    cd ../wpa_supplicant
    cp defconfig .config
    make clean
    make
#4. The binaries are available here
#     hostap_2_9/hostapd/hostapd
#     hostap_2_9/hostapd/hostapd_cli
#     hostap_2_9/wpa_supplicant/wpa_supplicant
#     hostap_2_9/wpa_supplicant/wpa_cli
```
Note: Set CONFIG_SAE=y in .config to enable WPA3-Personal (SAE) support.


Test Environment
----------------
* ARM (MCIMX6SX-SDB)
   * Linux v4.14.78 (NXP imx_4.14.78_1.0.0_ga)
   * Backports driver package
* x86
   * Linux v4.12
   * Backports driver package

