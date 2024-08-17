---
title: Optimize Context Selection by Omitting Show More
date: 2024-08-16T00:28:30.413Z
updated: 2024-08-17T00:28:30.413Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Optimize Context Selection by Omitting Show More
excerpt: This Article Describes Optimize Context Selection by Omitting Show More
keywords: Context Optimization,Show Less Strategy,Data Filtering,Reduce Overload,Focus Selection,Keyword Curation,Content Streamlining
thumbnail: https://thmb.techidaily.com/d9580a0fe0d295d2fe4ac5bc754f7348af6d4884ba16ea4dee8b131acea9d9aa.jpg
---

## Optimize Context Selection by Omitting Show More

 Windows 11 comes with a fresh new look and has mainly got a positive response for its new interface. However, there are a couple of features that are not being welcomed by the users. For instance, the addition of the "show more options" entry to the right-click context menu.

 Although it was introduced to simplify things, many users still prefer the old context menu from Windows 10\. Fortunately, you can remove Show more options from the context menu on Windows 11 by following the below methods.

## 1\. How to Remove "Show More Options" From the Context Menu With Folder Options

 The [Windows Folder Options](https://www.makeuseof.com/windows-folder-options-guide/) in File Explorer is the go-to place to view and manage File Explorer settings. You can use it to [enable compact view in File Explorer on Windows 11](https://www.makeuseof.com/how-to-enable-compact-view-windows-11-file-explorer/) , manage file thumbnails, remove the "show more options" entry, and much more.

 Here's how to use the folder option to remove the "show more options" entry from the context menu:

1. Press the**Win + E** hotkey to open the**File Explorer.**
2. Click the three horizontal dots at the top bar and choose**Options.**
3. In the**Folder Options,** switch to the**View** tab.
4. Check the**Launch folder** **windows in a separate process** box.  
![Launch folder windows in a separate process box in the Folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/launch-folder-windows-in-a-separate-process-box.jpg)
5. Click**Apply** \>**OK** to save the changes.

Next, restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Remove Show More Options From the Context Menu Using the Command Prompt

 If you're a power user, you can use Command Prompt to remove the "show more options" entry from the context menu. Here's how:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane.
3. Click**Yes** to the UAC that crops up.
4. In the elevated Command Prompt window, type the following command and press**Enter** :  
`reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve`

![Command to Remove Context menu in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-to-remove-context-menu.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->

 After executing the command, you'll see the "The operation completed successfully" message to confirm that it went through.

 Now, you will have to restart Windows Explorer to see the changes. To do that, open the**Task Manager** (see how to [launch the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) ), right-click on**Windows Explorer,** and choose**Restart.**

 Check if you can see the changes. If not, then you will have to restart your computer for the changes to take effect.

 In the future, if you want to add the "show more options" entry to the context menu, then open Command Prompt with admin rights and run the following command:

`reg delete "HKEY_CURRENT_USER\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f​`

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Remove Show More Options From the Context Menu Using the Registry Editor

 Another quick way to remove the "show more options" entry is through the Registry Editor. Here's what you need to do:

 Before making any changes to the registry, ensure you've [created a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) or [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . This will ensure your system settings and files are secure, and you can quickly access them if something goes wrong.

1. Open the Start Menu, type**Registry Editor** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID`
3. Right-click on the empty space on the right pane, click**New,** and then select**DWORD** **(32-bit) Value** from the context menu.
4. Name the value as**"UndockingDisabled"** and press**Enter** .  
![UndockingDisabled entry in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/undockingdisabled-entry.jpg)
5. Double-click on the UndockingDisabled key, type**1** in the**Value data,** and click**OK** to save the changes.  
![Editing UndockingDisabled in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-undockingdisabled.jpg)

## 4\. Remove the "Show More Options" Entry From the Context Menu Using Winaero Tweaker

 There are plenty of third-party tools using which you can customize the look of your Windows 11 computer. For this guide, we will use Winaero Tweaker.

 Here's how to download Winaero Tweaker and use it to remove the "show more options" entry from the context menu:

1. Download the [Winaero Tweaker zip file](https://winaero.com/downloads/winaerotweaker.zip) on your computer.
2. Unzip the file, open the executable, and then follow the on-screen instructions to install it on your computer.
3. Launch Winaero Tweaker and choose the**Classic Full Context Menus** option from the left sidebar.  
![Classic Full Context Menus option of Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/classic-full-context-menus-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
4. Check the**Enable classic full context menus** box.  
![Enable classic full context menus option in Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-classic-full-context-menus.jpg)
<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Click the**Restart Explorer** button that appears.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Enjoy an Old School Context Menu on Windows 11

 The desktop context menu lets you quickly access areas like the personalization menu, display settings, and much more. In Windows 11, you get the new "Show more options" entry in the context menu. But if you prefer the old design, you can quickly disable the "Show more options" entry from the context using either of the above methods.


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
<li><a href="https://extra-hints.techidaily.com/new-charting-the-course-a-graphic-designers-blueprint-to-progress/"><u>[New] Charting the Course  A Graphic Designer's Blueprint to Progress</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-17-best-lights-and-lighting-equipment-for-youtube/"><u>[Updated] In 2024, 17 Best Lights and Lighting Equipment for YouTube</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-reddits-crowned-champions-the-10-most-upvoted-posts/"><u>[Updated] In 2024, Reddit's Crowned Champions  The 10 Most Upvoted Posts</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-vibrant-plumage-and-agile-maneuvers-bebops-parrot-tale/"><u>2024 Approved  Vibrant Plumage and Agile Maneuvers  Bebop’s Parrot Tale</u></a></li>
<li><a href="https://extra-information.techidaily.com/5-expedited-mobile-video-tools-on-android-for-2024/"><u>5 Expedited Mobile Video Tools on Android for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-prevent-unauthorized-access-on-windows/"><u>7 Ways to Prevent Unauthorized Access on Windows</u></a></li>
<li><a href="https://video-capture.techidaily.com/advanced-archiving-preserving-full-fbm-call-history-for-2024/"><u>Advanced Archiving  Preserving Full FBM Call History for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/android-hacks-counterclockwise-video-stream-for-2024/"><u>Android Hacks  Counterclockwise Video Stream for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-flickering-screens-windows-11-edition/"><u>Banishing Flickering Screens: Windows 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-the-gap-find-missing-devices-in-dm/"><u>Bridge the Gap: Find Missing Devices In DM</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/charting-your-course-in-the-world-of-youtube-tracking-success-and-monetary-value/"><u>Charting Your Course in the World of YouTube  Tracking Success & Monetary Value</u></a></li>
<li><a href="https://win11.techidaily.com/curbing-microsoft-edges-heavy-background-tasks/"><u>Curbing Microsoft Edge's Heavy Background Tasks</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-pc-windows-11-device-options-revised/"><u>Customize Your PC: Windows 11 Device Options Revised</u></a></li>
<li><a href="https://win11.techidaily.com/digital-retrofit-modernizing-windows-11-with-a-98-twist/"><u>Digital Retrofit: Modernizing Windows 11 with a '98 Twist</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-macos-with-cross-platform-windows-features/"><u>Enhancing macOS with Cross-Platform Windows Features</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-server-not-available-error-steams-content-link-issue/"><u>Fixing Server Not Available Error: Steam's Content Link Issue</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-the-power-of-multiple-directories-windows-11-edition/"><u>Harnessing the Power of Multiple Directories: Windows 11 Edition</u></a></li>
<li><a href="https://extra-tips.techidaily.com/how-to-brighten-a-video-on-android-step-by-step-explained/"><u>How To Brighten A Video On Android – Step By Step Explained</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-unexpected-token-call-issues-on-windows-devices/"><u>How To Resolve “Unexpected Token Call” Issues on Windows Devices</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-xiaomi-redmi-k70-pro-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Xiaomi Redmi K70 Pro | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-vivo-s17-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Vivo S17</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-laughter-lab-free-comic-creation-at-the-gateway/"><u>In 2024, Laughter Lab  Free Comic Creation at the Gateway</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-what-does-jailbreaking-apple-iphone-12-pro-max-i-do-get-answers-here-by-drfone-ios/"><u>In 2024, What Does Jailbreaking Apple iPhone 12 Pro Max i Do? Get Answers here</u></a></li>
<li><a href="https://win11.techidaily.com/incorporating-visual-disk-space-insights-into-windows-cli/"><u>Incorporating Visual Disk Space Insights Into Windows CLI</u></a></li>
<li><a href="https://win11.techidaily.com/key-steps-for-activating-windows-recovery-software/"><u>Key Steps for Activating Windows Recovery Software</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-fixing-black-screens-and-blank-cursors-on-win11/"><u>Master the Art of Fixing Black Screens & Blank Cursors on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-app-management-with-winget-on-w11/"><u>Mastering App Management with Winget on W11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-permissions-to-prevent-read-only-mode/"><u>Mastering File Permissions to Prevent Read-Only Mode</u></a></li>
<li><a href="https://win11.techidaily.com/methods-for-fixing-audacitys-failed-sound-device-openings-on-win-os/"><u>Methods for Fixing Audacity's Failed Sound Device Openings on Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-error-code-0xc00ce556/"><u>Navigating Windows Error Code: 0XC00CE556</u></a></li>
<li><a href="https://win11.techidaily.com/nine-best-window-timers-enhancing-pomodoro-productivity/"><u>Nine Best Window Timers Enhancing Pomodoro Productivity</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-sound-system-issue-with-windows-general-device/"><u>Overcoming Sound System Issue with Windows General Device</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-the-ink-flow-pc-pen-and-touch-adjustments/"><u>Perfecting the Ink Flow: PC Pen and Touch Adjustments</u></a></li>
<li><a href="https://win11.techidaily.com/powershell-pro-tips-for-win-ipmac-extraction/"><u>PowerShell Pro Tips for Win IP/MAC Extraction</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-dormant-radeon-software-interface/"><u>Quick Fixes for Dormant Radeon Software Interface</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-to-tackle-black-screens-on-windows-11/"><u>Quick-Fix Guide to Tackle Black Screens on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-detection-of-razer-devices-by-synapse-software/"><u>Reinstating Detection of Razer Devices by Synapse Software</u></a></li>
<li><a href="https://win11.techidaily.com/removing-personal-data-from-the-windows-login-area/"><u>Removing Personal Data From the Windows Login Area</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-file-access-error-on-windows-a-step-by-step-guide/"><u>Resolving File Access Error on Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-microsoft-store-color-glitches/"><u>Resolving Microsoft Store Color Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-off-view-apps-in-win-1011-the-ultimate-guide-to-6-recovery-methods/"><u>Reviving Off-View Apps in Win 10/11: The Ultimate Guide to 6 Recovery Methods</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-route-from-gaming-archives-to-windows-memories/"><u>The Essential Route From Gaming Archives to Windows Memories</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-guide-swift-solutions-for-adding-a-folder-to-onedrive-successfully/"><u>Troubleshooting Guide: Swift Solutions for Adding a Folder to OneDrive Successfully</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-filesystem-woes-a-win10win11-fixers-manual/"><u>Unpacking Filesystem Woes: A Win10/Win11 Fixer's Manual</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-a-runtime-broker-unpacking-its-importance-for-pcs/"><u>What Is a Runtime Broker? Unpacking Its Importance for PCs</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-nokia-130-music-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Nokia 130 Music? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/win11-error-fixer-correcting-code-0x0000011b/"><u>Win11 Error Fixer: Correcting Code 0X0000011B</u></a></li>
<li><a href="https://win11.techidaily.com/winning-back-original-icon-placement/"><u>Winning Back Original Icon Placement</u></a></li>
<li><a href="https://win11.techidaily.com/winning-cars-mouse-keys-and-acceleration-mastery/"><u>Winning Cars: Mouse, Keys, and Acceleration Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/winshift-troubles-how-to-resolve-them/"><u>WinShift Troubles: How to Resolve Them.</u></a></li>
</ul></div>
