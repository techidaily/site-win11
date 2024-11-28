---
title: Reactivating Disabled CPU Cooling Mechanism in OS
date: 2024-11-24T19:18:09.543Z
updated: 2024-11-27T18:20:50.832Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reactivating Disabled CPU Cooling Mechanism in OS
excerpt: This Article Describes Reactivating Disabled CPU Cooling Mechanism in OS
keywords: Reactive CPU Cooling Fix,CPU Overheat Solution,Reactivate Cooler Control,Restart Cooling System,Disabled Heatsink Reset,CPU Temp Regulation,Revive Cooling Function
thumbnail: https://thmb.techidaily.com/333b95c20ee75bfb354881848c952d7c6576f1601ed8967bdbaf6f2fda50fa89.jpg
---

## Reactivating Disabled CPU Cooling Mechanism in OS

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on[what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c1yHj02oP3w?si=mwi3FyP0p68gkBqV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-webster.techidaily.com/ecoding-youtubes-best-video-editing-practices/"><u>[New] Decoding YouTube's Best Video Editing Practices</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-in-2024-dreaming-shutterbugs-guide-top-6-4k-dslr-cameras/"><u>[New] In 2024, Dreaming Shutterbugs Guide Top 6 4K DSLR Cameras</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-perfecting-your-tiktok-content-utilizing-templates-to-enhance-videos/"><u>[New] In 2024, Perfecting Your TikTok Content Utilizing Templates to Enhance Videos</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-mastering-podcast-cover-art-top-decoding-strategies/"><u>[New] Mastering Podcast Cover Art Top Decoding Strategies</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-snapshot-styles-a-guide-to-using-old-school-vhs-in-modern-editing/"><u>[Updated] Snapshot Styles A Guide to Using Old-School VHS in Modern Editing</u></a></li>
<li><a href="https://win11.techidaily.com/gain-immediate-control-overcoming-pin-locking/"><u>Gain Immediate Control: Overcoming PIN Locking</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-streamlining-browsing-with-lowered-process-count/"><u>Guide to Streamlining Browsing with Lowered Process Count</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-install-and-load-new-drivers-on-windows-11/"><u>How to Install and Load New Drivers on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-functionality-of-your-asus-laptops-broken-fn-keys/"><u>How to Restore Functionality of Your Asus Laptop's Broken Fn Keys</u></a></li>
<li><a href="https://fox-glue.techidaily.com/perfect-your-skills-applying-radial-blur-in-photoshop-easily/"><u>Perfect Your Skills Applying Radial Blur in Photoshop Easily</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-unspecified-obs-error-in-live-streaming-windows-11/"><u>Preventing Unspecified OBS Error in Live Streaming Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/repair-keyboard-woes-solving-f-keys-issues-in-win-11/"><u>Repair: Keyboard Woes - Solving F-Keys Issues in Win 11</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resolving-continuous-blender-software-freezing-problems-in-5-easy-steps/"><u>Resolving Continuous Blender Software Freezing Problems in 5 Easy Steps</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-crafting-your-own-speech-to-text-app-with-windows/"><u>Step-by-Step Guide to Crafting Your Own Speech-to-Text App with Windows</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-correcting-isdonedll-isarcextract-issues/"><u>Strategies for Correcting ISDone.dll (ISArcExtract) Issues</u></a></li>
</ul></div>

