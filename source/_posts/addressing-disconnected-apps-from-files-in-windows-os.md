---
title: Addressing Disconnected Apps From Files in Windows OS
date: 2024-08-15T23:14:57.104Z
updated: 2024-08-16T23:14:57.104Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Disconnected Apps From Files in Windows OS
excerpt: This Article Describes Addressing Disconnected Apps From Files in Windows OS
keywords: Fix Windows File-App Link,Untangle Windows App Deletion,Resolve Windows App Isolation,Reconnect Files to Windows Programs,Stop Disconnected Windows Apps,Restore Apps From Windows Files,Prevent Windows App Disconnection
thumbnail: https://thmb.techidaily.com/aef9f8cb7b85429cf28cb38f2d49cc0528e1c43a7556fd8a130e20454901702b.jpg
---

## Addressing Disconnected Apps From Files in Windows OS

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

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
4. If it's not there, right-click in the blank area and go to**New > String Value** . Then rename it to**"IsShortcut** .**"**  
![Create and Rename the New String Value in Windows Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/6.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
5. If the string value is already there, right-click on it and select**Delete** .  
![Select Delete by Right-clicking on the String Value in Windows Registry Editor App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/7.jpg)
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. After that, follow step four to recreate it. Don't forget to rename it appropriately so you don't encounter any issues.
7. Restart your device once after that.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Do You Encounter the Error When Opening Folders? Follow These Tips

 If you get the "This file does not have an app associated with it" error when opening folders, try these checks:

* Restart File Explorer (see [how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) for tips).
* If you're opening a folder by searching it in Windows Search or Quick Access, consider opening it directly from File Explorer.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
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
<li><a href="https://eaxpv-info.techidaily.com/new-finding-a-different-way-to-naming-your-channel-with-filmora-for-2024/"><u>[New] Finding a Different Way to Naming Your Channel with Filmora for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/1716984558413-new-how-to-remove-background-noise-from-your-youtube-video/"><u>[New] How To Remove Background Noise From Your YouTube Video</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-multimedia-mac-recording-software-with-sound-for-2024/"><u>[New] Multimedia Mac Recording Software with Sound for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-how-to-generate-stellar-podcast-title-ideas/"><u>2024 Approved  How to Generate Stellar Podcast Title Ideas</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-mac-enthusiasts-selection-of-premier-editing-suites/"><u>2024 Approved  Mac Enthusiasts' Selection of Premier Editing Suites</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-honor-x7b-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Honor X7b | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/30-days-in-football-fantasy-how-to-play-ocm-for-no-charge/"><u>30 Days in Football Fantasy: How to Play OCM for No Charge</u></a></li>
<li><a href="https://win11.techidaily.com/8-things-to-remember-before-you-clean-install-windows/"><u>8 Things to Remember Before You Clean Install Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-complete-guide-on-using-w11s-automated-hdr-feature/"><u>A Complete Guide on Using W11's Automated HDR Feature</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-typing-mastering-windows-powertoys/"><u>Accelerate Typing: Mastering Windows PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/access-banishment-4-streamlined-steps-for-stripping-win11-of-users/"><u>Access Banishment: 4 Streamlined Steps for Stripping Win11 of Users</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disconnected-files-in-steam-library/"><u>Addressing Disconnected Files in Steam Library</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-secure-boot-grayout-windows-bios-fix-guide/"><u>Addressing Secure Boot Grayout: Windows BIOS Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-unsuccessful-java-vm-startup/"><u>Addressing the Unsuccessful Java VM Startup</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tips-for-isolating-subjects-in-photography/"><u>Advanced Tips for Isolating Subjects in Photography</u></a></li>
<li><a href="https://win11.techidaily.com/automatic-empty-recycle-bin-in-windows-step-by-step/"><u>Automatic Empty Recycle Bin in Windows Step by Step</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-unauthorized-user-error-on-windows-11-and-11/"><u>Avoiding Unauthorized User Error on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-update-failure-code-0x800f0845/"><u>Avoiding Update Failure - Code 0X800F0845</u></a></li>
<li><a href="https://win11.techidaily.com/bargain-bonanza-black-friday-612-for-lifelong-win10-life/"><u>Bargain Bonanza: Black Friday - $6.12 for Lifelong Win10 Life</u></a></li>
<li><a href="https://win11.techidaily.com/boot-security-errors-squashed-in-5-easy-steps-for-windows-users/"><u>Boot Security Errors Squashed in 5 Easy Steps for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/break-the-code-essential-steps-to-game-folder-opening/"><u>Break the Code: Essential Steps to Game Folder Opening</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-error-x80072f30-in-microsoft-store-on-windows/"><u>Breaking Down Error X80072F30 in Microsoft Store on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-wi-fi-setup-barriers-filling-action-voids-on-pc/"><u>Breaking Down Wi-Fi Setup Barriers: Filling Action Voids on PC</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-adjusting-immovable-gif-sizes-for-windows-users-of-discord/"><u>Breaking Free: Adjusting Immovable GIF Sizes for Windows Users of Discord</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-a-locked-lenovo-thinkphone-phone-by-drfone-android/"><u>How to Reset a Locked Lenovo ThinkPhone Phone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-solve-recurring-audio-issues-on-your-windows-11-device-effortlessly/"><u>How to Solve Recurring Audio Issues on Your Windows 11 Device Effortlessly</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-is-greyed-out-on-apple-iphone-12-pro-how-to-bypass-by-drfone-ios/"><u>In 2024, Apple ID is Greyed Out On Apple iPhone 12 Pro How to Bypass?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-fix-oem-unlock-missing-on-xiaomi-13-ultra-by-drfone-android/"><u>In 2024, How To Fix OEM Unlock Missing on Xiaomi 13 Ultra?</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-navigating-advanced-editing-techniques-for-immersive-video-in-premiere-pro/"><u>In 2024, Navigating Advanced Editing Techniques for Immersive Video in Premiere Pro</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-nubia-red-magic-9-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, Pokémon Go Cooldown Chart On Nubia Red Magic 9 Pro+ | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/intel-wi-fi-6e-ac-9560-driver-download-and-installation-tutorial/"><u>Intel Wi-Fi 6E (AC 9560) Driver Download & Installation Tutorial</u></a></li>
<li><a href="https://techidaily.com/is-your-lava-blaze-2-5g-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Lava Blaze 2 5G working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719224494525-revive-w11s-chrome-immediate-troubleshooting-advice/"><u>Revive W11's Chrome - Immediate Troubleshooting Advice</u></a></li>
<li><a href="https://win11.techidaily.com/1719369059725-streamline-facebook-messenger-on-your-pc-now/"><u>Streamline Facebook Messenger On Your PC Now!</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-essential-fcpx-add-ons-top-10-free-and-paid-plugins-you-need/"><u>Updated Essential FCPX Add-Ons Top 10 Free and Paid Plugins You Need</u></a></li>
</ul></div>
