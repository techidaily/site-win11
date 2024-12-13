---
title: "Winway Login Tips: Removing Personal Emails"
date: 2024-12-12T02:49:55.206Z
updated: 2024-12-13T04:19:41.785Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Winway Login Tips: Removing Personal Emails"
excerpt: "This Article Describes Winway Login Tips: Removing Personal Emails"
keywords: Winway Login Guide,Email Removal Tips,Safe Login Steps,Avoid Personal Info,Secure Login Methods,Privacy in Login,Opt-Out of Email
thumbnail: https://thmb.techidaily.com/57a4dd5881ee89a7ccb05cda2bbc7d01f9c197463ce070f6b273e0abf69dbbe5.jpg
---

## Winway Login Tips: Removing Personal Emails

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mMYEK2gtY5c?si=ytxNz_JHZkTrwb4b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the[many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nl0Z0eth1u4?si=0eecOBNfc--51AJO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-content.techidaily.com/new-mastering-soundtrack-addition-to-social-media-videos-on-facebook-for-2024/"><u>[New] Mastering Soundtrack Addition to Social Media Videos on Facebook for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-capturing-the-moment-advanced-tips-for-iphone-silhouettes-for-2024/"><u>[Updated] Capturing the Moment Advanced Tips for iPhone Silhouettes for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-cost-effective-subscriber-growth-hundreds-at-a-bargain-price-for-2024/"><u>[Updated] Cost-Effective Subscriber Growth - Hundreds at a Bargain Price for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-essential-audio-techniques-capturing-clear-sound-for-2024/"><u>[Updated] Essential Audio Techniques Capturing Clear Sound for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-ultimate-clock-companion-for-wedding-planners-and-couples/"><u>[Updated] The Ultimate Clock Companion for Wedding Planners & Couples</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-error-zero-eighty-three-one-in-windows/"><u>Conquering Error Zero-Eighty-Three-One in Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-tecno-spark-go-2024-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Tecno Spark Go (2024) | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-erase-iphone-14-plus-data-permanently-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>How To Erase iPhone 14 Plus Data Permanently | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-ffmpeg-review-upholding-authentic-audio-formats/"><u>In 2024, FFmpeg Review Upholding Authentic Audio Formats</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-sudo-for-enhanced-windows-security/"><u>Leveraging Sudo for Enhanced Windows Security</u></a></li>
<li><a href="https://win11.techidaily.com/maintain-your-data-expand-disk-space-techniques-for-windows-11-users-max-156-chars/"><u>Maintain Your Data, Expand Disk Space: Techniques for Windows 11 Users (Max 156 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-task-execution-efficient-keybinds-in-win-os/"><u>Personalize Task Execution: Efficient Keybinds in WIN OS</u></a></li>
<li><a href="https://win11.techidaily.com/solving-windows-camera-app-issues-quickly/"><u>Solving Windows Camera App Issues Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-directx-update-procedures-uncovered/"><u>Step-by-Step DirectX Update Procedures Uncovered</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/visual-power-in-gaming-channels-a-template-guidebook/"><u>Visual Power in Gaming Channels A Template Guidebook</u></a></li>
<li><a href="https://win11.techidaily.com/winning-notetakers-the-7-greatest-for-pcs-and-slate/"><u>Winning Notetakers: The 7 Greatest for PCs and Slate</u></a></li>
</ul></div>

