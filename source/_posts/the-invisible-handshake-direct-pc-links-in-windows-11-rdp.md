---
title: "The Invisible Handshake: Direct PC Links in Windows 11 RDP"
date: 2024-08-15T23:38:28.303Z
updated: 2024-08-16T23:38:28.303Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes The Invisible Handshake: Direct PC Links in Windows 11 RDP"
excerpt: "This Article Describes The Invisible Handshake: Direct PC Links in Windows 11 RDP"
keywords: Windows RDP Connections,PC Direct Sharing,RDP Windows Linking,Invisible Network Share,Remote Desktop Protocol,Win11 Secure Connection,Digital Handshake Tech
thumbnail: https://thmb.techidaily.com/0244557d86d8e1a27dc054dedba4a1385b1696e504c943e408d092d2c07266c8.jpg
---

## The Invisible Handshake: Direct PC Links in Windows 11 RDP

 Remote Desktop connections let two computers share data and applications online. It's handy for accessing files and programs from afar. Although security measures often require passwords. But what if you could connect to your remote desktop without it? This article explains how to connect to a remote desktop without a password in Windows 11\.

## 1\. Using Group Policy

 A group policy editor is a tool administrators use to set user access control policies. You can use this feature to disable passwords. Make sure you are running Windows Pro, Enterprise, or Education Edition.

 Note that Windows Home Edition does not support Group Policy because it is a non-domain system. However, you can enable Local Group Policy Editor on your Windows Home device.

 To allow remote desktop connections without passwords, follow these steps:

1. Press **Win + R** on your keyboard to [open the Run dialogue box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **gpedit.msc** in the text field box and hit Enter. The Local Group Policy Editor will open as a result.
3. In the left-hand navigation pane, expand the **Computer Configuration** policy sets.
4. Then navigate to the following folders:  
Windows Settings > Security Settings > Local Policies > Security Options
5. In the right panel, double-click on **Accounts: Limit local account use of blank passwords to console logon only**. The Properties window will pop up.  
![Remote desktop connections without a password Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/remote-desktop-connections-without-a-password-using-group-policy.jpg)
6. Choose **Disabled** and click **OK** to save the changes.  
![Limit local account use of blank passwords to console logon only](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/limit-local-account-use-of-blank-passwords-to-console-logon-only.jpg)

 This will allow users to connect remotely without using a password. If you want to enable the password prompt again, just follow the same steps and select **Enabled** instead of **Disabled** in the last step.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Using Security Policy

 Security policies are another way to connect remotely without passwords. This tool is similar to the group policy editor but specific to the local computer. This means any changes you make to the local security policy will only apply to the local computer while group policies are domain-wide.

 To make passwordless remote connections using a security policy, follow these steps:

1. Press **Win + S** on your keyboard to open the Windows Search.
2. Type **secpol.msc** in the search bar and hit Enter.
3. Select the result from the top of the list to open the Local Security Policy.
4. In the left-hand navigation pane, navigate to the following folders:  
Security Settings > Local Policies > Security Options
5. Now move to the right panel and double-click on **Accounts: Limit local account use of blank passwords to console logon only**. This will open the Properties window for this policy.  
![Use Security Policy to Connect Remote Desktop Without a Password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-security-policy-to-connect-remote-desktop-without-a-password.jpg)
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Select **Disabled** and click on **Apply > OK** to save changes.

 Once you save this setting, remote connections are possible without passwords.

 To enable the password prompt again, go through the same steps and double-click on the policy. When the Properties window opens, select **Enabled**. Click **Apply** \> **OK** to save the changes.

## 3\. Using Registry Editor

 When running Windows Home, use the registry editor instead of the group policy editor. The registry editor is a hierarchical database that stores system configuration and settings.

 However, be careful when using it as one mistake can permanently damage your system and cause data loss. Therefore, you always [back up your registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making changes.

 To make remote desktop connections without a password on Windows Home, follow these steps:

1. Click on Start and type **regedit** in the search box.
2. Select the **Registry Editor** option from the results list.
3. If UAC (User Account Control) pops up, click on **Yes** to grant permission. This will open the Registry Editor on your screen.
4. In the left-hand sidebar, navigate to the following registry key:  
HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa
5. In the right panel, double-click on **LimitBlankPasswordUse**. The Edit DWORD window will pop up.  
![Make remote desktop connections using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/make-remote-desktop-connections-using-registry.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Change the **Value data** field to **0** and click **OK** to save changes.

 This will prevent Windows from requiring a password when connecting remotely.

 If you ever want to re-enable the password prompt, navigate back to the same registry key and change the value data field to **1**. Now close the Registry Editor and you are ready to connect remotely without a password.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
## 4\. Using Command Prompt

 If you prefer the command line over graphical tools, try this method. It works the same way as the registry editor but is done through the command prompt. Since this could be difficult for novice users, double-check each step. This ensures you don't make mistakes and damage your system.

 To enable passwordless remote connections using the command prompt, follow these steps:

1. Right-click on **Start** and select **Run** from the menu.
2. Type **cmd** in the text field and press **Ctrl + Shift + Enter** simultaneously.
3. If the UAC dialog box pops up, click **Yes** to grant permission. This will open the Command Prompt with administrative privileges.  
![Make Passwordless Remote Desktop Connections Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/make-passwordless-remote-desktop-connections-using-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Now type the following command and hit Enter.  
Reg add “HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa” /v LimitBlankPasswordUse /t REG_DWORD /d 0 /f

 Running this command will change the value data field to **0** and disable the remote password prompt.

 If you ever want to re-enable the password prompt, run the same command but replace the **0** at the end with a **1**. This way the command will look like this.

Reg add “HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa” /v LimitBlankPasswordUse /t REG_DWORD /d 1 /f

## 5\. Using a Reg File

 If you're not good at editing with the registry editor, create a .reg file instead. The .reg files are basically text files with predefined instructions. When executed, they change the registry and apply settings automatically.

 To create a .reg file, follow these steps:

1. Open Notepad (see [how to open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) for methods).
2. Copy and paste the following:  
`Windows Registry Editor Version 5.00  

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa  
"LimitBlankPasswordUse"=dword:00000000`
3. Now click **File** \> **Save as** and set the file type to **All files**.  
![Create a Reg File Connect Remote Desktop Without a Password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-a-reg-file-connect-remote-desktop-without-a-password.jpg)
4. Name the file **no-password.reg** and save it to your desktop.
5. Double-click on the file to execute it and apply the settings automatically.

 Your remote connections will now run without passwords. To re-enable the password prompt, create another text file with the following code:

`Windows Registry Editor Version 5.00  
  
HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa  
"LimitBlankPasswordUse"=dword:00000001`

 Now save the file as **enabled\_password.reg** and double-click it to apply the changes.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Enjoy Password-Free Remote Access

 Read this guide to access remote desktop without remembering and entering passwords each time. This creates a password-free experience, making it easier to connect with coworkers or friends whenever required.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-recollection-runway-your-easy-path-to-story-archives/"><u>[New] 2024 Approved  Recollection Runway  Your Easy Path to Story Archives</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-best-practices-elevating-your-virtual-identity-on-facebook/"><u>[New] In 2024, Best Practices  Elevating Your Virtual Identity on Facebook</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-top-5-secure-downloader-apps-for-fb-video-extraction/"><u>[New] In 2024, Top 5 Secure Downloader Apps for FB Video Extraction</u></a></li>
<li><a href="https://youtube-web.techidaily.com/58262689-new-started-streaming-learn-obs-for-youtube-now/"><u>[New] Started Streaming? Learn OBS for Youtube Now</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-detailed-guide-to-dollar-counts-a-stepwise-strategy-to-track-youtube-earnings/"><u>[Updated] In 2024, Detailed Guide to Dollar Counts  A Stepwise Strategy to Track YouTube Earnings</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-instagram-desktop-tips-for-effortless-video-posts/"><u>[Updated] Instagram Desktop Tips for Effortless Video Posts</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-understanding-and-mastering-google-chromes-pip-functionality/"><u>[Updated] Understanding and Mastering Google Chrome’s PIP Functionality</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-youtube-phenomenon-forecast-for-2024/"><u>[Updated] YouTube Phenomenon Forecast for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-live-stream-platform-showdown-xsplit-and-obs-face-off/"><u>2024 Approved  Live Stream Platform Showdown  XSplit & OBS Face-Off</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-fundamentals-of-compelling-documentary-screenplay/"><u>2024 Approved  The Fundamentals of Compelling Documentary Screenplay</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-unleash-creativity-unlimited-samples-of-50-youtube-banners-for-free/"><u>2024 Approved  Unleash Creativity  Unlimited Samples of 50 YouTube Banners for Free</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-samsung-galaxy-a14-4g-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Samsung Galaxy A14 4G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/8-microsoft-apps-you-must-install-on-android-if-you-have-a-windows-pc/"><u>8 Microsoft Apps You Must Install on Android if You Have a Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-immersive-surround-sound-incorporating-atmos-into-win-1011/"><u>Achieve Immersive Surround Sound: Incorporating Atmos Into Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-geforce-0x0001-in-windows-1011-environment/"><u>Addressing GeForce 0X0001 in Windows 10/11 Environment</u></a></li>
<li><a href="https://win11.techidaily.com/analyzing-the-electrical-footprint-of-your-personal-windows-pc/"><u>Analyzing the Electrical Footprint of Your Personal Windows PC</u></a></li>
<li><a href="https://extra-information.techidaily.com/autofocus-plus-next-gen-hdr-image-processing-explained-for-2024/"><u>Autofocus Plus  Next-Gen HDR Image Processing Explained for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/boost-productivity-with-slack-alert-systems-a-detailed-exploration/"><u>Boost Productivity with Slack Alert Systems: A Detailed Exploration</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-lava-yuva-2-pro-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Lava Yuva 2 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/confronting-clutter-eliminate-onedrive-symbol-from-explorer/"><u>Confronting Clutter: Eliminate OneDrive Symbol From Explorer</u></a></li>
<li><a href="https://tech-haven.techidaily.com/digital-dharma-harnessing-ai-to-enhance-meditation-habits/"><u>Digital Dharma: Harnessing AI to Enhance Meditation Habits</u></a></li>
<li><a href="https://win11.techidaily.com/easy-auto-shutdown-techniques-for-idle-windows-pcs/"><u>Easy Auto-Shutdown Techniques for Idle Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-vm-experience-seamless-upgrade-to-virtualbox-v70-on-w11-systems/"><u>Elevate Your VM Experience: Seamless Upgrade to VirtualBox v7.0 on W11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-11-with-personal-touches/"><u>Enhancing Windows 11 with Personal Touches</u></a></li>
<li><a href="https://data-wizards.techidaily.com/error-free-trash-clearance-unlock-macos/"><u>Error-Free Trash Clearance - Unlock macOS</u></a></li>
<li><a href="https://win11.techidaily.com/excellent-windows-pens-tablet-notes-companions/"><u>Excellent Windows Pens' Tablet Notes Companions</u></a></li>
<li><a href="https://win11.techidaily.com/first-day-with-windows-11-heres-what-not-to-do-top-7-mistakes/"><u>First Day with Windows 11? Here's What Not to Do! - Top 7 Mistakes</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-installed-disk-issue-on-windows-11-system/"><u>Fixing Non-Installed Disk Issue on Windows 11 System</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-windows-11s-security-and-credentials-panel/"><u>Guide to Windows 11'S Security & Credentials Panel</u></a></li>
<li><a href="https://win11.techidaily.com/harmonizing-hues-overcoming-color-issues-on-windows/"><u>Harmonizing Hues: Overcoming Color Issues on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-num-caps-and-scroll-lock-key-indicators-to-windows-11s-system-tray/"><u>How to Add Num, Caps, and Scroll Lock Key Indicators to Windows 11’S System Tray</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bypass-sie-and-load-unverified-drivers-in-windows/"><u>How to Bypass SIE & Load Unverified Drivers in Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-detailed-review-of-doctorsim-unlock-service-for-iphone-15-pro-max-by-drfone-ios/"><u>In 2024, Detailed Review of doctorSIM Unlock Service For iPhone 15 Pro Max</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-forgot-your-apple-id-password-and-email-on-apple-iphone-xs-heres-the-best-fixes-by-drfone-ios/"><u>In 2024, Forgot Your Apple ID Password and Email On Apple iPhone XS? Heres the Best Fixes</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/in-2024-handy-tips-downloading-youtube-like-content-via-android/"><u>In 2024, Handy Tips  Downloading YouTube-Like Content via Android</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-high-speed-snapshot-and-voice-commentary-assistant-device/"><u>In 2024, High-Speed Snapshot & Voice Commentary Assistant Device</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-top-7-skype-hacker-to-hack-any-skype-account-on-your-htc-u23-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Skype Hacker to Hack Any Skype Account On your HTC U23 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/ios-and-android-leading-10-apps-for-captivating-stickers-on-images/"><u>IOS & Android  Leading 10 Apps for Captivating Stickers on Images</u></a></li>
<li><a href="https://win11.techidaily.com/leading-password-guardians-revolutionizing-windows-11-life/"><u>Leading Password Guardians Revolutionizing Windows 11 Life</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-high-res-display-settings-in-windows/"><u>Mastering High-Res Display Settings in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-site-trust-on-windows-11/"><u>Mastering Site Trust on Windows 11</u></a></li>
<li><a href="https://games-able.techidaily.com/1719173428059-oled-gaming-tech-why-i-made-the-switch-in-2-years/"><u>OLED Gaming Tech: Why I Made the Switch in 2 Years</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-missed-display-after-windows-starts/"><u>Overcoming Missed Display After Windows Starts</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-non-playable-media-error-xc10100bf/"><u>Overcoming Non-Playable Media Error XC10100BF</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-read-failure-errors-in-windows-1011/"><u>Overcoming Read Failure Errors in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-your-win11-screen-scaling-preference/"><u>Personalizing Your Win11 Screen Scaling Preference</u></a></li>
<li><a href="https://location-social.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-oppo-a56s-5g-drfone-by-drfone-virtual-android/"><u>Proven Ways in How To Hide Location on Life360 For Oppo A56s 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reestablish-clear-view-fixing-black-screens-on-win11/"><u>Reestablish Clear View: Fixing Black Screens on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-windows-hello-authentication-compatibility-issue/"><u>Remedying Windows Hello Authentication Compatibility Issue</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-removing-null-space-in-your-system-drive/"><u>Step-by-Step Guide: Removing Null Space in Your System Drive</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-recovering-windows-11s-aid-features/"><u>Steps for Recovering Windows 11'S Aid Features</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-budget-buyers-guide-to-the-lg-um7300-49-inch-4k-smart-tv/"><u>The Budget Buyer's Guide to the LG UM7300 49-Inch 4K Smart TV</u></a></li>
<li><a href="https://win11.techidaily.com/the-financial-backbone-of-microsofts-windows-11/"><u>The Financial Backbone of Microsoft's Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-10-plugin-power-duo-for-final-cut-pro-for-2024/"><u>The Ultimate 10 Plugin Power Duo for Final Cut Pro for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-display-experience-an-in-depth-look-at-windows-11s-hdr/"><u>Transforming Display Experience: An In-Depth Look at Windows 11'S HDR</u></a></li>
<li><a href="https://win11.techidaily.com/trick-to-invoke-admin-level-powershell-on-your-win11-pc/"><u>Trick to Invoke Admin-Level PowerShell on Your Win11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-xbox-live-games-access-failures-on-windows-os/"><u>Troubleshooting: Xbox Live Games Access Failures on Windows OS</u></a></li>
<li><a href="https://extra-information.techidaily.com/understanding-digital-color-with-rgb-and-srgb-analysis/"><u>Understanding Digital Color with Rgb & Srgb Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-display-management-in-windows-11/"><u>Understanding Display Management in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719374785731-unlock-additional-space-on-your-windows-system-for-free/"><u>Unlock Additional Space on Your Windows System, For Free!</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-insights-into-repairing-windows-error-0x80040610/"><u>Unlocking Insights Into Repairing Windows' Error 0X80040610</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/unlocking-the-art-of-captions-a-short-guide-to-facebook-videos/"><u>Unlocking the Art of Captions  A Short Guide to Facebook Videos</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-menu-unlocking-ancestral-functions/"><u>Windows 11'S Menu: Unlocking Ancestral Functions</u></a></li>
<li><a href="https://win11.techidaily.com/winning-strategies-making-stagnant-batch-files-work-again/"><u>Winning Strategies: Making Stagnant Batch Files Work Again</u></a></li>
</ul></div>
