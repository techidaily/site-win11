---
title: Managing Failed App Verifications in Windows OS
date: 2024-07-13T09:50:21.723Z
updated: 2024-07-14T09:50:21.723Z
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

1. Open the Local Group Policy Editor. To do this, check out [how to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) if you're not using Windows Home edition, and learn [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) if you are.
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/updated-overcoming-shadows-in-indoor-vlogging-environments/"><u>[Updated] Overcoming Shadows in Indoor Vlogging Environments</u></a></li>
<li><a href="https://win11.techidaily.com/faster-teams-cleaner-systems-microsofts-pivot/"><u>Faster Teams, Cleaner Systems: Microsoft's Pivot</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-how-to-shoot-breathtaking-igtv-content-on-smartphonesdlsrs/"><u>[Updated] 2024 Approved  How to Shoot Breathtaking IGTV Content on Smartphones/DLSRs</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-it-administrator-cant-do-more-warning-in-winsec/"><u>Resolving 'IT Administrator Can’t Do More' Warning in WinSec</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-pivoting-with-purpose-rotate-and-rethink-with-youtubes-latest-tools/"><u>In 2024, Pivoting with Purpose  Rotate and Rethink with YouTube's Latest Tools</u></a></li>
<li><a href="https://win11.techidaily.com/power-tools-for-pc-mastery-command-prompt-edition-of-win-registry-edits/"><u>Power Tools for PC Mastery: Command Prompt Edition of Win Registry Edits</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-samsung-flow-linking-winpc-and-galaxy-device/"><u>Mastering Samsung Flow: Linking WinPC & Galaxy Device</u></a></li>
<li><a href="https://win11.techidaily.com/solving-installed-but-inaccessible-microsoft-apps/"><u>Solving Installed but Inaccessible Microsoft Apps</u></a></li>
<li><a href="https://win11.techidaily.com/make-windows-11-shine-a-holiday-system-guide/"><u>Make Windows 11 Shine: A Holiday System Guide</u></a></li>
<li><a href="https://win11.techidaily.com/resurrect-dead-audio-a-step-by-step-guide-to-tech-sound/"><u>Resurrect Dead Audio: A Step-by-Step Guide to Tech Sound</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-to-do-if-your-iphone-8-has-bad-esn-or-blacklisted-imei-by-drfone-ios/"><u>What to do if your iPhone 8 has bad ESN or blacklisted IMEI?</u></a></li>
<li><a href="https://win11.techidaily.com/tackle-windows-geforce-scanning-problems-effectively/"><u>Tackle Windows GeForce Scanning Problems Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/from-boring-to-stunning-switching-themes-in-windows-11-made-simple/"><u>From Boring to Stunning: Switching Themes in Windows 11 Made Simple</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-android-gaming-on-win-11-via-play-store-linkup/"><u>Seamless Android Gaming on Win 11 via Play Store Linkup</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-microsoft-teams-stalling-in-w11w10-systems/"><u>Fixing Microsoft Teams Stalling in W11/W10 Systems</u></a></li>
<li><a href="https://tools.techidaily.com/digisigner/"><u>Free Electronic Signature Service - DigiSigner</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-synching-youtube-songs-to-video-frameworks/"><u>2024 Approved  Synching YouTube Songs to Video Frameworks</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-biometric-settings-of-w11-for-domains/"><u>Mastering the Biometric Settings of W11 for Domains</u></a></li>
<li><a href="https://win11.techidaily.com/rapid-pc-data-access-everythingapp-utilization/"><u>Rapid PC Data Access: EverythingApp Utilization</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-top-10-steps-to-dominance-in-innovative-tiktok-marketing-playbooks/"><u>[Updated] In 2024, Top 10 Steps to Dominance in Innovative TikTok Marketing Playbooks</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-no-more-space-files-issue/"><u>Overcoming 'No More Space' Files Issue</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-windows-11-file-transfers-that-halt/"><u>How to Resolve Windows 11 File Transfers That Halt</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-group-policy-changes-on-a-windows-system/"><u>Navigating Group Policy Changes on a Windows System</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/academic-allies-premier-educators-on-youtube-for-2024/"><u>Academic Allies  Premier Educators on YouTube for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/ignoring-the-windows-lsa-protection-deactivation/"><u>Ignoring the Windows LSA Protection Deactivation</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-uncovering-the-best-apps-to-transform-your-speech/"><u>[New] In 2024, Uncovering the Best Apps to Transform Your Speech</u></a></li>
<li><a href="https://win11.techidaily.com/fingerprint-fiasco-can-you-still-count-on-windows-hello/"><u>Fingerprint Fiasco: Can You Still Count on Windows Hello?</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-the-disappeared-disk-space-issue/"><u>Rectify the Disappeared Disk Space Issue</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-zte-axon-40-lite-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from ZTE Axon 40 Lite To Phone | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/should-you-embrace-windows-11s-secure-environment/"><u>Should You Embrace Windows 11'S Secure Environment?</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-earn-big-on-tiktok-unveiling-the-top-8-profitable-approaches/"><u>[Updated] In 2024, Earn Big on TikTok  Unveiling the Top 8 Profitable Approaches</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-thumbnails-dimensions-on-desktop/"><u>Personalize Thumbnails: Dimensions on Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-keyboard-errors-fixing-function-keys-on-windows-11/"><u>Resolve: Keyboard Errors - Fixing Function Keys on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/solving-full-screen-glitches-in-sonic-frontiers-windows-11/"><u>Solving Full-Screen Glitches in Sonic Frontiers (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fixes-for-error-code-0x8000fffd-on-pcs/"><u>Mastering Fixes for Error Code 0X8000FFFD on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-volume-adjustment-issues-in-windows-os/"><u>Mastering Volume Adjustment Issues in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/running-advanced-ai-on-windows-devices/"><u>Running Advanced AI on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unable-to-display-errors-in-microsoft-store/"><u>Overcoming 'Unable to Display' Errors in Microsoft Store</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/real-time-recording-prowess-without-any-delays-for-2024/"><u>Real-Time Recording Prowess Without Any Delays for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-galaxy-performance-through-seamless-integration-in-windows-11/"><u>Optimizing Galaxy Performance Through Seamless Integration in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/solving-mbs-service-connection-failures-on-windows-11/"><u>Solving MB's Service Connection Failures on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/stop-blue-screen-bsos-quick-fix-strategies-for-win11/"><u>Stop Blue Screen BSOS: Quick Fix Strategies for Win11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-flash-and-fly-gaming-top-10-speedy-apps-on-desktopmobile/"><u>2024 Approved  Flash & Fly Gaming  Top 10 Speedy Apps on Desktop/Mobile</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-and-fixing-startup-item-disappearance/"><u>Identifying & Fixing Startup Item Disappearance</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-simplifying-windows-11-sound-logging/"><u>2024 Approved  Simplifying Windows 11 Sound Logging</u></a></li>
<li><a href="https://win11.techidaily.com/five-keys-to-a-streamlined-firewall-configuration/"><u>Five Keys to a Streamlined Firewall Configuration</u></a></li>
</ul></div>
