---
title: Quick Guide to Reactivate Missing Windows Apps & Options
date: 2024-09-11T09:39:06.340Z
updated: 2024-09-12T09:39:06.340Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Guide to Reactivate Missing Windows Apps & Options
excerpt: This Article Describes Quick Guide to Reactivate Missing Windows Apps & Options
keywords: Reactivate Apps Guide,Restore Missing Windows,Reinstating Apps Windows,Revive Lost Windows Features,Fix Deleted Windows Options,Uninstall Error Correction,Recover Forgotten Windows Apps
thumbnail: https://thmb.techidaily.com/5bfb2b2f01975a3eebb8a0b131dcc5bf0873594ba112a1d8a6d8b08b27b2cbba.jpg
---

## Quick Guide to Reactivate Missing Windows Apps & Options

 Optional features are those that you can add to get more functionality or support for certain file formats. For example, you can install different font packs or old Windows utilities like Paint and WordPad.

 If you're having trouble installing optional features, you're not alone. Sometimes optional features may fail to install due to corrupt system files, an outdated Windows version, or incorrect configuration settings.

 Fortunately, there are several ways to fix this problem and get the optional features running again. So, how can you fix the optional features not installing issue?

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Use the DISM Tool

 One of the first things you can try is using the Deployment Image Servicing and Management (DISM) tool. This tool is part of Windows, and you can use it to fix corrupt system files, including ones that could be causing problems when installing optional features.

To use the DISM tool, follow these steps:

1. Press**Win + Q** to bring up the Windows search dialogue box.
2. Type**cmd** and click**Run as administrator** to open the Command Prompt.
3. Type**dism /online /cleanup-image /restorehealth** and press**Enter** .  
![DISM Windows Utility Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/dism-windows-utility.jpg)

 This will start the DISM tool and begin scanning your system for any corrupt or missing files. If it finds any issues with your computer, it will automatically repair them.

 Once the process is complete, you can restart your computer and try installing the optional feature again. If DISM does not work or throws an error code, make sure to go through the[DISM not working fixes](https://www.makeuseof.com/windows-11-dism-error-2-fix/) .

## 2\. Run the System File Checker or SFC Utility

 Another tool you can use to fix issues with optional feature installation is the System File Checker (SFC) utility.

 SFC is a command-line utility on Windows, which means you can use it from the Command Prompt itself. It is a useful tool for troubleshooting and repairing problems with the system files on your computer, similar to the DISM tool.

To check your system using SFC, follow these steps:

1. Open the Command Prompt with administrative rights using any of the[ways to open CMD as an admin on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. Type**sfc /scannow** and press**Enter** .  
![SFC Utility In Windows Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-utility-in-windows.jpg)
3. Once SFC scans for errors, make sure to restart your computer.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135417/19272" target="_top" id="2135417">
  <img src="//a.impactradius-go.com/display-ad/19272-2135417" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135417/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Want to know the best part?

 The best part is that the System File Checker not only helps you fix the optional features problem but also any other Windows issues. In fact, it's one of the best[ways to repair corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

## 3\. Reset the Windows Update Components

 Windows Update Components include all the services, tasks, and programs that work together to make sure your Windows system is up-to-date and secure.

 Resetting the Windows Update components might help solve the issue with optional feature installation. Here's how you can reset the Windows Update components easily:

1. Open the Command Prompt utility as an administrator.
2. Type the following commands one after the other, pressing**Enter** after each one:

`net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver  
ren C:\Windows\SoftwareDistribution SoftwareDistribution.old  
ren C:\Windows\System32\catroot2 catroot2.old  
net start wuauserv  
net start cryptSvc  
net start bits  
net start msiserver`

 This command will stop the Windows Update services, rename the**SoftwareDistribution** and**catroot2** folders, and then restart the services. This can help reset the update process and fix any issues that might be causing problems with optional feature installation.

![Update Components Reset In CMD Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/update-components-reset-in-cmd.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123476/16836" target="_top" id="2123476">
  <img src="//a.impactradius-go.com/display-ad/16836-2123476" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123476/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 While the commands may look intimidating, you don't need to worry, as all the commands mentioned above will not cause any harm to your system.​​​​

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132160/7443" target="_top" id="2132160">
  <img src="//a.impactradius-go.com/display-ad/7443-2132160" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132160/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Run the Windows Update Troubleshooter

 If the Command Prompt method did not work for you, you can use the Windows Update Troubleshooter to reset update components. This tool can help identify and fix problems with the update process, including issues that might be preventing optional features from installing.

Follow these steps to run the update troubleshooter on Windows:

1. Press**Win + I** to launch the Settings app.
2. Scroll down and click**Troubleshoot > Other troubleshooters.**  
![Troubleshooter Settings In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/troubleshooter-settings-in-windows.jpg)
3. Click**Run** next to**Windows Update** to run the troubleshooter.  
![Other Troubleshooters In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/other-troubleshooters-in-windows.jpg)
4. Follow the prompts to complete the troubleshooting process.

 If you're using Windows 10, the Windows Update Troubleshooter is in**Settings > Update & Security >** **Troubleshoot > Windows Update** .

 The troubleshooter will begin scanning your system for any issues with the update process and will offer suggestions for how to fix them. So, you just need to follow the prompts, and then try[installing the optional features](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) again.

## 5\. Update Windows to the Latest Version

 If the issue with optional feature installation is related to outdated system files, you may be able to fix it by updating Windows to the latest version.

 Updating Windows can help ensure that you have the latest security patches, bug fixes, and system files, which can help resolve any issues you may be experiencing.

Here's how you can update Windows to the latest version:

1. Press**Win + I** to open the Settings app.
2. Click on**Windows** **Update > Check for updates** on Windows 11\. For Windows 10, click on **Update & Security > Windows Update > Check for Updates** .  
![Windows Update In Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-update-in-windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137212/26400" target="_top" id="2137212">
  <img src="//a.impactradius-go.com/display-ad/26400-2137212" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137212/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 That's it. Now, you can install any update that is available for your computer.

 By default, Windows automatically downloads and installs updates, but you can also check for updates manually by following the steps above.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123750/7443" target="_top" id="2123750">
  <img src="//a.impactradius-go.com/display-ad/7443-2123750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123750/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Restart the Windows Module Installer Service

 The Windows Module Installer service allows you to install, change, and remove Windows features and optional components. If it is not working properly, it can make it difficult to install optional features.

 Follow the below-given steps to restart the Windows Module Installer service:

1. Open Windows search and type**services** .
2. Select the best match to open the**Services** app.
3. Scroll down and find the**Windows Module Installer** service.
4. Right-click on the service and select**Restart** .  
![Windows Modules Installer Service In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-modules-installer-service.jpg)

 When you reset the module installer service, Windows tries to stop it and then start it again, which can help reset the installation process of optional features and fix any issues that might be causing problems.

 Once the service restarts, try installing the optional feature again, and it should work now.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134229/18498" target="_top" id="2134229">
  <img src="//a.impactradius-go.com/display-ad/18498-2134229" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134229/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Restore Windows Features Using PowerShell

 If all the above methods fail to work, restoring Windows features is your last resort. So, if you are unable to use or install an optional Windows feature, you might be able to fix the problem by using PowerShell to restore a particular feature.

 Here are the steps for restoring Windows features using the PowerShell:

1. Press**Win + X** to open the Power User menu.
2. Click on**Windows PowerShell (Admin)** or**Terminal (Admin)** .
3. Type the following command and press**Enter** :  
Get-WindowsOptionalFeature -Online  
![Get Optional Feature Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/get-optional-feature-command.jpg)  
 This command will show you the**FeatureName** and**State** of every optional Windows feature that you can use. Make sure to copy the "**FeatureName** " of the feature that you want to enable on Windows.

<!-- affiliate ads begin -->
<span id="1977004">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977004.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977004">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977004.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977004%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977004/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. To turn on a certain feature, use the following command and replace "**FEATURENAME** " with the feature's name that you copied earlier:  
Enable-WindowsOptionalFeature -Online -FeatureName FEATURENAME  
![Enable Optional Feature Command In PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/optional-feature-in-powershell.jpg)
5. Restart your computer for the changes to take effect.

 This will add the feature back to your system and should make it available for you to enable or disable in the features window.

 This method only allows you to restore a specific feature and, not all the features at once. So, you need to copy and paste the same command and edit the**FEATURENAME** every time.

 If these steps don't fix the problem, you may need to ask Microsoft or a technical support professional for more help.

<!-- affiliate ads begin -->
<span id="1770776">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770776.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770776">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770776.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770776%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770776/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Back the Windows Optional Features

 Hopefully, the issue with optional features not installing on your system should be fixed now. In any case, it is important to keep your system up-to-date and to follow best practices for maintaining your computer properly to help prevent issues like this from occurring.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-links.techidaily.com/updated-copyright-compliance-for-streaming-songs-on-instagram-for-2024/"><u>[Updated] Copyright Compliance for Streaming Songs on Instagram for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-a-step-by-step-guide-to-crafting-facebook-visual-stories/"><u>[Updated] In 2024, A Step-by-Step Guide to Crafting Facebook Visual Stories</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-intuitive-methods-to-log-your-google-voice-conversations/"><u>[Updated] In 2024, Intuitive Methods to Log Your Google Voice Conversations</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-outstanding-movies-beyond-the-leading-titles/"><u>[Updated] In 2024, Outstanding Movies Beyond the Leading Titles</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-masterclass-selecting-christian-streaming-platforms/"><u>2024 Approved Masterclass Selecting Christian Streaming Platforms</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/oggmp3202/"><u>最新フリーツールを紹介! OGGからMP3へ完全変換：専門的な操作手順のレッスン(202</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721451244609-avoid-mistakes-with-friends-and-family-names-in-your-iphones-fix-them-here/"><u>Avoid Mistakes with Friends & Family Names in Your iPhones - Fix Them Here!</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-file-properties-on-windows-platforms/"><u>Customizing File Properties on Windows Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-the-lunar-client-not-functional-message-in-os/"><u>Dealing with the Lunar Client Not Functional Message in OS</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-unwanted-edge-desktop-buttons/"><u>Disabling Unwanted Edge Desktop Buttons</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-this-file-has-no-app-windows-issue/"><u>Eliminating 'This File Has No App' Windows Issue</u></a></li>
<li><a href="https://win11.techidaily.com/empowering-your-pc-navigation-with-apple-maps/"><u>Empowering Your PC Navigation with Apple Maps</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-audio-integrating-dolby-atmos-in-windows/"><u>Enhance Your Audio: Integrating Dolby Atmos in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-consistent-reading-pane-openness-setup-for-email-attachments-in-ms-word/"><u>Ensuring Consistent Reading Pane Openness: Setup for Email Attachments In MS Word</u></a></li>
<li><a href="https://win11.techidaily.com/guide-finding-the-storage-for-your-desktop-pics/"><u>Guide: Finding the Storage for Your Desktop Pics</u></a></li>
<li><a href="https://win11.techidaily.com/handling-download-issues-with-windows-1011-files/"><u>Handling Download Issues with Windows 10/11 Files</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-infinix-smart-8-plus-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Infinix Smart 8 Plus Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-and-when-to-use-the-ping-command-in-windows/"><u>How (and When) to Use the Ping Command in Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-google-play-location-on-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>How to Change Google Play Location On Samsung Galaxy F15 5G | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-when-apple-account-locked-from-apple-iphone-15-pro-max-by-drfone-ios/"><u>How to Fix when Apple Account Locked From Apple iPhone 15 Pro Max?</u></a></li>
<li><a href="https://data-wizards.techidaily.com/how-to-repair-corrupt-mpeg-files/"><u>How to Repair Corrupt MPEG Files</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-motorola-g54-5g-phone-password-without-factory-reset-by-drfone-android/"><u>How to Unlock Motorola G54 5G Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-oneplus-open-pin-codepattern-lockpassword-by-drfone-android/"><u>How to Unlock OnePlus Open PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-premier-selection-of-best-indoor-android-games-no-wi-fi-required/"><u>In 2024, Premier Selection of Best Indoor Android Games (No Wi-Fi Required)</u></a></li>
<li><a href="https://win11.techidaily.com/journey-into-the-new-era-evolution-of-file-explorer-on-windows-11/"><u>Journey Into the New Era: Evolution of File Explorer on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/prolific-path-to-excellence-our-top-7-windows-11-widget-choices/"><u>Prolific Path to Excellence: Our Top 7 Windows 11 Widget Choices</u></a></li>
<li><a href="https://win11.techidaily.com/realignment-of-data-win11-hdd-optimization-techniques/"><u>Realignment of Data: Win11 HDD Optimization Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/reboot-your-win11-experience-three-tricks-up-your-sleeve/"><u>Reboot Your Win11 Experience: Three Tricks Up Your Sleeve</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-functionality-to-windows-photos-with-registering-packages/"><u>Reinstating Functionality to Windows Photos with Registering Packages</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-vitality-to-slow-moving-windows-batches/"><u>Restoring Vitality to Slow-Moving Windows Batches</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-and-solving-winerror-0x80071a90-in-windows/"><u>Simplifying & Solving WinError: 0X80071a90 in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/sixfold-solution-to-off-screen-woes-a-roadmap-for-rejuvenating-your-windows-desktop/"><u>Sixfold Solution to Off-Screen Woes: A Roadmap for Rejuvenating Your Windows Desktop</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/step-by-step-process-youtube-vids-converted-to-mp3/"><u>Step-by-Step Process YouTube Vids, Converted to MP3</u></a></li>
<li><a href="https://win11.techidaily.com/the-5-best-apps-to-help-you-write-better-on-a-windows-pc/"><u>The 5 Best Apps to Help You Write Better on a Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-blueprint-for-customizing-windows-startup/"><u>The Complete Blueprint for Customizing Windows Startup</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-managing-deletion-alerts-in-windows-os/"><u>Tips for Managing Deletion Alerts in Windows OS</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-persistent-game-crashes-on-oxygen-not-included-solved/"><u>Troubleshooting Persistent Game Crashes on Oxygen Not Included - Solved!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/unveiling-top-gear-secrets-expert-advice-from-toms-hardware/"><u>Unveiling Top Gear Secrets - Expert Advice From Tom's Hardware</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-taskbar-chat-discontinuation-what-does-this-mean-for-us/"><u>Windows 11 Taskbar Chat Discontinuation: What Does This Mean for Us?</u></a></li>
<li><a href="https://win11.techidaily.com/windows-time-tangle-solved-unify-system-dates/"><u>Windows Time Tangle Solved: Unify System Dates</u></a></li>
<li><a href="https://win11.techidaily.com/winning-task-managers-for-windows-10-and-11-users/"><u>Winning Task Managers for Windows 10 & 11 Users</u></a></li>
</ul></div>

