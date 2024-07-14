---
title: Diagnosing and Fixing the Frozen Resource Monitor App in Win11
date: 2024-07-13T10:16:07.155Z
updated: 2024-07-14T10:16:07.155Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Diagnosing and Fixing the Frozen Resource Monitor App in Win11
excerpt: This Article Describes Diagnosing and Fixing the Frozen Resource Monitor App in Win11
keywords: Freeze Resource Monitor Windows 11,Fixed Resource Monitor Errors,Win11 Monitor Unfreezing Tips,Resolve Win11 Resource Lag,Troubleshoot Frozen Resource Monitor,Fixing Resource Monitor in Win11,Diagnose Windows 11 Freeze Issue
thumbnail: https://thmb.techidaily.com/368a70a14b371c8e08eacb0b3d4a99240a39fbb092918116ea6d8f331f8e83e6.jpg
---

## Diagnosing and Fixing the Frozen Resource Monitor App in Win11

 Resource Monitor is a Windows utility that monitors the use and performance of your computer's hardware resources. Unfortunately, it sometimes stops working or encounters issues, making it difficult to track system performance and manage resource usage.

 So, if you're having trouble getting the Resource Monitor tool working on your computer, check out the steps below to troubleshoot any issues and get it up and running again.

## What Causes the Resource Monitor App to Stop Working?

 Before we dive into solving the problem, let's first check what causes the Resource Monitor app to stop working correctly. There are a few potential causes you should consider.

 The most common cause of Resource Monitor not working is corrupted or outdated drivers. Outdated or incorrect drivers can prevent the software from running properly and cause functionality errors. Additionally, if there are hardware issues with your computer, such as a faulty power supply or RAM, problems with Resource Monitor could also arise.

 Finally, if you have recently installed new antivirus software on your computer, it could block access to the Resource Monitor program.

So, let's move on to the solution and fix this problem.

## 1\. Restart the Computer

![windows restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-restart.jpg)

 When troubleshooting software-related issues, a computer restart can often resolve them without resorting to complex solutions. Doing so refreshes all running programs and services while also clearing out any temporary files that might be causing problems.

 In most cases, this can get things back up and running without requiring extra effort. Plus, this solution is usually quick and easy since you only need to shut down your PC and wait for it to boot back up again. If you're having trouble restarting your PC, you can check out our guide on the [different ways you can restart Windows](https://www.makeuseof.com/windows-restart-methods/) .

## 2\. Change the DPI Settings

 Another possible fix for Resource Monitor not working on Windows is to change your DPI settings. Changing the scaling from 100% to 125% or higher on some computers can cause issues with Resource Monitor. Therefore, try adjusting it back to its original setting and check if the tool works again.

To change the DPI scale to its default settings, follow these steps:

1. Press**Win + I** on your keyboard to [open the Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. From the left pane, select**System** .
3. Then click**Display** on the right.
4. Under the**Scale & layout** section, click the drop-down menu next to the**Scale** option.  
![Change DPI Scale in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/change-dpi-scale-in-settings.jpg)
5. Choose the recommended value.

 Once you have made the changes, close the Settings window and run the Resource Monitor app to see if the problem is resolved.

## 3\. Run the System File Checker

 If restarting your computer and changing the DPI settings didn't work, running an SFC scan can often detect and repair any corrupted system files that might be causing problems.

To do this, follow these steps:

1. Right-click on Start and select**Run** from the menu list.
2. Type**cmd** in the text box and press**Ctrl + Shift + Enter** on your keyboard.
3. When the UAC popup appears on the screen, click**Yes** to open Command Prompt with admin access. If you want in-depth information, read our guide on [running the command prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) .  
![Run SFC Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-sfc-command.jpg)
4. Now in the elevated Command Prompt window, type in the command below and press Enter:  
sfc /scannow
5. Wait for the process to complete, then restart your PC.

## 4\. Check for Windows Updates

 It is also possible for an outdated version of Windows to cause this issue, so [manually check for any pending Windows updates](https://www.makeuseof.com/update-windows-manually/) and install them.

 Microsoft regularly releases new versions of Windows that fix bugs and improve performance, which makes updating worthwhile. Here's how to do it:

1. Press**Win + I** on your keyboard to launch the System Settings.
2. From the left side of the Settings menu, click**Windows Update** .
3. When Windows Update opens, click the**Check for updates** button.  
![Check for Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/check-for-updates.jpg)

 If there are any updates available, it will download and install them automatically. After the download completes, install the updates and restart your computer. After that, check to see if Resource Monitor is working.

## 5\. Uninstall the Latest Windows Updates

 If you recently updated your OS and there are no newer updates for it, the last update might have caused the issue. So, try uninstalling any recent update you may have installed, which could help resolve conflicts between the updates and existing system files that are causing problems with Resource Monitor.

1. Press**Win + I** on your keyboard to open the Settings menu
2. Select**Windows Update** from the left pane
3. Now go to the right and click on**Update history** .  
![Update history in Windows Update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/update-history-in-windows-update.jpg)
4. Scroll down to Related settings and click**Uninstall updates** .  
![Uninstall the latest Windows Update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-the-latest-windows-update.jpg)

 Then select any recent updates that you want to uninstall. After that, restart your computer and check if Resource Monitor is now working properly.

## 6\. Create a New User Account

 If you're still having issues, try [creating a new local user account](https://www.makeuseof.com/windows-11-create-local-user-account/) and see if that fixes the issue. This can be helpful if corrupted user profile data or settings cause the problem. To do so, follow the steps below:

1. Open the Settings app on your computer.
2. From the left, select**Accounts** .
3. Click**Other users** under Account settings.
4. Next to Add other users, click**Add account** .  
![Create a New User Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-a-new-user-account.jpg)
5. On the Microsoft account page, click **I don't have this person's sign-in information** .

 Then follow the instructions to add a new user account and then sign in with that account. Now open Resource Monitor and see if it's working properly.

## 7\. Troubleshoot in Clean Boot State

 When all else fails, try starting your computer in safe mode and see if the problem persists. If it does not, then background services and applications are possibly conflicting with startup items and causing this error to occur.

In such a case, you need to perform a clean boot as instructed below:

1. Open the**Run** dialog box.
2. Type**MSConfig** in the text box and hit Enter.
3. Check the**Selective startup** box on the General tab.  
![Perform-a-Clean-Boot-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Perform-a-Clean-Boot-1.jpg)
4. Uncheck the**Load startup items** box.
5. Switch to the**Services** tab and check the**Hide all Microsoft services** box.  
![Hide all Microsoft services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Hide-all-Microsoft-services.jpg)
6. Then click**Disable All** .
7. Go to the Startup tab and click the**Open Task Manager** link
8. Disable any services or programs that are active in Startup apps.

 Once you have done this, close Task Manager, then click**OK** on the MSConfig window to save these changes. Now restart your computer for them to take effect, then try using Resource Monitor to see if they work now.

## Resolve Resource Monitor Issues in Windows 11

 Resource Monitor helps you monitor the performance and usage of your system's resources, including memory, disk, and network activity. If you're having trouble accessing this tool, this guide may help.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://ai-voice-clone.techidaily.com/updated-2024-approved-how-to-make-an-animated-explainer-video/"><u>Updated 2024 Approved How to Make an Animated Explainer Video</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unknown-hardware-in-windows-1110/"><u>Troubleshooting Unknown Hardware in Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/utilizing-the-fn-key-operations-and-tips/"><u>Utilizing the FN Key: Operations and Tips</u></a></li>
<li><a href="https://win11.techidaily.com/upgrade-your-task-management-easy-run-tool-integration-on-windows/"><u>Upgrade Your Task Management: Easy Run Tool Integration on Windows</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-epic-soundscape-trending-audio-for-cutting-edge-youtube-short-videos-for-2024/"><u>[Updated] Epic Soundscape  Trending Audio for Cutting-Edge YouTube Short Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-a-microsoft-account-and-a-local-account-are-different-on-windows/"><u>6 Ways a Microsoft Account and a Local Account Are Different on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/cure-for-mcuicntexe-entry-point-loss-in-windows-systems/"><u>Cure for McUICnt.exe Entry Point Loss in Windows Systems</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-recommendation-best-websites-to-download-classical-ringtones/"><u>[New] Recommendation  Best Websites to Download Classical Ringtones</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-precision-in-replication-crafting-a-perfect-clone-on-the-worlds-stage-tiktok/"><u>In 2024, Precision in Replication  Crafting a Perfect Clone on the World's Stage, TikTok</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/extensive-audit-unveiling-the-dji-inspire-1-drone-for-2024/"><u>Extensive Audit  Unveiling the DJI Inspire 1 Drone for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/pro-tips-show-more-pins-on-windows-11-start/"><u>Pro Tips: Show More Pins on Windows 11 Start</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-code-0x0000004e-hiccups/"><u>Resolving Windows Code 0X0000004E Hiccups</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-device-not-recognized-fix-for-windows-users/"><u>Overcoming Device Not Recognized: Fix for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/harness-the-power-of-github-desktop-for-windows-os-devops/"><u>Harness the Power of GitHub Desktop for Windows OS DevOps</u></a></li>
<li><a href="https://win11.techidaily.com/refreshing-window-icons-on-windows/"><u>Refreshing Window Icons on Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-conquer-kinemaster-rule-the-meme-world/"><u>2024 Approved  Conquer KineMaster, Rule the Meme World</u></a></li>
<li><a href="https://win11.techidaily.com/a-fresh-start-for-your-computers-firewall-settings/"><u>A Fresh Start for Your Computer's Firewall Settings</u></a></li>
<li><a href="https://fox-access.techidaily.com/action-filming-at-its-peak-garmin-virb-ultra-30-analysis-for-2024/"><u>Action Filming at Its Peak  Garmin VIRB Ultra 30 Analysis for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-password-policy-setting-new-limit-post-failed-logins/"><u>Revamping Password Policy: Setting New Limit Post Failed Logins</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-extend-windows-10-shutdown-for-ongoing-processes/"><u>Strategies to Extend Windows 10 Shutdown for Ongoing Processes</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-your-system-top-5-tips-for-mastering-windows-folders/"><u>Supercharge Your System: Top 5 Tips for Mastering Windows Folders</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-xiaomi-redmi-k70-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Xiaomi Redmi K70 Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mysteries-of-sam-errors-windows-edition/"><u>Unraveling the Mysteries of SAM Errors, Windows Edition</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-reset-apple-id-and-apple-password-on-apple-iphone-12-by-drfone-ios/"><u>In 2024, How to Reset Apple ID and Apple Password On Apple iPhone 12</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-top-7-skype-hacker-to-hack-any-skype-account-on-your-vivo-v27e-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Skype Hacker to Hack Any Skype Account On your Vivo V27e | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-explore-advanced-techniques-making-a-difference-with-your-captivating-slow-motion-videos-and-photos-for-instagram/"><u>[New] In 2024, Explore Advanced Techniques  Making a Difference with Your Captivating Slow-Motion Videos & Photos for Instagram</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-ultimate-guide-to-infinix-note-30-vip-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to Infinix Note 30 VIP Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-x-recorder-for-pc-free-recording-software/"><u>[New] In 2024, X-Recorder for PC  Free Recording Software</u></a></li>
<li><a href="https://ai-topics.techidaily.com/what-is-talking-avatar/"><u>What Is Talking Avatar?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-tips-and-tricks-to-tell-if-your-apple-iphone-6s-is-unlocked-by-drfone-ios/"><u>In 2024, Tips And Tricks To Tell if Your Apple iPhone 6s Is Unlocked</u></a></li>
<li><a href="https://win11.techidaily.com/from-blank-canvases-to-dynamic-displays-on-win-1011/"><u>From Blank Canvases to Dynamic Displays on Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/pro-tips-for-maximizing-speed-and-efficiency-in-3d-painting/"><u>Pro Tips for Maximizing Speed and Efficiency in 3D Painting</u></a></li>
<li><a href="https://win11.techidaily.com/insightful-analysis-hibernations-role-in-windows/"><u>Insightful Analysis: Hibernation's Role in Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-get-your-video-dimensions-spot-on-for-instagram-sharing/"><u>[Updated] Get Your Video Dimensions Spot-On for Instagram Sharing</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-on-nokia-g42-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos on Nokia G42 5G</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-spotify-location-after-moving-to-another-country-on-gionee-f3-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Spotify Location After Moving to Another Country On Gionee F3 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/making-your-windows-11-pin-more-secure-and-elongated/"><u>Making Your Windows 11 PIN More Secure & Elongated</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-funniest-faces-learning-kinemaster/"><u>[New] Funniest Faces  Learning KineMaster</u></a></li>
<li><a href="https://win11.techidaily.com/from-start-menu-to-control-panel-a-guide/"><u>From Start Menu to Control Panel: A Guide</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/o-accelerate-subscriber-count-on-your-channel/"><u>How to Accelerate Subscriber Count on Your Channel</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-conquering-instagrams-video-challenges-head-on/"><u>[New] In 2024, Conquering Instagram's Video Challenges Head-On</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-functioning-automated-rules-in-microsoft-outlook/"><u>Restoring Functioning Automated Rules in Microsoft Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/pixelprecision-snag-9-tactics-to-reinstate-it/"><u>PixelPrecision Snag? 9 Tactics to Reinstate It</u></a></li>
<li><a href="https://win11.techidaily.com/windows-cab-files-explained-formatting-and-implementation/"><u>Windows CAB Files Explained: Formatting and Implementation</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/leshooting-why-are-your-shorts-thumbnails-hiding-in-2024/"><u>Troubleshooting  Why Are Your Shorts' Thumbnails Hiding, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-fix-nvidias-geforce-error-x0001-on-windows-1011/"><u>Steps to Fix Nvidia's GeForce Error X0001 on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/expertly-navigate-and-enhance-text-via-the-snipping-tool/"><u>Expertly Navigate and Enhance Text via the Snipping Tool</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-discover-how-to-share-your-screen-on-discord/"><u>[New] 2024 Approved  Discover How to Share Your Screen on Discord</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-list-of-pokemon-go-joysticks-on-motorola-moto-g34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, List of Pokémon Go Joysticks On Motorola Moto G34 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-enabling-windows-11-toolbar-elements/"><u>Guide to Enabling Windows 11 Toolbar Elements</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-reframe-your-videos-in-seconds-best-editor-options/"><u>Updated In 2024, Reframe Your Videos in Seconds Best Editor Options</u></a></li>
</ul></div>
