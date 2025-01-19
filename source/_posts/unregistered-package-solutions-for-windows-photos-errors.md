---
title: Unregistered Package Solutions for Windows Photos Errors
date: 2025-01-13T20:43:21.687Z
updated: 2025-01-18T16:46:56.839Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unregistered Package Solutions for Windows Photos Errors
excerpt: This Article Describes Unregistered Package Solutions for Windows Photos Errors
keywords: Photo Error Fix,Windows Photos Troubleshoot,Unregister Windows Photos,Photo Package Management,Windows Error Resolution,Unlisted Package Solutions,Photo System Glitches
thumbnail: https://thmb.techidaily.com/af14611bf221d9521ecefac4bb5738408a7016fb6a0da262331d951510430549.jpg
---

## Unregistered Package Solutions for Windows Photos Errors

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`Get-AppxPackage -allusers Microsoft.Windows.Photos | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Photos app command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-photos-app.jpg)
4. Restart your PC after reinstalling Photos.

## 6\. Reset Windows

 If you’ve tried all other resolutions suggested here, there could be a deeper Windows issue causing the “Package could not be registered” Photos error. Then a system reset could be needed to remedy that deeper issue. Resetting Windows will refresh the platform’s components and restore it to a default state.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-this-pc-tool.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-record-videos.techidaily.com/new-expert-choices-best-video-cards-for-youtubes-clearest-output-for-2024/"><u>[New] Expert Choices Best Video Cards for YouTube's Clearest Output for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-thrill-town-10-similar-video-games-to-gta-v-for-2024/"><u>[New] Thrill Town 10 Similar Video Games To GTA V for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-the-quintessential-selection-5-must-have-mac-snipers/"><u>2024 Approved The Quintessential Selection 5 Must-Have Mac Snipers</u></a></li>
<li><a href="https://technical-tips.techidaily.com/accessing-netgear-devices-july-2024-default-passwords-revealed/"><u>Accessing NETGEAR Devices: July 2024 Default Passwords Revealed</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/cinemas-best-hope-fueled-film-selections-for-2024/"><u>Cinema's Best Hope-Fueled Film Selections for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-editing-expertise-with-windows-11-and-11s-custom-text-hotkeys/"><u>Elevate Your Editing Expertise with Windows 11 & 11'S Custom Text Hotkeys</u></a></li>
<li><a href="https://win11.techidaily.com/fix-windows-11s-glitch-empty-spots-for-file-images/"><u>Fix Windows 11'S Glitch: Empty Spots for File Images</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-icloud-lock-from-your-apple-iphone-xs-max-and-ipad-by-drfone-ios/"><u>In 2024, How to Unlock iCloud lock from your Apple iPhone XS Max and iPad?</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-pure-serenity-in-the-air-top-asmr-microphones-at-low-costs/"><u>In 2024, Pure Serenity in the Air - Top ASMR Microphones at Low Costs</u></a></li>
<li><a href="https://win11.techidaily.com/insight-into-the-cessation-of-hardware-assisted-gfx-tasking-windows/"><u>Insight Into the Cessation of Hardware-Assisted GFX Tasking Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-key-features-youre-missing-out-on/"><u>Mastering Windows 11: Key Features You're Missing Out On</u></a></li>
<li><a href="https://win11.techidaily.com/tweak-context-menus-for-streamlined-software-use-on-pcs/"><u>Tweak Context Menus for Streamlined Software Use on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-cause-of-chromes-dark-display/"><u>Unveiling the Cause of Chrome's Dark Display</u></a></li>
<li><a href="https://win-answers.techidaily.com/war-thunder-continues-to-crash-top-strategies-to-fix-it/"><u>War Thunder Continues to Crash : Top Strategies to Fix It</u></a></li>
</ul></div>

