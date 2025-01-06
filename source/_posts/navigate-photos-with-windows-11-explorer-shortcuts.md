---
title: Navigate Photos with Windows 11 Explorer Shortcuts
date: 2025-01-03T16:25:04.112Z
updated: 2025-01-06T21:02:39.634Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigate Photos with Windows 11 Explorer Shortcuts
excerpt: This Article Describes Navigate Photos with Windows 11 Explorer Shortcuts
keywords: Windows 11 Photo Viewing,Explore Win11 Images,Navigate Win11 Pics,Quick Photos in Win11,Shortcuts for Image Explorer,Fast Access Photos Win11,Windows 11 Photo Shortcuts
thumbnail: https://thmb.techidaily.com/4e90942cb4f7cac0b8179c9a85473a893720905506787f6d97b44b698d179a25.jpg
---

## Navigate Photos with Windows 11 Explorer Shortcuts

 Windows 11’s File Explorer has a tabs feature now. You can open a new location on the disk in a new tab rather than opening a new File Explorer window. Switching between multiple file locations is seamless, all thanks to this feature. But Microsoft isn’t planning to stop here. It wants to completely overhaul the File Explorer.

 File Explorer Gallery is one such new feature that Microsoft is testing in the Canary channel. Having a Gallery section will remove the need to browse separate folders to find or preview an image. Want to enable the feature on your system? Let’s begin.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is the Gallery Feature in Windows File Explorer?

 File Explorer’s Gallery feature works exactly like it sounds. It categorically lists all the images on your system in a separate section, so you can find and view all the images in one tab. Android File Explorers have had this feature for quite a long, but Windows seems to care about it now.

 This new feature is available in the Windows Insider build version 25300 and above. But Microsoft made a big change to the Insider program by adding a Canary channel. So, any new Canary build will also have this experimental feature. Microsoft adds the new File Explorer based on Windows App SDK, which you can verify by hovering over the “pizza” icon in the File Explorer address bar.

 The Gallery section displays images from the Pictures and OneDrive folders and lists them by date. It has nice, rounded corners around each image in the Gallery section, which makes it feel like a part of the overall Windows 11 design. It appears right below the Home option in the left pane.

## How to Enable Gallery in File Explorer in Windows 11

 Repeat the following steps to enable the new Gallery section in File Explorer:

### 1\. Update to the Appropriate Windows Insider Build

 The Gallery section is hidden in Insider builds 25300 and above. If you are a Windows Insider program participant, open and check for the latest Insider builds on your system. Make sure to be in the Dev or Canary channel because this experimental feature is exclusive to these channels only. Or, you can use[UUP Dump to download Windows Insider builds without participating in Microsoft’s Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

### 2\. Download ViVeTool

 You will also need ViVeTool to enable these experimental features on your system. You can[download ViVetool from GitHub](https://github.com/thebookisclosed/ViVe/releases) , but make sure that you pick the most recent release. Extract the tool to the C drive and then proceed to the next section.

### 2\. Enabling Gallery in Windows File Explorer

 Retrace the following steps to enable the Gallery section on Windows 11:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press**Ctrl + Shift + Enter** keys at once to open a new Command Prompt window with administrator privileges.
2. Now, navigate to the main directory in C drive. Type**cd C:\\ command** and press the enter key.
3. Next, type the**cd Vivetool** command to enter the folder where Vivetool is present in the C drive. It is the main reason why we suggested you extract Vivetool in a convenient location.
4. Type the**Vivetool** command and press enter key to check if the tool is accessible and working. You will see the version of the tool along with the parameters it supports.  
![Enable Gallery in File Explorer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-gallery-in-file-explorer-in-windows-11.jpg)
5. Now, type the following command and press the enter key:  

vivetool /enable /id:41040327
6. If the command executes correctly, you will see a “Successfully set feature configuration(s)” message. But don’t close the Command Prompt window. Type the following commands to enable all the Gallery features one by one and execute them.  
vivetool /enable /id:40729001 vivetool /enable /id:40731912 vivetool /enable /id:41969252 vivetool /enable /id:42922424 vivetool /enable /id:42295138
7. After running all the commands without any error, type**exit** and press the enter key to close the command prompt window.  
![Enable Gallery in File Explorer in Windows 11 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-gallery-in-file-explorer-in-windows-11-2.jpg)
8. Restart your computer for the changes made by Vivetool to take effect.

9. Once your computer boots up, press**Win + E** to open File Explorer. You will see a new**Gallery** option in the left pane below the**Home** option.

## How to View the Gallery in File Explorer

 You can access the Gallery section by launching File Explorer and clicking on the Gallery option in the left navigation pane. You will see all the images from the Pictures folder and OneDrive folder arranged by modification time (new to old). There is also a handy slider to scroll through the vast image tiles without using the mouse scroll wheel.

![Gallery in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/gallery-in-windows-file-explorer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The gallery app allows you to adjust the view of the image tiles to accommodate more or less in a single window. You can use the View option in the menu bar of File Explorer to change the image tile size. If you click on any image, it will open in a separate app window (Photos app or any other app that you use).

## How to Add or Remove Locations From Gallery in Windows File Explorer

 By default, the Gallery selection displays all the images located in the Pictures folder and OneDrive. But you can add or remove a folder from the Gallery section as well.

1. To add a folder to the Gallery, go to the menu bar and click on the**Locations** option. A new pop-up window will open and list all the folders that the Gallery section is pulling images from. Click on the**Add** button.  
![Adding a Folder to Gallery in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/adding-a-folder-to-gallery-in-windows-file-explorer.jpg)
2. Now select any folder or sub-folder with images and click on the**Include Folder** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. The selected folder will appear in the list of available folders. Click on the**OK** button.
4. File Explorer gallery will now display the images present inside the newly added folder as well.

To remove a folder from Gallery, repeat the following steps:

1. Open the Gallery section and click on the**Locations** option in the menu bar.
2. You will see the list of all the folders currently included in the Gallery.
3. Click on the folder you want to remove to select it. Then click on the**Remove** button.  
![Removing a Folder from Gallery in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/removing-a-folder-from-gallery-in-windows-file-explorer.jpg)
4. Lastly, click on the**OK** button to finalize the changes. The Gallery section won’t display any images from the excluded folder from now onwards.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Problems With the Gallery Section in Windows File Explorer

 The current preview of the Gallery feature is far from perfect. Firstly, the section works well in finding and categorically listing all the images from the included folders. But the images, despite being big, appear hazy. What’s the point of including a section if the images aren’t visible clearly?

 There is also the issue of images opening in a separate tab rather than in the same File Explorer window. If you plan to open the image in another window, you can do it from the image folder as well. So, future builds should include an option to preview the image in the File Explorer window. Otherwise, you are opening two apps to achieve the same thing. The Gallery section cannot list any videos as well and just ignores all the video files.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Find All Your Images in One Place on Windows With Galleries

 Adding a Gallery section to File Explorer is a fantastic decision by Microsoft. But the current version is full of kinks we hope that Microsoft irons out before the final preview. If done right, this would make the File Explorer app a powerhouse and reduce dependency on other apps.

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
<li><a href="https://fox-info.techidaily.com/new-2024-approved-write-striking-introductions-insights-and-demonstrations/"><u>[New] 2024 Approved Write Striking Introductions Insights & Demonstrations</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-from-game-to-giga-full-ps4-capture-using-obs/"><u>[New] In 2024, From Game to Giga Full PS4 Capture Using OBS</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-pioneering-post-production-excellence-with-these-11-top-tutorials-for-2024/"><u>[New] Pioneering Post-Production Excellence with These 11 Top Tutorials for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/windows-11dvdmp4aviwmv-3/"><u>免费在Windows 11上高效转换DVD成MP4/AVI/WMV - 顶级3种软件推荐</u></a></li>
<li><a href="https://tech-revival.techidaily.com/automating-microsoft-word-docs-via-chatgpt-a-comprehensive-guide/"><u>Automating Microsoft Word Docs via ChatGPT - A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-resolving-d3d11-issues-for-w11w10-systems/"><u>Decoding and Resolving D3D11 Issues for W11/W10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-unwanted-updates-with-4-tactics/"><u>Eliminate Unwanted Updates with 4 Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-addressing-unresponsive-device-camera-in-win11/"><u>Guide to Addressing Unresponsive Device: Camera in Win11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-lock-apps-on-motorola-edge-40-neo-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Motorola Edge 40 Neo to Protect Your Individual Information</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-2023s-best-intro-editor-app-for-all-your-devices/"><u>In 2024, 2023’S Best Intro Editor App for All Your Devices</u></a></li>
<li><a href="https://win11.techidaily.com/leap-into-productivity-here-are-the-best-9-upgrade-points/"><u>Leap Into Productivity: Here Are the Best 9 Upgrade Points</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-troubleshooting-for-windows-msc-not-found-error/"><u>Mastering Troubleshooting for Windows MSC Not Found Error</u></a></li>
<li><a href="https://win11.techidaily.com/pioneering-personalization-a-step-by-step-to-changing-username-on-windows-11/"><u>Pioneering Personalization: A Step-by-Step to Changing UserName on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/realign-prime-video-subtitles-with-windows-11-settings/"><u>Realign Prime Video Subtitles with Windows 11 Settings</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-cybersecurity-why-more-than-one-antivirus-is-unnecessary-for-windows-pcs/"><u>Simplify Cybersecurity: Why More Than One Antivirus Is Unnecessary for Windows PCs</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-beginners-guide-to-selecting-cams-in-the-year-2024/"><u>The Beginner's Guide to Selecting Cams in the Year 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-fixes-for-your-windows-net-system-max-156/"><u>The Essential Fixes for Your Windows .NET System (Max 156)</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-guide-setting-up-your-new-x-twitters-successor-profile/"><u>Ultimate Guide: Setting Up Your New X (Twitter's Successor) Profile</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-itel-a05s-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your Itel A05s | Dr.fone</u></a></li>
</ul></div>

