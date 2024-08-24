---
title: "Fixing Invalid OneDrive Tags: Steps for Windows Users"
date: 2024-08-23T06:12:16.171Z
updated: 2024-08-24T06:12:16.171Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Fixing Invalid OneDrive Tags: Steps for Windows Users"
excerpt: "This Article Describes Fixing Invalid OneDrive Tags: Steps for Windows Users"
keywords: OneDrive Tag Fix Guide,Windows User OneDrive Error,Resolve OneDrive Issues,Correcting OneDrive Errors,OneDrive Tags Correction,Steps for Docs Error,Windows 10 OneDrive Repair
thumbnail: https://thmb.techidaily.com/5f63ba1e3593ebd7d73d1c72fb68eace0cd63a5c8a537d585a504e6de4ee75de.jpg
---

## Fixing Invalid OneDrive Tags: Steps for Windows Users

 Have you encountered the "the tag present in the reparse point buffer is invalid" error when altering a folder or deleting it on your Windows device? You may have encountered this error when accessing a folder via Command Prompt or File Explorer, mainly for files and folders synced to OneDrive. How does this error occur? OneDrive is the source of the error.

 In this article, we'll explain the causes of this error and provide you with possible solutions to resolve it.

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Run the DISM and SFC Scan

 Like CHKDSK, SFC and DISM scans can be used when your system behaves strangely. Initially, you should run the SFC scan because it usually resolves the issue. However, if it fails to diagnose the problem or run, you should run a DISM scan.

 Performing both scans ensures that your device does not have corrupted system files causing the trouble. To run both scans, follow these steps:

1. Open Command Prompt as an administrator.
2. To run the SFC scan, type the following command and press**Enter** :  
`SFC /scannow`
3. To run the DISM scan, type the following command and press**Enter** :  
`DISM /Online /Cleanup-Image /RestoreHealth`

![Run SFC and DISM scans](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/scannow-restorehealth-cmd-1.jpg)

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To better understand the results of these scans, see our[article about the differences between CHKDSK, DISM, and SFC](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) . If the error persists after running the above scans, move on to the next fix.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Check for File-Specific Issues

 Next, you should check whether the error occurs for a particular file or all files synced on OneDrive. Attempt to make the exact change that caused the error in a different folder and see if the problem repeats. If the issue is file-specific, it is recommended that you restore the file to its previous version, if possible. Here are the steps you need to follow:

1. Right-click on the file you're experiencing the error with and open**Properties** .
2. Click on the**Previous Versions** tab.
3. Select the previous version, if available.
4. Click the**Restore** button, then click**Apply** and**OK** .  
![Restoring Previous Version of a File in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-restore-previous-file-version.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## 4\. Remove the Passwords From the Problematic Files

 Has this error occurred after password-protecting a synced file on OneDrive? In this case, you should go to OneDrive, check the history of modified files, and restore the problematic file to a previous version. Our article on[recovering OneDrive files from version history](https://www.makeuseof.com/tag/restore-onedrive-files-version-history/#rolling-back-a-file) explains how to roll back a file. Reset OneDrive if this fix does not solve the problem.

## 5\. Reset OneDrive

 Resetting the app or service is a good troubleshooting step for problems that don't resolve with general fixes. Therefore, if none of the fixes have worked so far, you should reset OneDrive. Remember that resetting OneDrive will not delete your data, but you'll have to set up the sync connection again.

 In our article on[how to fix OneDrive when you can't open the files](https://www.makeuseof.com/ways-fix-onedrive-when-you-cannot-open-your-files/#reset-onedrive) , we have explained how to reset OneDrive. Follow the instructions in the article to reset OneDrive, and hopefully, you will be able to fix the issue. However, if that also fails to work and the error appears periodically, you can delete or relocate the problematic file or folder.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 6\. Delete or Relocate the Problematic File

 If all else fails, delete or relocate the problematic file. However, before you do that, you need to pause the OneDrive sync and leave it for an hour. Then, access your OneDrive online and remove the synced file from there.

 Once done, you should turn off your device's internet connection and[start Windows 11 in Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/) (or[Windows 10](https://www.makeuseof.com/tag/boot-windows-10-safe-mode/) if you're using an older version). Afterward, navigate to your local drive, where the problematic file is located. Delete it from there and restart your device normally.

 If the file you are experiencing the error with has value to you and you cannot delete it, move it to another computer and delete it from your primary device. Hopefully, relocating or deleting the file will prevent the error from occurring again.

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
<li><a href="https://facebook-video-files.techidaily.com/new-enrich-your-video-narratives-with-background-melodies-on-fb-for-2024/"><u>[New] Enrich Your Video Narratives with Background Melodies on FB for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-top-time-lapse-techniques-and-tools-5/"><u>[New] In 2024, Top Time-Lapse Techniques & Tools #5</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-pixelation-portraiture-sketching-a-playful-virtual-emblem/"><u>[New] Pixelation Portraiture  Sketching a Playful Virtual Emblem</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-ultimate-asus-display-a-journey-through-precision-and-color/"><u>[New] The Ultimate ASUS Display  A Journey Through Precision and Color</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-tips-for-kickstarting-a-social-philanthropy-blitz/"><u>[New] Tips for Kickstarting a Social Philanthropy Blitz</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-exploring-the-authenticity-of-visual-identity-sharing-on-instagram/"><u>[Updated] 2024 Approved  Exploring the Authenticity of Visual Identity Sharing on Instagram</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-finding-and-following-leading-biz-channels-online/"><u>[Updated] 2024 Approved  Finding and Following Leading Biz Channels Online</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-elevate-viewing-experience-enable-av1-on-youtube-for-2024/"><u>[Updated] Elevate Viewing Experience – Enable AV1 on YouTube for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-staying-within-the-limits-key-youtube-policies/"><u>[Updated] In 2024, Staying Within the Limits  Key YouTube Policies</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-peek-into-past-posts-panel/"><u>[Updated] Peek Into Past Posts Panel</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-fundamentals-of-hue-adjustments-in-photoshop/"><u>2024 Approved  Fundamentals of Hue Adjustments in Photoshop</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-mastering-stardews-core-principles-and-secrets-with-special-emphasis-on-ginger-island/"><u>2024 Approved  Mastering Stardew's Core Principles and Secrets, With Special Emphasis on Ginger Island</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-tecno-spark-10-pro-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Tecno Spark 10 Pro</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/biography-breakthroughs-101-expert-tips-and-tricks-for-facebook-biographers/"><u>Biography Breakthroughs  101 Expert Tips and Tricks for Facebook Biographers</u></a></li>
<li><a href="https://change-location.techidaily.com/can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-vivo-y36-drfone-by-drfone-virtual-android/"><u>Can I use iTools gpx file to catch the rare Pokemon On Vivo Y36 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-context-menu-for-a-cleaner-win-11-experience/"><u>Customize Your Context Menu for a Cleaner Win 11 Experience</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-dismantling-error-0x80246007-in-w10w11/"><u>Deciphering and Dismantling Error 0X80246007 in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/differences-spotlighted-microsoft-account-vs-non-microsoft-windows-logins/"><u>Differences Spotlighted: Microsoft Account vs Non-Microsoft Windows Logins</u></a></li>
<li><a href="https://win11.techidaily.com/discover-file-metrics-in-windows-with-easy-powershell-scripts/"><u>Discover File Metrics in Windows With Easy PowerShell Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/discovering-the-magic-in-w11s-moment-22h2-update/"><u>Discovering the Magic in W11’s Moment #22H2 Update</u></a></li>
<li><a href="https://techtrends.techidaily.com/elevate-your-gaming-experience-expert-tips-for-achieving-120fps-on-ps5/"><u>Elevate Your Gaming Experience: Expert Tips for Achieving 120FPS on PS5</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-ui-quality-with-dpi-tuning/"><u>Elevating UI Quality with DPI Tuning</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-correcting-discord-set-up-issues-on-win-1011/"><u>Guide to Correcting Discord Set-Up Issues on Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-common-rainmeter-issues-on-windows/"><u>How to Fix Common Rainmeter Issues on Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-pokemon-go-joystick-on-vivo-x-flip-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Vivo X Flip? | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-seamlessly-embedding-youtube-subtitles-an-easy-to-follow-guide/"><u>In 2024, Seamlessly Embedding YouTube Subtitles  An Easy-to-Follow Guide</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-the-weave-of-wisdom-mastering-looms-tech/"><u>In 2024, The Weave of Wisdom  Mastering Loom's Tech</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-unleash-the-power-of-your-mi-11s-screen-recording-features/"><u>In 2024, Unleash the Power of Your Mi 11'S Screen Recording Features</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-d3d11-errors-on-windows-11/"><u>Mastering the Art of Fixing D3D11 Errors on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-stopping-self-generating-chromium-tabs/"><u>Mastering the Art of Stopping Self-Generating Chromium Tabs</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-oppo-reno-10-pro-5g-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Oppo Reno 10 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-your-roadmap-to-printer-success-in-windows-11/"><u>Quick-Fix Guide: Your Roadmap to Printer Success in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/recovering-from-frozen-windows-itunes-a-step-by-step-approach/"><u>Recovering From Frozen Windows iTunes: A Step-by-Step Approach</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-your-window-experience-through-shortcuts/"><u>Revolutionize Your Window Experience Through Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-inclusion-of-emoji-15-in-windows-11-systems/"><u>Seamless Inclusion of Emoji 15 in Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/swift-and-simple-fixes-conquer-winerror-740-on-winos/"><u>Swift and Simple Fixes: Conquer WinError 740 on WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/the-subtle-art-of-hidden-storage-in-windows-1110/"><u>The Subtle Art of Hidden Storage in Windows 11/10</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/top-5-tecno-spark-go-2023-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Tecno Spark Go (2023) Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://win11.techidaily.com/top-7-strategies-for-successful-folders-management-in-win-11/"><u>Top 7 Strategies for Successful Folders Management in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-cooperative-touchscreen-actions-in-windows/"><u>Troubleshooting Non-Cooperative Touchscreen Actions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-update-failure-code-0x80246007-on-1011/"><u>Troubleshooting: Windows Update Failure Code 0X80246007 on 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-ai-in-windows-11-the-co-pilot-effect/"><u>Understanding AI in Windows 11: The Co-Pilot Effect</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-roblox-error-403-on-windows/"><u>Unraveling Roblox Error 403 on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/virtual-box-upgrade-unleashed-migrating-to-version-70-on-windows-11-pcs/"><u>Virtual Box Upgrade Unleashed: Migrating to Version 7.0 on Windows 11 PCs</u></a></li>
</ul></div>
