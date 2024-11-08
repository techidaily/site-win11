---
title: "Overcoming Access Issues: Win11/10's NVidia Control Panel"
date: 2024-11-07T00:08:36.755Z
updated: 2024-11-07T18:46:57.173Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overcoming Access Issues: Win11/10's NVidia Control Panel"
excerpt: "This Article Describes Overcoming Access Issues: Win11/10's NVidia Control Panel"
keywords: Win11AccessImprovement,FixWinControlPanel,NVIDIAPatchWin10,OvercomingNVDACtrl,NVDAWin11Resolve,Win10NVGAUpgrade,AccessToWindowsNVIDIA
thumbnail: https://thmb.techidaily.com/4552dd09d3248cdc2d2f0b5a8866485e28d07f676a831c6174ae4d9651da8ef0.jpg
---

## Overcoming Access Issues: Win11/10's NVidia Control Panel

 The NVIDIA Control Panel is an app included on PCs with NVIDIA GPUs with which users can change graphical settings. However, some users can’t change NVIDIA Control Panel options because of an “Access denied” error. The message of that error says, “Failed to apply selected settings to your system.”

 The “Access denied” error is mostly reported to arise for 3D settings. As a result, NVIDIA Control Panel doesn’t apply (save) the settings users select. This is how you can resolve NVIDIA Control Panel’s “Access denied” error within Windows 11/10.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the NVIDIA Control Panel as an Administrator

 Firstly, try running the NVIDIA Control Panel with elevated admin permissions, which has worked for some users. To do that, press the**Windows** logo +**S** keyboard buttons and input NVIDIA Control Panel. Right-click NVIDIA Control Panel and select**Run as administrator** .

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-as-administrator-option2.jpg)

 Should this potential fix work, then it would be better to set the NVIDIA Control Panel to always run with administrative rights. However, that UWP app is located within a protected folder. You’ll need to[take ownership of the WindowsApps folder](https://www.makeuseof.com/windows-10-11-own-folder/) to set permanent admin rights for the NVIDIA Control Panel.

 If you take ownership of the WindowsApps folder, open the NVIDIACorp subfolder to reach the NVIDIA Control Panel file. Then you’ll need to set the nvcplui.exe file to run with admin rights. Follow the steps in this how to[set an app to always run as an administrator guide](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) to set elevated permissions for the nvcplui.exe file. The path for the NVIDIA Control Panel folder is:

`C:\Program Files\WindowsApps\NVIDIACorp.NVIDIAControlPanel_8.1.964.0_x64__56jybvy8sckqj`

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1884002/19272" target="_top" id="1884002">
  <img src="//a.impactradius-go.com/display-ad/19272-1884002" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884002/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Select the Repair and Reset Options for the NVIDIA Control Panel

 The NVIDIA Control Panel app has**Repair** and**Reset** troubleshooting options you can select in Settings. Both options can be useful for fixing apps when they’re not working right. So, try selecting the**Repair** option first and then**Reset** to clear the app’s data if repairing isn’t enough. Check out this[article about resetting apps in Windows](https://www.makeuseof.com/windows-reset-app/) for details about how to apply this potential fix.

![The Repair and Reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-reset-options.jpg)

<!-- affiliate ads begin -->
<span id="1982508">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982508.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982508">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982508.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982508%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982508/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Start or Restart the NVIDIA Display Container Service

 The NVIDIA Display Container is an important GPU service that runs numerous other NVIDIA background tasks. Make sure that service is running or restart it if it is. You can start or restart NVIDIA Display Container like this:

1. Click the**Type here to search** button or the Search box on the taskbar to access the Windows file finder tool.
2. Input**services** inside the file search utility.
3. Select**Services** to launch that app.
4. Then double-click**NVIDIA Display Container** to view the settings for that service.  
![The Services app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-services-app.jpg)  
 Screenshot captured by Jack Slater - No attribution required

5. Click on the**Startup type** menu and select**Automatic** from there.
6. Next, select**Start** if the NVIDIA Display Container service is stopped. Or select**Stop** \>**Start** to restart that service.  
![The NVIDIA Display Container service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/nvidia-display-container-service.jpg)
7. Click**Apply** to set the NVIDIA Display Container service’s settings.
8. Close the NVIDIA Display Container Properties window by clicking**OK** .

## 4\. Update Your NVIDIA Graphics Card Driver

 The most widely confirmed fix for the “Access denied” error is to manually update the NVIDIA graphics driver. Thus, this is often an issue caused by outdated or faulty NVIDIA drivers. This[guide to updating NVIDIA drivers](https://www.makeuseof.com/how-update-nvidia-graphics-card-drivers-windows/) provides further details about how to apply this potential solution by manually downloading the latest GPU driver available from the NVIDIA site.

 When you’ve downloaded the latest NVIDIA driver package for your GPU, bring up the directory that includes its setup file. Double-click the NVIDIA driver package file to view its setup wizard and select the**Custom** option. Then select the**Perform a clean installation** checkbox and click**Next** to install.

![The Perform a clean installation checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/perform-a-clean-installation.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012415/19272" target="_top" id="2012415">
  <img src="//a.impactradius-go.com/display-ad/19272-2012415" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Roll Back the NVIDIA Driver

 If the “Access denied” error arises after installing a new NVIDIA driver, rolling back that driver to a previous one could be a viable potential solution. You’ll only be able to do that if the previous NVIDIA GPU driver file is still available. Our[article about rolling back drivers](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) includes guidelines for how to apply this potential fix.

 If the**Roll Back** option is grayed out, you might still be able to roll back to a previous NVIDIA graphics driver with the System Restore utility. Rolling Windows back to a restoration point restores drivers installed before the selected date. However, that will only work if your PC has a restore point that predates the driver update.

![The Roll Back Driver button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/roll-back-driver-option.jpg)

 This[post about creating and utilizing restore points](https://www.makeuseof.com/windows-11-create-restore-point/) tells you how to roll back Windows. Select a restore point that will restore the previous NVIDIA graphics driver. You can click**Scan for affected** programs in System Restore to check if a chosen restoration point will restore an NVIDIA graphics driver.

## 6\. Restore a Previous Version of the DRS Folder

 Some NVIDIA Control Panel users have said they fixed the “Access denied” error by restoring a DRS folder version backup. Note that you’ll only be able to apply this potential fix if you’ve got File History enabled or restore points saved on your PC. This is how you can restore a previous DRS folder version in Windows 11/10:

1. First, bring up File Explorer by clicking the taskbar button with the folder library icon.
2. Then click the**View** button to select a**Show** option.
3. Select the**Hidden Items** option.  
![The Hidden items checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hidden-items-option.jpg)
4. Clear Explorer’s address bar to input the following path:  
`C:\ProgramData\NVIDIA Corporation`
5. Then right-click the DRS folder and select**Properties** .
6. Click the**Previous Versions** tab.  
![The Previous Versions tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/previous-version-tab.jpg)
7. Select the most recent folder version shown in that tab.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137213/26400" target="_top" id="2137213">
  <img src="//a.impactradius-go.com/display-ad/26400-2137213" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137213/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Click the**Restore** button.

 To select the same**Hidden Items** option in Windows 10, you’ll need to open the**View** tab in Explorer. Then select the checkbox labeled**Hidden Items** on that tab.

## 7\. Turn Off the Game Bar

 It’s also recommended to turn off the Game Bar in case that’s causing any issues with the NVIDIA Control Panel. This potential resolution applies more to Windows 10 since Windows 11’s Settings app doesn’t include a specific option for disabling the Game Bar. You can turn off the Game Bar in Windows 10 like this:

1. Open Settings by clicking the cog icon on the Start menu.
2. Click the**Gaming** category.
3. Then turn off the**Enable Xbox Game Bar** option.  
![The Xbox Game Bar setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-xbox-game-bar-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118325/7443" target="_top" id="2118325">
  <img src="//a.impactradius-go.com/display-ad/7443-2118325" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118325/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Change Your Settings in the NVIDIA Control Panel Again

 Many users have resolved NVIDIA Control Panel’s “Access denied” error with the potential fixes covered above. So, the probability one of them will also fix that issue on your PC is good. With that issue sorted, you can change all settings in the NVIDIA Control Panel as required.

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
<li><a href="https://instagram-video-files.techidaily.com/new-enhance-your-images-choosing-great-border-options-on-ig/"><u>[New] Enhance Your Images Choosing Great Border Options on IG</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-pazera-free-extractor-analysis-the-ultimate-guide-to-2024-sound-freedom/"><u>[New] Pazera Free Extractor Analysis The Ultimate Guide to 2024 Sound Freedom</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/-and-methods-how-to-resize-youtube-thumbnail/"><u>[Tools & Methods] How To Resize YouTube Thumbnail</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-brightening-filmmaking-ranking-the-17-best-lights/"><u>[Updated] 2024 Approved Brightening Filmmaking Ranking the 17 Best Lights</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-error-0xc0000001-expert-tips/"><u>Correcting Windows Error 0xC0000001: Expert Tips</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/essential-wake-up-companions-choose-from-these-7-best-alarm-apps/"><u>Essential Wake-Up Companions: Choose From These 지7 Best Alarm Apps</u></a></li>
<li><a href="https://win11.techidaily.com/from-blank-screen-to-focused-workspace-reviving-hidden-panes-with-these-6-effortless-methods/"><u>From Blank Screen to Focused Workspace: Reviving Hidden Panes with These 6 Effortless Methods</u></a></li>
<li><a href="https://discover-deluxe.techidaily.com/guia-rapida-y-sencilla-para-clonar-tu-sistema-operativo-en-una-memoria-usb/"><u>Guía Rápida Y Sencilla Para Clonar Tu Sistema Operativo en Una Memoria USB</u></a></li>
<li><a href="https://win11.techidaily.com/guidance-to-rectify-microsoft-store-error-0x80072efd/"><u>Guidance to Rectify Microsoft Store Error 0X80072EFD</u></a></li>
<li><a href="https://extra-support.techidaily.com/leading-the-color-grading-revolution-with-lightrooms-best-10-luts-for-2024/"><u>Leading the Color Grading Revolution with LightRoom’s Best 10 LUTs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-windows-taskbar-showing-internet-speed/"><u>Maximizing Windows Taskbar: Showing Internet Speed</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-system-load-visualizers/"><u>Optimal System Load Visualizers</u></a></li>
<li><a href="https://win-answers.techidaily.com/quick-and-easy-ways-to-increase-your-ubisoft-connect-speed/"><u>Quick and Easy Ways to Increase Your Ubisoft Connect Speed</u></a></li>
<li><a href="https://win11.techidaily.com/reveal-and-recognize-six-ways-to-discover-your-pc-model/"><u>Reveal & Recognize - Six Ways To Discover Your PC Model</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-gaining-windows-high-level-control/"><u>Steps for Gaining Windows' High-Level Control</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-memory-couldnt-be-written-in-windows/"><u>Tackling 'Memory Couldn’t Be Written' In Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-6-appsservices-to-trace-any-infinix-smart-8-pro-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>Top 6 Apps/Services to Trace Any Infinix Smart 8 Pro Location By Mobile Number | Dr.fone</u></a></li>
</ul></div>

