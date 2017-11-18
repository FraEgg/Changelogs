<h1>Changelog RR-Luis-Builds Oneplus 3/3T</h1>
<p></p>
<h2>Changelog builds after 11/18/2017:</h2>
<ul>
  <li>kernel: Sinput: synaptics: Ignore keypad presses when touchscreen is in use...</li>
  <li>kernel: Squashed revert of buggy and clunky is_keypad_stopped feature... </li>
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
