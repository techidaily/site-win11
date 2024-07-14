---
title: Advanced Methods to Remove Restrictions on Blocked Windows Files
date: 2024-07-13T10:39:06.557Z
updated: 2024-07-14T10:39:06.557Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Advanced Methods to Remove Restrictions on Blocked Windows Files
excerpt: This Article Describes Advanced Methods to Remove Restrictions on Blocked Windows Files
keywords: Unblock Windows Files,Eliminate File Blocking Windows,Clear Restriction Windows Files,Bypass Blocked Windows Content,Override Windows File Limits,Disable Windows Filters,Freeze Windows Permissions
thumbnail: https://thmb.techidaily.com/cbb1e3102bf892cff8d3ec0a8653b920867c497d12f1be8e2ab6e11d350e85ee.jpg
---

## Advanced Methods to Remove Restrictions on Blocked Windows Files

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  
![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on [how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

## Now You Know How to Unblock Files You Know Are Safe

 With the instruction above unlocking a bunch of downloaded files in a directory should be easier. Keep in mind that you shouldn’t do this on files you don’t trust. The last thing you want to do is put your Windows PC at risk unnecessarily


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
<li><a href="https://win11.techidaily.com/methods-to-retain-calculator-top-status-on-win-os/"><u>Methods to Retain Calculator Top Status on Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/from-simple-logon-to-strong-authentication-changing-your-windows-11-login-habit/"><u>From Simple Logon to Strong Authentication: Changing Your Windows 11 Login Habit</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-resolving-inbox-notifications-on-pcs/"><u>Comprehensive Guide to Resolving Inbox Notifications on PCs</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-boost-engagement-through-anime-style-subscribe-buttons-filmora-tutorial/"><u>2024 Approved  Boost Engagement Through Anime-Style Subscribe Buttons (Filmora Tutorial)</u></a></li>
<li><a href="https://extra-skills.techidaily.com/progressive-volume-cut-down-in-fl-for-2024/"><u>Progressive Volume Cut-Down in FL for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/command-prompt-wizardry-admin-skills-unveiled/"><u>Command Prompt Wizardry: Admin Skills Unveiled</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-essence-of-e-story-creation-techniques-for-2024/"><u>The Essence of E-Story Creation Techniques for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/2024-approved-prankster-peak-standout-comedians-of-the-week/"><u>2024 Approved  Prankster Peak  Standout Comedians of the Week</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/7-top-ways-to-resolve-apple-id-not-active-issue-for-apple-iphone-6s-plus-drfone-by-drfone-ios/"><u>7 Top Ways To Resolve Apple ID Not Active Issue For Apple iPhone 6s Plus | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-top-30-screen-selections-for-xbox-series-x-gamers-enhance-every-playtime/"><u>[Updated] Top 30 Screen Selections for Xbox Series X Gamers - Enhance Every Playtime</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-best-gionee-frp-bypass-guide-by-drfone-android/"><u>In 2024, Best Gionee FRP Bypass Guide</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-clear-obstacles-no-access-allowed-windows-errors/"><u>Methods to Clear Obstacles: No Access Allowed Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-rescuing-flaky-windows-programs/"><u>Mastering the Art of Rescuing Flaky Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/changing-windows-read-only-settings-easily/"><u>Changing Windows Read-Only Settings Easily</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-11s-hidden-data-files/"><u>Navigating Through Windows 11'S Hidden Data Files</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-splitting-clips-in-adobe-after-effects-step-by-step/"><u>Updated Splitting Clips in Adobe After Effects Step by Step</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-solve-active-directory-issues-impacting-print-in-windows-11/"><u>How to Solve Active Directory Issues Impacting Print in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/modify-homescreen-without-altering-windows-11-start-menu/"><u>Modify Homescreen without Altering Windows 11 Start Menu</u></a></li>
<li><a href="https://win11.techidaily.com/6-methods-to-supercharge-virtual-machine-speed-in-windows/"><u>6 Methods to Supercharge Virtual Machine Speed in Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-youtube-video-shooting-equipment-list-what-you-need-to-start-recording-videos/"><u>In 2024, YouTube Video Shooting Equipment List  What You Need to Start Recording Videos</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-aspect-ratio-changer-top-10-free-and-paid-options-for-2024/"><u>New Aspect Ratio Changer Top 10 Free and Paid Options for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-understanding-igs-evolution-reels-vs-stories/"><u>[Updated] In 2024, Understanding IG's Evolution  Reels vs Stories</u></a></li>
<li><a href="https://win11.techidaily.com/is-steam-unable-to-connect-to-the-internet-on-windows-heres-how-to-fix-it/"><u>Is Steam Unable to Connect to the Internet on Windows? Here's How to Fix It</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-terror-in-town-a-list-of-intense-zombie-games/"><u>2024 Approved  Terror in Town  A List of Intense Zombie Games</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-the-confusion-five-windows-cures-to-unsupported-boots/"><u>Clearing Up the Confusion: Five Windows Cures to Unsupported Boots</u></a></li>
<li><a href="https://extra-support.techidaily.com/navigating-inter-service-playlist-shuffling-with-ease-for-2024/"><u>Navigating Inter-Service Playlist Shuffling with Ease for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-resolving-common-instagram-video-glitches/"><u>[New] 2024 Approved  Resolving Common Instagram Video Glitches</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-elevate-your-group-dynamics-with-discord-roles/"><u>[Updated] Elevate Your Group Dynamics with Discord Roles</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-kickstart-your-earnings-with-periscope-strategies/"><u>[New] Kickstart Your Earnings with Periscope Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-enhancing-interface-through-ms-store-themes/"><u>Effortlessly Enhancing Interface Through MS Store Themes</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-delaying-windows-10-shutdown-processes/"><u>Mastering the Art of Delaying Windows 10 Shutdown Processes</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-beyond-easy-video-joiner-10-alternative-solutions-for-seamless-video-editing/"><u>New 2024 Approved Beyond Easy Video Joiner 10 Alternative Solutions for Seamless Video Editing</u></a></li>
<li><a href="https://win11.techidaily.com/6-high-performance-windows-video-editors-unveiled/"><u>6 High-Performance Windows Video Editors Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/winter-wonderland-offering-apps-from-microsofts-store/"><u>Winter Wonderland: Offering Apps From Microsoft's Store</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-innovative-approaches-to-capturing-moments-with-zooms-snaps/"><u>[New] Innovative Approaches to Capturing Moments with Zoom's Snaps</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-from-good-to-great-elevate-your-tiktok-edits-for-2024/"><u>[New] From Good to Great  Elevate Your TikTok Edits for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-crafting-moments-of-happiness-animated-filters-on-your-phone/"><u>[New] In 2024, Crafting Moments of Happiness  Animated Filters on Your Phone</u></a></li>
<li><a href="https://win11.techidaily.com/dispel-limitations-escalating-internet-speed-past-100mbps-in-windows/"><u>Dispel Limitations: Escalating Internet Speed Past 100Mbps in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-rapid-notification-curbing-guide/"><u>Windows 11: Rapid Notification Curbing Guide</u></a></li>
<li><a href="https://win11.techidaily.com/elite-screen-grabbers-5-non-windows-counterparts-to-snipping-tool/"><u>Elite Screen Grabbers: 5 Non-Windows Counterparts to Snipping Tool</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-for-error-0x800700e1-in-windows-11-os/"><u>Essential Fixes for Error 0X800700E1 in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-the-mouse-without-borders-and-peek-features-in-powertoys/"><u>How to Use the Mouse Without Borders and Peek Features in PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/windows-enthusiasts-how-dxvk-shapes-your-gameplay/"><u>Windows Enthusiasts - How DXVK Shapes Your Gameplay</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-tackle-misdirected-token-call-on-windows/"><u>Methods to Tackle Misdirected Token Call” On Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-vivo-t2-5g-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-does-microsofts-copilot-key-transform-windows-11/"><u>How Does Microsoft's Copilot Key Transform Windows 11?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-vivo-y78-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Vivo Y78 5G to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-5-best-zoom-transcription-software-free-and-paid-for-2024/"><u>[New] 5 Best Zoom Transcription Software [Free & Paid] for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-from-novice-to-expert-tiktok-voiceovers-journey/"><u>[Updated] 2024 Approved  From Novice to Expert  TikTok Voiceovers Journey</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-oppo-a79-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Oppo A79 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/foster-innovation-for-privacy-protection-explore-cutting-edge-technologies-like-onboard-anonymization-systems-or-secure-data-transmission-techniques-to-mini44/"><u>Foster Innovation for Privacy Protection: Explore Cutting-Edge Technologies Like Onboard Anonymization Systems or Secure Data Transmission Techniques to Minimize the Risk of Violating Customer's Privacy During Cookie Deliveries.</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-top-10plus-websites-to-download-games/"><u>New In 2024, Top 10+ Websites to Download Games</u></a></li>
<li><a href="https://win11.techidaily.com/file-locations-decoded-win11s-best-practices-for-retrieving-file-and-folder-paths-6-methods/"><u>File Locations Decoded: Win11's Best Practices for Retrieving File & Folder Paths (6 Methods)</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-scripts-in-windows-quick-fixes-for-loading-powershell-failures/"><u>Enabling Scripts in Windows: Quick Fixes for Loading PowerShell Failures</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-installation-in-vmware-17-player/"><u>Mastering Windows 11 Installation in VMWare 17 Player</u></a></li>
</ul></div>
