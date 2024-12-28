---
title: Guide to Conceal Dim Display Feature in Win OS Control Panel
date: 2024-12-22T00:03:09.924Z
updated: 2024-12-27T22:08:26.654Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Conceal Dim Display Feature in Win OS Control Panel
excerpt: This Article Describes Guide to Conceal Dim Display Feature in Win OS Control Panel
keywords: Windows Hidden Features Guide,Dim Screen Settings Windows,Control Panel Customization,Windows OS Concealment Tips,Display Concealment Techniques,WinOS Feature Management,Optimize Win OS Visibility
thumbnail: https://thmb.techidaily.com/94f7e6bb0d500f60edc6e34b363527bd47bbfffa481cdc60b824492075830e06.jpg
---

## Guide to Conceal Dim Display Feature in Win OS Control Panel

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/e4Nt2xXXtmE?si=CtKwFry4b0AJXnaN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Controlling the “Dim Display After” Option in the Power Options Menu

 Now that you know how to show or hide **Dim display after**, you know what to do when you can’t find it in the Power Options menu or need to remove it. We recommend keeping it hidden and then bringing it up whenever you need it. This will make sure that no one messes with this important display setting when you’ve set it up perfectly.

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
<li><a href="https://fox-blue.techidaily.com/new-in-2024-effortless-facial-obscurity-in-photos/"><u>[New] In 2024, Effortless Facial Obscurity in Photos</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-prime-8-chart-tracer-apex-of-youtube-rankings/"><u>2024 Approved Prime 8 Chart Tracer Apex of YouTube Rankings</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-revolutionary-6-applications-to-enhance-photo-editing-experience/"><u>2024 Approved Revolutionary 6 Applications to Enhance Photo Editing Experience</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-top-10-extensions-for-maxed-out-terria/"><u>2024 Approved Top 10 Extensions for Maxed-Out Terria</u></a></li>
<li><a href="https://some-techniques.techidaily.com/easy-instructions-for-starting-google-chrome-from-terminal-on-windows-11/"><u>Easy Instructions for Starting Google Chrome From Terminal on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/get-back-into-the-microsoft-store-top-login-solutions/"><u>Get Back Into the Microsoft Store - Top Login Solutions</u></a></li>
<li><a href="https://discover-exclusive.techidaily.com/hd-video-converter-factory-for-mobile-devices-download-guide-and-tips-gratuito/"><u>HD Video Converter Factory for Mobile Devices - Download Guide & Tips Gratuito</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-install-android-apks-with-a-double-click-in-windows-11/"><u>How to Install Android APKs With a Double-Click in Windows 11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-3-easy-ways-to-factory-reset-a-locked-iphone-15-pro-without-itunes-by-drfone-ios/"><u>In 2024, 3 Easy Ways to Factory Reset a Locked iPhone 15 Pro Without iTunes</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-ensuring-accurate-iphone-photo-archive-in-snapchat/"><u>In 2024, Ensuring Accurate iPhone Photo Archive in Snapchat</u></a></li>
<li><a href="https://win11.techidaily.com/inside-out-decoding-wacatacbmls-impact-on-microsoft-windows-users/"><u>Inside Out: Decoding Wacatac.B!ml's Impact on Microsoft Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-edges-uninterrupted-operation-on-win11/"><u>Mastering Edge's Uninterrupted Operation on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-server-connection-in-the-latest-win11-version/"><u>Mastering File Server Connection in the Latest Win11 Version</u></a></li>
<li><a href="https://win11.techidaily.com/overriding-windows-error-codes-with-amd-solutions/"><u>Overriding Windows Error Codes with AMD Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-error-with-amd-195-software/"><u>Resolving Windows Error with AMD 195 Software</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-development-best-practices-for-wsl-2-on-pcs/"><u>Supercharge Development: Best Practices for WSL 2 on PCs</u></a></li>
<li><a href="https://screen-recording.techidaily.com/the-complete-lowdown-on-io-image-recording-software-for-2024/"><u>The Complete Lowdown on IO Image Recording Software for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-windows-nvidia-software-links/"><u>Unblocking Windows NVIDIA Software Links</u></a></li>
<li><a href="https://win11.techidaily.com/winning-over-window-devices-no-more-naming-clashes/"><u>Winning Over Window Devices: No More Naming Clashes!</u></a></li>
</ul></div>

