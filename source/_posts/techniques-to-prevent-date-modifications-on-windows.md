---
title: Techniques to Prevent Date Modifications on Windows
date: 2024-09-21T19:39:17.559Z
updated: 2024-09-28T22:58:06.441Z
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

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557746/17382" target="_top" id="1557746">
  <img src="//a.impactradius-go.com/display-ad/17382-1557746" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557746/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1172027/12108" target="_top" id="1172027">
  <img src="//a.impactradius-go.com/display-ad/12108-1172027" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1172027/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080317/19272" target="_top" id="2080317">
  <img src="//a.impactradius-go.com/display-ad/19272-2080317" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080317/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151866/7443" target="_top" id="2151866">
  <img src="//a.impactradius-go.com/display-ad/7443-2151866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151866/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-samurai-spirit-explored-in-top-10-gaming-worlds/"><u>[New] 2024 Approved Samurai Spirit, Explored in Top 10 Gaming Worlds</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-subscribers-on-a-shoestring-grow-your-channel-fast/"><u>[New] 2024 Approved Subscribers on a Shoestring Grow Your Channel Fast</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-best-in-class-music-video-platforms-for-2024/"><u>[Updated] Best-in-Class Music Video Platforms for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-dxgi-failures-on-windows-1011/"><u>Addressing DXGI Failures on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/boot-time-essentials-configuring-windows-startups/"><u>Boot Time Essentials: Configuring Windows Startups</u></a></li>
<li><a href="https://win-dash.techidaily.com/cavitation-typically-occurs-at-high-flow-rates-where-low-pressure-zones-are-created-potentially-causing-damage-to-the-impeller/"><u>Cavitation Typically Occurs at High Flow Rates Where Low-Pressure Zones Are Created, Potentially Causing Damage to the Impeller.</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-typing-managing-filter-keys-on-pcs/"><u>Elevate Your Typing: Managing Filter Keys on PCs</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-can-you-transfer-files-from-htc-u23-pro-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How Can You Transfer Files From HTC U23 Pro To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-google-pixel-8-pro-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track Google Pixel 8 Pro Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-techniques-to-transfer-data-from-oneplus-12r-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Techniques to Transfer Data from OnePlus 12R to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-most-useful-tips-for-pokemon-go-ultra-league-on-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>In 2024, The Most Useful Tips for Pokemon Go Ultra League On Google Pixel 8 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-correcting-error-740-on-winos/"><u>Mastering the Art of Correcting Error 740 on WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-sluggishness-fixing-edge-speed-woes-in-windows-10plus11/"><u>Overcoming Sluggishness: Fixing Edge Speed Woes in Windows 10+11</u></a></li>
<li><a href="https://win11.techidaily.com/win11-mastering-custom-key-combos-for-fixed-text-insertions/"><u>Win11: Mastering Custom Key Combos for Fixed Text Insertions</u></a></li>
<li><a href="https://win11.techidaily.com/windows-activation-the-hidden-traps-in-inexpensive-keys/"><u>Windows Activation: The Hidden Traps in Inexpensive Keys</u></a></li>
</ul></div>

