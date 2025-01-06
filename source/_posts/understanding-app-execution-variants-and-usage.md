---
title: Understanding App Execution Variants & Usage
date: 2025-01-01T17:37:47.337Z
updated: 2025-01-06T20:56:25.460Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Understanding App Execution Variants & Usage
excerpt: This Article Describes Understanding App Execution Variants & Usage
keywords: Execute App Variants,Track Usage Metrics,Optimize Mobile Experience,Monitor Performance Gains,Analyze User Engagement,Streamline App Strategy,Enhance Conversion Rates
thumbnail: https://thmb.techidaily.com/fa290563760e589f24a85fc95189dcd8b9293ad6203d8af2e7f7aed06726e6d2.jpg
---

## Understanding App Execution Variants & Usage

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several[Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and[PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NTQGoOOiJzs?si=zbZwflEfXgBY3qbs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_SbYznUy_zY?si=ThBkP934r3mizi48" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-docs.techidaily.com/n-2024-youtube-shorts-a-beginners-guide/"><u>[New] In 2024, YouTube Shorts A Beginner's Guide</u></a></li>
<li><a href="https://buynow-help.techidaily.com/book-lovers-guide-to-portable-e-readers-unveiling-the-kobo-clara-hd/"><u>Book Lovers' Guide to Portable E-Readers: Unveiling the Kobo Clara HD</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-xiaomi-redmi-note-12t-pro-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Xiaomi Redmi Note 12T Pro Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/dial-down-windows-contrast-mode-intensity/"><u>Dial Down Windows Contrast Mode Intensity</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-methods-to-handle-printer-access-issues/"><u>Efficient Methods to Handle Printer Access Issues</u></a></li>
<li><a href="https://win11.techidaily.com/excessive-resource-use-unwanted-features-in-malware-tools/"><u>Excessive Resource Use: Unwanted Features in Malware Tools</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-fashion-meets-makeup-brilliance/"><u>In 2024, Fashion Meets Makeup Brilliance</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-simulate-gps-movement-in-ar-games-on-asus-rog-phone-8-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Simulate GPS Movement in AR games On Asus ROG Phone 8 Pro? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-poco-c65-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Poco C65 Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://buynow-info.techidaily.com/personalize-your-play-experience-crafting-a-nintendo-3ds-login-credential-guide/"><u>Personalize Your Play Experience: Crafting a Nintendo 3DS Login Credential Guide</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/the-art-of-capture-and-storage-managing-snapshots-like-a-pro-for-2024/"><u>The Art of Capture and Storage Managing Snapshots Like a Pro for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/top-8-elements-for-choosing-an-effective-cpu-cooler/"><u>Top 8 Elements for Choosing an Effective CPU Cooler</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-techniques-for-winning-at-warhammer-40k-on-pc/"><u>Troubleshooting Techniques for Winning at Warhammer 40K on PC</u></a></li>
<li><a href="https://win11.techidaily.com/windows-and-sudo-a-powerful-combination/"><u>Windows & Sudo: A Powerful Combination</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-covert-command-channels-how-to-hide-menus/"><u>Windows 11’S Covert Command Channels: How to Hide Menus</u></a></li>
</ul></div>

