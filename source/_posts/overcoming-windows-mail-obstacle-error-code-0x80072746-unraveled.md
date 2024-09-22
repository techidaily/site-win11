---
title: "Overcoming Windows Mail Obstacle: Error Code 0X80072746 Unraveled"
date: 2024-09-17T00:49:00.363Z
updated: 2024-09-21T18:17:26.382Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overcoming Windows Mail Obstacle: Error Code 0X80072746 Unraveled"
excerpt: "This Article Describes Overcoming Windows Mail Obstacle: Error Code 0X80072746 Unraveled"
keywords: Fixing Windows Mail Errors,Resolving MSN Email Issue,Clearing Error X80072746,Dealing with Mail Error Code,Troubleshooting Office 365 Emails,Windows Mail Problem-Solving,Unlocking Mail Obstacle Error
thumbnail: https://thmb.techidaily.com/7989d193b701c6c4112afd659656de357f20d61f1ee9fa4b40235e3cbfd62f11.jpg
---

## Overcoming Windows Mail Obstacle: Error Code 0X80072746 Unraveled

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

<!-- affiliate ads begin -->
<span id="1770526">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770526.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770526">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770526.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770526%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770526/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 While you are at it, we also recommend installing any system updates that might be available in the Settings app.

## 5\. Fix Corruption Issues Within the Mail App

 If updating the application did not help, there are also some other fixes that can help you resolve any corruption issues within the Mail app that might be leading to the problem. This involves [repairing and resetting the Mail application](https://www.makeuseof.com/mail-app-cant-get-mail-windows/).

 The Repair option attempts to fix any damaged or missing files that might be contributing to the error, while the Reset option will restore the default, error-free state of the application. It is important to note, however, that while these solutions are effective at fixing the underlying problem, you are likely to lose your settings and preferences within the Mail app.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896505/19272" target="_top" id="1896505">
  <img src="//a.impactradius-go.com/display-ad/19272-1896505" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896505/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://snapchat-videos.techidaily.com/new-hot-pursuit-of-snaps-tactics-for-uninterrupted-streaks-for-2024/"><u>[New] Hot Pursuit of Snaps - Tactics for Uninterrupted Streaks for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-video-conference-to-youtube-broadcast-google-meet-explained/"><u>[New] In 2024, From Video Conference to Youtube Broadcast Google Meet Explained</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-10-best-tiktok-filters-to-make-your-videos-stand-out/"><u>[Updated] 2024 Approved 10 Best TikTok Filters to Make Your Videos Stand Out</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-flawless-visual-shifts-for-filmmakers-for-2024/"><u>[Updated] Flawless Visual Shifts for Filmmakers for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-walking-deadlines-the-ultimate-selection-of-excellent-zombie-games/"><u>[Updated] In 2024, Walking Deadlines The Ultimate Selection of Excellent Zombie Games</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-writing-that-grabs-and-grips-podcast-description-tactics/"><u>2024 Approved Writing That Grabs and Grips Podcast Description Tactics</u></a></li>
<li><a href="https://some-guidance.techidaily.com/easy-steps-to-transform-your-mkv-files-into-avi-format-on-both-windows-and-macos/"><u>Easy Steps to Transform Your MKV Files Into AVI Format on Both Windows & macOS</u></a></li>
<li><a href="https://media-tips.techidaily.com/enhanced-youtube-multiview-experience-now-available-for-nfl-sunday-ticket-fans/"><u>Enhanced YouTube MultiView Experience Now Available for NFL Sunday Ticket Fans</u></a></li>
<li><a href="https://win11.techidaily.com/simple-steps-transforming-videos-into-avc-format-with-ease/"><u>Simple Steps: Transforming Videos Into AVC Format with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-converting-your-ipad-videos-into-mp4-format/"><u>Step-by-Step Guide: Converting Your iPad Videos Into MP4 Format</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-mastering-the-basics-of-free-mpeg-video-converter-factory/"><u>Step-by-Step Guide: Mastering the Basics of Free MPEG Video Converter Factory</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-removing-custom-kodi-modifications-and-restoring-default-settings/"><u>Step-by-Step Guide: Removing Custom Kodi Modifications & Restoring Default Settings</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-setting-up-the-latest-enzo-plugins-on-kodi-leia-and-krypton-for-reliable-live-tv/"><u>Step-by-Step Guide: Setting Up the Latest Enzo Plugins on Kodi (Leia and Krypton) for Reliable Live TV</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-list-of-top-11-youtube-downloaders-latest-version/"><u>The Ultimate List of Top 11 YouTube Downloaders - Latest Version</u></a></li>
<li><a href="https://hardware-help.techidaily.com/unveiling-the-excellence-an-in-depth-look-at-the-asus-rog-swift-pg32ucdp-oled-display/"><u>Unveiling the Excellence: An In-Depth Look at the Asus ROG Swift PG32UCDP OLED Display</u></a></li>
</ul></div>

