---
title: How to Enable the Gallery in File Explorer in Windows 11
date: 2024-07-13T11:01:10.626Z
updated: 2024-07-14T11:01:10.626Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Enable the Gallery in File Explorer in Windows 11
excerpt: This Article Describes How to Enable the Gallery in File Explorer in Windows 11
keywords: Enable Gallery Windows 11,File Explorer Gallery,Gallery Access Window,Windows 11 Gallery View,File Explore Photo Viewer,Windows 11 Image Display,Enabling Gallery in PC
thumbnail: https://thmb.techidaily.com/fb9dc69321147c58e76f643c816e11fbbc732b6fd56c746767b53b83551e6f78.jpg
---

## How to Enable the Gallery in File Explorer in Windows 11

 Windows 11’s File Explorer has a tabs feature now. You can open a new location on the disk in a new tab rather than opening a new File Explorer window. Switching between multiple file locations is seamless, all thanks to this feature. But Microsoft isn’t planning to stop here. It wants to completely overhaul the File Explorer.

 File Explorer Gallery is one such new feature that Microsoft is testing in the Canary channel. Having a Gallery section will remove the need to browse separate folders to find or preview an image. Want to enable the feature on your system? Let’s begin.

## What Is the Gallery Feature in Windows File Explorer?

 File Explorer’s Gallery feature works exactly like it sounds. It categorically lists all the images on your system in a separate section, so you can find and view all the images in one tab. Android File Explorers have had this feature for quite a long, but Windows seems to care about it now.

 This new feature is available in the Windows Insider build version 25300 and above. But Microsoft made a big change to the Insider program by adding a Canary channel. So, any new Canary build will also have this experimental feature. Microsoft adds the new File Explorer based on Windows App SDK, which you can verify by hovering over the “pizza” icon in the File Explorer address bar.

 The Gallery section displays images from the Pictures and OneDrive folders and lists them by date. It has nice, rounded corners around each image in the Gallery section, which makes it feel like a part of the overall Windows 11 design. It appears right below the Home option in the left pane.

## How to Enable Gallery in File Explorer in Windows 11

 Repeat the following steps to enable the new Gallery section in File Explorer:

### 1\. Update to the Appropriate Windows Insider Build

 The Gallery section is hidden in Insider builds 25300 and above. If you are a Windows Insider program participant, open and check for the latest Insider builds on your system. Make sure to be in the Dev or Canary channel because this experimental feature is exclusive to these channels only. Or, you can use [UUP Dump to download Windows Insider builds without participating in Microsoft’s Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

### 2\. Download ViVeTool

 You will also need ViVeTool to enable these experimental features on your system. You can [download ViVetool from GitHub](https://github.com/thebookisclosed/ViVe/releases) , but make sure that you pick the most recent release. Extract the tool to the C drive and then proceed to the next section.

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
<li><a href="https://screen-video-capture.techidaily.com/in-2024-mastering-quick-mac-screen-capture-with-deft-shortcuts/"><u>In 2024, Mastering Quick Mac Screen Capture with Deft Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/method-to-release-administrator-restricted-apps/"><u>Method to Release Administrator-Restricted Apps</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-perfecting-your-valorant-thumbnails-a-comprehensive-tutorial/"><u>In 2024, Perfecting Your Valorant Thumbnails  A Comprehensive Tutorial</u></a></li>
<li><a href="https://youtube-help.techidaily.com/how-to-keep-unwanted-content-away-from-your-computer-and-phone-for-2024/"><u>How to Keep Unwanted Content Away From Your Computer and Phone for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-honor-play-8t-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Honor Play 8T Phones? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/6-fixes-to-try-if-the-right-click-context-menu-gets-stuck-in-windows/"><u>6 Fixes to Try if the Right Click Context Menu Gets Stuck in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-mask-after-dim-display-option-on-pcs/"><u>Steps to Mask After Dim Display Option on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/winning-speed-efficient-download-strategies-for-valorant-on-pc/"><u>Winning Speed: Efficient Download Strategies for Valorant on PC</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-manage-secure-boot-and-tpm-settings-on-virtualbox-70/"><u>Step-by-Step Guide to Manage Secure Boot & TPM Settings on VirtualBox 7.0</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-guide-to-windows-10s-video-creation-capabilities/"><u>[Updated] The Ultimate Guide to Windows 10'S Video Creation Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/swift-strike-against-script-failures-in-windows/"><u>Swift Strike Against Script Failures in Windows</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-inside-the-tech-a-comprehensive-review-of-apowersofts-recorder/"><u>[New] In 2024, Inside the Tech  A Comprehensive Review of Apowersoft’s Recorder</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-taskbar-design-proposals-for-windows-11s-user-interaction-improvements/"><u>Elevating Taskbar Design: Proposals for Windows 11'S User Interaction Improvements</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-ultimate-directory-top-10-sources-for-free-graphics/"><u>[Updated] The Ultimate Directory  Top 10 Sources for Free Graphics</u></a></li>
<li><a href="https://win11.techidaily.com/flattening-windows-11-corner-style/"><u>Flattening Windows 11 Corner Style</u></a></li>
<li><a href="https://games-able.techidaily.com/1719172780797-hot-10-gaming-picks-sonys-summertime-savings/"><u>Hot 10 Gaming Picks: Sony's Summertime Savings</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-glitches-and-error-0xc00d36b4-on-windows/"><u>Troubleshooting Glitches & Error 0xC00D36B4 on Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-print-service-non-responsive/"><u>Solved: Print Service Non-Responsive</u></a></li>
<li><a href="https://win11.techidaily.com/preserving-customization-transferring-powertoys-to-a-new-machine/"><u>Preserving Customization: Transferring PowerToys to a New Machine</u></a></li>
<li><a href="https://win11.techidaily.com/winpc-restoring-lost-connections-with-easy-6-strategies-for-troubleshooting-adapters/"><u>WinPC: Restoring Lost Connections with Easy 6 Strategies for Troubleshooting Adapters</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-techniques-for-moving-files-in-windows-11/"><u>Boost Productivity: Techniques for Moving Files in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-google-maps-installation-on-pc/"><u>Quick Guide: Google Maps Installation on PC</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-end-your-videos-professionally-with-these-free-tools-top-6/"><u>[New] 2024 Approved  End Your Videos Professionally with These Free Tools (Top 6)</u></a></li>
<li><a href="https://win11.techidaily.com/instructions-for-completely-getting-rid-of-wsl-on-win-11/"><u>Instructions for Completely Getting Rid of WSL on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-power-of-your-laptops-touch-sensitivity-with-ease/"><u>Unleash the Power of Your Laptop's Touch Sensitivity with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/contrasting-features-of-installation-methods-exe-vs-msi-files/"><u>Contrasting Features of Installation Methods: Exe vs Msi Files</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-the-art-of-adding-descriptive-texts-in-tiktok-videos/"><u>[Updated] In 2024, The Art of Adding Descriptive Texts in TikTok Videos</u></a></li>
<li><a href="https://win11.techidaily.com/windows-mastering-app-and-browser-oversight/"><u>Windows: Mastering App & Browser Oversight</u></a></li>
<li><a href="https://howto.techidaily.com/play-store-stuck-on-downloading-of-realme-narzo-60-pro-5g-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of Realme Narzo 60 Pro 5G? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-integrating-text-overlays-into-social-media-streaming/"><u>[New] Integrating Text Overlays Into Social Media Streaming</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-pinpointing-instagram-follower-losses-on-the-fly/"><u>[Updated] In 2024, Pinpointing Instagram Follower Losses on the Fly</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-tune-into-your-instagram-feed-music-integration-essentials/"><u>[New] Tune Into Your Instagram Feed  Music Integration Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-complexities-of-windows-system-restore-for-easy-rollbacks/"><u>Unraveling the Complexities of Windows System Restore for Easy Rollbacks</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-lsassexe-unable-to-locate-error-on-win-810/"><u>How to Overcome lsass.exe Unable to Locate Error on Win 8/10</u></a></li>
<li><a href="https://win11.techidaily.com/quick-compression-and-decompression-tactics-in-windows-cli/"><u>Quick Compression & Decompression Tactics in Windows CLI</u></a></li>
<li><a href="https://win11.techidaily.com/deciding-between-upgrades-here-are-7-reasons-for-win10/"><u>Deciding Between Upgrades? Here Are 7 Reasons for Win10</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-anything-from-oppo-f23-5g-to-apple-tv-drfone-by-drfone-android/"><u>How To Stream Anything From Oppo F23 5G to Apple TV | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-disabled-security-authority-on-desktops/"><u>Remedy for Disabled Security Authority on Desktops</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-the-ultimate-guide-to-free-avi-video-rotators-top-5/"><u>In 2024, The Ultimate Guide to Free AVI Video Rotators Top 5</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-samsung-galaxy-s23-tactical-edition-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Samsung Galaxy S23 Tactical Edition | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-properties-puzzles-in-windows-os/"><u>Unveiling Properties Puzzles in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-the-mystery-of-infinite-c-drive-usage/"><u>Combatting the Mystery of Infinite C: Drive Usage</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-the-ultimate-list-of-free-video-stabilizer-apps-for-android-users/"><u>2024 Approved The Ultimate List of Free Video Stabilizer Apps for Android Users</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-elite-no-price-facebook-visual-storytelling-suite/"><u>[New] Elite No-Price Facebook Visual Storytelling Suite</u></a></li>
<li><a href="https://win11.techidaily.com/curbing-problems-with-outlooks-error-0x80040610-on-windows/"><u>Curbing Problems with Outlook's Error 0X80040610 on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-asana-glitches-on-pc/"><u>Troubleshooting Asana Glitches on PC</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-divide-recovering-lost-winvpn-links/"><u>Bridging the Divide: Recovering Lost WinVPN Links</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-unleash-creativity-professional-insights-into-shooting-and-editing-stunning-slow-motion-content-for-instagram/"><u>[New] In 2024, Unleash Creativity  Professional Insights Into Shooting and Editing Stunning Slow Motion Content for Instagram</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-maximizing-your-monetary-gains-on-social-media-with-snapchat-for-2024/"><u>[New] Maximizing Your Monetary Gains on Social Media with Snapchat for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-virtualbox-v70-potential-the-upgrade-on-windows-11/"><u>Unlock VirtualBox v7.0 Potential: The Upgrade on Windows 11</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-step-by-step-guide-to-speed-up-and-slow-down-a-video/"><u>Updated Step-by-Step Guide to Speed Up and Slow Down a Video</u></a></li>
<li><a href="https://win11.techidaily.com/speak-get-text-win-a-comprehensible-guide-to-windows-whisper/"><u>Speak, Get Text, Win: A Comprehensible Guide to Windows Whisper</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-chromes-false-virus-detection-issue/"><u>Overcoming Chrome’s False Virus Detection Issue</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-oppo-f23-5g-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Oppo F23 5G to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-comprehensive-guide-to-free-cloud-communication-software-for-2024/"><u>[Updated] Comprehensive Guide to Free Cloud Communication Software for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/cut-to-perfection-top-video-editors-for-your-win11-pc/"><u>Cut-to-Perfection: Top Video Editors For Your Win11 PC</u></a></li>
</ul></div>
