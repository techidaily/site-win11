---
title: Disabling SSI Compliance in Windows for Driver Installation
date: 2024-10-10T19:47:29.031Z
updated: 2024-10-15T21:26:43.191Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151854/7443" target="_top" id="2151854">
  <img src="//a.impactradius-go.com/display-ad/7443-2151854" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151854/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Disable Driver Signature Enforcement in the Local Group Policy Editor

 You can also disable driver signature enforcement by tweaking the **Code signing for driver packages** policy in the Local Group Policy Editor (LGPE). Doing this will allow you to install unsigned drivers even if you restart your computer.

 Unfortunately, you can only natively access the LGPE if you're on Windows Pro or Enterprise Edition. However, there is a way to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

1. Press **Win + S** to bring up Windows Search, enter **group policy** in the Search box, and select **Edit group policy** in the Search results.  
![Open Group Policy Editor Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-group-policy-editor-using-windows-search.jpg)
2. Once the LGPE opens up, head to **User Configuration > Administrative Templates > System > Driver Installation**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049388/7443" target="_top" id="2049388">
  <img src="//a.impactradius-go.com/display-ad/7443-2049388" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049388/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135416/19272" target="_top" id="2135416">
  <img src="//a.impactradius-go.com/display-ad/19272-2135416" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135416/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If that is the case, you can try [turning off Secure Boot](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) and trying again. But if you don't want to do this, using Startup Settings and the Local Group Policy Editor is perfectly okay.

 You can also put Windows in test mode, which disables driver signature enforcement, allowing you to install those unsigned drivers. To enter test mode, follow the steps below (keep in mind that you may run into the Secure Boot error):

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set testsigning on** and paste it into PowerShell.  
![turning on Test Mode in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-on-test-mode-in-terminal.jpg)
4. Hit **Enter** to run the command.

 Now restart your computer, and when it boots back up, it will be in test mode. After you're done installing those drivers, don't forget to disable test mode. The command to do that is **bcdedit /set testsigning off**.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139110/17108" target="_top" id="2139110">
  <img src="//a.impactradius-go.com/display-ad/17108-2139110" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139110/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://extra-skills.techidaily.com/new-how-to-live-stream-with-onestream-online-and-app/"><u>[New] How To Live Stream With OneStream - Online & App</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-depth-assessment-comprehensive-camstudio-review-for-2024/"><u>[New] In-Depth Assessment Comprehensive CamStudio Review for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exploring-top-open-source-video-tools-for-pcs-and-macs/"><u>[Updated] Exploring Top Open Source Video Tools for PCs and Macs</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-teaching-trends-top-10-innovative-audio-visual-recording-tools/"><u>[Updated] In 2024, Teaching Trends Top 10 Innovative Audio-Visual Recording Tools</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-instant-inspiration-the-easy-guide-to-building-custom-youtube-music-mixes-webapp/"><u>2024 Approved Instant Inspiration The Easy Guide to Building Custom YouTube Music Mixes (Web/App)</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/chatgpt-plus-review-top-5-benefits-of-membership/"><u>ChatGPT Plus Review: Top 5 Benefits of Membership</u></a></li>
<li><a href="https://win11.techidaily.com/combining-directories-a-windows-11-technique/"><u>Combining Directories: A Windows 11 Technique</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-context-menu-functionality-in-windows-11-add-folders/"><u>Enhance Context Menu Functionality in Windows 11 - Add Folders</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-google-chrome-from-tracking-your-location-on-xiaomi-13-ultra-drfone-by-drfone-virtual-android/"><u>How to Stop Google Chrome from Tracking Your Location On Xiaomi 13 Ultra? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-successfully-bypass-icloud-activation-lock-on-apple-iphone-14-pro-by-drfone-ios/"><u>How to Successfully Bypass iCloud Activation Lock on Apple iPhone 14 Pro</u></a></li>
<li><a href="https://discover-excellent.techidaily.com/mastering-the-art-of-toutv-content-saving-a-comprehensive-tutorial/"><u>Mastering the Art of Tou.TV Content Saving: A Comprehensive Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-device-hang-how-to-fix-dxgierrordevicehunk/"><u>Overcoming Device Hang: How to Fix DXGI_ERROR_DEVICE_HUNK</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-user-centric-design-windows-and-ai-revolution/"><u>Redefining User-Centric Design: Windows and AI Revolution</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-windows-11-parental-guidance-features/"><u>Setting Up Windows 11 Parental Guidance Features</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-minimized-tiworkerexe-cpu-activity/"><u>Solutions for Minimized TiWorker.exe CPU Activity</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-systems-with-microsofts-pc-manager-setup-on-win11/"><u>Streamlining Systems with Microsoft's PC Manager Setup on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/the-power-couple-in-mindfulness-cognitive-function-and-emotional-mastery/"><u>The Power Couple in Mindfulness: Cognitive Function & Emotional Mastery</u></a></li>
</ul></div>

