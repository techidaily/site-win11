---
title: Unlocking Code Word Prefixes for Software Execution
date: 2024-08-23T06:13:18.694Z
updated: 2024-08-24T06:13:18.694Z
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
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
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-mapping-instagrams-unfollowers-landscape/"><u>[New] In 2024, Mapping Instagram's Unfollowers Landscape</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-dive-deep-into-the-soundscapes-of-iphone-podcasts-for-2024/"><u>[Updated] Dive Deep Into the Soundscapes of iPhone Podcasts for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-how-to-enhance-audibility-with-adjusted-obs-settings/"><u>[Updated] How to Enhance Audibility with Adjusted OBS Settings</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-snapshot-to-sequence-capturing-life-in-motion-for-2024/"><u>[Updated] Snapshot to Sequence  Capturing Life in Motion for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-enhancing-non-working-windows-batch-files/"><u>Deciphering and Enhancing Non-Working Windows Batch Files</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-disk-capacity-in-windows-7-best-no-cost-techniques/"><u>Elevate Disk Capacity in Windows - 7 Best No-Cost Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-rectify-missing-windows-component/"><u>Essential Steps to Rectify Missing Windows Component</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-error-code-31-for-your-pcs-internet-connection/"><u>Fixing Error Code 31 for Your PC's Internet Connection</u></a></li>
<li><a href="https://win11.techidaily.com/granting-admin-access-to-win11s-task-manager/"><u>Granting Admin Access to Win11's Task Manager</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-you-through-the-admin-access-passway/"><u>Guiding You Through the Admin Access Passway</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-poco-x6-pictures-an-easy-method-explained-by-fonelab-android-recover-pictures/"><u>How to Restore Deleted Poco X6 Pictures  An Easy Method Explained.</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-cartoonize-your-memories-a-simple-guide-to-converting-videos/"><u>In 2024, Cartoonize Your Memories A Simple Guide to Converting Videos</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-infinite-jest-10-ultimate-meme-layouts/"><u>In 2024, Infinite Jest - 10 Ultimate Meme Layouts</u></a></li>
<li><a href="https://win11.techidaily.com/intuitive-setup-techniques-for-desktop-icons-in-windows-11/"><u>Intuitive Setup Techniques for Desktop Icons in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/jumpstart-tech-legacy-for-windows-11-22h2-compatibility/"><u>Jumpstart Tech Legacy for Windows 11 22H2 Compatibility</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-winsminecrafts-lan-play-functionality/"><u>Mastering WinsMinecraft's LAN Play Functionality</u></a></li>
<li><a href="https://win-able.techidaily.com/rainbow-six-siege-not-opening-heres-the-solution/"><u>Rainbow Six Siege Not Opening? Here's the Solution</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-non-deletable-keys-on-microsoft-platforms/"><u>Repairing Non-Deletable Keys on Microsoft Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/revealing-indexers-control-accessibility/"><u>Revealing Indexer's Control Accessibility</u></a></li>
<li><a href="https://win11.techidaily.com/risk-averse-approach-foregoing-bots-for-win-11-authentication/"><u>Risk-Averse Approach: Foregoing Bots for Win 11 Authentication</u></a></li>
<li><a href="https://extra-skills.techidaily.com/selective-blur-for-enhanced-privacy-measures-for-2024/"><u>Selective Blur for Enhanced Privacy Measures for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/sprachweiterentwicklung-zahlreim-fur-die-ersten-100-deutsche/"><u>Sprachweiterentwicklung: Zählreim Für Die Ersten 100 Deutsche</u></a></li>
<li><a href="https://win11.techidaily.com/sticky-ideas-on-screens-essential-notes-apps-for-windows-users/"><u>Sticky Ideas on Screens: Essential Notes Apps for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-avoid-print-server-communication-failures/"><u>Strategies to Avoid Print Server Communication Failures</u></a></li>
<li><a href="https://win11.techidaily.com/stripping-decorative-elements-from-window-search-ui/"><u>Stripping Decorative Elements From Window Search UI</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-errors-forbidden-explained/"><u>Tackling Windows Errors: Forbidden Explained</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-windows-display-duration-manual/"><u>The Complete Windows Display Duration Manual</u></a></li>
<li><a href="https://win11.techidaily.com/the-comprehensive-blueprint-for-addressing-directdraw-errors-on-windows-1011/"><u>The Comprehensive Blueprint for Addressing DirectDraw Errors on Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tips-to-ensure-camera-activity-notifications-in-ws11/"><u>Tips to Ensure Camera Activity Notifications in WS11</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-full-control-of-windows-key-using-these-tips/"><u>Unlock Full Control of Windows Key Using These Tips</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-your-disks-easy-steps-in-w10w11/"><u>Unlocking Your Disks: Easy Steps in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/zoning-out-realign-your-mouse-wheel-now-7-steps/"><u>Zoning Out? Realign Your Mouse Wheel Now! (7 Steps)</u></a></li>
</ul></div>
