---
title: Why You Can't See a Drive Letter On Your PC? Insights & Remedies for Win Users
date: 2024-10-10T22:21:05.595Z
updated: 2024-10-15T20:17:00.482Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Why You Can't See a Drive Letter On Your PC? Insights & Remedies for Win Users
excerpt: This Article Describes Why You Can't See a Drive Letter On Your PC? Insights & Remedies for Win Users
keywords: Drive Letter View,Windows Drive Visibility,Missing Drive Icon,PC Drive Display,Unseen Drives Fix,Win Users Drive Issue,Address Hidden Drive
thumbnail: https://thmb.techidaily.com/733caf2abbd8fb995bf457552e00ba90aafeaec9c6d7712345148ce88c83b02a.jpg
---

## Why You Can't See a Drive Letter On Your PC? Insights & Remedies for Win Users

 Seeing the error message "drive letter not available" when accessing or creating a new storage drive can be very frustrating. The reason for the error isn't always immediately obvious, but it is rarely unsolvable.

 Here are the most common causes for an unavailable drive letter on Windows, and ways you can fix the problem.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Are Drive Letters in Windows?

 Any new storage drive, volume, or partition you add to your computer (especially if you[add a partition to your hard drive for optimum performance](https://www.makeuseof.com/how-to-partition-hard-drive/) ) needs to have a letter assigned before it will work. It is basically a label, a way for the system and the user to recognize different storage spaces.

 If a drive or partition does not have a letter assigned, it will be inaccessible to you and the software and services that may need to see the files in that space.

 Drive letters, occasionally called device letters, run alphabetically from A to Z. These days, A and B are rarely used, and we've covered before[why local drives on Windows start from "C"](https://www.makeuseof.com/why-local-drives-windows-start-from-c/) .

 New storage devices will be automatically assigned the first unused letter when connected. This automatic process occasionally fails or gets blocked by a conflict in the system settings.

 Upgrading from an older version of Windows to a new version can sometimes cause drive letters to be reassigned. Let's say that your applications all point to a particular drive, but that drive is now assigned a different letter. Things will get frustrating quickly if you can't select the letter you need.

## Reasons Why Drive Letters Are Unavailable

 As mentioned, there are several possible reasons why you might see the "Drive letter not available" error. The most common reasons include:

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118323/7443" target="_top" id="2118323">
  <img src="//a.impactradius-go.com/display-ad/7443-2118323" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118323/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### The Letter Is In Use by a Hidden Removable Drive

 When you connect a removable drive, such as a USB thumb drive, a drive letter will be assigned to it. Sometimes even after the removable drive is disconnected, the drive letter remains associated with it. In this case, it will be unavailable, and you'll see the error message.

### The Letter Is Permanently Assigned to Another Storage Volume

 It is possible to permanently assign a drive letter to a particular partition or drive. This also includes optical devices like the CD/DVD drive. If you have previously done this, the drive letter will no longer be available to choose from when setting up a new partition or drive.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136613/26400" target="_top" id="2136613">
  <img src="//a.impactradius-go.com/display-ad/26400-2136613" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136613/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Make Drive Letters Available for Use

 Both of the causes for the error detailed above are fixable. You can download free software to help with reassigning the letters. But you can also use the Windows Registry Editor to solve the problem yourself. Here's how.

1. Open the**Run dialog** by pressing**Win + R** .
2. Type**Regedit** and click**Ok** to open the Registry Editor.
3. Using either the panel on the left or the address field at the top, navigate to:**HKEY\_LOCAL\_MACHINE\\SYSTEM\\MountedDevices** .  
![Mounted devices in the Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/drive-letter-registry.jpg)
4. In the list of assigned devices, right-click on the one you want to change and select**Rename** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915870/19272" target="_top" id="1915870">
  <img src="//a.impactradius-go.com/display-ad/19272-1915870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915870/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Change the drive letter to any other unused letter to free up the one being used.
6. Close the Registry Editor and restart your computer. You should then be able to assign the unused letter as you wish.

 If you prefer not to mess around with the Registry directly, you can use something like[AOMEI Partition Assistant Standard](https://www.diskpart.com/download-home.html) . The free version has limited tools but will let you reassign drive letters.

1. Open the Partition Assistant app and find the drive you want to reassign in the main window.
2. Right-click on the drive and select**Advanced > Change Drive Letter** from the menu.
3. In the new panel, use the dropdown menu to select a new and unused drive letter.  
![Changing a drive letter in third-party software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/partition-assistant-driveletter.jpg)
4. Click**Ok** and confirm the operation on the next screen. It may take a few seconds to process the change.
5. You can then return to the main screen, find the drive to which you want to assign that released letter, and repeat the process.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134228/18498" target="_top" id="2134228">
  <img src="//a.impactradius-go.com/display-ad/18498-2134228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134228/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-tips.techidaily.com/n-2024-the-essence-of-elegance-in-video-color-balancing/"><u>[New] In 2024, The Essence of Elegance in Video Color Balancing</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-how-to-avoid-and-eliminate-fog-on-gopro-lenshousing/"><u>2024 Approved How to Avoid and Eliminate Fog on GoPro Lens/Housing</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/4-ways-to-reset-your-password-in-windows-10/"><u>4 Ways to Reset Your Password in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-correcting-error-0x80004004-on-defender/"><u>Deciphering and Correcting Error 0X80004004 on Defender</u></a></li>
<li><a href="https://some-guidance.techidaily.com/effortless-method-for-posting-full-sized-dvds-on-facebook-without-conforming-to-standard-formats/"><u>Effortless Method for Posting Full-Sized DVDs on Facebook Without Conforming to Standard Formats</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-unlocking-perfect-presentation-youtubes-video-ratio-insights/"><u>In 2024, Unlocking Perfect Presentation YouTube's Video Ratio Insights</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-tabs-on-pc-login-separating-goals-from-errors/"><u>Keeping Tabs on PC Login: Separating Goals From Errors</u></a></li>
<li><a href="https://win11.techidaily.com/keyboardmouse-wake-issues-fix-for-win11-users/"><u>Keyboard/Mouse Wake Issues: Fix for Win11 Users</u></a></li>
<li><a href="https://fox-helps.techidaily.com/pinnacle-camera-technology-the-best-reviewed-for-2024/"><u>Pinnacle Camera Technology – The Best Reviewed for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-cannot-preview-error-with-microsoft-office-outlook/"><u>Resolving 'Cannot Preview' Error with Microsoft Office Outlook</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/sea-dwellers-in-focus-tips-for-shooting-stunning-gopro-video-below-water-for-2024/"><u>Sea Dwellers in Focus Tips for Shooting Stunning GoPro Video Below Water for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-for-persistent-windows-10-bsod-problems/"><u>Solutions for Persistent Windows 10 BSOD Problems</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-retrieve-faded-bios-messages/"><u>Tips to Retrieve Faded BIOS Messages</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ultimate-guide-to-selecting-the-perfect-vr-headset-for-pc-play-and-gaming-adventures/"><u>Ultimate Guide to Selecting the Perfect VR Headset for PC Play & Gaming Adventures</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-the-purpose-of-pagefilesys-and-should-it-be-deleted/"><u>What Is the Purpose of Pagefile.sys and Should It Be Deleted?</u></a></li>
<li><a href="https://win11.techidaily.com/winning-back-access-to-steam-remote-play/"><u>Winning Back Access to Steam Remote Play</u></a></li>
</ul></div>

