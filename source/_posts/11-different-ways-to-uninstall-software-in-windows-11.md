---
title: 11 Different Ways to Uninstall Software in Windows 11
date: 2024-07-13T11:12:20.239Z
updated: 2024-07-14T11:12:20.239Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 11 Different Ways to Uninstall Software in Windows 11
excerpt: This Article Describes 11 Different Ways to Uninstall Software in Windows 11
keywords: Win11 Uninstall Guide,Remove Windows Apps Easily,Windows 11 Software Removal,Installation Toolkit,Deleting Programs Quickly,Win11 Clean Slate,Effective Windows Cleanup
thumbnail: https://thmb.techidaily.com/ccf2cd6688a4adcaeda8d922b0b91ea561ec3cf2936a8b4a71d20d4455d103fb.jpg
---

## 11 Different Ways to Uninstall Software in Windows 11

 Most Windows users need to uninstall software now and again. The more software you install, the less free drive storage space you’ll have. Removing programs is the best way to retrieve drive storage space on your PC.

 There are various ways you can uninstall software in Windows 11\. Most users will probably be familiar with Windows’ built-in "Programs and Features" uninstaller. However, utilizing that uninstaller is not necessarily the best way to remove software; and sometimes you might have to try different methods. These are seven ways you can remove software packages in Windows 11\.

## 1\. Uninstall Software in the Control Panel

 The Control Panel is the uninstallation method most users will likely be familiar with. The Control Panel includes the Programs and Features applet. That’s an applet with which you can uninstall desktop apps that run on computers with x86 system architecture.

 Programs and Features is becoming a little outdated compared with some third-party uninstallers. It doesn’t always fully erase all files, folders, and registry entries for uninstalled software, which leaves behind some leftovers. Furthermore, Microsoft hasn’t updated Programs and Features to include UWP (Universal Windows Platform) apps for uninstalling. This is how to uninstall software with that applet.

1. Right-click **Start** on the taskbar and select the Power User’s menu **Run** shortcut.
2. Type **appwiz.cpl** into Run.
3. Click **OK** to bring up the Programs and Features window.
4. Select a software package to remove.
5. Click the **Uninstall** button.  
![programs-and-features-applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/programs-and-features-applet.png)
6. Then select **Yes** on any confirmation dialog boxes that might pop up.
7. An uninstaller wizard for the software might then open. Go through that wizard to select the required uninstall options.

## 2\. Uninstall Software in Settings

 As you can’t remove Microsoft Store apps with Programs and Features, you’ll probably need to uninstall some software via Settings. Settings includes an **Apps & features** tab from which you can select and uninstall UWP apps. You can uninstall software in Settings like this.

1. Press **Win + I** to launch Settings.
2. Click the **Apps** tab.
3. Select **Apps and features** to view a list of installed software.  
![The Apps & features tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/apps--features-in-settings.png)
4. Click a three-dot button on the right side of an app to select **Uninstall**.  
![uninstall-option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/uninstall-option.png)

## 3\. Uninstall Software via the Start Menu

 The Start menu lists most of the desktop and UWP apps installed on your desktop or laptop. That menu provides handy context menu shortcuts for uninstalling software. These are the steps for removing software via the Start menu.

1. Click the **Start** taskbar button for opening the menu.
2. Select the **All apps** menu option.
3. Right-click an app to remove and select **Uninstall**.  
![programs-and-features-applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/programs-and-features-applet.png)
4. If the software has a folder on the Start menu, click the folder to expand it. Then right-click the app in the folder to select its **Uninstall** option.

## 4\. Uninstall Software via File Explorer

 Many desktop software packages will have uninstall.exe files in their folders you can click to uninstall them with. To do so, you’ll need to find their uninstall.exe files within Explorer. This is how you remove software via File Explorer.

1. Press the **Win + E** key combination to open File Explorer.
2. Open the installation folder for the software you need to uninstall. If you stick with default installation directories, it will probably be in the "Program Files" folder.
3. Then have a look for an uninstall.exe file within the software folder.  
![The uninstall.exe file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/uninstallexe-file.png)
4. Double-click the uninstall.exe to open an uninstall window.
5. Select the required options in the uninstaller window to remove the software.

## 5\. Remove Software With the Command Prompt

 The Command Prompt is one of two command-line interpreters in Windows 11\. That has a Windows Management Instrumentation Command-line utility (WMIC) you can uninstall software with. If you prefer command-line methods, you can uninstall software with Command Prompt’s WMIC tool as follows.

1. Click the search button (magnifying glass icon) on Windows 11’s taskbar button.
2. Enter **Command Prompt** to find that app.
3. Select the **Run as administrator** option for the Command Prompt search result.
4. Input **wmic** in the Prompt and press Return.
5. Type in this command and press **Enter**:  
`product get name`
6. Note down the name of the software you want to uninstall from the list. You’ll need to include that name within the uninstall command.  
![The product get name command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/product-get-name-command.png)
7. Then input this command:  
`product where name="program name" call uninstall`
8. Press **Enter** to run the command.  
![The uninstall software Command Prompt command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/uninstall-software-command.png)
9. Then press the **Y** key and press **Return** to confirm.
10. You’ll need to replace the program name in the command specified above with the software title you noted down. For example, this is the command for uninstalling Epic Games Launcher:

`product where name="Epic Games Launcher" call uninstall`

## 6\. Remove Software With PowerShell

 You can’t uninstall some built-in Windows UWP apps, such as Camera and Photos, in Settings. If you want to remove some of those built-in apps, you can do so with this PowerShell command-line method. Follow the steps below to uninstall software with PowerShell.

1. Open Windows 11’s search tool by pressing **Win** or using the search bar on the taskbar.
2. Type **PowerShell** in the search box to find that command-line interpreter.
3. Right-click Windows Powershell’s search result to select a **Run as administrator** option.
4. To view an app list, type in this command and press **Return**:  
`Get-AppxPackage`
5. Find the app you want to uninstall in the list, and note down the PackageFullName specified for it. You can copy the PackageFullName by selecting its text and pressing the **Ctrl + C** hotkey.  
![The Get-AppxPackage command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/get-appxpackage-command.png)
6. Then input this uninstall app command and press **Return**:  
`Remove-AppxPackage [App Name]`

![The Remove-AppxPackage command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/remove-apppackage.png)

 Make sure you replace **\[App Name\]** in that command with the PackageFullName for the app you want to uninstall. A command to uninstall Edge would look like this:

`Remove-AppxPackage Microsoft.MicrosoftEdge_44.19041.1266.0_neutral__8wekyb3d8bbwe`

## 7\. Remove Software With Third-Party Uninstallers

 There are numerous third-party uninstaller tools for Windows 11/10 with which you can uninstall both desktop software and UWP apps. Many of them include options for erasing the leftover residual files and registry keys from uninstalled software. Thus, the best third-party uninstaller utilities uninstall software more thoroughly than Programs and Features, which makes them preferable alternatives.

 Some third-party uninstallers even enable users to batch uninstall software packages, which is a handy feature. IObit Uninstaller is a freeware uninstaller tool that incorporates such a feature. This guide to [batch uninstalling software with IObit Uninstaller](https://www.makeuseof.com/windows-10-iobit-uninstaller-batch-uninstall/) provides details about how you can utilize that feature.

## 8\. Uninstall Software via the Search Tool

 Aside from finding software with Windows 11’s search tool, you can also select to uninstall software from there. This is how you can uninstall software with the search tool:

1. To access the file finder utility, click **Search** on the taskbar or simultaneously press the **Windows** logo and **S** keys.
2. Enter the name of the software you want to uninstall in the search tool.
3. Click the **Uninstall** option for the matching software search result.  
![The Uninstall option in Windows 11's search tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-uninstall-option-in-the-search-tool.jpg)
4. If the software you want to install isn’t the best match, right-click its search result and select **Uninstall**.

## 9\. Uninstall Software With Gaming Clients

 Many users install games with gaming clients, such as Steam and Epic Games Launcher. If you’ve installed a game with a gaming client, you can also uninstall it with the same software. You can do so by selecting the uninstall option for a game within the client software. This [how-to-uninstall Steam games article](https://www.makeuseof.com/how-to-uninstall-steam-games-reinstall/) tells you how to remove games within Steam.

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/uninstall-option-in-epic-games.jpg)

## 10\. How to Uninstall Software With Registry Editor and Run

 Utilizing the Registry Editor for removing software packages is not something many users will consider. However, you can remove software by entering the UninstallString values for them shown in the registry into Run. It might be necessary to sometimes utilize this method to remove software packages for which uninstall errors occur. This is how you can uninstall software with the Registry Editor and Run apps:

1. Start the Registry Editor, which you can access with the methods outlined in this [guide to opening the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
2. Next, go to this **Uninstall** key location:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Uninstall`
3. Select a key with a name that matches the software you want to install.
4. Double-click **UninstallString** to bring up a window for editing the string.
5. Select the text in the **Value data** box and press **Ctrl** \+ **C** to copy.  
![The value data for an UninstallString](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-uninstallstring-string.jpg)
6. Click **OK** on the **Edit String** window and close the Registry Editor.
7. Next, you’ll need to start the Run dialog, which has a convenient **Windows** logo + **R** hotkey.
8. Click in Run’s **Open** box and press **Ctrl** \+ **V** to paste in the copied value for the **UninstallString**.  
![The Run dialog that includes an UninstallString value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-run-dialog.jpg)
9. Press **OK** to bring up an uninstall window for the software.
10. Select to uninstall the software from there.

 Some programs will have keys with alphanumeric codes that don’t match their titles in any way. So, you may need to identify program keys differently. To do so, select a key with an alphanumeric code and look at the value for its **DisplayName** string. The **DisplayName** strings show you the names of the keys’ software packages.

![The value data for a DisplayName string](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/a-displayname-string-value.jpg)

## 11\. Uninstall Software via the Context Menu

 Uninstalling software via the right-click context menu is a convenient way to remove programs. The only thing is File Explorer doesn’t include a context menu option for uninstalling software. However, you can add a context menu option for uninstalling programs with software like Windows Uninstaller and IObit Uninstaller. Check out this [guide to adding uninstall shortcuts to the context menu](https://www.makeuseof.com/how-to-add-uninstall-shortcut-context-menu-windows-11-10/) for further details.

 When you’ve added an uninstall shortcut to the context menu, you can remove software by right-clicking its desktop shortcut and selecting the uninstall option. Note that the shortcut will be on the classic context menu, meaning you'll need to click **Show more options** to access it. Alternatively, right-click the program’s EXE (application) file within its installation folder and select the uninstall context menu option.

![The Uninstall desktop context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-uninstall-context-menu-option-1.jpg)

## Uninstall Software You Don’t Need

 Don’t let unneeded software waste drive storage space on your PC. You can free up many gigabytes of drive space by removing desktop software and UWP apps with any of the methods above. How you uninstall programs is entirely up to you. Choose whatever method for uninstalling software you prefer.

 There are various ways you can uninstall software in Windows 11\. Most users will probably be familiar with Windows’ built-in "Programs and Features" uninstaller. However, utilizing that uninstaller is not necessarily the best way to remove software; and sometimes you might have to try different methods. These are seven ways you can remove software packages in Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-budget-friendly-top-7-mac-apps-for-enhanced-tiktok-videos/"><u>2024 Approved  Budget-Friendly Top 7 Mac Apps for Enhanced TikTok Videos</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-final-cut-pro-x-jump-cuts-take-your-editing-to-the-next-level/"><u>2024 Approved Final Cut Pro X Jump Cuts Take Your Editing to the Next Level</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reverse-failed-zip-file-extractions-on-windows-11/"><u>How To Reverse Failed Zip File Extractions on Windows 11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-the-ultimate-premiere-pro-pc-build-a-beginners-guide/"><u>New 2024 Approved The Ultimate Premiere Pro PC Build A Beginners Guide</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-elevating-your-broadcast-combining-zoom-and-fb-live-for-2024/"><u>[Updated] Elevating Your Broadcast  Combining ZOOM & FB Live for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-acclaimed-discord-screen-capture-apps-reviewed/"><u>[New] Acclaimed Discord Screen Capture Apps Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-update-failure-0x8024800c/"><u>Correcting Windows Update Failure: 0X8024800C</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-turn-off-chrome-notifications-windows-version/"><u>Steps to Turn Off Chrome Notifications, Windows Version</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-email-apps-0x800713f-issue-on-win11/"><u>Navigating Through Email App's 0X800713F Issue on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/flashback-fun-enjoying-oldschool-games-with-dosbox-x/"><u>Flashback Fun: Enjoying Oldschool Games with DOSBox-X</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-update-fault-x8019/"><u>Eliminating Windows Update Fault X8019</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-tecno-pova-5-drfone-by-drfone-android/"><u>How to Screen Mirroring Tecno Pova 5? | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-harmonious-news-audio-compilation-volume-15/"><u>New In 2024, Harmonious News Audio Compilation - Volume 15</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-savvy-screenshot-tactics-for-netflix-on-mac-a-complete-guide-of-six-ways/"><u>[New] In 2024, Savvy Screenshot Tactics for Netflix on Mac - A Complete Guide of Six Ways</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-repairing-code-0x0000004e-on-pcs/"><u>Step-by-Step: Repairing Code 0X0000004E on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-for-microsoft-store-crash-error-0x800704cf-in-windows/"><u>Quick Fix for Microsoft Store Crash: Error 0X800704CF in Windows</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-2024-approved-exclusive-content-pure-unwatermarked-tiktok-downloads/"><u>[Updated] 2024 Approved  Exclusive Content  Pure, Unwatermarked TikTok Downloads</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-windows-11-tablet-bar-accessibility/"><u>Maximizing Windows 11 Tablet Bar Accessibility</u></a></li>
<li><a href="https://win11.techidaily.com/strategic-steps-for-purging-microsoft-defender-traces-from-win-11/"><u>Strategic Steps for Purging Microsoft Defender Traces From Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-tips-for-access-denied-on-nvidia-panel/"><u>Quick-Fix Tips for Access Denied on NVIDIA Panel</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-speech-recognition-launch-failures-in-windows-os/"><u>Overcoming Speech Recognition Launch Failures in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-home-screen-norm-setting-default-position-of-win-11-keyboards/"><u>Achieving Home Screen Norm: Setting Default Position of Win 11 Keyboards</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-system-health-improvement-via-updates/"><u>Understanding System Health Improvement via Updates</u></a></li>
<li><a href="https://win11.techidaily.com/chronology-clash-wintime-harmony-guide/"><u>Chronology Clash? WinTime Harmony Guide</u></a></li>
<li><a href="https://win11.techidaily.com/winfixer-rectifying-the-network-not-reachable-error-in-windows-11/"><u>Winfixer: Rectifying the 'Network Not Reachable' Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-slow-printer-on-windows/"><u>How to Fix a Slow Printer on Windows</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-step-up-to-youtube-live-with-minimal-subscriber-threshold-reached/"><u>[New] 2024 Approved  Step Up to YouTube Live with Minimal Subscriber Threshold Reached</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-clear-past-security-checks-on-your-wins-system/"><u>How to Clear Past Security Checks on Your Wins System</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-basics-of-visual-storytelling/"><u>2024 Approved  Basics of Visual Storytelling</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-how-to-turn-yourself-into-anime-character-for-2024/"><u>Updated How To Turn Yourself Into Anime Character for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-stop-infinite-data-depletion-in-windows/"><u>5 Ways to Stop Infinite Data Depletion in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-endless-scrolls-on-large-datasheets-windows/"><u>Overcome Endless Scrolls on Large Datasheets, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-security-avoid-chatbots-for-win-11-keys/"><u>Bypassing Security: Avoid Chatbots for Win 11 Keys</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-choreographing-newscast-endings/"><u>[Updated] In 2024, Choreographing Newscast Endings</u></a></li>
<li><a href="https://extra-hints.techidaily.com/audio-amplification-for-powerpoint-presentations/"><u>Audio Amplification for PowerPoint Presentations</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-os-install-windows-for-steam-deck/"><u>Streamline OS Install: Windows for Steam Deck</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2023s-leading-youtube-engagement-tools-for-2024/"><u>2023'S Leading YouTube Engagement Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-efficient-device-communication-via-google-sharing/"><u>Tips for Efficient Device Communication via Google Sharing</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-print-on-edge-security-mode-windows-11/"><u>Enabling Print on Edge Security Mode Windows 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-best-6-android-video-capture-apps-for-screen-recording-for-2024/"><u>[Updated] Best 6 Android Video Capture Apps for Screen Recording for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mysteries-of-recurring-anydesk-errors-on-windows/"><u>Unraveling the Mysteries of Recurring AnyDesk Errors on Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-lava-blaze-2-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Lava Blaze 2? | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-maximize-your-library-a-comprehensive-list-of-online-mp3-tag-editor-powerhouses-for-2024/"><u>New Maximize Your Library A Comprehensive List of Online MP3 Tag Editor Powerhouses for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-screen-savers-a-guide-to-win11/"><u>Tailoring Screen Savers: A Guide to Win11</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-to-re-enable-your-windows-11-device-after-error-22/"><u>Expert Tips to Re-Enable Your Windows 11 Device After Error 22</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-honor-90-gt-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On Honor 90 GT? Here Is the Answer | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/tailored-approach-installing-and-using-outlook-preview-for-windows-11-users/"><u>Tailored Approach: Installing and Using Outlook Preview for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-functionality-of-component-services-utility-in-windows/"><u>Exploring the Functionality of Component Services Utility in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-dealing-with-not-handled-exception-error-on-pcs/"><u>Tips for Dealing with Not Handled Exception Error on PCs</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/in-2024-seamless-transfer-of-social-media-videos-from-twitter-to-whatsapp/"><u>In 2024, Seamless Transfer of Social Media Videos From Twitter to WhatsApp</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-nokia-c210-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on Nokia C210? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
</ul></div>
