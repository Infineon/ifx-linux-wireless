Infineon WiFi Linux WiFi Solution - Release Notes
=================================================

Release Version
---------------
v6.1.145-2026_0108

Release Date
------------
2026-01-08

Wi-Fi Driver Change List
----------------------
 * 0001-non-upstream-add-sg-parameters-dts-parsing.patch [x]
 * 0002-brcmfmac-support-AP-isolation.patch
 * 0003-non-upstream-make-firmware-eap_restrict-a-module-par.patch [x]
 * 0004-non-upstream-support-wake-on-ping-packet.patch [x]
 * 0005-non-upstream-remove-WOWL-configuration-in-disconnect.patch [x]
 * 0006-non-upstream-avoid-network-disconnection-during-susp.patch [x]
 * 0007-non-upstream-Changes-to-improve-USB-Tx-throughput.patch [x]
 * 0008-brcmfmac-introduce-module-parameter-to-configure-def.patch
 * 0009-non-upstream-configure-wowl-parameters-in-suspend-fu.patch [x]
 * 0010-non-upstream-disable-command-decode-in-sdio_aos-for-.patch [x]
 * 0011-non-upstream-Enable-Process-and-forward-PHY_TEMP-eve.patch [x]
 * 0012-non-upstream-add-sleep-in-bus-suspend-and-cfg80211-r.patch [x]
 * 0013-brcmfmac-Support-multiple-AP-interfaces-and-fix-STA-.patch
 * 0014-non-upstream-Support-custom-PCIE-BAR-window-size.patch [x]
 * 0015-brcmfmac-support-for-virtual-interface-creation-from.patch
 * 0016-brcmfmac-set-net-carrier-on-via-test-tool-for-AP-mod.patch
 * 0017-nl80211-add-authorized-flag-back-to-ROAM-event.patch
 * 0018-brcmfmac-set-authorized-flag-in-ROAM-event-for-offlo.patch
 * 0019-brcmfmac-set-authorized-flag-in-ROAM-event-for-PMK-c.patch
 * 0020-nl80211-add-authorized-flag-to-CONNECT-event.patch
 * 0021-brcmfmac-set-authorized-flag-in-CONNECT-event-for-PM.patch
 * 0022-brcmfmac-add-support-for-Opportunistic-Key-Caching.patch
 * 0023-brcmfmac-To-support-printing-USB-console-messages.patch
 * 0024-non-upstream-Fix-no-P2P-IE-in-probe-requests-issue.patch [x]
 * 0025-brcmfmac-add-54591-PCIE-device.patch
 * 0026-non-upstream-support-DS1-exit-firmware-re-download.patch [x]
 * 0027-non-upstream-fix-43012-insmod-after-rmmod-in-DS1-fai.patch [x]
 * 0028-non-upstream-fix-43012-driver-reload-failure-after-D.patch [x]
 * 0029-brcmfmac-reset-PMU-backplane-all-cores-in-CYW4373-du.patch
 * 0030-non-upstream-calling-skb_orphan-before-sending-skb-t.patch [x]
 * 0031-non-upstream-workaround-for-4373-USB-WMM-5.2.27-test.patch [x]
 * 0032-non-upstream-disable-command-decode-in-sdio_aos-for-.patch [x]
 * 0033-non-upstream-disable-command-decode-in-sdio_aos-for-.patch [x]
 * 0034-non-upstream-disable-command-decode-in-sdio_aos-for-.patch [x]
 * 0035-brcmfmac-support-the-forwarding-packet.patch
 * 0036-brcmfmac-add-a-variable-for-packet-forwarding-condit.patch
 * 0037-brcmfmac-don-t-allow-arp-nd-offload-to-be-enabled-if.patch
 * 0038-non-upstream-ignore-FW-BADARG-error-when-removing-no.patch [x]
 * 0039-brcmfmac-Support-DPP-feature.patch
 * 0040-brcmfmac-move-firmware-path-to-cypress-folder.patch
 * 0041-brcmfmac-add-support-for-sof-time-stammping-for-tx-p.patch
 * 0042-non-upstream-free-eventmask_msg-after-updating-event.patch [x]
 * 0043-brcmfmac-add-a-timer-to-read-console-periodically-in.patch
 * 0044-non-upstream-return-error-when-getting-invalid-max_f.patch [x]
 * 0045-brcmfmac-dump-dongle-memory-when-attaching-failed.patch
 * 0046-brcmfmac-update-address-mode-via-test-tool-for-AP-mo.patch
 * 0047-brcmfmac-load-54591-firmware-for-chip-ID-0x4355.patch
 * 0048-brcmfmac-Fix-interoperating-DPP-and-other-encryption.patch
 * 0049-brcmfmac-fix-SDIO-bus-errors-during-high-temp-tests.patch
 * 0050-brcmfmac-Add-dump_survey-cfg80211-ops-for-HostApd-Au.patch
 * 0051-revert-brcmfmac-set-state-of-hanger-slot-to-FREE-whe.patch
 * 0052-brcmfmac-correctly-remove-all-p2p-vif.patch
 * 0053-brcmfmac-fix-firmware-trap-while-dumping-obss-stats.patch
 * 0054-brcmfmac-add-creating-station-interface-support.patch
 * 0055-brcmfmac-support-station-interface-creation-version-.patch
 * 0056-brcmfmac-To-fix-crash-when-platform-does-not-contain.patch
 * 0057-brcmfmac-fix-CERT-P2P-5.1.10-failure.patch
 * 0058-brcmfmac-Fix-for-when-connect-request-is-not-success.patch
 * 0059-brcmfmac-Avoiding-Connection-delay.patch
 * 0060-non-upstream-Revert-brcm80211-select-WANT_DEV_COREDU.patch [x]
 * 0061-brcmfmac-Fix-connecting-enterprise-AP-failure.patch
 * 0062-brcmfmac-Fix-for-skbuf-allocation-failure-in-memory-.patch
 * 0063-brcmfmac-Update-SSID-of-hidden-AP-while-informing-it.patch
 * 0064-brcmfmac-Fix-PCIE-suspend-resume-issue.patch
 * 0065-brcmfmac-disable-mpc-when-power_save-is-disabled.patch
 * 0066-brcmfmac-Fix-authentication-latency-caused-by-OBSS-s.patch
 * 0067-brcmfmac-support-external-SAE-authentication-in-stat.patch
 * 0068-brcmfmac-fix-sdio-watchdog-timer-start-fail-issue.patch
 * 0069-brcmfmac-Frameburst-vendor-command-addition.patch
 * 0070-brcmfmac-add-support-for-CYW43439-SDIO-chipset.patch
 * 0071-brcmfmac-add-BT-shared-SDIO-support.patch
 * 0072-brcmfmac-add-CYW43439-SR-related-changes.patch
 * 0073-brcmfmac-add-support-for-CYW43439-with-blank-OTP.patch
 * 0074-brcmfmac-support-43439-Cypress-Vendor-and-Device-ID.patch
 * 0075-brcmfmac-fix-P2P-device-discovery-failure.patch
 * 0076-brcmfmac-Add-SDIO-vendor-device-id-for-CYW89459-in-h.patch
 * 0077-brcmfmac-Add-CYW89459-HW-ID-and-modify-sdio-F2-block.patch
 * 0078-brcmfmac-Fix-AP-interface-delete-issue.patch
 * 0079-brcmfmac-Revise-channel-info-for-WPA3-external-SAE.patch
 * 0080-brcmfmac-Fix-structure-size-for-WPA3-external-SAE.patch
 * 0081-brcmfmac-support-54590-54594-PCIe-device-id.patch
 * 0082-brcmfmac-revise-SoftAP-channel-setting.patch
 * 0083-brcmfmac-Optimize-CYW4373-SDIO-current.patch
 * 0084-brcmfmac-use-request_firmware_direct-for-loading-boa.patch
 * 0085-brcmfmac-enable-pmk-catching-for-ext-sae-wpa3-ap.patch
 * 0086-brcmfmac-fixes-CYW4373-SDIO-CMD53-error.patch
 * 0087-brcmfmac-add-support-for-TRX-firmware-download.patch
 * 0088-brcmfmac-add-Cypress-PCIe-vendor-ID.patch
 * 0089-brcmfmac-add-support-for-CYW55560-PCIe-chipset.patch
 * 0090-brcmfmac-add-bootloader-console-buffer-support-for-P.patch
 * 0091-brcmfmac-support-4373-pcie.patch
 * 0092-brcmfmac-extsae-supports-SAE-OKC-roam.patch
 * 0093-nl80211-add-roaming-offload-support.patch
 * 0094-brcm80211-add-FT-11r-OKC-roaming-offload-support.patch
 * 0095-brcmfmac-support-extsae-with-psk-1x-offloading.patch
 * 0096-brcmfmac-Disable-out-of-band-device-wake-based-DeepS.patch
 * 0097-brcmfmac-skip-6G-oob-scan-report.patch
 * 0098-brcmfmac-Improve-the-delay-during-scan.patch
 * 0099-brcmfmac-add-FW-AP-selection-mod-param.patch
 * 0100-brcmfmac-Changing-info-messages-under-debug-BRCMF_IN.patch
 * 0101-revert-brcmfmac-Set-timeout-value-when-configuring-p.patch
 * 0102-brcmfmac-fixes-scan-invalid-channel-when-enable-host.patch
 * 0103-brcmfmac-do-not-disable-controller-in-apmode-stop.patch
 * 0104-brcmfmac-support-11ax-and-6G-band.patch
 * 0105-brcmfmac-fixes-invalid-channel-still-in-the-channel-.patch
 * 0106-non-upstream-Fix-lspci-not-enumerating-wifi-device-a.patch [x]
 * 0107-brcmfmac-support-signal-monitor-feature-for-wpa_supp.patch
 * 0108-brcmfmac-add-support-for-CYW55560-SDIO-chipset.patch
 * 0109-brcmfmac-Fix-incorrect-WARN_ON-causing-set_pmk-failu.patch
 * 0110-brcmfmac-report-cqm-rssi-event-based-on-rssi-change-.patch
 * 0111-brcmfmac-add-WPA3_AUTH_1X_SUITE_B_SHA384-related-sup.patch
 * 0112-non-upstream-Handle-the-6G-case-in-the-bw_cap-chansp.patch [x]
 * 0113-net-brcm80211-Fix-race-on-timer_add-in-wifi-driver.patch
 * 0114-brcmfmac-Remove-WARN_ON-while-no-6g-bw_cap.patch
 * 0115-brcmfmac-update-the-statically-defined-HE-MAC-PHY-Ca.patch
 * 0116-brcmfmac-fix-set_pmk-warning-message.patch
 * 0117-brcmfmac-update-BIP-setting-and-wsec_info-for-GMAC-a.patch
 * 0118-brcmfmac-send-roam-request-when-supplicant-triggers-.patch
 * 0119-brcmfmac-send-BCNLOST_MSG-event-on-beacon-loss-for-s.patch
 * 0120-brcmfmac-trying-to-get-GCMP-cap-before-doing-set-it.patch
 * 0121-brcmfmac-update-firmware-loading-name-for-CY5557x.patch
 * 0122-brcmfmac-use-SR-core-id-to-decide-SR-capability-for-.patch
 * 0123-brcmfmac-SAP-mode-parsing-sae_h2e-setting-from-beaco.patch
 * 0124-brcmfmac-add-sanity-check-for-potential-underflow-an.patch
 * 0125-brcmfmac-Fixing-vulnerability.patch
 * 0126-brcmfmac-Implementing-set_bitrate_mask-cfg80211-ops-.patch
 * 0127-brcmfmac-add-FT-PSK-roaming-offload-support.patch
 * 0128-brcmfmac-enable-6G-split-scanning-feature.patch
 * 0129-brcmfmac-set-HE-6GHz-capabilities-for-bring-up-SAP.patch
 * 0130-brcmfmac-add-interface-to-set-bsscolor-for-bring-up-.patch
 * 0131-non-upstream-add-IFX-vendor-OUI-file.patch [x]
 * 0132-non-upstream-adding-vendor_cmds-are-with-IFX_OUI.patch [x]
 * 0133-brcmfmac-introduce-a-module-parameter-to-disable-the.patch
 * 0134-brcmfmac-skip-6GHz-capab-registration-with-cfg80211-.patch
 * 0135-brcmfmac-set-HE-rate-only-if-HE-MCS-set-and-valid.patch
 * 0136-brcmfmac-remove-workaround-cause-the-FW-can-support-.patch
 * 0137-brcmfmac-ext_owe-supporting.patch
 * 0138-brcmfmac-Avoid-adding-two-sets-of-HE-Capab-and-Oper-.patch
 * 0139-non-upstream-Add-IFX-TWT-Offload-support.patch [x]
 * 0140-non-upstream-vendor-cmd-addition-for-wl-he-bsscolor.patch [x]
 * 0141-non-upstream-vendor-cmd-addition-for-wl-he-muedca_op.patch [x]
 * 0142-non-upstream-vendor-cmd-addition-for-wl-amsdu.patch [x]
 * 0143-non-upstream-vendor-cmd-addition-for-wl-ldpc_cap.patch [x]
 * 0144-non-upstream-Refine-TWT-code-for-checkpatch.patch [x]
 * 0145-non-upstream-vendor-cmd-addition-for-wl-oce-enable.patch [x]
 * 0146-non-upstream-vendor-cmd-addition-for-wl-randmac.patch [x]
 * 0147-brcmfmac-compile-warning-fix.patch
 * 0148-brcmfmac-Fix-invalid-RAM-address-warning-for-PCIE-pl.patch
 * 0149-brcmfmac-Fix-dpp-very-low-tput-issue.patch
 * 0150-non-upstream-keep-IFX-license-header-for-non-upstrea.patch [x]
 * 0151-non-upstream-internal-sup-uses-join-command-to-send-.patch [x]
 * 0152-non-upstream-Supporting-IFX_vendor-commands-of-MBO.patch [x]
 * 0153-brcmfmac-Set-corresponding-cqm-event-handlers-based-.patch
 * 0154-non-upstream-isolate-power_save-off-and-mpc-0.patch [x]
 * 0155-brcmfmac-Add-NULL-checks-to-fix-multiple-NULL-pointe.patch
 * 0156-brcmfmac-fix-compiler-error.patch
 * 0157-non-upstream-supporting-giartrx-IFX-vendor-ID.patch [x]
 * 0158-brcmfmac-replace-SDIO-function-number-with-definitio.patch
 * 0159-brcmfmac-move-SDIO-function-number-definition-to-sdi.patch
 * 0160-brcmfmac-Restore-channel-info.patch
 * 0161-brcmfmac-Avoid-adding-two-sets-of-HE-Capab-and-Oper-.patch
 * 0162-non-upstream-sdio-t-put-tuning.patch [x]
 * 0163-brcmfmac-get-chip-info-from-SDIOD-if-chip-common-spa.patch
 * 0164-non-upstream-vendor-cmd-addition-for-wpa_cli-wnm_max.patch [x]
 * 0165-brcm80211-Resolve-skb-alloc-failures-in-FMAC.patch
 * 0166-non-upstream-sdio-t-put-tuning.patch [x]
 * 0167-brcmfmac-Fix-a-NULL-pointer-dereference.patch
 * 0168-brcmfmac-add-protection-for-PCIe-Read-Write-out-of-b.patch
 * 0169-brcmfmac-Added-DSCP-to-WMM-UP-mapping.patch
 * 0170-brcmfmac-fix-mac-address-is-not-assigned-for-iovar-B.patch
 * 0171-non-upstream-fixing-compile-error-on-kernel-5.9-onwa.patch [x]
 * 0172-brcmfmac-fix-for-guard-interval-for-iw-set-bitrates.patch
 * 0173-brcmfmac-Add-support-for-ethtool-packet-statistics.patch
 * 0174-brcmfmac-Add-55500-chip-support.patch
 * 0175-brcmfmac-SDIO-Rev31-changes-in-rmmod-sequence.patch
 * 0176-brcmfmac-Wait-for-bootloader-ready-before-doing-back.patch
 * 0177-brcmfmac-Update-D2H-Validation-Done-Timeout.patch
 * 0178-brcmfmac-SR-in-not-getting-enabled-in-H1.patch
 * 0179-brcmfmac-set-up-wrong-status-when-use-internal-suppl.patch
 * 0180-brcmfmac-TWT-Add-a-new-feature-source-header-file-fo.patch
 * 0181-brcmfmac-TWT-Add-support-to-handle-the-async-TWT-eve.patch
 * 0182-brcmfmac-TWT-create-a-debugfs-file-to-expose-the-TWT.patch
 * 0183-brcmfmac-Update-IFX-NL80211-Vendor-source-and-header.patch
 * 0184-brcmfmac-add-protection-for-firmware-doesn-t-have-ex.patch
 * 0185-non-upstream-to-prevent-rx-interrupt-comes-too-early.patch [x]
 * 0186-brcmfmac-Send-CSA-to-supplicant-on-channel-change.patch
 * 0187-brcmfmac-extowe_ap-mode-supporting.patch
 * 0188-brcmfmac-resort-data-structure-of-owe_info.patch
 * 0189-brcmfmac-TWT-fixed-feature-check.patch
 * 0190-brcmfmac-External-roam-time-enhancements.patch
 * 0191-brcmfmac-fixing-compile-warning.patch
 * 0192-brcmfmac-TWT-Handle-unsolicited-setup-accept-and-sol.patch
 * 0193-brcmfmac-TWT-use-Dialog-Token-as-unique-identifier-t.patch
 * 0194-brcmfmac-TWT-Update-teardown-state-while-handling-Te.patch
 * 0195-brcmfmac-TWT-Handle-timeout-of-Setup-and-Teardown-ev.patch
 * 0196-brcmfmac-TWT-rephrase-print-statements-with-addition.patch
 * 0197-brcmfmac-offload-add-configuration-infrastructure-su.patch
 * 0198-brcmfmac-offload-clean-add-all-entries-in-ICMP-ND-fo.patch
 * 0199-brcmfmac-avoid-unnecessary-WL-Down-UP-while-setting-.patch
 * 0200-non-upstream-update-sae_password-for-potential-roami.patch [x]
 * 0201-brcmfmac-offload-update-the-brcmf_configure_arp_nd_o.patch
 * 0202-brcmfmac-Fix-DUT-is-vulnerable-to-key-reinstallation.patch
 * 0203-brcmfmac-Support-for-WPA3-FT-SAE-roam-offload.patch
 * 0204-brcmfmac-TWT-cleanup-stale-session-entries-after-rec.patch
 * 0205-brcmfmac-Fix-kernel-crash-while-updating-tx-statisti.patch
 * 0206-brcmfmac-avoid-memory-use-after-free-in-the-escan-ti.patch
 * 0207-brcmfmac-fix-kernel-6.1-insert-driver-warning.patch
 * 0208-brcmfmac-some-register-address-which-are-never-being.patch
 * 0209-brcmfmac-pcie-update-INTMASK-per-internal-doc.patch
 * 0210-non-upstream-add-command-to-show-module-parameter.patch [x]
 * 0211-brcmfmac-support-43022-Cypress-Vendor-and-Device-ID.patch
 * 0212-brcmfmac-Chip-id-changes-for-43022.patch
 * 0213-brcmfmac-Move-shared-console-address-location.patch
 * 0214-brcmfmac-enable-support-for-split-scan-to-optimize-t.patch
 * 0215-brcmfmac-kso-sequence-sleep-delay-enhancement.patch
 * 0216-brcmfmac-Avoid-realloc-resources-on-DS1-exit-in-fw-d.patch
 * 0217-brcmfmac-PCIe-RX-throughput-improvement.patch
 * 0218-brcmfmac-Increase-the-kso_sequence-bail-out-timer.patch
 * 0219-non-upstream-btsdio-add-ifx-bt-shared-sdio-file.patch [x]
 * 0220-non-upstream-fixing-the-last-hostapd_cli-disabled-in.patch [x]
 * 0221-brcmfmac-fixing-mbss-iovar-setting-for-multiple-BSS-.patch
 * 0222-non-upstream-new-value-for-roamoff-for-report-differ.patch [x]
 * 0223-brcmfmac-Support-idleclock-feature-for-43012-43022-c.patch
 * 0224-non-upstream-btsdio-enable-export-api-to-r-w-F3-one-.patch [x]
 * 0225-non-upstream-btsdio-enable-export-api-for-F3-receivi.patch [x]
 * 0226-non-upstream-btsdio-attach-init-deinit.patch [x]
 * 0227-non-upstream-btsdio-check-rx-interrupt-before-get-rx.patch [x]
 * 0228-non-upstream-btsdio-enable-export-api-for-F3-transfe.patch [x]
 * 0229-non-upstream-btsdio-support-export-api-to-set-block-.patch [x]
 * 0230-non-upstream-btsdio-claim-function-3-in-band-irq.patch [x]
 * 0231-non-upstream-btsdio-reset-bt-in-remove-flow-when-bt-.patch [x]
 * 0232-non-upstream-btsdio-add-command-to-show-bt-shared-sd.patch [x]
 * 0233-brcmfmac-DS2-udp-tx-crash-fix.patch
 * 0234-brcmfmac-OOB-irq-support-on-43022-DS2.patch
 * 0235-brcmfmac-fix-wrong-NULL-check-in-msgbuf_rx.patch
 * 0236-non-upstream-btsdio-support-43012-43022.patch [x]
 * 0237-brcmfmac-Bootloader-host-handshake-implementation.patch
 * 0238-brcmfmac-Avoid-socram-access-in-secure-mode.patch
 * 0239-brcmfmac-Support-secure-and-non-secure-code-flow.patch
 * 0240-brcmfmac-Bring-up-DS1-for-43022-DM-chip.patch
 * 0241-brcmfmac-do-not-access-D11-SHM-and-PMU-registers-for.patch
 * 0242-brcmfmac-fixes-for-FW-redownload-after-DS1-2-exit.patch
 * 0243-brcmfmac-New-rmmod-seq-for-43022-secure-mode.patch
 * 0244-brcmfmac-Change-bus-width-independent-of-sdio_idlecl.patch
 * 0245-brcmfmac-Remove-chip-id-check-from-kso-0-bail-out-lo.patch
 * 0246-brcmfmac-fix-wrong-FW-extension-problem-for-secure-c.patch
 * 0247-brcmfmac-separate-43022-sdio-download-function-from-.patch
 * 0248-nl80211-Sync-with-wireless-next-2023-10-26-include-u.patch
 * 0249-non-upstream-nl80211-bring-back-IFX-nl80211.h-change.patch [x]
 * 0250-brcmfmac-set-authorized-flag-in-CONNECT-event-for-al.patch
 * 0251-brcmfmac-fix-warning-error-when-enable-PCIE_BARWIN_S.patch
 * 0252-brcmfmac-Add-new-survey-dump-feature.patch
 * 0253-brcmfmac-update-local-pmklist-while-process-auth_sta.patch
 * 0254-brcmfmac-fix-mmc-tuning-failed.patch
 * 0255-non-upstream-check-and-set-default-fcmode-of-the-chi.patch [x]
 * 0256-brcmfmac-add-protection-for-not-calling-cfg80211_ch_.patch
 * 0257-brcmfmac-get-wdev-from-the-event-reporting-ifp.patch
 * 0258-non-upstream-vendor-cmd-addition-for-replay-counter.patch [x]
 * 0259-non-upstream-btsdio-forward-device-id-to-bt-driver.patch [x]
 * 0260-brcmfmac-skip-bss-update-when-NULL-mac-received-for-.patch
 * 0261-brcmfmac-Adding-set-and-remove-F3-device.patch
 * 0262-brcmfmac-Check-bus-sleep-state-in-isr.patch
 * 0263-brcmfmac-resetting-sb-window-address.patch
 * 0264-non-upstream-Increase-delay-in-kso-sequence.patch
 * 0265-brcmfmac-OOB-crash-Fix-on-iMX-platform.patch
 * 0266-non-upstream-btsdio-add-DM-device-ID.patch [x]
 * 0267-non-upstream-provide-the-iw-command-to-set-get-value.patch [x]
 * 0268-non-upstream-vendor-cmds-string-infrastructure-with-.patch [x]
 * 0269-non-upstream-mkeep_alive-and-tko-string-vendor-cmds.patch [x]
 * 0270-brcmfmac-Add-module_param-to-set-idle_time_zero.patch
 * 0271-brcmfmac-Fix-KERNEL-WARNING-on-customer-clm_blob.patch
 * 0272-brcmfmac-FW-Header-Changes-to-TRXv5-for-H1-CP-Combo-.patch
 * 0273-brcmfmac-Update-D2H-Validation-Done-Timeout.patch
 * 0274-brcmfmac-Hatched-1-DDR50-CRC-error-KSO-Change.patch
 * 0275-brcmfmac-add-new-iovar-format-for-action-frame.patch
 * 0276-non-upstream-reserve-tx-credit-for-txctl-frame.patch [x]
 * 0277-brcmfmac-refine-netif_rx-for-different-kernel-versio.patch
 * 0278-brcmfmac-fix-LINUX_VERSION_CODE-warning.patch
 * 0279-non-upstream-PFN-offload-implementation.patch [x]
 * 0280-non-upstream-PFN-Add-support-for-remove_network-all-.patch [x]
 * 0281-non-upstream-Add-support-for-pfn-autoswitch.patch [x]
 * 0282-non-upstream-PNO-Fix-for-fw-trap-when-we-add-more-th.patch [x]
 * 0283-non-upstream-PNO-PNO-Code-Cleanup.patch [x]
 * 0284-brcmfmac-align-brcmf_wlc_version_le-with-official-co.patch
 * 0285-brcmfmac-Add-FW-supplicant-profile-check-for-the-roa.patch
 * 0286-brcmfmac-Fix-for-wifi-generation-info-missing-in-wpa.patch
 * 0287-brcmfmac-WPA3-192bit-fixes.patch
 * 0288-brcmfmac-fix-CERT-11N-Traffic-Differentiation-in-Sin.patch
 * 0289-brcmfmac-Unexpected-failure-errors-are-seen-during-d.patch
 * 0290-brcmfmac-P2P-Call-trace-Fix-in-P2P-GO.patch
 * 0291-brcmfmac-Crash-in-OOB-Mode-while-using-sdio_in_isr.patch
 * 0292-brcmfmac-Fix-SDIO-bus-access-in-SDIO-sleep-state.patch
 * 0293-non-upstream-IW-vendor-cmds-for-NAT-keep-alive-tko-p.patch [x]
 * 0294-brcmfmac-WPA3-Cert-19.6.1-Disable-idsup-for-192-bit-.patch
 * 0295-brcmfmac-Enable-Internal-supplicant-for-OWE-AKM.patch
 * 0296-brcmfmac-Add-Support-for-OWE-offload.patch
 * 0297-brcmfmac-Add-CLM-support-to-USB-interface.patch
 * 0298-brcmfmac-FT-Cert-FT-and-FT-roam-support-in-driver.patch
 * 0299-brcmfmac-Fix-wpa_auth-setting-for-wpa3-1x-sha256.patch
 * 0300-non-upstream-fix-kernel-warning-for-Suite-B-192-call.patch [x]
 * 0301-non-upstream-rewrite-feat_flag-to-preven-the-use-of-.patch [x]
 * 0302-brcmfmac-fix-error-msg-while-deleting-virtual-interf.patch
 * 0303-brcmfmac-Send-sup_wpa-iovar-only-to-firmware-which-h.patch
 * 0304-brcmfmac-fix-reload-FMAC-timeout-error-while-using-b.patch
 * 0305-brcmfmac-CERT-OCE-Fix-EAPOL-Timeout-issue.patch
 * 0306-brcmfmac-enable-remote-wakeup-before-USB-suspend-if-.patch
 * 0307-brcmfmac-Fix-data-traffic-halted-after-reconnect.patch
 * 0308-brcmfmac-fix-get_assoc_ies-misused-endian-untranslat.patch
 * 0309-brcmfmac-Modified-and-extended-sdio-idle-sleep-param.patch
 * 0310-brcmfmac-change-actframe_v2-to-pointer-to-fix-compil.patch
 * 0311-brcmfmac-Fix-compilation-issue-for-PCIe-build-if-SDI.patch
 * 0312-brcmfmac-CERT-WPA3-9.2.1-fix-roaming-failed-after-DU.patch
 * 0313-non-upstream-fix-channel-issue-after-country-code-ch.patch  [x]
 * 0314-non-upstream-accept-ISO3166-country-code-by-default.patch   [x]
 * 0315-non-upstream-ignore-country-IE-with-regulatory-info-.patch  [x]
 * 0316-non-upstream-fix-core-dump-in-dump-survey-w-o-5g-ban.patch  [x]
 * 0317-brcmfmac-fix-kernel-warning-when-no-clm_blob-file.patch
 * 0318-non-upstream-btsdio-fix-build-warning-when-bt-shared.patch  [x]
 * 0319-brcmfmac-sync-kernel-version-to-current-codebase.patch
 * 0320-brcmfmac-fix-set-roamtrigger-CMD-error.patch
 * 0321-brcmfmac-fix-kernel-warning-triggered-by-brcmf_fws_r.patch
 * 0322-brcmfmac-Add-support-for-SSID-protection-nl-vendor-c.patch
 * 0323-brcmfmac-adding-Interworking-IE-in-STA-while-scan-fr.patch
 * 0324-brcmfmac-DDR50-Driver-load-issue-with-H1-chip.patch
 * 0325-brcmfmac-porting-auth_status-v2-for-WPA3-roam-fails.patch
 * 0326-non-upstream-ICMP-Echo-Request-offload-implementatio.patch  [x]
 * 0327-non-upstream-assigned-an-non-zero-packetid-to-preven.patch  [x]
 * 0328-brcmfmac-offload-indicate-GTK-rekey-support-from-FW-.patch
 * 0329-brcmfmac-offload-hook-set_rekey_data-while-firmware-.patch
 * 0330-brcmfmac-Low-WMM-TX-Throughput-fix-for-BK-access-cat.patch
 * 0331-brcmfmac-offload-p2p-fix-kernel-warning.patch
 * 0332-non-upstream-workaround-to-resend-cmd-if-bus-error-h.patch  [x]
 * 0333-non-upstream-workaround-to-recover-credit-if-bus-err.patch  [x]
 * 0334-brcmfmac-Ignore-Bus-sleep-changes-in-KSO-sequence.patch
 * 0335-non-upstream-add-IW-vendor-cmds-to-config-mchan-algo.patch  [x]
 * 0336-non-upstream-cleanup-fws-in-link-down-while-SDIO-bus.patch  [x]
 * 0337-non-upstream-handle-receive-error-in-SG-case.patch          [x]
 * 0338-brcmfmac-Restrict-SDIO-CMD53-access-when-bus-in-slee.patch
 * 0339-brcmfmac-Restrict-SDIO-CMD52-access-when-bus-in-slee.patch
 * 0340-brcmfmac-handle-SDIO-readl-command-error.patch
 * 0341-nl80211-Sync-with-wireless-next.git-include-uapi-lin.patch
 * 0342-brcmfmac-re-download-fw-while-encounter-failure-on-f.patch
 * 0343-brcmfmac-enhancing-the-reason-readibility-to-ROAMING.patch
 * 0344-brcmfmac-restore-mac-given-from-user-after-reset.patch
 * 0345-brcmfmac-Added-support-to-store-ram-dump-in-persiste.patch
 * 0346-brcmfmac-fix-compile-error-when-disable-bt-share-sdi.patch
 * 0347-brcmfmac-unwrap-brcmf_cfg80211_set_rekey_data-from-C.patch
 * 0348-brcmfmac-SDIO-recovery-fixes.patch
 * 0349-brcmfmac-Fix-for-H1-DM-FW-load-issue.patch
 * 0350-brcmfmac-fix-compile-error-on-v4.x-kernel-and-32bit-.patch
 * 0351-non-upstream-p2p_invite-reinvoke-a-Persistent-Group-.patch  [x]
 * 0352-brcmfmac-KSO-Logging-improvement.patch
 * 0353-brcmfmac-fix-hang-issue-after-bus_reset.patch
 * 0354-brcmfmac-Fix-missing-NULL-pointer-check.patch
 * 0355-non-upstream-fix-channel-issues-caused-by-iw-reg-set.patch  [x]

        [-] means under upstream review
        [x] means no plan to upstream

Hostap Change List
-----------------
 * 0001-Adding-gitlab-CI-yml.patch
 * 0002-wpa_supplicant-Support-4-way-handshake-offload-for-F.patch
 * 0003-wpa_supplicant-Notify-Neighbor-Report-for-driver-tri.patch
 * 0004-nl80211-Report-connection-authorized-in-EVENT_ASSOC.patch
 * 0005-wpa_supplicant-Add-PMKSA-cache-for-802.1X-4-way-hand.patch
 * 0006-OpenSSL-Fix-build-with-OpenSSL-1.0.1.patch
 * 0007-DPP-Do-more-condition-test-for-AKM-type-DPP-offload.patch
 * 0008-non-upstream-defconfig_base-Add-Infineon-default-con.patch    	[x]
 * 0009-Fix-to-check-Invalid-GTK-IE-length-in-M3-at-STA.patch
 * 0010-Add-CONFIG_WPA3_SAE_AUTH_EARLY_SET-flags-and-codes.patch
 * 0011-wpa_supplicant-Support-WPA_KEY_MGMT_FT-for-eapol-off.patch
 * 0012-wpa_supplicant-suppress-deauth-for-PMKSA-caching-dis.patch
 * 0013-Fix-for-PMK-expiration-issue-through-supplicant.patch
 * 0014-SAE-Drop-PMKSA-cache-after-receiving-specific-deauth.patch
 * 0015-Avoid-deauthenticating-STA-if-the-reason-for-freeing.patch
 * 0016-wpa_supplicant-support-bgscan.patch
 * 0017-non-upstream-wl-cmd-create-interface-to-support-driv.patch    	[x]
 * 0018-non-upstream-wl-cmd-create-wl_do_cmd-as-an-entry-doi.patch    	[x]
 * 0019-non-upstream-wl-cmd-create-ops-table-to-do-wl-comman.patch    	[x]
 * 0020-non-upstream-wl-cmd-add-more-compile-flag.patch					[x]
 * 0021-Fix-dpp-config-parameter-setting.patch
 * 0022-DPP-Resolving-failure-of-dpp-configurator-exchange-f.patch
 * 0023-Enabling-SUITEB192-and-SUITEB-compile-options.patch
 * 0024-DPP-Enabling-CLI_EDIT-option-for-enrollee-plus-respo.patch
 * 0025-non-upstream-SAE-disconnect-after-PMKSA-cache-expire.patch    	[x]
 * 0026-Add-support-for-beacon-loss-roaming.patch
 * 0027-wpa_supplicant-Set-PMKSA-to-driver-while-key-mgmt-is.patch
 * 0028-Enabling-OWE-in-wpa_supplicant.patch
 * 0029-Add-link-loss-timer-on-beacon-loss.patch
 * 0030-TWT-Add-support-to-offload-TWT-Session-setup-handlin.patch
 * 0031-nl80211-Introduce-new-Vendor-header-file-for-driver-.patch
 * 0032-TWT-Use-INF-Vendor-path-to-offload-TWT-session-setup.patch
 * 0033-TWT-Use-INF-Vendor-path-to-offload-TWT-session-Teard.patch
 * 0034-TWT-Add-support-to-configure-TWT-of-a-session-using-.patch
 * 0035-Fix-for-station-sending-open-auth-instead-of-SAE-aut.patch
 * 0036-Fix-associating-failed-when-PMK-lifetime-is-set-to-1.patch
 * 0037-non-upstream-p2p_add_group-command-unification.patch	    	[x]
 * 0038-non-upstream-MBO-wpa_cli-mbo-command-by-INF-vendorID.patch    	[x]
 * 0039-Enabling-TLS-v1.3-by-default.patch
 * 0040-Disable-4-way-handshake-offload-for-DPP.patch
 * 0041-non-upstream-WNM-wpa_cli-wnm_maxilde-command-by-INF-.patch    	[x]
 * 0042-OWE-AP-enable-OWE-compile-option-for-hostapd-executi.patch
 * 0043-DPP2.0-support-DPP2.0-and-add-pfs-init-flow-on-EVENT.patch
 * 0044-non-upstream-Prevent-invalid-akm-key-mgmt-when-MFP-r.patch    	[x]
 * 0045-brcmfmac-add-a-configurable-link_loss-parameter-for-.patch
 * 0046-DPP-fix-for-akm-sae-and-add-dpp_reconfig-command-to-.patch
 * 0047-DPP-enable-CONFIG_DPP3-flag.patch
 * 0048-MLD-STA-protect-connect-CMD-attribute-MLO-support-un.patch
 * 0049-nl8211-Set-NL80211_WPA_VERSION_2-vs-_3-based-on-AKM-.patch
 * 0050-bgscan-wpa_supplicant-segment-fault-when-do-simple-b.patch
 * 0051-hostapd-calling-driver-to-remove-pmkid-while-pmk-cac.patch
 * 0052-non-upstream-Check-supported-Replay-Counters-through.patch    	[x]
 * 0053-non-upstream-WNM-fix-wnm_maxilde-coredump-and-get-em.patch    	[x]
 * 0054-non-upstream-temporarily-disable-the-compiler-optimi.patch    	[x]
 * 0055-enable-ACS-compile-option-by-default.patch
 * 0056-non-upstream-Added-support-for-PFN-offload.patch	    		[x]
 * 0057-non-upstream-Fix-SSID-corruption-of-PFN-config-to-dr.patch    	[x]
 * 0058-non-upstream-Fix-pfn_status-and-SSID-corruption-of-P.patch    	[x]
 * 0059-non-upstream-PFN-Add-support-for-remove_network-all-.patch    	[x]
 * 0060-non-upstream-Add-support-for-pfn-autoswitch.patch		    	[x]
 * 0061-non-upstream-Fix-for-pno-scan-starts-after-30sec-of-.patch    	[x]
 * 0062-non-upstream-PNO-cleanup.patch							    	[x]
 * 0063-Suite-B-Update-Proper-PMK-len-for-192bit-Suite-B-AKM.patch
 * 0064-STA-connection-status-update-with-11AX-info.patch
 * 0065-DUT-fails-to-connect-in-WPA2-when-AP-is-configured-i.patch
 * 0066-WPA3-CERT-WPA3-5.8.3-Roam-to-WPA3-transition-mode-Fa.patch
 * 0067-OWE-Enable-4way-handshake-offload-for-OWE.patch
 * 0068-non-upstream-Disable-4way-offload-for-P2P-GO.patch		    	[x]
 * 0069-Block-hostapd-config-with-mfpr-and-PSK-key_mgmt.patch
 * 0070-Fix-EAPOL-retry-issue-while-roaming-with-BTM.patch
 * 0071-non-upstream-Fix-802.1x-Preauth-roaming-doesn-t-upda.patch    	[x]
 * 0072-PNO-Check-PFN_ENABLE-configuration.patch
 * 0073-non-upstream-Update-configuration.patch					    	[x]
 * 0074-TWT-allow-TWT-offload-even-though-CONFIG_TESTING_OPT.patch
 * 0075-non-upstream-Enable-Testing-configuration-for-DPP-ce.patch	   	[x]
 * 0076-PNO-remove-PNO-SSID-from-firmware-when-remove_networ.patch
 * 0077-Add-support-for-SSID-protection-nl-vendor-command.patch
 * 0078-SSID-protection-fixes.patch
 * 0079-PNO-show-error-when-add-more-than-16-SSID-via-wpa_cl.patch
 * 0080-Fix-for-incorrect-11ac-connection-status.patch
 * 0081-TWT-fix-twt_offset-with-wrong-value.patch

        [x] means no plan to upstream
