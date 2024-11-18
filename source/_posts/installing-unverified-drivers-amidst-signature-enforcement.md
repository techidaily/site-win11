---
title: Installing Unverified Drivers Amidst Signature Enforcement
date: 2024-11-16T02:36:11.073Z
updated: 2024-11-17T17:19:22.997Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Installing Unverified Drivers Amidst Signature Enforcement
excerpt: This Article Describes Installing Unverified Drivers Amidst Signature Enforcement
keywords: Unchecked Driver Installation,Bypassing Driver Verification,Software Driver Risks,Device Firmware Changes,Non-Verified Drivers Risk,Avoid Signature Checks,Enforcement of Driver Integrity
thumbnail: https://thmb.techidaily.com/7f46fac9a85eca734c1f07440ac82d4e70260de3231ef2557f357bda5f1ea303.jpg
---

## Installing Unverified Drivers Amidst Signature Enforcement

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115932/19272" target="_top" id="2115932">
  <img src="//a.impactradius-go.com/display-ad/19272-2115932" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Right-click **Code signing for driver packages** and select **Edit**.  
![editing the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-the-code-signing-for-driver-packages-policy.jpg)
4. Click the **Enabled** radio button, and then, in the **Options** section, click on the dropdown and select **Ignore**.  
![enabling the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/enabling-the-code-signing-for-driver-packages-policy.jpg)
5. Click on **OK**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075462/7443" target="_top" id="2075462">
  <img src="//a.impactradius-go.com/display-ad/7443-2075462" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075462/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130531/26400" target="_top" id="2130531">
  <img src="//a.impactradius-go.com/display-ad/26400-2130531" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130531/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137206/26400" target="_top" id="2137206">
  <img src="//a.impactradius-go.com/display-ad/26400-2137206" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137206/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now restart your computer, and when it boots back up, it will be in test mode. After you're done installing those drivers, don't forget to disable test mode. The command to do that is **bcdedit /set testsigning off**.

## Now You Can Install Unsigned Drivers on Windows

 Installing unsigned drivers on Windows is not recommended, since they can lead to unexpected behavior. However, if you trust the driver, there's no reason why the OS should block you from installing it. Just use one of the methods mentioned above, and you should be able to install and use unsigned drivers on your Windows PC.

 In this guide, we're going to show you several ways to do it.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-make-an-impression-with-youtube-clips-step-by-step-into-the-world-of-gif-making/"><u>[Updated] In 2024, Make an Impression With YouTube Clips Step-by-Step Into the World of Gif Making</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-simplifying-the-process-how-to-install-and-use-ez-grabber/"><u>[Updated] In 2024, Simplifying the Process How to Install and Use EZ Grabber</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-radiant-cinematography-the-ultimate-guide-for-videographers/"><u>2024 Approved Radiant Cinematography The Ultimate Guide for Videographers</u></a></li>
<li><a href="https://blog-min.techidaily.com/dvd-samsung-sony-lg/"><u>DVDバックアップ＆ライブストリームテクニック: ビデオレコーダーで楽しむSamsung, Sony, LG</u></a></li>
<li><a href="https://technical-tips.techidaily.com/expert-tips-on-integrating-a-subwoofer-into-your-samsung-soundbar-setup/"><u>Expert Tips on Integrating a Subwoofer Into Your Samsung Soundbar Setup</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-admin-access-launching-windows-terminal-effortlessly/"><u>Mastering Admin Access: Launching Windows Terminal Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-component-services-interface-in-windows-11/"><u>Mastering Component Services Interface in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-pc-efficiency-with-top-5-keyboard-cars/"><u>Maximizing PC Efficiency with Top 5 Keyboard Cars</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-faulty-data-handling-of-usb-sticks-in-windows-os/"><u>Overcoming Faulty Data Handling of USB Sticks in Windows OS</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/power-through-the-month-discover-the-revolutionary-ecoflow-portable-power-station-featured-by-zdnet/"><u>Power Through the Month: Discover the Revolutionary EcoFlow Portable Power Station Featured by ZDNet</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-your-keyboard-speed-typingaid-way/"><u>Skyrocket Your Keyboard Speed - TypingAid Way</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-playthrough-solutions-to-exit-code-woc/"><u>Streamline Playthrough - Solutions to Exit Code WoC</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-verizon-promotions-and-upgrades-available-this-month/"><u>Top Verizon Promotions & Upgrades Available This Month</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-malwarebytes-service-access-on-windows-devices/"><u>Unblocking Malwarebytes Service Access on Windows Devices</u></a></li>
<li><a href="https://win-net.techidaily.com/windows-spezifische-kostenfreie-losungen-zur-datenaufwartssynchronisation-und-verwaltung/"><u>Windows-Spezifische Kostenfreie Lösungen Zur Datenaufwärtssynchronisation Und -Verwaltung</u></a></li>
</ul></div>

