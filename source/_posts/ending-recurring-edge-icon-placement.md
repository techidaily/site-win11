---
title: Ending Recurring Edge Icon Placement
date: 2024-09-11T09:45:50.432Z
updated: 2024-09-12T09:45:50.432Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ending Recurring Edge Icon Placement
excerpt: This Article Describes Ending Recurring Edge Icon Placement
keywords: Ending Edge Icons,Recurring Icon Removal,Discontinue Edge Symbols,Cease Icon Repeats,Remove Edging Signs,Stop Icon Duplication,End Persistent Edge Marks
thumbnail: https://thmb.techidaily.com/2e153e0e621bce9ac8484d65d8c4dd2eb6f5a3b85fbf991174fd2d0ac26c3edd.png
---

## Ending Recurring Edge Icon Placement

 Does Windows keep showing the Microsoft Edge shortcut on your desktop even after you delete it? Don’t worry, your computer hasn't been compromised. Several users have shared their experiences of Windows automatically generating the Edge shortcut after a system restart or update.

 Fortunately, there's no requirement to manually delete the Edge desktop shortcut repeatedly. Here are some helpful tips that should help resolve the issue in no time.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123472/16836" target="_top" id="2123472">
  <img src="//a.impactradius-go.com/display-ad/16836-2123472" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123472/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Prevent Microsoft Edge From Opening at Startup

 By default, Microsoft Edge runs every time you start your Windows computer. Several users on the Microsoft forums reported fixing this particular issue by preventing Microsoft Edge from opening at startup. Hence, it’s the first thing you should try.

 You can use Task Manager to review all the apps that are configured to run at boot and disable Edge from there. Here are the steps you can follow:

1. Press **Win + X** to open the Power User menu.
2. Select **Task Manager** from the resulting menu.
3. Select **Startup apps** from the left pane.
4. Locate and select **Microsoft Edge** on the list. Right-click on it and select **Disabled** from the context menu.  
![Startup Apps in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Startup-Apps-in-Task-Manager.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118319/7443" target="_top" id="2118319">
  <img src="//a.impactradius-go.com/display-ad/7443-2118319" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118319/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Additionally, you should also [access the startup folder on your Windows PC](https://www.makeuseof.com/access-startup-folder-windows/) and delete any shortcuts labeled Microsoft Edge.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134241/18498" target="_top" id="2134241">
  <img src="//a.impactradius-go.com/display-ad/18498-2134241" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134241/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

 Close the Registry Editor window and restart your PC. After that, check if the issue is resolved.

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
7. Hit Apply followed by **OK**.
8. Similarly, disable the **Allow Microsoft Edge to start and load the Start and New Tab page at Windows startup, and each time Microsoft Edge is closed** policy as well.

 Restart your PC one more time and check if the issue is resolved.

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
<a href="https://ursime.pxf.io/c/5597632/2136548/16384" target="_top" id="2136548">
  <img src="//a.impactradius-go.com/display-ad/16384-2136548" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136548/16384" style="position:absolute;visibility:hidden;" border="0" />
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

 Further, you can [restrict others from creating and running tasks in the Task Scheduler app](https://www.makeuseof.com/windows-block-task-manager/) by modifying the group policy settings or the registry files.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115918/19272" target="_top" id="2115918">
  <img src="//a.impactradius-go.com/display-ad/19272-2115918" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115918/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Uninstall Microsoft Edge From Your PC

 If none of the above tips help, you can consider uninstalling Microsoft Edge to fix the problem. This can be useful if Microsoft Edge isn’t your preferred browser anyway.

 Use Command Prompt or PowerShell to [uninstall Microsoft Edge from your Windows computer](https://www.makeuseof.com/windows-11-uninstall-microsoft-edge/). Once you remove the browser, the issue should be resolved.

<!-- affiliate ads begin -->
<span id="2135471">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135471%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135471/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Prevent Microsoft Edge From Appearing on Your Desktop

 It can be confusing if Microsoft Edge’s shortcut keeps appearing on your desktop for no apparent reason. Hopefully, one of the above-mentioned fixes has helped fix the issue for good, and you are at peace.

 Does your Windows desktop look like a jumbled mess? If so, you can easily organize it by grouping desktop shortcut icons with a third-party program.

 Fortunately, there's no requirement to manually delete the Edge desktop shortcut repeatedly. Here are some helpful tips that should help resolve the issue in no time.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/024-approved-optimizing-content-editing-youtube-descriptions-and-titles-for-growth/"><u>[New] 2024 Approved Optimizing Content Editing YouTube Descriptions & Titles for Growth</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-step-by-step-method-for-changing-your-instagram-tone/"><u>[New] 2024 Approved Step-By-Step Method for Changing Your Instagram Tone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-the-art-of-facebook-video-coverage-standout-tips-and-tricks/"><u>[New] In 2024, The Art of Facebook Video Coverage Standout Tips & Tricks</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-mastering-lenovo-perfecting-screen-capture-techniques/"><u>[New] Mastering Lenovo Perfecting Screen Capture Techniques</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-in-2024-digital-decor-best-platforms-and-software-for-photo-frameups/"><u>[Updated] In 2024, Digital Decor Best Platforms & Software for Photo Frameups</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-groundbreaking-webinar-name-builder/"><u>[Updated] In 2024, Groundbreaking Webinar Name Builder</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-visionary-flying-discover-the-q500-typhoon/"><u>[Updated] Visionary Flying - Discover the Q500 Typhoon</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-expert-tips-for-high-quality-sound-memos/"><u>2024 Approved Expert Tips for High-Quality Sound Memos</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-exploring-peak-performance-best-oculus-rift-players/"><u>2024 Approved Exploring Peak Performance Best Oculus Rift Players</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-unveiling-the-secrets-of-premiere-pros-full-screen-magic/"><u>2024 Approved Unveiling the Secrets of Premiere Pro's Full Screen Magic</u></a></li>
<li><a href="https://facebook.techidaily.com/6-changes-that-have-redirected-online-community-gatherings/"><u>6 Changes That Have Redirected Online Community Gatherings</u></a></li>
<li><a href="https://extra-tips.techidaily.com/accuracy-at-hand-editing-tiktoks-personal-info/"><u>Accuracy at Hand Editing TikTok's Personal Info</u></a></li>
<li><a href="https://extra-information.techidaily.com/breakthrough-media-tools-to-complement-xsplit/"><u>Breakthrough Media Tools to Complement XSplit</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-tips-for-dealing-with-system-calls-in-windows/"><u>Comprehensive Tips for Dealing With System Calls in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-win11s-systray-with-caps-lock-and-num-key-icons/"><u>Customizing Win11's SysTray with Caps Lock & Num Key Icons</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-vac-was-unable-to-verify-your-game-session-error-on-steam-for-windows/"><u>How to Fix the “VAC Was Unable to Verify Your Game Session” Error on Steam for Windows</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-activation-lock-from-the-iphone-xs-without-previous-owner-by-drfone-ios/"><u>How to Remove Activation Lock From the iPhone XS Without Previous Owner?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-contacts-files-from-xiaomi-13t-by-fonelab-android-recover-contacts/"><u>How To Restore Missing Contacts Files from Xiaomi 13T.</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-cutting-through-clutter-standout-techniques-for-tiktok-stars/"><u>In 2024, Cutting Through Clutter Standout Techniques for TikTok Stars</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-mastering-xbox-one-step-by-step-screen-capture-guide/"><u>In 2024, Mastering Xbox One Step-by-Step Screen Capture Guide</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-preparation-to-beat-giovani-in-pokemon-go-for-xiaomi-mix-fold-3-drfone-by-drfone-virtual-android/"><u>In 2024, Preparation to Beat Giovani in Pokemon Go For Xiaomi Mix Fold 3 | Dr.fone</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-seo-booster-essentials-for-top-online-videos/"><u>In 2024, SEO Booster Essentials for Top Online Videos</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-itel-s23-drfone-by-drfone-virtual-android/"><u>In 2024, Unova Stone Pokémon Go Evolution List and How Catch Them For Itel S23 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-graphics-enhancement-in-windows-11s-shielded-browsing/"><u>Innovative Graphics Enhancement in Windows 11'S Shielded Browsing</u></a></li>
<li><a href="https://win11.techidaily.com/is-the-windows-settings-app-crashing-try-these-fixes/"><u>Is the Windows Settings App Crashing? Try These Fixes</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/joining-friends-showtime-on-tiktok-with-ease-for-2024/"><u>Joining Friends’ Showtime on TikTok with Ease for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-error-correction-windows-11-wow-mishaps/"><u>Mastering Error Correction: Windows 11 WoW Mishaps</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-speech-to-text-the-whisper-desktop-way/"><u>Mastering Speech-to-Text: The Whisper Desktop Way</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-ai-hub-revolutionizing-retail-shopping/"><u>Microsoft AI Hub: Revolutionizing Retail Shopping</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-buffering-issues-on-chrome-and-youtube/"><u>Overcoming Buffering Issues on Chrome & YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-epic-launcher-errors-a-windows-fix-guide/"><u>Overcoming Epic Launcher Errors: A Windows Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-store-error-code-x00000000/"><u>Overcoming Windows 11 Store Error Code X00000000</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-resetting-synapse-for-smooth-operation/"><u>Quick Guide: Resetting Synapse for Smooth Operation</u></a></li>
<li><a href="https://win11.techidaily.com/quick-remedies-for-stalled-asana-functionality-in-windows-environment/"><u>Quick Remedies for Stalled Asana Functionality in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-for-windows-11s-software-folder-restarts/"><u>Quick-Fix Guide for Windows 11'S Software Folder Restarts</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-cmd-prompt-lack-of-admin-privileges/"><u>Resolving Cmd Prompt Lack of Admin Privileges</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-disk-read-error-on-windows-os/"><u>Resolving Disk Read Error on Windows OS</u></a></li>
<li><a href="https://technical-tips.techidaily.com/seamless-pairing-a-step-by-step-guide-on-syncing-your-airpods-with-macbook-air/"><u>Seamless Pairing: A Step-by-Step Guide on Syncing Your AirPods with MacBook Air</u></a></li>
<li><a href="https://win11.techidaily.com/steam-game-achievement-reboot-guide/"><u>Steam Game Achievement Reboot Guide</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-installing-kali-into-your-windows-ecosystem/"><u>Step by Step: Installing Kali Into Your Windows Ecosystem</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-dns-flushing-in-modern-windows/"><u>Step-by-Step DNS Flushing in Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-setting-up-and-using-microsofts-code-assistant/"><u>Step-by-Step: Setting Up and Using Microsoft's Code Assistant</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-camera-non-storage-feedback/"><u>Tackling Windows Camera Non-Storage Feedback</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-companion-for-new-diablo-players/"><u>The Essential Companion for New Diablo Players</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-guide-to-altering-nat-settings-on-modern-windows-systems/"><u>The Essential Guide to Altering NAT Settings on Modern Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/the-skillful-technique-to-obscure-window-11-search/"><u>The Skillful Technique to Obscure Window 11 Search</u></a></li>
<li><a href="https://win11.techidaily.com/transform-workflow-efficiency-mastering-flow-launcher-basics/"><u>Transform Workflow Efficiency: Mastering Flow Launcher Basics</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-persistent-windows-volume-mixer/"><u>Troubleshooting Non-Persistent Windows Volume Mixer</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-error-0x800f082f-with-dism/"><u>Troubleshooting Windows Error 0X800F082F with DISM</u></a></li>
<li><a href="https://win11.techidaily.com/tutorial-mastering-github-desktop-for-windows-based-developers/"><u>Tutorial: Mastering GitHub Desktop for Windows-Based Developers</u></a></li>
<li><a href="https://win11.techidaily.com/unearthing-the-hidden-potential-of-windows-monitoring-systems/"><u>Unearthing the Hidden Potential of Windows Monitoring Systems</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    