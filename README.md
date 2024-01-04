# Unity-VR-Workshop-2021
Workshop project and materials for getting started with VR development in Unity

Template is from [Unity Learn's Create with VR Course](https://learn.unity.com/course/create-with-vr)
  
  ## Getting Started

### Dependencies and version numbers

+ Unity version: >= 2021.3.16f1
  + Requires Android build system, see [this document for install process](https://docs.unity3d.com/Manual/android-sdksetup.html)
+ XR Plugin Management >= 4.2.1, Released Jan 5,2022
+ XR Interaction Toolkit >= 2.0.4, Released Nov 3, 2022
+ Oculus Integration Version: >= 49.0, Released Feb 7, 2023

### Downloading the project

* Download this project repository to your local machine using *one* of the following methods:
  * Git clone the repository with `git clone https://github.com/VizRCA/Template-VRTK_OculusGoQuest.git`
  * Download the zip file using the button above and **extract it**.
  
### Setting up the hardware

* This learning content is fully verified with Meta Quest model headsets.
* You can use any other headsets that support OpenXR, including the Valve Index, HTC Vive, and Windows Mixed Reality Headsets, but you are more likely to encounter obstacles along the way. Everything should function properly, but the learning content has not been fully tested and verified on these devices.
> Note: If you do not have access to a VR headset, you can still benefit from this course, but your ability to fully test the VR experience will be somewhat limited.

#### Using Meta (Oculus) Quest 2

* Put your device in Developer Mode:
Follow the instructions on [Device Setup from the Oculus Developer page](https://developer.oculus.com/documentation/native/android/mobile-device-setup/) to put your device in Developer Mode.
This will allow you to do testing and development on your device.

* Connect your device to your computer through Oculus Link (Windows only):
  * If you are using a Mac, skip this step. The Oculus software is currently only compatible with Windows.
* From the [Oculus Link Setup page](https://www.oculus.com/accessories/oculus-link/), follow the instructions to connect your device to your computer.
  * You will need to connect your device with a compatible cable and download the Oculus software.
* If you have completed this step successfully, your device should be recognized and connected within the Oculus desktop app.

<img src="https://connect-prd-cdn.unity.com/20210316/learn/images/cdb1eb13-c9df-4b03-b637-79fdda9d66fb_0.1_4.jpg.2000x0x1.jpg" width="500">


##### Set up Quest for Android Development

* Make sure the Android Development Modules are installed in the Unity Hub for your specific editor
* Install [Oculus ADB Drivers](https://developer.oculus.com/downloads/package/oculus-adb-drivers/?locale=en_GB)
* To build app for Android, go to `Build Settings` and switch platform to Android: 
  * You can either `Build and Run` or `Patch and Run`
  * To deploy `.apk` to your headset you can use [Meta Quest Developer Hub](https://developer.oculus.com/documentation/unity/ts-odh/?locale=en_GB) or [ADB Commands in Shell](https://developer.oculus.com/documentation/native/android/ts-adb/#mobile-android-debug-intro)


#### Using HTC, Valve or other [OpenXR](https://www.khronos.org/openxr/) Devices

* Install [Steam](http://store.steampowered.com/about) and [SteamVR](https://store.steampowered.com/app/250820/SteamVR/).
* plug in headset into your computer and make sure its linked and recognized by SteamVR.

<img src="https://connect-prd-cdn.unity.com/20210316/learn/images/247e9360-ac92-411b-9b11-442f75d06b39_0.1_5.jpg.1000x0x1.jpg" width=500>




### Opening the downloaded project in the Unity software

> *Do not* drag and drop the project download into an existing Unity project. The repository download *is a Unity project* already and you should not nest a Unity project inside another Unity project. Follow the instructions below to open the Unity project.

#### Using the Unity Hub

* Open the [Unity Hub] panel.
* Click the `Add` Button:
* Browse to the local directory where the repository was downloaded to and click `Select Folder`:
* The Template project will now show up in the Unity Hub project window, so select it to open the Unity project in the Unity software:
* The Template project will now open within the Unity software.

#### Opening from within the Unity software

* Select `Main Menu -> File -> Open Project` within the Unity software.
* Browse to the local directory where the repository was downloaded to and click `Select Folder`.
* The Template project will now open within the Unity software.


## License

Code released under the [MIT License][License]. Check other integrations licenses.

## Disclaimer

These materials are not sponsored by or affiliated with Unity Technologies or its affiliates. "Unity" is a trademark or registered trademark of Unity Technologies or its affiliates in the U.S. and elsewhere.

[Unity]: https://unity3d.com/
[License]: LICENSE.md
[Unity Hub]: https://docs.unity3d.com/Manual/GettingStartedUnityHub.html
