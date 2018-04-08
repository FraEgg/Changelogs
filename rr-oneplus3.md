<h1>Changelog unofficial RR Oreo LuisROM for Oneplus 3/3T</h1>
<p></p>
<h2>Changelog builds after 04/08/2018:</h2>
<ul>
  <li>Add more tri-state slider options</li>
  <li>Update GCam to skulshady_gcam_5.1.018_Mod_v3.0</li>
  <li>Change kernel source to caesium kernel: tweaks-mcd-8.1-upstream: (46 commits)<br>
  - Linux 3.18.103<br>
  - defconfig: set local_version<br>
  - defconfig: enable usb fast charge<br>
  - drivers: misc: implement usb fast charge mode<br>
  - ARM: dts: 15801: Optimize display effects of SRGB, DCI-P3<br>
  - msm_adreno_tz: add adrenoboost parameter and display state awareness<br>
  - defconfig: enable maple and zen ioshed<br>
  - block: add zen(v2) iosched<br>
  - defconfig: enable quick-wakeup<br>
  - power: quickwakeup: initial driver<br>
  - mdss_fb: add backlight dimmer option<br>
  - defconfig: enable state notifier<br>
  - state_notifier: Remove internal enablement switch<br>
  - state_notifier: Drop unneeded module_param_named entries<br>
  - state_notifier: Make workqueues unbound<br>
  - state_notifier: Reduce defer on suspend call to 1 second<br>
  - state_notifier: Queue work on any core<br>
  - state_notifier: Enable by default<br>
  - OP3T: Add state notifier driver<br>
  - cpufreq: interactive: prevent perfd from messing with the governor params<br>
  - CPUFREQ: prevent setting io_is_busy by ROM - again<br>
  ...</li>
  <li>Add rounded corners in UI and Recents</li> 
  <li>Add OnePlusCameraService</li>
</ul>

<h2>Changelog builds after 04/06/2018:</h2>
<ul>
  <li>Luis: Update GCam to MGC_5.1.018_Urikill_vXXII</li>
</ul>

<h2>Changelog builds after 04/05/2018:</h2>
<ul>
  <li>Luis: Change kernel cross compiler to GCC 4.9.4 Linaro-4.9.4</li>
</ul>

<h2>Changelog builds after 04/01/2018:</h2>
<ul>
  <li>revert: "kernel: msm: add thermal: simple from sultanxda"</li>
  <li>revert: "kernel: enable in defconfig + input boost"</li>
  <li>revert: "kernel: cpu_input_boost: Import from msm8996 kernel  …"</li>
  <li>revert: "kernel: msm: thermal: simple: Import from msm8996 kernel"</li>
</ul>

<h2>Changelog builds after 03/31/2018:</h2>
<ul>
  <li>Fix ota rr updater app</li>
</ul>

<h2>Changelog builds after 03/28/2018:</h2>
<ul>
  <li>kernel: msm: add thermal: simple from sultanxda</li>
  <li>kernel: enable in defconfig + input boost</li>
  <li>kernel: cpu_input_boost: Import from msm8996 kernel  …</li>
  <li>kernel: msm: thermal: simple: Import from msm8996 kernel</li>
  <li>kernel: fs: Enable exfat and ntfs</li>
  <li>device/kernel: change device & kernel tree to rr-devices</li>
  <li>frameworks: fix google assistant scripts</li>
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
  <li>kernel: upstream-oreo-ex4.00: (77 commits)<br>
  update defconfig<br>
  misc: Update from OB32/OB23 kernel source<br>
  ANDROID: disable CONFIG_CC_OPTIMIZE_FOR_SIZE<br>
  arm64: mm: move dma_overlap() out of init section<br>
  misc: Fix uninitilized variables<br>
  drivers: iommu, leds, input, clk, devfreq: fix warnings<br>
  ASoC: wcd9335: Initialize variables before use<br>
  media: vidc: change default return vaule to 0<br>
  ANDROID: clean up uninitilized variable<br>
  ANDROID: fix uninitilized variable<br>
  Revert "ANDROID: Fix cpufreq stats table creation"<br>
  ANDROID: cpufreq: stats: Fix sleeping while atomic in cpufreq_task_stats_init<br>
  ANDROID: cpufreq_stats: Fix task time in state locking<br>
  ARM: dts: msm: Bit-banging ability for i2c-12 to reset the bus<br>
  i2c: remove i2c active check, add call to recover_bit_bang<br>
  i2c: msm: Replace HW recovery mechanism with SW bit-banging<br>
  net: core: Remove warning for cloned packets in ingress path<br>
  mm: fix pageblock heuristic<br>
  op3: Disable MSM_11AD<br>
  drivers: cpufreq_interactive: handle error for module load fail<br>
    ...</li>
  <li>device: op3: adjust interactive governor parameters based on CPU power efficiency curve</li>
  <li>device: op3: Moar fingerprint hal denial</li>
  <li>device: op3: adjust interactive governor parameters based on CPU power effici…</li>
</ul>

<h2>Changelog builds after 03/20/2018:</h2>
<ul>
<li>Merge branch 'upstream-oreo-ex4.00' into oreo-luis<br>
* upstream-oreo-ex4.00: (88 commits)<br>
  update defconfig<br>
  qcacld-2.0: Disable CONFIG_WLAN_THERMAL_SHUTDOWN<br>
  msm: mdss: Silence invalid data for dither log spam<br>
  clk: msm: clock-cpu-8996: Use CLKFLAG_NO_RATE_CACHE for perfcl_hf_mux<br>
  qcom-cpufreq: Use CLKFLAG_NO_RATE_CACHE<br>
  msm: msm_bus: Don't enable QoS clocks when none are present<br>
  serial: msm_serial_hs: optimize total tty port support<br>
  msm_serial_hs:  make the Bluetooth tty thread RT<br>
  Make msm_serial_hs RT to improve bluetooth performance<br>
  tty: add tty_port_set_policy function<br>
  tty: move tty_port workqueue to be a kthread<br>
  mdss: rotator: Use FIFO kthread for rotator work<br>
  UPSTREAM: sched/preempt: Fix preempt_count manipulations<br>
  gpio: Mask non-wakeup GPIO interrupts on suspend<br>
  misc: fpc1020: Use device struct as wakeup source<br>
  Revert "input: synaptic: s3320: Fix long delay in tp_baseline_get()"<br>
  Revert "input: synaptics: s3320: Don't run baseline on resume"<br>
  Revert "HACK: arm64: add CNTPCT_EL0 trap handler"<br>
  ARM: dts: msm: Define power configuration for msm8996 and msm8998<br>
  msm: vidc: Handle perf mode configuration<br>
  ...</li>
</ul>

<h2>Changelog builds after 03/12/2018:</h2>
<ul>
  <li>Merge branch 'upstream-oreo-ex4.00' into oreo-luis<br>
* upstream-oreo-ex4.00: (114 commits)<br>
  update defconfig<br>
  Revert "op3: Enable partial update mode for Samsung display"<br>
  msm: camera: isp: Use boot clock for recording start time<br>
  power: qpnp-smbcharger: Report charger types in REAL_TYPE property<br>
  power_supply: Add REAL_TYPE power_supply_property<br>
  arm64: Add BTAC/LinkStack sanitizations for Kryo<br>
  arm64: Implement branch predictor hardening for Falkor<br>
  arm64: cpu_errata: Add Kryo to Falkor 1003 errata<br>
  arm64: Implement branch predictor hardening for affected Cortex-A CPUs<br>
  drivers/firmware: Expose psci_get_version through psci_ops structure<br>
  arm64: Add skeleton to harden the branch predictor against aliasing attacks<br>
  arm64: cpu_errata: Allow an erratum to be match for all revisions of a core<br>
  arm64: cpufeature: Pass capability structure to ->enable callback<br>
  arm64: errata: Calling enable functions for CPU errata too<br>
  drivers: soc: Synchronize apr callback and voice svc release<br>
  msm: ipa: rndis: Fine tune threshold for rndis/ecm<br>
  dev_freq: devfreq_spdm: add null terminator to prevent OOB access<br>
  ARM: dts: msm: add internal pull up for I2C1 on MDM9650 TTP<br>
  msm: ais: sensor: Fix out of bound read for region params<br>
  msm: sensor: actuator: fix out of bound read for region params<br>
    ...  </li>
  <li>device: change device tree from rr-devices</li>
</ul>

<h2>Changelog builds after 03/09/2018:</h2>
<ul>
  <li>Update GCam to GoogleCamera-Pixel2Mod-Arnova8G2-V7beta-test</li>
  <li>Update media_profiles.xml (HEVC+SloMo GCam on OP3(T)/5)</li>
</ul>

<h2>Changelog builds after 03/08/2018:</h2>
<ul>
  <li>Bring up OTA Updater for this device</li>
</ul>

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
