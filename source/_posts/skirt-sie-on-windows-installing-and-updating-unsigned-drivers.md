---
title: "Skirt SIE on Windows: Installing and Updating Unsigned Drivers"
date: 2025-01-17T20:02:11.720Z
updated: 2025-01-24T17:40:56.024Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Skirt SIE on Windows: Installing and Updating Unsigned Drivers"
excerpt: "This Article Describes Skirt SIE on Windows: Installing and Updating Unsigned Drivers"
keywords: Skirt SIE Install Guide,Skirt SIE for Win Update,Skirt SIE Drivers Install,Skirt SIE Unsigned Driver,Windows Skirt SIE Setup,Updating Skirt SIE on Win,Unsigned Drivers Installation
thumbnail: https://thmb.techidaily.com/20a1161c2d60e760a9d2866e0269161f0abce5bf45e09881a1912be2c7963695.jpg
---

## Skirt SIE on Windows: Installing and Updating Unsigned Drivers

 Sometimes, Windows will block you from installing an unsigned driver, which is a driver you've downloaded elsewhere other than through a Windows Update or the device manufacturer's website. But if you need the driver, and you know it is perfectly safe, you can turn off driver signature enforcement and let it through.

 In this guide, we're going to show you several ways to do it.

## How to Disable Driver Signature Enforcement in the Startup Settings

 A temporary way to disable driver signature enforcement is through Startup Settings, allowing you to install the unsigned drivers. However, the moment you restart your PC, Windows will re-enable driver signature enforcement. The unsigned drivers you've installed will still work, but you may not be able to install new ones.

 To disable driver signature enforcement this way, you'll have to [access the Startup Settings screen](https://www.makeuseof.com/windows-startup-settings/). The **Disable driver signature enforcement** option will be the seventh one, so press **F7** or **7** on your keyboard to select it.

![windows 11 startup settings safe mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-startup-settings-safe-mode.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/grbt-5VvbuI?si=qnoirlmljslpqcQj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Your computer will then restart, and when it reboots, you'll be able to install those unsigned drivers.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/epKTCSREjhI?si=Ez_hObK1FZrmEE7f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Disable Driver Signature Enforcement in the Local Group Policy Editor

 You can also disable driver signature enforcement by tweaking the **Code signing for driver packages** policy in the Local Group Policy Editor (LGPE). Doing this will allow you to install unsigned drivers even if you restart your computer.

 Unfortunately, you can only natively access the LGPE if you're on Windows Pro or Enterprise Edition. However, there is a way to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

1. Press **Win + S** to bring up Windows Search, enter **group policy** in the Search box, and select **Edit group policy** in the Search results.  
![Open Group Policy Editor Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-group-policy-editor-using-windows-search.jpg)
2. Once the LGPE opens up, head to **User Configuration > Administrative Templates > System > Driver Installation**.
3. Right-click **Code signing for driver packages** and select **Edit**.  
![editing the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-the-code-signing-for-driver-packages-policy.jpg)
4. Click the **Enabled** radio button, and then, in the **Options** section, click on the dropdown and select **Ignore**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0nGlyEL5K6Y?si=3KZhTTBvKcPmyS68" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If that is the case, you can try [turning off Secure Boot](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) and trying again. But if you don't want to do this, using Startup Settings and the Local Group Policy Editor is perfectly okay.

 You can also put Windows in test mode, which disables driver signature enforcement, allowing you to install those unsigned drivers. To enter test mode, follow the steps below (keep in mind that you may run into the Secure Boot error):

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set testsigning on** and paste it into PowerShell.  
![turning on Test Mode in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-on-test-mode-in-terminal.jpg)
4. Hit **Enter** to run the command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-helps.techidaily.com/new-in-2024-expert-guide-to-android-time-lapse-video-magic/"><u>[New] In 2024, Expert Guide to Android Time-Lapse Video Magic</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/latform-faceoff-for-quick-viewers-a-clash-between-youtube-shorts-and-tiktok/"><u>[New] Platform Faceoff for Quick Viewers A Clash Between YouTube Shorts and TikTok</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-content-creation-crossroads-igtv-vs-youtube-which-one-fits-best/"><u>[Updated] 2024 Approved Content Creation Crossroads IGTV Vs. YouTube - Which One Fits Best?</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-exclusive-fb-video-downloads-enhance-firefox-use-for-2024/"><u>[Updated] Exclusive FB Video Downloads Enhance Firefox Use for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/12-unnecessary-windows-programs-and-apps-you-should-uninstall/"><u>12 Unnecessary Windows Programs and Apps You Should Uninstall</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-full-rotation-video-gear-for-social-media-broadcasts/"><u>2024 Approved Full Rotation Video Gear for Social Media Broadcasts</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-saving-success-mastering-ppt-errors-in-windows-11/"><u>Accelerate Saving Success: Mastering PPT Errors in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-system-awakening-tweak-windows-11-boot-timeout/"><u>Accelerating System Awakening: Tweak Windows 11 Boot Timeout</u></a></li>
<li><a href="https://win11.techidaily.com/adopting-new-visual-elements-the-microsoft-store-experience/"><u>Adopting New Visual Elements: The Microsoft Store Experience</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-clutter-with-a-sleek-setup-using-your-android-tab-in-w11/"><u>Avoiding Clutter with a Sleek Setup: Using Your Android Tab in W11</u></a></li>
<li><a href="https://fox-blue.techidaily.com/embrace-effortless-storage-our-20-most-trusted-free-cloud-service-choices-up-to-1tb-for-2024/"><u>Embrace Effortless Storage - Our 20 Most Trusted FREE Cloud Service Choices (Up To 1TB) for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719327784213-fixing-the-common-wwinplusp-errors-on-windows-devices/"><u>Fixing the Common WWin+P Errors on Windows Devices</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-on-vivo-y77t-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location on Vivo Y77t | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-one-source-livestream-perfection-a-streamers-blueprint/"><u>In 2024, One-Source Livestream Perfection A Streamer's Blueprint</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210396427-9781087996172-on-cue/"><u>On Cue | Free Book</u></a></li>
</ul></div>

