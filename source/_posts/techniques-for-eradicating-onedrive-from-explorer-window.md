---
title: Techniques for Eradicating OneDrive From Explorer Window
date: 2024-08-23T06:06:04.976Z
updated: 2024-08-24T06:06:04.976Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques for Eradicating OneDrive From Explorer Window
excerpt: This Article Describes Techniques for Eradicating OneDrive From Explorer Window
keywords: Remove Drives From Explorer,Eliminate OneDrive Explorer,Clearing OneDrive Windows,Banish OneDrive Explorer,Erase OneDrive Window Access,Forbid OneDrive Explorer Link,Purge OneDrive Explorer
thumbnail: https://thmb.techidaily.com/194a7e702c94714cd1ade34a1eef99f1c71a4608c10e7d8eb07bd33367c48152.jpg
---

## Techniques for Eradicating OneDrive From Explorer Window

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on[removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you[create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

 Once done, follow these steps to remove the OneDrive shortcut from File Explorer:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** if prompted by**User Account Control (UAC).**
3. Next, in the Registry Editor, navigate to the following location. Copy and paste the registry path in the editor for quicker navigation:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
4. In the right pane, right-click on**System.IsPinnedToNameSpaceTree** DWORD value and select**Modify** .  
![remove onedrive icon windows 11 registry editor modify system is pinned to name space free](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-modify-system-is-pinnedtonamespace-free.jpg)
5. In the**Value data** field, type**0** and click**OK** .  
![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.
9. When you open File Explorer, the OneDrive icon will not be visible anymore.

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
## Remove OneDrive Icon Without Uninstalling OneDrive

 This registry hack is a handy way to make the OneDrive icon disappear without deleting the app entirely from your PC. Alternatively, if you don’t use the service, you can completely remove OneDrive on Windows 11 or disable the service using Group Policy Editor.


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
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-vlogs-to-viral-jake-pauls-online-empire-expansion/"><u>[New] In 2024, From Vlogs to Viral  Jake Paul’s Online Empire Expansion</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-transforming-raw-audio-into-high-quality-youtube-videos/"><u>[New] Transforming Raw Audio Into High-Quality YouTube Videos</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-scaling-movies-on-a-mac-for-impeccable-instagram-shares/"><u>[Updated] 2024 Approved  Scaling Movies on a Mac for Impeccable Instagram Shares</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-fostering-duets-tiktok-vocal-pairings-for-2024/"><u>[Updated] Fostering Duets  TikTok Vocal Pairings for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-best-practices-for-imovie-videos-entering-the-vimeo-realm/"><u>[Updated] In 2024, Best Practices for iMovie Videos Entering the Vimeo Realm</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-streamline-music-craft-with-our-high-quality-beat-detection-software/"><u>[Updated] In 2024, Streamline Music Craft with Our High-Quality Beat Detection Software</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-newbies-guide-6-strategic-social-media-tactics-for-growth/"><u>[Updated] Newbies Guide  6 Strategic Social Media Tactics for Growth</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-sizing-up-how-to-make-videos-work-in-instagram-bests/"><u>[Updated] Sizing Up  How to Make Videos Work in Instagram Bests</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-explore-the-most-effective-zoom-screen-recorders/"><u>2024 Approved  Explore the Most Effective Zoom Screen Recorders</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-infinix-note-30-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Infinix Note 30 5G | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/a-streamlined-method-for-your-macos-sierra-enhancement-for-2024/"><u>A Streamlined Method for Your MacOS Sierra Enhancement for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/counteracting-sticky-note-desynchronization-in-w11/"><u>Counteracting Sticky Note Desynchronization in W11</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723341723202-cutting-edge-cost-effective-nvme-cooling-discover-the-power-of-the-uphere-m201-heatsink-under-5/"><u>Cutting-Edge, Cost-Effective NVMe Cooling - Discover the Power of the UpHere M201 Heatsink Under $5</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-dumps-on-windows-to-solve-issues/"><u>Deciphering Dumps on Windows to Solve Issues</u></a></li>
<li><a href="https://win11.techidaily.com/embrace-your-phones-games-enjoy-android-titles-on-windows-11-and-google-play/"><u>Embrace Your Phone's Games: Enjoy Android Titles on Windows 11 and Google Play</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-windows-connectivity-with-telnet-ways-3/"><u>Enhance Windows Connectivity with Telnet (Ways 3)</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-your-windows-ecosystem-wsl-and-win-11/"><u>Enhancing Your Windows Ecosystem: WSL & Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-to-do-list-software-for-windows-users/"><u>Essential To-Do List Software for Windows Users</u></a></li>
<li><a href="https://facebook.techidaily.com/five-more-ways-to-step-away-from-facebooks-clutches/"><u>Five More Ways to Step Away From Facebook's Clutches</u></a></li>
<li><a href="https://win11.techidaily.com/five-steps-to-wipe-ms-defender-history-on-windows-systems/"><u>Five Steps to Wipe MS Defender History on Windows Systems</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-huawei-nova-y91-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Huawei Nova Y91 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-interaction-failures-in-new-windows-11-os/"><u>Fixing Interaction Failures in New Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-invalid-path-in-windows-os/"><u>Fixing Invalid Path in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-xbox-subscription-issue-with-error-code-0x00000001/"><u>Fixing Xbox Subscription Issue with Error Code 0X00000001</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-and-update-new-radeon-rx-470-drivers-with-ease/"><u>Get and Update New Radeon RX 470 Drivers with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/get-direct-access-to-processes-in-win11-with-a-search-box/"><u>Get Direct Access to Processes in Win11 with a Search Box</u></a></li>
<li><a href="https://extra-resources.techidaily.com/guide-to-boost-your-telegram-marketing-efforts/"><u>Guide to Boost Your Telegram Marketing Efforts</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-do-you-unlock-your-apple-iphone-11-learn-all-4-methods-drfone-by-drfone-ios/"><u>How Do You Unlock your Apple iPhone 11? Learn All 4 Methods | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-or-disable-the-windows-installer-service-on-windows/"><u>How to Enable or Disable the Windows Installer Service on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-this-file-isnt-playable-error-0xc10100bf-in-windows/"><u>How to Fix the This File Isn’t Playable Error 0Xc10100bf in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-quick-settings-on-windows-11/"><u>How to Use Quick Settings on Windows 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-achieve-visual-harmony-optimal-sizing-for-instagram-videos/"><u>In 2024, Achieve Visual Harmony  Optimal Sizing for Instagram Videos</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-oppo-find-n3-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Pokémon Emerald Master Ball Cheat On Oppo Find N3 | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/leveraging-adobe-connect-for-exceptional-video-capture-and-editing-for-2024/"><u>Leveraging Adobe Connect for Exceptional Video Capture & Editing for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-overhauled-window-for-selecting-widgets-in-win11/"><u>Leveraging Overhauled Window for Selecting Widgets in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/minimize-delays-win11-optimized-launches/"><u>Minimize Delays: Win11 Optimized Launches</u></a></li>
<li><a href="https://review-topics.techidaily.com/mkv-playback-issues-on-motorola-edgeplus-2023-by-aiseesoft-video-converter-play-mkv-on-android/"><u>MKV playback issues on Motorola Edge+ (2023)</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-and-managing-windows-like-a-whiz/"><u>Navigating and Managing Windows Like a Whiz</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-past-glories-accessing-file-history/"><u>Navigating Past Glories: Accessing File History</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-wi-fi-woes-enhance-your-windows-apps-connectivity/"><u>Overcome Wi-Fi Woes: Enhance Your Windows Apps' Connectivity</u></a></li>
<li><a href="https://win11.techidaily.com/overruling-google-chromes-default-webp-imaging-process-pc-based/"><u>Overruling Google Chrome's Default WebP Imaging Process, PC-Based</u></a></li>
<li><a href="https://win11.techidaily.com/pioneers-playbook-for-win11-directory-creation/"><u>Pioneer's Playbook for Win11 Directory Creation</u></a></li>
<li><a href="https://win11.techidaily.com/reveal-usage-metrics-infusing-cpu-and-memory-details-into-systray/"><u>Reveal Usage Metrics: Infusing CPU & Memory Details Into SysTray</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/splendor-without-spending-big-best-value-luxury-tech-picks-revealed/"><u>Splendor Without Spending Big: Best Value Luxury Tech Picks Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-accessing-windows-11s-file-journey/"><u>Step-by-Step: Accessing Windows 11'S File Journey</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-energy-management-full-charge-alerts-on-windows-11/"><u>Streamlining Energy Management: Full Charge Alerts on Windows 11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/tailoring-textual-terminals/"><u>Tailoring Textual Terminals</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-art-of-captioning-text-techniques-for-images-in-oses/"><u>The Art of Captioning  Text Techniques for Images in OSes</u></a></li>
<li><a href="https://win11.techidaily.com/the-blueprint-of-devhome-integrating-win11-mastery/"><u>The Blueprint of DevHome: Integrating Win11 Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/the-clever-way-to-compress-streamlined-windows-explorer/"><u>The Clever Way to Compress: Streamlined Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/the-forgotten-features-windows-evolution/"><u>The Forgotten Features: Windows Evolution</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/the-ultimate-hair-and-makeup-guide-on-youtubes-top-influencers/"><u>The Ultimate Hair & Makeup Guide on YouTube's Top Influencers</u></a></li>
<li><a href="https://android-location.techidaily.com/toms-tech-insights-in-depth-reviews-and-news/"><u>Tom's Tech Insights: In-Depth Reviews & News</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-error-code-0xc0000005-on-windows-pcs/"><u>Troubleshooting Error Code 0xC0000005 on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-error-code-x7217-at-microsoft-store/"><u>Troubleshooting Error Code X7217 at Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-advanced-settings-for-a-secure-connection-on-win-11/"><u>Unlocking Advanced Settings for a Secure Connection on Win 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-realme-narzo-60x-5g-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Realme Narzo 60x 5G Users</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-productivity-keyboard-shortcuts-guide/"><u>Unlocking Windows Productivity: Keyboard Shortcuts Guide</u></a></li>
<li><a href="https://win11.techidaily.com/win11s-resource-monitor-how-to-rejuvenate-a-non-responsive-app/"><u>Win11's Resource Monitor: How To Rejuvenate a Non-Responsive App</u></a></li>
</ul></div>
