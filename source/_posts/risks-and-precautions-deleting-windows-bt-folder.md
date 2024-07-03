---
title: "Risks & Precautions: Deleting Windows ~BT Folder"
date: 2024-06-25T11:42:10.651Z
updated: 2024-06-26T11:42:10.651Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Risks & Precautions: Deleting Windows ~BT Folder"
excerpt: "This Article Describes Risks & Precautions: Deleting Windows ~BT Folder"
keywords: BT Folder Delete Risks,Windows Safe Deletion,Secure Data Removal,Avoiding Data Leakage,Preventing BT Data Loss,Cleanup Windows Safely,Protecting Privacy Post-Deletion
thumbnail: https://thmb.techidaily.com/b478b0983a67f36010d885714312f70db32d5d3a2179d68b62f5c8d46f0ea38e.jpg
---

## Risks & Precautions: Deleting Windows ~BT Folder

 Deleting the hidden "$Windows.\~BT" folder and recovering gigabytes of space on your hard drive is tempting. But what is this cryptically named folder for, and how critical is it to your Windows installation?

## What Is the “$Windows.\~BT” Folder, and Should You Delete It?

 Windows creates the "$Windows.\~BT" folder when you upgrade the operating system to a newer build. This folder contains all the essential files for the upgrade process, like temporary installation files and logs from the previous Windows installation.

 Windows automatically removes the "$Windows.\~BT" folder after 10 days. As manually deleting this folder will [remove old Windows installation files](https://www.makeuseof.com/tag/delete-old-windows-update-files/), you won't be able to roll back to the previous Windows build using the **Go back** option in the Recovery menu within that time (for example, to [downgrade from Windows 11 to Windows 10](https://www.makeuseof.com/windows-11-downgrade-to-windows-10/)). Hence, you should only get rid of this folder if you are satisfied with the current Windows build on your PC. You can also safely delete the massive folder if Windows fails to do it automatically after the grace period.

 But you shouldn't just delete this hidden folder like any other folder on the desktop. Instead, you should turn to the Disk Cleanup tool or the Command Prompt.

## How to Find and Delete the "$Windows.\~BT" Folder

 As "$Windows.\~BT" is a hidden folder, you need to [configure Windows to show hidden files and folders](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) to find it in File Explorer. Once you do, the **C:\\$Windows.\~BT** directory will become visible.

 You can’t delete the "$Windows.\~BT" folder directly, though. To do so, you need to run the Disk Cleanup tool. Here's how:

1. Press **Win + R** to open the Run dialog box.
2. Type **cleanmgr** in the box and press **Enter**.
3. Use the dropdown menu to select the system drive (usually **C:**) and click **OK**.
4. Click the **Clean up system files** button.
5. Under **Files to delete**, use the checkboxes to select these options: **Previous Windows Installations**, **Windows Update Cleanup**, **Windows upgrade log files**, **Temporary Windows installation files**, and **Temporary files**.
6. Click **OK**.
7. Choose **Delete Files** to confirm.  
![Delete the $Windows.~BT Folder Using the Disk Cleanup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/delete-the-windows-bt-folder-using-the-disk-cleanup-tool.jpg)

 If the "$Windows.\~BT" folder shows up even after you run the Disk Cleanup tool, you'll need to execute a few commands in Command Prompt. For that, [open Command Prompt with administrative rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) and then run the following commands one by one.

`takeown /F C:\$Windows.~BT\* /R /A
icacls C:\$Windows.~BT\*.* /T /grant administrators:F
rmdir /S /Q C:\$Windows.~BT\`

 Once you run the above commands, the "$Windows.\~BT" folder will be deleted for good.

 Now that you understand the purpose of the "$Windows.\~BT" folder, you can decide how to handle it. Beyond the "$Windows.\~BT" folder, you may also come across folders like "Windows.old," "$WinREAgent," "$SysReset," and others which can also be deleted safely using the Disk Cleanup tool.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/navigating-your-network-preferences-with-windows-11-proxies/"><u>Navigating Your Network Preferences with Windows 11 Proxies</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solutions-customize-windows-menu-for-instant-removal/"><u>Swift Solutions: Customize Windows Menu for Instant Removal</u></a></li>
<li><a href="https://win11.techidaily.com/prevent-windows-from-logging-app-starts/"><u>Prevent Windows From Logging App Starts</u></a></li>
<li><a href="https://win11.techidaily.com/greatest-non-microsoft-options-easy-screen-captures-without-windows/"><u>Greatest Non-Microsoft Options: Easy Screen Captures Without Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719319611800-overcoming-challenges-in-full-screen-snip-and-sketch-capturing/"><u>Overcoming Challenges in Full-Screen Snip & Sketch Capturing.</u></a></li>
<li><a href="https://win11.techidaily.com/fix-windows-11s-random-shutdown-phenomenon/"><u>Fix Windows 11'S Random Shutdown Phenomenon</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-to-tackle-black-screens-on-windows-11/"><u>Quick-Fix Guide to Tackle Black Screens on Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-3d-to-immersive-understanding-virtual-realitys-evolution/"><u>[Updated] From 3D to Immersive  Understanding Virtual Reality's Evolution</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-photos-after-samsung-galaxy-a24-has-been-deleted-by-fonelab-android-recover-photos/"><u>Recover your photos after Samsung Galaxy A24 has been deleted.</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-how-to-rediscover-the-past-watching-youtubes-lost-footage/"><u>[New] How to Rediscover the Past  Watching Youtube's Lost Footage</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-charting-success-with-these-top-15-youtube-introduction-techniques/"><u>[New] 2024 Approved  Charting Success with These Top 15 YouTube Introduction Techniques</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-high-quality-video-communication-ranking-the-top-10-mobile-apps/"><u>[New] 2024 Approved  High-Quality Video Communication  Ranking the Top 10 Mobile Apps</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-evaluating-enterprise-chat-apps-for-peak-productivity-which-one-wins-slack-or-discord-in-2024/"><u>[New] Evaluating Enterprise Chat Apps for Peak Productivity  Which One Wins, Slack or Discord, In 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/explore-the-top-free-screen-recorders-ranked-list/"><u>Explore the Top Free Screen Recorders  Ranked List</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-oppo-reno-10-5g-drfone-by-drfone-virtual-android/"><u>In 2024, All You Need To Know About Mega Greninja For Oppo Reno 10 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-enhancing-video-discoverability-through-youtube-images/"><u>[New] 2024 Approved  Enhancing Video Discoverability Through Youtube Images</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>