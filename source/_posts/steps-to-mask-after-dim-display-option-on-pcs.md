---
title: Steps to Mask After Dim Display Option on PCs
date: 2024-06-25T11:45:25.680Z
updated: 2024-06-26T11:45:25.680Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Mask After Dim Display Option on PCs
excerpt: This Article Describes Steps to Mask After Dim Display Option on PCs
keywords: Dim Screen Mask Tips,Post-Display Darkening Guide,PC Display Shade Steps,Hide Behind Glass Effect,Low Brightness Mode Advice,Reduce Reflections Techniques,Eye Comfort After Dimming
thumbnail: https://thmb.techidaily.com/029b0eb85077c27446243e8d1c815878a76764b760390b18a7b33382115f2d0b.jpg
---

## Steps to Mask After Dim Display Option on PCs

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

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
<li><a href="https://win11.techidaily.com/fixing-connection-issues-malwarebytes-service-errors-in-win-1011/"><u>Fixing Connection Issues: Malwarebytes' Service Errors in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/leading-painting-programs-beyond-the-procreate-window-experience/"><u>Leading Painting Programs Beyond the Procreate Window Experience</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-overprint-how-to-reactivate-the-missing-windows-functionality/"><u>Mastery Overprint: How to Reactivate the Missing Windows Functionality.</u></a></li>
<li><a href="https://win11.techidaily.com/chronology-clash-wintime-harmony-guide/"><u>Chronology Clash? WinTime Harmony Guide</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-cut-off-others-access-in-the-windows-network/"><u>How to Cut Off Others' Access in the WIndows Network</u></a></li>
<li><a href="https://win11.techidaily.com/revealing-how-ai-pcs-outperform-standard-computers/"><u>Revealing How AI PCs Outperform Standard Computers</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-pcs-global-ip-address-with-terminal-commands/"><u>Unveiling PC's Global IP Address with Terminal Commands</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionizing-creativity-microsoft-paints-fresh-additions/"><u>Revolutionizing Creativity: Microsoft Paint's Fresh Additions</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/olden-threshold-of-youtubes-monetization/"><u>The Golden Threshold of YouTube's Monetization</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-contacts-files-on-oppo-k11-5g-by-fonelab-android-recover-contacts/"><u>Complete guide for recovering contacts files on Oppo K11 5G.</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-oneplus-open-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from OnePlus Open to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/asmr-a-soundtrack-to-better-health-and-happiness-for-2024/"><u>ASMR  A Soundtrack to Better Health and Happiness for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/the-art-of-audio-alteration-for-stories-and-reels-on-ig/"><u>The Art of Audio Alteration  For Stories and Reels on IG</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-how-to-execute-a-budget-friendly-youtube-seminar/"><u>[Updated] How to Execute a Budget-Friendly Youtube Seminar</u></a></li>
<li><a href="https://tools.techidaily.com/wondershare/pdf/download/"><u>Smart PDFElement - PDF Editor</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/mp4-file-editor-for-pc-quickly-trim-cut-and-merge-videos-for-2024/"><u>MP4 File Editor for PC Quickly Trim, Cut, and Merge Videos for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-illuminating-emotions-an-hdr-portraitists-guide/"><u>In 2024, Illuminating Emotions  An HDR Portraitist's Guide</u></a></li>
</ul></div>
