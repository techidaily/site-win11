---
title: "Foster Innovation for Privacy Protection: Explore Cutting-Edge Technologies Like Onboard Anonymization Systems or Secure Data Transmission Techniques to Minimize the Risk of Violating Customer's Privacy During Cookie Deliveries."
date: 2024-07-13T10:24:38.231Z
updated: 2024-07-14T10:24:38.231Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Foster Innovation for Privacy Protection: Explore Cutting-Edge Technologies Like Onboard Anonymization Systems or Secure Data Transmission Techniques to Minimize the Risk of Violating Customer's Privacy During Cookie Deliveries."
excerpt: "This Article Describes Foster Innovation for Privacy Protection: Explore Cutting-Edge Technologies Like Onboard Anonymization Systems or Secure Data Transmission Techniques to Minimize the Risk of Violating Customer's Privacy During Cookie Deliveries."
keywords: Privacy Protection Innovation,Anonymization Systems Technology,Secure Data Transmission,Minimize Customer Privacy Risk,Onboard Anonymization Tech,Cookie Delivery Security,Privacy Violation Prevention
thumbnail: https://thmb.techidaily.com/30461ded64430f275adab068e1aa1246b69e0b37015df4b520c0cb3237617656.jpg
---

## Foster Innovation for Privacy Protection: Explore Cutting-Edge Technologies Like Onboard Anonymization Systems or Secure Data Transmission Techniques to Minimize the Risk of Violating Customer's Privacy During Cookie Deliveries.

 Controlled folder access is a feature of the Windows Security antivirus app on Microsoft desktop platforms. That feature forestalls ransomware by preventing modifications to files in protected folders. Enabling controlled folder access prevents untrusted apps, malware or otherwise, from changing files within protected directories.

 Controlled folder access is an extra security feature in Windows 10 and 11 that some users appreciate. Ransomware isn’t something to be taken lightly, and enabling that feature will keep system and user files extra safe. These are four ways you can enable controlled folder access in Windows.

##  How to Turn On Controlled Folder Access in Windows Security

 The Controlled folder access setting is buried within ransomware protection in the Windows Security app. However, it’s easy to find and turn that option on/off when you know where it is. This is how to turn on the Windows Security’s app Controlled folder access option.

1. To view the Windows Security app, double-click its shield system tray icon.
2. Select Windows Security’s**Virus & threat protection** tab.  
![The Manage ransomware protection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/manage-ransomware-option.jpg)
3. Click**Manage ransomware protection** to reach the**Controlled folder access** setting.  
![The Controlled folder access option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/controlled-folder-access.jpg)
4. Now turn on the**Controlled folder access** option to enable that feature.

 Controlled folder access protects your Documents, Videos, Pictures, and Music user folders when enabled. To view the list of protected user directories, click**Protected folder** . You can add more to the list by clicking the**Add protected folder** button, choosing a directory, and clicking**Select Folder** .

![The Add a protected folder button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-a-protected-folder-button.jpg) 

##  How to Turn on Controlled Folder Access With PowerShell

 Windows PowerShell gives you an alternative method to enable and disable controlled folder access by executing commands. You can turn on controlled folder access with PowerShell as follows:

1. To activate a file search tool, press**Win + S** .
2. Input**PowerShell** within the activated search utility.
3. Open PowerShell in an elevated mode by selecting**Run as administrator** .
4. To enable controlled folder access, input this command text and hit**Enter** :  
`Set-MpPreference -EnableControlledFolderAccess Enabled`  
![The enable controlled folder access command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-controlled-folder-access-command.jpg)
5. You can disable controlled folder access by executing this command:  
`Set-MpPreference -EnableControlledFolderAccess Disabled`

##  How to Enable Controlled Folder Access With Group Policy Editor

 If you have Windows 11 Pro or Enterprise edition, you can enable controlled folder access with Group Policy Editor. Group Policy Editor also includes some extra configuration settings for controlled folder access, which is a bonus. This is how to turn on controlled folder access via GPE.

 If you're on Windows Home, the Group Policy Editor won't appear by default. Check out [how to access the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) to get around this.

1. Bring up the search tool in Windows and enter**gpedit.msc** there.
2. Select**gpedit.msc** to [bring up the Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) .
3. Click**Computer Configuration** \>**Administrative Templates** inside Group Policy Editor’s left pane.  
![Administrative Templates in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/computer-configuration-in-group-policy-editor.jpg)
4. Double-click**Windows Components** to expand it.
5. Click the arrows for expanding**Microsoft Defender Antivirus** and**Microsoft Defender Exploit Guard** .

1. Select**Controlled Folder Access** to view policy settings for that feature.
2. Then double-click**Configure Controlled folder access** to view that setting’s window.  
![The Controlled Folder Access policy in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/controlled-folder-access-in-group-policy-editor.jpg)
3. Select the Configure Controlled folder access window’s**Enabled** radio button.
4. Click**Block** on the drop-down menu to select the strictest CFA mode. However, you can also select alternative**Audit Mode** ,**Block disk notification only** , and**Audit disk notification only** options for enabling controlled folder access.  
![The Configure the guard my folders feature drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/configure-controlled-folder-access.jpg)
5. Select**Apply** in the Configure Controlled folder access window.
6. Click the Configure Controlled folder access window’s**OK** button.

##  How to Turn on Controlled Folder Access From the Windows Context Menu

 Alternatively, you can create a context menu shortcut for enabling/disabling controlled folder access. Then you’ll be able to access a Turn on Control folder access setting directly from the desktop area of Windows. You can add such a CFA option to the right-click menu by setting up and running a registry script like this:

1. Open Notepad.
2. Then select this script text, and press the**Ctrl** +**C** key combination:  
`Windows Registry Editor Version 5.00  
     
    
 ; Created by: Shawn Brink  
    
 ; Created on: July 19th 2018  
    
 ; Tutorial: https://www.tenforums.com/tutorials/114389-add-turn-off-controlled-folder-access-context-menu-windows-10-a.html  
     
    
 [HKEY_CLASSES_ROOT\DesktopBackground\Shell\ControlledFolderAccess]  
    
 "HasLUAShield"=""  
    
 "Icon"="%ProgramFiles%\\Windows Defender\\EppManifest.dll,-101"  
    
 "MUIVerb"="Turn On or Off Control folder access"  
    
 "Position"="Bottom"  
    
 "SubCommands"=""  
     
    
 [HKEY_CLASSES_ROOT\DesktopBackground\Shell\ControlledFolderAccess\shell\001flyout]  
    
 "MUIVerb"="Turn on Control folder access"  
    
 "HasLUAShield"=""  
    
 "Icon"="%ProgramFiles%\\Windows Defender\\EppManifest.dll,-101"  
     
    
 [HKEY_CLASSES_ROOT\DesktopBackground\Shell\ControlledFolderAccess\shell\001flyout\command]  
    
 @="PowerShell -windowstyle hidden -Command \"Start-Process cmd -ArgumentList '/s,/c,start PowerShell.exe Set-MpPreference -EnableControlledFolderAccess Enabled' -Verb RunAs\""  
     
    
 [HKEY_CLASSES_ROOT\DesktopBackground\Shell\ControlledFolderAccess\shell\002flyout]  
    
 "MUIVerb"="Turn off Control folder access"  
    
 "HasLUAShield"=""  
    
 "Icon"="%ProgramFiles%\\Windows Defender\\EppManifest.dll,-101"  
     
    
 [HKEY_CLASSES_ROOT\DesktopBackground\Shell\ControlledFolderAccess\shell\002flyout\command]  
    
 @="PowerShell -windowstyle hidden -Command \"Start-Process cmd -ArgumentList '/s,/c,start PowerShell.exe Set-MpPreference -EnableControlledFolderAccess Disabled' -Verb RunAs\""`
3. Paste that script into Notepad by clicking in that app’s window and pressing**Ctrl** +**V** .  
![The controlled folder access registry script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/controlled-folder-access-registry-script.jpg)
4. Next, press**Ctrl** +**Shift** +**S** to view Notepad’s "Save as" window.
5. Set the**Save as type** option to**All files** .  
![The All files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/all-files-option.jpg)

1. Type**Turn on Control folder access.reg** inside the file name box.
2. Select to save the script to the desktop location.
3. Click**Save** to add the**Turn on Control folder access** registry file to the desktop.
4. Close the Notepad editor, and double-click the**Turn on Control folder access.reg** file on the desktop.  
![The registry script confirmation dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-script-confirmation-dialog.jpg)
5. Select**Yes** to confirm you trust the script.

 Now you can enable controlled folder access from the Windows context menu.

 Right-click any clear area of the desktop and select**Show more options** on Windows' context menu. Move the cursor over the**Turn On or Off Control** **folder access** submenu. Click**Turn on Control folder access** to enable that Windows Security feature.

 If you ever want to remove the controlled folder access context menu option, you can do so by deleting the registry key for it. This is how to delete the key for the**Turn On or Off Control folder access** submenu:

1. Launch the Registry Editor (our guide for [opening the Regedit registry app](https://www.makeuseof.com/windows-11-open-registry-editor/) includes various methods).
2. Go to this registry key location:  
`HKEY_CLASSES_ROOT\DesktopBackground\Shell\ControlledFolderAccess`
3. Right-click the Controlled Folder Access key to select**Delete** .  
![The Delete key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-option-for-registry-key.jpg)
4. Click**Yes** to erase that key.

##  How to Set Controlled Folder Access Exceptions

 The problem with controlled folder access is that it can stop legitimate apps from accessing required files when they need to. That can be an especially big issue for Windows gaming since untrusted games often can’t save progress with controlled folder access enabled. In-game settings can also reset when that feature is turned on.

 Fortunately, controlled folder access has an exclusion (exception) list for adding trusted apps. It won’t block any trusted apps on that list from modifying files within protected folders. You can add software to the CFA exclusion list as follows:

1. Bring up the**Controlled folder access** setting in Windows Security as covered in steps one to three of the first method above.
2. Click the **Allow an app through Controlled folder access navigation** link.
3. Press the**\+ Add an allowed app** button.  
![The Add an allowed app button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-an-allowed-app.jpg)
4. Click**Browse all** **apps** on the menu that appears.  
![The Browse all apps option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/browse-all-apps-option.jpg)
5. Select the EXE (application) file for a game or other software you want to exclude from controlled folder access.
6. Click**Open** to add the selected game or software.

##  Enable Controlled Folder Access for Greater Ransomware Protection

 Turning on controlled folder access in Windows 10 and 11 with the above methods will give files on your PC an extra layer of protection from malware. It makes little difference how you enable that feature, but you can select more configuration options by using Group Policy Editor. Adding controlled folder access context menu settings also gives you a more direct way to toggle that feature on/off as required.

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
<li><a href="https://win11.techidaily.com/addressing-and-repairing-your-windows-headsets-microphone/"><u>Addressing and Repairing Your Windows Headset's Microphone</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-natural-windows-file-sorting-settings/"><u>Restoring Natural Windows File Sorting Settings</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-unveiling-new-ways-to-record-presentations/"><u>[New] Unveiling New Ways to Record Presentations</u></a></li>
<li><a href="https://win11.techidaily.com/making-your-desktop-more-dynamic-activate-windows-11-widget-bar/"><u>Making Your Desktop More Dynamic: Activate Window's 11 Widget Bar</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-faster-typing-using-windows-powertools/"><u>Unleash Faster Typing Using Windows' PowerTools</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-cultivating-confidence-for-captivating-your-youtube-audience/"><u>[New] In 2024, Cultivating Confidence for Captivating Your YouTube Audience</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/ipogo-will-be-the-new-ispoofer-on-apple-iphone-15-pro-drfone-by-drfone-virtual-ios/"><u>iPogo will be the new iSpoofer On Apple iPhone 15 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/constructing-an-audio-experience-beyond-boundaries-in-windows-11/"><u>Constructing an Audio Experience Beyond Boundaries in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-system-resources-for-fps-performance/"><u>Optimizing System Resources for FPS Performance</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-topmusicreactionvids-yt-celebrity-highlights-2023/"><u>2024 Approved  TopMusicReactionVids  YT Celebrity Highlights, 2023</u></a></li>
<li><a href="https://win11.techidaily.com/windows-unseen-the-emergence-of-ai-futures/"><u>Windows Unseen: The Emergence of AI Futures</u></a></li>
<li><a href="https://win11.techidaily.com/exploiting-windows-software-to-elevate-macos-usability/"><u>Exploiting Windows Software to Elevate macOS Usability</u></a></li>
<li><a href="https://win11.techidaily.com/effective-techniques-to-combat-dxgi-errors/"><u>Effective Techniques to Combat DXGI Errors</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-optimize-your-startup-programs-in-windows-11-for-improved-performance/"><u>How to Optimize Your Startup Programs in Windows 11 for Improved Performance</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-longest-flight-drone-champions-unveiled/"><u>[Updated] Longest Flight Drone Champions Unveiled</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-the-best-of-both-worlds-10-video-editing-apps-for-kids-with-free-and-paid-features/"><u>Updated The Best of Both Worlds 10 Video Editing Apps for Kids with Free and Paid Features</u></a></li>
<li><a href="https://win11.techidaily.com/1719363401331-win10-troubleshooting-make-functions-work-again/"><u>WIN10 Troubleshooting: Make Functions Work Again!</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-blueprint-for-exceptional-tiktok-promotion-tactics/"><u>[Updated] In 2024, Blueprint for Exceptional TikTok Promotion Tactics</u></a></li>
<li><a href="https://fox-links.techidaily.com/vr-tech-trends-right-now-for-2024/"><u>VR Tech Trends Right Now for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-onedrive-server-failures-a-quick-guide/"><u>Overcoming Windows OneDrive Server Failures: A Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/proper-methods-to-turn-windows-key-onoff/"><u>Proper Methods to Turn Windows Key On/Off</u></a></li>
<li><a href="https://win11.techidaily.com/permanent-elimination-guide-for-wsl-on-windows-11-systems/"><u>Permanent Elimination Guide for WSL on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/clear-cut-techniques-eradicate-stutter-in-your-winx-media-streams/"><u>Clear Cut Techniques: Eradicate Stutter in Your WinX Media Streams</u></a></li>
<li><a href="https://android-frp.techidaily.com/ultimate-guide-on-oppo-a79-5g-frp-bypass-by-drfone-android/"><u>Ultimate Guide on Oppo A79 5G FRP Bypass</u></a></li>
<li><a href="https://win11.techidaily.com/five-solutions-for-windows-defender-virus-shield-malfunction/"><u>Five Solutions for Windows Defender Virus Shield Malfunction</u></a></li>
<li><a href="https://win11.techidaily.com/revitalizing-dormant-screen-saver-configurations-in-windows/"><u>Revitalizing Dormant Screen Saver Configurations in Windows</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-universal-unlock-pattern-for-samsung-galaxy-f15-5g-by-drfone-android/"><u>In 2024, Universal Unlock Pattern for Samsung Galaxy F15 5G</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-windows-notification-service-for-phone-link-app/"><u>Restoring Windows Notification Service for Phone Link App</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-the-art-of-video-marketing-11-tips-to-skyrocket-fb-traffic/"><u>In 2024, The Art of Video Marketing  11 Tips to Skyrocket FB Traffic</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-honor-magic-v2-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your Honor Magic V2 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-create-multiple-folders-at-once-in-windows-10-and-11/"><u>3 Ways to Create Multiple Folders at Once in Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-windows-icon-placement-strategies/"><u>Perfect Window's Icon Placement Strategies</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-verizon-iphone-12-by-drfone-ios/"><u>How to Unlock Verizon iPhone 12</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-turn-off-auto-start-for-spotify/"><u>Guide to Turn Off Auto-Start for Spotify</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-navigating-the-world-of-gopro-streaming-and-social-media-networks-for-2024/"><u>[Updated] Navigating the World of Gopro Streaming and Social Media Networks for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-spinning-media-a-quick-guide-to-rotating-videos-in-vlc-for-2024/"><u>[New] Spinning Media  A Quick Guide to Rotating Videos in VLC for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/open-windows-ease-of-access-center-top-5-tactics/"><u>Open Windows Ease of Access Center: Top 5 Tactics</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-capturing-online-clarity-a-zoomers-guide/"><u>2024 Approved  Capturing Online Clarity  A Zoomer's Guide</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-vivo-y200-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your Vivo Y200 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-access-diskspace-tools-for-windows-context-menu/"><u>Quick Access DiskSpace: Tools for Window's Context Menu</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-nokia-xr21-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Nokia XR21 Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-frozen-ctrl-key-functionality-in-windows-11-pcs/"><u>Addressing Frozen CTRL Key Functionality in Windows 11 PCs</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-top-10-free-online-tools-for-creating-stunning-glitch-effects-for-2024/"><u>Updated Top 10 Free Online Tools for Creating Stunning Glitch Effects for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-unlocking-free-audacity-features-for-efficient-audio-recording/"><u>Updated 2024 Approved Unlocking FREE Audacity Features for Efficient Audio Recording</u></a></li>
<li><a href="https://win11.techidaily.com/boost-typing-prowess-changing-and-adding-keyboards-for-win-11/"><u>Boost Typing Prowess: Changing and Adding Keyboards for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-insight-discerning-storage-type-on-windows/"><u>Exclusive Insight: Discerning Storage Type on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-photo-size-transformation-with-these-six-ways-on-windows-11/"><u>Master the Art of Photo Size Transformation with These Six Ways on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/prevent-early-edge-tab-launches-on-windows-11/"><u>Prevent Early Edge Tab Launches on Windows 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-capturing-the-spectrum-a-broad-overview-of-recorders/"><u>In 2024, Capturing the Spectrum  A Broad Overview of Recorders</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-11s-user-sid-identification-methods/"><u>Unveiling Windows 11'S User SID Identification Methods</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-special-features-virtual-location-on-nokia-c210-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Nokia C210? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-your-batch-scripts-creating-windows-exes/"><u>Elevating Your Batch Scripts: Creating Windows EXEs</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-definitive-guide-for-effective-and-smooth-youtube-video-uploads-for-2024/"><u>The Definitive Guide for Effective and Smooth YouTube Video Uploads for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionizing-device-interaction-with-windows-and-galaxy/"><u>Revolutionizing Device Interaction with Windows & Galaxy</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-code-navigating-through-lost-windows-1110-patches/"><u>Unlock the Code: Navigating Through Lost Windows 11/10 Patches</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-mystery-of-windows-ram-caching/"><u>Unveiling the Mystery of Windows RAM Caching</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/corrected-clandestine-miniature-video-absence-for-2024/"><u>Corrected  Clandestine Miniature Video Absence for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-windows-activation-error-0x803f700f-hurdle/"><u>Overcoming the Windows Activation Error 0X803F700f Hurdle</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-behind-the-scenes-insider-knowledge-for-youtube-video-production/"><u>[Updated] In 2024, Behind the Scenes  Insider Knowledge for YouTube Video Production</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-what-the-fn-keys-do-in-windows-11-and-11/"><u>How to Change What the Fn Keys Do in Windows 11 and 11</u></a></li>
</ul></div>
