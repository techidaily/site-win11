---
title: "Windows: Define Custom Idle Timeframe"
date: 2024-06-25T11:39:22.467Z
updated: 2024-06-26T11:39:22.467Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows: Define Custom Idle Timeframe"
excerpt: "This Article Describes Windows: Define Custom Idle Timeframe"
keywords: Windows Idle Timer,Customize Idle Time,Set Idle Window,Personal Idle Period,Adjust System Idle,Tailor Idle Time,Custom Idle Settings
thumbnail: https://thmb.techidaily.com/7210d597b33981cf8e8bc74bc3a1da89a343d982eff67b18284889061aed1be5.jpg
---

## Windows: Define Custom Idle Timeframe

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

1. Type**Registry Editor** in**Windows Search** and select**Registry Editor** under**Best match** . Or use one of the many[ways to open the Registry Editor in Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) .
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

 Now your PC will get locked if you're not using it or are away from it after the time you have set in the Registry Editor. If you're on a Windows 11 machine, you can also[explore a few other ways to lock your PC](https://www.makeuseof.com/windows-11-ways-to-lock/) .

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
<li><a href="https://win11.techidaily.com/circumvent-unauthorized-windows-login-errors-easy-guide/"><u>Circumvent Unauthorized Windows Login Errors (Easy Guide)</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-windows-camera-conflict-error-0xa00f4243/"><u>Remedying Windows' Camera Conflict Error 0xA00F4243</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-computing-experience-best-windows-devices-2024/"><u>Ultimate Computing Experience - Best Windows Devices 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-another-app-is-using-the-camera-already-0xa00f4243-error-on-windows/"><u>How to Fix the Another App Is Using the Camera Already 0xA00F4243 Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-non-operational-snipviewer-keys/"><u>Quick Fixes for Non-Operational SnipViewer Keys</u></a></li>
<li><a href="https://win11.techidaily.com/the-definitive-guide-on-defeating-windows-11s-0x8007045d-error/"><u>The Definitive Guide on Defeating Windows 11'S 0X8007045D Error</u></a></li>
<li><a href="https://win11.techidaily.com/introduction-to-windows-hello-for-fingerprint-recognition/"><u>Introduction to Windows Hello for Fingerprint Recognition</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-mastering-3d-painting-shortcuts/"><u>Expert Tips for Mastering 3D Painting Shortcuts</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-infinix-note-30-vip-racing-edition-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked Infinix Note 30 VIP Racing Edition Phone | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-cost-effective-gaming-selecting-the-best-keyboard-choices/"><u>[Updated] Cost-Effective Gaming  Selecting the Best Keyboard Choices</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-mastering-the-art-of-transforming-social-media-videos-to-gifs/"><u>[New] In 2024, Mastering the Art of Transforming Social Media Videos to GIFs</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-freeing-up-youtube-footage-borderless-exploration/"><u>[Updated] 2024 Approved  Freeing Up YouTube Footage  Borderless Exploration</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-shooting-up-expert-advice-for-creating-vertical-content-on-your-phone/"><u>In 2024, Shooting Up Expert Advice for Creating Vertical Content on Your Phone</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-what-is-mov-format-and-how-to-edit-mov-video-creatively/"><u>Updated What Is MOV Format and How To Edit MOV Video Creatively?</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-prime-browser-modifiers-expertly-downloaded-vimeo-videos/"><u>[Updated] Prime Browser Modifiers  Expertly Downloaded Vimeo Videos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/how-to-craft-contagious-instagram-visuals/"><u>How to Craft Contagious Instagram Visuals</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-youtube-thumbnail-secrets-boost-views-with-the-right-size-design-and-strategy/"><u>New In 2024, YouTube Thumbnail Secrets Boost Views with the Right Size, Design, and Strategy</u></a></li>
</ul></div>
