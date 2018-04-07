<h1>Changelog for unofficial RR-Nougat LuisROM Builds for the Oneplus 5T (dumpling)</h1>
<p></p>
<h2>Changelog builds after 04/06/2018:</h2>
<ul>
  <li>Luis: Update GCam to MGC_5.1.018_Urikill_vXXII</li>
</ul>

<h2>Changelog builds after 03/26/2018:</h2>
<ul>
<li>kernel: upstream-cm-14.1-sultan:<br>
  - kernel: Restrict unbound kthreads to little CPU cluster<br>
  - Revert "kernel: Force as many kernel tasks as possible onto CPU0"</li>
  <li>Add exfat and ntfs filesystem support</li>
</ul>

<h2>Changelog builds after 03/18/2018:</h2>
<ul>
<li>kernel: upstream-cm-14.1-sultan: (84 commits)<br>
  - qcacld-3.0: Load driver at device_initcall<br>
  - msm: mdss: Silence "invalid data for dither" error<br>
  - input: synaptics: s3320: Don't send input event timestamps to userspace<br>
  - Revert "input: add new input event code to pass timestamp to userspace"<br>
  - qcacld-3.0: Update to CAF LA.UM.5.8.r1-03300-8x98.0<br>
  - arm64: Move BP hardening to check_and_switch_context<br>
  - arm64: Add BTAC/LinkStack sanitizations for Kryo cores<br>
  - arm64: Implement branch predictor hardening for Falkor<br>
  - arch: arm64: Add midr values for kryo2xx big cores<br>
  - arm64: Implement branch predictor hardening for affected Cortex-A CPUs<br>
  - arm64: Define Cortex-A73 MIDR<br>
  - arm64: cputype: Add missing MIDR values for Cortex-A72 and Cortex-A75<br>
  - arm64: cpu_errata: Allow an erratum to be match for all revisions of a core<br>
  - arm64: Add skeleton to harden the branch predictor against aliasing attacks<br>
  - arm64: Move post_ttbr_update_workaround to C code<br>
  - drivers/firmware: Expose psci_get_version through psci_ops structure<br>
  - arm64: cpufeature: Pass capability structure to ->enable callback<br>
  - arm64: errata: Calling enable functions for CPU errata too<br>
  - mm-camera2:isp2: Handle use after free buffer<br>
  - msm: sensor: actuator: fix out of bound read for region params<br>
  ...</li>
</ul>

<h2>Changelog builds after 03/15/2018:</h2>
<ul>
  <li>Bump security patch level to 2018-03-05</li>
</ul>

<h2>Changelog builds after 03/12/2018:</h2>
<ul>
<li>Some update from LOS-14.1 framework sources:<br>
- Update tint of resource icons of third party QS tiles<br>
- SystemUI: Fix LiveDisplay tile off color  …<br>
- livedisplay: Allow tile creation before boot completed phase [2/2]  …<br>
- mtp: fix double free of thumbnail data  …<br>
- Throw OOME if Bitmap.nativeCreate fails  … <br>
- Adjust Uri host parsing to use last instead of first @.  …<br>
</li>
</ul>

<h2>Changelog builds after 03/12/2018:</h2>
<ul>
  <li>device: dumpling: Prefer CPUs 0-1 and 4-5</li>
  <li>kernel: wakeup: Create fake debugfs folder solely for wakeup_sources</li>
</ul>

<h2>Changelog builds after 03/11/2018:</h2>
<ul>
<li>kernel: Merge branch 'upstream-cm-14.1-sultan' into cm-14.1-luis  …</li>
<li>kernel: misc: goodix: Offload fb notifier onto worker  … </li>
<li>kernel: power: smb-lib: Remove unnecessary fb notifier  …</li>
<li>kernel: power: smb-lib: Fix charging issues due to incorrect intake voltage</li>
</ul>

<h2>Changelog builds after 03/09/2018:</h2>
<ul>
  <li>Update GCam to GoogleCamera-Pixel2Mod-Arnova8G2-V7beta-test</li>
  <li>Update media_profiles.xml (HEVC+SloMo GCam on OP3(T)/5)</li>
</ul>

<h2>Changelog builds after 03/05/2018:</h2>
<ul>
  <li>msm8998: add audio_amplifier for setting ANC parameter</li>
  <li>Revert "msm8998: audio: Convert audio_effect.conf to audio_effects.xml"</li>
</ul>

<h2>Changelog builds after 03/03/2018:</h2>
<ul>
  <li>kernel: power: bq27541: Restore old fuelgauge  …</li>
<li>kernel: power: Back up SOC to charger data register upon shutdown  …</li>
<li>kernel: power: bq27541: Use atomic variables to store old data  …</li>
<li>kernel: power: bq27541: Don't make 100% last longer than it should  …</li>
<li>kernel: power: Add back set_allow_reading() hooks  …</li>
<li>kernel: power: bq27541: Clean up unnecessary wrapper functions  …</li>
<li>kernel: dumpling_defconfig: Enable GSI driver for USB tethering  …</li>
<li>kernel: power: Clean up unused external oem fg functions  …</li>
<li>kernel: power: bq27541: Rewrite based on bacon bq27541 rewrite  …</li> 
<li>kernel: i2c-msm-v2: Ensure system is always active for i2c transfers  …</li> 
<li>kernel: Merge branch 'LA.UM.5.7.r1-11800-8x98.0' into cm-14.1-sultan</li>
</ul>

<h2>Changelog builds after 02/14/2018:</h2>
<ul>
  <li>Bump security patch level to 2018-02-05</li>
</ul>

<h2>Changelog builds after 02/12/2018:</h2>
<ul>
  <li>dumpling: audio: Fix typo on mmap-buffer-playback hdmi</li>
</ul>

<h2>Changelog builds after 02/09/2018:</h2>
<ul>
  <li>device/vendor: add aptX and aptX HD support</li>
  <li>device: Enable HAL3 for GCam</li>
</ul>

<h2>Changelog builds after 02/08/2018:</h2>
<ul>
  <li>kernel: disable crc check  …</li>
  <li>kernel: Added fsync on/off support.  …  </li>
</ul>

<h2>Changelog builds after 02/07/2018:</h2>
<ul>
  <li>frameworks: Add signature Spoofing permission (microG)</li>
  <li>kernel: Revert "cpufreq: Underclock performance cluster to 1958400 kHz"</li>
  <li>kernel: Declare mode and keyCode to slider (fix hardware keys)</li>
</ul>
<h2>Changelog builds after 02/05/2018:</h2>
<ul>
  <li>Initial sultanize RR Luis Build (Nougat) for Oneplus 5T (dumpling)</li>
</ul>
