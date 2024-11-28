---
title: Customize Your Taskbar Size & Space on Win11
date: 2024-11-25T21:16:08.576Z
updated: 2024-11-28T03:42:08.950Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
![changing the taskbarsi value to 2 in the Registry Editor on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/taskbarsi-value-2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you restart your computer, you will see the result: an enlarged Taskbar.

![an enlarged Taskbar on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-enlarged-taskbar.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To make the Taskbar smaller, enter**0** in the**Value data** text box, click**OK** , and then restart your computer. You will then see that the Taskbar has shrunk.

![a smaller taskbar in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-desktop-small-taskbar.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you decide to go back to the Taskbar’s default size, you can easily set**Value data** to**1** or simply delete the**TaskbarSi** value.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-expert-tips-for-changing-mac-screenshot-formats/"><u>[Updated] In 2024, Expert Tips for Changing Mac Screenshot Formats</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-strategies-for-boosting-your-youtube-shorts-audience/"><u>[Updated] Strategies for Boosting Your YouTube Shorts Audience</u></a></li>
<li><a href="https://win11.techidaily.com/blu-ray-disc-h264/"><u>「品質保証の下、ハイスピードでBlu-Ray Disc H.264への変換手順」</u></a></li>
<li><a href="https://win11.techidaily.com/cm-3/"><u>動画素材中のCMパターンを見つけ出せ: 3つのスニファリティ方法</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-hd-content-transfer-no-loss-h2-cuffing-guide-using-windows-tools/"><u>Accelerate Your HD Content Transfer: No-Loss H.2 Cuffing Guide Using Windows Tools</u></a></li>
<li><a href="https://win11.techidaily.com/ape-to-wav-file-transformation-techniques-for-windows-macos-smartphones-and-online-tools/"><u>APE to WAV File Transformation Techniques for Windows, macOS, Smartphones & Online Tools</u></a></li>
<li><a href="https://win11.techidaily.com/best-video-format-changers-from-dvd-and-avi-to-mp4-on-windows-11-2024-rankings/"><u>Best Video Format Changers From DVD & AVI to MP4 on Windows 11 (2024 Rankings)</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-understanding-and-evaluating-blackberrys-playbook-tablet/"><u>Comprehensive Guide: Understanding and Evaluating BlackBerry's PlayBook Tablet</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/decoding-the-scope-of-googles-ai-gemini-venture/"><u>Decoding the Scope of Google's AI Gemini Venture</u></a></li>
<li><a href="https://hardware-help.techidaily.com/dive-into-the-world-of-lenovos-thinkpad-x1-fold-a-peculiar-journey-through-unconventional-laptop-design-and-premium-pricing/"><u>Dive Into the World of Lenovo's ThinkPad X1 Fold: A Peculiar Journey Through Unconventional Laptop Design and Premium Pricing</u></a></li>
<li><a href="https://win11.techidaily.com/dvd-mp4/"><u>DVDコピーワラジ脱出 MP4への変換手順</u></a></li>
<li><a href="https://fox-info.techidaily.com/optical-opus-the-elite-list-of-8k-cameras-for-2024/"><u>Optical Opus The Elite List of 8K Cameras for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/play-mov-movies-on-sony-xperia-5-v-is-it-possible-by-aiseesoft-video-converter-play-mov-on-android/"><u>Play MOV movies on Sony Xperia 5 V, is it possible?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/step-by-step-instructions-save-and-enjoy-netflix-titles-later-from-a-mac-computer/"><u>Step-by-Step Instructions: Save and Enjoy Netflix Titles Later From a Mac Computer</u></a></li>
<li><a href="https://extra-resources.techidaily.com/zipped-content-unveiled-crafting-srt-text-files/"><u>Zipped Content Unveiled Crafting Srt Text Files</u></a></li>
</ul></div>

