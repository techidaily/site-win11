---
title: Unraveling the Mystery of Windows' Error 0X80073D26
date: 2024-07-13T10:13:46.579Z
updated: 2024-07-14T10:13:46.579Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unraveling the Mystery of Windows' Error 0X80073D26
excerpt: This Article Describes Unraveling the Mystery of Windows' Error 0X80073D26
keywords: WinError0X80073D26,WindowsFatalUIStall,FixingUiErrorWindows,ErrorCode0x80073D26Win,UnravelingUiFailError,ResolvingWindowUIException,DebuggingError0X8073D26
thumbnail: https://thmb.techidaily.com/14af88c4727edfc68754682f8d9e5a16b4632ead51b56f451896cf5d83dd52e4.jpg
---

## Unraveling the Mystery of Windows' Error 0X80073D26

 Error 0x80073D26 is an issue that users have widely reported occurring when trying to install or play Xbox Game Pass titles via Microsoft Store. When this issue arises, users get redirected to install the Gaming Services app in the Microsoft Store. Users then see the “Something unexpected happened” error 0x80073D26 message when they try to install (or update) Gaming Services.

 Players can’t enjoy their Xbox Game Pass titles because of error 0x80073D26, which makes this an annoying issue for Xbox Game Pass users. This is how you can fix the Microsoft Store error 0x80073D26 in Windows

## 1\. Run the Windows Store App Troubleshooting Tool

 This isn’t the most likely solution for error 0x80073D26, but it’s worth trying since Microsoft Store is a UWP app. Running the Windows Store App troubleshooter might detect a Microsoft Store issue and provide a fix. These are the steps for running the Windows Store App troubleshooting utility:

1. Open Settings and click **System** to view that tab.
2. Next, select **Troubleshoot** to reach three troubleshooting navigation options.
3. Bring up the list of troubleshooting tools by clicking **Other trouble-shooters**.
4. Then click **Run** to launch the Windows Store Apps troubleshooting tool.  
![The Run button for the Windows App Store troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-app-store-troubleshooter.jpg)
5. Apply all troubleshooting suggestions provided within Windows Store Apps window.  
![The Windows Store Apps window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-store-app-troubleshooter.jpg)

 You can run the same troubleshooter tool in Windows 10, but the steps for accessing it are a bit different. Click **Update & Security** \> **Troubleshoot** \> **Additional troubleshooters** in Windows 10’s Settings app. Then select **Windows Store Apps** \> **Run the troubleshooter** to get troubleshooting.

## 2\. Repair and Reset the Microsoft Store App

 Accumulated and corrupted Microsoft Store cache data is a potential cause for error 0x80073D26\. Resetting the Microsoft Store app via Settings or the Command Prompt will clear the app’s data. Try applying both methods in this guide to resetting Microsoft Store. Also, select the **Repair** option for the Microsoft Store just above its **Reset** button in Settings to see if that resolves the issue.

![The Reset button for Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button-1.jpg)

## 3\. Edit the Registry

 One of the most widely confirmed fixes for error 0x80073D26 is to enter the Registry and delete the GamingServices and GamingServicesNet Registry keys. Although confirmed to work, we still recommend users [back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before deleting keys. Then follow these steps for editing the registry:

1. Open the Windows Run accessory by right-clicking **Start** on your taskbar and selecting the **Run** option.
2. Input the **regedit** Run command and click **OK** to [launch the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Copy and paste this key location in the registry address bar:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services`
4. Right-click the **GamingServices** subkey within the Services key to select **Delete** \> **Yes**.  
![The Delete registry key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/delete-option-1.jpg)
5. Click the **GamingServicesNet** key with the mouse’s right button and select the **Delete** \> **Yes** options.
6. Exit Registry Editor and restart your PC.

## 5\. Reinstall the Microsoft Gaming Service

 One of Microsoft’s official resolutions for error 0x80073D26 is to reinstall Gaming Service. This potential solution involves entering three PowerShell commands that will remove the Gaming Service app along with associated registry entries. These are the steps for applying this potential fix:

1. Activate Windows Search by pressing **Win + S**.
2. Enter **PowerShell** inside the file search tool.
3. Open PowerShell with admin rights by right-clicking that app in the search results and selecting **Run as Administrator**.
4. Next, remove the Gaming Service app by entering this command and hitting **Enter**:  
`Get-AppxPackage *gaming services* -allusers | remove-appxpackage -allusers`  
![The remove-app package command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-app-package-command.jpg)
5. Then input these separate commands, pressing **Return** after each:  
`Remove-Item -Path "HKLM:\System\CurrentControlSet\Services\GamingServices" -recurse  

Remove-Item -Path "HKLM:\System\CurrentControlSet\Services\GamingServicesNet" -recurse` 
![The remove-app package command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-app-package-command.jpg)
6. Close out of PowerShell to restart Windows.
7. Reopen Powershell and execute the following command:  
`start ms-windows-store://pdp/?productid=9MWPM2CQNLHN`
8. Then click the **Get** button for installing Gaming Service.

## 5\. Perform Some Generic Windows Fixes for Errors

 Windows is by no means impervious to errors. Fortunately, there are some tricks you can apply to almost every error, including this one.

### Repair System Files

![The Reset button for Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button-1.jpg)

 To begin with, try repairing system files to see if there are any issues. You can do that by executing a System File Checker scan within the Command Prompt. That tool will check for and repair corrupted system files detected when you run its command. To apply this potential fix, follow the instructions in our [how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide.

### Set Windows to Clean Boot

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-services-tab.jpg)

 Another possibility is that a software conflict might be causing error 0x80073D26 to occur on your PC. Setting Windows to clean boot by disabling third-party startup items will likely eliminate such a potential cause. That will stop third-party apps and services that could be conflicting with the Microsoft Store from automatically starting.

 To apply this fix, check out this guide about [clean-booting Windows 10 or 11](https://www.makeuseof.com/clean-boot-windows-11/). Disable startup programs in Task Manager and services in MS Config as covered within that guide; then restart your PC and try installing Microsoft Store games again to see if the issue persists.

### Reinstall the Microsoft Store

![The remove Microsoft Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-microsoft-store-command.jpg)

 Some users might need to reinstall the Microsoft Store to fix error 0x80073D26\. Such a resolution might be necessary for fixing wider issues with the Microsoft Store app other potential solutions don’t address.

 There isn’t a standard uninstall option available for Microsoft Store. So, you’ll have to reinstall that app with two PowerShell commands. Our guide about [how to reinstall the Microsoft Store](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) tells you how to apply this potential fix.

### Perform an In-Place Windows Upgrade

 Some Microsoft Store users have also fixed error 0x80073D26 by performing an in-place Windows upgrade. An in-place upgrade is a method for installing the latest Windows 11/10 version without losing any installed software or user files.

 This will likely fix the 0x80073D26 error because it will refresh all of the system's registry entries, the system files, and also upgrade Windows to the latest version.

 Performing a Windows 11 in-place upgrade is relatively straightforward. All you need to do is download the latest Windows 11 ISO file, open it up, and launch the setup wizard from there. Our article about [performing an in-place upgrade of Windows 11](https://www.makeuseof.com/in-place-upgrade-windows-11/) includes full guidelines for how to do this.

![The Windows 11 Setup window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-11-setup-window2.jpg)

 You can also perform a Windows 10 in-place upgrade much the same. One difference is that you’ll need to download a Windows 10 Setup file by clicking **Download tool** on the [Microsoft Windows 10 download webpage](https://www.microsoft.com/en-gb/software-download/windows10). Then select **Upgrade this PC** now in the Windows 10 Setup wizard to install the latest version of the OS.

## Enjoy the Best Xbox Game Pass Games Available on the Microsoft Store

 It’s very likely the potential resolutions covered in this guide will fix error 0x80073D26, as some of them are widely confirmed to work. Hopefully, you can get this error fixed and get back into gaming.

 Players can’t enjoy their Xbox Game Pass titles because of error 0x80073D26, which makes this an annoying issue for Xbox Game Pass users. This is how you can fix the Microsoft Store error 0x80073D26 in Windows



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/tackling-windows-11s-camera-issue-fixing-a00f425d-error/"><u>Tackling Windows 11'S Camera Issue: Fixing A00F425D Error</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-how-to-maximize-your-photos-with-samsungs-image-enhancers/"><u>In 2024, How to Maximize Your Photos with Samsung's Image Enhancers</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-changing-gender-representation-in-social-media-images/"><u>[Updated] 2024 Approved  Changing Gender Representation in Social Media Images</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-get-your-data-on-site-quickly-5-best-techniques-for-computer-transfer-for-2024/"><u>[Updated] Get Your Data On-Site Quickly  5 Best Techniques for Computer Transfer for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-improper-thx-surround-in-windows/"><u>Addressing Improper THX Surround in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-learning-7-strategies-for-windows-users/"><u>Enhancing Learning: 7 Strategies for Windows Users</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/expert-insights-on-saving-smartphone-moments/"><u>Expert Insights on Saving Smartphone Moments</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-your-yuzu-gameplay-speed/"><u>Amplify Your Yuzu Gameplay Speed</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-recording-and-incorporating-narration-a-step-by-step-approach-for-todays-videos/"><u>New 2024 Approved Recording & Incorporating Narration A Step-by-Step Approach for Todays Videos</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-reset-a-xiaomi-14-phone-that-is-locked-by-drfone-android/"><u>In 2024, How to Reset a Xiaomi 14 Phone that is Locked?</u></a></li>
<li><a href="https://win11.techidaily.com/rewind-records-key-tools-to-modify-files-creation-dates/"><u>Rewind Records: Key Tools to Modify File's Creation Dates</u></a></li>
<li><a href="https://win11.techidaily.com/alter-viewer-angle-in-windows-setup/"><u>Alter Viewer Angle in Windows Setup</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-rapid-rise-rapid-recognition-youtubes-quick-climbing-view-count-milestones/"><u>In 2024, Rapid Rise, Rapid Recognition – YouTube's Quick-Climbing View Count Milestones</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-yearly-showcase-superior-business-simulations-for-mobilepc/"><u>[New] Yearly Showcase  Superior Business Simulations for Mobile/PC</u></a></li>
<li><a href="https://win11.techidaily.com/conducting-harmonious-auditory-performance-in-windows/"><u>Conducting Harmonious Auditory Performance in Windows</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/viral-video-victories-the-daily-top-10-twitch-videos-for-2024/"><u>Viral Video Victories  The Daily Top 10 Twitch Videos for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-instant-record-and-commentary-assistive-software/"><u>[Updated] 2024 Approved  Instant Record & Commentary Assistive Software</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-who-skipped-my-story-unfollowers-scan/"><u>[Updated] 2024 Approved  Who Skipped My Story? Unfollowers Scan</u></a></li>
<li><a href="https://win11.techidaily.com/dxvk-uncovered-enhancing-win-based-gameplay-dynamics/"><u>DXVK Uncovered: Enhancing Win-Based Gameplay Dynamics</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-universal-unlock-pattern-for-realme-narzo-60-5g-by-drfone-android/"><u>In 2024, Universal Unlock Pattern for Realme Narzo 60 5G</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-flip-the-script-ios-method-to-reverse-vids/"><u>2024 Approved  Flip the Script  IOS Method to Reverse Vids</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-best-action-cameras-on-wheels-top-5-picks-for-23-riders/"><u>[New] In 2024, Best Action Cameras on Wheels – Top 5 Picks for '23 Riders</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-essential-guide-to-html5s-most-acclaimed-tools/"><u>2024 Approved  The Essential Guide to HTML5's Most Acclaimed Tools</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-clipchamp-solve-windows-11-install-problems/"><u>Unlocking ClipChamp: Solve Windows 11 Install Problems</u></a></li>
<li><a href="https://win11.techidaily.com/6-tips-to-improve-your-wsl-2-docker-experience-on-windows/"><u>6 Tips to Improve Your WSL 2 Docker Experience on Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-astronaut-eyes-choosing-the-finest-fps-games/"><u>[Updated] Astronaut Eyes  Choosing the Finest FPS Games</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-an-inactive-firewall-a-step-by-step-guide/"><u>Bypassing an Inactive Firewall: A Step-by-Step Guide</u></a></li>
<li><a href="https://facebook.techidaily.com/essential-tips-for-fb-privacy-settings/"><u>Essential Tips for FB Privacy Settings</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-extracting-sids-from-users-on-windows-11/"><u>Unraveling the Mystery: Extracting SIDs From Users on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/creating-a-personalized-calendar-experience-with-windows-outlook/"><u>Creating a Personalized Calendar Experience with Windows Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-covert-query-beam-of-windows-11/"><u>Unveiling the Covert Query Beam of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-accessibility-5-ways-to-open-windows-help-hub/"><u>Enhance Accessibility: 5 Ways to Open Windows Help Hub</u></a></li>
<li><a href="https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>Is pgsharp legal when you are playing pokemon On Xiaomi Redmi Note 12 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/dual-screen-delight-personalized-pixels-per-monitor-of-windows-1011/"><u>Dual Screen Delight: Personalized Pixels per Monitor of Windows 10/11</u></a></li>
<li><a href="https://extra-information.techidaily.com/kinetic-keywords-animation-mastery-for-social-media-captions/"><u>Kinetic Keywords  Animation Mastery for Social Media Captions</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-crafting-content-for-success-a-step-by-step-channel-guide/"><u>2024 Approved  Crafting Content for Success  A Step-by-Step Channel Guide</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-your-windows-experience-adding-contextual-items/"><u>Upgrading Your Windows Experience: Adding Contextual Items</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-your-nokia-g310-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>How to Mirror Your Nokia G310 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-quick-and-easy-techniques-for-standardizing-sound-amplitude/"><u>2024 Approved Quick and Easy Techniques for Standardizing Sound Amplitude</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-unparalleled-editing-experience-vimeo-edition-awaits/"><u>[New] In 2024, Unparalleled Editing Experience  Vimeo Edition Awaits</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-ai-capabilities-at-ms-store/"><u>Delving Into AI Capabilities at MS Store</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-top-12-html5-videophones-for-optimal-viewing/"><u>[Updated] Top 12 HTML5 Videophones for Optimal Viewing</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-gaming-potential-android-on-win-11-through-google-services-access/"><u>Unlock Gaming Potential: Android on Win 11 Through Google Services Access</u></a></li>
<li><a href="https://win11.techidaily.com/setting-failed-logon-retry-timeframe-in-win-1011/"><u>Setting Failed Logon Retry Timeframe in Win 10/11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-vivo-y200-drfone-by-drfone-virtual-android/"><u>In 2024, Methods to Change GPS Location On Vivo Y200 | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-capturing-the-essence-the-best-windows-1110-recorders-ranked/"><u>[Updated] 2024 Approved  Capturing the Essence  The Best Windows 11/10 Recorders Ranked</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-regain-control-over-non-operational-media-playback/"><u>Strategies to Regain Control Over Non-Operational Media Playback</u></a></li>
<li><a href="https://win11.techidaily.com/an-effective-guide-to-fix-error-0xc0000001-on-windows-pcs/"><u>An Effective Guide to Fix Error 0XC0000001 on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/winx-fix-guide-for-geforce-xs-cant-retrieve-settings/"><u>WinX Fix Guide for GeForce X's Can’t Retrieve Settings</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/locked-out-of-iphone-15-pro-max-5-ways-to-get-into-a-locked-iphone-15-pro-max-drfone-by-drfone-ios/"><u>Locked Out of iPhone 15 Pro Max? 5 Ways to get into a Locked iPhone 15 Pro Max | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionizing-gaming-with-dxvk-the-windows-perspective/"><u>Revolutionizing Gaming with DXVK - The Windows Perspective</u></a></li>
<li><a href="https://win11.techidaily.com/ai-copilot-in-windows-11-enhancing-user-efficiency/"><u>AI Copilot in Windows 11: Enhancing User Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-windows-visual-aid-the-cursor/"><u>Tailoring Your Window's Visual Aid: The Cursor</u></a></li>
<li><a href="https://win11.techidaily.com/win-friendly-tools-the-8-best-video-editing-picks/"><u>Win-Friendly Tools: The 8 Best Video Editing Picks</u></a></li>
<li><a href="https://win11.techidaily.com/win11s-dns-cache-how-to-clear-and-maintain-efficiency/"><u>Win11's DNS Cache: How to Clear and Maintain Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-unhandled-exception-strategies-to-mitigate-on-pc/"><u>Simplifying Unhandled Exception: Strategies to Mitigate on PC</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-multi-screen-setup-on-windows-11-os/"><u>Streamlining Multi-Screen Setup on Windows 11 OS</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-key-approaches-to-microphone-and-computer-speaker-documentation/"><u>[Updated] Key Approaches to Microphone & Computer Speaker Documentation</u></a></li>
<li><a href="https://win11.techidaily.com/best-7-free-players-for-your-pcs-viewing-pleasure-win/"><u>Best 7 Free Players for Your PC's Viewing Pleasure (Win)</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-a-simple-way-to-get-kinemaster-on-your-mac-download-and-install/"><u>New 2024 Approved A Simple Way to Get KineMaster on Your Mac Download and Install</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-channel-building-through-characters-and-plot-twists/"><u>2024 Approved  Channel-Building Through Characters and Plot Twists</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-motorola-moto-g14-drfone-by-drfone-virtual-android/"><u>In 2024, Will Pokémon Go Ban the Account if You Use PGSharp On Motorola Moto G14 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-disabling-error-0xc00000f-on-pc/"><u>Solutions for Disabling Error 0Xc00000f on PC</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-more-disk-room-in-windows-here-are-the-7-best-aids/"><u>Unleash More Disk Room in Windows - Here Are the 7 Best Aids</u></a></li>
<li><a href="https://extra-hints.techidaily.com/behind-the-scenes-of-podcast-scripts-tips-and-examples-for-2024/"><u>Behind the Scenes of Podcast Scripts  Tips and Examples for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/conquer-file-management-crafting-multitudes-of-subfolders-instantly/"><u>Conquer File Management: Crafting Multitudes of Subfolders Instantly</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-yoga-enthusiasts-go-to-guide-on-youtube/"><u>[New] 2024 Approved  Yoga Enthusiasts' Go-To Guide on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/10-solutions-when-wifi-detection-fails-in-windows-11/"><u>10 Solutions When Wifi Detection Fails in Windows 11</u></a></li>
</ul></div>
