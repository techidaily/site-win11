---
title: Adjusting Win 11 Context Menu to Omit Additional Entry
date: 2025-02-26T18:14:43.262Z
updated: 2025-03-04T18:52:10.499Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Win 11 Context Menu to Omit Additional Entry
excerpt: This Article Describes Adjusting Win 11 Context Menu to Omit Additional Entry
keywords: Win 11 Context Menu Edit,Omitting Menu Entry in Win 11,Removing Win 11 Add-Ons,Editing Windows Menu Options,Customizing Win 11 UI,Adjusting Context Menu Items,Streamlining Win 11 Interface
thumbnail: https://thmb.techidaily.com/a68fefb1cd3e565ec5f454a0d5028d3000ec7ede8d478967f77735423a6ab539.jpg
---

## Adjusting Win 11 Context Menu to Omit Additional Entry

 Windows 11 comes with a fresh new look and has mainly got a positive response for its new interface. However, there are a couple of features that are not being welcomed by the users. For instance, the addition of the "show more options" entry to the right-click context menu.

 Although it was introduced to simplify things, many users still prefer the old context menu from Windows 10\. Fortunately, you can remove Show more options from the context menu on Windows 11 by following the below methods.

## 1\. How to Remove "Show More Options" From the Context Menu With Folder Options

 The [Windows Folder Options](https://www.makeuseof.com/windows-folder-options-guide/) in File Explorer is the go-to place to view and manage File Explorer settings. You can use it to [enable compact view in File Explorer on Windows 11](https://www.makeuseof.com/how-to-enable-compact-view-windows-11-file-explorer/) , manage file thumbnails, remove the "show more options" entry, and much more.

 Here's how to use the folder option to remove the "show more options" entry from the context menu:

1. Press the**Win + E** hotkey to open the**File Explorer.**
2. Click the three horizontal dots at the top bar and choose**Options.**
3. In the**Folder Options,** switch to the**View** tab.
4. Check the**Launch folder** **windows in a separate process** box.  
![Launch folder windows in a separate process box in the Folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/launch-folder-windows-in-a-separate-process-box.jpg)
5. Click**Apply** \>**OK** to save the changes.

Next, restart your computer for the changes to take effect.

## 2\. Remove Show More Options From the Context Menu Using the Command Prompt

 If you're a power user, you can use Command Prompt to remove the "show more options" entry from the context menu. Here's how:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane.
3. Click**Yes** to the UAC that crops up.
4. In the elevated Command Prompt window, type the following command and press**Enter** :  
`reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve`

![Command to Remove Context menu in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-to-remove-context-menu.jpg)

 After executing the command, you'll see the "The operation completed successfully" message to confirm that it went through.

 Now, you will have to restart Windows Explorer to see the changes. To do that, open the**Task Manager** (see how to [launch the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) ), right-click on**Windows Explorer,** and choose**Restart.**

 Check if you can see the changes. If not, then you will have to restart your computer for the changes to take effect.

 In the future, if you want to add the "show more options" entry to the context menu, then open Command Prompt with admin rights and run the following command:

`reg delete "HKEY_CURRENT_USER\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f​`

## 3\. Remove Show More Options From the Context Menu Using the Registry Editor

 Another quick way to remove the "show more options" entry is through the Registry Editor. Here's what you need to do:

 Before making any changes to the registry, ensure you've [created a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) or [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . This will ensure your system settings and files are secure, and you can quickly access them if something goes wrong.

1. Open the Start Menu, type**Registry Editor** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID`
3. Right-click on the empty space on the right pane, click**New,** and then select**DWORD** **(32-bit) Value** from the context menu.
4. Name the value as**"UndockingDisabled"** and press**Enter** .  
![UndockingDisabled entry in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/undockingdisabled-entry.jpg)
5. Double-click on the UndockingDisabled key, type**1** in the**Value data,** and click**OK** to save the changes.  
![Editing UndockingDisabled in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-undockingdisabled.jpg)

## 4\. Remove the "Show More Options" Entry From the Context Menu Using Winaero Tweaker

 There are plenty of third-party tools using which you can customize the look of your Windows 11 computer. For this guide, we will use Winaero Tweaker.

 Here's how to download Winaero Tweaker and use it to remove the "show more options" entry from the context menu:

1. Download the [Winaero Tweaker zip file](https://winaero.com/downloads/winaerotweaker.zip) on your computer.
2. Unzip the file, open the executable, and then follow the on-screen instructions to install it on your computer.
3. Launch Winaero Tweaker and choose the**Classic Full Context Menus** option from the left sidebar.  
![Classic Full Context Menus option of Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/classic-full-context-menus-option.jpg)
4. Check the**Enable classic full context menus** box.  
![Enable classic full context menus option in Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-classic-full-context-menus.jpg)
5. Click the**Restart Explorer** button that appears.

## Enjoy an Old School Context Menu on Windows 11

 The desktop context menu lets you quickly access areas like the personalization menu, display settings, and much more. In Windows 11, you get the new "Show more options" entry in the context menu. But if you prefer the old design, you can quickly disable the "Show more options" entry from the context using either of the above methods.

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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-elevate-engagement-natural-ways-to-popularize-your-videos/"><u>[New] 2024 Approved Elevate Engagement Natural Ways to Popularize Your Videos</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-explore-the-best-8-mirrorless-cameras-for-youtube-vloggers/"><u>[New] 2024 Approved Explore the Best 8 Mirrorless Cameras for YouTube Vloggers</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-live-the-experience-top-4-ways-to-preserve-your-gaming-adventures/"><u>[New] In 2024, Live the Experience Top 4 Ways to Preserve Your Gaming Adventures</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-best-companions-choosing-blu-ray-software-freepaid-on-pcsmacs-for-2024/"><u>[Updated] Best Companions Choosing Blu-Ray Software (Free/Paid) on PCs/Macs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-correcting-windows-0x80072af9-mistake/"><u>Decoding and Correcting Windows' 0X80072AF9 Mistake</u></a></li>
<li><a href="https://win11.techidaily.com/empowering-buyers-with-ai-at-microsofts-digital-marketplace/"><u>Empowering Buyers with AI at Microsoft's Digital Marketplace</u></a></li>
<li><a href="https://win-forum.techidaily.com/1722915385576-essential-social-networking-sites-explore-facebook-twitter-instagram-and-youtube/"><u>Essential Social Networking Sites - Explore Facebook, Twitter, Instagram, and YouTube!</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-engage-with-widget-features-in-win11-os/"><u>How to Engage With Widget Features in Win11 OS</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-keep-starfield-running-smoothly-without-crashing-on-your-desktop-system/"><u>How to Keep Starfield Running Smoothly Without Crashing on Your Desktop System</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-to-move-playlist-library-from-apple-music-to-youtube-music-for-a-unified-listening-experience/"><u>How to Move Playlist Library From Apple Music to YouTube Music for a Unified Listening Experience</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-essential-tips-for-capturing-evening-portraits/"><u>In 2024, Essential Tips for Capturing Evening Portraits</u></a></li>
<li><a href="https://win11.techidaily.com/personalized-protocol-for-spotting-system-intrusions/"><u>Personalized Protocol for Spotting System Intrusions</u></a></li>
<li><a href="https://win11.techidaily.com/power-users-unite-local-gpo-in-windows-11/"><u>Power Users Unite: Local GPO in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/revitalizing-pre-ultimate-windows-pc-accessibility/"><u>Revitalizing Pre-Ultimate Windows PC Accessibility</u></a></li>
<li><a href="https://win11.techidaily.com/the-swift-route-to-opening-iis-manager-interface/"><u>The Swift Route to Opening IIS Manager Interface</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-motorola-moto-g34-5g-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Motorola Moto G34 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/tracking-bandwidth-icon-tutorial-for-taskbar/"><u>Tracking Bandwidth: Icon Tutorial for Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/tricks-for-bypassing-windows-11-lock-in-minutes/"><u>Tricks for Bypassing Windows 11 Lock in Minutes</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-access-denied-message-for-windows-device-files/"><u>Troubleshooting the 'Access Denied' Message for Windows Device Files</u></a></li>
</ul></div>

