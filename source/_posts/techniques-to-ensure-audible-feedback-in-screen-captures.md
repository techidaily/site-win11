---
title: Techniques to Ensure Audible Feedback in Screen Captures
date: 2024-07-13T10:27:15.572Z
updated: 2024-07-14T10:27:15.572Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques to Ensure Audible Feedback in Screen Captures
excerpt: This Article Describes Techniques to Ensure Audible Feedback in Screen Captures
keywords: Audio Verification Techniques,Sound Feedback Methods,Effective Clear Noise,Dialogue Clarity Boosting,Precision in Screen Capture,Audible Feedback Strategies,Enhancing Visibility Quality
thumbnail: https://thmb.techidaily.com/fb8053ac7214659fa378f042df998d4365da978dd3a640439d6ee68045b0a185.jpg
---

## Techniques to Ensure Audible Feedback in Screen Captures

 The screen recording feature in Microsoft PowerPoint can be useful for recording tutorials or training videos on your computer. But what if PowerPoint fails to capture the audio when you record the screen of your Windows computer?

 If you are annoyed by a similar issue, here are some troubleshooting tips that will help.

## 1\. Restart PowerPoint

 Temporary issues with PowerPoint can sometimes disrupt its ability to capture audio on your Windows computer. If it’s just a one-off glitch, simply closing and reopening PowerPoint should fix the problem.

 Press **Ctrl + Shift + Esc** to open the Task Manager. In the **Processes** tab, right-click on **Microsoft PowerPoint** and select the **End task** option.

![Close PowerPoint Using Task Manager on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/close-powerpoint-using-task-manager-on-windows.jpg)

 Right-click on the **PowerPoint** shortcut and select **Run as administrator**. After that, try to create a screen recording and see if PowerPoint records the audio this time.

## 2\. Allow Desktop Apps to Use Your Microphone

 Another reason why PowerPoint might fail to record audio is if you have denied desktop apps permission to access your microphone. Here's how you can change that.

1. Press **Win + I** to open the Settings app.
2. Head to **Privacy & security > App permissions > Microphone**.
3. Enable the toggle next to **Let desktop apps access your microphone**.  
![Allow Desktop Apps to Access Microphone on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/allow-desktop-apps-to-access-microphone-on-windows.jpg)

 Once you complete the above steps, all your desktop apps, including PowerPoint, should be able to use your microphone.

## 3\. Check Which Device Is Set as the Default Microphone on Windows

 Are there several audio devices connected to your Windows computer? If so, you need to ensure that you have selected the correct microphone on Windows.

 To view or change the default microphone on Windows, use these steps:

1. Click the **magnifying icon** on the taskbar to access the search menu.
2. Type **sound settings** in the box and press **Enter**.
3. Under the **Input** tab, select your preferred audio device.  
![Select Default Microphone in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-default-microphone-in-windows.jpg)

 Is your microphone not showing up in the Settings app? Apply the necessary [fixes to get Windows to detect your microphone](https://www.makeuseof.com/windows-not-detecting-microphone/).

## 4\. Disable Hardware Graphics Acceleration in PowerPoint

 While enabling the hardware graphics acceleration feature in PowerPoint can improve its performance, the feature may not work seamlessly all the time. When this happens, you are likely to run into all kinds of issues, including issues with the screen recorder.

 According to a post on [Microsoft Community](https://answers.microsoft.com/en-us/msoffice/forum/all/audio-not-working-on-my-ppt-recording/79c77eae-2f86-4c09-a3d6-5fc4b3d89c58), several users managed to fix this particular issue by disabling the hardware graphics acceleration in PowerPoint. You can also give it a try with these steps:

1. Open PowerPoint on your PC.
2. Click the **File** menu in the top left corner.
3. Select **Options** from the left pane.
4. In the PowerPoint Options window, use the left pane to switch to the **Advanced** tab.
5. Scroll down to the **Display** section.
6. Clear the checkboxes that read **Disable hardware graphics acceleration** and **Disable Slide Show hardware graphics acceleration**.
7. Click **OK** to apply the changes.  
![Disable Hardware Acceleration in PowerPoint](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-hardware-acceleration-in-powerpoint.jpg)

 Restart PowerPoint after this for changes to take effect.

## 5\. Run the Windows Recording Audio Troubleshooter

 Windows offers several useful troubleshooters for fixing common issues on your computer. In this case, running the Recording Audio troubleshooter can help. It can automatically detect any issues with PowerPoint's audio recording functionality and fix them.

 To run the Recording Audio troubleshooter:

1. Right-click on the **Start** icon and select **Settings** from the list.
2. Navigate to **System > Troubleshoot > Other troubleshooters**.
3. Click the **Run** button next to **Recording Audio**.  
![Recording Audio Troubleshooter on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/recording-audio-troubleshooter-on-windows.jpg)

 Allow the troubleshooter to find and fix any issues, and then check if PowerPoint can record the audio.

## 6\. Restart the Windows Audio Services

 Windows relies on certain audio services to capture and record your audio. Typically, these services start automatically every time you boot your computer.

 However, if one of these services encounters any problems, your apps and programs may fail to record the audio. In most cases, you can fix such issues by simply restarting the audio services on your PC.

 To do so, use these steps:

1. Press **Win + S** to open the search menu.
2. Type **services** in the search box and select the first result that appears.
3. In the Services window, locate the **Windows Audio** service. Right-click on it and select **Restart**.
4. Similarly, restart the **Windows Audio Endpoint Builder** service as well.  
![Restart Windows Audio Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-windows-audio-service.jpg)

 Using the Services app isn't the only way to manage services on Windows. You can also use Task Manager, Command Prompt and PowerShell to [start, stop or restart services on Windows](https://www.makeuseof.com/how-to-start-stop-service-windows/).

## 7\. Start PowerPoint in Safe Mode

 One of your add-ins may be acting up and causing PowerPoint to malfunction. To check for this possibility, you need to open PowerPoint in safe mode. For that, press **Win + R** to open the Run dialog box. Type **PowerPnt /safe** in the text field and press **Enter**.

 After opening PowerPoint in safe mode, try creating a screen recording and see if it records audio as expected. If it does, it means one of your add-ins is causing the problem. To identify the one causing the issue, you will need to disable all of your add-ins and then re-enable them one at a time. Here’s how to do that.

1. In PowerPoint, click the **File** menu in the top left corner.
2. Select **Options** in the left pane.
3. In the PowerPoint Options window, switch to the **Add-ins** tab.
4. Click the drop-down menu next to **Manage** and select **COM Add-ins**.
5. Click the **Go** button.
6. Clear the checkboxes to disable add-ins and then click **OK**.  
![Disable Add-ins in PowerPoint](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-add-ins-in-powerpoint.jpg)

 Restart PowerPoint after this, and then enable your add-ins one at a time until the issue occurs again. Once you find the faulty add-in, consider removing it.

## 8\. Update Microsoft PowerPoint

 Such issues can also occur if you are using an outdated version of PowerPoint. To update PowerPoint, navigate to **File > Account**. Click on **Update Options** and select **Update Now**.

![Update PowerPoint on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-powerpoint-on-windows.jpg)

 Wait for Microsoft Office to update PowerPoint, and the issue should not occur after that.

## 9\. Run the Office Repair Tool

 If PowerPoint still won’t record audio while recording the screen on Windows, you can run the Office repair tool as a last resort. Here are the steps for the same.

1. Press **Win + S** to open the search menu.
2. Type **control panel** in the text box and press **Enter**.
3. Click on **Programs and Features**.
4. Locate the **Microsoft Office suite** on the list. Right-click on it and select **Change**.
5. Select the **Quick Repair** option and hit the **Repair** button.  
![Repair Microsoft Office](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-office.jpg)

 If the problem persists even after this, you can run the Office repair tool again to perform an **Online Repair**. Note that this process may take a little longer to complete, as the tool will attempt a more thorough repair.

## Get PowerPoint to Record Your Audio Again on Windows

 It can be frustrating when PowerPoint stops recording audio on your Windows computer. In any case, one of the above tips should help fix the underlying issue for good.

 If you are annoyed by a similar issue, here are some troubleshooting tips that will help.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/approaches-to-compatibility-issues-for-windows-packages/"><u>Approaches to Compatibility Issues for Windows Packages</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-inability-to-find-powershell-scripts/"><u>Addressing Windows Inability to Find PowerShell Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-not-sufficient-usb-issue-in-windows/"><u>Addressing “Not Sufficient USB” Issue in Windows</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/transforming-your-video-content-making-square-format-footage-for-instagram-for-2024/"><u>Transforming Your Video Content  Making Square-Format Footage for Instagram for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/add-ons-for-the-classics-mastering-achievements-via-retroarch-software-guide/"><u>Add-Ons for the Classics: Mastering Achievements via Retroarch Software Guide</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-instant-tiktok-content-access-a-step-by-step/"><u>[Updated] Instant TikTok Content Access - A Step-by-Step</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-ig-boomerangs-crafting-compelling-circular-content/"><u>[Updated] 2024 Approved  IG Boomerangs  Crafting Compelling Circular Content</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-upcoming-vr-masterpieces-top-5-new-titles-for-playstation-vr-enthusiasts/"><u>[Updated] Upcoming VR Masterpieces  Top 5 New Titles for PlayStation VR Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-compression-and-archiving-tools/"><u>Activating Windows Compression & Archiving Tools</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-10-best-meme-templates/"><u>In 2024, Top 10 Best Meme Templates</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-success-reinstalling-microsofts-pc-manager-in-winxp/"><u>Achieve Success: Reinstalling Microsoft's PC Manager in WinXP</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-techniques-for-capturing-uac-alerts/"><u>Advanced Techniques for Capturing UAC Alerts</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-apple-iphone-11-pro-max-to-pc-via-usb-drfone-by-drfone-ios/"><u>How to Mirror Apple iPhone 11 Pro Max to PC via USB? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-xbox-apps-audio-challenges-in-windows-1011/"><u>Addressing Xbox App's Audio Challenges in Windows 10/11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-crafting-content-step-by-step-guide-to-youtube-video-editing-for-2024/"><u>[New] Crafting Content  Step by Step Guide to YouTube Video Editing for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-expert-strategies-for-efficient-video-editing-with-gopro-studio/"><u>In 2024, Expert Strategies for Efficient Video Editing with GoPro Studio</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-share-glitches-with-nvidia/"><u>Addressing Windows 11 Share Glitches with NVIDIA</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-streamlined-converting-top-six-free-ios-apps-for-youtube-to-mp3/"><u>2024 Approved  Streamlined Converting  Top Six Free iOS Apps for YouTube-to-MP3</u></a></li>
<li><a href="https://fox-access.techidaily.com/introduce-audio-files-to-premiere-pro-timeline/"><u>Introduce Audio Files to Premiere Pro Timeline</u></a></li>
<li><a href="https://win11.techidaily.com/ace-the-art-of-completing-a-perfect-windows-update/"><u>Ace the Art of Completing a Perfect Window's Update</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-a-network-locked-infinix-note-30i-phone-by-drfone-android/"><u>In 2024, How to Unlock a Network Locked Infinix Note 30i Phone?</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-frustration-with-11-troubleshooting-windows-tips/"><u>Avoid Frustration with 11 Troubleshooting Windows Tips</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-samsung-galaxy-a15-4g-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Samsung Galaxy A15 4G Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-windows-11-laptop-touchpad-sensitivity-guide/"><u>Adjusting Windows 11 Laptop Touchpad Sensitivity Guide</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/simplified-steps-for-capturing-google-voice-calls-for-2024/"><u>Simplified Steps for Capturing Google Voice Calls for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-system32-folder-on-windows-11/"><u>Accessing System32 Folder on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-invalid-profile-alerts-on-windows-1011/"><u>Addressing Invalid Profile Alerts on Windows 10/11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-my-spouse-from-spying-on-my-realme-gt-neo-5-drfone-by-drfone-virtual-android/"><u>How to Stop My Spouse from Spying on My Realme GT Neo 5 | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-blend-photos-effortlessly-in-real-time/"><u>[Updated] Blend Photos Effortlessly in Real-Time</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-msvcr110dll-disappearance/"><u>Addressing msvcr110.dll Disappearance</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-keystrokes-mastery-via-typingaid/"><u>Accelerating Keystrokes: Mastery via TypingAid</u></a></li>
<li><a href="https://win11.techidaily.com/activatingdeactivating-filter-keys-on-microsoft-os/"><u>Activating/Deactivating Filter Keys on Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/aim-for-zero-error-windows-1011-bin-repair-guide/"><u>Aim for Zero-Error: Windows 10/11 Bin Repair Guide</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-epic-games-account-unlock-on-windows/"><u>Addressing Epic Games Account Unlock on Windows</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-unveiling-the-hidden-gems-of-tiktok-elements-for-creators/"><u>[New] In 2024, Unveiling the Hidden Gems of TikTok Elements for Creators</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-domain-services-print-problems-in-win11/"><u>Addressing Domain Services Print Problems in Win11</u></a></li>
<li><a href="https://facebook.techidaily.com/understanding-anonymity-options-in-social-networks/"><u>Understanding Anonymity Options in Social Networks</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-win-and-apple-users-favorites-top-picks-for-audio-recording-technology-mp3-for-2024/"><u>Updated Win & Apple Users Favorites Top Picks for Audio Recording Technology (MP3) for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/aesthetic-alchemy-how-to-seamlessly-change-windows-11-themes-and-enrich-your-workspace/"><u>Aesthetic Alchemy: How to Seamlessly Change Windows 11 Themes and Enrich Your Workspace</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-the-character-visualization-tool/"><u>Accessing the Character Visualization Tool</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-high-usage-issues-of-unrealcefsubprocess-on-windows-machines/"><u>Addressing High Usage Issues of UnrealCEFSubprocess on Windows Machines</u></a></li>
<li><a href="https://win11.techidaily.com/accurate-printouts-from-powerpoint-in-windows-9-top-fixes-unveiled/"><u>Accurate Printouts From PowerPoint in Windows: 9 Top Fixes Unveiled</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/26-low-cost-strategies-capture-webinars-without-spending-money/"><u>26 Low-Cost Strategies  Capture Webinars Without Spending Money</u></a></li>
<li><a href="https://win11.techidaily.com/activating-local-administrator-tools-in-windows-1110-home/"><u>Activating Local Administrator Tools in Windows 11/10 Home</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/free-top-10-best-websites-to-download-sound-clips-for-videos-for-2024/"><u>FREE Top 10 Best Websites to Download Sound Clips for Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/activate-windows-11-task-managers-search-functionality/"><u>Activate Windows 11 Task Manager's Search Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-onedrives-incorrect-tag-issue/"><u>Addressing Windows Error: OneDrive’s Incorrect Tag Issue</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/expert-choice-top-10-windows-and-pc-tiktok-editors-for-2024/"><u>Expert Choice  Top 10 Windows & PC TikTok Editors for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-avoiding-unwanted-accounts-on-insta/"><u>[Updated] Avoiding Unwanted Accounts on Insta</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unveil-images-clearly-10-online-editors-guide-for-2024/"><u>Unveil Images Clearly  10 Online Editors' Guide for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/review-of-sound-forge/"><u>Review of Sound Forge</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-honor-v-purse-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Honor V Purse | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-system-restore-problem-code-0x80780119/"><u>Addressing System Restore Problem: Code 0X80780119</u></a></li>
<li><a href="https://win11.techidaily.com/access-windows-greatness-through-microsoft-store/"><u>Access Windows Greatness Through Microsoft Store</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-navigating-the-rules-of-youtube-video-documentation/"><u>[Updated] Navigating the Rules of YouTube Video Documentation</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-new-windows-editions-which-fits-you-best-home-or-pro/"><u>Assessing New Windows Editions: Which Fits You Best, Home or Pro?</u></a></li>
<li><a href="https://win11.techidaily.com/automate-app-colors-with-the-help-of-windows-11-features/"><u>Automate App Colors with the Help of Windows 11 Features</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-photos-from-pixel-8-by-fonelab-android-recover-photos/"><u>How to Rescue Lost Photos from Pixel 8?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/ice-acceleration-showdown-at-the-olympics-2022-for-2024/"><u>Ice Acceleration Showdown at the Olympics, 2022 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/augment-context-menu-with-higher-powers/"><u>Augment Context Menu with Higher Powers</u></a></li>
<li><a href="https://activate-lock.techidaily.com/full-guide-to-apple-iphone-6-icloud-bypass-by-drfone-ios/"><u>Full guide to Apple iPhone 6 iCloud Bypass</u></a></li>
<li><a href="https://win11.techidaily.com/activating-prints-with-secure-browsing-feature-edge/"><u>Activating Prints with Secure Browsing Feature (Edge)</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-common-problems-with-windows-hello-fingerprint-detection/"><u>Addressing Common Problems with Windows Hello Fingerprint Detection</u></a></li>
<li><a href="https://fox-access.techidaily.com/best-subtitle-converters-win-and-mac-edition-leading-8-sbt-to-srtr-tools-for-2024/"><u>Best Subtitle Converters  Win & Mac Edition, Leading 8 SBT to SRTR Tools for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-take-your-video-editing-to-the-next-level-with-video-scopes/"><u>New Take Your Video Editing to the Next Level with Video Scopes</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-enhance-visibility-and-engagement-vlogs-seo-arsenal/"><u>In 2024, Enhance Visibility & Engagement  Vlog's SEO Arsenal</u></a></li>
<li><a href="https://win11.techidaily.com/activation-protocol-engaging-modernized-widget-pickers-toolset/"><u>Activation Protocol: Engaging Modernized Widget Pickers Toolset</u></a></li>
<li><a href="https://win11.techidaily.com/are-some-of-your-keyboard-keys-not-working-heres-how-to-fix-them-on-windows/"><u>Are Some of Your Keyboard Keys Not Working? Here's How to Fix Them on Windows</u></a></li>
</ul></div>
