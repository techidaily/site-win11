---
title: Enable Handwritten Entry on Windows Using Simple Steps
date: 2025-01-02T19:37:15.153Z
updated: 2025-01-06T16:06:39.250Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enable Handwritten Entry on Windows Using Simple Steps
excerpt: This Article Describes Enable Handwritten Entry on Windows Using Simple Steps
keywords: Handwritten Input Windows,Enable Writing Windows,Handwriting Windows,Windows Write Entry,Simple Windows Entry,Easy Windows Handwrite,Windows Input Method
thumbnail: https://thmb.techidaily.com/d68b2c77d9bc6992a97b4d45a79ba7275bc346cfc58c9a3e57e1e4c2f555ef0b.jpg
---

## Enable Handwritten Entry on Windows Using Simple Steps

 The fingertip writing feature in Windows allows users to write on a touch-enabled device using their fingertips, without a stylus or a pen. You can use it to input text directly into documents or applications easily.

 Below, we talk about the different ways to enable or disable the fingertip writing feature in the Handwriting Panel in Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-G7cU8dYvuI?si=JaKqRcW6qq9CDvty" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Name this key as EmbeddedInkControl.
2. Now, move to the right pane and right-click anywhere on an empty space.
3. Choose**New** \>**DWORD (32-bit) Value** .
4. Rename this key as EnableInkingWithTouch.
5. Double-click on**EnableInkingWithTouch** and under Value data, type 1\. This will enable the fingertip writing feature.  
![Enter 1 under Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enableinking-with-touch.jpg)
6. Click**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable the handwriting panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-handwriting-panel-1.jpg)
7. Click**Apply** \>**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-unleash-potential-in-digital-art-top-10-android-drawing-app-reviews/"><u>[New] In 2024, Unleash Potential in Digital Art Top 10 Android Drawing App Reviews</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-understanding-pewdiepies-annual-net-worth/"><u>[New] Understanding PewDiePie's Annual Net Worth</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-the-quest-for-ultimate-clarity-with-the-z32x-monitor/"><u>[Updated] The Quest for Ultimate Clarity with the Z32X Monitor</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/10-minute-blitz-for-fluency-in-urdu-language/"><u>10-Minute Blitz for Fluency in Urdu Language</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-ace-soundtracks-collection-for-cinematography/"><u>2024 Approved Ace Soundtracks Collection for Cinematography</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-mastering-the-art-of-social-media-videos-for-maximum-reach/"><u>2024 Approved Mastering the Art of Social Media Videos for Maximum Reach</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-secrets-revealed-effective-facebook-video-publishing-techniques/"><u>2024 Approved Secrets Revealed Effective Facebook Video Publishing Techniques</u></a></li>
<li><a href="https://blog-min.techidaily.com/android-to-apple-how-to-transfer-photos-from-samsung-galaxy-f15-5g-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Android to Apple How To Transfer Photos From Samsung Galaxy F15 5G to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-access-to-outlook-preview-in-the-latest-windows-os/"><u>Effortless Access to Outlook Preview in the Latest Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-user-experience-mouse-pointer-adjustments/"><u>Enhancing User Experience: Mouse Pointer Adjustments</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-your-machine-how-to-tweak-windows-11-preferences/"><u>Mastering Your Machine: How to Tweak Windows 11 Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/must-remember-actions-before-installation-of-new-windows/"><u>Must-Remember Actions Before Installation of New Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-steam-error-lack-of-file-access-on-win11/"><u>Resolving Steam Error: Lack of File Access on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-buffering-resolving-video-delay-in-vlc-win/"><u>Tackling Buffering: Resolving Video Delay in VLC Win</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-realme-note-50-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-efficient-power-management-techniques-for-windows/"><u>Unveiling Efficient Power Management Techniques for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-os-command-center-for-app-and-web-control/"><u>Windows OS: Command Center for App & Web Control</u></a></li>
</ul></div>

