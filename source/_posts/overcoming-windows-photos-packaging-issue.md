---
title: Overcoming Windows Photos Packaging Issue
date: 2024-12-01T23:16:38.634Z
updated: 2024-12-07T04:28:58.137Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Windows Photos Packaging Issue
excerpt: This Article Describes Overcoming Windows Photos Packaging Issue
keywords: Fix Windows Photo Errors,Resolve Photo Package Fails,Address Windows Image Problems,Eliminate Win Photo Packing Issues,Tackle WIN Photos Bottleneck,Solving PC Photo Compacting,Overcoming Photo Bundle Error
thumbnail: https://thmb.techidaily.com/5648c434c12cbf88b15506d6d23b8724252689511d16fa18d7a28833e2a6d9c5.jpg
---

## Overcoming Windows Photos Packaging Issue

 Microsoft Photos is the default image viewer in Windows with which many users open picture files. However, some users can’t open images in Photos because of a “Package could not be registered” error. That issue arises for some Photos users when they try to open JPG or PNG images in that app.

 This is how you can fix the “Package could not be registered” error in Windows 11 and 10.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Run the Windows Store Apps Troubleshooter

 Start your error troubleshooting with a troubleshooter for UWP apps on Microsoft Store. Windows Store Apps is a troubleshooter that could identify and resolve an issue with the Photos app. These are the steps for running that troubleshooter in Windows 11:

1. Simultaneously press the**Win + I** keyboard keys to bring up Settings.
2. Click**Troubleshoot** within the**System** tab of Settings.
3. Next, select**Other trouble-shooters** to reach the Windows troubleshooters in Settings.
4. Press the Windows Store Apps troubleshooter’s**Run** button.  
![The troubleshooters in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/other-troubleshooters-in-settings.jpg)
5. Then select to apply fixes suggested by the Windows Store App troubleshooter.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-store-apps-troubleshooter.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3UyJuZYzjt0?si=W87GeyzVKVORAk7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Reset Windows

 If you’ve tried all other resolutions suggested here, there could be a deeper Windows issue causing the “Package could not be registered” Photos error. Then a system reset could be needed to remedy that deeper issue. Resetting Windows will refresh the platform’s components and restore it to a default state.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-this-pc-tool.jpg)

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
<li><a href="https://fox-access.techidaily.com/new-fast-track-turning-zip-into-professional-quality-srt-files/"><u>[New] Fast Track Turning ZIP Into Professional-Quality Srt Files</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-sneaky-soundtrack-watching-youtube-unobtrusively/"><u>[Updated] Sneaky Soundtrack Watching YouTube Unobtrusively</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-ghostly-replay-instructional-guide/"><u>2024 Approved Ghostly Replay Instructional Guide</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-mouse-indicator-style-on-winos/"><u>Customize Your Mouse Indicator Style on WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-meaning-of-office-error-0x80041015/"><u>Decoding the Meaning of Office Error 0X80041015</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-vivo-v27-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Vivo V27 | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-vivo-t2x-5gfrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Vivo T2x 5GFRP Lock</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/keeping-your-views-private-top-5-insta-tools-for-2024/"><u>Keeping Your Views Private - Top 5 Insta Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-the-unseen-effective-tactics-for-off-screen-windows-in-win10win11/"><u>Reviving the Unseen: Effective Tactics for Off-Screen Windows in Win10/Win11</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/209826515-9780008366407-sagittarius-2021-your-personal-horoscope/"><u>Sagittarius 2021: Your Personal Horoscope | Free Book</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-media-non-playability-issue/"><u>Tackling Windows Media Non-Playability Issue</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-automatic-windows-store-openings/"><u>Troubleshooting Automatic Windows Store Openings</u></a></li>
<li><a href="https://common-error.techidaily.com/wind-down-your-windows-11-without-disturbances/"><u>Wind Down Your Windows 11 Without Disturbances</u></a></li>
</ul></div>

