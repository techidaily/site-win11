---
title: Windows 11 Icons Lost? Here's How to Fix It
date: 2024-11-30T19:50:59.334Z
updated: 2024-12-07T09:47:10.397Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Windows 11 Icons Lost? Here's How to Fix It
excerpt: This Article Describes Windows 11 Icons Lost? Here's How to Fix It
keywords: Windows 11 Icon Issue,Fixing Icons on W11,Restore Windows Icons,Reset Icons in Win11,Reinstall Icons W11,Recover Lost W11 Icons,Repair Win11 Icon Problems
thumbnail: https://thmb.techidaily.com/2bedac5967dc2670719be619f6173feb9adb0500628b631392642fa41c539d87.jpg
---

## Windows 11 Icons Lost? Here's How to Fix It

 Desktop icons on Windows 11 give you quick access to your favorite apps, files, folders, and more. But what if these desktop icons vanish without a trace? How do you get the icons back?

 If you're facing this baffling problem, this guide will help you restore the missing desktop icons in Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Enable Show Desktop Icons

 On Windows 11, you can show or hide desktop icons with a couple of clicks. So, if you’ve accidentally hidden your desktop icons, getting them back is fairly easy.

 Right-click anywhere on an empty spot on your desktop and select**View > Show desktop icons** . Once you do that, all your hidden desktop icons should reappear.

![Show Desktop Icons on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Show-Desktop-Icons-on-Windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Check Desktop Icon Settings

 If you're only missing a few desktop icons, such as This PC, Recycle Bin, Control Panel, and others, you may have disabled them in the "Desktop Icon Settings" window. In that case, you can use the following steps to re-enable those desktop icons.

1. Open the**Start menu** and click the**gear icon** to launch the Settings app.
2. Select**Personalization** from the left sidebar.
3. Select**Themes** .
4. Under**Related settings** , click on**Desktop icon settings** .
5. Under the**Desktop icons** section, use the checkboxes to enable the icons you want on your desktop.
6. Click**Apply** followed by**OK** to save the changes.  
![Desktop Icon Settings Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Desktop-Icon-Settings-Window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/97ydpSmzTJw?si=tFcelmtQX4u-b3u5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, your icons should appear on the desktop.

## 3\. Restart Windows Explorer

 The Windows Explorer process handles the Graphical User Interface (GUI) for a number of utilities, including the desktop. If this service encounters any issues, your desktop and taskbar icons may disappear. If this is the case, you can restart the Windows Explorer process to fix the problem.

1. Right-click on the Start icon or press**Win + X** to open the Power User menu.
2. Select**Task Manager** from the list.
3. In the**Processes** tab, locate**Windows Explorer** . Right-click on it and select**Restart** .  
![Restart Windows Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Restart-Windows-Explorer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Your taskbar will disappear for a brief moment and then reappear. Following this, your desktop icons should be visible.

## 4\. Rebuild Icon Cache

 Another reason why desktop icons on Windows may appear broken or go missing is if the existing icon cache data is corrupt. In that case, you can try clearing the corrupted icon cache data. This will force Windows to rebuild the icon cache from scratch and resolve your problem.

To rebuild icon cache on Windows 11:

1. Press**Win + S** to open the search menu.
2. Type**command prompt** in the box and select**Run as administrator** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Paste the following command in the console and press**Enter** to navigate to the directory where Windows stores the icon cache.  
`cd /d %userprofile%\AppData\Local\Microsoft\Windows\Explorer`
5. Run the following command to terminate the Explorer process:  
`taskkill /f /im explorer.exe`
6. Paste this command and press**Enter** to delete icon cache files:  
`del iconcache*`  
![Rebuild Icon Cache Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Rebuild-Icon-Cache-Windows.jpg)
7. Finally, type in the following text and hit**Enter** to restart Explorer:  

`Explorer.exe`

 Once you complete the above steps, restart your PC and see if the desktop icons appear.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Update Your PC’s Graphics Driver

 An outdated graphics driver on Windows can also lead to such anomalies. You can try updating the faulty driver using Device Manager to see if that helps. Here's how to do it.

1. Press**Win + S** to open the search menu.
2. Type**device manager** in the search box and select the first result that appears.
3. Expand**Display adapters** .
4. Right-click on your graphics driver and select**Update driver** .
5. Select**Search automatically for drivers** to let Windows find and install the best drivers.  
![Update Graphics Driver on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Update-Graphics-Driver-on-Windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the issue persists even after updating the driver, your graphics driver may be corrupt. In that case, you'll need to reinstall the graphics driver on your PC. Refer to our guide on[how to fix corrupt drivers on Windows](https://www.makeuseof.com/how-to-fix-corrupt-drivers-on-windows-10/) for more instructions on how to fix this.

## 6\. Check the Group Policy Settings

 The Group Policy Editor lets you make various system-wide changes on your Windows computer. If desktop icons are disabled from the Group Policy Editor, you won’t be able to add or remove desktop icons no matter what you do. To fix this, you must disable this “Hide and disable all items on the desktop” from the Group Policy Editor.

 Note that you can only access the Group Policy Editor on Windows 11 Professional, Enterprise, and Education editions. If you’re running Windows 11 Home, check our guide on[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Click the magnifying icon on the taskbar to open the search menu.
2. Type**gpedit.msc** in the box and press**Enter** . This will open the Local Group Policy Editor.
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Desktop** .
4. Double-click the**Hide and disable all items on the desktop** policy on your right.
5. Select**Not configured** or**Disabled** .
6. Click**Apply** followed by**OK** .  
![Enable Desktop Icons on Windows 11 via Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Enable-Deskop-Icons-on-Windows-11-via-Group-Policy-Editor-1.jpg)

## 7\. Perform a System Restore

 There's a chance that a recent system change is to blame for the missing desktop icons in Windows 11\. If you can't figure out what it is, you can use System Restore to restore Windows to a previous state.

Follow these steps to perform a system restore on Windows:

1. Press**Win + R** to open the Run dialog box.
2. Type**sysdm.cpl** in the box and press**Enter** .
3. Under the**System Protection** tab, click on**System Restore** .
4. Click**Next** .
5. Select a restore point before the issue first appeared and hit**Next** .
6. Click on**Finish** .  
![System Restore Dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/System-Restore-Dialog.jpg)

 Wait for Windows to reboot and revert to the specified restore point. Following that, your desktop icons should appear.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 8\. Manually Restore the Desktop Shortcut Icons

 If your desktop icons are still missing at this point, you can try restoring them manually.

 To add an icon to the desktop in Windows 11, open the**Start menu** and click on**All apps** . Scroll down to the app you want to add to the desktop. Finally, drag the app shortcut to your desktop.

![Create Desktop Shortcut From Start Menu in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Create-Desktop-Shortcut-From-Start-Menu-in-Windows.jpg)

 Alternatively, you can create a shortcut on your desktop by using the Create Shortcut wizard. To do so, right-click anywhere on the desktop and select**New > Shortcut** . Then, click the**Browse** button to locate the file, folder, or app you want to add to your desktop. Then, click**Next** followed by**Finish** .

 We covered this topic in more detail in our guide to[how to add icons to the desktop on Windows](https://www.makeuseof.com/how-to-add-icon-to-desktop-windows/) .

## Restore the Missing Desktop Icons on Windows 11

 Hopefully, the above-mentioned solutions have helped you restore the missing desktop icons on Windows 11 and things are back to normal. However, if none of the above solutions work, you may have to reset your Windows 11 PC as a last resort.

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
<li><a href="https://youtube-videos.techidaily.com/new-dive-deep-into-unreal-worlds-with-these-titles/"><u>[New] Dive Deep Into Unreal Worlds with These Titles</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-innovative-practices-for-online-learning-archives-for-2024/"><u>[New] Innovative Practices for Online Learning Archives for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-quintessential-stop-motion-films-a-top-15-list/"><u>[New] Quintessential Stop-Motion Films A Top 15 List</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-secure-your-animated-gifs-with-these-winning-recording-software-on-pc/"><u>[New] Secure Your Animated GIFs with These Winning Recording Software on PC</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-synthesizing-elements-crafting-a-captivating-youtube-video-start/"><u>[Updated] Synthesizing Elements Crafting a Captivating YouTube Video Start</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/compact-video-summary-key-insights-unveiled/"><u>Compact Video Summary Key Insights Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/create-a-fascinating-windows-11-display-with-lively-wallpaper/"><u>Create a Fascinating Windows 11 Display with Lively Wallpaper</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-aged-media-with-madvr-on-windows-platform/"><u>Elevate Aged Media with MadVR on Windows Platform</u></a></li>
<li><a href="https://win11.techidaily.com/forcefully-disconnect-and-delete-printer-in-modern-windows-os/"><u>Forcefully Disconnect & Delete Printer in Modern Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-handle-erroneous-updates-deciphering-code-0x30017/"><u>How to Handle Erroneous Updates: Deciphering Code 0X30017</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-microsofts-driver-verification-hurdles/"><u>How to Overcome Microsoft's Driver Verification Hurdles</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-apeaksofts-screen-tech-revolution-2023-review/"><u>In 2024, Apeaksoft's Screen Tech Revolution 2023 Review</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Samsung Galaxy M14 4G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-with-wintoys-the-compact-guidebook/"><u>Mastering Windows with WinToys: The Compact Guidebook</u></a></li>
<li><a href="https://buynow-info.techidaily.com/monoprices-affordable-graphics-tablet-tested-top-features-low-cost/"><u>Monoprice's Affordable Graphics Tablet Tested: Top Features, Low Cost</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-screenshot-stash/"><u>Navigating Windows Screenshot Stash</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-cropping-videos-in-avidemux-a-comprehensive-guide-for-beginners-and-pros/"><u>New Cropping Videos in Avidemux A Comprehensive Guide for Beginners and Pros</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-a-system-identifier-mistake-in-win11/"><u>Remedying a System Identifier Mistake in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/tailored-hotkeys-for-volume-control-in-the-newest-windows-version/"><u>Tailored Hotkeys for Volume Control in the Newest Windows Version</u></a></li>
</ul></div>

