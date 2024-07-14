---
title: Mastering the Biometric Settings of W11 for Domains
date: 2024-07-13T09:59:40.487Z
updated: 2024-07-14T09:59:40.487Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Biometric Settings of W11 for Domains
excerpt: This Article Describes Mastering the Biometric Settings of W11 for Domains
keywords: BioSecure W11 Domain Config,W11 Biometrics Mastery,Enhanced Domain Security,W11 Identity Authentication,Optimize W11 Settings,Advanced Biometric Domains,Tailored W11 Safeguards
thumbnail: https://thmb.techidaily.com/73087a990223851f6a7c5417d3512a4d93ddbbb6cac79840abc644367d7f8449.jpg
---

## Mastering the Biometric Settings of W11 for Domains

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

## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/1719366255245-functional-failures-cure-win10-key-issues-now/"><u>Functional Failures? Cure Win10 Key Issues Now!</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-vivo-x100-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your Vivo X100 Phone? Unlock It Now</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-mastering-the-eight-most-advanced-speech-technology-applications-for-desktop-environments-and-cloud-computing-for-2024/"><u>Updated Mastering the Eight Most Advanced Speech Technology Applications for Desktop Environments and Cloud Computing for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-no-trouble-recorder-for-win10-desktop/"><u>2024 Approved  No-Trouble Recorder for Win10 Desktop</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-top-10-best-free-online-screen-recorders/"><u>[New] 2024 Approved  Top 10 Best Free Online Screen Recorders</u></a></li>
<li><a href="https://win11.techidaily.com/a-new-era-for-windows-users-understanding-copilot-key-impact/"><u>A New Era for Windows Users: Understanding Copilot Key Impact</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/invest-in-your-health-these-10-best-yoga-streams-exist-for-2024/"><u>Invest in Your Health - These 10 Best Yoga Streams Exist for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-fix-for-inaccessible-screen-settings-in-windows/"><u>A Comprehensive Fix for Inaccessible Screen Settings in Windows</u></a></li>
<li><a href="https://facebook.techidaily.com/advice-addressing-kids-presence-on-social-networks/"><u>Advice: Addressing Kids' Presence on Social Networks</u></a></li>
<li><a href="https://win11.techidaily.com/4-minimalist-devices-compact-windows-edition/"><u>4 Minimalist Devices: Compact Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-boost-your-studying-on-windows/"><u>8 Ways to Boost Your Studying on Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-vivo-x90s-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Vivo X90S? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-restoring-lost-windows-update/"><u>A Beginner's Guide to Restoring Lost Windows Update</u></a></li>
<li><a href="https://win11.techidaily.com/7-windows-11-features-youre-probably-not-using-but-should/"><u>7 Windows 11 Features You’re Probably Not Using (but Should)</u></a></li>
<li><a href="https://win11.techidaily.com/1719333062146-resolve-windows-scheduler-glitches-now/"><u>Resolve Windows Scheduler Glitches Now</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-building-captivating-visual-puzzles-a-mosaic-journey/"><u>2024 Approved  Building Captivating Visual Puzzles  A Mosaic Journey</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/pull-the-crowd-tactics-for-viral-instagram-videos-for-2024/"><u>Pull the Crowd  Tactics for Viral Instagram Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-saving-success-mastering-ppt-errors-in-windows-11/"><u>Accelerate Saving Success: Mastering PPT Errors in Windows 11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-filmora-discount-code-finder-explore-the-best-deals/"><u>Updated In 2024, Filmora Discount Code Finder Explore the Best Deals</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-tutorial-incorporating-widgets-in-windows-11/"><u>A Step-by-Step Tutorial: Incorporating Widgets in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/6-fixes-if-the-c-drive-keeps-filling-up-for-no-reason-on-windows/"><u>6 Fixes if the C: Drive Keeps Filling Up for No Reason on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/8-tactics-to-unlock-windows-with-persistent-pin-problems/"><u>8 Tactics to Unlock Windows with Persistent PIN Problems</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-s-most-popular-public-domain-image-websites/"><u>New 2024 Approved S Most Popular Public Domain Image Websites</u></a></li>
<li><a href="https://facebook.techidaily.com/1719152839748-heres-what-facebooks-new-page-labels-mean/"><u>Here's What Facebook's New Page Labels Mean</u></a></li>
<li><a href="https://win11.techidaily.com/5-best-windows-counterparts-to-procreate-app/"><u>5 Best Windows Counterparts to Procreate App</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-from-anonymity-to-authority-the-essential-pathway-for-raising-issues-on-digital-platforms-like-discord/"><u>[New] From Anonymity to Authority  The Essential Pathway for Raising Issues on Digital Platforms Like Discord</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-the-red-zones-best-unraveling-zombie-gaming-delights/"><u>[New] In 2024, The Red Zone's Best  Unraveling Zombie Gaming Delights</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-walkthrough-for-installing-apps-via-wpm-on-windows-11/"><u>A Step-by-Step Walkthrough for Installing Apps via WPM on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-fix-the-black-desktop-background-display-issue-on-windows/"><u>8 Ways to Fix the Black Desktop Background Display Issue on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-overcome-excessive-gpu-demand-in-winwm/"><u>7 Ways to Overcome Excessive GPU Demand in WinWM</u></a></li>
<li><a href="https://win11.techidaily.com/1719373181052-gpt4alls-local-window-companion-a-cost-free-chatbot-clone/"><u>GPT4All's Local Window Companion - A Cost-Free ChatBot Clone.</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreayers-guide-accessing-windows-web-services-manager/"><u>A Compreayer's Guide: Accessing Windows Web Services Manager</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-resolving-upgrade-error-in-windows-os/"><u>A Step-By-Step Guide to Resolving Upgrade Error in Windows OS</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-your-oppo-f25-pro-5g-lock-screen-password-by-drfone-android/"><u>In 2024, How to Reset your Oppo F25 Pro 5G Lock Screen Password</u></a></li>
<li><a href="https://win11.techidaily.com/1719330765099-troubleshooting-tips-for-your-windows-predicaments/"><u>Troubleshooting Tips for Your Windows Predicaments!</u></a></li>
<li><a href="https://win11.techidaily.com/5-precise-steps-to-rectify-your-screen-res-in-windows/"><u>5 Precise Steps to Rectify Your Screen Res in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719355296197-dimming-windows-11-brightness-simple-fixes-unveiled/"><u>Dimming Windows 11 Brightness - Simple Fixes Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/1719374180426-navigate-through-faulty-shift-in-windows/"><u>Navigate Through Faulty Shift in Windows.</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-building-a-studio-quality-setup-at-home-for-2024/"><u>[Updated] Building a Studio-Quality Setup at Home for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-techniques-of-composing-persuasive-content-in-vlogging/"><u>2024 Approved  Techniques of Composing Persuasive Content in Vlogging</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-unveiling-the-finest-8-android-based-digital-audio-workstations-of-this-year/"><u>Updated In 2024, Unveiling the Finest 8 Android-Based Digital Audio Workstations of This Year</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-fixing-the-full-screen-freeze-in-obs/"><u>[New] In 2024, Fixing the Full-Screen Freeze in OBS</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-walkthrough-of-ms-error-lookup-in-w11/"><u>A Comprehensive Walkthrough of MS Error Lookup in W11</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-clearing-defender-history-on-windows-pcs/"><u>A Comprehensive Guide to Clearing Defender History on Windows PCs</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-lock-on-apple-iphone-xr-by-drfone-ios/"><u>In 2024, How to Bypass iCloud Lock on Apple iPhone XR</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-use-windows-11-more-efficiently/"><u>7 Ways to Use Windows 11 More Efficiently</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-elevate-your-content-secrets-to-becoming-a-staff-favorite-at-vimeo/"><u>[New] In 2024, Elevate Your Content  Secrets to Becoming a Staff Favorite at Vimeo</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreenas-for-navigating-windows-11s-troubleshooter/"><u>A Compreenas for Navigating Windows 11'S Troubleshooter</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-temporarily-disable-windows-security-in-windows-11/"><u>4 Ways to Temporarily Disable Windows Security in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/7-reasons-why-most-users-havent-upgraded-to-windows-11/"><u>7 Reasons Why Most Users Haven’t Upgraded to Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-deep-dive-into-microsoft-family-safety-tools/"><u>A Deep Dive Into Microsoft Family Safety Tools</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-activating-god-control-on-pcs/"><u>A Step-by-Step Guide to Activating God Control on PCs</u></a></li>
<li><a href="https://audio-editing.techidaily.com/best-voice-changer-and-editor-for-singing/"><u>Best Voice Changer and Editor for Singing</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-walkthrough-to-activate-notepad-dark-mode-on-windows-11/"><u>A Detailed Walkthrough to Activate Notepad Dark Mode on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719346431441-navigate-through-common-snip-and-sketch-screen-capture-issues/"><u>Navigate Through Common Snip & Sketch Screen Capture Issues.</u></a></li>
<li><a href="https://win11.techidaily.com/a-quick-guide-to-restoring-functionality-of-your-windows-11-search-box/"><u>A Quick Guide to Restoring Functionality of Your Windows 11 Search Box</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/discover-the-top-tools-to-record-and-share-classroom-content/"><u>Discover the Top Tools to Record and Share Classroom Content</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-task-management-in-microsoft-project/"><u>Accelerate Task Management in Microsoft Project</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-to-recover-your-windows-apps/"><u>A Step-by-Step Approach to Recover Your Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/9-strategies-for-troubleshooting-windows-10-blue-screen-crashes/"><u>9 Strategies for Troubleshooting Windows 10 Blue Screen Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/a-simplified-guide-to-jdk-setup-for-modern-windows-11-users/"><u>A Simplified Guide to JDK Setup for Modern Windows 11 Users</u></a></li>
</ul></div>
