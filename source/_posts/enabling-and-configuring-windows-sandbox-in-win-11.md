---
title: Enabling and Configuring Windows Sandbox in Win 11
date: 2024-06-25T10:32:13.035Z
updated: 2024-06-26T10:32:13.035Z
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
<li><a href="https://win11.techidaily.com/solving-win-error-no-access-to-network-paths/"><u>Solving WIN Error: No Access to Network Paths</u></a></li>
<li><a href="https://win11.techidaily.com/revive-muted-slack-on-windows-easy-steps-to-resuscitate-alerts/"><u>Revive Muted Slack on Windows: Easy Steps to Resuscitate Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disconnected-from-vpn-client-errors/"><u>Addressing Disconnected From VPN Client Errors</u></a></li>
<li><a href="https://win11.techidaily.com/visual-virtuoso-top-tips-to-overcome-blurry-windows-11-displays/"><u>Visual Virtuoso: Top Tips to Overcome Blurry Windows 11 Displays</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-and-personalize-windows-11-files-via-added-movecopy/"><u>Streamline and Personalize Windows 11 Files via Added 'Move'/'Copy'</u></a></li>
<li><a href="https://win11.techidaily.com/tailor-windows-11-notification-settings/"><u>Tailor Windows 11 Notification Settings</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-reactivating-razer-device-detection-by-synapse-software/"><u>Solutions for Reactivating Razer Device Detection by Synapse Software</u></a></li>
<li><a href="https://win11.techidaily.com/removing-updater-code-0x8019-issue-on-xp/"><u>Removing Updater Code 0X8019 Issue on XP</u></a></li>
<li><a href="https://win11.techidaily.com/curing-frozen-windows-desktop-context-options/"><u>Curing Frozen Windows Desktop Context Options</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-the-best-7-tiktok-gadgets-to-skyrocket-your-popularity/"><u>[New] The Best 7 TikTok Gadgets to Skyrocket Your Popularity</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-best-10-mock-location-apps-worth-trying-on-samsung-galaxy-m14-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Best 10 Mock Location Apps Worth Trying On Samsung Galaxy M14 5G | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-from-xiaomi-redmi-12-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from Xiaomi Redmi 12 Devices</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-archive-powerpoint-into-video-repository/"><u>[Updated] 2024 Approved  Archive PowerPoint Into Video Repository</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-sideways-scene-understanding-igs-upside-down-issue/"><u>[Updated] Sideways Scene  Understanding IG's Upside-Down Issue</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-real-time-recording-rivalry-obs-versus-shadowreplay-for-2024/"><u>[New] Real-Time Recording Rivalry  OBS Versus ShadowReplay for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-rise-of-the-gaming-titans-top-10-on-tiktok-for-2024/"><u>[New] Rise of the Gaming Titans  Top 10 on TikTok for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-car-locator-apps-for-realme-gt-5-pro-drfone-by-drfone-virtual-android/"><u>Top 5 Car Locator Apps for Realme GT 5 Pro | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-detailed-look-into-youtubes-featured-community-dialogue/"><u>[Updated] In 2024, Detailed Look Into YouTube's Featured Community Dialogue</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-10-fingerprint-lock-apps-to-lock-your-xiaomi-redmi-note-12-4g-phone-by-drfone-android/"><u>Top 10 Fingerprint Lock Apps to Lock Your Xiaomi Redmi Note 12 4G Phone</u></a></li>
</ul></div>
