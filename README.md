
## TWRP device tree for Galaxy J3 Unlocked (2017)

Add to `.repo/local_manifests/j3popelteue.xml`:


<?xml version="1.0" encoding="UTF-8"?>
<manifest>
	<project path="device/samsung/j3popelteue" name="android_device_samsung_j3popelteue" remote="TeamWin" revision="android-6.0" />
</manifest>


Then run `repo sync` to check it out.

To build:

` . build/en* `
` lunch omni_j3popelteue-eng `
` make -j5 recoveryimage 

