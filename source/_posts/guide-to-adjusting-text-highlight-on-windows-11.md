---
title: Guide to Adjusting Text Highlight on Windows 11
date: 2024-10-21T07:42:47.965Z
updated: 2024-10-27T07:24:57.562Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Adjusting Text Highlight on Windows 11
excerpt: This Article Describes Guide to Adjusting Text Highlight on Windows 11
keywords: WinHighlightTips,TextHighlighterWin,ColorAdjustWin,ThemeChangeGuide,AppearanceWindows,HighlightTextWin,FormattingControlWin
thumbnail: https://thmb.techidaily.com/8dc1e121faf37e853cf5b4a2c9e429100f4acf86a44ca231431cd5b1e8fdd239.jpg
---

## Guide to Adjusting Text Highlight on Windows 11

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

<!-- affiliate ads begin -->
<span id="1975636">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975636.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975636">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975636.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975636%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975636/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886015/19272" target="_top" id="1886015">
  <img src="//a.impactradius-go.com/display-ad/19272-1886015" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886015/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

## 3\. Turn Search Highlights On and Off in the Registry Editor

 Press **Win + R** to open the Windows Run dialog box, type **regedit** in the text box, and then hit the **Enter** key. Click **Yes** in the UAC prompt to finally launch the Registry Editor.

 Before you proceed, we recommend that you read our guide on [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). This may come in handy in case you accidentally break the Windows Registry.

 In the address bar of the Registry Editor, copy and paste the below text, and then press **Enter**:

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\SearchSettings`

 Right-click the **SearchSettings** key on the left side menu and select **New > DWORD (32-bit) Value** in the menu that appears. Then, name the value **IsDynamicSearchBoxEnabled**.

![creating a dword value in the Windows registry for the SearchSettings key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/creating-dword-windows-registry.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139107/17108" target="_top" id="2139107">
  <img src="//a.impactradius-go.com/display-ad/17108-2139107" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139107/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the right panel, double-click **IsDynamicSearchBoxEnabled** (the value you just created) and then enter **1** in the **Value data** text box to turn search highlights on. Then, click **OK** to apply the change.

![the IsDynamicSearchBoxEnabled value in the Registry Editor and Value data has been set to 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/editing-isdynamicsearchboxenabled-value-windows-registry.jpg)

 To turn search highlights off, enter **0** in the **Value data** text box, and then click **OK**.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484944/16446" target="_top" id="1484944">
  <img src="//a.impactradius-go.com/display-ad/16446-1484944" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484944/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Control Your Search Highlights on Windows 11

 Windows 11 being customizable is what makes interacting with the OS enjoyable. The power is in your hands whether you want to see search highlights or not in Windows Search. And now you know three ways to enable or disable them.

 So, keep on reading to find out three ways to turn search highlights on and off.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/he-next-level-of-collaboration-youtubes-elite-meetups/"><u>[New] The Next Level of Collaboration Youtube's Elite Meetups</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-best-mobile-animation-tools-free-3d-apps-for-android-and-ios/"><u>In 2024, Best Mobile Animation Tools Free 3D Apps for Android and iOS</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-samsung-galaxy-s23plus-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location On Facebook Dating for your Samsung Galaxy S23+ | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-honor-x9b-drfone-by-drfone-virtual-android/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Honor X9b | Dr.fone</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/in-2024-ultimate-guide-to-convert-srt-to-txt-in-minutes/"><u>In 2024, Ultimate Guide to Convert SRT to TXT in Minutes</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/is-photoshops-shake-control-a-game-changer-in-2024/"><u>Is Photoshop's Shake Control a Game Changer, In 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-the-fcp-factor-10-blockbuster-movies-edited-with-final-cut-pro/"><u>New The FCP Factor 10 Blockbuster Movies Edited with Final Cut Pro</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-converting-your-videos-from-vimeo-to-mov-format-on-windows/"><u>Quick Guide: Converting Your Videos From Vimeo to MOV Format on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-google-drive-file-downloads-top-14-solutions/"><u>Resolving 'Google Drive File Downloads' - Top 14 Solutions</u></a></li>
<li><a href="https://solve-outstanding.techidaily.com/ripristina-i-tuoi-download-eliminati-di-windows-1011-una-guida-completa/"><u>Ripristina I Tuoi Download Eliminati Di Windows 10/11: Una Guida Completa</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-mov-to-mp4-transformation-top-video-converters-reviewed/"><u>Seamless MOV to MP4 Transformation: Top Video Converters Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-converting-psp-pmf-movies-into-high-quality-mp4-format-with-sound/"><u>Step-by-Step Guide to Converting PSP PMF Movies Into High-Quality MP4 Format With Sound</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-setting-up-the-au-addon-for-iptv-streaming-in-kodi-with-over-30-australian-free-tv-channel-options/"><u>Step-by-Step Guide: Setting Up the AU Addon for IPTV Streaming in Kodi with Over 30 Australian Free TV Channel Options</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-shrinking-flac-file-size-without-losing-quality/"><u>Step-by-Step Guide: Shrinking FLAC File Size Without Losing Quality</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-transforming-mkv-files-into-avi-format-with-premium-quality-offline-and-online-methods/"><u>Step-by-Step Guide: Transforming MKV Files Into AVI Format with Premium Quality Offline & Online Methods</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    