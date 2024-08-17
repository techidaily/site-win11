---
title: Fixing 'Your IT Admin Can't Do More' On Windows OS
date: 2024-08-16T00:13:00.846Z
updated: 2024-08-17T00:13:00.846Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing 'Your IT Admin Can't Do More' On Windows OS
excerpt: This Article Describes Fixing 'Your IT Admin Can't Do More' On Windows OS
keywords: Windows IT Management,Overcoming Limits in Windows,Enhancing Windows Administration,Optimizing Windows Performance,Resolving Admin Issues on Windows,Improve Windows OS Controls,Maximize Windows Admin Capacity
thumbnail: https://thmb.techidaily.com/5ed909f597267ef924f41dbe3db988e7da363a5d5c3d20cd43f4003c2eedf878.jpg
---

## Fixing 'Your IT Admin Can't Do More' On Windows OS

 Some users have posted on troubleshooting forums about a “Page not available” error that occurs when they open Windows Security. The “Page not available” error message says, “Your IT Administrator has limited access to some areas of this app.” That error message appears within Windows Security, and users can’t access that app’s antivirus settings because of it.

 This error message suggests another administrative user has applied restrictions to Windows Security. However, it often arises on standalone PCs that aren’t connected to an organization network. This is how you can fix the “Your IT administrator has limited access” error.

## 1\. Change Your User Account to an Admin Account

 You shouldn’t usually need admin rights to access Windows Security. However, make sure you’re signed in to an admin account to ensure you have full system permissions. If you’re utilizing a standard account, change it to an administrator one. You can do that with one of the methods outlined in this guide to [changing user account type in Windows](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) .

![The Access work or school account settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/work-or-school-accounts.jpg)

## 2\. Uninstall Third-Party Security Software

 Have you installed a third-party antivirus app on your PC? If so, that security software could be by conflicting with Microsoft Defender and causing the “Page not available” error. Try uninstalling the third-party antivirus utility you’ve installed with a method in our guide to [removing Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) . Or utilize a dedicated removal tool for your antivirus app if there’s one available.

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/uninstall-option-3.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->

## 3\. Remove Any Work or School Accounts

 Have you connected your PC with any school or work organization account? If so, such an account could be restricting access to Windows Security settings. Try disconnecting your PC from the school or work in Settings as follows:

1. Bring up Settings and click that app’s**Accounts** tab (or category).
2. Scroll down to select the**Access work or school navigation** option.
3. Click a connected work or school account to expand it.  
![The Access work or school account settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/work-or-school-accounts.jpg)
4. Press the**Disconnect** button and select**Yes** .

## 4\. Disable the Turn Off Microsoft Defender Antivirus Policy

 Some Windows Pro and Enterprise users have confirmed they’ve fixed the “Page not available” error by disabling a**Turn off Microsoft Defender Antivirus** policy. So, check that policy setting even if you can’t recall changing it yourself. This is how you can check and disable the**Turn Off Microsoft Defender Antivirus** Group Policy setting in Windows Pro and Enterprise:

1. To access the file search box, hold the Windows logo key and press S.
2. Type**gpedit.msc** inside the file search box.
3. Double-click**gpedit.msc** to [open the Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) window.
4. Next, double-click**Computer Configuration** and**Administrative Templates** within Group Policy Editor’s sidebar.
5. Expand the**Windows Components** folder in the sidebar.

1. Click**Microsoft Defender Antivirus** to select that policy.  
![Microsoft Defender Antivirus settings in Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-antivirus-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Then double-click**Turn off Microsoft Defender Antivirus** .
3. Click**Disabled** if the**Turn off Microsoft Defender Antivirus** policy is enabled.  
![The Turn off Microsoft Defender Antivirus window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-turn-off-microsoft-defender-antivirus-window.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Select the policy’s**Apply** and**OK** options.
5. Double-click**Allow antimalware to startup with normal priority** and select to disable that policy as outlined in the previous two steps as well.  
![The Allow antimalware service to startup with normal priority window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-antimalware-service-window.jpg)
6. Next, click**Client Interface** within the Microsoft Defender Antivirus settings.  
![Allow antimalware service to startup with normal priority](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/client-interface-setting.jpg)
7. Double-click the**Enable headless UI mode** policy to view it.  
![The Client Interface settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-headless-ui-mode.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Select**Disabled** \>**Apply** \>**OK** in the Enable headless UI mode policy window.

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Run a PowerShell Command

 Running a set-MpPreference PowerShell command is a widely confirmed potential resolution for the “Page not available” error. The confirmed command disables Microsoft Defender’s UI lockdown mode. You can run that PowerShell command like this:

1. Activate the Windows search utility.
2. Input a**PowerShell** search phrase to find that command-line app.
3. Open PowerShell with elevated permissions by right-clicking the search result for that command-line app and selecting**Run as administrator** .
4. Input this**MpPreference** command and press**Return** :  
`set-MpPreference -UILockdown`  
![The set-Mppreference PowerShell command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-set-mppreference-command.jpg)
5. Exit PowerShell and open Windows Security again to see if the error persists.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Repair/Reset Windows Security

 Windows Security is a UWP app for which you can select**Repair** and**Reset** Settings options that can resolve various issues. Those options are there to help users fix apps that aren’t working right. So, try selecting Windows Security’s**Repair** and**Reset** options to see if they make any difference.

![The Reset button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button.jpg)

 Our article [about resetting Windows apps](https://www.makeuseof.com/windows-reset-app/) tells you how to access the**Reset** button. The**Repair** button is just above the**Reset** option. It’s recommended to select**Repair** first since that doesn’t affect app data.

## 7\. Modify the Registry via Command Prompt

 Users also confirm that running a series of Command Prompt commands that modify the registry can resolve the “Page not available” issue. As those are reg delete commands, we recommend you back up the registry before applying this potential fix. Then try running the registry commands for erasing policies like this:

 Open the utility for finding files and apps with the**Windows** logo +**S** key combination.

1. Find the Command Prompt by typing in a**CMD** search phrase.
2. Click the Command Prompt app with the mouse’s right button to select a**Run as administrator** context menu option.
3. Execute the following commands separately, pressing**Enter** after inputting each one:  
`reg delete "HKLM\Software\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKLM\Software \Microsoft\WindowsSelfHost" /f  

reg delete "HKLM\Software\Policies" /f  

reg delete "HKLM\Software\WOW6432Node\Microsoft\Policies" /f  

reg delete "HKLM\Software\WOW6432Node\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKLM\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableAntiSpyware  

reg delete "HKCU\Software\Microsoft\Windows\CurrentVersion\Policies" /f  

reg delete "HKCU\Software\Microsoft\WindowsSelfHost" /f  

reg delete "HKCU\Software\Policies" /f  

reg delete "HKLM\Software\Microsoft\Policies" /f`
4. Input**exit** in the Command Prompt to close the app.  
![The reg delete command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reg-delete.jpg)
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Open the Start menu, select**Power** , and press the**Restart** button.

## 8\. Perform a System Restore

 If the “Page not available” error remains after applying other potential solutions, try performing a system restore. That might work if you can select a restore point predating the “Page not available” error on your PC. Rolling Windows back to an earlier time could undo any system changes that caused the issue to arise.

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-resotre-window.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Our guide on [creating and utilizing restore points](https://www.makeuseof.com/windows-11-create-restore-point/) provides instructions for rolling back Windows with System Restore. Choose the oldest restore point you can. However, remember that you’ll probably need to reinstall some software packages installed after the restore point’s date.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
## Start Utilizing Windows Security Again

 The potential solutions covered in this guide address many of the primary causes for that error occurring. So, they’ll probably get the “Page not available” error sorted on most users’ Windows 11/10 PCs. Fixing the “Page not available” error will enable you to access all the settings in Windows Security again.

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
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-upload-wisdom-tiktok-video-rights-and-compliance-guide/"><u>[New] 2024 Approved  Upload Wisdom  TikTok Video Rights & Compliance Guide</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-lecturers-guide-to-efficient-classroom-sound-archiving-on-macs/"><u>[New] In 2024, Lecturer's Guide to Efficient Classroom Sound Archiving on Macs</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-secure-and-store-your-saved-snaps-on-androidmac-hardware/"><u>[New] In 2024, Secure and Store Your Saved Snaps on Android/Mac Hardware</u></a></li>
<li><a href="https://youtube-data.techidaily.com/astering-creativity-top-10-yt-reaction-hacks-for-2024/"><u>[New] Mastering Creativity  Top 10 YT Reaction Hacks for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-beyond-the-buzz-the-top-10-competitive-video-editors/"><u>[Updated] 2024 Approved  Beyond the Buzz  The Top 10 Competitive Video Editors</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-elevate-views-and-subscribers-a-list-of-proven-youtube-techniques/"><u>[Updated] In 2024, Elevate Views and Subscribers  A List of Proven YouTube Techniques</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-techniques-for-harvesting-hd-facebook-videos-for-2024/"><u>[Updated] Techniques for Harvesting HD Facebook Videos for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-sierras-complete-access-to-cloud-documentationdrive/"><u>2024 Approved  Sierra's Complete Access to Cloud Documentation/Drive</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-step-by-step-tutorial-applying-computer-vhs-filters/"><u>2024 Approved  Step-by-Step Tutorial  Applying Computer VHS Filters</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/an-impartial-appraisal-the-power-of-recordcast-for-2024/"><u>An Impartial Appraisal  The Power of RecordCast for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-samsung-galaxy-xcover-6-pro-tactical-edition-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Samsung Galaxy XCover 6 Pro Tactical Edition | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-new-life-into-your-win11-printer-with-these-tips/"><u>Breathe New Life Into Your Win11 Printer with These Tips</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-gap-fixing-laptop-and-phone-connection-discrepancies/"><u>Bridge Gap: Fixing Laptop and Phone Connection Discrepancies</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-the-gap-connecting-your-computer-again/"><u>Bridge the Gap: Connecting Your Computer Again</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-windows-explorer-tab-lapses/"><u>Bridging Windows Explorer Tab Lapses</u></a></li>
<li><a href="https://win11.techidaily.com/bring-order-to-your-notetaking-chaos-using-obsidian-palette/"><u>Bring Order to Your Notetaking Chaos Using Obsidian Palette</u></a></li>
<li><a href="https://win11.techidaily.com/bring-the-spirit-of-christmas-alive-with-these-wonderful-windows-themes/"><u>Bring the Spirit of Christmas Alive With These Wonderful Windows Themes</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-winget-back-online-window-11-edition/"><u>Bringing Winget Back Online: Window 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-oculus-setup-errors-with-proven-win11win10-methods/"><u>Bypass Oculus Setup Errors with Proven Win11/Win10 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-blocked-onedrive-fixes-for-windows-users/"><u>Bypassing Blocked OneDrive: Fixes for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-secure-answers-for-win-11s-default-administrator/"><u>Bypassing Secure Answers for Win 11'S Default Administrator</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-termination-error-a-guide-for-windows-users/"><u>Bypassing Termination Error: A Guide for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-wsl-smart-choice/"><u>Bypassing WSL - Smart Choice</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-fixing-outdated-windows-user-password-issue/"><u>Bypassing: Fixing Outdated Window's User Password Issue</u></a></li>
<li><a href="https://win11.techidaily.com/cease-unsolicited-search-menu-activation-win11-style/"><u>Cease Unsolicited Search Menu Activation, Win11 Style</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-constant-pc-startup-in-bios-mode/"><u>Circumventing Constant PC Startup in BIOS Mode</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-error-0x80242016-for-updates/"><u>Circumventing Error 0X80242016 for Updates</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-obstacles-with-amd-195-setup-on-pcs/"><u>Circumventing Obstacles with AMD 195 Setup on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/classic-diablo-playbook-step-by-step-guide/"><u>Classic Diablo Playbook: Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/clear-the-path-nine-tricks-to-dodge-steady-windows-update-stalls/"><u>Clear the Path: Nine Tricks to Dodge Steady Windows Update Stalls</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-errors-successfully-downloading-from-the-ms-store/"><u>Clearing Errors: Successfully Downloading From the MS Store</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-the-path-for-startup-display-in-taskbar/"><u>Clearing the Path for Startup Display in Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-disk-needs-format-warning-on-windows/"><u>Clearing Up 'Disk Needs Format' Warning on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-dark-screen-with-windows-webcam/"><u>Clearing Up Dark Screen with Windows Webcam</u></a></li>
<li><a href="https://win11.techidaily.com/cleverly-camouflaged-these-programs-slow-down-windows-users/"><u>Cleverly Camouflaged, These Programs Slow Down Windows Users</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-samsung-galaxy-a25-5g-has-native-hevc-support-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Does Samsung Galaxy A25 5G has native HEVC support?</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/how-to-get-more-video-views-on-youtube-for-2024/"><u>How To Get More Video Views on YouTube for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-a-found-apple-iphone-8-plus-by-drfone-ios/"><u>In 2024, How To Unlock A Found Apple iPhone 8 Plus?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-pinnacle-lineup-of-flexible-fonts/"><u>In 2024, Pinnacle Lineup of Flexible Fonts</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-rapid-video-rendering-in-powerpoint-presentations/"><u>In 2024, Rapid Video Rendering in PowerPoint Presentations</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-lava-blaze-pro-5g-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For Lava Blaze Pro 5G Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-understanding-and-managing-video-layouts-in-zoom-for-windows-11-users/"><u>In 2024, Understanding and Managing Video Layouts in Zoom for Windows 11 Users</u></a></li>
<li><a href="https://ai-topics.techidaily.com/new-in-2024-demystifying-ai-game-generators-from-definition-to-distinction/"><u>New In 2024, Demystifying AI Game Generators From Definition to Distinction</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-vivo-v27e-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock Vivo V27e Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-path-to-ingenious-visuals-mastery-over-microsofts-copilot/"><u>The Path to Ingenious Visuals: Mastery Over Microsoft's Copilot</u></a></li>
<li><a href="https://youtube-data.techidaily.com/form-your-online-presence-sharing-youtube-videos-on-fb-today-for-2024/"><u>Transform Your Online Presence  Sharing YouTube Videos on FB Today for 2024</u></a></li>
</ul></div>
