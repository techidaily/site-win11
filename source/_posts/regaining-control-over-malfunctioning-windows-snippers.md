---
title: Regaining Control Over Malfunctioning Windows Snippers
date: 2024-07-13T11:03:19.983Z
updated: 2024-07-14T11:03:19.983Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Regaining Control Over Malfunctioning Windows Snippers
excerpt: This Article Describes Regaining Control Over Malfunctioning Windows Snippers
keywords: Fix Windows Snippets Issues,Unlock Snip Tool,Resolve Snip Errors,Snippet Functionality,Snipper Control Guide,Correct Snip App Glitches,Tips for Snippers Troubleshoot
thumbnail: https://thmb.techidaily.com/d44947af2d23263a61b2bb19233d3717a7fd178394378301c673d9cd094e466a.jpg
---

## Regaining Control Over Malfunctioning Windows Snippers

 Whether you need to capture an error message or share something specific with someone, screenshots can be a lifesaver. The Win + Shift + S shortcut makes it easy to take screenshots with the Snipping Tool, but what if that shortcut stops responding?

 Is your screenshot-taking career over? Definitely not. There are still some fixes you can try to solve this issue. Read on to learn what to do when your Win + Shift + S shortcut isn't working.

## 1\. Restart the Computer

 It might sound simple, but restarting your computer often solves minor problems. This can help clear out any glitches that may prevent the shortcut from working correctly.

 To restart your computer, close any running programs. Now, open the Start menu and choose **Restart** in the list of options.

## 2\. Check Your Keyboard

 Check the keyboard for any dirt or debris that may obstruct the keys. Clean off dust, crumbs, and other particles with compressed air. Ensure that all the keys are working correctly and that none are stuck or pressed down. If the keys have been damaged or worn down, consider replacing your keyboard.

## 3\. Enable the Clipboard History

 If keyboard dirt and debris are not the issues, you may need to enable the clipboard history feature. This will help you restore any screenshots taken with Win + Shift + S that have been lost.

![Enable the Clipboard History](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-the-clipboard-history.jpg)

 To enable it, open Settings and navigate to **System** \> **Clipboard**. There, you'll find the toggle for **Clipboard history** – turn it on.

 You can also use the Windows search bar to type in **Clipboard settings** and open it directly. If you prefer shortcuts, hit **Win + R** or type **ms-settings:clipboard** into Run.

## 4\. Turn on Snipping Tool Notification Toggle

 When you press Win + Shift + S on your keyboard, a notification should appear in the bottom-right corner of the screen. This notification toggle helps you quickly access screenshots taken with the shortcut.

 If you don't see a notification, that means the toggle is off, and you may need to enable it manually. Here's how to do it:

1. Right-click on Start and select **Settings**.
2. In the Settings window, navigate to **System** \> **Notifications**.
3. Under **Notifications from apps and other senders**, scroll down to the bottom and turn on the Snipping Tool notification toggle.  
![Turn on Snipping Tool Notification Toggle](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/turn-on-snipping-tool-notification-toggle.jpg)

 Once you have enabled this option, press **Win + Shift + S** to take a screenshot. If the shortcut works, you will see a notification that the screenshot is saved to the clipboard.

## 5\. Reset the Snipping Tool

 Another solution is to reset the Snipping Tool. It restores the default settings and can help if something goes wrong.

 To reset it, right-click on the **Start** menu and select **Installed apps**. Find **Snipping Tool** in the list, click three dots, and select **Advanced options**.

 You can also use **Win + R** or type **ms-settings:appsfeatures** in the Run dialog box to open Installed apps. From there, you can find the Advanced options for the Snipping Tool.

![Reset Snipping Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-snipping-tool.jpg)

 On the next page, scroll down to the **Reset** section. Select **Reset** and then click on **Reset** again in the confirmation popup. After resetting the Snipping Tool, check if the Win + Shift + S shortcut works.

## 6\. Reinstall the Snipping Tool

 If resetting doesn't solve the problem, try reinstalling the Snipping Tool. It will resolve any issues you may have with your current installation.

 To reinstall the Snipping Tool, open the System Settings. Select **Apps** \> **Installed apps**, then find and select **Snipping Tool** from the list of installed programs.

![Reset the Snipping Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-the-snipping-tool.jpg)

 Click the three dots and select **Uninstall**. Now follow the on-screen instructions to complete the process. Once done, download and install a new version of the Snipping Tool from the Microsoft Store app.

## 7\. Turn on Windows Hotkeys

 If your Windows hotkeys are disabled for some reason, the shortcut keys will not work. In such cases, you will need to enable the Windows hotkeys through the group policy editor. Here's how to do it:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **gpedit.msc** in the dialog box and hit Enter. This will open the Group Policy Editor window.  
![Turn on Windows Hotkeys Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/turn-on-windows-hotkeys-using-group-policy.jpg)
3. Navigate to the path:  
`User Configuration > Administrative Templates > Windows Components > File Explorer`
4. In the right pane, double-click on the **Turn off Windows Key hotkeys** option.
5. Select Enabled in the settings window and click **Apply** \> **OK**.

 After making these changes, try taking a screenshot with Win + Shift + S shortcut. It should work now.

 One thing to remember is that this method will only work with Windows Pro and Enterprise editions. If you have the Home edition, you can't access the Group Policy Editor. In such a case, you'll need to [enable the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated, skip this method and use the Registry Editor instead.

 To enable Windows Hotkeys through the Registry Editor, follow these steps:

* Click on Start, type **regedit**, and hit **Enter**.
* If the UAC window pops up, click Yes to open the registry editor.  
`Navigate to HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Policies\Explorer`
* If you don't see the Explorer folder, right-click on **Policies** and select **New > Key**. Name the newly created key **Explorer**.
* Now right-click on **Explorer** and select **New** \> **DWORD 32-bit**.
* Name the DWORD **NoWinKeys**.
* Double-click on **NoWinKeys** and set the value data to **0**.  
![Turn on Windows Hotkeys Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/turn-on-windows-hotkeys-using-registry.jpg)
* Select Base as **Hexadecimal** and click **OK** to save the changes.

 After that, exit the registry editor and restart your computer. Once the system reboots, check if the issue has been resolved.

## 8\. Perform Some Generic Fixes

 There are a few general fixes that might help you get the Win + Shift + S keyboard shortcut working. Here's what you need to do:

1. Check the keyboard driver status and update it if needed.
2. Try [running the SFC utility](https://www.makeuseof.com/windows-built-in-repair-tools/) to fix corrupted system files.
3. Make sure you are [running the latest version of Windows](https://www.makeuseof.com/update-windows-manually/).
4. [Run a full scan with your antivirus program](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and see if it solves the issue.
5. If the issue still persists, there's a chance that third-party applications are interfering with the Snipping Tool shortcut. In such a case, [try performing a clean boot](https://www.makeuseof.com/clean-boot-windows-11/). This will temporarily disable all the third-party applications and allow you to check if they were causing the issue.

## Taking Screenshots Is Easy With Shortcut Keys

 Keyboard shortcuts provide quick and easy access to different functions on your PC. It allows you to easily switch between applications and perform tasks. There are times, though, when the Win + Shift + S hotkey does not work properly. Hopefully, one of the above methods fixed this issue for you.

 Is your screenshot-taking career over? Definitely not. There are still some fixes you can try to solve this issue. Read on to learn what to do when your Win + Shift + S shortcut isn't working.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://voice-adjusting.techidaily.com/updated-the-ultimate-idevice-audio-recorders-handbook-for-2024/"><u>Updated The Ultimate iDevice Audio Recorders Handbook for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-honor-x50-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On Honor X50 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/get-icloud-running-without-glitches-on-your-windows-device/"><u>Get iCloud Running Without Glitches on Your Window's Device</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-essential-free-tools-perfecting-your-video-calls-for-2024/"><u>[Updated] Essential Free Tools  Perfecting Your Video Calls for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-cost-free-creative-twitter-videos-to-gif-magic/"><u>[New] Cost-Free Creative  Twitter Videos to Gif Magic</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/the-art-of-sound-integration-a-detailed-tutorial-on-video-audio-addition-for-2024/"><u>The Art of Sound Integration A Detailed Tutorial on Video Audio Addition for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-handling-winservicesexe-errors/"><u>Expert Tips for Handling Winservices.exe Errors</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-reverse-color-issue-with-windows-marketplace/"><u>Techniques to Reverse Color Issue with Windows Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-java-functionality-after-failed-installation/"><u>Restoring Java Functionality After Failed Installation</u></a></li>
<li><a href="https://win11.techidaily.com/reinstate-your-favorite-microsoft-store-for-windows-devices/"><u>Reinstate Your Favorite Microsoft Store for Windows Devices</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-grateful-for-viewership-template-choices-at-no-cost/"><u>2024 Approved  Grateful for Viewership!  Template Choices at No Cost</u></a></li>
<li><a href="https://win11.techidaily.com/next-steps-for-mobile-connectivity-in-windows-11/"><u>Next Steps for Mobile Connectivity in Windows 11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-top-ranked-internet-mp3-trimmer-and-merger-tool/"><u>New In 2024, Top-Ranked Internet MP3 Trimmer & Merger Tool</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-strategizing-against-the-phantom-follower-phenomenon/"><u>[New] In 2024, Strategizing Against the Phantom Follower Phenomenon</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-other-software-using-device-errors/"><u>Strategies for Overcoming 'Other Software Using Device' Errors</u></a></li>
<li><a href="https://techidaily.com/will-mov-files-play-on-samsung-galaxy-s24-by-aiseesoft-video-converter-play-mov-on-android/"><u>Will MOV files play on Samsung Galaxy S24 ?</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-filmora-coupon-hunters-guide-uncover-the-latest-deals-and-discounts/"><u>2024 Approved Filmora Coupon Hunters Guide Uncover the Latest Deals and Discounts</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-improve-usb-interaction-points/"><u>Steps to Improve USB Interaction Points</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-from-voice-to-print-effective-speech-to-text-strategies/"><u>Updated In 2024, From Voice to Print Effective Speech-to-Text Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-windows-task-management-addressing-misplaced-cpu-metrics/"><u>Fixes for Windows Task Management: Addressing Misplaced CPU Metrics</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/per-view-payment-potential-for-online-content-creators/"><u>Per-View Payment Potential for Online Content Creators</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-grammarly-non-functionality-in-windows-10/"><u>Fixing Grammarly Non-Functionality in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-lost-flight-buddy-copilot-in-windows-11/"><u>Reclaiming Lost Flight Buddy (Copilot) in Windows 11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-quietude-on-the-silver-screen-a-study-for-2024/"><u>[Updated] Quietude on the Silver Screen  A Study for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-growth-and-profitability-in-the-digital-marketplace-explore-these-top-15-facebook-insights-for-2024/"><u>[Updated] Growth & Profitability in the Digital Marketplace  Explore These Top 15 Facebook Insights for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/bring-back-classic-ps3-fun-with-best-tools/"><u>Bring Back Classic PS3 Fun with Best Tools</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/be-video-creation-secrets-of-the-professionals-unveiled/"><u>YouTube Video Creation  Secrets of the Professionals Unveiled</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/ultimate-guide-on-vivo-y28-5g-frp-bypass-by-drfone-android/"><u>Ultimate Guide on Vivo Y28 5G FRP Bypass</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-a-list-of-trustworthy-websites-for-procuring-creative-outro-harmonies-without-copyright-issues-for-2024/"><u>Updated A List of Trustworthy Websites for Procuring Creative Outro Harmonies Without Copyright Issues for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-admin-blocked-application-issue/"><u>Troubleshooting Admin-Blocked Application Issue</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-unable-to-open-on-ges-sharing-feature/"><u>Remedy for Unable to Open on GE's Sharing Feature</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-narrowing-focus-mac-techniques-for-snapchat-videos/"><u>[Updated] In 2024, Narrowing Focus  Mac Techniques for Snapchat Videos</u></a></li>
<li><a href="https://extra-hints.techidaily.com/reviewing-the-newest-2023-samsung-bd-j5900-model/"><u>Reviewing the Newest 2023 Samsung BD-J5900 Model</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-systemsettingsexe-failure-on-windows-11/"><u>Preventing SystemSettings.exe Failure on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-disrupted-photo-packaging-in-windows-10-and-11/"><u>Tackling Disrupted Photo Packaging in Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-error-0x0000004e-on-win11-devices/"><u>Remedying Error 0X0000004E on Win11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-set-win-10s-internet-safety-mechanism/"><u>How to Set Win 10’S Internet Safety Mechanism</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/mastering-fcpx-subtitles-a-comprehensive-tutorial-and-beyond-for-2024/"><u>Mastering FCPX Subtitles A Comprehensive Tutorial and Beyond for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/top-5plus-windows-1011-productivity-boosters-for-maximum-output/"><u>Top 5+ Windows 10/11 Productivity Boosters for Maximum Output</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-windows-screen-clarity-challenges/"><u>Mastery Over Windows Screen Clarity Challenges</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-reviewers-guide-to-yuneec-typhoon-h-performance/"><u>In 2024, Reviewer’s Guide to Yuneec Typhoon H Performance</u></a></li>
<li><a href="https://screen-recording.techidaily.com/innovative-use-of-plugins-for-skype-call-capture-in-obs-for-2024/"><u>Innovative Use of Plugins for Skype Call Capture in OBS for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-basics-easy-access-aids-for-novices/"><u>Windows Basics: Easy-Access Aids for Novices</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-experience-beyond-reality-choosing-the-premier-10-headsets-for-360-video-on-pc/"><u>In 2024, Experience Beyond Reality  Choosing the Premier 10 Headsets for 360 Video on PC</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-beyond-virtualdub-exploring-the-top-video-editing-software-options-for-2024/"><u>Updated Beyond Virtualdub Exploring the Top Video Editing Software Options for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-injecting-spark-into-your-unique-podcast-format/"><u>2024 Approved  Injecting Spark Into Your Unique Podcast Format</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-direct-voice-communication-for-xbox-on-windows-11/"><u>Reinstating Direct Voice Communication for Xbox on Windows 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-artisans-guide-to-animation-enchantment/"><u>[Updated] The Artisan's Guide to Animation Enchantment</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-mastery-of-transferring-multitudes-of-tiktok-videos/"><u>2024 Approved  Mastery of Transferring Multitudes of TikTok Videos</u></a></li>
<li><a href="https://win11.techidaily.com/master-system-configurations-optimizing-usage-options/"><u>Master System Configurations: Optimizing Usage Options</u></a></li>
<li><a href="https://win11.techidaily.com/the-intelligent-os-shift-ai-redefining-windows-software/"><u>The Intelligent OS Shift: AI Redefining Windows Software</u></a></li>
<li><a href="https://win11.techidaily.com/the-chronometers-comeback-recovering-windows-time-service/"><u>The Chronometer's Comeback: Recovering Windows Time Service</u></a></li>
<li><a href="https://win11.techidaily.com/winning-smoothly-eradicate-lags-from-star-wars-bf2-on-pc/"><u>Winning Smoothly: Eradicate Lags From Star Wars BF2 on PC</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-reactivating-razer-device-detection-by-synapse-software/"><u>Solutions for Reactivating Razer Device Detection by Synapse Software</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-resolving-non-operational-wsresetexe-in-windows/"><u>Troubleshooting: Resolving Non-Operational WSReset.exe in Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-xiaomi-13t-pro-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock Xiaomi 13T Pro Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-the-special-traits-of-ai-machines/"><u>Understanding the Special Traits of AI Machines</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-high-fidelity-playback-of-games-using-obs/"><u>[Updated] High Fidelity Playback of Games Using OBS</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-vivo-y78-5g-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Vivo Y78 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-power-indicators-full-charge-alerts-for-windows-11/"><u>Mastering Power Indicators: Full Charge Alerts for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/simplified-techniques-to-discard-a-drives-divisional-structure-in-windows/"><u>Simplified Techniques to Discard a Drive's Divisional Structure in Windows</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-the-experts-blueprint-boosting-income-via-vimeo-advertising/"><u>[Updated] 2024 Approved  The Expert's Blueprint  Boosting Income via Vimeo Advertising</u></a></li>
<li><a href="https://win11.techidaily.com/from-minuscule-to-monumental-boosting-windows-11-icon-sizes/"><u>From Minuscule to Monumental - Boosting Windows 11 Icon Sizes</u></a></li>
<li><a href="https://fox-helps.techidaily.com/panasonics-hx-a1-the-wearable-action-camera-revealed/"><u>Panasonic’s HX-A1 - The Wearable Action Camera Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/1719352195023-quick-fixes-for-your-windows-hurdles-and-complications/"><u>Quick Fixes for Your Windows Hurdles & Complications</u></a></li>
<li><a href="https://win11.techidaily.com/mellowing-down-post-high-life-hectic-windows-routine/"><u>Mellowing Down Post-High Life Hectic Windows Routine</u></a></li>
<li><a href="https://win11.techidaily.com/quick-disconnect-solution-non-operative-printer-removal-in-win-1011/"><u>Quick Disconnect Solution: Non-Operative Printer Removal in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/sharpen-outlook-response-in-the-windows-realm/"><u>Sharpen Outlook Response in the Windows Realm</u></a></li>
<li><a href="https://win11.techidaily.com/stress-free-script-repair-quick-fixes-for-windows-issues/"><u>Stress-Free Script Repair: Quick Fixes for Windows Issues</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-note-visibility-in-win-11/"><u>Maximizing Note Visibility in Win 11</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-conquering-background-hum-comprehensive-strategies-for-sound-control-with-audacity/"><u>New In 2024, Conquering Background Hum Comprehensive Strategies for Sound Control with Audacity</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-expert-advice-on-free-youtube-events-without-extra-cost-for-2024/"><u>[Updated] Expert Advice on Free Youtube Events without Extra Cost for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/win-friendly-methods-to-resolve-error-1-in-games/"><u>Win-Friendly Methods to Resolve Error 1 in Games</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/1715683919937-how-to-choose-between-filmora-and-democreator/"><u>How to Choose Between Filmora and Democreator?</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/quick-quill-the-best-caption-apps-for-your-photos-iosandroid-for-2024/"><u>Quick Quill  The Best Caption Apps for Your Photos (iOS/Android) for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/excel-in-windows-top-5-productivity-enhancers-you-cant-miss/"><u>Excel in Windows: Top 5 Productivity Enhancers You Can't Miss</u></a></li>
</ul></div>
