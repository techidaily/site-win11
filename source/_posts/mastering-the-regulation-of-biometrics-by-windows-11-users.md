---
title: Mastering the Regulation of Biometrics by Windows 11 Users
date: 2024-08-23T06:07:53.164Z
updated: 2024-08-24T06:07:53.164Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Regulation of Biometrics by Windows 11 Users
excerpt: This Article Describes Mastering the Regulation of Biometrics by Windows 11 Users
keywords: Windows 11 BioRegulation,Biometric Mastery Win11,11 Win Biometrics Control,Win11 Biometry Management,BioRegulate Win Users,User BioControl Win11,Win11 Biometrics Guide
thumbnail: https://thmb.techidaily.com/704c497d76ce3443a342fa34e8883ce74ed2e3eea338695faa58de9221c96a80.jpg
---

## Mastering the Regulation of Biometrics by Windows 11 Users

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

## How to Allow or Block a Biometrics Log-On via the Local Group Policy Editor

 The quickest way to configure your computer to allow or block a biometrics scan for domain users is through the Local Group Policy Editor. Here are the steps you need to follow:

1. Press the **Win + R** key to open the **Run tool.**
2. Type **gpedit.msc** in the search bar and click OK.
3. In the Local Group Policy Editor, head towards the following location:  
`Computer Configuration > Administrative Templates > Windows Components > Biometrics`
4. Double-click on the **Allow domain users to log on using biometrics** policy in the right pane.  
![Allow domain users to log on using biometrics policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/allow-domain-users-to-log-on-using-biometrics-policy.jpg)
5. Choose the **Enabled** option to allow biometrics log on for the domain users. And choose the **Disabled** option to block biometrics log on for the domain users.  
![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
4. Name the value **Domain Accounts.**  
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-mastering-the-art-of-disabling-youtube-shorts/"><u>[New] Mastering the Art of Disabling YouTube Shorts</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-styling-your-content-a-compreran-guide-to-insta-photo-watermarks/"><u>[New] Styling Your Content  A Compreran Guide to Insta Photo Watermarks</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-from-beginner-to-pro-essential-steps-in-recording-with-logitech-cameras/"><u>[Updated] 2024 Approved  From Beginner to Pro  Essential Steps in Recording with Logitech Cameras</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-best-practices-for-secondary-footage-selection-and-use/"><u>[Updated] Best Practices for Secondary Footage Selection and Use</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/2024-approved-unlocking-talkshoplive-pros-and-tips-for-live-shopping-success/"><u>2024 Approved Unlocking TalkShopLive Pros and Tips for Live Shopping Success</u></a></li>
<li><a href="https://article-tips.techidaily.com/acclaimed-music-archives-for-visual-media-for-2024/"><u>Acclaimed Music Archives for Visual Media for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/calming-chronicles-on-screen-evaluating-bedtime-story-videos-for-2024/"><u>Calming Chronicles on Screen  Evaluating Bedtime Story Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/command-prompt-strategies-for-effective-data-management/"><u>Command Prompt Strategies for Effective Data Management</u></a></li>
<li><a href="https://facebook.techidaily.com/creators-get-richer-on-instagram-the-new-ways-to-cash-in/"><u>Creators Get Richer on Instagram: The New Ways to Cash In</u></a></li>
<li><a href="https://win11.techidaily.com/discovering-ai-driven-tools-on-microsofts-platform/"><u>Discovering AI-Driven Tools on Microsoft's Platform</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-methods-to-uncover-and-clear-windows-usage-tracks/"><u>Efficient Methods to Uncover and Clear Windows Usage Tracks</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-no-servers-frustration-9-fixes-for-pc-apex-legends-errors-(156-chars/"><u>Eliminate 'No Servers' Frustration: 9 Fixes for PC Apex Legends Errors (<156 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-server-unreachable-for-ea-games/"><u>Eliminating Server Unreachable for EA Games</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-user-experience-streamlined-approaches-for-decoding-qr-codes-on-windows/"><u>Enhancing User Experience: Streamlined Approaches for Decoding QR Codes on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enriched-learning-through-ed-themed-ui-on-win-11/"><u>Enriched Learning Through Ed-Themed UI on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-file-notifications-in-windows-outlook/"><u>Eradicating File Notifications in Windows Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-crash-0x00000709-issue/"><u>Fixing Windows Crash: 0X00000709 Issue</u></a></li>
<li><a href="https://win11.techidaily.com/flip-your-view-6-image-rotation-techniques-in-win11/"><u>Flip Your View: 6 Image Rotation Techniques in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-taskbar-power-in-windows-11/"><u>Harnessing Taskbar Power in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-capture-gameplay-on-windows-with-intel-graphics-command-center/"><u>How to Capture Gameplay on Windows With Intel Graphics Command Center</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-disregard-the-upcoming-expiry-alert-in-windows-1011/"><u>How To Disregard the “Upcoming Expiry” Alert in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-mend-sound-error-code-0xc00d36b4-win11/"><u>How to Mend Sound Error: Code 0xC00D36B4, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-regain-credential-manager-entry/"><u>How to Regain Credential Manager Entry</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-stop-your-battlefield-5-game-from-keeping-crashing-on-windows/"><u>How to Stop Your Battlefield 5 Game From Keeping Crashing on Windows</u></a></li>
<li><a href="https://ai-voice.techidaily.com/how-to-successfully-address-and-correct-indivisible-crash-issues-once-and-for-all/"><u>How to Successfully Address and Correct 'Indivisible' Crash Issues Once and For All</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-tecno-camon-20-premier-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Tecno Camon 20 Premier 5G | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-infinix-zero-5g-2023-turbo-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Infinix Zero 5G 2023 Turbo Phone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-recommended-best-applications-for-mirroring-your-lava-blaze-2-5g-screen-drfone-by-drfone-android/"><u>In 2024, Recommended Best Applications for Mirroring Your Lava Blaze 2 5G Screen | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-tailored-editing-for-impeccable-instagram-videos/"><u>In 2024, Tailored Editing for Impeccable Instagram Videos</u></a></li>
<li><a href="https://win11.techidaily.com/incorporating-scroll-capslock-indicators-in-systemtray-win11/"><u>Incorporating Scroll, CapsLock Indicators in SystemTray Win11</u></a></li>
<li><a href="https://win11.techidaily.com/is-windows-scrolling-by-itself-heres-how-to-fix-it/"><u>Is Windows Scrolling By Itself? Here's How to Fix It</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-adjusting-admin-settings-on-windows-11/"><u>Master the Art of Adjusting Admin Settings on Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mastering-machine-learning-dialogues-with-mac-and-gpt/"><u>Mastering Machine Learning Dialogues with Mac & GPT</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-iomap64-freezebsod-in-windows-10-and-8-systems/"><u>Overcoming IOMap64 Freeze/BSOD in Windows 10 & 8 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/panels-in-peril-bring-them-back-with-these-hacks/"><u>Panels in Peril? Bring Them Back with These Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/reestablish-uninterrupted-gameplay-in-gaming-environment/"><u>Reestablish Uninterrupted Gameplay in Gaming Environment</u></a></li>
<li><a href="https://win11.techidaily.com/restore-your-5ghz-network-visibility-in-windows-11-top-fixes/"><u>Restore Your 5GHz Network Visibility in Windows 11 - Top Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/sidestepping-error-code-0xa00f4243-for-multiple-camera-usage/"><u>Sidestepping Error Code: 0XA00F4243 for Multiple Camera Usage</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-unblocked-files-via-powershell-on-pc/"><u>Simplifying Unblocked Files via PowerShell on PC</u></a></li>
<li><a href="https://win11.techidaily.com/solving-camera-problems-in-windows-like-a-pro/"><u>Solving Camera Problems in Windows Like a Pro</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-vivo-v27-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Vivo V27? | Dr.fone</u></a></li>
<li><a href="https://facebook.techidaily.com/steps-to-monitor-youth-activity-within-social-media-networks/"><u>Steps to Monitor Youth Activity Within Social Media Networks</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-combat-error-0x80072f8f-0x20000/"><u>Strategies to Combat Error 0X80072f8f - 0X20000</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-hidden-net-identity-errors-windows/"><u>Tackling Hidden Net Identity Errors Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-guide-to-gone-security-questions-for-your-local-admin-user/"><u>The Guide to Gone Security Questions for Your Local Admin User</u></a></li>
<li><a href="https://win11.techidaily.com/the-shield-of-anonymity-network-file-security-on-windows/"><u>The Shield of Anonymity: Network File Security on Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-ultimate-strategy-for-organizing-a-zoom-event-on-your-phonetablet/"><u>The Ultimate Strategy for Organizing a Zoom Event on Your Phone/Tablet</u></a></li>
<li><a href="https://win11.techidaily.com/transform-windows-tasks-admin-cmd-mode/"><u>Transform Windows Tasks: Admin CMD Mode</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-vintage-pc-a-step-by-step-guide-to-windows-11-to-go-and-rufus/"><u>Transform Your Vintage PC: A Step-by-Step Guide to Windows 11, To Go & Rufus</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-active-directory-errors-with-xp-devices/"><u>Troubleshooting Active Directory Errors with XP Devices</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshooting-guide-solving-the-starfield-not-starting-issue-on-steam-or-xbox/"><u>Troubleshooting Guide: Solving the 'Starfield Not Starting' Issue on Steam or Xbox</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-secrets-to-hd-classic-quests-top-tips-and-tricks-on-windows-plus-scummvm/"><u>Unlock the Secrets to HD Classic Quests: Top Tips and Tricks on Windows + ScummVM</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/virtual-success-in-lithuanian-acquisition/"><u>Virtual Success in Lithuanian Acquisition</u></a></li>
<li><a href="https://win11.techidaily.com/win11-compatibility-with-google-play-store/"><u>Win11 Compatibility with Google Play Store</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-tecno-spark-10-5g-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Tecno Spark 10 5G | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>