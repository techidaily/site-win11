---
title: "Disguising or Displaying Time: Win 10/11 Tutorial"
date: 2024-06-25T11:29:05.242Z
updated: 2024-06-26T11:29:05.242Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Disguising or Displaying Time: Win 10/11 Tutorial"
excerpt: "This Article Describes Disguising or Displaying Time: Win 10/11 Tutorial"
keywords: Win10TimeTutorial,Win11TimeDisplay,PCTroubleshootingGuide,OperatingSystemUpdate,TimeTrackingWindows,SystemPerformanceBoost,OSUpgradeHelpCenter
thumbnail: https://thmb.techidaily.com/48eff568c35933b40401a65faa40dbe7bb6a58eb499e343dac1cbda32fedf601.jpg
---

## Disguising or Displaying Time: Win 10/11 Tutorial

 The system tray clock on the right side of the Windows taskbar shows the date and time. While most users find this information useful, others might consider it a source of distraction.

 As such, if you want to hide the clock and date from the taskbar, then this is the place where you need to be. We'll share three different ways by which you can configure the taskbar to hide or show the clock and date.

## 1\. Hide or Show the Clock and Date from the Taskbar by Using Windows System Settings

 The System Settings is the central hub of a Windows PC. You can use it to update Windows, manage privacy settings,[customize the taskbar](https://www.makeuseof.com/windows-11-customize-taskbar/) , and more.

 It's also one of the places from where you can configure the taskbar to hide or show the clock and date. You can do this by following the below instructions:

 This method only works for Windows 10\. If you are using Windows 11, you can try any other method in this article.

1. Open the**Settings** menu by pressing the**Win + I** hotkeys.
2. Choose the**Personalization** option.
3. Select**Taskbar** from the left panel.
4. Scroll down and click the**Turn system icon on or off** option under the**Notification** area.  
![Turn system icons on or off option in Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-system-icons-on-or-off.png)
5. In the new window that crops up, disable the toggle next to**Clock.**  
![Disable the Clock in System Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-the-clock.png)

 That's it. You've disabled the clock and date from the taskbar.

 To enable them again, head towards the above settings again and enable the toggle.

## 2\. Hide or Show the Clock and Date from the Taskbar by Using the Local Group Policy Editor

 The next utility that will help you hide or show the clock and date from the taskbar is the Local Group Policy Editor. You can use this utility to manage Windows features, sign-in and shutdown processes, and more.

 The Local Group Policy Editor is disabled by default in the Windows Home edition. To enable it, check out our guide on how to[access the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 Nevertheless, here's how to use Local Group Policy Editor to configure the taskbar to hide the clock and date.

1. Open the Run dialog box, type**gpedit.msc,** and press Enter.
2. In the Local Group Policy Editor, select the**Administrative Templates** folder under**User configuration.**
3. Click the**Start Menu and Taskbar** folder.
4. Click the**Setting** option in the right pane.
5. Search for and right-click on the**Remove Clock from the system notification area** policy. Then, choose**Edit** from the context menu.
6. In the policy edit window, choose the**Enabled** option.  
![Disabling Clock and Date using the local group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disabling-clock-and-date.jpg)
7. Click**Apply** \>**OK** to save the changes.

 Next,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) for changes to take effect.

 If you want to add the clock and date again to the taskbar, open the edit window of the Remove Clock from the system notification area policy, choose the Disabled option and save the settings.

## 3\. Hide or Show the Clock and Date from the Taskbar Using the Registry Editor

 The[Registry Editor](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is an extensive database of your Windows operating system configuration settings. You can use it to navigate the registry and edit its keys.

 Here's how to use the Registry Editor to hide the clock and date from the taskbar:

1. In the Run dialog box, type**regedit** and click**OK.** It'll[open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Navigate to the following location:  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies`
3. Right-click on the**Policies** key in the left panel, choose**New,** and then select**Key.**
4. Name the key**Explorer** and press Enter.  
![Creating new key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/creating-new-key.jpg)
5. In the Explorer key, right-click on the blank space, and choose**New** \>**DWORD (32-bit Value)** .
6. Name the value**HideClock** and press Enter.
7. Right-click on the HideClock value, type**1** in the**Value data** section, and click**OK.**  
![Modifying HideClock Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/modifying-hideclock-value.jpg)

 Close the Registry Editor window, and you'll see that the clock and date have disappeared from the taskbar.

 To reverse the changes, type**0** in the Value data section of HideClock value and click OK.

## Remove Any Distraction from the Taskbar

 The system tray clock helps you to keep track of the date and time. But if it has become a distraction or you want to keep the taskbar clean, you can use either of the above methods to configure the taskbar to hide the clock and date.


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
<li><a href="https://win11.techidaily.com/audio-amplifiers-4-essential-tools-that-push-pc-sounds-past-100/"><u>Audio Amplifiers: 4 Essential Tools that Push PC Sounds Past 100%%</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-system-reliability-automatic-updates-plus-graphics-card-swap/"><u>Enhance System Reliability: Automatic Updates + Graphics Card Swap</u></a></li>
<li><a href="https://win11.techidaily.com/erasing-email-on-windows-sign-in-a-guide/"><u>Erasing Email on Windows Sign-In: A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-visual-appeal-with-custom-pointer-design/"><u>Enhancing Visual Appeal with Custom Pointer Design</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-top-windows-11-challenges-with-ease/"><u>Tackling Top Windows 11 Challenges with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-soundscape-windows-11-spatial-tips/"><u>Elevate Your Soundscape: Windows 11 Spatial Tips</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-email-notification-shortcom-written-exercise/"><u>Repairing Email Notification Shortcom Written Exercise:</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-clip-of-fame-vimeo-quick-look/"><u>[New] Clip of Fame  Vimeo Quick Look</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/forgot-locked-apple-iphone-xs-max-password-learn-the-best-methods-to-unlock-by-drfone-ios/"><u>Forgot Locked Apple iPhone XS Max Password? Learn the Best Methods To Unlock</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-google-pixel-8-pro-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On Google Pixel 8 Pro Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-the-easy-way-to-remove-an-apple-id-from-your-macbook-for-your-iphone-6-plus-by-drfone-ios/"><u>In 2024, The Easy Way to Remove an Apple ID from Your MacBook For your iPhone 6 Plus</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-quick-witness-youtube-techniques-for-rapid-rendering/"><u>2024 Approved  Quick-Witness YouTube Techniques for Rapid Rendering</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/seamlessly-integrate-into-others-tiktok-livestreams/"><u>Seamlessly Integrate Into Others’ TikTok Livestreams</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/advanced-steps-for-documenting-online-meetings-for-2024/"><u>Advanced Steps for Documenting Online Meetings for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-unlock-the-potential-of-mac-for-top-tier-ootd-tiktoks/"><u>In 2024, Unlock the Potential of Mac for Top-Tier OOTD TikToks</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/a-complete-guide-to-oem-unlocking-on-poco-x6-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Poco X6</u></a></li>
</ul></div>
