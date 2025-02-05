---
title: Unlock Copy & Paste on Edge Within Windows 11'S App Guard
date: 2025-02-02T19:36:58.999Z
updated: 2025-02-04T09:40:37.774Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlock Copy & Paste on Edge Within Windows 11'S App Guard
excerpt: This Article Describes Unlock Copy & Paste on Edge Within Windows 11'S App Guard
keywords: Unlock C&P Edge Security,Navigate Ctrl+C/V Edge,Bypass Edge APG Lock,Enable Copy on Windows 11,Edge's App Guard Bypass,Access Paste in Edge 11,Override APG Copy Feature
thumbnail: https://thmb.techidaily.com/f61e0cf06b5f94c52331e7280bfea34d0fc7a11feee31daa0334519a989e1892.jpg
---

## Unlock Copy & Paste on Edge Within Windows 11'S App Guard

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

## 1\. How to Enable Copy and Paste via Windows Settings

 To enable copy and paste in Application Guard for Edge, follow the steps below:

1. Right-click on Start and select**Settings** from the menu list. For more information, check out our guide on[how to open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Privacy & security** from the left pane.
3. Then click the**Windows Security** option on the right-hand side.
4. On the following screen, select**App & browser control** .
5. Go to the Isolated browsing section and click the link "Change Applications Guard settings."  
![Change Application Guard Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-application-guard-settings.jpg)
6. Search for the**Copy and paste** option, then click the toggle to enable it.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fo4lNZ84x9Q?si=WdcYPZp-9VJnZEnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Enable Copy and Paste Using Registry Editor

 The Windows Registry is another method you can use to copy and paste within Application Guard for Edge on your Windows 11 PC. But, please be aware that editing the registry can have severe consequences if done incorrectly. To be safe,[back up the registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you begin making any changes.

 Follow these steps to enable copy and paste using the Windows Registry Editor:

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type "regedit" in the text box and press the Enter key.
3. If UAC prompts appear on the screen, click**Yes** to confirm your action.
4. In the Registry Editor window, navigate to the following location:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi`
5. If you don't find the Hvsi key there, you will need to create it. To do this, right-click on Microsoft and select**New > Key** .

1. In the box that appears, give it the name**Hvsi** , and then hit Enter to save the file.
2. Now right-click on**Hvsi** and select**New > DWORD (32-bit) Value** .  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
3. Put**EnableClipboard** as the name for the new DWORD key, then press Enter.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OmJZ4Z8jgk?si=YIoEaPI8geoiFSYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

## Copy and Paste Now Works With Edge Application Guard

 With Application Guard for Edge, your device can remain secure while browsing the web. Unfortunately, certain functionalities such as copy and paste are disabled by default - but don't worry! This guide will explain two methods to activate them quickly and easily.

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
<li><a href="https://screen-capture.techidaily.com/new-in-2024-a-step-by-step-approach-to-youtube-video-saving/"><u>[New] In 2024, A Step-by-Step Approach to YouTube Video Saving</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-the-future-in-your-hands-screenflows-role-in-macos-innovation-for-2024/"><u>[New] The Future in Your Hands ScreenFlow's Role in MacOS Innovation for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-apowersoft-screen-recorder-review-and-alternative/"><u>[Updated] Apowersoft Screen Recorder Review and Alternative</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-fine-tune-video-quality-for-instagram-excellence/"><u>[Updated] In 2024, Fine-Tune Video Quality for Instagram Excellence</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-tapping-into-trends-your-guide-to-impactful-instagram-tags/"><u>[Updated] In 2024, Tapping Into Trends Your Guide to Impactful Instagram Tags</u></a></li>
<li><a href="https://win11.techidaily.com/apexflac/"><u>「瞬時にAPEXファイルから高品質なFLACへの完全保存変換テクニック」</u></a></li>
<li><a href="https://win11.techidaily.com/m4a-wma-m4awma/"><u>初心者向けガイド：M4A ファイルとWMA ファイルの差異と M4AをWMAに容易に変換する方法</u></a></li>
<li><a href="https://win11.techidaily.com/best-video-transformation-tool-batch-convert-avi-over-1gb-to-mp4-for-free/"><u>Best Video Transformation Tool: Batch Convert AVI over 1GB to MP4 for Free!</u></a></li>
<li><a href="https://extra-tips.techidaily.com/capture-like-a-pro-gopro-model-comparison-guide/"><u>Capture Like a Pro Gopro Model Comparison Guide</u></a></li>
<li><a href="https://win11.techidaily.com/complete-guide-downloading-facebook-live-content-self-and-others/"><u>Complete Guide: Downloading Facebook Live Content - Self & Others</u></a></li>
<li><a href="https://win11.techidaily.com/cut-your-tracks-like-a-pro-best-no-cost-mp3-clippers-compatible-with-windows-11/"><u>Cut Your Tracks Like a Pro: Best No-Cost MP3 Clippers Compatible with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/easy-techniques-for-adding-subtitles-during-video-file-conversion/"><u>Easy Techniques for Adding Subtitles During Video File Conversion</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-thumbnail-length-a-guide-to-captivating-audiences/"><u>In 2024, Thumbnail Length A Guide to Captivating Audiences</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-resizing-videos-a-comprehensive-guide-for-optimized-aspect-ratios-on-tiktok/"><u>Master the Art of Resizing Videos: A Comprehensive Guide for Optimized Aspect Ratios on TikTok</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-webm-video-compression-made-easy-best-online-services/"><u>New WebM Video Compression Made Easy Best Online Services</u></a></li>
<li><a href="https://win-deluxe.techidaily.com/yl-software-expertise-mastering-sound-configuration-in-windows-settings-for-enhanced-user-experience/"><u>YL Software Expertise: Mastering Sound Configuration in Windows Settings for Enhanced User Experience</u></a></li>
<li><a href="https://win11.techidaily.com/1726029187166-wonderfox/"><u>すべての角を守る！WonderFox | カバーマウントモデル検討</u></a></li>
</ul></div>

