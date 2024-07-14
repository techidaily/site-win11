---
title: Tactics to Address Non-Signed Windows Update Files
date: 2024-07-13T10:52:49.506Z
updated: 2024-07-14T10:52:49.506Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tactics to Address Non-Signed Windows Update Files
excerpt: This Article Describes Tactics to Address Non-Signed Windows Update Files
keywords: Fix Unsigned Updates,Block Signature Missing,Secure Windows Update,Prevent Untrusted Updates,Safe Windows Patches,Stop Insecure Windows Files,Protect Without Signatures
thumbnail: https://thmb.techidaily.com/9c499903b4fab811676ace6dccfa6523d6366f829a8f8e74e35020e8fb091823.jpg
---

## Tactics to Address Non-Signed Windows Update Files

 Users frequently report Windows 11/10 update errors on software support forums. One such update issue reported is an error message that says, “Some update files aren’t signed.” Some users see that error message appear within Settings’ Windows Update tab when trying to update Windows.

 Windows updates fail to install when this issue occurs. This error usually includes either a 0x800b0109 or 0x800b0100 code after its message. This is how you can resolve the “Some update files aren’t signed” error 0x800b0109 on a Windows 11/10 PC.

## 1\. Utilize the Windows Update Troubleshooter

 The Windows Update troubleshooting tool is there to help you fix any issues encountered when trying to update Windows 11/10\. That troubleshooter doesn’t necessarily fix every update error, but it can at least resolve some issues.

 So, utilizing that troubleshooter is always worth a try, which you can access in Settings as covered within this guide to [running any troubleshooter on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/).

![The Windows Update troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-update-troubleshooter.jpg)

## 2\. Run Deployment Imaging and System File Scans

 System file corruption is among the [most common reasons for Windows update errors](https://www.makeuseof.com/reasons-why-windows-updates-fail/). For that reason, running a System File Checker scan to address system file corruption is a recommended troubleshooting method for error 0x800b0109\.

 It’s also advisable to utilize the Deployment Imaging and Servicing Management to repair possible Windows image corruption.

 Both Deployment Imaging and System File Checker are Command Prompt tools. You can run them by inputting and executing two commands within the Command Prompt. Our article on [repairing corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) includes instructions on how to utilize the SFC and DISM command-line tools.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-sfc-scannow.jpg)

## 3\. Check the Windows Update and BITS Services Are Enabled

 Windows Updates and Background Intelligent Transfer Service (BITS) are two services that need to be enabled for updates. So, check those services are correctly set like this:

1. Simultaneously press the **Windows** logo + **S** keys on your keyboard.
2. Enter the search phrase "services" to find the app with a matching title.
3. Click on **Services** inside the search results.
4. Double-click **Windows Update** to access settings for that service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/services-window.jpg)
5. Set the **Startup type** setting to the **Automatic** option.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/startup-type-drop-down-menu.jpg)
6. Click **Start** (inside the properties windows) to run the Windows Update service.
7. Save the settings by pressing the **Apply** and **OK** buttons.
8. Double-click the **Background Intelligent Transfer Service** to view its settings.
9. Select a **Manual** startup option.
10. Click the **Start** option for the BITS service if it’s stopped.
11. Then click on the **Apply** and **OK** options to set that service’s options.

 If you find both services to be already enabled and running, try restarting them. You can do so by right-clicking the BITS and Windows Update service names and selecting a **Restart** option on their context menus.

## 4\. Reset Components for Windows Updates

 Resetting components for Windows updates will completely refresh the catroot2 and SoftwareDistribution folders, which store update data. This troubleshooting method also reregisters all DLL files for important update services. Applying such a potential resolution can fix corrupted components causing error 0x800b0109\.

 To apply this possible error 0x800b0109 resolution, check out our article on [resetting Windows update components](https://www.makeuseof.com/reset-windows-update-components/). That guide includes a command-line and batch file method. Creating and running a batch file is the quicker and more straightforward way to reset Windows update components.

## 5\. Deactivate Third-Party Security Software

 A third-party security (antivirus) app can potentially conflict with Windows update processes. This can happen when the antivirus protection of a security app locks files needed by Windows Update. It’s not something that happens often, but temporarily disable any third-party antivirus protection on your PC just in case.

 Security apps typically include options for disabling antivirus protection on their system tray context menus. Right-click your security app’s icon in Windows 11’s system tray area to find and select its option for temporarily disabling the antivirus shield. Then, return to the Settings app to see if error 0x800b0109 still happens with the antivirus shield disabled.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

## 6\. Erase the Windows Update Key

 Deleting the Windows Update registry key is a potential resolution some users confirm to fix error 0x800b0109\. However, we always recommend [backing up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or saving a system restoration point before deleting registry keys.

 When you’ve done that, try deleting the Windows Update key like this:

1. Open Run, accessible by pressing **Windows** logo key + **R**, and type a **regedit** command into that accessory.
2. Select Run’s **OK** option to open the Registry Editor.
3. Next, clear the registry address bar and input this key path there:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate`
4. Right-click the WindowsUpdate registry key to select **Delete**.  
![The Delete context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-delete-option-1.jpg)
5. Click **Yes** when prompted for confirmation to delete the key.  
![The Confirm Key Delete prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-key-confirmation-1.jpg)

 Thereafter, it’s also recommended to restart the Windows Update and BITS services. To do so, open Services as covered in the first three steps of resolution three. Then, select the **Restart** context menu options for Windows Update and BITS.

## 7\. Try Downloading the Failed Update From Microsoft Update Catalog

 If error 0x800b0109 still isn’t fixed after applying the potential resolutions above, try going around it by manually downloading the affected update from [Microsoft Update Catalog](https://www.catalog.update.microsoft.com/Home.aspx). Then, you can install the update with an MSU file downloaded from there.

 You will first need to identify what update is failing as follows:

1. Simultaneously press your keyboard’s **Windows** logo + **I** keys to access Settings.
2. Click **Windows Update** (or **Update & Security**) in Settings.
3. Select **Update history** to view installed and failed updates.  
![The update history in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-history4.jpg)
4. Note down the KB code for your recently failed Windows update.

 Then, you can find and download that failed update on the Microsoft Update Catalog website. This article about [updating Windows manually](https://www.makeuseof.com/update-windows-manually/) includes instructions for utilizing the Microsoft Update Catalog.

## 8\. Apply an In-Place Windows Upgrade

 An in-place Windows upgrade is the last resort for fixing error 0x800b0109\. Applying this potential resolution will reinstall Windows on your PC with its latest ISO file. The installation of a fresh Windows copy will likely resolve other issues causing the 0x800b0109 update error that other potential solutions couldn’t fix.

 The good thing about an in-place upgrade is that it won’t eradicate your installed software or user files. This [how-to perform an in-place upgrade](https://www.makeuseof.com/in-place-upgrade-windows-11/) guide tells you how to apply this potential solution for Windows 11\. The steps are quite similar for Windows 10, but you’ll need to download its ISO with the Media Creation Tool available on this [Microsoft page](https://www.microsoft.com/en-gb/software-download/windows10).

![The Windows 10 Media Creation tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-10-setup-window.jpg)

## Get Windows Updated Again

 There isn’t a surefire way to fix error 0x800b0109 since there are varied possible reasons for that Windows 11/10 issue occurring. However, it’s likely at least one of the eight potential resolutions in this guide will fix that update issue on your PC.

 Some of the best third-party Windows repair tools might also be helpful for resolving the “Some update files aren’t signed” error.

 Windows updates fail to install when this issue occurs. This error usually includes either a 0x800b0109 or 0x800b0100 code after its message. This is how you can resolve the “Some update files aren’t signed” error 0x800b0109 on a Windows 11/10 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-skills.techidaily.com/mastery-of-safaris-picture-in-picture-for-ios-and-macos-for-2024/"><u>Mastery of Safari's Picture-in-Picture for iOS & macOS for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/taskbar-transformation-through-38-years/"><u>Taskbar Transformation Through 38 Years</u></a></li>
<li><a href="https://win11.techidaily.com/self-contained-strategies-for-hardware-duplication/"><u>Self-Contained Strategies for Hardware Duplication</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastering-multitask-media-consumption-harnessing-pip-feature-in-netflix/"><u>[New] Mastering Multitask Media Consumption  Harnessing PIP Feature in Netflix</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-ultimate-guide-to-adding-text-on-images/"><u>2024 Approved  Ultimate Guide to Adding Text on Images</u></a></li>
<li><a href="https://win11.techidaily.com/top-4-techniques-for-mac-address-discovery-in-windows-11/"><u>Top 4 Techniques for Mac Address Discovery in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-a-productive-win-11-taskbar/"><u>The Ultimate Guide to a Productive Win 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-strategies-to-overcome-access-barriers-on-win-pcs/"><u>Top 8 Strategies to Overcome Access Barriers on Win PCs</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-enhance-video-production-7-best-free-sounds-for-editors/"><u>[New] Enhance Video Production - 7 Best Free Sounds for Editors</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-recognize-non-appearing-hdd/"><u>Strategies to Recognize Non-Appearing HDD</u></a></li>
<li><a href="https://iphone-location.techidaily.com/6-methods-to-protect-yourself-from-location-tracking-on-apple-iphone-15-pro-drfone-by-drfone-virtual-ios/"><u>6 Methods to Protect Yourself from Location Tracking on Apple iPhone 15 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-ultimate-vision-quest-samsung-galaxy-s8s-4k-prowess/"><u>The Ultimate Vision Quest  Samsung Galaxy S8's 4K Prowess</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-infinix-smart-8-hd-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your Infinix Smart 8 HD Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-controlling-windows-key-status/"><u>Understanding and Controlling Windows Key Status</u></a></li>
<li><a href="https://win11.techidaily.com/silent-restarts-a-windows-1011-guide-to-going-dark/"><u>Silent Restarts: A Windows 10/11 Guide to Going Dark</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-make-your-text-pop-8-top-rated-neon-generators-online/"><u>In 2024, Make Your Text Pop 8 Top-Rated Neon Generators Online</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-everything-you-need-to-know-about-lock-screen-settings-on-your-nokia-c02-by-drfone-android/"><u>In 2024, Everything You Need to Know about Lock Screen Settings on your Nokia C02</u></a></li>
<li><a href="https://win11.techidaily.com/7-personal-touches-for-windows-11s-search-engine/"><u>7 Personal Touches for Windows 11'S Search Engine</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-windows-experience-7-fixes-for-broken-apps/"><u>Seamless Windows Experience: 7 Fixes for Broken Apps</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-if-you-are-trying-to-create-a-countdown-effect-but-youre-not-sure-where-to-start-then-this-post-is-going-to-show-you-some-ways-to-create-a-countdown-ani/"><u>New If You Are Trying to Create a Countdown Effect, but Youre Not Sure Where to Start, Then This Post Is Going to Show You some Ways to Create a Countdown Animation for Your Videos</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-oppo-f23-5g-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your Oppo F23 5G | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-seamlessly-reorganize-video-playlists-on-yt/"><u>[Updated] In 2024, How to Seamlessly Reorganize Video Playlists on YT</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steam-backup-mishaps/"><u>Troubleshooting Steam Backup Mishaps</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/free-software-roundup-mac-compatible-tiktok-editors-for-2024/"><u>Free Software Roundup  Mac-Compatible TikTok Editors for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-data-from-lost-or-stolen-iphone-14-pro-in-easy-steps-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How To Recover Data From Lost or Stolen iPhone 14 Pro In Easy Steps | Stellar</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-motorola-moto-g84-5g-phones-by-drfone-android/"><u>In 2024, Top 11 Free Apps to Check IMEI on Motorola Moto G84 5G Phones</u></a></li>
<li><a href="https://win11.techidaily.com/turbo-windows-11-app-opening-secrets-revealed/"><u>Turbo Windows 11 App Opening Secrets Revealed</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-tiktok-watermark-remover-software-online-options-compared/"><u>New In 2024, TikTok Watermark Remover Software Online Options Compared</u></a></li>
<li><a href="https://win11.techidaily.com/windows-save-location-glitch-quick-guide/"><u>Windows Save Location Glitch: Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-disabling-of-windows-11-alerts/"><u>Speedy Disabling of Windows 11 Alerts</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-best-concealed-vids-2023s-selective-8-software-guide/"><u>[Updated] 2024 Approved  Best Concealed Vids - 2023'S Selective 8 Software Guide</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tips-simply-recognize-your-computers-ram-type/"><u>Tech Tips: Simply Recognize Your Computer's RAM Type</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-boot-on-windows-sound-service-reboot-needs/"><u>Troubleshooting Boot-On Windows Sound Service Reboot Needs</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-responsive-touchpad-gestures-on-windows/"><u>Troubleshooting Non-Responsive Touchpad Gestures on Windows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-pro-tips-transforming-mundane-footage-into-epic-gopro-time-lapses/"><u>[New] Pro Tips  Transforming Mundane Footage Into Epic GoPro Time-Lapses</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-what-you-want-to-know-about-two-factor-authentication-for-icloud-on-your-iphone-se-2020-by-drfone-ios/"><u>In 2024, What You Want To Know About Two-Factor Authentication for iCloud On your iPhone SE (2020)</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-ensure-audible-feedback-in-screen-captures/"><u>Techniques to Ensure Audible Feedback in Screen Captures</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-navigating-blank-login-page-fixes/"><u>Windows 11: Navigating Blank Login Page Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-activating-newly-redesigned-widget-tool/"><u>Step-by-Step Guide: Activating Newly Redesigned Widget Tool</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-steam-performance-overcoming-degraded-download-rates/"><u>Skyrocket Steam Performance: Overcoming Degraded Download Rates</u></a></li>
<li><a href="https://win11.techidaily.com/windows-warnings-identifying-critical-processes-for-malware-detection/"><u>Windows Warnings: Identifying Critical Processes for Malware Detection</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-dissecting-youtubes-selection-of-trending-video-responses/"><u>[New] In 2024, Dissecting YouTube's Selection of Trending Video Responses</u></a></li>
</ul></div>
