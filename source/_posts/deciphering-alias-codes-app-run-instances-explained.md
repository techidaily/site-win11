---
title: "Deciphering Alias Codes: App Run Instances Explained"
date: 2024-11-23T20:10:53.424Z
updated: 2024-11-28T00:41:28.813Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Deciphering Alias Codes: App Run Instances Explained"
excerpt: "This Article Describes Deciphering Alias Codes: App Run Instances Explained"
keywords: Decode Alias Codes,App Run Keywords,Instance Explanation SEO,Alias Codebreak SEO,App Execution Analysis,Running Apps SEO,Deciphering App Codes SEO
thumbnail: https://thmb.techidaily.com/f578a6dc00b86f004f0eebf050b3c39c1e5f0c46ca38580b5c0bd47ee47b9b9c.jpg
---

## Deciphering Alias Codes: App Run Instances Explained

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several[Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and[PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8U3ooyFiAB4?si=yXPQrDhMBEJwN2EZ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://visual-screen-recording.techidaily.com/new-expert-review-of-ios-screenshot-software-for-2024/"><u>[New] Expert Review of iOS Screenshot Software for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-how-to-do-screen-record-snapchat-on-mobile-phone-in-2024/"><u>[New] How to Do Screen Record Snapchat on Mobile Phone, In 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-how-to-maximize-your-content-impact-with-imovie-on-vimeo/"><u>[New] In 2024, How to Maximize Your Content Impact with iMovie on Vimeo</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ath-to-youtube-riches-optimal-view-figures-for-monetization-success/"><u>[New] Path to YouTube Riches Optimal View Figures for Monetization Success</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-the-journey-of-drones-from-current-uses-to-future-applications-for-2024/"><u>[New] The Journey of Drones From Current Uses to Future Applications for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-capturing-life-on-a-macbook-air-the-comprehensive-guide-to-screen-recording/"><u>[Updated] Capturing Life on a MacBook Air The Comprehensive Guide to Screen Recording</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-rapid-rise-to-instagram-riches-15-innovative-techniques-for-quick-popularity-boost/"><u>[Updated] Rapid Rise to Instagram Riches 15 Innovative Techniques for Quick Popularity Boost</u></a></li>
<li><a href="https://win11.techidaily.com/discovering-undetected-windows-malware-risks/"><u>Discovering Undetected Windows Malware Risks</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-connectivity-with-5ghz-networks/"><u>Mastering Windows 11: Connectivity with 5GHz Networks</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-disk-space-with-windows-11s-ntfs-options/"><u>Maximizing Disk Space with Windows 11'S NTFS Options</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-and-resolving-minecrafts-lan-network-issues/"><u>Navigating and Resolving Minecraft's LAN Network Issues</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-admin-policies-that-hinder-setup/"><u>Overcoming Windows Admin Policies That Hinder Setup</u></a></li>
<li><a href="https://win11.techidaily.com/quick-aid-to-recover-googles-nonresponsive-windows-share-app/"><u>Quick Aid to Recover Google's Nonresponsive Windows Share App</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-for-disconnected-spotify-streaming/"><u>Quick-Fix Guide for Disconnected Spotify Streaming</u></a></li>
<li><a href="https://win-blog.techidaily.com/solve-your-battlefield-2042-game-crashes-caused-by-directx-errors-today/"><u>Solve Your Battlefield 2042 Game Crashes Caused by DirectX Errors Today</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ltimate-manual-for-youtube-playlist-reordering-for-2024/"><u>The Ultimate Manual for YouTube Playlist Reordering for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-undisclosed-menu-maestros-guide-to-win11-concealment/"><u>The Undisclosed Menu Maestro's Guide to Win11 Concealment</u></a></li>
</ul></div>

