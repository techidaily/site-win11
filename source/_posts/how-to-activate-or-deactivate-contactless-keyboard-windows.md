---
title: How to Activate or Deactivate Contactless Keyboard Windows
date: 2024-12-04T06:05:27.994Z
updated: 2024-12-07T06:18:08.329Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Activate or Deactivate Contactless Keyboard Windows
excerpt: This Article Describes How to Activate or Deactivate Contactless Keyboard Windows
keywords: WinKeyboard Activation Guide,Deactivate Keyboard,Enable/Disable Wireless Keyboard,Contactless Keyboard Settings,Windows Keypad Control,Optimize Contactless PC Use,Laptop NFC Key Adjustment
thumbnail: https://thmb.techidaily.com/891c1ef62d1f0cae8f261e14a3ae4e9d18efe066afd0af7e2373c813aa6b6f85.jpg
---

## How to Activate or Deactivate Contactless Keyboard Windows

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/T-ssCD10v2M?si=WVWGNayUiCAkMZzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can now close the Settings app if you want. To disable the feature in the future, simply follow these steps again and uncheck the Write with your fingertip option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zgwn5kVI5V4?si=1j6j4OuSSndFieXU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xtylXDY9YfA?si=VonzSiDFGCpJm2uC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-the-pros-playlist-shuffle-manual/"><u>[New] 2024 Approved The Pro's Playlist Shuffle Manual</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-easy-conversion-of-youtube-videos-from-twitter-into-gifs/"><u>[New] Easy Conversion of YouTube Videos From Twitter Into GIFs</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/wipe-right-on-creativity-youtubes-top-techniques-for-greenscreens/"><u>[New] Swipe Right on Creativity YouTube’s Top Techniques for Greenscreens</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-sync-your-device-pace-youtube-audio-control-guide/"><u>[Updated] Sync Your Device Pace YouTube Audio Control Guide</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-tailor-made-viewing-pace-on-youtube-at-your-fingertips/"><u>[Updated] Tailor-Made Viewing Pace on YouTube at Your Fingertips</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/digital-retouch-fundamentals-eliminate-backdrops-with-ease/"><u>Digital Retouch Fundamentals Eliminate Backdrops with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-microsoft-store-error-on-win11-with-code-0x80073cf3/"><u>Fixing the Microsoft Store Error on Win11 with Code 0X80073cf3</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-11s-0x8007045d-blue-screen-issue/"><u>Fixing Windows 11'S 0X8007045D Blue Screen Issue</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-11s-screen-configurations-a-guide-to-10-methods/"><u>Mastering Window 11'S Screen Configurations: A Guide to 10 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-application-unable-to-initialize-due-to-missing-qt-plugin/"><u>Overcoming 'Application Unable to Initialize Due to Missing Qt Plugin'</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016487888-the-ultimate-guide-to-repairing-your-microphone-on-fortnite-no-more-silent-battles/"><u>The Ultimate Guide to Repairing Your Microphone on Fortnite - No More Silent Battles</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-free-ae-template-packs-for-amateurs-for-2024/"><u>Top FREE AE Template Packs for Amateurs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-potential-analyzing-windows-reliable-tools/"><u>Unleashing Potential: Analyzing Windows' Reliable Tools</u></a></li>
</ul></div>

