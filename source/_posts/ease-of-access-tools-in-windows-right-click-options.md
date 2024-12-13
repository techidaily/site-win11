---
title: Ease of Access Tools in Windows' Right-Click Options
date: 2024-12-11T04:49:10.032Z
updated: 2024-12-13T01:07:52.428Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ease of Access Tools in Windows' Right-Click Options
excerpt: This Article Describes Ease of Access Tools in Windows' Right-Click Options
keywords: Windows Accessibility Aids,Right-Click Assistive Features,Easy Access in Windows Tools,In-Menu Help Windows,Right Click Support Windows,Navigate Right Window Menu,Quick Aid in Right-Click Context
thumbnail: https://thmb.techidaily.com/1127690728774d68859773ac2967a71d9b05c7378c0abebd2da2f4a67474809a.jpg
---

## Ease of Access Tools in Windows' Right-Click Options

 There are many ways to run the Compatibility Troubleshooter, but the easiest way is to do it from the context menu by right-clicking on a program and selecting**Troubleshoot Compatibility** . However, sometimes, this option can go missing, and the good news is that you can add it back with a couple of registry tweaks. Keep on reading to find out how.

## What to Do Before Tweaking the Registry Editor

 Before you go about making big changes to your Windows PC, it’s always a good idea to have some sort of backup in case things go wrong. To do that, we highly recommend reading our guide on[creating a system restore with Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) . If you want, you can also read our other guide on[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) if you want to have a copy of it somewhere.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GU08CQVsZz0?si=V-SvPfzRsQysMS0e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Add a "Troubleshoot Compatibility" Option to the Context Menu With the Registry Editor

 Now that you know how to keep the Windows registry safe, it's time to change it with the Registry Editor. We are going to start by adding the**Troubleshoot Compatibility** option to the context menu for EXE files. Afterward, the steps for adding it to other programs are going to be similar. To do that, follow the steps below:

1. Press**Win + R** to open the Run dialog box, enter**regedit** in the text box, and hit the**Enter** key to open the Registry Editor.
2. First, we are going to add the Troubleshoot Compatibility option for the EXE files. Start by copying and pasting the below key path in the address of the Registry Editor and hit the**Enter** key:  
HKEY_CLASSES_ROOT\cmdfile\shellEx\ContextMenuHandlers
3. Right-click the**ContextMenuHandlers** key and then select**New > Key** and name it**Compatibility** . If it is already there, move on to the next step.  
![Adding a new key to the ContextMenuHandler key for the EXE files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-key-compatibility-troubleshooter-context-menu.jpg)
4. Select the**Compatibility** key, double-click**Default** on the right, and set**Value data** to**{1d27f844-3a1f-4410-85ac-14651078412d}** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Entering value data for a string value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enter-value-data.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Next, you’re going to repeat the steps above to add the**Troubleshoot Compatibility** to the context menu of other BAT and CMD files. Just replace the key path in step two with**HKEY\_CLASSES\_ROOT\\batfile\\shellEx\\ContextMenuHandlers\\** for BAT files and**HKEY\_CLASSES\_ROOT\\cmdfile\\shellEx\\ContextMenuHandlers\\** for CMD files.

 Now when you right-click an EXE, BAT, or CMD file, you should see the**Troubleshoot Compatibility** option in the context menu.

![The Troubleshoot compatibility option in the context menu on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/troubleshoot-compatibility-context-menu.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1KKovVi9epE?si=EF7KA7b4KsEpWA-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now you have one more way to[run the Program Compatibility Troubleshooter](https://www.makeuseof.com/run-program-compatibility-troubleshooter-windows/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Run the Program Compatibility Troubleshooter Easily

 The Program Compatibility Troubleshooter is one of the best ways to fix compatibility issues on Windows. If you use it often, it helps to have the tool close. With the instructions above, you can add it to and run it from the context menu, which is extremely convenient.

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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-navigate-office-tasks-with-voice-recognition-in-microsoft-word/"><u>[New] 2024 Approved Navigate Office Tasks with Voice Recognition in Microsoft Word</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-unlocking-the-potential-of-wide-angle-360-photos/"><u>[New] 2024 Approved Unlocking the Potential of Wide Angle 360 Photos</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-exclusive-top-8-gear-in-the-vr-sphere/"><u>[New] Exclusive Top 8 Gear in the VR Sphere</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-secrets-to-crafting-winning-freefire-videos/"><u>[Updated] In 2024, Secrets to Crafting Winning FreeFire Videos</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-elite-collective-photo-music-plus-visual-creation-fusion/"><u>2024 Approved Elite Collective Photo, Music + Visual Creation Fusion</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/a-complete-guide-to-oem-unlocking-on-oneplus-nord-n30-se-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on OnePlus Nord N30 SE</u></a></li>
<li><a href="https://some-approaches.techidaily.com/achieving-ideal-illumination-a-guide-to-masterful-video-lighting-techniques/"><u>Achieving Ideal Illumination: A Guide to Masterful Video Lighting Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/coordinated-chaos-how-androidpluswindows-sync-works/"><u>Coordinated Chaos: How Android+Windows Sync Works</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-or-disabling-tpm-support-a-complete-vbox-70-guide/"><u>Enabling or Disabling TPM Support - A Complete VBox 7.0 Guide</u></a></li>
<li><a href="https://discover-hacks.techidaily.com/free-online-converter-convert-mov-files-into-high-quality-flac-format/"><u>Free Online Converter: Convert MOV Files Into High-Quality FLAC Format</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-a-weather-icon-to-your-system-tray-in-windows-11/"><u>How to Add a Weather Icon to Your System Tray in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/latest-tricks-for-resolving-2024-miracast-reception-error-on-your-device/"><u>Latest Tricks for Resolving 2024 Miracast Reception Error on Your Device</u></a></li>
<li><a href="https://win11.techidaily.com/learn-to-leverage-windows-11s-pcm-bar-tools-quickly-and-effectively/"><u>Learn to Leverage Windows 11'S PCM Bar Tools Quickly & Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/revive-sluggish-excel-operations-in-a-windows-environment/"><u>Revive Sluggish Excel Operations in a Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/windows-maintenance-navigating-and-purge-of-vacant-directories/"><u>Windows Maintenance: Navigating & Purge of Vacant Directories</u></a></li>
</ul></div>

