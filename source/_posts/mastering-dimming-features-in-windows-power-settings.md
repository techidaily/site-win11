---
title: Mastering Dimming Features in Windows Power Settings
date: 2024-10-31T21:29:23.292Z
updated: 2024-11-01T16:44:10.273Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Dimming Features in Windows Power Settings
excerpt: This Article Describes Mastering Dimming Features in Windows Power Settings
keywords: Power Control Mastery,Windows Power Dimming,Optimize Power Settings,Energy-Saving Techniques,Windows Efficiency Tips,Adjusting Power Sliders,Save Energy with PCs
thumbnail: https://thmb.techidaily.com/e1c4df4174fbb7e774640c12444893c833b651d1c12bd8c02f2b01f747786c25.jpg
---

## Mastering Dimming Features in Windows Power Settings

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006955/19272" target="_top" id="2006955">
  <img src="//a.impactradius-go.com/display-ad/19272-2006955" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006955/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130533/26400" target="_top" id="2130533">
  <img src="//a.impactradius-go.com/display-ad/26400-2130533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130533/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134224/18498" target="_top" id="2134224">
  <img src="//a.impactradius-go.com/display-ad/18498-2134224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134224/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105860/7443" target="_top" id="2105860">
  <img src="//a.impactradius-go.com/display-ad/7443-2105860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105860/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Controlling the “Dim Display After” Option in the Power Options Menu

 Now that you know how to show or hide **Dim display after**, you know what to do when you can’t find it in the Power Options menu or need to remove it. We recommend keeping it hidden and then bringing it up whenever you need it. This will make sure that no one messes with this important display setting when you’ve set it up perfectly.

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
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-best-free-and-paid-drawing-apps-for-windows/"><u>[Updated] 2024 Approved Best Free and Paid Drawing Apps for Windows</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-overcome-the-invisibility-of-short-videos/"><u>[Updated] 2024 Approved Overcome The Invisibility of Short Videos</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-tiktok-effect-overhaul-the-two-pronged-approach/"><u>2024 Approved TikTok Effect Overhaul The Two-Pronged Approach</u></a></li>
<li><a href="https://techtrends.techidaily.com/comprehensive-guide-to-resolving-the-stop-error-code-0xc0000185/"><u>Comprehensive Guide to Resolving the STOP Error (Code 0Xc0000185)</u></a></li>
<li><a href="https://win11.techidaily.com/converting-cr2-images-to-jpg-on-windows-with-ease-and-precision/"><u>Converting CR2 Images to JPG on Windows with Ease and Precision</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-screen-with-ordered-icons/"><u>Enhance Your Screen with Ordered Icons</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-access-your-apple-iphone-13-pro-when-you-forget-the-passcode-drfone-by-drfone-ios/"><u>How to Access Your Apple iPhone 13 Pro When You Forget the Passcode? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/key-uses-for-visual-cplusplus-redistribution/"><u>Key Uses for Visual C++ Redistribution</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-input-methods-and-keyboard-setups-for-win-11-users/"><u>Optimize Input Methods and Keyboard Setups for Win 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/sprint-to-efficiency-quick-fixes-for-win-outlook/"><u>Sprint to Efficiency: Quick Fixes for WIN Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-resolve-screen-driver-failure-on-windows-11/"><u>Strategies to Resolve Screen Driver Failure on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-update-windows-11-admin-identity-and-role/"><u>Strategies to Update Windows 11 Admin Identity and Role</u></a></li>
<li><a href="https://buynow-help.techidaily.com/the-extollo-lansocket-1500-review-a-deep-dive-into-high-performance-ethernet-solutions-with-quick-response-times/"><u>The Extollo LANSocket 1500 Review: A Deep Dive Into High-Performance Ethernet Solutions with Quick Response Times</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-15-apps-to-hack-wifi-password-on-infinix-smart-8-pro-by-drfone-android/"><u>Top 15 Apps To Hack WiFi Password On Infinix Smart 8 Pro</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-persistence-in-augmented-reality-the-gateway-to-a-thriving-metaverse/"><u>Unveiling Persistence in Augmented Reality: The Gateway to a Thriving Metaverse</u></a></li>
</ul></div>

