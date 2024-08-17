---
title: Reclaiming the Lost Startup Window in Windows
date: 2024-08-16T00:25:30.548Z
updated: 2024-08-17T00:25:30.548Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reclaiming the Lost Startup Window in Windows
excerpt: This Article Describes Reclaiming the Lost Startup Window in Windows
keywords: WinStartupsLost,ReclaimWindowsStartup,ReviveStartupWin,RestoreWindowsStartup,StartupResetWin,ReinitiateWindowsSys,WindowsStartupRecover
thumbnail: https://thmb.techidaily.com/1226fbaa741004693d1f4b8bc9bf88f0e71c8201ee5e911ba173ac8995ac7535.jpg
---

## Reclaiming the Lost Startup Window in Windows

 While using the Windows Task Manager, you may suddenly come across an error message that reads, “There are no startup items to display in Task Manager.” It's a confusing error message, but don't fret; it's very easy to fix.

 Let’s check out the best ways to fix Task Manager's "no startup items" error.

## 1\. Restart File Explorer

 Restarting File Explorer is one of the easiest ways to resolve this issue. The best way to do this is to restart your Windows PC completely.

 If that doesn’t resolve the problem, or you'd rather not restart your PC, you can restart File Explorer through these steps:

1. Press**Win + X** to open the Quick Access menu.
2. Select**Task Manager** from the options.
3. Right-click on the**Windows Explorer** option and then select**Restart** .

![Restarting the Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Restarting-the-Windows-File-Explorer.jpg)

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Create a New Startup Folder

 In some cases, you’d run into the issue at hand if the startup folder is corrupted. So, the best way to resolve the problem is to create a new startup folder.

Now, here are the steps for creating a new startup folder on Windows:

1. Press**Win + E** to open File Explorer.
2. Copy-paste the command into the File Explorer address bar and press**Enter** :

`C:\Users\%username%\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\`

From there, follow these steps:

1. Locate and delete the**Startup folder** .
2. Create a new startup folder by right-clicking on a blank space and selecting**New > Folder** .
3. Name the folder as**Startup** and press**Enter** .

![Selecting the Startup folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/selecting-the-startup-folder.jpg)

Finally, restart your device to save these changes.

## 3\. Perform a Check Disk Scan

![An illustration of a lens scanning digital devices](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/An-illustration-of-a-lens-scanning-digital-devices.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->

 There’s a possibility that the issue at hand might be caused by system issues. In such instances, scanning and repairing your device’s hard drive could help.

 Here’s how you can resolve the problem using a Check Disk (CHKDSK) scan:

1. Type**Command Prompt** in the Start menu search bar.
2. Right-click on the**Best match** result and select**Run as administrator** .
3. Type the following command and then press**Enter** to scan and repair your hard drive:

`chkdsk C: /f`

 If your Windows operating system (OS) is installed on a different drive, then replace**C:** in the command with the letter of the relevant drive.

Finally, restart your device when the scan is complete.

## 4\. Scan and Repair Windows Using the DISM and SFC Tools

![Computer antivirus illustration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/08/Computer-antivirus-illustration.jpg)

 If a normal disk scan doesn’t help, then you’d need to scan and repair your hard drive using advanced tools such as DISM and SFC. As we covered in our guide on [how to repair corrupted files with built-in Windows tools](https://www.makeuseof.com/windows-built-in-repair-tools/) , DISM and SFC are handy services that can help repair Windows errors.

Let’s start by checking out how you can run the DISM tool:

1. Press**Ctrl + Shift + Esc** to open the Task Manager.
2. Click**File** in the top-left corner and select**Run new task** .
3. Type**CMD** and then check the**Create this task with administrative privileges** box.
4. Press**OK** to run the Command Prompt.
5. Type the following command and press**Enter** :

`DISM /Online /Cleanup-Image /ScanHealth`

 Wait for the process to complete. From there, type the following command and press**Enter** :

`DISM /Online /Cleanup-Image /RestoreHealth`

Finally, restart your device once the DISM scan is complete.

Now, you can run the SFC tool through these steps:

1. Open the**Command Prompt** by following the previous steps.
2. Type the following command and press**Enter** to run the scan:

`sfc /scannow`

Wait for the scan to complete and then restart your device.

## 5\. Run the System Maintenance Troubleshooter

![An illustration of someone configuring settings on a PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/An-illustration-of-someone-configuring-settings-on-a-PC.jpg)
<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Still struggling to resolve the issue? If so, you might be experiencing a system maintenance problem. In this case, you could tackle the error by running the System Maintenance troubleshooter.

Here are the steps you need to follow:

1. Type**Perform recommended maintenance tasks automatically** in the Start menu search bar and press**Enter** .
2. Click the**Next** button and then follow the on-screen instructions.

![Running the System Maintenance Troubleshooter on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Running-the-System-Maintenance-Troubleshooter-on-Windows.jpg)

Wait for the process to complete and then restart your PC.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## 6\. Temporarily Disable the Windows Defender Firewall

 In some instances, temporarily disabling the Windows Defender Firewall could tackle the problem. However, don’t forget to re-enable the tool later.

Now, here are the steps for disabling the Windows Defender Firewall:

1. Type**Control Panel** in the Start menu search bar and select the**Best match** .
2. Click the**View by** drop-down menu and then select**Large icons** .
3. Select**Windows Defender Firewall** from the options.
4. Click the**Turn Windows Defender Firewall on and off** option.

![Selecting the Turn Defender Firewall on or off option on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Selecting-the-Turn-Defender-Firewall-on-or-off-option-on-Windows.jpg)

 Locate the**Domain** ,**Private** , and**Public network settings** and then check the**Turn off Windows Defender Firewall** boxes next to them. Finally, press**OK** and then restart your computer.

![Turning off the Defender Firewall on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Turning-off-the-Defender-Firewall-on-Windows.jpg)

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
## 7\. Use a System Restore Point

 Using a system restore point can help you tackle the issue at hand. However, this approach will only help if you’ve already learned [how to create a system restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) and made one.

 During the restoration process, the system restore tool will revert your PC to a previous state. As such, this tool will help only if the Task Manager error only started appearing recently.

 Here’s how you can tackle the issue at hand using a restore point:

1. Type "Create a restore point" in the Start menu search bar and select the**Best match** .
2. Click the**System Protection** tab and then select**System Restore** from the options.
3. Press**Next** to continue.
4. Select**Show more restore points** and then pick a restore point.
5. Click**Next** and then click**Finish** to finalize the process.

![Using a Restore Point on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Using-a-Restore-Point-on-Windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 8\. Update Your Device

 In some instances, updating your Windows device might be the best solution. Ideally,[you should always update Windows to the latest version](https://www.makeuseof.com/windows-update-new-version-releases-reasons/) , but if you've put it off for a while, try updating your PC.

Here are the steps for updating Windows:

1. Type**Settings** in the Start menu search bar and select the**Best match** .
2. Select**Update & Security** from the options.
3. Select the**Windows Update** option on the left.
4. Click the**Check for updates** button on the right and then follow the on-screen steps.

![Checking for Windows PC updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/9-Checking-for-Windows-PC-updates.jpg)

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## You’ve Successfully Resolved Your Task Manager Issues

 The Task Manager is a reliable tool that helps you close slow programs and improve your PC’s performance. However, this tool also often runs into various problems. If it's experiencing issues with startup programs, you can easily resolve the error using any of the solutions in this article.

 If the issue persists, then maybe it’s time to start exploring some Task Manager alternatives.


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
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-elevate-your-portraits-with-hdr-techniques/"><u>[New] 2024 Approved  Elevate Your Portraits with HDR Techniques</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-how-to-record-perfect-videos-in-total-quietude/"><u>[New] How To Record Perfect Videos in Total Quietude</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-identifying-hidden-account-activities/"><u>[New] Identifying Hidden Account Activities</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-rendering-reawakening-amds-radeon/"><u>[New] In 2024, Rendering Reawakening  AMD's Radeon</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-video-magic-begins-macbooks-webcam-guide/"><u>[New] Video Magic Begins  MacBook's Webcam Guide</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-androids-facetime-essentials-explained/"><u>[Updated] 2024 Approved  Android's FaceTime Essentials Explained</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-from-underscrutinized-to-unforgettable-bio-hacks-for-love-success/"><u>2024 Approved  From Underscrutinized to Unforgettable  Bio Hacks for Love Success</u></a></li>
<li><a href="https://win11.techidaily.com/ditch-the-focus-spotlight-icon-on-win11-desktop/"><u>Ditch the Focus: Spotlight Icon on Win11 Desktop</u></a></li>
<li><a href="https://fox-helps.techidaily.com/enhancing-visual-quests-hunt-for-pristine-pexels-images/"><u>Enhancing Visual Quests  Hunt for Pristine Pexels Images</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-setup-failures-windows-10-and-11-edition/"><u>Fixing Windows Setup Failures: Windows 10 & 11 Edition</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-samsung-galaxy-s24-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For Samsung Galaxy S24 | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hp-deskjet-d1360-print-drivers-troubleshooting-across-windows-versions/"><u>HP Deskjet D1360 Print Drivers: Troubleshooting Across Windows Versions</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-honor-100-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Honor 100 Pro? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-vivo-v29-pro-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For Vivo V29 Pro Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-guide-to-setting-up-windows-11-calendar/"><u>In-Depth Guide to Setting Up Windows 11 Calendar</u></a></li>
<li><a href="https://win11.techidaily.com/master-artistic-creation-with-windows-11-make-amazing-ai-images-using-paint-tool-sai/"><u>Master Artistic Creation with Windows 11: Make Amazing AI Images Using Paint Tool SAI</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-window-settings-for-optimal-space-in-win11/"><u>Master the Window Settings for Optimal Space in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fixes-for-the-exception-has-been-reached-on-pcs/"><u>Mastering Fixes for The Exception Has Been Reached on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-the-managerial-maze-free-old-championship-soccer-management-guide/"><u>Navigate the Managerial Maze: Free Old Championship Soccer Management Guide</u></a></li>
<li><a href="https://win11.techidaily.com/nexus-controller-down-regain-control-with-these-fixes/"><u>Nexus Controller Down? Regain Control with These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-cross-device-use-harnessing-the-power-of-dex/"><u>Optimizing Cross-Device Use: Harnessing the Power of DeX</u></a></li>
<li><a href="https://win11.techidaily.com/pinnacle-speed-5-expertly-engineered-pc-enhancements/"><u>Pinnacle Speed: 5 Expertly Engineered PC Enhancements</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-unpreviewed-documents-error-in-office-outlook/"><u>Quick Fixes for Unpreviewed Documents Error in Office Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-not-found-rockalldlldll-on-windows/"><u>Rectifying 'Not Found' Rockalldll.dll on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-usability-ai-transformations-in-windows/"><u>Redefining Usability: AI Transformations in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-directories-not-empty-error-on-win11-with-0x80070091/"><u>Remedying Directories Not Empty Error on Win11 with #0X80070091</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-a-dormant-tab-key-for-seamless-typing/"><u>Reviving a Dormant Tab Key for Seamless Typing</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-windows-interface-with-alignment/"><u>Streamline Windows Interface with Alignment</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-corrupted-recycle-bin-on-win-11/"><u>Tackling Corrupted Recycle Bin on Win 11</u></a></li>
<li><a href="https://howto.techidaily.com/tecno-spark-go-2023-stuck-on-screen-finding-solutions-for-stuck-on-boot-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Tecno Spark Go (2023) Stuck on Screen – Finding Solutions For Stuck on Boot | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ultimate-guide-to-catch-the-regional-located-pokemon-for-oneplus-nord-3-5g-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Catch the Regional-Located Pokemon For OnePlus Nord 3 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-not-found-in-windows-environments/"><u>Unraveling 'Not Found' In Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-approach-to-turn-off-gpgpu-prioritization-on-winos/"><u>Unveiling the Approach to Turn Off GPGPU Prioritization on WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-virtualbox-to-70-in-win11-a-comprehensive-tutorial/"><u>Upgrading VirtualBox to 7.0 in Win11: A Comprehensive Tutorial</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-oneplus-open-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For OnePlus Open? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/where-are-win11-control-panel-settings-locate-missing-keys/"><u>Where Are Win11 Control Panel Settings? Locate Missing Keys</u></a></li>
<li><a href="https://win11.techidaily.com/xbox-not-launching-fix-it-with-these-tips/"><u>Xbox Not Launching? Fix It with These Tips</u></a></li>
</ul></div>
