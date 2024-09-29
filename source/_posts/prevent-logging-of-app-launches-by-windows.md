---
title: Prevent Logging of App Launches by Windows
date: 2024-09-23T21:33:01.492Z
updated: 2024-09-28T19:27:49.993Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Prevent Logging of App Launches by Windows
excerpt: This Article Describes Prevent Logging of App Launches by Windows
keywords: Prevent Winlogon Launch Records,Stop Windows App Logs,Disable App Start Tracking,Avoid Windows Event Recordings,Halt Windows Session Timestamping,Block User Action Logging,Eliminate System App Launch Data
thumbnail: https://thmb.techidaily.com/757021be603bb0b62889fcb3393264ba25afdf3ad53016173b55a4a0650b3071.jpg
---

## Prevent Logging of App Launches by Windows

 Windows records and monitors how often you use particular applications. While this may enhance productivity, it does also raise privacy concerns.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Disable App Launch Tracking Through Windows Settings

 To disable app launch tracking, open the Start menu and type **Settings** in the search bar. Select the **Settings** option in the search results. In the left-side menu, click the **Privacy & security** tab. Then click **General** under the Windows permissions section.

 On the next page, locate **Let Windows improve Start and search results by tracking app launches** and toggle it off.

![Disable App Launch Tracking through Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-windows-settings.jpg)

 After making the changes, Windows will stop tracking and recording your app launches.

 If you ever need to re-enable the feature, repeat the same steps and toggle the switch back on. This will enable Windows to start tracking and recording your app launches.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100538/7443" target="_top" id="2100538">
  <img src="//a.impactradius-go.com/display-ad/7443-2100538" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Disable App Launch Tracking Using the Group Policy Editor

 You can also disable app launch tracking using the Group Policy Editor. But this method is only available in the Pro and Enterprise versions.

 If you don't have these Windows versions, [turn on the group policy editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) and follow these instructions.

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **gpedit.msc** in the text box and click **OK**.
3. In the Group Policy Editor window, navigate to the following path:  
`User Configuration > Administrative Templates > Windows Components > Edge UI​`
4. Go to the right side of the window and double-click on **Turn off tracking of app usage**.  
![Disable App Launch Tracking using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-using-group-policy-editor.jpg)
5. On the next page, check the **Enabled** box.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134489/18498" target="_top" id="2134489">
  <img src="//a.impactradius-go.com/display-ad/18498-2134489" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134489/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Click **Apply** \> **OK** to save your changes.

 This way, you can disable app launch tracking using the group policy editor.

 To enable the feature again, follow the same steps and navigate to _User Configuration > Administrative Templates > Windows Components > Edge UI_. Then double-click on **Turn off tracking of app usage** and check the **Not Configured** or **Disabled** option.

## 3\. How to Disable App Launch Tracking Through the Registry Editor

 Registry Editor is another method to disable app launch tracking. The process is tricky as you need to manually modify the registry keys and one wrong move can cause serious problems. So, we suggest you [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 To disable app launch tracking through Registry Editor, do the following:

1. Right-click on Start and select **Run** from the menu list.
2. Type **regedit** in the text field and click **OK**. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. When the UAC window appears, click **Yes** to grant privileges.
4. In the left pane, navigate to the following path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. If you don't find the Advanced folder, right-click on **Explorer** and select **New** \> **Key**.
6. Name it **Advanced** and press the Enter key.
7. Now, right-click on the **Advanced** folder and choose **New** \> **DWORD (32-bit) Value**.
8. Name it **Start\_TrackProgs** and hit Enter.  
![Disable App Launch Tracking through the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/disable-app-launch-tracking-through-the-registry-editor.jpg)
9. Double-click on the **Start\_TrackProgs** DWORD and set its value to **0**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975821/19272" target="_top" id="1975821">
  <img src="//a.impactradius-go.com/display-ad/19272-1975821" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975821/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you're done, close the Registry Editor and restart your computer. Now, Windows won't track or record app launches.

 If you ever want to turn back on app launch tracking, double-click on the **Start\_TrackProgs** DWORD in Registry Editor and set its value to **1**. After that, restart your system for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139109/17108" target="_top" id="2139109">
  <img src="//a.impactradius-go.com/display-ad/17108-2139109" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139109/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Windows Won’t Track or Monitor the Apps You Use

 If you don't want to mess with the Registry Editor or Group Policy Editor, use the Settings option to disable app launch tracking. Choose the method you prefer and enjoy a tracking-free experience.

 If you're uncomfortable with Windows monitoring your application usage, there are a few ways to disable app launch tracking on your Windows PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-knowledge.techidaily.com/updated-frequency-fluctuations-for-game-mastery/"><u>[Updated] Frequency Fluctuations for Game Mastery</u></a></li>
<li><a href="https://tech-haven.techidaily.com/7-reasons-to-question-generative-ai-use-in-chats/"><u>7 Reasons to Question Generative AI Use in Chats</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-steam-efficiency-counteracting-zero-speed/"><u>Boosting Windows Steam Efficiency: Counteracting Zero-Speed</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-fixing-chromes-profiles-issues/"><u>Comprehensive Guide to Fixing Chrome's Profiles Issues</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-faulty-m365-functionality-code-30015-26/"><u>Disabling Faulty M365 Functionality: Code 30015-26</u></a></li>
<li><a href="https://extra-tips.techidaily.com/essential-guide-best-free-video-effect-websites-reviewed-and-rated-by-experts/"><u>Essential Guide Best Free Video Effect Websites Reviewed & Rated by Experts</u></a></li>
<li><a href="https://win11.techidaily.com/facilitating-regular-updates-toolbar-integration-in-the-windows-ui/"><u>Facilitating Regular Updates: Toolbar Integration in the Windows UI</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unsuccessful-attempts-to-connect-to-nvidia-geforce-in-windows-11/"><u>Fixing Unsuccessful Attempts to Connect to Nvidia GeForce in Windows 11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-a-found-iphone-6-drfone-by-drfone-ios/"><u>In 2024, How To Unlock A Found iPhone 6? | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-videotwit-hatcher-harvest-tweets-visuals-for-ios-devices/"><u>In 2024, VideoTwit Hatcher Harvest Tweets' Visuals for iOS Devices</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-vlc-a-guide-to-streaming-videos-on-your-apple-tv/"><u>Mastering VLC: A Guide to Streaming Videos on Your Apple TV</u></a></li>
<li><a href="https://win11.techidaily.com/measuring-electrical-use-for-windows-pcs-effectively/"><u>Measuring Electrical Use for Windows PCs Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-shift-away-from-windows-xp-7-and-81-support/"><u>Navigating the Shift Away From Windows XP, 7 & 8.1 Support</u></a></li>
<li><a href="https://win11.techidaily.com/new-horizons-in-windows-11-dissecting-update-wxxs-additions/"><u>New Horizons in Windows 11: Dissecting Update W.x.x's Additions</u></a></li>
<li><a href="https://article-tips.techidaily.com/the-future-of-action-photography-tomtoms-bandit-review/"><u>The Future of Action Photography TomTom's Bandit Review</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-future-of-freelancing-can-these-8-ai-tools-outshine-chatgpt-in-making-extra-cash/"><u>The Future of Freelancing: Can These 8 AI Tools Outshine ChatGPT in Making Extra Cash?</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-tricks-for-mass-folder-creation-at-a-click-in-windows-oses/"><u>The Ultimate Tricks for Mass Folder Creation at a Click in Windows OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-unable-to-open-geforce-experience-error/"><u>Troubleshooting Unable to Open GeForce Experience Error</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-the-top-5-free-m4a-file-editors-you-need/"><u>Updated In 2024, The Top 5 Free M4A File Editors You Need</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    