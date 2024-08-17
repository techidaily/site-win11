---
title: Accessing Invisible Icons Menu on Modern Windows 11
date: 2024-08-15T23:47:24.589Z
updated: 2024-08-16T23:47:24.589Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Accessing Invisible Icons Menu on Modern Windows 11
excerpt: This Article Describes Accessing Invisible Icons Menu on Modern Windows 11
keywords: Win11 Invisible Menu Access,Modern PC Icon View,Windows 11 Hidden Icons,Navigate Win11 Settings,Icon Menus in Win11,Unlocking Win11 UI,Mastering Win11 Controls
thumbnail: https://thmb.techidaily.com/7bb5cd6c098dcc354a1616a8cf729a503ba552ba0d30358349d319e43f0bdaa3.jpg
---

## Accessing Invisible Icons Menu on Modern Windows 11

 The system tray, which is part of the Taskbar and shows the apps you use frequently, among other things, can become overcrowded.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

## How to Show or Hide System Tray Icons on Windows 11

 To show more icons in the system tray, you need to access the Taskbar's settings by pressing **Win + I**, selecting **Personalization** on the left side menu, and then clicking **Taskbar** in the right panel.

![Go to Taskbar Settings in the Personalization Tab of Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/6-go-to-taskbar-settings-in-the-personalization-tab-of-windows-settings-app.jpg)

 In Taskbar settings, scroll down and expand the **Other system tray icons** section. Find the icon you want to show (its toggle will be set to **Off** if it isn’t in the system tray) and click on the toggle on its right to set it to the **On** position.

![you can turn system tray icons on and off in the Taskbar settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-tray-icons-windows-11.jpg)

 If you want to remove the system tray icon, simply set the toggle to **Off**.

 Another way to remove icons from the system tray is to place them in the hidden icons menu. This is the menu that appears when you click the **up caret** icon in the system tray. When the menu is opened, the icon becomes a **down caret**.

![the hidden icons menu on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hidden-icons-menu-windows-11.jpg)

 To remove an icon from the system tray and place it into the hidden icons menu, click and drag it into the **up caret**. And when you expand the hidden icons menu, you will see that the icon is inside.

 When you remove system tray icons from the settings, they will not appear in the hidden icons menu but will be removed completely.

 To add the icon back in the system tray, click and drag it from the hidden icons menu and then place it in the system tray.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## How to Show or Hide the Hidden Icon Menu

 As mentioned earlier, the hidden icon menu is what appears when you click the **up caret** in the system tray. You can also hide and show this menu as you please.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
### Using the Settings App

 If you can't see the hidden icon menu, you can show it from the Taskbar settings as well. To get there, right-click an empty part of the Taskbar and select **Taskbar settings**.

![opening Taskbar settings by right clicking an empty part of the Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/opening-taskbar-settings.jpg)

 Scroll down until you reach the **Other system tray icons** section and expand it. To reveal the hidden icon menu, set the toggle next to the **Hidden menu icon** option to **On**. To hide it, set the toggle to **Off**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Using the Registry Editor

 If you’re not familiar with the Registry Editor, we recommend that you read our guide on [what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) before continuing. It’s crucial that you know what you’re working with before moving forward. Also, be sure to [make a backup of the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) while you're at it.

 With that out of the way, you can open the Registry Editor by pressing **Win + R**, entering **regedit** in the text box, and then clicking on **OK**. In the UAC prompt, click **Yes** to launch the tool.

 For more methods to launch the Registry Editor, please check out our guide on [ways to open the Registry Editor on Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/).

 Afterward, copy and paste the following path into the address bar of the Registry Editor and hit the **Enter** key:

HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\CurrentVersion\TrayNotify

 Next, double-click the **SystemTrayChevronVisibility** value in the right panel.

![the SystemTrayChevronVisibility value in the Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/systemtraychevronvisibility-value-regedit-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->

 To show the hidden icon menu, set the **Value data** text box to **1** and click **OK**.

![setting the SystemTrayChevronVisibility value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/systemtraychevronvisibility-value-data.jpg)
<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 And to hide the hidden icon menu set the **Value data** text box to **0** and click **OK**.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## Control the Icons that Appear in the System Tray on Windows 11

 Whether you want to add icons or remove them from the system tray, the process is simple. Just go to the Taskbar settings and turn them on or off as needed. You can also hide or show the hidden icon menu in the process.

 And if you want to show or hide the clock and date in the system tray, you can do that too.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-free-and-easy-best-mac-screen-recorder-software-of-2023-for-2024/"><u>[New] Free and Easy  Best Mac Screen Recorder Software of 2023 for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-learn-fb-live-mastering-2023-streaming/"><u>[Updated] 2024 Approved  Learn FB Live  Mastering 2023 Streaming</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-twitch-your-way-mastering-twitter-video-livestreaming/"><u>[Updated] 2024 Approved  Twitch Your Way  Mastering Twitter Video Livestreaming</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-customize-windows-10-and-11-with-winbubble/"><u>8 Ways to Customize Windows 10 and 11 With WinBubble</u></a></li>
<li><a href="https://win11.techidaily.com/a-systematic-approach-to-rejuvenating-your-media-software/"><u>A Systematic Approach to Rejuvenating Your Media Software</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-clandestine-windows-11-taskbar-seeker/"><u>Accessing Clandestine Windows 11 Taskbar Seeker</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-efficiency-in-the-digital-age-with-these-best-windows-tools/"><u>Boosting Efficiency in the Digital Age with These Best Windows Tools</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-with-descriptive-folders-in-windows-11/"><u>Boosting Productivity with Descriptive Folders in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-disallowed-label-on-windows-programs/"><u>Clearing Disallowed Label on Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/continuous-edge-background-on-windows-11-tips/"><u>Continuous Edge Background on Windows 11 - Tips</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-resolving-windows-11s-fatal-error/"><u>Deciphering and Resolving Windows 11'S Fatal Error</u></a></li>
<li><a href="https://win11.techidaily.com/diving-into-shortened-terms-alias-and-application-lifecycle/"><u>Diving Into Shortened Terms: Alias & Application Lifecycle</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-file-management-skills-multi-zip-extraction-techniques/"><u>Elevate Your File Management Skills: Multi-Zip Extraction Techniques</u></a></li>
<li><a href="https://extra-tips.techidaily.com/enhance-your-reality-the-best-vr-accessories/"><u>Enhance Your Reality  The Best VR Accessories</u></a></li>
<li><a href="https://win11.techidaily.com/1719343225911-epic-launcher-uninstallation-hurdles-bust-them-on-windows-11/"><u>Epic Launcher Uninstallation Hurdles, Bust Them On Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-to-eradicate-fluctuating-display-on-windows-1011/"><u>Expert Tips to Eradicate Fluctuating Display on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-disconnect-error-during-discord-setup-in-windows-os/"><u>Fixing Disconnect Error During Discord Setup in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-win1011-unraveling-error-code-0x800704b3/"><u>Fixing Win10/11: Unraveling Error Code 0X800704B3</u></a></li>
<li><a href="https://win11.techidaily.com/future-proof-your-pc-take-advantage-of-windows-11-h2-update-plan/"><u>Future-Proof Your PC: Take Advantage of Windows 11 H2 Update Plan</u></a></li>
<li><a href="https://win11.techidaily.com/guide-stop-hyber-v-with-ease-in-windows-11-pro/"><u>Guide: Stop Hyber-V with Ease in Windows 11 Pro</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-activation-lock-from-iphone-14-plus-or-ipad-by-drfone-ios/"><u>How to Bypass Activation Lock from iPhone 14 Plus or iPad?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-camera-apps-0xa00f429f-error-in-windows-11-and-11/"><u>How to Fix the Camera App’s 0xA00F429F Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-quickly-resolve-win1011-screen-flicker/"><u>How to Quickly Resolve WIN10/11 Screen Flicker</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/imagerefixer-pro-the-ultimate-guide-to-reviving-corrupt-jpeg-pictures-flawlessly/"><u>Imagerefixer Pro: The Ultimate Guide to Reviving Corrupt JPEG Pictures Flawlessly</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/immersive-beginnings-secrets-to-successful-podcast-intros-for-2024/"><u>Immersive Beginnings  Secrets to Successful Podcast Intros for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-find-my-iphone-without-apple-id-on-your-iphone-xs-by-drfone-ios/"><u>In 2024, How to Remove Find My iPhone without Apple ID On your iPhone XS?</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-tiktoks-best-practices-for-stellar-edits/"><u>In 2024, TikTok's Best Practices for Stellar Edits</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-installation-windows-cab-files-unpacked-and-utilized/"><u>Initiating Installation: Windows CAB Files Unpacked and Utilized</u></a></li>
<li><a href="https://win11.techidaily.com/instant-repair-tactics-for-windows-photo-app-malfunctions/"><u>Instant Repair Tactics for Windows Photo App Malfunctions</u></a></li>
<li><a href="https://win11.techidaily.com/investigating-the-efficacy-of-windows-11s-feature-additions/"><u>Investigating the Efficacy of Windows 11'S Feature Additions</u></a></li>
<li><a href="https://win11.techidaily.com/path-pursuit-6-efficient-strategies-for-copying-file-and-folder-paths-in-windows-11/"><u>Path Pursuit: 6 Efficient Strategies for Copying File and Folder Paths in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/proven-steps-for-clearer-images-using-windows-11s-background-blur-feature-in-the-app/"><u>Proven Steps for Clearer Images Using Windows 11'S Background Blur Feature in the App</u></a></li>
<li><a href="https://android-unlock.techidaily.com/remove-the-lock-screen-fingerprint-of-your-samsung-galaxy-a23-5g-by-drfone-android/"><u>Remove the Lock Screen Fingerprint Of Your Samsung Galaxy A23 5G</u></a></li>
<li><a href="https://win11.techidaily.com/resizing-desktop-picture-summaries-in-win11/"><u>Resizing Desktop Picture Summaries in Win11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/resolve-kernel32dll-errors-swiftly-techniques-and-tips-for-windows-users/"><u>Resolve Kernel32.dll Errors Swiftly: Techniques and Tips for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-network-unreachable-issue-in-windows/"><u>Resolving 'Network Unreachable' Issue in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-the-settings-retrieval-unsuccessful-problem-on-windows-11/"><u>Reversing the Settings Retrieval Unsuccessful Problem on Windows 11</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/secret-social-scrolls-best-kept-facebook-memes-for-2024/"><u>Secret Social Scrolls  Best-Kept Facebook Memes for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/securely-manage-tasks-as-an-admin-in-windows-11/"><u>Securely Manage Tasks as an Admin in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-beginners-handbook-to-github-desktop-and-windows-integration/"><u>The Beginner's Handbook to GitHub Desktop & Windows Integration</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-effective-rgb-light-settings-in-win11/"><u>Tips for Effective RGB Light Settings in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-video-editing-software-for-pc-users-windows/"><u>Top 8 Video Editing Software for PC Users (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-power-of-windows-11-quick-selective-copy-and-move/"><u>Unlock the Power of Windows 11: Quick Selective Copy & Move</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-6-factors-that-favor-windows-11/"><u>Unraveling 6 Factors That Favor Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-connectivity-issues-with-spotify-and-windows-11/"><u>Unraveling Connectivity Issues with Spotify & Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-is-a-sim-network-unlock-pin-get-your-poco-x5-pro-phone-network-ready-by-drfone-android/"><u>What Is a SIM Network Unlock PIN? Get Your Poco X5 Pro Phone Network-Ready</u></a></li>
<li><a href="https://win11.techidaily.com/winning-at-lan-play-fixes-for-no-connection-woes/"><u>Winning at LAN Play: Fixes for No Connection Woes</u></a></li>
</ul></div>
