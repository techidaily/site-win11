---
title: Resolving Power-User Permissions Issues in Windows OS
date: 2024-08-16T00:37:51.575Z
updated: 2024-08-17T00:37:51.575Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Power-User Permissions Issues in Windows OS
excerpt: This Article Describes Resolving Power-User Permissions Issues in Windows OS
keywords: Win User Access Control,Fixing Power Users,Resolve Permissions Errors,Windows XP User Rights,Adjust Privileges Windows,Optimize Admin Roles,Correct OS Permission Issues
thumbnail: https://thmb.techidaily.com/d615ac68260522d8e70b422dd5540cece714bbc625d61d049281d91eac42f958.jpg
---

## Resolving Power-User Permissions Issues in Windows OS

 Windows offers a Run as administrator option that allows users to run applications and programs with administrator privileges. You can also use it to troubleshoot computer issues. But what if this feature malfunctions, depriving you of administrator rights?

 That’s where this guide comes into play. So, let’s look at what you can do to fix Run as administrator not working on Windows.

## What Causes Run as Administrator Not Working?

 Before you start fixing things, you must understand what causes this issue. In general, you may experience Run as administrator not working due to the following reasons:

* Group Policy or User Account Control (UAC) blocks the application or program you’re trying to run.
* The user account associated with your device isn’t an administrator account and therefore doesn’t have the necessary privileges.
* Corrupt system files or registry entries could prevent you from running administrator programs.
* Malware infection on your computer could disrupt the feature.

 Now that you know the potential causes of this issue, let’s look at ways to fix it. ​​​

## 1\. Restart Your Computer

 If you’re having trouble running applications with administrative privileges, [restarting your computer](https://www.makeuseof.com/windows-restart-methods/) will likely solve the issue. This simple solution flushes out any temporary issues and puts the system in its default state.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Check Your Account Type

 Not all user accounts are equal. To run programs with administrative privileges, you must have an administrator account. So, [head to the Control Panel](https://www.makeuseof.com/windows-open-control-panel/) and [check your account type](https://www.makeuseof.com/check-windows-account-admin-rights/). If it’s not labeled as an administrator account, switch to a different one or create a new account.

## 3\. Check User Account Control Settings

 The Windows User Account Control (UAC) prevents malicious programs from installing on your computer. This security feature can stop you from using elevated privileges.

 To ensure the issue isn’t related to UAC, head to the Control Panel and check your User Account Settings. If it is set to the highest level, bring it down to the default. Here's how to do it:

1. Press **Win + S** simultaneously to open the search box.
2. Type **Control Panel** in the search box and press Enter. This will open the Control Panel window.
3. View items by **Large icons** in the Control Panel and click on **User Accounts**.
4. In the right pane, click on **Change User Account Control settings**. Doing this will open the User Account Control Settings window.
5. Here you’ll see a slider with four options: **Always notify**, **Default**, **Notify me only when applications try to make changes to my computer**, and **Never notify**.  
![User Account Control Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/user-account-control-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
6. Drag the slider to **Default**, then click **OK**. It will set your UAC to the default level and enable you to run applications with elevated privileges.

 Now, close the window and restart your PC. After that, try running the application with the Run as administrator feature and see if it works.

## 4\. Change Group Policy Settings

 Is the Run as administrator function not working despite trying the suggestions above? It's likely that group policy settings block the feature. To fix this, head to the Local Group Policy Editor and check the settings.

 Here’s what you need to do:

1. Press **Win + R** simultaneously to open the Run dialogue box.
2. Type **gpedit.msc** in the text field and press **Enter**. This will open the Local Group Policy Editor window on your computer screen.
3. From the left navigation panel, go to the following path:  
Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options
4. In the right pane, you'll see a list of different security options. Scroll to the bottom and double-click on the **User Account Control: Run all administrators in Admin Approval Mode** policy.  
![Run all administrators in admin approved](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/run-all-administrators-in-admin-approved.jpg)
5. Doing this will open another window. Here, select the **Disabled** option and click **Apply** \> **OK**.  
![Disable User Account Control in Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-user-account-control-in-group-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
6. Close the Local Group Policy Editor and restart your computer.

 After restarting, try running a program with elevated privileges. It should work now. Don't forget to re-enable the Admin Approval Mode setting once you're finished troubleshooting.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
## 5\. Clean up the Context Menu

 When you right-click on a program or file, you often see the Run as administrator option in the context menu. If it's missing, you should look at your context menu entries for clutter.

 This solution involves editing the Windows registry. A single mistake can cause serious problems. So proceed cautiously and [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before applying any changes.

 Follow these steps to clean up the context menu:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the text field and press Enter. Doing this will open the Windows Registry Editor.
3. If the UAC window pops up, click **Yes** to grant administrative privileges.
4. In the Registry Editor window, navigate to the following path:  
Computer\HKEY_CLASSES_ROOT\*\shellex\ContextMenuHandlers
5. Next, expand the **ContextMenuHandlers** folder and look for any suspicious entries. If you find any, delete them.  
![Clean the Context Menu Items](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/clean-the-context-menu-items.jpg)
6. Now exit the Registry Editor and restart your computer.

 Once your computer reboots, you will see the Run as administrator option in the context menu. Try running a program with elevated privileges and see if it works.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
## 6\. Try Some Generic Fixes

 Besides the fixes mentioned above, some generic solutions work in any situation. Try these out if you’re still having issues running applications with elevated privileges:

* [Repair Corrupted System Files](https://www.makeuseof.com/windows-built-in-repair-tools/): It restores your computer’s corrupted and missing system files. Use them to repair the root cause of the issue.
* [Perform a Clean Boot](https://www.makeuseof.com/clean-boot-windows-11/): When you start Windows in a clean boot state, the operating system will only run essential services and programs. It identifies any third-party software causing the issue.
* [Create a New Administrator User Account](https://www.makeuseof.com/tag/windows-administrator-account-everything-need-know/): If all else fails, try creating a new administrator user account and logging in. This ascertains if your existing account is corrupted or not.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Troubleshooting Run as Administrator on Windows

 We hope this guide helped you solve the Run as administrator not working on Windows issue. Despite the prevalence of this problem, it’s relatively easy to fix if you know what to do.

 If none of the troubleshooting steps worked, try running a system scan using an advanced antivirus program. Some malicious programs prevent you from running as an administrator. A complete system scan should find and remove any malicious software on your computer, so you can start using it again.

 That’s where this guide comes into play. So, let’s look at what you can do to fix Run as administrator not working on Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-data.techidaily.com/024-approved-achieve-more-engagement-on-youtube-learn-the-best-thumbnail-size/"><u>[New] 2024 Approved  Achieve More Engagement on YouTube  Learn the Best Thumbnail Size</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-image-jokes-laughgenix-hub/"><u>[New] Image Jokes  LaughGenix Hub</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-captivate-viewers-social-media-strategies-for-youtube/"><u>[New] In 2024, Captivate Viewers  Social Media Strategies for YouTube</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-essentials-of-editing-your-social-media-profile-picture/"><u>[Updated] Essentials of Editing Your Social Media Profile Picture</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-insta-share-tips-for-posting-youtube-videos/"><u>[Updated] In 2024, Insta-Share  Tips for Posting YouTube Videos</u></a></li>
<li><a href="https://extra-information.techidaily.com/10-recommended-free-online-photo-editor/"><u>10 Recommended Free Online Photo Editor</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-dreaming-through-the-viewfinder-inspiring-photo-ideas/"><u>2024 Approved  Dreaming Through the Viewfinder  Inspiring Photo Ideas</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-previews-blockage-in-windows-edition-of-outlook/"><u>Correcting Previews Blockage in Windows Edition of Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/counteracting-unforeseen-security-issues-in-win10win11/"><u>Counteracting Unforeseen Security Issues in Win10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-cpu-temperatures-on-windows-11-machines/"><u>Decreasing CPU Temperatures on Windows 11 Machines</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-windows-11-the-intricacies-of-its-file-system/"><u>Demystifying Windows 11: The Intricacies of Its File System</u></a></li>
<li><a href="https://win11.techidaily.com/effective-modification-of-nat-type-on-windows-win11-and-10-guide/"><u>Effective Modification of NAT Type on Windows: Win11 & 10 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-runtime-broker-purpose-and-impact-on-pcs/"><u>Exploring Runtime Broker: Purpose and Impact on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-inability-to-reach-mb-services-in-windows-11-devices/"><u>Fixing the Inability to Reach MB Services in Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-biometric-authentication-in-11th-gen-windows/"><u>How to Enable Biometric Authentication in 11Th Gen Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-oppo-a1x-5g-drfone-by-drfone-virtual-android/"><u>How to Fix Life360 Shows Wrong Location On Oppo A1x 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-fn-key-for-brightness-adjustment-in-windows-11/"><u>How to Reactivate Fn Key for Brightness Adjustment in Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-redmi-k70-pro-pin-codepattern-lockpassword-by-drfone-android/"><u>How to Unlock Xiaomi Redmi K70 Pro PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-special-features-virtual-location-on-poco-m6-pro-4g-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Poco M6 Pro 4G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/improving-vlc-media-player-reducing-buffer-lags-on-win/"><u>Improving VLC Media Player: Reducing Buffer Lags on Win</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-itel-p55-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Itel P55 via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-craft-a-symphony-for-screens-mastering-music-editing-in-canva/"><u>In 2024, Craft a Symphony for Screens  Mastering Music Editing in Canva</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-infinix-smart-8-hd-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Infinix Smart 8 HD? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-perfected-beats-on-the-go-no-cost-just-download-and-play/"><u>In 2024, Perfected Beats on the Go - No Cost, Just Download and Play</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-unlock-6-figure-videos-top-hashtag-trends/"><u>In 2024, Unlock 6-Figure Videos  Top Hashtag Trends</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-what-you-want-to-know-about-two-factor-authentication-for-icloud-from-your-apple-iphone-11-pro-max-by-drfone-ios/"><u>In 2024, What You Want To Know About Two-Factor Authentication for iCloud From your Apple iPhone 11 Pro Max</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-90-degree-display-flip-techniques-and-benefits/"><u>Mastering 90-Degree Display Flip: Techniques & Benefits</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/mastering-the-art-of-measuring-igtv-video-quality/"><u>Mastering the Art of Measuring IGTV Video Quality</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-visual-efficiency-top-5-ideal-windows-pc-clock-themed-screen-saver-creation-apps/"><u>Maximize Visual Efficiency: Top 5 Ideal Windows PC Clock-Themed Screen Saver Creation Apps</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-workflow-efficiency-mastering-tab-management-in-windows-11/"><u>Maximize Workflow Efficiency: Mastering Tab Management in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/meet-the-new-wave-exciting-laptops-from-ifa-2023/"><u>Meet the New Wave - Exciting Laptops From IFA 2023</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-network-nooks-for-your-windows-11s-mac/"><u>Navigating the Network Nooks for Your WIndows 11'S MAC</u></a></li>
<li><a href="https://extra-tips.techidaily.com/navigating-the-nuances-of-sound-reduction-in-pp-projects/"><u>Navigating the Nuances of Sound Reduction in PP Projects</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-issues-of-not-allowing-file-writes-on-windows-11/"><u>Overcoming Issues of Not Allowing File Writes on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-stuck-on-size-errors-with-easy-solutions-for-windows-discousers/"><u>Overcoming Stuck-On-Size Errors with Easy Solutions for Windows DiscoUsers</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-pixel-predictor-discovering-top-view-counts/"><u>Prime Pixel Predictor  Discovering Top View Counts</u></a></li>
<li><a href="https://win11.techidaily.com/privacy-measures-eliminate-email-from-logon-window/"><u>Privacy Measures: Eliminate Email From Logon Window</u></a></li>
<li><a href="https://win11.techidaily.com/quick-remedies-starting-fresh-with-explore-ui/"><u>Quick Remedies: Starting Fresh with Explore UI</u></a></li>
<li><a href="https://win11.techidaily.com/silent-speakers-unveil-audio-steps-immediately/"><u>Silent Speakers? Unveil Audio Steps Immediately</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-restoring-disabled-windows-sign-in-options/"><u>Steps for Restoring Disabled Windows Sign-In Options</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-endless-popups-of-edge-symbols/"><u>Stopping Endless Popups of Edge Symbols</u></a></li>
<li><a href="https://win11.techidaily.com/surgical-tweaks-to-the-android-resource-management-system/"><u>Surgical Tweaks to the Android Resource Management System</u></a></li>
<li><a href="https://win11.techidaily.com/syncing-calendars-ifttt-meets-microsoft-to-do/"><u>Syncing Calendars: IFTTT Meets Microsoft To-Do</u></a></li>
<li><a href="https://win11.techidaily.com/the-gamers-manual-to-prevent-data-loss-with-epic-backup/"><u>The Gamer's Manual to Prevent Data Loss with Epic Backup</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-beginners-guide-to-microsoft-copilot/"><u>The Ultimate Beginner's Guide to Microsoft Copilot</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-ultimate-guide-to-time-stamping-your-photos/"><u>The Ultimate Guide to Time-Stamping Your Photos</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-fixing-microsoft-store-error-0x87e00017/"><u>Tips for Fixing Microsoft Store Error 0X87e00017</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/top-rated-wrist-supports-for-keyboards-in-2/"><u>Top-Rated Wrist Supports for Keyboards in 2</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-administrative-blockage-for-software-installations/"><u>Troubleshooting Administrative Blockage for Software Installations</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-chrome-download-failures-on-pcs/"><u>Troubleshooting Chrome Download Failures on PCs</u></a></li>
<li><a href="https://extra-resources.techidaily.com/uniting-voices-and-sounds-the-ultimate-podcast-mixer-guide/"><u>Uniting Voices & Sounds  The Ultimate Podcast Mixer Guide</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unveiling-nikons-1j5-a-4k-video-masterpiece/"><u>Unveiling Nikon's 1J5  A 4K Video Masterpiece</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-art-of-size-calculation-powershell-ways/"><u>Unveiling the Art of Size Calculation: PowerShell Ways</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-graphical-performance-for-secure-browsing-edge/"><u>Upgrading Graphical Performance for Secure Browsing Edge</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-old-pcs-less-windows-more-efficiency/"><u>Upgrading Old PCs: Less Windows, More Efficiency</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-nubia-red-magic-9-pro-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of Nubia Red Magic 9 Pro on Mac?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-htc-u23-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your HTC U23 | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/why-artificial-intelligence-bots-arent-the-right-tool-for-legitimate-windows-11-key-production/"><u>Why Artificial Intelligence Bots Aren't the Right Tool for Legitimate Windows 11 Key Production</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-highlighted-icons-a-how-to-guide/"><u>Windows 11'S Highlighted Icons: A How-To Guide</u></a></li>
<li><a href="https://win11.techidaily.com/windows-explorer-excellence-the-ultimate-six-strategies-for-copying-filefolder-paths/"><u>Windows Explorer Excellence: The Ultimate Six Strategies for Copying File/Folder Paths</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/wirelessly-connect-your-television-a-guide-to-streaming-zoom-video-calls/"><u>Wirelessly Connect Your Television: A Guide to Streaming Zoom Video Calls</u></a></li>
</ul></div>
