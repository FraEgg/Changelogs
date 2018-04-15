<h1>Changelog unofficial RR Oreo LuisROM for Xiaomi Redmi 4x (santoni)</h1>
<p></p>
<h2>Changelog builds after 04/15/2018:</h2>
<ul>
  <li><b>My developer changelog has moved!!!</b><br> 
    Each new build has its own changelog file (* -Changelog.txt) in the download directory.<br>
    Link to the downloads: <a href="http://luis-builds.de/downloads/lineageos/rr/" target="_blank">http://luis-builds.de/downloads/lineageos/rr/</a>
  </li>
</ul>
<hr>

<h2>Changelog builds after 04/06/2018:</h2>
<ul>
  <li>Luis: Update GCam to MGC_5.1.018_Urikill_vXXII</li>
</ul>

<h2>Changelog builds after 04/05/2018:</h2>
<ul>
  <li>Luis: Change kernel cross compiler to GCC 4.9.4 Linaro-4.9.4</li>
</ul>

<h2>Changelog builds after 07/05/2018:</h2>
<ul>
<li>kernel: ryan-andri-clarity/AOSP/8.1: (7552 commits)<br>
zsmalloc: fix migrate_zspage-zs_free race condition<br>
ARM64: AutoSMP: create function helper to calculate previous cpu idle<br>
ARM64: AutoSMP: fixup and reflect to any changes about min cpus.<br>
wlan: Send STA authorized status to supplicant for AP<br>
wlan: Fix NULL pointer de-reference<br>
wlan: Fix uninitialized variable access<br>
wlan: Fix possible buffer overflow<br>
wlan: Add vendor event to get the driver hang reason<br>
wlan: Set max size of beacon and probe resp template to 384<br>
wlan: Activate max channel timer at scan start<br>
wlan: Reallocate skb before reusing in wlan_logging pkt_stats filled list<br>
wlan: Fix CPU soft lock up during workqueue cancellation<br>
wlan: Validate adapter before accessing 'hddArpStats'<br>
wlan: Get HDD context after validating adapter<br>
wlan: Add cfg_ini NULL check before dereferencing<br>
wlan: Return failure if input arguments are invalid<br>
wlan: Fix uninitialized memory access<br>
wlan: Fix Null pointer dereference<br>
wlan: Fix uninitialized variable access<br>
wlan: Cache last connection info<br>
  ...</li>
</ul>

<h2>Changelog builds after 04/05/2018:</h2>
<ul>
<li>kernel: upstream-ck-AOSP-8.1:<br>
  mmc: move to a SCHED_FIFO thread<br>
  ARM64: AutoSMP: create function helper to calculate previous cpu idle<br>
  ARM64: AutoSMP: fixup and reflect to any changes about min cpus.<br>
  ARM64: configs: santoni: update v2.9 AOSP 8.1.x<br>
  ARM64: AutoSMP: always check cpu 0/4 before incresed nr online.<br>
  ARM64: AutoSMP: changes specific limit min/max cpus<br>
  ARM64: AIO_hotplug: use unsigned integer for cpu in AiO_HotPlug_stop().<br>
  cpuidle: Add other commits left out during CAF's 3.18 stable merge<br>
  proc: Remove additional SafetyNet flags from /proc/cmdline<br>
  proc: Remove verifiedbootstate flag from /proc/cmdline<br>
  ARM64: AutoSMP: optimized up/down threshold<br>
  ARM64: AutoSMP: avoided touching reference functions.<br>
  ARM64: AutoSMP: use CPU load instead of CPU freq for up/down cpus<br>
  ion: adjust system heap pool orders<br>
  ARM64: AIO_hotplug: fix misleading indentation in AiO_HotPlug_stop().<br>
  ARM64: AIO_hotplug: use offline/online device operations<br>
  ARM64: AutoSMP: use offline/online device operations<br>
  ARM64: AutoSMP: fix reference for cpu up<br>
  ARM64: AutoSMP/AIO: don't allow users to enable more than 1 hotplug.<br>
  msm: camera_v2: fix compilation error</li>
  <li>qcom: * upstream-los-lineage-15.1-caf-8996:<br>
  hal: Fixed WSA channels for qrd450<br>
  configs: msm8953: Update controls for internal codec<br>
  hal: add support for sdm450 sku4<br>
  configs: msm8953: Add speaker and headphones paths<br>
  hal: use proper snd_card_name for acdb_init<br>
  hal: fix incorrect channel count of realtime recording</li>
</ul>

<h2>Changelog builds after 03/26/2018:</h2>
<ul>
  <li>kernel: add exfat and ntfs filesystem support</li>
</ul>

<h2>Changelog builds after 03/25/2018:</h2>
<ul>
  <li>frameworks: Add signature Spoofing permission (microG) …</li>
  <li>frameworks: telephony: Hack GSM and LTE signal strength  …</li>
  <li>frameworks: Allow location providers also outside of /system.  …</li>
  <li>frameworks: Add German translation for Dash Charging.  …</li>
</ul>

<p></p><h2>Changelog builds after 03/23/2018:</h2>
<ul>
  <li>Rebase new kernel from caf/nikesh001 sources:<br>
- ASoC: msm8x16-wcd: add speaker gain and prevent reset  …<br>
- ASoC: msm8x16-wcd: Sound control: allow further reduction of digital … <br>
- ASoC: msm8x16-wcd: Sound control: add mic gain  …<br>
- ASoC: msm8x16-wcd: Sound control  …<br>
- boeffla_wl_blocker: remove IPA stuf in list  …<br>
- boeffla_wl_blocker: Block default wakelocks we had before  …<br>
- boeffla_wl_blocker: update to wakelock blocker driver v1.1.0  …<br>
- boeffla_wl_blocker: update to wakelock blocker driver v1.0.1  …<br>
- boeffla_wl_blocker: add generic wakelock blocker driver v1.0.0  …<br>
- net/wireguard: add wireguard importer  …<br>
- Bring up for LuisROM</li>
</ul>

<h2>Changelog builds after 03/22/2018:</h2>
<ul>
<li>kernel: upstream-cm-14.1-ck: (71 commits)<br>
  - ARM64: configs: santoni: enable NTFS filesystem<br>
  - cpuidle: don't disable cpuidle when entering suspend<br>
  - PM / devfreq: Restart previous governor if new governor fails to start<br>
  - PM / devfreq: Skip status update on uninitialized previous_freq<br>
  - PM / devfreq: Add proper locking around list_del()<br>
  - Linux 3.18.101<br>
  - scsi: sg: only check for dxfer_len greater than 256M<br>
  - scsi: sg: fix static checker warning in sg_is_valid_dxfer<br>
  - scsi: sg: fix SG_DXFER_FROM_DEV transfers<br>
  - fs/aio: Use RCU accessors for kioctx_table->table[]<br>
  - fs/aio: Add explicit RCU grace period when freeing kioctx<br>
  - lock_parent() needs to recheck if dentry got __dentry_kill'ed under it<br>
  - ALSA: seq: Clear client entry before deleting else at closing<br>
  - ALSA: seq: Fix possible UAF in snd_seq_check_queue()<br>
  - ALSA: pcm: Fix UAF in snd_pcm_oss_get_formats()<br>
  - ima: relax requiring a file signature for new files with zero length<br>
  - rcutorture/configinit: Fix build directory error message<br>
  - ASoC: nuc900: Fix a loop timeout test<br>
  - mac80211: remove BUG() when interface type is invalid<br>
  - veth: set peer GSO values<br>
  ...</li>
</ul>

<h2>Changelog builds after 03/21/2018:</h2>
<ul>
<li>kernel: upstream-oreo-ck:<br>
  - ARM64: configs: santoni: update v2.6 AOSP 8.1.x<br>
  - Revert "ANDROID: ARM64: smp: disable preempt in backtracing across all cores"<br>
  - ARM: dts: add 1.57GHz cpu freq for msm8937/40<br>
  - ARM: dts: unlock 500MHz GPU Clock for msm8940<br>
  - msm: clk: clock-cpu-8939: force to use speed bin 1.<br>
  - Revert "ARM: dts: add overclock CPU for msm8937/40"<br>
  - power: qpnp-smbcharger: set back to 2000ma max allowed.<br>
  - power: qpnp-smbcharger: include 500MA into usb force fastcharge</li>
</ul>

<h2>Changelog builds after 03/18/2018:</h2>
<ul>
  <li>device: Change the source device tree @Nikesh001</li>
  <li>qcom8996: audio: Make CVD version retrieval nonfatal with ACDB v1</li>
  <li>kernel: upstream-oreo-ck: (82 commits)<br>
  - ARM64: configs: santoni: update v2.5 AOSP 8.1.x<br>
  - ARM: dts: add overclock CPU for msm8937/40<br>
  - cpufreq: alucard, nightmare: interactive governor drops bits in time calculation<br>
  - cpufreq: alucard, nightmare: use user policy for min/max responesive freq<br>
  - zswap: remove double definition of zswap_zpool_ops<br>
  - zram: unify error reporting<br>
  - mm: zpool: constify the zpool_ops<br>
  - zsmalloc: remove null check from destroy_handle_cache()<br>
  - zsmalloc: do not take class lock in zs_shrinker_count()<br>
  - zsmalloc: use class->pages_per_zspage<br>
  - zsmalloc: consider ZS_ALMOST_FULL as migrate source<br>
  - zsmalloc: partial page ordering within a fullness_list<br>
  - zsmalloc: use shrinker to trigger auto-compaction<br>
  - zsmalloc: account the number of compacted pages<br>
  - zsmalloc/zram: introduce zs_pool_stats api<br>
  - zram: fix pool name truncation<br>
  - zram: check comp algorithm availability earlier<br>
  - zram: cut trailing newline in algorithm name<br>
  - zram: cosmetic zram_bvec_write() cleanup<br>
  - zram: add dynamic device add/remove functionality<br>
    ...  </li>
</ul>

<h2>Changelog builds after 03/13/2018:</h2>
<ul>
<li>Change GCam to URIKILL FinalMOD V3</li>
<li>Switch the kernelbase from Clarity Kernel <a href="https://forum.xda-developers.com/xiaomi-redmi-4x/development/kernel-clarity-t3719341" target="_blank">@xda</a><br>
- Using Official XIAOMI Patch.<br>
- Support MIUI/AOSP (Nougat/Oreo)<br>
- Based on Android Linux Stable<br>
- Wlan Prima on CAF TAG "LA.UM.6.6.r1-05700-89xx.0"<br>
- Camera merge CAF TAG "LA.UM.5.6.r1-06300-89xx.0"<br>
- Video code/encode merge CAF TAG "LA.UM.5.6.r1-06900-89xx.0" (MIUI/AOSP Nougat)<br>
- Hybrid Kernel (Code Aurora Forum + Kernel.org).<br>
- Merge kernel.org linux-3.18.98<br>
- Mild Undervolts cpu voltages<br>
- support Doubletap2Wake / Sweep2Wake Gesture.<br>
- KCAL colour control & Backlight Dimmer<br>
- added latest alucard, nightmare, darkness cpu Governors.<br>
- added Zen, SIO i/o scheduler (CFQ as Default).<br>
- set default compression zram to Lz4.<br>
- Support F2FS only on AOSP Nougat version.<br>
- added usb force fast charge.<br>
- added sound control<br>
- added Wireguard<br>
- added boeffla wakelock blocker<br>
- added frandom<br>
- added fingerprint booster<br>
- added TTL target Support<br>
- Thanks to Contributors rainforce279 and Eduardo Noyer for the great work!</li>
</ul>

<h2>Changelog builds after 03/09/2018:</h2>
<ul>
  <li>Fix boot into recovery: Revert "drivers: power: msm-poweroff: Import Xiaomi changes"</li>
</ul>

<h2>Changelog builds after 03/08/2018:</h2>
<ul>
  <li>Add Incall Volume fix + Crystal clear audio recording mod v3.0</li>
  <li>Bring up OTA Updater for this device</li>
</ul>

<h2>Changelog builds after 03/06/2018:</h2>
<ul>
  <li>hal: switch audio_extn_set_parameters and amplifier_set_parameters</li>
</ul>

<h2>Changelog builds after 03/05/2018:</h2>
<ul>
  <li>Add wireguard vpn support</li>
  <li>Add msm8x16-wcd: Sound control @flar2</li>
  <li>Add wakelock blocker driver v1.1.0</li>
  <li>Add ElementalX governor</li>
  <li>Add Alucard governor</li>
  <li>Add Miui Camera</li>
  <li>Add OneplusGallery</li>
  <li>Add GCam</li>
</ul>

<h2>Changelog builds after 03/04/2018:</h2>
<ul>
  <li>Bring up RR Oreo LuisROM for Xiaomi Redmi 4x (beta)</li>
  <li>Based on Kernel source from: https://github.com/HridayHS/android_kernel_xiaomi_msm8937</li>
  <li>Based on Device source from: https://github.com/TeamButter/android_device_xiaomi_santoni</li>
  <li>Based on Vendor source from: https://github.com/TeamButter/android_vendor_xiaomi_santoni</li>
  <li>Fixed wlan and camera driver issue</li>
  <li>Fixed qcom audio</li>
  <li>Tested with Firmware: HM4X_fw_8.3.1glob_dev_baseband_v33.zip</li>
</ul>
