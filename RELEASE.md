Infineon WiFi Linux WiFi Solution - Release Notes
=================================================

Release Version
---------------
v6.1.97-2024_1115


Release Date
------------
2024-11-21


WiFi Driver Change List
-----------------------
1. non-upstream-add-sg-parameters-dts-parsing.patch [x]
1. brcmfmac-support-AP-isolation.patch
1. non-upstream-make-firmware-eap_restrict-a-module-par.patch [x]
1. non-upstream-support-wake-on-ping-packet.patch[x]
1. non-upstream-remove-WOWL-configuration-in-disconnect.patch [x]
1. non-upstream-make-setting-SDIO-workqueue-WQ_HIGHPRI-.patch [x]
1. non-upstream-avoid-network-disconnection-during-susp.patch [x]
1. non-upstream-Changes-to-improve-USB-Tx-throughput.patch [x]
1. brcmfmac-introduce-module-parameter-to-configure-def.patch
1. non-upstream-configure-wowl-parameters-in-suspend-fu.patch [x]
1. non-upstream-disable-command-decode-in-sdio_aos-for-.patch [x]
1. brcmfmac-increase-default-max-WOWL-patterns-to-16.patch
1. non-upstream-Enable-Process-and-forward-PHY_TEMP-eve.patch [x]
1. non-upstream-fix-continuous-802.1x-tx-pending-timeou.patch [x]
1. non-upstream-add-sleep-in-bus-suspend-and-cfg80211-r.patch [x]
1. brcmfmac-add-CYW43570-PCIE-device.patch
1. non-upstream-fix-scheduling-while-atomic-issue-when-.patch [x]
1. brcmfmac-Support-89459-pcie.patch
1. brcmfmac-Support-multiple-AP-interfaces-and-fix-STA-.patch
1. non-upstream-Support-custom-PCIE-BAR-window-size.patch [x]
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
1. non-upstream-Fix-no-P2P-IE-in-probe-requests-issue.patch [x]
1. brcmfmac-add-54591-PCIE-device.patch
1. non-upstream-support-DS1-exit-firmware-re-download.patch [x]
1. non-upstream-fix-43012-insmod-after-rmmod-in-DS1-fai.patch [x]
1. non-upstream-fix-43012-driver-reload-failure-after-D.patch [x]
1. brcmfmac-reset-PMU-backplane-all-cores-in-CYW4373-du.patch
1. non-upstream-calling-skb_orphan-before-sending-skb-t.patch [x]
1. non-upstream-workaround-for-4373-USB-WMM-5.2.27-test.patch [x]
1. non-upstream-disable-command-decode-in-sdio_aos-for-.patch [x]
1. non-upstream-disable-command-decode-in-sdio_aos-for-.patch [x]
1. non-upstream-disable-command-decode-in-sdio_aos-for-.patch [x]
1. brcmfmac-support-the-forwarding-packet.patch
1. brcmfmac-add-a-variable-for-packet-forwarding-condit.patch
1. brcmfmac-don-t-allow-arp-nd-offload-to-be-enabled-if.patch
1. non-upstream-ignore-FW-BADARG-error-when-removing-no.patch [x]
1. brcmfmac-Support-DPP-feature.patch
1. brcmfmac-move-firmware-path-to-cypress-folder.patch
1. brcmfmac-add-support-for-sof-time-stammping-for-tx-p.patch
1. non-upstream-free-eventmask_msg-after-updating-event.patch [x]
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
1. non-upstream-Revert-brcm80211-select-WANT_DEV_COREDU.patch [x]
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
1. revert-non-upstream-make-setting-SDIO-workqueue-WQ_H.patch [x]
1. brcmfmac-Set-SDIO-workqueue-as-WQ_HIGHPRI.patch[v5.15-rc1]
1. brcmfmac-revise-SoftAP-channel-setting.patch
1. brcmfmac-Optimize-CYW4373-SDIO-current.patch [v5.13-rc7]
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
1. brcmfmac-Disable-out-of-band-device-wake-based-DeepS.patch
1. brcmfmac-Improve-the-delay-during-scan.patch
1. brcmfmac-skip-6G-oob-scan-report.patch
1. revert-brcmfmac-Improve-the-delay-during-scan.patch
1. brcmfmac-Improve-the-delay-during-scan.patch
1. brcmfmac-add-FW-AP-selection-mod-param.patch
1. brcmfmac-Changing-info-messages-under-debug-BRCMF_IN.patch
1. revert-brcmfmac-Set-timeout-value-when-configuring-p.patch
1. brcmfmac-fixes-scan-invalid-channel-when-enable-host.patch
1. brcmfmac-do-not-disable-controller-in-apmode-stop.patch
1. brcmfmac-support-11ax-and-6G-band.patch
1. brcmfmac-fixes-invalid-channel-still-in-the-channel-.patch
1. non-upstream-Fix-lspci-not-enumerating-wifi-device-a.patch [x]
1. brcmfmac-support-signal-monitor-feature-for-wpa_supp.patch
1. brcmfmac-add-support-for-CYW55560-SDIO-chipset.patch
1. brcmfmac-Modified-Kconfig-help-format.patch
1. brcmfmac-Fix-incorrect-WARN_ON-causing-set_pmk-failu.patch
1. brcmfmac-report-cqm-rssi-event-based-on-rssi-change-.patch
1. brcmfmac-add-WPA3_AUTH_1X_SUITE_B_SHA384-related-sup.patch
1. non-upstream-Handle-the-6G-case-in-the-bw_cap-chansp.patch [x]
1. net-brcm80211-Fix-race-on-timer_add-in-wifi-driver.patch
1. brcmfmac-Remove-WARN_ON-while-no-6g-bw_cap.patch
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
1. brcmfmac-add-FT-PSK-roaming-offload-support.patch
1. brcmfmac-enable-6G-split-scanning-feature.patch
1. brcmfmac-set-HE-6GHz-capabilities-for-bring-up-SAP.patch
1. brcmfmac-add-interface-to-set-bsscolor-for-bring-up-.patch
1. non-upstream-add-IFX-vendor-OUI-file.patch [x]
1. non-upstream-adding-vendor_cmds-are-with-IFX_OUI.patch [x]
1. brcmfmac-introduce-a-module-parameter-to-disable-the.patch
1. brcmfmac-skip-6GHz-capab-registration-with-cfg80211-.patch
1. brcmfmac-set-HE-rate-only-if-HE-MCS-set-and-valid.patch
1. brcmfmac-remove-workaround-cause-the-FW-can-support-.patch
1. brcmfmac-ext_owe-supporting.patch
1. brcmfmac-Avoid-adding-two-sets-of-HE-Capab-and-Oper-.patch
1. non-upstream-Add-IFX-TWT-Offload-support.patch [x]
1. non-upstream-vendor-cmd-addition-for-wl-he-bsscolor.patch [x]
1. non-upstream-vendor-cmd-addition-for-wl-he-muedca_op.patch [x]
1. non-upstream-vendor-cmd-addition-for-wl-amsdu.patch [x]
1. non-upstream-vendor-cmd-addition-for-wl-ldpc_cap.patch [x]
1. non-upstream-Refine-TWT-code-for-checkpatch.patch [x]
1. cfg80211-fix-u8-overflow-in-cfg80211_update_notliste.patch
1. cfg80211-mac80211-reject-bad-MBSSID-elements.patch
1. cfg80211-fix-BSS-refcounting-bugs.patch
1. cfg80211-avoid-nontransmitted-BSS-list-corruption.patch
1. brcmfmac-Fix-potential-buffer-overflow-in-brcmf_fweh.patch
1. non-upstream-vendor-cmd-addition-for-wl-oce-enable.patch [x]
1. non-upstream-vendor-cmd-addition-for-wl-randmac.patch [x]
1. brcmfmac-compile-warning-fix.patch
1. brcmfmac-Fix-invalid-RAM-address-warning-for-PCIE-pl.patch
1. brcmfmac-Fix-dpp-very-low-tput-issue.patch
1. non-upstream-keep-IFX-license-header-for-non-upstrea.patch [x]
1. non-upstream-internal-sup-uses-join-command-to-send-.patch [x]
1. non-upstream-Supporting-IFX_vendor-commands-of-MBO.patch [x]
1. brcmfmac-Set-corresponding-cqm-event-handlers-based-.patch
1. non-upstream-isolate-power_save-off-and-mpc-0.patch [x]
1. brcmfmac-Add-NULL-checks-to-fix-multiple-NULL-pointe.patch
1. brcmfmac-fix-compiler-error.patch
1. non-upstream-supporting-giartrx-IFX-vendor-ID.patch [x]
1. wireless-brcmfmac-Use-netif_rx.patch
1. brcmfmac-replace-SDIO-function-number-with-definitio.patch
1. brcmfmac-move-SDIO-function-number-definition-to-sdi.patch
1. brcmfmac-Restore-channel-info.patch
1. brcmfmac-Avoid-adding-two-sets-of-HE-Capab-and-Oper-.patch
1. non-upstream-sdio-t-put-tuning.patch [x]
1. brcmfmac-get-chip-info-from-SDIOD-if-chip-common-spa.patch
1. non-upstream-vendor-cmd-addition-for-wpa_cli-wnm_max.patch [x]
1. brcm80211-Resolve-skb-alloc-failures-in-FMAC.patch
1. non-upstream-sdio-t-put-tuning.patch [x]
1. brcmfmac-Fix-a-NULL-pointer-dereference.patch
1. brcmfmac-add-protection-for-PCIe-Read-Write-out-of-b.patch
1. brcmfmac-Added-DSCP-to-WMM-UP-mapping.patch
1. brcmfmac-fix-mac-address-is-not-assigned-for-iovar-B.patch
1. non-upstream-fixing-compile-error-on-kernel-5.9-onwa.patch [x]
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
1. brcmfmac-Update-IFX-NL80211-Vendor-source-and-header.patch
1. brcmfmac-add-protection-for-firmware-doesn-t-have-ex.patch
1. brcmfmac-fix-compiler-error-when-using-vanilla-kerne.patch
1. non-upstream-to-prevent-rx-interrupt-comes-too-early.patch [x]
1. brcmfmac-Send-CSA-to-supplicant-on-channel-change.patch
1. brcmfmac-extowe_ap-mode-supporting.patch
1. brcmfmac-resort-data-structure-of-owe_info.patch
1. brcmfmac-TWT-fixed-feature-check.patch
1. brcmfmac-External-roam-time-enhancements.patch
1. brcmfmac-fixing-compile-warning.patch
1. brcmfmac-TWT-Handle-unsolicited-setup-accept-and-sol.patch
1. brcmfmac-TWT-use-Dialog-Token-as-unique-identifier-t.patch
1. brcmfmac-TWT-Update-teardown-state-while-handling-Te.patch
1. brcmfmac-TWT-Handle-timeout-of-Setup-and-Teardown-ev.patch
1. brcmfmac-TWT-rephrase-print-statements-with-addition.patch
1. brcmfmac-offload-add-configuration-infrastructure-su.patch
1. brcmfmac-offload-clean-add-all-entries-in-ICMP-ND-fo.patch
1. brcmfmac-avoid-unnecessary-WL-Down-UP-while-setting-.patch
1. non-upstream-update-sae_password-for-potential-roami.patch [x]
1. brcmfmac-offload-update-the-brcmf_configure_arp_nd_o.patch
1. brcmfmac-Fix-DUT-is-vulnerable-to-key-reinstallation.patch
1. brcmfmac-Support-for-WPA3-FT-SAE-roam-offload.patch
1. brcmfmac-TWT-cleanup-stale-session-entries-after-rec.patch
1. brcmfmac-Fix-kernel-crash-while-updating-tx-statisti.patch
1. brcmfmac-avoid-memory-use-after-free-in-the-escan-ti.patch
1. non-upstream-add-command-to-show-module-parameter.patch [x]
1. brcmfmac-support-43022-Cypress-Vendor-and-Device-ID.patch
1. brcmfmac-Chip-id-changes-for-43022.patch
1. brcmfmac-Move-shared-console-address-location.patch
1. brcmfmac-enable-support-for-split-scan-to-optimize-t.patch
1. brcmfmac-kso-sequence-sleep-delay-enhancement.patch
1. brcmfmac-Avoid-realloc-resources-on-DS1-exit-in-fw-d.patch
1. brcmfmac-PCIe-RX-throughput-improvement.patch
1. brcmfmac-Increase-the-kso_sequence-bail-out-timer.patch
1. non-upstream-btsdio-add-ifx-bt-shared-sdio-file.patch [x]
1. non-upstream-fixing-the-last-hostapd_cli-disabled-in.patch [x]
1. brcmfmac-fixing-mbss-iovar-setting-for-multiple-BSS-.patch
1. non-upstream-new-value-for-roamoff-for-report-differ.patch [x]
1. brcmfmac-Support-idleclock-feature-for-43012-43022-c.patch
1. non-upstream-btsdio-enable-export-api-to-r-w-F3-one-.patch [x]
1. non-upstream-btsdio-enable-export-api-for-F3-receivi.patch [x]
1. non-upstream-btsdio-attach-init-deinit.patch [x]
1. non-upstream-btsdio-check-rx-interrupt-before-get-rx.patch [x]
1. non-upstream-btsdio-enable-export-api-for-F3-transfe.patch [x]
1. non-upstream-btsdio-support-export-api-to-set-block-.patch [x]
1. non-upstream-btsdio-claim-function-3-in-band-irq.patch [x]
1. non-upstream-btsdio-reset-bt-in-remove-flow-when-bt-.patch [x]
1. non-upstream-btsdio-add-command-to-show-bt-shared-sd.patch [x]
1. brcmfmac-DS2-udp-tx-crash-fix.patch
1. brcmfmac-OOB-irq-support-on-43022-DS2.patch
1. brcmfmac-pcie-INTMASK-address-is-another-address-fro.patch
1. brcmfmac-fix-wrong-NULL-check-in-msgbuf_rx.patch
1. non-upstream-btsdio-support-43012-43022.patch [x]
1. brcmfmac-Bootloader-host-handshake-implementation.patch
1. brcmfmac-Avoid-socram-access-in-secure-mode.patch
1. brcmfmac-Support-secure-and-non-secure-code-flow.patch
1. brcmfmac-Bring-up-DS1-for-43022-DM-chip.patch
1. brcmfmac-do-not-access-D11-SHM-and-PMU-registers-for.patch
1. brcmfmac-fixes-for-FW-redownload-after-DS1-2-exit.patch
1. brcmfmac-New-rmmod-seq-for-43022-secure-mode.patch
1. brcmfmac-Change-bus-width-independent-of-sdio_idlecl.patch
1. brcmfmac-Remove-chip-id-check-from-kso-0-bail-out-lo.patch
1. brcmfmac-fix-wrong-FW-extension-problem-for-secure-c.patch
1. brcmfmac-separate-43022-sdio-download-function-from-.patch
1. nl80211-Sync-with-wireless-next-2023-10-26-include-u.patch
1. non-upstream-nl80211-bring-back-IFX-nl80211.h-change.patch [x]
1. brcmfmac-set-authorized-flag-in-CONNECT-event-for-al.patch
1. nl80211-Add-support-to-set-AP-settings-flags-with-si.patch
1. brcmfmac-fix-compiler-warning-on-kernel-v4.12.patch
1. brcmfmac-fix-warning-error-when-enable-PCIE_BARWIN_S.patch
1. brcmfmac-Add-new-survey-dump-feature.patch
1. brcmfmac-update-local-pmklist-while-process-auth_sta.patch
1. brcmfmac-fix-mmc-tuning-failed.patch
1. non-upstream-check-and-set-default-fcmode-of-the-chi.patch [x]
1. brcmfmac-add-protection-for-not-calling-cfg80211_ch_.patch
1. brcmfmac-get-wdev-from-the-event-reporting-ifp.patch
1. non-upstream-vendor-cmd-addition-for-replay-counter.patch [x]
1. non-upstream-btsdio-forward-device-id-to-bt-driver.patch [x]
1. brcmfmac-skip-bss-update-when-NULL-mac-received-for-.patch
1. brcmfmac-Adding-set-and-remove-F3-device.patch
1. brcmfmac-Fix-KERNEL-WARNING-due-to-invalid-chspec.patch
1. brcmfmac-Check-bus-sleep-state-in-isr.patch
1. brcmfmac-resetting-sb-window-address.patch
1. brcmfmac-SWLINUX-4018-Resolves-compilation-err.patch
1. non-upstream-Increase-delay-in-kso-sequence.patch [x]
1. brcmfmac-OOB-crash-Fix-on-iMX-platform.patch
1. non-upstream-fix-func3-compile-error.patch [x]
1. non-upstream-btsdio-add-DM-device-ID.patch [x]
1. wifi-brcmfmac-Fix-use-after-free-bug-in-brcmf_cfg802.patch
1. non-upstream-provide-the-iw-command-to-set-get-value.patch [x]
1. non-upstream-vendor-cmds-string-infrastructure-with-.patch [x]
1. non-upstream-mkeep_alive-and-tko-string-vendor-cmds.patch [x]
1. brcmfmac-Add-module_param-to-set-idle_time_zero.patch
1. brcmfmac-Fix-KERNEL-WARNING-on-customer-clm_blob.patch
1. brcmfmac-FW-Header-Changes-to-TRXv5-for-H1-CP-Combo-.patch
1. brcmfmac-Update-D2H-Validation-Done-Timeout.patch
1. brcmfmac-Hatched-1-DDR50-CRC-error-KSO-Change.patch
1. brcmfmac-add-new-iovar-format-for-action-frame.patch
1. non-upstream-reserve-tx-credit-for-txctl-frame.patch [x]
1. brcmfmac-refine-netif_rx-for-different-kernel-versio.patch
1. brcmfmac-fix-LINUX_VERSION_CODE-warning.patch
1. non-upstream-PFN-offload-implementation.patch [x]
1. non-upstream-PFN-Add-support-for-remove_network-all-.patch [x]
1. non-upstream-Add-support-for-pfn-autoswitch.patch [x]
1. non-upstream-PNO-Fix-for-fw-trap-when-we-add-more-th.patch [x]
1. non-upstream-PNO-PNO-Code-Cleanup.patch [x]
1. brcmfmac-align-brcmf_wlc_version_le-with-official-co.patch
1. brcmfmac-Add-FW-supplicant-profile-check-for-the-roa.patch
1. brcmfmac-Fix-for-wifi-generation-info-missing-in-wpa.patch
1. brcmfmac-WPA3-192bit-fixes.patch
1. brcmfmac-fix-CERT-11N-Traffic-Differentiation-in-Sin.patch
1. brcmfmac-Unexpected-failure-errors-are-seen-during-d.patch
1. brcmfmac-P2P-Call-trace-Fix-in-P2P-GO.patch
1. brcmfmac-Crash-in-OOB-Mode-while-using-sdio_in_isr.patch
1. brcmfmac-Fix-SDIO-bus-access-in-SDIO-sleep-state.patch
1. non-upstream-IW-vendor-cmds-for-NAT-keep-alive-tko-p.patch [x]
1. brcmfmac-WPA3-Cert-19.6.1-Disable-idsup-for-192-bit-.patch
1. brcmfmac-Enable-Internal-supplicant-for-OWE-AKM.patch
1. brcmfmac-Add-Support-for-OWE-offload.patch
1. brcmfmac-Add-CLM-support-to-USB-interface.patch
1. brcmfmac-FT-Cert-FT-and-FT-roam-support-in-driver.patch
1. brcmfmac-Fix-wpa_auth-setting-for-wpa3-1x-sha256.patch
1. non-upstream-fix-kernel-warning-for-Suite-B-192-call.patch [x]
1. non-upstream-rewrite-feat_flag-to-preven-the-use-of-.patch [x]
1. brcmfmac-fix-error-msg-while-deleting-virtual-interf.patch
1. brcmfmac-Send-sup_wpa-iovar-only-to-firmware-which-h.patch
1. brcmfmac-fix-reload-FMAC-timeout-error-while-using-b.patch
1. brcmfmac-CERT-OCE-Fix-EAPOL-Timeout-issue.patch
1. brcmfmac-enable-remote-wakeup-before-USB-suspend-if-.patch
1. brcmfmac-Fix-data-traffic-halted-after-reconnect.patch
1. brcmfmac-fix-get_assoc_ies-misused-endian-untranslat.patch

       [-] means under upstream review
       [x] means no plan to upstream
   
   
Ho stap Change List
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
1. non-upstream-defconfig_base-Add-Infineon-default-con.patch [x]
1. CVE_2019_9501-Fix-to-check-Invalid-GTK-IE-length-in-.patch
1. Add-CONFIG_WPA3_SAE_AUTH_EARLY_SET-flags-and-codes.patch
1. SAE-Set-the-right-WPA-Versions-for-FT-SAE-key-manage.patch
1. wpa_supplicant-Support-WPA_KEY_MGMT_FT-for-eapol-off.patch
1. wpa_supplicant-suppress-deauth-for-PMKSA-caching-dis.patch
1. Fix-for-PMK-expiration-issue-through-supplicant.patch
1. SAE-Drop-PMKSA-cache-after-receiving-specific-deauth.patch
1. Avoid-deauthenticating-STA-if-the-reason-for-freeing.patch
1. wpa_supplicant-support-bgscan.patch
1. non-upstream-wl-cmd-create-interface-to-support-driv.patch [x]
1. non-upstream-wl-cmd-create-wl_do_cmd-as-an-entry-doi.patch [x]
1. non-upstream-wl-cmd-create-ops-table-to-do-wl-comman.patch [x]
1. non-upstream-wl-cmd-add-more-compile-flag.patch [x]
1. Fix-dpp-config-parameter-setting.patch
1. DPP-Resolving-failure-of-dpp-configurator-exchange-f.patch
1. Enabling-SUITEB192-and-SUITEB-compile-options.patch
1. DPP-Enabling-CLI_EDIT-option-for-enrollee-plus-respo.patch
1. P2P-Fixes-Scan-trigger-failed-once-GC-invited-by-GO.patch
1. non-upstream-SAE-disconnect-after-PMKSA-cache-expire.patch [x]
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
1. Fix-associating-failed-when-PMK-lifetime-is-set-to-1.patch
1. non-upstream-p2p_add_group-command-unification.patch [x]
1. non-upstream-MBO-wpa_cli-mbo-command-by-IFX-vendorID.patch [x]
1. EAP-TLS-Allow-TLSv1.3-support-to-be-enabled-with-bui.patch
1. Enabling-TLS-v1.3-by-default.patch
1. Disable-4-way-handshake-offload-for-DPP.patch
1. non-upstream-WNM-wpa_cli-wnm_maxilde-command-by-IFX-.patch [x]
1. brcmfmac-sync-content-of-nl80211_copy.h-for-BSS_COLO.patch
1. WPA3-SAE-enable-nl_connect-socket-while-WPA_DRIVER_F.patch
1. OWE-AP-enable-OWE-compile-option-for-hostapd-executi.patch
1. DPP2.0-support-DPP2.0-and-add-pfs-init-flow-on-EVENT.patch
1. non-upstream-Prevent-invalid-akm-key-mgmt-when-MFP-r.patch
1. Reset-authentication-and-encryption-parameters-while.patch
1. brcmfmac-add-a-configurable-link_loss-parameter-for-.patch
1. DPP-fix-for-akm-sae-and-add-dpp_reconfig-command-to-.patch
1. DPP-enable-CONFIG_DPP3-flag.patch
1. MLD-STA-protect-connect-CMD-attribute-MLO-support-un.patch
1. nl8211-Set-NL80211_WPA_VERSION_2-vs-_3-based-on-AKM-.patch
1. bgscan-wpa_supplicant-segment-fault-when-do-simple-b.patch
1. hostapd-calling-driver-to-remove-pmkid-while-pmk-cac.patch
1. non-upstream-Check-supported-Replay-Counters-through.patch [x]
1. non-upstream-WNM-fix-wnm_maxilde-coredump-and-get-em.patch [x]
1. non-upstream-temporarily-disable-the-compiler-optimi.patch
1. enable-ACS-compile-option-by-default.patch
1. non-upstream-Added-support-for-PFN-offload.patch              [x] 
1. non-upstream-Fix-SSID-corruption-of-PFN-config-to-dr.patch    [x]
1. non-upstream-Fix-pfn_status-and-SSID-corruption-of-P.patch    [x]
1. non-upstream-PFN-Add-support-for-remove_network-all-.patch    [x]
1. non-upstream-Add-support-for-pfn-autoswitch.patch             [x]
1. non-upstream-Fix-for-pno-scan-starts-after-30sec-of-.patch    [x]
1. non-upstream-PNO-cleanup.patch                                [x]
1. Suite-B-Update-Proper-PMK-len-for-192bit-Suite-B-AKM.patch
1. STA-connection-status-update-with-11AX-info.patch
1. DUT-fails-to-connect-in-WPA2-when-AP-is-configured-i.patch
1. WPA3-CERT-WPA3-5.8.3-Roam-to-WPA3-transition-mode-Fa.patch
1. OWE-Enable-4way-handshake-offload-for-OWE.patch
1. non-upstream-Disable-4way-offload-for-P2P-GO.patch            [x]
1. Block-hostapd-config-with-mfpr-and-PSK-key_mgmt.patch
1. SAE-Reject-invalid-Rejected-Groups-element-in-the-pa.patch
1. SAE-Check-for-invalid-Rejected-Groups-element-length.patch
1. SAE-Check-for-invalid-Rejected-Groups-element-length.patch
1. Fix-EAPOL-retry-issue-while-roaming-with-BTM.patch
1. non-upstream-Fix-802.1x-Preauth-roaming-doesn-t-upda.patch    [x]
1. PNO-Check-PFN_ENABLE-configuration.patch
1. non-upstream-Update-configuration.patch                       [x]
1. TWT-allow-TWT-offload-even-though-CONFIG_TESTING_OPT.patch
1. non-upstream-Enable-Testing-configuration-for-DPP-ce.patch    [x]

       [*] is the upstream tag containing the patch
       [x] means no plan to upstream