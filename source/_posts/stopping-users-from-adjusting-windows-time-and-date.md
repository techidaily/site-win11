---
title: Stopping Users From Adjusting Windows Time and Date
date: 2024-06-25T11:41:47.971Z
updated: 2024-06-26T11:41:47.971Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stopping Users From Adjusting Windows Time and Date
excerpt: This Article Describes Stopping Users From Adjusting Windows Time and Date
keywords: Prevent Windows Clock Changes,Block Windows Date Alteration,Stop Time & Date on Windows,Halt Windows Time Update,Disable PC Date Change,Prohibit Windows Time Adjustment,Inhibit DST Time Shift in Windows
thumbnail: https://thmb.techidaily.com/f5eeb9ebfa2de64a3d4ee3942e718c9f14502e6b864cfccf1cdec1e982bafc3d.jpg
---

## Stopping Users From Adjusting Windows Time and Date

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
<li><a href="https://win11.techidaily.com/connecting-classics-windows-11s-pathway-to-photos-folder/"><u>Connecting Classics: Windows 11'S Pathway to Photos Folder</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-remedy-windows-onedrive-server-issues/"><u>Swiftly Remedy Windows OneDrive Server Issues</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-disabled-usb-wi-fi-adapters-in-windows/"><u>How To Reactivate Disabled USB Wi-Fi Adapters in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-file-properties-and-date-adjustments/"><u>Navigating Windows File Properties and Date Adjustments</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-could-not-create-the-java-virtual-machine-error-on-windows/"><u>How to Fix the “Could Not Create the Java Virtual Machine” Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-oculus-setup-fails-windows-1110-strategies/"><u>Addressing Oculus Setup Fails: Windows 11/10 Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-tech-tutorial-how-to-launch-calculator/"><u>Windows 11 Tech Tutorial: How to Launch Calculator</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-resolving-virtual-disk-service-failure-in-windows/"><u>Troubleshooting: Resolving Virtual Disk Service Failure in Windows</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-playback-paradox-starting-at-the-finish-line-on-youtube-for-2024/"><u>The Playback Paradox  Starting at the Finish Line on YouTube for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-apex-fusion-hubs-all-in-one-4k-multi-touch-desktops/"><u>[New] Apex Fusion Hubs  All-in-One 4K Multi-Touch Desktops</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-synchronize-your-scenes-editing-videos-in-step-with-the-music-in-adobe-premiere-pro/"><u>New Synchronize Your Scenes Editing Videos in Step With the Music in Adobe Premiere Pro</u></a></li>
<li><a href="https://howto.techidaily.com/fix-cant-take-screenshot-due-to-security-policy-on-samsung-galaxy-xcover-6-pro-tactical-edition-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Cant Take Screenshot Due to Security Policy on Samsung Galaxy XCover 6 Pro Tactical Edition | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-get-creative-with-free-video-invitations-the-best-online-makers/"><u>New 2024 Approved Get Creative with Free Video Invitations The Best Online Makers</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-reviewing-screenmasters-latest-tech-for-recording-for-2024/"><u>[Updated] Reviewing ScreenMaster's Latest Tech for Recording for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-from-script-to-screen-mastery-through-vida-writers-guide/"><u>[New] From Script to Screen  Mastery Through Vida’ Writers Guide</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-ultimate-guide-to-protected-and-entertaining-chatting-apps-for-unknown-individuals/"><u>New Ultimate Guide to Protected and Entertaining Chatting Apps for Unknown Individuals</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-combining-youtube-videos-for-seamless-playback/"><u>[New] 2024 Approved  Combining YouTube Videos for Seamless Playback</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>