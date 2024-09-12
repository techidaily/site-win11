---
title: Effortless Setup for Your Safety-First Workspace (Win 11)
date: 2024-09-11T09:33:11.341Z
updated: 2024-09-12T09:33:11.341Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Effortless Setup for Your Safety-First Workspace (Win 11)
excerpt: This Article Describes Effortless Setup for Your Safety-First Workspace (Win 11)
keywords: Win 11 Secure Workspace,Easy Win 11 Security,Safe Workspace Setup,Quick Win 11 Safety,Simplified Win 11 Guard,Effortless Win 11 Protection,Intuitive Win 11 Safeguard
thumbnail: https://thmb.techidaily.com/600ab240c6c8b1ad864f3c8d1c4daad9b77c19a5afa889dc63fba4f50be8c27e.jpg
---

## Effortless Setup for Your Safety-First Workspace (Win 11)

 Microsoft Windows 11 features multiple virtualization solutions out of the box. While Hyper-V is an excellent tool, Windows Sandbox is an easy alternative to Windows virtual machines. It lets you run untrusted apps in an isolated environment without the hassle of setting up a complete virtualization tool.

 Unfortunately, Windows Sandbox is not available on the Home edition of the OS. If you are running the Pro, Enterprise, and Education edition, here is how to enable and set up Windows Sandbox in Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Set Up Windows Sandbox in Windows 11

 Windows Sandbox is an optional feature, which means you'll have to install it from the Optional features section. You can[add and remove optional features from the Windows Features dialog](http://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) . Alternatively, you can use PowerShell or Command Prompt for a swift installation of Windows Sandbox.

 While the setup process is easier, your computer must meet some system requirements. Windows 11 Pro, Education, or Enterprise running computers with virtualization support are Windows Sandbox compatible. In most cases,[if your system can run Windows Hyper-V](https://www.makeuseof.com/windows-11-enable-hyper-v/) , it should also run Windows Sandbox.

## 1\. Enable Windows Sandbox Using the Windows Features Dialog

 You can install Windows Sandbox using the Windows Features dialog. This dialog houses most of the optional Windows features that are ready to be installed on your PC.

 Follow these steps to install Windows Sandbox using the Windows Features dialog:

1. Press**Win + R** to open**Run** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**
3. In the left panel, click on**Turn Windows features on or off.**  
![control panel turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/control-panel-turn-windows-features-on-or-off.jpg)
4. In the**Turn Windows features on or off dialog** , scroll down and locate**Windows Sandbox.**

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135394/19272" target="_top" id="2135394">
  <img src="//a.impactradius-go.com/display-ad/19272-2135394" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135394/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Check the**Windows Sandbox** option and click**OK** .  
![enable Windows sandbox turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-Windows-sandbox-turn-windows-features-on-or-off.jpg)
6. Windows will search for the files and install the required dependencies to run Windows Sandbox scenarios. Once the changes are applied, close the Windows features dialog and restart your PC.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134490/18498" target="_top" id="2134490">
  <img src="//a.impactradius-go.com/display-ad/18498-2134490" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134490/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. After the restart, press**Win + S** to open**Windows search.**
8. Type**sandbox** and click on**Windows Sandbox** from the search result to launch the virtualization tool.

## 3\. Install Windows Sandbox Using PowerShell

![enable windows sandbox powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-powershell.jpg)

<!-- affiliate ads begin -->
<span id="1983573">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983573.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983573">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983573.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983573%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983573/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can use the Enable WindowsOptionalFeature command in PowerShell to install Windows Sandbox in Windows. This method is useful if you find the sandbox option greyed out or unable to install it from the Windows Feature dialog.

To install Windows Sandbox using PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal (Admin)** to open the Windows Terminal with administrative privilege. Since PowerShell is assigned as the default profile upon launch, you can execute your PowerShell cmdlets straight away in Windows Terminal.
3. In the Windows Terminal window, copy and paste the following command and press Enter:  
Enable-WindowsOptionalFeature -Online -FeatureName "Containers-DisposableClientVM" -All
4. If no error occurs, Windows will install the required files to enable Windows Sandbox.
5. Once done, press**Y** and hit**Enter** to restart your PC.
6. After the restart, you can launch Windows Sandbox from Windows Search.

<!-- affiliate ads begin -->
<span id="1702748">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1702748.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18544-1702748">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1702748.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftwopages.pxf.io%2Fc%2F5597632%2F1702748%2F18544'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702748/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Install Windows SandBox Using Command Prompt

![enable windows sandbox command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-command-prompt.jpg)

<!-- affiliate ads begin -->
<span id="1975503">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975503.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975503">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975503.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975503%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975503/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Deployment Image Servicing and Management (DISM) is a command-line utility that facilitates the installation of optional features using the Command Prompt. To install Windows Sandbox, you will need to use the Enable-Feature command in Command Prompt. Here's how to do it.

1. Press**Win + R** to open**Run** .
2. Type**cmd** in the**Run** dialog. Press and hold**Ctrl + Shift** and click**OK** to open Command Prompt as administrator.
3. In the Command Prompt, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName: "Containers-DisposableClientVM" -All`
4. Wait for the process to complete. Once done, press**Y** and**Enter** to restart your PC.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139118/17108" target="_top" id="2139118">
  <img src="//a.impactradius-go.com/display-ad/17108-2139118" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139118/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Use Windows Sandbox

![Windows Sandbox Open](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Windows-Sandbox-Open.jpg)

 Now that you have Windows Sandbox installed, you can start using it to test untrusted apps in isolation. To launch the app, press**Win + S** to open**Windows Search** and type**Windows Sandbox.** Click on the app from the search result to open it.

 Upon its launch, Windows Sandbox looks like a lightweight version of your Windows machine. You can copy files from your host system or download them from the Internet using the built-in web browser. Any actions you perform in the sandbox will not affect your host system.

 Once the testing is complete, close the Sandbox and click**OK** to confirm the action. Unlike a VM, Sandbox will delete all the data (including apps and files) upon exit. So, you'll get a clean, isolated environment running the same Windows OS build as your host machine each time.

## Set Up and Use Windows Sandbox in Windows 11

 Windows Sandbox provides an excellent way to test apps and files in an isolated environment without the hassle of setting up a virtual machine. While the virtual machines have distinct advantages, Sandbox is lighter, faster, and loads a fresh copy of Windows OS each time it's run.

 Windows 11 Home users, however, have missed out on this excellent feature. But if you must use a sandbox, consider using third-party alternatives such as Sandboxie Plus and SHADE Sandbox. These alternatives offer a similar set of functionalities with no complicated setup involved.

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
<li><a href="https://digital-screen-recording.techidaily.com/new-apeaks-leap-forward-in-screen-capture-review-and-results/"><u>[New] Apeak’s Leap Forward in Screen Capture – Review and Results</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-perfecting-the-chorus-of-visual-content-on-facebook-through-music/"><u>[New] In 2024, Perfecting the Chorus of Visual Content on Facebook Through Music</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-master-the-art-of-typography-in-adobe-writes-for-2024/"><u>[New] Master the Art of Typography in Adobe' Writes for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/icro-vids-unpacked-whats-the-score/"><u>[New] Micro Vids Unpacked What's the Score?</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-prime-screen-grabs-for-film-enthusiasts/"><u>[Updated] 2024 Approved Prime Screen Grabs for Film Enthusiasts</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-a-primer-to-perfect-hdr-cameras-the-definitive-list/"><u>[Updated] A Primer to Perfect HDR Cameras The Definitive List</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-constructing-visually-captivating-photo-collections-for-2024/"><u>[Updated] Constructing Visually Captivating Photo Collections for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-oneplus-nord-n30-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on OnePlus Nord N30 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-windows-11-directory-exposure/"><u>Customize Your Window's 11 Directory Exposure</u></a></li>
<li><a href="https://win11.techidaily.com/decisive-action-plan-for-banishing-flashing-screens-on-windows/"><u>Decisive Action Plan for Banishing Flashing Screens on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/deconstructing-the-keygen-virus-symptoms-damage-and-how-to-eradicate-it-on-windows/"><u>Deconstructing the Keygen Virus: Symptoms, Damage, and How to Eradicate It on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/dial-down-dysfunction-restore-your-pcs-essential-esc-keys/"><u>Dial Down Dysfunction: Restore Your PC's Essential Esc Keys</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-always-on-top-notations-on-windows/"><u>Ensuring Always On-Top Notations on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/excellence-in-organizing-top-windows-to-dos-revealed/"><u>Excellence in Organizing: Top Windows To-Dos Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-iphone-images-not-working-with-windows-systems/"><u>Fixes for iPhone Images Not Working with Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-based-valorant-audio-glitches/"><u>Fixing Windows-Based Valorant Audio Glitches</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-oppo-find-x6-pro-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Oppo Find X6 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-around-regedit-is-not-found/"><u>How to Get Around Regedit Is Not Found</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-preserve-your-custom-audio-settings-on-windows/"><u>How to Preserve Your Custom Audio Settings on Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-spy-on-text-messages-from-computer-and-oppo-find-n3-flip-drfone-by-drfone-virtual-android/"><u>In 2024, How to Spy on Text Messages from Computer & Oppo Find N3 Flip | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-samsung-galaxy-a15-5g-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Samsung Galaxy A15 5G Phone Hassle-Free</u></a></li>
<li><a href="https://win11.techidaily.com/leverage-powertoys-to-speed-up-rename-tasks/"><u>Leverage PowerToys to Speed Up Rename Tasks</u></a></li>
<li><a href="https://win11.techidaily.com/master-plan-restore-google-drive-sync-on-your-desktop/"><u>Master Plan: Restore Google Drive Sync on Your Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-memory-metrics-for-windows-users/"><u>Mastery over Memory Metrics for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-maze-of-common-rainmeter-challenges-on-pcs/"><u>Navigating the Maze of Common Rainmeter Challenges on PCs</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-composing-the-perfect-audio-landscape-finding-silent-sound-for-visual-narratives-for-2024/"><u>New Composing the Perfect Audio Landscape Finding Silent Sound for Visual Narratives for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-barriers-for-unauthorized-software/"><u>Overcoming Windows Barriers for Unauthorized Software</u></a></li>
<li><a href="https://win11.techidaily.com/reactivating-disabled-cpu-cooling-mechanism-in-os/"><u>Reactivating Disabled CPU Cooling Mechanism in OS</u></a></li>
<li><a href="https://win11.techidaily.com/recognize-invisible-drives-and-fix-windows-errors/"><u>Recognize Invisible Drives & Fix Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/reigniting-windows-11-triggering-start-with-a-windows-7-code/"><u>Reigniting Windows 11: Triggering Start with a Windows 7 Code</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-no-saving-problem-with-photoapp/"><u>Remedy for 'No Saving' Problem with PhotoApp</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-crashing-resource-monitor-app-in-win11/"><u>Reviving Your Crashing Resource Monitor App in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/screenshots-secure-stow-in-windows/"><u>Screenshots' Secure Stow in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-integration-of-vbox-in-your-windows-environment/"><u>Seamless Integration of VBox in Your Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/speak-type-win-navigating-text-creation-using-windows-whisper/"><u>Speak, Type, Win: Navigating Text Creation Using Windows Whisper</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-fix-windows-virtualbox-efail-0x80004005-glitch/"><u>Steps to Fix Windows Virtualbox E_FAIL (0X80004005) Glitch</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-windows-pin-modification/"><u>The Ultimate Guide to Windows PIN Modification</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/the-ultimate-playbook-for-splitting-views-in-facebook-livestreams/"><u>The Ultimate Playbook for Splitting Views in Facebook Livestreams</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-trim-windows-overscan-for-flawless-screen-match/"><u>Tips to Trim Windows Overscan for Flawless Screen Match</u></a></li>
<li><a href="https://win11.techidaily.com/turbo-upgrade-top-5-tools-to-supercharge-your-pc/"><u>Turbo Upgrade: Top 5 Tools to Supercharge Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-peak-performance-windows-11s-best-productivity-widgets/"><u>Unlocking Peak Performance: Windows 11'S Best Productivity Widgets</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-if-the-microsoft-store-wont-install-an-app/"><u>What to Do If the Microsoft Store Won't Install an App</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-inside-the-settings-experience/"><u>Windows 11: Inside the Settings Experience</u></a></li>
<li><a href="https://win11.techidaily.com/windows-security-reboot-a-guide-to-altering-rules/"><u>Windows Security Reboot: A Guide to Altering Rules</u></a></li>
<li><a href="https://win11.techidaily.com/windows-subsystem-phaseout-strategizing-for-future-android-support/"><u>Windows Subsystem Phaseout: Strategizing for Future Android Support</u></a></li>
<li><a href="https://vp-tips.techidaily.com/zany-zooms-taking-your-selfies-to-a-whimsical-level-on-snapchat-for-2024/"><u>Zany Zooms Taking Your Selfies to a Whimsical Level on Snapchat for 2024</u></a></li>
</ul></div>

