---
title: Fix Unrecognized App Warning During Windows Setup
date: 2024-07-13T10:49:26.931Z
updated: 2024-07-14T10:49:26.931Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fix Unrecognized App Warning During Windows Setup
excerpt: This Article Describes Fix Unrecognized App Warning During Windows Setup
keywords: Fix Unrecognized Warning,Windows Setup Error,Boot Failure Message,Installation Alert,SafeBoot Troubleshoot,System Recovery Steps,PC Diagnostics Guide
thumbnail: https://thmb.techidaily.com/302790bfdd6c387be2ce7104b2f0ec7045e52a09e036ffbf26a83ecf9455ec5e.jpg
---

## Fix Unrecognized App Warning During Windows Setup

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
<li><a href="https://animation-videos.techidaily.com/new-10-trendy-free-logo-animation-templates/"><u>New 10 Trendy Free Logo Animation Templates</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/a-comprehensive-guide-to-creating-compelling-fb-reels-for-2024/"><u>A Comprehensive Guide to Creating Compelling FB Reels for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/top-7-windows-photo-management-tools-an-essential-guide/"><u>Top 7 Windows Photo Management Tools: An Essential Guide</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-honor-magic5-ultimate-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos From Honor Magic5 Ultimate to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/calculating-riches-a-look-at-mr-beasts-wallet/"><u>Calculating Riches  A Look at Mr. Beast's Wallet</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-navigating-best-options-expert-picks-from-top-9-free-logomakers/"><u>[Updated] Navigating Best Options  Expert Picks From Top 9 Free Logomakers</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-game-hub-error-code-0x800700e9-on-microsoft-devices/"><u>Resolving Game Hub Error Code 0X800700E9 on Microsoft Devices</u></a></li>
<li><a href="https://win11.techidaily.com/rejuvenating-inactive-recycle-bin-icon-on-win11/"><u>Rejuvenating Inactive Recycle Bin Icon on Win11</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-the-ultimate-checklist-for-pairing-airpods-with-laptops-and-desktops/"><u>2024 Approved The Ultimate Checklist for Pairing AirPods with Laptops and Desktops</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-vivo-t2x-5g-by-drfone-android/"><u>In 2024, 10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Vivo T2x 5G</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-leading-talents-premier-instragram-hlv-creators/"><u>[Updated] 2024 Approved  Leading Talents  Premier Instragram HLV Creators</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-dual-logins-eliminating-mixed-account-errors/"><u>Conquering Dual Logins: Eliminating Mixed Account Errors</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-gaming-channel-evolution-best-14-video-ideas-on-youtube/"><u>[New] 2024 Approved  Gaming Channel Evolution  Best 14 Video Ideas on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/revitalize-your-pc-display-interactive-and-lively-windows-11-walls/"><u>Revitalize Your PC Display: Interactive and Lively Windows 11 Walls</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-taking-a-step-back-inverting-image-queries-in-instagram/"><u>[New] 2024 Approved  Taking a Step Back  Inverting Image Queries in Instagram</u></a></li>
<li><a href="https://win11.techidaily.com/1719365130359-mastery-over-malfunctioning-windows-easy-fixes-at-hand/"><u>Mastery Over Malfunctioning Windows: Easy Fixes at Hand</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/unraveling-directx12-obstacles-for-halo-infinite-launch/"><u>Unraveling: DirectX12 Obstacles for Halo Infinite Launch</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-essential-mac-friendly-audio-mixers-the-ultimate-list-of-the-best-5/"><u>2024 Approved Essential Mac-Friendly Audio Mixers The Ultimate List of the Best 5</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-identify-missing-hardware-drivers-with-windows-device-manager-on-windows-11107-by-drivereasy-guide/"><u>How to identify missing hardware drivers with Windows Device Manager on Windows 11/10/7</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-gaps-in-file-explorer-indexing/"><u>Correcting Gaps in File Explorer Indexing</u></a></li>
<li><a href="https://win11.techidaily.com/triggering-driver-verifier-on-windows-11-pc/"><u>Triggering Driver Verifier on Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-11-glitches-solutions-guide/"><u>Unraveling WINDOWS 11 Glitches: Solutions Guide</u></a></li>
<li><a href="https://win11.techidaily.com/recording-games-simply-mastering-screen-captures-with-intel-tools/"><u>Recording Games Simply: Mastering Screen Captures with Intel Tools</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-breakdown-of-windows-startup-setup-options/"><u>A Step-by-Step Breakdown of Windows Startup Setup Options</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-increase-win11-icons-size/"><u>Techniques to Increase Win11 Icons Size</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-top-9-changes-in-win11-february-2023/"><u>Unveiling the Top 9 Changes in Win11 February 2023</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-overclocked-cpus-for-gaming-users/"><u>Troubleshooting Overclocked CPUs for Gaming Users</u></a></li>
<li><a href="https://win11.techidaily.com/the-power-and-essence-of-wintoys-an-uncomplicated-yet-comprehensive-explanation/"><u>The Power & Essence of 'WinToys': An Uncomplicated, Yet Comprehensive Explanation</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-fix-windows-11-when-you-cant-rename-folders/"><u>8 Ways to Fix Windows 11 When You Can’t Rename Folders</u></a></li>
<li><a href="https://win11.techidaily.com/aligning-your-preferences-with-nvidia-driver-choices/"><u>Aligning Your Preferences with Nvidia Driver Choices</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-dive-into-free-download-final-cut-pro/"><u>2024 Approved  Dive Into FREE Download  Final Cut Pro</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-key-sites-the-6-most-vital-platforms-for-b2b-relationships/"><u>[New] Key Sites  The 6 Most Vital Platforms for B2B Relationships</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-heat-in-windows-11-pcs/"><u>Troubleshooting Heat in Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-operation-warhammer-40k-boltgun-windows-stutter-fixes/"><u>Smooth Operation Warhammer 40K Boltgun: Windows Stutter Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-global-scripts-a-windows-font-guide/"><u>Unleashing Global Scripts: A Windows Font Guide</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-experience-microsoft-store-file-types-msixbundle/"><u>Streamline Your Experience: Microsoft Store File Types (MSixBundle)</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-the-10-most-efficient-ways-to-capture-your-music-on-windowsmac-systems/"><u>Updated 2024 Approved The 10 Most Efficient Ways to Capture Your Music on Windows/Mac Systems</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-the-ultimate-blueprint-for-earning-money-on-tiktok-8-strategies-for-2024/"><u>[New] The Ultimate Blueprint for Earning Money on TikTok (8 Strategies) for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-symphony-of-screenshots-incorinas-music-into-social-media/"><u>2024 Approved  Symphony of Screenshots  Incorinas Music Into Social Media</u></a></li>
<li><a href="https://win11.techidaily.com/window-lockscreen-tips-engage-or-mute-spotlight-images/"><u>Window Lockscreen Tips: Engage or Mute Spotlight Images</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-take-notes-on-windows-11-without-downloading-software/"><u>5 Ways to Take Notes on Windows 11 Without Downloading Software</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/revolutionizing-graphics-an-examination-of-cg318-4k-by-eizo-for-2024/"><u>Revolutionizing Graphics  An Examination of CG318-4K by EIZO for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-sidestep-social-media-sponsored-videos/"><u>[Updated] Sidestep Social Media Sponsored Videos</u></a></li>
<li><a href="https://fox-helps.techidaily.com/day-after-evaluation-new-approaches/"><u>Day After Evaluation  New Approaches</u></a></li>
<li><a href="https://win11.techidaily.com/the-windows-bar-evolution-story-1985present/"><u>The Windows Bar Evolution Story (1985–Present)</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/the-ultimate-list-of-prestige-business-strategy-titles-24-for-2024/"><u>The Ultimate List of Prestige Business Strategy Titles '24 for 2024</u></a></li>
</ul></div>
