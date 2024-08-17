---
title: Skimming Through Complex Windows Update Issues with Error 0X800736CC
date: 2024-08-16T00:25:34.904Z
updated: 2024-08-17T00:25:34.904Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Skimming Through Complex Windows Update Issues with Error 0X800736CC
excerpt: This Article Describes Skimming Through Complex Windows Update Issues with Error 0X800736CC
keywords: WinUpdateIssueError,ErrorCode0X36CC,WindowsUpdateError,UpdaterTroubleshoot,FixWindows0X36CC,UpdateErrorSolution,SkimmingWindowsUpdate
thumbnail: https://thmb.techidaily.com/0e07053ee64fa15ad5d79e86651cfe492e77f4718babb9ab9f4f477093729fe7.jpg
---

## Skimming Through Complex Windows Update Issues with Error 0X800736CC

 Windows Update keeps your computer safe and secure with the latest security patches. However, you might encounter errors while installing these updates, like 0x800736cc. This error code stops you from deploying critical security updates, leaving your computer vulnerable. In this guide, we’ll show you some troubleshooting steps to fix this error.

## 1\. Restart Your PC

 The first thing you need to do is [restart your computer](https://www.makeuseof.com/windows-restart-methods/). Although it may seem too simplistic, you'd be surprised how often this resolves various issues. When your computer reboots, it clears temporary files and processes that could cause problems. This includes incomplete Windows updates that failed to install or encountered installation errors.

 A quick reboot can bypass the error and complete the update, so it should be your primary course of action before delving into more intricate troubleshooting methods.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Run the Windows Update Troubleshooter

 If restarting the PC doesn't work, you can use the Windows Update Troubleshooter. This built-in utility solves minor problems that prevent Windows from updating correctly.

 To run the Windows Update Troubleshooter, follow these steps:

1. Press **Win + S** to open the Windows Search bar.
2. Type in **Troubleshoot** and select **Troubleshoot Settings** from the results list.
3. On the right sidebar, click **Other troubleshooters**.  
![Other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/other-troubleshooters.jpg)
<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Under **Most frequent**, locate **Windows Update** and click **Run**.  
![Run Windows Update Troubleshooter-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-windows-update-troubleshooter-1.jpg)

 Follow the on-screen instructions to complete the troubleshooting process. It may take a few minutes for the tool to finish its job.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->
## 3\. Clear the Windows Update Cache

 Windows Update Cache stores temporary files and processes related to updates. If these files become corrupted, they can interfere with the update process and cause errors like 0x800736cc. In this case, clearing the cache can fix the problem.

 To clear the Windows Update Cache, do the following:

1. Open the Start menu.
2. Type **services.msc** in the search box and hit Enter. The Services window will open.
3. Scroll down and locate the **Windows Update** service. Then, right-click on it and select **Stop**. Doing so temporarily stops Windows Update.
4. Now, [open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and navigate to this location:  
`C:\Windows\SoftwareDistribution`
5. In the SoftwareDistribution folder, delete all files and folders. This is just temporary data, so removing it won't affect your computer.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/clear-softwaredistribution-folder.jpg)
6. After deleting the files, head back to the Services window, right-click on the **Windows Update** service, and select **Start**. This step restarts the Windows Update service.

 Now restart your computer. It will allow Windows Update to recreate cache files from scratch.

## 4\. Disable your Antivirus Temporarily

 Security software interferes with Windows Update and causes errors. To avoid this issue, [temporarily disable your security program](http://www.makeuseof.com/how-to-turn-off-windows-defender/) before running updates. Once you have disabled it, restart the computer and install the update again. If it works, it was your security software that caused the issue.

 Remember that disabling security software leaves your computer vulnerable to malware attacks, so enable it immediately.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Reset Windows Update Components

 Windows Update components include files and processes crucial to the update process. If these components become corrupted or damaged, Windows Update cannot run correctly. In this case, you must reset the components to their original state.

 Fortunately, there’s an easy way to do this. Microsoft provides a batch script called Reset Windows Update Tool that resets various Windows Update components with just a few clicks.

 To reset Windows Update components, follow these steps:

1. Click on Start and type **Notepad** in the search bar.
2. Right-click on Notepad and select **Run as administrator**.
3. If the User Account Control window pops up, click **Yes** to continue.
4. In the Notepad window, copy and paste the following code:  
`<code>net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir%  
system32  
regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll  
netsh winsock reset  
netsh winsock reset proxy  
net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`
5. The above commands form part of a script to reset Windows Update components. After you paste the code into Notepad, click **File** and select **Save as**.
6. In the Save As window, select **All files** from the drop-down menu.
7. Type **ResetWindowsUpdate.bat** as the file name and save it to your desktop.  
![Reset Windows Update Components](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reset-windows-update-components.jpg)
<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Now, you have the batch script on your desktop. Right-click on it and select **Run as administrator**.
9. When the UAC pops up, click **Yes** to grant elevated privileges.

 The script will take a few minutes to run. When it's finished, close the Command Prompt window and restart your computer. Once your computer restarts, check if the 0x800736cc error is resolved.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
## 6\. Try Generic Windows Update Fixes

 Besides the methods listed above, you can also try some generic Windows Update fixes. These methods usually work if a temporary issue or corrupted system files cause the error.

 Here are some generic Windows Update fixes you can try:

* [Repair Corrupted System Files](https://www.makeuseof.com/windows-built-in-repair-tools/) \- Run the System File Checker tool to scan and repair corrupted system files. If you need help with this, you can find detailed instructions in our [SFC guide](https://www.makeuseof.com/system-file-checker-sfc-windows/). You can also use the Deployment Image Service and Management (DISM) tool to replace broken files with healthy ones.
* [Perform a Clean Boot](https://www.makeuseof.com/clean-boot-windows-11/) \- Clean Boot can identify software conflicts causing the error. It disables all non-essential services and programs from running in the background. That way, you can isolate the problematic process and resolve the issue.
* [Manually Install the Update](https://www.makeuseof.com/update-windows-manually/) \- If Windows Update fails to install or is stuck, you can download and install it manually

## Fixing Windows Update Error 0x800736cc

 As you can see, multiple ways exist to fix the Windows Update error. We hope one of these methods has solved your problem, and you can now successfully install Windows Update. If nothing else works, you can restore your computer to a previous state or reinstall Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-zero.techidaily.com/024-approved-capture-attention-yt-imagery-and-its-dimension-magic/"><u>[New] 2024 Approved  Capture Attention  YT Imagery and Its Dimension Magic</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-embracing-the-world-one-post-at-a-time-with-insta-captions/"><u>[New] Embracing the World, One Post at a Time with Insta Captions</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-revolutionary-wearable-camera-tech/"><u>[New] Revolutionary Wearable Camera Tech</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-digital-identity-building-crafting-perfect-channel-images/"><u>[Updated] 2024 Approved  Digital Identity Building  Crafting Perfect Channel Images</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-leveraging-insta-archive-features-a-step-by-step-approach/"><u>[Updated] 2024 Approved  Leveraging Insta Archive Features  A Step-by-Step Approach</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-visual-storytelling-with-vsco-a-complete-guide/"><u>[Updated] 2024 Approved  Visual Storytelling with VSCO  A Complete Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-a-curated-selection-best-stop-motion-movies-ever-made/"><u>[Updated] A Curated Selection  Best Stop-Motion Movies Ever Made</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-banner-bliss-savor-your-complimentary-set-of-designs/"><u>[Updated] In 2024, Banner Bliss  Savor Your Complimentary Set of Designs</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-unleashing-creativity-uploading-movies-from-mmc-to-vimeo/"><u>2024 Approved  Unleashing Creativity  Uploading Movies From MMC to Vimeo</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-steam-cloud-discrepancies-in-windows/"><u>Correcting Steam Cloud Discrepancies in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/data-resilience-on-windows-embrace-daily-savings/"><u>Data Resilience on Windows: Embrace Daily Savings</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-cpu-temperatures-on-windows-11-machines/"><u>Decreasing CPU Temperatures on Windows 11 Machines</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-and-repairing-win-error-31-on-your-computer/"><u>Dissecting and Repairing WIN Error 31 on Your Computer</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-updated-intel-lan-driver-pack-for-windows-11107-systems-now/"><u>Download Updated Intel LAN Driver Pack for Windows 11/10/7 Systems Now!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easy-guide-to-downloading-and-updating-your-lenovo-display-driver/"><u>Easy Guide to Downloading & Updating Your Lenovo Display Driver</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-managing-directx-on-your-system/"><u>Efficiently Managing DirectX on Your System</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-driving-experience-the-most-effective-5-free-tools-for-pcs/"><u>Enhance Driving Experience: The Most Effective 5 Free Tools for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-adjusting-directory-displays-on-windows-11/"><u>Expert Guide to Adjusting Directory Displays on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-runtime-broker-purpose-and-impact-on-pcs/"><u>Exploring Runtime Broker: Purpose and Impact on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-system-files-top-6-access-methods/"><u>Exploring System Files: Top 6 Access Methods</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-honor-x9b-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Honor X9b | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-ms-store-failure-code-0x80073d26-on-windows-11/"><u>Fixing MS Store Failure Code 0X80073D26 on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fourfold-path-to-permanently-delete-a-disk-partition-on-windows/"><u>Fourfold Path to Permanently Delete a Disk Partition on Windows</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/nize-your-favorites-creating-custom-youtube-playlists/"><u>Harmonize Your Favorites  Creating Custom YouTube Playlists</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-come-up-with-the-best-pokemon-team-on-oppo-reno-8t-drfone-by-drfone-virtual-android/"><u>How to Come up With the Best Pokemon Team On Oppo Reno 8T? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-turn-off-games-for-you-recommendations-on-windows-11/"><u>How to Turn Off Games for You Recommendations on Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Xiaomi Redmi Note 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-unveiling-horizon-based-approaches-to-post-on-igtv/"><u>In 2024, Unveiling Horizon-Based Approaches to Post on IGTV</u></a></li>
<li><a href="https://techtrends.techidaily.com/in-depth-evaluation-of-the-latest-apple-tv-4k-series-revamped-edition/"><u>In-Depth Evaluation of the Latest Apple TV 4K Series - Revamped Edition</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-the-power-of-package-management-in-windows-11/"><u>Leveraging the Power of Package Management in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-90-degree-display-flip-techniques-and-benefits/"><u>Mastering 90-Degree Display Flip: Techniques & Benefits</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-workflow-efficiency-mastering-tab-management-in-windows-11/"><u>Maximize Workflow Efficiency: Mastering Tab Management in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-application-floods-on-windows-solving-error-0x80860010/"><u>Navigating Application Floods on Windows: Solving Error 0X80860010</u></a></li>
<li><a href="https://win11.techidaily.com/old-techs-new-lease-on-life-the-art-of-employing-windows-11-to-go-and-rufus/"><u>Old Tech's New Lease on Life: The Art of Employing Windows 11, To Go & Rufus</u></a></li>
<li><a href="https://win11.techidaily.com/quick-remedies-starting-fresh-with-explore-ui/"><u>Quick Remedies: Starting Fresh with Explore UI</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-absent-cpu-cooling-directive-in-os/"><u>Reinstating Absent CPU Cooling Directive in OS</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-unresponsive-disk-optimization-utility/"><u>Solutions for Unresponsive Disk Optimization Utility</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-restoring-disabled-windows-sign-in-options/"><u>Steps for Restoring Disabled Windows Sign-In Options</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-eliminate-discord-javascript-dilemma-on-windows-11-pcs/"><u>Steps to Eliminate Discord Javascript Dilemma on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-endless-popups-of-edge-symbols/"><u>Stopping Endless Popups of Edge Symbols</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-steam-file-disconnect-issue-in-windows-settings/"><u>Tackling Steam File Disconnect Issue in Windows Settings</u></a></li>
<li><a href="https://win11.techidaily.com/the-6-best-tools-to-stress-test-your-gpu-on-windows/"><u>The 6 Best Tools to Stress Test Your GPU on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-gamers-manual-to-prevent-data-loss-with-epic-backup/"><u>The Gamer's Manual to Prevent Data Loss with Epic Backup</u></a></li>
<li><a href="https://win11.techidaily.com/top-6-windows-11-compatible-android-apps-worth-your-time/"><u>Top 6 Windows 11 Compatible Android Apps Worth Your Time</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-ancient-directx-software-using-modern-dxvk-techniques/"><u>Transforming Ancient DirectX Software Using Modern DXVK Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-administrative-blockage-for-software-installations/"><u>Troubleshooting Administrative Blockage for Software Installations</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-chrome-download-failures-on-pcs/"><u>Troubleshooting Chrome Download Failures on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-perpetual-inactivity-in-windows-11s-defender-feature/"><u>Unlocking Perpetual Inactivity in Windows 11'S Defender Feature</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-11-files-how-to-correctly-handle-access-denied-errors/"><u>Unlocking Windows 11 Files: How to Correctly Handle Access Denied Errors</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-graphical-performance-for-secure-browsing-edge/"><u>Upgrading Graphical Performance for Secure Browsing Edge</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-image-scaling-find-your-perfect-size-with-these-six-tips/"><u>Windows 11 Image Scaling: Find Your Perfect Size With These Six Tips</u></a></li>
<li><a href="https://win11.techidaily.com/windows-archive-support-a-quick-guide/"><u>Windows Archive Support: A Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/windows-users-wanted-learn-backup-tricks-for-notebooks/"><u>Windows Users Wanted: Learn Backup Tricks for Notebooks</u></a></li>
<li><a href="https://win11.techidaily.com/winning-over-error-code-31-your-guide-to-restoring-online-access/"><u>Winning Over Error Code 31: Your Guide to Restoring Online Access</u></a></li>
</ul></div>
