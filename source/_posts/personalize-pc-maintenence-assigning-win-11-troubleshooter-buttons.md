---
title: "Personalize PC Maintenence: Assigning Win 11 Troubleshooter Buttons"
date: 2024-10-31T21:28:59.001Z
updated: 2024-11-01T23:43:53.094Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Personalize PC Maintenence: Assigning Win 11 Troubleshooter Buttons"
excerpt: "This Article Describes Personalize PC Maintenence: Assigning Win 11 Troubleshooter Buttons"
keywords: PC Maintenance Personalized,Win 11 Troubleshoot Guide,Personal Win 11 Tools,Customize Win 11 Buttons,Easy Win 11 Fixes,Optimizing Win 11 Settings,Tailor Win 11 Interface
thumbnail: https://thmb.techidaily.com/d8236c8823bf190018d4a9a0035905199e51992e3c45e7b977770451483aa69d.jpg
---

## Personalize PC Maintenence: Assigning Win 11 Troubleshooter Buttons

 Windows 11 and 10 include various troubleshooting tools you can open via Settings and the Control Panel. There are troubleshooters for fixing Bluetooth, internet, Windows Update, audio, hardware, printer, video, and MS Store app-related errors that arise. Those troubleshooters detect issues and either automatically apply or suggest potential fixes to resolve them.

 Adding troubleshooter shortcuts to Windows 11/10 will save you from rummaging through Settings or the Control Panel whenever you need to access them. You can create troubleshooter shortcuts on the Windows 11/10 desktop, taskbar, Start menu, and even context menu with the methods below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to a Set Up a Desktop Shortcut for Opening the Troubleshooting Applet

 Most users probably go through Settings to bring up troubleshooters. However, Control Panel’s Troubleshooting applet includes more troubleshooters than the Settings app. Adding a[desktop shortcut](https://www.makeuseof.com/what-is-desktop-shortcut-how-work/) for opening the applet will enable you to access all troubleshooters included within it more quickly.

 You can create a Troubleshooting shortcut on the Windows desktop in the following steps:

1. Right-click any part of the desktop area and select**New** .
2. Click the**Shortcut** option on the**New** submenu.  
![The Shortcut option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/shortcut-option.jpg)
3. Input**explorer shell:::{C58C4893-3BE0-4B45-ABB5-A63E4B8C8651}** inside the location box, and select the Create Shortcut wizard’s**Next** option.  
![The Create Shortcut window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-shortcut-window.jpg)
4. Erase the default shortcut title, and type**Troubleshooting Applet** in the text box.
5. Select**Finish** to add the Troubleshooting Applet desktop shortcut.  
![The Troubleshooting Applet desktop shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/troubleshooting-applet-shortcut.jpg)

 Double-click the new desktop shortcut you just added to open the Troubleshooting applet. There you can click**Programs** ,**Hardware and Sound** ,**Network and Internet** , or**System and Security** to view and access different categories of troubleshooters. Alternatively, select**View all** open to bring up a full list of troubleshooters. You can click any troubleshooter there to open it.

![The Troubleshooting applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-troubleshooting-applet.jpg)

 The Troubleshooting shortcut will have the same folder library icon as Explorer’s taskbar button. If you would prefer something else, you can change the icon via the shortcut’s properties window. Check out our guide about[how to customize icons on Windows](https://www.makeuseof.com/tag/customize-icon-windows/) for details.

## How to Set Up Taskbar and Start Menu Troubleshooting Shortcuts

 You can easily convert the Troubleshooting Applet desktop shortcut into a taskbar or Start menu one. To do so in Windows 11, click the Troubleshooting Applet shortcut with the right mouse button and select**Show more options** . Select**Pin to taskbar** on the classic menu to stick the same shortcut on the taskbar. Or click**Pin to Start** to have one for opening the Troubleshooting applet from the pinned area of the Start menu.

![The Pin to taskbar option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/pin-to-taskbar-option.jpg)

 Then you may as well remove the desktop shortcut if a taskbar or Start menu one is preferred. Right-click Troubleshooting Applet to select**Delete** (the trash bin icon in Windows 11).

## How to Set Up a Troubleshooting Hotkey

 A Troubleshooting desktop shortcut can also become a convenient hotkey in a few quick steps. All you have to do is set a key combination for activating the desktop shortcut. Then you can open the Troubleshooting applet by pressing a**Ctrl** +**Alt** key combo. These are the steps for setting up a hotkey that opens the Troubleshooting applet:

1. Create a desktop shortcut for opening the Troubleshooting applet as outlined in the first method.
2. Right-click the Troubleshooting shortcut and select**Properties** .
3. Click inside the box labeled**Shortcut key** .
4. Press**T** (for troubleshooting) to establish a**Ctrl** +**Alt** +**T** key combination.  
![The Shortcut key box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/shortcut-key-option.jpg)
5. Select**Apply** to save your new troubleshooting hotkey.
6. Click**OK** or**X** to close the Shortcut tab and window.

 Now you can access the Troubleshooting applet with a key combo. Press**Ctrl** +**Alt** +**T** to open that applet and access its troubleshooters. That hotkey depends on the desktop shortcut you set it for. So, you’ve got to leave the shortcut on the desktop.

## How to Set Up Shortcuts for Opening Specific Troubleshooters

 You can also set up shortcuts for opening any specific troubleshooters included within the Troubleshooting Control Panel applet. Each troubleshooter there has a pack ID with which you can set up a desktop shortcut for opening it. You can set up a troubleshooter shortcut in such a way via the Create Shortcut wizard with the following command:

`msdt.exe /id <diagnostic_id>`

 The above command must include an actual diagnostic\_id for the troubleshooter. This[MSDT page](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2008-R2-and-2008/ee424379%28v=ws.10%29?redirectedfrom=MSDN) has a list of troubleshooting pack IDs you can include in that command. These are the diagnostic ID commands for some of the more useful troubleshooters:

`msdt.exe /id WindowsUpdateDiagnostic  
  
msdt.exe /id SearchDiagnostic  
  
msdt.exe /id DeviceDiagnostic  
  
msdt.exe /id PrinterDiagnostic  
  
msdt.exe /id NetworkDiagnosticsWeb  
  
msdt.exe /id AudioPlaybackDiagnostic`

 You can set up a desktop shortcut for a specific troubleshooter much the same as the Troubleshooting applet. Go through the same steps in this guide’s instructions for setting up a desktop shortcut, but input a troubleshooter diagnostic ID command at step three instead. Enter a different name for the shortcut in step four, and select the**Finish** option.

![The Windows Update troubleshooter command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-update-troubleshooter-command.jpg)

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137976/21526" target="_top" id="2137976">
  <img src="//a.impactradius-go.com/display-ad/21526-2137976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137976/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Double-clicking that desktop shortcut will open whatever troubleshooter you set it to with the diagnostic ID command. Then you can also pin that desktop shortcut to the taskbar or Start menu just the same as the Troubleshooting applet one. Or set up a hotkey for opening the troubleshooting tool as outlined in this guide’s keyboard shortcut instructions.

![The Windows Update troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-update-troubleshooter-and-shortcut.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997717/19272" target="_top" id="1997717">
  <img src="//a.impactradius-go.com/display-ad/19272-1997717" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997717/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Add a Troubleshooters Submenu to the Context Menu

 The right-click context menu is another place you can add Troubleshooting shortcuts in Windows 11/10\. You can set up a**Troubleshooters** submenu on the Windows 11/10 context menu that includes shortcuts for opening different parts of the Troubleshooting applet. To do that, you only need to download and run a premade registry script like this:

1. Open the[Add Troubleshooters Context Menu Softpedia page](https://www.softpedia.com/get/Tweak/System-Tweak/Add-Troubleshooters-Context-Menu-in-Windows-10.shtml) .
2. Select that registry script’s**Download Now** option.
3. Click the**Secure Download (US)** option.
4. Go into File Explorer (press**Win** +**E** to open), and bring up the directory containing the registry script’s ZIP archive.  
![The Extract Compressed Folders tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/extract-compressed-folder-tool.jpg)
5. Select to extract the troubleshooters-context-menu.zip archive. Our guide to[unzipping ZIP files on Windows](https://www.makeuseof.com/unzip-files-windows-10/) includes instructions for extracting these archives.
6. Open the extracted troubleshooters-context-menu folder.
7. Double-click the**Add Troubleshooters To Desktop Context Menu.reg** file.  
![The troubleshooters-context-menu folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/troubleshooters-context-menu-folder.jpg)
8. Click**Yes** on the prompt that asks for user confirmation to apply the script.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886073/19272" target="_top" id="1886073">
  <img src="//a.impactradius-go.com/display-ad/19272-1886073" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886073/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You will now see a new**Troubleshooters** submenu on your desktop’s context menu. Right-click any space within the desktop wallpaper area and select**Show more options** on Windows 11’s context menu. Move the cursor over the**Troubleshooters** submenu to view its shortcuts.

![The Troubleshooters submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/troubleshooters-option.jpg)

 There you can select**Classic Troubleshooting applet** to bring up the Troubleshooting home screen in the Control Panel. Select**All Categories** to open the full list of troubleshooters. Or click**Programs** ,**Hardware and Sound** ,**Network and Internet** , and**System Security** to view category pages for opening troubleshooters.

 The troubleshooters-context-menu folder also includes a script for removing the Troubleshooters submenu. Double-click**Remove Troubleshooters From Desktop Context Menu.reg** in that folder to run that script. Then select**Yes** to erase the submenu from the context menu.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130890/7443" target="_top" id="2130890">
  <img src="//a.impactradius-go.com/display-ad/7443-2130890" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130890/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Make Some Shortcuts for Accessing Troubleshooters in Windows

 So, now you can create Windows shortcuts for opening the Troubleshooting applet and more specific troubleshooters in various ways. You can create a general Troubleshooting Control Panel desktop, taskbar, keyboard, or context menu shortcut for accessing all troubleshooting tools. Or set up shortcuts that give you more direct access to the specific troubleshooting tools you utilize more regularly.

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
<li><a href="https://vp-tips.techidaily.com/new-premium-psd-free-3d-text-treasure-hunt/"><u>[New] Premium PSD Free 3D Text Treasure Hunt</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/solved-windows-11-100-disk-usage-in-task-manager/"><u>[SOLVED] Windows 11 100% Disk Usage in Task Manager</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-perfect-playback-overcoming-mutes-on-linkedin-video-posts/"><u>[Updated] 2024 Approved Perfect Playback Overcoming Mutes on LinkedIn Video Posts</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-ultimate-top-8-converter-list-for-sub-to-srt/"><u>[Updated] In 2024, Ultimate Top 8 Converter List for Sub to SRT</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-night-avenger-black-vs-day-defender-silver/"><u>[Updated] Night Avenger (Black) VS Day Defender (Silver)</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-seamless-clip-recording-solutions-for-2024/"><u>[Updated] Seamless Clip Recording Solutions for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-art-of-selecting-podcasts-for-iphone-devices/"><u>[Updated] The Art of Selecting Podcasts for iPhone Devices</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/8-safe-and-effective-methods-to-unlock-your-apple-iphone-se-2022-without-a-passcode-by-drfone-ios/"><u>8 Safe and Effective Methods to Unlock Your Apple iPhone SE (2022) Without a Passcode</u></a></li>
<li><a href="https://win11.techidaily.com/a-buyers-blueprint-essential-steps-for-your-win-pc-purchase/"><u>A Buyer’s Blueprint: Essential Steps for Your Win PC Purchase</u></a></li>
<li><a href="https://win11.techidaily.com/1719347210677-access-display-settings-right-click-on-the-desktop-and-select-display-settings/"><u>Access Display Settings: Right-Click on the Desktop and Select Display Settings.</u></a></li>
<li><a href="https://win11.techidaily.com/adapting-to-new-horizons-migrating-apps-for-a-windows-11-laptop/"><u>Adapting to New Horizons: Migrating Apps for a Windows 11 Laptop</u></a></li>
<li><a href="https://win11.techidaily.com/aligning-chromes-timeline-error-on-windows-machines/"><u>Aligning Chrome's Timeline Error on Windows Machines</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-unending-enter-password-interruptions-in-windows/"><u>Avoiding Unending Enter Password Interruptions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/blueprint-for-efficiently-updating-windows-solo/"><u>Blueprint for Efficiently Updating Windows Solo</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-pc-speed-post-media-downloads-on-w11/"><u>Boosting PC Speed Post Media Downloads on W11</u></a></li>
<li><a href="https://tech-haven.techidaily.com/guiding-kids-in-the-age-of-ai-5-essential-practices-for-responsible-chatgpt-use/"><u>Guiding Kids in the Age of AI: 5 Essential Practices for Responsible ChatGPT Use</u></a></li>
<li><a href="https://win11.techidaily.com/1719228805701-quick-jot-down-techniques-in-windows-11-no-apps/"><u>Quick Jot-Down Techniques in Windows 11, No Apps!</u></a></li>
</ul></div>

