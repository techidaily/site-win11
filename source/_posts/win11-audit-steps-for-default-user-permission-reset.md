---
title: "Win11 Audit: Steps for Default User Permission Reset"
date: 2024-07-13T10:12:47.448Z
updated: 2024-07-14T10:12:47.448Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win11 Audit: Steps for Default User Permission Reset"
excerpt: "This Article Describes Win11 Audit: Steps for Default User Permission Reset"
keywords: Win11 PrivilegeReset,AdminUserAuditWin,DefaultPermResetWin,Win11UserPermission,AuditDefaultPrivileges,ResetWin11UserRights,Win11AccessControl
thumbnail: https://thmb.techidaily.com/934c09a684ad314c00e00ed21a2e7539ae4858551b2266da80c837988bee503d.jpg
---

## Win11 Audit: Steps for Default User Permission Reset

 Having issues with apps or programs not running properly on your Windows computer? Resetting Windows Update permissions could be the solution you need. Similarly, if you're troubleshooting user profile problems, you can restore user permissions.

 This article covers three different methods to reset all user permissions – using the Icacls command, the Secedit command, and the Subinacl tool.

Let's now explore them in detail.

## 1\. Run the Icacls Command

 The Icacls command allows you to view, modify, and reset file system permissions on files and folders. To reset Windows Update permissions using this command, you will first have to [take ownership of the folders on Windows](https://www.makeuseof.com/windows-10-11-own-folder/) . Then [open an elevated Command Prompt on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) and type in the following command:

`icacls * /t /q /c /reset`

 Now press Enter on your keyboard to execute the command. This will reset all user permissions to default for every folder, subfolder, and file within the current working directory.

In the above command, here are the parameters explained:

* \* – This is a wildcard character that includes all folders within the current directory.
* /t – It targets all the subfolders and files within the current folder.
* /q – Run command without displaying success messages.
* /c – Continues the operation even if errors occur.
* /reset – This parameter resets the permission options to their default values.

## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
3. Click on**Next** and then accept the license agreement terms.  
![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
4. Next, copy and paste the following path into the Destination folder:  
`C:\Windows\System32`  
 Note: If you have installed Windows on a different drive, use that path instead.
5. Now click on**Install now** and wait for the Subinacl tool to be installed. This may take several minutes, so be patient.

1. When the installation is complete,[open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and type in the following commands:  
`subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=administrators=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=administrators=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=administrators=f  
subinacl /subdirectories %SystemDrive% /grant=administrators=f  
subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=system=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=system=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=system=f  
subinacl /subdirectories %SystemDrive% /grant=system=f`
2. On the Save As window, set the File name to**Reset.cmd** and then select**All Files** from the drop-down menu next to it.  
![Reset Windows Update permissions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-update-permissions.jpg)
3. Next, select**Desktop** from the left pane and click on**Save** .
4. Now double-click on it to reset the user permissions to default.
5. This may take a while to complete the procedure, so wait for it to finish.

 Once done, close any running program, and then restart your computer. Your Windows Update permissions will be reset to their default settings. These are three different methods you can use to reset the user permission settings on Windows.

## Restore User Permissions to Default on Windows

 User permissions play a crucial role in computer security. If you're experiencing user permission issues, you must reset them to their default settings. This guide helps you reset all user permissions on Windows using three different methods. You can use the ICACLS command, Secedit command, or Subinacl tool, depending on your preference.


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
<li><a href="https://phone-solutions.techidaily.com/can-i-recover-permanently-deleted-photos-from-itel-p55-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>Can I recover permanently deleted photos from Itel P55 5G</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-11-mail-readability-removing-html-from-email-text/"><u>Enhancing Windows 11 Mail Readability: Removing HTML From Email Text</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-tray-interface-with-numeric-and-caps-indicators/"><u>Personalize Tray Interface with Numeric and Caps Indicators</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-navigating-ppt-presentations-successfully-in-google-meet/"><u>In 2024, Navigating PPT Presentations Successfully in Google Meet</u></a></li>
<li><a href="https://win11.techidaily.com/managing-safe-browsing-in-microsofts-win11/"><u>Managing Safe Browsing in Microsoft’s Win11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-extend-windows-10-shutdown-for-ongoing-processes/"><u>Strategies to Extend Windows 10 Shutdown for Ongoing Processes</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/2024-approved-top-rated-video-editing-solutions-for-creators/"><u>2024 Approved Top-Rated Video Editing Solutions for Creators</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-eliminating-noise-fixing-silent-sounds-in-obs-streams/"><u>In 2024, Eliminating Noise  Fixing Silent Sounds in OBS Streams</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-top-earnings-forecasting-software-for-tiktok-content-makers/"><u>[Updated] Top Earnings Forecasting Software for TikTok Content Makers</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-building-a-sustainable-income-via-youtube-and-adsense/"><u>[Updated] Building a Sustainable Income via YouTube and AdSense</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-prankster-peak-standout-comedians-of-the-week/"><u>[New] Prankster Peak  Standout Comedians of the Week</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-windows-mail-glitches-the-0x80072746-fix-guide/"><u>Combatting Windows Mail Glitches: The 0X80072746 Fix Guide</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-cut-to-perfection-editing-video-duration-on-youtube/"><u>2024 Approved  Cut to Perfection  Editing Video Duration on YouTube</u></a></li>
<li><a href="https://extra-resources.techidaily.com/advanced-psd-text-styling/"><u>Advanced PSD Text Styling</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-how-to-secure-youtube-channels-audible-content/"><u>[New] How to Secure YouTube Channels' Audible Content</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-original-directory-display-preferences/"><u>Regaining Original Directory Display Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-excessive-use-of-windows-module-installer-worker/"><u>Decreasing Excessive Use of Windows Module Installer Worker</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-force-delete-or-uninstall-a-printer-in-windows-11-and-11/"><u>How to Force Delete or Uninstall a Printer in Windows 11 & 11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-a-step-by-step-tutorial-to-bring-more-life-and-humor-to-your-discord-chats-through-gifs/"><u>[Updated] 2024 Approved  A Step-by-Step Tutorial to Bring More Life and Humor to Your Discord Chats Through GIFs</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-color-grading-techniques-unraveling-the-mystery-of-luts/"><u>[New] Color Grading Techniques  Unraveling the Mystery of LUTs</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-visual-storytelling-for-social-media-editing-vt-videos-in-fcpx/"><u>[New] Visual Storytelling for Social Media  Editing VT Videos in FCPX</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-modify-win11s-network-preferences/"><u>Guide to Modify Win11's Network Preferences</u></a></li>
<li><a href="https://network-issues.techidaily.com/correcting-blackout-on-windows-11-post-fall/"><u>Correcting Blackout on Windows 11 Post-Fall</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-efficiency-quick-access-to-system-restore-in-windows-11/"><u>Unlocking Efficiency: Quick Access to System Restore in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/darkmodetoggleforwin-basedtexteditor/"><u>DarkModeToggleForWin-basedTextEditor</u></a></li>
<li><a href="https://win11.techidaily.com/beneath-the-surface-steps-to-engage-with-windows-covert-personality-explorer/"><u>Beneath the Surface: Steps to Engage with Windows’ Covert Personality Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-windows-11-start-up-with-these-simple-ideas/"><u>Streamline Windows 11 Start-Up with These Simple Ideas</u></a></li>
<li><a href="https://win11.techidaily.com/resurrect-your-xbox-on-a-slow-pc-steps-to-take/"><u>Resurrect Your Xbox on a Slow PC: Steps to Take</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-call-logs-on-motorola-moto-g24-by-fonelab-android-recover-call-logs/"><u>Complete guide for recovering call logs on Motorola Moto G24</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-uninstall-microsoft-edge-from-windows-11/"><u>How to Uninstall Microsoft Edge From Windows 11</u></a></li>
<li><a href="https://android-frp.techidaily.com/ultimate-guide-from-oppo-reno-10-proplus-5g-frp-bypass-by-drfone-android/"><u>Ultimate Guide from Oppo Reno 10 Pro+ 5G FRP Bypass</u></a></li>
<li><a href="https://win11.techidaily.com/turbo-tune-up-discover-windows-best-speed-solutions/"><u>Turbo Tune-Up: Discover Windows' Best Speed Solutions</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-13-mini-without-losing-anything-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 13 mini without Losing Anything? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-a-microsoft-account-and-a-local-account-are-different-on-windows/"><u>6 Ways a Microsoft Account and a Local Account Are Different on Windows</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/chinese-letter-system-basics-for-new-learners/"><u>Chinese Letter System Basics for New Learners</u></a></li>
<li><a href="https://win11.techidaily.com/minimizing-edges-process-count-in-windows/"><u>Minimizing Edge's Process Count in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-coding-in-windows-a-guide-to-using-microsoft-copilot/"><u>Mastering Coding in Windows: A Guide to Using Microsoft Copilot</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-dark-screen-quandary-in-window-8/"><u>Overcoming the Dark Screen Quandary in Window 8</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-about-to-expire-message-on-microsoft-os/"><u>Bypassing the About To Expire Message on Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-missing-action-buttons-on-windows-11-pc/"><u>Overcoming Missing Action Buttons on Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-accessing-the-fax-editor-in-win11/"><u>Essential Tips: Accessing the Fax Editor in Win11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-unbranded-full-hd-screen-taping-service-for-2024/"><u>[New] Unbranded Full HD Screen Taping Service for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-clarity-just-clicked/"><u>Windows Clarity, Just Clicked!</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-effortlessly-engage-with-an-array-of-available-youtube-content/"><u>[Updated] Effortlessly Engage with an Array of Available YouTube Content</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-fast-tracking-views-on-vimeo-for-2024/"><u>[Updated] Fast-Tracking Views on Vimeo for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-fresh-start-for-your-computers-firewall-settings/"><u>A Fresh Start for Your Computer's Firewall Settings</u></a></li>
<li><a href="https://win11.techidaily.com/disable-dim-display-feature-via-control-panel-quick-guide/"><u>Disable Dim Display Feature via Control Panel Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/1719334729837-fix-unusable-compatibility-center-on-vista7-pcs-fast/"><u>Fix Unusable Compatibility Center on Vista/7 PCs Fast</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-windows-assistance-entry/"><u>Mastering the Art of Windows Assistance Entry</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/rising-sun-talk-exchanging-good-morning-across-cultures/"><u>Rising Sun Talk: Exchanging 'Good Morning' Across Cultures</u></a></li>
<li><a href="https://location-fake.techidaily.com/8-solutions-to-fix-find-my-friends-location-not-available-on-samsung-galaxy-s24-ultra-drfone-by-drfone-virtual-android/"><u>8 Solutions to Fix Find My Friends Location Not Available On Samsung Galaxy S24 Ultra | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-simplifying-cross-platform-video-sharing-between-twitter-and-snapchat/"><u>[Updated] 2024 Approved  Simplifying Cross-Platform Video Sharing Between Twitter & Snapchat</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/rful-thumbnails-in-a-flash-professional-valorant-creations-for-2024/"><u>Masterful Thumbnails in a Flash  Professional Valorant Creations for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/free-audio-magic-at-your-fingertips-the-essential-top-10-sound-blending-software-for-2024/"><u>Free Audio Magic at Your Fingertips The Essential Top 10 Sound Blending Software for 2024</u></a></li>
</ul></div>
