---
title: "Erasing Email on Windows Sign-In: A Guide"
date: 2024-06-25T11:43:20.957Z
updated: 2024-06-26T11:43:20.957Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Erasing Email on Windows Sign-In: A Guide"
excerpt: "This Article Describes Erasing Email on Windows Sign-In: A Guide"
keywords: Erase Email Login,Wipe Sign-In Info,Remove Account Details,Clear Windows Passwords,Delete Email Credentials,Forget Windows ID,Purging Sign-In Data
thumbnail: https://thmb.techidaily.com/b1557e3d9700a9810b8b9bbec88362c53ba5a3f98f5f309c7652fc768db4746d.jpg
---

## Erasing Email on Windows Sign-In: A Guide

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the[many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

## 2\. How to Hide Email Address From Windows Login Screen Using the Group Policy Editor

 The Group Policy Editor (or gpedit.msc) is a handy Windows tool for configuring advanced system settings. You can also this tool to hide your email address from the Windows login screen.

 Note that the Group Policy Editor is only available on Windows Professional, Education, and Enterprise editions. If your PC is running Windows Home, check out[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the search box and select the first result that appears.
3. Use the left pane to navigate to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options** .
4. Double-click the **Interactive Logon: Display user information when the session is locked** policy on your right.
5. In the properties window, click the drop-down menu to select the**Do not display user information** option.
6. Click**Apply** followed by**OK** .  
![Hide Email From Windows Login Screen Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-group-policy-editor.jpg)
7. Next, double-click on the**Interactive logon: Do not display last user name** policy from the same section.
8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

## 3\. How to Hide Email Address From Windows Login Screen Using the Registry Editor

 If the above two methods don’t work for some reason, you can make changes to the Windows registry files to hide your email address from the login screen. For that, you’ll need to use the Registry Editor on Windows.

 When it comes to editing Registry files, it's important to be cautious as making incorrect changes can cause irreversible damage to your PC. We recommend you either back up all the registry files or create a restore point before you make any changes. If you need help with that, check our guides on[how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and[how to create a restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

 Once you’re done with that, use the following steps to hide your email address from the Windows login screen via Registry Editor.

1. Press**Win + X** to open the Power User menu and select**Run** from the list.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows > System** .
5. Right-click on the**System** key and select**New > DWORD (32-bit) Value** .
6. Rename the DWORD to**BlockUserFromShowingAccountDetailsOnSignin** .
7. Double-click on the newly created DWORD and enter**1** in the**Value data** field. Then, click**OK** .  
![Hide Email From Windows Login Screen Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-registry-editor.jpg)

 Exit the Registry Editor and restart your PC for the changes to take effect.

## Hiding Your Email Address From the Windows Login Screen Is Easy

 As we just saw, hiding your personal information from the Windows login screen barely takes a couple of minutes, regardless of the method you employ.


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
<li><a href="https://win11.techidaily.com/why-and-how-to-choose-effective-encoders-on-your-pc/"><u>Why and How to Choose Effective Encoders on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-windows-11-installation-with-these-essential-tweaks/"><u>Streamline Your Windows 11 Installation with These Essential Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/eliciting-hidden-taskbar-recon-in-windows-11/"><u>Eliciting Hidden Taskbar Recon in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-power-of-wpm-in-windows-11-environments/"><u>Unveiling the Power of WPM in Windows 11 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-image-formats-stopping-chromes-webp-savings-on-pc/"><u>Mastering Image Formats: Stopping Chrome's WebP Savings on PC</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-and-resolving-0x800704cf-error-in-windows-store/"><u>Unraveling and Resolving 0X800704CF Error in Windows' Store</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-ethernet-connection-fixes/"><u>Navigating Through Ethernet Connection Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-mastering-3d-painting-shortcuts/"><u>Expert Tips for Mastering 3D Painting Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-risks-ignoring-windows-11-push-notifications/"><u>Understanding Risks: Ignoring Windows 11 Push Notifications</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-choosing-between-podcast-and-youtube-for-content-delivery/"><u>In 2024, Choosing Between Podcast and YouTube for Content Delivery</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/elevate-video-views-twitter-to-facebook-transition/"><u>Elevate Video Views  Twitter to Facebook Transition</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/nending-shutdown-method-how-to-kill-off-youtube-shorts-for-2024/"><u>[New] Unending Shutdown Method  How to Kill Off Youtube Shorts for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-two-ways-to-track-my-boyfriends-vivo-v27e-without-him-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Two Ways to Track My Boyfriends Vivo V27e without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-top-performing-tiktok-metrics-for-account-growth-analysis-for-2024/"><u>[New] Top Performing TikTok Metrics for Account Growth Analysis for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-ultimate-digital-collage-creator-8x/"><u>[Updated] Ultimate Digital Collage Creator 8X</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-interpreting-the-functionality-behind-facebooks-blue-video-icon/"><u>In 2024, Interpreting the Functionality Behind Facebook's Blue Video Icon</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-apple-iphone-14-passcode-without-computer-drfone-by-drfone-ios/"><u>How to Unlock Apple iPhone 14 Passcode without Computer? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-how-to-take-360-videos-on-iphone-for-facebook/"><u>[Updated] 2024 Approved  How to Take 360 Videos on iPhone for Facebook</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-exploring-the-leading-10-cost-effective-podcast-production-applications/"><u>Updated 2024 Approved Exploring the Leading 10 Cost-Effective Podcast Production Applications</u></a></li>
</ul></div>
