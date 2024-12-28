---
title: Customizing Taskbar Spacing on Windows 11
date: 2024-12-23T19:26:56.490Z
updated: 2024-12-28T04:09:01.293Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Customizing Taskbar Spacing on Windows 11
excerpt: This Article Describes Customizing Taskbar Spacing on Windows 11
keywords: WinTaskbarAdjustment,SpaceBarTaskConfig,TaskbarCustomizeWin,WindowSpacingTaskbar,AdjustTaskBarWindows,CustomTaskbarSpacing,Windows11TaskBarSpace
thumbnail: https://thmb.techidaily.com/d6473782f31868e794fc3ab8460fc67b139be82f000417effd74e9124ff9dff3.jpg
---

## Customizing Taskbar Spacing on Windows 11

 Ever looked at the Windows 11 Taskbar and thought it looks too small for your liking? Or maybe you feel it could be a little smaller? If that’s the case, you can change its size to suit your needs by making it bigger or smaller.

 Unlike Windows 10, you can’t just unlock the Taskbar and adjust its size freely in Windows 11\. While Microsoft has removed this way of going about it in Windows 11, there is a workaround that you can use, although it’s not as elegant.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/QRaEdFMU-Xc?si=OjaiTvlogJy5wHhN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![changing the taskbarsi value to 2 in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/taskbarsi-value-2.jpg)

 Once you restart your computer, you will see the result: an enlarged Taskbar.

![an enlarged Taskbar on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-enlarged-taskbar.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To make the Taskbar smaller, enter**0** in the**Value data** text box, click**OK** , and then restart your computer. You will then see that the Taskbar has shrunk.

![a smaller taskbar in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-small-taskbar.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you decide to go back to the Taskbar’s default size, you can easily set**Value data** to**1** or simply delete the**TaskbarSi** value.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-art-of-making-youtube-thumbnails-on-the-go-mobile/"><u>[Updated] The Art of Making YouTube Thumbnails on the Go (Mobile)</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-chasing-titles-key-moments-from-2022-olympics-short-tracks/"><u>2024 Approved Chasing Titles Key Moments From 2022 Olympics Short Tracks</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-share-engage-on-leading-websites-facebook-twitter-instagram-and-youtube/"><u>Connect, Share, Engage on Leading Websites: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-integrated-video-workflows-on-ios/"><u>In 2024, Integrated Video Workflows on iOS</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-solutions-to-spy-on-nokia-150-2023-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>In 2024, Solutions to Spy on Nokia 150 (2023) with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://ai-topics.techidaily.com/new-2024-approved-what-is-ai-voice/"><u>New 2024 Approved What Is AI Voice?</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-the-blank-cursor-dilemma-in-win11-quickly/"><u>Overcome the Blank Cursor Dilemma in Win11, Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-barriers-caused-by-error-30005-on-file-creation/"><u>Overcoming Barriers Caused by Error 30005 on File Creation</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1726028910748-pcmdsd/"><u>PCMへの変換でDSDの音質低下を防ぐ方法</u></a></li>
<li><a href="https://win11.techidaily.com/revive-invisible-controls-in-your-windows-11-system-panel/"><u>Revive Invisible Controls in Your Windows 11 System Panel</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-avoid-no-more-space-error/"><u>Strategies To Avoid 'No More Space' Error</u></a></li>
<li><a href="https://win11.techidaily.com/surging-vm-speed-on-windows-implement-these-top-6-strategies/"><u>Surging VM Speed on Windows: Implement These Top 6 Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-overcome-unrecognized-interface-in-windows-os/"><u>Swiftly Overcome Unrecognized Interface in Windows OS</u></a></li>
<li><a href="https://techidaily.com/xiaomi-data-recovery-recover-lost-data-from-xiaomi-redmi-note-12-pro-4g-by-fonelab-android-recover-data/"><u>Xiaomi Data Recovery – recover lost data from Xiaomi Redmi Note 12 Pro 4G</u></a></li>
</ul></div>

