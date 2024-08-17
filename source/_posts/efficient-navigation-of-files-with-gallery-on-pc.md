---
title: Efficient Navigation of Files with Gallery on PC
date: 2024-08-15T23:55:26.489Z
updated: 2024-08-16T23:55:26.489Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Efficient Navigation of Files with Gallery on PC
excerpt: This Article Describes Efficient Navigation of Files with Gallery on PC
keywords: File Navigation,PC File Organizer,Gallery Viewing,Quick File Access,Improved File Layout,Enhanced Data Management,Intuitive File System,Efficient Navigation -,Gallery Files PC -,Organize Files Quickly,Access Files Easily,File System Layout,Data Management Intuitive,File System Improved
thumbnail: https://thmb.techidaily.com/8a64098fc8c00724b390ed4672a78681ea9b2ccc0c75a67c21e60baebffadabf.jpg
---

## Efficient Navigation of Files with Gallery on PC

 Windows 11’s File Explorer has a tabs feature now. You can open a new location on the disk in a new tab rather than opening a new File Explorer window. Switching between multiple file locations is seamless, all thanks to this feature. But Microsoft isn’t planning to stop here. It wants to completely overhaul the File Explorer.

 File Explorer Gallery is one such new feature that Microsoft is testing in the Canary channel. Having a Gallery section will remove the need to browse separate folders to find or preview an image. Want to enable the feature on your system? Let’s begin.

## What Is the Gallery Feature in Windows File Explorer?

 File Explorer’s Gallery feature works exactly like it sounds. It categorically lists all the images on your system in a separate section, so you can find and view all the images in one tab. Android File Explorers have had this feature for quite a long, but Windows seems to care about it now.

 This new feature is available in the Windows Insider build version 25300 and above. But Microsoft made a big change to the Insider program by adding a Canary channel. So, any new Canary build will also have this experimental feature. Microsoft adds the new File Explorer based on Windows App SDK, which you can verify by hovering over the “pizza” icon in the File Explorer address bar.

 The Gallery section displays images from the Pictures and OneDrive folders and lists them by date. It has nice, rounded corners around each image in the Gallery section, which makes it feel like a part of the overall Windows 11 design. It appears right below the Home option in the left pane.

## How to Enable Gallery in File Explorer in Windows 11

 Repeat the following steps to enable the new Gallery section in File Explorer:

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Update to the Appropriate Windows Insider Build

 The Gallery section is hidden in Insider builds 25300 and above. If you are a Windows Insider program participant, open and check for the latest Insider builds on your system. Make sure to be in the Dev or Canary channel because this experimental feature is exclusive to these channels only. Or, you can use [UUP Dump to download Windows Insider builds without participating in Microsoft’s Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Download ViVeTool

 You will also need ViVeTool to enable these experimental features on your system. You can [download ViVetool from GitHub](https://github.com/thebookisclosed/ViVe/releases) , but make sure that you pick the most recent release. Extract the tool to the C drive and then proceed to the next section.

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
### 2\. Enabling Gallery in Windows File Explorer

 Retrace the following steps to enable the Gallery section on Windows 11:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**cmd** and press**Ctrl + Shift + Enter** keys at once to open a new Command Prompt window with administrator privileges.
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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Restart your computer for the changes made by Vivetool to take effect.
9. Once your computer boots up, press**Win + E** to open File Explorer. You will see a new**Gallery** option in the left pane below the**Home** option.

## How to View the Gallery in File Explorer

 You can access the Gallery section by launching File Explorer and clicking on the Gallery option in the left navigation pane. You will see all the images from the Pictures folder and OneDrive folder arranged by modification time (new to old). There is also a handy slider to scroll through the vast image tiles without using the mouse scroll wheel.

![Gallery in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/gallery-in-windows-file-explorer.jpg)

 The gallery app allows you to adjust the view of the image tiles to accommodate more or less in a single window. You can use the View option in the menu bar of File Explorer to change the image tile size. If you click on any image, it will open in a separate app window (Photos app or any other app that you use).

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Add or Remove Locations From Gallery in Windows File Explorer

 By default, the Gallery selection displays all the images located in the Pictures folder and OneDrive. But you can add or remove a folder from the Gallery section as well.

1. To add a folder to the Gallery, go to the menu bar and click on the**Locations** option. A new pop-up window will open and list all the folders that the Gallery section is pulling images from. Click on the**Add** button.  
![Adding a Folder to Gallery in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/adding-a-folder-to-gallery-in-windows-file-explorer.jpg)
2. Now select any folder or sub-folder with images and click on the**Include Folder** button.
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
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-video-lessons-to-visual-gigs-youtube-videos-converted-seamlessly/"><u>[New] 2024 Approved  From Video Lessons to Visual Gigs  YouTube Videos Converted Seamlessly</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-step-by-step-guide-to-designing-impactful-imagery/"><u>[New] Step-by-Step Guide to Designing Impactful Imagery</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unlocking-optimal-flight-the-lipo-selection-saga/"><u>[New] Unlocking Optimal Flight  The LiPo Selection Saga</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-avoid-common-pitfalls-with-proper-use-of-youtube-tags/"><u>[Updated] 2024 Approved  Avoid Common Pitfalls with Proper Use of YouTube Tags</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-the-insiders-guide-to-recording-on-itunes/"><u>[Updated] 2024 Approved  The Insider's Guide to Recording on iTunes</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-building-a-million-views-empire-safe-and-secure-methods/"><u>[Updated] In 2024, Building a Million Views Empire  Safe and Secure Methods</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-unlocking-video-content-secure-facebook-live-recordings/"><u>[Updated] Unlocking Video Content  Secure Facebook Live Recordings</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-the-ultimate-guide-to-budget-drone-flights/"><u>2024 Approved  The Ultimate Guide to Budget Drone Flights</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-techniques-to-transfer-data-from-xiaomi-redmi-a2plus-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Techniques to Transfer Data from Xiaomi Redmi A2+ to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/android-safe-mode-how-to-turn-off-safe-mode-on-tecno-spark-20-proplus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Safe Mode - How to Turn off Safe Mode on Tecno Spark 20 Pro+? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/brightening-your-computerenas-dark-background-issue/"><u>Brightening Your Computer'enas Dark Background Issue</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-conflicting-apps-in-windows-10/"><u>Dealing with 'Conflicting Apps' In Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/decode-widows-code-to-unfreeze-handbrake/"><u>Decode Widows' Code to Unfreeze HandBrake</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/discover-free-sound-fx-websites-and-integrate-with-final-cut-pro/"><u>Discover Free Sound FX Websites and Integrate with Final Cut Pro</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-support-paths-for-common-windows-concerns/"><u>Efficient Support Paths for Common Windows Concerns</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-icon-visibility-windows-11s-hidden-menus/"><u>Elevate Icon Visibility: Windows 11'S Hidden Menus</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-digital-life-with-exclusive-ms-choice/"><u>Elevate Your Digital Life with Exclusive MS Choice</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-key-collectors-deal-wintry-windows-11-priced-at-612-per-year/"><u>Exclusive Key Collector's Deal - Wintry Windows 11 Priced at $6.12 Per Year</u></a></li>
<li><a href="https://win11.techidaily.com/from-basic-to-winning-converting-batch-to-executable/"><u>From Basic to Winning: Converting Batch to Executable</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-decrease-extras-in-win-11-context-list/"><u>How to Decrease Extras in Win 11 Context List</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-vivo-s18e-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Vivo S18e without Losing Data | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-nokia-130-music-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track Nokia 130 Music Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-change-infinix-hot-40i-lock-screen-clock-in-seconds-by-drfone-android/"><u>In 2024, How To Change Infinix Hot 40i Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://win11.techidaily.com/mending-disconnected-google-drive-windows-filesystem/"><u>Mending Disconnected Google Drive Windows Filesystem</u></a></li>
<li><a href="https://win11.techidaily.com/modifying-oculus-quest-2-for-windows-vr-use/"><u>Modifying Oculus Quest 2 for Windows VR Use</u></a></li>
<li><a href="https://buynow-info.techidaily.com/power-up-your-devices-with-aukeys-sleek-usb-3and-hub-review/"><u>Power Up Your Devices with Aukey's Sleek USB 3.([&] Hub Review)</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-absence-of-monitor-on-startup/"><u>Remedy for Absence of Monitor on Startup</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-sluggish-outlook-on-your-computer/"><u>Sidestep Sluggish Outlook on Your Computer</u></a></li>
<li><a href="https://win11.techidaily.com/stealth-mode-hiding-or-revealing-windows-protection-sectors/"><u>Stealth Mode: Hiding or Revealing Windows Protection Sectors</u></a></li>
<li><a href="https://facebook.techidaily.com/the-5-most-noteworthy-tech-failures-in-recent-times/"><u>The 5 Most Noteworthy Tech Failures in Recent Times</u></a></li>
<li><a href="https://win11.techidaily.com/the-blueprint-how-to-enhance-your-workflow-via-menus/"><u>The Blueprint: How to Enhance Your Workflow via Menus</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-guide-to-file-compression-via-cli/"><u>The Essential Guide to File Compression via CLI</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-assembling-a-taskbar-on-windows-11-slate/"><u>The Ultimate Guide to Assembling a Taskbar on Windows 11 Slate</u></a></li>
<li><a href="https://android-frp.techidaily.com/ultimate-guide-from-motorola-moto-g24-frp-bypass-by-drfone-android/"><u>Ultimate Guide from Motorola Moto G24 FRP Bypass</u></a></li>
<li><a href="https://win11.techidaily.com/window-terminal-design-your-own-palette/"><u>Window Terminal: Design Your Own Palette</u></a></li>
<li><a href="https://win11.techidaily.com/winerror-solved-addressing-ms-store-0x80072f17/"><u>WinError Solved: Addressing MS Store 0X80072f17</u></a></li>
</ul></div>
