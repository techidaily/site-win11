---
title: Start Windows File Explorer Using OneDrive Pathway
date: 2024-09-13T05:40:52.869Z
updated: 2024-09-17T00:59:45.905Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Start Windows File Explorer Using OneDrive Pathway
excerpt: This Article Describes Start Windows File Explorer Using OneDrive Pathway
keywords: Start File Explorer,Windows Explorer,Onedrive Access,Windows ONE DRIVE,Explore Documents,Drive Folder View,Windows ONE PATH
thumbnail: https://thmb.techidaily.com/9cc1ab34a2708ce6599562965ce7d038d6461c86c7f5043e45b0cca41d824dbd.jpg
---

## Start Windows File Explorer Using OneDrive Pathway

 When you launch Windows File Explorer, it automatically takes you to the "Quick Access" view. This page displays shortcuts to recently accessed folders and files and lists your favorite folders. It might be convenient for some users but not for others who prefer easy access to their cloud storage.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Use the Folder Options

 If you want to make OneDrive the starting point of your File Explorer, you can do so using folder options. Here's how to do it:

1. Open the Start menu and type **File Explorer** in the search box. When the File Explorer icon appears, click it to launch the app. You can also use **Win + E** to open the program quickly.
2. In the File Explorer window, look for **See more** (three dots) at the top. Clicking on it opens the Folder Options dialog box.  
![Open Folder Options in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-folder-options-in-file-explorer.jpg)
3. On the General tab, click the **Open File Explorer to** drop-down menu and select "Username Personal". Here, "Username" refers to your Windows account name.  
![Open File Explorer to OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive.jpg)
4. Click **Apply** \> **OK** to close the dialog box.

 From now on, opening File Explorer will automatically launch OneDrive rather than Quick Access.

## 2\. Using the Registry Editor

 You can also use the Registry Editor to set OneDrive as your default File Explorer view. But be warned: if you make an incorrect change to the system registry, you could damage your computer. We recommend [backing up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 Once backed up, follow these steps to make OneDrive the default view:

1. [Open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the text box and hit **Enter**.
3. If you're prompted for permission, select **Yes** to continue. The Registry Editor window will open.
4. In the Registry Editor window, navigate to this path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the right pane, locate and double-click the **LaunchTo** entry. If the entry isn't present, you'll need to create it. For that, right-click on the **Advanced** folder and select **New > DWORD (32-bit) Value**. Name the value "LaunchTo" and press Enter. Doing so will create a new DWORD in the registry.  
![Set File Explorer to Open OneDrive Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/set-file-explorer-to-open-onedrive-using-registry.jpg)
6. Double-click on this newly created value and set its value to **4**.
7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

## 3\. Using a Reg File

 The third and final method to set OneDrive as the default view involves using a reg file. It contains the necessary instructions that modify the registry on your behalf. So, if you're not comfortable using the registry editor, this is the right way to go.

 To create the reg file, follow these steps:

1. Right-click on your desktop and select **New > Text Document**.
2. Name the file **OneDrive.reg** and hit **Enter**.
3. Now open the file in a text editor such as Notepad.
4. Copy and paste the following code into the text document:  
`<code>Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced]  
"LaunchTo"=dword:00000004`
5. After pasting the given code, click **File** \> **Save as**.
6. In the Save as dialog box, select **All files** from the Save as type drop-down menu and hit Enter. Make sure the file is saved as a **.reg** file and not as a .txt file.  
![Open File Explorer to OneDrive Using REG File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive-using-reg-file.jpg)
7. Double-click the REG file you just created. If you're prompted for permission to change your computer, click **Yes**.
8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129041/19576" target="_top" id="2129041">
  <img src="//a.impactradius-go.com/display-ad/19576-2129041" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129041/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Set File Explorer to Open OneDrive Instead of Quick Access

 There you have it; three different methods to make OneDrive your default File Explorer view. If you like, you can also change other folder views, such as Downloads or This PC, using the same techniques we discussed above. I hope this guide helped you get things done quickly and easily.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-access.techidaily.com/new-2024-approved-crafting-straightforward-stories/"><u>[New] 2024 Approved Crafting Straightforward Stories</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-immerse-in-innovation-the-ultimate-vr-gear-guide/"><u>[Updated] Immerse in Innovation - The Ultimate VR Gear Guide</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-embed-youtube-in-your-gslides-presentation/"><u>[Updated] In 2024, How to Embed YouTube in Your GSlides Presentation</u></a></li>
<li><a href="https://win11.techidaily.com/pcmdsd/"><u>「優れた品質PCMへの移行：DSDオーディオからの高精度変換方法」</u></a></li>
<li><a href="https://article-tips.techidaily.com/enhance-film-scenes-with-soundtracks-in-premiere-pro/"><u>Enhance Film Scenes With Soundtracks in Premiere Pro</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-honor-x9b-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Honor X9b Phones with/without a PC</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-tecno-spark-10-pro-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Tecno Spark 10 Pro to Roku | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/install-the-newest-geforce-rtx-2070-drivers-for-enhanced-gaming-experience-on-all-windows-platforms/"><u>Install the Newest GeForce RTX 2070 Drivers for Enhanced Gaming Experience on All Windows Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/master-video-conversion-for-portable-gaming-systems-pspps3-compatible-solutions/"><u>Master Video Conversion for Portable Gaming Systems - PSP/PS3 Compatible Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-consistent-sound-quality-tips-for-balancing-mp4-audio/"><u>Mastering Consistent Sound Quality: Tips for Balancing MP4 Audio</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastering-the-art-of-naming-your-podcast-right-and-50plus-creative-title-suggestions-for-2024/"><u>Mastering the Art of Naming Your Podcast Right & 50+ Creative Title Suggestions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/most-effective-windows-11-dvd-regions-bypass-tool-reviews-and-comparisons/"><u>Most Effective Windows 11 DVD Regions Bypass Tool: Reviews & Comparisons</u></a></li>
<li><a href="https://win11.techidaily.com/mp3-to-m4a/"><u>MP3 to M4A変換フリーツール比較ガイド - 使いやすくて正確なソフトウェア集めました!</u></a></li>
<li><a href="https://windows11.techidaily.com/safeguard-files-with-windows-controlled-access-feature/"><u>Safeguard Files with Window's Controlled Access Feature</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    