# android-minimal
Have you ever scrolled through list of all applications you have installed on your Android device? Were you ever curios why there are around 100 system apps preinstalled on new device? What do they do? Are they necessary?
Here I am creating list of which system packages can be safely deleted, which are critical for system to function and which just break something. This data can be used to create "minimal fast Android super small build" with minimul of system apps installed.

For testing I am using Android x86 9.0 rc2 virtual machine, that was the most "generic" Android version. Keep in mind that If you are trying to perform same deletion actions on real hardware with different Android version the results may vary. Also most of manufacturers like to include thier own special apps which I can't test due to obvious reason.

GOALS

Main goal of this project is to map system packages and classify them, so there is possiblity of safely shrinking modern Android installation size to bare system.
Of course this requires some sacrifices, here main sacrifice is entire Google subsystem which is obviously (maybe this is not that obvious) not need for system to run.
