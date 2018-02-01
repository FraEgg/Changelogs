<h1>Changelog RR Luis-Builds Samsung Galaxy Tab S (T700/705/800/805) and Samsung Galaxy Note 2014 Edition (P600)</h1>
<p></p>
<h2>Changelog builds after 02/01/2018:</h2>
<ul>
  <li>Update weather provider apks</li>
</ul>

<h2>Changelog builds after 01/29/2018:</h2>
<ul>
<li>chagallwifi: Revert some device commits (fix wifi issue)</li>
</ul>

<h2>Changelog builds after 01/27/2018:</h2>
<ul>
<li>chagalllte: CONFIG_SECURITY_SELINUX_DEVELOP is not set (selinux enforcing)</li>
<li>v1awifi: Kernel Enforcing  …</li>
<li>fs/exec: fix use after free in execve</li>
<li>ALSA: compress_core: integer overflow in snd_compr_allocate_buffer() …</li>
<li>ALSA: compress - move the buffer check</li>
<li>ALSA: compress: fix an integer overflow check</li>
<li>net: wireless: bcmdhd: fix buffer overrun in private command path</li>
<li>ext4: fix condition of validate s_first_meta_bg  …</li>
</ul>

<h2>Changelog builds after 01/26/2018:</h2>
<ul>
<li>exynos5420-common: Add AptX blobs</li>
<li>exynos5420-common: enable AptXHD</li>
<li>exynos5420-common: enable OLED burnIn protection support</li>
<li>Don't seclabel sswap</li>
<li>Remove useless property sets</li>
<li>power: adjust the header for the new dynamic cluster configuration</li>
vinit: disable touchscreen and touchkey input boosters</li>
<li>exynos5420: enable variable touchkey brightness support</li>
<li>sepolicy: address a gpsd denial</li>
<li>exynos5420-common: Disable BOARD_CHARGER_ENABLE_SUSPEND</li>
<li>selinux: handle some denials</li>
<li>Revert "GPU: set 533mhz as the default max gpu clock"</li>
<li>system_props: Enable sdcardfs</li>
<li>sepolicy: Fix exFAT permissions</li>
<li>sepolicy: Update debugfs rules</li>
<li>proprietary-files: Update widevine</li>
<li>Use modified open source camera wrapper [1/2]</li>
<li>SamsungPowerHAL: do not define CPU4 node paths</li>
<li>Revert "net: wireless: bcmdhd: fix buffer overrun in private command path buffer overrun case found when length parameter manipulated."</li>
<li>ipv6: fix out of bound writes in __ip6_append_data()</li>
<li>BACKPORT: ipv6/dccp: do not inherit ipv6_mc_list from parent Like commit 657831ffc38e ("dccp/tcp: do not inherit mc_list from parent") we should clear ipv6_mc_list etc. for IPv6 sockets too.</li>
<li>BACKPORT: sctp: do not inherit ipv6_{mc|ac|fl}_list from parent SCTP needs fixes similar to 83eaddab4378 ("ipv6/dccp: do not inherit ipv6_mc_list from parent"), otherwise bad things can happen.</li>
<li>ipv6: Check ip6_find_1stfragopt() return value properly.</li>
<li>ipv6: Prevent overrun when parsing v6 header options</li>
<li>unix: correctly track in-flight fds in sending process user_struct</li>
<li>unix: properly account for FDs passed over unix sockets</li>
<li>ext4: fix fencepost in s_first_meta_bg validation</li>
<li>ext4: fix condition of validate s_first_meta_bg</li>
<li>dccp/tcp: do not inherit mc_list from parent</li>
<li>ping: implement proper locking</li>
<li>selinux: fix off-by-one in setprocattr</li>
<li>fs/exec.c: account for argv/envp pointers</li>
<li>BACKPORT: fiq_debugger: restrict access to critical commands.</li>
<li>sctp: validate chunk len before actually using it</li>
<li>net: wireless: bcmdhd: fix buffer overrun in private command path buffer overrun case found when length parameter manipulated.</li>
<li>arm: oabi compat: add missing access checks</li>
<li>kernel: Restrict permissions of /proc/iomem.</li>
<li>ALSA: compress: fix an integer overflow check<br>
...</li>
</ul>

<h2>Changelog builds after 01/23/2018:</h2>
<ul>
 <li>Add AptXHD for all exynos 5420 devices</li>
</ul>

<h2>Changelog builds after 01/22/2018:</h2>
<ul>
<li>Android: Update Security patch level 2018-01-05</li>
</ul>

<h2>Changelog builds 01/17/2018:</h2>
<ul>
<li>bt: add AptX blobs from OnePlus3t OxygenOS OpenBeta 5</li>
</ul>

<h2>Changelog builds 01/13/2018:</h2>
<ul>
 <li>device: Fix Miracast & Cast</li>
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

<h2>Changelog builds after 12/06/2017:</h2>
<ul>
 <li>Add Wireguard VPN ROM support</li>
 <li>Kernel: wacom: Report KEY_WAKEUP on s-pen removal</li>
 <li>Pie: Fix FC after reboot with french language  …</li>
 <li>Fix systemUI FC when using the Language QS tile</li>
</ul>

<h2>Changelog builds after 12/03/2017:</h2>
<ul>
<li>Update RR-Changelog to v5.8.5</li>
<li>Update Magisk to v14.5 (optional)  …</li>
<li>Update include method for prebuilt apks  …</li>
<li>prebuilt: Update included apk's to latest versions</li>
</ul>

<h2>Changelog builds after 11/28/2017:</h2>
<ul>
  <li>device: Fix/Add weather providers</li>
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

<h2>Changelog builds after 11/11/2017: (T705/T805)</h2>
<ul>
<li>back: Change dialer android_packages_apps_dialer to rr sources</li>
</ul>

<h2>Changelog builds after 11/05/2017:</h2>
<ul>
<li>Change default Wallpaper to Luis ;-) (Thanks to patmo.de)</li>
</ul>

<h2>Changelog builds after 11/02/2017 (T705/T805):</h2>
<ul>
<li>Allow T9 with ru_UA locale (Dialer)
<li>Change dialer sources to github.com/ROM-FIXES 
</ul>

<h2>Commits for Builds from 10/15/2017:</h2>
<ul>
<li>Remove wakelocks from LockClock widget (reduce battery drain)</li>
</ul>

<h2>Commits for Builds from Oct 03,2017</h2>
<ul>
<li>Downloads moved to http://luis-builds.de/downloads/lineageos/rr/</li>
</ul>

<h2>Commits for Builds from Sep 30,2017</h2>
<ul>
<li>Support signature spoofing (microG/GmsCore)</li>
</ul>

<h2>Commits for Builds from Sep 29, 2017</h2>
<ul>
<li>Enable burn in protection  …</li>
<li>v4l2: Implement exynos_v4l2_prepare  …</li>
<li>videocodec: Support recent MFC hardware  …</li>
</ul>

<h2>Commits for Builds from Aug 21, 2017</h2>
<ul>
<li>Increase volume for the build-in mics from 17/32 to 32/48 in device settings (mixer_paths.xml)</li>
</ul>

<h2>Commits for Builds from Aug 18, 2017</h2>
<ul>
<li>Merge pull request #11 from exynos5420/cm-14.1  …</li>
<li>fs/exec: fix use after free in execve  …</li>
</ul>
