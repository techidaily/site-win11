---
title: "Mastering the Quick Access Routine: Add OneDrive as First Step"
date: 2024-11-06T23:02:36.773Z
updated: 2024-11-07T22:56:57.247Z
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
<a href="https://aligracehair.sjv.io/c/5597632/1997662/19272" target="_top" id="1997662">
  <img src="//a.impactradius-go.com/display-ad/19272-1997662" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997662/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918703/19272" target="_top" id="1918703">
  <img src="//a.impactradius-go.com/display-ad/19272-1918703" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918703/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411">
  <img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118306/7443" target="_top" id="2118306">
  <img src="//a.impactradius-go.com/display-ad/7443-2118306" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118306/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Set File Explorer to Open OneDrive Instead of Quick Access

 There you have it; three different methods to make OneDrive your default File Explorer view. If you like, you can also change other folder views, such as Downloads or This PC, using the same techniques we discussed above. I hope this guide helped you get things done quickly and easily.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/ptimize-your-viewing-experience-on-youtube-with-speed-settings/"><u>[New] Optimize Your Viewing Experience on YouTube with Speed Settings</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-action-and-adventure-with-ions-pro-3-camera-insight/"><u>[Updated] 2024 Approved Action and Adventure with ION's Pro 3 Camera Insight</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-dive-into-makers-earnings-exploring-youtube-shorts-revenue-structure-for-2024/"><u>[Updated] Dive Into Maker's Earnings Exploring YouTube Shorts Revenue Structure for 2024</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-oppo-find-n3-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Oppo Find N3 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/effortless-mp4-video-tagging-top-editor-recommendations/"><u>Effortless MP4 Video Tagging Top Editor Recommendations</u></a></li>
<li><a href="https://win-solutions.techidaily.com/eliminate-starfield-applications-spike-in-cpu-usage-with-our-latest-2024-fixes/"><u>Eliminate Starfield Application's Spike in CPU Usage with Our Latest 2024 Fixes</u></a></li>
<li><a href="https://extra-tips.techidaily.com/hot-topic-in-photos-memes-and-their-origin-tales/"><u>Hot Topic in Photos Memes & Their Origin Tales</u></a></li>
<li><a href="https://win11.techidaily.com/is-your-pc-compatible-with-windows-11-see-here/"><u>Is Your PC Compatible with Windows 11? See Here!</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-7-fixes-for-non-scrolling-mouse-wheels/"><u>Mastering 7 Fixes for Non-Scrolling Mouse Wheels</u></a></li>
<li><a href="https://fox-blue.techidaily.com/mastering-social-connectivity-from-instagram-to-tiktoks-playground/"><u>Mastering Social Connectivity From Instagram to TikTok's Playground</u></a></li>
<li><a href="https://win11.techidaily.com/say-goodbye-to-wasted-space-clear-windows-temp-files/"><u>Say Goodbye to Wasted Space: Clear Windows Temp Files</u></a></li>
<li><a href="https://win11.techidaily.com/secure-win-vbox-install-deps-must-come-first/"><u>Secure Win VBox Install: Deps Must Come FIRST</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-adjust-standard-user-permissions-in-windows/"><u>Steps to Adjust Standard User Permissions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tweaking-the-default-commands-interpreter-in-windows/"><u>Tweaking the Default Commands Interpreter in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-correcting-windows-runtime-error-0x800700c6/"><u>Understanding and Correcting Windows Runtime Error 0X800700C6</u></a></li>
<li><a href="https://win11.techidaily.com/windows-time-turmoil-steady-the-systems-hour/"><u>Windows Time Turmoil: Steady the System's Hour</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    