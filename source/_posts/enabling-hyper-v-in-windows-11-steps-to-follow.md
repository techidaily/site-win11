---
title: "Enabling Hyper-V in Windows 11: Steps to Follow"
date: 2024-07-13T10:01:26.556Z
updated: 2024-07-14T10:01:26.556Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enabling Hyper-V in Windows 11: Steps to Follow"
excerpt: "This Article Describes Enabling Hyper-V in Windows 11: Steps to Follow"
keywords: Win11HyperVInstall,EnableWindowsHyperV,SetUpHyperVWin11,HyperVSetupWindows11,Windows11EnableHyperV,Hyper-VConfigureWin11,InstallWin11HyperV
thumbnail: https://thmb.techidaily.com/8581bfa31a5d038a1f8f5ee676586f0437981f1b9f6527b07717a27989fe2446.jpg
---

## Enabling Hyper-V in Windows 11: Steps to Follow

 You can enable Hyper-V in Windows 11 as an optional feature included by default with the operating system. It lets you create virtual machines to install and run the guest OS on virtual hardware. However, Hyper-V is only available for the Pro, Education, and Enterprise edition of the OS. If you are using the Home edition, you have to rely on a third-party virtual machine manager.

 If you don’t want to use a third-party virtual machine manager, here is how to install Hyper-V on Windows 11 Home using a batch script hack.

## How to Enable Hardware Virtualization in Windows 11

![enable hardware virtualization bios hp laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hardware-virtualization-bios-hp-laptoop-1.jpg)

 Hyper-V is a bare-metal hypervisor and requires [Hardware Virtualization enabled in BIOS to work](https://www.makeuseof.com/what-is-virtualization-and-what-is-it-for/). Most modern systems support Hardware Virtualization, and you can enable it in BIOS.

 The below steps are for an HP laptop. Refer to the user manual or Knowledge Base resources on the computer manufacturer's website for other systems.

 To enable Hardware Virtualization in BIOS:

1. Shut down your PC if it is powered on.
2. Press the **Power** button to turn on the computer and then start pressing the **F10 key** to enter BIOS. The BIOS setup key varies depending on the manufacturer. So, use **F10, F2, F12, F1,** or **DEL** and see which one works for you.
3. Once in the BIOS Setup utility, open the **Configuration** tab.
4. Use the down arrow key and highlight **Virtualization Technology.**
5. Hit **Enter** and then select **Enabled**. Press **Enter** again to make the selection.
6. Next, press **F10** to save the changes and exit **BIOS**.
7. Your PC will restart with the Hardware Virtualization enabled. Now you can continue to install Hyper-V on your system.

## How to Install Hyper-V on Windows 11 Home

 The next step is to create and run a batch script to install the required files to enable Hyper-V in Windows 11 Home.

 Before you proceed with the next set of steps, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/). This will help you restore your computer to its current state if something goes wrong during the process.

 To enable Hyper-V in Windows 11 Home:

 1\. Open a new Notepad file. To do this, press **Win + R**, type notepad, and click **OK.**

![hyper v install windows 11 home script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/hyper-v-install-windows-11-home-script.png)

 2\. In the Notepad file, copy and paste the following script:

`pushd "%~dp0"  
dir /b %SystemRoot%\servicing\Packages\*Hyper-V*.mum >hyper-v.txt  
for /f %%i in ('findstr /i . hyper-v.txt 2^>nul') do dism /online /norestart /add-package:"%SystemRoot%\servicing\Packages\%%i"  
del hyper-v.txt  
Dism /online /enable-feature /featurename:Microsoft-Hyper-V -All /LimitAccess /ALL  
pause`

 3\. Press **Ctrl + S** to open the save dialog.

 4\. In the file name field, type **hyperv.bat.** The **.bat** extension at the end of the file name is important to execute the script.

![save hyperv install script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/save-hyperv-install-script.png)

 5\. Next, click the drop-down for **Save as type** and select **All Files.**

 6\. Click the **Save** button to save the file.

![run hyperv bat script administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/run-hyperv-bat-script-administrator.png)

 7\. Next, right-click on the **hyperv.bat** file and select **Run as administrator**. Click **Yes** if prompted by User Account Control.

 8\. The scrip will start executing in the Command Prompt to install Hyper-V. It may take a while, so wait till the process is complete.

 9.Once completed, you will see the Operation completed successfully message.

![install hyper v install windows 11 home](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/install-hyper-v-install-windows-11-home.png)

 10\. Type **Y** to confirm and restart your PC. If not, enter N to exit the Command Prompt.

 Note that you will need to restart your PC to apply the changes. After the restart, you should have Hyper-V installed in Windows 11 Home. Type Hyper-V in Windows search and click on Hyper-V Manager to create new a virtual machine.

 If it is still not available, you can [enable Hyper-V using the Windows Features dialog](https://www.makeuseof.com/windows-11-enable-hyper-v/), Command Prompt, and Windows PowerShell.

 Here's how you can quickly add Hyper-V to Windows 11 using Command Prompt:

1. Press the **Win** key and type **cmd**. Then right-click on **Command Prompt** and select **Run as administrator.**  
![enable hyper v command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-command-prompt.png)
2. In the Command Prompt window, type the following command and press **Enter**:  
`<code>DISM /Online /Enable-Feature /All /FeatureName:Microsoft-Hyper-V`
3. The above command uses the Deployment Imaging Service and Management (DISM) tool to enable Microsoft Hyper-V and the necessary dependencies on your Windows computer. The operation completed successfully message means you have successfully enabled Hyper-V.

## How to Disable Hyper-V on Windows 11 Home

![disable hyper v windows 11 windows features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/disable-hyper-v-windows-11-windows-features.jpg)

 You can disable Hyper-V in Windows 11 Home using the Windows Features dialog.

 To disable Hyper-V:

1. Press **Win + R** to open the **Run** dialog box.
2. Type **optionalfeatures.exe** and click **OK**.
3. In the **Windows Features** dialog, locate the Hyper-V option.
4. Uncheck the **Hyper-V** option and click **OK**. Wait for the uninstallation process to complete.
5. Next, click on **Restart Now** to restart your PC and apply the changes.

 Apart from Hyper-V, the Windows OS features another nifty virtualization solution, Windows Sandbox—a lightweight desktop environment to run applications in isolation. You can [enable Windows Sandbox from Windows Features](https://www.makeuseof.com/enable-set-up-windows-sandbox-windows-11/), but only on the Pro and Enterprise edition of the OS.

 Unlike Hyper-V, there is no batch script hack to install the sandbox app on the Home edition of Windows 11\. Instead, you can use one of the [Windows Sandbox Alternatives for Windows](https://www.makeuseof.com/windows-11-sandbox-alternatives/) to run and test applications in isolation.

## Run Hyper-V on Windows 11 Home

 Microsoft has officially restricted the use of Hyper-V to the Pro, Education, and Enterprise edition of the OS. However, a little tweak in the BIOS and a handy batch script can help you install Hyper-V on Windows 11 Home.

 Once you have Hyper-V up and running, you can install Windows, Ubuntu, and other supported operating systems in a virtual machine.

 If you don’t want to use a third-party virtual machine manager, here is how to install Hyper-V on Windows 11 Home using a batch script hack.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-skills.techidaily.com/revealing-hidden-social-exchanges-in-yt-discussions-for-2024/"><u>Revealing Hidden Social Exchanges in YT Discussions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-win-compatible-free-media-devices/"><u>Essential Guide: Win-Compatible Free Media Devices</u></a></li>
<li><a href="https://win11.techidaily.com/notetaking-renaissance-discovering-obsidians-visuality/"><u>Notetaking Renaissance: Discovering Obsidian's Visuality</u></a></li>
<li><a href="https://win11.techidaily.com/quick-start-guide-for-efficient-note-placement-in-win11win10/"><u>Quick-Start Guide for Efficient Note Placement in Win11/Win10</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-prioritizing-visibility-a-guide-to-insta-highlights-perfection/"><u>2024 Approved  Prioritizing Visibility  A Guide to Insta Highlights Perfection</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-comparing-youtube-and-dailymotion-notable-contrasts-for-2024/"><u>[Updated] Comparing YouTube and Dailymotion  Notable Contrasts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-windows-features-for-macos-advantages/"><u>Integrating Windows Features for MacOS Advantages</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-web-sites-becoming-win-desktops/"><u>The Art of Web Sites Becoming Win Desktops</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-disable-protected-app-ban-on-windows/"><u>Steps to Disable Protected App Ban on Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-earnings-on-youtube-a-monthly-perspective-for-2024/"><u>[New] Earnings on YouTube  A Monthly Perspective for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-sound-surge-5-apps-to-take-windows-volume-well-above-100/"><u>The Sound Surge: 5 Apps to Take Windows' Volume Well Above 100%%</u></a></li>
<li><a href="https://win11.techidaily.com/explore-1-6-gpu-power-tools-to-assess-on-your-pc/"><u>Explore #1-#6 GPU Power Tools to Assess on Your PC</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/navigating-through-essential-zoom-recording-equipment/"><u>Navigating Through Essential Zoom Recording Equipment</u></a></li>
<li><a href="https://win11.techidaily.com/the-artisans-approach-to-perfect-slide-printouts-from-powerpoint-in-windows/"><u>The Artisan's Approach to Perfect Slide Printouts From PowerPoint in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-code-a-secure-window-for-hardware-unhook-in-win11/"><u>How to Code a Secure Window for Hardware Unhook in Win11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-crafting-cinematic-magic-making-your-instagram-videos-shine-for-2024/"><u>[New] Crafting Cinematic Magic  Making Your Instagram Videos Shine for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-git-operations-with-github-desktop-and-windows-1011/"><u>Streamlining Git Operations with GitHub Desktop & Windows 10/11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-gain-instagram-reel-fame-emulate-top-tiktok-trends-and-insights/"><u>[Updated] Gain Instagram Reel Fame  Emulate Top TikTok Trends & Insights</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/beyond-basiccams-prospects-of-elevated-performance-for-2024/"><u>Beyond BasicCams  Prospects of Elevated Performance for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-eliminate-server-stumbled-errors-in-microsoft-store/"><u>Steps to Eliminate Server Stumbled Errors in Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/microsofts-ai-hub-enhancing-shopping-experience/"><u>Microsoft’s AI Hub – Enhancing Shopping Experience</u></a></li>
<li><a href="https://win11.techidaily.com/improve-energy-monitoring-full-charge-alerts-for-a-more-efficient-win11/"><u>Improve Energy Monitoring: Full Charge Alerts for a More Efficient Win11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-installer-errors-in-windows-10-and-11/"><u>Overcoming Windows Installer Errors in Windows 10 & 11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-easy-steps-on-how-to-create-a-new-apple-id-account-on-iphone-8-by-drfone-ios/"><u>In 2024, Easy Steps on How To Create a New Apple ID Account On iPhone 8</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-the-chromebook-video-editors-secret-running-windows-and-mac-apps-with-ease/"><u>In 2024, The Chromebook Video Editors Secret Running Windows and Mac Apps with Ease</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-top-5-best-microphones-for-4k-camera/"><u>2024 Approved  Top 5 Best Microphones for 4K Camera</u></a></li>
<li><a href="https://win11.techidaily.com/key-techniques-for-win10-blue-screen-resolution/"><u>Key Techniques for Win10 Blue Screen Resolution</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-window-pc-always-unlocked/"><u>Keep Your Window PC Always Unlocked</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-absence-of-rockalldll-in-windows-os/"><u>Fixes for Absence of Rockalldll in Windows OS</u></a></li>
<li><a href="https://discord-videos.techidaily.com/mastering-attention-grabbers-top-30-discord-titles/"><u>Mastering Attention-Grabbers  Top 30 Discord Titles</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-enhance-your-fb-with-iphonesandroids-favorite-tunes/"><u>[Updated] In 2024, Enhance Your FB with iPhones/Androids' Favorite Tunes</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-cutting-edge-tips-for-capturing-movies-on-everyday-tech/"><u>[Updated] In 2024, Cutting-Edge Tips for Capturing Movies on Everyday Tech</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-the-newest-viral-content-on-tiktok-today/"><u>[New] 2024 Approved  The Newest Viral Content on TikTok Today</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-controlling-installer-service-in-windows/"><u>Guide to Controlling Installer Service in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-shortcuts-next-to-the-power-button-on-windows-11/"><u>How to Add Shortcuts Next to the Power Button on Windows 11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-unleash-your-creativity-top-video-animation-apps-for-android-ios-and-ipados/"><u>Updated 2024 Approved Unleash Your Creativity Top Video Animation Apps for Android, iOS, and iPadOS</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-office-outlook-alerts-in-windows/"><u>Troubleshooting Non-Functional Office Outlook Alerts in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-a-perfect-replica-of-your-drive/"><u>How to Make a Perfect Replica of Your Drive</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-xiaomi-14-ultra-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Xiaomi 14 Ultra Quickly | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/from-vanished-panes-to-visible-windows-essential-steps-for-recovering-hidden-screens-6-ways/"><u>From Vanished Panes to Visible Windows: Essential Steps for Recovering Hidden Screens (6 Ways)</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-disruptions-preventing-unexpected-crashes-in-dwarf-fortress/"><u>Unraveling Disruptions: Preventing Unexpected Crashes in Dwarf Fortress</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-awaken-the-artist-within-selective-shots-for-inspiration/"><u>[Updated] In 2024, Awaken the Artist Within  Selective Shots for Inspiration</u></a></li>
<li><a href="https://win11.techidaily.com/personalized-pixels-designing-unique-displays-on-each-monitor-of-windows/"><u>Personalized Pixels: Designing Unique Displays on Each Monitor of Windows</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-pioneering-easy-audio-alterations-for-competitive-play/"><u>In 2024, Pioneering Easy Audio Alterations for Competitive Play</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-search-service-not-available-on-windows/"><u>Tackling Search Service Not Available on Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-12-passcode-without-computer-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 12 Passcode without Computer?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-atandt-apple-iphone-13-mini-with-3-methods-by-drfone-ios/"><u>In 2024, How to Unlock AT&T Apple iPhone 13 mini with 3 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-accessibility-features/"><u>Navigating Through Windows' Accessibility Features</u></a></li>
<li><a href="https://win11.techidaily.com/trouble-removing-epic-games-hub-from-windows-11-a-quick-guide/"><u>Trouble Removing Epic Games Hub From Windows 11: A Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-modify-indexer-in-windows/"><u>Step-by-Step: Modify Indexer in Windows</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-the-ultimate-list-of-internet-locales-that-promote-in-person-friendships/"><u>In 2024, The Ultimate List of Internet Locales That Promote In-Person Friendships</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/-deep-dive-into-the-top-9-youtube-downloader-apps-for-android-for-2024/"><u>[New] A Deep Dive Into the Top 9 YouTube Downloader Apps for Android for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-transforming-visuals-the-power-of-customized-luts/"><u>[Updated] In 2024, Transforming Visuals  The Power of Customized LUTs</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-honor-80-pro-straight-screen-edition-drfone-by-drfone-virtual/"><u>In 2024, 9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Honor 80 Pro Straight Screen Edition | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-android-fun-for-windows-users-through-google-play/"><u>Streamlining Android Fun for Windows Users Through Google Play</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-exploring-8-youtube-fitness-hacks-that-energize-audiences/"><u>[New] 2024 Approved  Exploring 8 YouTube Fitness Hacks That Energize Audiences</u></a></li>
<li><a href="https://win11.techidaily.com/swift-keystrokes-in-win-os-a-guide-to-eliminate-delay/"><u>Swift Keystrokes in WIN OS: A Guide to Eliminate Delay</u></a></li>
<li><a href="https://win11.techidaily.com/filter-irrelevant-notification-feedback-in-windows-11/"><u>Filter Irrelevant Notification Feedback in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/insight-into-windows-11s-new-automated-data-safeguarding/"><u>Insight Into Windows 11’S New Automated Data Safeguarding</u></a></li>
</ul></div>
