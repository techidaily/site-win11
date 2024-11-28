---
title: How to Activate or Deactivate Contactless Keyboard Windows
date: 2024-11-25T00:03:02.327Z
updated: 2024-11-27T17:29:42.599Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Checkmark the box associated with**Write with your fingertip** .  
![Write with your fingertip option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/write-with-you-fingertip-1.jpg)

 You can now close the Settings app if you want. To disable the feature in the future, simply follow these steps again and uncheck the Write with your fingertip option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can now close the Group Policy Editor and begin using the fingertip writing feature with ease.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-pioneering-6-networks-supporting-business-development/"><u>[New] In 2024, Pioneering 6 Networks Supporting Business Development</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-complete-blueprint-for-tracking-yt-viewsrevenue-for-2024/"><u>[Updated] Complete Blueprint for Tracking YT Views/Revenue for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-from-feedback-to-fanbase-the-video-journey/"><u>[Updated] From Feedback to Fanbase The Video Journey</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-total-data-consumption-days-long-movie/"><u>[Updated] Total Data Consumption Day's Long Movie</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/comprehensive-snapshot-tool-az-reviews-and-substitutes/"><u>Comprehensive Snapshot Tool - AZ Reviews & Substitutes</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/discover-apples-holiday-deal-save-40-on-top-rated-airpods-before-independence-day-insights/"><u>Discover Apple's Holiday Deal: Save $40 on Top-Rated AirPods Before Independence Day - Insights</u></a></li>
<li><a href="https://extra-information.techidaily.com/essentials-of-drafting-engaging-vlogger-speeches/"><u>Essentials of Drafting Engaging Vlogger Speeches</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-privacy-centric-explore-instagram-stories-anon-on-your-devices/"><u>In 2024, Privacy-Centric Explore Instagram Stories Anon on Your Devices</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/leveraging-lut-technology-in-adobe-premiere-for-2024/"><u>Leveraging LUT Technology in Adobe Premiere for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-techniques-for-securely-managing-digital-copies-of-dvds-and-cds-rip-burn-and-duplicate/"><u>Ultimate Techniques for Securely Managing Digital Copies of DVDs and CDs - Rip, Burn, and Duplicate</u></a></li>
<li><a href="https://win11.techidaily.com/uncovering-leaked-clip-insights-and-teasers-for-the-affordable-next-generation-iphone/"><u>Uncovering Leaked Clip Insights & Teasers for the Affordable Next Generation iPhone</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-pls-files-a-comprehensive-guide-on-opening-and-conversion/"><u>Understanding PLS Files: A Comprehensive Guide on Opening & Conversion</u></a></li>
<li><a href="https://win11.techidaily.com/video/"><u>Videoダウンロードハンドラーの効果的な利用法を学ぶ</u></a></li>
<li><a href="https://win11.techidaily.com/watch-youre-next-a-top-recommendation-for-fans-seeking-a-thrilling-horror-experience/"><u>Watch 'You're Next': A Top Recommendation for Fans Seeking a Thrilling Horror Experience</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11stereo-mix/"><u>Windows 11でStereo Mixによる単音声録音手法</u></a></li>
<li><a href="https://win11.techidaily.com/wonderfox-navigation-error-why-you-cant-find-the-content-anymore-new-link-text/"><u>WonderFox Navigation Error: Why You Can’t Find the Content Anymore – New Link Text</u></a></li>
</ul></div>

