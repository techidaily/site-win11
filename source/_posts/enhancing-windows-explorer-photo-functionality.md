---
title: Enhancing Windows Explorer Photo Functionality
date: 2024-08-28T00:53:08.018Z
updated: 2024-08-29T00:53:08.018Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enhancing Windows Explorer Photo Functionality
excerpt: This Article Describes Enhancing Windows Explorer Photo Functionality
keywords: Window Photo Enhance,Explore Photography Tools,Image Editor for Windows,Improve Windows Picture View,Optimize Windows Explorer,Windows Photos Adjustment,Enhanced OS Image Viewer
thumbnail: https://thmb.techidaily.com/259bceb776cdbf3be867bf48c477b3f9885a0b2e906117f4f6cafe9378e4fe6f.jpg
---

## Enhancing Windows Explorer Photo Functionality

 Windows 11’s File Explorer has a tabs feature now. You can open a new location on the disk in a new tab rather than opening a new File Explorer window. Switching between multiple file locations is seamless, all thanks to this feature. But Microsoft isn’t planning to stop here. It wants to completely overhaul the File Explorer.

 File Explorer Gallery is one such new feature that Microsoft is testing in the Canary channel. Having a Gallery section will remove the need to browse separate folders to find or preview an image. Want to enable the feature on your system? Let’s begin.

## What Is the Gallery Feature in Windows File Explorer?

 File Explorer’s Gallery feature works exactly like it sounds. It categorically lists all the images on your system in a separate section, so you can find and view all the images in one tab. Android File Explorers have had this feature for quite a long, but Windows seems to care about it now.

 This new feature is available in the Windows Insider build version 25300 and above. But Microsoft made a big change to the Insider program by adding a Canary channel. So, any new Canary build will also have this experimental feature. Microsoft adds the new File Explorer based on Windows App SDK, which you can verify by hovering over the “pizza” icon in the File Explorer address bar.

 The Gallery section displays images from the Pictures and OneDrive folders and lists them by date. It has nice, rounded corners around each image in the Gallery section, which makes it feel like a part of the overall Windows 11 design. It appears right below the Home option in the left pane.

## How to Enable Gallery in File Explorer in Windows 11

 Repeat the following steps to enable the new Gallery section in File Explorer:

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
### 1\. Update to the Appropriate Windows Insider Build

 The Gallery section is hidden in Insider builds 25300 and above. If you are a Windows Insider program participant, open and check for the latest Insider builds on your system. Make sure to be in the Dev or Canary channel because this experimental feature is exclusive to these channels only. Or, you can use[UUP Dump to download Windows Insider builds without participating in Microsoft’s Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Download ViVeTool

 You will also need ViVeTool to enable these experimental features on your system. You can[download ViVetool from GitHub](https://github.com/thebookisclosed/ViVe/releases) , but make sure that you pick the most recent release. Extract the tool to the C drive and then proceed to the next section.

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Enabling Gallery in Windows File Explorer

 Retrace the following steps to enable the Gallery section on Windows 11:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press**Ctrl + Shift + Enter** keys at once to open a new Command Prompt window with administrator privileges.
2. Now, navigate to the main directory in C drive. Type**cd C:\\ command** and press the enter key.
3. Next, type the**cd Vivetool** command to enter the folder where Vivetool is present in the C drive. It is the main reason why we suggested you extract Vivetool in a convenient location.
4. Type the**Vivetool** command and press enter key to check if the tool is accessible and working. You will see the version of the tool along with the parameters it supports.  
![Enable Gallery in File Explorer in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-gallery-in-file-explorer-in-windows-11.jpg)
5. Now, type the following command and press the enter key:  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
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

 The gallery app allows you to adjust the view of the image tiles to accommodate more or less in a single window. You can use the View option in the menu bar of File Explorer to change the image tile size. If you click on any image, it will open in a separate app window (Photos app or any other app that you use).

## How to Add or Remove Locations From Gallery in Windows File Explorer

 By default, the Gallery selection displays all the images located in the Pictures folder and OneDrive. But you can add or remove a folder from the Gallery section as well.

1. To add a folder to the Gallery, go to the menu bar and click on the**Locations** option. A new pop-up window will open and list all the folders that the Gallery section is pulling images from. Click on the**Add** button.  
![Adding a Folder to Gallery in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/adding-a-folder-to-gallery-in-windows-file-explorer.jpg)
2. Now select any folder or sub-folder with images and click on the**Include Folder** button.
<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. The selected folder will appear in the list of available folders. Click on the**OK** button.
4. File Explorer gallery will now display the images present inside the newly added folder as well.

To remove a folder from Gallery, repeat the following steps:

1. Open the Gallery section and click on the**Locations** option in the menu bar.
2. You will see the list of all the folders currently included in the Gallery.
3. Click on the folder you want to remove to select it. Then click on the**Remove** button.  
![Removing a Folder from Gallery in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/removing-a-folder-from-gallery-in-windows-file-explorer.jpg)
4. Lastly, click on the**OK** button to finalize the changes. The Gallery section won’t display any images from the excluded folder from now onwards.

## Problems With the Gallery Section in Windows File Explorer

 The current preview of the Gallery feature is far from perfect. Firstly, the section works well in finding and categorically listing all the images from the included folders. But the images, despite being big, appear hazy. What’s the point of including a section if the images aren’t visible clearly?

 There is also the issue of images opening in a separate tab rather than in the same File Explorer window. If you plan to open the image in another window, you can do it from the image folder as well. So, future builds should include an option to preview the image in the File Explorer window. Otherwise, you are opening two apps to achieve the same thing. The Gallery section cannot list any videos as well and just ignores all the video files.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-skills.techidaily.com/new-the-pinnacle-of-vr-how-htc-vive-transforms-playtime/"><u>[New] The Pinnacle of VR  How HTC Vive Transforms Playtime</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ransform-your-short-form-content-top-10-mobile-video-cutting-tools-for-2024/"><u>[New] Transform Your Short-Form Content  Top 10 Mobile Video Cutting Tools for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-audiophiles-guide-techniques-to-elevate-sound-recording-for-2024/"><u>[Updated] Audiophile's Guide  Techniques to Elevate Sound Recording for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-crafting-perfect-youtube-introend-videos-at-no-cost/"><u>[Updated] In 2024, Crafting Perfect YouTube Intro/End Videos at No Cost</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-phantom-3-vs-phantom-4-for-2024/"><u>[Updated] Phantom 3 Vs Phantom 4 for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-seedling-selections-a-farmers-best-game-gems/"><u>[Updated] Seedling Selections  A Farmer's Best Game Gems</u></a></li>
<li><a href="https://win11.techidaily.com/compact-connoisseurs-panasonic-choice/"><u>Compact Connoisseur's Panasonic Choice</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-mute-status-in-windows-audiosystem/"><u>Correcting Mute Status in Windows Audiosystem</u></a></li>
<li><a href="https://unlock-android.techidaily.com/downloading-samfw-frp-tool-30-for-tecno-spark-20-by-drfone-android/"><u>Downloading SamFw FRP Tool 3.0 for Tecno Spark 20</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-recycling-bin-errors-on-windows-11/"><u>Eliminating Recycling Bin Errors on WIndows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unsupported-fingerprint-detector-issue-on-pc/"><u>Fixing Unsupported Fingerprint Detector Issue on PC</u></a></li>
<li><a href="https://win11.techidaily.com/flawless-functionality-in-windows-zoom-eliminate-error-1132/"><u>Flawless Functionality in Windows Zoom - Eliminate Error 1132</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-tackling-cc-issues-with-ease-in-window-10/"><u>Guide to Tackling CC Issues with Ease in Window 10</u></a></li>
<li><a href="https://win11.techidaily.com/hacks-expose-trust-in-your-biometric-windows-lock/"><u>Hacks Expose: Trust in Your Biometric Windows Lock</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-a-visual-disk-space-analyzer-tool-to-the-context-menu-in-windows-11-and-11/"><u>How to Add a Visual Disk Space Analyzer Tool to the Context Menu in Windows 11 & 11</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/how-to-add-bitmoji-to-keyboard-in-2024/"><u>How to Add Bitmoji to Keyboard, In 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-touch-screen-on-nubia-z50s-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Nubia Z50S Pro | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-6s-to-other-iphone-15-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 6s To Other iPhone 15 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-update-folder-icons-on-windows/"><u>How to Update Folder Icons on Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-bypassing-google-account-with-vnrom-bypass-for-infinix-smart-7-by-drfone-android/"><u>In 2024, Bypassing Google Account With vnROM Bypass For Infinix Smart 7</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-taskbar-organization-in-win-11/"><u>Mastering Taskbar Organization in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-network-key-inconsistencies-5-steps-for-windows-users/"><u>Navigating Through Network Key Inconsistencies: 5 Steps for Windows Users</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-top-10-anime-movies-of-all-time-for-2024/"><u>New Top 10 Anime Movies of All Time for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-data-flow-four-essential-steps-to-access-disk-management-in-win11/"><u>Optimize Data Flow: Four Essential Steps to Access Disk Management in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-limitations-without-moving-to-newest-os/"><u>Overcoming Limitations without Moving to Newest OS</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-dictionary-features-in-win11/"><u>Quick Guide to Dictionary Features in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/secure-your-cortana-journey-backup-and-restore-guide/"><u>Secure Your Cortana Journey: Backup and Restore Guide</u></a></li>
<li><a href="https://win11.techidaily.com/tidy-up-files-adopt-the-minimalist-way-with-windows-explorer/"><u>Tidy Up Files: Adopt the Minimalist Way with Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/trimming-up-surplus-graphics-from-windows-search/"><u>Trimming Up Surplus Graphics From Windows Search</u></a></li>
<li><a href="https://win11.techidaily.com/uncommon-processes-a-task-manager-tale/"><u>Uncommon Processes: A Task Manager Tale</u></a></li>
<li><a href="https://win11.techidaily.com/unveil-top-6-trackers-to-master-your-computerinas-windows-domain/"><u>Unveil Top 6 Trackers to Master Your Computer'inas Windows Domain</u></a></li>
</ul></div>
