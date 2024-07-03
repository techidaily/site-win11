---
title: Enabling and Configuring Windows Sandbox in Win 11
date: 2024-06-25T11:38:19.001Z
updated: 2024-06-26T11:38:19.001Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling and Configuring Windows Sandbox in Win 11
excerpt: This Article Describes Enabling and Configuring Windows Sandbox in Win 11
keywords: Win 11 Sandbox Setup,Windows 11 Sandbox Guide,Enable Win 11 Sandbox,Configuring Win Sandbox,Win 11 Virtual Workspace,Creating Win 11 Sandbox,Setting Up Win 11 Sandbox
thumbnail: https://thmb.techidaily.com/6de10ca092ea22440e0ee57b0e4d9c17ed8937d0ae7586606e65eab4d9ad7104.jpg
---

## Enabling and Configuring Windows Sandbox in Win 11

 Microsoft Windows 11 features multiple virtualization solutions out of the box. While Hyper-V is an excellent tool, Windows Sandbox is an easy alternative to Windows virtual machines. It lets you run untrusted apps in an isolated environment without the hassle of setting up a complete virtualization tool.

 Unfortunately, Windows Sandbox is not available on the Home edition of the OS. If you are running the Pro, Enterprise, and Education edition, here is how to enable and set up Windows Sandbox in Windows 11.

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
5. Check the**Windows Sandbox** option and click**OK** .  
![enable Windows sandbox turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-Windows-sandbox-turn-windows-features-on-or-off.jpg)
6. Windows will search for the files and install the required dependencies to run Windows Sandbox scenarios. Once the changes are applied, close the Windows features dialog and restart your PC.
7. After the restart, press**Win + S** to open**Windows search.**
8. Type**sandbox** and click on**Windows Sandbox** from the search result to launch the virtualization tool.

## 3\. Install Windows Sandbox Using PowerShell

![enable windows sandbox powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-powershell.jpg)

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
<li><a href="https://win11.techidaily.com/maximize-your-touchscreen-experience-on-a-windows-11-machine/"><u>Maximize Your Touchscreen Experience on a Windows 11 Machine</u></a></li>
<li><a href="https://win11.techidaily.com/five-solutions-for-windows-defender-virus-shield-malfunction/"><u>Five Solutions for Windows Defender Virus Shield Malfunction</u></a></li>
<li><a href="https://win11.techidaily.com/direct-download-tactics-for-new-windows-users/"><u>Direct Download Tactics for New Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/locating-post-bsod-error-logs-in-windows-explorer/"><u>Locating Post-BSOD Error Logs in Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/make-the-best-out-of-what-you-have-even-without-11/"><u>Make the Best Out of What You Have, Even Without 11</u></a></li>
<li><a href="https://win11.techidaily.com/enhanced-energy-visibility-personalized-notifications-for-fully-charged-batteries-on-win11/"><u>Enhanced Energy Visibility: Personalized Notifications for Fully Charged Batteries on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/reverting-system-backups-to-standard-configurations/"><u>Reverting System Backups to Standard Configurations</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-recent-calls-back-from-oppo-k11-5g-by-fonelab-android-recover-call-logs/"><u>Simple ways to get recent calls back from Oppo K11 5G</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-mastering-siri-voice-commands-for-dynamic-and-efficient-tiktok-videos/"><u>[New] Mastering Siri Voice Commands for Dynamic and Efficient TikTok Videos</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-evaluating-fraps-as-a-screen-grab-pro/"><u>[New] 2024 Approved  Evaluating Fraps as a Screen Grab Pro</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-navigating-backward-image-hunt-on-the-worlds-largest-social-site/"><u>[New] Navigating Backward Image Hunt on the World's Largest Social Site</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-converting-your-clips-upload-to-youtube-via-premiere/"><u>[New] 2024 Approved  Converting Your Clips  Upload to YouTube Via Premiere</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-find-my-app-troubleshooting-no-location-found-vs-location-not-available-and-how-to-fix-them-on-apple-iphone-15-drfone-by-drfone-virtual-ios/"><u>In 2024, Find My App Troubleshooting No Location Found vs. Location Not Available & How to Fix Them On Apple iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-demystifying-instagrams-videography-cap-constraint/"><u>2024 Approved  Demystifying Instagram’s Videography Cap Constraint</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-ultimate-tutorial-for-posting-pics-on-ig/"><u>The Ultimate Tutorial for Posting Pics on IG</u></a></li>
</ul></div>
