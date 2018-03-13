<h1>Changelog RR Luis-Builds Xiaomi Redmi 4x (santoni)</h1>
<p></p>
<h2>Changelog builds after 03/12/2018:</h2>
<ul>
<li>Change GCam to URIKILL FinalMOD V3</li>
<li>Some update from LOS-14.1 framework sources:<br>
- Update tint of resource icons of third party QS tiles<br>
- SystemUI: Fix LiveDisplay tile off color  …<br>
- livedisplay: Allow tile creation before boot completed phase [2/2]  …<br>
- mtp: fix double free of thumbnail data  …<br>
- Throw OOME if Bitmap.nativeCreate fails  … <br>
- Adjust Uri host parsing to use last instead of first @.  …<br>
</li>
</ul>

<h2>Changelog builds after 03/13/2018:</h2>
<ul>
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

<h2>Changelog builds after 03/08/2018:</h2>
<ul>
  <li>Add Incall Volume fix + Crystal clear audio recording mod v3.0</li>
</ul>

<h2>Changelog builds after 03/02/2018:</h2>
<ul>
  <li>device: Update ramdisk changes</li>
  <li>device: Enable Night Light</li>  
<li>Merge android-linux-stable/msm-3.18/kernel.lnx.3.18.r33-rel: (257 commits)<br>
  Revert "USB: f_fs: Use HS and SS descriptors without checking gadget speed"<br>
  Linux 3.18.97<br>
  ASN.1: fix out-of-bounds read when parsing indefinite length item<br>
  usb: gadget: f_fs: Process all descriptors during bind<br>
  usb: dwc3: gadget: Set maxpacket size for ep0 IN<br>
  arm64: Disable unhandled signal log messages by default<br>
  irqchip/gic-v3: Use wmb() instead of smb_wmb() in gic_raise_softirq()<br>
  x86/oprofile: Fix bogus GCC-8 warning in nmi_setup()<br>
  iio: adis_lib: Initialize trigger before requesting interrupt<br>
  iio: buffer: check if a buffer has been set up when poll is called<br>
  cfg80211: fix cfg80211_beacon_dup<br>
  scsi: ibmvfc: fix misdefined reserved field in ibmvfc_fcp_rsp_info<br>
  PCI: keystone: Fix interrupt-controller-node lookup<br>
  netfilter: drop outermost socket lock in getsockopt()<br>
  Linux 3.18.96<br>
  crypto: s5p-sss - Fix kernel Oops in AES-ECB mode<br>
  KVM: async_pf: Fix #DF due to inject "Page not Present" and "Page Ready" exceptions simultaneously<br>
  hippi: Fix a Fix a possible sleep-in-atomic bug in rr_close<br>
  xen: XEN_ACPI_PROCESSOR is Dom0-only<br>
  x86/mm/kmmio: Fix mmiotrace for page unaligned addresses<br>
  ...<br></li>
</ul>

<h2>Changelog builds after 02/14/2018:</h2>
<ul>
  <li>Bump security patch level to 2018-02-05</li>
</ul>

<h2>Changelog builds after 02/03/2018:</h2>
<ul>
  <li>Add MIUI Camera for Nougat</li>
</ul>

<h2>Changelog builds after 02/02/2018:</h2>
<ul>
<li>Change GoogleCamera to MGC_5.1.018.177470874.41362666__A7.0-8.1_kenzo_v2e_by_SerJo87_v1.4</li>
<li>Add alucard and elementalx governor</li>
<li>android-linux-stable/msm-3.18/kernel.lnx.3.18.r22-rel: (54 commits)<br>
  scsi: sg: Remove some locking for cleaner 3.18.93 merge<br>
  Linux 3.18.93<br>
  hrtimer: Reset hrtimer cpu base proper on CPU hotplug<br>
  ipv4: Make neigh lookup keys for loopback/point-to-point devices be INADDR_ANY<br>
  ipv6: fix udpv6 sendmsg crash caused by too small MTU<br>
  net: Allow neigh contructor functions ability to modify the primary_key<br>
  vmxnet3: repair memory leak<br>
  sctp: return error if the asoc has been peeled off in sctp_wait_for_sndbuf<br>
  sctp: do not allow the v4 socket to bind a v4mapped v6 address<br>
  pppoe: take ->needed_headroom of lower device into account on xmit<br>
  net: qdisc_pkt_len_init() should be more robust<br>
  tcp: __tcp_hdrlen() helper<br>
  net: igmp: fix source address check for IGMPv3 reports<br>
  dccp: don't restart ccid2_hc_tx_rto_expire() if sk in closed state<br>
  net: tcp: close sock if net namespace is exiting<br>
  x86/microcode/intel: Extend BDW late-loading further with LLC size check<br>
  eventpoll.h: add missing epoll event masks<br>
  scsi: libiscsi: fix shifting of DID_REQUEUE host byte<br>
  fs/fcntl: f_setown, avoid undefined behaviour<br>
  reiserfs: don't preallocate blocks for extended attributes<br>
  ...</li>
</ul>

<h2>Changelog builds after 02/01/2018:</h2>
<ul>
  <li>Update weather provider apks</li>
</ul>

<h2>Changelog builds after 01/26/2018:</h2>
<ul>
<li>Update GoogleCamera (GCam5.1.018-Arnova8G2-V1.6) Link: https://www.celsoazevedo.com/files/android/google-camera/</li>
</ul>

<h2>Changelog builds after 01/23/2018:</h2>
<ul>
  <li>Merge remote-tracking branch 'android-linux-stable/msm-3.18/kernel.lnx.3.18.r22-rel'<br>
Linux 3.18.92</li>
  <li>defconfig:Enable exFAT</li>
  <li>defconfig:Enable F2fs</li>
  <li>Add exFAT support</li>
  <li>Defconfig:Enable F2FS_FS_ENCRYPTION</li>
  <li>Defconfig:Enable NTFS</li>
  <li>:bug: fingerprint: fpc and goodix fixes</li>
  <li>Defconfig: enable boeffla wakelock blocker</li>
  <li>boeffla_wl_blocker: update to wakelock blocker driver v1.1.0</li>
  <li>boeffla_wl_blocker: update to wakelock blocker driver v1.0.1</li>
  <li>boeffla_wl_blocker: add generic wakelock blocker driver v1.0.0</li>
  <li>Defconfig:Enalbed ElementalX governor</li>
  <li>cpufreq; add elementalx governor</li>
  <li>Defconfig: Add ZEN I/O Scheduler</li>
  <li>block: add zen scheduler</li>
  <li>Defconfig: Enabled Sound control</li>
  <li>Defconfig: drop NFCQ driver, santoni doesn't have NFC.</li>
  <li>ASoC: msm8x16-wcd: add speaker gain and prevent reset</li>
  <li>ASoC: msm8x16-wcd: Sound control: allow further reduction of digital gain</li>
  <li>ASoC: msm8x16-wcd: Sound control: add mic gain</li>
 <li>ASoC: msm8x16-wcd: Sound control<br>...</li>
</ul>
 
<h2>Changelog builds after 01/22/2018:</h2>
<ul>
<li>Android: Update Security patch level 2018-01-05</li>
</ul>

<h2>Changelog builds 01/13/2018:</h2>
<ul>
 <li>device: Fix Miracast & Cast</li>
</ul>

<h2>Changelog builds after 01/12/2018:</h2>
<ul>
<li>santoni: Revert"Drop prebuilt cam"</li>
<li>Change Google Camera to Version MGC_5.1.018.177470874.41362666__A7.0-8.1_MI5S_v2b (https://www.celsoazevedo.com/files/android/google-camera/)</li>
<li>Change to OnePlus Gallery 2.0.44</li>
</ul>

<h2>Changelog builds after 01/11/2018:</h2>
<ul>
<li>santoni: Drop prebuilt cam</li>
 <li>santoni: Enable f2fs</li>
 <li>santoni: Enable Sdcardfs</li>
 <li>santoni: Fixed Recent key</li>
</ul>

<h2>Changelog builds after 01/04/2018:</h2>
<ul>
 <li>Change GoogleCamera to MGC-5.1.018_FullManual_v1.2_Android-7.0+</li>
 <li>input: doubletap2wake: disable by default  …</li>
 <li>Remove default Wakelocks from driver</li>
 </li>Defconfig: drop NFCQ driver, santoni doesn't have NFC</li>
</ul>

<h2>Changelog builds after 01/03/2018:</h2>
<ul>
<li>kernel: Merge remote-tracking branch 'android-linux-stable/msm-3.18/kernel.lnx.3.18.r22-rel' into cm-14.1-luis<br>
android-linux-stable/msm-3.18/kernel.lnx.3.18.r22-rel: (33 commits)<br>
 Linux 3.18.91</li>
<li>Update GCam to Camera_5.1.016.174405463</li>
<li>device: Fix keylayout for santoni device</li>
<li>device: Fix IR Blaster (IR Permissions)</li>
<li>kernel: add elementalx governor</li>
<li>kernel: fix alucard governor</li>
<li>kernel: bug: goodix fingerprint driver support</li>
<li>kernel: enable ntfs driver</li>
<li>kernel: enable extFAT driver</li>
<li>kernel: enable F2FS ENCRYPTION</li>

</ul>

<h2>Changelog builds after 12/28/2017:</h2>
<ul>
<li>Merge remote-tracking branch 'android-linux-stable/msm-3.18/kernel.lnx.3.18.r22-rel'<br>
Linux 3.18.90</li>
</ul>
 
<h2>Changelog builds after 12/24/2017:</h2>
<ul>
 <li>Merge remote-tracking branch 'Nikesh001/cm.14.1-new' to Linux from 3.18.87 to 3.18.89</li>
 <li>Add Alucard Governor</li>
 <li>driver: fingerprint: undef goodix debug</li>
</ul>

<h2>Changelog builds after 12/23/2017:</h2>
<ul>
<li>Tweak Power and Temperature control features…</li>
<li>Update mixer_paths  …</li>
<li>Update GPS config …</li>
<li>Update system.prop  …</li>
<li>BoardConfig: Add missing features  …</li>
<li>Correct these lines: isn't supported.</li>
<li>Drop prebuilt camera hal</li>
</ul>

<h2>Changelog builds after 12/22/2017:</h2>
<ul>
 <li>Fix CGam 4.4 (FC)</li>
</ul>

<h2>Changelog builds after 12/18/2017:</h2>
<ul>
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

<h2>Changelog builds after 12/17/2017:</h2>
<ul>
 <li>Enable Boeffla wakelock Driver 1.1.0 (defconfig)</li>
 <li>Add fastcharge thermal-enginge.conf (Mod)</li>
 <li>Add CONFIG_FB_MSM_MDSS_KCAL_CTRL=y (KCal) to defconfig</li>
</ul>

<h2>Changelog builds after 12/16/2017:</h2>
<ul>
<li>Add Boeffla wakelock Driver 1.1.0</li>
</ul>

<h2>Changelog builds after 12/15/2017:</h2>
<ul>
<li>Add Sound Control Driver by @flar2</li> 
<li>change device tree forked from @Nikesh001
<li>change kernel tree forked from @Nikesh001
<li>change vendor tree forked from @Nikesh001
</ul>

<h2>Changelog builds after 12/14/2017:</h2>
<ul>
 <li>Fix persist.camera.liveshot.size=1280x720 (Instagram fix)</li>
 <li>epoll: Drop struct epoll_event definition  …</li>
 <li>define SND_AUDIOCODEC_DSD and SND_AUDIOCODEC_APTX</li>
</ul>

<h2>Changelog builds after 12/13/2017:</h2>
<ul>
 <li>Update GCam to Arnova's 5.1.018_v1.2: GCam5.1.018-Arnova8G2-V1.2 (2017-12-11)</li>
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
<li>drivers: power: Fix 2% battery level drop</li> 
<li>proc: Remove verifiedbootstate flag from /proc/cmdline  …</li> 
<li>proc: Remove additional SafetyNet flags from /proc/cmdline  …</li> 
<li>Ghost Kernel</li> 
<li>Enable Fast Charge By Default</li> 
<li>Update santoni_defconfig</li> 
<li>netlink: add a start callback for starting a netlink dump  …</li> 
<li>ipsec: Fix aborted xfrm policy dump crash  …</li> 
<li>mm, thp: Do not make page table dirty unconditionally in touch_p[mu]d()  …</li> 
<li>mm/madvise.c: fix madvise() infinite loop under special circumstances  …</li> 
<li>KVM: x86: Exit to user-mode on #UD intercept when emulator requires  …</li> 
<li>btrfs: clear space cache inode generation always  …</li> 
<li>KVM: x86: inject exceptions produced by x86_decode_insn  …</li> 
<li>eeprom: at24: check at24_read/write arguments  …</li> 
<li>drm/panel: simple: Add missing panel_simple_unprepare() calls  …</li> 
<li>NFS: revalidate "." etc correctly on "open".  …</li> 
<li>drm/i915: Don't try indexed reads to alternate slave addresses …</li> 
<li>drm/i915: Prevent zero length "index" write  …</li> 
<li>Linux 3.18.86</li> 
<li>bcache: only permit to recovery read error when cache device is clean  …</li> 
<li>bcache: recover data from backing when data is clean  …</li> 
<li>serial: 8250_fintek: Fix rs485 disablement on invalid ioctl()  …</li> 
<li>EDAC, sb_edac: Fix missing break in switch  …</li> 
<li>spi: sh-msiof: Fix DMA transfer size check  …</li> 
<li>sysrq : fix Show Regs call trace on ARM  …</li> 
<li>perf test attr: Fix ignored test case result  …</li> 
<li>ARM: OMAP1: DMA: Correct the number of logical channels  …</li> 
<li>vti6: fix device register to report IFLA_INFO_KIND  …</li> 
<li>net/appletalk: Fix kernel memory disclosure  …</li> 
<li>NFSv4: Fix client recovery when server reboots multiple times  …</li> 
<li>net: sctp: fix array overrun read on sctp_timer_tbl  …</li> 
<li>tipc: fix cleanup at module unload  …</li> 
<li>mm: avoid returning VM_FAULT_RETRY from ->page_mkwrite handlers …</li> 
<li>net: fec: fix multicast filtering hardware setup  …</li> 
<li>ima: fix hash algorithm initialization  …</li> 
<li>usb: quirks: Add no-lpm quirk for KY-688 USB 3.1 Type-C Hub  …</li> 
<li>uas: Always apply US_FL_NO_ATA_1X quirk to Seagate devices  …</li> 
<li>serial: 8250_pci: Add Amazon PCI serial device ID  …</li> 
<li>usb: hub: Cycle HUB power when initialization fails  …</li> 
<li>USB: Increase usbfs transfer limit  …</li> 
<li>USB: devio: Prevent integer overflow in proc_do_submiturb()  …</li> 
<li>USB: usbfs: Filter flags passed in from user space  …</li> 
<li>usb: host: fix incorrect updating of offset  …</li> 
<li>Linux 3.18.87</li> 
</ul>

<h2>Changelog builds after 12/10/2017:</h2>
<ul>
 <li>santoni: Move to source built audio hal</li>
 <li>santoni: Move to oss consumerir hal</li>
 <li>Add missing restore hciattach</li>
</ul>

<h2>Changelog builds after 12/09/2017:</h2>
<ul>
 <li>fix compile error due to typo</li>
 <li>Change to Linux 3.18.85</li>
</ul>

<h2>Changelog builds after 12/06/2017:</h2>
<ul>
 <li>Pie: Fix FC after reboot with french language  …</li>
 <li>Fix systemUI FC when using the Language QS tile</li>
 <li>santoni: Enable Cpuset</li>
</ul>

<h2>Changelog builds after 12/03/2017:</h2>
<ul>
<li>Change to MIUICamera.apk V1.5 from pavaosk@xda<br>Thread: https://forum.xda-developers.com/xiaomi-redmi-4x/themes/camera-mod-miui-camera-added-features-t3713989</li>
<li>Update RR-Changelog to v5.8.5</li>
<li>Update Magisk to v14.5 (optional)  …</li>
<li>Update include method for prebuilt apks  …</li>
<li>prebuilt: Update included apk's to latest versions</li>
</ul>

<h2>Changelog builds after 12/02/2017:</h2>
<ul>
<li>add MIUI Camera</li>
<li>vendor:Revert "santoni: drop Camera HAL blobs, use OSS"</li>
<li>santoni: Move to oss consumerir hal</li>
<li>santoni: fix consumerir</li>
<li>kernel: msm: qpnp-haptic: set up sysfs interface for common cmhw implementation  …</li>
<li>msm: qpnp-haptic: Process haptics asynchronously  …</li>
<li>power:qpnp-charger: extended charge time from 30s to 100s when batter…  …</li>
<li>ASoC: wcd-mbhc: correct lineout detection  …</li>
<li>proc: Remove additional SafetyNet flags from /proc/cmdline  …</li>
<li>proc: Remove verifiedbootstate flag from /proc/cmdline  …</li>
<li>Enable Fast Charging By Default</li>
<li>Enable USB FastCharge</li>
<li>drivers: misc: implement usb fast charge mode  …</li>
<li>drivers: power: Fix 2% battery level drop</li>
<li>drivers : usb: Increase charge current</li>
<li>Enable Sound Control with Mic Gain @flar2 for apps (<a href="https://play.google.com/store/apps/details?id=com.grarak.kerneladiutor">Kernel Auditor</a> or <a href="https://play.google.com/store/apps/details?id=flar2.exkernelmanager">EX Kernel Manager)</a></li>
<li>ASoC: msm8x16-wcd: add speaker gain and prevent reset</li>
<li>ASoC: msm8x16-wcd: Sound control: allow further reduction of digital …</li>
<li>ASoC: msm8x16-wcd: Sound control: add mic gain</li>
<li>ASoC: msm8x16-wcd: Sound control  …</li>
<li>Enable Westwood TCP and Make it as Default</li>
<li>msm: mdss: KCAL: disable igc update</li>
<li>msm: mdss: KCAL: Send a pp display commit when changes are made …</li>
<li>mdss: mdp: kcal for mdss_mdp_v1_7  …</li>
</ul> 
 
<p></p>
<h2>Changelog builds after 11/30/2017:</h2>
<ul>
 <li>add Wireguard vpn support</li>
 <li>change kernel source from upstream-caf-kernels/msm-3.18</li>
 <li>santoni: camera: Camera hal updates …</li>
 <li>santoni: camera: squash update for camera HAL with compatible commits</li>
 <li>santoni: camera: HACK to make OSS hal work with camera blobs</li>
 <li>santoni: camera: Fixes to OSS camera hal to build in LineageOS tree  …</li>
 <li>santoni: camera: Import oss camera HAL</li>
 <li>Revert "Add multicolor LED with prebuilt kernel"</li>
 <li>santoni: set selinux as Enforcing</li>
<li>Update santoni_defconfig</li>
<li>Added fsync on/off support....</li>
<li>proc: Remove additional SafetyNet flags from /proc/cmdline...</li>
<li>proc: Remove verifiedbootstate flag from /proc/cmdline...</li>
<li>drivers: misc: implement usb fast charge mode...</li>
<li>power:qpnp-charger: extended charge time from 30s to 100s when batter...</li>
<li>ASoC: wcd-mbhc: correct lineout detection  ...</li>
<li>msm: qpnp-haptic: Process haptics asynchronously</li>
<li>qpnp-haptic: Dejank the haptics ...</li>
<li>msm: qpnp-haptic: set up sysfs interface for common cmhw implementation...</li>
<li>drivers : usb: Increase charge current</li>
</ul>

<h2>Changelog builds after 11/28/2017:</h2>
<ul>
 <li>device: Fix/Add weather providers</li>
 <li>santoni: block fp events for now</li>
 <li>santoni: drop prebuilt kernel && WLAN driver && set selinux as permis…</li>
 <li>santoni: restore hciattach …</li>
</ul>

<h2>Changelog builds after 11/27/2017:</h2>
<ul>
  <li>vendor: Use WLAN driver built into kernel</li>
  <li>santoni: drop prebuilt kernel && WLAN driver && set selinux as permis…  …</li>
  <li>santoni: block fp events for now</li>
</ul>

<h2>Changelog builds after 11/25/2017:</h2>
<ul>
  <li>Snap Camera: Add SD Card to KEY_CAMERA_SAVEPATH option (internal / SD card)</li>
  <li>Snap Camera: Rename Storage USB OTA drive to SD card</li>
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
<li>fix neverallow rules in rmt_storage.te sepolicy  …</li>
<li>Fixed recent app switcher</li> 
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
<li>Add fastcharge thermal-enginge.conf mod</li>
<li>Add OneplusGallery</li>
<li>Add Google Camera (MGCB_7.0H_C2API_Mid_v.3.7_AllinOne_Full_Manual_60fps from iivanich@xda)</li>
<li>kernel: Revert: add more sepolicies  …</li>
<li>kernel: Revert: Add rmt_storage to proper groups</li>
</ul>
  
<h2>Changelog builds after 11/17/2017:</h2>
<ul>
<li>kernel: init: Add netmgrd to proper groups</li>
<li>kernel: Add more sepolicies  …</li>
<li>kernel: fix bluetooth denials</li>
<li>kernel: Add rmt_storage to proper groups</li>
<li>kernel: fix typo  …</li>
<li>kernel: Fix reading Bluetooth MAC address</li>
<li>kernel: overlay: Set Default WiFi Hotspot Name  …</li>
<li>kernel: recent app switcher fixes  …</li>
</ul>

<h2>Changelog builds after 11/14/2017:</h2>
<ul>
  <li>Add WeChat fingerprint payment support</li>
  <li>kernel: Extracted defconfig from stock kernel</li>
  <li>santoni: Add Virtual flag to ft5x06_720p.kl</li>
  <li>Merge pull request #4 from HridayHS/cm-14.1</li>
</ul>

<h2>Changelog builds after 11/11/2017:</h2>
<ul>
<li>back: Change dialer android_packages_apps_dialer to rr sources</li>
<li>snap: Camera: fix incorrect photo orientation for landscape selfie mirror shots</li>
<li>proc: Set androidboot.verifiedbootstate=green</li>
</ul>

<h2>Changelog builds after 11/05/2017:</h2>
<ul>
<li>mdss_fb: add backlight dimmer option (@flar2)</li>
<li>Change default Wallpaper to Luis ;-) (Thanks to patmo.de)</li>
</ul>

<h2>Changelog builds after 11/04/2017:</h2>
<ul>
<li>Notification slider: add extra options</li>
<li>[PATCH] oppo-common: Don't make notification slider haptics</li>
<li>Allow T9 with ru_UA locale (Dialer)</li>
<li>Change dialer sources to github.com/ROM-FIXES</li> 
</ul>
