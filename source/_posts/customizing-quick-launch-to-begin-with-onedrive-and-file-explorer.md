---
title: Customizing Quick Launch to Begin with OneDrive and File Explorer
date: 2024-09-15T08:43:05.767Z
updated: 2024-09-17T01:51:00.244Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customizing Quick Launch to Begin with OneDrive and File Explorer
excerpt: This Article Describes Customizing Quick Launch to Begin with OneDrive and File Explorer
keywords: Custom Quick Launch,OneDrive Setup,File Explorer Integration,Personalized Start Menu,OneDrive Prompt,File Explorer Access,Quick Launch Tailoring
thumbnail: https://thmb.techidaily.com/f33adb8a41f790bc858c47b5fb66f5998fe40f1007e9c52f968a63abc439ec92.jpg
---

## Customizing Quick Launch to Begin with OneDrive and File Explorer

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
<a href="https://aligracehair.sjv.io/c/5597632/2115937/19272" target="_top" id="2115937">
  <img src="//a.impactradius-go.com/display-ad/19272-2115937" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115937/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Set File Explorer to Open OneDrive Instead of Quick Access

 There you have it; three different methods to make OneDrive your default File Explorer view. If you like, you can also change other folder views, such as Downloads or This PC, using the same techniques we discussed above. I hope this guide helped you get things done quickly and easily.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/1-successfully-streaming-mkv-files-on-xbox-series-xs-a-comprehensive-guide/"><u>1. Successfully Streaming MKV Files on Xbox Series X|S: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/1726026610963-bilibili/"><u>Bilibiliビューワで再生問題に見舞われたら、ダウンロード・セーブ不可を解決するポイント</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1723005102377-fallout-svensept-pc-server-connection-fixes-get-back-online-today/"><u>Fallout ˈsɛvən'sept PC Server Connection Fixes – Get Back Online Today!</u></a></li>
<li><a href="https://printer-issues.techidaily.com/hassle-free-connections-3-innovative-ways-to-link-laptop-plus-hp/"><u>Hassle-Free Connections: 3 Innovative Ways to Link Laptop + HP</u></a></li>
<li><a href="https://win-able.techidaily.com/improving-gaming-fluidity-expert-strategies-for-addressing-and-resolving-frame-rate-dips/"><u>Improving Gaming Fluidity: Expert Strategies for Addressing and Resolving Frame Rate Dips</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-3-ways-to-change-location-on-facebook-marketplace-for-motorola-edge-40-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Change Location on Facebook Marketplace for Motorola Edge 40 Pro | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-a-complete-guide-to-oem-unlocking-on-xiaomi-redmi-note-12-4g-by-drfone-android/"><u>In 2024, A Complete Guide To OEM Unlocking on Xiaomi Redmi Note 12 4G</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-insight-dji-paper-bird-goggles-functionality/"><u>In 2024, Insight DJI Paper Bird Goggles Functionality</u></a></li>
<li><a href="https://hardware-help.techidaily.com/upgraded-brother-mfc-7360n-printer-support-effortless-driver-download-and-update-for-all-windows-versions/"><u>Upgraded Brother MFC-7360N Printer Support: Effortless Driver Download and Update for All Windows Versions</u></a></li>
<li><a href="https://win11.techidaily.com/wma-to-mp3-or-other-formats-the-easy-free-way-of-converting-your-music-without-spending-a-dime/"><u>WMA to MP3 or Other Formats - The Easy, FREE Way of Converting Your Music Without Spending a Dime</u></a></li>
<li><a href="https://win11.techidaily.com/youtube-live-screen-recording-techniques-ideal-privacy-tips/"><u>YouTube Live Screen Recording Techniques - Ideal Privacy Tips</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    