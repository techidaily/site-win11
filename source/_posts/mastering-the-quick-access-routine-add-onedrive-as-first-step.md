---
title: "Mastering the Quick Access Routine: Add OneDrive as First Step"
date: 2024-11-14T16:10:51.861Z
updated: 2024-11-17T17:02:38.363Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering the Quick Access Routine: Add OneDrive as First Step"
excerpt: "This Article Describes Mastering the Quick Access Routine: Add OneDrive as First Step"
keywords: Quick File Sync,OneDrive Priority,Efficient Workflow,Streamline Productivity,Fast Office Tools,Microsoft OneStep,Secure Cloud Access
thumbnail: https://thmb.techidaily.com/00d8a989d7a324ab139f90cea816e72b6f2451ab8e331cf2285ff4f2ecbceec0.jpg
---

## Mastering the Quick Access Routine: Add OneDrive as First Step

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
<a href="https://appsumo.8odi.net/c/5597632/2144278/7443" target="_top" id="2144278">
  <img src="//a.impactradius-go.com/display-ad/7443-2144278" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144278/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1938721/19272" target="_top" id="1938721">
  <img src="//a.impactradius-go.com/display-ad/19272-1938721" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938721/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087408/7443" target="_top" id="2087408">
  <img src="//a.impactradius-go.com/display-ad/7443-2087408" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087408/7443" style="position:absolute;visibility:hidden;" border="0" />
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

8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123728/7443" target="_top" id="2123728">
  <img src="//a.impactradius-go.com/display-ad/7443-2123728" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123728/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Set File Explorer to Open OneDrive Instead of Quick Access

 There you have it; three different methods to make OneDrive your default File Explorer view. If you like, you can also change other folder views, such as Downloads or This PC, using the same techniques we discussed above. I hope this guide helped you get things done quickly and easily.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-dive-into-the-deep-end-of-facebook-meme-culture/"><u>[New] In 2024, Dive Into The Deep End of Facebook Meme Culture</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-ultimate-tutorial-customizing-the-final-frame-of-a-vimeo-video-for-2024/"><u>[New] Ultimate Tutorial Customizing the Final Frame of a Vimeo Video for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/boost-performance-on-pc-install-canon-printer-software-for-windows/"><u>Boost Performance on PC: Install Canon Printer Software for Windows</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/comprehensive-analysis-of-the-pioneer-bdr-xs06-external-blu-ray-burner-a-focus-on-mobility-and-efficiency/"><u>Comprehensive Analysis of the Pioneer BDR-XS06 External Blu-Ray Burner: A Focus on Mobility & Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/dxgidll-gone-regain-it-on-windows-11-heres-why/"><u>Dxgi.dll Gone? Regain It on Windows 11, Here's Why</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-workspace-a-guide-to-widget-additions-in-windows-11/"><u>Elevate Your Workspace: A Guide to Widget Additions in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-error-code-80080300-with-microsoft-teams-on-win11/"><u>Fixing Error Code 80080300 with Microsoft Teams on Win11</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Xiaomi Redmi Note 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-do-i-stop-someone-from-tracking-my-samsung-galaxy-a25-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Do I Stop Someone From Tracking My Samsung Galaxy A25 5G? | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-streamer-profitability-analysis-and-verification/"><u>In 2024, Streamer Profitability Analysis and Verification</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-repair-fixing-windows-office-system-hiccups/"><u>Mastering Repair: Fixing Windows Office System Hiccups</u></a></li>
<li><a href="https://win11.techidaily.com/method-for-solving-xc0f1103f-issue-on-windows-geforce/"><u>Method for Solving XC0F1103F Issue on Windows, GeForce</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/gen-gamers-wealth-wave-predictions-for-2024/"><u>Next-Gen Gamers' Wealth Wave Predictions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-wows-critical-failure-code-132/"><u>Quick Fixes for WoW’s Critical Failure Code #132</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-non-loading-steamuidll-on-windows/"><u>Remedy for Non-Loading SteamUI.DLL on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/scripting-a-robust-python-server-for-effective-filesharing-in-windows/"><u>Scripting a Robust Python Server for Effective Filesharing in Windows</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/t-to-clear-the-ultimate-guide-to-professional-audio-recording/"><u>Silent to Clear The Ultimate Guide to Professional Audio Recording</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-minimizing-webview2-footprint-on-windows/"><u>Steps for Minimizing WebView2 Footprint on Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-tracking-apps-to-track-motorola-g24-power-without-them-knowing-drfone-by-drfone-virtual-android/"><u>Top 5 Tracking Apps to Track Motorola G24 Power without Them Knowing | Dr.fone</u></a></li>
</ul></div>

