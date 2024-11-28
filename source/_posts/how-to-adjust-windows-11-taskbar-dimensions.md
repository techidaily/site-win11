---
title: How to Adjust Windows 11 Taskbar Dimensions
date: 2024-11-22T21:37:58.059Z
updated: 2024-11-27T21:00:43.534Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Adjust Windows 11 Taskbar Dimensions
excerpt: This Article Describes How to Adjust Windows 11 Taskbar Dimensions
keywords: Win11 Taskbar Size Change,Windows 11 Bar Width,Taskbar Thickness Control,Windows Settings Adjustment,Resize WIN11 Toolbar,Dimensions Taskbar Update,Modify WIN11 Bar Dims
thumbnail: https://thmb.techidaily.com/962100c4bb1cf841eba9a73f110c7891af5a14d4cf3e7d146e6c0272a50f3335.jpg
---

## How to Adjust Windows 11 Taskbar Dimensions

 Ever looked at the Windows 11 Taskbar and thought it looks too small for your liking? Or maybe you feel it could be a little smaller? If that’s the case, you can change its size to suit your needs by making it bigger or smaller.

 Unlike Windows 10, you can’t just unlock the Taskbar and adjust its size freely in Windows 11\. While Microsoft has removed this way of going about it in Windows 11, there is a workaround that you can use, although it’s not as elegant.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![changing the taskbarsi value to 2 in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/taskbarsi-value-2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you restart your computer, you will see the result: an enlarged Taskbar.

![an enlarged Taskbar on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-enlarged-taskbar.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To make the Taskbar smaller, enter**0** in the**Value data** text box, click**OK** , and then restart your computer. You will then see that the Taskbar has shrunk.

![a smaller taskbar in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-small-taskbar.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you decide to go back to the Taskbar’s default size, you can easily set**Value data** to**1** or simply delete the**TaskbarSi** value.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-stream-to-screen-how-to-download-youtube-on-iphoneipad/"><u>[Updated] 2024 Approved From Stream to Screen How to Download Youtube on iPhone/iPad</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-hashtags-that-elevate-your-channels-visibility-and-value/"><u>[Updated] Hashtags that Elevate Your Channels' Visibility & Value</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-eyecapture-screen-logger-x/"><u>[Updated] In 2024, EyeCapture Screen Logger X</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-wu-and-orchestrator-integration/"><u>Deciphering WU & Orchestrator Integration</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-visibility-a-cursor-guide-for-win10-and-11/"><u>Enhancing Visibility: A Cursor Guide for Win10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-control-win11-rgb-settings/"><u>How to Control Win11 RGB Settings</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-corrupt-video-files-of-oppo-a58-4g-using-video-repair-utility-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>How to Fix corrupt video files of Oppo A58 4G using Video Repair Utility on Mac?</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3utools-virtual-location-not-working-on-poco-f5-pro-5g-fix-now-drfone-by-drfone-virtual-android/"><u>In 2024, 3uTools Virtual Location Not Working On Poco F5 Pro 5G? Fix Now | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-honor-magic-6-lite-by-drfone-android/"><u>In 2024, Complete Review & Guide to Techeligible FRP Bypass and More For Honor Magic 6 Lite</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/learn-to-tweak-the-speed-of-your-stories-videos-for-2024/"><u>Learn to Tweak the Speed of Your Stories' Videos for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/locked-out-of-iphone-12-pro-5-ways-to-get-into-a-locked-iphone-12-pro-drfone-by-drfone-ios/"><u>Locked Out of iPhone 12 Pro? 5 Ways to get into a Locked iPhone 12 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/making-windows-11-update-problems-non-existent/"><u>Making Windows 11 Update Problems Non-Existent</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/tutoring-triumph-selecting-the-superior-video-recorder-list-for-2024/"><u>Tutoring Triumph Selecting the Superior Video Recorder List for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/your-guide-to-safest-free-software-for-windows-devices/"><u>Your Guide to Safest Free Software for Windows Devices</u></a></li>
</ul></div>

