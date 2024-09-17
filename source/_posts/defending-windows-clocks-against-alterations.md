---
title: Defending Windows Clocks Against Alterations
date: 2024-09-13T00:43:50.988Z
updated: 2024-09-17T04:48:24.293Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Defending Windows Clocks Against Alterations
excerpt: This Article Describes Defending Windows Clocks Against Alterations
keywords: Windows Time Defense,Clock Security Measures,Protecting System Clocks,Anti-Clock Modification,Windows Timestamp Safeguard,Counteract Clock Tampering,Secure Windows Hours
thumbnail: https://thmb.techidaily.com/4e54d2ee69e2d3cc5b62664f281e174d4bc506ec5c304888c5062a8c04d6107f.jpg
---

## Defending Windows Clocks Against Alterations

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136615/26400" target="_top" id="2136615">
  <img src="//a.impactradius-go.com/display-ad/26400-2136615" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136615/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-video-files.techidaily.com/updated-best-tiktok-pfp-ideas-to-make-your-tiktok-profile-stand-out-for-2024/"><u>[Updated] Best TikTok PFP Ideas to Make Your TikTok Profile Stand Out for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-uncovered-wonders-top-6-stealthy-audio-capture-tools-androidios-for-2024/"><u>[Updated] Uncovered Wonders Top 6 Stealthy Audio Capture Tools (Android/iOS) for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-the-art-of-photo-to-video-with-accompaniment-sounds/"><u>2024 Approved The Art of Photo-to-Video with Accompaniment Sounds</u></a></li>
<li><a href="https://win11.techidaily.com/2024-flv-windows-10/"><u>2024年版 FLV ビデオプレイヤーの復活！Windows 10用トップテクニックリスト公開</u></a></li>
<li><a href="https://win11.techidaily.com/5oiq5lq65zcr44gr44ot44oh44kq44ks44kt44oj44ox44ob44oj44gz44kl5yq55p6c55qe44gq44og44kv44ol44od44kv/"><u>成人向けビデオをキャプチャする効果的なテクニック</u></a></li>
<li><a href="https://win11.techidaily.com/aacm4a/"><u>音声ファイルの変換:AACとM4Aを比べて、最適な無劣化方法は何ですか？</u></a></li>
<li><a href="https://win11.techidaily.com/6zw35oyb44gh44gz44kl5pa55rov77ya44ov44oq44od44ox44ot44oh44kq44gu5pya6ygp44gq5lplusd5a2y5oml5q61/"><u>長持ちする方法：フリップビデオの最適な保存手段</u></a></li>
<li><a href="https://win11.techidaily.com/best-split-screen-video-software-discover-the-5-most-user-friendly-options-for-making-split-videos-with-ease/"><u>Best Split Screen Video Software: Discover the 5 Most User-Friendly Options for Making Split Videos with Ease</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-tecno-pop-7-pro-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Tecno Pop 7 Pro to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-10-best-fake-gps-location-spoofers-for-zte-blade-a73-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 10 Best Fake GPS Location Spoofers for ZTE Blade A73 5G | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-quick-guide-to-realme-narzo-60-pro-5g-frp-bypass-instantly-by-drfone-android/"><u>In 2024, A Quick Guide to Realme Narzo 60 Pro 5G FRP Bypass Instantly</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changefake-your-honor-play-8t-location-on-viber-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Fake Your Honor Play 8T Location on Viber | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-recommended-best-applications-for-mirroring-your-xiaomi-redmi-a2plus-screen-drfone-by-drfone-android/"><u>In 2024, Recommended Best Applications for Mirroring Your Xiaomi Redmi A2+ Screen | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/44kz44o844oh44od44kv5lin6laz44gr44ki44kl5yuv55s75yan55sf6zqc5a6z44ks5zue6yg44gz44kl5pa55rov/"><u>コーデック不足による動画再生障害を回避する方法</u></a></li>
<li><a href="https://win11.techidaily.com/44ot44oh44kq44gu5lit44gr44og44kt44k544oi44k144ow44k44kk44oi44or6lplus95yqg5oml6acg6zug/"><u>ビデオの中にテキストサブタイトル追加手順集</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    