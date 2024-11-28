---
title: Simplifying Your Win 11 Menu Choices
date: 2024-11-22T19:10:32.176Z
updated: 2024-11-27T23:08:25.356Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Simplifying Your Win 11 Menu Choices
excerpt: This Article Describes Simplifying Your Win 11 Menu Choices
keywords: Simplify Win11 Menu,Win11 User Guide,Streamline Win11 Menu,Easy Win11 Options,Optimize Win11 Selection,Win11 Menu Adjustments,Navigate Win11 Menus
thumbnail: https://thmb.techidaily.com/cf7a08bd282de8a6ab97b6e5d5d8ca10a7266e7f855e68e8c2f62606a22410cc.jpeg
---

## Simplifying Your Win 11 Menu Choices

 Windows 11 comes with a fresh new look and has mainly got a positive response for its new interface. However, there are a couple of features that are not being welcomed by the users. For instance, the addition of the "show more options" entry to the right-click context menu.

 Although it was introduced to simplify things, many users still prefer the old context menu from Windows 10\. Fortunately, you can remove Show more options from the context menu on Windows 11 by following the below methods.

## 1\. How to Remove "Show More Options" From the Context Menu With Folder Options

 The[Windows Folder Options](https://www.makeuseof.com/windows-folder-options-guide/) in File Explorer is the go-to place to view and manage File Explorer settings. You can use it to[enable compact view in File Explorer on Windows 11](https://www.makeuseof.com/how-to-enable-compact-view-windows-11-file-explorer/) , manage file thumbnails, remove the "show more options" entry, and much more.

 Here's how to use the folder option to remove the "show more options" entry from the context menu:

1. Press the**Win + E** hotkey to open the**File Explorer.**
2. Click the three horizontal dots at the top bar and choose**Options.**
3. In the**Folder Options,** switch to the**View** tab.
4. Check the**Launch folder** **windows in a separate process** box.  
![Launch folder windows in a separate process box in the Folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/launch-folder-windows-in-a-separate-process-box.jpg)
5. Click**Apply** \>**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Next, restart your computer for the changes to take effect.

## 2\. Remove Show More Options From the Context Menu Using the Command Prompt

 If you're a power user, you can use Command Prompt to remove the "show more options" entry from the context menu. Here's how:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane.
3. Click**Yes** to the UAC that crops up.
4. In the elevated Command Prompt window, type the following command and press**Enter** :  
`reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve`

![Command to Remove Context menu in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-to-remove-context-menu.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After executing the command, you'll see the "The operation completed successfully" message to confirm that it went through.

 Now, you will have to restart Windows Explorer to see the changes. To do that, open the**Task Manager** (see how to[launch the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) ), right-click on**Windows Explorer,** and choose**Restart.**

 Check if you can see the changes. If not, then you will have to restart your computer for the changes to take effect.

 In the future, if you want to add the "show more options" entry to the context menu, then open Command Prompt with admin rights and run the following command:

`reg delete "HKEY_CURRENT_USER\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f​`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Remove Show More Options From the Context Menu Using the Registry Editor

 Another quick way to remove the "show more options" entry is through the Registry Editor. Here's what you need to do:

 Before making any changes to the registry, ensure you've[created a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) or[back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . This will ensure your system settings and files are secure, and you can quickly access them if something goes wrong.

1. Open the Start Menu, type**Registry Editor** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID`
3. Right-click on the empty space on the right pane, click**New,** and then select**DWORD** **(32-bit) Value** from the context menu.
4. Name the value as**"UndockingDisabled"** and press**Enter** .  
![UndockingDisabled entry in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/undockingdisabled-entry.jpg)
5. Double-click on the UndockingDisabled key, type**1** in the**Value data,** and click**OK** to save the changes.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Editing UndockingDisabled in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-undockingdisabled.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Remove the "Show More Options" Entry From the Context Menu Using Winaero Tweaker

 There are plenty of third-party tools using which you can customize the look of your Windows 11 computer. For this guide, we will use Winaero Tweaker.

 Here's how to download Winaero Tweaker and use it to remove the "show more options" entry from the context menu:

1. Download the[Winaero Tweaker zip file](https://winaero.com/downloads/winaerotweaker.zip) on your computer.
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
<li><a href="https://fox-http.techidaily.com/new-in-2024-expert-strategy-for-melding-gopro-vids-with-spherical-video-projects/"><u>[New] In 2024, Expert Strategy for Melding GoPro Vids with Spherical Video Projects</u></a></li>
<li><a href="https://solve-helper.techidaily.com/1-best-online-green-screen-app-manycam-your-ultimate-live-streaming-and-video-call-tool/"><u>1. Best Online Green Screen App: ManyCam - Your Ultimate Live Streaming and Video Call Tool</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-pinnacle-gadgets-the-leading-smartphones-for-artists/"><u>2024 Approved Pinnacle Gadgets The Leading Smartphones for Artists</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-unleashing-the-power-of-pip-videos-with-sierras-os-advantages/"><u>2024 Approved Unleashing the Power of PIP Videos with Sierra's OS Advantages</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/cannot-play-mkv-files-on-galaxy-a25-5g-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Cannot play MKV files on Galaxy A25 5G</u></a></li>
<li><a href="https://win11.techidaily.com/creating-efficient-pathways-software-shortcut-addition-win11-style/"><u>Creating Efficient Pathways: Software Shortcut Addition Win11 Style</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-convergence-post-windows-11-subsystem-adjustments/"><u>Enhancing Convergence Post-Windows 11 Subsystem Adjustments</u></a></li>
<li><a href="https://article-helps.techidaily.com/exploring-microsofts-hololens-a-hologram-horizon-for-2024/"><u>Exploring Microsoft's HoloLens A Hologram Horizon for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-in-depth-analysis-understanding-the-google-podcast-app/"><u>In 2024, In Depth Analysis Understanding the Google Podcast App</u></a></li>
<li><a href="https://sound-issues.techidaily.com/quick-fix-tips-for-addressing-noise-absence-from-conexant-smartaudio-hd-under-windows-11/"><u>Quick Fix Tips for Addressing Noise Absence From Conexant SmartAudio HD Under Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-root-access-issues-in-cmd-windows/"><u>Resolving Root Access Issues in Cmd Windows</u></a></li>
<li><a href="https://fox-glue.techidaily.com/romantic-recitals-perfect-love-songs-for-your-proposal-moment/"><u>Romantic Recitals Perfect Love Songs for Your Proposal Moment</u></a></li>
<li><a href="https://win11.techidaily.com/title-fine-tuning-icon-gaps-in-windows-1110-environments/"><u>Title: Fine-Tuning Icon Gaps in Windows 11/10 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-hibernate-glitches/"><u>Troubleshooting Windows Hibernate Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/wins-blue-screen-blight-finding-the-fix/"><u>Win’s Blue Screen Blight - Finding the Fix</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-long-term-support-plan-explained-latest-update-details/"><u>Windows 11'S Long-Term Support Plan Explained: Latest Update Details</u></a></li>
<li><a href="https://win11.techidaily.com/windows-version-timeline-decryption/"><u>Windows Version Timeline Decryption</u></a></li>
</ul></div>

