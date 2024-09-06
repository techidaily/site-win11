---
title: "Resolving Directory Fullness Errors with Code: 0X80070091 on Windows 11"
date: 2024-09-05T08:30:07.839Z
updated: 2024-09-06T08:30:07.839Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resolving Directory Fullness Errors with Code: 0X80070091 on Windows 11"
excerpt: "This Article Describes Resolving Directory Fullness Errors with Code: 0X80070091 on Windows 11"
keywords: Directory Fullness Fix Win11,0X80070091 Resolution Win11,Stop File Error Code 0X80070091,Windows 11 Directory Space Issue,Handling OSError 70070091,Solving Full Disk in Windows 11,Addressing 0X70070091 Errors Win11
thumbnail: https://thmb.techidaily.com/bab37a5357094e09dd42f37d3cc78e25fe907bbcf4a7b3121bebc119dc83e730.jpg
---

## Resolving Directory Fullness Errors with Code: 0X80070091 on Windows 11

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

## 1\. Try Erasing the Folder With the Command Prompt

 The Command Prompt gives users another way to delete folders in Windows 11/10\. So, you might be able to erase an affected folder without issues by using the Command Prompt. Using the Command Prompt might be more of a workaround, but at least you’ll get the folder deleted if works.

 Run Command Prompt with elevated (administrative) rights. Our guide about[running Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) includes numerous methods for launching that app. Then input this command and press**Enter** to delete an affected folder:

`rmdir /s "folder path"`

 You’ll need to replace**folder path** in that command with the location of whatever directory you need to delete. The location should include a drive letter and a full path for the directory like in this example:

`rmdir /s "C:\Users\New folder"`

![The delete folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-folder-command.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2121335/18498" target="_top" id="2121335">
  <img src="//a.impactradius-go.com/display-ad/18498-2121335" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2121335/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
3. Press the**Restart** button for the selected Explorer process.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130531/26400" target="_top" id="2130531">
  <img src="//a.impactradius-go.com/display-ad/26400-2130531" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130531/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for[running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123749/7443" target="_top" id="2123749">
  <img src="//a.impactradius-go.com/display-ad/7443-2123749" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123749/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Check for Errors With a Disk Scan

 The 0x80070091 error is often due to corrupted or bad hard drive sectors. A lot of users have said they’ve resolved that issue by using the Check Disk (CHKDSK) utility for repairing bad drive sectors. This is how you can check for and repair bad sectors with Check Disk:

1. Open up the Command Prompt window with administrative rights.
2. Type in this Check Disk command and press**Enter:**  
`chkdsk /f /r C:`
3. Press**Y** to schedule the scan for a restart.  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk-scan-command.jpg)
4. Click**Start** and select**Power** \>**Restart** to reboot.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136621/26400" target="_top" id="2136621">
  <img src="//a.impactradius-go.com/display-ad/26400-2136621" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136621/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the folder the 0x80070091 error occurs for isn’t on the C: drive, you’ll need to modify the above command. Replace**C:** with the letter of the storage drive that includes the affected folder.

## 5\. Modify the Affected Folder’s Permissions

 Error 0x80070091 can arise because of insufficient folder permission. You might need to set an affected folder to full permission to resolve error 0x80070091\. To do that, change the folder’s permission settings as follows:

1. Open Explorer and right-click the affected folder to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option.jpg)
2. Click the window’s**Security** tab.
3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
4. Click**Change** beside the owner’s name.  
![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
5. Enter your Windows user account name inside the object name text box.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130886/7443" target="_top" id="2130886">
  <img src="//a.impactradius-go.com/display-ad/7443-2130886" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130886/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Select a User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/select-a-user-or-group.jpg)
6. Then select the**Check Names** option and**OK** .
7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126493/26400" target="_top" id="2126493">
  <img src="//a.impactradius-go.com/display-ad/26400-2126493" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126493/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Run an Antivirus Scan

 Malware could also feasibly be causing error 0x80070091 on your PC. If you’re still trying to fix that issue after going through all the potential fixes above, run an antivirus scan with Windows Security or alternative third-party software. This is how to run a scan with the Windows Security app.

1. Double-click a**Windows Security** (shield) icon in the system tray part of the taskbar.
2. Click**Virus & threat protection** \>**Scan options** to view all options for scanning.  
![The Scan options navigation link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-scan-options-link.jpg)
3. Select the most thorough**Full Scan** option, which could take more than an hour to finish.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118315/7443" target="_top" id="2118315">
  <img src="//a.impactradius-go.com/display-ad/7443-2118315" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118315/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
4. Press**Scan now** to start the antivirus scanning.
<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014859/22899" target="_top" id="2014859">
  <img src="//a.impactradius-go.com/display-ad/22899-2014859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014859/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139109/17108" target="_top" id="2139109">
  <img src="//a.impactradius-go.com/display-ad/17108-2139109" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139109/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Delete Your Folders in File Explorer Again With These Fixes

 You’ll probably be able to delete the folders for which error 0x80070091 occurred after applying those potential solutions. If that error persists, the Windows registry on your PC could be corrupted. To resolve such registry issues, you might need to perform a system restore or even reset Windows 11/10.

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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-deciphering-the-wealth-of-mr-beast/"><u>[New] 2024 Approved  Deciphering the Wealth of Mr. Beast</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-first-timer-accessories-transform-your-gopro-experience/"><u>[New] 2024 Approved  First-Timer Accessories - Transform Your GoPro Experience</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-seamless-shoot-and-stream-perfecting-dslr-broadcasts-from-home-pcsmacs/"><u>[New] 2024 Approved  Seamless Shoot & Stream  Perfecting DSLR Broadcasts From Home PCs/Macs</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-instant-recording-tips-for-facetime-chats/"><u>[New] Instant Recording Tips for FaceTime Chats</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-the-gopro-hero-series-comparison/"><u>[New] The GoPro Hero Series Comparison</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-chorus-of-commitment-best-ballads-for-marital-dreaming/"><u>[Updated] Chorus of Commitment  Best Ballads for Marital Dreaming</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-best-buy-top-10-gaming-gpus-for-high-quality-online-viewing/"><u>[Updated] In 2024, Best Buy  Top 10 Gaming GPUs for High-Quality Online Viewing</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-boost-views-through-effective-youtube-thumbnail-selection/"><u>[Updated] In 2024, Boost Views Through Effective YouTube Thumbnail Selection</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-exclusive-rescue-regaining-fb-passwords/"><u>[Updated] In 2024, Exclusive Rescue  Regaining FB Passwords</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-most-popular-image-stickering-apps-iosandroid-edition/"><u>[Updated] In 2024, Most Popular Image Stickering Apps – iOS/Android Edition</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unveiling-the-secrets-of-whatsapp-audio-conversations/"><u>[Updated] Unveiling the Secrets of WhatsApp Audio Conversations</u></a></li>
<li><a href="https://program-issues.techidaily.com/biomutant-troubleshooting-top-strategies-to-resolve-pc-issues/"><u>Biomutant Troubleshooting: Top Strategies to Resolve PC Issues</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-itel-a70-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Itel A70 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/cut-the-cost-boost-quality-wins-finest-players/"><u>Cut the Cost, Boost Quality: Win's Finest Players</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-fixing-common-issues-in-windows-camera/"><u>Decoding and Fixing Common Issues in Windows Camera</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-no-more-files-notifications-on-win-11/"><u>Disabling 'No More Files' Notifications on Win 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/dive-into-the-future-of-branding-with-these-10-igtv-ideas/"><u>Dive Into the Future of Branding with These 10 IGTV Ideas</u></a></li>
<li><a href="https://win11.techidaily.com/double-the-fun-with-a-swifter-mouse-click-process/"><u>Double the Fun with a Swifter Mouse Click Process</u></a></li>
<li><a href="https://win11.techidaily.com/examining-wsls-influence-on-linux-adoption/"><u>Examining WSL's Influence on Linux Adoption</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-application-couldnt-start-0xc000003e-hexadecimal-error/"><u>Fixing The Application Couldn't Start 0xC000003E Hexadecimal Error</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/from-frames-to-frequencies-transforming-instagram-videos/"><u>From Frames to Frequencies  Transforming Instagram Videos</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-samsung-galaxy-f54-5g-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Samsung Galaxy F54 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-the-windows-11-login-method-from-pin-to-password/"><u>How to Change the Windows 11 Login Method From PIN to Password</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-eliminate-obs-studio-error-windows-edition-strategy/"><u>How to Eliminate OBS Studio Error: Windows Edition Strategy</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-not-enough-usb-controller-resources-error-on-a-windows-computer/"><u>How to Fix “Not Enough USB Controller Resources” Error on a Windows Computer</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-make-the-most-of-your-iphone-xr-lock-screen-with-notifications-by-drfone-ios/"><u>How to Make the Most of Your iPhone XR Lock Screen with Notifications?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-msstore-crash-with-error-code-0x0-on-windows-1011/"><u>How to Overcome MsStore Crash with Error Code 0X0 on Windows 10/11</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/how-to-track-apple-iphone-xs-location-without-installing-software-drfone-by-drfone-virtual-ios/"><u>How to Track Apple iPhone XS Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-vivo-y55s-5g-2023-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track Vivo Y55s 5G (2023) Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/ideal-drawers-for-win-11-a-comprerancial-guide-to-best-apps/"><u>Ideal Drawers for Win 11: A Comprerancial Guide to Best Apps</u></a></li>
<li><a href="https://win11.techidaily.com/illuminating-holiday-joy-window-decor-inspirations/"><u>Illuminating Holiday Joy - Window Decor Inspirations</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-apple-iphone-15-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change Location On Facebook Dating for your Apple iPhone 15 Plus | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-revolutionize-your-social-media-strategy-essential-instagram-analytics-platforms/"><u>In 2024, Revolutionize Your Social Media Strategy  Essential Instagram Analytics Platforms</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-two-ways-to-sync-contacts-from-xiaomi-redmi-note-12-pro-5g-to-gmail-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Two Ways to Sync Contacts from Xiaomi Redmi Note 12 Pro 5G to Gmail | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/master-plan-to-conquer-windows-os-errors/"><u>Master Plan to Conquer Windows OS Errors</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-macos-with-external-windows-programs/"><u>Mastering macOS with External Windows Programs</u></a></li>
<li><a href="https://win-answers.techidaily.com/mastering-troubleshooting-8-key-strategies-to-resolve-vrchat-crashes-on-desktops/"><u>Mastering Troubleshooting: 8 Key Strategies to Resolve VRChat Crashes on Desktops</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-your-drive-space-a-disc-usage-command-breakdown/"><u>Navigating Through Your Drive Space: A Disc Usage Command Breakdown</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-retro-clips-using-madvr-software-for-pcs/"><u>Optimize Retro Clips Using MadVR Software for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unsuccessful-share-attempts-in-nvidias-experience/"><u>Overcoming Unsuccessful Share Attempts in NVIDIA's Experience</u></a></li>
<li><a href="https://win11.techidaily.com/quick-cure-all-ppt-save-errors-6-must-try-methods-in-win11/"><u>Quick Cure-All PPT Save Errors: 6 Must-Try Methods in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-insight-are-you-ready-for-windows-11/"><u>Quick Insight: Are You Ready for Windows 11?</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/-tips-to-create-dynamic-gifs-using-youtube-media/"><u>Quick Tips to Create Dynamic GIFs Using YouTube Media</u></a></li>
<li><a href="https://discord-videos.techidaily.com/real-time-interaction-best-practices-for-discord-streamers-for-2024/"><u>Real-Time Interaction  Best Practices for Discord Streamers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-1011-nvidia-connectivity-flaws/"><u>Resolving Windows 10/11 NVIDIA Connectivity Flaws</u></a></li>
<li><a href="https://win11.techidaily.com/screen-splendor-series-designing-distinct-displays-on-win-1011-per-monitor/"><u>Screen Splendor Series: Designing Distinct Displays on WIN 10/11 Per Monitor</u></a></li>
<li><a href="https://win11.techidaily.com/shielding-windows-default-screen-display-from-user-changes/"><u>Shielding Windows Default Screen Display From User Changes</u></a></li>
<li><a href="https://win11.techidaily.com/skip-steps-to-sidestep-login-questions-on-windows-11-local/"><u>Skip Steps to Sidestep Login Questions on Windows 11 Local</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-approach-to-fix-windows-charmap-woes/"><u>Streamlining Your Approach to Fix Windows CharMap Woes</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/superior-selection-best-windows-videophone-apps-guide-for-2024/"><u>Superior Selection  Best Windows Videophone Apps Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/switch-your-windows-11-preferred-apps/"><u>Switch Your Windows 11 Preferred Apps</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-the-failed-to-install-discord-error-win/"><u>Tackling the Failed to Install Discord Error (Win)</u></a></li>
<li><a href="https://win11.techidaily.com/the-project-pro-essential-ms-project-keys-explained/"><u>The Project Pro: Essential MS Project Keys Explained</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-list-for-windows-multi-monitor-brightness-tuning/"><u>The Ultimate List for Windows Multi-Monitor Brightness Tuning</u></a></li>
<li><a href="https://win11.techidaily.com/tomorrows-technology-today-a-new-windows-era/"><u>Tomorrow's Technology Today: A New Windows Era</u></a></li>
<li><a href="https://win11.techidaily.com/total-methodology-for-disabling-windows-subsystem-for-linux/"><u>Total Methodology for Disabling Windows Subsystem for Linux</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-windows-update-mysteries/"><u>Unpacking Window's Update Mysteries</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/webcam-tricks-for-smooth-video-on-hp-devices-for-2024/"><u>Webcam Tricks for Smooth Video on HP Devices for 2024</u></a></li>
</ul></div>
