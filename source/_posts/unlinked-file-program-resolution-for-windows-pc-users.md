---
title: Unlinked File Program Resolution for Windows PC Users
date: 2024-07-13T10:09:34.622Z
updated: 2024-07-14T10:09:34.622Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlinked File Program Resolution for Windows PC Users
excerpt: This Article Describes Unlinked File Program Resolution for Windows PC Users
keywords: Win Unlinked File Fix,Windows File Disconnect,PC Files Unlink Solve,Unlink Windows Data,Remove Unlinked Files WIN,Clear Links in WIN OS,Resolve WIN File Issues
thumbnail: https://thmb.techidaily.com/d156dc661c6f6baa9eb3b5c3ab4152f8f8f4fcdc0dbe084557e36eab0ab2db64.jpeg
---

## Unlinked File Program Resolution for Windows PC Users

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
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-leading-8-android-calling-apps-more-than-four-people/"><u>In 2024, Leading 8 Android Calling Apps  More Than Four People</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-key-collectors-deal-wintry-windows-11-priced-at-612-per-year/"><u>Exclusive Key Collector's Deal - Wintry Windows 11 Priced at $6.12 Per Year</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-display-adjustment-overcoming-overscan/"><u>Mastering Windows Display Adjustment: Overcoming Overscan</u></a></li>
<li><a href="https://win11.techidaily.com/stealth-mode-hiding-or-revealing-windows-protection-sectors/"><u>Stealth Mode: Hiding or Revealing Windows Protection Sectors</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-easily-unlock-your-vivo-s17t-device-sim-by-drfone-android/"><u>In 2024, Easily Unlock Your Vivo S17t Device SIM</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-digital-life-with-exclusive-ms-choice/"><u>Elevate Your Digital Life with Exclusive MS Choice</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-windows-configuration-pathways/"><u>Decoding the Windows Configuration Pathways</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-vivo-y78t-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Vivo Y78t to iPad | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/debating-choco-and-wslm-top-pick-for-windows-software/"><u>Debating Choco and WSLM: Top Pick for Windows Software</u></a></li>
<li><a href="https://win11.techidaily.com/window-terminal-design-your-own-palette/"><u>Window Terminal: Design Your Own Palette</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-unraveling-youtubes-ranks-the-deciding-elements-for-2024/"><u>[Updated] Unraveling YouTube's Ranks  The Deciding Elements for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/premier-game-viewing-platforms-for-2024/"><u>Premier Game Viewing Platforms for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-a-locked-motorola-moto-g84-5g-phone-by-drfone-android/"><u>How to Reset a Locked Motorola Moto G84 5G Phone</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-your-visual-experience-with-greater-vram/"><u>Enhancing Your Visual Experience with Greater VRAM</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-rootjunky-apk-to-bypass-google-frp-lock-for-samsung-galaxy-m54-5g-by-drfone-android/"><u>In 2024, Rootjunky APK To Bypass Google FRP Lock For Samsung Galaxy M54 5G</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-from-silence-to-soundtracks-tips-for-blending-audio-into-video-on-android-gadgets/"><u>New In 2024, From Silence to Soundtracks Tips for Blending Audio Into Video on Android Gadgets</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-understanding-and-turning-off-system-lockdown/"><u>Windows 11: Understanding & Turning Off System Lockdown</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-support-paths-for-common-windows-concerns/"><u>Efficient Support Paths for Common Windows Concerns</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-sluggish-outlook-on-your-computer/"><u>Sidestep Sluggish Outlook on Your Computer</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-conflicting-apps-in-windows-10/"><u>Dealing with 'Conflicting Apps' In Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/modifying-oculus-quest-2-for-windows-vr-use/"><u>Modifying Oculus Quest 2 for Windows VR Use</u></a></li>
<li><a href="https://win11.techidaily.com/winerror-solved-addressing-ms-store-0x80072f17/"><u>WinError Solved: Addressing MS Store 0X80072f17</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/streaming-mastery-with-obs-game-mode-for-2024/"><u>Streaming Mastery with OBS Game Mode for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-assembling-a-taskbar-on-windows-11-slate/"><u>The Ultimate Guide to Assembling a Taskbar on Windows 11 Slate</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/seamless-music-integration-transform-your-favorite-tunes-into-youtube-content/"><u>Seamless Music Integration  Transform Your Favorite Tunes Into YouTube Content</u></a></li>
<li><a href="https://win11.techidaily.com/from-basic-to-winning-converting-batch-to-executable/"><u>From Basic to Winning: Converting Batch to Executable</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-high-cpu-usage-by-wmi-service/"><u>Addressing High Cpu Usage by WMI Service</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-transitioning-from-rgb-to-srgb/"><u>[New] Transitioning From Rgb to Srgb</u></a></li>
<li><a href="https://win11.techidaily.com/mending-disconnected-google-drive-windows-filesystem/"><u>Mending Disconnected Google Drive Windows Filesystem</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/enjoy-youtube-on-iphoneipad-with-the-leading-ios-fb-video-downloader-for-2024/"><u>Enjoy YouTube on iPhone/iPad with the Leading iOS FB Video Downloader for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-error-0x0000004e-on-windows-11-systems/"><u>Conquering Error 0X0000004E on Windows 11 Systems</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/in-2024-masterful-archive-of-twitter-animations-at-your-fingertips/"><u>In 2024, Masterful Archive of Twitter Animations at Your Fingertips</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-the-ultimate-expertise-full-guide-to-record-your-macscreens/"><u>[Updated] The Ultimate Expertise  Full Guide to Record Your MacScreens</u></a></li>
<li><a href="https://win11.techidaily.com/decode-widows-code-to-unfreeze-handbrake/"><u>Decode Widows' Code to Unfreeze HandBrake</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-decrease-extras-in-win-11-context-list/"><u>How to Decrease Extras in Win 11 Context List</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-the-trouble-with-updates-code-0x80246007/"><u>Tackling the Trouble with Update's Code 0X80246007</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/learn-to-record-and-save-your-watching-experience-on-youtube-with-zero-costs-for-2024/"><u>Learn to Record and Save Your Watching Experience on YouTube with Zero Costs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-photo-overlays-for-windows-11/"><u>Adjusting Photo Overlays for Windows 11</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-6s-to-others-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 6s to others devices? | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-5-quick-methods-to-bypass-poco-f5-5g-frp-by-drfone-android/"><u>In 2024, 5 Quick Methods to Bypass Poco F5 5G FRP</u></a></li>
<li><a href="https://win11.techidaily.com/the-blueprint-how-to-enhance-your-workflow-via-menus/"><u>The Blueprint: How to Enhance Your Workflow via Menus</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-absence-of-monitor-on-startup/"><u>Remedy for Absence of Monitor on Startup</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-guide-to-file-compression-via-cli/"><u>The Essential Guide to File Compression via CLI</u></a></li>
</ul></div>
