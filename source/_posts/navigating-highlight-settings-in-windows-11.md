---
title: Navigating Highlight Settings in Windows 11
date: 2024-06-25T11:33:40.874Z
updated: 2024-06-26T11:33:40.874Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Highlight Settings in Windows 11
excerpt: This Article Describes Navigating Highlight Settings in Windows 11
keywords: Win11 Highlight Controls,Windows 11 Theme Editing,Adjusting Windows Colors,Changing Display Features,Windows Color Settings Guide,Master Window's Appearance,Tailor Windows UI Brightness
thumbnail: https://thmb.techidaily.com/095ce3d3eacef166f46f59459d5ef71a92a706285f3160a9b70eb170ae6406f1.jpg
---

## Navigating Highlight Settings in Windows 11

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

 You should no longer see search lights now.

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

## 3\. Turn Search Highlights On and Off in the Registry Editor

 Press **Win + R** to open the Windows Run dialog box, type **regedit** in the text box, and then hit the **Enter** key. Click **Yes** in the UAC prompt to finally launch the Registry Editor.

 Before you proceed, we recommend that you read our guide on [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). This may come in handy in case you accidentally break the Windows Registry.

 In the address bar of the Registry Editor, copy and paste the below text, and then press **Enter**:

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\SearchSettings`

 Right-click the **SearchSettings** key on the left side menu and select **New > DWORD (32-bit) Value** in the menu that appears. Then, name the value **IsDynamicSearchBoxEnabled**.

![creating a dword value in the Windows registry for the SearchSettings key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/creating-dword-windows-registry.jpg)

 In the right panel, double-click **IsDynamicSearchBoxEnabled** (the value you just created) and then enter **1** in the **Value data** text box to turn search highlights on. Then, click **OK** to apply the change.

![the IsDynamicSearchBoxEnabled value in the Registry Editor and Value data has been set to 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/editing-isdynamicsearchboxenabled-value-windows-registry.jpg)

 To turn search highlights off, enter **0** in the **Value data** text box, and then click **OK**.

## Control Your Search Highlights on Windows 11

 Windows 11 being customizable is what makes interacting with the OS enjoyable. The power is in your hands whether you want to see search highlights or not in Windows Search. And now you know three ways to enable or disable them.

 So, keep on reading to find out three ways to turn search highlights on and off.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/rectifying-not-an-empty-directory-error-code-0x80070091-in-win11-and-11/"><u>Rectifying Not an Empty Directory Error Code 0X80070091 in Win11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-accessing-cloud-drives-from-windows-drive-letters/"><u>Effortlessly Accessing Cloud Drives: From Windows Drive Letters</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-overcoming-file-access-barriers-using-powershell/"><u>Efficiently Overcoming File Access Barriers Using PowerShell</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-microsoft-store-access-on-windows-11/"><u>Troubleshooting Microsoft Store Access on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unrecognizable-hardware-in-windows-1011/"><u>Overcoming Unrecognizable Hardware in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-dont-make-these-top-8-mistakes/"><u>Mastering Windows 11: Don't Make These Top 8 Mistakes</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-system-restore-a-windows-11-perspective/"><u>Mastery Over System Restore: A Windows 11 Perspective</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-and-repairing-windows-enter-key-issues/"><u>Diagnosing and Repairing Windows Enter Key Issues</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-visibility-in-windows-network-guard-area/"><u>Mastery over Visibility in Windows' Network Guard Area</u></a></li>
<li><a href="https://youtube-web.techidaily.com/lent-7-dslrs-elevating-live-stream-cinematic-style-for-2024/"><u>Excellent 7 DSLRs Elevating Live-Stream Cinematic Style for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-unlocking-wealth-through-instagrams-revenue-avenues/"><u>In 2024, Unlocking Wealth Through Instagram's Revenue Avenues</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-creating-an-audio-visual-harmony-integrating-music-into-videos/"><u>In 2024, Creating an Audio-Visual Harmony Integrating Music Into Videos</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-transform-your-content-the-science-of-instagram-video-loops/"><u>[New] 2024 Approved  Transform Your Content  The Science of Instagram Video Loops</u></a></li>
<li><a href="https://some-tips.techidaily.com/top-20-unrestricted-zero-cost-pubg-snapshits-for-2024/"><u>Top 20 Unrestricted, Zero-Cost PUBG Snapshits for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-from-photos-to-film-creating-a-professional-slideshow-with-final-cut-pro-for-2024/"><u>New From Photos to Film Creating a Professional Slideshow with Final Cut Pro for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-growth-galore-farming-game-classics-revisited/"><u>In 2024, Growth Galore  Farming Game Classics Revisited</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-experts-guide-quick-removal-of-your-youtube-comments/"><u>2024 Approved  The Expert's Guide  Quick Removal of Your Youtube Comments</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-asus-rog-phone-7-get-deleted-photos-back-with-ease-and-safety-by-fonelab-android-recover-photos/"><u>How to Asus ROG Phone 7 Get Deleted photos Back with Ease and Safety?</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-premier-platform-pictograms-captivating-evolve/"><u>[Updated] Premier Platform Pictograms  Captivating Evolve</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>