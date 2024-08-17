---
title: "Guide: Dealing with Invalid App Installs on Windows"
date: 2024-08-15T23:52:24.183Z
updated: 2024-08-16T23:52:24.183Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Guide: Dealing with Invalid App Installs on Windows"
excerpt: "This Article Describes Guide: Dealing with Invalid App Installs on Windows"
keywords: Invalid Windows Install Guide,Windows Invalid Apps Fix,Addressing Invalid iOS Installs,Managing Android Invalid Purchases,Troubleshoot Windows Invalid Sign-Ins,Resolving Inappropriate Windows Downloads,Preventing Fake Windows Installs
thumbnail: https://thmb.techidaily.com/fed3ffae9229ff3a7d3580519bb324f0e6bad8a6cd96fa55cbded24321f049a3.jpg
---

## Guide: Dealing with Invalid App Installs on Windows

 Have you encountered the error"the app you're trying to install isn't a Microsoft-verified app"while installing an app? The error occurs if you have configured your system to only install apps from the Microsoft Store. You could have set this permission on purpose, or it might have been set by default.

 Other than that, a corrupted Microsoft Store cache, installing an app from an unofficial source, and enabling Windows S mode can also cause the error. Below, you will find a few checks and fixes you should apply to resolve the error and install the app successfully.

## 1\. Install the App From the Microsoft Store

 Considering you get the error when downloading apps outside the Microsoft Store, it makes sense to first check if the same app is available there. If the app is available, you can download it from there, and there won't be any need to go through advanced troubleshooting.

 Therefore, [open the Microsoft Store](https://www.makeuseof.com/windows-open-microsoft-store/) and search for the app. If you find the app in the store, click the **Get** button to install it. However, if the app isn't available in the store and can only be downloaded from another source, ensure it is safe to download.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Make Sure the App You're Downloading Is Safe

 Microsoft doesn't allow untrusted publishers to list their apps on the Microsoft Store. If you haven't found the app on the store, it could be unsafe and infect your computer. Thus, ensure that the app you want to download is secure before downloading.

 To determine if an app is safe, copy its download link and paste it into [VirusTotal's URL search box](https://www.virustotal.com/gui/home/url). After that, press **Enter**.

![Check the Authenticity of a Software by Entering its URL in VirusTotal’s Official Website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/1-check-the-authenticity-of-a-software-by-entering-its-url-in-virustotal-s-official-website.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->

 If the scanner doesn't find any problems with the download link, it's probably safe. After ensuring that, you can apply the remaining fixes to enable app installation outside the store.

## 3\. Change the Operating System App Settings

 Microsoft cares about the safety and security of its Windows users. To facilitate that, Windows offers a feature that blocks the installation of apps outside the Microsoft Store. The downside of enabling this feature is that it prevents users from installing popular and safe applications from the web.

 When users try to install an app with this restriction turned on, Windows will likely display an error message saying that the app isn't a Microsoft-verified app. Therefore, to avoid encountering the error described above, you should allow Windows to install apps outside the Microsoft Store.

 To modify the app permissions on Windows 10, follow the steps below:

1. Open the **Settings** app.
2. Open **Apps** settings and select **Apps and Features** from the left sidebar.
3. Select **Anywhere** from the dropdown menu under **Choose where to get apps**.

 To modify app permissions on Windows 11, open the **Settings** app, select the **Apps** tab, and then go to **Advanced app settings**.

![Go to Advanced Apps Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/2-go-to-advanced-apps-settings-in-windows-settings-app.jpg)

 Select **Anywhere** from the dropdown menu next to **Choose where to get apps**.

![Select Anywhere From the Dropdown Menu Next to Choose Where to Get Apps Option in Apps Settings in Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/3-select-anywhere-from-the-dropdown-menu-next-to-choose-where-to-get-apps-option-in-apps-settings-in-windows-settings-app.jpg)

## 4\. Turn Off the App Install Control Policy

 The App Install Control is a Microsoft Defender SmartScreen feature that prevents users from installing apps outside the Microsoft Store. It does this to prevent users from infecting their devices with third-party applications.

 Therefore, you should turn off this feature to remove any restrictions. To turn it off, follow these steps:

1. Open the Local Group Policy Editor. To do this, check out [how to open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) if you're not using Windows Home edition, and learn [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) if you are.
2. Navigate to **Computer Configuration > Administrative Templates > Windows Components > Windows Defender SmartScreen > Explorer**.  
![Go to Explorer Folder by Navigating to the Path in Windows Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/4-go-to-explorer-folder-by-navigating-to-the-path-in-windows-local-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Open the policy for **Configure App Install Control**.
4. Select **Disabled** to turn off this feature.  
![Disable the Policy for Configure App Install Control in Windows Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/5-disable-the-policy-for-configure-app-install-control-in-windows-local-group-policy-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Change the App Install Control Permission in the Registry Editor

 To modify the App Install Control permissions via the Registry Editor, follow the below steps:

1. Open the Registry Editor.
2. Navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer**.  
![Go to Explorer Folder by Navigating to the Path in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/6-go-to-explorer-folder-by-navigating-to-the-path-in-windows-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Right-click on **Explorer** and select **New > String value**.  
![Create New String Value in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/7-create-new-string-value-in-windows-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Name this new value **"AicEnabled."**  
![Name the Newly Created String Value AicEnabled in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/8-name-the-newly-created-string-value-aicenabled-in-windows-registry-editor.jpg)
5. Double-click on the newly created string and type "**Anywhere"** in the **Value data** field.  
![Type Anywhere in the Value Data Field of Newly Created String in Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/9-type-anywhere-in-the-value-data-field-of-newly-created-string-in-windows-registry-editor.jpg)
6. Restart the computer for the changes to take effect.

 If the above Registry tweak does not resolve the issue, turn off S mode.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Disable Windows S Mode

 Windows S mode is primarily the most secure environment you can get in Windows. It mainly serves as a means of protecting your children and keeping sensitive documents away from prying eyes.

 When this mode is active, users can only download apps from the Microsoft Store, can't use the command line or code editors, and can't modify the Windows Registry Editor.

 Therefore, if you have recently bought a new device and this mode is enabled there by default, Windows will probably throw the error if you attempt to install any app outside the store. Therefore, you should make sure it isn't enabled and disable it if it is.

 To determine whether your device is running S mode, open the **Settings** app, select the **System** tab on the left, and open the **About** page.

 If the S mode is enabled on your device, you'll see it there. If the feature is active, turn it off by following these steps:

1. Open the **Settings** app.
2. Navigate to the **System** tab and go to **Activation**.
3. Click on **Go to the store** under **Switch to Windows 11 Home/Pro**, which will take you to the Microsoft Store page where you can opt out of S mode.
4. Click the **Get** button and follow the on-screen instructions to get out of S mode.

## 7\. Run the Windows Store Apps Troubleshooter

 If the Windows S mode isn't enabled, and you haven't restricted your operating system from downloading apps from outside Microsoft, the error could be caused by an underlying issue with the Microsoft Store. To ensure this is not the case, you should run the Windows Store Apps troubleshooter, which is a built-in tool for troubleshooting issues with the Store.

 If you've never run the troubleshooter before, refer to our guide on [how to run a troubleshooter on Windows 10 or 11](https://www.makeuseof.com/run-troubleshooter-windows-10-11/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## Successfully Install Third-Party Applications Again on Windows

 Microsoft blocks the installation of third-party apps for your security, but it's pointless if it prevents you from installing vital apps. Hopefully, you now better understand why the Microsoft Store presents the "the app you're trying to install isn't a Microsoft-verified app" error. Following the fixes above will enable you to download the apps from unofficial sources.

 Have you encountered the error"the app you're trying to install isn't a Microsoft-verified app"while installing an app? The error occurs if you have configured your system to only install apps from the Microsoft Store. You could have set this permission on purpose, or it might have been set by default.

 Other than that, a corrupted Microsoft Store cache, installing an app from an unofficial source, and enabling Windows S mode can also cause the error. Below, you will find a few checks and fixes you should apply to resolve the error and install the app successfully.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-deciding-on-live-stream-software-streamlabs-vs-obs-comparison/"><u>[New] 2024 Approved  Deciding on Live Stream Software  Streamlabs Vs. OBS Comparison</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-from-camera-roll-to-screen-share-photos-fast-and-simple/"><u>[New] In 2024, From Camera Roll to Screen  Share Photos Fast and Simple</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-youtube-ad-revenue-how-much-do-youtubers-make-per-ad-in-2024/"><u>[New] YouTube Ad Revenue  How Much Do YouTubers Make Per Ad, In 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-2024-approved-make-memories-not-videos-top-10-buzz-creating-tiktok-hacks/"><u>[Updated] 2024 Approved  Make Memories, Not Videos!  Top 10 Buzz-Creating TikTok Hacks</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-mastering-instagram-the-art-of-rewinding-videos/"><u>[Updated] 2024 Approved  Mastering Instagram  The Art of Rewinding Videos</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-satirists-web-workshop/"><u>[Updated] Satirist's Web Workshop</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-top-3-voice-capturing-ipad-apps-reviewed-for-2024/"><u>[Updated] TOP 3 Voice Capturing iPad Apps Reviewed for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-top-picks-for-your-android-the-current-best-facebook-videos-downloaders-ranked-for-2024/"><u>[Updated] Top Picks for Your Android - The Current Best Facebook Videos Downloaders Ranked for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-battle-of-broadcasting-go-live-with-obstwitch/"><u>2024 Approved  Battle of Broadcasting  Go Live with OBS/Twitch</u></a></li>
<li><a href="https://win11.techidaily.com/5-key-strategies-for-overcoming-onedrive-errors/"><u>5 Key Strategies for Overcoming OneDrive Errors</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-fixing-discrepancies-in-to-do-app/"><u>A Comprehensive Guide to Fixing Discrepancies in To-Do App</u></a></li>
<li><a href="https://win11.techidaily.com/a-journey-into-celestial-mastery-windows-11s-divine-control/"><u>A Journey Into Celestial Mastery: Windows 11'S Divine Control</u></a></li>
<li><a href="https://win11.techidaily.com/a-tri-method-approach-to-understanding-and-applying-windows-policies/"><u>A Tri-Method Approach to Understanding and Applying Windows Policies</u></a></li>
<li><a href="https://win11.techidaily.com/a-windows-users-guide-for-web-site-app-conversion/"><u>A Windows User's Guide for Web Site App Conversion</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-system32-folder-on-windows-11/"><u>Accessing System32 Folder on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/activating-prints-with-secure-browsing-feature-edge/"><u>Activating Prints with Secure Browsing Feature (Edge)</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-discreprancies-in-power-usage-display-for-win-11-systems/"><u>Addressing Discreprancies in Power Usage Display for Win 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-high-memory-usage-by-microsoft-edge-webview2/"><u>Addressing High-Memory Usage by Microsoft Edge WebView2</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-empty-directory-issue-in-windows-11-error-0x80070091/"><u>Addressing Non-Empty Directory Issue in Windows 11: Error #0X80070091</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unclickable-elements-in-the-new-os/"><u>Addressing Unclickable Elements in the New OS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-ms-store-error-x7326/"><u>Addressing Windows 11 MS Store Error X7326</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-taskbar-latency-issues/"><u>Addressing Windows 11 Taskbar Latency Issues</u></a></li>
<li><a href="https://tech-hub.techidaily.com/analyzing-ais-sentiment-sages-dissecting-gpt-and-bert/"><u>Analyzing AI's Sentiment Sages: Dissecting GPT & BERT</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-blunders-proper-techniques-for-file-explorer-use/"><u>Avoiding Blunders: Proper Techniques for File Explorer Use</u></a></li>
<li><a href="https://extra-resources.techidaily.com/best-practices-in-apple-podcast-file-formatting/"><u>Best Practices in Apple Podcast File Formatting</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-with-these-8-window-study-secrets/"><u>Boost Productivity with These 8 Window Study Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-in-remote-steam-functionality/"><u>Breaking Barriers in Remote Steam Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-platforms-windows-now-on-apples-ios-and-microsoft-devices/"><u>Bridging Platforms: Windows Now on Apple's iOS and Microsoft Devices</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-frozen-windows-pin-with-easy-fixes/"><u>Bypass Frozen Windows Pin with Easy Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-obstacles-quick-fixes-for-stuck-windows-apps/"><u>Bypass Obstacles: Quick Fixes for Stuck Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-httptoomanyreq-error-quick-fixes-for-app-overloads/"><u>Bypassing HTTP_TOO_MANY_REQ Error: Quick Fixes for App Overloads</u></a></li>
<li><a href="https://win11.techidaily.com/cant-sign-into-onedrive-on-windows-try-these-fixes/"><u>Can't Sign Into OneDrive on Windows? Try These Fixes</u></a></li>
<li><a href="https://article-helps.techidaily.com/captivating-copy-creator-pro-for-2024/"><u>Captivating Copy Creator Pro for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/capture-notes-effortlessly-on-windows-11/"><u>Capture Notes Effortlessly on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/character-inspection-the-win11-way/"><u>Character Inspection: The Win11 Way</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-failed-to-launch-errors-with-your-pcs-display/"><u>Clearing Up “Failed to Launch” Errors with Your PC’s Display</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-dual-windows-devices-with-ms-error/"><u>Clearing Up Dual Windows Devices with MS Error</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-iomap64-blue-screen-of-death-issues-quickly/"><u>Clearing Up IOMap64 Blue Screen of Death Issues Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-the-stuck-gpsvc-delay-mystery/"><u>Clearing Up the Stuck GPSVC Delay Mystery</u></a></li>
<li><a href="https://win11.techidaily.com/code-of-shadows-mastering-invisibles-in-win11/"><u>Code of Shadows: Mastering Invisibles in Win11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-pictures-files-on-itel-by-fonelab-android-recover-pictures/"><u>Complete guide for recovering pictures files on Itel .</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/create-captivate-independent-animation-innovations/"><u>Create, Captivate  Independent Animation Innovations</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-samsung-galaxy-f14-5gwithwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Samsung Galaxy F14 5Gwith/without a PC</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-icloud-from-iphone-12-smoothly-by-drfone-ios/"><u>How To Remove iCloud From iPhone 12 Smoothly</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-realme-note-50-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-innovative-water-world-leading-game-experience-hits/"><u>In 2024, Innovative Water World  Leading Game Experience Hits</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-blueprint-for-on-screen-dialogues/"><u>In 2024, The Blueprint for On-Screen Dialogues</u></a></li>
<li><a href="https://win11.techidaily.com/1719328295929-reduce-or-increase-software-size-on-windows-11-the-easy-way/"><u>Reduce or Increase Software Size on Windows 11 – The Easy Way!</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-repairing-disconnected-or-unresponsive-windows-media-files/"><u>Step-by-Step Guide: Repairing Disconnected or Unresponsive Windows Media Files</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/techniques-to-reclaim-your-exclusive-snaps-for-2024/"><u>Techniques to Reclaim Your Exclusive Snaps for 2024</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-steps-when-armored-core-vi-wont-start/"><u>Troubleshooting Steps When Armored Core VI Won't Start</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlocking-made-easy-the-best-10-apps-for-unlocking-your-samsung-galaxy-f14-5g-device-by-drfone-android/"><u>Unlocking Made Easy The Best 10 Apps for Unlocking Your Samsung Galaxy F14 5G Device</u></a></li>
<li><a href="https://win11.techidaily.com/1719364992381-unraveling-windows-11-writable-error-fix-it-now/"><u>Unraveling Windows 11' Writable Error: Fix It Now!</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-discover-the-best-free-and-paid-subtitle-edit-alternatives-for-mac/"><u>Updated 2024 Approved Discover the Best Free and Paid Subtitle Edit Alternatives for Mac</u></a></li>
<li><a href="https://hardware-help.techidaily.com/upgrade-to-new-steelseries-driver-for-enhanced-performance/"><u>Upgrade to New SteelSeries Driver for Enhanced Performance</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/1715701104836-zombification-extravaganza-8-epic-titles-ranked/"><u>Zombification Extravaganza - 8 Epic Titles Ranked!</u></a></li>
</ul></div>
