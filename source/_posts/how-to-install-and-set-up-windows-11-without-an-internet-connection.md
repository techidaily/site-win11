---
title: How to Install and Set Up Windows 11 Without an Internet Connection
date: 2025-02-02T22:48:09.984Z
updated: 2025-02-03T22:56:18.143Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Install and Set Up Windows 11 Without an Internet Connection
excerpt: This Article Describes How to Install and Set Up Windows 11 Without an Internet Connection
keywords: No-Net Win11 Setup,Offline Win11 Install,Windows 11 Instalation,Win11 Without Net,Local Win11 Deploy,Offline PC Upgrade Win,Direct Win11 Setup
thumbnail: https://thmb.techidaily.com/83e25eed69df3aa92880d650ba4560e8ba50f00f0835c8a9e56b3818bf712cbe.jpg
---

## How to Install and Set Up Windows 11 Without an Internet Connection

 Microsoft requires your system to have an active internet connection to complete the Windows 11 setup. It asks you to log into your Microsoft account to download critical updates and new features before you can start using your freshly installed Windows operating system.

 This becomes an issue if you want to use a local user account or don’t have an active internet connection during setup. Luckily, there are a few workarounds to skip the Windows 11 network setup. Here we show you how to bypass this restriction and complete the Windows 11 setup without an internet connection.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fo4lNZ84x9Q?si=WdcYPZp-9VJnZEnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Type **exit** in the Command Prompt and hit enter.

 Now you will be back in the setup wizard. It will show some loading animation and then proceed to the next step. Here enter your name and password to [create a local user account in Windows 11](http://www.makeuseof.com/ways-to-create-local-user-account-windows/) and complete the setup.

## 3\. Directly Kill Network Connection Flow Using the Command Prompt

![end network connection flow command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/end-network-connection-flow-command-prompt.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you are unable to end the Network Connect Flow through Task Manager, you can directly kill it using the Command Prompt. Here’s how to do it.

1. At the Let’s connect you to a network screen, press **Shift + F10** to launch Command Prompt.
2. In the Command prompt window, type the following command and hit enter to execute:  
`taskkill /F /IM oobenetworkconnectionflow.exe`
3. Once executed, close the Command Prompt window to continue with the setup.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Skip Let’s Connect You to a Network Page with Alt + F4

 This workaround is more of a hit-or-miss but seems to have helped a few users. When at the **Let's connect you to a network screen**, pressthe **Alt + F4** keyboard shortcut to close the mandatory Internet connection required window. Incidentally, you can use this shortcut to close active windows/programs when working on your desktop as well.

 For more such handy shortcuts, explore our [ultimate guide to Windows 11 keyboard shortcuts](https://www.makeuseof.com/windows-11-keyboard-shortcuts/).

 If successful, Windows 11 will skip the current screen and move to the next step. Once you're past this step, you can create a local user account and then complete the setup.

## Completing the Windows 11 Setup Without Internet Access

 You can follow one of the four methods listed above to skip the let’s connect you to a network window and complete the Windows 11 setup without the internet.

 That said, once you finish the setup and create a local user account, connect to the Internet to download critical security updates and features. You may also notice a few missing icons after the initial setup. Windows will download these icons when you connect to the Internet next time.

 This becomes an issue if you want to use a local user account or don’t have an active internet connection during setup. Luckily, there are a few workarounds to skip the Windows 11 network setup. Here we show you how to bypass this restriction and complete the Windows 11 setup without an internet connection.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-fostering-resilience-in-the-face-of-cyber-haters-for-2024/"><u>[New] Fostering Resilience in the Face of Cyber Haters for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-unveiling-luxury-transforming-standard-shipments-into-memories/"><u>[New] In 2024, Unveiling Luxury Transforming Standard Shipments Into Memories</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-engaging-verbal-communicator-study-part-8/"><u>[Updated] Engaging Verbal Communicator Study, Part 8</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-ignite-a-sizzling-online-presence-with-these-instagram-9-strategies/"><u>[Updated] Ignite a Sizzling Online Presence with These Instagram #9 Strategies</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-overcome-video-file-cant-be-played-problem-with-error-22403/"><u>How to Overcome 'Video File Can't Be Played' Problem with Error 22403</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-cutting-edge-video-editing-strategies-for-impactful-obs-content/"><u>In 2024, Cutting-Edge Video Editing Strategies for Impactful OBS Content</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-an-airtag-from-your-apple-id-account-on-iphone-12-mini-by-drfone-ios/"><u>In 2024, How to Remove an AirTag from Your Apple ID Account On iPhone 12 mini?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-a-network-locked-xiaomi-redmi-k70e-phone-by-drfone-android/"><u>In 2024, How to Unlock a Network Locked Xiaomi Redmi K70E Phone?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-three-ways-to-sim-unlock-motorola-g24-power-by-drfone-android/"><u>In 2024, Three Ways to Sim Unlock Motorola G24 Power</u></a></li>
<li><a href="https://win11.techidaily.com/iphonespecific-quicktime/"><u>IPhonespecific QuickTimeムービー視聴・再生に支障があります - 解消策</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-youtube-to-mp3-conversion-using-vidtomp3-solving-common-issues-and-fixes/"><u>Mastering YouTube-to-MP3 Conversion Using VidToMp3 – Solving Common Issues & Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/mp4-to-mp3-in-a-flash-master-the-art-of-quick-video-to-audio-file-conversions/"><u>MP4 to MP3 in a Flash! Master the Art of Quick Video-to-Audio File Conversions</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-your-website-with-quick-and-effective-video-downsizing-methods/"><u>Optimizing Your Website with Quick and Effective Video Downsizing Methods</u></a></li>
<li><a href="https://win11.techidaily.com/ps4-pro-dvd-plays-flawlessly-ultimate-troubleshooting-guide/"><u>PS4 Pro DVD Plays Flawlessly: Ultimate Troubleshooting Guide</u></a></li>
<li><a href="https://win11.techidaily.com/recent-update-reveals-true-identity-of-9-anime-series/"><u>Recent Update Reveals True Identity of 9 Anime Series</u></a></li>
<li><a href="https://win11.techidaily.com/risk-free-deal-on-factorypro-for-ipads-professional-video-conversion-software-now-available-online/"><u>Risk-Free Deal on FactoryPro for iPads – Professional Video Conversion Software Now Available Online!</u></a></li>
<li><a href="https://win11.techidaily.com/iuocpoodoeodvoocuoobiplusociewniplusocgeocipluswlleeuupluswitus9ndrjgrnjg4bjg4pjg5fjg5djgqtjgrnjg4bjg4pjg5fjgqzjgqtjg4ki/"><u>イメージから始める動画制作:ステップバイステップガイド</u></a></li>
</ul></div>

