Infineon WiFi Linux WiFi Solution - Release Notes
=================================================

Release Version
---------------
v5.15.58-2023_0523

Release Date
------------
2023-05-23


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
1. brcmfmac-extsae-supports-SAE-OKC-roam.patch
1. nl80211-add-roaming-offload-support.patch
1. brcm80211-add-FT-11r-OKC-roaming-offload-support.patch
1. brcmfmac-support-extsae-with-psk-1x-offloading.patch
1. Disable-out-of-band-device-wake-based-DeepSleep-Stat.patch
1. brcmfmac-Improve-the-delay-during-scan.patch
1. brcmfmac-skip-6G-oob-scan-report.patch
1. Revert-brcmfmac-Improve-the-delay-during-scan.patch
1. brcmfmac-Improve-the-delay-during-scan.patch
1. brcmfmac-add-FW-AP-selection-mod-param.patch
1. Changing-info-messages-under-debug-BRCMF_INFO_VAL.patch
1. revert-brcmfmac-Set-timeout-value-when-configuring-p.patch
1. brcmfmac-fixes-scan-invalid-channel-when-enable-host.patch
1. brcmfmac-do-not-disable-controller-in-apmode-stop.patch
1. brcmfmac-support-11ax-and-6G-band.patch
1. brcmfmac-fixes-invalid-channel-still-in-the-channel-.patch
1. non-upstream-Fix-lspci-not-enumerating-wifi-device-a.patch
1. brcmfmac-support-signal-monitor-feature-for-wpa_supp.patch
1. brcmfmac-add-support-for-CYW55560-SDIO-chipset.patch
1. brcmfmac-Modified-Kconfig-help-format.patch
1. brcmfmac-Fix-incorrect-WARN_ON-causing-set_pmk-failu.patch
1. brcmfmac-report-cqm-rssi-event-based-on-rssi-change-.patch
1. brcmfmac-add-WPA3_AUTH_1X_SUITE_B_SHA384-related-sup.patch
1. non-upstream-Handle-the-6G-case-in-the-bw_cap-chansp.patch[x]
1. net-brcm80211-Fix-race-on-timer_add-in-wifi-driver.patch
1. Remove-WARN_ON-while-no-6g-bw_cap.patch
1. brcmfmac-update-the-statically-defined-HE-MAC-PHY-Ca.patch
1. brcmfmac-fix-set_pmk-warning-message.patch
1. brcmfmac-update-BIP-setting-and-wsec_info-for-GMAC-a.patch
1. brcmfmac-send-roam-request-when-supplicant-triggers-.patch
1. brcmfmac-send-BCNLOST_MSG-event-on-beacon-loss-for-s.patch
1. brcmfmac-trying-to-get-GCMP-cap-before-doing-set-it.patch
1. brcmfmac-update-firmware-loading-name-for-CY5557x.patch
1. brcmfmac-use-SR-core-id-to-decide-SR-capability-for-.patch
1. brcmfmac-SAP-mode-parsing-sae_h2e-setting-from-beaco.patch
1. brcmfmac-add-sanity-check-for-potential-underflow-an.patch
1. brcmfmac-Fixing-vulnerability.patch
1. brcmfmac-Implementing-set_bitrate_mask-cfg80211-ops-.patch
1. brcm80211-add-FT-PSK-roaming-offload-support.patch
1. brcmfmac-enable-6G-split-scanning-feature.patch
1. brcmfmac-set-HE-6GHz-capabilities-for-bring-up-SAP.patch
1. brcmfmac-add-interface-to-set-bsscolor-for-bring-up-.patch
1. non-upstream-add-IFX-vendor-OUI-file.patch
1. non-upstream-adding-vendor_cmds-are-with-IFX_OUI.patch
1. brcmfmac-introduce-a-module-parameter-to-disable-the.patch
1. brcmfmac-skip-6GHz-capab-registration-with-cfg80211-.patch
1. brcmfmac-set-HE-rate-only-if-HE-MCS-set-and-valid.patch
1. brcmfmac-remove-workaround-cause-the-FW-can-support-.patch
1. brcmfmac-ext_owe-supporting.patch
1. brcmfmac-Avoid-adding-two-sets-of-HE-Capab-and-Oper-.patch
1. non-upstream-Add-IFX-TWT-Offload-support.patch
1. non-upstream-vendor-cmd-addition-for-wl-he-bsscolor.patch[x]
1. non-upstream-vendor-cmd-addition-for-wl-he-muedca_op.patch[x]
1. non-upstream-vendor-cmd-addition-for-wl-amsdu.patch[x]
1. non-upstream-vendor-cmd-addition-for-wl-ldpc_cap.patch[x]
1. non-upstream-Refine-TWT-code-for-checkpatch.patch[x]
1. cfg80211-fix-u8-overflow-in-cfg80211_update_notliste.patch
1. cfg80211-mac80211-reject-bad-MBSSID-elements.patch
1. cfg80211-fix-BSS-refcounting-bugs.patch
1. cfg80211-avoid-nontransmitted-BSS-list-corruption.patch
1. brcmfmac-Fix-potential-buffer-overflow-in-brcmf_fweh.patch
1. non-upstream-vendor-cmd-addition-for-wl-oce-enable.patch[x]
1. non-upstream-vendor-cmd-addition-for-wl-randmac.patch[x]
1. brcmfmac-compile-warning-fix.patch
1. Fix-invalid-RAM-address-warning-for-PCIE-platforms.patch
1. brcmfmac-Fix-dpp-very-low-tput-issue.patch
1. non-upstream-keep-IFX-license-header-for-non-upstrea.patch[x]
1. non-upstream-internal-sup-uses-join-command-to-send-.patch[x]
1. non-upstream-Supporting-IFX_vendor-commands-of-MBO.patch[x]
1. brcmfmac-Set-corresponding-cqm-event-handlers-based-.patch
1. non-upstream-isolate-power_save-off-and-mpc-0.patch[x]
1. brcmfmac-Add-NULL-checks-to-fix-multiple-NULL-pointe.patch[x]
1. brcmfmac-fix-compiler-error.patch
1. non-upstream-supporting-giartrx-IFX-vendor-ID.patch[x]
1. wireless-brcmfmac-Use-netif_rx.patch
1. brcmfmac-replace-SDIO-function-number-with-definitio.patch
1. brcmfmac-move-SDIO-function-number-definition-to-sdi.patch
1. Restore-channel-info.patch
1. brcmfmac-Avoid-adding-two-sets-of-HE-Capab-and-Oper-.patch
1. non-upstream-sdio-t-put-tuning.patch[x]
1. brcmfmac-get-chip-info-from-SDIOD-if-chip-common-spa.patch
1. non-upstream-vendor-cmd-addition-for-wpa_cli-wnm_max.patch[x]
1. Resolve-skb-alloc-failures-in-FMAC.patch
1. non-upstream-sdio-t-put-tuning.patch[x]
1. Fix-a-NULL-pointer-dereference.patch
1. brcmfmac-add-protection-for-PCIe-Read-Write-out-of-b.patch
1. Added-DSCP-to-WMM-UP-mapping.patch
1. brcmfmac-fix-mac-address-is-not-assigned-for-iovar-B.patch
1. non-upstream-fixing-compile-error-on-kernel-5.9-onwa.patch
1. brcmfmac-fix-for-guard-interval-for-iw-set-bitrates.patch
1. brcmfmac-Add-support-for-ethtool-packet-statistics.patch
1. brcmfmac-Add-55500-chip-support.patch
1. brcmfmac-SDIO-Rev31-changes-in-rmmod-sequence.patch
1. brcmfmac-Wait-for-bootloader-ready-before-doing-back.patch
1. brcmfmac-prevent-double-free-on-hardware-reset.patch
1. brcmfmac-Update-D2H-Validation-Done-Timeout.patch
1. brcmfmac-SR-in-not-getting-enabled-in-H1.patch
1. brcmfmac-set-up-wrong-status-when-use-internal-suppl.patch
1. brcmfmac-TWT-Add-a-new-feature-source-header-file-fo.patch
1. brcmfmac-TWT-Add-support-to-handle-the-async-TWT-eve.patch
1. brcmfmac-TWT-create-a-debugfs-file-to-expose-the-TWT.patch
1. nl80211-Update-IFX-NL80211-Vendor-source-and-header-.patch
1. brcmfmac-add-protection-for-firmware-doesn-t-have-ex.patch



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
1. Fix-dpp-config-parameter-setting.patch
1. DPP-Resolving-failure-of-dpp-configurator-exchange-f.patch
1. Enabling-SUITEB192-and-SUITEB-compile-options.patch
1. DPP-Enabling-CLI_EDIT-option-for-enrollee-plus-respo.patch
1. P2P-Fixes-Scan-trigger-failed-once-GC-invited-by-GO.patch
1. non-upstream-SAE-disconnect-after-PMKSA-cache-expire.patch[x]
1. Add-support-for-beacon-loss-roaming.patch
1. wpa_supplicant-Set-PMKSA-to-driver-while-key-mgmt-is.patch
1. nl80211-Set-NL80211_SCAN_FLAG_COLOCATED_6GHZ-in-scan.patch
1. scan-Add-option-to-disable-6-GHz-collocated-scanning.patch
1. Enabling-OWE-in-wpa_supplicant.patch
1. Add-link-loss-timer-on-beacon-loss.patch
1. FT-Sync-nl80211-ext-feature-index.patch
1. nl80211-Introduce-a-vendor-header-for-vendor-NL-ifac.patch
1. add-support-to-offload-TWT-setup-request-handling-to.patch
1. add-support-to-offload-TWT-Teardown-request-handling.patch
1. Add-support-to-configure-TWT-of-a-session-using-offs.patch
1. Establish-a-Default-TWT-session-in-the-STA-after-ass.patch
1. validate-the-TWT-parameters-exponent-and-mantissa-pa.patch
1. Fix-for-station-sending-open-auth-instead-of-SAE-aut.patch
1. Fix-ROAMOFFLOAD-raises-portValid-too-early.patch
1. Fix-associating-failed-when-PMK-lifetime-is-set-to-1.patch
1. non-upstream-p2p_add_group-command-unification.patch[x]
1. non-upstream-MBO-wpa_cli-mbo-command-by-IFX-vendorID.patch[x]
1. EAP-TLS-Allow-TLSv1.3-support-to-be-enabled-with-bui.patch
1. Enabling-TLS-v1.3-by-default.patch
1. Disable-4-way-handshake-offload-for-DPP.patch
1. non-upstream-WNM-wpa_cli-wnm_maxilde-command-by-IFX-.patch[x]
1. brcmfmac-sync-content-of-nl80211_copy.h-for-BSS_COLO.patch
1. WPA3-SAE-enable-nl_connect-socket-while-WPA_DRIVER_F.patch


Note: [*] is the upstream tag containing the patch
      [x] means no plan to upstream

