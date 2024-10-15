---
title: Ensuring True Windows Time & Date Configuration
date: 2024-10-12T16:35:23.673Z
updated: 2024-10-15T19:37:05.316Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ensuring True Windows Time & Date Configuration
excerpt: This Article Describes Ensuring True Windows Time & Date Configuration
keywords: Windows Time Accuracy,Precise Windoze Clock,Validate WinTimeSync,Correct Windows Time Setup,Authenticate True DateTime,Ensure Correct WINDOWS Date,Verify True Windows Time
thumbnail: https://thmb.techidaily.com/5ef4b9be2cc03e1f5bba8134aa6b00b2355f4bf8946df71748d869f7b05769b2.jpg
---

## Ensuring True Windows Time & Date Configuration

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136615/26400" target="_top" id="2136615">
  <img src="//a.impactradius-go.com/display-ad/26400-2136615" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136615/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aidotcom.pxf.io/c/5597632/2129041/19576" target="_top" id="2129041">
  <img src="//a.impactradius-go.com/display-ad/19576-2129041" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129041/19576" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2037334/7443" target="_top" id="2037334">
  <img src="//a.impactradius-go.com/display-ad/7443-2037334" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037334/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098701/14409" target="_top" id="2098701">
  <img src="//a.impactradius-go.com/display-ad/14409-2098701" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098701/14409" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-tips.techidaily.com/ed-decoding-monetization-how-much-creators-earn-per-ad-on-youtube-for-2024/"><u>[Updated] Decoding Monetization How Much Creators Earn Per Ad on YouTube for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-compreranimal-webcam-tutorial-achieve-excellent-video-quality/"><u>[Updated] In 2024, Compreranimal Webcam Tutorial Achieve Excellent Video Quality</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-ultimate-ps4-recording-in-obs-a-detailed-walkthrough/"><u>[Updated] In 2024, Ultimate PS4 Recording in OBS - A Detailed Walkthrough</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-master-multi-screen-video-streaming-with-microsoft-edges-pip/"><u>2024 Approved Master Multi-Screen Video Streaming with Microsoft Edge's PIP</u></a></li>
<li><a href="https://blog-min.techidaily.com/windows-cuil-free-full-version3264/"><u>如何无缝下载Windows Cuil-Free Full Version：32位与64位比较介绍</u></a></li>
<li><a href="https://video-capture.techidaily.com/direct-mac-pics-to-a-new-saving-area/"><u>Direct Mac Pics to a New Saving Area</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-unclog-printer-usage-jams-in-win11/"><u>Guide to Unclog Printer Usage Jams in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-isdonedll-isarcextract-error-in-windows-10-and-11/"><u>How to Fix the ISDone.dll (ISArcExtract) Error in Windows 10 & 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/professionals-drone-guide-top-5-recommendations-inside/"><u>Professionals’ Drone Guide - Top 5 Recommendations Inside</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-wsl-the-4294967295-error-explained/"><u>Resolving WSL: The 4294967295 Error Explained</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-resolving-system-call-failures-in-windows-11/"><u>Troubleshooting: Resolving System Call Failures in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/unwanted-restart-alert-how-to-prevent-your-pc-from-starting-up-solo-windows-11/"><u>Unwanted Restart Alert: How to Prevent Your PC From Starting Up Solo (Windows 11)</u></a></li>
</ul></div>

