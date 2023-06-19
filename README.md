This simulation is to be used with Felis Leopard's Boeing 747-200 Classic, located here: https://store.x-plane.org/Boeing-747-200-Classic_p_1491.html
The 747-200 classic cockpit is essentially identical to the 747-100, and the 747sr. The exterior of the aircraft is not painted, or modified to exhibit JAL123's external damage. 

----

Before running the simulations:

- Each simulation needs to be run on a freshly-opened instance of X-Plane 11. Otherwise glitches with the gauges may occur.

- The directory structure of X-Plane 11 should be followed. This has been replicated in the .zip file for ease of doing so. In addition, the directory and filename of the aircraft should be as follows: (X-Plane 11 directory)/Aircraft/Extra Aircraft/747 Felis 1.2.0.7.1/B742_PW_Felis.acf

- This scenario has been tested with version 1.2.0.7.1 of the 747-200 classic, the latest version. Other versions likely should work, but are not guaranteed to do so. If you do use a different version, the directory/file reference will need to be updated for the .acf file on Cell B13 on each of the .fdr files (Line 13, after the second comma if editing in a text editor).

- Any addon which uses the Throttle levers, such as X-Multithrottle, will need to be disabled.

- The following addons are also known to have issues, and should be removed: X-Camera, xPilot, LiveTraffic, Gizmo64. X-Camera and Gizmo64 are known to cause crashes to desktop. xPilot, and LiveTraffic both cause the time to shift forward abnormally quickly in FDR playback.

- The following LUA scripts are known to have issues, and should be removed: shadows_fix.lua 

- This scenario requires the FlyWithLua addon in order to run the LUA script files for controlling cockpit animations. Descriptions of those files are included in "LUA script file descriptions.txt".

- Two of the aircraft cockpit files will need to be modified in order to properly display altimeter data on the Captain's altimeter, And the heading on the overhead compass. Details to do this are located in the "Editing Felis cockpit files.txt" file. I am uncertain if including the files and having one replace it will mess with the licensing validation, so it is better to edit them yourself, and create a backup beforehand.

----

Before allowing each simulation to run past the included scenery loading time buffers (90 seconds before the start of the actual data), it is recommended to do the following:

- Turn off any features that you don't wish to have included in your simulation, such as the mounted iPads (they didn't have those in 1985, after all).

- Changing any of the myriad number of lights that are included in the aircraft cockpit to suit your visual needs.

- The parking brake is also automatically set, and that should be turned off.

- Clicking the "Instrument Warn" button will stop it from blinking.

- It is also adviseable to mute sound from X-Plane 11. The takeoff warning/cabin altitude alert continuously goes off, which I was unable to remedy. While it is, ironically, appropriate for this specific scenario, you may wish to mute X-Plane due to this.

----

While running the sim:

- If, upon running the FDR simulation, you see that the rudder pedals are moving back and forth in tandem with control wheel motion, that is actually indicative that X-Plane is controlling the rudder pedal position relative to the control wheel position, a feature known as "Auto rudder". Apparently, the only way to disable this is to ensure that the yaw inputs are assigned to an axis on a joystick/keyboard/other controller. The actual rudder pedal data shows it was predominately held to the left, indicating the pilots may have been using it to brace themselves against the Dutch Rolling motions.

- Control input data for control column position and rudder pedal position becomes unreadable at approximately 55:10. As such, any motion for those two animations stops at that time. There is a second page of graphs for after that time frame in which the investigation team attempted data correction, but data for those two parameters seems far too scattered to be realistic. I was able to salvage what I believe is a reasonable record of the control wheel angle.
