---
title: Restoring Missing Heat Flow Management in PCs
date: 2024-12-27T00:13:40.485Z
updated: 2024-12-27T17:24:08.722Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Missing Heat Flow Management in PCs
excerpt: This Article Describes Restoring Missing Heat Flow Management in PCs
keywords: PC Overheat Fix,Heat Control Update,Thermal Regulation PC,Heatflow Mgmt PC Repair,Restore PC Temp Flow,Missing Heatware PC,Heat Management PC Fix
thumbnail: https://thmb.techidaily.com/6d060e78cf4821c16957dc0af5764350800050d4c706e3284222e7ce2389a41f.jpg
---

## Restoring Missing Heat Flow Management in PCs

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on[what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=lhdUUVYMVQjzHXBh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://desktop-recording.techidaily.com/updated-easy-steps-record-audio-on-mac-using-audacity/"><u>[Updated] Easy Steps Record Audio on Mac Using Audacity</u></a></li>
<li><a href="https://win-howtos.techidaily.com/avoiding-memory-integrity-risks-in-ftdibus-systems-with-compatible-device-drivers/"><u>Avoiding Memory Integrity Risks in Ftdibus Systems with Compatible Device Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-no-installed-devices-in-windows-os/"><u>Correcting 'No Installed Devices' In Windows OS</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/crafting-your-virtual-identity-initiating-an-oculus-questquest-2-login-journey/"><u>Crafting Your Virtual Identity: Initiating an Oculus Quest/Quest 2 Login Journey</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-efficiency-reducing-memorycpu-load-in-windows-10/"><u>Enhance Efficiency: Reducing Memory/CPU Load in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-diagnosing-and-fixing-the-continuous-not-recognized-error-on-your-usb-drives/"><u>Expert Tips for Diagnosing & Fixing the Continuous 'Not Recognized' Error on Your USB Drives</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-samsung-galaxy-f04mirror-share-to-pc-drfone-by-drfone-android/"><u>How Can Samsung Galaxy F04Mirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-xiaomi-redmi-note-12-5g-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Xiaomi Redmi Note 12 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-file-selection-activating-windows-11-checkboxes/"><u>Maximize File Selection: Activating Windows 11 Checkboxes</u></a></li>
<li><a href="https://win11.techidaily.com/no-cords-just-games-setting-up-ps3-controller/"><u>No Cords, Just Games: Setting Up PS3 Controller</u></a></li>
<li><a href="https://win11.techidaily.com/permanent-progress-mastering-the-save-file-security-in-epic-launcher/"><u>Permanent Progress: Mastering the Save File Security in Epic Launcher</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/secrets-of-high-quality-steam-gameplay-footage/"><u>Secrets of High-Quality Steam Gameplay Footage</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-multilingual-navigation-on-windows-1011-with-keys/"><u>Speedy Multilingual Navigation on Windows 10/11 with Keys</u></a></li>
<li><a href="https://android-transfer.techidaily.com/top-5-from-poco-x6-pro-to-iphone-contacts-transfer-apps-and-software-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Top 5 from Poco X6 Pro to iPhone Contacts Transfer Apps and Software | Dr.fone</u></a></li>
</ul></div>

