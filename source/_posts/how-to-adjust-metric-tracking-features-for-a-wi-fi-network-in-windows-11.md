---
title: How to Adjust Metric Tracking Features for a Wi-Fi Network in Windows 11
date: 2024-07-13T10:55:16.321Z
updated: 2024-07-14T10:55:16.321Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Adjust Metric Tracking Features for a Wi-Fi Network in Windows 11
excerpt: This Article Describes How to Adjust Metric Tracking Features for a Wi-Fi Network in Windows 11
keywords: Wi-Fi Metrics Tuning,Win11 Wifi Tracker Settings,Wi-Fi Performance Optimization,Windows Network Adjustments,Gain Wi-Fi Data Insights,Wi-Fi Metrics Control,Wifi Settings Enhancement
thumbnail: https://thmb.techidaily.com/8605278b5d648a8e727674b42f156215fdccc4c56056b931eaef077a91501e84.jpg
---

## How to Adjust Metric Tracking Features for a Wi-Fi Network in Windows 11

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to [launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the [Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.
6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on [the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

## Efficiently Manage Your Data With Metered Connection

 Enabling or disabling the metered connection option for Wi-Fi networks in Windows is relatively simple, regardless of the method you use.

 If you have a limited data plan, you can also set a data usage limit for your Wi-Fi connection. This way, Windows will notify you when you approach the set data limit.


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
<li><a href="https://techidaily.com/repair-video-tool-repair-all-your-damaged-video-files-of-s23-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>Repair Video Tool - Repair all your damaged video files of S23 on Mac</u></a></li>
<li><a href="https://android-location-track.techidaily.com/9-best-phone-monitoring-apps-for-infinix-smart-8-pro-drfone-by-drfone-virtual-android/"><u>9 Best Phone Monitoring Apps for Infinix Smart 8 Pro | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/easy-guide-to-crafting-fun-snapchat-lenses-for-2024/"><u>Easy Guide to Crafting Fun Snapchat Lenses for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-unleash-creative-power-instagrams-top-10-grid-makers/"><u>[Updated] In 2024, Unleash Creative Power  Instagram's Top 10 Grid Makers</u></a></li>
<li><a href="https://win11.techidaily.com/key-apps-to-bring-your-windows-pc-and-android-together/"><u>Key Apps to Bring Your Windows PC and Android Together</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-twilight-tactics-a-complete-guide-to-nighttime-photography/"><u>[New] In 2024, Twilight Tactics  A Complete Guide to Nighttime Photography</u></a></li>
<li><a href="https://win11.techidaily.com/sweeping-away-windows-access-errors-effectively/"><u>Sweeping Away Windows' Access Errors Effectively</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-unrivaled-cloud-based-chat-platforms/"><u>[New] Unrivaled Cloud-Based Chat Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-stop-infinite-data-depletion-in-windows/"><u>5 Ways to Stop Infinite Data Depletion in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/locate-vanished-settings-a-guide-to-finding-them-on-win11/"><u>Locate Vanished Settings: A Guide to Finding Them on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-solid-state-drive-speed-on-windows-via-ssd-fresh/"><u>Elevate Solid State Drive Speed on Windows via SSD Fresh</u></a></li>
<li><a href="https://win11.techidaily.com/selecting-the-best-downloader-choco-vs-windows-package-tool/"><u>Selecting the Best Downloader: Choco Vs. Windows Package Tool</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-premium-recording-solutions-windows-edition/"><u>[New] In 2024, Premium Recording Solutions  Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/windows-adjusting-user-permissions-for-regular-accounts/"><u>Windows: Adjusting User Permissions for Regular Accounts</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-how-to-create-metaverse-avatar-easily-an-ultimate-guide/"><u>[Updated] How to Create Metaverse Avatar Easily  An Ultimate Guide</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-journey-through-lut-based-color-enhancement-methods/"><u>[New] Journey Through LUT-Based Color Enhancement Methods</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/flashcapture-critique-plus-backup-software/"><u>FlashCapture Critique + Backup Software</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-nokia-105-classic-screen-sharing-drfone-by-drfone-android/"><u>How To Do Nokia 105 Classic Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-0x80d03801-issue-in-windows-shop/"><u>Remedying 0X80D03801 Issue in Windows Shop</u></a></li>
<li><a href="https://win11.techidaily.com/dive-into-efficiency-utilizing-windows-11s-taskbar-search/"><u>Dive Into Efficiency: Utilizing Windows 11'S Taskbar Search</u></a></li>
<li><a href="https://fix-guide.techidaily.com/spotify-keeps-crashing-a-complete-list-of-fixes-you-can-use-on-honor-90-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Spotify Keeps Crashing A Complete List of Fixes You Can Use on Honor 90 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quelling-the-0x800736cc-dilemran-in-windows-update/"><u>Quelling the 0X800736CC Dilemran in Windows Update</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-itel-p40plus-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Itel P40+ Phone with Broken Screen</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-alternative-methods-in-windows-exploration-no-ls/"><u>Deciphering Alternative Methods in Windows Exploration (No LS)</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-new-strategies-behind-extended-updates-in-windows-11-h2/"><u>Exploring the New Strategies Behind Extended Updates in Windows 11 H2</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-iphone-13-to-the-latest-ios-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade iPhone 13 to the Latest iOS Version? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/10-routes-to-windows-diagnostics-hub/"><u>10 Routes to Windows Diagnostics Hub</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-the-leading-10-competitors-to-zoom-for-pc-and-phone-for-2024/"><u>[New] The Leading 10 Competitors to Zoom for PC & Phone for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-vivo-y78plus-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>How to Cast Vivo Y78+ Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-hello-login-fingerprint-failure/"><u>Eliminating Windows Hello Login Fingerprint Failure</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-unresponsive-windows-11-printer-ports-and-devices/"><u>Tackling Unresponsive Windows 11 Printer Ports & Devices</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-revamped-widget-picker-in-win11/"><u>Configuring Revamped Widget Picker in Win11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-cinemusiceditor-for-elite-pc-video-enthusiasts/"><u>[New] CinemusicEditor for Elite PC Video Enthusiasts</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-a-detailed-vpna-fake-gps-location-free-review-on-oneplus-ace-2v-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed VPNa Fake GPS Location Free Review On OnePlus Ace 2V | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-best-stop-motion-animation-tools-for-mac-and-pc-for-2024/"><u>Updated Best Stop Motion Animation Tools for Mac and PC for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/essential-windows-microcomputers-reviewed/"><u>Essential Windows Microcomputers Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-instantaneous-folder-upload-failures-in-the-windows-onedrive-environment/"><u>Quick Fixes for Instantaneous Folder Upload Failures in the Windows OneDrive Environment</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-correct-display-not-available-error-in-windows-11/"><u>How to Correct 'Display Not Available' Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-home-screen-norm-setting-default-position-of-win-11-keyboards/"><u>Achieving Home Screen Norm: Setting Default Position of Win 11 Keyboards</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-error-codes-when-installing-windows-apps/"><u>Understanding Error Codes When Installing Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-stop-discord-initial-launch-and-searching-at-boot/"><u>Techniques: Stop Discord Initial Launch & Searching at Boot</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-infinix-hot-40i-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Infinix Hot 40i Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/audit-findings-on-sound-forges-integration-and-workflow-efficiency-for-2024/"><u>Audit Findings on Sound Forges Integration and Workflow Efficiency for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-motorola-g24-power-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Motorola G24 Power | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-windows-11-taskbar-datetime-visibility/"><u>Adjusting Windows 11 Taskbar Date/Time Visibility</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-subscription-wins-unlock-monetization-benefits/"><u>In 2024, Subscription Wins Unlock Monetization Benefits</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-this-article-ill-describe-how-to-flip-a-video-in-windows-using-the-filmora-video-program-for-2024/"><u>Updated In This Article, Ill Describe How to Flip a Video in Windows Using the Filmora Video Program for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-top-10-neon-font-generators-create-stunning-text-in-minutes-for-2024/"><u>Updated Top 10 Neon Font Generators Create Stunning Text in Minutes for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ssional-level-youtube-editing-techniques-you-need-to-know/"><u>Professional-Level Youtube Editing Techniques You Need To Know</u></a></li>
<li><a href="https://win11.techidaily.com/how-runtime-broker-enhances-system-efficiency-and-security/"><u>How Runtime Broker Enhances System Efficiency & Security</u></a></li>
<li><a href="https://win11.techidaily.com/the-convenience-of-uwp-shortcuts-in-windows-11/"><u>The Convenience of UWP Shortcuts in Windows 11</u></a></li>
<li><a href="https://video-capture.techidaily.com/top-strategies-for-efficient-mobizen-screencasting-for-2024/"><u>Top Strategies for Efficient Mobizen Screencasting for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/instagram-photo-edits-made-simple-pro-techniques-for-2024/"><u>Instagram Photo Edits Made Simple  Pro Techniques for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/detailed-review-of-doctorsim-unlock-service-for-apple-iphone-6-by-drfone-ios/"><u>Detailed Review of doctorSIM Unlock Service For Apple iPhone 6</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-pc-experience-on-windows-11-devices/"><u>Tailoring Your PC Experience on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tip-converting-esd-to-iso-without-compromising-data-integrity-on-windows/"><u>Tech Tip: Converting ESD to ISO without Compromising Data Integrity on Windows</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-mastery-in-messaging-perfecting-video-posting-on-discord/"><u>[Updated] 2024 Approved  Mastery in Messaging  Perfecting Video Posting on Discord</u></a></li>
<li><a href="https://win11.techidaily.com/whats-behind-yourphoneexe-in-modern-windows-systems/"><u>What's Behind YourPhone.exe in Modern Windows Systems?</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-individual-gpo-settings-for-windows-users-1111-edition/"><u>Implementing Individual GPO Settings for Windows Users 11/11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/re-establishing-normal-operations-of-netflix-window/"><u>Re-Establishing Normal Operations of Netflix Window</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unearthing-vivas-video-capabilities/"><u>In 2024, Unearthing Viva's Video Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-folders-reverting-to-read-only-mode-in-windows-10-and-11/"><u>How to Fix Folders Reverting to Read-Only Mode in Windows 10 and 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-reset-the-security-questions-of-your-apple-id-on-your-iphone-6s-by-drfone-ios/"><u>In 2024, How To Reset the Security Questions of Your Apple ID On Your iPhone 6s</u></a></li>
<li><a href="https://win11.techidaily.com/secure-clipchamp-install-on-windows-11-with-these-steps/"><u>Secure ClipChamp Install on Windows 11 with These Steps</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-vivo-t2-pro-5g-pin-codepattern-lockpassword-by-drfone-android/"><u>In 2024, How to Unlock Vivo T2 Pro 5G PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-10-standout-educational-websites-for-self-paced-learning/"><u>[Updated] 2024 Approved  10 Standout Educational Websites for Self-Paced Learning</u></a></li>
<li><a href="https://win11.techidaily.com/revitalize-pc-three-methods-for-a-clean-windows-boot/"><u>Revitalize PC: Three Methods for a Clean Windows Boot</u></a></li>
<li><a href="https://win11.techidaily.com/admin-controls-simplified-managing-users-and-groups-in-homes/"><u>Admin Controls Simplified: Managing Users & Groups in Homes</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-music-after-samsung-galaxy-a05-has-been-deleted-by-fonelab-android-recover-music/"><u>Recover your music after Samsung Galaxy A05 has been deleted</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-methods-to-embed-audios-in-mkv-files-new-edition-update-guide-for-2024/"><u>Updated Methods to Embed Audios in MKV Files New Edition Update Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/surface-laptop-studio-review-the-quest-for-perfection-continues/"><u>Surface Laptop Studio Review: The Quest for Perfection Continues</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-clipboard-problems-in-windows-11/"><u>Diagnosing Clipboard Problems in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/restore-peace-of-mind-with-these-5-family-safety-fixes/"><u>Restore Peace of Mind with These 5 Family Safety Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-charmap-incompatibility-challenges/"><u>Overcoming Windows CharMap Incompatibility Challenges</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/guide-on-how-to-erase-iphone-8-plus-data-completely-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>Guide on How To Erase iPhone 8 Plus Data Completely | Dr.fone</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-in-2024-want-to-make-a-meme-gif/"><u>Updated In 2024, Want to Make a Meme GIF?</u></a></li>
</ul></div>
