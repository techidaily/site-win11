---
title: Altering Security Protocols for Generalist Windows User
date: 2024-07-13T09:51:58.722Z
updated: 2024-07-14T09:51:58.722Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Altering Security Protocols for Generalist Windows User
excerpt: This Article Describes Altering Security Protocols for Generalist Windows User
keywords: Windows Security Update,Protocol Adjustment Tips,Secure Win User Access,General User Protocol,Enhanced Windows Protection,Optimize Window's Safety,Streamlining User Security
thumbnail: https://thmb.techidaily.com/8b5881e327b9c1ba2eb90535b5e52b8fb37d29efd85f95b1f8c43ff4375091ae.jpg
---

## Altering Security Protocols for Generalist Windows User

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

## The UAC Behaviors Available for Standard User Accounts

 Unlike when [changing UAC behaviors for administrator accounts](https://www.makeuseof.com/change-user-access-control-works-administrators-windows/), the behaviors for standard user accounts are a little more limited. According to the [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-standard-users) website, here are the behaviors you can choose and what they mean:

* **Automatically deny elevation requests**: This option returns an **Access denied** error message to standard users when they try to perform an operation that requires elevation of privilege. Most organizations that run desktops as standard users configure this policy to reduce help desk calls.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a different username and password. If the user enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the user to type an administrative username and password. If the user enters valid credentials, the operation continues with the applicable privilege.

 The default UAC behavior for standard user accounts is **Prompt for credentials**, but Microsoft recommends you change it to **Automatically deny elevation requests**. That way, only users with administrator accounts can decide how the UAC behaves and make choices that will keep the computer safe.

## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
3. Expand the dropdown and choose a different UAC behavior.  
![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.
3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  
![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

 Now restart your computer to allow the changes to take effect.

## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://iphone-unlock.techidaily.com/complete-fixes-to-solve-apple-iphone-15-pro-randomly-asking-for-apple-id-password-drfone-by-drfone-ios/"><u>Complete Fixes To Solve Apple iPhone 15 Pro Randomly Asking for Apple ID Password | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-the-ultimate-list-of-free-mp4-video-editing-software-for-2024/"><u>New The Ultimate List of Free MP4 Video Editing Software for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-11-best-location-changers-for-motorola-g54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 11 Best Location Changers for Motorola G54 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-and-repairing-windows-enter-key-issues/"><u>Diagnosing and Repairing Windows Enter Key Issues</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-a-comfortable-computing-environment-configuring-active-periods-and-managing-updates-in-windows-11/"><u>Crafting a Comfortable Computing Environment: Configuring Active Periods & Managing Updates in Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/google-pixel-7a-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Pixel 7a Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-steam-connectivity-issues-with-quick-solutions/"><u>Enhancing Steam Connectivity Issues with Quick Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-correcting-virtualboxs-0x80004005-error/"><u>Mastering the Art of Correcting VirtualBox's 0X80004005 Error</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-humor-highlights-tiktoks-funniest-newcomers-for-2024/"><u>[New] Humor Highlights  TikTok's Funniest Newcomers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-failed-outlook-notification-popups/"><u>Addressing Failed Outlook Notification Popups</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/cross-platform-audio-transcription-turning-text-into-mp3-clips-for-2024/"><u>Cross-Platform Audio Transcription Turning Text Into MP3 Clips for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-simple-steps-for-correction-of-character-map-errors/"><u>Unveiling Simple Steps for Correction of Character Map Errors</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-inside-top-15-emotes-a-look-at-the-masters-of-creation/"><u>In 2024, Inside Top 15 Emotes  A Look at the Masters of Creation</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-troubled-waters-eliminating-error-code-80080300-in-win11-tech/"><u>Navigate Through Troubled Waters: Eliminating Error Code 80080300 in Win11 Tech</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-steps-to-successful-remote-podcasting/"><u>[Updated] In 2024, Steps to Successful Remote Podcasting</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-revolutionizing-video-content-analyzing-tiktok-and-snapchats-innovation/"><u>[Updated] 2024 Approved  Revolutionizing Video Content  Analyzing TikTok and Snapchat’s Innovation</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-integrating-secondary-shots-a-filmmakers-blueprint/"><u>In 2024, Integrating Secondary Shots  A Filmmaker's Blueprint</u></a></li>
<li><a href="https://driver-install.techidaily.com/perfect-intel-windows-drivers-timing-and-techniques/"><u>Perfect Intel Windows Drivers: Timing and Techniques</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-culinary-chronicles-global-eats-showcased-by-tiktok/"><u>In 2024, Culinary Chronicles  Global Eats Showcased by TikTok</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-solving-error-code-31-in-windows-systems/"><u>Understanding and Solving Error Code 31 in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/securing-windows-11-with-additional-firewall-options-via-context-menu/"><u>Securing Windows 11 with Additional Firewall Options via Context Menu</u></a></li>
<li><a href="https://win11.techidaily.com/system-tray-simplified-the-art-of-minimizing-apps-on-windows/"><u>System Tray Simplified: The Art of Minimizing Apps on Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-top-15-augmented-reality-games-like-pokemon-go-to-play-on-vivo-v27e-drfone-by-drfone-virtual-android/"><u>In 2024, Top 15 Augmented Reality Games Like Pokémon GO To Play On Vivo V27e | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/supercharging-valorant-downloads-on-slow-systems/"><u>Supercharging Valorant Downloads on Slow Systems</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-windows-11-webcam-problem-a00f4289-expedition/"><u>Eradicating Windows 11 Webcam Problem: A00F4289 Expedition</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-8-best-multi-subtitles-translators-you-shouldnt-miss/"><u>New 8 Best Multi-Subtitles Translators You Shouldnt Miss</u></a></li>
<li><a href="https://win11.techidaily.com/systematic-solutions-locating-and-correcting-windows-errors-via-the-power-of-command-prompt/"><u>Systematic Solutions: Locating & Correcting Windows Errors via the Power of Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-business-best-windows-time-management-and-productivity-software/"><u>Boost Your Business: Best Windows Time Management and Productivity Software</u></a></li>
<li><a href="https://win11.techidaily.com/skirting-enforced-driver-checks-for-easier-updates/"><u>Skirting Enforced Driver Checks for Easier Updates</u></a></li>
<li><a href="https://win11.techidaily.com/orchestrated-workflows-joining-ifttt-and-to-do/"><u>Orchestrated Workflows: Joining IFTTT and To-Do</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-xiaomi-redmi-note-12-proplus-5g-by-drfone-android/"><u>In 2024, Complete Review & Guide to Techeligible FRP Bypass and More For Xiaomi Redmi Note 12 Pro+ 5G</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-mastering-audio-adjustment-on-youtube-devices/"><u>In 2024, Mastering Audio Adjustment on YouTube Devices</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-can-you-transfer-files-from-oneplus-open-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How Can You Transfer Files From OnePlus Open To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-windows-disk-space-save-personal-files/"><u>Amplify Windows Disk Space, Save Personal Files</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-touch-screen-on-realme-c55-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Realme C55 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/tidy-up-your-machine-best-windows-software-to-ditch/"><u>Tidy Up Your Machine: Best Windows Software to Ditch</u></a></li>
<li><a href="https://howto.techidaily.com/android-screen-stuck-general-lava-yuva-2-partly-screen-unresponsive-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Screen Stuck General Lava Yuva 2 Partly Screen Unresponsive | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-sharpen-your-focus-tips-for-zooming-inout-on-instagram-stories/"><u>[Updated] In 2024, Sharpen Your Focus  Tips for Zooming In/Out on Instagram Stories</u></a></li>
<li><a href="https://win11.techidaily.com/4-cool-things-you-can-do-with-windows-11-god-mode/"><u>4 Cool Things You Can Do With Windows 11 God Mode</u></a></li>
<li><a href="https://win11.techidaily.com/breeze-through-blurred-taskbars-in-windows-11/"><u>Breeze Through Blurred Taskbars in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-call-logs-from-samsung-galaxy-xcover-7-by-fonelab-android-recover-call-logs/"><u>How To  Restore Missing Call Logs from Samsung Galaxy XCover 7</u></a></li>
<li><a href="https://win11.techidaily.com/securing-save-configurations-in-your-windows-pubg-game/"><u>Securing Save Configurations in Your Windows PUBG Game</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-directx-setup-failures/"><u>Steps to Resolve DirectX Setup Failures</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-portable-balancing-system-for-video-capture/"><u>[New] Portable Balancing System for Video Capture</u></a></li>
<li><a href="https://win11.techidaily.com/the-window-whisperers-guide-to-unveiling-off-screen-apps-in-win-1011-6-proven-steps/"><u>The Window Whisperer's Guide to Unveiling Off-Screen Apps in Win 10/11 (6 Proven Steps)</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-capturecraft-in-depth-analysis-of-screen-capture-tech/"><u>[Updated] In 2024, CaptureCraft  In-Depth Analysis of Screen Capture Tech</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-chromatic-balance-and-visual-storytelling/"><u>2024 Approved  Chromatic Balance and Visual Storytelling</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-exploration-of-win11s-voice-control-shortcuts/"><u>A Detailed Exploration of Win11's Voice Control Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/journey-to-greatness-your-ultimate-new-pc-apps/"><u>Journey to Greatness: Your Ultimate New PC Apps</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-intel-wi-fi-6a-driver-failure-in-windows-os/"><u>Solutions for Intel Wi-Fi 6A Driver Failure in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/windows-mastery-directing-app-and-browser-traffic/"><u>Windows Mastery: Directing App and Browser Traffic</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-from-sd-to-hd-a-beginners-journey-to-higher-video-quality/"><u>New In 2024, From SD to HD A Beginners Journey to Higher Video Quality</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-mastering-social-snagging-5-chrome-hdl-vids/"><u>[Updated] In 2024, Mastering Social Snagging  5 Chrome HDL Vids</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-inaccessible-window-resolutions-8-simple-steps/"><u>Fixing Inaccessible Window Resolutions: 8 Simple Steps</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-integration-web-pages-as-windows-tools/"><u>Seamless Integration: Web Pages as Windows Tools</u></a></li>
<li><a href="https://win11.techidaily.com/stepwise-guide-to-amplifying-virtual-memory-on-microsofts-latest-os/"><u>Stepwise Guide to Amplifying Virtual Memory on Microsoft's Latest OS</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-the-delicate-process-of-unjoining-discords-for-2024/"><u>[Updated] The Delicate Process of Unjoining Discords for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-process-to-remove-wsl-from-windows/"><u>Mastering the Process to Remove WSL From Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-silence-the-expiring-windows-license-message/"><u>How To Silence the Expiring Window's License Message</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-swiftly-finding-and-fixing-windows-update-problems/"><u>Strategies for Swiftly Finding and Fixing Windows Update Problems</u></a></li>
<li><a href="https://win11.techidaily.com/tailored-web-safety-including-reliable-domains-in-windows-11/"><u>Tailored Web Safety: Including Reliable Domains in Windows 11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-explore-top-10-best-photo-layering-and-editing-apps-iosandroid/"><u>In 2024, Explore Top 10 Best Photo Layering & Editing Apps iOS/Android</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/top-10-ipad-slideshow-apps-to-create-a-slideshow-for-2024/"><u>Top 10 iPad Slideshow Apps to Create a Slideshow for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-xiaomi-redmi-note-12-4g-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Transfer Music from Xiaomi Redmi Note 12 4G to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-user-interaction-ai-integration-into-windows-11/"><u>Redefining User Interaction: AI Integration Into Windows 11</u></a></li>
</ul></div>
