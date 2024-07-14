---
title: "Xbox Games on Windows: Avoid Common Setup Pitfalls"
date: 2024-07-13T10:10:44.616Z
updated: 2024-07-14T10:10:44.616Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Xbox Games on Windows: Avoid Common Setup Pitfalls"
excerpt: "This Article Describes Xbox Games on Windows: Avoid Common Setup Pitfalls"
keywords: Xbox Setup Tips,Windows Gaming Guide,Xbox Errors Fix,Game Install Woes,PC Xbox Compatibility,Avoiding Setup Failures,Streamline Xbox Setup
thumbnail: https://thmb.techidaily.com/e788f79a8684ff135a50b06576e0943a8c2779cab90284e9a264c3a4912b0271.png
---

## Xbox Games on Windows: Avoid Common Setup Pitfalls

 The Xbox app lets you purchase and install games on any of your system drives. Usually, this process works well, but sometimes, the Xbox app won't let you install games in any location other than the default directory. This can be problematic, especially when you want to install a big-size game, but the default directory doesn't have enough space.

 Such situations usually arise due to corruption in the Xbox app or misconfigured registry settings. Fortunately, it's very easy to troubleshoot this problem. Here are some fixes to try when you can't choose a drive to install games on the Xbox app.

## 1\. Restart the Computer

![Restart option in Power menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restart.jpg)

 You might fail to change the installation drive in the Xbox app due to a temporary system glitch or bug. Luckily, you can quickly eliminate such bugs and glitches by restarting your computer.

 To restart, press the**Alt + F4** hotkeys to open the Shut Down Windows prompt, click the drop-down icon, choose**Restart** from the context menu, and then click**OK.** After restart, launch the Xbox app and check if you can choose a different drive to install games. If not, then it's time to dive into the advanced troubleshooting methods.

## 2\. Change the Installation Directory in the Xbox App Settings

 There are two places from where you can change the installation drive on the Xbox app. One is while installing the game, whereas the other is the Xbox settings menu.

 If the first method is not working, you can use the second method to change the installation drive in the Xbox app. So, here's how to edit the Xbox app settings to change its default download location.

1. Launch the Xbox app, click on your profile in the top left corner, and choose**Settings** from the context menu.
2. Choose**General** from the left sidebar.
3. Click the**Change folder** option under**Change where this app installs games by default** .  
![Change Folder in Xbox app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-folder.jpg)
4. Choose the location where you want to install the game and then click the**Select Folder** option.

## 3\. Customize the System Settings

 If editing the Xbox app settings wasn't helpful, you can edit the system settings and check if it makes a difference. Here's what you need to do:

1. Press the**Win + I** hotkeys to open the**Settings app.**
2. Choose**System** from the left sidebar and then click on the**Storage** option in the right pane.
3. Click the drop-down icon next to**Advanced storage settings** and choose**Where new content** **is saved** option from the context menu.  
![Where new content is saved option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/where-new-content-is-saved.png)
4. Click the drop-down icon under the**New** **apps** **will save to** section, choose the drive where you want to install the game, and then click**Apply.**  
![New apps will save to section in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/new-apps-will-save-to-section.jpg)

 That's it! Restart your computer and check if the problem continues.

## 4\. Restart Important Xbox Services

![Restart Service option in Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restart-service.jpg)

 There are certain Xbox services that must be running for you to use the Xbox app properly. If any of these services fail to start properly, you might face the problem at hand.

 To fix that, restart each service manually. Here's how to do that:

1. Open the Run dialog box by pressing the**Win + R** hotkeys.
2. Type**services.msc** in the search bar and click OK.
3. In the Services window, locate and right-click on the following services and choose**Restart** from the context menu.  
`Xbox Accessory Management  
Xbox Live Game Save  
Xbox Live Auth Manager  
Xbox Live Networking Service`

## 5\. Reinstall the Gaming Services App

 The Gaming Services app allows you to seamlessly download apps and games from the Microsoft Store and the Xbox app. But if the app gets corrupt, you might face various issues, including the one in question.

 The solution, in this case, is to reinstall the Gaming Services app on your computer. You can do that by following the below instructions:

 Editing the registry can be dangerous, as one wrong edit can make your system unstable. To ensure that your data is secure even if something goes wrong,[back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

1. Open the Run dialog box, type**regedit,** and click OK.
2. In the Registry Editor, navigate to the below location:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services`
3. Right-click on the**GamingServices** folder in the left sidebar and choose**Delete** from the context menu.  
![Delete option in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/delete-option.jpg)
4. Click**Yes** to confirm your selection.
5. Next, delete the**GamingServicesNet** folder as well in the left sidebar.

 Now, open the elevated PowerShell window (see how to [open Windows PowerShell as an administrator](https://www.makeuseof.com/windows-powershell-always-open-as-administrator/) ), type the following command, and press**Enter** .

`Get-AppxPackage *gamingservices* -allusers | remove-appxpackage -allusers`

![Remove Gaming Services command in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-gaming-services.jpg)

 After uninstalling the Gaming Services app, restart your computer. Then, open the Microsoft Store, search for and [download the Gaming Services](https://apps.microsoft.com/store/detail/gaming-services/9MWPM2CQNLHN?hl=en-us&gl=us) app again.

## 6\. Repair the Xbox App

 It's very common for the Xbox app to get corrupt and throw various issues. The best way to remove corruption from the UWP apps like the Xbox app is to use the Windows repair feature.

 Check out [how to repair apps and programs on Windows](https://www.makeuseof.com/windows-repair-apps-programs/) for information on how to do this.

## 7\. Update the Xbox App

 If repairing the Xbox app doesn't remove the corruption, consider updating the app. Downloading the latest update of the Xbox app will not only remove the corruption but also introduce new features.

To update the Xbox app, follow the below steps:

1. Open the Microsoft Store and click the**Library** option in the left sidebar.
2. Click the**Get updates** button to allow the Microsoft Store to search for available updates of the installed apps.

 The Microsoft Store will now automatically download updates for installed apps, including the Xbox app.

 While you're at installing updates, we'd also recommend [downloading any available Windows updates](https://www.makeuseof.com/tag/update-windows-software-guide/) . To do so, launch the Settings app, choose**Windows Update** from the left sidebar, and then click the**Check for Updates** button to install any available update on your computer. Following this, you will be able to choose a drive to install games on the Xbox app.

## Change the Download Location of the Xbox App

 The Xbox app is a great place to download your favorite games. However, the app might fail to change the installation location of games. Fortunately, you can quickly eliminate this issue by following the above fixes.

 Meanwhile, you might be interested to know how to increase downloading speed of the Xbox app.


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
<li><a href="https://win11.techidaily.com/embracing-deity-interactions-with-your-windows-11-pc/"><u>Embracing Deity Interactions with Your Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-silent-speaker-issue-in-win11-environments/"><u>Resolving Silent Speaker Issue in Win11 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-microsofts-activation-error-code-0x8007251d/"><u>Tackling Microsoft's Activation Error Code 0X8007251d</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-remove-programs-without-permission-in-windows/"><u>Steps to Remove Programs Without Permission in Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-cards-of-xiaomi-redmi-note-12-4g-without-puk-codes-by-drfone-android/"><u>In 2024, How To Unlock SIM Cards Of Xiaomi Redmi Note 12 4G Without PUK Codes</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-desktop-aesthetics-with-a-custom-weather-icon-in-windows-11/"><u>Elevate Desktop Aesthetics with a Custom Weather Icon in Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-androids-best-free-mp3-extraction-tools/"><u>[Updated] Android's Best Free MP3 Extraction Tools</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-windows-speaker-recognition-errors/"><u>Rectifying Windows Speaker Recognition Errors</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-winget-a-guide-for-windows-11-users/"><u>Reviving Winget: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-in-2024-reviewing-the-live-streaming-shopping-industry-in-china/"><u>New In 2024, Reviewing the Live Streaming Shopping Industry in China</u></a></li>
<li><a href="https://win11.techidaily.com/beginning-the-speedy-support-function-of-w11/"><u>Beginning the Speedy Support Function of W11</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-in-2024-filmora-is-a-great-video-editor-that-many-users-are-making-intro-video-with-it-this-article-will-guide-you-how-to-create-an-intro-video-with-fil/"><u>New In 2024, Filmora Is a Great Video Editor that Many Users Are Making Intro Video with It. This Article Will Guide You How to Create an Intro Video with Filmora</u></a></li>
<li><a href="https://win11.techidaily.com/a-deep-dive-into-windows-11s-8-confusing-features/"><u>A Deep Dive Into Windows 11’S 8 Confusing Features</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-local-devices-avoid-in-use-names-errors/"><u>Overcoming Windows' Local Devices: Avoid In-Use Names Errors</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-error-x70-on-windows-file-and-folder-restoration-guide/"><u>Eradicating Error X70 on Windows: File and Folder Restoration Guide</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-retry-interval-for-unsuccessful-login-attempts/"><u>Adjusting Retry Interval for Unsuccessful Login Attempts</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/mastering-moments-10-essential-ig-tools-everyone-needs/"><u>Mastering Moments  10 Essential IG Tools Everyone Needs</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/1714946822927-updated-best-spotify-ripper-how-to-rip-music-from-spotify-for-2024/"><u>Updated Best Spotify Ripper How to Rip Music From Spotify for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/introducing-efficient-speech-to-text-utilization-in-powerpoint/"><u>Introducing Efficient Speech-to-Text Utilization in PowerPoint</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-perfecting-yt-thumbnails-with-aspect-ratios/"><u>In 2024, Perfecting YT Thumbnails with Aspect Ratios</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-infinix-hot-30i-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Infinix Hot 30i | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-record-yourself-on-webcam-via-vlc-media/"><u>[Updated] In 2024, Record Yourself on Webcam via VLC Media</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-a-flawlessly-new-windows-experience-in-11th-gen/"><u>Crafting a Flawlessly New Windows Experience in 11Th Gen</u></a></li>
<li><a href="https://win11.techidaily.com/quantify-windows-computer-power-usage-for-optimization/"><u>Quantify Windows Computer Power Usage for Optimization</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-get-back-lost-contacts-from-galaxy-m14-5g-by-fonelab-android-recover-contacts/"><u>How to get back lost contacts from Galaxy M14 5G.</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-obs-tutorial-capturing-every-moment-of-gameplay/"><u>[Updated] OBS Tutorial  Capturing Every Moment of Gameplay</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-unbrick-a-dead-samsung-galaxy-m34-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Samsung Galaxy M34 | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-vistaview-hd-recordingapp/"><u>[New] VistaView HD RecordingApp</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-for-preventing-heat-in-w11-systems/"><u>Essential Steps for Preventing Heat in W11 Systems</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-whos-leading-in-screen-capture-tech-obs-studios-vs-bandicam-for-2024/"><u>[New] Who's Leading in Screen Capture Tech  OBS Studios Vs. Bandicam for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-freespace-a-comprehensive-windows-approach/"><u>Enhancing FreeSpace: A Comprehensive Windows Approach</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-gionee-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, Gionee ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-compress-videos-for-free-10-best-online-tools-with-no-downloads/"><u>In 2024, Compress Videos for Free 10 Best Online Tools with No Downloads</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-methods-to-tackle-programming-problems-on-vistawindows-7/"><u>Efficient Methods to Tackle Programming Problems on Vista/Windows 7</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-overcoming-windows-11s-rename-limitations/"><u>Essential Fixes: Overcoming Windows 11'S Rename Limitations</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-best-of-both-worlds-top-android-video-editor-apps-for-chromebook-users/"><u>New Best of Both Worlds Top Android Video Editor Apps for Chromebook Users</u></a></li>
<li><a href="https://win11.techidaily.com/unblock-your-pcs-usb-troubleshooting-guide-for-windows-users/"><u>Unblock Your PC's USB: Troubleshooting Guide for Windows Users</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-infinix-zero-30-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Infinix Zero 30 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-end-of-an-era-microsofts-abandonment-of-windows-7-and-81/"><u>The End of an Era: Microsoft's Abandonment of Windows 7 and 8.1</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-rectify-predominant-windows-anydesk-mishaps/"><u>Essential Steps to Rectify Predominant Windows AnyDesk Mishaps</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-the-art-of-srt-to-subc-innovative-techniques-explored/"><u>In 2024, The Art of SRT to SUBC  Innovative Techniques Explored</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-steam-disconnect-in-windows-os/"><u>Troubleshoot Steam Disconnect in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/craft-a-quick-fix-to-skip-windows-login-dialogs/"><u>Craft a Quick Fix to Skip Windows Login Dialogs</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-boosting-your-igtv-influence-techniques-to-amplify-audience-size/"><u>[New] Boosting Your IGTV Influence  Techniques to Amplify Audience Size</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-navigate-your-newly-enjoyed-facebook-movies-with-this-2023-guide/"><u>[Updated] 2024 Approved  Navigate Your Newly Enjoyed Facebook Movies with This 2023 Guide</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-selecting-the-ultimate-5-game-chat-devices/"><u>In 2024, Selecting the Ultimate 5 Game Chat Devices</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-file-handling-in-win-11-by-adding-movecopy-menus/"><u>Elevate Your File Handling in Win 11 by Adding Move/Copy Menus</u></a></li>
<li><a href="https://win11.techidaily.com/the-simple-way-to-self-empty-the-recycle-bin-on-windows/"><u>The Simple Way to Self-Empty the Recycle Bin on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-solution-for-geforce-now-error-xc0f1103f-on-windows-11/"><u>Comprehensive Solution for GeForce Now Error: Xc0f1103f on Windows 11</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-laughing-lineup-step-by-step-guide-to-funny-memes/"><u>In 2024, Laughing Lineup  Step-by-Step Guide to Funny Memes</u></a></li>
<li><a href="https://win11.techidaily.com/7-strategies-to-rectify-chromes-profile-problems-on-desktop/"><u>7 Strategies to Rectify Chrome's Profile Problems on Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/unclogging-a-stuck-windows-11-settings-bar-the-search-solution/"><u>Unclogging a Stuck Windows 11 Settings Bar - The Search Solution</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-comprehensive-study-editmagics-power-edition/"><u>2024 Approved  Comprehensive Study  EditMagic's Power Edition</u></a></li>
<li><a href="https://win11.techidaily.com/clarifying-computer-storage-c-d-distinctions/"><u>Clarifying Computer Storage: C, D Distinctions</u></a></li>
<li><a href="https://win11.techidaily.com/security-straightforward-quick-ways-to-suspend-user-accounts-in-win11/"><u>Security Straightforward: Quick Ways to Suspend User Accounts in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-the-isdonedll-error-in-windows-11-and-11x/"><u>Dealing with the ISDone.dll Error in Windows 11 & 11X</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-turning-on-copy-and-paste-operations-in-edges-security-shield-w11/"><u>Steps for Turning on Copy & Paste Operations in Edge's Security Shield W11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-master-the-art-of-crafting-impressive-discord-profile-pictures-for-2024/"><u>[Updated] Master the Art of Crafting Impressive Discord Profile Pictures for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/revealing-how-ai-pcs-outperform-standard-computers/"><u>Revealing How AI PCs Outperform Standard Computers</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-expert-tips-on-perfecting-zoom-video-conferencing-for-youtube/"><u>[New] Expert Tips on Perfecting Zoom Video Conferencing for YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-unbidden-command-window-activations/"><u>Preventing Unbidden Command Window Activations</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-chaos-into-clarity-with-obsidian-visual-techniques/"><u>Transforming Chaos Into Clarity with Obsidian Visual Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unsuccessful-image-saving-on-win11-pc/"><u>Addressing Unsuccessful Image Saving on Win11 PC</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-conquer-backward-motion-in-snapchat-videos-quickly/"><u>[New] In 2024, Conquer Backward Motion in Snapchat Videos Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-embedding-app-shortcuts-in-windows-11/"><u>Step-by-Step Guide to Embedding App Shortcuts in Windows 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-poco-m6-pro-5g-by-drfone-android/"><u>In 2024, The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Poco M6 Pro 5G</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-windows-movie-maker-tutorial-editing-videos-like-a-pro/"><u>New In 2024, Windows Movie Maker Tutorial Editing Videos Like a Pro</u></a></li>
<li><a href="https://fake-location.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-enhancing-youtube-visibility-with-tubebuddy/"><u>[New] 2024 Approved  Enhancing YouTube Visibility with TubeBuddy</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-after-deleting-from-recently-deleted-on-iphone-12-pro-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to recover deleted photos after deleting from Recently Deleted on iPhone 12 Pro | Stellar</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-inoperative-touchscreen-actions-in-windows/"><u>Addressing Inoperative Touchscreen Actions in Windows</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/chuckle-inducing-cover-versions-for-2024/"><u>Chuckle-Inducing Cover Versions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-icon-recovery-step-by-step-guide/"><u>Windows 11 Icon Recovery: Step-by-Step Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-leveraging-hashtags-to-skyrocket-your-engagement/"><u>In 2024, Leveraging Hashtags to Skyrocket Your Engagement</u></a></li>
</ul></div>
