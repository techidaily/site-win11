---
title: Disabling SSI Compliance in Windows for Driver Installation
date: 2024-09-15T07:33:00.281Z
updated: 2024-09-16T20:32:48.135Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling SSI Compliance in Windows for Driver Installation
excerpt: This Article Describes Disabling SSI Compliance in Windows for Driver Installation
keywords: Disable SSIs,Windows SSI Disable,SSI Off Windows,No SSIs Enabled,Remove Windows SSI,SSIs OFF Driver Install,Compliance SSI Deactivate
thumbnail: https://thmb.techidaily.com/b419546ab6fdd218d829eb22a844376fcf0d2afcf21c79595fda949de5f6b103.jpg
---

## Disabling SSI Compliance in Windows for Driver Installation

 Sometimes, Windows will block you from installing an unsigned driver, which is a driver you've downloaded elsewhere other than through a Windows Update or the device manufacturer's website. But if you need the driver, and you know it is perfectly safe, you can turn off driver signature enforcement and let it through.

 In this guide, we're going to show you several ways to do it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Disable Driver Signature Enforcement in the Startup Settings

 A temporary way to disable driver signature enforcement is through Startup Settings, allowing you to install the unsigned drivers. However, the moment you restart your PC, Windows will re-enable driver signature enforcement. The unsigned drivers you've installed will still work, but you may not be able to install new ones.

 To disable driver signature enforcement this way, you'll have to [access the Startup Settings screen](https://www.makeuseof.com/windows-startup-settings/). The **Disable driver signature enforcement** option will be the seventh one, so press **F7** or **7** on your keyboard to select it.

![windows 11 startup settings safe mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-startup-settings-safe-mode.jpg)

 Your computer will then restart, and when it reboots, you'll be able to install those unsigned drivers.

## How to Disable Driver Signature Enforcement in the Local Group Policy Editor

 You can also disable driver signature enforcement by tweaking the **Code signing for driver packages** policy in the Local Group Policy Editor (LGPE). Doing this will allow you to install unsigned drivers even if you restart your computer.

 Unfortunately, you can only natively access the LGPE if you're on Windows Pro or Enterprise Edition. However, there is a way to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

1. Press **Win + S** to bring up Windows Search, enter **group policy** in the Search box, and select **Edit group policy** in the Search results.  
![Open Group Policy Editor Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-group-policy-editor-using-windows-search.jpg)
2. Once the LGPE opens up, head to **User Configuration > Administrative Templates > System > Driver Installation**.
3. Right-click **Code signing for driver packages** and select **Edit**.  
![editing the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-the-code-signing-for-driver-packages-policy.jpg)
4. Click the **Enabled** radio button, and then, in the **Options** section, click on the dropdown and select **Ignore**.  
![enabling the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/enabling-the-code-signing-for-driver-packages-policy.jpg)
5. Click on **OK**.

 If you want to enable driver signature enforcement again, go back to step #4 and set the radio button to **Not configured**.

## How to Disable Driver Signature Enforcement in PowerShell

 Another way to disable driver signature enforcement is by running the command to turn off integrity checks in PowerShell (you'll have to run it as an administrator). And just like with the Local Group Policy Editor, it will remain disabled until you enable it again.

 Follow the steps below to turn off driver signature enforcement in PowerShell:

 You can disable driver signature enforcement by [opening Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) if you prefer it over PowerShell.

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set nointegritychecks on** and paste it into PowerShell.  
![turning off driver signature enforcement in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-off-driver-signature-enforcement-in-terminal.jpg)
4. Hit **Enter** to run the command.

 To turn on driver signature enforcement again, replace the command in step #3 with **bcdedit /set nointegritychecks off**.

 One potential problem you can run into when trying to turn off driver signature enforcement this way is an error stating **The value is protected by Secure Boot policy and cannot be modified or deleted**.

![Secure Boot error in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/secure-boot-error-powershell.jpg)

 If that is the case, you can try [turning off Secure Boot](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) and trying again. But if you don't want to do this, using Startup Settings and the Local Group Policy Editor is perfectly okay.

 You can also put Windows in test mode, which disables driver signature enforcement, allowing you to install those unsigned drivers. To enter test mode, follow the steps below (keep in mind that you may run into the Secure Boot error):

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set testsigning on** and paste it into PowerShell.  
![turning on Test Mode in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-on-test-mode-in-terminal.jpg)
4. Hit **Enter** to run the command.

 Now restart your computer, and when it boots back up, it will be in test mode. After you're done installing those drivers, don't forget to disable test mode. The command to do that is **bcdedit /set testsigning off**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115915/19272" target="_top" id="2115915">
  <img src="//a.impactradius-go.com/display-ad/19272-2115915" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115915/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Now You Can Install Unsigned Drivers on Windows

 Installing unsigned drivers on Windows is not recommended, since they can lead to unexpected behavior. However, if you trust the driver, there's no reason why the OS should block you from installing it. Just use one of the methods mentioned above, and you should be able to install and use unsigned drivers on your Windows PC.

 In this guide, we're going to show you several ways to do it.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-superior-7-streamers-choice-for-videos/"><u>[New] 2024 Approved Superior 7 Streamer's Choice for Videos</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-narrating-real-life-how-to-write-engaging-docu-scripts/"><u>2024 Approved Narrating Real Life How to Write Engaging Docu-Scripts</u></a></li>
<li><a href="https://android-unlock.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-lava-yuva-2-pro-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Lava Yuva 2 Pro</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/caption-crafting-select-writing-apps-for-your-photos-for-2024/"><u>Caption Crafting Select Writing Apps for Your Photos for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/cautionary-voice-the-dangers-of-chatgpt-data-exchanges/"><u>Cautionary Voice: The Dangers of ChatGPT Data Exchanges</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-unique-screencaps-for-win11/"><u>Crafting Unique Screencaps for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-restore-distribution-and-catroot2-in-ws11/"><u>Efficiently Restore Distribution & Catroot2 in WS11</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-error-0xc004f050-from-windows-update/"><u>Eliminating Error 0XC004F050 From Windows Update</u></a></li>
<li><a href="https://win11.techidaily.com/gentle-resting-practices-for-your-pc/"><u>Gentle Resting Practices for Your PC</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-xiaomi-redmi-note-12-pro-5g-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Xiaomi Redmi Note 12 Pro 5G Devices | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/is-a-drive-missing-on-windows-heres-how-to-fix-it/"><u>Is a Drive Missing on Windows? Here's How to Fix It</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/mastering-real-time-video-conversations-with-whatsapp-web-on-pcs/"><u>Mastering Real-Time Video Conversations with WhatsApp Web on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-enabling-startup-services/"><u>Mastering Windows 11: Enabling Startup Services</u></a></li>
<li><a href="https://win11.techidaily.com/microsofts-copilot-key-enhancing-productivity-with-windows-11/"><u>Microsoft's Copilot Key: Enhancing Productivity with Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/ultimate-guide-to-free-pptp-vpn-for-beginners-on-zte-blade-a73-5g-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Free PPTP VPN For Beginners On ZTE Blade A73 5G | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    