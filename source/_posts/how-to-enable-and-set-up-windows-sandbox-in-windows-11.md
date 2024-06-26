---
title: How to Enable and Set Up Windows Sandbox in Windows 11
date: 2024-06-25T10:24:43.501Z
updated: 2024-06-26T10:24:43.501Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Enable and Set Up Windows Sandbox in Windows 11
excerpt: This Article Describes How to Enable and Set Up Windows Sandbox in Windows 11
keywords: WinSandbox Setup Guide,Windows Sandbox Start,Windows 11 Sandbox,Enable Sandbox Feature,Windows 11 Sandbox Config,Activate Windows Sandbox,Sandbox in Win11
thumbnail: https://thmb.techidaily.com/fddafecbf8d052882c8613835d6b91422875b8a8af17428f6e6ddf368419a301.jpg
---

## How to Enable and Set Up Windows Sandbox in Windows 11

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
<li><a href="https://win11.techidaily.com/overcoming-the-unresponsive-keyboard-issue-x80049dd3-in-windows-11/"><u>Overcoming the Unresponsive Keyboard Issue - X80049DD3 in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-file-fixation-powerpoint-saves-crisis-solutions-win11/"><u>Immediate File Fixation: PowerPoint Saves Crisis, Solutions WIN11</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-cpu-woes-strategies-from-windows-rm-window/"><u>Unraveling CPU Woes: Strategies From Windows' RM Window</u></a></li>
<li><a href="https://win11.techidaily.com/protocols-to-enter-windows-administrative-hub/"><u>Protocols to Enter Windows' Administrative Hub</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-gaming-glitches-keeping-df-playtime-uninterrupted/"><u>Navigating Gaming Glitches: Keeping DF Playtime Uninterrupted</u></a></li>
<li><a href="https://win11.techidaily.com/handling-the-mysterious-windows-subsystem-for-linux-error-4294967295/"><u>Handling the Mysterious Windows Subsystem for Linux Error 4294967295</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-your-desktops-aesthetic-essential-theme-tips-for-win11/"><u>Transforming Your Desktop's Aesthetic: Essential Theme Tips for Win11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-zoom-mastery-for-podcasters-a-complete-guide-to-exceptional-audio-capture/"><u>[Updated] Zoom Mastery for Podcasters  A Complete Guide to Exceptional Audio Capture</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/complete-fixes-to-solve-iphone-15-pro-randomly-asking-for-apple-id-password-drfone-by-drfone-ios/"><u>Complete Fixes To Solve iPhone 15 Pro Randomly Asking for Apple ID Password | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-best-route-generator-apps-you-should-try-on-honor-x8b-drfone-by-drfone-virtual-android/"><u>5 Best Route Generator Apps You Should Try On Honor X8b | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/strategies-for-maximizing-your-video-footprint-in-instagram-for-2024/"><u>Strategies for Maximizing Your Video Footprint in Instagram for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/crafting-visual-stories-select-the-best-ig-video-editors/"><u>Crafting Visual Stories  Select the Best IG Video Editors</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-realme-note-50-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-turn-your-videos-into-treasures-the-best-dvd-creation-software-for-preserving-memories-for-2024/"><u>New Turn Your Videos Into Treasures The Best DVD Creation Software for Preserving Memories for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-silence-by-design-techniques-for-gradually-dimming-soundtracks-in-premiere-pro/"><u>In 2024, Silence by Design  Techniques for Gradually Dimming Soundtracks in Premiere Pro</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/windows-users-top-choices-for-screenshot-and-capture-for-2024/"><u>Windows User's Top Choices for Screenshot and Capture for 2024</u></a></li>
</ul></div>
