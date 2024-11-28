---
title: "Windows Lacks Drive Letters: Why and How to Rectify This Issue."
date: 2024-11-23T18:07:50.988Z
updated: 2024-11-27T18:18:05.849Z
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

## Reasons Why Drive Letters Are Unavailable

 As mentioned, there are several possible reasons why you might see the "Drive letter not available" error. The most common reasons include:

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### The Letter Is In Use by a Hidden Removable Drive

 When you connect a removable drive, such as a USB thumb drive, a drive letter will be assigned to it. Sometimes even after the removable drive is disconnected, the drive letter remains associated with it. In this case, it will be unavailable, and you'll see the error message.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/43goO8X0iX0?si=48Cqf6td2q_6T6h3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### The Letter Is Permanently Assigned to Another Storage Volume

 It is possible to permanently assign a drive letter to a particular partition or drive. This also includes optical devices like the CD/DVD drive. If you have previously done this, the drive letter will no longer be available to choose from when setting up a new partition or drive.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Make Drive Letters Available for Use

 Both of the causes for the error detailed above are fixable. You can download free software to help with reassigning the letters. But you can also use the Windows Registry Editor to solve the problem yourself. Here's how.

1. Open the**Run dialog** by pressing**Win + R** .
2. Type**Regedit** and click**Ok** to open the Registry Editor.
3. Using either the panel on the left or the address field at the top, navigate to:**HKEY\_LOCAL\_MACHINE\\SYSTEM\\MountedDevices** .  
![Mounted devices in the Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/drive-letter-registry.jpg)
4. In the list of assigned devices, right-click on the one you want to change and select**Rename** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://snapchat-videos.techidaily.com/new-elevating-your-snapping-game-tips-for-uninterrupted-streaks-for-2024/"><u>[New] Elevating Your Snapping Game Tips for Uninterrupted Streaks for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-how-to-download-igtv-videos-on-iphone-and-android-5-ways/"><u>[Updated] 2024 Approved How to Download IGTV Videos on iPhone & Android [5 Ways]</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-discovering-the-best-vr-camera-for-adventures/"><u>[Updated] Discovering the Best VR Camera for Adventures</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-leading-the-vr-charge-top-10-pc-headsets/"><u>[Updated] Leading The VR Charge Top 10 PC Headsets</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ing-quality-videos-a-guide-to-apple-device-screen-recording/"><u>Crafting Quality Videos A Guide to Apple Device Screen Recording</u></a></li>
<li><a href="https://win11.techidaily.com/desktop-icon-resurrection-in-windows-11/"><u>Desktop Icon Resurrection in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-and-solving-nvidia-disconnect-problems-in-win10win11/"><u>Diagnosing and Solving NVIDIA Disconnect Problems in Win10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-os-error-xc0000142-on-windows/"><u>Eradicating OS Error XC0000142 on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-screen-flickering-and-flashing-on-windows-11-and-11/"><u>How to Fix Screen Flickering and Flashing on Windows 11 and 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-facts-you-need-to-know-about-screen-mirroring-vivo-y17s-drfone-by-drfone-android/"><u>In 2024, 3 Facts You Need to Know about Screen Mirroring Vivo Y17s | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-from-concept-to-comic-10-must-have-strategies-for-making-gifs/"><u>In 2024, From Concept to Comic 10 Must-Have Strategies for Making GIFs</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-faulty-display-brightness-fn-buttons-in-windows-11/"><u>Repairing Faulty Display Brightness Fn Buttons in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/revive-your-usb-wi-fi-links-top-remedies-for-windows-users/"><u>Revive Your USB Wi-Fi Links – Top Remedies for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-skyrocket-your-winning-frames-in-csgo/"><u>Strategies to Skyrocket Your Winning Frames in CS:GO</u></a></li>
<li><a href="https://technical-tips.techidaily.com/understanding-the-shift-towards-electric-automobiles-a-comprehangive-guide/"><u>Understanding the Shift Towards Electric Automobiles: A Comprehangive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-11s-secrets-understanding-its-registry/"><u>Unlocking Windows 11'S Secrets: Understanding Its Registry</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-mystery-behind-windows-error-code-0x800704b3/"><u>Unveiling the Mystery Behind Windows' Error Code: 0X800704B3</u></a></li>
<li><a href="https://win-special.techidaily.com/wie-beheben-sie-den-facetime-fehler-auf-ihrem-iphone-modell-14-13-12-oder-11/"><u>Wie Beheben Sie Den FaceTime-Fehler Auf Ihrem iPhone Modell 14, 13, 12 Oder 11?</u></a></li>
<li><a href="https://discover-bits.techidaily.com/1726029296115-dvd/"><u>ダビングで始めるパワーディレクター：DVDからの主要映像統合ガイド</u></a></li>
</ul></div>

