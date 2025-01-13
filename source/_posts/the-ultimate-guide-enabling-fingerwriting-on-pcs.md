---
title: "The Ultimate Guide: Enabling Fingerwriting on PCs"
date: 2025-01-07T21:07:16.297Z
updated: 2025-01-12T17:38:45.673Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes The Ultimate Guide: Enabling Fingerwriting on PCs"
excerpt: "This Article Describes The Ultimate Guide: Enabling Fingerwriting on PCs"
keywords: PC Fingerwriting Basics,Enable Fingerwriting Tips,Fingerwriting Tech Guide,Easy PC Writing Method,Digital Fingerwriting for PCs,Fingerwriting Software Options,Secure PC Fingerwriting
thumbnail: https://thmb.techidaily.com/d9925e82a959f50569bbd42483d903b11385c17bd02f16f205258c110d37af55.jpg
---

## The Ultimate Guide: Enabling Fingerwriting on PCs

 The fingertip writing feature in Windows allows users to write on a touch-enabled device using their fingertips, without a stylus or a pen. You can use it to input text directly into documents or applications easily.

 Below, we talk about the different ways to enable or disable the fingertip writing feature in the Handwriting Panel in Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Use the Settings App to Enable/Disable Fingertip Writing

 The easiest, most straightforward way to enable or disable the fingertip writing feature is by using the Settings app. You can make these changes in the Bluetooth & devices section and do not need to have administrative access to the system as well.

Here is how you can proceed:

1. Press the**Win** +**I** keys to open the Settings app.
2. Choose**Bluetooth & devices** from the left pane.
3. Move to the right side of the window and click on**Pen & Windows Ink** .  
![Access the Pen & Windows Ink section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/pen-and-windows-ink.jpg)
4. Expand the**Use your handwriting to enter text** section under Handwriting.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Checkmark the box associated with**Write with your fingertip** .  
![Write with your fingertip option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/write-with-you-fingertip-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can now close the Settings app if you want. To disable the feature in the future, simply follow these steps again and uncheck the Write with your fingertip option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

1. Name this key as EmbeddedInkControl.
2. Now, move to the right pane and right-click anywhere on an empty space.
3. Choose**New** \>**DWORD (32-bit) Value** .
4. Rename this key as EnableInkingWithTouch.
5. Double-click on**EnableInkingWithTouch** and under Value data, type 1\. This will enable the fingertip writing feature.  
![Enter 1 under Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enableinking-with-touch.jpg)
6. Click**OK** to save the changes.
7. Close the Registry Editor and restart your computer.

 Upon reboot, you should be able to use the fingertip writing feature. To disable this feature, follow the aforementioned steps again and change the value data of the EnableInkingWithTouch key to 0.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Sj2QNA-JXI?si=V-_h73iE3VlE214k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
![Enable the handwriting panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-handwriting-panel-1.jpg)
7. Click**Apply** \>**OK** to save the changes.

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
<li><a href="https://video-screen-grab.techidaily.com/new-elite-apps-leading-video-grabber-programs-for-mac-for-2024/"><u>[New] Elite Apps Leading Video Grabber Programs for Mac for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-explore-artistic-possibilities-premier-android-graphics-app-selection/"><u>[New] Explore Artistic Possibilities Premier Android Graphics App Selection</u></a></li>
<li><a href="https://location-social.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-oneplus-nord-n30-se-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your OnePlus Nord N30 SE | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-realme-gt-5-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Realme GT 5 to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-flashing-on-windows-systematic-approach/"><u>Combatting Flashing on Windows: Systematic Approach</u></a></li>
<li><a href="https://buynow-info.techidaily.com/exploring-the-dual-capabilities-of-fitbit-versa-2-your-guide-to-health-monitoring-and-smartwatch-integration/"><u>Exploring the Dual Capabilities of Fitbit Versa 2 – Your Guide to Health Monitoring and Smartwatch Integration</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-flux-seven-tactics-for-obss-server-disconnect-issue/"><u>Fixing the Flux: Seven Tactics for OBS's Server Disconnect Issue</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-of-the-best-pokemon-discord-servers-to-join-on-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>Here are Some of the Best Pokemon Discord Servers to Join On Lava Blaze 2 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unlock-windows-11s-credential-and-permissions-center/"><u>How to Unlock Windows 11’S Credential and Permissions Center</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-itel-a60-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Itel A60 Location Settings | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reviewers-take-on-surface-studio-2-almost-flawless-for-artists/"><u>Reviewer's Take on Surface Studio 2: Almost Flawless for Artists</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723964488813-stream-like-a-pro-at-record-lows-with-logiteches-g-yeti-gx-microphone-offer-dont-miss-this-exclusive-deal/"><u>Stream Like a Pro at Record Lows with Logiteche's G Yeti GX Microphone Offer – Don’t Miss This Exclusive Deal!</u></a></li>
<li><a href="https://win11.techidaily.com/taming-the-quick-pointers-disabling-mouse-accel-in-windows-11/"><u>Taming the Quick Pointers: Disabling Mouse Accel in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-active-windows-alt-keys-52-characters/"><u>Troubleshooting Non-Active Windows Alt Keys (52 Characters)</u></a></li>
<li><a href="https://win11.techidaily.com/work-smart-not-harder-top-time-management-windows-apps/"><u>Work Smart, Not Harder: Top Time Management Windows Apps</u></a></li>
</ul></div>

