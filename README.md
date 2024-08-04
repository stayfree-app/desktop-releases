# StayFree Desktop - MacOS, Windows, and Linux

This repo holds the release packages for the MacOS, Windows, and Linux versions of StayFree.

These desktop platforms are under heavy development right now and contain a minimal feature set. They will be expanded with the full suite of StayFree features (that our users love!) as we continue to develop them.

## Overview

For the initial release:
* **Application Tracking:** The apps currently track usage of applications on your computer. For example, if you used "Google Chrome" for 2 hours and "Visual Studio Code" for another hour, this is what will be recorded in the app.
* **Website Tracking:** As of now, website tracking within your browser is not supported. For tracking website usage, please use our browser extensions available [here](https://stayfreeapps.com).
 

### Notable Features Missing:

* **App Blocking:** The functionality to block apps is not yet implemented but will be included in future updates.
* **Cross-Platform Integration:** The desktop app currently does not integrate with our cross-platform system. This means it won't display usage data from your phone or browser extensions yet. Integration is planned for future releases.
* **App Icons:** Custom app icons are not available yet. We will add these as we better understand the usage of this version of StayFree.
* **Advanced Blocking Features:** Features like Focus Mode will be introduced in upcoming releases.
* **Enhanced UI:** Future updates will bring more in-depth statistics, comparisons, and enhanced usability to the UI.
* **Functionality Alignment:** Over time, the desktop app's functionality will closely match that of our browser extensions.

## Installing the App

### MacOS

To install StayFree on MacOS:
1. Download the appropriate package from the following links:
   * [MacOS Version (Intel)](https://github.com/stayfree-app/desktop-releases/releases/latest/download/stayfree-mac-x64.dmg)
   * [MacOS Version (Apple Silicon)](https://github.com/stayfree-app/desktop-releases/releases/latest/download/stayfree-mac-arm64.dmg)
2. Open the downloaded `.dmg` file and drag the StayFree icon to your Applications folder.
3. Launch StayFree from your Applications folder.

### Windows

To install StayFree on Windows:
1. Download the installer from [StayFree Windows Version](https://www.microsoft.com/store/apps/9N51FGRV6NHG).
2. Run the downloaded `.exe` file and follow the on-screen instructions to complete the installation.
3. After installation, you can find StayFree in your Start Menu.

### Linux

StayFree is available for Linux in two formats: AppImage and DEB. Follow the instructions for the format that suits your system.

#### Installing AppImage

1. Download the AppImage from [StayFree Linux AppImage](https://github.com/stayfree-app/desktop-releases/releases/latest/download/stayfree-linux-x86_64.AppImage).
2. Make the AppImage executable by running the following command in your terminal:

```bash
chmod +x stayfree-x.y.z.AppImage
```

3. Execute the AppImage:

```bash
./stayfree-x.y.z.AppImage
```

#### Installing DEB

1. Download the DEB package from [StayFree Linux DEB](https://github.com/stayfree-app/desktop-releases/releases/latest/download/stayfree-linux-amd64.deb).
2. Install the DEB package using the following command:

```bash
sudo dpkg -i <stayfree-x.y.z.deb> 
```

>[!note]
>the stayfree-x.y.z.deb will be dependent on the downloaded files name 

## Download Links for Other Platforms

StayFree also offers downloads for other platforms:

* **Mobile:**
  * [Android](https://play.google.com/store/search?q=screen%20time&c=apps)
  * [iOS](https://apps.apple.com/us/app/stayfree-web-stay-focused/id1631132311?itsct=apps_box_badge&amp;itscg=30200)

* **Browser Extensions:**
  * [Chrome](https://chromewebstore.google.com/detail/stayfree-website-blocker/elfaihghhjjoknimpccccmkioofjjfkf?utm_source=stayfreeapps_website)
  * [Firefox](https://addons.mozilla.org/en-US/firefox/addon/stayfree/?utm_source=stayfreeapps_website)
  * [Safari](https://apps.apple.com/us/app/stayfree-track-block-sites/id6468659272)

## Additional Information

For more details and updates about StayFree, please visit our [official website](https://stayfreeapps.com). Here, you'll find the latest news, release notes, and support resources.

Thank you for using StayFree, and we appreciate your patience as we continue to improve and expand our desktop applications!
