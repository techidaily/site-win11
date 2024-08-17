---
title: "Combatting Windows Mail Glitches: The 0X80072746 Fix Guide"
date: 2024-08-15T23:41:42.253Z
updated: 2024-08-16T23:41:42.253Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Combatting Windows Mail Glitches: The 0X80072746 Fix Guide"
excerpt: "This Article Describes Combatting Windows Mail Glitches: The 0X80072746 Fix Guide"
keywords: WinMailGlitchSolve,0X80072746FixGuide,MailGlitchResolution,WindowsEmailFixTips,GlitchFreeWinMail,Fix0XMailIssue,ResolveWindowsMailError
thumbnail: https://thmb.techidaily.com/7f531620a49852bbff7e687b5f3193b68bdfdcb0db935514f90e93325010d261.jpg
---

## Combatting Windows Mail Glitches: The 0X80072746 Fix Guide

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
<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Enable the **Allow VPN over metered network** option.  
![Allow VPN over metered network in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/vpn-over-metered-network.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Confirm your action in the next window.
5. Once the email account is removed, launch the official website of your email provider and copy the manual settings for IMAP. If these settings are not available, choose POP3\.

1. Now, head back to the Mail client and launch the settings.
2. Head over to the Manage Account section and choose **Add account**.  
![Add account option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-account.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Scroll down and choose **Advanced Setup**.  
![Choose Advanced setup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/advanced-setup-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-tips.techidaily.com/024-approved-broadcasting-strategies-for-youtube-facebook-twitch-and-others/"><u>[New] 2024 Approved  Broadcasting Strategies for YouTube, Facebook, Twitch, and Others</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-hide-faces-in-photos-efficiently-with-these-tools/"><u>[New] Hide Faces in Photos Efficiently with These Tools</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-broadcasting-with-gopro-tips-for-facebookperiscope-integration/"><u>[New] In 2024, Broadcasting with GoPro  Tips for Facebook/Periscope Integration</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-elevate-your-gaming-experience-mastering-steam-recordings/"><u>[New] In 2024, Elevate Your Gaming Experience - Mastering Steam Recordings</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-finding-the-right-angle-for-your-fb-videos/"><u>[New] In 2024, Finding the Right Angle for Your FB Videos</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-20-timeless-anime-themes-making-a-mark-on-tiktok-for-2024/"><u>[Updated] 20 Timeless Anime Themes Making a Mark on TikTok for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-extract-your-favorites-best-playlist-tools-reviewed-and-rated/"><u>[Updated] 2024 Approved  Extract Your Favorites  Best Playlist Tools Reviewed and Rated</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-top-10-tips-for-excellent-xbox-game-playbacks/"><u>[Updated] In 2024, Top 10 Tips for Excellent Xbox Game Playbacks</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-social-synergy-blueprint-for-ig-and-tiktok-pairing/"><u>[Updated] Social Synergy Blueprint for IG & TikTok Pairing</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-your-essential-top-10-playlist/"><u>[Updated] Your Essential Top 10 Playlist</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-ultimate-tips-to-streamline-your-ipad-screen-saving/"><u>2024 Approved  Ultimate Tips to Streamline Your iPad Screen Saving</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-blink-quick-fixes-for-input-lag-on-latest-microsoft-os/"><u>Beat the Blink: Quick Fixes for Input Lag on Latest Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-audiovisual-capabilities-through-new-driver-installation/"><u>Boosting Windows Audiovisual Capabilities Through New Driver Installation</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-generations-old-games-with-dosbox-x/"><u>Bridging Generations: Old Games with DOSBox-X</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/coding-command-central-how-to-program-a-one-stop-remote-control-gadget/"><u>Coding Command Central: How to Program a One-Stop Remote Control Gadget</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-and-fixing-the-frozen-resource-monitor-app-in-win11/"><u>Diagnosing and Fixing the Frozen Resource Monitor App in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-the-source-of-windows-parse-error-0xc00ce556/"><u>Dissecting the Source of Windows' Parse Error 0xC00CE556</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/effortless-twitpic-integration-a-video-guide-for-2024/"><u>Effortless Twitpic Integration  A Video Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-workflow-adding-tasks-to-file-context-menus/"><u>Elevate Your Workflow: Adding Tasks to File Context Menus</u></a></li>
<li><a href="https://win11.techidaily.com/enable-microphone-and-camera-via-app-guard-in-windows-11/"><u>Enable Microphone & Camera via App Guard in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enrich-your-galaxy-experience-utilizing-the-dex-app-in-windows/"><u>Enrich Your Galaxy Experience: Utilizing the DeX App in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/esd-file-transformation-mastery-your-pathway-to-windows-iso-success/"><u>ESD File Transformation Mastery: Your Pathway to Windows ISO Success</u></a></li>
<li><a href="https://win11.techidaily.com/fix-slow-download-issues-in-steam-on-windows-platform/"><u>Fix Slow Download Issues in Steam on Windows Platform</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-absent-windows-notification-icons/"><u>Fixes for Absent Windows Notification Icons</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-an-application-not-installed-via-microsofts-store/"><u>Fixing an Application Not Installed via Microsoft's Store</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-installer-access-rights-shortcomings/"><u>Fixing Windows Installer Access Rights Shortcomings</u></a></li>
<li><a href="https://win11.techidaily.com/from-emulator-to-operating-system-windows-for-steam-deck/"><u>From Emulator to Operating System: Windows for Steam Deck</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-locked-for-security-reasons-from-iphone-8-plus-find-the-best-solution-here-by-drfone-ios/"><u>In 2024, Apple ID Locked for Security Reasons From iPhone 8 Plus? Find the Best Solution Here</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-vivo-s17t-drfone-by-drfone-virtual-android/"><u>In 2024, Will Pokémon Go Ban the Account if You Use PGSharp On Vivo S17t | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-file-explorer-running-with-helpful-windows-11-tricks/"><u>Keep Your File Explorer Running with Helpful Windows 11 Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/keyboard-proficiency-the-path-to-mastering-project/"><u>Keyboard Proficiency: The Path to Mastering Project</u></a></li>
<li><a href="https://win11.techidaily.com/1719286453674-library-installation/"><u>Library Installation:</u></a></li>
<li><a href="https://some-guidance.techidaily.com/mastering-iphone-hdr-imaging-techniques-for-2024/"><u>Mastering iPhone HDR Imaging Techniques for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-adding-folders-without-delays-in-windows-onedrive/"><u>Mastering the Art of Adding Folders without Delays in Windows OneDrive</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-app-changes-in-the-latest-windows-11-update/"><u>Navigating App Changes in the Latest Windows 11 Update</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unable-to-detect-camera-in-win11/"><u>Overcoming Unable to Detect Camera in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/preventive-measures-for-windows-safescreensaver-alteration/"><u>Preventive Measures for Windows SafeScreensaver Alteration</u></a></li>
<li><a href="https://win11.techidaily.com/pro-guide-how-to-locate-and-setup-shortcuts-near-win11s-power-icon/"><u>Pro Guide: How to Locate & Setup Shortcuts Near Win11's Power Icon</u></a></li>
<li><a href="https://win11.techidaily.com/reset-and-reboot-your-way-back-into-the-ms-store-windows-11/"><u>Reset & Reboot Your Way Back Into the MS Store (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-group-policy-management-in-windows-108/"><u>Simplifying Group Policy Management in Windows 10/8</u></a></li>
<li><a href="https://win11.techidaily.com/six-easy-steps-to-knowing-the-model-behind-your-pc-windows-edition/"><u>Six Easy Steps To Knowing The Model Behind Your PC Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-your-vm-workflow-6-expert-tips-for-windows-users/"><u>Supercharge Your VM Workflow: 6 Expert Tips for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/tech-guide-uninstalling-the-microsoft-store/"><u>Tech Guide: Uninstalling the Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/terminal-insight-discover-public-ip-in-windows-1110/"><u>Terminal Insight: Discover Public IP in Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/triumph-in-speed-mastering-double-click-on-windows-pc/"><u>Triumph in Speed: Mastering Double-Click on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-program-install-pathways-in-windows/"><u>Unveiling Program Install Pathways in Windows</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/unveiling-the-top-8-instagram-ae-design-choices-for-2024/"><u>Unveiling the Top 8 Instagram AE Design Choices for 2024</u></a></li>
</ul></div>
