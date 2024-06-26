---
title: Managing Failed App Verifications in Windows OS
date: 2024-06-25T09:47:21.149Z
updated: 2024-06-26T09:47:21.149Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Managing Failed App Verifications in Windows OS
excerpt: This Article Describes Managing Failed App Verifications in Windows OS
keywords: Windows App Fail Checks,Fixing Unverified App Errors,Troubleshoot OS App Rejections,Verification Issue Solutions,Manage Windows App Failures,Resolve Failed App Confirmations,Windows OS Verification Fixes
thumbnail: https://thmb.techidaily.com/9506d7bd2cecec98495cc03f8d004c03b0c85881c0a7db857ddbaa57f04d4e15.jpg
---

## Managing Failed App Verifications in Windows OS

 Have you encountered the error"the app you're trying to install isn't a Microsoft-verified app"while installing an app? The error occurs if you have configured your system to only install apps from the Microsoft Store. You could have set this permission on purpose, or it might have been set by default.

 Other than that, a corrupted Microsoft Store cache, installing an app from an unofficial source, and enabling Windows S mode can also cause the error. Below, you will find a few checks and fixes you should apply to resolve the error and install the app successfully.

## 1\. Install the App From the Microsoft Store

 Considering you get the error when downloading apps outside the Microsoft Store, it makes sense to first check if the same app is available there. If the app is available, you can download it from there, and there won't be any need to go through advanced troubleshooting.

 Therefore, [open the Microsoft Store](https://www.makeuseof.com/windows-open-microsoft-store/) and search for the app. If you find the app in the store, click the **Get** button to install it. However, if the app isn't available in the store and can only be downloaded from another source, ensure it is safe to download.

## 2\. Make Sure the App You're Downloading Is Safe

 Microsoft doesn't allow untrusted publishers to list their apps on the Microsoft Store. If you haven't found the app on the store, it could be unsafe and infect your computer. Thus, ensure that the app you want to download is secure before downloading.

 To determine if an app is safe, copy its download link and paste it into [VirusTotal's URL search box](https://www.virustotal.com/gui/home/url). After that, press **Enter**.

![Check the Authenticity of a Software by Entering its URL in VirusTotal’s Official Website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/1-check-the-authenticity-of-a-software-by-entering-its-url-in-virustotal-s-official-website.jpg)

 If the scanner doesn't find any problems with the download link, it's probably safe. After ensuring that, you can apply the remaining fixes to enable app installation outside the store.

## 3\. Change the Operating System App Settings

 Microsoft cares about the safety and security of its Windows users. To facilitate that, Windows offers a feature that blocks the installation of apps outside the Microsoft Store. The downside of enabling this feature is that it prevents users from installing popular and safe applications from the web.

 When users try to install an app with this restriction turned on, Windows will likely display an error message saying that the app isn't a Microsoft-verified app. Therefore, to avoid encountering the error described above, you should allow Windows to install apps outside the Microsoft Store.

 To modify the app permissions on Windows 10, follow the steps below:

1. Open the **Settings** app.
2. Open **Apps** settings and select **Apps and Features** from the left sidebar.
3. Select **Anywhere** from the dropdown menu under **Choose where to get apps**.

 To modify app permissions on Windows 11, open the **Settings** app, select the **Apps** tab, and then go to **Advanced app settings**.

![Go to Advanced Apps Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/2-go-to-advanced-apps-settings-in-windows-settings-app.jpg)

 Select **Anywhere** from the dropdown menu next to **Choose where to get apps**.

![Select Anywhere From the Dropdown Menu Next to Choose Where to Get Apps Option in Apps Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/3-select-anywhere-from-the-dropdown-menu-next-to-choose-where-to-get-apps-option-in-apps-settings-in-windows-settings-app.jpg)

## 4\. Turn Off the App Install Control Policy

 The App Install Control is a Microsoft Defender SmartScreen feature that prevents users from installing apps outside the Microsoft Store. It does this to prevent users from infecting their devices with third-party applications.

 Therefore, you should turn off this feature to remove any restrictions. To turn it off, follow these steps:

1. Open the Local Group Policy Editor. To do this, check out[how to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) if you're not using Windows Home edition, and learn [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) if you are.
2. Navigate to **Computer Configuration > Administrative Templates > Windows Components > Windows Defender SmartScreen > Explorer**.  
![Go to Explorer Folder by Navigating to the Path in Windows Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/4-go-to-explorer-folder-by-navigating-to-the-path-in-windows-local-group-policy-editor.jpg)
3. Open the policy for **Configure App Install Control**.
4. Select **Disabled** to turn off this feature.  
![Disable the Policy for Configure App Install Control in Windows Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/5-disable-the-policy-for-configure-app-install-control-in-windows-local-group-policy-editor.jpg)

## 5\. Change the App Install Control Permission in the Registry Editor

 To modify the App Install Control permissions via the Registry Editor, follow the below steps:

1. Open the Registry Editor.
2. Navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer**.  
![Go to Explorer Folder by Navigating to the Path in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/6-go-to-explorer-folder-by-navigating-to-the-path-in-windows-registry-editor.jpg)
3. Right-click on **Explorer** and select **New > String value**.  
![Create New String Value in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/7-create-new-string-value-in-windows-registry-editor.jpg)
4. Name this new value **"AicEnabled."**  
![Name the Newly Created String Value AicEnabled in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/8-name-the-newly-created-string-value-aicenabled-in-windows-registry-editor.jpg)
5. Double-click on the newly created string and type "**Anywhere"** in the **Value data** field.  
![Type Anywhere in the Value Data Field of Newly Created String in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/9-type-anywhere-in-the-value-data-field-of-newly-created-string-in-windows-registry-editor.jpg)
6. Restart the computer for the changes to take effect.

 If the above Registry tweak does not resolve the issue, turn off S mode.

## 6\. Disable Windows S Mode

 Windows S mode is primarily the most secure environment you can get in Windows. It mainly serves as a means of protecting your children and keeping sensitive documents away from prying eyes.

 When this mode is active, users can only download apps from the Microsoft Store, can't use the command line or code editors, and can't modify the Windows Registry Editor.

 Therefore, if you have recently bought a new device and this mode is enabled there by default, Windows will probably throw the error if you attempt to install any app outside the store. Therefore, you should make sure it isn't enabled and disable it if it is.

 To determine whether your device is running S mode, open the **Settings** app, select the **System** tab on the left, and open the **About** page.

 If the S mode is enabled on your device, you'll see it there. If the feature is active, turn it off by following these steps:

1. Open the **Settings** app.
2. Navigate to the **System** tab and go to **Activation**.
3. Click on **Go to the store** under **Switch to Windows 11 Home/Pro**, which will take you to the Microsoft Store page where you can opt out of S mode.
4. Click the **Get** button and follow the on-screen instructions to get out of S mode.

## 7\. Run the Windows Store Apps Troubleshooter

 If the Windows S mode isn't enabled, and you haven't restricted your operating system from downloading apps from outside Microsoft, the error could be caused by an underlying issue with the Microsoft Store. To ensure this is not the case, you should run the Windows Store Apps troubleshooter, which is a built-in tool for troubleshooting issues with the Store.

 If you've never run the troubleshooter before, refer to our guide on [how to run a troubleshooter on Windows 10 or 11](https://www.makeuseof.com/run-troubleshooter-windows-10-11/).

## Successfully Install Third-Party Applications Again on Windows

 Microsoft blocks the installation of third-party apps for your security, but it's pointless if it prevents you from installing vital apps. Hopefully, you now better understand why the Microsoft Store presents the "the app you're trying to install isn't a Microsoft-verified app" error. Following the fixes above will enable you to download the apps from unofficial sources.

 Have you encountered the error"the app you're trying to install isn't a Microsoft-verified app"while installing an app? The error occurs if you have configured your system to only install apps from the Microsoft Store. You could have set this permission on purpose, or it might have been set by default.

 Other than that, a corrupted Microsoft Store cache, installing an app from an unofficial source, and enabling Windows S mode can also cause the error. Below, you will find a few checks and fixes you should apply to resolve the error and install the app successfully.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/launching-quake-mode-using-windows-terminal/"><u>Launching Quake Mode: Using Windows Terminal</u></a></li>
<li><a href="https://win11.techidaily.com/fortifying-data-travel-best-practices-for-ws11w10/"><u>Fortifying Data Travel: Best Practices for WS11/W10</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-common-management-tool-hurdles-in-windows-11/"><u>Tackling Common Management Tool Hurdles in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/guarding-against-hidden-threats-in-these-7-windows-processes/"><u>Guarding Against Hidden Threats in These 7 Windows Processes</u></a></li>
<li><a href="https://win11.techidaily.com/curated-list-best-weather-trackers-for-w10w11/"><u>Curated List: Best Weather Trackers for W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/compre-written-for-pc-performance-metrics/"><u>Compre Written for PC Performance Metrics</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-a-mouse-wheel-that-keeps-zooming-instead-of-scrolling-on-windows/"><u>7 Ways to Fix a Mouse Wheel That Keeps Zooming Instead of Scrolling on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-silent-key-syndrome-cure-for-muted-mouse-clicks/"><u>The Silent Key Syndrome: Cure for Muted Mouse Clicks</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-excessive-pc-resources-by-unrealcefsubprocess-in-windows/"><u>Tackling Excessive PC Resources by UnrealCEFSubprocess in Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-nokia-c300-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Nokia C300 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-exclusive-choice-of-cost-free-chat-apps-plus-desktop-viewing/"><u>[New] In 2024, Exclusive Choice of Cost-Free Chat Apps + Desktop Viewing</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-all-encompassing-directory-guide-for-podcast-platforms/"><u>2024 Approved All-Encompassing Directory Guide for Podcast Platforms</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-messages-files-from-oppo-reno-9a-by-fonelab-android-recover-messages/"><u>How To  Restore Missing Messages Files from Oppo Reno 9A</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/5-ways-to-track-apple-iphone-14-without-app-drfone-by-drfone-virtual-ios/"><u>5 Ways to Track Apple iPhone 14 without App | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-ultimate-box-office-hype-films/"><u>[Updated] Ultimate Box Office Hype Films</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-10plus-preferred-no-pay-webm-player-options/"><u>2024 Approved  10+ Preferred No-Pay WebM Player Options</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-mastering-instagrams-music-stickers-integration-for-2024/"><u>[New] Mastering Instagram's Music Stickers Integration for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/2024-approved-melodies-meet-movements-creating-tiktok-videos-with-music/"><u>2024 Approved  Melodies Meet Movements  Creating TikTok Videos with Music</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-vivo-y78plus-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Vivo Y78+ Current Location of a Mobile Number | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>