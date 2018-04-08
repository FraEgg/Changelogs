<h1>Changelog Unofficial RR-Oreo LuisROM Builds for Oneplus 5T (dumpling)</h1>
<p></p>
<h2>Changelog builds after 04/08/2018:</h2>
<ul>
  <li>Add more tri-state slider options</li>
  <li>Update GCams to GoogleCamera-Pixel2Mod-Arnova8G2-V7-test-10-Op5-5t</li>
  <li>Add rounded corners in UI and Recents</li> 
  <li>Add OnePlusCameraService</li>
</ul>

<h2>Changelog builds after 04/06/2018:</h2>
<ul>
  <li>Luis: Update GCam to MGC_5.1.018_Urikill_vXXII</li>
</ul>

<h2>Changelog builds after 04/05/2018:</h2>
<ul>
  <li>Luis: Change kernel cross compiler to GCC 7.2.1</li>
</ul>

<h2>Changelog builds after 03/28/2018:</h2>
<ul>
  <li>frameworks: fix google assistant scripts</li>
</ul>

<h2>Changelog builds after 03/26/2018:</h2>
<ul>
  <li>msm8998: configs: move perfboostsconfig and powerhint to blobs  …</li>
    <li>kernel: add exfat and ntfs filesystem support</li>
</ul>

<h2>Changelog builds after 03/25/2018:</h2>
<ul>
  <li>frameworks: Add signature Spoofing permission (microG) …</li>
  <li>frameworks: telephony: Hack GSM and LTE signal strength  …</li>
  <li>frameworks: Allow location providers also outside of /system.  …</li>
  <li>frameworks: Add German translation for Dash Charging.  …</li>
</ul>
  
<h2>Changelog builds after 03/15/2018:</h2>
<ul>
  <li>kernel: switch kernelbase to francokernel (https://github.com/franciscofranco/OP5-5T-unified)</li>
</ul>

<h2>Changelog builds after 03/14/2018:</h2>
<ul>
  <li>vendor: msm8998: update lobs from OP5 beta6 / OP5T beta4</li>
  <li>msm8998: audio_tuning_mixer.txt is device specific</li>
</ul>

<h2>Changelog builds after 03/12/2018:</h2>
<ul>
<li>msm8998: sync WCNSS_qcom_cfg.ini with caf  …</li>
<li>msm8998-common: Add blobs needed for widevine L1 support  …</li>
<li>msm8998: camera: add com.android.camera and snap to aux.packagelist  …</li>
<li>msm8998: nfc: move to configs  …</li>
<li>msm8998: unpin camera config  …</li>  
  <li>kernel: upstream-fk-8.x-unified: (38 commits)<br>
  Linux 4.4.121<br>
  btrfs: preserve i_mode if __btrfs_set_acl() fails<br>
  bpf, x64: implement retpoline for tail call<br>
  dm io: fix duplicate bio completion due to missing ref count<br>
  mpls, nospec: Sanitize array index in mpls_label_ok()<br>
  net: mpls: Pull common label check into helper<br>
  sctp: verify size of a new chunk in _sctp_make_chunk()<br>
  s390/qeth: fix IPA command submission race<br>
  s390/qeth: fix SETIP command handling<br>
  sctp: fix dst refcnt leak in sctp_v6_get_dst()<br>
  sctp: fix dst refcnt leak in sctp_v4_get_dst<br>
  udplite: fix partial checksum initialization<br>
  ppp: prevent unregistered channels from connecting to PPP units<br>
  netlink: ensure to loop over all netns in genlmsg_multicast_allns()<br>
  net: ipv4: don't allow setting net.ipv4.route.min_pmtu below 68<br>
  net: fix race on decreasing number of TX queues<br>
  ipv6 sit: work around bogus gcc-8 -Wrestrict warning<br>
  hdlc_ppp: carrier detect ok, don't turn off negotiation<br>
  fib_semantics: Don't match route with mismatching tclassid<br>
  bridge: check brport attr show in brport_show<br>
  ...</li>
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

<h2>Changelog builds after 03/04/2018:</h2>
<ul>
  <li>Merge kernel branch 'upstream-fk-8.x-unified' into oreo-luis</li>
  </li>upstream-fk-8.x-unified: (47 commits)<br>
  ANDROID: keychord: Check for write data size<br>
  Linux 4.4.120<br>
  MIPS: Implement multi3 for GCC7 MIPS64r6 builds<br>
  net: gianfar_ptp: move set_fipers() to spinlock protecting area<br>
  sctp: make use of pre-calculated len<br>
  xen/gntdev: Fix partial gntdev_mmap() cleanup<br>
  xen/gntdev: Fix off-by-one error when unmapping with holes<br>
  SolutionEngine771x: fix Ether platform data<br>
  mdio-sun4i: Fix a memory leak<br>
  xen-netfront: enable device after manual module load<br>
  bnxt_en: Fix the 'Invalid VF' id check in bnxt_vf_ndo_prep routine.<br>
  can: flex_can: Correct the checking for frame length in flexcan_start_xmit()<br>
  mac80211: mesh: drop frames appearing to be from us<br>
  drm/ttm: check the return value of kzalloc<br>
  e1000: fix disabling already-disabled warning<br>
  xfs: quota: check result of register_shrinker()<br>
  xfs: quota: fix missed destroy of qi_tree_lock<br>
  IB/ipoib: Fix race condition in neigh creation<br>
  IB/mlx4: Fix mlx4_ib_alloc_mr error flow<br>
  s390/dasd: fix wrongly assigned configuration data<br>
  ...</li>
</ul>

<h2>Changelog builds after 03/03/2018:</h2>
<ul>
  <li>common: msm8998-common: Increase media volume steps 15 -> 25  …</li>
<li>common: msm8998: audio: fix acdb id of handset mic  …</li>
<li>common: msm8998: audio: fix acdb id of handset stereo mic  …</li>
<li>common: msm8998: audio: fix acdb id for handset  …</li>
<li>common: msm8998: DPM : Add radio group rules to dpmQmiMgr  …</li>
<li>common: msm8998: init: performance: set up boot time fs tuning  …</li>
<li>common: msm8998: init: performance: disable UFS powersaving while booting up  …</li>
<li>common: msm8998: init: performance: enable powersaving when in charger mode  …</li>
<li>common: msm8998: init: move charger perf config to init.target.performance.rc  …</li>
<li>common: msm8998: ueventd: set permissions for FRP config partition  …  </li>
<li>common: msm8998: commonize dalvik and hwui prop overrides  …</li>
</ul>

<h2>Changelog builds after 02/27/2018:</h2>
<ul>
<li>Update GoogleCamera to Google Camera Mod 5.1.018 v3.0 Full Auto by SKULSHADY</li>
</ul>

<h2>Changelog builds after 02/25/2018:</h2>
<ul>
  <li>vendor: Add front gcam portrait fix from Defcomg (SavitarZA)</li>
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

<h2>Changelog builds and kernel release after 02/21/2019:</h2>
<ul>
  <li>msm8998: use OP aptx and ldac blobs  …</li>
  <li>msm8998: define second back camera as back and back_aux  …</li>
  <li>msm8998: add missing vstab configs  …</li>
</ul>
  
<h2>Changelog builds and kernel release after 02/19/2019:</h2>
<ul>
<li>kernel: boeffla_wl_blocker: update to wakelock blocker driver v1.1.0  …</li>
</ul>

<h2>Changelog builds after 02/19/2018:</h2>
<ul>
  <li>kernel: misc: goodix: enable nav events …</li>
  <li>device: Add Google Camera (GCam5.1.018-Arnova8G2-V1.6)</li>
  <li>device: Add Oneplus Camera 2.5.21 (OP5)</li>
  <li>device: Add Oneplus Gallery 2.0.47 (OP5)</li>
</ul>

<h2>Changelog builds after 02/18/2018:</h2>
<b>First public beta build</b><br>
Custom kernel features:<br>
<ul>
<li>block: add zen scheduler</li>
<li>optional: cpufreq: Underclock performance cluster to 1958400 kHz  … (powersave LuisKERNEL)</li>
<li>display: add a simple api to query the display state (on/off) at any.</li>
<li>leds-qpnp: Notification LED control - V1.1c</li>
<li>mdss_fb: add backlight dimmer option</li>
<li>block: add zen scheduler</li>
<li>Add SIO and FIOPS i/o schedulers  …</li>
<li>ASoC: msm: qdsp6v2: Add simple API to check if a voice call is active  …</li>
<li>kernel: enable msm kernel protect</li>
<li>net/wireguard: add wireguard importer  …</li>
<li>disable crc check  …</li>
<li>Added fsync on/off support.  …</li>
<li>ASoC: wcd9335: add earpiece and mic gain, prevent headphone reset</li>
<li>ASoC: wcd9335: Sound control</li>
<li>workqueue: Schedule workers on CPU0 or 0-3 by default  …</li>
<li>ARM: dts: msm8998: Configure msm-thermal-simple device  …</li>
<li>cpu_input_boost: Add support for msm8998  …</li>
<li>power: msm-core: Compile out temperature polling  …</li>
<li>misc: goodix: Disable nav events  …</li>
<li>and other tweaks...</li>
</ul>
