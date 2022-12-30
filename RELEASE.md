Infineon WiFi Linux WiFi Solution - Release Notes
=================================================

Release Version
---------------
v5.10.9-2022_0909


Release Date
------------
2022-09-09


WiFi Driver Change List
-----------------------
1. non-upstream-add-sg-parameters-dts-parsing.patch[x]
1. brcmfmac-support-AP-isolation.patch
1. non-upstream-make-firmware-eap_restrict-a-module-par.patch[x]
1. non-upstream-support-wake-on-ping-packet.patch[x]
1. non-upstream-remove-WOWL-configuration-in-disconnect.patch[x]
1. non-upstream-make-setting-SDIO-workqueue-WQ_HIGHPRI-.patch[x]
1. non-upstream-avoid-network-disconnection-during-susp.patch[x]
1. non-upstream-Changes-to-improve-USB-Tx-throughput.patch[x]
1. brcmfmac-introduce-module-parameter-to-configure-def.patch
1. non-upstream-configure-wowl-parameters-in-suspend-fu.patch[x]
1. non-upstream-disable-command-decode-in-sdio_aos-for-.patch[x]
1. brcmfmac-increase-default-max-WOWL-patterns-to-16.patch
1. non-upstream-Enable-Process-and-forward-PHY_TEMP-eve.patch[x]
1. non-upstream-fix-continuous-802.1x-tx-pending-timeou.patch[x]
1. non-upstream-add-sleep-in-bus-suspend-and-cfg80211-r.patch[x]
1. brcmfmac-add-CYW43570-PCIE-device.patch
1. non-upstream-fix-scheduling-while-atomic-issue-when-.patch[x]
1. brcmfmac-Support-89459-pcie.patch
1. brcmfmac-Support-multiple-AP-interfaces-and-fix-STA-.patch
1. non-upstream-Support-custom-PCIE-BAR-window-size.patch[x]
1. brcmfmac-support-for-virtual-interface-creation-from.patch
1. brcmfmac-increase-dcmd-maximum-buffer-size.patch
1. brcmfmac-set-net-carrier-on-via-test-tool-for-AP-mod.patch
1. nl80211-add-authorized-flag-back-to-ROAM-event.patch
1. brcmfmac-set-authorized-flag-in-ROAM-event-for-offlo.patch
1. brcmfmac-set-authorized-flag-in-ROAM-event-for-PMK-c.patch
1. nl80211-add-authorized-flag-to-CONNECT-event.patch
1. brcmfmac-set-authorized-flag-in-CONNECT-event-for-PM.patch
1. brcmfmac-add-support-for-Opportunistic-Key-Caching.patch
1. brcmfmac-To-support-printing-USB-console-messages.patch
1. non-upstream-Fix-no-P2P-IE-in-probe-requests-issue.patch[x]
1. brcmfmac-add-54591-PCIE-device.patch
1. non-upstream-support-DS1-exit-firmware-re-download.patch[x]
1. non-upstream-fix-43012-insmod-after-rmmod-in-DS1-fai.patch[x]
1. non-upstream-fix-43012-driver-reload-failure-after-D.patch[x]
1. brcmfmac-reset-PMU-backplane-all-cores-in-CYW4373-du.patch
1. non-upstream-calling-skb_orphan-before-sending-skb-t.patch[x]
1. non-upstream-workaround-for-4373-USB-WMM-5.2.27-test.patch[x]
1. non-upstream-disable-command-decode-in-sdio_aos-for-.patch[x]
1. non-upstream-disable-command-decode-in-sdio_aos-for-.patch[x]
1. non-upstream-disable-command-decode-in-sdio_aos-for-.patch[x]
1. brcmfmac-support-the-forwarding-packet.patch
1. brcmfmac-add-a-variable-for-packet-forwarding-condit.patch
1. brcmfmac-don-t-allow-arp-nd-offload-to-be-enabled-if.patch
1. non-upstream-ignore-FW-BADARG-error-when-removing-no.patch[x]
1. brcmfmac-Support-DPP-feature.patch
1. brcmfmac-move-firmware-path-to-cypress-folder.patch
1. brcmfmac-add-support-for-sof-time-stammping-for-tx-p.patch
1. non-upstream-free-eventmask_msg-after-updating-event.patch[x]
1. brcmfmac-fix-invalid-address-access-when-enabling-SC.patch
1. brcmfmac-add-a-timer-to-read-console-periodically-in.patch
1. brcmfmac-return-error-when-getting-invalid-max_flowr.patch
1. brcmfmac-Fix-to-add-skb-free-for-TIM-update-info-whe.patch
1. brcmfmac-Fix-to-add-brcmf_clear_assoc_ies-when-rmmod.patch
1. brcmfmac-dump-dongle-memory-when-attaching-failed.patch
1. brcmfmac-update-address-mode-via-test-tool-for-AP-mo.patch
1. brcmfmac-load-54591-firmware-for-chip-ID-0x4355.patch
1. brcmfmac-Fix-interoperating-DPP-and-other-encryption.patch
1. brcmfmac-fix-SDIO-bus-errors-during-high-temp-tests.patch
1. brcmfmac-Add-dump_survey-cfg80211-ops-for-HostApd-Au.patch
1. revert-brcmfmac-set-state-of-hanger-slot-to-FREE-whe.patch
1. brcmfmac-correctly-remove-all-p2p-vif.patch
1. brcmfmac-fix-firmware-trap-while-dumping-obss-stats.patch
1. brcmfmac-add-creating-station-interface-support.patch
1. brcmfmac-support-station-interface-creation-version-.patch
1. brcmfmac-To-fix-crash-when-platform-does-not-contain.patch
1. brcmfmac-Remove-the-call-to-dtim_assoc-IOVAR.patch
1. brcmfmac-fix-CERT-P2P-5.1.10-failure.patch
1. brcmfmac-Fix-for-when-connect-request-is-not-success.patch
1. brcmfmac-Avoiding-Connection-delay.patch
1. non-upstream-Revert-brcm80211-select-WANT_DEV_COREDU.patch[x]
1. brcmfmac-Fix-connecting-enterprise-AP-failure.patch
1. brcmfmac-Fix-for-skbuf-allocation-failure-in-memory-.patch
1. brcmfmac-Update-SSID-of-hidden-AP-while-informing-it.patch
1. brcmfmac-Fix-PCIE-suspend-resume-issue.patch
1. brcmfmac-disable-mpc-when-power_save-is-disabled.patch
1. brcmfmac-Fix-authentication-latency-caused-by-OBSS-s.patch
1. brcmfmac-support-external-SAE-authentication-in-stat.patch
1. brcmfmac-fix-sdio-watchdog-timer-start-fail-issue.patch
1. brcmfmac-Frameburst-vendor-command-addition.patch
1. brcmfmac-add-support-for-CYW43439-SDIO-chipset.patch
1. brcmfmac-add-BT-shared-SDIO-support.patch
1. brcmfmac-add-CYW43439-SR-related-changes.patch
1. brcmfmac-add-support-for-CYW43439-with-blank-OTP.patch
1. brcmfmac-support-43439-Cypress-Vendor-and-Device-ID.patch
1. brcmfmac-fix-P2P-device-discovery-failure.patch
1. brcmfmac-Add-SDIO-verdor-device-id-for-CYW89459-in-h.patch
1. brcmfmac-Add-CYW89459-HW-ID-and-modify-sdio-F2-block.patch
1. brcmfmac-Fix-AP-interface-delete-issue.patch
1. brcmfmac-Revise-channel-info-for-WPA3-external-SAE.patch
1. brcmfmac-Fix-structure-size-for-WPA3-external-SAE.patch
1. brcmfmac-support-54590-54594-PCIe-device-id.patch
1. Revert-non-upstream-make-setting-SDIO-workqueue-WQ_H.patch[x]
1. brcmfmac-Set-SDIO-workqueue-as-WQ_HIGHPRI.patch[v5.15-rc1]
1. brcmfmac-revise-SoftAP-channel-setting.patch
1. cfg80211-make-certificate-generation-more-robust.patch[v5.13-rc7]
1. brcmfmac-Optimize-CYW4373-SDIO-current.patch
1. brcmfmac-use-request_firmware_direct-for-loading-boa.patch
1. brcmfmac-enable-pmk-catching-for-ext-sae-wpa3-ap.patch
1. brcmfmac-fixes-CYW4373-SDIO-CMD53-error.patch
1. brcmfmac-add-PCIe-mailbox-support-for-core-revision-.patch
1. brcmfmac-add-support-for-TRX-firmware-download.patch
1. brcmfmac-add-Cypress-PCIe-vendor-ID.patch
1. brcmfmac-add-support-for-CYW55560-PCIe-chipset.patch
1. brcmfmac-add-bootloader-console-buffer-support-for-P.patch
1. brcmfmac-support-4373-pcie.patch
1. brcmfmac-extsae-supports-FT-over-SAE.patch
1. brcmfmac-extsae-supports-SAE-OKC-roam.patch
1. nl80211-add-roaming-offload-support.patch
1. brcm80211-add-FT-11r-OKC-roaming-offload-support.patch
1. brcmfmac-support-extsae-with-psk-1x-offloading.patch
1. brcmfmac-disable-out-of-band-device-wake-based-DeepS.patch
1. brcmfmac-Improve-the-delay-during-scan.patch
1. non-upstream-skip-6G-oob-scan-report.patch[x]
1. brcmfmac-add-FW-AP-selection-mod-param.patch
1. brcmfmac-changing-info-messages-under-debug-BRCMF_IN.patch
1. brcmfmac-remove-default-2s-power-save-max-timeout.patch
1. brcmfmac-fixes-scan-invalid-channel-when-enable-host.patch
1. brcmfmac-do-not-disable-controller-in-apmode-stop.patch
1. brcmfmac-support-11ax-and-6G-band.patch
1. brcmfmac-fixes-invalid-channel-still-in-the-channel-.patch
1. non-upstream-Fix-lspci-not-enumerating-wifi-device-a.patch[x]
1. brcmfmac-support-signal-monitor-feature-for-wpa_supp.patch
1. brcmfmac-add-support-for-CYW55560-SDIO-chipset.patch
1. brcmfmac-Modified-Kconfig-help-format.patch
1. brcmfmac-Fix-incorrect-WARN_ON-causing-set_pmk-failu.patch
1. brcmfmac-report-cqm-rssi-event-based-on-rssi-change-.patch
1. brcmfmac-add-WPA3_AUTH_1X_SUITE_B_SHA384-related-sup.patch
1. non-upstream-Handle-the-6G-case-in-the-bw_cap-chansp.patch[x]
1. non-upstream-Fix-kernel-crash-caused-by-race-on-time.patch[x]
1. brcmfmac-update-the-statically-defined-HE-MAC-PHY-Ca.patch
1. brcmfmac-fix-set_pmk-warning-message.patch
1. brcmfmac-update-BIP-setting-and-wsec_info-for-GMAC-a.patch
1. brcmfmac-send-roam-request-when-supplicant-triggers-.patch
1. brcmfmac-send-BCNLOST_MSG-event-on-beacon-loss-for-s.patch
1. brcmfmac-trying-to-get-GCMP-cap-before-doing-set-it.patch
1. brcmfmac-update-firmware-loading-name-for-CY5557x.patch


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
1. wpa_supplicant-Support-4-way-handshake-offload-for-F.patch
1. wpa_supplicant-Notify-Neighbor-Report-for-driver-tri.patch
1. nl80211-Report-connection-authorized-in-EVENT_ASSOC.patch
1. wpa_supplicant-Add-PMKSA-cache-for-802.1X-4-way-hand.patch
1. OpenSSL-Fix-build-with-OpenSSL-1.0.1.patch
1. nl80211-Check-SAE-authentication-offload-support.patch
1. SAE-Pass-SAE-password-on-connect-for-SAE-authenticat.patch
1. nl80211-Support-4-way-handshake-offload-for-WPA-WPA2.patch
1. AP-Support-4-way-handshake-offload-for-WPA-WPA2-PSK.patch
1. nl80211-Support-SAE-authentication-offload-in-AP-mod.patch
1. SAE-Support-SAE-authentication-offload-in-AP-mode.patch
1. DPP-Do-more-condition-test-for-AKM-type-DPP-offload.patch
1. non-upstream-defconfig_base-Add-Infineon-default-con.patch[x]
1. P2P-Fix-copying-of-secondary-device-types-for-P2P-gr.patch[master]
1. P2P-Fix-a-corner-case-in-peer-addition-based-on-PD-R.patch[master]
1. Add-CONFIG_WPA3_SAE_AUTH_EARLY_SET-flags-and-codes.patch
1. SAE-Set-the-right-WPA-Versions-for-FT-SAE-key-manage.patch
1. wpa_supplicant-Support-WPA_KEY_MGMT_FT-for-eapol-off.patch
1. wpa_supplicant-suppress-deauth-for-PMKSA-caching-dis.patch
1. CVE_2019_9501-Fix-to-check-Invalid-GTK-IE-length-in-.patch
1. non-upstream-Remove-unnecessary-file.patch[x]
1. Avoid-deauthenticating-STA-if-the-reason-for-freeing.patch
1. wpa_supplicant-support-bgscan.patch
1. non-upstream-wl-cmd-create-interface-to-support-driv.patch[x]
1. non-upstream-wl-cmd-create-wl_do_cmd-as-an-entry-doi.patch[x]
1. non-upstream-wl-cmd-create-ops-table-to-do-wl-comman.patch[x]
1. non-upstream-wl-cmd-add-more-compile-flag.patch[x]
1. base-ifx-2.10-Fix-dpp-config-parameter-setting.patch
1. base-ifx-2_10-DPP-Resolving-failure-of-dpp-configura.patch
1. base-ifx-2.10-Enabling-SUITEB192-and-SUITEB-compile-.patch
1. base-ifx-2_10-DPP-Enabling-CLI_EDIT-option-for-enrol.patch
1. base-ifx-2_10-P2P-Fixes-Scan-trigger-failed-once-GC-.patch
1. non-upstream-SAE-disconnect-after-PMKSA-cache-expire.patch[x]
1. Add-support-for-beacon-loss-roaming.patch


Note: [*] is the upstream tag containing the patch
      [x] means no plan to upstream

