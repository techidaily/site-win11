---
title: Regain Access to Microsoft Store Features on PCs
date: 2024-07-13T09:45:26.956Z
updated: 2024-07-14T09:45:26.956Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Regain Access to Microsoft Store Features on PCs
excerpt: This Article Describes Regain Access to Microsoft Store Features on PCs
keywords: Microsoft Store Reentry,Gain MSFT Store Access,Restore Microsoft Pc Features,Regain MSO Store Functionality,Recover MS Windows Store Features,Resume Windows Store Use,Reactivate Microsoft Store on PC
thumbnail: https://thmb.techidaily.com/0a18a6b406ce9f21eda937adac64825b459ee3a87d13a642256000f5335eb2cc.jpg
---

## Regain Access to Microsoft Store Features on PCs

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the [Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.


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
<li><a href="https://win11.techidaily.com/eliminating-wsl-error-4294967295-a-comprehensive-guide/"><u>Eliminating WSL Error 4294967295: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/filter-out-superfluous-updates-from-your-windows-pc/"><u>Filter Out Superfluous Updates From Your Windows PC</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-designing-professional-youtube-editors-workflow/"><u>2024 Approved  Designing Professional YouTube Editors' Workflow</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-embedding-google-play-into-windows-11/"><u>Guide to Embedding Google Play Into Windows 11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/extract-silence-eradicating-audio-in-various-video-formats-mp4-mkv-avi-mov-wmv-2023-edition/"><u>Extract Silence Eradicating Audio in Various Video Formats (MP4, MKV, AVI, MOV, WMV) - 2023 Edition</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-fix-apple-iphone-13-mini-unavailable-issue-with-ease-by-drfone-ios/"><u>How To Fix Apple iPhone 13 mini Unavailable Issue With Ease</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-conceptualizing-shorter-vids-for-instagram-with-mac/"><u>[New] Conceptualizing Shorter Vids for Instagram with Mac</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-ready-for-high-res-our-choice-of-best-screenshot-and-recorder-apps/"><u>[Updated] 2024 Approved  Ready for High-Res  Our Choice of Best Screenshot & Recorder Apps</u></a></li>
<li><a href="https://win11.techidaily.com/linking-legacy-and-modernity-initiating-windows-11-with-a-window-7-code/"><u>Linking Legacy and Modernity: Initiating Windows 11 with a Window 7 Code</u></a></li>
<li><a href="https://win11.techidaily.com/making-vintage-windows-computers-more-elderly-friendly/"><u>Making Vintage Windows Computers More Elderly Friendly</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-image-quality-with-auto-hdr-in-w11/"><u>Maximizing Image Quality with Auto HDR in W11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-turntable-tunes-archive-stream-your-dj-favorites/"><u>New Turntable Tunes Archive Stream Your DJ Favorites</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fast-startup-in-windows-11/"><u>Mastering Fast Startup in Windows 11</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/easy-ways-to-remove-motion-blur-in-photoshop-for-2024/"><u>Easy Ways to Remove Motion Blur In Photoshop for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-ideal-audio-transformer-devices-for-youtube-experts/"><u>2024 Approved  Ideal Audio Transformer Devices for YouTube Experts</u></a></li>
<li><a href="https://extra-tips.techidaily.com/transforming-business-with-metaverse-ideas/"><u>Transforming Business with Metaverse Ideas</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-maximize-your-youtube-impact-mastering-the-art-of-influential-channels-branding/"><u>In 2024, Maximize Your YouTube Impact  Mastering the Art of Influential Channels' Branding</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-open-srt-soundtrack-on-windowsmacos/"><u>2024 Approved  Open SRT Soundtrack on Windows/macOS</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-nuances-of-using-github-desktop-in-windows-oses/"><u>Navigating the Nuances of Using GitHub Desktop in Windows OSes</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-make-every-story-stand-out-6-top-rated-apps-for-android-and-iphone/"><u>[New] In 2024, Make Every Story Stand Out  6 Top-Rated Apps for Android & iPhone</u></a></li>
<li><a href="https://win11.techidaily.com/holiday-harmony-delightful-wrapped-apps-through-ms-store/"><u>Holiday Harmony: Delightful Wrapped Apps Through MS Store</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-security-account-manager-failures/"><u>Combatting Security Account Manager Failures</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-application-was-unable-to-start-0xc000003e-error-in-windows-10-and-11/"><u>How to Fix “The Application Was Unable to Start” 0Xc000003e Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-system-failures-blue-screen-aftermath-in-windows/"><u>Delving Into System Failures: Blue Screen Aftermath in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-fix-windows-complications-with-java-installer/"><u>Steps to Fix Windows Complications with Java Installer</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-flv-conversion-for-content-creators-top-10-youtubes-alternatives-unveiled/"><u>[New] 2024 Approved  Flv Conversion for Content Creators  Top 10 YouTubes Alternatives Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/winning-at-overcoming-onedrive-errors-on-windows/"><u>Winning at Overcoming OneDrive Errors on Windows</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-expert-techniques-for-simple-iphone-screenshot-processes/"><u>[New] Expert Techniques for Simple IPhone Screenshot Processes</u></a></li>
<li><a href="https://win11.techidaily.com/stalling-windows-auto-updates-four-methods/"><u>Stalling Windows Auto-Updates: Four Methods</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-breakthrough-the-top-8-web-based-photo-blender/"><u>2024 Approved  Breakthrough  The Top 8 Web-Based Photo Blender</u></a></li>
<li><a href="https://win11.techidaily.com/boosted-performance-with-smart-use-of-windows-11s-bar/"><u>Boosted Performance with Smart Use of Windows 11'S Bar</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-family-safety-key-features-and-uses/"><u>Microsoft Family Safety: Key Features and Uses</u></a></li>
<li><a href="https://win11.techidaily.com/the-beginners-guide-to-avoiding-mistakes-in-windows-11/"><u>The Beginner's Guide to Avoiding Mistakes in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/beginners-blueprint-to-victory-in-original-diablo/"><u>Beginner’s Blueprint to Victory in Original Diablo</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-user-experience-linking-win-prefixes-and-ms-logins/"><u>Enhancing User Experience: Linking Win Prefixes & MS Logins</u></a></li>
<li><a href="https://win11.techidaily.com/powertoys-batch-renaming-made-simple/"><u>PowerToys' Batch Renaming Made Simple</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-digital-gateway-easy-desktop-connectivity-with-win-11/"><u>Unlocking the Digital Gateway: Easy Desktop Connectivity with Win 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-top-20-thumbnail-fonts-for-impressive-video-credits/"><u>In 2024, Top 20 Thumbnail Fonts for Impressive Video Credits</u></a></li>
<li><a href="https://win11.techidaily.com/altering-windows-11s-cam-access-silence-protocol/"><u>Altering Windows 11'S Cam Access Silence Protocol</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-mastering-facebook-video-auto-play/"><u>[Updated] In 2024, Mastering Facebook Video Auto-Play</u></a></li>
<li><a href="https://win11.techidaily.com/utilizing-windows-tools-for-superior-macos-experience/"><u>Utilizing Windows Tools for Superior macOS Experience</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-facebooks-10-best-music-clips-making-them-happen/"><u>In 2024, Facebook's 10 Best Music Clips  Making Them Happen</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-watch-deleted-youtube-videos-online-in-2-ways/"><u>[Updated] In 2024, How to Watch Deleted YouTube Videos Online in 2 Ways</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-flashing-frequencies-role-music-synopsis/"><u>[New] 2024 Approved  Flashing Frequencies  Role-Music Synopsis</u></a></li>
<li><a href="https://win11.techidaily.com/swift-pc-exploration-via-everythingapp/"><u>Swift PC Exploration via EverythingApp</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-for-outlook-error-0x80040610-on-windows-devices/"><u>Quick Fix for Outlook Error 0X80040610 on Windows Devices</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/essential-guide-mastering-audio-capture-on-your-mac-with-top-5-tricks/"><u>Essential Guide Mastering Audio Capture on Your Mac with Top 5 Tricks</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-from-beginner-to-pro-top-glitch-video-editors-for-every-skill-level/"><u>New In 2024, From Beginner to Pro Top Glitch Video Editors for Every Skill Level</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-gpu-capabilities-the-6-best-testers-in-windows/"><u>Navigate Through GPU Capabilities: The 6 Best Testers in Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/seamless-transitions-in-vlogs-with-jump-cuts-magic-for-2024/"><u>Seamless Transitions in Vlogs with Jump Cuts Magic for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-obs-supreme-vs-streamlabs-empire/"><u>[Updated] OBS Supreme vs Streamlabs Empire</u></a></li>
<li><a href="https://win11.techidaily.com/1719361152872-lowest-black-friday-keys-fan-discount-on-windows-11-free-forever/"><u>Lowest Black Friday Keys Fan Discount on Windows 11, Free Forever!</u></a></li>
</ul></div>
