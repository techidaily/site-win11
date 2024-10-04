---
title: How to Fix the Disk Defragmenter Not Working in Windows
date: 2024-10-02T16:44:13.909Z
updated: 2024-10-04T02:49:44.405Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the Disk Defragmenter Not Working in Windows
excerpt: This Article Describes How to Fix the Disk Defragmenter Not Working in Windows
keywords: Fixing Disc Defrag Errors,Troubleshoot Window Defrag,Resolve Defrag Issue Win,Stop Windows Disk Failure,Correcting Defrag Not Working,Remedy Windows Fragmentation,Addressing Defrag Problems
thumbnail: https://thmb.techidaily.com/7dd28955380e8f076f3116cabc92fc969f652f83985c018ac1bb6ff108bf9534.jpg
---

## How to Fix the Disk Defragmenter Not Working in Windows

 The Disk Defragmenter tool is a Windows user's best friend. This tool fixes fragmentation issues so that your hard drive runs smoother, but it itself sometimes comes across problems of its own. If you're having trouble with your disk defragmenter, there are a few things you can do to resolve the problem.

 In this article, you will learn how to fix the Disk Defragmenter so it works properly again.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is the Disk Defragmenter? Why Does It Stop Working?

 The Disk Defragmenter tool rearranges files on your hard drive so that they are stored in a contiguous manner. This helps to improve file access speed and overall system performance. Disk fragmentation can occur over time as you add, remove, and modify files on your hard drive.

 Although a disk defragmenter is an important tool for keeping your computer running smoothly, sometimes it does not work as it should. Here are a few things that can cause the disk defragmenter to stop working:

1. The tool won't work if you have a solid-state drive (SSD). SSDs don't need to be defragmented because they don't have the same type of moving parts that traditional hard drives do.
2. Another possibility is that you have a virus or malware on your computer that's interfering with the disk defragmenter. You can try running a virus scan to see if that fixes the problem.
3. Corrupt system files can also cause the service to malfunction. In such a case, it may be worthwhile running an SFC (System File Checker) scan as a way to diagnose the problem.

 Now we know what causes the Disk Defragmenter to stop working, it's time to look at some solutions that may help you fix the problem.

## 1\. Check Disk Defragmenter's Status

 If your computer is running slowly, one potential reason could be that the Disk Defragmenter service is not running properly. This service helps to optimize your hard drive by rearranging files so that they can be read more quickly and efficiently.

 To check if the Disk Defragmenter service is running properly, follow the steps:

1. Open the Services app (see[ways to open the Services app on Windows](https://www.makeuseof.com/windows-11-open-services-app/) ).
2. Scroll down to the "Optimise drives" service and double-click on it.
3. Click on the drop-down menu and set the Start type to "Manual."
4. Make sure the Service status is "Running." If it is not, then click on**Start** to run it.  
![Set Optimise drives Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Set-Optimise-drives-Properties.jpg)
5. Click**Apply > OK** to save it.

 After making the above changes, check if it solves the problem. If not, move on to the next solution.

## 2\. Run the System File Checker tool

 Another way to fix your disk defragmenter is to run the System File Checker tool. This tool will scan all of your system files and replace any that are corrupt or missing.

To run the System File Checker, follow these steps:

1. Press**Win + X** on your keyboard to open the Power User menu.
2. Select the**Run** option from the menu list.
3. In the Run command dialog box, type "cmd" and press**Ctrl + Shift + Enter** at the same time.
4. When UAC appears on the screen, select**Yes** to approve administrator access.
5. Once you're in the Command Prompt window, type "sfc /scannow", and press**Enter** .

 It may take a while for the scan to complete, so be patient. Once the scan is complete, restart your computer and try running Disk Defragmenter again. It should now work properly.

![SFC and DISM Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/SFC-and-DISM-Scan.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094418/7443" target="_top" id="2094418">
  <img src="//a.impactradius-go.com/display-ad/7443-2094418" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094418/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you're still having trouble with your Disk Defragmenter tool after running an SFC scan, you may need to use the DISM utility. To do this, open the Command Prompt as an administrator and run the below command line:

`DISM /Online /Cleanup-Image /ScanHealth\nDism.exe /online /cleanup-image /restorehealth`

 Once the scan is complete, restart your computer and try defragmenting again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135351/19272" target="_top" id="2135351">
  <img src="//a.impactradius-go.com/display-ad/19272-2135351" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Run the CHKDSK Utility

 If your computer's Disk Defragmenter is still not working, you can try[running the CHKDSK utility](http://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) . This is a computer program designed to check the integrity of your hard drive, identify errors, and fix them.

To run the CHKDSK utility, follow the below steps:

1. Press the Windows key and search for "Command Prompt".
2. Right-click on the search result and select**Run as administrator** .
3. Click**Yes** if UAC prompts on your computer screen. This will open a Command Prompt with admin access.  
![Run chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-chkdsk-command.jpg)
4. When you're in Command Prompt, type the following command and press Enter:  
`chkdsk C: /f`

 In the command above,**"C:"** represents your drive, so you should replace it with the letter that refers to your drive.

 Once the scanning process is completed, and you have been informed that your drive has been scanned, try to defragment it again.

 As it turns out, it may take several minutes for the scan to complete, depending on the size of your partition and sometimes it seems to get stuck. However, you should let it complete its task uninterrupted.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037355/7443" target="_top" id="2037355">
  <img src="//a.impactradius-go.com/display-ad/7443-2037355" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037355/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Close All Third-Party Applications

 Some third-party applications may interfere with Disk Defragmenter if they are running. In such a case, close all third-party programs and see if that helps the defragmenter to run properly.

 If you close all active windows and find that the defragmenter is still having issues, there might be a background process interfering with it. As such, you can try ending some third-party processes and see if that fixes it.

1. Press**Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
2. On the Processes tab, find a non-essential third-party service and right-click on it.
3. Then select**End task** from the context menu.  
![Close Programs Via Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Close-Programs-Via-Task-Manager.jpg)

 After closing one, check if the disk defragmenter works again. If it does, the service you just closed is the culprit. Now you can either update, re-install, or even uninstall the problematic app so it stops interfering with Disk Defragmenter.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148637/16836" target="_top" id="2148637">
  <img src="//a.impactradius-go.com/display-ad/16836-2148637" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148637/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fixing Windows Disk Defragmenter's Opening Issues

 Disk defragmentation can improve the situation by rearranging files so that they can be evenly distributed throughout the drive. However, sometimes the Disk Defragmenter tool doesn't work as expected. If you encounter this problem, the methods described above should help you resolve it.

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
<li><a href="https://facebook-record-videos.techidaily.com/new-top-tricks-in-sports-video-production/"><u>[New] Top Tricks in Sports Video Production</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-the-blueprint-strategies-to-profit-from-youtube-adsense/"><u>[Updated] 2024 Approved The Blueprint Strategies To Profit From YouTube AdSense</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-flattening-lines-easy-curve-transformation/"><u>2024 Approved Flattening Lines Easy Curve Transformation</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-tales-that-echo-through-time-top-8-halls-for-storytellers/"><u>2024 Approved Tales That Echo Through Time Top 8 Halls for Storytellers</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/android-call-history-recovery-recover-deleted-call-logs-from-x50-gt-by-fonelab-android-recover-call-logs/"><u>Android Call History Recovery - recover deleted call logs from X50 GT</u></a></li>
<li><a href="https://win-dash.techidaily.com/beyond-solutions-how-to-resolve-driver-issues-for-the-asus-pce-ac56-on-windows-7811/"><u>Beyond Solutions: How to Resolve Driver Issues for the ASUS PCE-AC56 on Windows 7/8/11</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chagpts-side-hustle-guide-profitability-in-focus/"><u>ChaGPT's Side Hustle Guide: Profitability in Focus</u></a></li>
<li><a href="https://win11.techidaily.com/comprehending-windows-11s-configuration-options/"><u>Comprehending Windows 11'S Configuration Options</u></a></li>
<li><a href="https://win11.techidaily.com/custom-fn-key-roles-win-10-and-11-guide/"><u>Custom FN Key Roles: Win 10 & 11 Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-oppo-a78-5g-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Oppo A78 5G Quickly? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-efficiently-control-windows-post-dim-display/"><u>Navigate Efficiently: Control Windows Post-Dim Display</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/strategies-to-leverage-youtubes-cc-licensing/"><u>Strategies to Leverage YouTube's CC Licensing</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-your-win11-connectivity-9-remarkable-tips-to-try/"><u>Supercharge Your Win11 Connectivity: 9 Remarkable Tips to Try</u></a></li>
<li><a href="https://win11.techidaily.com/win-xp-resurrecting-missing-mmc-snap-ins/"><u>Win XP: Resurrecting Missing MMC Snap-Ins</u></a></li>
<li><a href="https://win11.techidaily.com/win11-excellence-key-gratuitous-software-recommendations/"><u>Win11 Excellence: Key Gratuitous Software Recommendations</u></a></li>
<li><a href="https://win11.techidaily.com/windows-device-mgmt-camera-not-displayed-heres-how/"><u>Windows Device Mgmt: Camera Not Displayed? Here's How</u></a></li>
</ul></div>

