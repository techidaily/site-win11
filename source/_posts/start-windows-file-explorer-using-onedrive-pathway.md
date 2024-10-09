---
title: Start Windows File Explorer Using OneDrive Pathway
date: 2024-10-04T22:40:17.688Z
updated: 2024-10-08T19:43:58.481Z
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

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2141683/17092" target="_top" id="2141683">
  <img src="//a.impactradius-go.com/display-ad/17092-2141683" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettide.pxf.io/i/5597632/2141683/17092" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130528/26400" target="_top" id="2130528">
  <img src="//a.impactradius-go.com/display-ad/26400-2130528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130528/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137222/26400" target="_top" id="2137222">
  <img src="//a.impactradius-go.com/display-ad/26400-2137222" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137222/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://imp.i357552.net/c/5597632/999558/11832" target="_top" id="999558">
  <img src="//a.impactradius-go.com/display-ad/11832-999558" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/999558/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

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
<li><a href="https://extra-skills.techidaily.com/new-step-by-step-guide-to-linking-obs-and-streamlabs-mac/"><u>[New] Step-by-Step Guide to Linking OBS & Streamlabs (Mac)</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-instagram-flips-mastering-the-video-360-turn/"><u>[Updated] 2024 Approved Instagram Flips Mastering the Video 360-Turn</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-microsoft-store-error-x00000000-in-win-11/"><u>Addressing the Microsoft Store Error X00000000 in Win 11</u></a></li>
<li><a href="https://discover-excellent.techidaily.com/best-legal-sites-for-free-mp3-downloads-top-10-picks/"><u>Best Legal Sites for Free MP3 Downloads: Top 10 Picks</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-security-avoid-chatbots-for-win-11-keys/"><u>Bypassing Security: Avoid Chatbots for Win 11 Keys</u></a></li>
<li><a href="https://win11.techidaily.com/1719358014112-chrome-woes-on-windows-11-a-fixers-guide-to-reopening-it/"><u>Chrome Woes on Windows 11: A Fixer’s Guide to Reopening It.</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-update-failure-0x8024800c/"><u>Correcting Windows Update Failure: 0X8024800C</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-logitech-g600-controller-software-for-pc-users/"><u>Download Logitech G600 Controller Software for PC Users</u></a></li>
<li><a href="https://program-issues.techidaily.com/elevate-your-experience-expert-tips-for-eliminating-stutter-and-improving-frame-rates-in-gaming/"><u>Elevate Your Experience: Expert Tips for Eliminating Stutter and Improving Frame Rates in Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-to-re-enable-your-windows-11-device-after-error-22/"><u>Expert Tips to Re-Enable Your Windows 11 Device After Error 22</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-does-more-comprehensive-ai-governance-impact-future-innovations-lessons-from-openais-chief/"><u>How Does More Comprehensive AI Governance Impact Future Innovations? Lessons From OpenAI's Chief</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reverse-failed-zip-file-extractions-on-windows-11/"><u>How To Reverse Failed Zip File Extractions on Windows 11</u></a></li>
<li><a href="https://program-issues.techidaily.com/installing-hyper-v-virtualization-on-windows-11-an-easy-tutorial/"><u>Installing Hyper-V Virtualization on Windows 11: An Easy Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-email-apps-0x800713f-issue-on-win11/"><u>Navigating Through Email App's 0X800713F Issue on Win11</u></a></li>
<li><a href="https://win-blog.techidaily.com/solving-the-rocket-league-hang-up-issue-effective-strategies-for-unfreezing-gameplay/"><u>Solving the Rocket League Hang-Up Issue: Effective Strategies for Unfreezing Gameplay</u></a></li>
</ul></div>

