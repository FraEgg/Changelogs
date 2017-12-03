<h1>Changelog RR Luis-Builds Xiaomi Redmi 4x (santoni)</h1>
<p></p>
h2>Changelog builds after 12/03/2017:</h2>
<ul>
<li>Change to MIUICamera.apk V1.5 from pavaosk@xda Thread: https://forum.xda-developers.com/xiaomi-redmi-4x/themes/camera-mod-miui-camera-added-features-t3713989</li>
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
