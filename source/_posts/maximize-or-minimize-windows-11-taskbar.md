---
title: Maximize or Minimize Windows 11 Taskbar
date: 2024-12-17T18:00:56.349Z
updated: 2024-12-22T16:52:52.822Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Maximize or Minimize Windows 11 Taskbar
excerpt: This Article Describes Maximize or Minimize Windows 11 Taskbar
keywords: Maximize Windows Bar,Minimize Windows Bar,Taskbar Expansion,Taskbar Reduction,Adjust Window Bar,Control Taskbar Size,Optimize Taskbar Height
thumbnail: https://thmb.techidaily.com/f00def1c04cb418f21da5c60f199b078da943127e970aa7acf9eb30479f71c91.jpg
---

## Maximize or Minimize Windows 11 Taskbar

 Ever looked at the Windows 11 Taskbar and thought it looks too small for your liking? Or maybe you feel it could be a little smaller? If that’s the case, you can change its size to suit your needs by making it bigger or smaller.

 Unlike Windows 10, you can’t just unlock the Taskbar and adjust its size freely in Windows 11\. While Microsoft has removed this way of going about it in Windows 11, there is a workaround that you can use, although it’s not as elegant.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f3PFn06LijE?si=zHrmlTOzrKxXe-k4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![changing the taskbarsi value to 2 in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/taskbarsi-value-2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you restart your computer, you will see the result: an enlarged Taskbar.

![an enlarged Taskbar on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-enlarged-taskbar.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To make the Taskbar smaller, enter**0** in the**Value data** text box, click**OK** , and then restart your computer. You will then see that the Taskbar has shrunk.

![a smaller taskbar in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-small-taskbar.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you decide to go back to the Taskbar’s default size, you can easily set**Value data** to**1** or simply delete the**TaskbarSi** value.

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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-clipcomposer-critique-full-report/"><u>[New] 2024 Approved ClipComposer Critique – Full Report</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-free-youtube-endings-that-stand-out-ranked-for-2024/"><u>[Updated] Free YouTube Endings That Stand Out - Ranked for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-navigating-high-dynamic-range-photography-with-ps-for-2024/"><u>[Updated] Navigating High Dynamic Range Photography with PS for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/converting-apples-ical-to-windows-a-complete-tutorial/"><u>Converting Apple's iCal to Windows: A Complete Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/determine-active-tcp-ports-on-your-windows-pc/"><u>Determine Active TCP Ports on Your Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-find-out-how-much-space-your-apps-use-on-windows/"><u>How to Find Out How Much Space Your Apps Use on Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-capturing-the-cosmos-mastering-editing-techniques-for-starry-images/"><u>In 2024, Capturing the Cosmos Mastering Editing Techniques for Starry Images</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-11-zerox-error-code-0x80049dd3/"><u>Navigating Through Windows 11 Zerox Error (Code: 0X80049DD3)</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/new-how-to-add-emojis-to-discord-on-desktop-computer-and-mobile/"><u>New How to Add Emojis To Discord on Desktop Computer and Mobile</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-lockout-no-admin-pass-needed/"><u>Overcoming Windows 11 Lockout: No Admin Pass Needed</u></a></li>
<li><a href="https://win11.techidaily.com/preventive-measures-for-avoiding-windows-error-code-0xc00000f/"><u>Preventive Measures for Avoiding Windows Error Code: 0Xc00000f</u></a></li>
<li><a href="https://win-luxury.techidaily.com/troubleshooting-lost-drives-in-windows-systems-with-insights-from-yl-software-experts/"><u>Troubleshooting Lost Drives in Windows Systems with Insights From YL Software Experts</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-guide-winx-mediatrans-mastery-step-by-step-conversion-of-audio-video-and-images/"><u>Ultimate Guide: WinX MediaTrans Mastery – Step-by-Step Conversion of Audio, Video, and Images</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/king-youtube-melodies-safe-free-extraction-methods-for-2024/"><u>Unlocking YouTube Melodies Safe, Free Extraction Methods for 2024</u></a></li>
<li><a href="https://win-able.techidaily.com/1726029590268-wav/"><u>WAV形式音声ファイルの音量設定手順と、使いやすい無料アプリ・ウェブサービス</u></a></li>
<li><a href="https://win11.techidaily.com/windows-n-editions-unveiled-a-comparative-guide/"><u>Windows N Editions Unveiled: A Comparative Guide</u></a></li>
</ul></div>

