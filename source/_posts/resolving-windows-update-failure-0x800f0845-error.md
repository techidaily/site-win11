---
title: "Resolving Windows Update Failure: 0X800F0845 Error"
date: 2024-08-15T23:59:54.514Z
updated: 2024-08-16T23:59:54.514Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resolving Windows Update Failure: 0X800F0845 Error"
excerpt: "This Article Describes Resolving Windows Update Failure: 0X800F0845 Error"
keywords: WinUpdateErrorSolution,Fix0X800F0845Windows,XFixWindowsUpdate,WindowsFix0XF0845,UpdateFailure0X800F,0X800FWindowsCorrect,ErrorResolveWinUpd
thumbnail: https://thmb.techidaily.com/74722f9cb9d89019ce2bd2f1c80c266bfc2adc6c2152da5539a4a5d5cb3e57e3.jpg
---

## Resolving Windows Update Failure: 0X800F0845 Error

 Windows Update brings new features to your PC while installing important security updates and bug fixes. So it's vital to keep your system updated to work and play hassle-free on Windows.

 However, some unexpected errors occur, resulting in updates failing to install on your system. And 0x800f0845 is one such error.

 But you can get past the 0x800f0845 error and continue to install essential updates by trying the following fixes.

## What Is the Windows Update 0x800f0845 Error?

 0x800f0845 is an error that mostly occurs while installing cumulative updates on your Windows PC. You may experience this update error if Windows components and services are corrupted or if there are damaged or missing system files. Sometimes, this error happens by the interactions of third-party apps with the system apps.

 You may not come to know of the error while updating, as Windows will appear to be updating normally with messages of the updates installing—such as**Updates are underway. Please keep your computer on** .

 However, just before your PC reboots, the following message on your computer screen may appear: **Something didn't go as planned. No need to worry—undoing changes. Please keep your computer on** . This message indicates a problem with the update. When your computer restarts, the cumulative update would have failed to install.

 You can check for the same by going to**Settings > Windows Update** and then clicking**Update history** . In**Update history** , you will get the message that the cumulative update has failed to install with the error code**0x800f0845** like the screenshot below.

![0x800f0845 Error in Windows Update History](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/0x800f0845-error-update-history.jpg)

 So what can you do now? Cumulative updates are quality updates, so these must be installed. Fortunately, as there are ways to get past the 0x800f0845 error and install the failed updates.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## 1\. Run the Windows Update Troubleshooter

 It's always better to try fixing Windows update errors first by using the Windows Update Troubleshooter. It scans your PC for problems, attempts to resolve them, and then applies the fixes.

1. Right-click the**Windows icon** on the taskbar and select**Settings** . Or use the [many ways to open Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. On the left pane in**Settings** , click**System** . On the**System** page, click**Troubleshoot** on the right pane.
3. In the**Troubleshoot** page, select**Other troubleshooters** .  
![Select Other Trouble-shooters in Troubleshoot Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/troubleshoot-other-trouble-shooters.jpg)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Then click**Run** on the**Windows Update** troubleshooter.  
![Run Windows Update Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-windows-update-troubleshooter.jpg)

 The Windows Update troubleshooter will automatically run its scans to diagnose problems. After troubleshooting completes, you'll get the message that changes have been made to your system and you should try attempting the tasks you were doing earlier.

![Windows Update Troubleshooting Complete Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-troubleshooting-complete.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->

 So close the troubleshooter and restart your computer. Then try updating Windows again and check if the failed update gets installed.

## 2\. Temporarily Disable Your Antivirus Software

 Sometimes, third-party antivirus installed on your PC may cause problems when you're updating Windows. So try temporarily disabling it and then installing updates.

 Your antivirus may have options to disable it temporarily. Or right-click on the Windows icon on the taskbar and select**Task Manager** .

 In**Task Manager** , click the**Startup** tab and look for your antivirus software. Then, right-click on it and choose**Disable** .

Try updating Windows now and see if the update gets installed.

## 3\. Run the System File Checker and the DISM Tool

 Corrupted Windows system files could also be the cause of the 0x800f0845 error. To scan, repair, and replace such damaged files, run the System File Checker or SFC scan.

 And if the SFC doesn't work properly, and can’t repair your system files, you should run the DISM or Deployment Image Servicing and Management tool. DISM is a command-line tool that can be used to service and repair Windows images, including those used for Windows Recovery and Windows Setup.

 To know how to run the SFC and DSIM, you can explore our guide on [CHKSDK, SFC, and DISM, and how they work](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) .

 These scans will take a few minutes to run. If the 0x800f0845 error was caused by corrupted files, it should have been fixed. So try updating Windows again.

## 4\. Reset Windows Update Components

 Error 0x800f0845 could occur if some Windows Update components have got corrupted. You could reset Windows components to get the Windows update running fine again. Here's how:

[Open Windows Terminal](https://www.makeuseof.com/windows-11-open-windows-terminal/) using one of the many ways. Or type**Windows Terminal** in**Windows Search** . Then, right-click**Windows Terminal** under**Best match** and select**Run as administrator.**

 First, you need to stop the update services. In the Windows Terminal window, type the following four commands one by one, making sure that you press**enter** after each command:

`net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc`

 Then to set up a new SoftwareDistribution folder, you need to rename it. So enter the following command and press**enter** :

`Ren %systemroot%\SoftwareDistribution SoftwareDistribution.old`

 Next, rename the catroot2 folder for Windows to set up a new one. Type the following command and press**enter** :

`Ren %systemroot%\System32\catroot2 catroot2.old`

 Finally, you need to restart the stopped services. Type the following four commands one after the other, while pressing**enter** after each command:

`net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`

 Once you have run all the commands, the update error should have got fixed. Restart your PC and try installing the updates again.

## 5\. Install the Update Manually via the Microsoft Update Catalog

 What if none of the above solutions works for you? No worries, just install the update manually from the Microsoft Update Catalog.

1. Open your browser to search for and visit the [Microsoft Update Catalog website](https://www.catalog.update.microsoft.com/Home.aspx) .
2. Copy the number of the cumulative update or any other update that failed to install from the**Windows Update history** page. Type the update number in the**Search bar** on the**Microsoft Update Catalog** page and hit the**Search** button.  
![Search For Update On Microsoft Update Catalog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/search-on-microsoft-update-catalog.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
3. The matching updates will show up on the results page. Check the update that applies to your Windows PC—whether it is for Windows 10 or 11, and whether it is for an ARM64-based system or an x64-based system.  
![Microsoft Update Catalog Search Results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/microsoft-update-catalog-search-results.jpg)
4. To know the build of your PC, search for**About** in**Windows Search** and click on**About your PC** under**Best match** . In the**About** page, under**Device specifications** , check your**System type** to know whether it is x64-based or another.  
![Device Specifications in About Your PC Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/screenshot-10065.jpg)  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
 Select the update that matches your system in Microsoft Update Catalog and click the**Download** button.
5. The**Download** page will open with the file download link. Click on the link to download the update.  
![Download Update From Microsoft Update Catalog Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/download-update-from-link.jpg)
6. Double-click on the downloaded file to open the**Windows Update Standalone Installer** and click**Yes** when prompted to download the update.  
![Windows Update Standalone Installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-standalone-installer.jpg)  
 The update will begin installing and this could take some time.  
![Cumulative Update Installation in Progress](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/cumulative-update-installing-progress.jpg)  
 Finally, the**Installation complete** window will appear.  
![Click Restart Now to Complete Installation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restart-now-to-complete-installation.jpg)
<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
7. Just click the**Restart Now** button to complete the installation.
8. After your PC restarts, go to the**Windows Update history** page.  
![Cumulative Update Successfully Installed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/cumulative-update-successfully-installed.jpg)  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
 The update that failed to install would have been successfully installed—as you can see in the screenshot above, the KB5023706 update was installed.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## Stay Updated for a Secure and Smooth Windows Experience

 Update errors like 0x800fo845 can be annoying, especially when you've spent considerable time on an update that fails to install. Try the fixes discussed above to install important updates and enjoy a smooth, secure, and hassle-free Windows experience.


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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-experts-guide-to-minecraft-3d-shapes-crafting/"><u>[New] 2024 Approved  Expert's Guide to Minecraft 3D Shapes Crafting</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-expert-analysis-of-the-latest-video-show-app-24-release/"><u>[New] Expert Analysis of the Latest Video Show App '24 Release</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-mediamerge-creating-slideshows-on-macsierra-for-2024/"><u>[New] MediaMerge  Creating Slideshows on MacSierra for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/t-treasure-hunt-accessing-previously-deleted-content/"><u>[New] YT Treasure Hunt  Accessing Previously Deleted Content</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-your-secure-video-chatting-needs-met-top-10-safe-and-free-applications-on-smart-devices/"><u>[Updated] 2024 Approved  Your Secure Video Chatting Needs Met  Top 10 Safe & Free Applications on Smart Devices</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-making-photographs-larger-without-losing-quality/"><u>[Updated] Making Photographs Larger Without Losing Quality</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-unlock-online-visibility-with-essential-vids-tools/"><u>[Updated] Unlock Online Visibility with Essential Vids' Tools</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-epic-review-and-substitute-guidance/"><u>2024 Approved  Epic Review & Substitute Guidance</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-shoppers-insight-making-an-informed-choice-on-your-next-360camera/"><u>2024 Approved  Shopper's Insight  Making an Informed Choice on Your Next 360Camera</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-social-media-savvy-crafting-your-best-self-with-top-tips-for-bios/"><u>2024 Approved  Social Media Savvy  Crafting Your Best Self with Top Tips for Bios</u></a></li>
<li><a href="https://win11.techidaily.com/5-superior-windows-platform-bittorrent-apps/"><u>5 Superior Windows Platform BitTorrent Apps</u></a></li>
<li><a href="https://tech-hub.techidaily.com/6-best-chatgpt-extensions-for-vs-code/"><u>6 Best ChatGPT Extensions for VS Code</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-fix-the-windows-11-mail-app-when-it-shows-html-code-for-emails/"><u>6 Ways to Fix the Windows 11 Mail App When It Shows HTML Code for Emails</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-deleting-files-without-a-click-in-windows/"><u>A Step-by-Step Guide to Deleting Files Without a Click in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-network-drives-through-explorer-pane/"><u>Accessing Network Drives Through Explorer Pane</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-0x800704b3-network-hurdles-in-win1011/"><u>Addressing 0X800704B3 Network Hurdles in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-incorrect-profile-errors-windows-1011-guide/"><u>Addressing Incorrect Profile Errors: Windows 10/11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-mfc71udll-disappearance-on-pcs/"><u>Addressing Mfc71u.dll Disappearance on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-password-recall-issue-on-w10w11/"><u>Addressing the “Password Recall Issue on W10/W11”</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-usb-recognition-failures-in-win-11/"><u>Addressing USB Recognition Failures in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-update-problem-code-0x8024800c/"><u>Addressing Windows Update Problem: Code 0X8024800C</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-your-cursors-cadence-turn-off-acceleration-win-11/"><u>Adjusting Your Cursor's Cadence: Turn Off Acceleration Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-techniques-for-managing-packages-via-winget-on-win11/"><u>Advanced Techniques for Managing Packages via Winget on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/assisting-users-with-erratic-swipes-on-windows-systems/"><u>Assisting Users with Erratic Swipes on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/averting-the-def5-blunder-in-onedrive-w11-issues/"><u>Averting the Def5 Blunder in OneDrive W11 Issues</u></a></li>
<li><a href="https://win11.techidaily.com/banish-flickering-screens-a-windows-11-guide/"><u>Banish Flickering Screens: A Windows 11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-zoom-crashes-windows-error-1132-fix/"><u>Banishing Zoom Crashes: Windows Error 1132 Fix</u></a></li>
<li><a href="https://win11.techidaily.com/blackview-minipc-storage-space-speeds-still-sparse/"><u>Blackview MiniPC: Storage Space - Speeds Still Sparse</u></a></li>
<li><a href="https://win11.techidaily.com/blending-email-services-adding-gmail-to-the-outlook-app-in-windows/"><u>Blending Email Services: Adding Gmail to the Outlook App in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/boost-file-navigation-use-box-for-selection-in-win11/"><u>Boost File Navigation: Use Box for Selection in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-note-visibility-for-effective-productivity/"><u>Boost Note Visibility for Effective Productivity</u></a></li>
<li><a href="https://win-blog.techidaily.com/clearing-up-the-out-of-video-memory-problem-in-fortnite-effective-strategies/"><u>Clearing Up the 'Out of Video Memory' Problem in Fortnite: Effective Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/1719359813770-cloud-connected-computers-integrating-files-with-dropboxgoogledrive-in-c/"><u>Cloud-Connected Computers: Integrating Files with Dropbox/GoogleDrive in C</u></a></li>
<li><a href="https://win11.techidaily.com/1719362972502-enhance-printer-functionality-in-windows-11-today/"><u>Enhance Printer Functionality in Windows 11 Today!</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-itel-s23-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Itel S23 | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/greater-plant-growth-and-yield-as-a-result-of-better-nutrition/"><u>Greater Plant Growth and Yield as a Result of Better Nutrition</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-ipad-or-iphone-12-mini-stuck-on-activation-lock-by-drfone-ios/"><u>How to Fix iPad or iPhone 12 mini Stuck On Activation Lock?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-oppo-k11-5g-drfone-by-drfone-android/"><u>In 2024, How To Use Allshare Cast To Turn On Screen Mirroring On Oppo K11 5G | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-surrender-to-serenity-top-10-game-guides/"><u>In 2024, Surrender to Serenity  Top 10 Game Guides</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-unleash-creativity-a-comprehensive-guide-to-instagram-video-upload-via-desktop/"><u>In 2024, Unleash Creativity  A Comprehensive Guide to Instagram Video Upload via Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/1719218034374-provide-examples-from-real-life-where-understanding-another-cultures-perspective-could-lead-to-better-communication-and-relationships/"><u>Provide Examples From Real Life Where Understanding Another Culture's Perspective Could Lead to Better Communication and Relationships</u></a></li>
<li><a href="https://win11.techidaily.com/1719330298923-self-host-your-local-free-windows-based-chatgpt-clone-using-gpt4all/"><u>Self-Host Your Local, FREE Windows-Based ChatGPT Clone Using GPT4All.</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-recent-calls-back-from-a60-by-fonelab-android-recover-call-logs/"><u>Simple ways to get recent calls back from A60</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/solving-the-puzzle-of-non-responsive-apple-watch-cellular-service/"><u>Solving the Puzzle of Non-Responsive Apple Watch Cellular Service</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-poco-m6-pro-5g-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Poco M6 Pro 5G Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
</ul></div>
