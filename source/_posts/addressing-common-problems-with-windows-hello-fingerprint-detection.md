---
title: Addressing Common Problems with Windows Hello Fingerprint Detection
date: 2024-07-13T11:18:27.789Z
updated: 2024-07-14T11:18:27.789Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Common Problems with Windows Hello Fingerprint Detection
excerpt: This Article Describes Addressing Common Problems with Windows Hello Fingerprint Detection
keywords: Windows Fingerprint Troubleshoot,Windows Hello Fix Issues,Fingerprint Recognition Errors,WinHello Biometrics Problems,Windows Login Failures,Fingerprint Detection Solutions,Windows Authentication Hurdles
thumbnail: https://thmb.techidaily.com/d57dd9f54952f4e7ca5edd2db9c4efad701c22be438a3c8ee1521a12138dfcd3.jpg
---

## Addressing Common Problems with Windows Hello Fingerprint Detection

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
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-to-recover-your-windows-apps/"><u>A Step-by-Step Approach to Recover Your Windows Apps</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-lost-data-from-honor-magic-6-pro-by-fonelab-android-recover-data/"><u>How to recover lost data from Honor Magic 6 Pro?</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-vivo-x90s-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Vivo X90S | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-enable-or-disable-ntfs-file-compression-in-windows-11/"><u>4 Ways to Enable or Disable NTFS File Compression in Windows 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-rhythm-research-capture-and-review-music-files/"><u>[Updated] In 2024, Rhythm Research  Capture & Review Music Files</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-rising-stars-top-10-tiktok-reaction-clips/"><u>[Updated] Rising Stars  Top 10 TikTok Reaction Clips</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-apps-from-oneplus-ace-2-pro-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Apps from OnePlus Ace 2 Pro to Another | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-vimeo-insight-where-streaming-meets-originality/"><u>2024 Approved  Vimeo Insight  Where Streaming Meets Originality</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-set-up-efficient-live-conversations-on-pc-via-whatsapp-web-for-2024/"><u>[Updated] Set Up Efficient Live Conversations on PC via WhatsApp Web for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/masterclass-in-instagram-story-downloads-and-creation/"><u>Masterclass in Instagram Story Downloads & Creation</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-saving-success-mastering-ppt-errors-in-windows-11/"><u>Accelerate Saving Success: Mastering PPT Errors in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719364636660-self-hosted-windows-gptclone-via-gpt4all/"><u>Self-Hosted Windows GPTClone via GPT4All</u></a></li>
<li><a href="https://win11.techidaily.com/9-reasons-to-rethink-your-email-client-the-modern-outlook/"><u>9 Reasons to Rethink Your Email Client - The Modern Outlook</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-audio-archive-checkout-and-scrutiny-for-2024/"><u>[New] Audio Archive Checkout & Scrutiny for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-restoring-lost-windows-update/"><u>A Beginner's Guide to Restoring Lost Windows Update</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/selecting-perfect-google-pixel-ringers-a-guide-for-2024/"><u>Selecting Perfect Google Pixel Ringers  A Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-fix-the-black-desktop-background-display-issue-on-windows/"><u>8 Ways to Fix the Black Desktop Background Display Issue on Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-my-spouse-from-spying-on-my-nubia-red-magic-9-proplus-drfone-by-drfone-virtual-android/"><u>How to Stop My Spouse from Spying on My Nubia Red Magic 9 Pro+ | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-the-best-batch-mp3-conversion-services-with-text-output-compatible-with-smoothvideopro/"><u>New In 2024, The Best Batch MP3 Conversion Services with Text Output – Compatible with SmoothVideoPro</u></a></li>
<li><a href="https://win11.techidaily.com/8-latest-innovations-in-windows-11-post-update-release/"><u>8 Latest Innovations in Windows 11, Post-Update Release</u></a></li>
<li><a href="https://win11.techidaily.com/1719347919938-skip-steps-just-admin-command-prompt-anytime-now/"><u>Skip Steps, Just Admin Command Prompt Anytime Now!</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-sony-xperia-5-v-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Sony Xperia 5 V Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-the-best-of-the-best-5-free-online-tone-generators/"><u>2024 Approved The Best of the Best 5 Free Online Tone Generators</u></a></li>
<li><a href="https://win11.techidaily.com/1719330765099-troubleshooting-tips-for-your-windows-predicaments/"><u>Troubleshooting Tips for Your Windows Predicaments!</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-for-overcoming-the-pink-flash/"><u>A Comprehensive Guide for Overcoming the Pink Flash</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-8-free-online-instagram-reels-downloaders-that-will-save-your-day/"><u>2024 Approved  8 FREE Online Instagram Reels Downloaders That Will Save Your Day</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-walkthrough-to-activate-notepad-dark-mode-on-windows-11/"><u>A Detailed Walkthrough to Activate Notepad Dark Mode on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/8-essential-techniques-for-improved-cs-go-play/"><u>8 Essential Techniques for Improved CS Go Play</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/display-protocol-aligned-fixed-22/"><u>Display Protocol Aligned - Fixed #22</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-keyboard-skills-using-windows-powertoys/"><u>Accelerate Keyboard Skills Using Windows PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-reset-the-windows-firewall-settings/"><u>5 Ways to Reset the Windows Firewall Settings</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-fresh-to-famous-elevating-your-channels-views-and-youtube-subs-for-2024/"><u>[Updated] From Fresh to Famous  Elevating Your Channels Views & Youtube Subs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/7-reasons-why-most-users-havent-upgraded-to-windows-11/"><u>7 Reasons Why Most Users Haven’t Upgraded to Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719366255245-functional-failures-cure-win10-key-issues-now/"><u>Functional Failures? Cure Win10 Key Issues Now!</u></a></li>
<li><a href="https://win11.techidaily.com/6-fixes-if-the-c-drive-keeps-filling-up-for-no-reason-on-windows/"><u>6 Fixes if the C: Drive Keeps Filling Up for No Reason on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-simplified-guide-to-jdk-setup-for-modern-windows-11-users/"><u>A Simplified Guide to JDK Setup for Modern Windows 11 Users</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-checking-top-5-web-based-or-extension-voice-changers-for-chromebook/"><u>2024 Approved  Checking Top 5 Web-Based or Extension Voice Changers for Chromebook</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-alternate-escapades-where-the-gta-v-lives-are-missing/"><u>[New] Alternate Escapades - Where the GTA V Lives Are Missing</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreayers-guide-accessing-windows-web-services-manager/"><u>A Compreayer's Guide: Accessing Windows Web Services Manager</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-your-realme-c55-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>How to Mirror Your Realme C55 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-ultimate-tutorial-on-precise-audioshifting/"><u>In 2024, Ultimate Tutorial on Precise Audioshifting</u></a></li>
<li><a href="https://win11.techidaily.com/5-actionable-steps-to-solve-gpeditmsc-disappearance/"><u>5 Actionable Steps to Solve Gpedit.msc Disappearance</u></a></li>
<li><a href="https://win11.techidaily.com/1719346431441-navigate-through-common-snip-and-sketch-screen-capture-issues/"><u>Navigate Through Common Snip & Sketch Screen Capture Issues.</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-unlocking-adobe-premiere-pro-import-edit-and-export-video-files-with-ease/"><u>New In 2024, Unlocking Adobe Premiere Pro Import, Edit, and Export Video Files with Ease</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-ways-to-track-samsung-galaxy-s24-ultra-without-them-knowing-drfone-by-drfone-virtual-android/"><u>3 Ways to Track Samsung Galaxy S24 Ultra without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-ignite-interest-captivate-views-elevate-likes-on-your-unboxings/"><u>[New] Ignite Interest, Captivate Views  Elevate Likes on Your Unboxings</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-10-airplay-apps-in-nubia-red-magic-8s-proplus-for-streaming-drfone-by-drfone-android/"><u>In 2024, Top 10 AirPlay Apps in Nubia Red Magic 8S Pro+ for Streaming | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/5-proven-methods-to-clean-your-win11s-dns-cache/"><u>5 Proven Methods to Clean Your Win11's DNS Cache</u></a></li>
<li><a href="https://win11.techidaily.com/5-precise-steps-to-rectify-your-screen-res-in-windows/"><u>5 Precise Steps to Rectify Your Screen Res in Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ultimate-guide-to-catch-the-regional-located-pokemon-for-oppo-reno-8t-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Catch the Regional-Located Pokemon For Oppo Reno 8T | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-navigating-the-world-of-apex-legends-on-a-personal-platform-quest/"><u>[Updated] Navigating the World of Apex Legends on a Personal Platform Quest</u></a></li>
<li><a href="https://win11.techidaily.com/7-windows-11-features-youre-probably-not-using-but-should/"><u>7 Windows 11 Features You’re Probably Not Using (but Should)</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-tutorial-incorporating-widgets-in-windows-11/"><u>A Step-by-Step Tutorial: Incorporating Widgets in Windows 11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-free-video-stabilization-made-easy-top-8-online-tools-and-tutorials/"><u>New Free Video Stabilization Made Easy Top 8 Online Tools and Tutorials</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-walkthrough-of-ms-error-lookup-in-w11/"><u>A Comprehensive Walkthrough of MS Error Lookup in W11</u></a></li>
<li><a href="https://win11.techidaily.com/a-new-dimension-of-cleanliness-windows-eraser-feature/"><u>A New Dimension of Cleanliness: Windows' Eraser Feature</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-music-files-on-vivo-t2-5g-by-fonelab-android-recover-music/"><u>Complete guide for recovering music files on Vivo T2 5G</u></a></li>
<li><a href="https://win11.techidaily.com/a-deep-dive-into-microsoft-family-safety-tools/"><u>A Deep Dive Into Microsoft Family Safety Tools</u></a></li>
<li><a href="https://win11.techidaily.com/7-rapid-responses-to-combat-windows-app-failures/"><u>7 Rapid Responses to Combat Windows App Failures</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/strategizing-an-attention-grabbing-tiktok-signoff-for-2024/"><u>Strategizing an Attention-Grabbing TikTok Signoff for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-walkthrough-for-installing-apps-via-wpm-on-windows-11/"><u>A Step-by-Step Walkthrough for Installing Apps via WPM on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-keyboard-input-lag-on-windows-11-and-11/"><u>7 Ways to Fix Keyboard Input Lag on Windows 11 and 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-use-device-manager-to-reinstall-your-hardware-drivers-on-windows-1110-by-drivereasy-guide/"><u>How to use Device Manager to reinstall your hardware drivers on Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-tech-finding-your-graphics-spec-in-windows-11/"><u>Accelerate Tech: Finding Your Graphics Spec in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-task-management-in-microsoft-project/"><u>Accelerate Task Management in Microsoft Project</u></a></li>
</ul></div>
