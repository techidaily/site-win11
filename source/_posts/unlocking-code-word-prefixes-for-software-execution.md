---
title: Unlocking Code Word Prefixes for Software Execution
date: 2024-12-31T16:59:11.087Z
updated: 2025-01-06T17:47:37.642Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking Code Word Prefixes for Software Execution
excerpt: This Article Describes Unlocking Code Word Prefixes for Software Execution
keywords: Code Prefix Keywords,Execution Preconditions,Software Launch Codes,Deciphering Executable Triggers,Execution Sequence Identifiers,Pre-Execution Checks,Software Initialization Tokens
thumbnail: https://thmb.techidaily.com/f5d1594082aca6452dbc25a49388a37fc7e84721f123ecd76572cb92530c4365.jpg
---

## Unlocking Code Word Prefixes for Software Execution

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several[Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and[PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Create App Execution Aliases in Registry Editor

 Before editing or creating registry keys, it is advisable to[create a full backup of the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . Of course, you should also ensure you understand how to restore the Registry from that backup.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-blueprint-for-a-viral-solitary-audio-experience/"><u>[New] In 2024, Blueprint for a Viral Solitary Audio Experience</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-the-ultimate-guide-to-combining-zoom-and-fb-live/"><u>[New] In 2024, The Ultimate Guide to Combining ZOOM & FB Live</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-unlock-the-full-potential-of-group-video-conferencing-on-your-android-device-zoom/"><u>[New] In 2024, Unlock the Full Potential of Group Video Conferencing on Your Android Device (Zoom)</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-revolutionizing-youtube-success-through-smart-title-strategy/"><u>[Updated] 2024 Approved Revolutionizing YouTube Success Through Smart Title Strategy</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-infographic-spectacle-of-youtubes-2017-data/"><u>[Updated] The Infographic Spectacle of YouTube's 2017 Data</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-essential-tips-for-zoom-screen-sharing/"><u>2024 Approved Essential Tips for Zoom Screen Sharing</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-master-5-strategies-for-copying-files-to-your-system/"><u>2024 Approved Master 5 Strategies for Copying Files to Your System</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-down-unnecessary-workload-in-windows-system/"><u>Cutting Down Unnecessary Workload in Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/direct-steps-to-activatedisable-wifi-cost-metering-in-win11/"><u>Direct Steps to Activate/Disable Wifi Cost Metering in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-all-chromium-notifications-in-windows-pc/"><u>Disabling All Chromium Notifications in Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/effective-tactics-for-printer-troubles-on-windows-11/"><u>Effective Tactics for Printer Troubles on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-locate-a-vanishing-sd-card-in-windows-filesystem/"><u>How to Locate a Vanishing SD Card in Windows Filesystem</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-boosting-revenue-through-effective-facebook-video-marketing/"><u>In 2024, Boosting Revenue Through Effective Facebook Video Marketing</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-non-opening-issues-with-photoscape/"><u>Navigating Through Non-Opening Issues with Photoscape</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-workspace-viewing-switch-wmdesk-way/"><u>Optimize Workspace Viewing: Switch WmDesk Way</u></a></li>
<li><a href="https://win11.techidaily.com/proficient-techniques-for-managing-win-registry-from-cmd/"><u>Proficient Techniques for Managing Win Registry From CMD</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/seamless-setup-master-the-art-of-syncing-logitech-mice-with-pcs-and-tablets/"><u>Seamless Setup: Master the Art of Syncing Logitech Mice with PCs & Tablets</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-audio-issues-boosting-your-pcs-speakers-on-windows-1/"><u>Troubleshooting Audio Issues: Boosting Your PC's Speakers on Windows 1</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-playstation-network-error-fix-for-windows-users/"><u>Unblocking PlayStation Network Error: Fix for Windows Users</u></a></li>
</ul></div>

