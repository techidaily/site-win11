---
title: Guidelines for Upholding Windows Date/Time Integrity
date: 2024-06-25T11:45:30.157Z
updated: 2024-06-26T11:45:30.157Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guidelines for Upholding Windows Date/Time Integrity
excerpt: This Article Describes Guidelines for Upholding Windows Date/Time Integrity
keywords: TimeIntegrityWindows,DateTimeUpholdGuidance,DTSyncProcedures,OSDateTimeStandards,SystemTimeCorrection,DateSyncMethodology,WindowsDateTimeRules
thumbnail: https://thmb.techidaily.com/8b7337516e3ab4c7de40944c48ebe243474ab75d4e4c1c2d693991f9d3085553.jpg
---

## Guidelines for Upholding Windows Date/Time Integrity

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
<li><a href="https://win11.techidaily.com/cortanas-farewell-windows-future-awaits/"><u>Cortana's Farewell, Windows' Future Awaits</u></a></li>
<li><a href="https://win11.techidaily.com/the-compreenas-guide-track-down-your-windows-serial-number/"><u>The Compreenas Guide: Track Down Your Windows Serial Number</u></a></li>
<li><a href="https://win11.techidaily.com/windows-mastering-app-and-browser-oversight/"><u>Windows: Mastering App & Browser Oversight</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-key-activation-issues/"><u>Troubleshooting Windows Key Activation Issues</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-a-faulty-esc-key-in-windows-10-and-beyond/"><u>Troubleshoot a Faulty Esc Key in Windows 10 and Beyond</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-the-summary-size-of-your-pics/"><u>Customizing the Summary Size of Your Pics</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-samsung-flow-linking-winpc-and-galaxy-device/"><u>Mastering Samsung Flow: Linking WinPC & Galaxy Device</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-maximizing-facebook-video-engagement-with-the-right-cover-size/"><u>New 2024 Approved Maximizing Facebook Video Engagement with the Right Cover Size</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/rhythm-renders-infusing-sound-into-your-visual-storytelling-fb/"><u>Rhythm Renders  Infusing Sound Into Your Visual Storytelling (FB)</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-transforming-google-meet-screens-on-devices/"><u>[Updated] 2024 Approved  Transforming Google Meet Screens on Devices</u></a></li>
<li><a href="https://howto.techidaily.com/fix-oppo-reno-11-5g-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Oppo Reno 11 5G Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-unstable-footage-fix-it-with-these-top-5-free-android-video-stabilizer-apps/"><u>New Unstable Footage? Fix It with These Top 5 Free Android Video Stabilizer Apps</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-mastering-your-fb-profile-top-tips-for-impressive-biographies/"><u>[Updated] 2024 Approved  Mastering Your FB Profile  Top Tips for Impressive Biographies</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-tube-tallies-counting-the-top-10-watched-videos-on-twit-for-2024/"><u>[New] Tube Tallies  Counting the Top 10 Watched Videos on Twit for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-time-stretching-through-lenses-a-detailed-slomo-analysis-2024/"><u>[New] Time Stretching Through Lenses  A Detailed SloMo Analysis, 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>