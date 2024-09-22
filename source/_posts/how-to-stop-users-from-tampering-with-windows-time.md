---
title: How To Stop Users From Tampering with Windows Time
date: 2024-09-15T02:35:48.258Z
updated: 2024-09-21T16:31:03.816Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How To Stop Users From Tampering with Windows Time
excerpt: This Article Describes How To Stop Users From Tampering with Windows Time
keywords: Secure Time Settings,Prevent Windows Time Mods,Anti-Time Manipulation Techniques,Safeguard Windows Clock,Block Windows Time Tampering,Protect System Time Integrity,Windows Time Hardening Methods
thumbnail: https://thmb.techidaily.com/3b3746640fe26afab367eb3d6989fbedd82bfd022cd1e2fe844a87bc2bcb92f8.jpg
---

## How To Stop Users From Tampering with Windows Time

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

## 1\. Use the Group Policy Editor

 If your computer is part of an organization and users often change the date and time, use Group Policy Editor to stop it. This will prevent those with limited access to the computer from altering the date and time. However, this method only works for Windows Pro, Enterprise, or Education Editions.

 So, if you have Windows Home Edition, this won’t work. In that case, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). If it seems complicated, skip it and try the next solution instead.

 Follow these steps to prevent users from changing the date and time:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **gpedit.msc** in the text box and press Enter. This will open the Group Policy Editor window.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > System > Locale Services
4. In the right-side pane, double-click on **Disallow user override of locale settings**.  
![Disallow user override of locale settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disallow-user-override-of-locale-settings.jpg)
5. In the pop-up window, check the **Enabled** radio button.
6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

## 2\. Tweak the Registry Editor

 If you’re using Windows Home Edition or have disabled the Group Policy Editor, use the Registry Editor to protect date and time settings. This method is more advanced and has a higher risk of system damage.

 In that case, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it. Doing so will restore settings if something goes wrong.

 Follow these steps to stop users from changing the time and date via the registry:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the field and press Enter. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. In the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Software\Policies\Microsoft\Control Panel\International\
4. If the International folder doesn’t exist, create one. To do that, right-click on Control Panel and select **New** \> **Key**. Name it **International**.
5. Then right-click on **International** and select New > DWORD (32-bit) Value.
6. Name the newly created value **PreventUserOverrides**.
7. Double-click on the **PreventUserOverrides** DWORD value.  
![Use Registry Editor to Prevent Users From Chaning date and time settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-registry-editor-to-prevent-users-from-chaning-date-and-time-settings.jpg)
8. In the pop-up window, change the Value data to **1** and click **OK**.

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151870/7443" target="_top" id="2151870">
  <img src="//a.impactradius-go.com/display-ad/7443-2151870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151870/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-knowledge.techidaily.com/new-fresh-look-at-sonys-ultra-hd-player-s3700/"><u>[New] Fresh Look at Sony's Ultra HD PLAYER S3700</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-leading-apps-for-editing-dji-drone-film-content/"><u>[New] Leading Apps for Editing DJi Drone Film Content</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-the-insiders-look-at-facebook-video-proportions-and-settings-for-2024/"><u>[New] The Insider's Look at Facebook Video Proportions and Settings for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-quick-recovery-of-twitch-broadcasts/"><u>[New] The Quick Recovery of Twitch Broadcasts</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-seamless-soundscapes-youtube-music-integration-tips/"><u>[Updated] 2024 Approved Seamless Soundscapes YouTube Music Integration Tips</u></a></li>
<li><a href="https://win-remarkable.techidaily.com/1726219929592-8/"><u>8가지 강력한 사진 배경 정리 팁: 최고의 누끼 사이트 선택</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/edit-your-way-to-perfection-with-android/"><u>Edit Your Way to Perfection with Android</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-permanent-deletion-of-files-using-the-windows-11-and-11-trash-bin/"><u>Ensuring Permanent Deletion of Files Using the Windows 11 & 11 Trash Bin</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-windows-11-bluescreens-adopt-these-proven-tactics/"><u>Navigate Windows 11 Bluescreens: Adopt These Proven Tactics</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/navigating-legalities-of-instagram-harmonies/"><u>Navigating Legalities of Instagram Harmonies</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-exception-interrupted-issue-in-windows-systems/"><u>Resolving Exception Interrupted Issue in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/the-anatomy-of-windows-programming-and-linker-format-pe/"><u>The Anatomy of Windows' Programming and Linker Format (PE)</u></a></li>
<li><a href="https://win11.techidaily.com/the-rise-of-16gb-in-win-pcs-a-ram-revolution/"><u>The Rise of 16GB in Win PCs: A RAM Revolution</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-and-resolving-oculus-graphics-card-problems-successfully/"><u>Troubleshooting and Resolving Oculus Graphics Card Problems Successfully</u></a></li>
<li><a href="https://win11.techidaily.com/win-error-0x0000007b-your-quick-solution-guide/"><u>Win Error 0X0000007B - Your Quick Solution Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    