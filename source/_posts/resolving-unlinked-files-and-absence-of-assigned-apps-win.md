---
title: Resolving Unlinked Files and Absence of Assigned Apps (Win)
date: 2024-07-13T10:42:55.054Z
updated: 2024-07-14T10:42:55.054Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Unlinked Files and Absence of Assigned Apps (Win)
excerpt: This Article Describes Resolving Unlinked Files and Absence of Assigned Apps (Win)
keywords: Win File Resolution,Unlinked Windows Fix,Absent App Remedy,Link Error Windows,App Not Assigned Win,Missing Files Solution,Unassigned Tools Window
thumbnail: https://thmb.techidaily.com/95788679327077f3bf6744c4870d74096e3663b00fb525d667e1a6c4f5883874.jpg
---

## Resolving Unlinked Files and Absence of Assigned Apps (Win)

 The error "this file does not have an app associated with it" mainly occurs when Windows can't find a compatible app for opening a specific file type. If you have the relevant app installed, it might not be set as default to open files of that format, or the app or file itself could be corrupted or damaged.

 The error can also occur when opening folders, mainly from Windows Search, and even when running apps and games. Here are some solutions you can apply to resolve this error regardless of where you get it.

## 1\. Ensure You Have an App Installed That Can Open Such Files

 Windows presents this error primarily when it fails to find the appropriate app to open files. Therefore, first, you should check whether you have the right app installed to open files in this particular format. There are several ways to check this, but here is one of the easiest:

1. Navigate to the file that is displaying this error when you open it.
2. Right-click the file and select**Properties** .
3. Navigate to the**General** tab and look for the file format next to**Type of file** .  
![Check the File Format in Properties Window of File in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/1-1.jpg)

 If it's a commonly used file format, such as PDF, JPEG, PNG, Docx, etc., for which you have the appropriate app installed, move on directly to heading #2\. However, if you see an unusual file format here—something you haven't seen before, make sure you have the appropriate app installed.

 To confirm this, right-click the file and navigate to**Open with > Choose another app** .

![Click on Choose Another App by Right-clicking on the File in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/2-1.jpg)

 If you have a relevant app installed, Windows will suggest you select it to open the file. If you don't see any app suggestions here, you probably don't have any apps installed capable of opening this file type.

![Windows Suggesting Some Apps to Open the Image File in PNG Format](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-suggesting-some-apps-to-open-the-image-file-in-png-format.jpg)

 If that's the case, simply go to any of your browsers, search for Windows apps that can run files in that format, and download them. After downloading the appropriate app, make it the default for opening this file type.

## 2\. Set the Default Application for the File Type

 The error message states that if the app is already installed, you need to create an association in the Default Programs. If you already had the compatible app installed or have just downloaded it, your next step should be to set it as default for files having that file type or format. Setting the compatible application as default may solve this problem right away.

 If you haven't changed a default app before, check out our article on [Windows 11 default apps](https://www.makeuseof.com/change-windows-11-default-apps/) . The article discusses various ways to change the default app, but we recommend using the second method, which is using the Settings app. That's because this method lets you search for specific file formats and choose a default app for them.

## 3\. Is the Default App Already Selected? Repair or Change It

 If the app you intend to set as default for a particular file format is already selected as a default application, but Windows still displays this error, the app has likely become corrupt, thus causing the error.

 To rule out this possibility, you should run the App troubleshooter, update the problematic app, reset its cache, or repair and reset it. You can find instructions for performing these steps in our [g](https://www.makeuseof.com/apps-arent-working-properly-windows/) uide for [fixing apps that don't work on Windows](https://www.makeuseof.com/apps-arent-working-properly-windows/) .

 Try these steps to see if they fix the problem. If the issue persists after that, we recommend you reinstall the app or select a different one as the default. If you don't have a different app installed on your device that supports these files, install one that does.

## 4\. Check for Specific File Issues

 If you're opening the file in a compatible app, it's working normally, and you've already set it as default, but you're still encountering the error, verify the file itself isn't corrupt. To confirm that, open any other file having the same file format and see if it returns the same error.

 If other files open without error, but the issue persists with one file, it's likely that the file is corrupt. If that's the case, follow our [guide on using Windows built-in tools to fix corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) . If that doesn't fix the problem, try using one of the [dedicated tools for repairing corrupted files](https://www.makeuseof.com/tag/best-tools-repair-corrupted-damaged-files-windows/) .

 Misconfiguring the Registry settings can result in undesirable outcomes and even render your device unbootable. Before you try the next fix, create a [backup of the Windows Registry so you can restore it](https://www.makeuseof.com/tag/backup-restore-windows-registry/) if something goes wrong.

## 5\. Use the Registry

 If none of the above fixes have been successful, try this registry tweak as a last resort:

1. Type**"regedit"** in Windows Search and open the**Registry Editor** .  
![Open Registry Editor App From Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/4-1.jpg)
2. Paste the path below into the address bar of Registry Editor.  
Computer\HKEY_CLASSES_ROOT\lnkfile
3. Select the**Inkfile** key. Then, look in the right pane and see if there is a string value called**"IsShortcut** .**"**  
![Locate the IsShortcut String Value in the Inkfile Key of Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/5-1.jpg)
4. If it's not there, right-click in the blank area and go to**New > String Value** . Then rename it to**"IsShortcut** .**"**  
![Create and Rename the New String Value in Windows Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/6.jpg)
5. If the string value is already there, right-click on it and select**Delete** .  
![Select Delete by Right-clicking on the String Value in Windows Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/7.jpg)
6. After that, follow step four to recreate it. Don't forget to rename it appropriately so you don't encounter any issues.
7. Restart your device once after that.

## Do You Encounter the Error When Opening Folders? Follow These Tips

 If you get the "This file does not have an app associated with it" error when opening folders, try these checks:

* Restart File Explorer (see [how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) for tips).
* If you're opening a folder by searching it in Windows Search or Quick Access, consider opening it directly from File Explorer.

## Do You Encounter the Error When Opening Apps or Games? Try These Tips

 If you get the "This file does not have an app associated with it" error when opening an app or game, perform the following checks:

* If you're using a shortcut to open games, especially the ones installed in a gaming client, open them from the gaming client or the installation directory.
* In case the game launcher requires you to log in before playing any of the installed games, ensure you do so.
* If you're experiencing this error in a specific game or app, ensure its files haven't been corrupted.

## Easily Open Your Apps, Files, and Folders Again on Windows

 Seeing the error "this file does not have an app associated with it" when opening a file, folder, or app can be frustrating. If the file or folder isn't corrupt, the above fixes will help you identify and resolve the issue's root cause. If nothing works, you can reinstall the app or restore the older version of the file or folder from your backup.

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
<li><a href="https://ai-video-apps.techidaily.com/webm-vs-mp4-top-converters-to-switch-formats-seamlessly-for-2024/"><u>WebM vs MP4 Top Converters to Switch Formats Seamlessly for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-cease-windows-11-alarms-and-notifications/"><u>Swiftly Cease Windows 11 Alarms and Notifications</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-lava-blaze-2-pro-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Lava Blaze 2 Pro Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-a-detailed-settings-app-tour/"><u>Windows 11: A Detailed Settings App Tour</u></a></li>
<li><a href="https://fix-guide.techidaily.com/proven-ways-to-fix-there-was-a-problem-parsing-the-package-on-oppo-reno-9a-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Proven Ways to Fix There Was A Problem Parsing the Package on Oppo Reno 9A | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-oppo-reno-8t-5g-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Oppo Reno 8T 5G FRP Without Computer</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-elevate-your-vimeo-media-with-well-defined-chapters/"><u>[Updated] 2024 Approved  Elevate Your Vimeo Media with Well-Defined Chapters</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-control-over-your-pcs-touchpad-gestures/"><u>Regaining Control Over Your PC's Touchpad Gestures</u></a></li>
<li><a href="https://win11.techidaily.com/turbo-charge-battlenet-downloads-for-smooth-gaming/"><u>Turbo Charge Battle.net Downloads for Smooth Gaming</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-best-3d-entrance-makers-for-youtube-creators-for-2024/"><u>[New] Best 3D Entrance Makers for YouTube Creators for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-incompatible-application-downloads-on-microsoft-store/"><u>Tackling Incompatible Application Downloads on Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-correcting-windows-install-errors-win11/"><u>Understanding and Correcting Windows Install Errors (Win11)</u></a></li>
<li><a href="https://win11.techidaily.com/top-4-strategies-for-windows-pct-success/"><u>Top 4 Strategies for Windows PCT Success</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-explore-top-affordable-online-resources-your-dream-toolkit-for-visual-filmmaking/"><u>[Updated] Explore Top Affordable Online Resources - Your Dream Toolkit for Visual Filmmaking</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-techniques-windows-sandbox-lacks-hyprocvisor/"><u>Troubleshooting Techniques: Windows Sandbox Lacks Hyprocvisor</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-fix-wrongly-entered-characters-in-windows/"><u>Tips to Fix Wrongly Entered Characters in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-insights-for-placement-of-software-shortcuts-on-taskbar/"><u>Quick Insights for Placement of Software Shortcuts on Taskbar</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-itel-p55plus-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your Itel P55+ Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-honor-90-pro-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Honor 90 Pro to Roku | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-windows-11-to-advanced-auditory-features-dolby-atmos/"><u>Upgrading Windows 11 to Advanced Auditory Features (Dolby Atmos)</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-cloud-connectivity-revive-google-drive-windows-links/"><u>Streamlining Cloud Connectivity: Revive Google Drive Windows Links</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/capturing-moving-images-mirrorless-versus-dslr-for-2024/"><u>Capturing Moving Images  Mirrorless Versus DSLR for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/is-instagrams-self-validation-a-game-changer-in-2024/"><u>Is Instagram’s Self-Validation a Game Changer, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-missing-second-display-on-w11/"><u>Troubleshooting Missing Second Display on W11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/unleash-your-earning-potential-on-tiktok-in-just-8-steps-for-2024/"><u>Unleash Your Earning Potential on TikTok in Just 8 Steps for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-android-essentials-must-have-apps-from-google-play-for-2024/"><u>New Android Essentials Must-Have Apps From Google Play for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-13-pro-to-other-iphone-13-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 13 Pro to other iPhone 13 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-expert-tips-on-mastering-the-preview-application-on-mac/"><u>2024 Approved  Expert Tips on Mastering the Preview Application on Mac</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-apple-iphone-11-pro-drfone-by-drfone-virtual-ios/"><u>Full Guide to Fix iToolab AnyGO Not Working On Apple iPhone 11 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-webcam-shutdown/"><u>Strategies for Overcoming Webcam Shutdown</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-solve-the-email-fault-caused-by-0x800713f-on-win11/"><u>Steps to Solve the Email Fault Caused by 0X800713F on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-remedy-windows-onedrive-server-issues/"><u>Swiftly Remedy Windows OneDrive Server Issues</u></a></li>
<li><a href="https://win11.techidaily.com/stay-true-to-tech-avoiding-impostor-apps-on-windows-platform/"><u>Stay True to Tech: Avoiding Impostor Apps on Windows Platform</u></a></li>
<li><a href="https://win11.techidaily.com/strategizing-shortcut-placement-near-win11s-power-button/"><u>Strategizing Shortcut Placement Near Win11's Power Button</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-amd-195-error-in-windows-installations/"><u>Tackling AMD 195 Error in Windows Installations</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-phenomenal-edits-the-digital-illusionists-art/"><u>In 2024, Phenomenal Edits  The Digital Illusionist's Art</u></a></li>
<li><a href="https://win11.techidaily.com/shuffling-monitors-order-in-modern-oses/"><u>Shuffling Monitors' Order in Modern OSes</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-methods-for-eliminating-windows-errors/"><u>Top 8 Methods for Eliminating Windows Errors</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-channel-cashflow-effective-tactics-for-monetizing-on-mobile-devices/"><u>[Updated] Channel Cashflow  Effective Tactics for Monetizing on Mobile Devices</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-windows-ui-5-steps-toward-mac-os-aesthetics/"><u>Transforming Windows UI: 5 Steps Toward Mac OS Aesthetics</u></a></li>
</ul></div>
