---
title: Removing Personal Data From the Windows Login Area
date: 2024-07-13T11:05:32.028Z
updated: 2024-07-14T11:05:32.028Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Removing Personal Data From the Windows Login Area
excerpt: This Article Describes Removing Personal Data From the Windows Login Area
keywords: Remove Privacy Info,Clear Windows Login,Wipe User Details,Delete Login Data,Erase Account Info,Privacy Cleanup Windows,Unlink Personal Windows
thumbnail: https://thmb.techidaily.com/c477119574c19e1fe1c1e24c760eca970cf6d9df63cc3bc93f37a86e27d2e105.png
---

## Removing Personal Data From the Windows Login Area

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the [many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

## 2\. How to Hide Email Address From Windows Login Screen Using the Group Policy Editor

 The Group Policy Editor (or gpedit.msc) is a handy Windows tool for configuring advanced system settings. You can also this tool to hide your email address from the Windows login screen.

 Note that the Group Policy Editor is only available on Windows Professional, Education, and Enterprise editions. If your PC is running Windows Home, check out [how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the search box and select the first result that appears.
3. Use the left pane to navigate to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options** .
4. Double-click the **Interactive Logon: Display user information when the session is locked** policy on your right.
5. In the properties window, click the drop-down menu to select the**Do not display user information** option.
6. Click**Apply** followed by**OK** .  
![Hide Email From Windows Login Screen Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-group-policy-editor.jpg)
7. Next, double-click on the**Interactive logon: Do not display last user name** policy from the same section.
8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

## 3\. How to Hide Email Address From Windows Login Screen Using the Registry Editor

 If the above two methods don’t work for some reason, you can make changes to the Windows registry files to hide your email address from the login screen. For that, you’ll need to use the Registry Editor on Windows.

 When it comes to editing Registry files, it's important to be cautious as making incorrect changes can cause irreversible damage to your PC. We recommend you either back up all the registry files or create a restore point before you make any changes. If you need help with that, check our guides on [how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [how to create a restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

 Once you’re done with that, use the following steps to hide your email address from the Windows login screen via Registry Editor.

1. Press**Win + X** to open the Power User menu and select**Run** from the list.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows > System** .
5. Right-click on the**System** key and select**New > DWORD (32-bit) Value** .
6. Rename the DWORD to**BlockUserFromShowingAccountDetailsOnSignin** .
7. Double-click on the newly created DWORD and enter**1** in the**Value data** field. Then, click**OK** .  
![Hide Email From Windows Login Screen Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-registry-editor.jpg)

 Exit the Registry Editor and restart your PC for the changes to take effect.

## Hiding Your Email Address From the Windows Login Screen Is Easy

 As we just saw, hiding your personal information from the Windows login screen barely takes a couple of minutes, regardless of the method you employ.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-helps.techidaily.com/new-premier-vr-movies-for-immersive-viewing/"><u>[New] Premier VR Movies for Immersive Viewing</u></a></li>
<li><a href="https://win11.techidaily.com/missing-dxgidll-in-win11-heres-an-action-plan/"><u>Missing Dxgi.dll in Win11? Here's an Action Plan</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-sudden-freeze-and-blackout-with-steam/"><u>Resolving Sudden Freeze & Blackout with Steam</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-streamlining-your-presentations-vimeo-video-embedding-in-powerpoint/"><u>[Updated] Streamlining Your Presentations  Vimeo Video Embedding in PowerPoint</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-nokia-c22-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Nokia C22 without App | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-cash-flow-curiosity-how-much-does-the-celebrity-make/"><u>[New] Cash Flow Curiosity  How Much Does the Celebrity Make?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/the-impact-and-value-of-instagrams-self-verifying-feature/"><u>The Impact and Value of Instagram's Self-Verifying Feature</u></a></li>
<li><a href="https://win11.techidaily.com/the-importance-of-consistent-windows-data-saves/"><u>The Importance of Consistent Windows Data Saves</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-creating-revenue-streams-on-snapchat-for-2024/"><u>[New] Creating Revenue Streams on Snapchat for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-essential-mobile-apps-top-8-creativity-boosters-on-ios-and-android/"><u>[New] Essential Mobile Apps  Top 8 Creativity Boosters on iOS and Android</u></a></li>
<li><a href="https://win11.techidaily.com/the-path-to-peace-sleep-mode-strategies/"><u>The Path to Peace: Sleep Mode Strategies</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-superior-recommendations-elite-ios-audio-makers/"><u>[Updated] Superior Recommendations  Elite iOS Audio Makers</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-averting-crashes-of-epic-games-launcher/"><u>Strategies for Averting Crashes of Epic Games Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-correcting-type-mistakes-in-windows-11-zerox-error/"><u>Solutions for Correcting Type Mistakes in Windows 11 Zerox Error</u></a></li>
<li><a href="https://win11.techidaily.com/mending-the-missing-entry-in-windows-os/"><u>Mending the Missing Entry in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/propel-power-5-best-windows-optimization-strategies/"><u>Propel Power: 5 Best Windows Optimization Strategies</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-aspect-ratio-made-easy-a-calculator-and-tutorial/"><u>Updated In 2024, Aspect Ratio Made Easy A Calculator and Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/secure-your-account-transitioning-from-pin-to-password-in-windows-11/"><u>Secure Your Account: Transitioning From PIN to Password in Windows 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-video-splitting-expertise-best-recorder-verdict/"><u>[New] In 2024, Video Splitting Expertise  Best Recorder Verdict</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-copy-and-paste-on-chrome-edge-and-firefox-windows/"><u>Restoring Copy & Paste on Chrome, Edge, and Firefox (Windows)</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-from-novice-to-pro-mastering-spotify-advertisement-techniques/"><u>2024 Approved  From Novice to Pro  Mastering Spotify Advertisement Techniques</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-vimeo-insight-where-streaming-meets-originality/"><u>2024 Approved  Vimeo Insight  Where Streaming Meets Originality</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-top-10-live-audio-transformers-in-depth-analysis-and-recommendations-for-2024/"><u>New Top 10 Live Audio Transformers In-Depth Analysis and Recommendations for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-freeze-issues-photoshopping-onoff-windows-11-versions-2023/"><u>Overcoming Freeze Issues: Photoshopping On/Off Windows 11, Versions 2023</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/perfect-your-youtube-intro-step-by-step-method-a-plus-b/"><u>Perfect Your YouTube Intro  Step by Step (Method A + B)</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-windows-event-viewer-fixes/"><u>Strategies for Windows Event Viewer Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-user-initiated-windows-screen-shift/"><u>Stopping User-Initiated Windows Screen Shift</u></a></li>
<li><a href="https://win11.techidaily.com/probing-into-windows-11s-potential-for-phone-synergy/"><u>Probing Into Windows 11’S Potential for Phone Synergy</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-master-your-sketches-with-the-ultimate-mac-apps/"><u>2024 Approved  Master Your Sketches with the Ultimate Mac Apps</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-best-of-the-best-gaming-intro-makers-you-need-to-know/"><u>In 2024, Best of the Best Gaming Intro Makers You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-white-screen-on-logging-into-win1011/"><u>Overcoming White Screen on Logging Into Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/organize-like-a-pro-5-must-try-windows-folder-tricks/"><u>Organize Like a Pro: 5 Must-Try Windows Folder Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/reigniting-ram-overcoming-obstacles-in-windows/"><u>Reigniting RAM: Overcoming Obstacles in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/removing-the-0x800704cf-hurdle-in-windows-store-experience/"><u>Removing the 0X800704CF Hurdle in Windows Store Experience</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-resolve-0x80072efd-on-windows-devices/"><u>Quick Guide to Resolve 0X80072EFD on Windows Devices</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-exploring-next-gen-coding-is-av1-superior-to-vp9/"><u>[New] Exploring Next-Gen Coding  Is AV1 Superior to VP9?</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-mastering-animation-drawing-the-7-best-software-solutions/"><u>Updated In 2024, Mastering Animation Drawing The 7 Best Software Solutions</u></a></li>
<li><a href="https://howto.techidaily.com/4-ways-to-fix-android-blue-screen-of-death-on-honor-magic-5-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Ways to Fix Android Blue Screen of Death On Honor Magic 5 Pro | Dr.fone</u></a></li>
</ul></div>
