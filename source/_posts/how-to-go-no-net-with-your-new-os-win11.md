---
title: How to Go No Net With Your New OS, Win11
date: 2024-08-16T00:05:48.969Z
updated: 2024-08-17T00:05:48.969Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Go No Net With Your New OS, Win11
excerpt: This Article Describes How to Go No Net With Your New OS, Win11
keywords: Win11 NO NETWORK SETUP,Win11 Zero Internet,Win11 Offline OS,Win11 No Network Use,Go Net-Free Win11,Win11 Without Internet,Setting Up Win11 Offline
thumbnail: https://thmb.techidaily.com/0f034b01e896bfeb1b76fcb002ff3f08bf8065e806075d9660abdc53bcbc29eb.jpg
---

## How to Go No Net With Your New OS, Win11

 Microsoft requires your system to have an active internet connection to complete the Windows 11 setup. It asks you to log into your Microsoft account to download critical updates and new features before you can start using your freshly installed Windows operating system.

 This becomes an issue if you want to use a local user account or don’t have an active internet connection during setup. Luckily, there are a few workarounds to skip the Windows 11 network setup. Here we show you how to bypass this restriction and complete the Windows 11 setup without an internet connection.

## Why Does Windows 11's Setup Require an Internet Connection?

![lets connect you to a network](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/lets-connect-you-to-a-network.png)

 According to Microsoft, you need an active internet connection to perform updates and download and use some features. In addition, Windows 11 Home edition requires a Microsoft Account to complete device setup on first use.

 However, this may not be feasible due to many reasons. First, you may want to use a local user account, but connecting to the Internet will force you to log in with a Microsoft account. The second potential issue is the [missing WiFi drivers to connect to the network](https://www.makeuseof.com/windows-11-missing-wi-fi-option/). Finally, the unavailability of a working Internet connection is another reason you may want to bypass this restriction.

 In Windows 10, bypassing this restriction was easy. You could click on the "I don't have internet" option and proceed to create a local user account and complete the setup.

 Windows 11, however, stops at the "Let’s connect you to a network" screen with the "Next" button grayed out. Windows 11 Pro, Enterprise and Education users can click on "I don’t have internet" and proceed to complete the setup with a local user account; however, Home edition users don't have this option.

 Here are a few workarounds to install Windows 11 Home without an active Internet connection.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 1\. Bypass Out-of-the-Box-Experience (OOBE) Internet Requirement

 You can bypass the Let’s connect you to a network screen using the OOBE \\BYPASSNRO command in Command Prompt.

 When executed, it runs an existing CMD script, bypassnro.cmd, stored in the System32 folder to modify the Windows registry. This modification allows you to complete the Windows 11 setup without an Internet connection.

 To complete the Windows 11 setup without internet:

1. Make sure your computer is not connected to the Internet.
2. Next, boot your computer with the Windows installation media. Skip to **Step 9** below if you are already on the **Let's connect you to a network** screen.
3. When the **Windows Setup** dialog appears, select your preferred language, time, and keyboard input layout and click **Next**.  
![Windows-11-setup-screen-install-now](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-screen-install-now.jpg)
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
2. In the Command Prompt window, type the following command and press **Enter**:  
`OOBE\BYPASSNRO`
3. Upon successful execution, your system will restart and relaunch the OOBE dialog.  
![Windows-11-setup-select-installation-i-don't-have-internet-connection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-select-installation-i-don-t-have-internet-connection.jpg)
4. Follow the on-screen instructions to complete the setup. When you reach the **Let’s connect you to a network screen**, click on **I don’t have Internet** option.
5. Next, click on **Continue with limited setup.**  
![Windows 11 setup select installation continue with limited setup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-select-installation-continue-with-limited-setup.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
6. Accept the **License Agreement** and proceed to create your local user account.

 Make sure to add security questions. This will help you recover your local user account in case you forget your password. Once done, follow the on-screen instructions to complete the setup.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. End Network Connection Flow Process Using Task Manager

 You can bypass the "let’s connect you to a network" screen by killing the **oobenetworkconnectionflow.exe** process using the Windows Task Manager.

 Since you already have Windows 11 installed at this stage, you can [launch the Task Manager](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/) on top of your setup wizard using Command Prompt and kill the process.

 To skip the Windows 11 network setup using Task Manager:

1. Assuming you are in the **Let’s connect you to a network screen**, press **Shift + F10** to launch the Command Prompt.
2. In the Command Prompt window, type **taskmgr** and hit enter to launch **Task Manager.**  
![open task manager command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/open-task-manager-command-prompt.png)
<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
3. Alternatively, use the **Ctrl + Shift + Esc** shortcut to launch Task Manager without Command Prompt.
4. Click **More Details** to open Task Manager in full view.
5. In the **Processes** tab, locate **Network Connection Flow.** Use the search bar in Task Manager to find the Network Connection Flow process.  
![Windows 11 setup select installation task manager kill network connection flow](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-11-setup-select-installation-task-manager-kill-network-connection-flow.jpg)
6. Select the **Network Connection Flow** process and then click the **End task** button. Wait for the process to end and then close the Task Manager.
7. Type **exit** in the Command Prompt and hit enter.

 Now you will be back in the setup wizard. It will show some loading animation and then proceed to the next step. Here enter your name and password to [create a local user account in Windows 11](http://www.makeuseof.com/ways-to-create-local-user-account-windows/) and complete the setup.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-insta-velocity-strategic-use-of-likes-and-videos-for-growth/"><u>[New] In 2024, Insta Velocity  Strategic Use of Likes & Videos for Growth</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-leveraging-hashtags-for-a-huge-impact-on-your-youtube-views/"><u>[New] Leveraging #Hashtags for a Huge Impact on Your YouTube Views</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-rhythm-wizards-choice-online-tempo-tester-apps/"><u>[New] Rhythm Wizards' Choice  Online Tempo Tester Apps</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-the-ultimate-guide-to-forming-your-instagram-company-identity/"><u>[New] The Ultimate Guide to Forming Your Instagram Company Identity</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-decrypting-the-mystery-understanding-unlisted-content-on-youtube/"><u>[Updated] In 2024, Decrypting the Mystery  Understanding 'Unlisted' Content on YouTube</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-minimum-view-count-for-youtube-success-stories/"><u>[Updated] The Minimum View Count for YouTube Success Stories</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-capture-the-past-with-your-camera-roll-snapchat-edition/"><u>2024 Approved  Capture the Past with Your Camera Roll - Snapchat Edition</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-original-tape-review-study-guide/"><u>2024 Approved  Original Tape Review Study Guide</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-networking-with-python-servers-on-windows-os/"><u>Advanced Networking with Python Servers on Windows OS</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/artedit-master/"><u>ArtEdit Master</u></a></li>
<li><a href="https://tech-haven.techidaily.com/beyond-chatgpt-discover-10-superior-custom-gpt-innovations/"><u>Beyond ChatGPT: Discover 10 Superior Custom GPT Innovations</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-the-gif-size-barrier-on-discord-for-win11-users/"><u>Breaking Down the GIF Size Barrier on Discord for Win11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/burying-your-data-secretive-drive-practices/"><u>Burying Your Data: Secretive Drive Practices</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-play-mkv-movies-on-civi-3-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Can I play MKV movies on Civi 3?</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-overcoming-file-access-barriers-using-powershell/"><u>Efficiently Overcoming File Access Barriers Using PowerShell</u></a></li>
<li><a href="https://win11.techidaily.com/essential-note-taking-software-the-winning-seven/"><u>Essential Note-Taking Software: The Winning Seven</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/exploring-the-full-potential-of-obs-screen-capture/"><u>Exploring the Full Potential of OBS Screen Capture</u></a></li>
<li><a href="https://win11.techidaily.com/fix-for-invisible-second-screen-on-windows-11/"><u>Fix for Invisible Second Screen on Windows 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/guide-on-how-to-remove-apple-id-from-iphone-15-by-drfone-ios/"><u>Guide on How To Remove Apple ID From iPhone 15</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-personalize-wins-standard-cli-application/"><u>How To Personalize Win’s Standard CLI Application</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-straighten-out-window-corners/"><u>How to Straighten Out Window Corners</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-oneplus-nord-ce-3-lite-5gmirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can OnePlus Nord CE 3 Lite 5GMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-screen-time-saviors-expert-evaluations-of-video-tech/"><u>In 2024, Screen Time Saviors  Expert Evaluations of Video Tech</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-unlocking-your-cameras-screen-recording-features/"><u>In 2024, Unlocking Your Camera's Screen Recording Features</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/iron-out-glitches-restore-missing-facebook-watch-icons-for-2024/"><u>Iron Out Glitches - Restore Missing Facebook Watch Icons for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/is-obs-studio-unable-to-record-audio-on-windows-11-try-these-fixes/"><u>Is OBS Studio Unable to Record Audio on Windows 11? Try These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-calendar-a-step-by-step-guide/"><u>Mastering Windows 11 Calendar: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-the-nuances-of-winstall-for-grouped-windows-11-installs/"><u>Navigate the Nuances of Winstall for Grouped Windows 11 Installs</u></a></li>
<li><a href="https://win11.techidaily.com/pivot-to-new-life-for-your-outdated-tech-without-windows/"><u>Pivot to New Life for Your Outdated Tech Without Windows</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-not-an-empty-directory-error-code-0x80070091-in-win11-and-11/"><u>Rectifying Not an Empty Directory Error Code 0X80070091 in Win11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-audio-output-on-microsofts-read-aloud-functionality/"><u>Resetting Audio Output on Microsoft's Read Aloud Functionality</u></a></li>
<li><a href="https://extra-skills.techidaily.com/reviewers-guide-to-yuneec-typhoon-h-performance-for-2024/"><u>Reviewer’s Guide to Yuneec Typhoon H Performance for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-notes-with-obsidians-visual-approach/"><u>Streamlining Notes with Obsidian's Visual Approach</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-system-checks-a-guide-for-updating-context-menus/"><u>Streamlining System Checks: A Guide for Updating Context Menus</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-address-code-3-error-in-nvidia-opengl-win1011/"><u>Techniques to Address Code 3 Error in Nvidia OpenGL (Win10/11)</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-guide-to-file-sync-in-multiple-windows-systems-using-aoemi/"><u>The Essential Guide to File Sync in Multiple Windows Systems Using AOEMi</u></a></li>
<li><a href="https://win11.techidaily.com/the-essentials-of-windows-cab-files-purpose-and-installation-tactics/"><u>The Essentials of Windows CAB Files: Purpose & Installation Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-rdp-access-quickly-in-the-latest-windows/"><u>Unlock RDP Access Quickly in the Latest Windows</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-2024-approved-best-photo-slideshow-maker-how-to-make-a-photo-slideshow/"><u>Updated 2024 Approved Best Photo Slideshow Maker How to Make a Photo Slideshow</u></a></li>
<li><a href="https://win11.techidaily.com/windows-a-deep-dive-into-data-consumption-patterns/"><u>Windows: A Deep Dive Into Data Consumption Patterns</u></a></li>
</ul></div>
