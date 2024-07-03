---
title: Eliminating Not Enough Privileges Error During Installation on Windows
date: 2024-06-25T11:23:37.186Z
updated: 2024-06-26T11:23:37.186Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating Not Enough Privileges Error During Installation on Windows
excerpt: This Article Describes Eliminating Not Enough Privileges Error During Installation on Windows
keywords: Fix Privilege Error Windows,Eliminate Install Error,Stop Privilege Failure,Remove Insufficient Rights,Correct Permissions Issue,End Upgrade Access Denied,Overcome Installer Restrictions
thumbnail: https://thmb.techidaily.com/beb79c97cd88302125e646092101e6316bc065b6e8c0e4d468eed617783ebeeb.jpg
---

## Eliminating Not Enough Privileges Error During Installation on Windows

 Users report Windows software installation errors of various kinds on support forums. Some of those reports have been about an error message that says, “The installer has insufficient privileges to access this directory.” That error message pops up on some users’ Windows 11/10 PCs when they try to install desktop programs with setup files.

 The result of this installation error is the same as most others. Users can’t install the software packages they need to when it happens. This is how you can fix the “installer has insufficient privileges” error on a Windows 11/10 PC.

## 1\. Run the Affected Software’s Setup File With Admin Rights

 Running the setup file for an affected program with administrator rights is perhaps the simplest of potential fixes for the “installer has insufficient privileges” error.

 A few users say that’s all they needed to do to fix the “installer has insufficient privileges” error. So, try right-clicking the software’s installer file and selecting **Run as administrator**.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/run-as-administrator-option.jpg)

## 2\. Unblock the Setup File

 In addition, check if the installer file is blocked before running it. To do that, right-click the program’s setup file and select **Properties**.

 If you can see an **Unblock** option on the **General** tab, deselect the checkbox and select **Apply**.

## 3\. Take Ownership of the Software’s Installation Directory

 One of the more widely confirmed solutions for fixing the “installer has insufficient privileges” error is to take ownership of the installation directory for the affected software.

 The “installer has sufficient privileges” error message specifies the path of the directory selected to install the software. Take ownership of the second to last folder of that path. The last folder is the one created during the installation that won’t currently exist on your PC.

 Alternatively, you can also apply this potential solution by manually creating the folder specified within the error message that doesn’t currently exist. Keep the error message open and create the last folder in the path. Then take ownership of the last folder in the installation path specified and click **Retry** within the error message.

 You can take ownership of a folder manually or by adding a new context menu option that does the job. This guide about [taking ownership of folders in Windows 11](https://www.makeuseof.com/windows-10-11-own-folder/) includes full instructions for both methods. It’s more straightforward to apply this potential solution by adding a **Take Ownership** option to the context menu with Winaero Tweaker.

![The Take Ownership option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/take-ownership-option.jpg)

## 4\. Try Installing it in a Different Folder

 You might be able to bypass the “installer has insufficient privileges” error by selecting to install the software in a different directory. Many users install software packages in the Program Files folder. So, try selecting to install a program at a completely different folder path from the one specified in the error message.

## 5\. Start or Restart Windows Installer

 Installation issues can arise because of Windows Installer service issues. Or that service might not even be running. So, check that service and either start or restart it depending on whether it’s running or not. You can start or restart Windows Installer like this:

1. [Open Services](https://www.makeuseof.com/windows-11-open-services-app/), an app you can access by pressing the **Windows** logo + **R** hotkey and inputting a **service.msc** command.
2. Right-click Windows Installer and select **Start** if that service isn’t on and running.  
![windows installer option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-installer-option.jpg)
3. If Windows Installer is running, select its **Restart** context menu option.

 Alternatively, you can double-click the **Windows Installer** service to view its properties window and restart it from there. Click **Start** if the service is already stopped, or, select **Stop > Start** to restart.

## 6\. Disable UAC Before Installing

 User Account Control is one of the security features that can generate installation issues when set to its higher levels. Turn off UAC before attempting to install affected software to see if that resolves the “installer has insufficient privileges” error. Check out this guide about [disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) for details about how to turn off UAC.

![The Never notify option in UAC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/never-notify-option.jpg)

## 7\. Disable All User Account Control Policy Settings

 If you’re a Windows Pro or Enterprise user, you can disable all UAC security settings that might be causing this error by restricting software installation.

 The Group Policy Editor tool in Windows Pro and Enterprise editions enables users to disable more User Account Control settings. You can turn off all UAC policy settings with Group Policy Editor like this:

1. [Open the Group Policy Editor tool](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and double-click **Computer Configuration** in its sidebar.
2. Then double-click **Windows Settings** \> **Security Settings** \> **Local Policies** \> **Security Options** to access UAC policy settings.
3. Double-click **User Account Control: Admin Approval Mode** to bring up that policy setting window.  
![The UAP security policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-options.jpg)
4. Select **Disabled** to turn off that policy setting.
5. Click **Apply** \> **OK** to save the policy setting you’ve selected.  
![The Enabled radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-enabled-radio-button.jpg)

 Once done, repeat steps three to five above for all the User Account Control policy settings. Exit Group Policy Editor and restart your PC after disabling all UAC policy settings.

## 8\. Turn Off Third-Party Security Apps

 If you’ve installed a third-party security app, such as antivirus or firewall software, that could be a possible cause for the “installer has insufficient privileges” error on your PC.

 Third-party antivirus tools have settings that can restrict or block the installation of suspicious programs when enabled. That’s more likely to happen when you’re trying to install unsigned software, which antivirus apps sometimes flag.

 You can prevent potential security app blocks when installing programs by temporarily disabling their antivirus shields.

 To find an option for disabling your antivirus app’s shield, right-click its system tray icon; select a setting to turn off your antivirus for a while on the right-click context menu that opens. Then have a go at installing affected software packages again with the antivirus shield disabled.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

## 9\. Try Installing Software After Clean Booting

 Clean booting means disabling all third-party apps and services that start with Windows. This troubleshooting method can prevent software conflicts by eliminating unneeded apps and services running in the background. In this case, a clean boot might disable an app or service that’s hindering the software installation process.

 We have a detailed guide on [performing a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) explaining how you can disable the startup items with System Configuration and Task Manager. Select to restart your PC after you’ve set a clean boot configuration. Install the software you need after restarting to see if the clean booting has made any difference.

![The Services tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-services-tab.jpg)

## 10\. Uninstall Older Software Versions

 The “installer has insufficient privileges” has been reported to occur by users trying to install new versions of software already on their PCs.

 If there’s an older version of the software you can’t install already on your PC, then try uninstalling the preceding version first. This guide on [uninstalling software in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) includes various methods for removing programs.

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-uninstall-option.jpg)

## Get Your Windows 11/10 Software Installed

 The possible fixes covered here will probably resolve the “installer has insufficient privileges” Windows error in most cases but aren’t necessarily guaranteed.

 Resolution three, taking ownership of the installation directory, is the most widely confirmed solution. So, this error is usually a privilege (permission) issue for installing software, which the potential resolutions above will likely address.

 The result of this installation error is the same as most others. Users can’t install the software packages they need to when it happens. This is how you can fix the “installer has insufficient privileges” error on a Windows 11/10 PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/the-convenient-path-to-iis-manager-entry-point/"><u>The Convenient Path to IIS Manager Entry Point</u></a></li>
<li><a href="https://win11.techidaily.com/fix-for-invisible-second-screen-on-windows-11/"><u>Fix for Invisible Second Screen on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-secure-windows-sound-level-adjustments/"><u>Tips to Secure Windows Sound Level Adjustments</u></a></li>
<li><a href="https://win11.techidaily.com/probing-into-the-heart-of-windows-11-system32/"><u>Probing Into the Heart of Windows 11: System32</u></a></li>
<li><a href="https://win11.techidaily.com/streaming-windows-network-shares-from-smartphones/"><u>Streaming Windows Network Shares From Smartphones</u></a></li>
<li><a href="https://win11.techidaily.com/rebuilding-with-purpose-windows-11-from-scratch/"><u>Rebuilding with Purpose: Windows 11 From Scratch</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-keep-word-reading-mode-active-when-handling-email-attachments/"><u>Tips to Keep Word Reading Mode Active When Handling Email Attachments</u></a></li>
<li><a href="https://win11.techidaily.com/a-fresh-start-for-your-computers-firewall-settings/"><u>A Fresh Start for Your Computer's Firewall Settings</u></a></li>
<li><a href="https://win11.techidaily.com/tricks-to-enable-touch-typing-on-windows-laptops/"><u>Tricks to Enable Touch Typing on Windows Laptops</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-blackout-getting-out-of-dark-mode/"><u>Bypassing The Blackout: Getting Out Of Dark Mode</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-monetization-timeline-for-successful-youtubers/"><u>[Updated] Monetization Timeline for Successful YouTubers</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-prime-picks-for-classroom-audio/"><u>[New] 2024 Approved  Prime Picks for Classroom Audio</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-innovative-text-to-speech-solutions-dominating-the-market/"><u>New In 2024, Innovative Text-to-Speech Solutions Dominating the Market</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-swift-comment-removal-on-youtube-a-practical-guide/"><u>2024 Approved  Swift Comment Removal on YouTube  A Practical Guide</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-ultimate-asmr-content-guides/"><u>[Updated] Ultimate ASMR Content Guides</u></a></li>
<li><a href="https://change-location.techidaily.com/ultimate-guide-to-catch-the-regional-located-pokemon-for-vivo-y02t-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Catch the Regional-Located Pokemon For Vivo Y02T | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-top-15-soundtracks-without-copyrights-for-montage-projects/"><u>New Top 15 Soundtracks Without Copyrights for Montage Projects</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-15-pro-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone 15 Pro without iTunes? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-how-to-prevent-and-mend-live-stream-glitches-fb-for-2024/"><u>[New] How to Prevent & Mend Live Stream Glitches (FB) for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ring-your-youtube-live-video-thumbnail-game-for-2024/"><u>Mastering Your YouTube Live Video Thumbnail Game for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>