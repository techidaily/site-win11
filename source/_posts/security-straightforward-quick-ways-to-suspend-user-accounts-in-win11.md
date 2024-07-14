---
title: "Security Straightforward: Quick Ways to Suspend User Accounts in Win11"
date: 2024-07-13T09:52:43.973Z
updated: 2024-07-14T09:52:43.973Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Security Straightforward: Quick Ways to Suspend User Accounts in Win11"
excerpt: "This Article Describes Security Straightforward: Quick Ways to Suspend User Accounts in Win11"
keywords: Win11 Security Controls,Suspending Windows Users,Admin Access Limitation,Immediate Account Lockout,User Management Tools,Secure Windows Environment,Efficient PC Safety
thumbnail: https://thmb.techidaily.com/a49d5779dbd8d3bcb3bf8423c93f4ef941ba145d1cb34757b006a9b7dc8bcdff.jpeg
---

## Security Straightforward: Quick Ways to Suspend User Accounts in Win11

 You can create multiple users account on Windows 11 for yourself and others. This allows you to create different spaces for your personal and work tasks and enable others to share your computer and have their own spaces.

 But what if you need to stop someone from accessing their account without deleting it? While you can temporarily disable a user account on Windows 11 using the block sign-in option, there are a few other ways to disable specific or all user accounts on Windows 11.

## 1\. How to Disable a User Account in Windows Settings

 Windows allows the system administrator to manage user accounts on Windows 11\. Not only can you [add a local user account](https://www.makeuseof.com/windows-11-create-local-user-account/) there, but you can also block sign-in to disable an account temporarily.

To disable user accounts via Settings:

1. Press**Win + I** to open the**Settings** panel.
2. In the left pane, click on the**Accounts** tab.  
![windows 11 settings account family](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-account-family-1.jpg)
3. Next, in the right pane, scroll down and click on**Family** .
4. Under**Your family** , scroll down and click on the account you want to disable.  
![windows 11 settings account family block sign in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-account-family-block-sign-in-1.jpg)
5. Next, click the**Block sign in** button and click**Block** in the confirmation dialog.  
![windows 11 settings account family allow sign in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-account-family-allow-sign-in-1.jpg)
6. If you need to enable the user account again, click the**Allow sign in** button and click**Allow** to confirm the action.

 Note that you must log in to your administrator account to make changes to user accounts. Also, you can only block sign-in for members of**Your family** in the Family groups from Settings. If you need to disable a local user account, you must use the PowerShell and Command Prompt methods below.

## 2\. How to Disable a User Account Using Windows PowerShell

 If you need to disable and enable user accounts frequently, PowerShell can help you do it efficiently. To do this, you can use the Disable-LocalUser cmdlet and specify the user account name you want to disable.

To disable a user account using PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Terminal (Admin)** . It will open Windows Terminal with PowerShell set as the default profile.
3. If not, click the drop-down icon in the**Terminal** tabs section and select**Windows PowerShell** .  
![powerhsell user account list view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/powerhsell-user-account-list-view.jpg)
4. Next, type the following command to find all the user accounts on your PC:  
`Get-LocalUser`
5. Locate the user account name in the**Name** column.

1. Next, type the following command to disable the specified user account:  
`Disable-LocalUser -Name &ldquo;NewUser&rdquo;`
2. In the above command, replace**NewUser** with the user account name you want to disable.  
![powerhsell user account disable](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/powerhsell-user-account-disable.jpg)
3. PowerShell will not return a success message after the user account is disabled.
4. If you need to enable the account again, type the following command and press Enter:  
`Enable-LocalUser -Name &ldquo;NewUser&rdquo;`
5. In the above command replace NewUser with your user account name.

 When disabled, the user account will be hidden from your lock screen. To verify the same, press**Win + L** to [lock your Windows 11 computer](https://www.makeuseof.com/windows-11-ways-to-lock/) . Next, double-click on the lock screen to view the login screen. If disabled, the user account will appear on the lower left side of your screen.

## 3\. Disable a User Account Using the Command Prompt

 Another way to disable a local user account is via the Command Prompt. It is a command-line utility that you can use to disable Microsoft or local user accounts.

To disable a user account using Command Prompt:

1. Press**Win + R** to open**Run** .
2. Type**cmd** in the**Run** box. Next, press**OK** while holding the**Ctrl + Shift** key to open the elevated Command Prompt. Click**Yes** if prompted by User Account Control.
3. In the Command Prompt window, type the following command to find all the available user accounts on your PC:  
`net user`
4. Locate the user account name in the return list.  
![command prompt net user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/command-prompt-net-user.jpg)
5. Next, type the following command to disable the specified user account:  
`net user NewUser /active:no`
6. In the above command, replace**NewUser** with the user account name you want to disable.  
![command prompt net user disable account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/command-prompt-net-user-disable-account.jpg)
7. Next, type**exit** and press Enter to close Command Prompt.
8. If you need to enable the account again, execute the following command:  
`net user NewUser /Active:yes`
9. Make sure to replace NewUser with the account name you want to enable.

## 4\. Disable a User Account From the Computer Management Console

 The Computer Management Console gives system administrators access to advanced tools such as Task Scheduler, Event Viewer, Device Manager, etc. Another useful Computer Management feature is Local Users and Groups.

 Local User and Groups lets you manage user accounts and groups on your Windows computer. While the Computer Management console is available on all versions of Windows, Local User and Groups is only available on the Pro, Edu, and Enterprise edition of the OS.

 To disable user accounts using the Local Users and Groups Management console:

1. Click on the**Search icon** in**Taskbar** .
2. Type**computer management** and click on**Computer Management** from the search result.
3. In the**Computer Management** console, expand**System Tools** .  
![computer management local users groups users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/computer-managemnet-local-users-groups-users.jpg)
4. Next, locate and select**Local Users and Groups.**
5. Select the**Users** folder**.**

1. In the right pane, you can view all the user accounts on your PC.
2. To disable a user account, right-click on the**User Account Name** and select**Properties** .  
![computer management local users groups users account is disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/computer-managemnet-local-users-groups-users-account-is-disabled.jpg)
3. In the**Properties** dialog, select the**Account is disabled** option.
4. Click**Apply** and**OK** to save the changes.
5. To enable the account gain, uncheck the**Account is disabled** option and click**Apply** and**OK** .

### Disable User Account Using Local Users and Groups on Windows 11 Home

 Windows 11 Home users will have to rely on a third-party tool to disable a user account via the Local User and Groups console. Lusrmgr is a third-party snap-in that offers similar functionalities as the Local Users and Groups Management console.

 To install the tool, follow our guide to [enable Local User and Group Management on Windows 11](https://www.makeuseof.com/windows-home-edition-enable-local-user-group-management/) . Once done, follow the steps below:

1. Double-click on the**lusrmgr.exe** file to launch the application.
2. In the**Local users and groups** dialog, select**Users** .
3. Right-click on the user account you want to disable and select**Edit** .  
![run lusrmgr exe file edit account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/run-lusrmgr-exe-file-edit-account.jpg)
4. Next, open the**Account** tab.
5. Select the**Account is disabled** option.  
![run lusrmgr exe file edit account disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/run-lusrmgr-exe-file-edit-account-disabled.jpg)
6. Click**Apply** and**OK** to save the changes.

## There Are Many Ways to Disable a User Account on Windows 11

 Disabling a user account lets you restrict access to a specific user account without deleting the account completely. This way, if you need to restore the account at a later stage, you can enable it and continue using it without restoring files and folders.

 That said, removing a user account on Windows 11 is not a complicated process. Just log in to your administrator account and block sign-in or remove user accounts from Settings, and you're pretty much done.

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
<li><a href="https://some-knowledge.techidaily.com/updated-expert-tips-for-smooth-win11-meetings-via-zoom/"><u>[Updated] Expert Tips for Smooth Win11 Meetings via Zoom</u></a></li>
<li><a href="https://some-techniques.techidaily.com/expressive-faces-with-motion-blur-in-picsart-for-2024/"><u>Expressive Faces with Motion Blur in Picsart for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/installation-steps-for-dolby-atmos-in-windows-11/"><u>Installation Steps for Dolby Atmos in Windows 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-everything-you-need-to-know-about-lock-screen-settings-on-your-nokia-c12-plus-by-drfone-android/"><u>In 2024, Everything You Need to Know about Lock Screen Settings on your Nokia C12 Plus</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-exclusive-movies-behind-the-best-chart/"><u>[Updated] In 2024, Exclusive Movies Behind the Best Chart</u></a></li>
<li><a href="https://win11.techidaily.com/winning-speed-efficient-download-strategies-for-valorant-on-pc/"><u>Winning Speed: Efficient Download Strategies for Valorant on PC</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-divide-recovering-lost-winvpn-links/"><u>Bridging the Divide: Recovering Lost WinVPN Links</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-free-scape-discovering-the-artistic-no-money-backdrops-of-tiktok/"><u>[Updated] FREE-Scape  Discovering the Artistic No-Money Backdrops of TikTok</u></a></li>
<li><a href="https://win11.techidaily.com/speak-get-text-win-a-comprehensible-guide-to-windows-whisper/"><u>Speak, Get Text, Win: A Comprehensible Guide to Windows Whisper</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-elevate-your-video-visibility-11-secrets-of-successful-seo/"><u>[Updated] In 2024, Elevate Your Video Visibility  11 Secrets of Successful SEO</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-immersive-escapes-how-to-choose-between-rift-vive-ps-vr-in-2024/"><u>[Updated] Immersive Escapes  How to Choose Between Rift, Vive, PS VR, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/curbing-problems-with-outlooks-error-0x80040610-on-windows/"><u>Curbing Problems with Outlook's Error 0X80040610 on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/cut-to-perfection-top-video-editors-for-your-win11-pc/"><u>Cut-to-Perfection: Top Video Editors For Your Win11 PC</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-unlock-3d-magic-a-beginners-guide-to-video-effects-on-windows-10-and-11-for-2024/"><u>Updated Unlock 3D Magic A Beginners Guide to Video Effects on Windows 10 and 11 for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/2024-approved-voice-modification-tools-the-ultimate-guide-for-youtubers/"><u>2024 Approved  Voice Modification Tools – The Ultimate Guide for YouTubers</u></a></li>
<li><a href="https://win11.techidaily.com/5-immediate-actions-reviving-disabled-windows-defender-protection/"><u>5 Immediate Actions: Reviving Disabled Windows Defender Protection</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-the-best-strategies-for-saving-igtv-videos-mobilely/"><u>In 2024, The Best Strategies for Saving IGTV Videos Mobilely</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-unveiling-tricky-feed-functions-more-vids-please/"><u>[New] 2024 Approved  Unveiling Tricky Feed Functions  More Vids Please</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-complete-analysis-of-gecatas-play-recorder-for-2024/"><u>[Updated] Complete Analysis of Gecata's Play Recorder for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/deciding-between-upgrades-here-are-7-reasons-for-win10/"><u>Deciding Between Upgrades? Here Are 7 Reasons for Win10</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-techniques-for-moving-files-in-windows-11/"><u>Boost Productivity: Techniques for Moving Files in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-virtualbox-v70-potential-the-upgrade-on-windows-11/"><u>Unlock VirtualBox v7.0 Potential: The Upgrade on Windows 11</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-2024-approved-ghostly-pause-recorder-tutorial/"><u>[New] 2024 Approved  Ghostly Pause Recorder Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-asana-glitches-on-pc/"><u>Troubleshooting Asana Glitches on PC</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-disabled-security-authority-on-desktops/"><u>Remedy for Disabled Security Authority on Desktops</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/2024-approved-snaptweet-transporter-swift-transfer-of-tweets-content/"><u>2024 Approved  SnapTweet Transporter  Swift Transfer of Tweets' Content</u></a></li>
<li><a href="https://win11.techidaily.com/flattening-windows-11-corner-style/"><u>Flattening Windows 11 Corner Style</u></a></li>
<li><a href="https://win11.techidaily.com/a-new-dawn-for-unadvertised-windows-start-menus/"><u>A New Dawn for Unadvertised Windows Start Menus</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/quick-guide-to-capturing-timelapses-with-gopro-hero5/"><u>Quick Guide to Capturing Timelapses with GoPro Hero5</u></a></li>
<li><a href="https://win11.techidaily.com/windows-mastering-app-and-browser-oversight/"><u>Windows: Mastering App & Browser Oversight</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-music-from-xiaomi-redmi-note-12-pro-5g-by-fonelab-android-recover-music/"><u>Easy steps to recover deleted music from Xiaomi Redmi Note 12 Pro 5G</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-the-ultimate-list-of-free-vob-video-editors/"><u>Updated The Ultimate List of Free VOB Video Editors</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-the-art-of-engaging-responding-in-discord-conversations/"><u>[Updated] 2024 Approved  The Art of Engaging  Responding in Discord Conversations</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-10-password-cracking-tools-for-infinix-note-30-vip-by-drfone-android/"><u>Top 10 Password Cracking Tools For Infinix Note 30 VIP</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-google-maps-installation-on-pc/"><u>Quick Guide: Google Maps Installation on PC</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-one-connected-video-experience-joining-on-youtube/"><u>2024 Approved  One Connected Video Experience  Joining on YouTube</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-stream-success-starts-here-choosing-the-right-camera-for-twitch/"><u>[Updated] 2024 Approved  Stream Success Starts Here  Choosing the Right Camera for Twitch</u></a></li>
<li><a href="https://win11.techidaily.com/essential-techniques-to-revitalize-frozen-spotify-win11/"><u>Essential Techniques to Revitalize Frozen Spotify Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-lsassexe-unable-to-locate-error-on-win-810/"><u>How to Overcome lsass.exe Unable to Locate Error on Win 8/10</u></a></li>
<li><a href="https://win11.techidaily.com/6-fixes-to-try-if-the-right-click-context-menu-gets-stuck-in-windows/"><u>6 Fixes to Try if the Right Click Context Menu Gets Stuck in Windows</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-top-8-immersive-virtual-reality-adventures-on-oculus/"><u>[New] Top 8 Immersive Virtual Reality Adventures on Oculus</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-manage-secure-boot-and-tpm-settings-on-virtualbox-70/"><u>Step-by-Step Guide to Manage Secure Boot & TPM Settings on VirtualBox 7.0</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-screenplay-foundations-a-guide/"><u>2024 Approved  Screenplay Foundations  A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-properties-puzzles-in-windows-os/"><u>Unveiling Properties Puzzles in Windows OS</u></a></li>
<li><a href="https://fix-guide.techidaily.com/spotify-keeps-crashing-a-complete-list-of-fixes-you-can-use-on-realme-c67-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Spotify Keeps Crashing A Complete List of Fixes You Can Use on Realme C67 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bypass-windows-update-error-codes-a-step-by-step-approach/"><u>How to Bypass Windows Update Error Codes: A Step-by-Step Approach</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-one-ear-beats-issue-repair-path/"><u>In 2024, One-Ear Beats Issue Repair Path</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-overcome-windowsapps-protection-measures/"><u>Strategies to Overcome WindowsApps Protection Measures</u></a></li>
<li><a href="https://win11.techidaily.com/method-to-release-administrator-restricted-apps/"><u>Method to Release Administrator-Restricted Apps</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/phone-friendly-design-the-importance-of-aspect-ratio-considerations/"><u>Phone-Friendly Design The Importance of Aspect Ratio Considerations</u></a></li>
<li><a href="https://extra-skills.techidaily.com/satirists-web-workshop-for-2024/"><u>Satirist's Web Workshop for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/preserving-customization-transferring-powertoys-to-a-new-machine/"><u>Preserving Customization: Transferring PowerToys to a New Machine</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-virtual-meetup-spaces-the-best-videochat-services-as-alternatives-to-omegle-for-2024/"><u>New Virtual Meetup Spaces The Best Videochat Services as Alternatives to Omegle for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-0x30017-update-issue-in-windows-os/"><u>Troubleshooting 0X30017 Update Issue in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/swift-strike-against-script-failures-in-windows/"><u>Swift Strike Against Script Failures in Windows</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-video-streaming-sonic-database-youtube/"><u>Updated 2024 Approved Video Streaming Sonic Database - YouTube</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-best-route-generator-apps-you-should-try-on-tecno-spark-10-5g-drfone-by-drfone-virtual-android/"><u>5 Best Route Generator Apps You Should Try On Tecno Spark 10 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/confronting-and-correcting-uninitialized-disk-errors-in-win/"><u>Confronting & Correcting 'Uninitialized Disk' Errors in Win</u></a></li>
<li><a href="https://win11.techidaily.com/cant-open-exe-files-on-windows-try-these-fixes/"><u>Can’t Open EXE Files on Windows? Try These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-glitches-and-error-0xc00d36b4-on-windows/"><u>Troubleshooting Glitches & Error 0xC00D36B4 on Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-professional-techniques-for-video-narrative-inclusion/"><u>In 2024, Professional Techniques for Video Narrative Inclusion</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-upholding-windows-datetime-integrity/"><u>Guidelines for Upholding Windows Date/Time Integrity</u></a></li>
<li><a href="https://win11.techidaily.com/solving-steamuidll-not-loaded-problems-in-windows-steam/"><u>Solving “Steamui.dll Not Loaded” Problems in Windows Steam</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-mask-after-dim-display-option-on-pcs/"><u>Steps to Mask After Dim Display Option on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-taskbar-design-proposals-for-windows-11s-user-interaction-improvements/"><u>Elevating Taskbar Design: Proposals for Windows 11'S User Interaction Improvements</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-complexities-of-windows-system-restore-for-easy-rollbacks/"><u>Unraveling the Complexities of Windows System Restore for Easy Rollbacks</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-s-mode-understanding-its-role-in-security/"><u>Windows 11'S 'S Mode': Understanding Its Role in Security</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-update-speed-of-task-monitor-win-11/"><u>Accelerate Update Speed of Task Monitor Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/contrasting-features-of-installation-methods-exe-vs-msi-files/"><u>Contrasting Features of Installation Methods: Exe vs Msi Files</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-power-of-your-laptops-touch-sensitivity-with-ease/"><u>Unleash the Power of Your Laptop's Touch Sensitivity with Ease</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-mastering-animation-drawing-a-guide-to-the-best-software/"><u>2024 Approved Mastering Animation Drawing A Guide to the Best Software</u></a></li>
</ul></div>
