# Create-with-VR-Workshop
Workshop project and materials for getting started with VR development in Unity

For where I got the lesson plan material from [Unity Learn's Create with VR Course](https://learn.unity.com/course/create-with-vr)
Environment Assets from [JustCreate](https://assetstore.unity.com/publishers/44390) free packages, see [License](License) Below. 
  
## Getting Started

### Dependencies and version numbers

+ Unity version: >= 2021.3.16f1
  + Requires Android build system, see [this document for install process](https://docs.unity3d.com/Manual/android-sdksetup.html)
+ XR Plugin Management >= 4.2.1, Released Jan 5,2022
+ XR Interaction Toolkit >= 2.0.4, Released Nov 3, 2022
+ Oculus Integration Version: >= 49.0, Released Feb 7, 2023

### Downloading the project

+ Download this project repository to your local machine using *one* of the following methods:
  + Git clone the repository with `git clone https://github.com/XRRCA/Create-with-VR-Workshop.git`
  + Download the `create-with-vr-workshop.unitypackage` file [here](https://github.com/XRRCA/Create-with-VR-Workshop/raw/main/create-with-vr-workshop.unitypackage).
 
### Set up scene

+ In the Unity taskbar go `Assets` -> `Import Package` -> `Custom Package` then find where you saved `create-with-vr-workshop.unitypackage` and `Import All`.
+ Then open the scene at `Assets/Scenes/create_vr_with_unity_scene.unity` in the `Project` window.

  
### Using Meta (Oculus) Quest 2

+ Put your device in Developer Mode:
Follow the instructions on [Device Setup from the Oculus Developer page](https://developer.oculus.com/documentation/native/android/mobile-device-setup/) to put your device in Developer Mode.
This will allow you to do testing and development on your device.

#### Connect your device to your computer through Oculus Link (Windows only):
+ From the [Oculus Link Setup page](https://www.oculus.com/accessories/oculus-link/), follow the instructions to connect your device to your computer.
+ You will need to connect your device with a compatible cable and download the Oculus software.
+ If you have completed this step successfully, your device should be recognized and connected within the Oculus desktop app.

<img src="https://connect-prd-cdn.unity.com/20210316/learn/images/cdb1eb13-c9df-4b03-b637-79fdda9d66fb_0.1_4.jpg.2000x0x1.jpg" width="500">


#### Set up Quest for Android Development

+ Make sure the Android Development Modules are installed in the Unity Hub for your specific editor
+ Install [Oculus ADB Drivers](https://developer.oculus.com/downloads/package/oculus-adb-drivers/?locale=en_GB)
+ To build app for Android, go to `Build Settings` and switch platform to Android: 
  + You can either `Build and Run` or `Patch and Run`
  + To deploy `.apk` to your headset you can use [Meta Quest Developer Hub](https://developer.oculus.com/documentation/unity/ts-odh/?locale=en_GB) or [ADB Commands in Shell](https://developer.oculus.com/documentation/native/android/ts-adb/#mobile-android-debug-intro)


#### Using HTC, Valve or other [OpenXR](https://www.khronos.org/openxr/) Devices

+ Install [Steam](http://store.steampowered.com/about) and [SteamVR](https://store.steampowered.com/app/250820/SteamVR/).
+ plug in headset into your computer and make sure its linked and recognized by SteamVR.

<img src="https://connect-prd-cdn.unity.com/20210316/learn/images/247e9360-ac92-411b-9b11-442f75d06b39_0.1_5.jpg.1000x0x1.jpg" width=500>


## License

Code released under the [MIT License][License]. Check other integrations licenses.

JustCreate Assets used under the [Standard Unity Asset Store EULA](https://unity.com/legal/as-terms).

## Disclaimer

These materials are not sponsored by or affiliated with Unity Technologies or its affiliates. "Unity" is a trademark or registered trademark of Unity Technologies or its affiliates in the U.S. and elsewhere.

[Unity]: https://unity3d.com/
[License]: LICENSE.md
[Unity Hub]: https://docs.unity3d.com/Manual/GettingStartedUnityHub.html
