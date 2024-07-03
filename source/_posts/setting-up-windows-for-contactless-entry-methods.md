---
title: Setting Up Windows For Contactless Entry Methods
date: 2024-06-25T11:40:24.176Z
updated: 2024-06-26T11:40:24.176Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Setting Up Windows For Contactless Entry Methods
excerpt: This Article Describes Setting Up Windows For Contactless Entry Methods
keywords: TouchEntryWindowsSetup,ContactlessWindowsTech,WindowsCtAccessMethod,EnableTouchWindows,CtEntryWindowsConfig,WindowsContactlessMode,ConfigWindowsForCtEntry
thumbnail: https://thmb.techidaily.com/74113c2d83645a48c9d2ad195371cc6a07bee43db8bd23e967a3613c122b6663.jpg
---

## Setting Up Windows For Contactless Entry Methods

 The fingertip writing feature in Windows allows users to write on a touch-enabled device using their fingertips, without a stylus or a pen. You can use it to input text directly into documents or applications easily.

 Below, we talk about the different ways to enable or disable the fingertip writing feature in the Handwriting Panel in Windows.

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

1. Name this key as EmbeddedInkControl.
2. Now, move to the right pane and right-click anywhere on an empty space.
3. Choose**New** \>**DWORD (32-bit) Value** .
4. Rename this key as EnableInkingWithTouch.
5. Double-click on**EnableInkingWithTouch** and under Value data, type 1\. This will enable the fingertip writing feature.  
![Enter 1 under Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enableinking-with-touch.jpg)
6. Click**OK** to save the changes.
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
<li><a href="https://win11.techidaily.com/correcting-the-windows-access-denied-error-code-0x80070522/"><u>Correcting the Windows Access Denied Error: Code 0X80070522</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-no-powershell-on-windows-system/"><u>Troubleshooting: No PowerShell on Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/instituting-new-pdf-reader-as-standard/"><u>Instituting New PDF Reader as Standard</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-vpn-network-disconnection-on-a-remote-work-pc/"><u>Fixing VPN Network Disconnection on a Remote Work PC</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-inaccessible-printmanagement-service-in-os/"><u>Dealing with Inaccessible 'PrintManagement' Service in OS</u></a></li>
<li><a href="https://win11.techidaily.com/faster-teams-cleaner-systems-microsofts-pivot/"><u>Faster Teams, Cleaner Systems: Microsoft's Pivot</u></a></li>
<li><a href="https://win11.techidaily.com/maxing-out-melodies-best-5-apps-for-boosting-windows-audio-by-100plus/"><u>Maxing Out Melodies: Best 5 Apps for Boosting Windows' Audio By 100%%+</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/top-picks-for-traditional-japanese-huts-in-mc-worlds-for-2024/"><u>Top Picks for Traditional Japanese Huts in MC Worlds for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-mastering-the-art-of-mass-message-removal-on-discord-servers/"><u>[Updated] Mastering the Art of Mass Message Removal on Discord Servers</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-expert-strategies-for-an-engaging-zoom-youtube-live-session/"><u>[New] Expert Strategies for an Engaging Zoom YouTube Live Session</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-srt-to-sub-masterful-conversion-methods-explored/"><u>In 2024, From SRT to SUB  Masterful Conversion Methods Explored</u></a></li>
<li><a href="https://techidaily.com/guide-on-how-to-free-up-apple-iphone-se-2020-space-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>Guide on How To Free Up Apple iPhone SE (2020) Space | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/exploring-the-best-a-ranked-list-of-10-podcast-transcription-software-options-for-2024/"><u>Exploring the Best A Ranked List of 10 Podcast Transcription Software Options for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unleash-humor-kapwings-meme-crafting-app/"><u>2024 Approved  Unleash Humor  Kapwing's Meme Crafting App</u></a></li>
<li><a href="https://unlock-android.techidaily.com/full-guide-to-unlock-your-honor-play-40c-by-drfone-android/"><u>Full Guide to Unlock Your Honor Play 40C</u></a></li>
</ul></div>
