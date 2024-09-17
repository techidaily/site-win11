---
title: Fixing the Unregistered Photos Package Issue in Windows OS
date: 2024-09-12T23:41:33.406Z
updated: 2024-09-17T01:25:45.014Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing the Unregistered Photos Package Issue in Windows OS
excerpt: This Article Describes Fixing the Unregistered Photos Package Issue in Windows OS
keywords: Fix Photo Registration Windows,Resolve Win OS Image Errors,Address Unregistered Pics Windows,Correct Photo Sync WindowsOS,Remedy Photos Package Fails,Mend Photo Issue Windows XP,Solve Windows Images Problems
thumbnail: https://thmb.techidaily.com/6ae69a61ee431cd865eb63071b7e7dab33df662eeb4d068d44c620780bca6c82.jpeg
---

## Fixing the Unregistered Photos Package Issue in Windows OS

 Microsoft Photos is the default image viewer in Windows with which many users open picture files. However, some users can’t open images in Photos because of a “Package could not be registered” error. That issue arises for some Photos users when they try to open JPG or PNG images in that app.

 This is how you can fix the “Package could not be registered” error in Windows 11 and 10.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Windows Store Apps Troubleshooter

 Start your error troubleshooting with a troubleshooter for UWP apps on Microsoft Store. Windows Store Apps is a troubleshooter that could identify and resolve an issue with the Photos app. These are the steps for running that troubleshooter in Windows 11:

1. Simultaneously press the**Win + I** keyboard keys to bring up Settings.
2. Click**Troubleshoot** within the**System** tab of Settings.
3. Next, select**Other trouble-shooters** to reach the Windows troubleshooters in Settings.
4. Press the Windows Store Apps troubleshooter’s**Run** button.  
![The troubleshooters in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/other-troubleshooters-in-settings.jpg)
5. Then select to apply fixes suggested by the Windows Store App troubleshooter.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-store-apps-troubleshooter.jpg)

 The same troubleshooter is also available within Windows 10’s Settings app. To access it, click the**Update & Security** category and**Troubleshoot** tab. Then you can select**Additional troubleshooters** to bring up the list of troubleshooting tools.

## 2\. Update Photos

 Updating Microsoft Store apps like Photos can fix issues with them. So, try updating Microsoft Photos like this:

1. Click**Start** and select Microsoft Store on that button’s menu.
2. Select Microsoft Store’s**Library** tab.
3. Click**Get updates** to see what apps need updating. MS Store will then automatically download and install an update for Photos if available.  
![The Get updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/get-updates-button.jpg)
4. Wait for the Photos app update to finish before closing Microsoft Store.

## 3\. Repair and Reset the Photos Apps

 Repairing or resetting Photos will likely fix the “Package could not be registered” if that app has corrupted files or data. You can select adjacent**Repair** and**Reset** troubleshooting options for Photos within Settings’ Apps & Features tool. To apply this solution, follow the instructions in our guide for[resetting Microsoft Store apps](https://www.makeuseof.com/windows-reset-app/) . Select the**Repair** option first and**Reset** second if necessary.

![The Repair and Reset buttons for Photos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-repair-reset-buttons.jpg)

## 4\. Run the Deployment Image and System File Checker Tools

 The “Package could not be registered” error can also be due to Windows system file corruption. That much has been confirmed by users who’ve said that running Deployment Image Servicing Management and System File Checker scans fixed this issue on their PCs. You can apply this potential solution by[opening the Command Prompt with admin rights](https://www.makeuseof.com/windows-11-open-command-prompt/) and running these separate DISM and SFC commands:

`DISM.exe /Online /Cleanup-image /Restorehealth`

`sfc /scannow`

 Run the Deployment Image Servicing Management scan command before the System File Checker tool. Leave the Command Prompt open until it shows a Windows Resource Protection message for the SFC scan. If it says Windows Resource Protection repaired files, this resolution might have resolved the “Package could not be registered” error.

## 5\. Reinstall Photos

 If the “Package could not be registered” error persists after applying the resolutions above, you might need to reinstall Photos to fix it. This solution is the most likely one to fix a corrupted Photos app. You can uninstall and reinstall Photos with PowerShell like this:

1. Start PowerShell with a method in our guide to[opening PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Then input this command for uninstalling PowerShell and hit**Enter** :  
`Get-AppxPackage Microsoft.Windows.Photos | Remove-AppxPackage`  
![The uninstall Photos command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-photos-command.jpg)
3. To reinstall Photos, input this PowerShell command and press**Enter** :  
`Get-AppxPackage -allusers Microsoft.Windows.Photos | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Photos app command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-photos-app.jpg)
4. Restart your PC after reinstalling Photos.

<!-- affiliate ads begin -->
<span id="1484963">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1484963.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1484963">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1484963.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1484963%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1484963/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Reset Windows

 If you’ve tried all other resolutions suggested here, there could be a deeper Windows issue causing the “Package could not be registered” Photos error. Then a system reset could be needed to remedy that deeper issue. Resetting Windows will refresh the platform’s components and restore it to a default state.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-this-pc-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137208/26400" target="_top" id="2137208">
  <img src="//a.impactradius-go.com/display-ad/26400-2137208" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137208/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This is suggested as a last resort because you’ll need to reinstall third-party software installed before resetting Windows. However, you can select to keep user files such as photos, documents, videos, etc. Our[guide to resetting Windows 10 and 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) tells you how to perform a factory reset.

<!-- affiliate ads begin -->
<span id="1983539">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983539.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983539">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983539.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983539%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983539/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Open Your Images in Photos Again

 One of the above resolutions will likely resolve the “Package Could not be Registered” error on your Windows 11/10 PC. However, remember there are plenty of third-party app alternatives you can open your images with if that Photos error persists. IrfanView, XnView, and FastStone Image Viewer are among the best Photos alternatives that are freely available.

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
<li><a href="https://youtube-blog.techidaily.com/rivia-trek-exploring-yts-fascinating-figures-and-infographics-for-2024/"><u>[New] Trivia Trek Exploring YT's Fascinating Figures and Infographics for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-office-design-evolution-trends-and-practices-for-maximum-output/"><u>[Updated] 2024 Approved Office Design Evolution Trends and Practices for Maximum Output</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-efficient-video-download-from-facebooks-domain/"><u>2024 Approved Efficient Video Download From Facebook's Domain</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-top-5-captivating-videos-from-the-world-of-fb/"><u>2024 Approved Top 5 Captivating Videos From the World of FB</u></a></li>
<li><a href="https://win11.techidaily.com/budget-friendly-guide-converting-your-vertical-footage-to-horizontal-view/"><u>Budget-Friendly Guide: Converting Your Vertical Footage to Horizontal View</u></a></li>
<li><a href="https://win11.techidaily.com/convert-dvds-videos-and-music-swiftly-with-wonderfox-quality-enhancement-tool/"><u>Convert DVDs, Videos, and Music Swiftly with WonderFox Quality Enhancement Tool</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-best-starter-zumba-fitness-dvd-collection-learn-easy-conversion-techniques-for-digital-videos/"><u>Discover the Best Starter Zumba Fitness DVD Collection: Learn Easy Conversion Techniques for Digital Videos!</u></a></li>
<li><a href="https://win11.techidaily.com/diy-tutorial-how-to-craft-an-audio-only-video-without-hitches/"><u>DIY Tutorial: How To Craft An Audio Only Video Without Hitches</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/downloading-facebook-videos-to-mp4-no-hassle-for-2024/"><u>Downloading Facebook Videos to MP4 - No Hassle for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/easy-guide-adding-diamond-shadow-plug-in-compatible-with-matrix-to-your-kodi-setup/"><u>Easy Guide: Adding Diamond Shadow Plug-In Compatible with Matrix to Your Kodi Setup</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-conversion-of-m2ts-files-to-avi-a-step-by-step-tutorial-at-no-charge/"><u>Effortless Conversion of M2TS Files to AVI - A Step-by-Step Tutorial at No Charge</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-sound-glitches-on-windows-11-the-ultimate-5-step-solution/"><u>Fixing Sound Glitches on Windows 11 - The Ultimate 5-Step Solution</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-can-i-get-more-stardust-in-pokemon-go-on-vivo-y28-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How can I get more stardust in pokemon go On Vivo Y28 5G? | Dr.fone</u></a></li>
<li><a href="https://discover-extraordinary.techidaily.com/the-unseen-longevity-of-eco-friendly-electronic-accessories-iphone-case-tested-for-half-a-year/"><u>The Unseen Longevity of Eco-Friendly Electronic Accessories: IPhone Case Tested for Half a Year</u></a></li>
<li><a href="https://facebook.techidaily.com/unraveling-new-antitrust-regulations-and-their-impact/"><u>Unraveling New Antitrust Regulations and Their Impact</u></a></li>
<li><a href="https://win11.techidaily.com/dvd-walkman/"><u>ワイヤレスでDVDコピー - 簡単! Walkman内へのビデオと音声移行</u></a></li>
</ul></div>

