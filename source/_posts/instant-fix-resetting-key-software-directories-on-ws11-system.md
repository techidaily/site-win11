---
title: "Instant Fix: Resetting Key Software Directories on WS11 System"
date: 2024-11-06T21:32:01.100Z
updated: 2024-11-07T20:58:15.762Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Instant Fix: Resetting Key Software Directories on WS11 System"
excerpt: "This Article Describes Instant Fix: Resetting Key Software Directories on WS11 System"
keywords: Quick System Reset,WS11 Directory Repair,Fixed Key Software,Reset Directories WS11,Instant Fix for WS11,Software Directories Restore,Key WS11 Correction
thumbnail: https://thmb.techidaily.com/7180d1f46214638b981f44d739909bb52ccedea125713b9abadc25eed94ff8d6.jpg
---

## Instant Fix: Resetting Key Software Directories on WS11 System

 Users widely report Windows 11 update errors on support forums. Updates fail to install because of such errors. You can often fix update errors by resetting the catroot 2 and Windows SoftwareDistribution folders as covered below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Are the SoftwareDistribution and Catroot2 Folders?

 The SoftwareDistribution folder is a directory that stores files required for installing Windows updates on PCs. It is a temporary repository of the update files. Thus, the SoftwareDistribution folder is an important component for updating Windows.

 Catroot 2 is a folder that stores the signature data for Windows 11 updates. Those are the files the Cryptographic service needs for update verification.

 Both folders contain files needed for the installation of Windows updates. Windows update installation issues can occur because of corrupted data in those folders. Those errors typically appear in Settings with variable codes like 0x800f0922 when users manually select to check for and install updates.

 Therefore, resetting those folders is a troubleshooting method for fixing Windows 11 update installation issues. Resetting the SoftwareDistribution and Catroot2 folders removes corrupted data they might contain, which rebuilds them. You can reset those folders by deleting their contents or renaming them.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938745/19272" target="_top" id="1938745">
  <img src="//a.impactradius-go.com/display-ad/19272-1938745" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938745/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Reset the SoftwareDistribution and Catroot2 Folders by Erasing Their Contents

 This method for resetting the SoftwareDistribution and Catroot2 folders involves manually eradicating the data in them via File Explorer. It’s also necessary to disable and re-enable certain services via the Command Prompt to ensure they’re not utilizing files in them. Delete the files in the SoftwareDistribution and Catroot2 folders as follows:

1. Open the file finder utility accessible with a **Windows** logo + **S** hotkey.
2. Locate the Command Prompt by entering the keyword **cmd** into the search text box.
3. Select to [open the Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) by clicking its **Run as administrator** option on the right of the search tool.
4. Input and execute the following separate commands to disable services required for updating Windows 11:  
`net stop bits  

net stop wuauserv  

net stop cryptsvc  

net stop msiserver`
5. Press the **Windows key + E** on your keyboard to go to File Explorer.
6. Open the SoftwareDistribution folder at this path:  
`C:\Windows\SoftwareDistribution`
7. Press **Ctrl** \+ **A** to select all the files in the SoftwareDistribution folder.
8. Right-click and select **Delete** (the trash can button) to eradicate selected content.  
![The SoftwareDistribution folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/softwaredistribution-folder.jpg)
9. Bring up the catroot2 folder by entering this path in Explorer’s address bar:  
`C:\Windows\System32\catroot2`
10. Repeat steps seven and eight above to erase everything in that folder.  
![The catroot2 folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/catroot2folder.jpg)
11. Return to the Command Prompt and execute these separate commands for restarting the disabled services.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111994/7443" target="_top" id="2111994">
  <img src="//a.impactradius-go.com/display-ad/7443-2111994" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111994/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`net start bits  

net start wuauserv  

net start cryptSvc  

net start msiserver`
12. Restart the PC and check for updates after clearing those folders.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105873/7443" target="_top" id="2105873">
  <img src="//a.impactradius-go.com/display-ad/7443-2105873" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105873/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Reset the SoftwareDistribution and Catroot2 Folders by Renaming Them

 Renaming the SoftwareDistribution and Catroot2 directories is an alternative method for resetting those folders. Windows will recreate those folders after you’ve renamed them. You can rename the SoftwareDistribution and catroot2 folders with the Command Prompt like this:

1. Run the Command Prompt with elevated admin rights.
2. Repeat step four of the preceding method to execute the commands for disabling services.  
![The net stop commands](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/net-stop-commands.jpg)
3. Input this command to rename the SoftwareDistribution folder and press **Return**:  
`ren %systemroot%\softwaredistribution softwaredistribution.bak`  
![The rename SoftwareDistribution folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-softwaredistribution-command.jpg)
4. Enter and execute this rename command for the catroot2 folder:  
`ren %systemroot%\system32\catroot2 catroot2.bak`  
![The ren catroot2 command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/ren-catroot2-folder.jpg)
5. Repeat step 11 of the preceding method by executing the four commands for restarting the disabled services.  
![The net start command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/net-start-commands.jpg)
6. Exit Command Prompt and select to restart your PC.

## How to Reset the SoftwareDistribution and Catroot2 Folders With FixWin 11

 FixWin 11 is one of the [best freely available Windows repair tools](https://www.makeuseof.com/tag/5-free-tools-fix-problem-windows-10/) that includes troubleshooting options. Among them are two options for resetting the catroot2 and SoftwareDistribution folders. This is how you can select those quick fix options in FixWin 11:

1. Open this [FixWin 11 page](https://www.softpedia.com/get/Tweak/System-Tweak/FixWin-11.shtml) on the Softpedia website.
2. Click on the **Free Download** button for FixWin.
3. Select **Secure Download (US)** to obtain FixWin’s ZIP archive.
4. Activate a File Explorer window and go to your browser’s downloads folder.
5. Extract the FixWin archive by going through the steps in this article about [unzipping ZIP files on Windows](https://www.makeuseof.com/how-to-extract-zip-files-windows-11/).  
![The Extract Compressed ZIP archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/extract-compressed-window.jpg)
6. Double-click the **FixWin 11.1.exe** file in the extracted folder for FixWin.
7. Click **Additional Fixes** on the left of the FixWin window.
8. Select the **Quick Fixes** tab.
9. Press the **Reset Software Distribution folder** button.  
![The Quick Fixes tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/quick-fixes-tab.jpg)
10. Click the **Reset catroo2 Folder** option.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136612/26400" target="_top" id="2136612">
  <img src="//a.impactradius-go.com/display-ad/26400-2136612" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136612/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

11. Exit FixWin and reboot your PC after selecting those options.

## Fix Windows Update Issues by Resetting the SoftwareDistribution and Catroot2 Folders

 It’s important to resolve update issues when they arise for the sake of keeping Windows updated. Resetting the catroo2 and SoftwareDistribution folders is one of the most effective troubleshooting methods for fixing Windows update errors.

 So, try doing that whenever you need to fix an error code shown within the Windows Update tab of Settings.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/024-approved-boosting-views-with-customized-thumbnail-sizes-on-youtube/"><u>[New] 2024 Approved Boosting Views with Customized Thumbnail Sizes on YouTube</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-acquiring-fcp-for-zip-legal-strategies-explained/"><u>[New] Acquiring FCP for Zip Legal Strategies Explained</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-transformative-visual-experiences-with-tiktok-enhancements/"><u>[New] Transformative Visual Experiences with TikTok Enhancements</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-achieve-more-money-from-your-short-videos-on-youtube/"><u>[Updated] 2024 Approved Achieve More Money From Your Short Videos on YouTube</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1726219609657-movavi/"><u>「ファイナルエクササイズ - Movaviで簡単な方法:高画質動画のキャプチャ技術」</u></a></li>
<li><a href="https://extra-information.techidaily.com/dive-deep-into-durability-gopro-hero5-vs-hero5-session/"><u>Dive Deep Into Durability GoPro Hero5 vs Hero5 Session</u></a></li>
<li><a href="https://win11.techidaily.com/encouraging-readers-to-consider-homestays-or-volunteer-exchanges-for-authentic-local-experiences/"><u>Encouraging Readers to Consider Homestays or Volunteer Exchanges for Authentic Local Experiences.</u></a></li>
<li><a href="https://win11.techidaily.com/get-free-downloads-access-your-favorite-movies-and-tunes-from-anywhere/"><u>Get Free Downloads: Access Your Favorite Movies & Tunes From Anywhere</u></a></li>
<li><a href="https://win11.techidaily.com/guide-transforming-video-files-into-mp3s-via-windows-media-player/"><u>Guide: Transforming Video Files Into MP3s via Windows Media Player</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-capture-your-desktop-and-sound-a-step-by-step-guide/"><u>How to Capture Your Desktop & Sound: A Step-by-Step Guide</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-honor-play-8t-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Honor Play 8T? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/itunesisoiphone/"><u>ITunesからISOファイルを読み込むiPhoneのテクニック：知って得するヒント</u></a></li>
<li><a href="https://win11.techidaily.com/manage-your-documents-with-confidence-using-wonderfoxs-top-notch-pdf-organizer-suite/"><u>Manage Your Documents with Confidence Using WonderFox's Top-Notch PDF Organizer Suite</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-powerpoint-multimedia-seamless-tutorial-on-adding-mp4-files-perfectly/"><u>Mastering PowerPoint Multimedia: Seamless Tutorial on Adding MP4 Files Perfectly</u></a></li>
<li><a href="https://win11.techidaily.com/mp4wmawindows-1011/"><u>MP4とWMAの間で素早く変換:Windows 10/11ユーザー向け方法</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-windows-11-update-obstacles-expert-advice-and-solutions/"><u>Overcoming Windows 11 Update Obstacles: Expert Advice & Solutions</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/the-ultimate-guide-to-effective-screen-recorders/"><u>The Ultimate Guide to Effective Screen Recorders</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    