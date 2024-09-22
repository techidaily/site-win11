---
title: Techniques to Prevent Date Modifications on Windows
date: 2024-09-19T21:52:01.235Z
updated: 2024-09-21T21:36:06.725Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques to Prevent Date Modifications on Windows
excerpt: This Article Describes Techniques to Prevent Date Modifications on Windows
keywords: WinDateChangePrevention,StopWindowsModification,SecureWindowsDates,AvoidWindowsEditing,ProtectWindowsTimestamps,SafeTimeSettingsWin,WindowsDateFormatLock
thumbnail: https://thmb.techidaily.com/ca38034074275621f4e2db5f63e60466f24745c2303d23667377ba30f3317569.jpg
---

## Techniques to Prevent Date Modifications on Windows

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
<a href="https://appsumo.8odi.net/c/5597632/2130874/7443" target="_top" id="2130874">
  <img src="//a.impactradius-go.com/display-ad/7443-2130874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130874/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/n-2024-elevate-your-channels-templates-at-no-charge/"><u>[New] In 2024, Elevate Your Channels - Templates at No Charge</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-game-on-easy-ways-to-record-your-overwatch-experience/"><u>[New] In 2024, Game On! Easy Ways to Record Your Overwatch Experience</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-break-down-the-essentials-of-youtube-sharing-on-facebook/"><u>[Updated] Break Down The Essentials of YouTube Sharing on Facebook</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-efficient-video-download-from-facebooks-domain/"><u>[Updated] In 2024, Efficient Video Download From Facebook's Domain</u></a></li>
<li><a href="https://win11.techidaily.com/best-split-screen-video-software-discover-the-5-most-user-friendly-options-for-making-split-videos-with-ease/"><u>Best Split Screen Video Software: Discover the 5 Most User-Friendly Options for Making Split Videos with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/best-video-format-changer-app-for-ps4-easy-steps-to-enjoy-any-content/"><u>Best Video Format Changer App for PS4: Easy Steps to Enjoy Any Content!</u></a></li>
<li><a href="https://win11.techidaily.com/complete-tutorial-on-restoring-damaged-mkv-movie-files/"><u>Complete Tutorial on Restoring Damaged MKV Movie Files</u></a></li>
<li><a href="https://win11.techidaily.com/daznpc/"><u>DAZN映像取得・保管手順に関するPCユーザ向けの詳細マニュアル</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-ultimate-selection-top-10-no-cost-image-repositories-with-extensive-high-end-visual-archives/"><u>Discover the Ultimate Selection: Top 10 No-Cost Image Repositories with Extensive, High-End Visual Archives</u></a></li>
<li><a href="https://win11.techidaily.com/duplicate-dvds-easily-using-1click-dvd-copy-plus-top-alternatives-revealed/"><u>Duplicate DVDs Easily Using 1Click DVD Copy - Plus Top Alternatives Revealed!</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-tutorial-unlocking-the-secrets-of-peekvids-video-extraction/"><u>Effortless Tutorial: Unlocking the Secrets of PeekVids Video Extraction</u></a></li>
<li><a href="https://some-techniques.techidaily.com/frame-by-frame-helpdesk-for-2024/"><u>Frame by Frame Helpdesk for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-easily-upload-groups-of-photos-to-facebook-in-one-go/"><u>How To Easily Upload Groups of Photos to Facebook in One Go</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-honor-100-pro-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Honor 100 Pro Location Settings | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-top-6-ways-to-transfer-text-messages-from-xiaomi-redmi-note-12-proplus-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Top 6 Ways to Transfer Text Messages from Xiaomi Redmi Note 12 Pro+ 5G to Other Android Devices | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    