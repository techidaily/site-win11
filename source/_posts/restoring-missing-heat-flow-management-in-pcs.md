---
title: Restoring Missing Heat Flow Management in PCs
date: 2024-08-28T00:52:03.960Z
updated: 2024-08-29T00:52:03.960Z
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

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
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
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-discover-the-leading-free-naming-resources-11-must-have-makers/"><u>[New] In 2024, Discover the Leading Free Naming Resources - 11 Must-Have Makers</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-step-by-step-guide-to-youtube-video-editing-mastery/"><u>[New] In 2024, Step by Step Guide to YouTube Video Editing Mastery</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-many-viewer-thumbs-up-equals-money-youtube-tips/"><u>[Updated] 2024 Approved  How Many Viewer Thumbs Up Equals Money? YouTube Tips</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-5-best-photo-video-maker-with-music/"><u>[Updated] 5 Best Photo Video Maker With Music</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-broadcasting-vids-directly-from-phone-twitter-without-retweets/"><u>[Updated] Broadcasting Vids Directly From Phone – Twitter, Without Retweets</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-easy-steps-to-setting-up-a-professional-discord-stream/"><u>[Updated] In 2024, Easy Steps to Setting Up a Professional Discord Stream</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-samsung-galaxy-s24-drfone-by-drfone-virtual-android/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Samsung Galaxy S24 | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/best-3-nokia-g22-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>Best 3 Nokia G22 Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-disms-potential-in-win11-system-restoration/"><u>Decoding Dism's Potential in Win11 System Restoration</u></a></li>
<li><a href="https://win11.techidaily.com/digital-dots-top-8-window-friendly-note-apps/"><u>Digital Dots: Top 8 Window-Friendly Note Apps</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-web-interaction-enable-mouse-gestures-in-microsofts-edge-browser/"><u>Elevate Your Web Interaction: Enable Mouse Gestures in Microsoft's Edge Browser</u></a></li>
<li><a href="https://video-capture.techidaily.com/elite-picks-a-list-mac-video-capture-tools-for-2024/"><u>Elite Picks  A-List Mac Video Capture Tools for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-long-wait-semaphore-failure-overcome-expired-timers-error-0x80070079/"><u>Fixing the Long-Wait Semaphore Failure, Overcome Expired Timers Error (0X80070079)</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unresponsive-nvidia-experience-on-windows-devices/"><u>Fixing Unresponsive NVIDIA Experience on Windows Devices</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/gratitude-archive-complete-collection-freepaid-for-2024/"><u>Gratitude Archive  Complete Collection (Free/Paid) for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-unaltered-screenscape-in-windows-11/"><u>Guide to Unaltered Screenscape in Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-samsung-galaxy-z-fold-5-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Samsung Galaxy Z Fold 5? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-disable-windows-11s-tracking-features/"><u>How to Disable Windows 11'S Tracking Features</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-discord-installation-has-failed-error-on-windows-11-and-11/"><u>How to Fix the Discord “Installation Has Failed” Error on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-vmware-bsod-error-on-windows-11/"><u>How to Fix VMware BSOD Error on Windows 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-get-the-apple-id-verification-code-from-iphone-xs-max-in-the-best-ways-by-drfone-ios/"><u>How To Get the Apple ID Verification Code From iPhone XS Max in the Best Ways</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-handle-windows-error-code-1053-for-non-responsive-services/"><u>How to Handle Windows' Error Code 1053 for Non-Responsive Services</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-to-apple-iphone-7-plus-drfone-by-drfone-ios/"><u>How to Mirror PC to Apple iPhone 7 Plus? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-revert-windows-11s-search-bar-to-a-search-icon/"><u>How to Revert Windows 11'S Search Bar to a Search Icon</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-newfrontiersincameratech/"><u>In 2024, NewFrontiersInCameraTech</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-honor-play-7t-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For Honor Play 7T Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-car-locator-apps-for-lava-blaze-2-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Car Locator Apps for Lava Blaze 2 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/introducing-ed-inspired-visuals-to-windows/"><u>Introducing Ed-Inspired Visuals to Windows</u></a></li>
<li><a href="https://win11.techidaily.com/master-plan-to-eliminate-microsoft-store-error-0x80072efd/"><u>Master Plan to Eliminate Microsoft Store Error 0X80072EFD</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-books-unlocking-potential-with-7-top-study-methods-on-a-windowed-computer/"><u>Master the Books: Unlocking Potential with 7 Top Study Methods on a Windowed Computer</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-remedies-for-windows-app-issues-7-steps-to-success/"><u>Masterful Remedies for Windows App Issues, 7 Steps to Success</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-microsoft-edge-malfunctions-step-by-step-repair-guide/"><u>Mastering Microsoft Edge Malfunctions: Step-by-Step Repair Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-microsoft-powertoys-in-win11-setup/"><u>Mastering Microsoft PowerToys in Win11 Setup</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-password-retrieval-a-comprehensive-tutorial-for-mac-enthusiasts/"><u>Mastering Password Retrieval: A Comprehensive Tutorial for Mac Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-full-screen-capture-efficiency-with-these-fixes-in-windows/"><u>Maximize Full-Screen Capture Efficiency with These Fixes in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-excessive-heat-on-windows-11-devices/"><u>Mitigating Excessive Heat on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-camera-quirks-with-ease/"><u>Navigating Window's Camera Quirks with Ease</u></a></li>
<li><a href="https://extra-resources.techidaily.com/optimal-viewing-experience-selecting-between-ultrawide-and-uhd-4k/"><u>Optimal Viewing Experience  Selecting Between UltraWide and UHD 4K</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-upload-obstacles-with-onedrive-on-win-11/"><u>Overcoming Upload Obstacles with OneDrive on Win 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-oneplus-ace-2-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On OnePlus Ace 2 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-error-0x80041015-in-ms-word-and-excel/"><u>Quick Fixes for Error 0X80041015 in MS Word & Excel</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-your-desktop-icon-order/"><u>Reclaiming Your Desktop Icon Order</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-fabricated-device-specification-error-in-win-11/"><u>Rectifying Fabricated Device Specification Error in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-access-fixing-frozen-windows-terminals-quickly/"><u>Regaining Access: Fixing Frozen Windows Terminals Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-network-not-available-errors-on-your-windows-11-pc/"><u>Resolving 'Network Not Available' Errors on Your Windows 11 PC</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolving-audio-interruptions-from-bluetooth-devices-on-your-pc-with-windows-1110/"><u>Resolving Audio Interruptions From Bluetooth Devices on Your PC with Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-1011-uninstalls-that-fail/"><u>Resolving Windows 10/11 Uninstalls That Fail</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-functionality-to-your-corrupted-windows-11-trash/"><u>Restoring Functionality to Your Corrupted WIndows 11 Trash</u></a></li>
<li><a href="https://win11.techidaily.com/retrieve-past-cortana-interactions-in-windows-files/"><u>Retrieve Past Cortana Interactions in Windows Files</u></a></li>
<li><a href="https://win11.techidaily.com/step-into-the-twilight-zone-paints-dark-mode-magic/"><u>Step Into the Twilight Zone: Paint's Dark Mode Magic</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-tweak-indexer-in-windows/"><u>Steps to Tweak Indexer in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-workflows-with-windows-11-multitasking-tips/"><u>Streamline Workflows with Windows 11 Multitasking Tips</u></a></li>
<li><a href="https://win11.techidaily.com/surgical-solutions-to-windows-11-login-screen-problems/"><u>Surgical Solutions to Windows 11 Login Screen Problems</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-failed-mobile-hotspot-connectivity-on-windows-11/"><u>Troubleshooting Failed Mobile Hotspot Connectivity on Windows 11</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-tips-to-stop-thaumaturge-from-freezing-your-pc-during-gameplay/"><u>Troubleshooting Tips to Stop Thaumaturge From Freezing Your PC During Gameplay</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-video-editing-essentials-how-to-crop-videos-using-avidemux/"><u>Updated Video Editing Essentials How to Crop Videos Using Avidemux</u></a></li>
</ul></div>
