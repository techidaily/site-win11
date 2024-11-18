---
title: Strategies to Maintain Windows Time Settings
date: 2024-11-12T20:51:55.006Z
updated: 2024-11-18T01:33:52.245Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies to Maintain Windows Time Settings
excerpt: This Article Describes Strategies to Maintain Windows Time Settings
keywords: Windows Time Controls,Setting Windows Clock,Update Time on Windows,Windows Date Adjustment,Set PC Time Windows,Correct Windows Timing,Manage Windows Schedule
thumbnail: https://thmb.techidaily.com/efe03172267db8e41dde950b174798601940a22588399da557fc77a3f3ce0d36.jpeg
---

## Strategies to Maintain Windows Time Settings

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134489/18498" target="_top" id="2134489">
  <img src="//a.impactradius-go.com/display-ad/18498-2134489" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134489/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://imp.i357552.net/c/5597632/1061528/11832" target="_top" id="1061528">
  <img src="//a.impactradius-go.com/display-ad/11832-1061528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1061528/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885932/19272" target="_top" id="1885932">
  <img src="//a.impactradius-go.com/display-ad/19272-1885932" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885932/19272" style="position:absolute;visibility:hidden;" border="0" />
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

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105873/7443" target="_top" id="2105873">
  <img src="//a.impactradius-go.com/display-ad/7443-2105873" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105873/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-perfecting-cinematography-for-reddit-amas/"><u>[Updated] In 2024, Perfecting Cinematography for Reddit AMAs</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-top-picks-for-superior-nintendo-switch-gaming/"><u>[Updated] Top Picks for Superior Nintendo Switch Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-errors-fixing-failed-windows-mmc-snap-creation/"><u>Demystifying Errors: Fixing Failed Windows MMC Snap Creation</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/from-mobile-to-tv-mastering-the-setup-of-disney-plus-streaming-through-chromecast/"><u>From Mobile to TV: Mastering the Setup of Disney + Streaming Through Chromecast</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-lava-blaze-curve-5g-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Lava Blaze Curve 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-stop-and-fix-a-frozen-spotify-on-windows-11/"><u>How to Stop and Fix a Frozen Spotify on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-black-screens-in-windows-based-gameplay/"><u>Overcoming Black Screens in Windows-Based Gameplay</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-xiaomi-redmi-13c-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Xiaomi Redmi 13C Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/silencing-google-chrome-on-your-windows-machine/"><u>Silencing Google Chrome on Your Windows Machine</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-disabling-fake-security-warnings-from-chrome/"><u>Steps for Disabling Fake Security Warnings From Chrome</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/stepwise-instructions-preserve-your-memories-by-uploading-to-snapchat/"><u>Stepwise Instructions Preserve Your Memories by Uploading to Snapchat</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-excessive-memory-demand-from-microsofts-edge/"><u>Troubleshooting Excessive Memory Demand From Microsoft's Edge</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-the-best-of-both-worlds-video-editing-apps-with-music-for-android-and-iphone-users/"><u>Updated In 2024, The Best of Both Worlds Video Editing Apps with Music for Android and iPhone Users</u></a></li>
<li><a href="https://win11.techidaily.com/win-free-up-space-expert-guide-to-erase-temp-files/"><u>Win-Free Up Space: Expert Guide to Erase Temp Files</u></a></li>
<li><a href="https://win-studio.techidaily.com/1728491029038-windows/"><u>Windows系統下還原被損壞或丟失的分割區資料：選擇最高效的軟件</u></a></li>
</ul></div>

