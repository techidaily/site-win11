---
title: Adjusting Quick Access for File Explorer Through OneDrive
date: 2024-08-15T23:17:09.278Z
updated: 2024-08-16T23:17:09.278Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Quick Access for File Explorer Through OneDrive
excerpt: This Article Describes Adjusting Quick Access for File Explorer Through OneDrive
keywords: Quick File Explorer Adjust,OneDrive Access Improve,Enhance Explorer Settings,Streamline OneDrive Views,Optimize Office Explorer,Direct OneDrive Access,Refine File Explorer Options
thumbnail: https://thmb.techidaily.com/805432a26a63c24a3ad7f94c306f1a1291a2364beb1c1710fc99d1f9d71ae26e.jpg
---

## Adjusting Quick Access for File Explorer Through OneDrive

 When you launch Windows File Explorer, it automatically takes you to the "Quick Access" view. This page displays shortcuts to recently accessed folders and files and lists your favorite folders. It might be convenient for some users but not for others who prefer easy access to their cloud storage.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

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
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Double-click on this newly created value and set its value to **4**.
7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
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
<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
7. Double-click the REG file you just created. If you're prompted for permission to change your computer, click **Yes**.
8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-in-the-spotlight-top-viewers-choice/"><u>[New] 2024 Approved  In the Spotlight  Top Viewers' Choice</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-crafting-splitscreen-youtube-videos-a-guide-to-creativity-for-2024/"><u>[New] Crafting Splitscreen YouTube Videos  A Guide to Creativity for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-elevating-content-strategy-with-effective-youtube-partnerships-for-2024/"><u>[New] Elevating Content Strategy with Effective YouTube Partnerships for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-new-era-facebooks-quintessential-features-showcased/"><u>[New] New Era  Facebook's Quintessential Features Showcased</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-record-internal-audio-in-android-without-root-4-ways/"><u>[New] Record Internal Audio in Android without Root [4 Ways]</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-superior-skills-for-video-preservation-devices/"><u>2024 Approved  Superior Skills for Video Preservation Devices</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-disable-microsoft-edge-tab-preloading-in-windows-11/"><u>4 Ways to Disable Microsoft Edge Tab Preloading in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-peak-productivity-configure-multiple-monitors-in-win11/"><u>Achieve Peak Productivity: Configure Multiple Monitors in Win11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpt-and-you-a-handy-approach-to-troubleshooting-pc-problems-efficiently/"><u>ChatGPT and You: A Handy Approach to Troubleshooting PC Problems Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-graphics-from-windows-search-interface/"><u>Clearing Graphics From Windows Search Interface</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-crashes-sonic-frontiers-full-screen-fixes/"><u>Conquering Crashes: Sonic Frontiers Full-Screen Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/directly-to-dialer-windows-11-tutorial/"><u>Directly to Dialer: Windows 11 Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-finest-zero-cost-windows-media-devices/"><u>Discover the Finest Zero-Cost Windows Media Devices</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-windows-1110s-required-privilege-error-code-0x80070522/"><u>Eradicating Windows 11/10'S “Required Privilege” Error: Code 0X80070522</u></a></li>
<li><a href="https://win11.techidaily.com/essential-insights-into-os-upgrade-schedules-and-methods/"><u>Essential Insights Into OS Upgrade Schedules & Methods</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-mitigate-local-security-offline-issue/"><u>Essential Steps to Mitigate Local Security Offline Issue</u></a></li>
<li><a href="https://win11.techidaily.com/finding-essential-data-win-pc-ip-and-mac-via-powershell/"><u>Finding Essential Data: Win PC IP & MAC via PowerShell</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-top-10-game-recorder-software-list/"><u>In 2024, Top 10 Game Recorder Software List</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-realme-c67-5g-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On Realme C67 5G</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-top-6-ways-to-transfer-text-messages-from-vivo-y200e-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Top 6 Ways to Transfer Text Messages from Vivo Y200e 5G to Other Android Devices | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-screen-capture-tool-in-windows-11-swiftly/"><u>Navigate to Screen Capture Tool in Windows 11 Swiftly</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-exe-file-opener-failures-in-windows/"><u>Overcoming .exe File Opener Failures in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-rectifying-epic-games-logins/"><u>Quick Guide to Rectifying Epic Games Logins</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-for-handling-the-lack-of-msvcr120dll-in-windows/"><u>Quick Tips for Handling the Lack of MSVCR120.DLL in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-paste-functionality-across-chromeedgefirefox-windows/"><u>Reviving Paste Functionality Across Chrome/Edge/Firefox Windows</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-windows-update-experience-with-easy-fixes-here/"><u>Seamless Windows Update Experience With Easy Fixes Here</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-offline-mode-in-microsoft-onedrive/"><u>Setting Up Offline Mode in Microsoft OneDrive</u></a></li>
<li><a href="https://win11.techidaily.com/shadowing-shutdown-hide-win11s-power-icon-strategically/"><u>Shadowing Shutdown: Hide Win11's Power Icon Strategically</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-windows-update-error-0x8024800c/"><u>Solutions for Windows Update Error 0X8024800C</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-turn-on-end-task-feature-in-windows-11-ui/"><u>Steps to Turn On End Task Feature in Windows 11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/triggering-dormant-pane-windows-6-tips-for-win11-users/"><u>Triggering Dormant Pane Windows: 6 Tips for Win11 Users</u></a></li>
<li><a href="https://games-able.techidaily.com/unbeatable-5-reasons-choosing-the-right-retro-handheld/"><u>Unbeatable 5 Reasons: Choosing the Right Retro Handheld</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-cab-files-explanations-and-steps-for-installation/"><u>Understanding Windows Cab Files: Explanations & Steps for Installation</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-potential-your-custom-hotkey-journey/"><u>Unlocking Windows Potential: Your Custom Hotkey Journey</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-missing-tab-button-on-your-machine/"><u>Unveiling the Missing Tab Button on Your Machine</u></a></li>
<li><a href="https://win11.techidaily.com/upgrade-your-display-selecting-premium-timers-and-savers/"><u>Upgrade Your Display: Selecting Premium Timers & Savers</u></a></li>
</ul></div>
