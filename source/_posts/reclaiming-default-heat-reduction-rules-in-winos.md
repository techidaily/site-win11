---
title: Reclaiming Default Heat Reduction Rules in WinOS
date: 2024-06-25T11:41:05.565Z
updated: 2024-06-26T11:41:05.565Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reclaiming Default Heat Reduction Rules in WinOS
excerpt: This Article Describes Reclaiming Default Heat Reduction Rules in WinOS
keywords: Windows Heat Rule Reclamation,Optimize OS WinTemp,WinOS Coolness Controls,Default Temp Fixes Win,Reduce WinHeat Effectively,Thermal Settings Adjust Win,Manage WinTemperature Norm
thumbnail: https://thmb.techidaily.com/6462de374e4f489455f584c5102443a7cb28c7609933729fa2bbdde0fb2df507.jpg
---

## Reclaiming Default Heat Reduction Rules in WinOS

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on[what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

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
<li><a href="https://win11.techidaily.com/ancestry-unveiled-7-enduring-features-of-windows-11/"><u>Ancestry Unveiled: 7 Enduring Features of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enablingdisabling-microsofts-smartguard-in-win-10/"><u>Enabling/Disabling Microsoft's SmartGuard in Win 10</u></a></li>
<li><a href="https://win11.techidaily.com/delve-into-artificially-inspired-visuals-how-to-use-paint-cocreator-win11/"><u>Delve Into Artificially Inspired Visuals: How to Use Paint Cocreator (Win11)</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-black-screen-during-games-on-win/"><u>Resolving Black Screen During Games on WIN</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-secrets-to-removing-windows-extract-error-1152/"><u>Unlocking Secrets to Removing Windows Extract Error 1152</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-about-to-expire-message-on-microsoft-os/"><u>Bypassing the About To Expire Message on Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/win11-solutions-for-unfunctional-resource-monitor-app/"><u>Win11: Solutions for Unfunctional Resource Monitor App</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-no-money-down-mics-the-frugal-filmmakers-list/"><u>2024 Approved  No-Money-Down Mics  The Frugal Filmmaker's List</u></a></li>
<li><a href="https://extra-information.techidaily.com/isyncslideshow-integrate-ios-plus-sierra-images/"><u>ISyncSlideshow  Integrate iOS + Sierra Images</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-a-stepwise-journey-through-windows-10-recording/"><u>[Updated] A Stepwise Journey Through Windows 10 Recording</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-9-best-phone-monitoring-apps-for-realme-10t-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Best Phone Monitoring Apps for Realme 10T 5G | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-motorola-edge-40-pro-drfone-by-drfone-virtual-android/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Motorola Edge 40 Pro | Dr.fone</u></a></li>
<li><a href="https://ai-voice.techidaily.com/best-celebrity-voice-generator-tools-you-cannot-miss-for-2024/"><u>Best Celebrity Voice Generator Tools You Cannot Miss for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-call-logs-from-sony-xperia-10-v-by-fonelab-android-recover-call-logs/"><u>Possible solutions to restore deleted call logs from Sony Xperia 10 V</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-6s-to-other-iphone-13-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 6s To Other iPhone 13 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-oneplus-ace-2-pro-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your OnePlus Ace 2 Pro Phone</u></a></li>
</ul></div>
