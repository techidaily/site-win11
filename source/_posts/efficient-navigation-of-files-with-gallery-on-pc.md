---
title: Efficient Navigation of Files with Gallery on PC
date: 2024-06-25T11:37:33.451Z
updated: 2024-06-26T11:37:33.451Z
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

 The gallery app allows you to adjust the view of the image tiles to accommodate more or less in a single window. You can use the View option in the menu bar of File Explorer to change the image tile size. If you click on any image, it will open in a separate app window (Photos app or any other app that you use).

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
<li><a href="https://win11.techidaily.com/bringing-peace-sleep-functions-in-windows/"><u>Bringing Peace: Sleep Functions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-your-pc-with-apples-imessage/"><u>Setting Up Your PC with Apple's iMessage</u></a></li>
<li><a href="https://win11.techidaily.com/from-blank-canvases-to-dynamic-displays-on-win-1011/"><u>From Blank Canvases to Dynamic Displays on Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-remedying-windows-11-app-error-afc/"><u>Understanding and Remedying Windows 11 APP Error AFC</u></a></li>
<li><a href="https://win11.techidaily.com/end-of-windows-subsystem-preparing-for-androids-future/"><u>End of Windows Subsystem: Preparing For Android's Future</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11s-program-compatibility-troubleshooter/"><u>Mastering Windows 11'S Program Compatibility Troubleshooter</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-fix-microsoft-powerpoint-not-printing-correctly-on-windows/"><u>9 Ways to Fix Microsoft PowerPoint Not Printing Correctly on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-clear-unidentified-devices-issue-in-win-11/"><u>How to Clear Unidentified Devices Issue in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-win1011-nvidia-opengl-error-3/"><u>Overcoming Win10/11 NVIDIA OpenGL Error 3</u></a></li>
<li><a href="https://win11.techidaily.com/making-your-desktop-more-dynamic-activate-windows-11-widget-bar/"><u>Making Your Desktop More Dynamic: Activate Window's 11 Widget Bar</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-swift-restoration-retrieving-lost-fb-access-for-2024/"><u>[New] Swift Restoration  Retrieving Lost FB Access for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-joint-recording-of-webcam-and-desktop-display/"><u>[Updated] Joint Recording of Webcam and Desktop Display</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-mastering-minecraft-screen-capture-a-mac-guide/"><u>[Updated] In 2024, Mastering Minecraft Screen Capture  A Mac Guide</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/the-essential-software-catalog-for-isolating-audio-from-videos-as-for-2024/"><u>The Essential Software Catalog for Isolating Audio From Videos As for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-snapchat-secrets-lowering-playback-rate-for-better-views/"><u>[New] In 2024, Snapchat Secrets  Lowering Playback Rate for Better Views</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-the-art-of-instagram-video-craftsmanship-for-2024/"><u>[New] The Art of Instagram Video Craftsmanship for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-maximizing-video-quality-in-zoom-conferences/"><u>[New] Maximizing Video Quality in Zoom Conferences</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-from-live-to-digital-preserving-your-skype-talks/"><u>[Updated] 2024 Approved  From Live to Digital  Preserving Your Skype Talks</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-flash-dead-realme-gt-5-pro-safely-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Flash Dead Realme GT 5 Pro Safely | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-highlighting-tiktoks-most-sharing-moments/"><u>[New] In 2024, Highlighting TikTok's Most Sharing Moments</u></a></li>
</ul></div>
