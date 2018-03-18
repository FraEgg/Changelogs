<h1>Changelog unofficial RR Oreo LuisROM for Xiaomi Redmi 4x (santoni)</h1>
<p></p>
<h2>Changelog builds after 03/18/2018:</h2>
<ul>
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
