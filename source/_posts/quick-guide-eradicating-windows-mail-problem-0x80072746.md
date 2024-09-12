---
title: "Quick Guide: Eradicating Windows Mail Problem 0X80072746"
date: 2024-09-11T09:32:12.153Z
updated: 2024-09-12T09:32:12.153Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Guide: Eradicating Windows Mail Problem 0X80072746"
excerpt: "This Article Describes Quick Guide: Eradicating Windows Mail Problem 0X80072746"
keywords: WinmailIssueGuide,EliminateWinMailError,ResolveWindowsMailFault,QuickWinMailTroubleshoot,X80072746WindowsRepair,FixZeroX80072746Mail,WindowsEmailProblemSolve
thumbnail: https://thmb.techidaily.com/b940b6b0f5ea7e32cad1821c53c7dd63eece1d15c1851d2a65f8ffeb1e28c4c2.jpg
---

## Quick Guide: Eradicating Windows Mail Problem 0X80072746

 The Mail app error 0x80072746 often occurs when users try to access their newly received emails, and it indicates network-related issues within Windows. This error message typically points towards a problem with the mail server or the network connection.

 Below, we take a look at the different troubleshooting methods that can help fix this issue for good.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Allow svchost.exe in the Firewall

 The 0x80072746 error in the Mail app commonly occurs when a third-party firewall interferes with a critical Windows program called svchost.exe.

 This process is responsible to host various essential services necessary for the proper functioning of your Windows operating system. Among these services, the Mail app heavily relies on svchost.exe to establish network connections and download messages.

 If you have installed a third-party security program on your computer, there is a possibility that it is mistakenly blocking svchost.exe. This might be preventing the Mail app from fetching or sending emails, leading to the 0x80072746 error.

 To address this issue, you can check your firewall settings and whitelist svchost.exe. Alternatively, you can [temporarily disable the security program](https://www.makeuseof.com/windows-features-error-0x80071a90/)and check if that fixes the problem.

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

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137973/21526" target="_top" id="2137973">
  <img src="//a.impactradius-go.com/display-ad/21526-2137973" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137973/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Allow VPN over metered network in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/vpn-over-metered-network.jpg)
4. Now, head over to the "Related settings" section and choose **Change adapter options**.
5. Right-click on your LAN (Wi-Fi) connectivity and choose **Properties** from the context menu.
6. Select **Internet Protocol Version 6 (TCP/PV6)** and click **OK** to save the changes.

 You can now close the Settings app and check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137229/26400" target="_top" id="2137229">
  <img src="//a.impactradius-go.com/display-ad/26400-2137229" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137229/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Set Up Your Account Manually

 Another reason behind the Mail error 0x80072746 is incorrect server settings and incompatibility with specific email providers, which typically occurs when you rely on the automatic setup process.

 You can eliminate these potential issues with the automatic configuration process by setting up your account manually.

 Therefore, if you previously configured your Mail account using the automatic setup process, you might want to try setting it up manually this time in order to bypass any errors or conflicts.

 Here is how you can do that:

1. Launch the Mail client and click on the **gear icon** at the bottom.
2. Choose **Manage Accounts**.  
![Manage accounts option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/manage-accounts.jpg)
3. Select the problematic email and choose **Delete account from this device** from the options available.  

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139114/17108" target="_top" id="2139114">
  <img src="//a.impactradius-go.com/display-ad/17108-2139114" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139114/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<span id="1912746">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1912746.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20231-1912746">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1912746.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmindmanager.sjv.io%2Fc%2F5597632%2F1912746%2F20231'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1912746/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="864" height="1296" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://wigfever.sjv.io/c/5597632/2014854/22899" target="_top" id="2014854">
  <img src="//a.impactradius-go.com/display-ad/22899-2014854" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014854/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Fix Corruption Issues Within the Mail App

 If updating the application did not help, there are also some other fixes that can help you resolve any corruption issues within the Mail app that might be leading to the problem. This involves [repairing and resetting the Mail application](https://www.makeuseof.com/mail-app-cant-get-mail-windows/).

 The Repair option attempts to fix any damaged or missing files that might be contributing to the error, while the Reset option will restore the default, error-free state of the application. It is important to note, however, that while these solutions are effective at fixing the underlying problem, you are likely to lose your settings and preferences within the Mail app.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129042/19576" target="_top" id="2129042">
  <img src="//a.impactradius-go.com/display-ad/19576-2129042" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129042/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Multiple Ways to Fix the Windows Mail App

 Encountering issues with the Mail app can be incredibly frustrating, especially if you rely on it for your important work. Hopefully, the solutions listed above will help you fix the 0x80072746 error once and for all.

 To avoid problems like this from occurring in the future, we recommend keeping your Mail app up-to-date and whitelisting it in the firewall as well as the VPN.

 Below, we take a look at the different troubleshooting methods that can help fix this issue for good.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/new-dive-into-effortless-gif-sharing-in-snapchats-guide/"><u>[New] Dive Into Effortless Gif Sharing in Snapchat's Guide</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-elevate-your-marketing-game-high-roi-through-animated-fb-advertising/"><u>[New] Elevate Your Marketing Game High ROI Through Animated FB Advertising</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-quick-quirky-and-funny-creating-memes-anytime-for-2024/"><u>[New] Quick, Quirky, and Funny Creating Memes Anytime for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-top-snapchat-content-strategies-to-stand-out-for-2024/"><u>[New] Top Snapchat Content Strategies to Stand Out for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-instant-tv-viewing-of-popular-facebook-feeds-for-2024/"><u>[Updated] Instant TV Viewing of Popular Facebook Feeds for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-essentials-for-transforming-your-google-meet-into-youtube-live/"><u>[Updated] The Essentials for Transforming Your Google Meet Into Youtube Live</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-unveil-the-secrets-of-exceptional-tiktok-intro-videos-mac-for-2024/"><u>[Updated] Unveil the Secrets of Exceptional TikTok Intro Videos (Mac) for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/addressing-and-fixing-invalid-inf-installation-sections/"><u>Addressing and Fixing Invalid INF Installation Sections</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/banish-flash-on-win11-display/"><u>Banish Flash on Win11 Display</u></a></li>
<li><a href="https://win11.techidaily.com/cross-device-compatibility-windows-app-supports-apple-and-desktop-oses/"><u>Cross-Device Compatibility: Windows App Supports Apple and Desktop OSes</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-network-protocols-in-windows/"><u>Demystifying Network Protocols in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/dxgidll-gone-unveiling-win11-remedy-steps/"><u>Dxgi.dll Gone? Unveiling Win11 Remedy Steps</u></a></li>
<li><a href="https://tech-hub.techidaily.com/easy-guide-setting-up-your-epson-printers-wi-fi-connection/"><u>Easy Guide: Setting Up Your Epson Printer's Wi-Fi Connection</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-root-of-windows-defender-error-0x80004004/"><u>Eliminating the Root of Windows Defender Error 0X80004004</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-for-windows-11-dolby-atmos-setup/"><u>Essential Guide for Windows 11 Dolby Atmos Setup</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expertly-selected-best-ios-mail-applications-our-preferred-choices/"><u>Expertly Selected Best iOS Mail Applications - Our Preferred Choices</u></a></li>
<li><a href="https://win11.techidaily.com/getting-acquainted-with-windows-11s-widgets/"><u>Getting Acquainted with Windows 11'S Widgets</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-determine-if-someone-has-read-your-gmail-messages-a-step-by-step-tutorial/"><u>How to Determine If Someone Has Read Your Gmail Messages: A Step-by-Step Tutorial</u></a></li>
<li><a href="https://network-issues.techidaily.com/how-to-fix-youtube-green-screen-issues/"><u>How To Fix YouTube Green Screen Issues</u></a></li>
<li><a href="https://win11.techidaily.com/is-google-chrome-not-opening-on-windows-11-try-these-fixes/"><u>Is Google Chrome Not Opening on Windows 11? Try These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-taskbar-features-in-windows-11/"><u>Mastering Taskbar Features in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/nativity-scene-delivering-apps-via-microsofts-hub/"><u>Nativity Scene: Delivering Apps via Microsoft's Hub</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-windows-11-taskbar-sizing-techniques/"><u>Perfect Windows 11 Taskbar Sizing Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/recovering-lost-tabs-in-navigator-interface/"><u>Recovering Lost Tabs in Navigator Interface</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-windows-11s-media-app-a-fix-guide/"><u>Reviving Windows 11'S Media App: A Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-local-device-naming-clashes-with-5-steps-for-windows/"><u>Sidestep Local Device Naming Clashes with 5 Steps for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-a-harmonious-windows-desktop/"><u>Strategies for a Harmonious Windows Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-unidentified-status-messages-in-windows-applications/"><u>Tackling 'Unidentified' Status Messages in Windows Applications</u></a></li>
<li><a href="https://win11.techidaily.com/taming-the-non-empty-directory-error-in-windows-11-and-win11-code-0x80070091/"><u>Taming the Non-Empty Directory Error in Windows 11 & Win11 (Code: 0X80070091)</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-art-of-photo-to-video-with-accompaniment-sounds/"><u>The Art of Photo-to-Video with Accompaniment Sounds</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steps-for-source-unavailable-errors-in-windows-1011/"><u>Troubleshooting Steps for “Source Unavailable” Errors in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-magic-behind-16gb-memory-in-windows-pcs/"><u>Unveiling the Magic Behind 16GB Memory in Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-select-and-modify-your-screensaver/"><u>Windows 11: Select and Modify Your Screensaver</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    