---
title: "Windows Lacks Drive Letters: Why and How to Rectify This Issue."
date: 2024-09-05T08:46:51.293Z
updated: 2024-09-06T08:46:51.293Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Lacks Drive Letters: Why and How to Rectify This Issue."
excerpt: "This Article Describes Windows Lacks Drive Letters: Why and How to Rectify This Issue."
keywords: Windows Drive Issues,Missing Disk Letters,Fixing Windows Errors,Adding Drives in WinOS,System File Corruption,Registry Edit for Disks,OS Boot Configuration
thumbnail: https://thmb.techidaily.com/61e1fbca092ac5d2ffa00e76582e3823f6ee9bd8608e03fb6613489ba0869657.jpg
---

## Windows Lacks Drive Letters: Why and How to Rectify This Issue

 Seeing the error message "drive letter not available" when accessing or creating a new storage drive can be very frustrating. The reason for the error isn't always immediately obvious, but it is rarely unsolvable.

 Here are the most common causes for an unavailable drive letter on Windows, and ways you can fix the problem.

## What Are Drive Letters in Windows?

 Any new storage drive, volume, or partition you add to your computer (especially if you[add a partition to your hard drive for optimum performance](https://www.makeuseof.com/how-to-partition-hard-drive/) ) needs to have a letter assigned before it will work. It is basically a label, a way for the system and the user to recognize different storage spaces.

 If a drive or partition does not have a letter assigned, it will be inaccessible to you and the software and services that may need to see the files in that space.

 Drive letters, occasionally called device letters, run alphabetically from A to Z. These days, A and B are rarely used, and we've covered before[why local drives on Windows start from "C"](https://www.makeuseof.com/why-local-drives-windows-start-from-c/) .

 New storage devices will be automatically assigned the first unused letter when connected. This automatic process occasionally fails or gets blocked by a conflict in the system settings.

 Upgrading from an older version of Windows to a new version can sometimes cause drive letters to be reassigned. Let's say that your applications all point to a particular drive, but that drive is now assigned a different letter. Things will get frustrating quickly if you can't select the letter you need.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139108/17108" target="_top" id="2139108">
  <img src="//a.impactradius-go.com/display-ad/17108-2139108" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139108/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Reasons Why Drive Letters Are Unavailable

 As mentioned, there are several possible reasons why you might see the "Drive letter not available" error. The most common reasons include:

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118326/7443" target="_top" id="2118326">
  <img src="//a.impactradius-go.com/display-ad/7443-2118326" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118326/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### The Letter Is In Use by a Hidden Removable Drive

 When you connect a removable drive, such as a USB thumb drive, a drive letter will be assigned to it. Sometimes even after the removable drive is disconnected, the drive letter remains associated with it. In this case, it will be unavailable, and you'll see the error message.

### The Letter Is Permanently Assigned to Another Storage Volume

 It is possible to permanently assign a drive letter to a particular partition or drive. This also includes optical devices like the CD/DVD drive. If you have previously done this, the drive letter will no longer be available to choose from when setting up a new partition or drive.

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114263/17093" target="_top" id="2114263">
  <img src="//a.impactradius-go.com/display-ad/17093-2114263" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114263/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Make Drive Letters Available for Use

 Both of the causes for the error detailed above are fixable. You can download free software to help with reassigning the letters. But you can also use the Windows Registry Editor to solve the problem yourself. Here's how.

1. Open the**Run dialog** by pressing**Win + R** .
2. Type**Regedit** and click**Ok** to open the Registry Editor.
3. Using either the panel on the left or the address field at the top, navigate to:**HKEY\_LOCAL\_MACHINE\\SYSTEM\\MountedDevices** .  
![Mounted devices in the Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/drive-letter-registry.jpg)
4. In the list of assigned devices, right-click on the one you want to change and select**Rename** .
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135398/19272" target="_top" id="2135398">
  <img src="//a.impactradius-go.com/display-ad/19272-2135398" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135398/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Change the drive letter to any other unused letter to free up the one being used.
6. Close the Registry Editor and restart your computer. You should then be able to assign the unused letter as you wish.

 If you prefer not to mess around with the Registry directly, you can use something like[AOMEI Partition Assistant Standard](https://www.diskpart.com/download-home.html) . The free version has limited tools but will let you reassign drive letters.

1. Open the Partition Assistant app and find the drive you want to reassign in the main window.
2. Right-click on the drive and select**Advanced > Change Drive Letter** from the menu.
3. In the new panel, use the dropdown menu to select a new and unused drive letter.  
![Changing a drive letter in third-party software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/partition-assistant-driveletter.jpg)
4. Click**Ok** and confirm the operation on the next screen. It may take a few seconds to process the change.
<!-- affiliate ads begin -->
<span id="1993654">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993654.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993654">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993654.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993654%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993654/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. You can then return to the main screen, find the drive to which you want to assign that released letter, and repeat the process.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139563/4704" target="_top" id="2139563">
  <img src="//a.impactradius-go.com/display-ad/4704-2139563" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139563/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Getting a Drive Letter Back on Windows

 Although frustrating, seeing the "Drive Letter Not Available" error is rarely due to an unsolvable issue. In most cases, you just need to force the change using the Registry Editor or a bit of third-party software. Either solution is fast and easy and should see your desired drive letter free to use quickly.


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
<li><a href="https://screen-capture.techidaily.com/new-become-an-engaging-speaker-on-google-meet-platforms/"><u>[New] Become an Engaging Speaker on Google Meet Platforms</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-binge-worthy-20-catchy-tiktok-songs-by-artists-for-2024/"><u>[New] Binge-Worthy  20 Catchy TikTok Songs by Artists for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-screenmagic-pro-the-windows-10-companion/"><u>[New] In 2024, ScreenMagic Pro  The Windows 10 Companion</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-roadmap-to-seamless-mass-tiktok-downloads-for-2024/"><u>[New] The Roadmap to Seamless Mass TikTok Downloads for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-boost-viewership-mastering-vimeo-distribution/"><u>[Updated] In 2024, Boost Viewership  Mastering Vimeo Distribution</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-who-rules-the-realm-of-youtube/"><u>[Updated] In 2024, Who Rules the Realm of YouTube?</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-recording-your-world-how-camstudio-redefined/"><u>2024 Approved  Recording Your World - How CamStudio Redefined</u></a></li>
<li><a href="https://win11.techidaily.com/comprehending-winservicesexe-for-effective-troubleshooting/"><u>Comprehending Winservices.exe for Effective Troubleshooting</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-update-failure-error-0x8e00c/"><u>Correcting Windows Update Failure (Error 0X8e00c)</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-windows-bar-to-reflect-internet-speed/"><u>Customizing Windows Bar to Reflect Internet Speed</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-repairing-the-application-failed-to-launch-code-0xc000003e-on-win11/"><u>Deciphering and Repairing The Application Failed to Launch: Code 0XC000003E on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-windows-11s-net-settings/"><u>Delving Into Windows 11'S Net Settings</u></a></li>
<li><a href="https://win11.techidaily.com/disguising-windows-11-taskbars-task-view-control/"><u>Disguising Windows 11 TaskBar's Task View Control</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-11-update-failure-code-0x800f0922/"><u>Eliminating Windows 11 Update Failure - Code 0X800f0922</u></a></li>
<li><a href="https://win11.techidaily.com/empower-your-pc-with-these-critical-windows-update-tips/"><u>Empower Your PC with These Critical Windows Update Tips</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/full-examination-of-razer-kiyo-cam/"><u>Full Examination of Razer Kiyo Cam</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-avi-files-of-oppo-reno-8t-5g-with-video-repair-utility-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and AVI files of Oppo Reno 8T 5G with Video Repair Utility on Mac?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-switch-off-virtualization-on-windows-11/"><u>How to Switch Off Virtualization on Windows 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-oneplus-nord-n30-5g-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock OnePlus Nord N30 5G Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unmute-yourself-on-google-meet-windows-edition/"><u>How to Unmute Yourself on Google Meet, Windows Edition</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-6-methods-for-switching-from-apple-iphone-12-to-samsung-drfone-by-drfone-transfer-from-ios/"><u>In 2024, 6 Methods for Switching from Apple iPhone 12 to Samsung | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-best-tecno-pova-5-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>In 2024, Best Tecno Pova 5 Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-elevate-your-audio-game-with-free-vocal-effects/"><u>In 2024, Elevate Your Audio Game with Free Vocal Effects</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-full-guide-to-unlock-your-samsung-galaxy-f04-by-drfone-android/"><u>In 2024, Full Guide to Unlock Your Samsung Galaxy F04</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-lock-screen-wallpaper-on-samsung-galaxy-f04-by-drfone-android/"><u>In 2024, How to Change Lock Screen Wallpaper on Samsung Galaxy F04</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-apple-iphone-6-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, How to get the dragon scale and evolution-enabled pokemon On Apple iPhone 6 Plus? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-icloud-lock-on-your-apple-iphone-13-mini-and-ipad-by-drfone-ios/"><u>In 2024, How to Unlock iCloud lock on your Apple iPhone 13 mini and iPad?</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-insider-tips-on-finding-and-designing-standout-instagram-ringtone-alerts/"><u>In 2024, Insider Tips on Finding & Designing Standout Instagram Ringtone Alerts</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-maximizing-audio-capture-essential-techniques-for-facetime/"><u>In 2024, Maximizing Audio Capture  Essential Techniques for FaceTime</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-perfect-your-game-with-these-top-7-stardew-valley-modifications/"><u>In 2024, Perfect Your Game with These Top 7 Stardew Valley Modifications</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-still-using-pattern-locks-with-motorola-moto-g-stylus-5g-2023-tips-tricks-and-helpful-advice-by-drfone-android/"><u>In 2024, Still Using Pattern Locks with Motorola Moto G Stylus 5G (2023)? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-unveiling-the-secrets-of-crafting-perfect-audio-for-videos/"><u>In 2024, Unveiling the Secrets of Crafting Perfect Audio for Videos</u></a></li>
<li><a href="https://techtrends.techidaily.com/invest-wisely-why-you-shouldnt-pay-over-1000-for-a-standard-cell-phone/"><u>Invest Wisely: Why You Shouldn't Pay over $1,000 for a Standard Cell Phone</u></a></li>
<li><a href="https://facebook.techidaily.com/making-the-most-of-facebooks-3d-feature/"><u>Making the Most of Facebook's 3D Feature</u></a></li>
<li><a href="https://win-able.techidaily.com/masterclass-diagnose-and-repair-counter-strike-global-offensives-startup-problems/"><u>Masterclass: Diagnose and Repair Counter-Strike Global Offensive's Startup Problems</u></a></li>
<li><a href="https://win11.techidaily.com/mending-failed-volume-backup-in-microsoft-os/"><u>Mending Failed Volume Backup in Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/mending-window-11-opengl-driver-flaw-code-3/"><u>Mending Window 11 OpenGL Driver Flaw Code #3</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-git-branches-using-github-desktop-in-win-11/"><u>Navigating Git Branches Using GitHub Desktop in Win 11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/next-execute-a-dism-scan-by-typing-dism-online-cleanup-image-restorehealth-into-the-command-prompt-and-press-enter-this-will-also-take-some-time-to-complete76/"><u>Next, Execute a DISM Scan by Typing `DISM /Online /Cleanup-Image /RestoreHealth` Into the Command Prompt and Press Enter. This Will Also Take some Time to Complete as It Scans All System Images on Your Computer.</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-collaboration-and-efficiency-master-these-5-innovative-window-tips/"><u>Optimize Collaboration and Efficiency: Master These 5 Innovative Window Tips</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-device-freeze-fixing-error-0x887a0006/"><u>Overcoming Device Freeze: Fixing Error 0X887A0006</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-nvidia-experience-connection-issues-on-win-11/"><u>Overcoming Nvidia Experience Connection Issues on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-your-file-organization-skills-in-windows-11-edition/"><u>Perfect Your File Organization Skills in Windows 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-windows-blue-screen-due-to-not-handled-errors/"><u>Preventing Windows Blue Screen Due to Not Handled Errors</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-to-handle-user-profile-errors-in-w11os/"><u>Quick Fixes to Handle User Profile Errors in W11OS</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-inconsistent-windows-thx-audio-output/"><u>Rectifying Inconsistent Windows THX Audio Output</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-windows-11s-video-conferencing-snag-code-1132/"><u>Rectifying Windows 11'S Video Conferencing Snag: Code 1132</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-ios-images-errors-when-importing-to-windows-os/"><u>Resolving iOS Images Errors When Importing to Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-unauthorized-user-profile-issue-in-windows/"><u>Resolving Unauthorized User Profile Issue in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-correcting-code-0x0000004e-on-pcs/"><u>Solutions for Correcting Code 0X0000004E on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-system-recalibration-windows-update-restart-guide/"><u>Streamlining System Recalibration: Windows Update Restart Guide</u></a></li>
<li><a href="https://win11.techidaily.com/switching-up-your-desktop-how-to-change-themes-in-win11/"><u>Switching Up Your Desktop: How To Change Themes in Win11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/the-ultimate-ranking-of-smart-spectacles-find-your-perfect-pair/"><u>The Ultimate Ranking of Smart Spectacles – Find Your Perfect Pair</u></a></li>
<li><a href="https://win11.techidaily.com/tips-and-tricks-for-resurrecting-non-operative-resource-monitors-in-win11/"><u>Tips & Tricks for Resurrecting Non-Operative Resource Monitors in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-strategies-for-a-more-efficient-windows-11-search-experience/"><u>Top 5 Strategies for a More Efficient Windows 11 Search Experience</u></a></li>
<li><a href="https://win-able.techidaily.com/understanding-and-fixing-the-persistent-ntdlldll-system-crashes-in-modern-operating-systems/"><u>Understanding and Fixing the Persistent ntdll.dll System Crashes in Modern Operating Systems</u></a></li>
<li><a href="https://win11.techidaily.com/ungroup-taskbar-on-win-11-simple-steps/"><u>Ungroup Taskbar on Win 11 - Simple Steps</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-high-fidelity-audio-dolby-atmos-integration-steps/"><u>Unlocking High-Fidelity Audio: Dolby Atmos Integration Steps</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-more-secure-future-with-windows-11s-updated-support-schedule/"><u>Unveiling More Secure Future With Windows 11'S Updated Support Schedule</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-arm-installation-made-simple-via-iso-download-guide/"><u>Windows 11 ARM Installation Made Simple via ISO Download Guide</u></a></li>
</ul></div>
