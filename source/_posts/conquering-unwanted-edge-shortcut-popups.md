---
title: Conquering Unwanted Edge Shortcut Popups
date: 2024-08-16T00:42:24.888Z
updated: 2024-08-17T00:42:24.888Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Conquering Unwanted Edge Shortcut Popups
excerpt: This Article Describes Conquering Unwanted Edge Shortcut Popups
keywords: Stop Edge Shortcuts,Eliminate Edge Pops,Remove Edge Overlays,No More Edge Ads,Halt Edge Prompts,Block Edge Alerts,Silence Edge Notifications
thumbnail: https://thmb.techidaily.com/a0a9154950aed42e7733b765877eaeb4a66b52b52c8c12f95943f09a40bb3819.jpg
---

## Conquering Unwanted Edge Shortcut Popups

 Does Windows keep showing the Microsoft Edge shortcut on your desktop even after you delete it? Don’t worry, your computer hasn't been compromised. Several users have shared their experiences of Windows automatically generating the Edge shortcut after a system restart or update.

 Fortunately, there's no requirement to manually delete the Edge desktop shortcut repeatedly. Here are some helpful tips that should help resolve the issue in no time.

## 1\. Prevent Microsoft Edge From Opening at Startup

 By default, Microsoft Edge runs every time you start your Windows computer. Several users on the Microsoft forums reported fixing this particular issue by preventing Microsoft Edge from opening at startup. Hence, it’s the first thing you should try.

 You can use Task Manager to review all the apps that are configured to run at boot and disable Edge from there. Here are the steps you can follow:

1. Press **Win + X** to open the Power User menu.
2. Select **Task Manager** from the resulting menu.
3. Select **Startup apps** from the left pane.
4. Locate and select **Microsoft Edge** on the list. Right-click on it and select **Disabled** from the context menu.  
![Startup Apps in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Startup-Apps-in-Task-Manager.jpg)

 Additionally, you should also [access the startup folder on your Windows PC](https://www.makeuseof.com/access-startup-folder-windows/) and delete any shortcuts labeled Microsoft Edge.

## 2\. Edit Registry Files

 Another way to prevent the Microsoft Edge shortcut from reappearing on your desktop involves editing registry files.

 Making incorrect changes to the registry files can cause serious damage to your system. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

 Even if you are familiar with the registry editor, make sure you follow the steps carefully to [avoid accidentally messing up the Windows registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/).

 Use the following instructions:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft**.
5. Right-click on the **Microsoft** key and select **New > Key**. Name it **EdgeUpdate**.
6. Right-click on the **EdgeUpdate** key and select **New > DWORD (32-bit) Value**. Rename it **CreateDesktopShortcutDefault**.
7. Double-click the newly created DWORD and enter **0** in the Value data field. Then, click **OK**.
8. Within the **EdgeUpdate** key, create another DWORD and name it **RemoveDesktopShortcutDefault**.
9. Double-click the **RemoveDesktopShortcutDefault** DWORD and enter **0** in the Value data field.
10. Click **OK**.  
![EdgeUpdate Key in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edgeupdate-key-in-registry.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->

 Close the Registry Editor window and restart your PC. After that, check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## 3\. Modify Group Policy Settings

 If the issue remains even after you edit registry files, you can try modifying the group policy settings.

 The Group Policy Editor is only available in the Professional, Education, or Enterprise editions of Windows. That said, you can [access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) with a simple workaround.

 Follow these steps to modify Group Policy settings:

1. Press **Win + S** to open the search menu.
2. Type **gpedit.msc** in the search box and press **Enter**.
3. Select **Yes** if the User Account Control (UAC) prompt appears.
4. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Components > Microsoft Edge**.
5. Double-click the **Allow Microsoft Edge to pre-launch at Windows startup, when the system is idle, and each time Microsoft Edge is closed** policy in the right pane.
6. Select the **Disabled** option.  
![Microsoft Edge pre-launch policy selected in the Local Group Policy Editor Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Local-Group-Policy-Editor-Window.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
7. Hit Apply followed by **OK**.
8. Similarly, disable the **Allow Microsoft Edge to start and load the Start and New Tab page at Windows startup, and each time Microsoft Edge is closed** policy as well.

 Restart your PC one more time and check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Remove Microsoft Edge as the Default Browser

 Another reason why the Microsoft Edge shortcut may keep showing up on your Windows desktop is if you have set it as the default browser.

 Try [changing the default browser on your Windows PC](https://www.makeuseof.com/windows-11-change-default-browser/) to something other than Microsoft Edge and see if that fixes the issue.

 If you need help picking a reliable browser, you can check out [the best browsers for Windows](https://www.makeuseof.com/windows-11-best-browsers/).

## 5\. Restrict Other Users From Creating Desktop Shortcuts

 If you share your computer with others, someone else may be creating shortcuts for Edge without your permission. If you don't want this to happen, you can use the Group Policy Editor to prevent other users from creating desktop shortcuts.

 Here are the steps for the same:

1. Click the search icon on the taskbar to access the search menu.
2. Type **edit group policy** or **gpedit** in the search box and select the first result that appears.
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
4. Double-click on the **Prevent changing desktop icons** policy in the right pane.
5. Select the **Enabled** option.
6. Click **Apply** and then **OK**.  
![Using the Local Group Policy to Prevent Others From Changing Desktop Icons](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Using-the-Local-Group-Policy-to-Prevent-Others-From-Changing-Desktop-Icons.jpg)

 And that's about it. Once you make the above changes, the other users won't be able to create, modify, or delete your desktop icons.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Review Scheduled Tasks

 It is possible that a scheduled task is causing Windows to create a desktop shortcut for Edge repeatedly. To check for this possibility, you need to review tasks in the Task Scheduler app.

 Use these steps to check automated tasks in Task Scheduler:

1. Right-click on the **Start icon** and select **Run** from the menu that appears.
2. Type **taskschd.msc** in the box and press **Enter** to open the Task Scheduler app.
3. Select **Task Scheduler Library** in the left pane to view a list of tasks in the middle pane.
4. Locate and select any Edge-related tasks.
5. Click the **Disable** option in the right pane.  
![An Automated task selected in the Task Scheduler window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Task-Scheduler-Window.jpg)
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Further, you can [restrict others from creating and running tasks in the Task Scheduler app](https://www.makeuseof.com/windows-block-task-manager/) by modifying the group policy settings or the registry files.

## 7\. Uninstall Microsoft Edge From Your PC

 If none of the above tips help, you can consider uninstalling Microsoft Edge to fix the problem. This can be useful if Microsoft Edge isn’t your preferred browser anyway.

 Use Command Prompt or PowerShell to [uninstall Microsoft Edge from your Windows computer](https://www.makeuseof.com/windows-11-uninstall-microsoft-edge/). Once you remove the browser, the issue should be resolved.

## Prevent Microsoft Edge From Appearing on Your Desktop

 It can be confusing if Microsoft Edge’s shortcut keeps appearing on your desktop for no apparent reason. Hopefully, one of the above-mentioned fixes has helped fix the issue for good, and you are at peace.

 Does your Windows desktop look like a jumbled mess? If so, you can easily organize it by grouping desktop shortcut icons with a third-party program.

 Fortunately, there's no requirement to manually delete the Edge desktop shortcut repeatedly. Here are some helpful tips that should help resolve the issue in no time.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-decoding-youtubes-legal-framework-for-video-creators-for-2024/"><u>[New] Decoding YouTube's Legal Framework for Video Creators for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-from-novice-to-expert-perfecting-mac-audio-with-audacity-for-2024/"><u>[New] From Novice to Expert  Perfecting Mac Audio with Audacity for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-the-ultimate-screenshotting-handbook-by-professionals-using-zd-softs-software/"><u>[New] In 2024, The Ultimate Screenshotting Handbook by Professionals Using ZD Soft’s Software</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-mastering-the-art-of-recording-macs-roblox-sessions/"><u>[New] Mastering the Art of Recording Mac's Roblox Sessions</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-understanding-your-best-fit-in-virtual-reality-worlds-choosing-between-portable-and-plugged-in/"><u>[New] Understanding Your Best Fit in Virtual Reality Worlds  Choosing Between Portable and Plugged In</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-elevate-your-facebook-profile-with-these-11-superior-tools/"><u>[Updated] In 2024, Elevate Your Facebook Profile with These 11 Superior Tools</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-essential-techniques-for-recording-instagram-stories/"><u>[Updated] In 2024, Essential Techniques for Recording Instagram Stories</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-fast-and-easy-guide-how-to-set-up-snapchat-on-a-mac/"><u>[Updated] In 2024, Fast & Easy Guide  How to Set up Snapchat on a Mac</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-producing-channel-trailer-synopses-a-guide/"><u>[Updated] In 2024, Producing Channel Trailer Synopses  A Guide</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-mastering-full-view-fb-movie-magic-for-2024/"><u>[Updated] Mastering Full-View Fb Movie Magic for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/beyond-the-screen-vr-movie-innovation/"><u>Beyond the Screen  VR Movie Innovation</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-from-google-chrome-glitch-on-windows-11-now/"><u>Break Free From Google Chrome Glitch on Windows 11 Now!</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-wacatacbml-understanding-and-neutralizing-threats-on-windows/"><u>Breaking Down Wacatac.B!ml: Understanding and Neutralizing Threats on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bridge-the-gap-quick-fixes-for-slow-windows-app-connections/"><u>Bridge the Gap: Quick Fixes for Slow Windows App Connections</u></a></li>
<li><a href="https://win11.techidaily.com/ceasing-erratic-mouse-movement-in-windows/"><u>Ceasing Erratic Mouse Movement in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/converting-from-pin-to-password-a-windows-11-users-guide-for-enhanced-security/"><u>Converting From PIN to Password: A Windows 11 User's Guide for Enhanced Security</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-error-code-0xa00f425d-in-windows-1e11-camera/"><u>Correcting Error Code: 0XA00F425D in Windows 1E11 Camera</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-management-using-mspcm-toolbar-in-w11-os/"><u>Efficient Management Using MSPCM Toolbar in W11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-user-sign-in-after-windows-authentication-issues/"><u>Enabling User Sign-In After Windows Authentication Issues</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-root-user-access-in-the-windows-terminal/"><u>Ensuring Root User Access in the Windows Terminal</u></a></li>
<li><a href="https://win11.techidaily.com/flush-your-steam-dns-data-a-windows-user-guide/"><u>Flush Your Steam DNS Data - A Windows User Guide</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-iphone-13-mini-online-without-jailbreak-by-drfone-ios/"><u>How to Unlock SIM Card on iPhone 13 mini online without jailbreak</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-text-actions-in-the-snipping-tool-on-windows-11/"><u>How to Use Text Actions in the Snipping Tool on Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-oppo-reno-8t-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Oppo Reno 8T Phone and Remove Locked Screen</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-samsung-galaxy-a15-5g-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Samsung Galaxy A15 5G to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mobile-and-desktop-audiospeed-alteration-essentials/"><u>In 2024, Mobile & Desktop Audiospeed Alteration Essentials</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-smooth-transition-of-scale-enhancing-instagram-tv-video-clarity/"><u>In 2024, Smooth Transition of Scale  Enhancing Instagram TV Video Clarity</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-in-nullifying-windows-11s-eyes-on-you/"><u>Mastery in Nullifying Windows 11'S Eyes on You</u></a></li>
<li><a href="https://win11.techidaily.com/overhaul-your-inbox-and-calendar-use-custom-images/"><u>Overhaul Your Inbox and Calendar: Use Custom Images</u></a></li>
<li><a href="https://win11.techidaily.com/1719376947968-regain-your-account-in-microsoft-store-now/"><u>Regain Your Account in Microsoft Store, Now!</u></a></li>
<li><a href="https://win11.techidaily.com/sly-settings-shuffle-disguising-power-buttons-on-desktop/"><u>Sly Settings Shuffle: Disguising Power Buttons on Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-accurate-game-detection-failure-in-discord-windows-pc/"><u>Solutions for Accurate Game Detection Failure in Discord (Windows PC)</u></a></li>
<li><a href="https://extra-resources.techidaily.com/step-up-the-fun-top-new-wins11-games-unveiled/"><u>Step Up the Fun  Top New Wins11 Games Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-windows-11s-printer-interface-max-52-chars/"><u>Streamline Windows 11'S Printer Interface (Max 52 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-solve-your-windows-fbm-hiccups-today/"><u>Swiftly Solve Your Windows FBM Hiccups Today</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-integrating-secondary-antivirus-without-defenders-hindrance/"><u>Tips for Integrating Secondary Antivirus Without Defender’s Hindrance</u></a></li>
<li><a href="https://win11.techidaily.com/why-win10-is-more-than-enough-in-the-current-tech-scene/"><u>Why Win10 Is More Than Enough in the Current Tech Scene</u></a></li>
<li><a href="https://win11.techidaily.com/win11-solutions-for-unfunctional-resource-monitor-app/"><u>Win11: Solutions for Unfunctional Resource Monitor App</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>