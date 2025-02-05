---
title: Navigate Photos with Windows 11 Explorer Shortcuts
date: 2025-01-30T20:12:35.127Z
updated: 2025-02-03T17:16:40.170Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Update to the Appropriate Windows Insider Build

 The Gallery section is hidden in Insider builds 25300 and above. If you are a Windows Insider program participant, open and check for the latest Insider builds on your system. Make sure to be in the Dev or Canary channel because this experimental feature is exclusive to these channels only. Or, you can use[UUP Dump to download Windows Insider builds without participating in Microsoft’s Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

### 2\. Download ViVeTool

 You will also need ViVeTool to enable these experimental features on your system. You can[download ViVetool from GitHub](https://github.com/thebookisclosed/ViVe/releases) , but make sure that you pick the most recent release. Extract the tool to the C drive and then proceed to the next section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Problems With the Gallery Section in Windows File Explorer

 The current preview of the Gallery feature is far from perfect. Firstly, the section works well in finding and categorically listing all the images from the included folders. But the images, despite being big, appear hazy. What’s the point of including a section if the images aren’t visible clearly?

 There is also the issue of images opening in a separate tab rather than in the same File Explorer window. If you plan to open the image in another window, you can do it from the image folder as well. So, future builds should include an option to preview the image in the File Explorer window. Otherwise, you are opening two apps to achieve the same thing. The Gallery section cannot list any videos as well and just ignores all the video files.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aRMCbJxLuwE?si=E5sfJvoqkv1qCMWz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://vp-tips.techidaily.com/new-in-2024-compare-and-contrast-best-6-hdmi-monitor-models-in-detail/"><u>[New] In 2024, Compare & Contrast Best 6 HDMI Monitor Models in Detail</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-instagram-enhancement-picture-posting-guide-for-2024/"><u>[New] Instagram Enhancement Picture Posting Guide for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-professional-mix-techniques-for-crossfading-sounds-with-audacity-for-2024/"><u>[New] Professional Mix Techniques for Crossfading Sounds with Audacity for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-streamlining-social-sharing-coordinating-vids-on-tweets-plus-tumbles/"><u>[Updated] In 2024, Streamlining Social Sharing Coordinating Vids on Tweets + Tumbles</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-vivo-x-flip-drfone-by-drfone-virtual-android/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Vivo X Flip | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/convert-websites-to-windows-desktop-applications/"><u>Convert Websites to Windows Desktop Applications</u></a></li>
<li><a href="https://win-able.techidaily.com/fixes-for-when-dirt-5-continuously-fails-on-your-pc/"><u>Fixes For When Dirt 5 Continuously Fails On Your PC</u></a></li>
<li><a href="https://extra-resources.techidaily.com/hilarity-renderings-kapwings-image-craft/"><u>Hilarity Renderings Kapwing's Image Craft</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-realme-c53-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Realme C53 PC | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/is-fake-gps-location-spoofer-a-good-choice-on-samsung-galaxy-xcover-7-drfone-by-drfone-virtual-android/"><u>Is Fake GPS Location Spoofer a Good Choice On Samsung Galaxy XCover 7? | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/is-it-time-to-upgrade-comparing-features-of-galaxy-s23-and-s21-ultra/"><u>Is It Time to Upgrade? Comparing Features of Galaxy S23 & S21 Ultra</u></a></li>
<li><a href="https://win11.techidaily.com/rapid-typing-learning-from-typingaid-methods/"><u>Rapid Typing Learning From TypingAid Methods</u></a></li>
<li><a href="https://win11.techidaily.com/reconstructing-the-windows-icon-database/"><u>Reconstructing the Windows Icon Database</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-bsod-when-using-vmware-in-windows-11/"><u>Remedying BSOD when Using VMware in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-no-login-issue-on-windows-1011-screens/"><u>Resolving No-Login Issue on Windows 10/11 Screens</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-standard-operations-in-managed-organizational-browsers-chromeedge/"><u>Restoring Standard Operations in Managed Organizational Browsers (Chrome/Edge)</u></a></li>
<li><a href="https://win11.techidaily.com/seamlessly-merge-kali-into-your-windows/"><u>Seamlessly Merge Kali Into Your Windows</u></a></li>
<li><a href="https://win11.techidaily.com/secure-your-work-with-a-customized-windows-sandbox-win-11/"><u>Secure Your Work with a Customized Windows Sandbox (Win 11)</u></a></li>
<li><a href="https://win11.techidaily.com/seven-steps-to-unlocking-windows-11-memory-safety/"><u>Seven Steps to Unlocking Windows 11 Memory Safety</u></a></li>
</ul></div>

