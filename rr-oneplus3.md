<h1>Changelog RR Nougat LuisROM for Oneplus 3/3T</h1>
<p></p>
<h2>Changelog builds after 03/12/2018:</h2>
<ul>
  <li>Revert "msm: mdss: Always set non-zero brightness on unblank"</li>
  <li>wakeup: Create fake debugfs folder solely for wakeup_sources
</ul>

<h2>Changelog builds after 03/09/2018:</h2>
<ul>
  <li>Update GCam to GoogleCamera-Pixel2Mod-Arnova8G2-V7beta-test</li>
  <li>Update media_profiles.xml (HEVC+SloMo GCam on OP3(T)/5)</li>
</ul>

<h2>Changelog builds after 03/04/2018:</h2>
<ul>
  <li>kernel: Merge remote-tracking branch 'Sultanxda/cm-14.1-sultan"</li>
  <li>kernel: power: bq27541: Don't load saved soc on boot</li>
  <li>kernel: input: synaptics: s3320: Restore nonsensical tp_baseline_get() code</li>
  <li>kernel: power: bq27541: Remove suspend/resume routines</li>
  <li>kernel: i2c-msm-v2: Ensure system is always active for i2c transfers</li>
  <li>kernel: misc: fpc1020: Use device struct as wakeup source</li>
  <li>kernel: Revert "i2c-msm-v2: Ensure i2c bus is always active for transfers"</li>
  <li>kernel: cpu_stress_test: Disable preemption while looping intensive instructions</li>
  <li>kernel: cpu_stress_test: Add back an increased start delay of 15 seconds</li>
  <li>kernel: cpu_stress_test: Add specialized assembly for stressing arm64</li>
  <li>kernel: cpu_stress_test: Ensure all available CPUs are tested thoroughly</li>
  <li>device: Merge remote-tracking branch 'Sultanxda/cm-14.1-sultan' into cm-14.1-…</li>
  <li>device: ulp proxy set capabilities race condition  …</li>
  <li>device: Revert "oneplus3: Don't use Snapdragon LLVM"  …</li>
</ul>

<h2>Changelog builds after 02/14/2018:</h2>
<ul>
  <li>Bump security patch level to 2018-02-05</li>
</ul>

<h2>Changelog builds after 02/10/2018:</h2>
<ul>
  <li>Merge remote-tracking branch 'sultanxda/cm-14.1-sultan' into cm-14.1-…</li> 
  <li>msm: thermal: simple: Fix incorrect notifier priority  …</li>
</ul>

<h2>Changelog builds after 02/03/2018:</h2>
<ul>
  <li>Update Google Camera to GoogleCamera-Pixel2Mod-Arnova8G2-V5</li>
</ul>

<h2>Changelog builds after 02/01/2018:</h2>
<ul>
  <li>Revert to Oneplus Camera and Gallery (OnePlusCamera-V8-siankatabg.apk and OnePlusGallery-V8-siankatabg.apk)</li>
  <li>Update weather provider apks</li>
</ul>

<h2>Changelog builds after 01/31/2018:</h2>
<ul>
<li>Merge remote-tracking branch 'sultanxda/cm-14.1-sultan' into cm-14.1-luis<br>
sultanxda/cm-14.1-sultan: (33 commits)<br>
  Revert "msm: camerav2: isp: Reserve rdi ub based on image size"<br>
  msm: sensor: Don't return an error when failing to read pinctrl<br>
  iommu: Don't return an error during init when debugfs init fails<br>
  oneplus3_defconfig: Disable EFI<br>
  msm: secure_buffer: Fix stage-2 protection of kernel text region<br>
  qcacld-2.0: Update to CAF LA.UM.5.5.r1-06700-8x96.0<br>
  msm: ipa: Fix the handling of default IPA header<br>
  socinfo: msm: Add soc id for SDA450<br>
  ARM: dts: msm: Add DT support for SDA450 with PMI8950<br>
  msm: sensor: actuator: add null pointer check for i2c array<br>
  soc: qcom: pil: Fix error handling during PIL driver probe<br>
  drivers: cpuidle: lpm-levels: Fix untrusted pointer dereference.<br>
  oc: qcom: rpm-smd-debug: Fix potential memory leaks<br>
  usb: gadget: f_uvc: Correct SS Companion descriptors<br>
  usb: gadget: f_uvc: Fix incorrect wBytesPerInterval<br>
  msm: camera: Prevent buffer overread in write_logsync.<br>
  ALSA: pcm: add locks for accessing runtime resource<br>
  ALSA: pcm: use lock to protect substream runtime resource<br>
  ion: ensure CMO target is valid<br>
  msm: adsprpc: Use unsigned integer for length values<br>
  ...</li>
</ul>

<h2>Changelog builds after 01/26/2018:</h2>
<ul>
<li>Update GoogleCamera (GCam5.1.018-Arnova8G2-V1.6) Link: https://www.celsoazevedo.com/files/android/google-camera/</li>
<li>Revert some Camera2Api commits (blue and red pixel with gacm)</li>
</ul>

<h2>Changelog builds after 01/23/2018:</h2>
<ul>
<li>Merge branch 'cm-14.1-sultan' into cm-14.1-luis<br>
* cm-14.1-sultan: (35 commits)<br>
  oneplus3_defconfig: Don't disable heap placement randomization<br>
  oneplus3_defconfig: Regenerate<br>
  qcom-cpufreq: Clean up underclock code<br>
  Revert "Revert "msm: mdss: add recovery if TE is not coming from the panel""<br>
  qcacld-2.0: Update to CAF LA.UM.5.5.r1-06400-8x96.0<br>
  msm: camera: isp: Allocate kernel page and map to userspace<br>
  power: qpnp-smbcharger: Disable parallel charger before changing ICL<br>
  BACKPORT: ext4: fix data exposure after a crash<br>
  msm: camera: Synchronize v4l2 subscribe and unsubscribe event in camera.c<br>
  msm: sps: Update debug message format specifier<br>
  diag: dci: Add validity check for dci client's process descriptor<br>
  msm: msm_bus: Add mutex lock for floor vote data<br>
  msm: sde: disable support for v4l2 event subscription<br>
  ext4: provide ext4_issue_zeroout()<br>
  packet: fix races in fanout_add()<br>
  Bluetooth - Fix for checking proper user-supplied buffers<br>
  driver core: platform: fix race condition with driver_override<br>
  mm/mempolicy.c: fix error handling in set_mempolicy and mbind.<br>
  ip6_gre: fix ip6gre_err() invalid reads<br>
  ipx: call ipxitf_put() in ioctl error path<br>
  ...
  </li>
  <li>device: Disable user panic feature</li>
  <li>device: Disable inline xattr feature for F2FS formatted /data</li>
</ul>

<h2>Changelog builds after 01/22/2018:</h2>
<ul>
<li>Android: Update Security patch level 2018-01-05</li>
</ul>

<h2>Changelog builds after 01/14/2018:</h2>
<ul>
 <li>Remove Boeffla Wakeblock Driver from Kernel (instable on Sultan Kernel)</li>
</ul>

<h2>Changelog builds after 01/13/2018:</h2>
<ul>
<li>Fix miracast in system.prob (persist.debug.wfd.enable=1 and persist.sys.wfd.virtual=0)</li>
</ul>

<h2>Changelog builds after 01/12/2018:</h2>
<ul>
<li>Change Google Camera to Version MGC_5.1.018.177470874.41362666__A7.0-8.1_MI5S_v2b (https://www.celsoazevedo.com/files/android/google-camera/)</li>
<li>Change to OnePlus Camera 2.5.21</li>
<li>Change to OnePlus Gallery 2.0.44</li>
</ul>
 
<h2>Changelog builds after 01/08/2018:</h2>
<ul>
 <li>device: Update media_profiles.xml for hevc (GCam)</li>
</ul>

<h2>Changelog builds after 01/04/2018:</h2>
<ul>
 <li>Change GoogleCamera to MGC-5.1.018_FullManual_v1.2_Android-7.0+</li>
</ul>

<h2>Changelog builds after 12/18/2017:</h2>
<ul>
<b>Sultan-Build:</b>
 <li>kthread: Allow kthread_bind() to actually control kthread affinity</li>
<li>Merge remote-tracking branch 'msm-3.18/rel/msm-3.18.r5-redone' to Linux from 3.18.31 to 3.18.87: <br>
Linux 3.18.87<br>
usb: host: fix incorrect updating of offset<br>
USB: usbfs: Filter flags passed in from user space<br>
USB: devio: Prevent integer overflow in proc_do_submiturb()<br>
USB: Increase usbfs transfer limit<br>
usb: hub: Cycle HUB power when initialization fails<br>
serial: 8250_pci: Add Amazon PCI serial device ID<br>
usb: quirks: Add no-lpm quirk for KY-688 USB 3.1 Type-C Hub<br>
uas: Always apply US_FL_NO_ATA_1X quirk to Seagate devices<br>
ima: fix hash algorithm initialization<br>
net: fec: fix multicast filtering hardware setup<br>
mm: avoid returning VM_FAULT_RETRY from ->page_mkwrite handlers<br>
tipc: fix cleanup at module unload<br>
net: sctp: fix array overrun read on sctp_timer_tbl<br>
NFSv4: Fix client recovery when server reboots multiple times<br>
net/appletalk: Fix kernel memory disclosure<br>
vti6: fix device register to report IFLA_INFO_KIND<br>
ARM: OMAP1: DMA: Correct the number of logical channels<br>
perf test attr: Fix ignored test case result<br>
sysrq : fix Show Regs call trace on ARM<br>
 ...
</li>
</ul>

<h2>Changelog builds after 12/16/2017:</h2>
<ul>
<b>Sultan-Build:</b>
<li>Add Boeffla wakelock Driver 1.1.0</li>
</ul>

<h2>Changelog builds after 12/13/2017:</h2>
<ul>
<li>Update GCam to Arnova's 5.1.018_v1.2: GCam5.1.018-Arnova8G2-V1.2 (2017-12-11)</li>
</ul>
<b>Elementalx-Build:</b>
<ul>
<li>op3: Disable inline xattr feature for F2FS formatted /data</li>
</ul>

<h2>Changelog builds 12/12/2017:</h2>
<ul>
 <li>CMParts: gestures: Update KeyHandler for API change  …</li>
 <li>Merge pull request #3 from Davehimself7586/patch-1</li>
</ul>

<h2>Changelog builds after 12/11/2017:</h2>
<ul>
 <li>fw/b: Return a KeyEvent instead of a boolean in KeyHandler  …</li>
<li>ZenModeHelper: Allow lights by default  …</li>
<li>Clearing up invalid entries when SyncStorageEngine starts  …</li>
<li>Prevent getting data from Clipboard if device is locked  …</li>
<li>SystemUI: Fix title text clipping when task lock button is visible …</li>
<li>Stop explicitly using kCallerPasses_Ownership  …</li>
<li>Fix ClipboardService device lock check for cross profile  …</li>
</ul>

<h2>Changelog builds after 12/09/2017:</h2>
<ul>
 <b>Sultan-Build:</b>
<li>pm-levels: Disable sleep by default to speed up boot  ...</li>
<li>input: synaptics: s3320: Clean up optimized-init insanity  ...</li>
<li>input: synaptics: s3320: Remove tons of junk </li>
<li>input: synaptics: s3320: Fix touchscreen not working on wake sometimes  ...</li>
</ul>

<h2>Changelog builds after 12/06/2017:</h2>
<ul>
 <li>Pie: Fix FC after reboot with french language  …</li>
 <li>Fix systemUI FC when using the Language QS tile</li>
</ul>

<h2>Changelog builds after 12/05/2017:</h2>
<ul>
  <b>Sultan-Build:</b>
<li>Revert "Revert "oneplus3_defconfig: Restrict kswapd to power cluster"" …</li>
<li>Revert "Revert "rcu: Restrict nocb kthreads to power cluster""  …</li>
<li>Revert "Revert "msm: mdss: Restrict display commit thread to power cl… …</li>
<li>Revert "kthread: Force all non-percpu kthreads onto the power cluster" …</li>
</ul>

<h2>Changelog builds after 12/04/2017:</h2>
<ul>
  <b>Sultan-Build:</b>
  <li>Revert <a href="https://github.com/FraEgg/android_kernel_oneplus_msm8996_sultanxda/commit/e6698de91e79c951405672c98969403342282ebc">"workqueue: Schedule workers on CPU0 or CPU0/CPU1 by default"</a></li>
  <li>misc: fpc1020: Ignore home button when virtual_key_enable is enabled  …</li>
  <li>input: synaptics: s3320: Clean up and optimize int_touch()  …</li>
</ul>

<h2>Changelog builds after 12/03/2017:</h2>
<ul>
<li>Update RR-Changelog to v5.8.5</li>
<li>Update Magisk to v14.5 (optional)  …</li>
<li>Update include method for prebuilt apks  …</li>
<li>prebuilt: Update included apk's to latest versions</li>
</ul>
<ul>
<b>Sultan-Build:</b>
<li>Revert "oneplus3_defconfig: Restrict kswapd to power cluster" …</li>
<li>Revert "rcu: Restrict nocb kthreads to power cluster"  …</li>
<li>Revert "msm: mdss: Restrict display commit thread to power cluster" …</li>
<li>oneplus3_defconfig: Use -O2 optimization …</li>
<li>treewide: Fix compile errors when -O2 is used  …</li>
<li>workqueue: Schedule workers on CPU0 or CPU0/CPU1 by default  …</li>
<li>kthread: Force all non-percpu kthreads onto the power cluster  …</li>
<li>Makefile: Use -finline-functions when -O2 is used  …</li>
<li>qcacld-2.0: Fix compile errors when -finline-functions is used  …</li>
<li>input: synaptics: s3320: Clean up and optimize hw power on/off  </li>
<li>input: synaptics: s3320: Add back missing case to IRQ handler  …</li>
<li>input: synaptics: s3320: Remove delay_qt_ms()  …</li>
<li>misc: fpc1020: Rewrite and optimize  …</li>
<li>input: synaptics: s3320: Remove s3320_disable_gestures  …</li>
<li>cpu: Don't allow CPUs in the power cluster to be unplugged  …</li>
<li>arm64: mmu: Fix alloc_init_pud section mismatches  …</li>
<li>oneplus3: extract-files: Bring back old behavior for SRC</li>
</ul>

<h2>Changelog builds after 11/29/2017:</h2>
<ul>
  <li>Revert "common: Update KeyHandler for api change"</li>
</ul>

<h2>Changelog builds after 11/28/2017:</h2>
<ul>
<li>device: Fix/Add weather providers (elementalx)</li>
<li>common: Update KeyHandler for api change</li>
</ul>

<h2>Changelog builds after 11/27/2017:</h2>
<ul>
  <li>Add Wireguard VPN ROM support</li>
</ul>

<h2>Changelog builds after 11/25/2017:</h2>
<ul>
  <li>Snap Camera: Add SD Card to KEY_CAMERA_SAVEPATH option (internal / SD card)</li>
  <li>Snap Camera: Rename Storage USB OTA drive to SD card</li>
</ul>
<ul>
<b>Merge only to LuisSultan-Build:</b>
<li>msm: vidc: Increase minimum input buffer count for VP9 decode  …</li>
<li>rtac: add size check when reading cal data kvaddr buffer  …</li>
<li>diag: Fix possible usage of freed resource issue  …</li>
<li>crypto: ice: Sanitize the ice device return address.  …</li>
<li>net: rmnet_data: validate csum in SW  …</li>
<li>Merge "msm: vidc: Increase minimum input buffer count for VP9 decode"</li>
<li>Merge "rtac: add size check when reading cal data kvaddr buffer"</li>
<li>Merge "diag: Fix possible usage of freed resource issue"</li>
<li>Merge "crypto: ice: Sanitize the ice device return address."</li>
<li>Promotion of kernel.lnx.3.18.c5-171013.  …</li>
<li>msm: ADSPRPC: Support offloading to mdsp  …</li>
<li>msm: ADSPRPC: Use modem heap for MDSP buffer allocations  …</li>
<li>media: v4l2-compat-ioctl32: memset stack union in compat ioctl …</li>
<li>Prevent potential double frees in sg driver  …</li>
<li>ASoC: wcd9xxx: restrict debugfs permission  …</li>
<li>power: reset: Do hard reset when user reboots from UI  …</li>
<li>msm: ipa: add null terminator  …</li>
<li>Merge "net: rmnet_data: validate csum in SW"</li>
<li>Merge "Prevent potential double frees in sg driver"</li>
<li>Merge "msm: ipa: add null terminator"</li>
<li>Promotion of kernel.lnx.3.18.c5-171018.  …</li>
<li>Merge "power: reset: Do hard reset when user reboots from UI"</li>
<li>Merge "ASoC: wcd9xxx: restrict debugfs permission"</li>
<li>Promotion of kernel.lnx.3.18.c5-171019.  …</li>
<li>Promotion of kernel.lnx.3.18.c5-171021.  …</li>
<li>ALSA: usb-audio: Add length check after string desc copy  …</li>
<li>Merge "msm: ADSPRPC: Support offloading to mdsp"</li>
<li>Merge "msm: ADSPRPC: Use modem heap for MDSP buffer allocations"</li>
<li>ipv6/dccp: do not inherit ipv6_mc_list from parent  …</li>
<li>diag: Add mutex protection while reading dci debug statistics  …</li>
<li>scsi: ufs: Fix race condition in ufs qcom debugfs driver  …</li>
<li>scsi: ufs: Fix stack overflow read in ufs debugfs driver  …</li>
<li>msm: ipa: prevent string buffer overflows  …</li>
<li>usb: phy: msm: Disable runtime PM for root hub upon usb disconnect …</li>
<li>Merge "media: v4l2-compat-ioctl32: memset stack union in compat ioctl"</li>
<li>Merge "ipv6/dccp: do not inherit ipv6_mc_list from parent"</li>
<li>Merge "diag: Add mutex protection while reading dci debug statistics"</li>
<li>Merge "scsi: ufs: Fix race condition in ufs qcom debugfs driver"</li>
<li>Merge "scsi: ufs: Fix stack overflow read in ufs debugfs driver"</li>
<li>Merge "msm: ipa: prevent string buffer overflows"</li>
<li>Promotion of kernel.lnx.3.18.c5-171023.  …</li>
<li>Promotion of kernel.lnx.3.18.c5-171023.1.  …</li>
<li>mmc: core: Prevent accessing user space buffer directly  …</li>
<li>Merge "ALSA: usb-audio: Add length check after string desc copy"</li>
<li>Merge "mmc: core: Prevent accessing user space buffer directly"</li>
<li>Revert "ARM: dts: msm: Add VFE efuse support for 8953"  …</li>
<li>Promotion of kernel.lnx.3.18.c5-171024.  …</li>
<li>Merge "Revert "ARM: dts: msm: Add VFE efuse support for 8953""</li>
<li>Merge 9b000a5 on remote branch  …</li>
<li>ASoC: msm8x16-wcd: Fix lineout pop issue  …</li>
<li>Promotion of kernel.lnx.3.18.c5-171025.  …</li>
<li>diag: dci: Validate dci client entries prior to access  …</li>
<li>Revert "osq_lock: fix osq_lock queue corruption"  …</li>
<li>locking/osq_lock: Fix osq_lock queue corruption  …</li>
<li>ASoC: APR: initialize struct member before being used  …</li>
<li>wcnss: fix the race condition issue during cal data extraction …</li>
<li>nl80211: Define policy for packet pattern attributes  …</li>
<li>Merge "wcnss: fix the race condition issue during cal data extraction"</li>
<li>net: rps: send out pending IPI's on CPU hotplug  …</li>
<li>net: rps: reset backlog state when IPI fails.  …</li>
<li>Merge "usb: phy: msm: Disable runtime PM for root hub upon usb discon…  …</li>
<li>Merge "net: rps: reset backlog state when IPI fails."</li>
<li>Promotion of kernel.lnx.3.18.c5-171026.  …</li>
<li>Merge "diag: dci: Validate dci client entries prior to access"</li>
<li>Merge "ASoC: msm8x16-wcd: Fix lineout pop issue"</li>
<li>Merge "ASoC: APR: initialize struct member before being used"</li>
<li>Merge "nl80211: Define policy for packet pattern attributes"</li>
<li>Promotion of kernel.lnx.3.18.c5-171030.  …</li>
<li>Promotion of kernel.lnx.3.18.c5-171031.  …</li>
<li>sched: Fix integer overflow in sched_update_nr_prod()  …</li>
<li>msm: sensor: actuator: avoid accessing out of bound memory  …</li>
<li>Merge "msm: sensor: actuator: avoid accessing out of bound memory"</li>
<li>Promotion of kernel.lnx.3.18.c5-171107.  …</li>
<li>Merge f01812f on remote branch  …</li>
<li>Revert "misc: fpc1020: Increase fingerprintd nice value when screen i…  …</li>
<li>oneplus3_defconfig: Disable unused errata fixes and PAN  …</li>
<li>rcu: Restrict nocb kthreads to power cluster  …</li>
<li>oneplus3_defconfig: Restrict kswapd to power cluster  …</li>
<li>ARM: dts: msm8996: Remove redundant CPU bandwidth devfreq devices …</li>
<li>arm64: Don't force compilation of memlat devfreq governors</li>
<li>oneplus3_defconfig: Disable perf events  …</li>
<li>input: synaptics: s3320: Fix touch_enable/disable logic  …</li>
<li>input: synaptics: s3320: Fix i2c errors on resume  …</li>
<li>input: synaptic: s3320: Fix long delay in tp_baseline_get()  …</li>
<li>input: synaptics: s3320: Add missing mutex lock in PM worker  …</li>
<li>Merge branch 'LA.UM.5.5.r1-06300-8x96.0' into cm-14.1-sultan</li>
<li>qcacld-2.0: Update to CAF LA.UM.5.5.r1-06300-8x96.0</li>
</ul>

<h2>Changelog builds after 11/24/2017:</h2>
<ul>
<li> Update Google Camera to: Arnova's 5.1.016_v1.1: GCam5.1.016-Arnova8G2-v1.1 (2017-11-17)<br>https://forum.xda-developers.com/oneplus-3/how-to/modded-google-camera-hdr-60fps-video-t3658552<br>
<b>When GCam App crashing just after being opened:</b><br>
Using a root file manager/explorer, delete the following files, and try again:<br>
<br>
Code:<br>
/System/framework/com.google.android.camera.experimental2016.jar<br>
/System/etc/permission/com.google.android.camera.experimental2016.xml<br>
</li>
</ul>
  
<h2>Changelog builds after 11/23/2017:</h2>
<ul>
<li>merge op3: Add WeChat fingerprint payment support from sultan tree (sultan)</li>
<li>soc: qcom: complete clear the memory before freeing it up. (sultan)</li>
<li>Revert "mdss: Validate cursor image size"  …(sultan)</li>
<li>tcp: fix tcp_mtu_probe() vs highest_sack (sultan)</li> 
</ul>

<h2>Changelog builds after 11/19/2017:</h2>
<ul>
<li>qcom: Allow setting custom audio, display, and media HALs  …</li>
<li>Add WOM Internet/MMS (CL) apn  …</li>
<li>Add Correios Celular (BR) APN  …</li>
<li>build: qcom_target: Add sdm660  …</li>
<li>tasks: kernel: Kill unexisting wiki reference  …</li>
<li>Update initial attach for Tmo US  …</li>
<li>charger: Remove battery_fail images  …</li>
<li>qcom_target: Commonize UM target HALs  …</li>
<li>envsetup: Fix cmremote for AOSP projects  …</li>
<li>cm/aosp/cafremote: Make variables local  …</li>
<li>Added more USA sensitive phone numbers  …</li>
<li>Updated apns for device bringup for S4 Mini - serranolteusc  …</li>
<li>cm: build: kernel: Rework kernel module logic  …</li>
</ul>

<h2>Changelog builds after 11/18/2017:</h2>
<ul>
  <li>kernel: Sinput: synaptics: Ignore keypad presses when touchscreen is in use...(sultan)</li>
  <li>kernel: Squashed revert of buggy and clunky is_keypad_stopped feature... (sultan)</li>
</ul>

<h2>Changelog builds after 11/17/2017:</h2>
<ul>
<li>Update Google Camera<br> 
-MGCB_7.0H_C2API_Mid_v.3.7_AllinOne_Full_Manual_60fps from iivanich@xda</li>
<li>Update OOS Camera & Gallery<br>
- com.oneplus.camera_2.4.17-20410150_minAPI24(arm64-v8aarmeabi-v7a)(nodpi)<br>
- com.oneplus.gallery_2.0.25-20370139_minAPI24(arm64-v8aarmeabiarmeabi-v7ax86x86_64)(nodpi)</li>
</ul>

<h2>Changelog builds after 11/14/2017:</h2>
<ul>
  <li>Add WeChat fingerprint payment support</li>
</ul>

<h2>Changelog builds after 11/11/2017:</h2>
<ul>
<li>back: Change dialer android_packages_apps_dialer to rr sources</li>
<li>snap: Camera: fix incorrect photo orientation for landscape selfie mirror shots</li>
<li>msm: mdss: Restrict display commit thread to power cluster (sultan)</li>
<li>input: synaptics: s3320: Clean up IRQ handler (sultan)</li>
<li>input: synaptics: s3320: Clean up and optimize PM routines (sultan)</li>
</ul>

<h2>Changelog builds after 11/05/2017:</h2>
<ul>
<li>tri_state_key:allow more key codes for extra modes - hardware keys fix
<li>mdss_fb: add backlight dimmer option (@flar2)</li>
<li>set hal1 for oos camera in system.prop</li>
<li>Change default Wallpaper to Luis ;-) (Thanks to patmo.de)</li>
</ul>

<h2>Changelog builds after 11/04/2017:</h2>
<li>Change default tiles</li>
<li>Notification slider: add extra options</li>
<li>[PATCH] oppo-common: Don't make notification slider haptics</li>

<h2>Changelog builds after 11/02/2017:</h2>
<ul>
<li>Allow T9 with ru_UA locale (Dialer)</li>
<li>Change dialer sources to github.com/ROM-FIXES </li>
</ul>

<h2>Changelog builds after 10/23/2017 (sultanxda):</h2>
<ul>
<li>enable burnIn protection support</li>
<li>Update blobs from OxygenOS 4.5.1</li>
<li>kernel: qcacld-2.0: Update to CAF LA.UM.5.5.r1-06100-8x96.0</li>
<li>device: Clear the GNSS Sv used list data when position fix fails</li>
</ul>

<h2>Changelog builds after 10/15/2017:</h2>
<ul>
<li>Remove wakelocks from LockClock widget (reduce battery drain)</li>
</ul>

<h2>Changelog builds after 10/10/2017:</h2>
<ul>
<li>Add DCI-P3 color Display for Sultan-Kernel</li>
<li>Add enable VoLTE support</li>
<li>Enable night display support</li>
<li>add quick setting titles</li>
<li>enable Wifi bonding 2,6GHz</li>
<li>Thanks to Ashoksoni</li>
</ul>

<h2>Changelog builds after 10/08/2017:</h2>
<ul>
<li>Fix: Show dash charging on Lockscreen</li>
<li>Add sound control driver from flar2 (elementalx) into Sultanxda kernel (You can use the <a href="https://play.google.com/store/apps/details?id=com.grarak.kerneladiutor">Kernel Auditor</a> app or the <a href="https://play.google.com/store/apps/details?id=flar2.exkernelmanager">EX Kernel Manager</a> app to control the speaker, headphone and mic gain. )</li>
</ul>

<h2>Changelog builds after 10/03/2017:</h2>
<ul>
<li>Downloads moved to http://luis-builds.de/downloads/lineageos/rr/</li>
</ul>

<h2>Changelog builds after 09/30/2017:</h2>
<ul>
<li>Update GoogleCamera to MGCB_7.0H_C2API_Mid_v.3.8b_AllinOne_Full_Manual_XDA_Developers.apk </li>
</ul>

<h2>Changelog builds after 09/29/2017:</h2>
<ul>
<li>Support signature spoofing (microG/GmsCore)</li>
</ul>

<h2>Changelog builds after 09/25/2017:</h2>
<ul>
<li>set sultan-kernel CONFIG_IP_NF_TARGET_TTL=y</li>
</ul>

<h2>Changelog builds after 09/24/2017:</h2>
<ul>
<li>Update blobs from OB24 / OB15 (sultan builds)</li>
</ul>

<h2>Changelog builds after 09/23/2017:</h2>
<ul>
<li>Update blobs from OB24 / OB15 (elementalX builds)</li>
</ul>

<h2>Changelog builds after 09/21/2017:</h2>
<ul>
<li>Revert to OnePlusCamera and Gallery 1.5 from OB14 (thanks to nvertigo)</li>
</ul>

<h2>Changelog builds after 09/19/2017:</h2>
<ul>
<li>Update Google Camera to MGCB_7.0H_C2API_Min_v.2.1_AllinOneN6P_60fps (2017-09-14). Use this https://forum.xda-developers.com/showpost.php?p=73745008&postcount=327 Config</li>
</ul>
Changes only Sultan-Builds (Kernel):
<ul>
<li>trace: ipc_logging: Avoid buffer overflow in ipc_log_string() </li>
<li>diag: Synchronize msg mask read and write on a peripheral </li>
<li>thermal: tsens: Disable Tsens interrupts during driver initialization</li> 
<li>Merge "trace: ipc_logging: Avoid buffer overflow in ipc_log_string()" </li>
<li>Promotion of kernel.lnx.3.18.c5-170815. </li>
<li>msm: sensor: Fix crash when ioctl VIDIOC_MSM_SENSOR_INIT_CFG</li> 
<li>ASoC: msm: qdsp6v2: Check out-of-bound access in put functions </li>
<li>msm: camera: Avoid deadlock for vb2 operations using separate lock </li>
<li>msm: sensor: Add mutex lock during ois power down operations </li>
<li>qseecom: Fix accessing userspace memory in kernel space </li>
<li>msm: mdss: Add check for ioctl calls </li>
<li>msm: mdss: Check htotal for calculating programmable fetch</li> 
<li>Merge "msm: camera: Avoid deadlock for vb2 operations using separate …</li> 
<li>Merge "ASoC: msm: qdsp6v2: Check out-of-bound access in put functions" </li>
<li>Merge "qseecom: Fix accessing userspace memory in kernel space" </li>
<li>Merge "msm: sensor: Add mutex lock during ois power down operations" </li>
<li>msm: kgsl: Fix the syncpoint_fence trace </li>
<li>msm: kgsl: Protect the event->handle with spinlock</li> 
<li>msm:ipa: Fix to incorrect structure access </li>
<li>drm/msm: Fix potential buffer overflow issue </li>
<li>Promotion of kernel.lnx.3.18.c5-170817. </li>
<li>Merge "msm: mdss: Add check for ioctl calls" </li>
<li>Merge "msm: mdss: Check htotal for calculating programmable fetch"</li> 
<li>qbt1000: Validate FP app name before qseecom_start_app </li>
<li>Merge "drm/msm: Fix potential buffer overflow issue" </li>
<li>Merge "msm:ipa: Fix to incorrect structure access" </li>
<li>Merge "msm: kgsl: Protect the event->handle with spinlock"</li> 
<li>Merge "qbt1000: Validate FP app name before qseecom_start_app" </li>
<li>Promotion of kernel.lnx.3.18.c5-170818. </li>
<li>qseecom: use strnlen in qseecom_start_app </li>
<li>Promotion of kernel.lnx.3.18.c5-170820. </li>
<li>Promotion of kernel.lnx.3.18.c5-170821. </li>
<li>BACKPORT: f2fs: sanity check log_blocks_per_seg</li> 
<li>timerfd: Protect the might cancel mechanism proper </li>
<li>f2fs: sanity check segment count </li>
<li>FROMLIST: f2fs: sanity check checkpoint segno and blkoff</li> 
<li>Merge "timerfd: Protect the might cancel mechanism proper" </li>
<li>Merge "f2fs: sanity check segment count" </li>
<li>Merge "FROMLIST: f2fs: sanity check checkpoint segno and blkoff"</li> 
<li>tracing : fix race condition reading saved tgids </li>
<li>Merge "thermal: tsens: Disable Tsens interrupts during driver initial…</li> 
<li>Promotion of kernel.lnx.3.18.c5-170823. </li>
<li>msm: ipa3: Fix IPA aggregation force close call</li> 
<li>Merge "msm: ipa3: Fix IPA aggregation force close call"</li> 
<li>Promotion of kernel.lnx.3.18.c5-170823.1. </li>
<li>Merge "diag: Synchronize msg mask read and write on a peripheral"</li> 
<li>Merge "tracing : fix race condition reading saved tgids" </li>
<li>Promotion of kernel.lnx.3.18.c5-170824. </li>
<li>ASoC: msm: qdspv2: initialize struct member before being used</li> 
<li>Promotion of kernel.lnx.3.18.c5-170825. </li>
<li>Promotion of kernel.lnx.3.18.c5-170828. </li>
<li>Merge ec3b3f7 on remote branch </li>
<li>Merge branch 'LA.UM.5.5.r1-05800-8x96.0' into cm-14.1-sultan </li>
</ul>

<h2>Changelog builds ElementalX after 09/14/2017:</h2>
<ul>
<li>ARM: dts: 15801: Nuke redundant panel cmds</li>
<li>ARM: dts: 15801: Update panel sRGB & DCI-P3 cmd from Open Beta kernel...</li>
<li>FROMLIST: f2fs: make background threads of f2fs being aware of freezing...</li>
<li>FROMLIST: f2fs: use IPU for cold files...</li>
<li>FROMLIST: f2fs: introduce discard_granularity sysfs entry…</li>
<li>Merge remote-tracking branch 'lineageos/cm-14.1' into ElementalX-3.00… </li>
</ul>

<h2>Changelog builds after 09/12/2017:</h2>
<ul>
<li>op3: Update blobs from OxygenOS Open Beta 14 and 23</li>
<li>Sultan: Add potential fix for MediaScanner crashes on raw files</li>
<li>Sultan: Snap: Fix face detection crash when switching cameras</li>
<li>Sultan: Revert "ARM: dts: 15801/15811: Update panel sRGB commands from Open Beta kernel</li>
</ul>

<h2>Changelog builds after 09/03/2017:</h2>
<ul>
<li>op3: Update blobs from OxygenOS Open Beta 13 and 22</li>
<li>Update blobs from OB22 / OB13  …		</li>
<li>Address wcnss_service denial  …		</li>
<li>Add specific camera parameter library  …			</li>
<li>Don't advertise manual ISO modes for the OP3T's front camera  …		</li>	
<li>Increase the number of voice call and media volume steps …			
<li>Increase handset volume  …			</li>
<li>Disable WiFi calling  …			</li>
<li>Update non-pro Adreno firmware checksums for Open Beta 22</li>
<li>Update panel sRGB commands from Open Beta kernel</li>
<li>Snap: Fix selfie mirror for OP3(T) camera stack</li>
</ul>

<h2>Changelog builds after 09/01/2017:</h2>
<ul>
<li>Use Gallery2 app from cm-14.1</li>
<li>Update all sourcetrees from sultanxda and flar2</li>
<li>Update Google Camera Port (30/60fps)</li>
<li>Update OnePlus Gallery and switch to OnePlus Camera from OnePlus 5</li>
</ul>

<h2>Changelog builds after 08/07/2017:</h2>
<ul>
<li>Use Gallery2 app from cm-13.0</li>
<li>Revert "Revert "Add Gallery2 decoding speed-up patch"</li>
<li>Revert "Remove Gallery2 Nougat compilation fix"</li>
</ul>

<h2>Changelog builds after 08/06/2017:</h2>
<ul>
<li>fix video rec issues with elemental kernel version</li>
<li>add Build in Google Camera 4.4.012.156195200 (From Android O Dev Preview 3)</li>
</ul>

<h2>Changelog builds after 08/03/2017:</h2>
<ul>
<li>builds update sources with ElementalX-Kernel from and device sources from sultanxda</li>
<li>fixed elementalx builds with camera issues (can't connect camera) </li>
<li>add build in OxygenOS Camera and Gallery V8 after builds 08/03/17 (OxygenOS Stock Camera and Gallery Port from siankatabg)</li>
</ul>

