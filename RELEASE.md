Infineon WiFi Linux WiFi Solution - Release Notes
=================================================

Release Version
---------------
v5.10.9-2022_0511


Release Date
------------
2022-05-11


WiFi Driver Change List
-----------------------
1. brcmfmac: set F2 blocksize and watermark for 4373 [v5.8-rc1]
1. non-upstream: add sg parameters dts parsing [x]
1. brcmfmac: set apsta to 0 when AP starts on primary interface [v5.8-rc1]
1. brcmfmac: support AP isolation [-]
1. brcmfmac: make firmware eap_restrict a module parameter [-]
1. non-upstream: support wake on ping packet [x]
1. non-upstream: remove WOWL configuration in disconnect state [x]
1. brcmfmac: make setting SDIO workqueue WQ_HIGHPRI a module parameter [-]
1. brcmfmac: remove "arp_hostip_clear" from "brcmf_netdev_stop" [v5.8-rc1]
1. brcmfmac: P2P CERT 6.1.9-Support GOUT handling P2P Presence Request [v5.8-rc1]
1. brcmfmac: only generate random p2p address when needed [v5.8-rc1]
1. brcmfmac: increase max hanger slots from 1K to 3K in fws layer [v5.7-rc1]
1. brcmfmac: map 802.1d priority to precedence level based on AP WMM params [v5.8-rc1]
1. brcmfmac: set state of hanger slot to FREE when flushing PSQ [v5.9-rc1]
1. brcmfmac: add RSDB condition when setting interface combinations [v5.6-rc1]
1. brcmfmac: not set mbss in vif if firmware does not support MBSS [v5.6-rc1]
1. brcmfmac: support the second p2p connection [v5.8-rc1]
1. brcmfmac: add support for BCM4359 SDIO chipset [v5.6-rc1]
1. brcmfmac: send port authorized event for FT-802.1X [v5.5-rc1]
1. brcmfmac: add vendor ie for association responses [v5.8-rc1]
1. brcmfmac: fix 4339 CRC error under SDIO 3.0 SDR104 mode [v5.8-rc1]
1. brcmfmac: fix the incorrect return value in brcmf_inform_single_bss(). [v5.7-rc1]
1. brcmfmac: Fix double freeing in the fmac usb data path [v5.7-rc1]
1. brcmfmac: Fix driver crash on USB control transfer timeout [v5.7-rc1]
1. brcmfmac: avoid network disconnection during suspend with linux-3.8 and above kernel [x]
1. brcmfmac: allow credit borrowing for all access categories [v5.9-rc1]
1. non-upstream: Changes to improve USB Tx throughput. [x]
1. brcmfmac: reset two D11 cores if chip has two D11 cores [v5.6-rc1]
1. brcmfmac: introduce module parameter to configure default PM mode
1. brcmfmac: configure wowl parameters in suspend function only if firmware support wowl [x]
1. brcmfmac: keep SDIO watchdog running when console_interval is non-zero [v5.9-rc1]
1. brcmfmac: To fix kernel crash on out of boundary access [v5.9-rc1]
1. brcmfmac: reduce maximum station interface from 2 to 1 in RSDB mode [v5.9-rc1]
1. brcmfmac: validate ifp pointer in brcmf_txfinalize [v5.2-rc1]
1. brcmfmac: clean up iface mac descriptor before de-initializing it [v5.2-rc1]
1. brcmfmac: To fix Bss Info flag definition Bug [v5.9-rc1]
1. brcmfmac: disable command decode in sdio_aos for 4356 [x]
1. brcmfmac: increase default max WOWL patterns to 16
1. non-upstream: Enable, Process, and forward PHY_TEMP event. [x]
1. brcmfmac: Use FW priority definition to initialize WMM AC priority array [v5.9-rc1]
1. brcmfmac: Fix P2P Group Formation failure via Go-neg method [v5.8-rc1]
1. brcmfmac: Add P2P Action Frame retry delay to fix GAS Comeback Response failure issue [v5.8-rc1]
1. brcmfmac: Use default FW priority when EDCA params same for all ACs [v5.9-rc1]
1. brcmfmac: fix continuous 802.1x tx pending timeout error [x]
1. brcmfmac: add sleep in bus suspend and cfg80211 resume functions [x]
1. brcmfmac: fix 43455 CRC error under SDIO 3.0 SDR104 mode [v5.8-rc1]
1. brcmfmac: set F2 blocksize and watermark for 4359 [v5.6-rc1]
1. brcmfmac: reserve 2 credits for host tx control path [v5.9-rc1]
1. brcmfmac: update tx status flags to sync with firmware [v5.9-rc1]
1. brcmfmac: fix credit reserve for each access category [-]
1. brcmfmac: fix throughput zero stalls on PM 1 mode due to credit map [v5.9-rc1]
1. brcmfmac: 43012 Update MES Watermark [v5.8-rc1]
1. brcmfmac: add support for CYW89359 SDIO chipset [x]
1. brcmfmac: add CYW43570 PCIE device
1. brcmfmac: Use seq/seq_len and set iv_initialize when plumbing of rxiv in (GTK) keys [v5.8-rc1]
1. brcmfmac: use actframe_abort to cancel ongoing action frame [v5.8-rc1]
1. brcmfmac: fix scheduling while atomic issue when deleting flowring [x]
1. brcmfmac: increase message buffer size for control packets [v5.9-rc1]
1. brcmfmac: Support 89459 pcie
1. brcmfmac: Fix for unable to return to visible SSID [v5.9-rc1]
1. brcmfmac: Fix for wrong disconnection event source information. [v5.9-rc1]
1. brcmfmac: add support for SAE authentication offload [v5.5-rc1]
1. brcmfmac: Support multiple AP interfaces and fix STA disconnection issue
1. brcmfmac: Support custom PCIE BAR window size.
1. brcmfmac: set F2 blocksize and watermark for 4354 [v5.8-rc1]
1. brcmfmac: support for virtual interface creation from firmware [-]
1. brcmfmac: set security after reiniting interface [v5.8-rc1]
1. brcmfmac: increase dcmd maximum buffer size [-]
1. brcmfmac: set F2 blocksize and watermark for 4356 SDIO [v5.8-rc1]
1. brcmfmac: set net carrier on via test tool for AP mode [-]
1. nl80211: add authorized flag back to ROAM event
1. brcmfmac: set authorized flag in ROAM event for offload FT roaming
1. brcmfmac: set authorized flag in ROAM event for PMK caching
1. nl80211: add authorized flag to CONNECT event
1. brcmfmac: set authorized flag in CONNECT event for PMK caching
1. brcmfmac: add support for Opportunistic Key Caching
1. nl80211: support 4-way handshake offloading for WPA/WPA2-PSK in AP mode [v5.9-rc1]
1. brcmfmac: support 4-way handshake offloading for WPA/WPA2-PSK in AP mode [v5.10-rc1]
1. nl80211: support SAE authentication offload in AP mode [v5.10-rc1]
1. brcmfmac: support SAE authentication offload in AP mode [v5.10-rc1]
1. brcmfmac: add USB autosuspend feature support [v5.7-rc1]
1. brcmfmac: To support printing USB console messages [-]
1. brcmfmac: reset SDIO bus on a firmware crash [v5.9-rc1]
1. brcmfmac: fix for WPA/WPA2-PSK 4-way handshake and SAE offload failures [v5.8-rc1]
1. non-upstream: Fix no P2P IE in probe requests issue [x]
1. brcmfmac: add 54591 PCIE device
1. brcmfmac: support DS1 exit firmware re-download [x]
1. brcmfmac: fix 43012 insmod-after-rmmod in DS1 failure. [x]
1. brcmfmac: fix 43012 driver reload failure after DS1 exit [x]
1. brcmfmac: reset PMU, backplane & all cores in CYW4373 during rmmod
1. brcmfmac: do not disconnect for disassoc frame from unconnected AP [v5.9-rc1]
1. brcmfmac: Set pacing shift before transmitting skb to bus [v5.9-rc1]
1. brcmfmac: fix 802.1d priority to ac mapping for pcie dongles [v5.8-rc1]
1. non-upstream: calling skb_orphan before sending skb to SDIO bus [x]
1. non-upstream: workaround for 4373 USB WMM 5.2.27 test failure [x]
1. brcmfmac: disable command decode in sdio_aos for 4373 [x]
1. brcmfmac: disable command decode in sdio_aos for 4339 [x]
1. brcmfmac: disable command decode in sdio_aos for 43455 [x]
1. brcmfmac: support the forwarding packet [-]
1. brcmfmac: add a variable for packet forwarding condition [-]
1. non-upstream: don't change arp/nd offload in multicast_work [x]
1. non-upstream: revert "don't change arp/nd offload in multicast_work" [x]
1. brcmfmac: don't allow arp/nd offload to be enabled if ap mode exists [-]
1. brcmfmac: fix permanent MAC address in wiphy is all zero address [v5.9-rc1]
1. non-upstream: ignore FW BADARG error when removing non-existed pkt filter [x]
1. Revert "brcmfmac: validate ifp pointer in brcmf_txfinalize" [x]
1. Revert "brcmfmac: clean up iface mac descriptor before de-initializing it" [x]
1. brcmfmac: Support DPP feature [-]
1. brcmfmac: move firmware path to cypress folder
1. brcmfmac: add support for sof time-stammping for tx packets
1. Revert "brcmfmac: add support for CYW89359 SDIO chipset" [x]
1. brcmfmac: initialize the requested dwell time [v5.9-rc1]
1. non-upstream: free eventmask_msg after updating event mask [x]
1. brcmfmac: fix invalid address access when enabling SCAN log level
1. brcmfmac: calling brcmf_free when removing SDIO device
1. brcmfmac: add a timer to read console periodically in PCIE bus
1. brcmfmac: return error when getting invalid max_flowrings from dongle
1. brcmfmac: Fix to add skb free for TIM update info when tx is completed
1. brcmfmac: Fix to add brcmf_clear_assoc_ies when rmmod
1. brcmfmac: dump dongle memory when attaching failed
1. brcmfmac: update address mode via test tool for AP mode
1. brcmfmac: load 54591 firmware for chip ID 0x4355
1. brcmfmac: reserve tx credit only when txctl is ready to send [v5.9-rc1]
1. brcmfmac: Fix interoperating DPP and other encryption network access [-]
1. brcmfmac: fix SDIO bus errors during high-temp tests
1. brcmfmac: Add dump_survey cfg80211 ops for HostApd AutoChannelSelection
1. brcmfmac: Fix warning message after dongle setup failed [v5.10-rc1]
1. revert: brcmfmac: set state of hanger slot to FREE when flushing PSQ [x]
1. brcmfmac: Fix warning when hitting FW crash with flow control feature [v5.10-rc1]
1. brcmfmac: correctly remove all p2p vif
1. brcmfmac: use firmware_request_nowarn for the board-specific nvram
1. brcmfmac: fix firmware trap while dumping obss stats
1. brcmfmac: add creating station interface support
1. brcmfmac: support station interface creation version 1, 2 and 3
1. brcmfmac: To fix crash when platform does not contain platform data/DTS
1. brcmfmac: Remove the call to "dtim_assoc" IOVAR
1. brcmfmac: fix CERT-P2P:5.1.10 failure
1. brcmfmac: Fix for when connect request is not success
1. brcmfmac: Avoiding Connection delay
1. non-upstream: Revert "brcm80211: select WANT_DEV_COREDUMP conditionally for brcmfmac"
1. brcmfmac: Fix connecting enterprise AP failure
1. brcmfmac: Fix for skbuf allocation failure in memory limited system
1. brcmfmac: Update SSID of hidden AP while informing its bss to cfg80211 layer
1. brcmfmac: Fix PCIE suspend/resume issue
1. brcmfmac: disable mpc when power_save is disabled
1. brcmfmac: Fix authentication latency caused by OBSS stats survey
1. brcmfmac: support external SAE authentication in station mode
1. brcmfmac: fix sdio watchdog timer start fail issue
1. brcmfmac: Frameburst vendor command addition
1. brcmfmac-add-support-for-CYW43439-SDIO-chipset
1. brcmfmac-add-BT-shared-SDIO-support
1. brcmfmac-add-CYW43439-SR-related-changes
1. brcmfmac-add-support-for-CYW43439-with-blank-OTP
1. brcmfmac-support-43439-Cypress-Vendor-and-Device-ID
1. brcmfmac-fix-P2P-device-discovery-failure
1. brcmfmac-Add-SDIO-verdor-device-id-for-CYW89459-in-h
1. brcmfmac-Add-CYW89459-HW-ID-and-modify-sdio-F2-block
1. brcmfmac-Fix-AP-interface-delete-issue
1. brcmfmac-Revise-channel-info-for-WPA3-external-SAE
1. brcmfmac-Fix-structure-size-for-WPA3-external-SAE
1. brcmfmac-support-54590-54594-PCIe-device-id
1. Revert-non-upstream-make-setting-SDIO-workqueue-WQ_H
1. brcmfmac-revise-SoftAP-channel-setting
1. cfg80211-make-certificate-generation-more-robust
1. brcmfmac-Optimize-CYW4373-SDIO-current
1. brcmfmac-use-request_firmware_direct-for-loading-boa
1. brcmfmac-enable-pmk-catching-for-ext-sae-wpa3-ap
1. brcmfmac-fixes-CYW4373-SDIO-CMD53-error
1. brcmfmac-add-PCIe-mailbox-support-for-core-revision-
1. brcmfmac-add-support-for-TRX-firmware-download
1. brcmfmac-add-Cypress-PCIe-vendor-ID
1. brcmfmac-add-support-for-CYW55560-PCIe-chipset
1. brcmfmac-add-bootloader-console-buffer-support-for-P
1. brcmfmac-support-4373-pcie
1. brcmfmac-extsae-supports-FT-over-SAE
1. brcmfmac-extsae-supports-SAE-OKC-roam
1. nl80211-add-roaming-offload-support
1. brcm80211-add-FT-11r-OKC-roaming-offload-support
1. brcmfmac-support-extsae-with-psk-1x-offloading
1. brcmfmac-disable-out-of-band-device-wake-based-DeepS
1. brcmfmac-Improve-the-delay-during-scan
1. non-upstream-skip-6G-oob-scan-report
1. brcmfmac-add-FW-AP-selection-mod-param
1. brcmfmac-changing-info-messages-under-debug-BRCMF_IN
1. brcmfmac-remove-default-2s-power-save-max-timeout
1. brcmfmac-fixes-scan-invalid-channel-when-enable-host

      [-] means under upstream review
      [x] means no plan to upstream


WiFi Driver Changes
-------------------
Change areas mapping (refer to the above sequence numbers)
* 4373 (0001, 0090, 0096)
* Device tree changes (0002)
* APSTA (0003, 0101-103)
* SoftAP (0004, 0070)
* Fast roaming (0005, 0019, 0071-0075)
* Wake on Wireless LAN (0006-0007, 0025, 0030, 0038)
* Throughput enhancement (0008, 0051, 0092, 0094)
* ARP Offload (0009)
* Peer-to-peer (0010-0011, 0041-0042, 0056, 0085, 112, 130, 137)
* USB (0012, 0014, 0022-0024, 0027, 0032, 0034-0035, 0081-0082)
* WMM (0013, 0026, 0040, 0043, 0093, 0095)
* 89359 (0015-0018, 0028, 0033, 0047, 0053, 0063, 0066-0067, 111)
* Miracast (0020)
* 4339 (0021, 0097)
* Power saving (0029, 0045, 0057, 144-145)
* SDIO (0031, 0083, 115, 125, 148)
* Firmware interface (0036, 0039, 0068, 113, 131)
* 4356 (0037, 0069)
* PCIe (0044, 0058, 0064, 0099-0100, 116-117)
* 43455 (0046, 0098)
* SDIO/USB flow control (0049-0050, 123, 128-129)
* 43012 (0052, 0087-0089)
* 43570 (0054)
* GTK rekey (0055)
* 54591 (0059, 0086, 122)
* Generic bugs (0060, 0061, 0091, 104-107, 114, 118-119, 135-136, 138-140, 142-143)
* WPA3 (0062, 0077-0080, 0084, 147)
* 4354 (0065)
* OKC (0076)
* DPP (108, 124, 141)
* Firmware naming (109)
* Monitor mode (110)
* Debug capability (120, 127)
* Manufacturing (121, 149)
* Auto channel selection (126)
* OBSS (132, 146)
* RSDB (133-134)


Hostap Change List
-----------------
1. wpa_supplicant: Support 4-way handshake offload for FT-EAP
1. wpa_supplicant: Notify Neighbor Report for driver-triggered request
1. nl80211: Report connection authorized in EVENT_ASSOC
1. wpa_supplicant: Add PMKSA cache for 802.1X 4-way handshake
1. Sync with mac80211-next.git include/uapi/linux/nl80211.h
1. nl80211: Check SAE authentication offload support
1. SAE: Pass SAE password on connect for SAE authentication offload support
1. OpenSSL: Fix build with OpenSSL 1.0.1
1. non-upstream: Sync nl80211.h for PSK 4-way HS offload support in AP mode [x]
1. nl80211: Support 4-way handshake offload for WPA/WPA2-PSK in AP mode
1. AP: Support 4-way handshake offload for WPA/WPA2-PSK
1. nl80211: Support SAE authentication offload in AP mode
1. SAE: Support SAE authentication offload in AP mode
1. P2P: Fix P2P authentication failure due to AP-mode 4-way handshake offload
1. AP: Silently ignore management frame from unexpected source address
1. DPP: Do more condition test for AKM type DPP offload.
1. hostapd: Fix PMF connection issue
1. AP: Set Authenticator state properly for PSK 4-way handshake offload
1. non-upstream:defconfig_base-Add-Infineon-default-configuration
1. P2P:Fix-copying-of-secondary-device-types-for-P2P-group-client
1. P2P:Fix-a-corner-case-in-peer-addition-based-on-PD-Request
1. wpa_supplicant:Add-CONFIG_WPA3_SAE_AUTH_EARLY_SET-flags
1. nl80211:Set-the-right-WPA-Versions-for-FT-SAE-key-manage
1. wpa_supplicant:Support-WPA_KEY_MGMT_FT-for-eapol-offloading
1. wpa_supplicant:Suppress-deauth-for-PMKSA-caching-disabled
1. wpa_supplicant:Fix-to-check-Invalid-GTK-IE-length-in-M3-at-STA
1. AP:SAE-Fix-for-PMK-expiration-issue-through-supplicant
1. wpa_supplicant:SAE-Drop-PMKSA-cache-after-receiving-specific-deauth
1. AP:Deauthenticate-STA-only-if-PMK-expired


Note: [*] is the upstream tag containing the patch
      [x] means no plan to upstream

