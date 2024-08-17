---
title: Simultaneous Shutdown Techniques for Windowed Applications
date: 2024-08-16T00:40:56.303Z
updated: 2024-08-17T00:40:56.303Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Simultaneous Shutdown Techniques for Windowed Applications
excerpt: This Article Describes Simultaneous Shutdown Techniques for Windowed Applications
keywords: Windows Shutdown Methods,App-Window Shutdown Strategies,Simultaneous Close Apps,Coordinated Application Closure,Windowed Program Termination,Seamless Shutdown Procedures,Multiplexed Software Halt
thumbnail: https://thmb.techidaily.com/75afd5a2790c3528915ac28a66faf57312a6eb60abbc500be807cdf0c4c1fe06.jpg
---

## Simultaneous Shutdown Techniques for Windowed Applications

 Running multiple apps simultaneously can usually affect your PC’s performance. This means you might often want to close some programs to speed up your device. But here’s the thing—closing your apps one by one can be quite tedious.

 So, how can you simplify things and close your multiple apps simultaneously on Windows? Let’s find out.

## 1\. Use the Taskbar

 The Windows taskbar displays all your active and pinned programs. This means you can easily close your active apps by scrolling to the relevant taskbar icon and clicking the “close” button.

 The good news is that you can also use the taskbar to close multiple windows of the same program. However, you won’t be able to close different apps simultaneously using the taskbar.

 Here's how to close multiple windows of the same program on the taskbar:

1. Navigate to the taskbar and locate an app that has multiple active windows.
2. Right-click on the app and select the **Close all windows** option.

![Closing multiple windows on the taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/closing-multiple-windows-on-the-taskbar.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
## 2\. Use the Resource Monitor

 You probably know that you can [force close your PC programs](https://www.makeuseof.com/tag/how-to-kill-unresponsive-programs-without-the-task-manager/) using the Task Manager. But the problem is that this tool doesn’t let you close your programs simultaneously.

 Wondering if there's an alternative tool you can use? Try the Resource Monitor!

 Here are the steps for closing multiple apps simultaneously using the Resource Monitor:

1. Type **Resource Monitor** in the Start menu search bar and select the **Best match**.
2. Navigate to the **Overview** tab.
3. Check the boxes of the apps you want to close.
4. Right-click on one of the results and select the **End Process** option. This should simultaneously close all the programs you selected.

![Closing multiple apps using the Resource Monitor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/closing-multiple-apps-using-the-resource-monitor.jpg)

 Want to know the best part about using the Resource Monitor? This tool allows you to re-open multiple apps simultaneously with just a few clicks!

 Here's how to reopen your apps with the Resource Monitor:

1. Access the **Resource Monitor** by applying the previous steps.
2. Check the boxes of all the apps you want to re-open.
3. Right-click on one of the results and select **Resume Process**.

## 3\. Use the Command Prompt

![Person using a Windows PC while placing it on a lap](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Person-using-a-Windows-PC-while-placing-it-on-a-lap.jpg)

 The Command Prompt can help you troubleshoot PC issues, configure some system settings, and run your Windows apps.

 Interestingly, this tool can also help you simultaneously close multiple windows of the same app. However, the Command Prompt might not be the best option if you want to close different apps simultaneously.

 Here’s how you can close multiple windows of the same app using the Command Prompt:

1. Type **Command Prompt** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.

![Opening the Command Prompt using the Start menu search bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/opening-the-command-prompt-using-the-start-menu-search-bar.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->

 Let’s say you want to close multiple File Explorer windows simultaneously. To do that, type the following command in the Command Prompt and press **Enter**:

taskkill /f /im explorer.exe

 The “taskkill /f /im” command is the one that closes the program, and the “explorer.exe” command is the name of the app. To close multiple windows of your other apps, replace the “explorer.exe” part with the relevant command.

## 4\. Create a Batch Script for Closing Multiple Apps Simultaneously

![A person using a Windows device on a desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-person-using-a-Windows-device-on-a-desk.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->

 We’ve already discovered that the Command Prompt can only help you close multiple windows of the same app.

 But if you apply a few tricks, you can close multiple apps using some commands. However, you’d need to [create a batch script](https://www.makeuseof.com/tag/write-simple-batch-bat-file/) for that.

 Here's how you can create a batch script for closing multiple apps on Windows:

1. Press **Win + D** to access the desktop. Alternatively, check out the [various ways to access the Windows desktop](https://www.makeuseof.com/windows-quickly-access-desktop/).
2. Right-click on a blank space and select **New > Text Document**. This will create an untitled document on your desktop.

 Now, let’s say you want to close the **Snipping Tool** and the **Paint.net** app simultaneously. Here are the steps you need to follow:

1. Navigate to the desktop and double-click on the text document you’ve just created.
2. Type the following command to close the Snipping Tool:

taskkill /f /im SnippingTool.exe /T > nul

 Next, type the following command to close the Paint.net app:

taskkill /f /im paintdotnet.exe /T > nul

![Creating a Batch Script for Closing Multiple Apps Simultaneously](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/creating-a-batch-script-for-closing-multiple-apps-simultaneously.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->

 From there, follow these steps:

1. Press the **File** tab in the top-left corner of the text file.
2. Select the **Save As** option.
3. Type **Close Multiple Apps Simultaneously.bat** in the **File name** box.
4. Press the **Save** button.

 Now, you can close the Snipping Tool and the Paint.net app simultaneously by following these steps:

1. Press **Win + E** to access File Explorer.
2. Select the **Desktop** option on the left.
3. Click the **Close Multiple Apps Simultaneously.bat** batch file.

![Clicking a batch script on the desktop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/clicking-a-batch-script-on-the-desktop.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can add as many apps as you want to your batch script.

 And when using the batch script, ensure that it doesn’t end up closing some important apps by mistake. This means it might be worth regularly checking what’s on the script first before running it.

## 5\. Use the Close All Windows Tool

![The Close All Windows Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-close-all-windows-tool.jpg)

 You can also quickly close your multiple active apps using a third-party program like the [Close All Windows tool](https://www.softpedia.com/get/System/System-Miscellaneous/AA-Close-All-Windows.shtml). The tool is lightweight, which means it won’t take up much of your disk space.

 This app works almost like the Windows built-in Resource Monitor. However, it comes with a basic and easy-to-understand interface. When you open the tool, it immediately displays all your active apps. All you need to do is tick the relevant boxes and then click the **OK** button to close those apps.

 The tool displays all your apps and places them under a specific category. For example, it displays all your Google Chrome windows under the Google Chrome category.

 To select all the apps on the screen, press **Ctrl + A** or navigate to the **Command** tab and click **Select All**. And if you want to uncheck all the apps, press **Ctrl + D** or click the **Deselect All** option from the **Command** tab.

 You can customize the Close All Windows tool by clicking the **View** tab and ticking the relevant boxes. And if the tool seems a bit too complicated to use, then you can navigate to the **Help** tab to get some assistance.

**Download**: Close All Windows for [Windows](https://www.softpedia.com/get/System/System-Miscellaneous/AA-Close-All-Windows.shtml) (Free, subscription available)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## Close Your Multiple Apps Simultaneously With Just a Few Clicks

 It’s always frustrating when your Windows device suddenly becomes slow or buggy. In most cases, such issues are caused by running tons of apps simultaneously.

 Want a quick way to speed up your device? Close your multiple active programs simultaneously using the tips we’ve covered. And if you end up closing some apps by mistake, you can apply some quick tricks to restore them again.


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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-cutting-edge-techniques-for-private-yt-content-dissemination-in-gmail/"><u>[New] 2024 Approved  Cutting-Edge Techniques for Private YT Content Dissemination in Gmail</u></a></li>
<li><a href="https://win11.techidaily.com/11-different-ways-to-uninstall-software-in-windows-11/"><u>11 Different Ways to Uninstall Software in Windows 11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-pro-tips-for-kinemaster-dominance-plus-best-digital-platforms-on-the-web/"><u>2024 Approved  Pro Tips for KineMaster Dominance + Best Digital Platforms on the Web</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-enable-telnet-in-windows-11-and-11/"><u>3 Ways to Enable Telnet in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-fix-the-windows-11-mail-app-when-it-shows-html-code-for-emails/"><u>6 Ways to Fix the Windows 11 Mail App When It Shows HTML Code for Emails</u></a></li>
<li><a href="https://win11.techidaily.com/a-deeper-dive-into-your-computer-writes-mouse-secrets-of-windows-11/"><u>A Deeper Dive Into Your Computer' Writes: Mouse Secrets of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-deleting-files-without-a-click-in-windows/"><u>A Step-by-Step Guide to Deleting Files Without a Click in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-network-drives-through-explorer-pane/"><u>Accessing Network Drives Through Explorer Pane</u></a></li>
<li><a href="https://win11.techidaily.com/activating-prints-with-microsofts-shielded-browsing/"><u>Activating Prints with Microsoft's Shielded Browsing</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-0x800704b3-network-hurdles-in-win1011/"><u>Addressing 0X800704B3 Network Hurdles in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-incorrect-profile-errors-windows-1011-guide/"><u>Addressing Incorrect Profile Errors: Windows 10/11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-strategies-for-extending-shutdown-duration-in-windows-10/"><u>Advanced Strategies for Extending Shutdown Duration in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/altering-visual-angle-in-windows-configuration/"><u>Altering Visual Angle in Windows Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/assisting-users-with-erratic-swipes-on-windows-systems/"><u>Assisting Users with Erratic Swipes on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/automating-printer-removal-on-win11-devices/"><u>Automating Printer Removal on Win11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-remote-procedure-call-mishaps-in-windows/"><u>Avoiding Remote Procedure Call Mishaps in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/banish-already-in-use-errors-and-unique-device-naming/"><u>Banish 'Already in Use' Errors and Unique Device Naming</u></a></li>
<li><a href="https://win11.techidaily.com/bitlock-less-windows-defense-tactics-4-suggestions/"><u>BitLock-Less Windows Defense Tactics: 4 Suggestions</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-into-windows-passwords-the-11-easiest-ways-to-open-credential-manager/"><u>Breaking Into Windows Passwords: The 11 Easiest Ways to Open Credential Manager</u></a></li>
<li><a href="https://change-location.techidaily.com/can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-xiaomi-civi-3-disney-100th-anniversary-edition-drfone-by-drfone-virtual-android/"><u>Can I use iTools gpx file to catch the rare Pokemon On Xiaomi Civi 3 Disney 100th Anniversary Edition | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-honor-x50i-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Honor X50i | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719296331398-fixes-for-inadequate-screen-shots-in-windows-snip-and-sketch-app/"><u>Fixes for Inadequate Screen Shots in Windows’ Snip & Sketch App.</u></a></li>
<li><a href="https://sound-issues.techidaily.com/hdmi-problem-solutions-preventing-device-access-by-competing-software/"><u>HDMI Problem Solutions: Preventing Device Access by Competing Software</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/iphones-strategic-move-continuous-technological-progress/"><u>IPhone's Strategic Move: Continuous Technological Progress</u></a></li>
<li><a href="https://buynow-info.techidaily.com/non-stop-action-and-chuckles-in-plants-vs-zombies-battle-for-neighborville-a-complete-game-evaluation/"><u>Non-Stop Action & Chuckles in Plants Vs. Zombies: Battle for Neighborville: A Complete Game Evaluation</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/pinnacle-speed-windows-10-image-browser-for-2024/"><u>Pinnacle Speed Windows 10 Image Browser for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719330298923-self-host-your-local-free-windows-based-chatgpt-clone-using-gpt4all/"><u>Self-Host Your Local, FREE Windows-Based ChatGPT Clone Using GPT4All.</u></a></li>
<li><a href="https://extra-information.techidaily.com/step-by-step-guide-to-iphones-dynamic-images/"><u>Step-by-Step Guide to iPhone's Dynamic Images</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/the-instagram-savvy-strategists-guide-to-understanding-engagement-figures/"><u>The Instagram Savvy Strategist’s Guide to Understanding Engagement Figures</u></a></li>
<li><a href="https://howto.techidaily.com/vivo-y02t-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Vivo Y02T Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
</ul></div>
