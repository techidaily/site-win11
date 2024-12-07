---
title: Maximizing PC Potential Through Processor Options
date: 2024-12-05T00:54:25.220Z
updated: 2024-12-07T06:10:53.128Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Maximizing PC Potential Through Processor Options
excerpt: This Article Describes Maximizing PC Potential Through Processor Options
keywords: Optimal PC Performance,Enhance CPU Capacity,Boost System Speed,Advanced Processor Choices,Elevate Computing Power,Superior Chip Selection,Increase PC Output
thumbnail: https://thmb.techidaily.com/cc2d4ffbafce624b537835413e18b0d5bee03ddebe9cf76be61f42eab18cd22c.jpg
---

## Maximizing PC Potential Through Processor Options

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many[ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

![Cmd in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-cmd.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

To show the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c -ATTRIB_HIDE`

To hide the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c +ATTRIB_HIDE`

To show the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec -ATTRIB_HIDE`

To hide the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec +ATTRIB_HIDE`

 After you have typed in the command you want in the CMD window, hit the**Enter** key on your keyboard to run it.

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PKZUYice-ws?si=L8iMa9T3h7TMSWdQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Add or Remove the Minimum and Maximum Processor States From Power Options

 Setting the minimum or maximum processor state on your Windows computer is vital to helping you get the performance you want from it. If you can’t see these options in the Power Options menu, you can easily reveal them with either Command Prompt or the Registry Editor. And after you’re done tweaking the states, you can hide them for their protection.

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
<li><a href="https://extra-guidance.techidaily.com/2024-approved-melody-migration-transitioning-playlists-across-platforms/"><u>2024 Approved Melody Migration Transitioning Playlists Across Platforms</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-phones-at-odds-dissecting-iphone-x-vs-galaxy-face-recognition/"><u>2024 Approved Phones at Odds Dissecting iPhone X Vs. Galaxy Face Recognition</u></a></li>
<li><a href="https://technical-tips.techidaily.com/apple-endorses-national-legislation-supporting-consumers-right-to-repair-electronics/"><u>Apple Endorses National Legislation Supporting Consumer's Right to Repair Electronics</u></a></li>
<li><a href="https://win11.techidaily.com/direct-play-recording-with-intels-gpu-center/"><u>Direct Play Recording with Intel's GPU Center</u></a></li>
<li><a href="https://win11.techidaily.com/easing-into-a-corruption-free-windows-state/"><u>Easing Into a Corruption-Free Windows State</u></a></li>
<li><a href="https://win11.techidaily.com/ending-operation-failures-address-code-0x000-written-by-user2295431/"><u>Ending Operation Failures: Address Code 0X000 Written by User2295431</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-videos-from-your-realme-by-fonelab-android-recover-video/"><u>How to recover old videos from your Realme</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-resolve-non-functional-windows-version-of-battlenet-launcher/"><u>How to Resolve Non-Functional Windows Version of Battle.net Launcher</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-motorola-moto-e13-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Motorola Moto E13 to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://network-issues.techidaily.com/mastering-the-art-of-system-safety-with-safe-mode-on-windows-8/"><u>Mastering the Art of System Safety with Safe Mode on Windows 8</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-mac-video-trimming-made-easy-fast-and-efficient-methods/"><u>New 2024 Approved Mac Video Trimming Made Easy Fast and Efficient Methods</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-your-file-journey-skip-these-file-explorer-slip-ups/"><u>Perfect Your File Journey: Skip These File Explorer Slip-Ups</u></a></li>
</ul></div>

