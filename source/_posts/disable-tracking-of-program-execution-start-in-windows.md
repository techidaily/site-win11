---
title: Disable Tracking of Program Execution Start in Windows
date: 2024-12-06T09:20:40.071Z
updated: 2024-12-06T16:33:29.641Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disable Tracking of Program Execution Start in Windows
excerpt: This Article Describes Disable Tracking of Program Execution Start in Windows
keywords: Disable Windows Tracking,Stop Exec Start Logging,Prevent PC Execution Log,Turn Off Execution Tracker,Halt Exec Start Monitoring,Cease Program Tracking,Inhibit Startup Logging
thumbnail: https://thmb.techidaily.com/1382e80fe89cdc85e3f86df652866f8b806d3041c2bfdfcea85ed48c584b9f54.JPG
---

## Disable Tracking of Program Execution Start in Windows

 Windows records and monitors how often you use particular applications. While this may enhance productivity, it does also raise privacy concerns.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Disable App Launch Tracking Through Windows Settings

 To disable app launch tracking, open the Start menu and type **Settings** in the search bar. Select the **Settings** option in the search results. In the left-side menu, click the **Privacy & security** tab. Then click **General** under the Windows permissions section.

 On the next page, locate **Let Windows improve Start and search results by tracking app launches** and toggle it off.

![Disable App Launch Tracking through Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-windows-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After making the changes, Windows will stop tracking and recording your app launches.

 If you ever need to re-enable the feature, repeat the same steps and toggle the switch back on. This will enable Windows to start tracking and recording your app launches.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Disable App Launch Tracking Using the Group Policy Editor

 You can also disable app launch tracking using the Group Policy Editor. But this method is only available in the Pro and Enterprise versions.

 If you don't have these Windows versions, [turn on the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and follow these instructions.

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **gpedit.msc** in the text box and click **OK**.
3. In the Group Policy Editor window, navigate to the following path:  
`User Configuration > Administrative Templates > Windows Components > Edge UI​`
4. Go to the right side of the window and double-click on **Turn off tracking of app usage**.  
![Disable App Launch Tracking using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-using-group-policy-editor.jpg)
5. On the next page, check the **Enabled** box.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Disable App Launch Tracking Through the Registry Editor

 Registry Editor is another method to disable app launch tracking. The process is tricky as you need to manually modify the registry keys and one wrong move can cause serious problems. So, we suggest you [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To disable app launch tracking through Registry Editor, do the following:

1. Right-click on Start and select **Run** from the menu list.
2. Type **regedit** in the text field and click **OK**. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. When the UAC window appears, click **Yes** to grant privileges.
4. In the left pane, navigate to the following path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. If you don't find the Advanced folder, right-click on **Explorer** and select **New** \> **Key**.
6. Name it **Advanced** and press the Enter key.
7. Now, right-click on the **Advanced** folder and choose **New** \> **DWORD (32-bit) Value**.
8. Name it **Start\_TrackProgs** and hit Enter.  
![Disable App Launch Tracking through the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-the-registry-editor.jpg)
9. Double-click on the **Start\_TrackProgs** DWORD and set its value to **0**.

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

## Windows Won’t Track or Monitor the Apps You Use

 If you don't want to mess with the Registry Editor or Group Policy Editor, use the Settings option to disable app launch tracking. Choose the method you prefer and enjoy a tracking-free experience.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-upcoming-games-with-industry-experts/"><u>[Updated] In 2024, Upcoming Games with Industry Experts</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-video-sectioning-mastery-in-vimeo-videos-for-2024/"><u>[Updated] Video Sectioning Mastery in Vimeo Videos for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-realme-narzo-60-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Realme Narzo 60 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/confirming-the-active-state-in-windows-11/"><u>Confirming the Active State in Windows 11</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-realme-11-5g-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Realme 11 5G Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easy-guide-updating-your-broadcom-bluetooth-driver-for-windows-1087-systems/"><u>Easy Guide: Updating Your Broadcom Bluetooth Driver for Windows 10/8/7 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-flaws-methods-to-incorporate-hidden-windows-11-extras/"><u>Fixing the Flaws: Methods to Incorporate Hidden Windows 11 Extras</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-write-only-file-problems-in-windows-11/"><u>Fixing Write-Only File Problems in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fortify-your-pc-with-these-7-leading-gratis-password-apps/"><u>Fortify Your PC with These 7 Leading, Gratis Password Apps</u></a></li>
<li><a href="https://win11.techidaily.com/guide-turn-off-hyber-v-in-windows-11-pro/"><u>Guide: Turn Off Hyber-V in Windows 11 Pro</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-nokia-c32-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Nokia C32 by Phone Number | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-scale-up-channel-followers-faster-and-cheaper/"><u>In 2024, Scale Up Channel Followers Faster and Cheaper</u></a></li>
<li><a href="https://win11.techidaily.com/samsung-dex-unlocked-enhance-your-galaxy-windows-experience/"><u>Samsung DeX Unlocked: Enhance Your Galaxy-Windows Experience</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-genuine-adobe-on-pc/"><u>Troubleshooting Non-Genuine Adobe on PC</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/twitch-chat-explained-common-confusions-freshmen-should-know/"><u>Twitch Chat Explained: Common Confusions Freshmen Should Know</u></a></li>
</ul></div>

