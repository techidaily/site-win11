---
title: Seven Methods to Resolve Absence of Optional Windows Options
date: 2024-09-11T09:42:52.768Z
updated: 2024-09-12T09:42:52.768Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Seven Methods to Resolve Absence of Optional Windows Options
excerpt: This Article Describes Seven Methods to Resolve Absence of Optional Windows Options
keywords: Missing Window Features,Fixing No Option Dialogues,Restoring Window Menu Items,Enabling Windows Options,Unlocking OS Settings,Rediscovering GUI Features,Reinstating UI Choices
thumbnail: https://thmb.techidaily.com/cd1e0583a3f82954a7a1df94033dc0576cc47353ebb15c30e049205c45a363ba.jpg
---

## Seven Methods to Resolve Absence of Optional Windows Options

 Optional features are those that you can add to get more functionality or support for certain file formats. For example, you can install different font packs or old Windows utilities like Paint and WordPad.

 If you're having trouble installing optional features, you're not alone. Sometimes optional features may fail to install due to corrupt system files, an outdated Windows version, or incorrect configuration settings.

 Fortunately, there are several ways to fix this problem and get the optional features running again. So, how can you fix the optional features not installing issue?

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126492/26400" target="_top" id="2126492">
  <img src="//a.impactradius-go.com/display-ad/26400-2126492" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126492/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Use the DISM Tool

 One of the first things you can try is using the Deployment Image Servicing and Management (DISM) tool. This tool is part of Windows, and you can use it to fix corrupt system files, including ones that could be causing problems when installing optional features.

To use the DISM tool, follow these steps:

1. Press**Win + Q** to bring up the Windows search dialogue box.
2. Type**cmd** and click**Run as administrator** to open the Command Prompt.
3. Type**dism /online /cleanup-image /restorehealth** and press**Enter** .  
![DISM Windows Utility Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/dism-windows-utility.jpg)

 This will start the DISM tool and begin scanning your system for any corrupt or missing files. If it finds any issues with your computer, it will automatically repair them.

 Once the process is complete, you can restart your computer and try installing the optional feature again. If DISM does not work or throws an error code, make sure to go through the[DISM not working fixes](https://www.makeuseof.com/windows-11-dism-error-2-fix/) .

## 2\. Run the System File Checker or SFC Utility

 Another tool you can use to fix issues with optional feature installation is the System File Checker (SFC) utility.

 SFC is a command-line utility on Windows, which means you can use it from the Command Prompt itself. It is a useful tool for troubleshooting and repairing problems with the system files on your computer, similar to the DISM tool.

To check your system using SFC, follow these steps:

1. Open the Command Prompt with administrative rights using any of the[ways to open CMD as an admin on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. Type**sfc /scannow** and press**Enter** .  
![SFC Utility In Windows Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-utility-in-windows.jpg)
3. Once SFC scans for errors, make sure to restart your computer.

<!-- affiliate ads begin -->
<span id="1424527">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424527.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424527">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424527.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424527%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424527/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Want to know the best part?

 The best part is that the System File Checker not only helps you fix the optional features problem but also any other Windows issues. In fact, it's one of the best[ways to repair corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

## 3\. Reset the Windows Update Components

 Windows Update Components include all the services, tasks, and programs that work together to make sure your Windows system is up-to-date and secure.

 Resetting the Windows Update components might help solve the issue with optional feature installation. Here's how you can reset the Windows Update components easily:

1. Open the Command Prompt utility as an administrator.
2. Type the following commands one after the other, pressing**Enter** after each one:

`net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver  
ren C:\Windows\SoftwareDistribution SoftwareDistribution.old  
ren C:\Windows\System32\catroot2 catroot2.old  
net start wuauserv  
net start cryptSvc  
net start bits  
net start msiserver`

 This command will stop the Windows Update services, rename the**SoftwareDistribution** and**catroot2** folders, and then restart the services. This can help reset the update process and fix any issues that might be causing problems with optional feature installation.

![Update Components Reset In CMD Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/update-components-reset-in-cmd.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137412/7443" target="_top" id="2137412">
  <img src="//a.impactradius-go.com/display-ad/7443-2137412" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137412/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 While the commands may look intimidating, you don't need to worry, as all the commands mentioned above will not cause any harm to your system.​​​​

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123732/7443" target="_top" id="2123732">
  <img src="//a.impactradius-go.com/display-ad/7443-2123732" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123732/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Run the Windows Update Troubleshooter

 If the Command Prompt method did not work for you, you can use the Windows Update Troubleshooter to reset update components. This tool can help identify and fix problems with the update process, including issues that might be preventing optional features from installing.

Follow these steps to run the update troubleshooter on Windows:

1. Press**Win + I** to launch the Settings app.
2. Scroll down and click**Troubleshoot > Other troubleshooters.**  
![Troubleshooter Settings In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/troubleshooter-settings-in-windows.jpg)
3. Click**Run** next to**Windows Update** to run the troubleshooter.  
![Other Troubleshooters In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/other-troubleshooters-in-windows.jpg)
4. Follow the prompts to complete the troubleshooting process.

 If you're using Windows 10, the Windows Update Troubleshooter is in**Settings > Update & Security >** **Troubleshoot > Windows Update** .

 The troubleshooter will begin scanning your system for any issues with the update process and will offer suggestions for how to fix them. So, you just need to follow the prompts, and then try[installing the optional features](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) again.

## 5\. Update Windows to the Latest Version

 If the issue with optional feature installation is related to outdated system files, you may be able to fix it by updating Windows to the latest version.

 Updating Windows can help ensure that you have the latest security patches, bug fixes, and system files, which can help resolve any issues you may be experiencing.

Here's how you can update Windows to the latest version:

1. Press**Win + I** to open the Settings app.
2. Click on**Windows** **Update > Check for updates** on Windows 11\. For Windows 10, click on **Update & Security > Windows Update > Check for Updates** .  
![Windows Update In Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-update-in-windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136618/26400" target="_top" id="2136618">
  <img src="//a.impactradius-go.com/display-ad/26400-2136618" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136618/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 That's it. Now, you can install any update that is available for your computer.

 By default, Windows automatically downloads and installs updates, but you can also check for updates manually by following the steps above.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136614/26400" target="_top" id="2136614">
  <img src="//a.impactradius-go.com/display-ad/26400-2136614" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136614/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Restart the Windows Module Installer Service

 The Windows Module Installer service allows you to install, change, and remove Windows features and optional components. If it is not working properly, it can make it difficult to install optional features.

 Follow the below-given steps to restart the Windows Module Installer service:

1. Open Windows search and type**services** .
2. Select the best match to open the**Services** app.
3. Scroll down and find the**Windows Module Installer** service.
4. Right-click on the service and select**Restart** .  
![Windows Modules Installer Service In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-modules-installer-service.jpg)

<!-- affiliate ads begin -->
<span id="701707">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/701707.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/7443-701707">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/701707.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fappsumo.8odi.net%2Fc%2F5597632%2F701707%2F7443'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/701707/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 When you reset the module installer service, Windows tries to stop it and then start it again, which can help reset the installation process of optional features and fix any issues that might be causing problems.

 Once the service restarts, try installing the optional feature again, and it should work now.

## 7\. Restore Windows Features Using PowerShell

 If all the above methods fail to work, restoring Windows features is your last resort. So, if you are unable to use or install an optional Windows feature, you might be able to fix the problem by using PowerShell to restore a particular feature.

 Here are the steps for restoring Windows features using the PowerShell:

1. Press**Win + X** to open the Power User menu.
2. Click on**Windows PowerShell (Admin)** or**Terminal (Admin)** .
3. Type the following command and press**Enter** :  
Get-WindowsOptionalFeature -Online  
![Get Optional Feature Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/get-optional-feature-command.jpg)  
 This command will show you the**FeatureName** and**State** of every optional Windows feature that you can use. Make sure to copy the "**FeatureName** " of the feature that you want to enable on Windows.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135371/19272" target="_top" id="2135371">
  <img src="//a.impactradius-go.com/display-ad/19272-2135371" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135371/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To turn on a certain feature, use the following command and replace "**FEATURENAME** " with the feature's name that you copied earlier:  
Enable-WindowsOptionalFeature -Online -FeatureName FEATURENAME  
![Enable Optional Feature Command In PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/optional-feature-in-powershell.jpg)
5. Restart your computer for the changes to take effect.

 This will add the feature back to your system and should make it available for you to enable or disable in the features window.

 This method only allows you to restore a specific feature and, not all the features at once. So, you need to copy and paste the same command and edit the**FEATURENAME** every time.

 If these steps don't fix the problem, you may need to ask Microsoft or a technical support professional for more help.

## Get Back the Windows Optional Features

 Hopefully, the issue with optional features not installing on your system should be fixed now. In any case, it is important to keep your system up-to-date and to follow best practices for maintaining your computer properly to help prevent issues like this from occurring.

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
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-streaming-snapshots-for-facebook-2023/"><u>[New] In 2024, Streaming Snapshots for Facebook, 2023</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-instagram-riches-301-safe-and-highest-earning-strategies/"><u>[Updated] Instagram Riches 301 Safe and Highest Earning Strategies</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-beam-your-ideas-master-screencast-with-ezvide-video-maker/"><u>2024 Approved Beam Your Ideas Master Screencast with EZvide Video Maker</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/crafting-a-revenue-generating-online-presence/"><u>Crafting a Revenue-Generating Online Presence</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cross-pc-qbittorrent-migration-tips-and-techniques/"><u>Cross-PC qBittorrent Migration Tips & Techniques</u></a></li>
<li><a href="https://tech-revival.techidaily.com/deep-dive-into-rising-risks-how-generative-ais-security-problems-are-set-to-intensify/"><u>Deep Dive Into Rising Risks: How Generative AI's Security Problems Are Set to Intensify</u></a></li>
<li><a href="https://win11.techidaily.com/edges-steady-cycle-managing-on-windows-11/"><u>Edge's Steady Cycle: Managing on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-continuous-tab-integrity-in-explorer/"><u>Ensuring Continuous Tab Integrity in Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-functional-status-of-windows-event-viewer/"><u>Ensuring Functional Status of Windows Event Viewer</u></a></li>
<li><a href="https://win11.techidaily.com/experience-freed-digital-conversations-winstyle/"><u>Experience Freed Digital Conversations, WinStyle</u></a></li>
<li><a href="https://win11.techidaily.com/expert-fixes-how-to-bypass-the-inability-to-rename-directories-in-win-11/"><u>Expert Fixes: How to Bypass the Inability to Rename Directories in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/expertise-at-your-fingertips-powerrename-capabilities/"><u>Expertise at Your Fingertips: PowerRename Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-windows-11s-enhanced-data-protection-strategy/"><u>Exploring Windows 11'S Enhanced Data Protection Strategy</u></a></li>
<li><a href="https://win11.techidaily.com/extending-windows-10-shutdown-time-tips-for-active-tasks/"><u>Extending Windows 10 Shutdown Time: Tips for Active Tasks</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/farm-frontier-the-best-seed-to-sow-in-gaming-for-2024/"><u>Farm Frontier The Best Seed to Sow in Gaming for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/full-guide-to-bypass-tecno-spark-20-proplus-frp-by-drfone-android/"><u>Full Guide to Bypass Tecno Spark 20 Pro+ FRP</u></a></li>
<li><a href="https://discover-advanced.techidaily.com/gartner-magic-quadrant-2024abbyy/"><u>Gartner® Magic Quadrant™ 2024でABBYY: 先駆的なプロセスマイニングソリューションのトップ選</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-fix-a-non-responsive-login-screen-in-windows-1011/"><u>Guide to Fix a Non-Responsive Login Screen in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/guide-how-to-quickly-screenshot-uac-prompts/"><u>Guide: How to Quickly ScreenShot UAC Prompts</u></a></li>
<li><a href="https://win11.techidaily.com/guide-stopping-discord-initial-launch-and-updates-on-windows/"><u>Guide: Stopping Discord Initial Launch & Updates on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-windows-keyboard-shortcuts-activating-while-typing/"><u>How to Fix Windows Keyboard Shortcuts Activating While Typing</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-increase-virtual-memory-in-windows-11/"><u>How to Increase Virtual Memory In Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-win-friendly-chatgpt-services/"><u>Implementing Win-Friendly ChatGPT Services</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-4-ways-to-transfer-music-from-infinix-zero-30-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 4 Ways to Transfer Music from Infinix Zero 30 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-samsung-galaxy-m14-5g-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on Samsung Galaxy M14 5G</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-mastering-snapchat-boomerangs-ultimate-instructions/"><u>In 2024, Mastering Snapchat Boomerangs Ultimate Instructions</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-oppo-find-n3-flip-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Oppo Find N3 Flip? | Dr.fone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-your-pathway-to-successful-youtube-beginnings-techniques-1-and-2/"><u>In 2024, Your Pathway to Successful YouTube Beginnings (Techniques 1 & 2)</u></a></li>
<li><a href="https://extra-tips.techidaily.com/leveraging-the-power-of-windows-11s-auto-hdr-enhancement/"><u>Leveraging the Power of Windows 11'S Auto HDR Enhancement</u></a></li>
<li><a href="https://win11.techidaily.com/minecraft-wi-fi-connectivity-problems-solved-on-pc/"><u>Minecraft Wi-Fi Connectivity Problems, Solved on PC</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/node-local-and-link-local-multicasts-cannot-leave-their-immediate-network-or-link-respectively/"><u>Node-Local and Link-Local Multicasts Cannot Leave Their Immediate Network or Link, Respectively</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-speaker-mixer-levels-after-a-system-glitch/"><u>Resetting Speaker Mixer Levels After a System Glitch</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-non-running-print-spooler-on-windows-devices/"><u>Resolving Non-Running Print Spooler on Windows Devices</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/snap-worthy-success-logging-galaxy-gaming-stories-for-2024/"><u>Snap-Worthy Success Logging Galaxy Gaming Stories for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-invalid-profile-error-windows-xpvista7-solution/"><u>Tackling Invalid Profile Error: Windows XP/Vista/7 Solution</u></a></li>
<li><a href="https://win11.techidaily.com/the-ins-and-outs-of-windows-11-calendar-interface/"><u>The Ins and Outs of Windows 11 Calendar Interface</u></a></li>
<li><a href="https://win11.techidaily.com/the-new-codex-of-operating-systems-post-windows-era/"><u>The New Codex of Operating Systems: Post-Windows Era</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-correctly-handle-windows-update-failure-error-0x80070003/"><u>Tips to Correctly Handle Windows Update Failure Error 0X80070003</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-stuck-exe-files-in-windows-systems/"><u>Unlocking Stuck .exe Files in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-characters-with-win11s-tool/"><u>Unraveling Characters with Win11's Tool</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-vocal-vanishing-act-how-to-seamlessly-remove-singers-voice-from-an-audio-track-using-audacity-tools/"><u>Updated Vocal Vanishing Act How to Seamlessly Remove Singers Voice From an Audio Track Using Audacity Tools</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-oneplus-11-5g-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On OnePlus 11 5G | Dr.fone</u></a></li>
</ul></div>

