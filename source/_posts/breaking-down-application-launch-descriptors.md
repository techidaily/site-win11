---
title: Breaking Down Application Launch Descriptors
date: 2025-02-25T20:16:41.905Z
updated: 2025-03-04T21:28:10.644Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Breaking Down Application Launch Descriptors
excerpt: This Article Describes Breaking Down Application Launch Descriptors
keywords: App Launch Guide,Launch Process Steps,Launch Descriptor Use,Application Deployment Tips,Launching App Efficiently,Launch Protocols for Apps,Descriptors in App Launch
thumbnail: https://thmb.techidaily.com/26237c0b8cf6f930c119cd7d58abe423d11d796e2ad6cf886d90c9a4679357e1.jpg
---

## Breaking Down Application Launch Descriptors

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several [Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.

## Create App Execution Aliases in Registry Editor

 Before editing or creating registry keys, it is advisable to [create a full backup of the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . Of course, you should also ensure you understand how to restore the Registry from that backup.

 The process below for creating app execution aliases in the Registry Editor should be the same in both Windows 10 and 11.

1. Open**Windows Search** , type**Registry Editor** , and click on the search result to open it.
2. In the editor, navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\App Paths** .
3. Next, right-click on the**App Paths** key in the left-hand pane, and select**New > Key** .
4. Give the new key an alias name that relates to the app and ends with .exe. For example, if the alias is for Calendar, call it something like cal.exe.
5. With the alias selected, double-click the**Default** value in the right-hand pane.  
![editing app aliases in registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-regedit.jpg)
6. In the Value data field, you will need to enter the full path to the app executable file. For example**C:\\Program Files (x86)\\Calendar.exe** .
7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

## Using and Creating App Execution Aliases

 Entering commands into tools such as Command Prompt and PowerShell can be laborious. You can streamline that process by enabling or creating aliases for apps that commonly feature in those commands. Why type out a full path to an executable file when you can point to it with a few keystrokes?

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
<li><a href="https://vimeo-videos.techidaily.com/new-content-creators-guide-to-thriving-in-a-digital-economy-on-vimeo-for-2024/"><u>[New] Content Creators' Guide to Thriving in a Digital Economy on Vimeo for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-breaking-down-the-monetization-barriers/"><u>[New] In 2024, Breaking Down the Monetization Barriers</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-2024-approved-10-best-photo-grid-apps-to-make-your-pictures-stand-out/"><u>[Updated] 2024 Approved 10 Best Photo Grid Apps to Make Your Pictures Stand Out</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-expert-video-capture-maximizing-performance-with-logitech-webcam-tech-for-2024/"><u>[Updated] Expert Video Capture Maximizing Performance with Logitech Webcam Tech for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/guide-overcoming-banned-program-error-message-in-pc/"><u>Guide: Overcoming Banned Program Error Message in PC</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>In 2024, Read This Guide to Find a Reliable Alternative to Fake GPS On Oppo Reno 9A | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-homescreen-access/"><u>Mastering Windows 11 Homescreen Access</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-deactivated-volume-copies-error/"><u>Resolving Deactivated Volume Copies Error</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-the-deadly-js-error-a-comprehensive-guide-for-win-11-users/"><u>Resolving the Deadly JS Error: A Comprehensive Guide for Win 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/solving-windows-shutdown-issues-caused-by-suspicious-apps/"><u>Solving Windows Shutdown Issues Caused by Suspicious Apps</u></a></li>
<li><a href="https://driver-install.techidaily.com/speedier-system-setup-get-scsi-drivers-quickly/"><u>Speedier System Setup: Get SCSI Drivers Quickly</u></a></li>
</ul></div>

