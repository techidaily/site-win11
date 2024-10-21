---
title: Shifting Focus to File Explorer with OneDrive Connection
date: 2024-10-15T23:25:26.316Z
updated: 2024-10-21T01:22:14.626Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Shifting Focus to File Explorer with OneDrive Connection
excerpt: This Article Describes Shifting Focus to File Explorer with OneDrive Connection
keywords: File Explorer Links,OneDrive Access Direct,Data Sync Explorer,Cloud Storage Explorer,Explorer & Drive Synch,Direct Explorer Share,OneDrive Explorer Hook,FileExplorerSync,OneDriveDirectLink,SyncOneDriveFiles,CloudDataExplorer,ExplorerCloudSync,DirectShareExplorer,OneDriveHookup
thumbnail: https://thmb.techidaily.com/8a3dcbc1949f8fc1125959e7981cf826a5c632863c20a3e0bedcec7b541e0029.jpg
---

## Shifting Focus to File Explorer with OneDrive Connection

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043617/7443" target="_top" id="2043617">
  <img src="//a.impactradius-go.com/display-ad/7443-2043617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043617/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135365/19272" target="_top" id="2135365">
  <img src="//a.impactradius-go.com/display-ad/19272-2135365" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135365/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1918719/19272" target="_top" id="1918719">
  <img src="//a.impactradius-go.com/display-ad/19272-1918719" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918719/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532">
  <img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-captureking-chronicles-the-best-recorders-unveiled/"><u>[New] 2024 Approved CaptureKing Chronicles The Best Recorders Unveiled</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-premium-desktop-and-mobile-video-call-platforms-zoom-replacements/"><u>[Updated] 2024 Approved Premium Desktop & Mobile Video Call Platforms (Zoom Replacements)</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-evaluating-on-demand-media-podcast-or-youtube/"><u>[Updated] Evaluating On-Demand Media Podcast or YouTube?</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-top-picks-excellent-4k-displays-for-playing-games/"><u>[Updated] In 2024, Top Picks Excellent 4K Displays for Playing Games</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/2024-approved-twitters-video-standards-focus-on-aspect-ratios/"><u>2024 Approved Twitter's Video Standards Focus on Aspect Ratios</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-down-high-resource-usage-by-ntoskrnlexe/"><u>Cutting Down High Resource Usage by Ntoskrnl.exe</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-windows-error-x70-your-path-to-data-recovery/"><u>Demystifying Windows Error X70: Your Path to Data Recovery</u></a></li>
<li><a href="https://win11.techidaily.com/digital-guardrails-7-practices-to-halt-uac-breaches/"><u>Digital Guardrails: 7 Practices to Halt UAC Breaches</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-file-management-for-win-users/"><u>Enhancing File Management for Win Users</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/f1-2020-on-pc-overcoming-persistent-crashing-problems-for-a-smoother-gaming-experience/"><u>F1 2020 on PC - Overcoming Persistent Crashing Problems for a Smoother Gaming Experience</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-messages-from-x9b-by-fonelab-android-recover-messages/"><u>How to retrieve erased messages from X9b</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-infinix-hot-30i-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Infinix Hot 30i to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-samsung-galaxy-a25-5g-drfone-by-drfone-virtual/"><u>In 2024, 10 Fake GPS Location Apps on Android Of your Samsung Galaxy A25 5G | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/latest-guide-how-to-bypass-poco-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Poco FRP Without Computer</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-functionality-with-win11s-widget-bar/"><u>Maximizing Functionality with Win11's Widget Bar</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-a-disrupted-windows-update-on-discord/"><u>Navigating a Disrupted Windows Update on Discord</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-thx-spatial-audio-problems/"><u>Overcoming Windows THX Spatial Audio Problems</u></a></li>
<li><a href="https://win11.techidaily.com/self-sufficient-storage-duplication-techniques/"><u>Self-Sufficient Storage Duplication Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/tabbing-techniques-for-a-streamlined-user-experience-windows-11/"><u>Tabbing Techniques for a Streamlined User Experience (Windows 11)</u></a></li>
</ul></div>

