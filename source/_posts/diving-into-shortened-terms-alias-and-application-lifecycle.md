---
title: "Diving Into Shortened Terms: Alias & Application Lifecycle"
date: 2024-06-25T11:44:51.517Z
updated: 2024-06-26T11:44:51.517Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Diving Into Shortened Terms: Alias & Application Lifecycle"
excerpt: "This Article Describes Diving Into Shortened Terms: Alias & Application Lifecycle"
keywords: Dive Into Aliases,Term Lifecycles,Alias Impact,Appl. Lifecycle Insight,Shortened Keywords,Alias Usage Trends,Lifecycle Management
thumbnail: https://thmb.techidaily.com/4e339c0438a311f0739fe8dd767b8fe136567e49f78cba1047e1590ff1927d2b.png
---

## Diving Into Shortened Terms: Alias & Application Lifecycle

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several[Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and[PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

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
<li><a href="https://win11.techidaily.com/navigating-your-phones-role-in-windows-recording/"><u>Navigating Your Phone's Role in Windows Recording</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-settings-managing-device-permissions/"><u>Navigating Windows Settings: Managing Device Permissions</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-error-code-3-in-nvidia-opengl-win10-and-11/"><u>Eliminating Error Code 3 in NVIDIA OpenGL (Win10 & 11)</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-cheap-traps-the-realities-of-inferior-windows-activation-codes/"><u>Avoid Cheap Traps: The Realities of Inferior Windows Activation Codes</u></a></li>
<li><a href="https://win11.techidaily.com/curbing-the-catastrophe-recycle-bin-errors-in-win1011/"><u>Curbing the Catastrophe: Recycle Bin Errors in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-rectify-ge-share-function-failures/"><u>Guide to Rectify GE Share Function Failures</u></a></li>
<li><a href="https://win11.techidaily.com/essential-4-password-guardians-elevating-windows-11-security/"><u>Essential 4 Password Guardians Elevating Windows 11 Security</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-windows-login-validity-and-failures/"><u>Assessing Windows Login Validity and Failures</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-for-error-0x800700e1-in-windows-11-os/"><u>Essential Fixes for Error 0X800700E1 in Windows 11 OS</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-snapchat-boomerangs-demystified-your-comprehensive-guide/"><u>2024 Approved  Snapchat Boomerangs Demystified  Your Comprehensive Guide</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/ps3-gaming-reimagined-best-emulators-of-the-year-for-2024/"><u>PS3 Gaming Reimagined  Best Emulators of the Year for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/hone-your-iphone-skills-with-shortened-and-customized-vids-for-2024/"><u>Hone Your iPhone Skills with Shortened & Customized Vids for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-in-2024-unlocking-sound-the-top-six-free-techniques-for-transforming-videos-into-audio-coming-soon/"><u>New In 2024, Unlocking Sound The Top Six Free Techniques for Transforming Videos Into Audio (Coming Soon!)</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-breaking-the-mold-pushing-a-video-into-hot-water/"><u>In 2024, Breaking the Mold  Pushing a Video Into Hot Water</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-navigating-novelty-applying-cartoon-lenses-in-snapchat/"><u>In 2024, Navigating Novelty  Applying Cartoon Lenses in Snapchat</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-az-capture-extraordinaire-thorough-app-reviews/"><u>2024 Approved  AZ Capture Extraordinaire  Thorough App Reviews</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-epic-audio-essentials-top-10-for-trending-yt-shorts/"><u>[New] Epic Audio Essentials  Top 10 for Trending YT Shorts</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-can-you-enhance-your-drone-footage-with-cinematic-drone-luts-this-article-discusses-top-drone-luts-recommendations-to-simplify-video-e/"><u>Updated 2024 Approved Can You Enhance Your Drone Footage with Cinematic Drone LUTs? This Article Discusses Top Drone LUTs Recommendations to Simplify Video Editing</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-transforming-your-shots-with-ease-in-photoshop/"><u>[Updated] Transforming Your Shots with Ease in Photoshop</u></a></li>
</ul></div>
