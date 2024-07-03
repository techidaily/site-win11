---
title: "Prepare for Airplane Mode: Installation of Win11"
date: 2024-06-25T11:37:16.334Z
updated: 2024-06-26T11:37:16.334Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Prepare for Airplane Mode: Installation of Win11"
excerpt: "This Article Describes Prepare for Airplane Mode: Installation of Win11"
keywords: Win11 Setup Guide,Windows 11 Launch,Airplane Mode Tips,Pre-Install Win11,Win11 Initial Install,Laptop Readiness,Win11 Deployment Steps
thumbnail: https://thmb.techidaily.com/8b86753cae048297a750321083f2087f1622c0cfcb3cab69136de042dba1a8be.jpg
---

## Prepare for Airplane Mode: Installation of Win11

 Microsoft requires your system to have an active internet connection to complete the Windows 11 setup. It asks you to log into your Microsoft account to download critical updates and new features before you can start using your freshly installed Windows operating system.

 This becomes an issue if you want to use a local user account or don’t have an active internet connection during setup. Luckily, there are a few workarounds to skip the Windows 11 network setup. Here we show you how to bypass this restriction and complete the Windows 11 setup without an internet connection.

## Why Does Windows 11's Setup Require an Internet Connection?

![lets connect you to a network](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/lets-connect-you-to-a-network.png)

 According to Microsoft, you need an active internet connection to perform updates and download and use some features. In addition, Windows 11 Home edition requires a Microsoft Account to complete device setup on first use.

 However, this may not be feasible due to many reasons. First, you may want to use a local user account, but connecting to the Internet will force you to log in with a Microsoft account. The second potential issue is the [missing WiFi drivers to connect to the network](https://www.makeuseof.com/windows-11-missing-wi-fi-option/). Finally, the unavailability of a working Internet connection is another reason you may want to bypass this restriction.

 In Windows 10, bypassing this restriction was easy. You could click on the "I don't have internet" option and proceed to create a local user account and complete the setup.

 Windows 11, however, stops at the "Let’s connect you to a network" screen with the "Next" button grayed out. Windows 11 Pro, Enterprise and Education users can click on "I don’t have internet" and proceed to complete the setup with a local user account; however, Home edition users don't have this option.

 Here are a few workarounds to install Windows 11 Home without an active Internet connection.

## 1\. Bypass Out-of-the-Box-Experience (OOBE) Internet Requirement

 You can bypass the Let’s connect you to a network screen using the OOBE \\BYPASSNRO command in Command Prompt.

 When executed, it runs an existing CMD script, bypassnro.cmd, stored in the System32 folder to modify the Windows registry. This modification allows you to complete the Windows 11 setup without an Internet connection.

 To complete the Windows 11 setup without internet:

1. Make sure your computer is not connected to the Internet.
2. Next, boot your computer with the Windows installation media. Skip to **Step 9** below if you are already on the **Let's connect you to a network** screen.
3. When the **Windows Setup** dialog appears, select your preferred language, time, and keyboard input layout and click **Next**.  
![Windows-11-setup-screen-install-now](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-screen-install-now.jpg)
4. Click **Install Now.**  
![Windows 11 setup i dont have product key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-i-dont-have-product-key.jpg)
5. Enter your product key. If you don't have a product key, click the **I don't have a product key** link in the bottom right corner. If you are upgrading from Windows 10 and had Windows 11 previously installed, the operating system will automatically recognize and validate the Windows product key linked to your computer hardware.

1. Next, if prompted, select the edition of Windows 11 you want to install.
2. Check the box to accept terms and click **Next**.
3. Select **Custom: Install Windows Only (Advanced).**  
![Windows 11 setup select installation drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-select-installation-drive.jpg)
4. Select the installation drive and click **Next**. Wait for Windows to finish installation and restart your computer.
5. In the setup screen, select your region and keyboard layout.

1. Once in the **Let’s connect you to a network** screen, press **Shift + F10** to launch the **Command Prompt.**  
![oobe bypass nro command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/oobe-bypass-nro-command-prompt.jpg)
2. In the Command Prompt window, type the following command and press **Enter**:  
`OOBE\BYPASSNRO`
3. Upon successful execution, your system will restart and relaunch the OOBE dialog.  
![Windows-11-setup-select-installation-i-don't-have-internet-connection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-select-installation-i-don-t-have-internet-connection.jpg)
4. Follow the on-screen instructions to complete the setup. When you reach the **Let’s connect you to a network screen**, click on **I don’t have Internet** option.
5. Next, click on **Continue with limited setup.**  
![Windows 11 setup select installation continue with limited setup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-select-installation-continue-with-limited-setup.jpg)
6. Accept the **License Agreement** and proceed to create your local user account.

 Make sure to add security questions. This will help you recover your local user account in case you forget your password. Once done, follow the on-screen instructions to complete the setup.

## 2\. End Network Connection Flow Process Using Task Manager

 You can bypass the "let’s connect you to a network" screen by killing the **oobenetworkconnectionflow.exe** process using the Windows Task Manager.

 Since you already have Windows 11 installed at this stage, you can [launch the Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/) on top of your setup wizard using Command Prompt and kill the process.

 To skip the Windows 11 network setup using Task Manager:

1. Assuming you are in the **Let’s connect you to a network screen**, press **Shift + F10** to launch the Command Prompt.
2. In the Command Prompt window, type **taskmgr** and hit enter to launch **Task Manager.**  
![open task manager command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/open-task-manager-command-prompt.png)
3. Alternatively, use the **Ctrl + Shift + Esc** shortcut to launch Task Manager without Command Prompt.
4. Click **More Details** to open Task Manager in full view.
5. In the **Processes** tab, locate **Network Connection Flow.** Use the search bar in Task Manager to find the Network Connection Flow process.  
![Windows 11 setup select installation task manager kill network connection flow](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-select-installation-task-manager-kill-network-connection-flow.jpg)
6. Select the **Network Connection Flow** process and then click the **End task** button. Wait for the process to end and then close the Task Manager.
7. Type **exit** in the Command Prompt and hit enter.

 Now you will be back in the setup wizard. It will show some loading animation and then proceed to the next step. Here enter your name and password to [create a local user account in Windows 11](http://www.makeuseof.com/ways-to-create-local-user-account-windows/) and complete the setup.

## 3\. Directly Kill Network Connection Flow Using the Command Prompt

![end network connection flow command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/end-network-connection-flow-command-prompt.png)

 If you are unable to end the Network Connect Flow through Task Manager, you can directly kill it using the Command Prompt. Here’s how to do it.

1. At the Let’s connect you to a network screen, press **Shift + F10** to launch Command Prompt.
2. In the Command prompt window, type the following command and hit enter to execute:  
`taskkill /F /IM oobenetworkconnectionflow.exe`
3. Once executed, close the Command Prompt window to continue with the setup.

## 4\. Skip Let’s Connect You to a Network Page with Alt + F4

 This workaround is more of a hit-or-miss but seems to have helped a few users. When at the **Let's connect you to a network screen**, pressthe **Alt + F4** keyboard shortcut to close the mandatory Internet connection required window. Incidentally, you can use this shortcut to close active windows/programs when working on your desktop as well.

 For more such handy shortcuts, explore our [ultimate guide to Windows 11 keyboard shortcuts](https://www.makeuseof.com/windows-11-keyboard-shortcuts/).

 If successful, Windows 11 will skip the current screen and move to the next step. Once you're past this step, you can create a local user account and then complete the setup.

## Completing the Windows 11 Setup Without Internet Access

 You can follow one of the four methods listed above to skip the let’s connect you to a network window and complete the Windows 11 setup without the internet.

 That said, once you finish the setup and create a local user account, connect to the Internet to download critical security updates and features. You may also notice a few missing icons after the initial setup. Windows will download these icons when you connect to the Internet next time.

 This becomes an issue if you want to use a local user account or don’t have an active internet connection during setup. Luckily, there are a few workarounds to skip the Windows 11 network setup. Here we show you how to bypass this restriction and complete the Windows 11 setup without an internet connection.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/mastering-password-storage-windows-text-file-security-tips/"><u>Mastering Password Storage: Windows Text File Security Tips</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-lan-gaming-challenges-on-pc-winsminecraft/"><u>Overcoming LAN Gaming Challenges on PC, WinsMinecraft</u></a></li>
<li><a href="https://win11.techidaily.com/compre-written-for-pc-performance-metrics/"><u>Compre Written for PC Performance Metrics</u></a></li>
<li><a href="https://win11.techidaily.com/must-know-factors-a-consumers-checklist-for-buying-a-win-laptop/"><u>Must-Know Factors: A Consumer's Checklist for Buying a Win Laptop</u></a></li>
<li><a href="https://win11.techidaily.com/a-novices-guide-to-windows-11-sound-capture/"><u>A Novice's Guide to Windows 11 Sound Capture</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-and-personalizing-win11s-default-screen-saver/"><u>Configuring and Personalizing Win11's Default Screen Saver</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-tackle-windows-error-0xc0000001-efficiently/"><u>How To Tackle Windows Error 0xC0000001 Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/master-autominimize-windows-woes-no-more/"><u>Master AutoMinimize: Windows Woes No More</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-reset-account-lockout-counter-after-failed-logins-win-11-edition/"><u>Fine-Tuning Reset Account Lockout Counter After Failed Logins, Win 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/reducing-wasteful-usage-by-core-system-processes/"><u>Reducing Wasteful Usage by Core System Processes</u></a></li>
<li><a href="https://extra-information.techidaily.com/top-10-drones-your-ever-present-aviation-partner/"><u>Top 10 Drones  Your Ever-Present Aviation Partner</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-undoing-movement-how-to-reverse-video-on-snapchat/"><u>[New] 2024 Approved  Undoing Movement  How to Reverse Video on Snapchat</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-stages-of-change/"><u>2024 Approved  Stages of Change</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-a-comprehensible-approach-to-personal-branding-in-the-youtube-sphere-for-2024/"><u>[New] A Comprehensible Approach to Personal Branding in the YouTube Sphere for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-the-essential-guide-to-choosing-your-best-guitar-recording-application/"><u>Updated 2024 Approved The Essential Guide to Choosing Your Best Guitar Recording Application</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-realme-note-50-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Realme Note 50 in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-nokia-g310-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Nokia G310 Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-cutting-through-the-clutter-a-comprehensive-approach-to-sound-management-in-video-editing/"><u>Updated Cutting Through the Clutter A Comprehensive Approach to Sound Management in Video Editing</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-apple-iphone-13-pro-max-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Reset Apple iPhone 13 Pro Max? | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>