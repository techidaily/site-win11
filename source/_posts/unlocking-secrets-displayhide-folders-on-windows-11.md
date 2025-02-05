---
title: "Unlocking Secrets: Display/Hide Folders on Windows 11"
date: 2025-02-02T22:17:26.673Z
updated: 2025-02-04T02:59:59.923Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking Secrets: Display/Hide Folders on Windows 11"
excerpt: "This Article Describes Unlocking Secrets: Display/Hide Folders on Windows 11"
keywords: Win11 Folder Management,Hide Windows Files,Show Hidden Content,XP/Vista Comparison,Secure File Hiding,Windows Privacy Settings,Advanced Explorer Tweaks
thumbnail: https://thmb.techidaily.com/3da56b4dd62c9d29faa422fa86eb533c5fdaa7995cd6fe5de9f6ecf749c3b6f7.jpg
---

## Unlocking Secrets: Display/Hide Folders on Windows 11

 If you’re running the latest version of Windows 11, the folders in This PC will be hidden by default. That's by design so you can pay more attention to your drives. However, there’s a way you can unhide them so you can access them.

 In this guide, we are going to show you how to add or remove the 3D Objects, Documents, Music, Video, Pictures, and Downloads in This PC by making a few Windows Registry tweaks.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Before You Start Adding or Removing Folders in This PC…

 We are going to make changes to the Windows Registry by adding keys and values to it using the Registry Editor. To fire it up, press **Win + R** to bring up the Windows Run dialog box, enter **regedit** in the text box, and then click **OK**.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 Before you proceed, we highly recommend reading our guide on [what the Windows Registry is and how to edit it](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) to familiarize yourself with what we will be doing next. Also important is knowing [how to back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). Considering this is the database that Windows stores the data it needs to operate properly, you will need this backup in case you make an error.

 For showing and hiding folders in This PC to work, make sure you’re running the latest version of Windows 11\. You'll know you have it if File Explorer has tabs.

 With the Registry Editor open, let's get to it.

## How to Show or Hide the 3D Objects Folder in This PC

 For the **3D Objects** folder, you need to add a key to the registry and the folder will pop up in This PC. So, in the address bar of the Registry Editor, enter the below path and then hit the **Enter** key:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace

 Next, right-click the **NameSpace** key in the left panel and select **New > Key**. Then, name that key **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}**. If the name is a bit too hard to type out, just copy and paste it.

![new-key-namespace-regedit-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-key-namespace-regedit-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once done, refresh File Explorer by hitting **F5**. Now you will see that the **3D Objects** folder has appeared in This PC.

![3d-objects-this-pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3d-objects-this-pc.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To remove the folder again, just go back to the Registry Editor, right-click the **{0DB7E03F-FC29-4DC6-9020-FF41B59E513A}** key, and select **Delete**. After you refresh File Explorer, the folder will be gone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vca--yEhtdo?si=7ijqjyP-oi3LYze1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the Documents, Music, Videos, Pictures, and/or Downloads Folders in This PC

 To add the **Documents** folder to This PC, enter the below path in the address bar of the Registry Editor and then hit **Enter** on your keyboard to go where its key is located:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{d3162b92-9365-467a-956b-92703aca08af}

 Right-click the **HideIfEnabled** value in the right panel and select **Delete**.

![delete-hideifenabled-value-regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-hideifenabled-value-regedit.jpg)

 Now, refresh File Explorer with **F5** and the **Documents** folder will appear in This PC.

 To hide it, right-click the key on the left panel and select **New > DWORD (32-bit) Value** and name it **HideIfEnabled**. Double-click the newly-created value in the right panel, set **Value data** to **22ab9b9**, and then click **OK**.

![set-hideifenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/set-hideifenabled.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SgRVYjqB70s?si=My_2cDvJVdincQRu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now when you refresh This PC in File Explorer, you will see that the **Documents** folder is gone.

 The steps to show or hide the other folders from this point on are the same. Just go to the respective key in the Registry Editor and either delete the **HideIfEnabled** value to show the folder in this PC or create the value and set it to **22ab9b9** to hide the folder.

 Here’s the path to the **Music** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{3dfdf296-dbec-4fb4-81d1-6a3438bcf4de}

 Here’s the path to the **Video** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{f86fa3ab-70d2-4fc7-9c99-fcbf05467f3a}

 Here’s the path to the **Pictures** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{24ad3ad4-a569-4530-98e1-ab02f9417aa8}

 Here’s the path to the **Downloads** folder:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\MyComputer\NameSpace\{088e3905-0323-4b02-9826-5d99428e115f}

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Choose the Folders You Want to Appear on This PC in Windows 11

 If you want to see folders on This PC, you can do so by making a couple of edits to the Windows Registry. While we do recommend that you know what you’re doing if you proceed, we have made the instructions relatively simple to follow so there's minimal chance of messing up the registry.

 As long as you take the necessary steps not to mess up the Windows Registry, you should be able to hide and show the folders you want easily.

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
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-youtubes-buffering-blues-your-pathway-out-current-strategies/"><u>[Updated] 2024 Approved YouTube's Buffering Blues – Your Pathway Out (Current Strategies)</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-premiere-moments-in-motion/"><u>[Updated] Premiere Moments in Motion</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-screen-commanders-clash-for-2024/"><u>[Updated] Screen Commanders Clash for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/discover-the-leading-productivity-laptop-thats-not-from-lenovo-or-apple-exclusive-review/"><u>Discover the Leading Productivity Laptop That's Not From Lenovo or Apple: Exclusive Review</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-media-management-lowering-memory-and-cpu-demand-in-windows/"><u>Efficient Media Management: Lowering Memory and CPU Demand in Windows</u></a></li>
<li><a href="https://win-hot.techidaily.com/guida-per-reimpostare-e-recuperare-file-cancellati-accidentalmente-in-windows-11/"><u>Guida per Reimpostare E Recuperare File Cancellati Accidentalmente in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-microsoft-teams-when-it-keeps-asking-you-to-sign-in-on-windows/"><u>How to Fix Microsoft Teams When It Keeps Asking You to Sign In on Windows</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-itel-p55plus-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked Itel P55+ in Minutes | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-elevating-online-presence-with-obs-facebook-linking/"><u>In 2024, Elevating Online Presence with OBS-Facebook Linking</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-encouraging-student-participation/"><u>In 2024, Encouraging Student Participation</u></a></li>
<li><a href="https://win11.techidaily.com/initiate-15-approaches-to-system-controls/"><u>Initiate: 15 Approaches to System Controls</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/leading-luminaries-of-livestreaming-success/"><u>Leading Luminaries of Livestreaming Success</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-screen-management-via-driver-rollbacks-in-win1011/"><u>Mastering Screen Management via Driver Rollbacks in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-network-address-translation-change-in-win1110/"><u>Navigating Network Address Translation Change in Win11/10</u></a></li>
<li><a href="https://win11.techidaily.com/pathway-to-the-canvas-launching-ms-paint-in-windows-11/"><u>Pathway to the Canvas: Launching MS Paint in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/rapid-renders-how-to-quickly-fix-wwe-2k23-on-pcs/"><u>Rapid Renders: How to Quickly Fix WWE 2K23 on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-smooth-full-screen-play-for-sonic-games-w11/"><u>Unlocking Smooth Full Screen Play for Sonic Games (W11)</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-zte-nubia-z60-ultra-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On ZTE Nubia Z60 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/winning-the-battle-against-file-error-0x80070570-fix-guide-for-windows-11/"><u>Winning the Battle Against File Error 0X80070570: Fix Guide for Windows 11</u></a></li>
</ul></div>

