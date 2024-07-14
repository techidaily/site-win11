---
title: Quick Steps for Mending Windows Hello Fingerprint Issues
date: 2024-07-13T10:51:40.674Z
updated: 2024-07-14T10:51:40.674Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Steps for Mending Windows Hello Fingerprint Issues
excerpt: This Article Describes Quick Steps for Mending Windows Hello Fingerprint Issues
keywords: Fixing HL Fingersync,HL Fingerprint Troubleshoot,Quick HL Fingerprint Fix,Resolve HL Finger ID Errors,Mend Windows Hello FP Issues,Tips for HL Fingerprint,Realign HL Fingerprint Data
thumbnail: https://thmb.techidaily.com/fea6185edc685da72ba963a46eed57a3a71d461697393364ab3bd89b9977de72.jpg
---

## Quick Steps for Mending Windows Hello Fingerprint Issues

 Using a fingerprint scanner is perhaps the most convenient way to log in to your Windows computer. It not only eliminates the need to type in a complex password or PIN every time you want to access your computer but also saves you time. But what if Windows Hello fingerprint authentication stops working on your computer?

 Fortunately, there are several ways to fix this annoying issue. So, let’s dive in and explore what you should do when Windows Hello fingerprint login isn’t working.

## 1\. Remove and Re-Register Your Fingerprint

 Your first step is to remove your Windows Hello fingerprint and register it again. This may sound basic, but it is one of the most straightforward ways to get your fingerprint reader to work again. Here are the steps you can follow.

1. Press **Win + I** to open the Settings app.
2. Head to **Accounts > Sign-in options**.
3. Under the **Windows Hello** section, click the **Remove** button.  
![Windows Sign-in Options window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Remove-Windows-Hello-Fingerprint-1.jpg)
4. Once removed, click the **Set up** button and follow the on-screen instructions to register your fingerprint again.

 If the issue persists or if you are unable to remove and re-add your fingerprint due to the "This option is currently unavailable" error on the Windows Hello page, there may be a problem with the Biometric drivers on your PC.

## 2\. Reinstall the Biometric Device Driver

 Biometric drivers on your PC help Windows communicate with your PC's fingerprint scanner. If these drivers are outdated or malfunctioning, you may run into problems.

 Most of the time, you can fix the problem by simply uninstalling and reinstalling the driver on your PC. Here’s how you can go about it.

1. Right-click on the **Start** icon to open the Power User menu.
2. Select **Device Manager** from the list.
3. Expand **Biometric devices**.  
![Biometric Driver selected in Device Manager window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Biometric-Driver-in-Device-Manager-1.jpg)
4. Right-click on your fingerprint scanner device and select **Uninstall device**.
5. Select **Uninstall** to confirm.

 Additionally, you should also expand the **Universal Serial Bus Controllers** section in the Device Manager and look for any entries with a yellow exclamation. If you find any, right-click on them one by one and select **Uninstall device** to remove them.

 Restart your PC after completing the above steps and check if the issue still occurs.

## 3\. Run the Hardware and Devices Troubleshooter

 Windows 10 and 11 include a number of [troubleshooters for resolving various system-related issues](https://www.makeuseof.com/windows-11-troubleshooters/). In this case, you should run the Hardware and Devices troubleshooter. It will scan your computer’s fingerprint scanner for any issues and attempt to fix them.

 Follow these steps to run the Hardware and Devices troubleshooter on Windows:

1. Press **Win + R** to open the Run dialog box.
2. Type **msdt.exe -id DeviceDiagnostic** in the Open field and press **Enter**.
3. In the Hardware and Devices window, click **Next**.  
![Hardware and Devices Troubleshooter Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Hardware-and-Devices-Troubleshooter-Window.jpg)

 Wait for Windows to diagnose any issues with your computer. If any issues are detected, follow the on-screen instructions to apply the recommended fixes.

## 4\. Turn Off Fast Startup

 Fast Startup is a handy Windows feature that speeds up your PC's boot time after shutdown. However, this feature might sometimes prevent Windows from loading properly. When this happens, the fingerprint scanner may not work on your Windows 10 or 11 PC.

 Use one of the many ways to [disable Fast Startup on your Windows computer](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) and see if that gets the fingerprint scanner to work.

## 5\. Configure Windows Biometric Service to Start Automatically

 The Windows Biometric Service is an essential program for Windows Hello, as it captures and manages your fingerprint data. Ideally, the service should start automatically every time Windows boots. However, this might not happen if the service is not configured correctly.

 Use these steps to configure the Windows Biometric Service:

1. Open the **Services** app using the search menu.
2. Scroll down to locate the **Windows Biometric Service** on the list.
3. Right-click on it and select **Properties**.
4. Click the drop-down menu to change the **Startup type** to **Automatic**.
5. Hit **Apply** followed by **OK**.  
![Windows Biometric Service Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Windows-Biometric-Service-Properties.jpg)

 Restart your PC after this. Following that, you should be able to sign in with your fingerprint.

## 6\. Enable Biometrics via the Local Group Policy Editor

 Another reason why Windows Hello fingerprint sign-in may not work is if the feature is disabled from the Local Group Policy. It's important to note that Group Policy Settings are only available on Professional, Education, and Enterprise editions of Windows. If you are on Windows Home, you don't need to worry about this step.

 To enable fingerprint authentication via the Local Group Policy Editor, use these steps:

1. Press **Win + S** to open the search menu.
2. Type **gpedit.msc** in the search box and press **Enter** to [open the Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/).
3. Use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Components > Biometrics**.
4. Check if all the policies within the Biometrics folder are enabled. If not, double-click each policy one by one and set them to **Enabled**.  
![Biometric Policies in Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Local-Group-Policy-Editor-Window-1.jpg)

 Restart your PC one more time and check if the issue is still there.

## 7\. Create a New User Account

 An issue with your current user account can also cause certain Windows features to stop working. This usually happens when your user account files get corrupted. If you suspect that to be the case, you can [create and switch to a new user account](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) to fix the issue. Here’s how you can go about it.

1. Press **Win + I** to open the Settings app.
2. Head to **Accounts > Other users**.
3. Click the **Add account** button.
4. In the Microsoft account window, click on **I don't have this person's sign-in information** and follow the on-screen prompts to create a new user account.  
![Microsoft Account Sign In Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Microsoft-Account-Sign-In-Window.jpg)

 Set up Windows Hello fingerprint login for your new user account and see if you can sign in with your fingerprint.

## 8\. Perform a System Restore

 If the fingerprint not working issue only occurred recently, you can use System Restore to revert Windows to a previous state. This will allow you to undo any changes that may have caused the issue. Note that this is only possible if you have previously [enabled System Restore on your PC](https://www.makeuseof.com/windows-11-enable-system-restore/).

 Follow these steps to perform a system restore on Windows:

1. Press **Win + S** to open the search menu.
2. Type **Create a restore point in the search box** and press **Enter**.
3. Under the **System Protection** tab, click on **System Restore**.
4. Click **Next**.
5. Select a restore point before the issue first appeared and hit **Next**.
6. Review all the details one more time before hitting **Finish**.  
![System Restore Dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/System-Restore-Dialog.jpg)

 Windows will restart and revert to the specified restore point. After that, the fingerprint should work as before.

## 9\. Install the Latest Windows Updates

 Microsoft regularly releases software updates for Windows 10 and Windows 11 to add new features, improve performance, and—crucially for our purposes—fix bugs. If the fingerprint not working issue is caused by a system bug, updating Windows to its most recent version should help.

 You can check for new updates by going to the **Windows Update** tab in the **Settings** app. Download and install any pending updates on your PC. Hopefully, this will resolve the issue.

## Fixing Windows Hello's Fingerprint Check

 It’s annoying when your PC's fingerprint scanner stops working all of a sudden. However, that shouldn’t force you to use your password or PIN to sign in to your computer.

 We hope one of the methods mentioned above has helped and you are able to sign in with your fingerprint again. However, if all else fails, you may want to consider resetting your Windows computer.

 Fortunately, there are several ways to fix this annoying issue. So, let’s dive in and explore what you should do when Windows Hello fingerprint login isn’t working.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/achieving-an-unadulterated-system-restart-in-windows-11/"><u>Achieving an Unadulterated System Restart in Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/guffaw-on-your-phone-hysterical-site-listings-for-2024/"><u>Guffaw on Your Phone  Hysterical Site Listings for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-sound-error-on-audacity-in-win1011/"><u>Resolving Sound Error on Audacity in Win10/11</u></a></li>
<li><a href="https://apple-account.techidaily.com/a-step-by-step-guide-to-finding-your-apple-id-on-your-apple-iphone-7-plus-by-drfone-ios/"><u>A Step-by-Step Guide to Finding Your Apple ID On Your Apple iPhone 7 Plus</u></a></li>
<li><a href="https://win11.techidaily.com/the-leaders-small-computers-running-windows/"><u>The Leaders: Small Computers Running Windows</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-total-data-consumption-days-long-movie/"><u>[Updated] Total Data Consumption  Day's Long Movie</u></a></li>
<li><a href="https://win11.techidaily.com/paint-your-thoughts-desktop-design-mastery-in-windows/"><u>Paint Your Thoughts: Desktop Design Mastery in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-system-use-with-6-advanced-trackers-for-win-users/"><u>Streamline System Use with 6 Advanced Trackers for Win Users</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-complete-guide-to-optimizing-your-picsart-experience/"><u>In 2024, Complete Guide to Optimizing Your PicsArt Experience</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-and-configuring-windows-data-sources-by-odbc/"><u>Accessing and Configuring Windows Data Sources by ODBC</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-leveraging-video-cropping-to-maximize-instagram-reach/"><u>[New] In 2024, Leveraging Video Cropping to Maximize Instagram Reach</u></a></li>
<li><a href="https://extra-hints.techidaily.com/brilliant-barrage-essential-gadgets-for-clips-for-2024/"><u>Brilliant Barrage  Essential Gadgets for Clips for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reinitializing-distro-and-catroot2-in-w11-a-step-by-step-guide/"><u>Reinitializing Distro & Catroot2 in W11: A Step-by-Step Guide</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-gaming-to-goals-celebrating-the-top-10-ladies-on-youtube/"><u>[New] 2024 Approved  From Gaming to Goals  Celebrating the Top 10 Ladies on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/winning-strategy-against-c0000022-system-collapse/"><u>Winning Strategy Against C0000022 System Collapse</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-past-windows-0x80242016-update-fails/"><u>Navigating Past Windows' 0X80242016 Update Fails</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-1011s-recycle-bin-issues/"><u>Navigating Through Windows 10/11'S Recycle Bin Issues</u></a></li>
<li><a href="https://extra-tips.techidaily.com/bring-back-windows-photo-viewer-steps-in-win-11-edition-for-2024/"><u>Bring Back Windows Photo Viewer  Steps in Win 11 Edition for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-the-ultimate-fcpx-plugin-repair-guide-diagnose-and-fix-issues-fast/"><u>New 2024 Approved The Ultimate FCPX Plugin Repair Guide Diagnose and Fix Issues Fast</u></a></li>
<li><a href="https://win11.techidaily.com/sketch-mastery-for-desktop-users-in-windows-11/"><u>Sketch Mastery for Desktop Users in Windows 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-from-beginner-to-pro-the-top-tips-for-instagram-stories/"><u>2024 Approved  From Beginner to Pro  The Top Tips for Instagram Stories</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-resize-with-confidence-the-up-to-date-aspect-ratio-guide-for-social-media/"><u>New Resize with Confidence The Up-to-Date Aspect Ratio Guide for Social Media</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-top-rated-speech-to-text-applications-for-mobile-devices/"><u>In 2024, Top-Rated Speech-to-Text Applications for Mobile Devices</u></a></li>
<li><a href="https://win11.techidaily.com/win11-fixing-persistent-read-only-folders/"><u>Win11: Fixing Persistent Read-Only Folders</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-secrets-to-surpassing-the-top-in-youtube-fame/"><u>2024 Approved  Secrets to Surpassing the Top in YouTube Fame</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-insights-new-folder-formation-in-windows-11/"><u>Innovative Insights: New Folder Formation in Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-express-humor-no-charge-with-easymeme-tools/"><u>2024 Approved  Express Humor, No Charge with EasyMeme Tools</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-essential-hashtag-analyzers-facebook-twitter-and-instagram-edition-for-2024/"><u>[New] Essential Hashtag Analyzers  Facebook, Twitter & Instagram Edition for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-printer-uninstallation-without-recovery-options/"><u>Mastering Printer Uninstallation without Recovery Options</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-ultimate-guide-to-theta-s-features/"><u>The Ultimate Guide to Theta S Features</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-motorola-moto-g23-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Motorola Moto G23 to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-d3d11-gpu-error-on-windows-11-and-10/"><u>Troubleshooting D3D11 GPU Error on Windows 11 & 10</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-recurring-audiotrack-flaw-the-fix-for-code-9999/"><u>Tackling Windows' Recurring Audiotrack Flaw: The Fix for Code 9999</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-mastering-visual-communication-a-comprehensive-guide-to-using-gifs-on-the-discord-platform/"><u>[New] In 2024, Mastering Visual Communication  A Comprehensive Guide to Using GIFs on the Discord Platform</u></a></li>
<li><a href="https://win11.techidaily.com/surface-laptop-studio-2-the-artists-dream-device-unveiled/"><u>Surface Laptop Studio 2: The Artist's Dream Device Unveiled</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-navigating-intellectual-property-on-instagram-for-2024/"><u>[Updated] Navigating Intellectual Property on Instagram for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-11-overcoming-5ghz-wi-fi-barriers/"><u>Breaking Down Windows 11: Overcoming 5GHz Wi-Fi Barriers</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-startup-changing-boot-timeout-in-windows-11/"><u>Optimize Startup: Changing Boot Timeout in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-microsofts-safe-mode-only-constraint/"><u>Navigating Through Microsoft's Safe Mode Only Constraint</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-bypass-iphone-6s-plus-passcode-easily-video-inside-drfone-by-drfone-ios/"><u>In 2024, How to Bypass iPhone 6s Plus Passcode Easily Video Inside | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/instructional-manual-restoring-originality-in-windows-11-search/"><u>Instructional Manual: Restoring Originality in Windows 11 Search</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-uncomplicated-tutorial-for-capturing-mac-screenshots/"><u>[New] 2024 Approved  Uncomplicated Tutorial for Capturing Mac Screenshots</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-sluggish-windows-printer/"><u>Troubleshoot Sluggish WIndows Printer</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-beginners-strategy-boosting-business-via-telegram-marketing-for-2024/"><u>A Beginner’s Strategy  Boosting Business via Telegram Marketing for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-gaming-intro-creation-made-easy-top-10-tools-for-windows-and-mac/"><u>Updated In 2024, Gaming Intro Creation Made Easy Top 10 Tools for Windows and Mac</u></a></li>
<li><a href="https://win11.techidaily.com/powerful-techniques-for-unlocking-your-system-writable-files/"><u>Powerful Techniques for Unlocking Your System' Writable Files</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-learn-video-editing-fast-top-beginner-friendly-software/"><u>Updated In 2024, Learn Video Editing Fast Top Beginner-Friendly Software</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-line-up-of-artistic-software-for-windows-10/"><u>The Ultimate Line-Up of Artistic Software for Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-code-0xc0000142-in-winos/"><u>Resolving Code 0XC0000142 in WINOS</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-integrating-lut-technology-into-your-obs-setup/"><u>In 2024, Integrating LUT Technology Into Your OBS Setup</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-unleash-the-power-of-reversal-advanced-tiktok-video-editing-techniques/"><u>Updated 2024 Approved Unleash the Power of Reversal Advanced TikTok Video Editing Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-screens-boost-your-pcs-performance-with-hotkeys/"><u>Streamlined Screens: Boost Your PC's Performance with Hotkeys</u></a></li>
<li><a href="https://win11.techidaily.com/the-science-behind-windows-11s-streamlined-file-safety-measures/"><u>The Science Behind Windows 11’S Streamlined File Safety Measures</u></a></li>
<li><a href="https://win11.techidaily.com/smart-pc-enhancement-add-gmail-bar-to-taskbar-border/"><u>Smart PC Enhancement: Add Gmail Bar to Taskbar Border</u></a></li>
<li><a href="https://win11.techidaily.com/win11-quick-fixes-for-photoshop-not-launching/"><u>Win11: Quick Fixes for Photoshop Not Launching</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-apple-iphone-6-to-mac-drfone-by-drfone-ios/"><u>How to Mirror Apple iPhone 6 to Mac? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/ancestry-unveiled-7-enduring-features-of-windows-11/"><u>Ancestry Unveiled: 7 Enduring Features of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-hidden-taskbar-while-running-full-screen-edges/"><u>Unveiling Hidden Taskbar While Running Full Screen Edges</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-direct-pathway-iphone-files-on-your-desktop/"><u>2024 Approved  Direct Pathway  IPhone Files on Your Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-errors-with-proper-use-of-winservicesexe/"><u>Avoiding Errors with Proper Use of Winservices.exe</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-getting-prepared-for-macos-11-big-sur-upgrade/"><u>[Updated] Getting Prepared for MacOS 11 Big Sur Upgrade</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-msstore-from-error-0x0-issue-in-windows-os/"><u>Unblocking MsStore From Error 0X0 Issue in Windows OS</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-in-2024-discover-the-secret-of-dynamic-tiktok-videos-with-voiceovers/"><u>[Updated] In 2024, Discover the Secret of Dynamic TikTok Videos with Voiceovers</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-11s-potential-with-latest-patch-details/"><u>Unlocking Windows 11'S Potential with Latest Patch Details</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/enhance-video-transmission-success-in-messenger-apps-for-iphone-android/"><u>Enhance Video Transmission Success in Messenger Apps for iPhone, Android</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-fatal-application-hiccups-windows-edition/"><u>Overcoming Fatal Application Hiccups: Windows Edition</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-essential-tips-precise-video-trimming-on-vimeo-5-methods-for-2024/"><u>[Updated] Essential Tips  Precise Video Trimming on Vimeo [5 Methods] for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-tecno-spark-10-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Tecno Spark 10 5G Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-grouped-taskbar-symbols-on-windows-11/"><u>Clearing Grouped Taskbar Symbols on Windows 11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-channel-expansion-via-youtube-outros-maximizing-visibility/"><u>[New] Channel Expansion via YouTube Outros  Maximizing Visibility</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-bsod-traces-within-windows-108/"><u>Understanding BSOD Traces Within Windows 10/8</u></a></li>
</ul></div>
