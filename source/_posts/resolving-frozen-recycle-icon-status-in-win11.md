---
title: Resolving Frozen Recycle Icon Status in Win11
date: 2024-07-13T10:48:44.265Z
updated: 2024-07-14T10:48:44.265Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Frozen Recycle Icon Status in Win11
excerpt: This Article Describes Resolving Frozen Recycle Icon Status in Win11
keywords: Fix Recycle Icons,Windows 11 Freeze Fix,Unfreeze Recycle Bin,Resolve WIN11 Errors,Clear Icon Halt,Win11 Troubleshooting,Stop Icon Stuck Status
thumbnail: https://thmb.techidaily.com/60fbcd30864e8b21a8752d2636e7944e4f6dffcb372de2311bd231d44717be72.jpg
---

## Resolving Frozen Recycle Icon Status in Win11

 The Recycle Bin has been a staple on Windows for a long time, but not everyone wants it on the desktop. You can disable it via the Desktop Icon Settings, but there is a bug where if you try to re-enable it, the "Recycle Bin" option is grayed out and cannot be toggled.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

## 1\. How to Bring Back the Recycle Bin Using the Group Policy Editor

 The Group Policy Editor lets you show or hide the Recycle Bin icon from the desktop. Check if you have modified and accidentally disabled the Recycle Bin group policy recently. If so you can set the Remove Recycle Bin icon from the desktop policy to "Not Configured" which will restore it.

 You may not find the Local Group Policy Editor in Windows Home Edition. However, you can run a batch script to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) or skip to the Registry Editor-based fix in the next step.

 To restore the Recycle Bin icon using the Group Policy Editor:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor**.  
![gpedit msc windows 11 run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/gpedit-msc-windows-11-run.jpg)
3. Next, navigate to the following location:  
`User Configuration > Administrative Templates > Desktop`
4. In the right pane, locate and double-click on the **Remove Recycle Bin icon from the desktop** option to open its properties.  
![edit remove recycle bin icon from settings gpedit policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy.jpg)
5. In the **Properties** dialog, select **Not Configured**.  
![edit remove recycle bin icon from settings gpedit policy not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy-not-configured.jpg)
6. Click **Apply** and **OK** to save the changes.

 Close the Group Policy Editor and check your desktop to see if you can access the Recycle Bin. If not, make sure the Recycle Bin is set to show in Desktop Icon Settings.

 To enable Recycle Bin in Desktop Icon Settings:

1. Press **Win + I** to open **Settings**.
2. Next, open the **Personalization** tab in the left panel.
3. Click on **Themes**.  
![desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/desktop-icon-settings-windows-11.jpg)
4. Click on **Desktop icon settings** under the **Related settings** section.
5. In the **Desktop Icon Settings** dialog, select **Recycle Bin**.  
![enable recycle bin desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/enable-recycle-bin-desktop-icon-settings-windows-11.jpg)
6. Click **Apply** and **OK** to save the changes.

 If you can’t access Group Policy Editor or if the issue persists, you can use the Registry Editor to fix this problem.

## 2\. Modify the Recycle Bin Registry Settings

 Another way to resolve and restore the grayed-out Recycle Bin icon in the Desktop settings is via the Windows Registry. You can modify the registry entry value responsible for the settings and configurations of Recycle Bin working to restore the functionality.

 Making modifications to the Windows registry involves tweaking settings that may harm your device if performed incorrectly. We recommend you [create a Windows restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [take a Windows registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before attempting to modify the Windows registry.

 To modify the Recycle Bin registry value:

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**. Click **Yes** if prompted by **User Account Control**.
3. In the Registry Editor, navigate to the following location. You can copy and paste the path in the editor for quicker navigation:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\NonEnum`
4. In the right pane, locate the **{645FF040-5081-101B-9F08-00AA002F954E}** DWORD (32-bit) value.  
![registry editor nonnum new dword value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value.jpg)
5. If it does not exist, you’ll need to create a new value. To do this, right-click on the **NonEnum** subkey folder in the left pane and select **New > DWORD (32-bit) Value**.
6. Rename the value as **{645FF040-5081-101B-9F08-00AA002F954E}**.
7. Next, double-click on the new DWORD value to open its properties.  
![registry editor nonnum new dword value edit 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value-edit-0.jpg)
8. Type **0** in the Value data field and click **OK** to save the changes.
9. Close Registry Editor and restart your computer. Sometimes, you’ll need to restart your computer for the new registry modifications to work.

 If the issue persists, try to [create a new user account with administrative rights](https://www.makeuseof.com/windows-11-create-local-user-account/), [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/), or [repair corrupted Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

## Get Access to the Recycle Bin Desktop Icon Setting Again

 An incorrectly modified group policy can gray out the Recycle Bin icon in the Desktop Icon Settings dialog. Fortunately, it's an easy fix, and you should now have your Recycle Bin back to how you like it.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-the-innovators-pathway-advanced-video-editing-techniques-for-instagram/"><u>[New] In 2024, The Innovator's Pathway  Advanced Video Editing Techniques for Instagram</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-locked-iphone-12-pro-max-by-restoring-by-drfone-ios-unlock-ios-unlock/"><u>How to Unlock locked iPhone 12 Pro Max by restoring</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-workspace-incorporating-sketches-into-windows-11/"><u>Customize Your Workspace: Incorporating Sketches Into Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/targeted-user-group-policies-implementing-changes-step-by-step/"><u>Targeted User Group Policies: Implementing Changes Step-by-Step</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-instructions-eradicating-wsl-from-windows/"><u>Comprehensive Instructions: Eradicating WSL From Windows</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-locked-apple-id-on-apple-iphone-14-pro-max-by-drfone-ios/"><u>How to Fix Locked Apple ID on Apple iPhone 14 Pro Max</u></a></li>
<li><a href="https://win11.techidaily.com/google-nearby-share-vs-windows-nearby-sharing-which-should-you-use/"><u>Google Nearby Share Vs. Windows Nearby Sharing: Which Should You Use?</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-high-cpu-usage-a-guide-via-windows-resource-monitor/"><u>Conquering High CPU Usage: A Guide via Windows Resource Monitor</u></a></li>
<li><a href="https://win11.techidaily.com/disguising-or-displaying-time-win-1011-tutorial/"><u>Disguising or Displaying Time: Win 10/11 Tutorial</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-crucial-chrome-aids-for-effortless-vimeo-viewing-for-2024/"><u>[Updated] Crucial Chrome Aids for Effortless Vimeo Viewing for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/effective-strategies-to-dial-down-memorycpu-in-windows/"><u>Effective Strategies to Dial Down Memory/CPU in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-valorant-lags-with-windows-tweaks/"><u>Eliminating Valorant Lags with Windows Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-cut-off-others-access-in-the-windows-network/"><u>How to Cut Off Others' Access in the WIndows Network</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-perfecting-podcast-production-an-ultimate-tutorial-for-high-quality-zoom-recordings-for-2024/"><u>[New] Perfecting Podcast Production  An Ultimate Tutorial for High-Quality Zoom Recordings for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-unseen-glimpse-of-fb-stories/"><u>[New] Unseen Glimpse of FB Stories</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-tracking-disk-space-usage-in-windows-pcs/"><u>The Ultimate Guide to Tracking Disk Space Usage in Windows PCs</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-easy-ios-screen-recording-tips-and-tricks/"><u>[Updated] Easy iOS Screen Recording Tips & Tricks</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-touch-screen-on-samsung-galaxy-a05-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-pure-video-downloads-from-tiktok-no-watermark-required-for-2024/"><u>[Updated] Pure Video Downloads From TikTok – No Watermark Required for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-techniques-for-inspecting-and-cleansing-windows-trail/"><u>Efficient Techniques for Inspecting & Cleansing Windows Trail</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/a-closer-look-at-virtualdub-review-benefits-and-top-alternatives/"><u>A Closer Look at Virtualdub Review, Benefits, and Top Alternatives</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-fixing-winget-on-w11/"><u>Comprehensive Guide to Fixing Winget on W11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-tecno-pop-8-by-phone-number-drfone-by-drfone-virtual-android/"><u>How to Track Tecno Pop 8 by Phone Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-access-10-fast-methods-to-control-center/"><u>Accelerate Access: 10 Fast Methods to Control Center</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-encompass-entire-webpage-in-view/"><u>[Updated] Encompass Entire Webpage in View</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-asus-rog-phone-8-pro-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Asus ROG Phone 8 Pro | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-samsung-galaxy-a25-5g-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Samsung Galaxy A25 5G 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-vivo-v27e-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Vivo V27e Phone Hassle-Free</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/video-cam-gurus-top-picks/"><u>Video Cam Gurus  Top Picks</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solution-to-0x800713f-malfunction-in-windows-mail/"><u>Swift Solution to 0X800713F Malfunction in Windows Mail</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-airplane-mode-turn-off-gps-location-on-realme-gt-5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Does Airplane Mode Turn off GPS Location On Realme GT 5 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-system-reliability-automatic-updates-plus-graphics-card-swap/"><u>Enhance System Reliability: Automatic Updates + Graphics Card Swap</u></a></li>
<li><a href="https://audio-editing.techidaily.com/leading-edge-mp3-sync-service-at-no-cost-for-2024/"><u>Leading Edge MP3 Sync Service at No Cost for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/expert-recommendations-for-limitless-data-holding/"><u>Expert Recommendations for Limitless Data Holding</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-photoshop-performance-issues/"><u>Streamlining Windows Photoshop Performance Issues</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-stopping-bsod-from-vmware-on-windows-11/"><u>Strategies for Stopping BSOD From VMware on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-block-of-microsoft-store-in-windows-11/"><u>Disabling Block of Microsoft Store in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-rgb-customization-on-your-win11-device/"><u>Enabling RGB Customization on Your Win11 Device</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-how-to-archive-your-favorite-movies-mac-screenshots-for-netflix/"><u>[New] In 2024, How to Archive Your Favorite Movies  Mac Screenshots for Netflix</u></a></li>
<li><a href="https://win11.techidaily.com/freedomgpt-for-pc-running-ai-conversation-tools/"><u>FreedomGPT for PC: Running AI Conversation Tools</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ltimate-screener-tech-the-choice-of-top-youtube-creators-for-2024/"><u>[New] Ultimate Screener Tech  The Choice of Top YouTube Creators for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-effortless-data-purging-in-windows-1011/"><u>Master the Art of Effortless Data Purging in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-username-experience-on-windows-11-platform/"><u>Transforming UserName Experience on Windows 11 Platform</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tactics-avoiding-counterfeit-creations-on-microsofts-platform/"><u>Tech Tactics: Avoiding Counterfeit Creations on Microsoft's Platform</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-incredible-trend-trackers-monitor-highest-youtube-spots/"><u>[New] Incredible Trend Trackers  Monitor Highest YouTube Spots</u></a></li>
<li><a href="https://win11.techidaily.com/mapping-out-gpo-landscape-a-gpresult-perspective/"><u>Mapping Out GPO Landscape: A GPResult Perspective</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-master-the-art-of-video-annotation-using-markers-with-ease/"><u>[Updated] 2024 Approved  Master the Art of Video Annotation  Using Markers with Ease</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-2024-approved-how-to-edit-facebook-video-ads-for-e-commerce-business/"><u>Updated 2024 Approved How to Edit Facebook Video Ads for E-Commerce Business</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-elevating-your-tiktok-identity-in-under-10-steps/"><u>[Updated] Elevating Your TikTok Identity in Under 10 Steps</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-path-not-found-on-pc-networks/"><u>Addressing Path Not Found on PC Networks</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-verifying-realness-in-instagrams-visual-identity-expressions-for-2024/"><u>[New] Verifying Realness in Instagram's Visual Identity Expressions for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-best-3-itel-p55-5g-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>In 2024, Best 3 Itel P55 5G Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/1715859698536-new-explore-mp4-recording-tools-today/"><u>[New] Explore MP4 Recording Tools Today!</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-access-to-windows-odbc-settings/"><u>Mastering Access to Windows' ODBC Settings</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-xiaomi-redmi-note-12-proplus-5g-phone-without-any-data-loss-by-drfone-android/"><u>In 2024, How to Unlock Xiaomi Redmi Note 12 Pro+ 5G Phone without Any Data Loss</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-image-formats-stopping-chromes-webp-savings-on-pc/"><u>Mastering Image Formats: Stopping Chrome's WebP Savings on PC</u></a></li>
<li><a href="https://win11.techidaily.com/the-best-file-sharing-software-on-windows-os/"><u>The Best File-Sharing Software on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-volume-control-slider-not-working-in-windows-11-and-11/"><u>How to Fix the Volume Control Slider Not Working in Windows 11 & 11</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/proscreencapture-ultimate-edition-for-2024/"><u>ProScreenCapture Ultimate Edition for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/interpreting-the-significance-of-blue-emojis-on-messenger/"><u>Interpreting the Significance of Blue Emojis on Messenger</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-achieve-a-seamless-experience-less-latency-more-fps/"><u>How to Achieve a Seamless Experience: Less Latency, More FPS</u></a></li>
<li><a href="https://win11.techidaily.com/windows-1011-reimagined-establishing-personalized-pin-patterns/"><u>Windows 10/11 Reimagined: Establishing Personalized Pin Patterns</u></a></li>
<li><a href="https://win11.techidaily.com/deleting-windows-bt-directory-purpose-and-process/"><u>Deleting Windows ~BT Directory: Purpose & Process</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-cinematic-chronicles-in-depth-video-tech-reviews-for-2024/"><u>[Updated] Cinematic Chronicles  In-Depth Video Tech Reviews for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-pixel-playground-discovering-the-art-of-picture-distortion/"><u>[New] Pixel Playground  Discovering the Art of Picture Distortion</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-facebook-fans-access-more-from-your-twitch-channel/"><u>[New] 2024 Approved  Facebook Fans  Access More From Your Twitch Channel</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-produce-playful-photoshopped-gifs-via-giphy/"><u>In 2024, Produce Playful Photoshopped Gifs via Giphy</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-15-best-free-mp4-video-rotators-windowsmac-android-iphone-and-online/"><u>Updated 2024 Approved 15 Best Free MP4 Video Rotators Windows,Mac， Android, iPhone & Online</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-full-control-in-windows-cmd/"><u>Unlock Full Control in Windows CMD</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-password-protectionists-for-the-modern-windows-user/"><u>Masterful Password Protectionists for the Modern Windows User</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-the-read-only-shackles-of-windows-11/"><u>Breaking Free From the Read-Only Shackles of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-the-life-solutions-for-non-responsive-bluetooth-mice-windows/"><u>Bring Back the Life: Solutions for Non-Responsive Bluetooth Mice (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-rectify-unresponsive-windows-media-files/"><u>Steps to Rectify Unresponsive Windows Media Files</u></a></li>
<li><a href="https://win11.techidaily.com/hasten-enablingdisabling-microsofts-bing-assistant-in-taskbar/"><u>Hasten Enabling/Disabling: Microsoft's Bing Assistant in Taskbar</u></a></li>
</ul></div>
