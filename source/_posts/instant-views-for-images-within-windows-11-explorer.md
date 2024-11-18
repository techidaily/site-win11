---
title: Instant Views for Images Within Windows 11 Explorer
date: 2024-11-15T01:42:27.232Z
updated: 2024-11-18T03:21:20.100Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Instant Views for Images Within Windows 11 Explorer
excerpt: This Article Describes Instant Views for Images Within Windows 11 Explorer
keywords: Instant Image Display,Windows Explorer Image View,Quick Image Explore,Windows Explorer Gallery,Fast Image Windows Access,Immediate Picture Viewer,Windows 11 Image Inspector
thumbnail: https://thmb.techidaily.com/c07b7ea823a20fff0d48f1accc60826d6016566f3469f152eba0254ae0b7e1bc.jpg
---

## Instant Views for Images Within Windows 11 Explorer

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

<!-- affiliate ads begin -->
<span id="1982570">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982570.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982570">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982570.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982570%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982570/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Once your computer boots up, press**Win + E** to open File Explorer. You will see a new**Gallery** option in the left pane below the**Home** option.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098700/14409" target="_top" id="2098700">
  <img src="//a.impactradius-go.com/display-ad/14409-2098700" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098700/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to View the Gallery in File Explorer

 You can access the Gallery section by launching File Explorer and clicking on the Gallery option in the left navigation pane. You will see all the images from the Pictures folder and OneDrive folder arranged by modification time (new to old). There is also a handy slider to scroll through the vast image tiles without using the mouse scroll wheel.

![Gallery in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/gallery-in-windows-file-explorer.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094428/7443" target="_top" id="2094428">
  <img src="//a.impactradius-go.com/display-ad/7443-2094428" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094428/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The gallery app allows you to adjust the view of the image tiles to accommodate more or less in a single window. You can use the View option in the menu bar of File Explorer to change the image tile size. If you click on any image, it will open in a separate app window (Photos app or any other app that you use).

## How to Add or Remove Locations From Gallery in Windows File Explorer

 By default, the Gallery selection displays all the images located in the Pictures folder and OneDrive. But you can add or remove a folder from the Gallery section as well.

1. To add a folder to the Gallery, go to the menu bar and click on the**Locations** option. A new pop-up window will open and list all the folders that the Gallery section is pulling images from. Click on the**Add** button.  
![Adding a Folder to Gallery in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/adding-a-folder-to-gallery-in-windows-file-explorer.jpg)
2. Now select any folder or sub-folder with images and click on the**Include Folder** button.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/857869/11832" target="_top" id="857869">
  <img src="//a.impactradius-go.com/display-ad/11832-857869" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/857869/11832" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2006919/19272" target="_top" id="2006919">
  <img src="//a.impactradius-go.com/display-ad/19272-2006919" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006919/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-video-recordings.techidaily.com/updated-elevate-engagement-crafting-effective-youtube-backlinks/"><u>[Updated] Elevate Engagement Crafting Effective YouTube Backlinks</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-professional-opinions-best-9-digital-microphone-capture-gear-for-2024/"><u>[Updated] Professional Opinions Best 9 Digital Microphone Capture Gear for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-unlocking-google-chromes-pip-potential-on-all-platforms-for-2024/"><u>[Updated] Unlocking Google Chrome's PIP Potential on All Platforms for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-look-at-the-future-leading-photo-framing-apps-for-2024/"><u>A Look at the Future Leading Photo Framing Apps for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-enhanced-productivity-through-a-90-degree-display-reorientation/"><u>Harnessing Enhanced Productivity Through a 90-Degree Display Reorientation</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-app-induced-power-control-failures-in-windows/"><u>How To Overcome App-Induced Power Control Failures in Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/methods-to-change-gps-location-on-honor-magic-6-lite-drfone-by-drfone-virtual-android/"><u>Methods to Change GPS Location On Honor Magic 6 Lite | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reset-the-frozen-netflix-app-in-windows/"><u>Steps to Reset the Frozen Netflix App in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-efficiently-operating-windows-print-management-interface/"><u>Tips for Efficiently Operating Windows Print Management Interface</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/top-10-channels-to-watch-on-igtv-daily/"><u>Top 10 Channels to Watch on IGTV Daily</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-guide-solving-battlefield-v-crash-problems-for-a-smoother-gaming-experience/"><u>Troubleshooting Guide: Solving Battlefield V Crash Problems for a Smoother Gaming Experience</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/why-snapchats-my-ai-stands-out-beyond-toys-and-games/"><u>Why Snapchat’s My AI Stands Out Beyond Toys and Games</u></a></li>
</ul></div>

