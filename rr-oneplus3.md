<h1>Changelog RR-Oreo LuisROM for Oneplus 3/3T</h1>
<p></p>

<h2>Changelog builds after 03/07/2018:</h2>
<ul>
  <li>kernel: sched: avoid migrating when softint on tgt cpu should be short</li>
  <li>kernel: sched: avoid scheduling RT threads on cores currently handling softirqs</li>
  <li>kernel: sched/rt: Avoid moving rt task if destination CPU does not run low priority task.</li>
  <li>kernel: perf:arm64: fix lockdep warning when handling CPU_STARTING.</li>
  <li>kernel: perf:arm64: fix pmu percpu irq handling at hotplug.</li>
  <li>kernel: perf: arm64: fix RCU usage on pmu resume from low-power</li>
  <li>kernel: perf: arm64: implement CPU_PM notifier</li>
  <li>kernel: Revert "Perf: arm64: support hotplug and power collapse"</li>
  <li>kernel: Revert "Perf: arm64: fix disable of pmu irq during hotplug"</li>
  <li>kernel: Revert "Perf: arm64: restore registers after reset"</li>
  <li>kernel: Revert "Perf: arm64: stop counters when going into hotplug"</li>
  <li>kernel: ion: adjust system heap pool orders</li>
  <li>kernel: Silences WLAN, PCIe, and CPU suspend state kernel messages</li>
  <li>kernel: cpuidle: don't disable cpuidle when entering suspend</li>
  <li>kernel: ARM64: Fix merge derp</li>
  <li>kernel: Revert "scripts: gcc-wrapper: Use wrapper to check compiler warnings"</li>
  <li>kernel: ANDROID: cpufreq: stats: add uid removal for uid_time_in_state</li>
  <li>kernel: ANDROID: cpufreq_stat: add per task/uid/freq stats</li>
  <li>kernel: ANDROID: Fix cpufreq stats table creation</li>
  <li>...</li>
</ul>

<h2>Changelog builds after 03/05/2018:</h2>
<ul>
  <li>op3: Re-enable variable button brightness</li>
  <li>op3: Use api v2 for Snap</li>
  <li>Revert "msm8996: Remove the default perf mode configuration"</li>
  <li>op3: Disable debug.sf.recomputecrop</li>
  <li>op3: Use exfat-nofuse</li>
</ul>

<h2>Changelog builds after 02/27/2018:</h2>
<ul>
  <li>Add OnePlus 3/3T Front Camera Fix by defcomg</li>
  <li>Update OneplusCamera 2.5.20 & OneplusGallery 2.0.37</li>
  <li>Update GoogleCamera to Google Camera Mod 5.1.018 v3.0 Full Auto by SKULSHADY</li>
</ul>

<h2>Changelog builds after 02/25/2018:</h2>
<ul>
  <li>device: AoD: Enable burn-in protection</li>
  <li>frameworks: NightDisplayController: report unvailable if livedisplay feature is p…</li>
  <li>frameworks:Show 3G data icon for TD-SCDMA network type  …</li>
</ul>

<h2>Changelog builds after 02/23/2018:</h2>
<ul>
  <li>Add simple thermal driver @sultanxda</li>
  <li>Add touch boost @sultanxda</li>
  <li>Change kernel base from rr-devices to @flar2 elementalx</li>
  <li>Change device base from rr-devices to LineageOS</li>
   <li>Kernel Features:<br>
- Optimized for performance and battery life<br>
- Overclock/underclock CPU<br>
- Advanced color control<br>
- Sound control driver from flar2 (elementalx) (You can use the https://play.google.com/store/apps/details?id=com.grarak.kerneladiutor (Kernel Auditor app) or the https://play.google.com/store/apps/details?id=flar2.exkernelmanager (EX Kernel Manager app / recommend) to control the speaker, headphone and mic gain. )<br>
- Notification light control<br>
- Sweep2sleep<br>
- Backlight dimmer option<br>
- Wake Gestures (Sweep2Wake and DoubleTap2Wake)<br>
- Boeffla Wakelock blocker driver V1.1.0 from andip71<br>
- Simple thermal driver from sultanxda<br>
- LED Notification LED control - V1.1c<br>
- sRGB and DCI-P3 color profile <br>
- NTFS r/w support<br>
- Option to disable fsync<br>
- Adjust or disable vibration<br>
- Dash charge<br>
- WireGuard support, a next generation secure VPN tunnel https://forum.xda-developers.com/android/development/wireguard-rom-integration-t3711635<br>
- Does not force encryption<br>
- Many other misc. improvements not listed here<br>
</ul>

<h2>Changelog builds after 02/21/2018:</h2>
<ul>
<li>device: Fix camera hal</li>
<li>kernel: Fix defconfig for LuisKERNEL</li>
<li>kernel: boeffla_wl_blocker: update to wakelock blocker driver v1.1.0</li>
<li>kernel: synaptics_s3320: Fix touchscreen after resume when gesture disabled</li>
<li>kernel: msm: mdss: KCAL: disable igc update</li>
<li>kernel: msm: mdss: KCAL: Send a pp display commit when changes are made  …</li>
<li>kernel: mdss mdp: kcal for mdss_mdp_v1_7</li>
<li>kernel: leds-qpnp: Notification LED control - V1.1b</li>
<li>kernel: cpuidle: don't disable cpuidle when entering suspend  …</li>
<li>kernel: block: Make CFQ default to IOPS mode on SSDs  …</li>
<li>kernel: zen-iosched: change fifo_batch to 16</li>
<li>kernel: adrenoboost: disable by default</li>
<li>kernel: adrenoboost: finetuning algorithm - scale it a bit down  …</li>
<li>kernel: msm_adreno_tz: add adrenoboost parameter  …</li>
<li>kernel: block: add zen scheduler  …</li>
<li>kernel: mdss_fb: add backlight dimmer option</li>
<li>kernel: platform/msm: haptic: expose vibrate function</li>
<li>kernel: PM: devfreq: Use high priority workqueue  …</li>
<li>kernel: AIO: Don't plug the I/O queue in do_io_submit()  …</li>
<li>kernel: Add SIO and FIOPS i/o schedulers</li>
<li>kernel: Added fsync on/off support.  …</li>
<li>op3: Add missing OMX blobs</li>
<li>op3: Update blobs from OB32/OB22 </li> 
</ul>

<h2>Changelog builds after 02/18/2018:</h2>
<ul>
<li>kernel: defconfig: Set westwood as default TCP congestion handler</li>
<li>Linux 3.18.95<br>
mn10300/misalignment: Use SIGSEGV SEGV_MAPERR to report a failed user copy<br>
ACPI: sbshc: remove raw pointer from printk() message<br>
pktcdvd: Fix pkt_setup_dev() error path<br>
EDAC, octeon: Fix an uninitialized variable warning<br>
xtensa: fix futex_atomic_cmpxchg_inatomic<br>
alpha: fix reboot on Avanti platform<br>
alpha: fix crash if pthread_create races with signal delivery<br>
signal/sh: Ensure si_signo is initialized in do_divide_error<br>
signal/openrisc: Fix do_unaligned_access to send the proper signal<br>
kernel/async.c: revert "async: simplify lowest_in_progress()"<br>
media: cxusb, dib0700: ignore XC2028_I2C_FLUSH<br>
crypto: caam - fix endless loop when DECO acquire fails<br>
crypto: cryptd - pass through absence of ->setkey()<br>
crypto: hash - introduce crypto_hash_alg_has_setkey()<br>
kernfs: fix regression in kernfs_fop_write caused by wrong type<br>
NFS: commit direct writes even if they fail partially<br>
NFS: Add a cond_resched() to nfs_commit_release_pages()<br>
mtd: nand: Fix nand_do_read_oob() return value<br>
media: dvb-usb-v2: lmedm04: move ts2020 attach to dm04_lme2510_tuner<br>
  ..</li>
</ul>
