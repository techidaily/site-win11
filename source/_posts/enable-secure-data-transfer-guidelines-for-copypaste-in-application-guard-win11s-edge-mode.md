---
title: "Enable Secure Data Transfer: Guidelines for Copy/Paste in Application Guard, Win11's Edge Mode"
date: 2024-11-20T21:39:12.165Z
updated: 2024-11-27T17:39:21.106Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enable Secure Data Transfer: Guidelines for Copy/Paste in Application Guard, Win11's Edge Mode"
excerpt: "This Article Describes Enable Secure Data Transfer: Guidelines for Copy/Paste in Application Guard, Win11's Edge Mode"
keywords: Secure Data Transfer,Copy Paste Security,Application Guard,Win11 Edge Mode,Safe Pasting Practices,Edge Mode Guidelines,Protected Data Exchange
thumbnail: https://thmb.techidaily.com/c2d843fc2e375187b2194dd914e4e340539dd6293ab4433f92ecd542eef0fd55.jpg
---

## Enable Secure Data Transfer: Guidelines for Copy/Paste in Application Guard, Win11's Edge Mode

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Enable Copy and Paste via Windows Settings

 To enable copy and paste in Application Guard for Edge, follow the steps below:

1. Right-click on Start and select**Settings** from the menu list. For more information, check out our guide on[how to open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Privacy & security** from the left pane.
3. Then click the**Windows Security** option on the right-hand side.
4. On the following screen, select**App & browser control** .
5. Go to the Isolated browsing section and click the link "Change Applications Guard settings."  
![Change Application Guard Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-application-guard-settings.jpg)
6. Search for the**Copy and paste** option, then click the toggle to enable it.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

## 2\. How to Enable Copy and Paste Using Registry Editor

 The Windows Registry is another method you can use to copy and paste within Application Guard for Edge on your Windows 11 PC. But, please be aware that editing the registry can have severe consequences if done incorrectly. To be safe,[back up the registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you begin making any changes.

 Follow these steps to enable copy and paste using the Windows Registry Editor:

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type "regedit" in the text box and press the Enter key.
3. If UAC prompts appear on the screen, click**Yes** to confirm your action.
4. In the Registry Editor window, navigate to the following location:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi`
5. If you don't find the Hvsi key there, you will need to create it. To do this, right-click on Microsoft and select**New > Key** .

1. In the box that appears, give it the name**Hvsi** , and then hit Enter to save the file.
2. Now right-click on**Hvsi** and select**New > DWORD (32-bit) Value** .  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
3. Put**EnableClipboard** as the name for the new DWORD key, then press Enter.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Copy and Paste Now Works With Edge Application Guard

 With Application Guard for Edge, your device can remain secure while browsing the web. Unfortunately, certain functionalities such as copy and paste are disabled by default - but don't worry! This guide will explain two methods to activate them quickly and easily.

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
<li><a href="https://facebook-clips.techidaily.com/new-youtube-identity-recording-measurements-conversion-time-for-2024/"><u>[New] YouTube Identity Recording Measurements, Conversion, Time for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-elevate-narrative-flow-expert-tips-on-using-jump-cuts/"><u>[Updated] In 2024, Elevate Narrative Flow Expert Tips on Using Jump Cuts</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-side-by-side-hero4-vs-hero5-analysis-for-2024/"><u>[Updated] Side by Side Hero4 vs Hero5 Analysis for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-honor-magic-5-pro-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Honor Magic 5 Pro without App | Dr.fone</u></a></li>
<li><a href="https://fox-ssl.techidaily.com/boost-your-books-online-presence-create-a-social-sharing-ebook-with-flipbuilder/"><u>Boost Your Book's Online Presence: Create a Social Sharing EBook with FlipBuilder</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-to-motorola-moto-g13-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Motorola Moto G13 FRP Bypass With Best Methods</u></a></li>
<li><a href="https://tech-haven.techidaily.com/has-the-stewardship-of-chatgpt-fallen-from-openais-hands/"><u>Has the Stewardship of ChatGPT Fallen From OpenAI's Hands?</u></a></li>
<li><a href="https://win11.techidaily.com/organize-your-data-with-excel-mastering-alphabetical-tab-arrangement-techniques/"><u>Organize Your Data with Excel: Mastering Alphabetical Tab Arrangement Techniques</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/pro-editors-picks-optimal-after-effects-plugin-choices/"><u>Pro Editor's Picks Optimal After Effects Plugin Choices</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/resolve-your-apple-iphone-12-mini-keeps-asking-for-outlook-password-drfone-by-drfone-ios/"><u>Resolve Your Apple iPhone 12 mini Keeps Asking for Outlook Password | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/simple-steps-transferring-data-between-sheets-using-microsoft-excel/"><u>Simple Steps: Transferring Data Between Sheets Using Microsoft Excel</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-data-visualization-with-excel-2010-your-step-by-step-sparkline-tutorial/"><u>Simplify Data Visualization with Excel 2010: Your Step-by-Step Sparkline Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-automatically-populating-date-columns-in-excel/"><u>Step-by-Step Guide: Automatically Populating Date Columns in Excel</u></a></li>
</ul></div>

