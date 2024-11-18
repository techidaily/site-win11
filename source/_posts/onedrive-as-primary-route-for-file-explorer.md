---
title: OneDrive as Primary Route for File Explorer
date: 2024-11-13T20:35:18.550Z
updated: 2024-11-17T23:36:21.740Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes OneDrive as Primary Route for File Explorer
excerpt: This Article Describes OneDrive as Primary Route for File Explorer
keywords: OneDrive_FileExplorer,PrimaryOneDriveRoute,DrivedirectFiles,FileExplorerPrimary,OneDriveAccess,DirectSyncStorage,OneDriveLeadPath
thumbnail: https://thmb.techidaily.com/fce57db6d0ca9f41bfe3bd2fdd239ef79b5c70d705be5a8d6f566c06a2b27fc0.jpg
---

## OneDrive as Primary Route for File Explorer

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
<a href="https://aligracehair.sjv.io/c/5597632/1880927/19272" target="_top" id="1880927">
  <img src="//a.impactradius-go.com/display-ad/19272-1880927" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880927/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://laganoo.pxf.io/c/5597632/1528693/16446" target="_top" id="1528693">
  <img src="//a.impactradius-go.com/display-ad/16446-1528693" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528693/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043662/7443" target="_top" id="2043662">
  <img src="//a.impactradius-go.com/display-ad/7443-2043662" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043662/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

<!-- affiliate ads begin -->
<a href="https://oneplusfr.sjv.io/c/5597632/1622438/14044" target="_top" id="1622438">
  <img src="//a.impactradius-go.com/display-ad/14044-1622438" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://oneplusfr.sjv.io/i/5597632/1622438/14044" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Set File Explorer to Open OneDrive Instead of Quick Access

 There you have it; three different methods to make OneDrive your default File Explorer view. If you like, you can also change other folder views, such as Downloads or This PC, using the same techniques we discussed above. I hope this guide helped you get things done quickly and easily.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/our-path-to-youtube-earnings-setting-up-and-selling-content/"><u>[New] Your Path to YouTube Earnings Setting Up and Selling Content</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-filmoquery-your-guide-to-video-editing-insights/"><u>[Updated] FilmoQuery Your Guide to Video Editing Insights</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-lifetime-favorites-reddits-highly-endorsed-top-10/"><u>[Updated] In 2024, Lifetime Favorites Reddit's Highly-Endorsed Top 10</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/a-complete-look-at-hand-recognition-systems/"><u>A Complete Look at Hand Recognition Systems</u></a></li>
<li><a href="https://fox-sys.techidaily.com/get-organized-build-the-perfect-toc-for-your-digital-book-using-flipbuilder/"><u>Get Organized: Build the Perfect TOC for Your Digital Book Using FlipBuilder</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-recover-from-windows-11s-zero-a00f-camera-blunder/"><u>How to Recover From Windows 11'S Zero-A00F Camera Blunder</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-call-history-on-xperia-5-v-by-fonelab-android-recover-call-logs/"><u>How to restore wiped call history on Xperia 5 V?</u></a></li>
<li><a href="https://win11.techidaily.com/ideal-replacements-for-windows-snipping-functionality-in-other-oses/"><u>Ideal Replacements for Windows' Snipping Functionality in Other OSes</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-share-location-in-messenger-on-oppo-find-x6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share Location in Messenger On Oppo Find X6 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/locating-group-policies-a-users-guide-for-win-users/"><u>Locating Group Policies: A User's Guide for Win Users</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-noir-world-of-microsoft-paint/"><u>Navigating the Noir World of Microsoft Paint</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-windows-11-priority-over-entertainment/"><u>Optimizing Windows 11: Priority over Entertainment</u></a></li>
<li><a href="https://win11.techidaily.com/solving-the-jittery-cursor-problem-on-windows-xp/"><u>Solving the Jittery Cursor Problem on Windows XP</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-text-interaction-emoji-15-on-windows-11-explained/"><u>Tailoring Text Interaction: Emoji 15 on Windows 11 Explained</u></a></li>
<li><a href="https://fox-links.techidaily.com/the-evolved-examination-of-sony-bdp-s3700/"><u>The Evolved Examination of Sony BDP-S3700</u></a></li>
<li><a href="https://win11.techidaily.com/top-tier-video-coders-for-windows-a-comparative-review/"><u>Top-Tier Video Coders for Windows: A Comparative Review</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/ws-2902a-ambient-weather-station-overview-and-analysis-exceptional-value-with-rich-functionality/"><u>WS-2902A Ambient Weather Station Overview & Analysis - Exceptional Value with Rich Functionality</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    