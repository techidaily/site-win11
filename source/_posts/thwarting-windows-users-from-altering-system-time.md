---
title: Thwarting Windows Users From Altering System Time
date: 2024-06-25T11:39:55.497Z
updated: 2024-06-26T11:39:55.497Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Thwarting Windows Users From Altering System Time
excerpt: This Article Describes Thwarting Windows Users From Altering System Time
keywords: Stop Time Change on Win PCs,Prevent Windows Clock Adjustment,Halt User Time Manipulation (Windows),Block System Time in Windows,Secure Windows Time Settings,Thwart Clock Changes Windows,Protect Windows Time Accuracy
thumbnail: https://thmb.techidaily.com/b271e3424a506666cfc32d0840f08d97d7b8b324df271cfd9aff178b05822fa5.jpg
---

## Thwarting Windows Users From Altering System Time

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

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

## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/override-hardware-acceleration-in-widnos-graphics-ordering/"><u>Override Hardware Acceleration in WIDNO's Graphics Ordering</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-your-vm-workflow-6-expert-tips-for-windows-users/"><u>Supercharge Your VM Workflow: 6 Expert Tips for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/delving-deep-into-windows-booting-mechanics-and-settings/"><u>Delving Deep Into Windows' Booting Mechanics and Settings</u></a></li>
<li><a href="https://win11.techidaily.com/1719338109987-windows-desk-icons-clashing-find-harmony/"><u>Windows Desk Icons Clashing - Find Harmony</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-slow-icon-loading-with-cache-refresh/"><u>Avoiding Slow Icon Loading with Cache Refresh</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-11s-user-sid-identification-methods/"><u>Unveiling Windows 11'S User SID Identification Methods</u></a></li>
<li><a href="https://win11.techidaily.com/direct-pc-access-through-smb-protocols-mobile/"><u>Direct PC Access Through SMB Protocols (Mobile)</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-world-apple-maps-on-windows/"><u>Navigating the World: Apple Maps on Windows</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-end-screen-makers/"><u>New 2024 Approved End Screen Makers</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/recommended-best-applications-for-mirroring-your-oppo-a58-4g-screen-drfone-by-drfone-android/"><u>Recommended Best Applications for Mirroring Your Oppo A58 4G Screen | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-10-top-rated-image-to-video-creation-platforms/"><u>2024 Approved 10 Top-Rated Image to Video Creation Platforms</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-do-you-unlock-your-apple-iphone-15-pro-learn-all-4-methods-by-drfone-ios/"><u>How Do You Unlock your Apple iPhone 15 Pro? Learn All 4 Methods</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-unlock-youtubes-monetizing-potential-with-strategic-short-videos/"><u>[New] Unlock YouTube's Monetizing Potential with Strategic Short Videos</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-itel-a60s-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Itel A60s | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/youtube-subscriber-awards-the-play-button-awards-for-creators/"><u>YouTube Subscriber Awards The Play Button Awards for Creators</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-2024-guide-to-auditory-freedom-through-pazera-extraction/"><u>The 2024 Guide to Auditory Freedom Through Pazera Extraction</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/unveiling-the-capabilities-of-springs-advanced-screenscape-for-2024/"><u>Unveiling the Capabilities of Spring's Advanced Screenscape for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>