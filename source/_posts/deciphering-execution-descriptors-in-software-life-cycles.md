---
title: Deciphering Execution Descriptors in Software Life Cycles
date: 2024-08-08T13:17:05.867Z
updated: 2024-08-09T13:17:05.867Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deciphering Execution Descriptors in Software Life Cycles
excerpt: This Article Describes Deciphering Execution Descriptors in Software Life Cycles
keywords: SoftDev ExecDescriptions,CodeLifeCycle Analysis,DevProcess Decoding,Software Lifecycle Keywords,Deciphering Dev Terms,ExecDescriptors Explained,Life Cycle Process Insight
thumbnail: https://thmb.techidaily.com/6ed52b8d826a5b6701c9229d81239cb21a1a6ea95480871656b8b252c90f9890.jpeg
---

## Deciphering Execution Descriptors in Software Life Cycles

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
## Create App Execution Aliases in Registry Editor

 Before editing or creating registry keys, it is advisable to[create a full backup of the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . Of course, you should also ensure you understand how to restore the Registry from that backup.

 The process below for creating app execution aliases in the Registry Editor should be the same in both Windows 10 and 11.

1. Open**Windows Search** , type**Registry Editor** , and click on the search result to open it.
2. In the editor, navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\App Paths** .
3. Next, right-click on the**App Paths** key in the left-hand pane, and select**New > Key** .
4. Give the new key an alias name that relates to the app and ends with .exe. For example, if the alias is for Calendar, call it something like cal.exe.
5. With the alias selected, double-click the**Default** value in the right-hand pane.  
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![editing app aliases in registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-regedit.jpg)
6. In the Value data field, you will need to enter the full path to the app executable file. For example**C:\\Program Files (x86)\\Calendar.exe** .
7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
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
<li><a href="https://facebook-record-videos.techidaily.com/new-discover-7-unforgettable-marriage-videos-on-vimeo-for-2024/"><u>[New] Discover 7 Unforgettable Marriage Videos on Vimeo for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-erase-unwanted-boards-from-old-youtube-videos-for-clearer-viewing/"><u>[New] In 2024, Erase Unwanted Boards From Old YouTube Videos for Clearer Viewing</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-initiating-a-join-in-google-meet-through-computermobile/"><u>[New] In 2024, Initiating a Join in Google Meet Through Computer/Mobile</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-laughs-lab-innovator/"><u>[New] Laughs Lab Innovator</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-digital-dynamo-unleashing-videoviral-impact-for-2024/"><u>[Updated] Digital Dynamo  Unleashing #VideoViral Impact for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-expert-tips-for-mastering-iphones-sound-capture/"><u>[Updated] Expert Tips for Mastering iPhone's Sound Capture</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-savor-the-spectacle-best-practices-for-cooking-channel-titling/"><u>[Updated] Savor the Spectacle  Best Practices for Cooking Channel Titling</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-zoom-in-to-speed-boosting-video-playback-mobileonline-for-2024/"><u>[Updated] Zoom in to Speed  Boosting Video Playback (Mobile/Online) for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-apex-palette-adjuster/"><u>2024 Approved  Apex Palette Adjuster</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-tomtom-gopro-alternative-a-2023-review/"><u>2024 Approved  TomTom GoPro Alternative  A 2023 Review</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-fix-the-local-device-name-is-already-in-use-error-on-windows/"><u>5 Ways to Fix the Local Device Name Is Already in Use Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/7-reasons-why-most-users-havent-upgraded-to-windows-11/"><u>7 Reasons Why Most Users Haven’t Upgraded to Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensible-guide-to-managing-windows-11-default-applications/"><u>A Comprehensible Guide to Managing Windows 11 Default Applications</u></a></li>
<li><a href="https://win11.techidaily.com/a-concise-guide-to-windows-11-user-grievances-and-gripes/"><u>A Concise Guide to Windows 11 User Grievances and Gripes</u></a></li>
<li><a href="https://win11.techidaily.com/a-practical-guide-to-accessing-the-windows-iscsi-initiator/"><u>A Practical Guide to Accessing the Windows iSCSI Initiator</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/a-quick-guide-secure-your-instagram-stories-with-screen-record-for-2024/"><u>A Quick Guide  Secure Your Instagram Stories with Screen Record for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-simplified-guide-to-jdk-setup-for-modern-windows-11-users/"><u>A Simplified Guide to JDK Setup for Modern Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-breakdown-of-entering-and-exiting-terminals-zen-space/"><u>A Step-by-Step Breakdown of Entering & Exiting Terminal's Zen Space</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-linux-vms-within-windows-via-hyper-v/"><u>A Step-by-Step Guide to Linux VMs Within Windows via Hyper-V</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-solution-to-eradicate-error-code-740-on-win-11/"><u>A Step-by-Step Solution to Eradicate Error Code 740 on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-and-starting-verifier-manager-in-win11-os/"><u>Accessing and Starting Verifier Manager in Win11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/ace-the-art-of-completing-a-perfect-windows-update/"><u>Ace the Art of Completing a Perfect Window's Update</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-invalid-token-usage-in-modern-windows-systems/"><u>Addressing Invalid Token Usage in Modern Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-powershell-from-windows-command-prompt/"><u>Addressing Missing PowerShell From Windows Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-screen-driver-crash-in-windows-11/"><u>Addressing Screen Driver Crash in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-activation-issue-with-error-0x803f700f/"><u>Addressing Windows Activation Issue with Error 0X803F700f</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-disk-fragmentation-issue/"><u>Addressing Windows Disk Fragmentation Issue</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-gameplay-recording-harnessing-intel-graphics-hub/"><u>Advanced Gameplay Recording: Harnessing Intel Graphics Hub</u></a></li>
<li><a href="https://win11.techidaily.com/advancing-classic-games-in-hd-best-practices-with-scummvm-and-windows-os/"><u>Advancing Classic Games in HD: Best Practices with ScummVM and Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/affordable-access-securing-low-cost-windows-11-vcs/"><u>Affordable Access: Securing Low-Cost Windows 11 VCs</u></a></li>
<li><a href="https://win11.techidaily.com/altering-windows-standard-pdf-display/"><u>Altering Window's Standard PDF Display</u></a></li>
<li><a href="https://win11.techidaily.com/asuss-innovation-unleashed-exploring-s15-oled-and-bape-edition/"><u>Asus's Innovation Unleashed: Exploring S15 OLED and BAPE Edition</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-compatibility-woes-with-surface-firmware-upgrade-tips/"><u>Avoid Compatibility Woes with Surface Firmware Upgrade Tips</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-challenges-of-windows-steam-content-blocks/"><u>Avoiding the Challenges of Windows Steam Content Blocks</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-realme-narzo-60-5g-drfone-by-drfone-virtual-android/"><u>Best 10 Mock Location Apps Worth Trying On Realme Narzo 60 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/blackview-mp60-mini-pc-expandable-storage-but-unremarkable-performance/"><u>Blackview MP60 Mini PC: Expandable Storage but Unremarkable Performance</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-ease-of-use-with-mouse-settings-in-win11/"><u>Boosting Ease of Use with Mouse Settings in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-key-steps-to-tackle-windows-blue-screen/"><u>Breaking Down Key Steps to Tackle Windows Blue Screen</u></a></li>
<li><a href="https://fox-glue.techidaily.com/decoding-the-process-behind-gopro-burst-recordings/"><u>Decoding the Process Behind GoPro Burst Recordings</u></a></li>
<li><a href="https://techtrends.techidaily.com/expert-advice-correcting-error-codes-39-on-windows-based/"><u>Expert Advice: Correcting Error Codes 39 on Windows-Based</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-can-i-get-more-stardust-in-pokemon-go-on-zte-axon-40-lite-drfone-by-drfone-virtual-android/"><u>How can I get more stardust in pokemon go On ZTE Axon 40 Lite? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-honor-x8b-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Honor X8b to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-breaking-down-the-animation-process-a-movie-maker-approach/"><u>In 2024, Breaking Down the Animation Process  A Movie Maker Approach</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-motorola-moto-e13-drfone-by-drfone-virtual-android/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Motorola Moto E13 | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-any-xiaomi-redmi-12-5g-phone-password-using-emergency-call-by-drfone-android/"><u>In 2024, How To Unlock Any Xiaomi Redmi 12 5G Phone Password Using Emergency Call</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-tecno-phantom-v-fold-drfone-by-drfone-virtual-android/"><u>In 2024, Will Pokémon Go Ban the Account if You Use PGSharp On Tecno Phantom V Fold | Dr.fone</u></a></li>
<li><a href="https://program-issues.techidaily.com/solving-the-issue-of-persistent-minecraft-crashes-a-step-by-step-guide/"><u>Solving the Issue of Persistent Minecraft Crashes - A Step-by-Step Guide</u></a></li>
<li><a href="https://extra-hints.techidaily.com/streamline-your-audio-content-with-googles-tools/"><u>Streamline Your Audio Content with Google’s Tools</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-fourfold-technique-to-achieve-a-blurred-look-in-iphone-photography-for-2024/"><u>The Fourfold Technique to Achieve a Blurred Look in iPhone Photography for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/vivo-y27-4g-stuck-on-screen-finding-solutions-for-stuck-on-boot-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Vivo Y27 4G Stuck on Screen – Finding Solutions For Stuck on Boot | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719275577489-winshift-troubles-how-to-resolve-them/"><u>WinShift Troubles: How to Resolve Them</u></a></li>
</ul></div>
