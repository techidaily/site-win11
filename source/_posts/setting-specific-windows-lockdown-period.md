---
title: Setting Specific Windows Lockdown Period
date: 2024-06-25T11:36:02.063Z
updated: 2024-06-26T11:36:02.063Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Setting Specific Windows Lockdown Period
excerpt: This Article Describes Setting Specific Windows Lockdown Period
keywords: Lockdown Windows Time,Secure Window Lock,Set Windows Lock,Timed Windows Safeguard,Schedule Window Security,Lock Period Windows,Define Lockdown Window
thumbnail: https://thmb.techidaily.com/e937c769751b4b8235d825da190a8de514c18ce6c728b4bc630fa21c8db2efdc.jpg
---

## Setting Specific Windows Lockdown Period

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
<li><a href="https://win11.techidaily.com/best-practices-for-addressing-system-call-failed-on-pcs/"><u>Best Practices for Addressing System Call Failed on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/propel-power-5-best-windows-optimization-strategies/"><u>Propel Power: 5 Best Windows Optimization Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/proven-tools-to-assist-in-making-your-pc-to-mac-os-transition-easier/"><u>Proven Tools to Assist in Making Your PC-to-Mac OS Transition Easier</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-correcting-virtualboxs-0x80004005-error/"><u>Mastering the Art of Correcting VirtualBox's 0X80004005 Error</u></a></li>
<li><a href="https://win11.techidaily.com/winning-back-your-gameplay-fixed-windows-wow-connectivity/"><u>Winning Back Your Gameplay: Fixed Windows WoW Connectivity</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-disk-usage-errors-in-modern-windows-os/"><u>Circumventing Disk Usage Errors in Modern Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-windows-services-command-line-tool-with-these-7-steps/"><u>Restoring Window's Services Command Line Tool with These 7 Steps</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-turn-off-auto-start-for-spotify/"><u>Guide to Turn Off Auto-Start for Spotify</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-increase-windows-disk-size-securely/"><u>Strategies to Increase Windows Disk Size Securely</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-direct-confrontation-assessing-obs-versus-twitch-hubs-for-2024/"><u>[New] Direct Confrontation  Assessing OBS versus Twitch Hubs for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-the-ultimate-guide-to-slow-motion-in-windows-live-movie-maker/"><u>Updated The Ultimate Guide to Slow Motion in Windows Live Movie Maker</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-fleet-footed-fun-prime-pc-and-mobile-game-picks/"><u>[Updated] Fleet-Footed Fun  Prime PC and Mobile Game Picks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-percussive-peacock-swing/"><u>[Updated] In 2024, Percussive Peacock Swing</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-2024-approved-best-filmic-pro-luts-for-video-editing/"><u>Updated 2024 Approved Best Filmic Pro LUTs For Video Editing</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-all-must-knows-to-use-fake-gps-go-location-spoofer-on-apple-iphone-x-drfone-by-drfone-virtual-ios/"><u>In 2024, All Must-Knows to Use Fake GPS GO Location Spoofer On Apple iPhone X | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-first-choice-webcams-ready-for-zoom-mastery/"><u>[Updated] First Choice Webcams, Ready for Zoom Mastery</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-ultimate-guide-to-choosing-mac-screenshot-tools/"><u>In 2024, Ultimate Guide to Choosing Mac Screenshot Tools</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-do-honor-x9b-screen-sharing-drfone-by-drfone-android/"><u>In 2024, How To Do Honor X9b Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-obs-or-streamlabs-determining-the-superior-livestream-software/"><u>2024 Approved  OBS or Streamlabs? Determining the Superior Livestream Software</u></a></li>
</ul></div>
