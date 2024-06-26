---
title: "Quick Glance: Windows 11 Expert Guide to Image Access"
date: 2024-06-25T10:20:43.682Z
updated: 2024-06-26T10:20:43.682Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick Glance: Windows 11 Expert Guide to Image Access"
excerpt: "This Article Describes Quick Glance: Windows 11 Expert Guide to Image Access"
keywords: Win11 Image Viewing,Windows 11 Photo Access,Navigate Images in Win11,Master Windows Image View,Windows 11 Picture Inspect,Quick Guide to WinImage,Expert Win11 Image Lookup
thumbnail: https://thmb.techidaily.com/e874e7774ed1bae47e14908261fcbf31de304eed1c8fec16cc5f931b201e9fca.jpg
---

## Quick Glance: Windows 11 Expert Guide to Image Access

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
<li><a href="https://win11.techidaily.com/guides-to-rectifying-confirm-pin-error-in-w11w10-setups/"><u>Guides to Rectifying Confirm PIN Error in W11/W10 Setups</u></a></li>
<li><a href="https://win11.techidaily.com/solving-the-jittery-cursor-problem-on-windows-xp/"><u>Solving the Jittery Cursor Problem on Windows XP</u></a></li>
<li><a href="https://win11.techidaily.com/fix-inflexible-scrollbar-issue-in-microsoft-excel-2016/"><u>Fix Inflexible Scrollbar Issue in Microsoft Excel 2016</u></a></li>
<li><a href="https://win11.techidaily.com/win11-steps-to-correct-steam-file-privileges-failure/"><u>Win11 Steps to Correct Steam File Privileges Failure</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-file-properties-a-windowayers-manual/"><u>Fine-Tuning File Properties: A Window'ayer's Manual</u></a></li>
<li><a href="https://win11.techidaily.com/craft-command-capabilities-for-the-windowed-world/"><u>Craft Command Capabilities for the Windowed World</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-program-install-pathways-in-windows/"><u>Unveiling Program Install Pathways in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-handling-windows-updater-problems-focusing-on-error-0x80070003/"><u>Decoding and Handling Windows Updater Problems: Focusing on Error 0X80070003</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/extract-sound-from-instagram-reels-and-videos-for-2024/"><u>Extract Sound From Instagram Reels and Videos for 2024</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-how-to-fake-gps-on-android-without-mock-location-for-your-vivo-v29-pro-drfone-by-drfone-virtual/"><u>In 2024, How to Fake GPS on Android without Mock Location For your Vivo V29 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-step-by-step-guide-to-screen-capturing-hulu-content-seamlessly-for-2024/"><u>[Updated] Step-by-Step Guide to Screen Capturing Hulu Content Seamlessly for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/create-professional-valorant-thumbnails-in-no-time-for-2024/"><u>Create Professional Valorant Thumbnails in No Time for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-13-pro-max-apples-new-iphone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 13 Pro Max, Apples New iPhone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-amplify-content-with-free-audio-samples/"><u>[New] 2024 Approved  Amplify Content with Free Audio Samples</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-balance-aesthetics-and-functionality-on-instagram/"><u>[New] Balance Aesthetics and Functionality on Instagram</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-make-a-lasting-impression-how-to-create-professional-looking-dvds/"><u>Updated 2024 Approved Make a Lasting Impression How to Create Professional-Looking DVDs</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-ultimate-guide-to-securing-photographic-backdrops/"><u>[Updated] Ultimate Guide to Securing Photographic Backdrops</u></a></li>
</ul></div>
