---
title: Mute Windows Update Announcements
date: 2024-12-26T23:21:31.568Z
updated: 2024-12-27T17:44:17.759Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mute Windows Update Announcements
excerpt: This Article Describes Mute Windows Update Announcements
keywords: Mute UUpdate Notifications,Silence Windows Updates,Block Windows Update Sounds,Stop Windows Update Alerts,Quiet Windows Update Sound,Deactivate Windows Update Chime,Hush Windows Patch Announcements
thumbnail: https://thmb.techidaily.com/08f2c817ace11f52f69518bb589ba81c382ee3c50cca52847005eac86a562eee.jpg
---

## Mute Windows Update Announcements

 When an update is ready for installation, Windows notifies you and prompts you to restart your computer. As helpful as these reminders are, they can also be distracting at times. Fortunately, it’s possible to disable update notifications on Windows.

 You can disable Windows update notifications using the Settings app, Group Policy Editor, or Registry Editor. Let's go over each of these methods one by one.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Disable Windows Update Notifications via the Settings App

 The quickest way to disable update notifications on Windows is through the Settings app. Here are the steps for the same.

1. Press**Win + I** to open Windows Settings. You can also use any method we cover in[how to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Update & Security > Windows Update** .
3. Select**Advanced options** .
4. Disable the toggle for**Notify me when a restart is required to finish updating** .
5. Disable the toggle for**Get me up to date** so that Windows does not display a restart warning when an update is ready for installation.  
![Disable Windows Update Notifications Using the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disable-windows-update-notifications-using-the-settings-app.jpg)

 Once you complete the above steps, Windows should not bother you with update notifications.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipTu54inBo?si=gRegjvtVq5gm_PHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Exit the Registry Editor window and restart your PC to apply the changes. Following that, Windows will not display update notifications on your computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-webster.techidaily.com/024-approved-crafting-channel-graphics-icons-banners-and-thumbnails/"><u>[New] 2024 Approved Crafting Channel Graphics Icons, Banners & Thumbnails</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-chic-characters-enhancing-facial-photo-appeal-with-picsart-motion-blur/"><u>[New] Chic Characters Enhancing Facial Photo Appeal with Picsart Motion Blur</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-demystify-video-editing-with-free-vimeo-resources/"><u>[New] Demystify Video Editing with Free Vimeo Resources</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-blueprint-for-attracting-brands-as-youtube-affiliates/"><u>2024 Approved The Blueprint for Attracting Brands as Youtube Affiliates</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-oppo-f23-5g-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Oppo F23 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-pc-revamp-with-these-three-windows-steps/"><u>Efficient PC Revamp with These Three Windows Steps</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-no-network-windows-notification/"><u>Fixes for 'No Network' Windows Notification</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-disconnect-unauthorized-accounts-on-win-11/"><u>How to Disconnect Unauthorized Accounts on Win 11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-fix-hyperx-cloud-alpha-headset-microphone-issues-a-complete-guide/"><u>How to Fix HyperX Cloud Alpha Headset Microphone Issues: A Complete Guide</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-audible-feedback-in-os-xwindows/"><u>How to Get Audible Feedback in OS X/Windows</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-change-country-on-app-store-for-iphone-xr-with-7-methods-drfone-by-drfone-ios/"><u>In 2024, How To Change Country on App Store for iPhone XR With 7 Methods | Dr.fone</u></a></li>
<li><a href="https://win-webster.techidaily.com/optimierung-der-datenspeicherung-verhindere-die-unnotige-beibehaltung-alter-backups-auf-dem-windows-server/"><u>Optimierung Der Datenspeicherung: Verhindere Die Unnötige Beibehaltung Alter Backups Auf Dem Windows Server</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-wows-deadly-error-132-on-windows-11/"><u>Overcoming WoW's Deadly Error #132 on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-pc-shortcuts-in-windows-11/"><u>Personalizing PC Shortcuts in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/steering-device-activation-through-pc-sleep-states/"><u>Steering Device Activation Through PC Sleep States</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-addressing-cc-errors-on-windows-11/"><u>Understanding and Addressing CC Errors on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/wheel-alignment-keep-your-wheels-properly-aligned-to-reduce-undue-stress-on-suspension-components-misalignment-can-cause-premature-wear-and-potentially-dama66/"><u>Wheel Alignment: Keep Your Wheels Properly Aligned to Reduce Undue Stress on Suspension Components. Misalignment Can Cause Premature Wear and Potentially Damage Other Parts of the Vehicle if Not Addressed Promptly</u></a></li>
</ul></div>

