---
title: Customize Your Taskbar Size & Space on Win11
date: 2024-12-05T02:23:55.059Z
updated: 2024-12-07T10:25:49.920Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customize Your Taskbar Size & Space on Win11
excerpt: This Article Describes Customize Your Taskbar Size & Space on Win11
keywords: Win11 Taskbar Resize,Personal Taskbar Setup,Adjust Windows Bar,Custom Taskbar Sizing,Optimize Screen Bar,Change Taskbar Size,Space Control Bar
thumbnail: https://thmb.techidaily.com/3435ed54de8a47266623e22c7fb2a2e96dbea38f3e30be83e17069ff0556f42f.png
---

## Customize Your Taskbar Size & Space on Win11

 Ever looked at the Windows 11 Taskbar and thought it looks too small for your liking? Or maybe you feel it could be a little smaller? If that’s the case, you can change its size to suit your needs by making it bigger or smaller.

 Unlike Windows 10, you can’t just unlock the Taskbar and adjust its size freely in Windows 11\. While Microsoft has removed this way of going about it in Windows 11, there is a workaround that you can use, although it’s not as elegant.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Make the Windows 11 Taskbar Bigger or Smaller?

 The only way to change the size of the Taskbar is to use the Registry Editor. However, we advise caution when dealing with the Windows Registry because if something goes wrong, you might experience performance issues on your Windows 11 PC. If you’re unfamiliar with it, we recommend reading our guides on[what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) and[how to not mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/) .

 Once you’re all caught up or are already familiar with the Windows Registry, and you know what you’re doing, you can make the Taskbar bigger or smaller. To do that:

1. Start by pressing**Win + R** to open Windows Run.
2. Type**regedit** in the text box and hit the**Enter** key.
3. Then, click**Yes** on the UAC prompt to launch the Registry Editor.
4. Copy and paste the below text in the address bar of the Registry Editor and hit the**Enter** key:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the**Advanced** key, look for a value called**TaskbarSi** . If it’s not there, right-click**Advanced** , select**New > DWORD (32-bit) Value** , and name that value**TaskbarSi.**  
![creating a new dword in the advanced key in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/new-dword-advanced-regedit.jpg)
6. Double-click**TaskbarSi** to edit it, and then enter**2** in the**Value data** text box and click**OK** to make the Taskbar bigger.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PNw3Lb26wFA?si=5NR1XRVSp41EQYMy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![changing the taskbarsi value to 2 in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/taskbarsi-value-2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you restart your computer, you will see the result: an enlarged Taskbar.

![an enlarged Taskbar on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-enlarged-taskbar.jpg)

 To make the Taskbar smaller, enter**0** in the**Value data** text box, click**OK** , and then restart your computer. You will then see that the Taskbar has shrunk.

![a smaller taskbar in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-small-taskbar.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/e4Nt2xXXtmE?si=CtKwFry4b0AJXnaN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you decide to go back to the Taskbar’s default size, you can easily set**Value data** to**1** or simply delete the**TaskbarSi** value.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Adjust the Taskbar’s Size to Suit Your Needs on Windows 11

 Even though you can’t make the Taskbar bigger or smaller on Windows 11 as easily as you can on Windows 10, a little know-how can help. And as long as you followed the instructions mentioned above correctly, you shouldn’t worry about messing up the Windows Registry. However, we still recommend that you use this method only if you know what you’re doing.

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
<li><a href="https://some-techniques.techidaily.com/new-innovative-image-editors-your-ultimate-text-companion/"><u>[New] Innovative Image Editors Your Ultimate Text Companion</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-unveil-8-reliable-video-promotion-services/"><u>[New] Unveil 8 Reliable Video Promotion Services</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-unveiling-5-strategies-for-fb-story-access-on-pctablet-and-phone/"><u>[New] Unveiling 5 Strategies for FB Story Access on PC/Tablet and Phone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-transforming-discord-chats-into-lasting-memories-for-2024/"><u>[Updated] Transforming Discord Chats Into Lasting Memories for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723203675679-5-effective-techniques-to-unfreeze-a-stubborn-windows-10-taskbar/"><u>5 Effective Techniques to Unfreeze a Stubborn Windows 10 Taskbar</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-on-mobile-unveiling-six-superiorities-of-the-ios-app-compared-to-its-web-counterpart/"><u>ChatGPT on Mobile: Unveiling Six Superiorities of the iOS App Compared to Its Web Counterpart</u></a></li>
<li><a href="https://win-solutions.techidaily.com/crash-free-gaming-top-strategies-to-tackle-state-of-decay-2-bugs-this-year/"><u>Crash-Free Gaming: Top Strategies to Tackle State of Decay 2 Bugs This Year!</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-user-profiles-with-precise-gpo-settings-in-win-oses/"><u>Customizing User Profiles with Precise GPO Settings in Win OSes</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-platform-user-service-stability-on-windows/"><u>Enhancing Platform User Service Stability on Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-spotify-location-after-moving-to-another-country-on-oneplus-ace-2-drfone-by-drfone-virtual-android/"><u>How to Change Spotify Location After Moving to Another Country On OnePlus Ace 2 | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-how-to-view-instagram-stories-anonymously-on-pc-android-and-iphone/"><u>In 2024, How to View Instagram Stories Anonymously on PC, Android, and iPhone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-tecno-phantom-v-flip-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On Tecno Phantom V Flip? Fixed | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/nostalgic-gameplay-unlocked-dosbox-x-edition/"><u>Nostalgic Gameplay Unlocked: DOSBox-X Edition</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-interactive-functionality-of-windows-11-menu-system/"><u>Restoring Interactive Functionality of Windows 11 Menu System</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-onedrive-account-on-a-windows-pc/"><u>Restoring OneDrive Account on a Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/scribble-to-screen-top-8-notetaking-alternatives-for-windows-pcs/"><u>Scribble to Screen: Top 8 Notetaking Alternatives for Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/shattered-crypto-key-dont-rush-for-new-guardians/"><u>Shattered Crypto Key: Don't Rush for New Guardians</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-viewing-best-free-windows-media-players/"><u>Streamline Your Viewing: Best Free Windows Media Players</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-task-management-speed-in-windows-11/"><u>Upgrading Task Management Speed in Windows 11</u></a></li>
</ul></div>

