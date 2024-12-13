---
title: Hack-Proof Guide for Stripping Emails Post Logon
date: 2024-12-09T03:49:26.518Z
updated: 2024-12-13T04:17:23.704Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Hack-Proof Guide for Stripping Emails Post Logon
excerpt: This Article Describes Hack-Proof Guide for Stripping Emails Post Logon
keywords: Hack-Proof Email Security,Stripped Login Data Safety,Secure Email Practices,Logon Email Protection,Robust Password Emailing,Resilient Email Handling,Safe Post-Login Email Access
thumbnail: https://thmb.techidaily.com/410b1a4d385c6e4b30f8c2bafd9b2a73f332bf6953f02a101819f0b8ffe4d954.jpg
---

## Hack-Proof Guide for Stripping Emails Post Logon

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the[many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Exit the Registry Editor and restart your PC for the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3C51hzX46eY?si=o5qiDSkT7mXUGm3F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-webster.techidaily.com/n-2024-the-most-economical-tools-for-youtube-audio-conversion/"><u>[New] In 2024, The Most Economical Tools for YouTube Audio Conversion</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-adapt-to-the-digital-age-mastering-computer-based-live-feeds-on-tiktok/"><u>[Updated] Adapt to the Digital Age Mastering Computer-Based Live Feeds on TikTok</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-the-insiders-guide-to-watermark-free-images/"><u>2024 Approved The Insider's Guide to Watermark-Free Images</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/apples-revolutionary-ipados-18-unveiled-at-wwdc-202n-must-have-features-for-a-seamless-switching-experience-digitalsavvy/"><u>Apple's Revolutionary iPadOS 18 Unveiled at WWDC 202N: Must-Have Features for a Seamless Switching Experience | DigitalSavvy</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-to-samsung-galaxy-z-flip-5-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Samsung Galaxy Z Flip 5 FRP Bypass With Best Methods</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-disappeared-battery-life-meter-for-windows-11-computers/"><u>Fixing Disappeared Battery Life Meter for Windows 11 Computers</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-prevent-and-resolve-video-crash-on-win1110-pcs/"><u>How to Prevent and Resolve Video Crash on Win11/10 PCs</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-hidden-guide-watching-highly-engaged-comments-with-ease-on-youtube/"><u>In 2024, The Hidden Guide Watching Highly Engaged Comments with Ease on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-solve-windows-11-upgrade-issue-0x800f0922/"><u>Quick Guide to Solve Windows 11 Upgrade Issue 0X800f0922</u></a></li>
<li><a href="https://fox-that.techidaily.com/top-6-solutions-for-troubleshooting-guidedowntime-issues-on-iphones/"><u>Top 6 Solutions for Troubleshooting GuideDowntime Issues on iPhones</u></a></li>
<li><a href="https://tech-haven.techidaily.com/troubleshooting-login-problems-with-chatgpt-easily-and-effectively/"><u>Troubleshooting Login Problems with ChatGPT Easily and Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-when-windows-cant-use-powershell/"><u>What to Do When Windows Can’t Use PowerShell</u></a></li>
</ul></div>

