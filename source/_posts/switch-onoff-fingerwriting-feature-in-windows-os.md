---
title: Switch On/Off Fingerwriting Feature in Windows OS
date: 2024-12-05T06:56:57.840Z
updated: 2024-12-07T05:39:44.483Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Switch On/Off Fingerwriting Feature in Windows OS
excerpt: This Article Describes Switch On/Off Fingerwriting Feature in Windows OS
keywords: Off/On Finger Writing,Windows Finger Write Switch,Turn Fingerwriting ON-OFF,Windows OS Finger Drawing Controls,Activate Fingerwriting in WinOS,Enable/Disable Fingerwrite Feature,Finger Writing Windows Switch
thumbnail: https://thmb.techidaily.com/cf530c2c593b6932cef8db0cdf4cd19063a18ed96567f34da25c1f69a7f2e22f.jpg
---

## Switch On/Off Fingerwriting Feature in Windows OS

 The fingertip writing feature in Windows allows users to write on a touch-enabled device using their fingertips, without a stylus or a pen. You can use it to input text directly into documents or applications easily.

 Below, we talk about the different ways to enable or disable the fingertip writing feature in the Handwriting Panel in Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Use the Settings App to Enable/Disable Fingertip Writing

 The easiest, most straightforward way to enable or disable the fingertip writing feature is by using the Settings app. You can make these changes in the Bluetooth & devices section and do not need to have administrative access to the system as well.

Here is how you can proceed:

1. Press the**Win** +**I** keys to open the Settings app.
2. Choose**Bluetooth & devices** from the left pane.
3. Move to the right side of the window and click on**Pen & Windows Ink** .  
![Access the Pen & Windows Ink section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/pen-and-windows-ink.jpg)
4. Expand the**Use your handwriting to enter text** section under Handwriting.
5. Checkmark the box associated with**Write with your fingertip** .  
![Write with your fingertip option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/write-with-you-fingertip-1.jpg)

 You can now close the Settings app if you want. To disable the feature in the future, simply follow these steps again and uncheck the Write with your fingertip option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Enable/Disable Fingertip Writing via the Registry Editor

 If the "Write with your fingertip" option is disabled in the Settings app, you can also make these changes using the Registry Editor.

 Windows Registry is a powerful tool that is typically used to manage important system settings and configurations. This is an administrative-level utility, so you will need to log into your administrator account if you are using a standard user account to use it. You can also[convert your standard user account into an administrator account](https://www.makeuseof.com/windows-standard-adminstrator-account-differences/) .

 Once you have logged into Windows as an administrator,[create a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) , just to be safe.

Then, proceed with these steps:

1. Press the**Win** +**R** keys together to open Run.
2. Type "regedit" in the text field of Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you have launced the Registry Editor, navigate to the location below:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\TabletTip`
5. Right-click on**TableTip** and choose**New** \>**Key** .  
![Create a new key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/create-new-key.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KdpTAZ9zonQ?si=5Nd5SPW1axA7GPuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Name this key as EmbeddedInkControl.
2. Now, move to the right pane and right-click anywhere on an empty space.
3. Choose**New** \>**DWORD (32-bit) Value** .
4. Rename this key as EnableInkingWithTouch.
5. Double-click on**EnableInkingWithTouch** and under Value data, type 1\. This will enable the fingertip writing feature.  
![Enter 1 under Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enableinking-with-touch.jpg)
6. Click**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/j5gTm5KxtQ0?si=onF1rBS2nEM5nLGg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. Close the Registry Editor and restart your computer.

 Upon reboot, you should be able to use the fingertip writing feature. To disable this feature, follow the aforementioned steps again and change the value data of the EnableInkingWithTouch key to 0.

## 3\. Enable/Disable Fingertip Writing Via the Group Policy Editor

 The third way of enabling/disabling the fingertip writing feature is via the Group Policy Editor. Like the Windows Registry, this utility also allows the administrators to manage the advanced-level system settings in Windows.

 To use the Group Policy Editor for managing the fingertip writing feature, follow these steps:

1. Press the**Win** +**R** keys simultaneously to open Run.
2. Type "gpedit.msc" in Run and click**Enter** .
3. Click**Yes** in the User Account Control prompt.
4. Once you are in the Group Policy Editor, navigate to the location below:  
`Computer Configuration > Administrative Templates > Windows Components > Handwriting`
5. Locate the**Handwriting Panel Default Mode Docked** policy in the right pane and double-click on it.  
![Access the Handwriting panel default mode docked policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/handwriting-policy.jpg)
6. To enable the feature, choose**Not configured** . If you want to disable it, choose**Disable** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable the handwriting panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-handwriting-panel-1.jpg)
7. Click**Apply** \>**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can now close the Group Policy Editor and begin using the fingertip writing feature with ease.

## Use Your Fingertips to Write Away on Windows

 The fingertip writing feature can be a great tool for those who do not prefer using a stylus or a writing pen. You can use it to take handwritten notes and have them automatically converted into digital text which you then further organize and share.

 The three methods we have listed above should help you manage this feature easily. However, it is important to exercise caution and create a backup before you make any changes to the system settings and configurations.

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
<li><a href="https://extra-information.techidaily.com/new-beijings-ice-arena-olympic-moments-2022/"><u>[New] Beijing's Ice Arena Olympic Moments, 2022</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-leveraging-the-power-of-visual-storytelling-in-fb-covers/"><u>[Updated] In 2024, Leveraging the Power of Visual Storytelling in FB Covers</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mastering-windows-11-a-step-by-step-upgrade-guide/"><u>[Updated] Mastering Windows 11 A Step-by-Step Upgrade Guide</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-honor-100-pro-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for Honor 100 Pro | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-optimizing-facebook-ads-with-a-structured-triple-layered-copywriting-approach/"><u>2024 Approved Optimizing Facebook Ads with a Structured, Triple-Layered Copywriting Approach</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-and-repairing-spotify-crashes-in-win11/"><u>Diagnosing and Repairing Spotify Crashes in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/expansive-yet-unimpressive-performance-in-mp60/"><u>Expansive Yet Unimpressive Performance in MP60</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-media-player-app-when-it-stops-working-on-windows-11/"><u>How to Fix the Media Player App When It Stops Working on Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-apps-from-oppo-a1x-5g-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Apps from Oppo A1x 5G to Another | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/invigorating-previous-generations-directx-software-via-dxvk/"><u>Invigorating Previous Generations' DirectX Software via DXVK</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ipad-showdown-discovering-the-unique-features-of-mini-and-air-variants/"><u>IPad Showdown: Discovering the Unique Features of Mini and Air Variants</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1721952284796-new-chatgpt-ios-app-revealed/"><u>New ChatGPT iOS App Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/proactive-measures-for-a-smooth-sailing-win11-microsoft-teams-journey/"><u>Proactive Measures for a Smooth-Sailing Win11 Microsoft Teams Journey</u></a></li>
<li><a href="https://discover-dash.techidaily.com/quicktime-imoviemp4/"><u>QuickTime iMovieでMP4にコンバートする方法とトラブルシューティング手帳</u></a></li>
<li><a href="https://win11.techidaily.com/rejuvenate-archived-media-enhancing-videos-through-madvr-and-windows/"><u>Rejuvenate Archived Media: Enhancing Videos Through MadVR and Windows</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-windows-memory-errors/"><u>Strategies for Overcoming Windows Memory Errors</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unveiling-the-new-imac-m1-cutting-edge-design-meets-impressive-processing-power/"><u>Unveiling the New iMac M1: Cutting-Edge Design Meets Impressive Processing Power</u></a></li>
<li><a href="https://win11.techidaily.com/virtualbox-upgrade-strategies-to-version-70-on-windows-11-systems/"><u>VirtualBox Upgrade Strategies to Version 7.0 on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/windows-memory-management-ram-cache-clearance-tips/"><u>Windows Memory Management: RAM Cache Clearance Tips</u></a></li>
</ul></div>

