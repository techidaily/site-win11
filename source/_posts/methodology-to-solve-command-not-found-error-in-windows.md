---
title: Methodology to Solve 'Command Not Found Error' In Windows
date: 2024-08-28T00:53:40.693Z
updated: 2024-08-29T00:53:40.693Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Methodology to Solve 'Command Not Found Error' In Windows
excerpt: This Article Describes Methodology to Solve 'Command Not Found Error' In Windows
keywords: Windows Command Error Fix,Resolving WinError NoExit,Troubleshoot WinCMD Failure,Windows Execution Error Guide,Solve CMD Not Found Issue,Unpacking WinShell Errors,Overcoming CMD Command Error
thumbnail: https://thmb.techidaily.com/10b343d090bf904bc6bf8fe5ac35deb164bc4c88645e3dc6ba8f681d6f6e808f.jpg
---

## Methodology to Solve 'Command Not Found Error' In Windows

 Regedit.exe is the application file for Registry Editor, which is an app with which users tweak the registry. However, some users can’t open that app because of a regedit.exe error. Those users have reported this error message pops up when they try to launch Registry Editor: “Windows cannot find C:\\Windows\\regedit.exe.”

 This registry app error can arise in Windows 11/10 and earlier platforms of the same OS series. It effectively blocks registry access for users who need to resolve it. These are some of the ways to fix the “cannot find regedit.exe” error in Windows 11/10.

## 1\. Run a Full Antivirus Scan

 The “cannot find regedit.exe” error can sometimes be due to malware targeting the Registry Editor. So, we recommend all users who need to resolve this issue first run a full antivirus scan. If you haven’t got any antivirus software installed, try running a Windows Security scan as follows:

1. Double-click Windows Security’s shield icon within the system tray on the right of your taskbar.
2. Click the**Virus & threat** **protection** tab along the left of Windows Security.
3. Select**Scan options** to access all the scanning radio buttons.  
![The Virus & threat protection tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/virus-threat-protection-tab.jpg)
4. Next, click Windows Security’s**Full Scan** option.
5. Press**Scan now** to initiate the scanning.  
![The Scan now button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/scan-now-button.jpg)
6. If Windows Security detects something, select the**Remove action** options for everything detected.
7. Then click**Start actions** .

## 2\. Scan and Repair System Files

 Scanning system files is a potential solution for the “cannot find regedit.exe” error confirmed to work by some. Those users resolved the issue with the System File Checker Command Prompt utility. You can scan and repair system files with that SFC tool like this:

1. First, click the search box button along the taskbar.
2. Look for the Command Prompt by typing**cmd** inside the search tool.
3. Launch Command Prompt in its admin mode by clicking that search result with the mouse’s right button and selecting Run as administrator.
4. Before running an SFC scan, execute the following command:  
`DISM.exe /Online /Cleanup-image /Restorehealth`
5. Type in this SFC command text and press**Enter** :  
`sfc /scannow`  
![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-scannow-command.jpg)
6. Wait until that tool’s scan gets to 100 percent. Then you’ll see a Windows Resource Protection message in the Prompt’s window.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Enable Registry Editor Access in Group Policy Editor

 Windows Pro and Enterprise editions have a Group Policy Editor tool that includes a**Prevent access to registry editing tools** option. If you’re a Pro or Enterprise user, check if that policy setting is enabled and causing the issue at hand. This is how you can enable Registry Editor access with Group Policy Editor:

1. Open Run (see[how to open Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) ), type**gpedit.msc** in that accessory’s command box, and select**OK** .
2. Select User Configuration in Group Policy Editor’s sidebar.
3. Double-click**Administrative Templates** \>**System** to reach the**Prevent access to registry editing tools** option.  
![The Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/local-group-policy-editor.jpg)
4. Then double-click**Prevent access to registry editing** tools to bring up the window for that policy setting.
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
5. Select the**Disabled** option, and click**Apply** to save.  
![The prevent access to registry editing tools policy setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/prevent-access-to-registry-edting-tools.jpg)
6. Press the Prevent access to registry editing tools window’s**OK** button.
7. Exit Group Policy Editor, and restart your PC.

## 4\. Edit the Path Environment Variable

 A wrongly configured or missing path environment variable can cause the “cannot find regedit.exe” error. Some users may need to edit an environment variable to resolve this issue. To do so, follow these steps for editing the Path variable:

1. Press**Win + S** to access the search box.
2. Enter**View advanced system settings** inside the**Type here to search** box.
3. Select**View advanced system settings** to view a System Properties window.
4. Click**Environment Variables** to open up that window.  
![The Environment Variables button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/environment-variables-button.jpg)
5. Select**Path** , and click the**Edit** button.  
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
![The Environment Variables window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/environment-varibles-window.jpg)
6. Click**Edit** on the environment variable window.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
7. Input this variable:  
`%USERPROFILE%\AppData\Local\Microsoft\WindowsApps`
8. Select the Edit environment variable window’s**OK** option.  
![The Edit environment variables window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/edit-environent-variables-window.jpg)
9. Reboot your Windows desktop or laptop.

## 5\. Restore the Registry Editor’s Default Registry Values

 This error can occur because some of the Registry Editor’s registry values have been altered. So, restoring the default registry values for the regedit.exe could be a solution for some users. You can restore those values to default without the Registry Editor app by setting up a script as follows:

1. Bring up the Windows text editor with a method in our guide for opening Notepad.
2. Select this script code and press the**Ctrl** +**C** key combination:  
`[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion]  

 "SM_GamesName"="Games"  

 "SM_ConfigureProgramsName"="Set Program Access and Defaults"  

 "CommonFilesDir"="C:\\Program Files\\Common Files"  

 "CommonFilesDir (x86)"="C:\\Program Files (x86)\\Common Files"  

 "CommonW6432Dir"="C:\\Program Files\\Common Files"  

 "DevicePath"=hex(2):25,00,53,00,79,00,73,00,74,00,65,00,6d,00,52,00,6f,00,6f,\  

 00,74,00,25,00,5c,00,69,00,6e,00,66,00,3b,00,00,00  

 "MediaPathUnexpanded"=hex(2):25,00,53,00,79,00,73,00,74,00,65,00,6d,00,52,00,\  

 6f,00,6f,00,74,00,25,00,5c,00,4d,00,65,00,64,00,69,00,61,00,00,00  

 "ProgramFilesDir"="C:\\Program Files"  

 "ProgramFilesDir (x86)"="C:\\Program Files (x86)"  

 "ProgramFilesPath"=hex(2):25,00,50,00,72,00,6f,00,67,00,72,00,61,00,6d,00,46,\  

 00,69,00,6c,00,65,00,73,00,25,00,00,00  

 "ProgramW6432Dir"="C:\\Program Files"  

 Windows Registry Editor Version 5.00`
3. Click inside the Notepad window, and press the**Ctrl** +**V** keyboard shortcut for pasting.  
![The registry script for restoring default values](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/edit-registry-script.jpg)
4. Press Notepad’s**Ctrl** +**Shift** +**S** keyboard shortcut for opening the "Save as" window.
5. Select the**All files** option in the**Save as type** menu.  
![The All Files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/all-files-option.jpg)
6. Type**Registry Fix.reg** inside the name box.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
7. Choose to save the script on the desktop area.
8. Select the**Save** option, and then close Notepad.
9. Right-click the saved**Registry Fix.reg** script on the desktop and select**Show more options** \>**Merge** .
10. Click**Yes** to confirm the selected option.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
## 6\. Perform a System Restore

 Restoring Windows to an earlier date can fix corrupted files. If you have the System Restore tool turned on, that might be worth a try. You can roll back Windows as outlined in our guide for[creating restore points in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) and utilizing System Restore. Select a restore point predating the “cannot find regedit.exe” error on your PC if you can.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/system-restore-tool.jpg)

 You may need to reinstall some software after performing system restoration. Software installed after any restore point’s date is not preserved. Click the**Scan for affected programs** option for whatever restoration point you chose to see what software it removes.

## 7\. Reset Windows

 This last resolution will restore Windows 11/10 to a factory default configuration, which will likely resolve the “cannot find regedit.exe” issue. However, this is the last thing you should try since resetting Windows will also remove software packages that weren’t preinstalled. Our guide about[factory resetting a Windows PC](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) includes the steps for applying this fix.

![The Reset this PC button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-reset-this-pc-button.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
## Edit the Registry With Registry Editor Once More

 We hope and expect the potential resolutions in this guide will fix the “cannot find regedit.exe” error on your PC. Those possible solutions don’t come with a 100 percent guarantee, but they’ll probably get that issue sorted in most cases. Try applying them all as ordered above to get the Registry Editor working again.

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
<li><a href="https://fox-access.techidaily.com/new-2024-approved-high-end-camcorders-reviewed-top-15/"><u>[New] 2024 Approved  High-End Camcorders Reviewed  Top 15</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-step-by-step-process-for-free-youtube-introend-making/"><u>[New] 2024 Approved  Step-by-Step Process for Free YouTube Intro/End Making</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-mac-visionaries-reveal-screenflow-secrets-and-benefits-for-2024/"><u>[New] Mac Visionaries Reveal ScreenFlow Secrets and Benefits for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-byte-sized-hits-the-heart-of-viral-content/"><u>[Updated] In 2024, Byte-Sized Hits  The Heart of Viral Content</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-enhancing-youtube-beauty-mastering-video-color-dynamics/"><u>2024 Approved  Enhancing YouTube Beauty  Mastering Video Color Dynamics</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-leading-the-way-in-affordable-video-conferencing-technology/"><u>2024 Approved  Leading the Way in Affordable Video Conferencing Technology</u></a></li>
<li><a href="https://location-fake.techidaily.com/8-solutions-to-fix-find-my-friends-location-not-available-on-vivo-y02t-drfone-by-drfone-virtual-android/"><u>8 Solutions to Fix Find My Friends Location Not Available On Vivo Y02T | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/1721408166152-chatgpt-revolutions-top-features-that-matter-most/"><u>ChatGPT Revolutions: Top Features That Matter Most!</u></a></li>
<li><a href="https://fox-glue.techidaily.com/crafting-audible-magic-cropping-and-edits-in-canva-videos/"><u>Crafting Audible Magic  Cropping and Edits in Canva Videos</u></a></li>
<li><a href="https://win11.techidaily.com/devhome-demystified-guiding-you-through-win11-upgrades/"><u>DevHome Demystified: Guiding You Through Win11 Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-ms-resouce-text-error-on-windows-11/"><u>Eliminating Ms-Resouce Text Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-startup-functionality-for-a-smooth-windows-11-launch/"><u>Fine-Tuning Startup Functionality for a Smooth Windows 11 Launch</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-iphoneipad-photo-import-error-a-compreayers-approach-on-w11/"><u>Fixing iPhone/iPad Photo Import Error: A Compreayer’s Approach on W11</u></a></li>
<li><a href="https://win-dash.techidaily.com/fixing-issues-with-intel-optane-storage-easy-driver-download-and-update-tips-for-windows-users/"><u>Fixing Issues with Intel Optane Storage: Easy Driver Download & Update Tips for Windows Users</u></a></li>
<li><a href="https://win-amazing.techidaily.com/free-download-logitech-g-pro-driving-force-ls-gamepad-compatible-with-windows-11-10-8-and-7/"><u>Free Download: Logitech G PRO Driving Force LS Gamepad Compatible with Windows 11, 10, 8 & 7</u></a></li>
<li><a href="https://win11.techidaily.com/halt-unprompted-gaming-suggestions-on-windows-11/"><u>Halt Unprompted Gaming Suggestions on Windows 11</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/how-to-effortlessly-record-and-share-snapchat-videos-for-2024/"><u>How to Effortlessly Record and Share Snapchat Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-revert-windows-11s-search-bar-to-a-search-icon/"><u>How to Revert Windows 11'S Search Bar to a Search Icon</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-overview-of-various-cameras-used-in-film-and-tv/"><u>In 2024, Overview of Various Cameras Used in Film & TV</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-ways-to-stop-parent-tracking-your-tecno-spark-20-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to stop parent tracking your Tecno Spark 20 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/master-compatibility-fixes-without-the-troubleshooter/"><u>Master Compatibility Fixes Without the Troubleshooter</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-new-window-11-the-best-modifications-for-an-optimized-experience/"><u>Master Your New Window 11: The Best Modifications for an Optimized Experience</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-microsoft-powertoys-in-win11-setup/"><u>Mastering Microsoft PowerToys in Win11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-productivity-with-sticky-notes-in-w11w10/"><u>Maximize Productivity with Sticky Notes in W11/W10</u></a></li>
<li><a href="https://discover-advanced.techidaily.com/meeting-of-global-experts-in-artificial-intelligence-and-robotic-process-automation-abbyys-role-at-the-2018-ai-and-rpa-world-summit-in-berlin/"><u>Meeting of Global Experts in Artificial Intelligence and Robotic Process Automation: ABBYY's Role at the 2018 AI & RPA World Summit in Berlin</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-back-to-your-copilot-in-ws11-spacecraft/"><u>Navigate Back to Your Copilot in WS11 Spacecraft</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-a-new-era-of-interactive-technology-between-pc-and-galaxy/"><u>Navigating a New Era of Interactive Technology Between PC & Galaxy</u></a></li>
<li><a href="https://techtrends.techidaily.com/new-to-twitch-clear-up-these-5-misconceptions-about-live-chatting/"><u>New to Twitch? Clear Up These 5 Misconceptions About Live Chatting</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-clipboard-utility-in-windows-11-pcs/"><u>Optimizing Clipboard Utility in Windows 11 PCs</u></a></li>
<li><a href="https://some-approaches.techidaily.com/perfect-cone-view-mounts-vr-for-2024/"><u>Perfect Cone View Mounts VR for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-desk-view-including-this-pc-on-the-screen/"><u>Personalize Desk View: Including 'This PC' On the Screen</u></a></li>
<li><a href="https://win11.techidaily.com/solving-the-puzzle-of-a-unresponsive-discord-overlay-in-windows/"><u>Solving the Puzzle of a Unresponsive Discord Overlay in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-workflows-with-windows-11-multitasking-tips/"><u>Streamline Workflows with Windows 11 Multitasking Tips</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-sound-system-upgrade-with-atmos-on-win-1011/"><u>Streamlined Sound System Upgrade with Atmos on Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-sign-in-with-windows-hello-biometrics/"><u>Streamlining Sign-In with Windows Hello Biometrics</u></a></li>
<li><a href="https://win11.techidaily.com/tapping-into-hidden-taskbar-explorer-of-windows-11/"><u>Tapping Into Hidden Taskbar Explorer of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/top-factors-for-choosing-windows-10-over-the-latest-operating-system-win11/"><u>Top Factors for Choosing Windows 10 over the Latest Operating System - Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unblock-selecthighlight-capabilities-in-windows-pdf-viewer/"><u>Unblock Select/Highlight Capabilities in Windows' PDF Viewer</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-app-execution-variants-and-usage/"><u>Understanding App Execution Variants & Usage</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-vanishing-printmanagement-in-windows/"><u>Unraveling the Mystery of Vanishing 'Printmanagement' In Windows</u></a></li>
<li><a href="https://some-skills.techidaily.com/unveiling-youtubes-finest-story-sages-and-weavers-in-23-for-2024/"><u>Unveiling YouTube's Finest Story Sages and Weavers in '23 for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-nokia-g42-5g-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On Nokia G42 5G? | Dr.fone</u></a></li>
</ul></div>
