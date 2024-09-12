---
title: Handling and Fixing Windows System’s Exception Breakpoint Error
date: 2024-09-11T09:31:00.214Z
updated: 2024-09-12T09:31:00.214Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Handling and Fixing Windows System’s Exception Breakpoint Error
excerpt: This Article Describes Handling and Fixing Windows System’s Exception Breakpoint Error
keywords: Windows System Error Resolution,Solve System Exceptions,Debugging Window Errors,Handling Windows Crashes,Fixing System Breakpoints,Exception Error Windows,Troubleshoot OS Crashes
thumbnail: https://thmb.techidaily.com/603cef112c71acaaa3fdccdd6f7a956de3ad09701fee843146114a343a411d66.jpg
---

## Handling and Fixing Windows System’s Exception Breakpoint Error

 When you try to shut down or restart your PC, you may encounter an error that reads "the exception breakpoint has been reached." This error can also occur when you try to open specific apps on your PC.

 Issues with your system files, glitchy apps, memory leaks, and bad disk sectors are common contributing factors to this error. If you experience this error, here is a quick troubleshooting guide to help you fix the "the exception breakpoint has been reached" error on your PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Disable Any Automatic Startup Apps

 Apart from the essential Windows services, third-party apps enabled to run during startup can cause conflicts and cause problems. To determine the cause, disable all the automatic startup apps and restart your PC.

To disable startup apps on Windows:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Task Manager** to open the app.
3. In Task Manager, open the**Startup apps** tab.
4. Click the**Status** column to sort the table with the enabled apps at the top.
5. Select all the apps one by one and click**Disabled** .  
![disable startup apps windows 11 new](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/disable-startup-apps-windows-11-new.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123732/7443" target="_top" id="2123732">
  <img src="//a.impactradius-go.com/display-ad/7443-2123732" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123732/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once done, restart your PC and check if the error persists. If not, enable the apps again one by one until you find the problematic application. Depending on the use, you can update, uninstall or find an alternative for the app.

## 2\. Run the System File Checker and the DISM Tools

 The Deployment Image Service Management (DISM) tool is a command-line utility that can find and fix issues with your Windows image. If your error is triggered by a corrupt system image, the DISM command can help you fix the error.

 In addition, we'll also run the System File Checker utility. Like DISM, the System File Checker is a built-in command-line utility to detect and fix corrupted or missing system files on Windows computers.

Follow these steps to run the DISM and System File Checker tools:

1. Open Command Prompt as an administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) if you need help).
2. In the Command Prompt window, type the following command to check your system health:  
`Dism /Online /Cleanup-Image /CheckHealth`
3. ![DISM scan health restore health command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dism-scan-health-restore-health-command-prompt-1.jpg)  
 Next, type the following command and press**Enter** to scan your PC's health:  

<!-- affiliate ads begin -->
<span id="1495277">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1495277.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17189-1495277">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1495277.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ffunwhole.sjv.io%2Fc%2F5597632%2F1495277%2F17189'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1495277/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`Dism /Online /Cleanup-Image /ScanHealth`
4. Once done, type the following command to repair the system image:  
`Dism /Online /Cleanup-Image /RestoreHealth`
5. This process may take several minutes, so wait till the verification reaches 100%.
6. Once done, type the following command to execute the System File Checker utility:  
`sfc /scannow`
7. This process can take some time to complete. Once the verification reaches 100%, it will display the result and any actions taken.
8. Type**exit** and press**Enter** to close Command Prompt.

## 3\. Check Your Hard Drive for Errors With CHKDSK

 Check Disk (CHKDSK) is a Windows command-line utility to find and fix issues on your hard drive due to bad sectors. You can run the tool on your traditional mechanical hard drive and Solid State Drives (SSDs).

 You can use the CHKDSK utility with multiple parameters. Here we'll use the /r parameter to locate bad sections and recover readable information.

To run the CHKDSK tool:

1. Open Command Prompt as administrator, as you did in method two.
2. In the Command Prompt window, type the following command and press**Enter** to run the CHKDSK utility:  
`chkdsk C: /r`

![The chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-chkdsk-command.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123473/16836" target="_top" id="2123473">
  <img src="//a.impactradius-go.com/display-ad/16836-2123473" border="0" alt="https://techidaily.com" width="254" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123473/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 When executed, it will scan and check your system drive (C:/) for bad sectors. Wait for the scan to finish and close the Command Prompt window.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120866/26400?prodsku=mars" target="_top" id="2120866">
  <img src="//a.impactradius-go.com/display-ad/26400-2120866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120866/26400?prodsku=mars" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Turn Off Any GPU Overclocking

 If the error is triggered while performing a graphic-intensive task (such as playing a game or rendering 3D models), it can be due to an overclocked GPU.

 While an overclocked GPU offers performance benefits, it can cause your system to crash and trigger multiple errors if not done correctly. Whether you have used a third-party GPU overclocking tool or a proprietary app from your GPU manufacturer, undo all the recent instances of GPU overclocking to see if that helps fix this error.

 If you need help with overclocking, check out[the best GPU overclocking tools](https://www.makeuseof.com/best-gpu-overclocking-tools/) to get the best results.

<!-- affiliate ads begin -->
<span id="1983539">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983539.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983539">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983539.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983539%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983539/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Check for Memory Leaks

 The "the exception breakpoint has been reached" 0x80000003 can occur if your system fails to efficiently utilize the available memory resulting in a memory leak. Fortunately, Window comes with a built-in Memory Diagnostic Tool to check your computer for memory problems. Here's how to do it.

1. Make sure to save all the work and close all the running apps.
2. Press**Win + R** to open**Run** .
3. Type**mdsched.exe** and click**OK** .
4. In the**Windows Memory Diagnostic** dialog, click**Restart now and check for problems (recommended)** .  
![Windows memory diagnostic tool restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-memory-diagnostic-tool-restart.jpg)
5. Your computer will restart and boot into the Windows Memory Diagnostic Tool menu, and the system will start a test automatically.  
![Windows memory diagnostic tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-memory-diagnostic-tooljpg.jpg)
6. You can also perform**Basic, Standard, or Extended** test manually. To do this, press**F1** to access the**Options** menu and select from the**Basic, Standard, and Extended** option under the**Test Mix** section.
7. If a problem is detected, you can view it under the Status section. Even if the test appears inactive or stuck, do not shut down your computer until testing is complete.
8. Once done, the PC will start, and the Windows Memory Diagnostic Tool will display the test result after you log on.

## 6\. Create a New Windows Local Account

 A corrupted user profile may cause the "the exception breakpoint has been reached" error. To fix the error, you can[create a new user local user profile on Windows 11](https://www.makeuseof.com/windows-11-create-local-user-account/) and give it administrator privilege. Sign into your new user profile and launch the app to see if the error is resolved.

<!-- affiliate ads begin -->
<span id="1982596">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982596.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982596">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982596.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982596%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982596/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Update or Uninstall the Problematic App

 If specific apps trigger the error, such as the Origin launcher or the Steam client, consider reinstalling the app to solve the issue.

 Before you uninstall it, check if your app has any pending updates. Install any update available and check for any improvements. If the issue persists, reinstalling the app may be necessary.

To uninstall an application on Windows:

1. Press**Win + I** to open**Settings** .
2. Open the**Apps** tab in the left pane.
3. Click on**Install** **apps** .  
![windows 11 settings installed apps](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-11-settings-installed-apps.jpg)
4. Type the name of your app in the search bar.  

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123477/16836" target="_top" id="2123477">
  <img src="//a.impactradius-go.com/display-ad/16836-2123477" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123477/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![uninstall apps windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-apps-windows-11.jpg)
5. Next, click**the three-dots menu** next to the app name and**Uninstall** .
6. Click on**Uninstall** again to confirm the action.
7. Once uninstalled, download the app installer and install the app. Restart your PC and check for any improvements.

 Note that, at times, the issue can be with a specific version of the app. To fix this, try to install an older version of the app to see if that works.

## Fixing the "The Exception Breakpoint Has Been Reached" Error on Windows

 This error is often related to your system's inability to utilize the memory resources available due to system file corruption or issues with your hard disk. Use the built-in Windows image repair and System File Checker too to resolve system issues. Also, install pending updates for the app or reinstall the problematic app to fix the problem.

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
<li><a href="https://remote-screen-capture.techidaily.com/new-maximizing-communication-clarity-with-professional-skype-recordings/"><u>[New] Maximizing Communication Clarity with Professional Skype Recordings</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-tips-and-tricks-for-effective-google-meet-capture-for-2024/"><u>[New] Tips and Tricks for Effective Google Meet Capture for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-evaluating-the-future-of-video-editing-with-movavis-plus-2024/"><u>[Updated] Evaluating the Future of Video Editing with Movavi's Plus 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-superior-solutions-3d-models-in-animation-space/"><u>[Updated] In 2024, Superior Solutions 3D Models in Animation Space</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-premier-manual-leveraging-mobizens-full-potential-for-mobile-capture-for-2024/"><u>[Updated] Premier Manual Leveraging Mobizen's Full Potential for Mobile Capture for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-realizing-dreamscapes-picks-of-the-best-tools-for-animation-artists/"><u>[Updated] Realizing Dreamscapes Picks of the Best Tools for Animation Artists</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-video-ventures-uploading-to-twtplustumble-feeds-for-2024/"><u>[Updated] Video Ventures Uploading to Twt+Tumble Feeds for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-photoshops-role-in-crafting-stunning-hdr-visuals/"><u>2024 Approved Photoshop's Role in Crafting Stunning HDR Visuals</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-asus-rog-phone-7-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Asus ROG Phone 7 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-edge-text-alterations-with-snipping-tool/"><u>Cutting Edge Text Alterations with Snipping Tool</u></a></li>
<li><a href="https://win11.techidaily.com/do-your-windows-settings-reset-to-default-on-reboot-try-these-fixes/"><u>Do Your Windows Settings Reset to Default on Reboot? Try These Fixes</u></a></li>
<li><a href="https://driver-download.techidaily.com/download-free-and-updated-realtek-graphics-card-drivers-compatible-with-windows-nx/"><u>Download Free & Updated Realtek Graphics Card Drivers Compatible with Windows nX</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-multitasking-through-90-degree-display-rotation/"><u>Efficient Multitasking Through 90-Degree Display Rotation</u></a></li>
<li><a href="https://win11.techidaily.com/eight-slips-new-users-shouldnt-fall-into-with-windows-11/"><u>Eight Slips New Users Shouldn't Fall Into With Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-problematic-code-0x00000001-a-guide-to-xbox-game-pass-fixes-on-windows-11/"><u>Eliminating Problematic Code 0X00000001: A Guide to Xbox Game Pass Fixes on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/ensure-your-windows-screenscape-remains-same/"><u>Ensure Your Windows Screenscape Remains Same</u></a></li>
<li><a href="https://win11.techidaily.com/evade-windows-sign-in-sequence-with-short-term-profiles/"><u>Evade Windows Sign-In Sequence with Short-Term Profiles</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/exploring-the-compact-marvel-in-depth-analysis-of-the-apple-iphone-12-mini/"><u>Exploring the Compact Marvel - In-Depth Analysis of the Apple iPhone 12 Mini</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/failed-to-play-mp4-movies-with-xiaomi-14-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Failed to play MP4 movies with Xiaomi 14</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-infinix-note-30i-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Infinix Note 30i | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-eliminate-windows-task-failure-error-0x8007000f/"><u>How to Eliminate Window's Task Failure Error 0X8007000f</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-install-windows-11-in-vmware-workstation-17-player/"><u>How to Install Windows 11 in VMware Workstation 17 Player</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-6-proven-ways-to-unlock-oppo-f23-5g-phone-when-you-forget-the-password-by-drfone-android/"><u>In 2024, 6 Proven Ways to Unlock Oppo F23 5G Phone When You Forget the Password</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-8-solutions-to-fix-find-my-friends-location-not-available-on-realme-c55-drfone-by-drfone-virtual-android/"><u>In 2024, 8 Solutions to Fix Find My Friends Location Not Available On Realme C55 | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-a-comprehensive-guide-to-penning-appealing-vlog-narratives/"><u>In 2024, A Comprehensive Guide to Penning Appealing Vlog Narratives</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-full-tutorial-to-bypass-your-oppo-find-n3-flip-face-lock-by-drfone-android/"><u>In 2024, Full Tutorial to Bypass Your Oppo Find N3 Flip Face Lock?</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-list-of-pokemon-go-joysticks-on-infinix-note-30-vip-drfone-by-drfone-virtual-android/"><u>In 2024, List of Pokémon Go Joysticks On Infinix Note 30 VIP | Dr.fone</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/in-depth-gimp-assessment-top-rated-no-cost-graphics-software-across-multiple-platforms/"><u>In-Depth GIMP Assessment: Top Rated, No Cost Graphics Software Across Multiple Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/interface-revamp-visualizing-disk-and-network-resources/"><u>Interface Revamp: Visualizing Disk and Network Resources</u></a></li>
<li><a href="https://win11.techidaily.com/key-driven-awakening-mouse-and-keyboards-role-on-windows-1011/"><u>Key-Driven Awakening: Mouse & Keyboard's Role on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-fix-for-media-server-collapse/"><u>Mastering the Fix for Media Server Collapse</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-globally-advanced-mouse-techniques-in-powertoys/"><u>Navigating Globally: Advanced Mouse Techniques in PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-network-nooks-overcoming-obs-connectivity-concerns-7-ways/"><u>Navigating Network Nooks: Overcoming OBS Connectivity Concerns (7 Ways)</u></a></li>
<li><a href="https://win11.techidaily.com/power-surprise-camouflaging-the-shutdown-icon-in-win11/"><u>Power Surprise: Camouflaging the Shutdown Icon in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/powerrename-the-essential-tool-for-files/"><u>PowerRename: The Essential Tool for Files</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-updater-glitch-code-0x80073712/"><u>Quick Fixes for Updater Glitch: Code 0X80073712</u></a></li>
<li><a href="https://win11.techidaily.com/responding-to-noninteractive-elements-in-new-windows-release/"><u>Responding to Noninteractive Elements in New Windows Release</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-your-win-11-menu-choices/"><u>Simplifying Your Win 11 Menu Choices</u></a></li>
<li><a href="https://win11.techidaily.com/spooler-revival-instruction-for-win/"><u>Spooler Revival Instruction for Win</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solutions-for-win-rpc-errors-a-quick-guide/"><u>Swift Solutions for Win RPC Errors - A Quick Guide</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ultimate-buyers-guide-leading-pc-configurations-for-gamers-in-2e3-budget-to-luxury/"><u>Ultimate Buyer's Guide: Leading PC Configurations for Gamers in 2E3 (Budget to Luxury)</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-overcoming-non-registered-devices-issue/"><u>Understanding & Overcoming Non-Registered Devices Issue</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-disk-space-insights-via-powershell-scripts/"><u>Unlocking Disk Space Insights via PowerShell Scripts</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-the-art-of-audio-fading-2-techniques-to-elevate-your-videos-in-final-cut-pro/"><u>Updated The Art of Audio Fading 2 Techniques to Elevate Your Videos in Final Cut Pro</u></a></li>
<li><a href="https://win11.techidaily.com/win11-customization-keeping-the-look-unaltered/"><u>Win11 Customization: Keeping the Look Unaltered</u></a></li>
</ul></div>

