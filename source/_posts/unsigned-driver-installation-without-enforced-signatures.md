---
title: Unsigned Driver Installation Without Enforced Signatures
date: 2024-09-11T09:36:02.770Z
updated: 2024-09-12T09:36:02.770Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unsigned Driver Installation Without Enforced Signatures
excerpt: This Article Describes Unsigned Driver Installation Without Enforced Signatures
keywords: DriverInstallNoSignature,UnsignedDriversSetup,ByPassEnforcedSigns,NoSignedDriverInstalls,InstallersWithoutSig,SignatureFreeDriver,EnforceSignaturesOff
thumbnail: https://thmb.techidaily.com/2921f580a005bca983d6da9a3afb73cd46b3297303a92739f51d69c3aa21056e.jpg
---

## Unsigned Driver Installation Without Enforced Signatures

 Sometimes, Windows will block you from installing an unsigned driver, which is a driver you've downloaded elsewhere other than through a Windows Update or the device manufacturer's website. But if you need the driver, and you know it is perfectly safe, you can turn off driver signature enforcement and let it through.

 In this guide, we're going to show you several ways to do it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<span id="1982570">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982570.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982570">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982570.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982570%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982570/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130533/26400" target="_top" id="2130533">
  <img src="//a.impactradius-go.com/display-ad/26400-2130533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130533/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Right-click **Code signing for driver packages** and select **Edit**.  
![editing the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-the-code-signing-for-driver-packages-policy.jpg)
4. Click the **Enabled** radio button, and then, in the **Options** section, click on the dropdown and select **Ignore**.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123726/7443" target="_top" id="2123726">
  <img src="//a.impactradius-go.com/display-ad/7443-2123726" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123726/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![enabling the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/enabling-the-code-signing-for-driver-packages-policy.jpg)
5. Click on **OK**.

 If you want to enable driver signature enforcement again, go back to step #4 and set the radio button to **Not configured**.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129043/19576" target="_top" id="2129043">
  <img src="//a.impactradius-go.com/display-ad/19576-2129043" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129043/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137412/7443" target="_top" id="2137412">
  <img src="//a.impactradius-go.com/display-ad/7443-2137412" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137412/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now restart your computer, and when it boots back up, it will be in test mode. After you're done installing those drivers, don't forget to disable test mode. The command to do that is **bcdedit /set testsigning off**.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005184/22899" target="_top" id="2005184">
  <img src="//a.impactradius-go.com/display-ad/22899-2005184" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005184/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Now You Can Install Unsigned Drivers on Windows

 Installing unsigned drivers on Windows is not recommended, since they can lead to unexpected behavior. However, if you trust the driver, there's no reason why the OS should block you from installing it. Just use one of the methods mentioned above, and you should be able to install and use unsigned drivers on your Windows PC.

 In this guide, we're going to show you several ways to do it.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-final-cut-pro-x-mastery-crafting-instagrams-desired-format/"><u>[New] In 2024, Final Cut Pro X Mastery Crafting Instagram's Desired Format</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-innovative-house-blueprints-for-snapshot-players/"><u>[New] In 2024, Innovative House Blueprints for Snapshot Players</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-crafting-softer-sounds-with-live-software/"><u>[Updated] Crafting Softer Sounds with Live Software</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-science-behind-apples-m1-processor-unveiled/"><u>2024 Approved The Science Behind Apple’s M1 Processor Unveiled</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/complete-guide-to-duplicate-your-dvd-to-iso-format-using-winx-dvd-copy-software/"><u>Complete Guide to Duplicate Your DVD to ISO Format Using WinX DVD Copy Software</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-best-of-both-worlds-windows-and-games/"><u>Exploring the Best of Both Worlds: Windows & Games</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-windows-bluetooth-mouse-problems-quickly-and-easily-a-comprehensive-guide/"><u>Fix Windows Bluetooth Mouse Problems Quickly and Easily – A Comprehensive Guide</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/from-novice-to-pro-mastering-the-art-of-tiktok-video-capture/"><u>From Novice to Pro Mastering the Art of TikTok Video Capture</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-vector-graphics-101-overview-of-varieties-and-tools/"><u>In 2024, Vector Graphics 101 Overview of Varieties & Tools</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-exploration-of-windows-system-caching/"><u>In-Depth Exploration of Window’s System Caching</u></a></li>
<li><a href="https://win11.techidaily.com/leverage-windows-11-features-with-github-desktop-integration/"><u>Leverage Windows 11 Features with GitHub Desktop Integration</u></a></li>
<li><a href="https://win11.techidaily.com/master-naming-conventions-for-windows-files-max-156/"><u>Master Naming Conventions for Windows Files (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-unresponsive-services-error-1053/"><u>Navigating Through Windows Unresponsive Services (Error 1053)</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-winget-hurdles-on-windows-11-systems/"><u>Overcoming Winget Hurdles on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-ensuring-steam-recognizes-your-console-controller/"><u>Quick Fixes: Ensuring Steam Recognizes Your Console Controller</u></a></li>
<li><a href="https://win11.techidaily.com/recovering-absent-logins-in-windows-11-os/"><u>Recovering Absent Logins in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-network-prompt-gaps-seamless-action-integration-in-windows/"><u>Resolving Network Prompt Gaps: Seamless Action Integration in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/securing-your-control-center-mastering-management-on-windows-11/"><u>Securing Your Control Center: Mastering Management on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/solving-win1011s-network-error-code-0x800704b3/"><u>Solving Win10/11's Network Error Code: 0X800704B3</u></a></li>
<li><a href="https://win11.techidaily.com/sync-fail-resolving-outlook-app-errors-on-pcs/"><u>Sync Fail: Resolving Outlook App Errors on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-choosing-drawing-apps-on-win-11/"><u>The Ultimate Guide to Choosing Drawing Apps on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-resource-for-streamlined-navigation-windows-narrator-keybindings/"><u>The Ultimate Resource for Streamlined Navigation: Windows Narrator Keybindings</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-rectify-malfunctioning-discord-game-checker-on-windows/"><u>Tips to Rectify Malfunctioning Discord Game Checker on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/transition-to-windows-11-seamlessly-on-mac-via-parallels-pro/"><u>Transition to Windows 11 Seamlessly on Mac via Parallels Pro</u></a></li>
<li><a href="https://solve-news.techidaily.com/ultimate-guide-to-using-winx-mediatrans-the-top-choice-app-for-seamless-ios-device-and-computer-syncing/"><u>Ultimate Guide to Using WinX MediaTrans™ - The Top Choice App for Seamless iOS Device & Computer Syncing</u></a></li>
<li><a href="https://win11.techidaily.com/unfreezing-frozen-firewall-settings-in-windows-11/"><u>Unfreezing Frozen Firewall Settings in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-microsoft-store-quick-sign-in-fixes/"><u>Unlocking the Microsoft Store: Quick Sign-In Fixes</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-3gp-file-trimmer-edit-and-split-your-videos-easily-for-2024/"><u>Updated 3GP File Trimmer Edit and Split Your Videos Easily for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-wallpaper-guide-incorporating-spotlight-photos/"><u>Windows Wallpaper Guide: Incorporating Spotlight Photos</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/youtube-studio-editor-transform-your-videos-with-ease/"><u>YouTube Studio Editor Transform Your Videos with Ease</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    