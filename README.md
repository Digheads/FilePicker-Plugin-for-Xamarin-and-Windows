## FilePicker-Plugin-for-Xamarin-and-Windows
FilePicker Plugin for Xamarin and Windows

Simple cross-platform plug-in that allows Pick files, save files and open the archive application standards.

### Setup

* Available on NuGet: [FilePicker Nuget](https://www.nuget.org/packages/Xam.Plugin.FilePicker)
* Install into your PCL project and Client projects.

**Platform Support**

|Platform|Supported|Version|
| ------------------- | :-----------: | :------------------: |
|Xamarin.iOS|Yes|iOS 6+|
|Xamarin.iOS Unified|Yes|iOS 6+|
|Xamarin.Android|Yes|API 10+|
|Windows Phone Silverlight|NO||
|Windows Phone RT|Yes|8.1+|
|Windows Store RT|Yes|8.1+|
|Windows 10 UWP|Yes|10+|
|Xamarin.Mac|No||

### API Usage

Call **CrossFilePicker.Current** from any project or PCL to gain access to APIs.

### **IMPORTANT**
**Android:**
The `WRITE_EXTERNAL_STORAGE` & `READ_EXTERNAL_STORAGE` permissions are required.

**iOS:** 
Need [Configure iCloud Driver for your app](https://developer.xamarin.com/guides/ios/platform_features/intro_to_cloudkit)

#### Contributors
* [rafaelrmou](https://github.com/rafaelrmou)
 
Thanks!

#### License
Licensed under main repo license
