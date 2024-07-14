---
title: 4 Key Approaches to Activate a Dormant Windows Guard
date: 2024-07-13T10:23:22.226Z
updated: 2024-07-14T10:23:22.226Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 4 Key Approaches to Activate a Dormant Windows Guard
excerpt: This Article Describes 4 Key Approaches to Activate a Dormant Windows Guard
keywords: WinGuard Reactivation Strategies,Reviving Windows Defender,Enhance DefGuard Functionality,Boosting Windows Guard Efficacy,Reinvigorate Defender Security,Activating Dormant Antivirus,Optimize WinGuard Performance
thumbnail: https://thmb.techidaily.com/7618ed5212ad2fa17c4d0cff006f1dcb4d7c52766a583e2029f0351c0b405229.jpg
---

## 4 Key Approaches to Activate a Dormant Windows Guard

 Windows Firewall is crucial to ensure the security of your computer and protect it from potential threats. However, sometimes you may encounter issues while enabling it.

 Below, we explore the different solutions you can try to fix this issue for good.

## 1\. Run the Firewall Troubleshooter

 If you are having trouble enabling Firewall in Windows, it is a good idea to start troubleshooting using the official Firewall troubleshooter released by Microsoft Automated Troubleshooting Services.

 This utility will scan your system for underlying problems that might be preventing Firewall from functioning. If an issue is identified, it will suggest relevant fixes that you can either apply manually or from within the troubleshooter.

 Here is how you can run the troubleshooter:

1. Head over to the [official Microsoft page for the troubleshooter](https://support.microsoft.com/en-us/windows/automatically-diagnose-and-fix-problems-with-windows-firewall-513e9cf8-19ae-d579-2092-d5e64fe06f5f) and download it.  
![Download firewall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/download-troubleshooter.jpg)
2. Click on the downloaded file and proceed with the on-screen instructions to start the scan.  
![Firewall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/firewall-troubleshooter.jpg)
3. Once the scan completes, check the results and apply the solutions suggested by the troubleshooter.

 You can now close the troubleshooter and check if the issue is resolved.

## 2\. Check if Another Security Software Is Active

 Are you using a third-party security program on your computer? If so, there is a good chance that it is conflicting with Windows Firewall and stopping it from working. As such, if you have installed another antivirus app recently, we recommend temporarily disabling or uninstalling the third-party security program and then enabling Windows Firewall.

 Disabling the third-party antivirus software may vary depending on the program you have installed. However, a common approach is to right-click on the antivirus icon located in the taskbar. From the context menu that appears, you should find an option to disable the antivirus temporarily until you restart your computer.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 After disabling the antivirus, try enabling the Windows Firewall and check if it functions properly now.

## 3\. Reset the Windows Firewall settings

 The issue might also be with the Firewall settings. You can fix any such issues by resetting Windows Firewall settings, as it will restore the firewall configuration to its default state, undoing any customizations or changes that might be causing conflicts.

 Here is how you can proceed:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type “control” in Run and click **Enter**.
3. In the Control Panel, expand the View by option and choose **Category**.
4. Click on **System and Security** \> **Windows Defender Firewall**.  
![Defender Firewall in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/defender-firewall.jpg)
5. Head over to the left pane and choose **Restore defaults**.  
![Restore defaults for firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-defaults.jpg)

1. Confirm the action in the following prompt and proceed with the on-screen instructions to proceed.
2. Once done, open Run again.
3. Type "cmd" in the text field and press **Ctrl** \+ **Shift** \+ **Enter** keys together. This will open Command Prompt with administrator privileges.
4. Click **Yes** in the User Account Control prompt.
5. Once you are inside the Command Prompt window, type the command mentioned below and click **Enter** to execute it. This will force enable the Firewall component.  
`netsh firewall set opmode mode=ENABLE exceptions=enable`
6. Wait for the command to execute and then restart your computer. Check if the problem is now fixed.

## 4\. Modify the Registry Editor

 There is also a chance that a Registry key DisableAntiSpyware is enabled, which is preventing you from enabling Firewall on your computer.

 To check if this is the case in your situation, you can access the Registry Editor and check the status of the DisableAntiSpyware key.

 However, before you proceed, we highly recommend [creating a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just to be safe.

 Once that is done, proceed with the steps below:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "regedit" in Run and click **Enter**.
3. Click **Yes** in the User Account Control prompt.
4. In the Registry Editor, navigate to the location below.  
`​​​​​​​HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender`
5. Move to the right side and look for the DisableAntiSpyware key. If you locate it, delete it. You can also double-click on it and change its value to 0 if you do not want to delete it.  
![Disable or delete the registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/antispyware-key.jpg)

1. Once done, head over to the following location:  
`​​​​​​​​​​​​​​HKEY_LOCAL_MACHINE/SYSTEM/CurrentControlSet/Services/BFE`
2. Right-click on the **BFE** key and choose **Permissions** from the context menu.  
![Access permissions of the key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/access-permissions.jpg)
3. Under "Group or user names", click on **Add**.
4. Type "Everyone" in the "Enter the object names to select" and click **OK**.  
![Modify permissions of the key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/modify-permissions.jpg)
5. Now, head over to the "Permissions for Everyone" section and checkmark the box associated with **Full Control** under Allow.
6. Click **Apply** to save the changes and check if the issue is now resolved.

## Additional Generic Fixes to Try

 Apart from the fixes we have listed above, here are some additional solutions that you can try to fix the Firewall problem.

* **Ensure relevant services are running**: Windows Firewall relies on several services to function properly. Ensure that the Windows Defender Firewall, Windows Defender Advanced Threat Protection, Windows Defender Antivirus Network Inspection, and Windows Defender Antivirus services are working fine in the Windows Services utility.
* **Scan with SFC**: You can also scan the system for underlying corruption errors that might be leading to the problem using the [System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/). You can run it via Command Prompt and analyze the results to find the culprit.
* **Clean install Windows**: If nothing works and it is essential for you to enable Firewall, you can [perform a clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) of Windows. It will wipe the existing installation and download a new one without any underlying problems.

## Protect Your System With Windows Firewall

 The steps above should help you fix issues with Windows Firewall easily. If the error persists and you do not want to clean install the system yet, you can report the issue to Microsoft and wait for them to suggest a fix.

 Below, we explore the different solutions you can try to fix this issue for good.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/quick-compression-and-decompression-tactics-in-windows-cli/"><u>Quick Compression & Decompression Tactics in Windows CLI</u></a></li>
<li><a href="https://win11.techidaily.com/flattening-windows-11-corner-style/"><u>Flattening Windows 11 Corner Style</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-what-is-public-domain-art/"><u>[New] In 2024, What Is Public Domain Art</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-asana-glitches-on-pc/"><u>Troubleshooting Asana Glitches on PC</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/how-to-add-music-or-voiceover-to-instagram-reels-for-2024/"><u>How to Add Music or Voiceover to Instagram Reels for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-memory-write-failure-in-windows/"><u>Overcoming Memory Write Failure in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/securing-your-pcs-login-trail-a-win-flip-guide/"><u>Securing Your PC's Login Trail: A Win-Flip Guide</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-which-screen-recording-app-wins-bandicam-vs-camtasia-analysis/"><u>[New] 2024 Approved  Which Screen Recording App Wins? Bandicam Vs Camtasia Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-the-mystery-of-infinite-c-drive-usage/"><u>Combatting the Mystery of Infinite C: Drive Usage</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-free-location-spoofers-to-fake-gps-location-on-your-xiaomi-redmi-k70-drfone-by-drfone-virtual/"><u>In 2024, 10 Free Location Spoofers to Fake GPS Location on your Xiaomi Redmi K70 | Dr.fone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-the-ultimate-mac-video-editor-mkvtoolnix-features-and-benefits-2023/"><u>New 2024 Approved The Ultimate Mac Video Editor MKVtoolnix Features and Benefits 2023</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-revolutionize-your-videos-top-10-free-green-screen-apps-for-mobile/"><u>New 2024 Approved Revolutionize Your Videos Top 10 Free Green Screen Apps for Mobile</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-how-to-share-videos-on-twitter-on-your-phone-without-retweeting/"><u>[Updated] How to Share Videos on Twitter on Your Phone Without Retweeting?</u></a></li>
<li><a href="https://win11.techidaily.com/method-to-release-administrator-restricted-apps/"><u>Method to Release Administrator-Restricted Apps</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-google-maps-installation-on-pc/"><u>Quick Guide: Google Maps Installation on PC</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-divide-recovering-lost-winvpn-links/"><u>Bridging the Divide: Recovering Lost WinVPN Links</u></a></li>
<li><a href="https://win11.techidaily.com/winpc-restoring-lost-connections-with-easy-6-strategies-for-troubleshooting-adapters/"><u>WinPC: Restoring Lost Connections with Easy 6 Strategies for Troubleshooting Adapters</u></a></li>
<li><a href="https://win11.techidaily.com/solving-uninstall-issues-in-windows-11/"><u>Solving Uninstall Issues in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-glitches-and-error-0xc00d36b4-on-windows/"><u>Troubleshooting Glitches & Error 0xC00D36B4 on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/swift-strike-against-script-failures-in-windows/"><u>Swift Strike Against Script Failures in Windows</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-scrutinizing-how-content-makers-get-paid-from-youtube-shorts-videos/"><u>2024 Approved  Scrutinizing How Content Makers Get Paid From YouTube Shorts Videos</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-the-a-list-of-audio-harvesters-10-indispensable-tools-to-master-your-sound-design-for-2024/"><u>Updated The A-List of Audio Harvesters 10 Indispensable Tools to Master Your Sound Design for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-social-sphere-score-10-videos-that-are-going-viral-today/"><u>2024 Approved  Social Sphere Score  10 Videos That Are Going Viral Today</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-achieve-seamless-video-playback-by-removing-bars-in-youtube/"><u>In 2024, Achieve Seamless Video Playback by Removing Bars in YouTube</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-hook-listeners-first-introductory-podcast-lines/"><u>2024 Approved  Hook Listeners First  Introductory Podcast Lines</u></a></li>
<li><a href="https://win11.techidaily.com/windows-mastering-app-and-browser-oversight/"><u>Windows: Mastering App & Browser Oversight</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-mask-after-dim-display-option-on-pcs/"><u>Steps to Mask After Dim Display Option on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-your-window-11-potential-7-tips/"><u>Unleash Your Window 11 Potential: 7 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-fix-the-access-denied-error-on-windows-11/"><u>5 Ways to Fix the “Access Denied” Error on Windows 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-peering-into-the-heart-of-4k-vision-with-benqs-ultra-hd-model-bl2711u/"><u>In 2024, Peering Into the Heart of 4K Vision with BenQ’s Ultra HD Model, BL2711U</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-the-missing-search-back-into-win11s-task-manager/"><u>Bringing the Missing Search Back Into Win11's Task Manager</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-advanced-tech-the-most-reliable-webcams-for-podcasters/"><u>2024 Approved  Advanced Tech  The Most Reliable Webcams for Podcasters</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-disabled-security-authority-on-desktops/"><u>Remedy for Disabled Security Authority on Desktops</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-microsoft-store-error-0x80073cf3/"><u>Steps to Resolve Microsoft Store Error 0X80073CF3</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-audiobook-creation-simplified-your-comprehensive-step-by-step-tutorial-for-2024/"><u>New Audiobook Creation Simplified Your Comprehensive Step-by-Step Tutorial for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-steps-to-confirm-video-compliance-before-tiktok-posting/"><u>[New] Steps to Confirm Video Compliance Before TikTok Posting</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-2024-approved-animate-photo-online-with-these-awesome-tools/"><u>New 2024 Approved Animate Photo Online with These Awesome Tools</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-grayed-out-extend-volume-option-in-disk-management-for-windows/"><u>How to Fix a Grayed Out Extend Volume Option in Disk Management for Windows</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/exploring-the-most-effective-10-yoga-video-platforms/"><u>Exploring The Most Effective 10 Yoga Video Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/is-your-hardware-upgraded-for-win11-find-out/"><u>Is Your Hardware Upgraded For Win11? Find Out!</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-demystifying-viewer-statistics-on-instagram-images/"><u>[New] Demystifying Viewer Statistics on Instagram Images</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-edge-enhancements-in-windows-10-release/"><u>[New] The Edge Enhancements in Windows 10 Release</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-virtualbox-v70-potential-the-upgrade-on-windows-11/"><u>Unlock VirtualBox v7.0 Potential: The Upgrade on Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-motorola-edge-40-drfone-by-drfone-virtual-android/"><u>How to Check Distance and Radius on Google Maps For your Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-techniques-for-moving-files-in-windows-11/"><u>Boost Productivity: Techniques for Moving Files in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/instructions-for-completely-getting-rid-of-wsl-on-win-11/"><u>Instructions for Completely Getting Rid of WSL on Win 11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-unparalleled-youtube-soundscapes-to-experience/"><u>Updated Unparalleled YouTube Soundscapes to Experience</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-instantaneous-frame-construction-facebook-photo-groups/"><u>[New] Instantaneous Frame Construction  Facebook Photo Groups</u></a></li>
<li><a href="https://driver-install.techidaily.com/flexible-driver-changes-on-lenovos-u310/"><u>Flexible Driver Changes on Lenovo's U310</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-infinix-zero-30-5g-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Infinix Zero 30 5G to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-should-you-choose-vn-video-editor-pro-for-your-video-editing-needs-for-2024/"><u>New Should You Choose VN Video Editor Pro for Your Video Editing Needs for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-the-ultimate-sandbox-experience-playlist-for-2024/"><u>[New] The Ultimate Sandbox Experience Playlist for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-here-are-the-apps-that-we-recommended-to-blur-a-face-or-any-part-of-an-image-just-moments-after-youve-recorded-a-video-or-taken-a-photo-for-2024/"><u>Updated Here Are the Apps that We Recommended to Blur a Face or Any Part of an Image Just Moments After Youve Recorded a Video or Taken a Photo for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/refreshing-classic-directx-games-with-dxvk-upgrades/"><u>Refreshing Classic DirectX Games with DXVK Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-variances-a-comparison-between-microsoft-and-standard-windows-accounts/"><u>Exploring Variances: A Comparison Between Microsoft and Standard Windows Accounts</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-power-of-your-laptops-touch-sensitivity-with-ease/"><u>Unleash the Power of Your Laptop's Touch Sensitivity with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/winning-speed-efficient-download-strategies-for-valorant-on-pc/"><u>Winning Speed: Efficient Download Strategies for Valorant on PC</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-winupdate-error-x8019/"><u>Troubleshooting WinUpdate Error X8019</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/how-to-dive-into-a-friends-life-without-fuss-on-tiktok-for-2024/"><u>How To Dive Into a Friend's Life Without Fuss on TikTok for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-sketches-to-stakes-leading-platforms-turning-art-into-nfts/"><u>2024 Approved  From Sketches to Stakes  Leading Platforms Turning Art Into NFTs</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-xbox-mic-use-with-windows-11-app/"><u>Unblocking Xbox Mic Use with Windows 11 App</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-taskbar-design-proposals-for-windows-11s-user-interaction-improvements/"><u>Elevating Taskbar Design: Proposals for Windows 11'S User Interaction Improvements</u></a></li>
<li><a href="https://extra-tips.techidaily.com/amplifying-your-youtube-presentation-size-for-2024/"><u>Amplifying Your YouTube Presentation Size for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-saving-your-best-on-instagram-a-comprehensive-guide/"><u>[Updated] In 2024, Saving Your Best on Instagram  A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-lsassexe-unable-to-locate-error-on-win-810/"><u>How to Overcome lsass.exe Unable to Locate Error on Win 8/10</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-chromes-false-virus-detection-issue/"><u>Overcoming Chrome’s False Virus Detection Issue</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/explore-tools-that-beat-sharex-performance/"><u>Explore Tools That Beat ShareX Performance</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-lecturers-guide-to-efficient-classroom-sound-archiving-on-macs/"><u>[Updated] Lecturer's Guide to Efficient Classroom Sound Archiving on Macs</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-melodic-movies-the-art-of-making-musical-reels/"><u>[New] Melodic Movies  The Art of Making Musical Reels</u></a></li>
<li><a href="https://win11.techidaily.com/preserving-customization-transferring-powertoys-to-a-new-machine/"><u>Preserving Customization: Transferring PowerToys to a New Machine</u></a></li>
</ul></div>
