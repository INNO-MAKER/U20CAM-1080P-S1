## U20CAM-1080P-S1 Trouble Shooting:



Q1： Why is the test rate not reaching 30 frames on my computer or device, and the displayed actual frame rate is slightly lower than the real frame rate?

A1:   

(1) **Insufficient USB port bandwidth or power supply**: If the USB port bandwidth or power supply is inadequate, it can affect the device's performance. Plug the camera module directly into the computer's USB port to avoid sharing bandwidth with other devices, or use a USB hub with external power supply. Try plugging into a USB 3.0 port, as these ports typically offer stronger driving capabilities.

(2)**Insufficient CPU/MPU/GPU/RAM performance**: This issue is common with o8lder computers or ARM development boards. Older hardware may struggle to process image data quickly, causing the frame rate to fall short. Consider upgrading the hardware platform or reducing the resolution to alleviate the system's load.

(3)**Driver or testing software issues**: This is less common, but if the first two causes are ruled out and the issue persists, consider updating the UVC drivers or switching to another testing software.



Q2： Why does the U20CAM-1080P-S1 experience overexposure, resulting in a completely white image, when used in strong outdoor light?

A2: The camera was initially designed to better support various operating modes, which led to suboptimal exposure adjustments for outdoor use. A temporary solution is to disable the auto exposure option in the software when using it outdoors, and manually adjust the exposure to an appropriate level. We expect to release a new version in November 2025 (with no hardware changes), which will optimize and better accommodate both indoor and outdoor lighting conditions.

Q3：The PCBA has reserved silkscreen for infrared LEDs and infrared diodes. Can I solder and add the infrared function myself?

A3: The PCB does indeed have a reserved design for the night vision version. However, in addition to soldering the infrared LEDs, users would also need to replace the lens with one that has an IR-CUT filter. Currently, we have released other series of night vision cameras with IR-CUT filters that can be purchased on Amazon directly. Therefore, we do not recommend that customers solder the infrared LEDs or replace the lens with an IR-CUT filter themselves. Since this camera module has already passed CE, FCC, and UKCA certifications, we will not be changing its PCB shape, and will continue to retain the pads for the infrared LEDs and IR-CUT filter, which will not affect normal usage.

Link: https://github.com/INNO-MAKER/U20CAM-1080PD-N-S1
