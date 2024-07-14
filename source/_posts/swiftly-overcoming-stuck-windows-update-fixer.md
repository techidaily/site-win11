---
title: Swiftly Overcoming Stuck Windows Update Fixer
date: 2024-07-13T10:13:37.945Z
updated: 2024-07-14T10:13:37.945Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Swiftly Overcoming Stuck Windows Update Fixer
excerpt: This Article Describes Swiftly Overcoming Stuck Windows Update Fixer
keywords: Quick Windows Fix,Unstuck Updates,Swift Update Help,Fast Windows Repair,Stop Update Failure,Speedy Windows Solve,Rapid Fixer Window
thumbnail: https://thmb.techidaily.com/87f89d3b15c9e03d195fa4c767fb7770437292a210562c1ab5e7ca0ee4b18377.jpg
---

## Swiftly Overcoming Stuck Windows Update Fixer

 Sometimes, the Windows Update Troubleshooter gets stuck while diagnosing and resolving problems. A slow or unstable internet connection, a stuck application, outdated drivers, or corrupt system files could cause this error.

 But, it is not difficult to get the Windows Update Troubleshooter working again—as you will discover by exploring the following fixes.

## 1\. Restart Your Computer

 You may have rebooted your phone at times to fix some lags and stuck applications. And you probably know that restarting your Windows PC works in the same way—it can fix issues like an unresponsive app and glitches too.

 When you restart your PC, the system shuts down temporarily and then turns on again. The RAM is cleaned up and refreshed, and so is the processor cache. So when your PC reboots, you will get a clean start all over again.

 Restarting your PC should be the first thing you do when the Windows Update Troubleshooter gets stuck on a "resolving problems" loop.

 Then try running the Windows Update Troubleshooter to see if it works.

## 2\. Clear the DNS Cache

 When you run the Windows Update Troubleshooter, it checks for Windows update issues, diagnoses, and resolves problems, resets Windows Update components, clears temporary files, and more. To do all this, it needs a stable internet connection.

 Often the Windows Update Troubleshooter malfunctions due to an unstable internet connection caused by an outdated or corrupt DNS (Domain Name System) cache.

 The DNS cache uses stored information like IP addresses and DNS Records to load websites and pages faster. However, the DNS cache can get corrupted.

 But you can clear or flush the DNS cache to resolve security and internet connectivity issues. Check out [how to flush the DNS cache on Windows](https://www.makeuseof.com/flush-dns-cache-windows/) for more information on how to do this.

 If the process is successful, you will get the confirmation message of the DNS Resolver Cache being successfully flushed. Now try running the Windows Update Troubleshooter.

## 3\. Restart Windows Cryptographic Services

 At times, an erratic or stopped Windows Cryptographic Services can cause problems in the smooth running of the Windows Update Troubleshooter.

 Cryptographic Services is an inbuilt Windows feature that provides encryption, decryption, and verification services. If it doesn't work properly, Windows Update Troubleshooter may also malfunction.

To fix this, you can try restarting Cryptographic Services.

1. Search for**Services** in**Windows Search** and click on the**Services app** under**Best match** . Or use one of the [many ways to open Services](https://www.makeuseof.com/windows-11-open-services-app/) .
2. In the**Services** app, look for**Cryptographic** **Services** and double-click on it to open its**Properties** .  
![Windows Cryptographic Services in the Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-cryptographic-services.jpg)
3. In**Properties** , click the**Stop** button to stop Cryptographic Services.  
![Cryptographic Services Stopped](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/stop-cryptographic-services.jpg)
4. Now, wait a few seconds and then click on the**Start** button. Also, ensure that the**Startup type** is set to**Automatic** .  
![Cryptographic Services Started With Automatic Startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/start-cryptographic-services.jpg)
5. Then click**Apply** and then**OK** .

 Now close Services and try running the Windows Update Troubleshooter again.

## 4\. Run System File Checker and DISM Command

 The Windows Update Troubleshooter can also get stuck in a loop if system files have gotten corrupted. Fortunately, you can resolve this issue by running the SFC scan. It scans, repairs, and replaces these damaged files automatically.

 Sometimes you may experience that the SFC is not working properly. To overcome that, you should run the DISM command that will service and repair Windows images.

 You can quickly learn how to run the SFC and DISM, and also explore how they work. Check out our piece on the [differences between CHKDSK, SFC, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) for the full low-down.

 After these scans finish running, try running the Windows Update Troubleshooter again.

## 5\. Update System Drivers

 Computer drivers enable Windows and its components to communicate and function efficiently. So it's good for you to [know what drivers are and why you should keep them updated](https://www.makeuseof.com/computer-drivers-what-are-they-why-should-you-update/) .

 If you're regularly keeping your Windows PC updated, the drivers your system needs would automatically be getting installed with the updates.

 But since the working of the Windows Update Troubleshooter may be affected by outdated or corrupt drivers, it's best if you check for driver updates and install them manually.

1. Right-click the**Windows icon** on the taskbar and select**Settings** from the menu.
2. Click**Windows Update** in**Settings** and then on the right pane select**Advanced options** .  
![Advanced Options in Windows Update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/advanced-options-windows-update.jpg)
3. In**Advanced options** , under the**Additional options** section, click on**Optional updates** .  
![Optional Updates in Advanced Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/optional-updates-windows-update.jpg)
4. If there are driver updates available they would be listed under the**Driver Updates** option. Select all the driver updates and click on**Download & install** .

 After you've updated the drivers, try running the Windows Troubleshooter and see if it works properly.

## 6\. Configure Troubleshooting in Group Policy Editor

 The Windows Update Troubleshooter may be stuck if the troubleshooting service is disabled in the Group Policy Editor.

 If you're using Windows 10 Pro or Windows 11 Pro editions, you can try tweaking the Scripted Diagnostics policy in Troubleshooting and Diagnostics in the Group Policy Editor.

 Though it's not available on Windows Home, you can still [access the Group Policy Editor by enabling it](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

To edit and enable the Scripted Diagnostics policy:

1. Press the**Windows** +**R** keys together to open the**Run** box.
2. Type**gpedit.msc** in the navigation bar and click**Enter** .  
![Open Group Policy Editor Via Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-group-policy-editor-via-run.jpg)
3. Click**Yes** on the UAC prompt. The**Group Policy Editor** will open.
4. In the**Group Policy Editor** , navigate to**Scripted Diagnostics** using the following path:  
`Computer Configuration > Administrative Templates > System > Troubleshooting and Diagnostics > Scripted Diagnostics`
5. In the left pane, click on**Scripted Diagnostics** to open its three items.  
![Open Scripted Diagnostics Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-scripted-diagnostics-policy.jpg)
6. Double-click on the first item and select the**Enable** option in the window that opens.  
![Enable Each Item in Scripted Diagnostics Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-items-of-scripted-diagnostics-policy.jpg)
7. Finally, tap on**Apply** and then**OK** .
8. Repeat steps 5 and 6 for the other two items of Scripted Diagnostics.

 Now close the Group Policy Editor and run the Windows Update Troubleshooter.

## Get the Windows Update Troubleshooter Working Again to Fix Update Errors

 It's important to have the Windows Update Troubleshooter running fine. Try the above fixes if it ever gets stuck or stops working. And ensure you can install essential updates to enjoy a smooth and secure Windows experience.

 You can also know more about security updates and why it makes sense to install them quickly.

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
<li><a href="https://win11.techidaily.com/addressing-disrupted-audio-playback-on-windows/"><u>Addressing Disrupted Audio Playback on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/atlasos-reboot-transform-your-old-game-machine/"><u>AtlasOS Reboot: Transform Your Old Game Machine</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-a-pristine-windows-11-workspace/"><u>Achieve a Pristine Windows 11 Workspace</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-facebook-video-orientation-dilemma/"><u>In 2024, Facebook  Video Orientation Dilemma?</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-the-fast-lane-to-excellent-captioning-a-guide-to-impressive-fb-media-posts/"><u>[Updated] In 2024, The Fast Lane to Excellent Captioning  A Guide to Impressive FB Media Posts</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-efficiently-utilizing-discord-spoiler-features-for-2024/"><u>[New] Efficiently Utilizing Discord Spoiler Features for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-disconnectivity-of-nvidias-geforce-experience-on-windows-11/"><u>Addressing the Disconnectivity of Nvidia's GeForce Experience on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/activatingdeactivating-cost-monitoring-for-wifi-on-win11/"><u>Activating/Deactivating Cost Monitoring for Wifi on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/altering-windows-standard-pdf-display/"><u>Altering Window's Standard PDF Display</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-optimal-7-dslr-recommendations-for-dynamic-video-content/"><u>2024 Approved  Optimal 7 DSLR Recommendations For Dynamic Video Content</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-sound-identity-shift-for-free-fire-characters-no-money-required-for-2024/"><u>[Updated] Sound Identity Shift for Free Fire Characters - No Money Required for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-uncover-the-joyful-journey-best-comedy-and-sadness-on-insta/"><u>In 2024, Uncover the Joyful Journey  Best Comedy & Sadness on Insta</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-expert-advice-enhancing-your-screen-capture-game-with-mobizen-tools/"><u>[New] 2024 Approved  Expert Advice  Enhancing Your Screen Capture Game with Mobizen Tools</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-the-quietest-cool-memes-on-the-web/"><u>2024 Approved  The Quietest Cool Memes on the Web</u></a></li>
<li><a href="https://extra-information.techidaily.com/one-on-one-youtube-streams-on-mobile-without-thousanders-club/"><u>One-on-One Youtube Streams on Mobile Without Thousanders' Club</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-oneplus-ace-2-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your OnePlus Ace 2</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/avs-video-editor-2023-review-pros-cons-and-verdict/"><u>AVS Video Editor 2023 Review Pros, Cons, and Verdict</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-connectivity-issues-fix-iphone-images-not-uploading-in-windows/"><u>Addressing Connectivity Issues: Fix iPhone Images Not Uploading in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/alter-icon-and-thumbnail-dimensions-w11/"><u>Alter Icon and Thumbnail Dimensions W11</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-airplane-mode-turn-off-gps-location-on-honor-x50i-drfone-by-drfone-virtual-android/"><u>In 2024, Does Airplane Mode Turn off GPS Location On Honor X50i? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-compatibility-woes-with-surface-firmware-upgrade-tips/"><u>Avoid Compatibility Woes with Surface Firmware Upgrade Tips</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-critical-system-breakdown-windows-c0000022-fixes/"><u>Addressing Critical System Breakdown: Windows C0000022 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/an-intuitive-roadmap-for-installing-java-development-kit-on-windows-11/"><u>An Intuitive Roadmap for Installing Java Development Kit on Windows 11</u></a></li>
<li><a href="https://facebook.techidaily.com/creating-safe-social-space-free-from-religiouspolitical-views/"><u>Creating Safe Social Space: Free From Religious/Political Views</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-discover-popular-sad-background-music/"><u>In 2024, Discover Popular Sad Background Music</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-error-code-30015-26-in-m365-software-for-pcs/"><u>Addressing Error Code 30015-26 in M365 Software for PCs</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-best-free-mac-apps-for-professional-tiktok-cuts/"><u>2024 Approved  Best Free Mac Apps for Professional TikTok Cuts</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-20-quirky-tiktok-joke-threads-for-endless-chuckles-for-2024/"><u>[Updated] 20 Quirky TikTok Joke Threads for Endless Chuckles for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-streamline-your-images-in-canva-without-clutter/"><u>In 2024, Streamline Your Images in Canva Without Clutter</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-command-prompt-authorization-problems/"><u>Addressing Command Prompt Authorization Problems</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unreadable-folder-in-microsoft-office-for-desktop-users/"><u>Addressing Unreadable Folder In Microsoft Office for Desktop Users</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-icy-illusions-reveling-at-beijings-olympic-event-2022/"><u>In 2024, Icy Illusions  Reveling at Beijing's Olympic Event, 2022</u></a></li>
<li><a href="https://extra-information.techidaily.com/elevating-vision-a-compre-written-by-jovita-lara-msn-student-arizona-state-university/"><u>Elevating Vision  A Compre Written By  Jovita Lara, MSN Student (Arizona State University)</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-screen-driver-crash-in-windows-11/"><u>Addressing Screen Driver Crash in Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-oppo-find-x7-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on Oppo Find X7</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-clarity-windows-11-taskbar-tutorial/"><u>Achieving Clarity: Windows 11 Taskbar Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-sluggish-downloads-on-windows-pcs-a-guide/"><u>Addressing Sluggish Downloads on Windows PCs: A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-essential-items-not-met-error-in-windows-11/"><u>Addressing the 'Essential Items Not Met' Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-strategies-for-extending-shutdown-duration-in-windows-10/"><u>Advanced Strategies for Extending Shutdown Duration in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-3d-audio-with-dolby-atmos-on-windows/"><u>Achieving 3D Audio with Dolby Atmos on Windows</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-harnessing-hobbies-for-hefty-helpings-on-digital-domains/"><u>[New] 2024 Approved  Harnessing Hobbies for Hefty Helpings on Digital Domains</u></a></li>
<li><a href="https://win11.techidaily.com/automating-success-windows-audio-at-system-startup/"><u>Automating Success: Windows Audio at System Startup</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-steam-download-rates-in-windows-environment/"><u>Accelerating Steam Download Rates in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-windows-baseline-energy-profile/"><u>Achieving Windows' Baseline Energy Profile</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/discover-the-secret-to-turning-iphone-pics-around/"><u>Discover the Secret to Turning iPhone Pics Around</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-spontaneous-store-openings-on-pc/"><u>Addressing Spontaneous Store Openings on PC</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-ubuntus-best-kept-secrets-top-10-free-video-editing-tools/"><u>New In 2024, Ubuntus Best Kept Secrets Top 10 Free Video Editing Tools</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-from-slow-mo-to-hyper-speed-the-best-free-video-speed-changer-apps/"><u>New In 2024, From Slow-Mo to Hyper-Speed The Best Free Video Speed Changer Apps</u></a></li>
<li><a href="https://win11.techidaily.com/alternatives-for-enabling-elusive-firewall-on-windows/"><u>Alternatives for Enabling Elusive Firewall on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-silencing-of-windows-11-pings/"><u>Accelerated Silencing of Windows 11 Pings</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disappearances-in-file-explorer/"><u>Addressing Disappearances in File Explorer</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-edit-and-send-fake-location-on-telegram-for-your-oppo-find-n3-flip-in-3-ways-drfone-by-drfone-virtual-android/"><u>In 2024, Edit and Send Fake Location on Telegram For your Oppo Find N3 Flip in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-sam-mismanagement/"><u>Addressing Windows SAM Mismanagement</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-10-best-tools-to-bypass-icloud-activation-lock-on-iphone-15-pro-you-should-try-out-by-drfone-ios/"><u>The 10 Best Tools to Bypass iCloud Activation Lock On iPhone 15 Pro You Should Try Out</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-invisible-broadcasts-anonymous-instagram-live-tips/"><u>[Updated] Invisible Broadcasts  Anonymous Instagram Live Tips</u></a></li>
</ul></div>
