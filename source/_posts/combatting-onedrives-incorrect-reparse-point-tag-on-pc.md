---
title: Combatting OneDrive’s Incorrect Reparse Point Tag on PC
date: 2024-10-21T23:00:17.650Z
updated: 2024-10-26T20:53:41.747Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Combatting OneDrive’s Incorrect Reparse Point Tag on PC
excerpt: This Article Describes Combatting OneDrive’s Incorrect Reparse Point Tag on PC
keywords: Fixing ODRI Errors,Stop ODRI Issues,Remove ODRI Tagging,Correct ODRI Behavior,Solve ODRI Conflicts,Improve ODRI on PC,Eliminate ODRI Glitches
thumbnail: https://thmb.techidaily.com/9482ded5e871af812d18f96a64c4deb315943988e9201916667eb608e7a9ffd3.jpg
---

## Combatting OneDrive’s Incorrect Reparse Point Tag on PC

 Have you encountered the "the tag present in the reparse point buffer is invalid" error when altering a folder or deleting it on your Windows device? You may have encountered this error when accessing a folder via Command Prompt or File Explorer, mainly for files and folders synced to OneDrive. How does this error occur? OneDrive is the source of the error.

 In this article, we'll explain the causes of this error and provide you with possible solutions to resolve it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Causes "The Tag Present in the Reparse Point Buffer Is Invalid" on Windows?

 As mentioned earlier, the error is caused by a problem with OneDrive sync. It could be that the folder you're trying to access is corrupt, or that there is an issue with other system files preventing OneDrive from syncing successfully.

 There are several ways in which the "the tag present in the reparse point buffer is invalid" error can appear. Here are the two most common ones:

* Error 0x80071129: The tag present in the reparse point buffer is invalid
* Location not found: The tag present in the reparse point buffer is invalid

 "Error 0x80071129" or "Location not found" appears as the title of the error window, while the main part of the error appears in the error window. Any variation of this error has nearly the same causes, regardless of its nature. In light of that, similar fixes are effective in resolving the issue. Let's see how you can fix it.

## But First, Some Preliminary Checks

 Apply the following preliminary checks before attempting the major fixes:

* Pause the OneDrive sync and try opening the folder again.
* Restart your device once.
* Log out of your OneDrive account.
* If you have made any changes to the problematic folder on OneDrive, go back and revert them for a while.

 If the above preliminary checks do not solve the problem and the issue persists, start implementing the remaining fixes.

## 1\. Run a CHKDSK Scan

 For Windows users, CHKDSK is a go-to utility for scanning and fixing hard drive problems. Whenever users encounter a hard drive error or an issue with the data stored on their drive, the CHKDSK scan proves to be a godsend.

 This scan may be helpful to fix the issue under discussion since "the tag present in the reparse point buffer is invalid" is also associated with an inability to access a particular file correctly. Therefore, follow the steps below to run the CHKDSK scan before you attempt any other repair or fix:

1. In the Windows Search box, type**"Command Prompt** .**"**
2. Right-click the**Command Prompt** app and click**Run as administrator** .
3. Enter the following command in the Command Prompt app:  
`Chkdsk C: /f /r`
4. Then press**Enter** .  
![Running Check Disk Scan in Windows Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/running-check-disk-scan-in-windows-command-prompt.jpg)

 Here,**C:** refers to the drive where your operating system is installed. If your operating system resides on a different drive, change the command accordingly. Also, don't forget to enter the**"/f"** and**"/r"** parameters since these are needed to fix errors, locate bad sectors, and recover corrupted information.

 The CHKDSK scan has the greatest chance of adequately fixing the error under discussion. However, if it doesn't resolve the problem, you can move on to the next solution.

## 2\. Run the DISM and SFC Scan

 Like CHKDSK, SFC and DISM scans can be used when your system behaves strangely. Initially, you should run the SFC scan because it usually resolves the issue. However, if it fails to diagnose the problem or run, you should run a DISM scan.

 Performing both scans ensures that your device does not have corrupted system files causing the trouble. To run both scans, follow these steps:

1. Open Command Prompt as an administrator.
2. To run the SFC scan, type the following command and press**Enter** :  
`SFC /scannow`
3. To run the DISM scan, type the following command and press**Enter** :  
`DISM /Online /Cleanup-Image /RestoreHealth`

![Run SFC and DISM scans](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/scannow-restorehealth-cmd-1.jpg)

 To better understand the results of these scans, see our[article about the differences between CHKDSK, DISM, and SFC](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) . If the error persists after running the above scans, move on to the next fix.

## 3\. Check for File-Specific Issues

 Next, you should check whether the error occurs for a particular file or all files synced on OneDrive. Attempt to make the exact change that caused the error in a different folder and see if the problem repeats. If the issue is file-specific, it is recommended that you restore the file to its previous version, if possible. Here are the steps you need to follow:

1. Right-click on the file you're experiencing the error with and open**Properties** .
2. Click on the**Previous Versions** tab.
3. Select the previous version, if available.
4. Click the**Restore** button, then click**Apply** and**OK** .  
![Restoring Previous Version of a File in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-restore-previous-file-version.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657396/16446" target="_top" id="1657396">
  <img src="//a.impactradius-go.com/display-ad/16446-1657396" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657396/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Remove the Passwords From the Problematic Files

 Has this error occurred after password-protecting a synced file on OneDrive? In this case, you should go to OneDrive, check the history of modified files, and restore the problematic file to a previous version. Our article on[recovering OneDrive files from version history](https://www.makeuseof.com/tag/restore-onedrive-files-version-history/#rolling-back-a-file) explains how to roll back a file. Reset OneDrive if this fix does not solve the problem.

<!-- affiliate ads begin -->
<span id="1982456">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982456.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982456">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982456.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982456%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982456/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Reset OneDrive

 Resetting the app or service is a good troubleshooting step for problems that don't resolve with general fixes. Therefore, if none of the fixes have worked so far, you should reset OneDrive. Remember that resetting OneDrive will not delete your data, but you'll have to set up the sync connection again.

 In our article on[how to fix OneDrive when you can't open the files](https://www.makeuseof.com/ways-fix-onedrive-when-you-cannot-open-your-files/#reset-onedrive) , we have explained how to reset OneDrive. Follow the instructions in the article to reset OneDrive, and hopefully, you will be able to fix the issue. However, if that also fails to work and the error appears periodically, you can delete or relocate the problematic file or folder.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068432/7443" target="_top" id="2068432">
  <img src="//a.impactradius-go.com/display-ad/7443-2068432" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068432/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Delete or Relocate the Problematic File

 If all else fails, delete or relocate the problematic file. However, before you do that, you need to pause the OneDrive sync and leave it for an hour. Then, access your OneDrive online and remove the synced file from there.

 Once done, you should turn off your device's internet connection and[start Windows 11 in Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/) (or[Windows 10](https://www.makeuseof.com/tag/boot-windows-10-safe-mode/) if you're using an older version). Afterward, navigate to your local drive, where the problematic file is located. Delete it from there and restart your device normally.

 If the file you are experiencing the error with has value to you and you cannot delete it, move it to another computer and delete it from your primary device. Hopefully, relocating or deleting the file will prevent the error from occurring again.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148647/16836" target="_top" id="2148647">
  <img src="//a.impactradius-go.com/display-ad/16836-2148647" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148647/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Keep Annoying OneDrive Errors at Bay

 It can be very frustrating to encounter the "The tag present in the reparse point buffer is invalid" error when making changes to our files. If you apply the fixes in the article, hopefully, you'll be able to fix the error and reaccess your files. If nothing works, you can move it elsewhere and delete it from your primary drive.

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
<li><a href="https://facebook-record-videos.techidaily.com/updated-effortless-music-extraction-choose-the-right-apps-for-youtube-and-mp3-for-2024/"><u>[Updated] Effortless Music Extraction Choose the Right Apps for YouTube & MP3 for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-white-walkers-whistle-where-to-find-your-favorite-got-ringtone/"><u>[Updated] In 2024, White Walkers Whistle Where to Find Your Favorite GoT Ringtone</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-errors-in-windows-media-playback/"><u>Correcting Errors in Windows Media Playback</u></a></li>
<li><a href="https://win11.techidaily.com/elusive-command-center-hide-and-seek-guide-for-win/"><u>Elusive Command Center Hide-and-Seek Guide for Win</u></a></li>
<li><a href="https://program-issues.techidaily.com/expert-tips-for-preventing-frequent-valorant-clashes-and-freezes-on-desktops/"><u>Expert Tips for Preventing Frequent Valorant Clashes and Freezes on Desktops</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-adjust-camera-settings-to-prevent-whatsapp-zoom-glitches/"><u>How to Adjust Camera Settings to Prevent WhatsApp Zoom Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-erase-google-chromes-default-webp-saving-on-your-pc/"><u>How to Erase Google Chrome's Default WebP Saving on Your PC</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-vivo-y200e-5g-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Vivo Y200e 5G Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-try-connecting-your-device-bluetooth-pairing-error-in-windows-11-and-11/"><u>How to Fix the “Try Connecting Your Device” Bluetooth Pairing Error in Windows 11 & 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-nokia-c12-plus-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Nokia C12 Plus? | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-home-movie-mastery-ezvid-for-mac-makes-video-creation-a-breeze/"><u>New Home Movie Mastery Ezvid for Mac Makes Video Creation a Breeze</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-notepad-on-windows-quick-fixes-guide/"><u>Reviving Your Notepad on Windows: Quick Fixes Guide</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-end-of-an-era-at-openai-as-ceo-sam-altman-steps-down-how-will-it-affect-chatgpt/"><u>The End of an Era at OpenAI as CEO Sam Altman Steps Down - How Will It Affect ChatGPT?</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-ultimate-guide-to-professional-livestreamers-vmix-or-wirecast/"><u>The Ultimate Guide to Professional Livestreamers VMix or Wirecast?</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-power-of-windows-updates/"><u>Unlock the Power of Windows Updates</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-secrets-to-fixing-error-code-0x80040610-in-windows/"><u>Unveiling the Secrets to Fixing Error Code 0X80040610 in Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-xiaomi-redmi-note-13-pro-5g-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Xiaomi Redmi Note 13 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-change-your-onedrive-folders-address/"><u>Win 11: Change Your OneDrive Folder's Address</u></a></li>
<li><a href="https://win11.techidaily.com/win-friendly-ways-to-address-exit-code-1-wow/"><u>Win-Friendly Ways to Address Exit Code: 1 WoW</u></a></li>
</ul></div>

