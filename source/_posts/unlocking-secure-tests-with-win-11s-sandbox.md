---
title: Unlocking Secure Tests with Win 11'S Sandbox
date: 2024-09-05T08:45:06.039Z
updated: 2024-09-06T08:45:06.039Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking Secure Tests with Win 11'S Sandbox
excerpt: This Article Describes Unlocking Secure Tests with Win 11'S Sandbox
keywords: Secure Test Windows 11 Sandbox,Win 11 Security Mode,11Sandbox Safe Environment,Tests Unlock in Win 11,Windows 11 Security Features,Sandbox for Windows Testing,Enhanced Secure Testing Win 11
thumbnail: https://thmb.techidaily.com/b918b2416ccc3c3bc24e5dbb4922efd59cd6316c83a82113344d8ae306f1223c.jpg
---

## Unlocking Secure Tests with Win 11'S Sandbox

 Microsoft Windows 11 features multiple virtualization solutions out of the box. While Hyper-V is an excellent tool, Windows Sandbox is an easy alternative to Windows virtual machines. It lets you run untrusted apps in an isolated environment without the hassle of setting up a complete virtualization tool.

 Unfortunately, Windows Sandbox is not available on the Home edition of the OS. If you are running the Pro, Enterprise, and Education edition, here is how to enable and set up Windows Sandbox in Windows 11.

## How to Set Up Windows Sandbox in Windows 11

 Windows Sandbox is an optional feature, which means you'll have to install it from the Optional features section. You can[add and remove optional features from the Windows Features dialog](http://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) . Alternatively, you can use PowerShell or Command Prompt for a swift installation of Windows Sandbox.

 While the setup process is easier, your computer must meet some system requirements. Windows 11 Pro, Education, or Enterprise running computers with virtualization support are Windows Sandbox compatible. In most cases,[if your system can run Windows Hyper-V](https://www.makeuseof.com/windows-11-enable-hyper-v/) , it should also run Windows Sandbox.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135354/19272" target="_top" id="2135354">
  <img src="//a.impactradius-go.com/display-ad/19272-2135354" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135354/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Enable Windows Sandbox Using the Windows Features Dialog

 You can install Windows Sandbox using the Windows Features dialog. This dialog houses most of the optional Windows features that are ready to be installed on your PC.

 Follow these steps to install Windows Sandbox using the Windows Features dialog:

1. Press**Win + R** to open**Run** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**
3. In the left panel, click on**Turn Windows features on or off.**  
![control panel turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/control-panel-turn-windows-features-on-or-off.jpg)
4. In the**Turn Windows features on or off dialog** , scroll down and locate**Windows Sandbox.**
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137221/26400" target="_top" id="2137221">
  <img src="//a.impactradius-go.com/display-ad/26400-2137221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137221/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Check the**Windows Sandbox** option and click**OK** .  
![enable Windows sandbox turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-Windows-sandbox-turn-windows-features-on-or-off.jpg)
6. Windows will search for the files and install the required dependencies to run Windows Sandbox scenarios. Once the changes are applied, close the Windows features dialog and restart your PC.
7. After the restart, press**Win + S** to open**Windows search.**
8. Type**sandbox** and click on**Windows Sandbox** from the search result to launch the virtualization tool.

## 3\. Install Windows Sandbox Using PowerShell

![enable windows sandbox powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-powershell.jpg)

<!-- affiliate ads begin -->
<span id="1912746">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1912746.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20231-1912746">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1912746.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmindmanager.sjv.io%2Fc%2F5597632%2F1912746%2F20231'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1912746/20231" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120864/26400?prodsku=Mercury" target="_top" id="2120864">
  <img src="//a.impactradius-go.com/display-ad/26400-2120864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120864/26400?prodsku=Mercury" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Install Windows SandBox Using Command Prompt

![enable windows sandbox command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098705/14409" target="_top" id="2098705">
  <img src="//a.impactradius-go.com/display-ad/14409-2098705" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098705/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Deployment Image Servicing and Management (DISM) is a command-line utility that facilitates the installation of optional features using the Command Prompt. To install Windows Sandbox, you will need to use the Enable-Feature command in Command Prompt. Here's how to do it.

1. Press**Win + R** to open**Run** .
2. Type**cmd** in the**Run** dialog. Press and hold**Ctrl + Shift** and click**OK** to open Command Prompt as administrator.
3. In the Command Prompt, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName: "Containers-DisposableClientVM" -All`
4. Wait for the process to complete. Once done, press**Y** and**Enter** to restart your PC.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115909/19272" target="_top" id="2115909">
  <img src="//a.impactradius-go.com/display-ad/19272-2115909" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115909/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-web.techidaily.com/024-approved-top-6-ios-apps-turn-youtube-videos-into-mp3-files/"><u>[New] 2024 Approved  Top 6 iOS Apps  Turn YouTube Videos Into MP3 Files</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-xiaomi-mix-fold-3-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Xiaomi Mix Fold 3 to Roku | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/a-comprehensive-review-of-gaomon-pd1560-digital-sketching-device-is-it-a-top-tier-art-pad/"><u>A Comprehensive Review of Gaomon PD1560 Digital Sketching Device: Is It a Top-Tier Art Pad?</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-phantom-hardware-listings-on-windows-system/"><u>Correcting Phantom Hardware Listings on Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/dial-down-windows-intense-contrast-level/"><u>Dial Down Windows' Intense Contrast Level</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-taskbar-functionality-on-windows-11/"><u>Elevate Taskbar Functionality on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-code-management-on-windows-11-with-github-desktop/"><u>Elevate Your Code Management on Windows 11 with Github Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-already-used-errors-in-windows-1011-152-chars/"><u>Eliminate 'Already Used' Errors in Windows 10/11 (152 Chars)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/essentials-of-using-igtv-effectively-and-efficiently/"><u>Essentials of Using IGTV Effectively and Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-touchpad-settings-on-windows-11/"><u>Fine-Tuning Touchpad Settings on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-11s-discord-javascript-crisis-a-step-by-step-approach/"><u>Fixing Windows 11'S Discord JavaScript Crisis: A Step-by-Step Approach</u></a></li>
<li><a href="https://win11.techidaily.com/how-and-when-to-use-file-locksmith-in-powertoys/"><u>How and When to Use File Locksmith in PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-break-down-and-fix-frozen-windows-updates/"><u>How to Break Down and Fix Frozen Windows Updates</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fix-my-poco-m6-5g-location-is-wrong-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix My Poco M6 5G Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-the-artisans-guide-to-flawless-free-and-paid-software-video-downloads/"><u>In 2024, The Artisan's Guide to Flawless Free and Paid Software Video Downloads</u></a></li>
<li><a href="https://win11.techidaily.com/innovate-taskbar-functionality-with-additional-folders-in-11/"><u>Innovate Taskbar Functionality with Additional Folders in 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-change-of-guard-swapping-your-windows-11-logon-method/"><u>Navigating the Change of Guard: Swapping Your Windows 11 Logon Method</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-terrain-of-excessive-disk-space-in-windows/"><u>Navigating the Terrain of Excessive Disk Space in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-limitations-maximizing-ram-in-windows/"><u>Overcoming Limitations: Maximizing RAM In Windows</u></a></li>
<li><a href="https://fox-direct.techidaily.com/prime-7-video-software-for-mac/"><u>Prime 7 Video Software for Mac</u></a></li>
<li><a href="https://win11.techidaily.com/quick-and-easy-fixes-to-reinstall-overlooked-windows-apps/"><u>Quick and Easy Fixes to Reinstall Overlooked Windows Apps</u></a></li>
<li><a href="https://extra-resources.techidaily.com/seamless-guide-integrating-instagram-with-tiktok/"><u>Seamless Guide  Integrating Instagram with TikTok</u></a></li>
<li><a href="https://win11.techidaily.com/simplified-techniques-to-purge-image-borders/"><u>Simplified Techniques to Purge Image Borders</u></a></li>
<li><a href="https://win11.techidaily.com/starting-storytelling-voice-commands-in-windows-11/"><u>Starting Storytelling: Voice Commands in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-mitigating-the-failed-lunar-client-launch-errors/"><u>Strategies for Mitigating the Failed Lunar Client Launch Errors</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-fix-disk-read-error-in-windows/"><u>Strategies to Fix Disk Read Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solutions-for-xps-xffffffff-printer-failure/"><u>Swift Solutions for XP's XFFFFFFFF Printer Failure</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-complications-from-new-windows-installations/"><u>Tackling Complications From New Windows Installations</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-enlargement-win11-taskbar-icons-reimagined/"><u>The Art of Enlargement: Win11 Taskbar Icons Reimagined</u></a></li>
<li><a href="https://win11.techidaily.com/the-mystery-of-ftdibussys-and-windows-memory-standards/"><u>The Mystery of ftdibus.sys & Windows Memory Standards</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-12-prominent-xiaomi-redmi-a2-fingerprint-not-working-solutions-by-drfone-android/"><u>Top 12 Prominent Xiaomi Redmi A2 Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://techtrends.techidaily.com/unveiling-the-ultimate-6-savings-portals-slash-costs-effortlessly/"><u>Unveiling the Ultimate 6 Savings Portals: Slash Costs Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/win-1111-guide-solving-audacity-sound-error/"><u>Win 11/11 Guide: Solving Audacity Sound Error</u></a></li>
</ul></div>
