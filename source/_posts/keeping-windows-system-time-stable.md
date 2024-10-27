---
title: Keeping Windows' System Time Stable
date: 2024-10-26T02:14:38.436Z
updated: 2024-10-26T17:27:26.805Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Keeping Windows' System Time Stable
excerpt: This Article Describes Keeping Windows' System Time Stable
keywords: TimeSync Windows,Stable SystemTime,Keeping Windows TimeStable,Windows TimeStability,Uniform Windows Time,Consistent WindowsTime,SecureWindows Timestamp
thumbnail: https://thmb.techidaily.com/33f7a6674447c8f7173ff1c687707de6ab2b192d47bf8afae9f7fe02b3355e59.jpg
---

## Keeping Windows' System Time Stable

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925473/19272" target="_top" id="1925473">
  <img src="//a.impactradius-go.com/display-ad/19272-1925473" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925473/19272" style="position:absolute;visibility:hidden;" border="0" />
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
6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134244/18498" target="_top" id="2134244">
  <img src="//a.impactradius-go.com/display-ad/18498-2134244" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134244/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2043638/7443" target="_top" id="2043638">
  <img src="//a.impactradius-go.com/display-ad/7443-2043638" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043638/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915830/19272" target="_top" id="1915830">
  <img src="//a.impactradius-go.com/display-ad/19272-1915830" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915830/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://discover-help.techidaily.com/mts-file-conversion-tutorial-simplified-guide/"><u>.MTS File Conversion Tutorial - Simplified Guide</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-make-every-minute-count-with-these-15-engaging-activities-while-listening-to-podcasts/"><u>[New] 2024 Approved Make Every Minute Count with These 15 Engaging Activities While Listening to Podcasts</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-10-best-no-cost-video-calls-for-remote-collaboration/"><u>[Updated] 2024 Approved 10 Best No-Cost Video Calls for Remote Collaboration</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-top-8-premium-and-gratis-mobile-video-mosaic-tools-for-android/"><u>[Updated] 2024 Approved Top 8 Premium & Gratis Mobile Video Mosaic Tools for Android</u></a></li>
<li><a href="https://unlock-android.techidaily.com/7-ways-to-unlock-a-locked-infinix-hot-30-5g-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Infinix Hot 30 5G Phone</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-unique-screencaps-for-win11/"><u>Crafting Unique Screencaps for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-error-0xc004f050-from-windows-update/"><u>Eliminating Error 0XC004F050 From Windows Update</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-startups-on-win11-the-ultimate-guide/"><u>Immediate Startups on Win11: The Ultimate Guide</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-nubia-red-magic-8s-propluswithwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Nubia Red Magic 8S Pro+with/without a PC</u></a></li>
<li><a href="https://driver-download.techidaily.com/intel-ac-3160-wifi-adapter-fast-simple-installation-guide/"><u>Intel AC 3160 WiFi Adapter: Fast, Simple Installation Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-enabling-startup-services/"><u>Mastering Windows 11: Enabling Startup Services</u></a></li>
<li><a href="https://win11.techidaily.com/microsofts-copilot-key-enhancing-productivity-with-windows-11/"><u>Microsoft's Copilot Key: Enhancing Productivity with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-non-synchronization-with-microsofts-to-do-app/"><u>Overcoming Non-Synchronization with Microsoft's To-Do App</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    