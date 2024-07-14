---
title: Disabling Excessive Windows Contrast Effects
date: 2024-07-13T10:00:19.732Z
updated: 2024-07-14T10:00:19.732Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Excessive Windows Contrast Effects
excerpt: This Article Describes Disabling Excessive Windows Contrast Effects
keywords: Reduce Windows Contrast,Minimize Windows Palette,Lower Window Brightness,Decrease Windows Glare,Dim Windows Overexposure,Cut Windows Highlighting,Control Windows Luminosity
thumbnail: https://thmb.techidaily.com/6d6cac7e56858e74f7b2bccf55f62023ebda6695ca7ede5596cad05ed3aac833.jpg
---

## Disabling Excessive Windows Contrast Effects

 Microsoft first introduced high-contrast themes with Windows 7\. The idea was to add a theme that helps users with low vision or photosensitivity see screen elements better. But not everyone needs the high contrast mode on Windows 11 or older versions. Maybe you turned it on by accident and are now struggling to turn it off.

 High contrast mode makes the screen elements darker to increase clarity, but the result may not look inviting for every user. As such, we will explore multiple methods to turn off the high contrast mode on Windows 11 or older operating systems.

## What Is High Contrast Mode?

 High Contrast Mode is an accessibility feature that comes free with Windows. It makes certain screen elements darker and more distinguishable so that users with low vision can see everything. High contrast mode isn’t limited to Windows only; you can also find it in Android, iOS, macOS, Linux, and more.

 But there is a dark mode on Windows 11, isn't there? So, why do we need high-contrast themes? It is because dark mode can reduce the strain on the eyes and is helpful for users who don’t have problems with their vision. But dark mode makes everything black except the text and people with low vision may struggle with it.

 High contrast themes offer customizability to tweak different screen elements, like text, links, background, button text, and more. It's a lot more helpful than dark mode, which just adds a dark or black-grayish background with a white color.

## How to Disable High Contrast Mode on Windows

 If High Contrast Mode has been turned on and you'd like to change that, there are multiple ways to get the job done.

### 1\. Using the High Contrast Mode Shortcut keys

 To disable high contrast mode on Windows using keyboard shortcuts, press the**Left Alt + Left Shift + Print Screen** keys at once. You won’t see any pop-up window to confirm the action, but you will hear a “beep” sound before the system reverts to the default theme. You can use this shortcut again if you need to re-enable High Contrast mode.

### 2\. Using the Settings app

 To disable the high contrast mode using the Settings app on Windows 8 and above, do as follows.

1. Press**Win + I** to [launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) on your system.
2. Navigate to the left-hand side menu and click on**Personalization** .
3. Click on the**Themes** option under Personalization. Scroll down and click on the**Contrast Themes** option.
4. Click on the drop-down menu in the Contrast Themes option and select the**None** option.  
![Disable High Contrast Mode Using Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-settings-app.jpg)
5. Then, click on the**Apply** option. Windows will change back to the previous theme.

### 3\. Using the Sign-in screen

 You can even disable the high contrast mode on Windows 11 and 10 before you sign in. Here’s how to do it:

1. Power on your Windows PC. Press any key or click the mouse key to go to the sign-in screen.
2. Navigate to the bottom-right area and click on the**Accessibility** icon.
3. The Accessibility menu will pop up. Click on the**Contrast Theme** toggle to disable it.  
![Disable High Contrast Mode Using Sign In Screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-sign-in-screen.jpg)
4. Windows will revert to the default theme. Enter your PIN or password and log in.

### 4\. Using the Control Panel

 To disable the high contrast mode in Windows 11 and 10, do as follows:

1. Press the**Win + S** to bring up Windows Search. Type Control Panel and click on the search result
2. The Control Panel will launch. Click on the**Appearance and Personalization** option.
3. Select the Ease of Access option and click on the**Set Up high contrast** option.
4. Now, select the**Choose a high contrast theme** option.  
![Disable High Contrast Mode Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-control-panel.jpg)
5. Navigate to**Themes > Contrast Themes** .
6. Click on the drop-down menu in the Contrast Themes option and select the**None** option.
7. Then, click on the**Apply** button.

 Windows 7 doesn’t have a Settings app, so the process of disabling high contrast mode using the Control Panel is a bit different:

1. Press the**Win** key and click on the Control Panel option.
2. Navigate to**Appearance and Personalization > Personalization** .
3. Click on the Windows classic theme or any other system theme.
4. Windows 7 will switch from the high contrast theme to a normal theme.

### 5\. Using the Run Dialog Box

 Repeat the following steps to disable high contrast mode using the run command box:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type “**shell:::{ED834ED6-4B5A-4bfe-8F11-A626DCB6A921}** ” in the text input area and press the Enter key.  
![Disable High Contrast Mode Using Run Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-run-box.jpg)
3. The old personalization settings control panel window will launch.
4. Click on any system theme. It will deactivate the current high-contrast theme and apply the selected theme.

### 6\. Using Another Theme

 You can disable the high-contrast theme by applying another theme to your system. Here’s how to do it:

1. Press**Win + I** to launch the Settings app.
2. Navigate to**Personalization > Themes** .
3. Move to the**Current theme** section and click on any default system theme or a downloaded theme.  
![Disable High Contrast Mode Using A Different Theme](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-a-different-theme.jpg)
4. Windows will apply the selected theme.

 If you want to re-enable the high-contrast theme, you have to visit the "high contrast theme" section here and choose a compatible theme.

### 7\. Using a Script

 It is also possible to revert to a system theme using a script file on Windows. It will take less time as opposed to navigating the settings app to disable the high contrast mode. Here’s how to do it:

1. Go to the desktop. Right-click on the desktop and click on**New > Text Document** .
2. Open the newly created text file and paste the following script into it.  
@echo off C:\Windows\resources\Themes\aero.themetaskkill /F /IM systemsettings.exe
3. Now, press**Ctrl + S** to save the file. Type the name “**disablehc.bat** ” and click on the**save** button.  
![Disable High Contrast Mode Using a script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-high-contrast-mode-using-a-script.jpg)
4. Go to the desktop again and right-click on the newly created .bat file.
5. Select the**Run as administrator** option in the context menu.
6. UAC will pop up. Click on the**Yes** button to grant administrator privileges to the .bat file. Otherwise, it won’t be able to make changes to the system theme.
7. The command prompt will pop up for a few seconds, run the script, and then close automatically. Your Windows system will disable the high contrast mode and switch to the aero theme.

## The Windows High Contrast Theme Won’t Bother You Anymore

 These were the seven methods using which you can disable the high contrast theme on Windows. The quickest way is to use the hotkeys for contrast themes or use a BAT script. If you want to save your eyes from the harsh white light but cannot stand high-contrast themes, use a dark theme on Windows 11.

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
<li><a href="https://win11.techidaily.com/to-keep-or-not-to-delete-the-case-of-pagefilesys/"><u>To Keep or Not to Delete: The Case of Pagefile.sys</u></a></li>
<li><a href="https://win11.techidaily.com/quashing-the-spontaneous-search-on-win11-pc/"><u>Quashing the Spontaneous Search on Win11 PC</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2023s-must-have-tiktok-items-available-on-amazon/"><u>[New] 2023'S Must-Have TikTok Items Available on Amazon</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-honor-90-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, Honor 90 ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/how-to-be-a-beauty-guru-on-youtube-beauty-vlogger-set-up/"><u>How To Be A Beauty Guru on YouTube  Beauty Vlogger Set Up</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-laughter-labyrinas-ideas-that-resonate-with-crowds/"><u>In 2024, Laughter Labyrinas  Ideas That Resonate with Crowds</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-nixing-facebook-broadcasts-effortlessly-for-2024/"><u>[New] Nixing Facebook Broadcasts Effortlessly for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-ringtone-recommendations-for-your-chromium-phone/"><u>2024 Approved  Ringtone Recommendations for Your Chromium Phone</u></a></li>
<li><a href="https://win11.techidaily.com/swift-methods-how-to-determine-hard-drivessd-status-in-windows-system/"><u>Swift Methods: How to Determine Hard Drive/SSD Status in Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/protocols-to-enter-windows-administrative-hub/"><u>Protocols to Enter Windows' Administrative Hub</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-prolong-shutdown-in-windows-10-amidst-active-processes/"><u>Techniques to Prolong Shutdown in Windows 10 Amidst Active Processes</u></a></li>
<li><a href="https://techidaily.com/solutions-to-repair-corrupt-pdf-v12-file-stellar-by-stellar-guide/"><u>Solutions to Repair Corrupt PDF v1.2 File | Stellar</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-fixes-conquering-the-fatal-javascript-glitch-in-discord-win-11/"><u>Step-by-Step Fixes: Conquering the Fatal Javascript Glitch in Discord Win 11</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-in-2024-a-lens-on-innovation-how-hdri-redefines-video-production-standards/"><u>[New] In 2024, A Lens on Innovation  How HDRI Redefines Video Production Standards</u></a></li>
<li><a href="https://win11.techidaily.com/maxing-out-melodies-best-5-apps-for-boosting-windows-audio-by-100plus/"><u>Maxing Out Melodies: Best 5 Apps for Boosting Windows' Audio By 100%%+</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-the-art-of-format-transmutation-srt-to-ssa-and-more/"><u>[New] 2024 Approved  The Art of Format Transmutation  SRT to SSA & More</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-tutorial-turning-on-grid-view-in-google-meet-chats-for-2024/"><u>[Updated] Tutorial  Turning On Grid View in Google Meet Chats for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-driver-not-running-error-in-windows-11/"><u>Solutions for Driver Not Running Error in Windows 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-the-red-zones-best-unraveling-zombie-gaming-delights-for-2024/"><u>[New] The Red Zone's Best  Unraveling Zombie Gaming Delights for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-5ghz-wireless-hurdles/"><u>Overcoming Windows 11 5GHz Wireless Hurdles</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-navigating-through-complete-circles-on-screen/"><u>In 2024, Navigating Through Complete Circles on Screen</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-solve-package-problems-in-windows-oses/"><u>Strategies to Solve Package Problems in Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-error-0x8007251d-windows-activation-demystified/"><u>Mastery over Error 0X8007251D: Windows Activation Demystified</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-closed-nvidia-cp-window-in-w11-os/"><u>Overcoming Closed Nvidia CP Window in W11 OS</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-youtube-earnings-estimator-tools/"><u>In 2024, YouTube Earnings Estimator Tools</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-os-security-patches/"><u>Navigating Windows OS Security Patches</u></a></li>
<li><a href="https://win11.techidaily.com/why-gamers-should-trust-windows-vision-and-performance/"><u>Why Gamers Should Trust Windows' Vision and Performance</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-essential-choices-top-10-best-video-editing-software-free-2023/"><u>In 2024, Essential Choices  Top 10 Best Video Editing Software (Free, 2023)</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-key-selections-top-6-fb-lite-video-grabs/"><u>[New] Key Selections  Top 6 FB Lite Video Grabs</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-experience-clearing-and-rebuilding-icons/"><u>Streamlining Your Experience: Clearing and Rebuilding Icons</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-win11-startup-options-a-comprehensive-guide/"><u>Navigating Win11 Startup Options: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-microphone-settings-in-w11-systems/"><u>Mastering Microphone Settings in W11 Systems</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-skyrocket-your-youtube-dollars-with-short-video-monetization/"><u>2024 Approved  Skyrocket Your YouTube Dollars with Short Video Monetization</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-top-picks-for-superior-nintendo-switch-gaming-for-2024/"><u>[New] Top Picks for Superior Nintendo Switch Gaming for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-track-windows-10-and-11-note-hacks/"><u>Keeping Track: Windows 10 & 11 Note Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-missing-thermal-policy-in-windows-environment/"><u>Restoring Missing Thermal Policy in Windows Environment</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-innovative-android-for-ultimate-3d-playback/"><u>2024 Approved  Innovative Android for Ultimate 3D Playback</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-2024-approved-social-snippet-collection-mastery-efficient-method-for-downloading-animated-tweet-graphics/"><u>[New] 2024 Approved  Social Snippet Collection Mastery  Efficient Method for Downloading Animated Tweet Graphics</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-ultimate-guide-to-economical-high-performance-asmr-microphones/"><u>In 2024, Ultimate Guide to Economical, High-Performance ASMR Microphones</u></a></li>
<li><a href="https://win11.techidaily.com/pro-tips-for-using-lesser-known-windows-11-assets-efficiently/"><u>Pro-Tips for Using Lesser Known Windows 11 Assets Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-your-pc-with-apples-imessage/"><u>Setting Up Your PC with Apple's iMessage</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-explore-diverse-backdrops-for-tiktok-videos/"><u>2024 Approved  Explore Diverse Backdrops for TikTok Videos</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-not-writable-file-problems-in-windows-11/"><u>Solutions for Not Writable File Problems in Windows 11</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-becoming-a-final-cut-pro-expert-your-quick-reference-for-2024/"><u>[Updated] Becoming a Final Cut Pro Expert – Your Quick Reference for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-comprehensive-pathway-to-load-moviemaker-6/"><u>[New] Comprehensive Pathway to Load Moviemaker 6</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-the-conflict-between-apps-and-computers-default-audio/"><u>Remedying the Conflict Between Apps and Computer's Default Audio</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-secure-boot-and-tpm-activationdeactivation-in-vbox-70/"><u>Mastering Secure Boot and TPM Activation/Deactivation in VBox 7.0</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-step-up-your-podcast-game-with-expert-guidance-on-zooming-into-quality/"><u>[Updated] Step Up Your Podcast Game with Expert Guidance on Zooming Into Quality</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-choices-activating-filters-on-windows-11-files/"><u>Streamline Choices: Activating Filters on Windows 11 Files</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-guide-reactivate-disabled-slack-notifications/"><u>Win 11 Guide: Reactivate Disabled Slack Notifications</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-effortless-method-to-retrace-video-steps-in-snapchat/"><u>[Updated] 2024 Approved  Effortless Method to Retrace Video Steps in Snapchat</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-the-seamless-journey-of-audio-recording-in-windows-10-tips-and-tricks-for-clear-soundscape-creation/"><u>New The Seamless Journey of Audio Recording in Windows 10 Tips and Tricks for Clear Soundscape Creation</u></a></li>
<li><a href="https://driver-install.techidaily.com/easy-installer-enable-your-tp-link-adapter-on-windows-pcs/"><u>Easy Installer: Enable Your TP Link Adapter on Windows PCs</u></a></li>
<li><a href="https://techidaily.com/is-your-lava-agni-2-5g-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Lava Agni 2 5G working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-windows-services-command-line-tool-with-these-7-steps/"><u>Restoring Window's Services Command Line Tool with These 7 Steps</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/elevate-your-live-streaming-with-phone-webcams-and-filming-hacks-for-2024/"><u>Elevate Your Live Streaming with Phone Webcams and Filming Hacks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-10-best-apps-to-replace-windows-11s-default-apps/"><u>The 10 Best Apps to Replace Windows 11'S Default Apps</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/leading-5-audio-caps-for-streaming-enthusiasts/"><u>Leading 5 Audio Caps for Streaming Enthusiasts</u></a></li>
<li><a href="https://extra-resources.techidaily.com/top-tier-editing-suites-in-apples-macos-big-sur-release/"><u>Top-Tier Editing Suites in Apple's MacOS Big Sur Release</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-enhancing-professionalism-with-zooms-snappy-functionality/"><u>[New] 2024 Approved  Enhancing Professionalism with Zoom’s Snappy Functionality</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ow-to-turn-on-av1-settings-on-youtube-and-why-you-should-do-it-for-2024/"><u>[New] How to Turn on AV1 Settings on YouTube and Why You Should Do It for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-installing-new-drivers-in-windows-11/"><u>Mastering the Art of Installing New Drivers in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-11-mail-issues-with-html-enhanced-emails/"><u>Troubleshooting Windows 11 Mail Issues with HTML-Enhanced Emails</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-error-exception-breaking-point-achieved-in-windows/"><u>Troubleshooting Error: Exception Breaking Point Achieved in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/operating-unity-windows-rolls-out-across-apple-pc-mac-android-world/"><u>Operating Unity: Windows Rolls Out Across Apple, PC, Mac, Android World</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-fix-to-unknown-not-initialized-in-windows/"><u>Step-by-Step Fix to 'Unknown Not Initialized' In Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-after-format-on-lava-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos from Android Gallery after format on Lava</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-prevalent-windows-rainmeter-troubles/"><u>Navigating Through Prevalent Windows Rainmeter Troubles</u></a></li>
</ul></div>
