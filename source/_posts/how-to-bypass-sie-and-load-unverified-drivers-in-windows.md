---
title: How to Bypass SIE & Load Unverified Drivers in Windows
date: 2024-06-25T10:31:29.635Z
updated: 2024-06-26T10:31:29.635Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Bypass SIE & Load Unverified Drivers in Windows
excerpt: This Article Describes How to Bypass SIE & Load Unverified Drivers in Windows
keywords: Bypass SIE Restrictions,Loading Unverified Drivers,Windows Driver Modding,Disabling Driver Signature,Unverified Drivers Installation,Windows Patching Techniques,Circumvent Windows Security
thumbnail: https://thmb.techidaily.com/904e4358c32651c8870cd752598cbad0b1afa3205d185e4b265bf0a0d105bd32.jpg
---

## How to Bypass SIE & Load Unverified Drivers in Windows

 Sometimes, Windows will block you from installing an unsigned driver, which is a driver you've downloaded elsewhere other than through a Windows Update or the device manufacturer's website. But if you need the driver, and you know it is perfectly safe, you can turn off driver signature enforcement and let it through.

 In this guide, we're going to show you several ways to do it.

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

## Now You Can Install Unsigned Drivers on Windows

 Installing unsigned drivers on Windows is not recommended, since they can lead to unexpected behavior. However, if you trust the driver, there's no reason why the OS should block you from installing it. Just use one of the methods mentioned above, and you should be able to install and use unsigned drivers on your Windows PC.

 In this guide, we're going to show you several ways to do it.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/overcoming-speech-recognition-launch-failures-in-windows-os/"><u>Overcoming Speech Recognition Launch Failures in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-fatal-windows-errors-the-0xf0831-guide/"><u>Avoiding Fatal Windows Errors: The 0xF0831 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-no-browser-scenarios-in-new-oss/"><u>Overcoming No-Browser Scenarios in New OSs</u></a></li>
<li><a href="https://win11.techidaily.com/the-key-to-organized-print-setup-in-windows-systems/"><u>The Key to Organized Print Setup in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-ms-paint-within-windows-11/"><u>Initiating MS Paint Within Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-download-your-cortana-data-on-windows/"><u>How to Download Your Cortana Data on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/configure-windows-apps-with-personalized-keys/"><u>Configure Windows Apps with Personalized Keys</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-art-of-app-migration-from-older-windows-versions/"><u>Unveiling the Art of App Migration From Older Windows Versions</u></a></li>
<li><a href="https://win11.techidaily.com/stop-recurring-file-explorer-autoload/"><u>Stop Recurring File Explorer Autoload</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-x80072f30-quick-fix-for-windows-store-problems/"><u>Eliminate X80072F30: Quick Fix for Windows Store Problems</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-expertise-in-anime-vocal-alteration-hottest-voice-change-tools-on-pcs-and-smartphones-for-2024/"><u>New Expertise in Anime Vocal Alteration Hottest Voice-Change Tools on PCs and Smartphones for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-perfectly-pair-photos-for-your-instagram-story-easy-guide/"><u>[New] In 2024, Perfectly Pair Photos for Your Instagram Story  Easy Guide</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-top-10-anime-movies-of-all-time/"><u>Updated Top 10 Anime Movies of All Time</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/elevate-your-vlogs-optimizing-title-description-and-tags/"><u>Elevate Your Vlogs  Optimizing Title, Description & Tags</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-best-video-dimensions-for-instagram/"><u>2024 Approved BEST Video Dimensions for Instagram?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-can-i-unlock-my-iphone-11-pro-after-forgetting-my-pin-code-by-drfone-ios/"><u>How Can I Unlock My iPhone 11 Pro After Forgetting my PIN Code?</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-how-to-share-videos-on-twitter-on-your-phone-without-retweeting-in-2024/"><u>[New] How to Share Videos on Twitter on Your Phone Without Retweeting, In 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-acquiring-lifelike-vampire-sonic-traces/"><u>Updated Acquiring Lifelike Vampire Sonic Traces</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-add-digital-signature-to-a-pdf-v14-document-by-ldigisigner-sign-a-pdf-sign-a-pdf/"><u>How to add digital signature to a PDF v1.4 document</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-in-2024-how-to-control-the-speed-of-video/"><u>New In 2024, How to Control the Speed of Video</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>