---
title: Disabling Windows System Update Warnings
date: 2024-06-25T11:43:04.481Z
updated: 2024-06-26T11:43:04.481Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Windows System Update Warnings
excerpt: This Article Describes Disabling Windows System Update Warnings
keywords: Disable Update Alerts,Stop Win Updates Notify,Silence OS Update Warnings,Halt Windows System Alerts,Prevent Windows Update Alarms,Mute Windows Update Issues,Cease Updates Notifications
thumbnail: https://thmb.techidaily.com/6e0cdf2b7038ec925488e32c1b0811331fe39479e79326e6be564a7361db8bbb.jpg
---

## Disabling Windows System Update Warnings

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in[how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

 Once you complete the above steps, Windows should not bother you with update notifications.

## 2\. Disable Windows Update Notifications Using Group Policy Editor

 Group Policy Editor is a powerful tool for configuring various settings on your Windows computer. If you have the Enterprise or Professional edition of Windows, you can disable update notifications using the Group Policy Editor. If you don't have either of those versions, read our guide on[how to access Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

To disable Windows update notifications using Group Policy Editor:

1. Press**Win + R** to open the Run dialog box.
2. Type**gpedit.msc** in the box and press**Enter** .
3. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Windows Update > Manage end use experience.**
4. Double-click the**Display options for update notifications** policy on your right.
5. Select the**Disabled** option.
6. Click**Apply** followed by**OK** .  
![Disable Windows Update Notifications Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-group-policy-editor-1.jpg)

 If you want to re-enable the Windows update notifications later, follow the same steps above and set the**Display options for update notifications** policy to**Not configured** .

## 3\. Disable Windows Update Notifications With Registry Editor

 If you can’t seem to access the Group Policy Editor for some reason, you can use the Registry Editor to disable update notifications.

 Since Registry Editor is a powerful tool that needs to be handled with care, we recommend that you back up all the registry files or create a restore point before proceeding with the changes below. If you need help, check our guides on[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and[how to create a restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

To disable Windows update notifications using Registry Editor:

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window, use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows** .
5. Locate the**WindowsUpdate** key. If you can’t find it, right-click on the**Windows** key and select**New > Key** . Rename the key as**WindowsUpdate** .
6. Right-click the**WindowsUpdate** key and select**New > DWORD (32-bit) Value** .
7. Rename the DWORD as**SetUpdateNotificationLevel** .
8. Double-click the newly created DWORD and change its**Value data** to**0** .
9. Click**OK** .  
![Disable Windows Update Notifications Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-registry-editor.jpg)

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

## No More Update Notifications on Windows

 Windows updates are critical for the overall stability of your computer. That said, turning off Windows update notifications makes sense if you're not in a rush to install updates as soon as they are ready for installation.

 If you find Windows notifications to be distracting in general, you can use Focus Assist to silence all alerts and stay productive.


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
<li><a href="https://win11.techidaily.com/establishing-enduring-trash-settings-in-the-windows-environment/"><u>Establishing Enduring Trash Settings in the Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-login-hurdles-for-epic-games/"><u>Overcoming Windows Login Hurdles for Epic Games</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-how-choosing-a-pc-over-a-mac-can-benefit-you-more-9/"><u>Decoding How Choosing a PC Over A Mac Can Benefit You More (#9)</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-printer-network-errors-in-windows/"><u>Steps to Resolve Printer Network Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-windows-11-taskbar-discrepan-marketplace/"><u>Rectifying Windows 11 Taskbar Discrepan Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-windows-11s-security-and-credentials-panel/"><u>Guide to Windows 11'S Security & Credentials Panel</u></a></li>
<li><a href="https://win11.techidaily.com/quick-pc-revival-unearthing-windows-best-eight-methods/"><u>Quick PC Revival: Unearthing Windows' Best Eight Methods</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/fixed-video-short-display-for-you-for-2024/"><u>Fixed Video Short Display for You for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-what-is-animated-gif-gif-example-and-advantages-of-gif-for-2024/"><u>Updated What Is Animated GIF | GIF Example & Advantages of GIF for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-itel-p40plus-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Itel P40+ to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-xiaomi-14-pro-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Xiaomi 14 Pro Device</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-sharefake-gps-on-uber-for-itel-p55-drfone-by-drfone-virtual-android/"><u>How to share/fake gps on Uber for Itel P55 | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-for-social-media-savants-distinguishing-between-igtv-and-youtube/"><u>[New] In 2024, For Social Media Savants  Distinguishing Between IGTV & YouTube</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-mirthful-mayhem-a-top-20-list-of-hilarious-tiktok-jokes-and-riddles/"><u>[New] In 2024, Mirthful Mayhem  A Top 20 List of Hilarious TikTok Jokes & Riddles</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-transform-your-videos-into-cinematic-masterpieces-on-mac-for-2024/"><u>New Transform Your Videos Into Cinematic Masterpieces on Mac for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-can-we-unlock-our-samsung-galaxy-a15-5g-phone-screen-by-drfone-android/"><u>How Can We Unlock Our Samsung Galaxy A15 5G Phone Screen?</u></a></li>
</ul></div>
