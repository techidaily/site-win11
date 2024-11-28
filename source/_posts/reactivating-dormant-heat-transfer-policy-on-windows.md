---
title: Reactivating Dormant Heat Transfer Policy on Windows
date: 2024-11-26T20:11:13.532Z
updated: 2024-11-28T03:29:52.633Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reactivating Dormant Heat Transfer Policy on Windows
excerpt: This Article Describes Reactivating Dormant Heat Transfer Policy on Windows
keywords: WINDOWS HT Policy Reactivation,HT Policy Update Windows,Reviving Windows Thermal Policy,Restarting HT Policy Windows,Dormant Heat Transfer in Windows,Thermal Management Windows Reinitiate,Windows HT Process Renewal
thumbnail: https://thmb.techidaily.com/79265524b64a96a355aa9c66ef040a78b4c61cd77b813b963d28880dc313d729.jpg
---

## Reactivating Dormant Heat Transfer Policy on Windows

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on[what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Bringing Back the System Cooling Policy on Windows

 Now that the system cooling policy has returned you can tweak it to your liking. We have even shown you how to hide it again in case you don’t want others messing with it. If these methods don’t work, you might have another problem with your computer.

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
<li><a href="https://youtube-webster.techidaily.com/024-approved-enriching-videos-with-no-cost-sounds-legally/"><u>[New] 2024 Approved Enriching Videos with No-Cost Sounds Legally</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-simplified-game-video-capture-via-nvidia/"><u>[New] 2024 Approved Simplified Game Video Capture via NVIDIA</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-on-demand-broadcasts-a-guide-to-efficient-recording/"><u>[Updated] 2024 Approved On-Demand Broadcasts A Guide to Efficient Recording</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-the-ultimate-viewer-writers-guide/"><u>[Updated] In 2024, The Ultimate Viewer' Writers Guide</u></a></li>
<li><a href="https://win-docs.techidaily.com/excel-9/"><u>如何恢复失去或丢失的 Excel 文件: 走向成功的 9 种方法</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-add-a-pcmcia-adapter-to-your-computer-using-windows-quick-and-effective-tutorials/"><u>Effortlessly Add a PCMCIA Adapter to Your Computer Using Windows – Quick & Effective Tutorials!</u></a></li>
<li><a href="https://win11.techidaily.com/flacitunesmp3/"><u>FLAC形式からiTunes対応のMP3への完全ガイド変換</u></a></li>
<li><a href="https://win11.techidaily.com/guide-steps-for-transferring-films-onto-your-portable-usb-flash-drive/"><u>Guide: Steps for Transferring Films Onto Your Portable USB Flash Drive</u></a></li>
<li><a href="https://win11.techidaily.com/how-does-handbrake-enable-video-rotation-and-flipping-techniques/"><u>How Does Handbrake Enable Video Rotation and Flipping Techniques?</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-dvd-ripping-for-pcs-and-macs-comprehensive-step-by-step-instructions/"><u>Mastering the Art of DVD Ripping for PCs & Macs: Comprehensive Step-by-Step Instructions</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-windowsgif/"><u>Microsoft Windowsインターフェース内で簡単に動く画像(GIF)を制作するためのガイド</u></a></li>
<li><a href="https://fox-helps.techidaily.com/speech-to-text-magic-free-edition-for-2024/"><u>Speech-to-Text Magic Free Edition for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/trouble-with-updownleftright-keys-discover-easy-fixes-now/"><u>Trouble with Up/Down/Left/Right Keys? Discover Easy Fixes Now!</u></a></li>
<li><a href="https://article-tips.techidaily.com/unpacking-the-features-and-shortcomings-of-samsung-image-editor-for-2024/"><u>Unpacking the Features and Shortcomings of Samsung Image Editor for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/iuodkplusodhplusocquobruocsoodroodvoocueocseodvoodqpluswkieapmpluswfpemwgdog44gz44g544gm44gr5b2556ul44gk55m96bus5yyw5pa55rovig/"><u>ビデオのグレースケール変換入門: すべてに役立つ白黒化方法</u></a></li>
</ul></div>

