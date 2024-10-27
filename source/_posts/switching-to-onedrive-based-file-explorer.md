---
title: Switching to OneDrive-Based File Explorer
date: 2024-10-26T05:17:47.764Z
updated: 2024-10-27T09:36:47.376Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Switching to OneDrive-Based File Explorer
excerpt: This Article Describes Switching to OneDrive-Based File Explorer
keywords: OneDrive Explorer,Cloud File Viewer,Digital Files Hub,Online File Explorer,Cloud Sync Manager,OneDrive Integration,File Explorer Cloud
thumbnail: https://thmb.techidaily.com/a6fbcf7b87c69b74abd8f2d894637274c942b2c57ba584189354e0290ce20d66.jpg
---

## Switching to OneDrive-Based File Explorer

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082542/7443" target="_top" id="2082542">
  <img src="//a.impactradius-go.com/display-ad/7443-2082542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082542/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997643/19272" target="_top" id="1997643">
  <img src="//a.impactradius-go.com/display-ad/19272-1997643" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997643/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896541/19272" target="_top" id="1896541">
  <img src="//a.impactradius-go.com/display-ad/19272-1896541" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896541/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130530/26400" target="_top" id="2130530">
  <img src="//a.impactradius-go.com/display-ad/26400-2130530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130530/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

## Set File Explorer to Open OneDrive Instead of Quick Access

 There you have it; three different methods to make OneDrive your default File Explorer view. If you like, you can also change other folder views, such as Downloads or This PC, using the same techniques we discussed above. I hope this guide helped you get things done quickly and easily.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/024-approved-into-the-unknown-how-to-start-and-flourish-as-a-travel-videographer/"><u>[New] 2024 Approved Into the Unknown How To Start & Flourish As a Travel Videographer</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-elevate-your-mobile-shoot-ranking-the-best-9-camgear-innovations/"><u>[New] In 2024, Elevate Your Mobile Shoot - Ranking the Best 9 CamGear Innovations</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-hdr-horizon-unveiled-an-elite-list-of-online-sky-sites/"><u>[Updated] HDR Horizon Unveiled An Elite List of Online Sky Sites</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-mirrorless-impact-on-professional-video-recording/"><u>[Updated] Mirrorless Impact on Professional Video Recording</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/ius7iuobmeobkoobiuaxguocgtog6auy5zob6loq44gq5pif5pio5yaz55yf5lplusu57mv44k144o844ot44k5ig/"><u>今すぐお求め: 高品質な星明写真修繕サービス</u></a></li>
<li><a href="https://win11.techidaily.com/a-simple-guide-converting-stunning-hdr-videos-into-compatible-sdr-format/"><u>A Simple Guide: Converting Stunning HDR Videos Into Compatible SDR Format</u></a></li>
<li><a href="https://win11.techidaily.com/can-i-trust-online-video-conversion-services-understanding-their-security-risks-and-benefits/"><u>Can I Trust Online Video Conversion Services? Understanding Their Security Risks and Benefits</u></a></li>
<li><a href="https://win11.techidaily.com/clipchampgif/"><u>Clipchampによる簡単なGIF制作手順とヒント:動画から始めましょう!</u></a></li>
<li><a href="https://win11.techidaily.com/comparing-mp4-and-mpg-formats-unveiling-key-distinctions-and-selecting-optimal-options/"><u>Comparing MP4 & MPG Formats: Unveiling Key Distinctions and Selecting Optimal Options</u></a></li>
<li><a href="https://win11.techidaily.com/complete-system-audio-recording-on-windowsmac-os-tips-and-tricks/"><u>Complete System Audio Recording on Windows/Mac OS – Tips & Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/downloadable-apps-and-tricks-to-compress-videos-on-your-iphone-at-no-cost/"><u>Downloadable Apps & Tricks to Compress Videos on Your iPhone at No Cost</u></a></li>
<li><a href="https://win11.techidaily.com/easy-methods-for-converting-and-saving-your-dvd-movies-onto-an-external-hard-drive/"><u>Easy Methods for Converting and Saving Your DVD Movies Onto an External Hard Drive</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/from-concept-to-characters-integrating-chatgpt-into-game-development/"><u>From Concept to Characters: Integrating ChatGPT Into Game Development</u></a></li>
<li><a href="https://discover-forum.techidaily.com/methods-to-restore-files-dealing-with-data-loss-on-damaged-drives-includes-4-techniques/"><u>Methods to Restore Files: Dealing with Data Loss on Damaged Drives (Includes 4 Techniques)</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolving-game-breaking-crashes-for-star-wars-old-republic-expert-fixes-unlocked/"><u>Resolving Game-Breaking Crashes for Star Wars Old Republic - Expert Fixes Unlocked</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-car-locator-apps-for-vivo-x90s-drfone-by-drfone-virtual-android/"><u>Top 5 Car Locator Apps for Vivo X90S | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/cpicpimp4/"><u>コンポジットピクチャーフィールド(CPI)とは？CPIをMP4にどう変換するか学ぶ！</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    