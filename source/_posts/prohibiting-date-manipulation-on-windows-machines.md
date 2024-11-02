---
title: Prohibiting Date Manipulation on Windows Machines
date: 2024-10-28T20:44:53.672Z
updated: 2024-11-01T18:38:04.312Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Prohibiting Date Manipulation on Windows Machines
excerpt: This Article Describes Prohibiting Date Manipulation on Windows Machines
keywords: Anti-Date Tampering (Windows),Windows Date Integrity,Prevent Data Alteration,Secure Windows Timestamps,Stop Time Manipulation,Windows System Security,Protect OS Dates
thumbnail: https://thmb.techidaily.com/5599db5b0351dfe7fe4d3ef01a51b823176684e86c63c43fb2d60eaab80af0aa.jpg
---

## Prohibiting Date Manipulation on Windows Machines

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918698/19272" target="_top" id="1918698">
  <img src="//a.impactradius-go.com/display-ad/19272-1918698" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918698/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135412/19272" target="_top" id="2135412">
  <img src="//a.impactradius-go.com/display-ad/19272-2135412" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135412/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394">
  <img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135374/19272" target="_top" id="2135374">
  <img src="//a.impactradius-go.com/display-ad/19272-2135374" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135374/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-crafting-compelling-content-on-reddit-a-stepwise-path/"><u>[Updated] In 2024, Crafting Compelling Content on Reddit - A Stepwise Path</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-mastering-the-art-of-insta-top-gadgets-for-success/"><u>[Updated] In 2024, Mastering the Art of Insta Top Gadgets for Success</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-learn-efficient-techniques-for-clearing-backdrop-in-figma-for-2024/"><u>[Updated] Learn Efficient Techniques for Clearing Backdrop In Figma for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-off-switch-for-instagrams-igtv/"><u>2024 Approved Off Switch for Instagram's IGTV</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-the-barrier-between-you-and-your-browsers-content/"><u>Breaking the Barrier Between You and Your Browser's Content</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-the-gap-between-wired-and-wi-fi-on-your-windows-11-machine/"><u>Bridge the Gap Between Wired and Wi-Fi on Your Windows 11 Machine</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-break-restoring-server-connection-in-obs-on-pc/"><u>Bridging the Break: Restoring Server Connection in OBS on PC</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-divide-restoring-your-remote-network-connection/"><u>Bridging The Divide: Restoring Your Remote Network Connection</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-broadband-speed-top-7-windows-11-solutions/"><u>Bring Back Broadband Speed: Top 7 Windows 11 Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-boundaries-instantly-access-windows-terminal-admin-mode/"><u>Bypass Boundaries: Instantly Access Windows Terminal, Admin Mode</u></a></li>
<li><a href="https://win11.techidaily.com/capturing-your-windows-world-tool-tally-of-the-capture-titans/"><u>Capturing Your Windows World: Tool Tally of the Capture Titans</u></a></li>
<li><a href="https://win11.techidaily.com/check-if-your-pc-meets-windows-11-criteria/"><u>Check If Your PC Meets Windows 11 Criteria</u></a></li>
<li><a href="https://win11.techidaily.com/clarifying-windows-tools-what-makes-wintoolss-chkdsk-unique/"><u>Clarifying Windows Tools: What Makes WinTools's CHKDSK Unique?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/fixing-the-issue-when-video-is-not-displayed-in-fullscreen-mode-on-various-devices/"><u>Fixing the Issue When Video Is Not Displayed in Fullscreen Mode on Various Devices</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/high-end-humor-scripts/"><u>High-End Humor Scripts</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-locked-iphone-13-pro-by-restoring-it-to-factory-settings-by-drfone-ios-unlock-ios-unlock/"><u>How to Unlock locked iPhone 13 Pro by restoring it to factory settings</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/in-2024-viral-video-champions-the-shortlist-of-100plus-million-viewers-by-24/"><u>In 2024, Viral Video Champions The Shortlist of 100+ Million Viewers by '24</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-premier-top-ten-creative-av-media-maker-directory-for-2024/"><u>The Premier Top-Ten Creative Av Media Maker Directory for 2024</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/transitioning-from-nursing-to-technology-a-comprehensive-guide/"><u>Transitioning From Nursing to Technology: A Comprehensive Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    