---
title: "Revive Your Windows 11: Re-Activate MS Store Applications"
date: 2024-07-13T10:30:24.226Z
updated: 2024-07-14T10:30:24.226Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Revive Your Windows 11: Re-Activate MS Store Applications"
excerpt: "This Article Describes Revive Your Windows 11: Re-Activate MS Store Applications"
keywords: Reactivate W11 MSStore,Reset Windows 11 Apps,Revive Windows Store,Update MSStore,Fix Windows App Error,Re-Activate W11 Store,Restart W11 MSApps
thumbnail: https://thmb.techidaily.com/371f85ea9dfa1babb000dca91773b4eb09149fff5b762b5c34efcbd5187b5306.jpg
---

## Revive Your Windows 11: Re-Activate MS Store Applications

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the [Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.


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
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-the-windows-11-mixer-interface/"><u>A Beginner’s Guide to the Windows 11 Mixer Interface</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-open-the-sound-settings-in-windows-11/"><u>9 Ways to Open the Sound Settings in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-fix-slack-notifications-not-working-on-windows-11/"><u>8 Ways to Fix Slack Notifications Not Working on Windows 11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-spark-conversation-crafting-questions-for-ig-story-boost/"><u>In 2024, Spark Conversation  Crafting Questions for IG Story Boost</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-factory-reset-your-windows-computer/"><u>3 Ways to Factory Reset Your Windows Computer</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-restoring-content-servers-connectivity/"><u>A Step-by-Step Guide to Restoring Content Servers' Connectivity</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-snap-and-save-your-android-no-price-tag/"><u>2024 Approved  Snap & Save Your Android - No Price Tag</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-ultimate-software-guide-to-gamers-broadcast/"><u>[New] Ultimate Software Guide to Gamers' Broadcast</u></a></li>
<li><a href="https://youtube-web.techidaily.com/n-2024-seamlessly-integrating-device-screens-into-your-youtube-projects/"><u>[New] In 2024, Seamlessly Integrating Device Screens Into Your YouTube Projects</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-recover-an-off-screen-window-in-windows-11-and-11/"><u>6 Ways to Recover an Off-Screen Window in Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-look-at-triggering-system-restore-in-windows-11/"><u>A Detailed Look at Triggering System Restore in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719367447353-multiplying-malware-defenses-think-again-windows/"><u>Multiplying Malware Defenses? Think Again, Windows</u></a></li>
<li><a href="https://article-tips.techidaily.com/unparalleled-camera-tech-s-filmmaking-for-2024/"><u>Unparalleled Camera Tech 'S Filmmaking for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719366357478-6-ultimate-methods-to-end-stuck-windows-updates-now/"><u>6 Ultimate Methods to End Stuck Windows Updates Now</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/premium-desktop-and-mobile-video-call-platforms-zoom-replacements-for-2024/"><u>Premium Desktop & Mobile Video Call Platforms (Zoom Replacements) for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-remove-faces-from-photos-and-videos-the-best-10-free-apps-for-anonymization/"><u>2024 Approved Remove Faces From Photos and Videos The Best 10 Free Apps for Anonymization</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-walkthrough-windows-11-calendar/"><u>A Comprehensive Walkthrough: Windows 11 Calendar</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-pcs-wake-up-time-enabling-quick-start/"><u>Accelerate Your PC's Wake-Up Time: Enabling Quick Start</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/perfecting-the-aesthetic-ootd-tiktok-on-a-mac-for-2024/"><u>Perfecting the Aesthetic  OOTD TikTok on a Mac for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-from-meta-to-omni-a-new-age-digital-odyssey-guide/"><u>In 2024, From Meta to Omni  A New Age Digital Odyssey Guide</u></a></li>
<li><a href="https://win11.techidaily.com/1719338015239-team-share-dilemma-heres-the-solution/"><u>Team Share Dilemma? Here's the Solution</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-the-history-button-navigating-old-facebook-stories/"><u>2024 Approved  The History Button  Navigating Old Facebook Stories</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-fixing-your-windows-photo-app/"><u>A Comprehensive Guide to Fixing Your Windows Photo App</u></a></li>
<li><a href="https://youtube-data.techidaily.com/he-most-popular-6-free-and-quick-youtube-video-repositories-for-2024/"><u>[New] The Most Popular 6  Free & Quick YouTube Video Repositories for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-open-the-startup-repair-tool-on-windows/"><u>5 Ways to Open the Startup Repair Tool on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/8-handy-windows-11-and-11-command-shortcuts-you-can-set-up-with-nircmd/"><u>8 Handy Windows 11 & 11 Command Shortcuts You Can Set Up With NirCmd</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-limitless-screen-recording-with-no-brand-identity/"><u>[Updated] 2024 Approved  Limitless Screen Recording with No Brand Identity</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-for-overcoming-the-pink-flash/"><u>A Comprehensive Guide for Overcoming the Pink Flash</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-quickly-launch-apps-on-windows-11/"><u>5 Ways to Quickly Launch Apps on Windows 11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-elevate-your-profile-instagram-voice-alteration-guide/"><u>In 2024, Elevate Your Profile  Instagram Voice Alteration Guide</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-compiling-leading-short-form-video-editors-iosandroid-edition/"><u>In 2024, Compiling Leading Short-Form Video Editors  IOS/Android Edition</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-delete-a-drive-partition-on-windows/"><u>4 Ways to Delete a Drive Partition on Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-deciphering-highlighted-discussion-threads/"><u>[New] In 2024, Deciphering Highlighted Discussion Threads</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-chuckle-laugh-moments-and-tears-from-these-top-ten-ig-feeds/"><u>[New] In 2024, Chuckle-Laugh Moments & Tears From These Top Ten IG Feeds</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-workflow-efficiency-introducing-flow-launcher-methodology/"><u>Accelerate Workflow Efficiency: Introducing Flow Launcher Methodology</u></a></li>
<li><a href="https://win11.techidaily.com/7-actionable-tips-to-reduce-gaming-pcs-gui-load/"><u>7 Actionable Tips to Reduce Gaming PC's GUI Load</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-tidy-up-video-borders-with-smart-edit-techniques/"><u>[New] 2024 Approved  Tidy Up Video Borders with Smart Edit Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-troubleshooting-windows-desktop-icons/"><u>A Guide to Troubleshooting Windows Desktop Icons</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-channel-prominence-mastery-a-comprehensive-youtube-guide/"><u>2024 Approved  Channel Prominence Mastery  A Comprehensive YouTube Guide</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-fix-the-network-security-key-mismatch-error-on-windows-11/"><u>5 Ways to Fix the Network Security Key Mismatch Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-stepwise-approach-to-win11s-hyper-v-activation/"><u>A Stepwise Approach to Win11's Hyper-V Activation</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-sluggish-windows-based-excel-processes/"><u>Accelerate Sluggish Windows-Based Excel Processes</u></a></li>
<li><a href="https://win11.techidaily.com/1719322695938-new-windows-11-users-beware-of-these-top-8-errors/"><u>New Windows 11 Users, Beware of These Top 8 Errors</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-the-ultimate-tutorial-for-novices-navigating-wave-editor-features/"><u>New The Ultimate Tutorial for Novices Navigating Wave Editor Features</u></a></li>
<li><a href="https://iphone-location.techidaily.com/double-location-dongle-all-to-know-about-apple-iphone-15-plusipad-gps-spoofing-drfone-by-drfone-virtual-ios/"><u>Double Location Dongle All to Know About Apple iPhone 15 Plus/iPad GPS Spoofing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-journey-into-celestial-mastery-windows-11s-divine-control/"><u>A Journey Into Celestial Mastery: Windows 11'S Divine Control</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-evaluate-apps-in-depth-az-screen-logger/"><u>[Updated] Evaluate Apps in Depth  AZ Screen Logger</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-samsung-galaxy-m34-lock-screen-clock-in-seconds-by-drfone-android/"><u>In 2024, How To Change Samsung Galaxy M34 Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://win11.techidaily.com/1719366214502-efficient-support-paths-for-common-windows-concerns/"><u>Efficient Support Paths for Common Windows Concerns!</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-the-ultimate-guide-to-youtube-video-distribution-on-fb-for-2024/"><u>[New] The Ultimate Guide to YouTube Video Distribution on FB for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-exit-recovery-mode-on-iphone-14-pro-max-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Exit Recovery Mode on iPhone 14 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-enable-compact-view-in-file-explorer-on-windows-11/"><u>3 Ways to Enable Compact View in File Explorer on Windows 11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-streamline-your-audio-capture-with-these-top-5-mp3-specific-recording-devices/"><u>New Streamline Your Audio Capture with These Top 5 MP3-Specific Recording Devices</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-the-creative-process-behind-bigger-head-effects-for-tiktok-films-3-techniques/"><u>[Updated] In 2024, The Creative Process Behind Bigger-Head Effects for TikTok Films (3 Techniques)</u></a></li>
<li><a href="https://win11.techidaily.com/1719383152108-tackle-lagginess-in-winoutlook-effortlessly/"><u>Tackle Lagginess in WinOutlook, Effortlessly</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-in-this-article-we-will-compare-sony-vegas-and-adobe-premiere-about-workflow-output-and-usability-and-you-will-see-which-one-is-better-for-y/"><u>Updated In 2024, In This Article, We Will Compare Sony Vegas and Adobe Premiere About Workflow, Output and Usability, and You Will See Which One Is Better for You</u></a></li>
</ul></div>
