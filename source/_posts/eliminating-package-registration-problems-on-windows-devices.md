---
title: Eliminating Package Registration Problems on Windows Devices
date: 2024-07-13T09:52:14.202Z
updated: 2024-07-14T09:52:14.202Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating Package Registration Problems on Windows Devices
excerpt: This Article Describes Eliminating Package Registration Problems on Windows Devices
keywords: Fixing Packages Errors (Windows),Resolve WinPack Issues,Simplify Device Registration,Ease Windows Package Installation,Eliminate Devices' Logging Problems,Streamline Windows Update Process,Unhindered Packages on PCs
thumbnail: https://thmb.techidaily.com/d6473782f31868e794fc3ab8460fc67b139be82f000417effd74e9124ff9dff3.jpg
---

## Eliminating Package Registration Problems on Windows Devices

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

 The same troubleshooter is also available within Windows 10’s Settings app. To access it, click the**Update & Security** category and**Troubleshoot** tab. Then you can select**Additional troubleshooters** to bring up the list of troubleshooting tools.

## 2\. Update Photos

 Updating Microsoft Store apps like Photos can fix issues with them. So, try updating Microsoft Photos like this:

1. Click**Start** and select Microsoft Store on that button’s menu.
2. Select Microsoft Store’s**Library** tab.
3. Click**Get updates** to see what apps need updating. MS Store will then automatically download and install an update for Photos if available.  
![The Get updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/get-updates-button.jpg)
4. Wait for the Photos app update to finish before closing Microsoft Store.

## 3\. Repair and Reset the Photos Apps

 Repairing or resetting Photos will likely fix the “Package could not be registered” if that app has corrupted files or data. You can select adjacent**Repair** and**Reset** troubleshooting options for Photos within Settings’ Apps & Features tool. To apply this solution, follow the instructions in our guide for [resetting Microsoft Store apps](https://www.makeuseof.com/windows-reset-app/) . Select the**Repair** option first and**Reset** second if necessary.

![The Repair and Reset buttons for Photos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-repair-reset-buttons.jpg)

## 4\. Run the Deployment Image and System File Checker Tools

 The “Package could not be registered” error can also be due to Windows system file corruption. That much has been confirmed by users who’ve said that running Deployment Image Servicing Management and System File Checker scans fixed this issue on their PCs. You can apply this potential solution by [opening the Command Prompt with admin rights](https://www.makeuseof.com/windows-11-open-command-prompt/) and running these separate DISM and SFC commands:

`DISM.exe /Online /Cleanup-image /Restorehealth`

`sfc /scannow`

 Run the Deployment Image Servicing Management scan command before the System File Checker tool. Leave the Command Prompt open until it shows a Windows Resource Protection message for the SFC scan. If it says Windows Resource Protection repaired files, this resolution might have resolved the “Package could not be registered” error.

## 5\. Reinstall Photos

 If the “Package could not be registered” error persists after applying the resolutions above, you might need to reinstall Photos to fix it. This solution is the most likely one to fix a corrupted Photos app. You can uninstall and reinstall Photos with PowerShell like this:

1. Start PowerShell with a method in our guide to [opening PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
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

 This is suggested as a last resort because you’ll need to reinstall third-party software installed before resetting Windows. However, you can select to keep user files such as photos, documents, videos, etc. Our [guide to resetting Windows 10 and 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) tells you how to perform a factory reset.

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
<li><a href="https://win11.techidaily.com/regaining-access-to-your-favorite-ms-store-games-and-tools/"><u>Regaining Access to Your Favorite MS Store Games & Tools</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-code-0x0000004e-hiccups/"><u>Resolving Windows Code 0X0000004E Hiccups</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-overcome-not-trusted-update-error-in-winos/"><u>Strategies to Overcome Not Trusted Update Error in WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/no-more-grouped-taskbars-win-11-edition/"><u>No More Grouped Taskbars: Win 11 Edition</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-a-comprehensible-explanation-of-youtubes-viewership-puzzle/"><u>2024 Approved  A Comprehensible Explanation of YouTube's Viewership Puzzle</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-confirmation-procedures-for-youtube-users/"><u>[Updated] In 2024, Confirmation Procedures for YouTube Users</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/digital-domination-rise-from-thousands-to-a-million-on-youtube/"><u>Digital Domination  Rise From Thousands to a Million on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-inability-to-connect-error-for-malwarebytes-on-win11/"><u>Fixing the Inability to Connect Error for Malwarebytes on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-for-io-errors-in-photo-import-from-apple-devices/"><u>Essential Fixes for I/O Errors in Photo Import From Apple Devices</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-infinix-smart-7-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Infinix Smart 7 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-interface-effective-process-filtering-and-customizing-themes-in-w11/"><u>Navigating the Interface: Effective Process Filtering & Customizing Themes in W11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-blue-screen-analysis-key-to-troubleshooting/"><u>Windows Blue Screen Analysis: Key to Troubleshooting</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-formulating-a-seamless-subscription-hyperlink-to-youtube-for-2024/"><u>[Updated] Formulating a Seamless Subscription Hyperlink to YouTube for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-cab-files-explained-formatting-and-implementation/"><u>Windows CAB Files Explained: Formatting and Implementation</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-the-best-free-and-paid-online-vertical-video-editors/"><u>New 2024 Approved The Best Free and Paid Online Vertical Video Editors</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-securing-snapchat-footage-essential-mobile-tips/"><u>[New] In 2024, Securing Snapchat Footage  Essential Mobile Tips</u></a></li>
<li><a href="https://win11.techidaily.com/pro-tips-for-maximizing-speed-and-efficiency-in-3d-painting/"><u>Pro Tips for Maximizing Speed and Efficiency in 3D Painting</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-banishing-black-edges-on-your-youtube-video-for-2024/"><u>[Updated] Banishing Black Edges on Your YouTube Video for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-and-fixing-the-windows-update-hurdles/"><u>Breaking Down and Fixing the Windows Update Hurdles</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-journey-10-key-windows-store-tools/"><u>Boost Your Journey: 10 Key Windows Store Tools</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-know-how-to-create-obs-slideshow-creating-obs-slideshow-in-simple-steps-application-for-creating-obs-slideshow-make-obs-slideshow-onli/"><u>Updated 2024 Approved Know How to Create OBS Slideshow. Creating OBS Slideshow in Simple Steps; Application for Creating OBS Slideshow. Make OBS Slideshow Online</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-transforming-simple-sessions-into-high-end-audacity-recordings/"><u>[New] Transforming Simple Sessions Into High-End Audacity Recordings</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-crafting-engagement-top-5-typeface-tools-to-amplify-your-tiktok-reach/"><u>2024 Approved  Crafting Engagement  Top 5 Typeface Tools to Amplify Your TikTok Reach</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-harmonizing-technology-with-taste-your-guide-to-mastering-audio-format-selection/"><u>Updated Harmonizing Technology with Taste Your Guide to Mastering Audio Format Selection</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-key-activation-issues/"><u>Troubleshooting Windows Key Activation Issues</u></a></li>
<li><a href="https://win11.techidaily.com/from-start-menu-to-control-panel-a-guide/"><u>From Start Menu to Control Panel: A Guide</u></a></li>
<li><a href="https://extra-support.techidaily.com/step-by-step-download-and-personalize-whatsapp-ringtones-on-mobile-for-2024/"><u>Step-by-Step  Download & Personalize WhatsApp Ringtones on Mobile for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/expertly-navigate-and-enhance-text-via-the-snipping-tool/"><u>Expertly Navigate and Enhance Text via the Snipping Tool</u></a></li>
<li><a href="https://win11.techidaily.com/activation-procedure-for-copypaste-functionality-in-w11s-security-mode-edge/"><u>Activation Procedure for Copy/Paste Functionality in W11's Security Mode, Edge</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-nokia-c210-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Nokia C210 | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-realme-narzo-60-pro-5g-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Realme Narzo 60 Pro 5G without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/from-obscurity-to-opulence-grow-your-insta-following-to-1000-for-2024/"><u>From Obscurity to Opulence  Grow Your Insta Following to 1,000 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-no-logging-in-run-commands-on-pcs/"><u>Fixing No Logging in Run Commands on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-non-automatic-timezone-change/"><u>Overcoming Windows' Non-Automatic Timezone Change</u></a></li>
<li><a href="https://win11.techidaily.com/pro-tips-show-more-pins-on-windows-11-start/"><u>Pro Tips: Show More Pins on Windows 11 Start</u></a></li>
<li><a href="https://win11-tips.techidaily.com/innovative-ways-to-make-your-windows-11-unique/"><u>Innovative Ways to Make Your Windows 11 Unique</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-design-and-send-video-invites-with-these-top-ios-and-android-apps/"><u>New 2024 Approved Design and Send Video Invites with These Top iOS and Android Apps</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-best-practices-in-finding-quality-photo-and-video-banners/"><u>[New] In 2024, Best Practices in Finding Quality Photo & Video Banners</u></a></li>
<li><a href="https://win11.techidaily.com/insightful-analysis-hibernations-role-in-windows/"><u>Insightful Analysis: Hibernation's Role in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/harness-the-power-of-github-desktop-for-windows-os-devops/"><u>Harness the Power of GitHub Desktop for Windows OS DevOps</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-best-realme-gt-5-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>In 2024, Best Realme GT 5 Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-xiaomi-civi-3-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for Xiaomi Civi 3 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-tactics-for-repeated-usernamepassword-alerts/"><u>Bypass Tactics for Repeated Username/Password Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/tactics-to-address-non-signed-windows-update-files/"><u>Tactics to Address Non-Signed Windows Update Files</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-fix-nvidias-geforce-error-x0001-on-windows-1011/"><u>Steps to Fix Nvidia's GeForce Error X0001 on Windows 10/11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/charming-chic-explore-the-hottest-discothemes-by-curators/"><u>Charming Chic  Explore the Hottest DiscoThemes by Curators</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-enabling-windows-11-toolbar-elements/"><u>Guide to Enabling Windows 11 Toolbar Elements</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-windows-disastrous-dism-0x800f082f-error/"><u>Demystifying Windows' Disastrous DISM 0X800F082F Error</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-itel-p55t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Itel P55T | Dr.fone</u></a></li>
</ul></div>
