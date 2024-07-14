---
title: "Bypassing Glitch 0X80072746: A Fix Guide for Windows Mail"
date: 2024-07-13T11:00:58.282Z
updated: 2024-07-14T11:00:58.282Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Bypassing Glitch 0X80072746: A Fix Guide for Windows Mail"
excerpt: "This Article Describes Bypassing Glitch 0X80072746: A Fix Guide for Windows Mail"
keywords: Fix Glitch 0X80072746,Windows Mail Troubleshooting,Email Issues in Windows,Resolve WinMail Errors,Overcoming Glitch 72746,WinMail Performance Fixes,Optimize Windows Mail Sync
thumbnail: https://thmb.techidaily.com/5a612b69f151ee0b6ea165a5e0a8368a6294f13aca50623658d8bbb7241b81d0.jpg
---

## Bypassing Glitch 0X80072746: A Fix Guide for Windows Mail

 The Mail app error 0x80072746 often occurs when users try to access their newly received emails, and it indicates network-related issues within Windows. This error message typically points towards a problem with the mail server or the network connection.

 Below, we take a look at the different troubleshooting methods that can help fix this issue for good.

## 1\. Allow svchost.exe in the Firewall

 The 0x80072746 error in the Mail app commonly occurs when a third-party firewall interferes with a critical Windows program called svchost.exe.

 This process is responsible to host various essential services necessary for the proper functioning of your Windows operating system. Among these services, the Mail app heavily relies on svchost.exe to establish network connections and download messages.

 If you have installed a third-party security program on your computer, there is a possibility that it is mistakenly blocking svchost.exe. This might be preventing the Mail app from fetching or sending emails, leading to the 0x80072746 error.

 To address this issue, you can check your firewall settings and whitelist svchost.exe. Alternatively, you can [temporarily disable the security program](https://www.makeuseof.com/windows-features-error-0x80071a90/) and check if that fixes the problem.

![Disable antivirus in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-antivirus-windows.jpg)

 It's worth noting that the exact steps of performing this action can vary depending on the specific program you are using. Typically, this information is available in the application settings of the app.

## 2\. Modify VPN Settings

 Active VPNs can also interfere with the Mail app's ability to establish network connections, leading to the problem at hand.

 If you are using a VPN on your computer, you can try the following steps to troubleshoot the issue:

* **Disconnect from the VPN**: Temporarily disable the VPN and then try loading messages in the Mail app again. If this fixes the problem, it implies that VPN was causing the problem.
* **Whitelist Mail app or email server**: Launch the VPN settings and look to whitelist the Mail app or email server’s IP address to prevent VPN from interfering with the program’s network connections.
* **Modify VPN protocols or settings**: If it is essential to use the VPN while using the Mail app, you can modify the protocol and check if that makes any difference.

 Here is how you can modify the VPN settings to resolve the Mail app error:

1. Press the **Win** \+ **I** keys together to open the Settings app.
2. Choose **Network & Internet** \> **VPN**.  
![VPN settings in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/vpn-settings-windows.jpg)
3. Enable the **Allow VPN over metered network** option.  
![Allow VPN over metered network in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/vpn-over-metered-network.jpg)
4. Now, head over to the "Related settings" section and choose **Change adapter options**.
5. Right-click on your LAN (Wi-Fi) connectivity and choose **Properties** from the context menu.
6. Select **Internet Protocol Version 6 (TCP/PV6)** and click **OK** to save the changes.

 You can now close the Settings app and check if the issue is resolved.

## 3\. Set Up Your Account Manually

 Another reason behind the Mail error 0x80072746 is incorrect server settings and incompatibility with specific email providers, which typically occurs when you rely on the automatic setup process.

 You can eliminate these potential issues with the automatic configuration process by setting up your account manually.

 Therefore, if you previously configured your Mail account using the automatic setup process, you might want to try setting it up manually this time in order to bypass any errors or conflicts.

 Here is how you can do that:

1. Launch the Mail client and click on the **gear icon** at the bottom.
2. Choose **Manage Accounts**.  
![Manage accounts option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/manage-accounts.jpg)
3. Select the problematic email and choose **Delete account from this device** from the options available.  
![Delete the account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/delete-mail-app.jpg)
4. Confirm your action in the next window.
5. Once the email account is removed, launch the official website of your email provider and copy the manual settings for IMAP. If these settings are not available, choose POP3\.

1. Now, head back to the Mail client and launch the settings.
2. Head over to the Manage Account section and choose **Add account**.  
![Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-account.jpg)
3. Scroll down and choose **Advanced Setup**.  
![Choose Advanced setup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/advanced-setup-option.jpg)
4. Click on **Internet email** and enter the manual settings you copied earlier.  
![Click Internet email](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/internet-email-option.jpg)
5. Finally, click on **Sign in** and check if the issue is resolved.

## 4\. Update the Mail App

 Your Mail app might also be outdated, which is preventing it from being fully compatible with the latest email server configurations and security protocols, leading to the error at hand.

 To check if this is the case, you can head over to Microsoft Store and check for the pending updates that might be available for the Mail app. If you find any, take your time to install them and then check if the Mail app can display emails.

 Follow these steps to proceed:

1. Click on the **Microsoft Store icon** in the taskbar to launch the program.
2. Choose the **Library icon** in the bottom left pane.
3. In the following window, click on the **Get updates** button. This should display all the available updates for the installed apps. MS Store will begin to download them automatically.  
![The Get updates button in MS Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-get-updates-button.jpg)
4. Wait for the updates to download and check if the problem is resolved.

 While you are at it, we also recommend installing any system updates that might be available in the Settings app.

## 5\. Fix Corruption Issues Within the Mail App

 If updating the application did not help, there are also some other fixes that can help you resolve any corruption issues within the Mail app that might be leading to the problem. This involves [repairing and resetting the Mail application](https://www.makeuseof.com/mail-app-cant-get-mail-windows/).

 The Repair option attempts to fix any damaged or missing files that might be contributing to the error, while the Reset option will restore the default, error-free state of the application. It is important to note, however, that while these solutions are effective at fixing the underlying problem, you are likely to lose your settings and preferences within the Mail app.

## Multiple Ways to Fix the Windows Mail App

 Encountering issues with the Mail app can be incredibly frustrating, especially if you rely on it for your important work. Hopefully, the solutions listed above will help you fix the 0x80072746 error once and for all.

 To avoid problems like this from occurring in the future, we recommend keeping your Mail app up-to-date and whitelisting it in the firewall as well as the VPN.

 Below, we take a look at the different troubleshooting methods that can help fix this issue for good.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-essential-techniques-for-saving-lol-games/"><u>[New] In 2024, Essential Techniques for Saving LOL Games</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-unbrick-a-dead-realme-c33-2023-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Realme C33 2023 | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-your-oppo-find-n3-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>How to Mirror Your Oppo Find N3 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-wonders-unlock-the-secrets-of-measuring-ethernet-speeds/"><u>Windows Wonders: Unlock the Secrets of Measuring Ethernet Speeds</u></a></li>
<li><a href="https://win11.techidaily.com/rethink-reviving-windows-or-beyond/"><u>Rethink Reviving: Windows or Beyond?</u></a></li>
<li><a href="https://win11.techidaily.com/make-your-windows-11-desktop-sparkle-with-lively-wallpaper-art/"><u>Make Your Windows 11 Desktop Sparkle with Lively Wallpaper Art</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-transitioning-from-sierra-to-legacy-os-el-capitan/"><u>[New] Transitioning From Sierra To Legacy OS - El Capitan</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-step-by-step-guide-to-android-movie-upturning/"><u>[New] Step-by-Step Guide to Android Movie Upturning</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-pc-power-for-distributed-video-conversion-by-tdarr/"><u>Optimize PC Power for Distributed Video Conversion by Tdarr</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fixing-foneazy-mockgo-not-working-on-xiaomi-mix-fold-3-drfone-by-drfone-virtual-android/"><u>In 2024, Fixing Foneazy MockGo Not Working On Xiaomi Mix Fold 3 | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/pixel-perfection-combining-computer-photos/"><u>Pixel Perfection  Combining Computer Photos</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-addressing-windows-non-response-to-powershell-command/"><u>Steps for Addressing Windows Non-Response to PowerShell Command</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-mastering-igtv-a-comprehensive-guide-for-beginners/"><u>[New] 2024 Approved  Mastering IGTV  A Comprehensive Guide for Beginners</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-boot-failures-8-fixes-for-virtual-machines-on-wm11os/"><u>Overcome Boot Failures: 8 Fixes for Virtual Machines on WM11OS</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-quick-strategies-logging-lectures-in-ppt/"><u>[New] In 2024, Quick Strategies  Logging Lectures in PPT</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-reliable-voice-commands-for-valorant-gaming/"><u>Ensuring Reliable Voice Commands for Valorant Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-the-gallery-in-file-explorer-in-windows-11/"><u>How to Enable the Gallery in File Explorer in Windows 11</u></a></li>
<li><a href="https://fox-access.techidaily.com/avoid-complexity-easy-video-edits-on-windows-10-for-everyone/"><u>Avoid Complexity  Easy Video Edits on Windows 10 for Everyone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/selecting-perfect-unboxing-tunes-a-guide-for-2024/"><u>Selecting Perfect Unboxing Tunes  A Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/speed-sector-mastering-windows-methods-for-adapter-velocity-check/"><u>Speed Sector: Mastering Windows Methods for Adapter Velocity Check</u></a></li>
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-oneplus-nord-n30-5g-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your OnePlus Nord N30 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-overcoming-geforce-x0001-on-w10w11-pcs/"><u>Quick Tips: Overcoming GeForce X0001 on W10/W11 PCs</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-mov-files-of-ace-2v-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and MOV files of Ace 2V?</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-for-re-establishing-managed-status-on-windows-11/"><u>Comprehensive Guide for Re-Establishing Managed Status on Windows 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-alternate-avenues-10-great-games-like-gta-v/"><u>[New] Alternate Avenues  10 Great Games Like GTA V</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-typing-experience-changing-layouts-on-windows-11/"><u>Tailoring Your Typing Experience: Changing Layouts on Windows 11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-everything-you-need-to-know-about-unlocked-iphone-12-drfone-by-drfone-ios/"><u>In 2024, Everything You Need To Know About Unlocked iPhone 12 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-blueprint-for-beginning-your-steam-gamers-journey-anew/"><u>The Blueprint for Beginning Your Steam Gamers' Journey Anew</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-dxgi-error-by-reattaching-devices-in-windows/"><u>Bypassing DXGI ERROR by Reattaching Devices in Windows</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-2024-approved-8-excellent-video-and-photo-mergers-on-desktopmobileonline/"><u>New 2024 Approved 8 Excellent Video and Photo Mergers on Desktop/Mobile/Online</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-non-functional-email-banners-for-office-users/"><u>Reviving Non-Functional Email Banners for Office Users</u></a></li>
<li><a href="https://win11.techidaily.com/blue-screen-demystified-how-to-resolve-windows-crashes-quickly/"><u>Blue Screen Demystified: How To Resolve Windows Crashes Quickly</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-unlocking-youtubes-potential-a-detailed-guide-on-tracking-earnings-and-audiences/"><u>[New] Unlocking YouTube's Potential  A Detailed Guide on Tracking Earnings and Audiences</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-navigating-android-video-calls-effortlessly/"><u>[New] 2024 Approved  Navigating Android Video Calls Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-requires-privilege-error-code-0x80070522-in-windows-devices/"><u>Eradicating Requires Privilege Error (Code 0X80070522) in Windows Devices</u></a></li>
<li><a href="https://extra-skills.techidaily.com/picture-perfect-pieces-diy-collage-masterclass-for-2024/"><u>Picture Perfect Pieces  DIY Collage Masterclass for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unhindered-administrator-experience-via-terminals-every-time/"><u>Unhindered Administrator Experience via Terminals Every Time</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/2024-approved-overdub-voice-with-ai-virbo-at-its-finest/"><u>2024 Approved Overdub Voice With AI Virbo At Its Finest</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-error-x0001-in-windows-devices/"><u>Strategies for Overcoming Error X0001 in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-hurdle-of-windows-laptop-lag-on-dual-screens/"><u>Overcoming the Hurdle of Window's Laptop Lag on Dual Screens</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-11-writable-error-fix-it-now/"><u>Unraveling Windows 11' Writable Error: Fix It Now</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-keyboard-efficiency-via-powertoys/"><u>Accelerate Keyboard Efficiency via PowerToys</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-navigate-your-gaming-world-with-steams-switch-controller/"><u>[New] In 2024, Navigate Your Gaming World with Steam's Switch Controller</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-uncertainty-check-cpu-generation-on-windows-8-ways/"><u>Avoid Uncertainty – Check CPU Generation on Windows (8 Ways)</u></a></li>
<li><a href="https://win11.techidaily.com/adapting-the-search-function-in-windows-11-for-you/"><u>Adapting the Search Function in Windows 11 for You</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-to-reopen-stuck-adobe-photoshop-in-windows/"><u>Guidelines to Reopen Stuck Adobe Photoshop in Windows</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-streaming-facebook-movies-via-apple-tv/"><u>In 2024, Streaming Facebook Movies via Apple TV</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-the-technologies-in-microsofts-ai-hub/"><u>Demystifying the Technologies in Microsoft's AI Hub</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/transformative-visuals-the-pixiz-process-for-photo-video-fusion/"><u>Transformative Visuals  The Pixiz Process for Photo-Video Fusion</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-greyed-out-display-changes-on-windows-system/"><u>Eliminate Greyed-Out Display Changes on Windows System</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-light-it-right-elevating-your-youtube-video-presence/"><u>[New] In 2024, Light It Right  Elevating Your YouTube Video Presence</u></a></li>
<li><a href="https://win11.techidaily.com/intro-to-windows-canary-your-security-ally/"><u>Intro to Windows Canary: Your Security Ally</u></a></li>
</ul></div>
