---
title: "Mastering File Safety: Turning On Folder Controls in Windows"
date: 2024-07-13T10:47:28.504Z
updated: 2024-07-14T10:47:28.504Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering File Safety: Turning On Folder Controls in Windows"
excerpt: "This Article Describes Mastering File Safety: Turning On Folder Controls in Windows"
keywords: Win Folders Secure,File Lockdown Tips,Save Files Proactively,Shield Data Wisely,Guard Files Safely,Control Folder Settings,Optimize File Protection
thumbnail: https://thmb.techidaily.com/025f6d9d96521fea43b8d17c7244b091345a22a6d0cc7e77077266caaed2704c.jpg
---

## Mastering File Safety: Turning On Folder Controls in Windows

 Controlled folder access is a feature of the Windows Security antivirus app on Microsoft desktop platforms. That feature forestalls ransomware by preventing modifications to files in protected folders. Enabling controlled folder access prevents untrusted apps, malware or otherwise, from changing files within protected directories.

 Controlled folder access is an extra security feature in Windows 10 and 11 that some users appreciate. Ransomware isn’t something to be taken lightly, and enabling that feature will keep system and user files extra safe. These are four ways you can enable controlled folder access in Windows.

## How to Turn On Controlled Folder Access in Windows Security

 The Controlled folder access setting is buried within ransomware protection in the Windows Security app. However, it’s easy to find and turn that option on/off when you know where it is. This is how to turn on the Windows Security’s app Controlled folder access option.

1. To view the Windows Security app, double-click its shield system tray icon.
2. Select Windows Security’s**Virus & threat protection** tab.  
![The Manage ransomware protection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/manage-ransomware-option.jpg)
3. Click**Manage ransomware protection** to reach the**Controlled folder access** setting.  
![The Controlled folder access option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/controlled-folder-access.jpg)
4. Now turn on the**Controlled folder access** option to enable that feature.

 Controlled folder access protects your Documents, Videos, Pictures, and Music user folders when enabled. To view the list of protected user directories, click**Protected folder** . You can add more to the list by clicking the**Add protected folder** button, choosing a directory, and clicking**Select Folder** .

![The Add a protected folder button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/add-a-protected-folder-button.jpg)

## How to Turn on Controlled Folder Access With PowerShell

 Windows PowerShell gives you an alternative method to enable and disable controlled folder access by executing commands. You can turn on controlled folder access with PowerShell as follows:

1. To activate a file search tool, press**Win + S** .
2. Input**PowerShell** within the activated search utility.
3. Open PowerShell in an elevated mode by selecting**Run as administrator** .
4. To enable controlled folder access, input this command text and hit**Enter** :  
`Set-MpPreference -EnableControlledFolderAccess Enabled`  
![The enable controlled folder access command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-controlled-folder-access-command.jpg)
5. You can disable controlled folder access by executing this command:  
`Set-MpPreference -EnableControlledFolderAccess Disabled`

## How to Enable Controlled Folder Access With Group Policy Editor

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

## How to Turn on Controlled Folder Access From the Windows Context Menu

 Alternatively, you can create a context menu shortcut for enabling/disabling controlled folder access. Then you’ll be able to access a Turn on Control folder access setting directly from the desktop area of Windows. You can add such a CFA option to the right-click menu by setting up and running a registry script like this:

1. Open Notepad.
2. Then select this script text, and press the**Ctrl** +**C** key combination:  
`Windows Registry Editor Version 5.00  

 ; Created by: Shawn Brink  

 ; Created on: July 19th 2018  

 ; Tutorial: <https://www.tenforums.com/tutorials/114389-add-turn-off-controlled-folder-access-context-menu-windows-10-a.html>  

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

## How to Set Controlled Folder Access Exceptions

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

## Enable Controlled Folder Access for Greater Ransomware Protection

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
<li><a href="https://facebook-record-videos.techidaily.com/updated-one-frame-at-a-time-your-guide-to-free-youtube-navigation/"><u>[Updated] One Frame at A Time  Your Guide to Free YouTube Navigation</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-enable-compact-view-in-file-explorer-on-windows-11/"><u>3 Ways to Enable Compact View in File Explorer on Windows 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-secure-and-save-your-sessions-a-pc-and-smartphone-recorders-haven-for-2024/"><u>[Updated] Secure & Save Your Sessions  A PC & Smartphone Recorder's Haven for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/8-latest-innovations-in-windows-11-post-update-release/"><u>8 Latest Innovations in Windows 11, Post-Update Release</u></a></li>
<li><a href="https://win11.techidaily.com/5-proven-methods-to-clean-your-win11s-dns-cache/"><u>5 Proven Methods to Clean Your Win11's DNS Cache</u></a></li>
<li><a href="https://win11.techidaily.com/7-rapid-responses-to-combat-windows-app-failures/"><u>7 Rapid Responses to Combat Windows App Failures</u></a></li>
<li><a href="https://win11.techidaily.com/1719322695938-new-windows-11-users-beware-of-these-top-8-errors/"><u>New Windows 11 Users, Beware of These Top 8 Errors</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-ispoofer-on-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>How to use iSpoofer on Xiaomi Redmi Note 12T Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/5-actionable-steps-to-solve-gpeditmsc-disappearance/"><u>5 Actionable Steps to Solve Gpedit.msc Disappearance</u></a></li>
<li><a href="https://extra-tips.techidaily.com/maximize-creativity-with-top-10-cost-free-photo-editors-online/"><u>Maximize Creativity with Top 10 Cost-Free Photo Editors Online</u></a></li>
<li><a href="https://win11.techidaily.com/1719383152108-tackle-lagginess-in-winoutlook-effortlessly/"><u>Tackle Lagginess in WinOutlook, Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-sluggish-windows-based-excel-processes/"><u>Accelerate Sluggish Windows-Based Excel Processes</u></a></li>
<li><a href="https://location-social.techidaily.com/set-your-preferred-job-location-on-linkedin-app-of-your-realme-note-50-drfone-by-drfone-virtual-android/"><u>Set Your Preferred Job Location on LinkedIn App of your Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/forgot-locked-apple-iphone-15-password-learn-the-best-methods-to-unlock-drfone-by-drfone-ios/"><u>Forgot Locked Apple iPhone 15 Password? Learn the Best Methods To Unlock | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/social-media-story-scooper/"><u>Social Media Story Scooper</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/crafting-cinematic-magic-making-your-instagram-videos-shine/"><u>Crafting Cinematic Magic  Making Your Instagram Videos Shine</u></a></li>
<li><a href="https://win11.techidaily.com/a-new-dimension-of-cleanliness-windows-eraser-feature/"><u>A New Dimension of Cleanliness: Windows' Eraser Feature</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-economic-expressiveness-in-video-theming-tools/"><u>[Updated] 2024 Approved  Economic Expressiveness in Video Theming Tools</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-keyboard-skills-using-windows-powertoys/"><u>Accelerate Keyboard Skills Using Windows PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-fix-slack-notifications-not-working-on-windows-11/"><u>8 Ways to Fix Slack Notifications Not Working on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-reset-the-windows-firewall-settings/"><u>5 Ways to Reset the Windows Firewall Settings</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/clone-yourself-in-videos-with-filmora/"><u>Clone Yourself in Videos with Filmora</u></a></li>
<li><a href="https://win11.techidaily.com/1719364636660-self-hosted-windows-gptclone-via-gpt4all/"><u>Self-Hosted Windows GPTClone via GPT4All</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-reimagining-anime-narratives-in-trending-tiktok-creations-for-2024/"><u>[Updated] Reimagining Anime Narratives in Trending TikTok Creations for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-the-windows-11-mixer-interface/"><u>A Beginner’s Guide to the Windows 11 Mixer Interface</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-for-overcoming-the-pink-flash/"><u>A Comprehensive Guide for Overcoming the Pink Flash</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-channel-titling-101-the-quest-for-an-original-label/"><u>[Updated] In 2024, Channel Titling 101  The Quest for an Original Label</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-thriving-in-the-world-of-instavids-design-an-impactful-strategy/"><u>[New] Thriving in the World of InstaVids  Design an Impactful Strategy</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-honor-70-lite-5g-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Honor 70 Lite 5G Phone</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-walkthrough-windows-11-calendar/"><u>A Comprehensive Walkthrough: Windows 11 Calendar</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-exploring-and-utilizing-your-twitter-archive/"><u>[Updated] 2024 Approved  Exploring and Utilizing Your Twitter Archive</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-realme-narzo-60-pro-5g-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Realme Narzo 60 Pro 5G Phone</u></a></li>
<li><a href="https://win11.techidaily.com/7-windows-11-features-youre-probably-not-using-but-should/"><u>7 Windows 11 Features You’re Probably Not Using (but Should)</u></a></li>
<li><a href="https://win11.techidaily.com/1719347919938-skip-steps-just-admin-command-prompt-anytime-now/"><u>Skip Steps, Just Admin Command Prompt Anytime Now!</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-tech-finding-your-graphics-spec-in-windows-11/"><u>Accelerate Tech: Finding Your Graphics Spec in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-look-at-triggering-system-restore-in-windows-11/"><u>A Detailed Look at Triggering System Restore in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-pcs-wake-up-time-enabling-quick-start/"><u>Accelerate Your PC's Wake-Up Time: Enabling Quick Start</u></a></li>
<li><a href="https://win11.techidaily.com/8-essential-techniques-for-improved-cs-go-play/"><u>8 Essential Techniques for Improved CS Go Play</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-budget-friendly-tips-for-acquiring-high-end-gopros/"><u>In 2024, Budget-Friendly Tips for Acquiring High-End GoPros</u></a></li>
<li><a href="https://win11.techidaily.com/a-stepwise-approach-to-win11s-hyper-v-activation/"><u>A Stepwise Approach to Win11's Hyper-V Activation</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-key-platforms-ranking-the-best-6-sites-for-business-interaction/"><u>2024 Approved  Key Platforms  Ranking the Best 6 Sites for Business Interaction</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-the-path-to-proficiency-mastering-gif-sharing-on-snapchat/"><u>[New] 2024 Approved  The Path to Proficiency  Mastering Gif Sharing on Snapchat</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-restoring-content-servers-connectivity/"><u>A Step-by-Step Guide to Restoring Content Servers' Connectivity</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-vivo-y200e-5g-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From Vivo Y200e 5G to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-open-the-sound-settings-in-windows-11/"><u>9 Ways to Open the Sound Settings in Windows 11</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-retro-reel-upgrade-converting-photographs-to-videos/"><u>[Updated] Retro Reel Upgrade  Converting Photographs to Videos</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-saving-success-mastering-ppt-errors-in-windows-11/"><u>Accelerate Saving Success: Mastering PPT Errors in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-a-svd-file-document-online-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to Sign a .svd file document online</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-keyboard-input-lag-on-windows-11-and-11/"><u>7 Ways to Fix Keyboard Input Lag on Windows 11 and 11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-15-pro-max-passcode-without-itunes-without-knowing-passcode-drfone-by-drfone-ios/"><u>How to Unlock iPhone 15 Pro Max Passcode without iTunes without Knowing Passcode? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/9-reasons-to-rethink-your-email-client-the-modern-outlook/"><u>9 Reasons to Rethink Your Email Client - The Modern Outlook</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-top-16-avi-video-cutters-trimcut-avi-videos-windows-mac-android-iphone-and-online/"><u>2024 Approved Top 16 AVI Video Cutters Trim/Cut AVI Videos Windows, MAC, Android, iPhone, and Online</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-enable-or-disable-ntfs-file-compression-in-windows-11/"><u>4 Ways to Enable or Disable NTFS File Compression in Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-apple-iphone-12-mini-here-is-the-answer-drfone-by-drfone-virtual-ios/"><u>Wondering the Best Alternative to Hola On Apple iPhone 12 mini? Here Is the Answer | Dr.fone</u></a></li>
</ul></div>
