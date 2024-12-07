---
title: "Leading Edge of Power Management: Max & Min States"
date: 2024-12-02T05:43:55.066Z
updated: 2024-12-07T05:26:03.826Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Leading Edge of Power Management: Max & Min States"
excerpt: "This Article Describes Leading Edge of Power Management: Max & Min States"
keywords: Power State Leadership,Energy Efficiency Peak,Optimal Power Control,Max/Min Energy States,Advanced Battery Management,Energy Minimization Strategies,Power Maximization Techniques
thumbnail: https://thmb.techidaily.com/8823459ab6574b19c976d6905c67df41ee5da35193b7ba8be663bba21950e5e8.jpg
---

## Leading Edge of Power Management: Max & Min States

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many[ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

![Cmd in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-cmd.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-files.techidaily.com/new-professional-advice-how-to-attach-srt-to-video-media-2024/"><u>[New] Professional Advice How to Attach SRT to Video Media 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-ace-your-look-celebrity-youtubers-for-the-year-2024/"><u>[Updated] Ace Your Look Celebrity YouTubers for the Year 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-expert-psd-overhaul-techniques/"><u>[Updated] Expert PSD Overhaul Techniques</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-ideal-websites-for-accessing-free-licensed-audio-files/"><u>[Updated] Ideal Websites for Accessing Free, Licensed Audio Files</u></a></li>
<li><a href="https://win11.techidaily.com/curbing-excessive-cpu-load-from-windows-core/"><u>Curbing Excessive CPU Load From Windows Core</u></a></li>
<li><a href="https://win11.techidaily.com/designing-safe-quick-access-tool-for-hardware-in-win11/"><u>Designing Safe, Quick Access Tool for Hardware in Win11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-nokia-c300-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Nokia C300 | Dr.fone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-repair-your-pcs-rec-room-microphone-issues-a-comprehensive-guide/"><u>How to Repair Your PC's Rec Room Microphone Issues: A Comprehensive Guide</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-best-anti-tracker-software-for-zte-nubia-flip-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Best Anti Tracker Software For ZTE Nubia Flip 5G | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-motorola-moto-g34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Motorola Moto G34 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-windows-account-pin-change/"><u>Mastering the Art of Windows Account Pin Change</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-workflow-windows-11s-elite-selection-of-widgets/"><u>Transform Your Workflow: Windows 11'S Elite Selection of Widgets</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-guide-resolving-total-war-saga-troy-stability-problems-on-windowspc/"><u>Troubleshooting Guide: Resolving Total War Saga: Troy Stability Problems on Windows/PC</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/understanding-hdr-techniques-in-modern-photoshoots/"><u>Understanding HDR Techniques in Modern Photoshoots</u></a></li>
<li><a href="https://win11.techidaily.com/windows-updates-whats-in-the-name-and-number/"><u>Windows Updates: What's in the Name and Number?</u></a></li>
</ul></div>

