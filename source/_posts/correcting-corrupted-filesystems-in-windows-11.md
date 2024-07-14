---
title: Correcting Corrupted Filesystems in Windows 11
date: 2024-07-13T10:09:48.908Z
updated: 2024-07-14T10:09:48.908Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Corrupted Filesystems in Windows 11
excerpt: This Article Describes Correcting Corrupted Filesystems in Windows 11
keywords: FileSystemRepairWin11,FixWindows11FS,Win11FixFileError,CorrectCorruptFSWindows,WindowsFilesystemRecovery,RepairWindows11FSys,RecoverCORRUPTedFSWin11
thumbnail: https://thmb.techidaily.com/30c580f4aaa4373c8a4d05322fd912eb007bcd184d7b7f33639176575d3c4909.jpg
---

## Correcting Corrupted Filesystems in Windows 11

 A file system error can occur in Windows 10 and 11 when you try to open files or Microsoft Store apps. When such an error occurs, a message pops up that says, “File system error (code).” File system errors have variable error codes like -2147219195, -2147219196, -2147163893, and -1073741521.

 The causes of such errors vary, but the result is much the same. Users can’t open the files or apps for which file system errors arise. These general resolutions can fix a wide variety of file system errors in Windows 10 and 11.

## 1\. Run the SFC and DISM Command Line Tools

 File system errors can often be related to system file corruption. Windows 11 and 10 have the same SFC and DISM command-line tools for repairing system files and Windows system image. Running those utilities in the Command Prompt could feasibly resolve numerous file system errors.

 Our guide on [how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) tells you how to initiate an SFC scan. You can also run a Deployment Image Servicing Management scan in the Command Prompt before or after running the SFC tool. To do so, you’ll need to execute the following command:

`DISM.exe /Online /Cleanup-image /Restorehealth`

## 2\. Scan Your Hard Drive

 Hard drive integrity issues such as bad sectors also cause file system errors to occur in Windows 11/10\. For that reason, scanning your hard drive with the Check Disk tool is a recommended troubleshooting method for file system errors. The Check Disk utility (otherwise CHKDSK) scans for and repairs bad drive sectors detected. This is how you can run CHKDSK in the Command Prompt:

1. Open the file and app search box by pressing the**Win + S** key combination.
2. Select Command Prompt’s**Run as administrator** option within the search results to launch the app with elevated privileges.
3. Then type this command in the Prompt’s window and press**Enter** :  
`chkdsk c: /f /r`
4. You’ll need to press**Y** to schedule the scan for a restart.  
![The chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk.jpg)
5. Exit the Command Prompt window.
6. Click**Start > Power** to select**Restart** . The CHKDSK scan will start after the restart.

## 3\. Run the Windows Store App Troubleshooter

 If a file system error occurs when you try launching MS Store apps or opening files with them, the Windows Store App troubleshooter might be useful for fixing it. That troubleshooter is there to resolve issues that stop UWP apps from working as they should. These are the steps for opening the Windows Store App troubleshooter:

1. To access Settings, press the**Windows** logo key +**E** keyboard shortcut that opens that app.
2. Scroll down the tab and click a**Troubleshoot navigation** option.
3. Select**Other trouble-shooters** to bring up a list of tools for troubleshooting Windows.
4. Then press the**Run** button for launching the Windows Store App troubleshooter.  
![The troubleshooter list in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-apps-troubleshooter1.jpg)
5. Apply any suggestions the troubleshooter provides.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-app-window.jpg)

## 4\. Check That the Windows License Manager Service Is Running

 Some file system errors can arise for opening files with UWP apps when the Windows License Manager service is disabled. That’s a service required for MS Store infrastructure support, and apps downloaded from the store don’t always work right when it’s disabled. This is how you can check that service is enabled and start it if necessary:

1. Bring up the Windows search tool and input**Services** inside its text box.
2. Select**Services** within the search results.
3. Double-click**Windows License Manager Service** to access its properties window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-services-window2.jpg)
4. Click on the**Startup type** menu to open it and select**Automatic** .  
![The Windows License Manager server window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-license-service-manager.jpg)
5. If the service isn’t running, press**Start** within the properties window.
6. Select**Apply** to save settings for the Windows License Manager Service.
7. Click**OK** to close the Windows License Manager Service Properties window.

## 5\. Reinstall Any Affected App

 This potential solution is more applicable to fixing file system errors that occur for opening specific UWP apps. Reinstalling the app for which the error arises might resolve it in such a scenario. For example, users confirmed reinstalling Microsoft Photos can resolve file system error -2147219196.

 You can remove UWP apps with some of the methods in our guide for uninstalling software in Windows 11\. You can uninstall most apps with the Apps & Features tool in Settings. However, you might need to use the PowerShell method in our guide to remove some pre-installed Windows 11 apps.

![Apps & features in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/apps-features-window.jpg)

 When you’ve uninstalled the app, reinstall it from the MS Store. Bring up the Microsoft Store, and input the app’s title in its search box. Then select the app to reinstall in the search results, and click the**Get** button for it.

## 6\. Set Up a New Local User Account on Windows

 File system errors can arise because of user account issues. Such errors might not arise if you set up and utilize a new local user account in Windows 11\. That might not be the most ideal resolution, but you can migrate user files to a newly established account.

 Our guide on [how to fix Windows issues by creating new accounts](https://www.makeuseof.com/tag/fix-windows-issues-creating-new-user-account/) includes full instructions for how to apply this solution.

![The Add account button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-account-button.jpg)

## 7\. Restore Windows to an Earlier Date

 System Restore is a troubleshooting tool that can potentially address various causes for file system errors, be it system file corruption, app conflicts, or recent Windows updates. It fixes many things by restoring Windows to an earlier date (system snapshot). However, restoring Windows to an earlier time will only likely work if you can select a restore point that predates the file system error on your PC.

 To apply this potential solution, read through our guide to [utilizing System Restore and creating restore points](https://www.makeuseof.com/windows-11-create-restore-point/) . Select a restoration date that will take your PC back to a time when there wasn’t a system file error on it. The oldest restore point available is the most likely one to do that.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/system-restore-window.jpg)

 However, restoring Windows to a previous time removes software not installed on the restoration point’s date. So, it’s likely you’ll have to reinstall some apps after rolling back Windows. Clicking**Scan for affected programs** in System Restore provides an overview of software that will be removed for a restore point.

## 8\. Reset Windows

 This final system file error solution is the most drastic of all since it amounts to reinstalling Windows 10 or 11\. Factory resetting restores Windows to a default system state, which can fix many errors caused by registry, third-party software, and system file issues. If you can’t fix a system file error with any other potential fix in this guide, then resetting is the last thing to try.

 Windows 11 and 10 have a Reset this PC tool that makes it easy to factory reset the platform. That tool also includes an option that enables you to keep user files in the process. Our guide on [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) includes instructions for applying this potential resolution with this tool.

## Get File System Errors Sorted in Windows

 Users often report file system errors on support forums much the same as BSOD (Blue Screen of Death) and missing DLL file issues. You can't ignore them when they stop you from opening important user files or apps. Whatever file system error you need to fix in Windows 10 and 11, you’ll probably be able to resolve it with at least one of the potential resolutions above.

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-swift-playback-on-instagram-videos-mobiledesktop/"><u>[New] In 2024, Swift Playback on Instagram Videos (Mobile/Desktop)</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-unfocus-the-background-best-free-online-photo-blur-tools/"><u>Updated Unfocus the Background Best Free Online Photo Blur Tools</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-quick-steps-to-validate-your-youtube-login/"><u>[Updated] In 2024, Quick Steps to Validate Your YouTube Login</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-best-free-call-apps-on-android-ranks-them/"><u>[Updated] 2024 Approved  Best Free Call Apps on Android, Ranks Them</u></a></li>
<li><a href="https://win11.techidaily.com/uncomplicated-system-fixes-through-keyboard-shortcuts-on-windows/"><u>Uncomplicated System Fixes Through Keyboard Shortcuts on Windows</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-navigating-the-dancefloor-of-tiktoks-anime-rhythms-sounds-and-iconic-moments/"><u>[New] 2024 Approved  Navigating the Dancefloor of TikTok's Anime  Rhythms, Sounds & Iconic Moments</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-regain-basic-windows-settings-after-restart/"><u>Guide to Regain Basic Windows Settings After Restart</u></a></li>
<li><a href="https://win11.techidaily.com/conjuring-a-cohesive-file-landscape-in-win1011/"><u>Conjuring a Cohesive File Landscape in WIN10/11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-vn-video-editor-pro-review-does-it-live-up-to-the-hype/"><u>Updated 2024 Approved VN Video Editor Pro Review Does It Live Up to the Hype?</u></a></li>
<li><a href="https://win11.techidaily.com/skirting-persistent-login-prompt-issues-in-windows/"><u>Skirting Persistent Login Prompt Issues in Windows</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-discover-the-secret-to-perfect-twitter-video-formatting/"><u>New 2024 Approved Discover the Secret to Perfect Twitter Video Formatting</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-setback-preserving-saving-functionality-of-nvidia-cp/"><u>Overcoming Setback: Preserving Saving Functionality of Nvidia CP</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-ar-is-a-trend-these-days-here-you-can-browse-the-list-of-top-10-picks-for-ar-video-editing-apps/"><u>New AR Is a Trend These Days. Here, You Can Browse the List of Top 10 Picks for AR Video Editing Apps</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-how-to-alter-your-macs-snapshot-format-for-2024/"><u>[New] How to Alter Your Mac's Snapshot Format for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-interruptnothandled-error-on-win11/"><u>Eliminating the INTERRUPT_NOT_HANDLED Error on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/win-1011-customize-your-functional-keys-configuration/"><u>Win 10/11: Customize Your Functional Keys Configuration</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-the-ultimate-list-of-free-video-trimmers-for-windows-10/"><u>In 2024, The Ultimate List of Free Video Trimmers for Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-ms-teams-hurdle-error-80080300-in-win11/"><u>Overcoming MS Teams Hurdle Error 80080300 in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/w11s-moment-update-a-glimpse-at-the-next-gen-features/"><u>W11's Moment Update: A Glimpse at the Next-Gen Features</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/the-ultimate-guide-to-facebook-live-recording/"><u>The Ultimate Guide to Facebook Live Recording</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-repair-microsoft-outlook-problems-effectively/"><u>How to Repair Microsoft Outlook Problems Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/hidden-gems-of-windows-world-windows-11s-stealth-menu-secrets/"><u>Hidden Gems of Window's World: Windows 11’S Stealth Menu Secrets</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-10-shopping-powerhouses-where-to-buy-personalized-present-wrappers/"><u>[New] 10 Shopping Powerhouses  Where to Buy Personalized Present Wrappers</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-full-guide-to-catch-100-iv-pokemon-using-a-map-on-samsung-galaxy-a15-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Catch 100 IV Pokémon Using a Map On Samsung Galaxy A15 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-system-calls-fails-on-windows-devices/"><u>Overcoming System Calls Fails on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-diagnose-and-correct-disk-read-errors/"><u>How to Diagnose and Correct Disk Read Errors</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-0x80041015-problem-from-windows-ms-office/"><u>Eradicating 0X80041015 Problem From Windows MS Office</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-trendsetters-pictures-origins-explored/"><u>[Updated] Trendsetters' Pictures  Origins Explored</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-11s-6-unusual-visual-cues/"><u>Understanding Windows 11'S 6 Unusual Visual Cues</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-win11-how-to-resolve-stalled-file-transfers-4/"><u>Overcoming WIN11: How to Resolve Stalled File Transfers (4)</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/restoring-available-display-preferences-on-nvidia/"><u>Restoring Available Display Preferences on NVIDIA</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-your-smartphone-as-a-windows-microphone/"><u>How to Use Your Smartphone as a Windows Microphone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-6-unparalleled-mac-apps-for-video-grabbing/"><u>In 2024, 6 Unparalleled Mac Apps for Video Grabbing</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-interpreting-the-significance-of-blue-emojis-on-messenger/"><u>2024 Approved  Interpreting the Significance of Blue Emojis on Messenger</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-obs-studio-basics-full-guide-to-ps4-game-recording/"><u>2024 Approved  Obs Studio Basics - Full Guide to PS4 Game Recording</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-three-paths-to-archiving-every-engaging-second-of-your-disco-streaming-experience/"><u>[New] Three Paths to Archiving Every Engaging Second of Your Disco Streaming Experience</u></a></li>
<li><a href="https://win11.techidaily.com/no-snip-from-prtscan-how-to-prevent-launch-of-snipping-tool-in-windows-11/"><u>No Snip From PrtScan: How to Prevent Launch of Snipping Tool in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-accessing-your-iis-management-center/"><u>Quick Fixes for Accessing Your IIS Management Center</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-smart-choices-best-windows-camcorders-list/"><u>2024 Approved  Smart Choices  Best Windows Camcorders List</u></a></li>
<li><a href="https://win11.techidaily.com/jumpstart-your-virtual-machine-performance-with-six-windows-tricks/"><u>Jumpstart Your Virtual Machine Performance with Six Windows Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/premium-temperature-trackers-on-win-os/"><u>Premium Temperature Trackers on Win OS</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-easiest-guide-how-to-clone-samsung-galaxy-s24-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Easiest Guide How to Clone Samsung Galaxy S24 Phone? | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-platform-preference-opting-for-obstwitch-live/"><u>In 2024, Platform Preference  Opting for OBS/Twitch Live</u></a></li>
<li><a href="https://win11.techidaily.com/finding-lost-windows-proven-strategies-for-win11-users/"><u>Finding Lost Windows: Proven Strategies for Win11 Users</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-how-to-make-vimeo-videos/"><u>[Updated] How to Make Vimeo Videos</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-mindful-browsing-a-compendium-of-online-destinations-to-find-tranquility-and-relaxation-this-year-for-2024/"><u>Updated Mindful Browsing A Compendium of Online Destinations to Find Tranquility and Relaxation This Year for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-text-conversations-emoji-15-installation-guide-for-windows-11/"><u>Revamping Text Conversations: Emoji 15 Installation Guide for Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-a-working-guide-for-pachirisu-pokemon-go-map-on-zte-axon-40-lite-drfone-by-drfone-virtual-android/"><u>In 2024, A Working Guide For Pachirisu Pokemon Go Map On ZTE Axon 40 Lite | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-the-visual-vibrancy-of-a-frozen-windows-device/"><u>Reviving the Visual Vibrancy of a Frozen Windows Device</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-unlock-adobe-premieres-full-potential-top-15-plugins-free-download/"><u>Updated In 2024, Unlock Adobe Premieres Full Potential Top 15 Plugins (Free Download)</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-webcam-visuals-uncluttered-remove-obscurants/"><u>2024 Approved  Webcam Visuals Uncluttered  Remove Obscurants</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-leveraging-googles-board-tools-for-smooth-online-engagement-on-all-platforms/"><u>2024 Approved  Leveraging Google's Board Tools for Smooth Online Engagement on All Platforms</u></a></li>
<li><a href="https://facebook.techidaily.com/balancing-authenticity-and-promotion-on-your-social-media-profile/"><u>Balancing Authenticity and Promotion on Your Social Media Profile</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/breaking-barriers-making-your-post-a-sensation-on-fb-for-2024/"><u>Breaking Barriers  Making Your Post a Sensation on FB for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/win1011-solving-directdraw-glitches-quickly/"><u>Win10/11: Solving DirectDraw Glitches Quickly</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-after-effects-guide-to-elevating-song-visualization/"><u>New After Effects Guide to Elevating Song Visualization</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-breaking-barriers-youtube-marketing-mastery/"><u>[New] 2024 Approved  Breaking Barriers  YouTube Marketing Mastery</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-mastering-your-video-projects-with-superior-recorder-software/"><u>[New] In 2024, Mastering Your Video Projects with Superior Recorder Software</u></a></li>
<li><a href="https://win11.techidaily.com/tips-and-tricks-for-addressing-winscombsvc-errors-in-windows-os/"><u>Tips & Tricks for Addressing WinScombSvc Errors in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-1011s-share-issue-with-nvidia/"><u>Addressing Windows 10/11'S Share Issue with NVIDIA</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-failed-syncs-a-guide-to-onedrive-operations-on-windows/"><u>Fixing Failed Syncs: A Guide to OneDrive Operations on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/examining-the-role-and-relevance-of-wasd-in-windows/"><u>Examining the Role and Relevance of WASD in Windows</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/-makers-the-online-marvel-experience/"><u>Dream Makers  The Online Marvel Experience</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-secure-network-shadows-in-windows/"><u>Crafting Secure Network Shadows in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unzipping-complex-archives-a-windows-cli-experts-manual/"><u>Unzipping Complex Archives: A Windows CLI Expert's Manual</u></a></li>
<li><a href="https://win11.techidaily.com/why-ditch-bot-helmed-windows-key-creation/"><u>Why Ditch Bot-Helmed Windows Key Creation?</u></a></li>
<li><a href="https://win11.techidaily.com/one-os-multiple-worlds-windows-across-mobile-tablet-mac-and-desktop-realized/"><u>One OS, Multiple Worlds: Windows Across Mobile, Tablet, Mac & Desktop Realized</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-for-moving-programs-from-older-win-pcs-to-windows-11/"><u>Essential Steps for Moving Programs From Older Win PCs to Windows 11</u></a></li>
</ul></div>
