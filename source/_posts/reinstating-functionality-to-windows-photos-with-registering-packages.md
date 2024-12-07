---
title: Reinstating Functionality to Windows Photos with Registering Packages
date: 2024-11-30T01:54:29.921Z
updated: 2024-12-06T17:12:53.116Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Functionality to Windows Photos with Registering Packages
excerpt: This Article Describes Reinstating Functionality to Windows Photos with Registering Packages
keywords: Windows Photo Restore,Photos Registration Packs,Reinstate Photo Features,Windows Photos Enhance,Package Integration for Photos,Photo Functionality Update,Register Photos in Windows
thumbnail: https://thmb.techidaily.com/2b68f106433b091c014f2083746f9820ace97ab74d68e3b5f340250f5652e1ee.jpg
---

## Reinstating Functionality to Windows Photos with Registering Packages

 Microsoft Photos is the default image viewer in Windows with which many users open picture files. However, some users can’t open images in Photos because of a “Package could not be registered” error. That issue arises for some Photos users when they try to open JPG or PNG images in that app.

 This is how you can fix the “Package could not be registered” error in Windows 11 and 10.

## 1\. Run the Windows Store Apps Troubleshooter

 Start your error troubleshooting with a troubleshooter for UWP apps on Microsoft Store. Windows Store Apps is a troubleshooter that could identify and resolve an issue with the Photos app. These are the steps for running that troubleshooter in Windows 11:

1. Simultaneously press the**Win + I** keyboard keys to bring up Settings.
2. Click**Troubleshoot** within the**System** tab of Settings.
3. Next, select**Other trouble-shooters** to reach the Windows troubleshooters in Settings.
4. Press the Windows Store Apps troubleshooter’s**Run** button.  
![The troubleshooters in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/other-troubleshooters-in-settings.jpg)
5. Then select to apply fixes suggested by the Windows Store App troubleshooter.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-store-apps-troubleshooter.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The same troubleshooter is also available within Windows 10’s Settings app. To access it, click the**Update & Security** category and**Troubleshoot** tab. Then you can select**Additional troubleshooters** to bring up the list of troubleshooting tools.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Update Photos

 Updating Microsoft Store apps like Photos can fix issues with them. So, try updating Microsoft Photos like this:

1. Click**Start** and select Microsoft Store on that button’s menu.
2. Select Microsoft Store’s**Library** tab.
3. Click**Get updates** to see what apps need updating. MS Store will then automatically download and install an update for Photos if available.  
![The Get updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/get-updates-button.jpg)
4. Wait for the Photos app update to finish before closing Microsoft Store.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GU08CQVsZz0?si=V-SvPfzRsQysMS0e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Repair and Reset the Photos Apps

 Repairing or resetting Photos will likely fix the “Package could not be registered” if that app has corrupted files or data. You can select adjacent**Repair** and**Reset** troubleshooting options for Photos within Settings’ Apps & Features tool. To apply this solution, follow the instructions in our guide for[resetting Microsoft Store apps](https://www.makeuseof.com/windows-reset-app/) . Select the**Repair** option first and**Reset** second if necessary.

![The Repair and Reset buttons for Photos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-repair-reset-buttons.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

## 6\. Reset Windows

 If you’ve tried all other resolutions suggested here, there could be a deeper Windows issue causing the “Package could not be registered” Photos error. Then a system reset could be needed to remedy that deeper issue. Resetting Windows will refresh the platform’s components and restore it to a default state.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-this-pc-tool.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This is suggested as a last resort because you’ll need to reinstall third-party software installed before resetting Windows. However, you can select to keep user files such as photos, documents, videos, etc. Our[guide to resetting Windows 10 and 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) tells you how to perform a factory reset.

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
<li><a href="https://youtube-web.techidaily.com/he-core-elements-in-asmr-visual-media/"><u>[New] The Core Elements in ASMR Visual Media</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-boost-traffic-to-your-videos-top-seo-practices-for-youtube-success-for-2024/"><u>[Updated] Boost Traffic to Your Videos Top SEO Practices for YouTube Success for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/1726028381076-mp4m4v/"><u>簡単な手順でMP4からM4Vへの変換テクニック</u></a></li>
<li><a href="https://win11.techidaily.com/conquer-non-compatibilities-easy-steps-for-windows-xp-users/"><u>Conquer Non-Compatibilities: Easy Steps for Windows XP Users</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-error-messages-solving-windows-crashes-easily/"><u>Decoding Error Messages: Solving Windows Crashes Easily</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/echoes-unleashed-mac-studio-techniques-for-2024/"><u>Echoes Unleashed Mac Studio Techniques for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-0x0000011b-failure-on-win-1011/"><u>Fixing 0X0000011B Failure on Win 10/11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-htc-u23-pro-drfone-by-drfone-virtual-android/"><u>How to Check Distance and Radius on Google Maps For your HTC U23 Pro | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-videos-from-your-c12-pro-by-fonelab-android-recover-video/"><u>How to recover old videos from your C12 Pro</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-x-to-other-iphone-15-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone X To Other iPhone 15 devices? | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-free-video-magic-top-5-effect-tools/"><u>In 2024, Free Video Magic Top 5 Effect Tools</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ter-library-selecting-witty-content-for-short-youtube-videos/"><u>Laughter Library Selecting Witty Content for Short YouTube Videos</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ng-your-marketing-journey-on-youtube/"><u>Mapping Your Marketing Journey on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-event-viewer-troubleshooting/"><u>Navigating Windows Event Viewer Troubleshooting</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-errors-in-onedrive-cloud-operations-win/"><u>Overcoming Errors in OneDrive Cloud Operations Win</u></a></li>
<li><a href="https://win11.techidaily.com/smart-storage-reclamation-on-windows-explained/"><u>Smart Storage Reclamation on Windows Explained</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-powerpoints-print-functionality-9-tips-for-windows-users/"><u>Streamlining PowerPoint's Print Functionality: 9 Tips for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/what-makes-the-updated-outlook-so-worth-it-top-9-reasons/"><u>What Makes the Updated Outlook So Worth It? - Top 9 Reasons</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-home-settings-made-simple/"><u>Windows 11 Home Settings Made Simple</u></a></li>
</ul></div>

