---
title: How to Overcome Microsoft's Driver Verification Hurdles
date: 2024-09-11T02:56:14.943Z
updated: 2024-09-17T05:10:39.942Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Overcome Microsoft's Driver Verification Hurdles
excerpt: This Article Describes How to Overcome Microsoft's Driver Verification Hurdles
keywords: Drivers Verify Techniques,Overcoming MS Driver Check,Eluding MS Verification,Skillful Drivers Approach,Beating Verification Bars,Microsoft Driver Challenges,Mastering Verification Hurdles
thumbnail: https://thmb.techidaily.com/f386bcd1cdef2e7eae82e10cf44eeb6665615e5a19222b7cb69d0ec540888707.jpg
---

## How to Overcome Microsoft's Driver Verification Hurdles

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
<a href="https://unicoeye.pxf.io/c/5597632/2134247/18498" target="_top" id="2134247">
  <img src="//a.impactradius-go.com/display-ad/18498-2134247" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134247/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Now You Can Install Unsigned Drivers on Windows

 Installing unsigned drivers on Windows is not recommended, since they can lead to unexpected behavior. However, if you trust the driver, there's no reason why the OS should block you from installing it. Just use one of the methods mentioned above, and you should be able to install and use unsigned drivers on your Windows PC.

 In this guide, we're going to show you several ways to do it.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-essential-writing-habits-for-successful-fb-campaigns-for-2024/"><u>[New] Essential Writing Habits for Successful FB Campaigns for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-gopro-camera-rewind-selecting-superior-sd-cards-hero-7-8/"><u>[New] In 2024, GoPro Camera Rewind Selecting Superior SD Cards (Hero 7, 8)</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-recording-internet-radios-simplified-tips-and-tricks/"><u>2024 Approved Recording Internet Radios Simplified Tips and Tricks</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-tiny-thesis-for-film-storyline/"><u>2024 Approved Tiny Thesis for Film Storyline</u></a></li>
<li><a href="https://win11.techidaily.com/drive-harmony-a-guide-to-efficient-hdds-in-win11/"><u>Drive Harmony: A Guide to Efficient HDDs in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-correcting-icon-misplacement/"><u>Guide to Correcting Icon Misplacement</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-obtain-your-logitech-m525-device-drivers/"><u>How To Obtain Your Logitech M525 Device Drivers?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-harnessing-multiple-windows-learn-pip-in-microsoft-edge/"><u>In 2024, Harnessing Multiple Windows Learn PIP in Microsoft Edge</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722964855318-latest-and-fastest-nvidia-drivers-now-available-for-windows-10-users/"><u>Latest & Fastest NVIDIA Drivers Now Available for Windows 10 Users</u></a></li>
<li><a href="https://extra-resources.techidaily.com/master-iphone-selfies-naturally-10-best-no-cost-enhancing-apps/"><u>Master iPhone Selfies Naturally 10 Best No-Cost Enhancing Apps</u></a></li>
<li><a href="https://tech-haven.techidaily.com/next-gen-conversational-tools-the-10-breakthroughs-outshining-chatgpt/"><u>Next-Gen Conversational Tools: The 10 Breakthroughs Outshining ChatGPT</u></a></li>
<li><a href="https://win11.techidaily.com/pinpointing-your-perfect-match-with-nvidia-driver-selection/"><u>Pinpointing Your Perfect Match with Nvidia Driver Selection</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-transitions-with-the-fn-button-in-windows-pcs/"><u>Smooth Transitions with the (Fn) Button in Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/windows-troubleshooting-resolving-code-0x0000004e-issue/"><u>Windows Troubleshooting: Resolving Code 0X0000004E Issue</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    