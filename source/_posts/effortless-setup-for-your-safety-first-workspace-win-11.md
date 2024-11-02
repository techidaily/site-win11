---
title: Effortless Setup for Your Safety-First Workspace (Win 11)
date: 2024-10-27T01:31:33.102Z
updated: 2024-11-01T22:09:48.023Z
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
<a href="https://appsumo.8odi.net/c/5597632/2118314/7443" target="_top" id="2118314">
  <img src="//a.impactradius-go.com/display-ad/7443-2118314" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118314/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Check the**Windows Sandbox** option and click**OK** .  
![enable Windows sandbox turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-Windows-sandbox-turn-windows-features-on-or-off.jpg)
6. Windows will search for the files and install the required dependencies to run Windows Sandbox scenarios. Once the changes are applied, close the Windows features dialog and restart your PC.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134238/18498" target="_top" id="2134238">
  <img src="//a.impactradius-go.com/display-ad/18498-2134238" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134238/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. After the restart, press**Win + S** to open**Windows search.**
8. Type**sandbox** and click on**Windows Sandbox** from the search result to launch the virtualization tool.

## 3\. Install Windows Sandbox Using PowerShell

![enable windows sandbox powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-powershell.jpg)

<!-- affiliate ads begin -->
<span id="1492813">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1492813.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1492813">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1492813.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1492813%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1492813/14559" style="position:absolute;visibility:hidden;" border="0" />
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

## 3\. Install Windows SandBox Using Command Prompt

![enable windows sandbox command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-command-prompt.jpg)

 Deployment Image Servicing and Management (DISM) is a command-line utility that facilitates the installation of optional features using the Command Prompt. To install Windows Sandbox, you will need to use the Enable-Feature command in Command Prompt. Here's how to do it.

1. Press**Win + R** to open**Run** .
2. Type**cmd** in the**Run** dialog. Press and hold**Ctrl + Shift** and click**OK** to open Command Prompt as administrator.
3. In the Command Prompt, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName: "Containers-DisposableClientVM" -All`
4. Wait for the process to complete. Once done, press**Y** and**Enter** to restart your PC.

## How to Use Windows Sandbox

![Windows Sandbox Open](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Windows-Sandbox-Open.jpg)

 Now that you have Windows Sandbox installed, you can start using it to test untrusted apps in isolation. To launch the app, press**Win + S** to open**Windows Search** and type**Windows Sandbox.** Click on the app from the search result to open it.

 Upon its launch, Windows Sandbox looks like a lightweight version of your Windows machine. You can copy files from your host system or download them from the Internet using the built-in web browser. Any actions you perform in the sandbox will not affect your host system.

 Once the testing is complete, close the Sandbox and click**OK** to confirm the action. Unlike a VM, Sandbox will delete all the data (including apps and files) upon exit. So, you'll get a clean, isolated environment running the same Windows OS build as your host machine each time.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012406/19272" target="_top" id="2012406">
  <img src="//a.impactradius-go.com/display-ad/19272-2012406" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012406/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://article-knowledge.techidaily.com/new-crafting-a-harmonic-narrative-adding-youtube-music-to-vids-for-2024/"><u>[New] Crafting a Harmonic Narrative Adding YouTube Music to Vids for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-from-mere-color-to-spectacle-hdr-vs-sdr-in-editing/"><u>[New] From Mere Color to Spectacle HDR vs SDR in Editing</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-secrets-for-successful-live-streams-on-youtube-with-a-tiny-fanbase/"><u>[New] Secrets for Successful Live Streams on YouTube with a Tiny Fanbase</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-top-10-budget-friendly-cloud-service-providers/"><u>[New] Top 10 Budget-Friendly Cloud Service Providers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-unraveling-the-lifecycle-of-windows-movie-maker-releases/"><u>[Updated] Unraveling the Lifecycle of Windows Movie Maker Releases</u></a></li>
<li><a href="https://extra-hints.techidaily.com/cybernetic-cinema-the-future-screen/"><u>Cybernetic Cinema The Future Screen</u></a></li>
<li><a href="https://win11-tips.techidaily.com/detailed-walkthrough-changing-nat-type-in-win11-and-10/"><u>Detailed Walkthrough: Changing NAT Type in Win11 & 10</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-blue-screen-error-on-windows-1011/"><u>Fixing Blue Screen Error on Windows 10/11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-gmail-password-on-motorola-defy-2-devices-by-drfone-android/"><u>In 2024, How to Reset Gmail Password on Motorola Defy 2 Devices</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/instagram-edge-advanced-photo-editing-strategies-for-2024/"><u>Instagram Edge Advanced Photo Editing Strategies for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-double-click-opener-techniques-for-w11w10-folders/"><u>Mastering Double-Click Opener Techniques for W11/W10 Folders</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-menus-eliminate-show-more-from-win-11/"><u>Mastering Menus: Eliminate Show More From Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-wows-catastrophic-breakdown-132/"><u>Overcoming WoW's Catastrophic Breakdown #132</u></a></li>
<li><a href="https://win-bits.techidaily.com/quick-tips-on-shifting-unowned-tracks-from-previous-device-to-your-latest-ios-gadget/"><u>Quick Tips on Shifting Unowned Tracks From Previous Device to Your Latest iOS Gadget</u></a></li>
<li><a href="https://win11.techidaily.com/solving-device-not-reachable-error-in-windows-steps-and-tips/"><u>Solving Device Not Reachable Error in Windows: Steps & Tips</u></a></li>
<li><a href="https://win11.techidaily.com/stop-webp-savings-a-step-by-step-chrome-tutorial/"><u>Stop WebP Savings - A Step-by-Step Chrome Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-restoring-your-windows-11-system/"><u>The Ultimate Guide to Restoring Your Windows 11 System</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-strategies-for-resolving-windows-defenders-protection-failure/"><u>Top 5 Strategies for Resolving Windows Defender's Protection Failure</u></a></li>
<li><a href="https://win11.techidaily.com/win-xpvista-control-deletion-prompts-ease/"><u>Win XP/Vista: Control Deletion Prompts Ease</u></a></li>
</ul></div>

