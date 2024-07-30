---
title: "Conquer File Management: Crafting Multitudes of Subfolders Instantly"
date: 2024-07-29T15:44:35.975Z
updated: 2024-07-30T15:44:35.975Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Conquer File Management: Crafting Multitudes of Subfolders Instantly"
excerpt: "This Article Describes Conquer File Management: Crafting Multitudes of Subfolders Instantly"
keywords: File Mgmt Mastery,Quick Folder Creation,Subfolder Strategy,Efficient Folder Hunt,Fast Subfldr Crafting,Multifold Organization,Instant Folder Prosperity
thumbnail: https://thmb.techidaily.com/79265524b64a96a355aa9c66ef040a78b4c61cd77b813b963d28880dc313d729.jpg
---

## Conquer File Management: Crafting Multitudes of Subfolders Instantly

 The latest Windows versions allow you to automate quite a few of your tasks, for instance letting you create multiple folders and sub-folders at once. This is quite helpful in situations where you need to sort out the data (for each semester, for instance) and do not want to spend hours doing it.

 There is more than one method of creating multiple files and folders in Windows, and we have outlined the best ways of doing so for you below. Read through the methods and proceed with the one you want.

## 1\. Use the Command Prompt to Create Multiple Folders at Once

 In this first method, we will be using a command-line utility called Command Prompt in Windows. Unless you are very tech-savvy, you may not have noticed it anywhere in Windows, but it has been around for quite a long time.

 Typically, administrators use it to make advanced-level changes throughout the system. You can enter text-based commands to automate a bunch of tasks.

 Below, we have listed detailed steps for using Command Prompt to create multiple folders at once. Make sure you are signed in to Windows as an administrator before you proceed:

1. Type **Command Prompt** in Windows search and click on **Run as administrator**.
2. Alternatively, you can also open Run by pressing **Win** \+ **R** and type **cmd** in the text field. Press **Ctrl** \+ **Shift** \+ **Enter** to open Command Prompt as an administrator.  
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
![Run dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/12/accessing-cmd-through-run-box.jpg)
3. Click **Yes** in the User Account Control prompt.
4. Type the following command in the Command Prompt window and hit **Enter** to execute it. Make sure to replace the \[location\] with the location where you want to create multiple folders.  
`cd /d [location]`
5. For instance, if we want to create folders in the C:\\users\\hp\\documents folder, we will execute the command like cd /d C:\\users\\hp\\documents.  
![Location command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-cd-d-location-1.jpg)
6. Then, type **md** following the names of the folders in one command and execute it. For instance, if we want to create folders for the first 4 months of the year. We will execute the command as:  
`md january february march april`  
![Command with file names](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-md-files.jpg)
7. Once done, close the Command Prompt window and visit the location of folders in File Explorer to see if the folders have been created.

 If for some reason using the Command Prompt does not work for you, you can use Windows Powershell (Admin) to perform the same steps. The Powershell works almost the same as Command Prompt, but it is much more powerful than cmd.

 To use Powershell, follow these steps:

1. Right-click on the **Windows icon** on your taskbar and choose **Powershell (Admin)**.  
![Windows Terminal (Admin)](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/windows-terminal.jpg)
2. Select Yes in the UAC prompt.  
![UAC prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-terminal-uac.jpg)
3. Now, execute the command mentioned below and change the \[Location\] with your targeted location for creating the folders.  
`cd [Location]`
4. We want to create the sub-folders in the document folders, so we will be executing the following command:  
`cd C:\users\hp\documents`  
![Execute location command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-terminal-cd-d-location.jpg)
5. Once done, execute the following command. Replace the \[foldername\] with the names you want to give the folders.  
`md "[foldername]", "[foldername]", "[foldername]", "[foldername]"`
6. For instance, if we want to create folders for the first 4 months of the year. We will execute the command as:  
`md "january", "february", "march", "april"`  
<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![File names command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-terminal-md-files.jpg)

 Finally, close the Powershell window and check if the folders have been created.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Use the Notepad to Create Multiple Folders at Once

 Though it may come as a surprise, the Windows Notepad can perform more advanced technical operations than just writing to-do lists.

 The methods above are suitable if you only want to create multiple folders without any subfolders. If you wish to create subfolders as well, then an easy way to do it is by creating a batch script via Notepad.

 Here is how you can do that:

1. Type **Notepad** in Windows search and click **Open**.
2. In the Notepad window, click type **@ECHO OFF** and click **Enter**.
3. Then type **md** followed by the folder and subfolder names enclosed in double quotes. For instance, if we want to create a MUO January folder with a Windows subfolder and a MUO February folder with an Android subfolder, we will type it down in Notepad as:  
`@ECHO OFF  
md "MUOJan"\"Windows" "MUOFeb"\"Android"`  
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Notepad command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-notepad-command.jpg)
4. After you have typed down the names of all the folders and subfolders that you want to create, navigate to **File** in the top-left corner and choose **Save as**.  
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
![Save as option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/notepad-save-as.jpg)
5. Give your file a name followed by **.bat**. For instance, we named our file as makeuseof.bat.  
![Notepad file name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/notepad-file-name.jpg)
6. Expand the dropdown for Save as type and choose **All files**.
7. Click **OK** and close the Notepad.
8. Now, navigate to the location of the folder and open the bat file. Opening it should create the folders and their subfolders for you.

 Now that you have created multiple files and folders, [organizing these files on Windows](https://www.makeuseof.com/tag/automatically-organize-files-windows/) is also worth considering if you do not want to spend a lot of time looking for information in them. Additionally, Windows also allows you to [rename multiple folders at once](https://www.makeuseof.com/cool-folder-tips-windows/), which can be helpful when organizing them.

## 3\. Use a Third-Party Application

 Last but not least, if you think using Command Prompt and Notepad is too time-consuming, you can try using a third-party application.

 There are quite a few apps that can help you achieve this, including the following:

* [Soboloft](https://www.sobolsoft.com/file-management.htm)
* [Text 2 Folders](https://www.softpedia.com/get/System/File-Management/Text-2-Folders.shtml)
* [Folder Frenzy](https://www.softpedia.com/get/System/File-Management/Folder-Frenzy.shtml)
* [FreeCommander XE](https://freecommander.com/en/summary/)
* [XMD](https://www.softpedia.com/get/System/File-Management/XMD.shtml)

 For illustration purposes, we will be using Folder Frenzy. The steps of creating multiple folders in other applications might vary, but the basics will remain the same.

1. Download Folder Frenzy.
2. Extract the downloaded file and then launch it.
3. Click **Yes** in the confirmation prompt.  
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Clicking Yes in the UAC prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/folder-frenzy-agreement.jpg)
4. Once the Folder Frenzy dialog launches, type the names of the folders you want to create and click on the **Create Folder** button. These folders will be created in the Folder Frenzy file.  
<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Create folder in Folder Frenzy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/folder-frenzy-create-folder.jpg)

 From here, you can even take a step further and learn [how to launch multiple programs with one shortcut on Windows](https://www.makeuseof.com/tag/launch-multiple-programs-single-shortcut-using-batch-file/) to increase your productivity at work or school. In case you no longer need the tool after creating bulk folders, you can uninstall it. This won't automatically delete the folders you have created using the tool, unless the uninstallation process explicitly offers to do so and you confirm that action.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Create Multiple Folders in a Few Clicks on Windows

 Creating several folders manually is a mundane task, and you can spend the same energy doing something more productive. The steps we have outlined above should help you automate this task, saving time for things that actually bring in some value.

 The latest Windows versions allow you to automate quite a few of your tasks, for instance letting you create multiple folders and sub-folders at once. This is quite helpful in situations where you need to sort out the data (for each semester, for instance) and do not want to spend hours doing it.

 There is more than one method of creating multiple files and folders in Windows, and we have outlined the best ways of doing so for you below. Read through the methods and proceed with the one you want.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-a-stepwise-approach-for-creating-an-interactive-skype-conversation-among-users-from-multiple-operating-systems/"><u>[New] 2024 Approved  A Stepwise Approach for Creating an Interactive Skype Conversation Among Users From Multiple Operating Systems</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-effortless-video-streams-youtube-loops-for-television-viewers/"><u>[New] 2024 Approved  Effortless Video Streams  YouTube Loops for Television Viewers</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-from-biting-snippets-to-captivating-narratives-an-experts-guide-to-youtube-edits/"><u>[New] 2024 Approved  From Biting Snippets to Captivating Narratives  An Expert's Guide to Youtube Edits</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-brand-your-channel-innovative-banner-templates-for-gamers-for-2024/"><u>[Updated] Brand Your Channel  Innovative Banner Templates for Gamers for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-easeus-reviewed-a-world-of-technology-for-2024/"><u>[Updated] EaseUS Reviewed  A World of Technology for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-high-definition-vision-recorder-devices/"><u>[Updated] In 2024, High Definition Vision Recorder Devices</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-navigating-small-business-video-markets/"><u>[Updated] Navigating Small Business Video Markets</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-selecting-the-right-top-15-tripods-for-gopro-cameras/"><u>[Updated] Selecting the Right Top 15 Tripods for GoPro Cameras</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreenas-beginners-guide-to-github-desktop-for-windows-users/"><u>A Compreenas Beginners Guide to GitHub Desktop for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/clear-your-screen-clutter-advanced-window-organization-win11-and-10/"><u>Clear Your Screen Clutter: Advanced Window Organization (Win11 & 10)</u></a></li>
<li><a href="https://win11.techidaily.com/confronting-and-correcting-windows-11-errors/"><u>Confronting and Correcting WINDOWS 11 Errors</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/connect-tv-audiences-with-creative-fb-livestream-strategies/"><u>Connect TV Audiences with Creative FB Livestream Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/cut-down-your-computers-warmup-time-in-win11/"><u>Cut Down Your Computer's Warmup Time in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/disentangle-clustered-taskbar-items-in-windows-11/"><u>Disentangle Clustered Taskbar Items in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-visibility-on-windows-11-discreet-features/"><u>Enabling Visibility on Windows 11 Discreet Features</u></a></li>
<li><a href="https://extra-information.techidaily.com/experience-transformative-text-design-with-these-leading-platforms/"><u>Experience Transformative Text Design with These Leading Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-resolving-windows-error-code-c0000022/"><u>Expert Guide to Resolving Windows Error Code C0000022</u></a></li>
<li><a href="https://win11.techidaily.com/facing-browser-blockades-top-tactics-to-reach-sites-on-your-system/"><u>Facing Browser Blockades: Top Tactics to Reach Sites on Your System</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-err-87-for-incompatible-library-loading/"><u>Fixing Err 87 for Incompatible Library Loading</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unreachable-friends-list-on-steam-win-11/"><u>Fixing Unreachable Friends List on Steam (Win 11)</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-from-streaming-to-savings-preserving-your-internet-tunes/"><u>In 2024, From Streaming to Savings  Preserving Your Internet Tunes</u></a></li>
<li><a href="https://win11.techidaily.com/install-windows-11-on-mac-with-parallels-step-by-step/"><u>Install Windows 11 on Mac with Parallels Step-by-Step</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-steam-cloud-failures-on-pc/"><u>Overcoming Steam Cloud Failures on PC</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-writing-errors-for-files-in-windows-systems/"><u>Overcoming Writing Errors for Files in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-your-recordings-best-free-windows-programs/"><u>Perfect Your Recordings: Best FREE Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-windows-lock-screen-timer-breakage/"><u>Repairing Window's Lock Screen Timer Breakage</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-error-code-0x800700e1-on-w10w11/"><u>Resolving Error Code: 0X800700E1 on W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/restore-steam-game-symbols-from-nowhere/"><u>Restore Steam Game Symbols From Nowhere</u></a></li>
<li><a href="https://win11.techidaily.com/secure-your-screens-overcoming-windows-setup-woes/"><u>Secure Your Screens: Overcoming Windows Setup Woes</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-non-disappearing-edge-shortcuts/"><u>Solutions for Non-Disappearing Edge Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-combat-breakpoint-exception-error-in-windows/"><u>Solutions to Combat Breakpoint Exception Error in Windows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/step-into-fantasy-with-these-samsung-gear-vr-titles-for-2024/"><u>Step Into Fantasy with These Samsung Gear VR Titles for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-personalizing-your-fn-keys-in-windows-os/"><u>Step-By Step Guide to Personalizing Your FN Keys in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-0x800713f-problem-repair-windows-11s-mail-service/"><u>Tackling 0X800713F Problem: Repair Windows 11'S Mail Service</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-windows-understanding-report-generation-and-analysis/"><u>The Art of Windows Understanding: Report Generation & Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-desktop-on-windows-11-with-vibrant-backdrops/"><u>Transform Your Desktop on Windows 11 with Vibrant Backdrops</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-xbox-mic-in-windows-11/"><u>Troubleshooting Non-Functional Xbox Mic in Windows 11</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/vlc-video-record-a-critique/"><u>VLC Video Record  A Critique</u></a></li>
<li><a href="https://win11.techidaily.com/windows-update-unpopular-version-11-among-users/"><u>Windows Update – Unpopular Version 11 Among Users</u></a></li>
<li><a href="https://win11.techidaily.com/winning-against-access-denied-a-comprehensive-guide-to-5-solutions/"><u>Winning Against 'Access Denied': A Comprehensive Guide to 5 Solutions</u></a></li>
</ul></div>
