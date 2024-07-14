---
title: Configuring Idle Screen Time on Windows
date: 2024-07-13T09:48:04.368Z
updated: 2024-07-14T09:48:04.368Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Configuring Idle Screen Time on Windows
excerpt: This Article Describes Configuring Idle Screen Time on Windows
keywords: Screen Time Control,Windows Idle Limit,Idle Display Timer,Set Screen Off Time,Configuring Idle Windows,Manage Inactive Screen,Reduce Standby Hours
thumbnail: https://thmb.techidaily.com/bbb97d5449382acc8b92ab96bfb70e5ca97a93f11d2d4de93a06ce4ca47d0742.jpg
---

## Configuring Idle Screen Time on Windows

 PC security is not just about having antivirus software on your computer. You should also restrict access to your documents on your PC while you're away from your machine.

 Read on to explore how you can automatically lock your PC after a set time, even when you leave it unattended.

## How to Keep Your Windows PC Inaccessible While Your Gone

 There are lots of places you could use a PC or laptop. It could be in the office, at a conference venue, or on the go at your favorite café. And there'll be times you just need to get up to attend to something pressing.

 Fortunately, you can set your PC to lock automatically after a custom amount of time without activity. This means you can safely leave your work desk, knowing your work is safe from prying eyes.

 Of course, you can also lock your PC manually when you walk away from it—just press the**Win + L** keys together or**Ctrl + Alt + Del** and then sign out. But you could miss doing that in a rush, or if you're distracted.

 Instead, check out these methods to configure your Windows PC to lock automatically when there is no activity after a specific amount of time.

## 1\. How to Lock Your Windows PC After a Set Time via the Local Security Policy

 Using the Local Security Policy, you can set the exact time in seconds after which your PC will lock itself automatically. Make sure you're signed in as an administrator to automatically lock your PC.

 Local Security Policy is only available in the Windows 10 and 11 Pro, Education, and Enterprise editions. If you're using the Home version, skip to method two.

1. Type**Local Security Policy** in Windows Search. Click the**Local Security Policy** under**Best match** to open it. Alternatively, press the**Win + R** keys together to open the**Run** box. Type**secpol.msc** in the**Open** navigation bar and click**OK** or hit**Enter** to launch it.  
![Open Local Security Policy via Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/open-local-security-policy-via-run.jpg)
2. Click the down arrow next to**Local Policies** in the left pane to expand it.
3. Click on**Security Options** to open it.
4. The Security Options will open up in the right pane. Now scroll down to the policy named**Interactive logon: Machine inactivity limit** and double-click on it to open its properties.  
![Machine Inactivity Limit Selected in Security Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-machine-inactivity-limit-in-security-options.jpg)
5. Under the section**Machine will be locked after** , enter the time in seconds after which you want your PC to get locked automatically. This time is the time of machine inactivity or the time when your PC is idle. You can enter the time between**0** to**599940** seconds. For this tutorial, we'll enter**300 seconds** which is five minutes. Now click on**Apply** and then**OK** .
6. Finally, close the Local Security Policy window and restart your computer for the change to take effect.

 Now, when you use your PC, you will experience that your PC will lock itself after your custom timer expires. And if someone tries to unlock your PC while you're gone, it'll ask them for your password, which should keep them at bay until you get back.

 If you ever want to reverse this action and not have your PC lock automatically, just open the**Interactive logon: Machine inactivity limit** policy in**Local Security Policy** . Then just change the time or seconds to**0** —this is the default setting and will not lock your PC automatically.

## 2\. How to Lock Your Windows PC After a Specific Amount of Inactivity via the Registry Editor

 You can tweak settings in the Registry Editor to configure your PC to lock automatically after a set time. And you can do this in Windows Home and all the other Windows editions.

 However, you must be careful while making changes in the registry and should only make the changes as detailed below and not change anything else. It'd be a good idea to create a restore point in Windows before you change your registry settings. If something goes wrong, you can revert your PC to its last working state.

 Now let's go ahead and explore how to lock your PC automatically via the Registry Editor.

1. Type**Registry Editor** in**Windows Search** and select**Registry Editor** under**Best match** . Or use one of the many [ways to open the Registry Editor in Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click on**Yes** on the UAC prompt.
3. In the left pane, use the following path to reach the**System** registry key: **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System**  
![Navigate to System Key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/navigate-to-system-key-in-registry-editor.jpg)
4. Click on the**System** key in the left pane and its components will open up in the right pane. Now scroll down to get to the**InactivityTimeoutSecs** DWORD.  
![Scroll to InactivityTimeoutSecs in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/scroll-to-inactivitytimeoutsecs.jpg)
5. Double-click on the**InactivityTimeoutSecs** DWORD to modify its value. Select**Decimal** under**Base** , and under**Value data** , enter a number between**0** to**599940** —this is the time in seconds after which your PC will get locked automatically. Like in the Local Security Policy method, we'll give it a time of**300 seconds** or five minutes. Now tap on**OK** .
6. In case you do not find the**InactivityTimeoutSecs** DWORD in your registry, you can create it. Right-click on the**System** key folder in the left pane or right-click on a space in the right pane of the**System** key. Select**New** , then select**DWORD (32-bit) Value** .  
![Create InactivityTimeoutSecs DWORD in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-inactivitytimeoutsecs-dword.jpg)  
 A new value will be created in the right pane. Name it**InactivityTimeoutSecs** . Then press**Enter** .
7. Now double-click on**InactivityTimeoutSecs** DWORD, and enter the time after which you want your PC to get locked.
8. Finally, close the Registry Editor and restart your PC to apply the changes.

 Now your PC will get locked if you're not using it or are away from it after the time you have set in the Registry Editor. If you're on a Windows 11 machine, you can also [explore a few other ways to lock your PC](https://www.makeuseof.com/windows-11-ways-to-lock/) .

 To stop your PC from getting locked automatically, modify the**InactivityTimeoutSecs** DWORD value in the Registry Editor by changing the time to**0** seconds.

## Work Worry-Free on Your Windows PC With a Custom Time-Out Lock

 Now never be tense about someone getting access to your PC or your work getting stolen while you're away from your PC. Use one of the above methods to automatically lock your PC after a set time.

 You can also explore how to set up Dynamic Lock using your phone to automatically lock your PC when you move away from it.


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
<li><a href="https://win11.techidaily.com/techniques-to-stop-windows-from-misidentifying-audio-device/"><u>Techniques to Stop Windows From Misidentifying Audio Device</u></a></li>
<li><a href="https://win11.techidaily.com/which-window-suits-you-best-home-versus-pro-in-windows-11/"><u>Which Window Suits You Best? Home Versus Pro in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/win11-addressing-inaudible-wireless-speaker-issues/"><u>Win11: Addressing Inaudible Wireless Speaker Issues</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-spark-social-media-flames-facebook-success-hacks/"><u>[Updated] Spark Social Media Flames  Facebook Success Hacks</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/transform-insta-videos-into-mp4-format-expert-methods-revealed-for-2024/"><u>Transform Insta Videos Into MP4 Format  Expert Methods Revealed for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-guide-implementing-animated-wallpapers-on-desktop/"><u>Windows 11 Guide: Implementing Animated Wallpapers on Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-cant-connect-nvidia-error-on-win-11-devices/"><u>Bypassing the Can't Connect Nvidia Error on Win 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/winning-over-full-screen-issues-in-sonic-adventure-on-windows-11/"><u>Winning Over Full-Screen Issues in Sonic Adventure on Windows 11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-seamless-tactic-for-igtv-stories-integration/"><u>[New] In 2024, Seamless Tactic for IGTV Stories Integration</u></a></li>
<li><a href="https://win11.techidaily.com/unseen-networks-windows-wi-fi-security-guide/"><u>Unseen Networks: Windows Wi-Fi Security Guide</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-optimal-msoffice-functionality-on-w11/"><u>Achieving Optimal MSOffice Functionality on W11</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-blackout-getting-out-of-dark-mode/"><u>Bypassing The Blackout: Getting Out Of Dark Mode</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-navigating-industry-titans-a-creators-guide-to-mnc-deals/"><u>[Updated] Navigating Industry Titans  A Creator's Guide to MNC Deals</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-infinix-note-30-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Infinix Note 30 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-infinix-note-30-pro-by-phone-number-drfone-by-drfone-virtual-android/"><u>How to Track Infinix Note 30 Pro by Phone Number | Dr.fone</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-how-to-make-a-photo-collage-in-microsoft-word/"><u>Updated 2024 Approved How To Make a Photo Collage in Microsoft Word</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-superior-methods-for-soundless-footage/"><u>[Updated] Superior Methods for Soundless Footage</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-find-ispoofer-pro-activation-key-on-samsung-galaxy-a34-5g-drfone-by-drfone-virtual-android/"><u>How to Find iSpoofer Pro Activation Key On Samsung Galaxy A34 5G? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-realme-c67-5g-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Realme C67 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unshackle-chromiums-network-access-via-windows-settings-blockers/"><u>Unshackle Chromium's Network Access via Windows Settings Blockers</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unlocking-visual-treasures-without-cost/"><u>Unlocking Visual Treasures Without Cost</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-from-stream-to-file-vimeo-hd-to-mp4-methods/"><u>[New] 2024 Approved  From Stream to File  Vimeo HD to MP4 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-microsoft-can-improve-windows-11s-clipboard-history/"><u>9 Ways Microsoft Can Improve Windows 11'S Clipboard History</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-channel-specific-choices-top-microphone-picks-adapted-to-each-youtube-niche/"><u>[New] Channel-Specific Choices  Top Microphone Picks Adapted To Each YouTube Niche</u></a></li>
<li><a href="https://win11.techidaily.com/terminal-and-powershell-delving-into-their-distinct-uses/"><u>Terminal and PowerShell: Delving Into Their Distinct Uses</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-make-a-movie-on-your-mac-tips-and-tricks-for-success-for-2024/"><u>New Make a Movie on Your Mac Tips and Tricks for Success for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-windows-for-secure-external-drive-handling/"><u>Configuring Windows for Secure External Drive Handling</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-potential-the-best-9-features-in-new-outlook/"><u>Unlocking Potential: The Best 9 Features in New Outlook</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-screen-recorder-showdown-for-gamers/"><u>In 2024, Screen Recorder Showdown for Gamers</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-unveiling-the-best-ways-to-capture-your-minecraft-quests-on-a-mac/"><u>[New] Unveiling the Best Ways to Capture Your Minecraft Quests on a Mac</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/digital-arena-100plus-titles-for-the-true-gamer/"><u>Digital Arena  100+ Titles for the True Gamer</u></a></li>
<li><a href="https://win11.techidaily.com/windows-photos-shortcuts-for-the-savvy-editor/"><u>Windows Photos Shortcuts for the Savvy Editor</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-desktop-no-overlaps/"><u>Streamline Your Desktop: No Overlaps</u></a></li>
<li><a href="https://win11.techidaily.com/curbing-the-catastrophe-recycle-bin-errors-in-win1011/"><u>Curbing the Catastrophe: Recycle Bin Errors in Win10/11</u></a></li>
<li><a href="https://youtube-web.techidaily.com/iscal-landmarks-understanding-mr-beasts-financial-growth-for-2024/"><u>[New] Fiscal Landmarks  Understanding Mr. Beast’s Financial Growth for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-techniques-for-ios-users-producing-and-transforming-tranquil-videos/"><u>2024 Approved  Techniques for iOS Users  Producing and Transforming Tranquil Videos</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-face-to-face-factor-dissecting-apples-x-and-samsungs-identification-methods/"><u>2024 Approved  Face-to-Face Factor  Dissecting Apple’s X and Samsung’s Identification Methods</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-0x80780119-on-system-image/"><u>Addressing Windows Error 0X80780119 on System Image</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-long-start-ups-in-windows-11-easily-and-swiftly/"><u>Conquering Long Start-Ups in Windows 11 Easily and Swiftly</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-ms-store-downloads-techniques-and-tips/"><u>Boosting MS Store Downloads: Techniques and Tips</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-win32keygen-threat-symptoms-damage-and-removal-guide/"><u>Unraveling Win32/Keygen Threat: Symptoms, Damage, & Removal Guide</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-s-best-time-lapse-video-editing-tools-free-paid-and-everything-in-between-for-2024/"><u>New S Best Time-Lapse Video Editing Tools Free, Paid, and Everything in Between for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unrequested-file-explorer-startups/"><u>Addressing Unrequested File Explorer Startups</u></a></li>
</ul></div>
