---
title: Navigating & Controlling Highlight on Windows 11
date: 2024-09-10T09:18:43.207Z
updated: 2024-09-16T17:51:48.000Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating & Controlling Highlight on Windows 11
excerpt: This Article Describes Navigating & Controlling Highlight on Windows 11
keywords: Win11 Highlighter Control,Windows Highlight Management,Highlight Navigation W11,PC Highlight Settings,Manage Windows Highlight,Highlight Functions W11,Window's Highlight Toolkit
thumbnail: https://thmb.techidaily.com/775033cec734e193d493811f769dcaa65d428fba2286e40a488d59f8b08228ae.png
---

## Navigating & Controlling Highlight on Windows 11

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115927/19272" target="_top" id="2115927">
  <img src="//a.impactradius-go.com/display-ad/19272-2115927" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115927/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Control Your Search Highlights on Windows 11

 Windows 11 being customizable is what makes interacting with the OS enjoyable. The power is in your hands whether you want to see search highlights or not in Windows Search. And now you know three ways to enable or disable them.

 So, keep on reading to find out three ways to turn search highlights on and off.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-learn-how-to-mute-instagram-recommendations/"><u>[New] In 2024, Learn How to Mute Instagram Recommendations</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-best-script-writing-website/"><u>[Updated] Best Script Writing Website</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-the-essential-iphone-screen-recording-manual/"><u>[Updated] The Essential iPhone Screen Recording Manual</u></a></li>
<li><a href="https://win11.techidaily.com/guide-steps-for-transferring-films-onto-your-portable-usb-flash-drive/"><u>Guide: Steps for Transferring Films Onto Your Portable USB Flash Drive</u></a></li>
<li><a href="https://win11.techidaily.com/how-does-handbrake-enable-video-rotation-and-flipping-techniques/"><u>How Does Handbrake Enable Video Rotation and Flipping Techniques?</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-hp-laptop-camera-not-working-in-windows-10/"><u>How To Fix HP Laptop Camera Not Working In Windows 10</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-samsung-galaxy-a05s-drfone-by-drfone-android/"><u>In 2024, How To Use Allshare Cast To Turn On Screen Mirroring On Samsung Galaxy A05s | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/inside-the-directors-cut-a-complete-review-of-powerdirector-2024/"><u>Inside the Director’s Cut A Complete Review of PowerDirector 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-dvd-ripping-for-pcs-and-macs-comprehensive-step-by-step-instructions/"><u>Mastering the Art of DVD Ripping for PCs & Macs: Comprehensive Step-by-Step Instructions</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-windowsgif/"><u>Microsoft Windowsインターフェース内で簡単に動く画像(GIF)を制作するためのガイド</u></a></li>
<li><a href="https://win11.techidaily.com/oggm4a/"><u>Ogg形式へのM4Aファイル変換手順</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/quick-glance-fastest-photo-viewer-in-11-os-for-2024/"><u>Quick Glance Fastest Photo Viewer in 11 OS for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/step-by-step-guide-to-maximizing-your-roi-on-spotify-ads-for-2024/"><u>Step-by-Step Guide to Maximizing Your ROI on Spotify Ads for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/iuodkplusodhplusocquobruocsoodroodvoocueocseodvoodqpluswkieapmpluswfpemwgdog44gz44g544gm44gr5b2556ul44gk55m96bus5yyw5pa55rovig/"><u>ビデオのグレースケール変換入門: すべてに役立つ白黒化方法</u></a></li>
</ul></div>

