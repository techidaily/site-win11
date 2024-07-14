---
title: 3 Ways to Remove the Microsoft Store App From Windows 11
date: 2024-07-13T11:15:09.569Z
updated: 2024-07-14T11:15:09.569Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 3 Ways to Remove the Microsoft Store App From Windows 11
excerpt: This Article Describes 3 Ways to Remove the Microsoft Store App From Windows 11
keywords: Removing MS Store,Uninstalling Windows 11 Store,Eliminate Windows 11 App,Disable Microsoft Apps,Delete OS Store Icon,MS Store Uninstall Guide,Remove Windows 11 Apps
thumbnail: https://thmb.techidaily.com/549ca928829525c9c386345bc34f0e1c4ffcbb4613654a88c4a76774162c73c8.jpg
---

## 3 Ways to Remove the Microsoft Store App From Windows 11

 Microsoft Store is the go-to place for Windows users if they want to install an app. The app library is slowly expanding, and you will find all the popular apps without any difficulty. But sometimes the Microsoft Store application behaves abnormally and requires troubleshooting.

 But what if it still doesn’t work, even after repairing and resetting? There is no uninstall option in the Settings app, so it is possible to uninstall Microsoft Store? Well, it is possible to remove and reinstall the Microsoft Store app. Here’s how.

## Why Should You Uninstall the Microsoft Store App?

 Microsoft Store houses all the useful and popular applications for Windows devices. Moreover, it guarantees safe and malware-free application downloads. But if the app fails to start or doesn’t work properly, removing it makes sense.

 But don’t worry. You can remove the app and then reinstall it if you want. Reinstallation can fix persistent issues with the current version of the Microsoft Store app. It will remove the current app installation and all its related files and corrupt data. After that, you can reinstall the Microsoft app with a single command.

## How to Uninstall Microsoft Store App From Windows 11

 You can remove the Microsoft Store app from Windows 11 using the winget tool and run it using the command prompt. In addition, you can use the PowerShell cmdlet to remove the Microsoft Store application package from your system or use a batch file.

### 1\. Using Winget

 Winget is a handy Windows package manager tool available with the newer releases of Windows 10 and 11\. It makes it ridiculously easy to search and manage applications on your system. You can use it to remove any application, even the Microsoft Store app from your system. Here’s how:

1. Press the**Win + R** key to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press the**Ctrl + Shift + Enter** keys to launch the Command Prompt with administrator privileges.
2. Now, we need to locate the ID of the Microsoft Store app installed on the system. Type the following command in the command prompt window and press the enter key:**Winget list Store**
3. Winget will list all the installed programs on your system containing the string “store” in their name. Find the Microsoft Store app in the list and**copy** its**ID** .
4. After that, you need to run the uninstall command using winget. The syntax is**winget uninstall \[app ID\]** . So, the command will be:  
winget uninstall Microsoft.WindowsStore_8wekyb3d8bb
5. Press enter to execute the command and wait for it to execute successfully.  
![Uninstall Microsoft Store App using winget](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-winget.jpg)
6. Type**exit** in the command prompt window and press enter to close it.

### 2\. Using PowerShell

 Before winget was officially integrated into Windows 10 and 11, there was a method to [remove the Microsoft Store app using PowerShell](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) . The method still works and all you need to do is list the package name and then use the**Remove-AppxPackage** cmdlet to uninstall the Microsoft Store app from your system. Make sure to run PowerShell with elevated permissions.

### 3\. Using a Batch File

 If you want to save the hassle of typing commands every time you want to uninstall the Microsoft Store app, you can use a batch file. It will help you to remove Microsoft Store app from your system in a couple of clicks whenever the normal troubleshooting methods don’t work for you. Repeat the following steps:

1. Press**Win + D** to switch to the Desktop. Right-click on the Desktop and select the**New > Text Document** option.
2. Open the newly created text document file on the desktop. A Notepad window will pop up. Paste the following text in it:  
@echo off winget uninstall "Microsoft Store" exit
3. Now, press**Ctrl + Shift + S** to open the "Save as" window. Name the batch file as**UninstallStore.bat** and keep the**Save as** type option as**All files** .  
![Uninstall Microsoft Store App using batch file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-microsoft-store-app-using-batch-file.jpg)
4. Click on the**Save** button. Close the Notepad window.
5. Press**Win + D** to switch to the desktop again. Right-click on the batch file and select the**Run as administrator** option from the context menu.
6. A command prompt window will open, run the Microsoft Store app uninstallation command, and close automatically. You don’t need to interact with the window.
7. Open the Start menu and search for Microsoft Store. You won’t find any matching app on your system.

## Easily Remove the Microsoft Store From Windows

 Windows 10 and 11 don’t offer an option to uninstall Microsoft Store. So, you are only left at the mercy of a system restore or reset. However, you can now uninstall the Microsoft Store app from your system using any of the three methods mentioned above. You can also reinstall it using the PowerShell cmdlet and continue using the app again.


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
<li><a href="https://win11.techidaily.com/automating-windows-11-app-installation-a-guide-to-winstall/"><u>Automating Windows 11 App Installation: A Guide to Winstall</u></a></li>
<li><a href="https://win11.techidaily.com/alert-essential-windows-processes-to-watch-for-malware/"><u>Alert: Essential Windows Processes to Watch for Malware</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/unleashing-revenue-with-review-videos-of-household-items/"><u>Unleashing Revenue with Review Videos of Household Items</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-software-removal-crafting-wins-context-menu-aids/"><u>Accelerating Software Removal: Crafting Win's Context Menu Aids</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/connecting-twitters-vids-with-fb-audience/"><u>Connecting Twitter's Vids with FB Audience</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-step-by-step-guidehow-to-stream-on-discord/"><u>In 2024, [Step-by-Step Guide]How to Stream on Discord</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-app-guard-features-with-graphical-upgrades-on-edge/"><u>Augmenting App Guard Features with Graphical Upgrades on Edge</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-system-awakening-tweak-windows-11-boot-timeout/"><u>Accelerating System Awakening: Tweak Windows 11 Boot Timeout</u></a></li>
<li><a href="https://win11.techidaily.com/activate-and-personalize-your-pcs-audio-with-windows-11-mixer/"><u>Activate and Personalize Your PC's Audio with Windows 11 Mixer</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-optimal-efficiency-nircmd-tips-for-mastering-windows-11/"><u>Achieve Optimal Efficiency: NirCmd Tips for Mastering Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-nokia-c110-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Nokia C110 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-faulty-timed-lock-screen-issue-windows/"><u>Addressing Faulty Timed Lock Screen Issue Windows</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-turning-xmlssattml-files-into-srt-formats-strategies-and-techniques/"><u>In 2024, Turning XML/SSA/TTML Files Into SRT Formats  Strategies and Techniques</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-art-of-magnification-in-roblox-worlds/"><u>In 2024, The Art of Magnification in Roblox Worlds</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-realme-narzo-60x-5g-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from Realme Narzo 60x 5G to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-macs-finest-the-ultimate-mp3-conversion-software-roundup-for-2024/"><u>New Macs Finest The Ultimate MP3 Conversion Software Roundup for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/automation-bane-keep-your-windows-backdrop-steady/"><u>Automation Bane: Keep Your Windows Backdrop Steady</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-pixelpioneer-mastering-the-art-of-screen-capture-for-2024/"><u>[New] PixelPioneer  Mastering the Art of Screen Capture for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/harmonizing-soundscape-and-aesthetics-showcasing-audio-signals-in-visual-forms-and-animating-them-for-cinematic-vision-in-adobe-audition-pro-master-for-2024/"><u>Harmonizing Soundscape and Aesthetics Showcasing Audio Signals in Visual Forms & Animating Them for Cinematic Vision in Adobe Audition Pro Master. For 2024</u></a></li>
<li><a href="https://win11.techidaily.com/averting-unwanted-windows-store-automatization/"><u>Averting Unwanted Windows Store Automatization</u></a></li>
<li><a href="https://youtube-help.techidaily.com/expert-smartphone-photo-and-film-capture-iphoneandroid-comparison-for-2024/"><u>Expert Smartphone Photo & Film Capture  IPhone/Android Comparison for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/mapping-media-memorable-ends/"><u>Mapping Media Memorable Ends</u></a></li>
<li><a href="https://win11.techidaily.com/adept-methods-for-switching-file-types-in-windows/"><u>Adept Methods for Switching File Types in Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-real-time-screen-replay-on-chrome-pcs/"><u>[New] Real-Time Screen Replay on Chrome PCs</u></a></li>
<li><a href="https://win11.techidaily.com/adjust-desktop-presence-embedding-this-pc-icons/"><u>Adjust Desktop Presence: Embedding 'This PC' Icons</u></a></li>
<li><a href="https://win11.techidaily.com/amd-graphics-update-essentials-for-windows-11-users/"><u>AMD Graphics Update Essentials for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-zeroxc000003e-problem-in-pc-application-startup/"><u>Addressing ZeroXc000003e Problem in PC Application Startup</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-from-novices-to-professionals-free-guide-on-google-meet-mastery/"><u>[New] 2024 Approved  From Novices to Professionals  Free Guide on Google Meet Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-cleanup-banishing-bloatware-on-win11/"><u>Accelerated Cleanup: Banishing Bloatware on Win11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-commanding-attention-crafting-podcast-starters/"><u>2024 Approved  Commanding Attention  Crafting Podcast Starters</u></a></li>
<li><a href="https://win11.techidaily.com/autonomous-windows-update-an-offline-methodology/"><u>Autonomous Windows Update: An Offline Methodology</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-navigating-the-art-of-iptv-screen-recording-for-2024/"><u>[Updated] Navigating the Art of IPTV Screen Recording for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-breaking-free-from-windows-movie-maker-top-alternatives-for-2024/"><u>Updated Breaking Free From Windows Movie Maker Top Alternatives for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-to-do-if-your-apple-iphone-14-pro-max-has-bad-esn-or-blacklisted-imei-by-drfone-ios/"><u>In 2024, What to do if your Apple iPhone 14 Pro Max has bad ESN or blacklisted IMEI?</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-sync-failures-with-microsoft-to-do/"><u>Addressing Sync Failures with Microsoft To Do</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-v22h2-update-installation-obstacle-in-win11/"><u>Addressing V22H2 Update Installation Obstacle in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/accessible-windows-10-navigating-as-a-first-timer/"><u>Accessible Windows 10: Navigating as a First-Timer</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-perfect-xbox-audio-with-windows-1011/"><u>Achieving Perfect Xbox Audio with Windows 10/11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-mastering-the-art-of-personalizing-video-covers-for-facebook/"><u>[New] Mastering the Art of Personalizing Video Covers for Facebook</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/integrated-upload-sending-vids-to-twitter-and-tumblr/"><u>Integrated Upload  Sending Vids to Twitter and Tumblr</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-heres-a-step-by-step-guide-for-the-powerdirector-color-match-process-also-check-out-the-professional-and-quick-powerdirector-alternative-if-yo/"><u>2024 Approved Heres a Step-by-Step Guide for the PowerDirector Color Match Process! Also, Check Out the Professional and Quick PowerDirector Alternative if You Find It a Bit Time-Consuming and Manual</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-windows-navigation-methods-without-ls-command/"><u>Advanced Windows Navigation Methods Without LS Command</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-crafting-engaging-captions-for-viral-tiktok-videos/"><u>[Updated] In 2024, Crafting Engaging Captions for Viral TikTok Videos</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-wsl-2s-error-4294967295-on-a-win-os/"><u>Addressing WSL 2'S ERROR 4294967295 on a Win OS</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-evaluating-engagement-a-side-by-side-look-at-tiktok-and-snap-for-2024/"><u>[New] Evaluating Engagement  A Side-by-Side Look at TikTok & Snap for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/android-extension-in-w11-workspace-enhancing-productivity/"><u>Android Extension in W11 Workspace: Enhancing Productivity</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-jvm-not-created-a-windows-solution/"><u>Addressing JVM Not Created: A Windows Solution</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-full-control-with-admin-cmd-role/"><u>Achieve Full Control with Admin CMD Role</u></a></li>
<li><a href="https://win11.techidaily.com/assess-if-your-system-qualifies-for-new-windows-11/"><u>Assess if Your System Qualifies for New Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/asus-s15-oled-a-blend-of-class-and-convenience-for-students/"><u>Asus S15 OLED - A Blend of Class and Convenience for Students</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-reverse-reality-expert-tips-for-turning-images-upside-down-on-insta/"><u>[New] Reverse Reality  Expert Tips for Turning Images Upside Down on Insta</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-mobile-devices-for-windows-mic-input/"><u>Amplify Mobile Devices for Windows Mic Input</u></a></li>
<li><a href="https://win11.techidaily.com/alter-display-angle-in-windows-settings/"><u>Alter Display Angle in Windows Settings</u></a></li>
<li><a href="https://win11.techidaily.com/art-software-showdown-windows-programs-vs-procreate/"><u>Art Software Showdown: Windows Programs Vs. Procreate</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-the-account-lockout-counter-following-unsuccessful-logins-in-w10w11/"><u>Adjusting the Account Lockout Counter Following Unsuccessful Logins in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/ascending-to-top-level-windows-management/"><u>Ascending to Top-Level Windows Management</u></a></li>
<li><a href="https://win11.techidaily.com/analyzing-local-file-transmission-methods-which-fits-best/"><u>Analyzing Local File Transmission Methods: Which Fits Best?</u></a></li>
<li><a href="https://extra-information.techidaily.com/transformative-experience-a-comprehensible-guide-to-google-photos/"><u>Transformative Experience  A Comprehensible Guide to Google Photos</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-0x8007000f-on-task-sequences/"><u>Addressing Windows Error 0X8007000f on Task Sequences</u></a></li>
<li><a href="https://win11.techidaily.com/adding-directories-to-your-windows-11-quick-access-menu/"><u>Adding Directories to Your Windows 11 Quick Access Menu</u></a></li>
<li><a href="https://extra-tips.techidaily.com/exclusive-lineup-all-angle-recorders/"><u>Exclusive Lineup  All-Angle Recorders</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-ultimate-source-guide-4-top-skype-ringtones/"><u>[New] The Ultimate Source Guide  4 Top Skype Ringtones</u></a></li>
<li><a href="https://win11.techidaily.com/aligning-chromes-timeline-error-on-windows-machines/"><u>Aligning Chrome's Timeline Error on Windows Machines</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/unleash-the-power-of-video-metadata-on-mac-8-editor-recommendations-for-2024/"><u>Unleash the Power of Video Metadata on Mac 8 Editor Recommendations for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/ultimate-review-best-camcorders-to-try/"><u>Ultimate Review  Best Camcorders to Try</u></a></li>
</ul></div>
