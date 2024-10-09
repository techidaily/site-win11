---
title: Tackling Blank Spaces in the Windows 11 Search Tool
date: 2024-10-04T00:10:57.063Z
updated: 2024-10-08T21:42:02.188Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Blank Spaces in the Windows 11 Search Tool
excerpt: This Article Describes Tackling Blank Spaces in the Windows 11 Search Tool
keywords: Win11 Search Improvement,Eliminating Search Gaps,Optimize Windows 11,Enhancing Search UI,Clearing Spaces in Search Tool,Windows 11 Search Fixes,Streamlining Win11 Search
thumbnail: https://thmb.techidaily.com/ac89aae2a326978b0ae60bac11755067574f83eed6bc1f4ab82f533632f5d39e.jpg
---

## Tackling Blank Spaces in the Windows 11 Search Tool

 Most users probably utilize the Windows 11/10 search tool to find apps and files. However, some users have reported their search tools don’t display any results. Some users see a “No results found” message whenever they search. Or the search tool displays nothing except a blank white screen in other instances.

 Either way, users can’t find things with the Windows search tool when it doesn’t display results right. Is your search tool not showing results either? If that’s the case, you can fix your search tool not displaying results in Windows 11/10 with these potential resolutions.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Update Windows

 Microsoft releases a multitude of patch updates to fix Windows bugs and issues. So, it’s recommended to manually check for and download any available Windows updates for the sake of fixing the search tool. That also includes build updates for new Windows versions. Here’s how you can manually download and install Windows 11/10 updates.

1. Press the**Windows** key, and select the pinned Settings app shortcut on the Start menu that opens.
2. Select**Windows Update** along the left of Settings. In Windows 10, click**Update & Security** on Settings’ home screen.
3. Then press**Check for updates** to initiate a search. Most available updates will download and install automatically.  
![The Check for updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-check-for-updates-button.jpg)
4. If selecting**Check for updates** doesn’t automatically install everything available, click the**Download and Install** buttons for any other updates (including version 22H2).

## 2\. Run the Search Troubleshooting Tool

 Windows has troubleshooters that can fix all kinds of errors and issues. The Search and Indexing troubleshooter is the one for resolving search-related issues that occur in Windows. You may be able to fix the search tool not displaying results with that troubleshooter as follows:

1. Use one of the many ways to open Settings on Windows, then open the Setting's**System** tab.
2. Click**Troubleshoot** inside the Settings app’s**System** tab.
3. Select**Other trouble-shooters** to reach the Windows troubleshooters.
4. Press**Run** for the Search and Indexing troubleshooter.  
![The Run button for the Search and Indexing troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-run-button-for-the-search-and-indexing-troubleshooter.jpg)
5. Click the**Can't start a search or see results** checkbox, and select the troubleshooter’s**Next** option. The **Files, folders, apps, or settings don't appear in results** checkbox is also a suitable option to select for troubleshooting this issue.  
![The Search and Indexing troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-search-and-indexing-troubleshooter.jpg)

 The steps for opening the Search and Indexing troubleshooter in Windows 10’s Settings app aren’t exactly the same. Click**Update & Security** \>**Troubleshoot** in Windows 10’s Settings app. Selecting**Additional troubleshooters** will bring up the list. Then you can click**Run the troubleshooter** for Search and Indexing to open it from there.

## 3\. Select the Enhanced Search Option

 The Settings app has some search options that can affect the effectiveness of the search tool. You can set the search utility to fully search a PC by selecting an**Enhanced** option. Try selecting that option in the following steps:

1. Click**Settings** on the Start or Power User (**Win** +**X**) menu.
2. Select the**Privacy & security** tab to view navigation options for Windows permissions.
3. Click the**Searching Windows** navigation option.  
![The Search Windows navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-searching-windows-navigation-option.jpg)
4. Then select the**Enhanced** radio button.  
![The Enhanced radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-enhanced-radio-button.jpg)
5. Click the menu buttons for all excluded search folders listed below that option and select**Remove** .  
![The Remove option for excluded folders](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-remove-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151888/7443" target="_top" id="2151888">
  <img src="//a.impactradius-go.com/display-ad/7443-2151888" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151888/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Start the Windows Search Service

 The search tool won’t display results if the Windows Search service it’s based on isn’t running. So, check the Windows Search is enabled and running:

1. To access Run, press**Win** +**R** . You can also use any method in our guide on[how to open Run on Windows](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Then type**services.msc** inside the**Open** box, and select Run’s**OK** option.
3. Double-click**Windows Search** within the Services app.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-services-window2.jpg)
4. Click the drop-down menu for the**Startup type** option to select the service’s**Automatic** option.  
![The Windows Search Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-windows-search-properties-window.jpg)
5. Press**Start** in the properties window if the search service isn’t running.
6. To save the changed settings, click the**Apply** option.
7. Select**OK** to close Windows Search Properties.

 If the Windows Search service is already running, try restarting it. Select the**Stop** option for Windows Search. Wait a few minutes, and click the**Start** button for the service to restart it.

## 5\. Run a Scan With the SFC Tool

 Microsoft recommends users run the System File Checker (SFC) tool when Windows functions aren’t working right. In this case, the search function isn’t displaying results, which could be because of corrupted Windows files on your PC. This is how you can start an SFC scan:

1. Launch the Run dialogue box as above, and enter**cmd** inside its**Open** box.
2. Press the**Ctrl** +**Shift** +**Enter** key combination to open Command Prompt with admin permissions.
3. First, run an image scan by entering this command text and pressing**Return** :  
`DISM.exe /Online /Cleanup-image /Restorehealth`
4. Then start the SFC scan by executing the following command:  
`sfc /scannow`  
![The SFC scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-sfc-scan-command.jpg)
5. Wait for the SFC tool to show a Windows Resource Protection scan outcome.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151859/7443" target="_top" id="2151859">
  <img src="//a.impactradius-go.com/display-ad/7443-2151859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151859/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134243/18498" target="_top" id="2134243">
  <img src="//a.impactradius-go.com/display-ad/18498-2134243" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134243/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Rebuild the Search Tool’s Index

 A corrupted or outdated search index database is another potential cause for the search tool not displaying results. In this case, you may need to select to rebuild the search index. Doing so will wipe the current index’s content and restart the indexing. These are the steps for rebuilding the search index in Windows:

1. To open Control Panel, bring up Run first. Type**Control Panel** into Run and click**OK** . See[how to open the Control Panel in Windows 11](https://www.makeuseof.com/windows-11-open-control-panel/) for more methods.
2. Select**Large icons** on Control Panel’s**View by** menu.  
![The Large icons option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-large-icons-button.jpg)
3. Click**Indexing Options** to view that applet.

<!-- affiliate ads begin -->
<span id="701707">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/701707.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/7443-701707">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/701707.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fappsumo.8odi.net%2Fc%2F5597632%2F701707%2F7443'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/701707/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Select**Advanced** in the Indexing Options window.
5. Click**Rebuild** in the Index**Settings** tab.  
![The Rebuild button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-rebuild-option.jpg)
6. Wait for the rebuilding to finish.
7. Select**OK** \>**Close** to exit the indexing applet.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027176/19272" target="_top" id="2027176">
  <img src="//a.impactradius-go.com/display-ad/19272-2027176" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027176/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Reinstall Cortana

 Cortana is an app that’s closely connected with the Windows search tool. Some users have been able to fix the search tool not displaying results by reinstalling that app. You can reinstall Cortana in PowerShell like this:

1. Press Task Manager’s**Ctrl** +**Shift** +**Esc** keyboard shortcut.
2. Click**File** and the**Run new task** option.
3. Type**PowerShell** inside the Create new task window’s**Open** box.
4. Select the checkbox for the**Create new task with administrative privileges** option.
5. Then select**OK** to access PowerShell.
6. Input the following command for reinstalling Cortana:  
`Get-AppXPackage -Name Microsoft.Windows.Cortana | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The command for reinstalling Cortana](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-reinstall-cortana-command.jpg)
7. Press**Enter** to execute the PowerShell command.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948876/19272" target="_top" id="1948876">
  <img src="//a.impactradius-go.com/display-ad/19272-1948876" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948876/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Reset Windows

 If nothing else fixes the search tool not showing results, this is the last-resort resolution to try. Resetting Windows reinstalls the platform by restoring it to a default configuration, which will most likely be enough to resolve this search issue. However, you’ll need to reinstall any software you previously installed after a reset.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-reset-this-pc-tool.jpg)

 You can perform a reset with the Reset this PC recovery tool. That utility includes an option for preserving user files. Our guide on[how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) includes instructions for applying this resolution with that tool.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144299/7443" target="_top" id="2144299">
  <img src="//a.impactradius-go.com/display-ad/7443-2144299" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144299/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Find Apps and Files Again With the Windows Search Tool

 So, that’s how you can get your Windows search tool fixed when it’s not showing results. We recommend applying the suggested resolutions in the order specified above. There’s a reasonable chance one will sort your search utility out so that you can find the apps and files you’re looking for with it again.

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
<li><a href="https://extra-lessons.techidaily.com/new-achieving-flawless-photos-with-size-tweaks-on-ios/"><u>[New] Achieving Flawless Photos with Size Tweaks on iOS</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-experts-choice-11-premium-video-extractors-for-2024/"><u>[Updated] Expert's Choice 11 Premium Video Extractors for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-sizing-up-how-to-make-videos-work-in-instagram-bests-for-2024/"><u>[Updated] Sizing Up How to Make Videos Work in Instagram Bests for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-breakpoint-failed-on-your-windows-system/"><u>Addressing 'Breakpoint Failed' On Your Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-techniques-for-capturing-uac-alerts/"><u>Advanced Techniques for Capturing UAC Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/audioscape-refresh-on-windows-the-driver-upgrade-path/"><u>Audioscape Refresh on Windows: The Driver Upgrade Path</u></a></li>
<li><a href="https://win11.techidaily.com/basking-in-low-light-the-art-of-dark-modes-in-paint/"><u>Basking in Low Light: The Art of Dark Modes in Paint</u></a></li>
<li><a href="https://win11.techidaily.com/bootable-windows-11-usb-setup-a-quick-easy-guide-to-3-methods/"><u>Bootable Windows 11 USB Setup: A Quick, Easy Guide to 3 Methods</u></a></li>
<li><a href="https://solve-news.techidaily.com/descubra-el-arte-perfecto-de-grabar-su-pantalla-con-acompanamiento-de-voz-un-manual-integral-para-quicktime/"><u>Descubra El Arte Perfecto De Grabar Su Pantalla Con Acompañamiento De Voz: Un Manual Integral Para QuickTime</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-can-we-unlock-our-tecno-camon-20-phone-screen-by-drfone-android/"><u>In 2024, How Can We Unlock Our Tecno Camon 20 Phone Screen?</u></a></li>
<li><a href="https://driver-install.techidaily.com/quick-firmware-update-intel-hd-650-sdk/"><u>Quick Firmware Update: Intel HD 650 SDK</u></a></li>
</ul></div>

