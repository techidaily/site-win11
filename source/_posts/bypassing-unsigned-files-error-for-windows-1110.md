---
title: Bypassing Unsigned Files Error for Windows 11/10
date: 2024-07-13T10:29:42.227Z
updated: 2024-07-14T10:29:42.227Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing Unsigned Files Error for Windows 11/10
excerpt: This Article Describes Bypassing Unsigned Files Error for Windows 11/10
keywords: Windows Unsigned Error Fix,Windows File Handling Bypass,Win11/10 Signature Exception,Silent Installation Skip Error,Unsigned Files Troubleshoot,W11/W10 Bootloader Correction,Bypassing File Validity Issue
thumbnail: https://thmb.techidaily.com/1d89ad9f3797ef5721bb1984cb133f0b9a82053479b93a4aeb543f338378bede.jpg
---

## Bypassing Unsigned Files Error for Windows 11/10

 Users frequently report Windows 11/10 update errors on software support forums. One such update issue reported is an error message that says, “Some update files aren’t signed.” Some users see that error message appear within Settings’ Windows Update tab when trying to update Windows.

 Windows updates fail to install when this issue occurs. This error usually includes either a 0x800b0109 or 0x800b0100 code after its message. This is how you can resolve the “Some update files aren’t signed” error 0x800b0109 on a Windows 11/10 PC.

## 1\. Utilize the Windows Update Troubleshooter

 The Windows Update troubleshooting tool is there to help you fix any issues encountered when trying to update Windows 11/10\. That troubleshooter doesn’t necessarily fix every update error, but it can at least resolve some issues.

 So, utilizing that troubleshooter is always worth a try, which you can access in Settings as covered within this guide to [running any troubleshooter on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/).

![The Windows Update troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-update-troubleshooter.jpg)

## 2\. Run Deployment Imaging and System File Scans

 System file corruption is among the [most common reasons for Windows update errors](https://www.makeuseof.com/reasons-why-windows-updates-fail/). For that reason, running a System File Checker scan to address system file corruption is a recommended troubleshooting method for error 0x800b0109\.

 It’s also advisable to utilize the Deployment Imaging and Servicing Management to repair possible Windows image corruption.

 Both Deployment Imaging and System File Checker are Command Prompt tools. You can run them by inputting and executing two commands within the Command Prompt. Our article on [repairing corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) includes instructions on how to utilize the SFC and DISM command-line tools.

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-sfc-scannow.jpg)

## 3\. Check the Windows Update and BITS Services Are Enabled

 Windows Updates and Background Intelligent Transfer Service (BITS) are two services that need to be enabled for updates. So, check those services are correctly set like this:

1. Simultaneously press the **Windows** logo + **S** keys on your keyboard.
2. Enter the search phrase "services" to find the app with a matching title.
3. Click on **Services** inside the search results.
4. Double-click **Windows Update** to access settings for that service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/services-window.jpg)
5. Set the **Startup type** setting to the **Automatic** option.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/startup-type-drop-down-menu.jpg)
6. Click **Start** (inside the properties windows) to run the Windows Update service.
7. Save the settings by pressing the **Apply** and **OK** buttons.
8. Double-click the **Background Intelligent Transfer Service** to view its settings.
9. Select a **Manual** startup option.
10. Click the **Start** option for the BITS service if it’s stopped.
11. Then click on the **Apply** and **OK** options to set that service’s options.

 If you find both services to be already enabled and running, try restarting them. You can do so by right-clicking the BITS and Windows Update service names and selecting a **Restart** option on their context menus.

## 4\. Reset Components for Windows Updates

 Resetting components for Windows updates will completely refresh the catroot2 and SoftwareDistribution folders, which store update data. This troubleshooting method also reregisters all DLL files for important update services. Applying such a potential resolution can fix corrupted components causing error 0x800b0109\.

 To apply this possible error 0x800b0109 resolution, check out our article on [resetting Windows update components](https://www.makeuseof.com/reset-windows-update-components/). That guide includes a command-line and batch file method. Creating and running a batch file is the quicker and more straightforward way to reset Windows update components.

## 5\. Deactivate Third-Party Security Software

 A third-party security (antivirus) app can potentially conflict with Windows update processes. This can happen when the antivirus protection of a security app locks files needed by Windows Update. It’s not something that happens often, but temporarily disable any third-party antivirus protection on your PC just in case.

 Security apps typically include options for disabling antivirus protection on their system tray context menus. Right-click your security app’s icon in Windows 11’s system tray area to find and select its option for temporarily disabling the antivirus shield. Then, return to the Settings app to see if error 0x800b0109 still happens with the antivirus shield disabled.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

## 6\. Erase the Windows Update Key

 Deleting the Windows Update registry key is a potential resolution some users confirm to fix error 0x800b0109\. However, we always recommend [backing up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or saving a system restoration point before deleting registry keys.

 When you’ve done that, try deleting the Windows Update key like this:

1. Open Run, accessible by pressing **Windows** logo key + **R**, and type a **regedit** command into that accessory.
2. Select Run’s **OK** option to open the Registry Editor.
3. Next, clear the registry address bar and input this key path there:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate`
4. Right-click the WindowsUpdate registry key to select **Delete**.  
![The Delete context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-delete-option-1.jpg)
5. Click **Yes** when prompted for confirmation to delete the key.  
![The Confirm Key Delete prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-key-confirmation-1.jpg)

 Thereafter, it’s also recommended to restart the Windows Update and BITS services. To do so, open Services as covered in the first three steps of resolution three. Then, select the **Restart** context menu options for Windows Update and BITS.

## 7\. Try Downloading the Failed Update From Microsoft Update Catalog

 If error 0x800b0109 still isn’t fixed after applying the potential resolutions above, try going around it by manually downloading the affected update from [Microsoft Update Catalog](https://www.catalog.update.microsoft.com/Home.aspx). Then, you can install the update with an MSU file downloaded from there.

 You will first need to identify what update is failing as follows:

1. Simultaneously press your keyboard’s **Windows** logo + **I** keys to access Settings.
2. Click **Windows Update** (or **Update & Security**) in Settings.
3. Select **Update history** to view installed and failed updates.  
![The update history in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-history4.jpg)
4. Note down the KB code for your recently failed Windows update.

 Then, you can find and download that failed update on the Microsoft Update Catalog website. This article about [updating Windows manually](https://www.makeuseof.com/update-windows-manually/) includes instructions for utilizing the Microsoft Update Catalog.

## 8\. Apply an In-Place Windows Upgrade

 An in-place Windows upgrade is the last resort for fixing error 0x800b0109\. Applying this potential resolution will reinstall Windows on your PC with its latest ISO file. The installation of a fresh Windows copy will likely resolve other issues causing the 0x800b0109 update error that other potential solutions couldn’t fix.

 The good thing about an in-place upgrade is that it won’t eradicate your installed software or user files. This [how-to perform an in-place upgrade](https://www.makeuseof.com/in-place-upgrade-windows-11/) guide tells you how to apply this potential solution for Windows 11\. The steps are quite similar for Windows 10, but you’ll need to download its ISO with the Media Creation Tool available on this [Microsoft page](https://www.microsoft.com/en-gb/software-download/windows10).

![The Windows 10 Media Creation tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-10-setup-window.jpg)

## Get Windows Updated Again

 There isn’t a surefire way to fix error 0x800b0109 since there are varied possible reasons for that Windows 11/10 issue occurring. However, it’s likely at least one of the eight potential resolutions in this guide will fix that update issue on your PC.

 Some of the best third-party Windows repair tools might also be helpful for resolving the “Some update files aren’t signed” error.

 Windows updates fail to install when this issue occurs. This error usually includes either a 0x800b0109 or 0x800b0100 code after its message. This is how you can resolve the “Some update files aren’t signed” error 0x800b0109 on a Windows 11/10 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/uncover-hidden-cameras-fix-their-absence-in-dm/"><u>Uncover Hidden Cameras: Fix Their Absence in DM</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-plugged-inspection-failure-for-pc-sound-devices/"><u>Addressing Plugged Inspection Failure for PC Sound Devices</u></a></li>
<li><a href="https://win11.techidaily.com/thwarting-windows-users-from-altering-system-time/"><u>Thwarting Windows Users From Altering System Time</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-avoiding-pitfalls-in-sub4sub-key-lessons-from-a-seasoned-guide/"><u>[Updated] Avoiding Pitfalls in Sub4sub  Key Lessons From a Seasoned Guide</u></a></li>
<li><a href="https://win11.techidaily.com/winning-strategy-fine-tuning-your-amd-settings-in-windows-gaming/"><u>Winning Strategy: Fine-Tuning Your AMD Settings in Windows Gaming</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-free-video-editing-made-easy-a-wax-tutorial-for-beginners/"><u>Updated In 2024, Free Video Editing Made Easy A Wax Tutorial for Beginners</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-virtual-space-clearing-perfecting-your-backdrop-in-zoom-and-google-meet-for-2024/"><u>[Updated] Virtual Space Clearing  Perfecting Your Backdrop in Zoom & Google Meet for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-switch-apps-using-snap-feature-in-windows-11/"><u>Swiftly Switch Apps Using Snap Feature in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tricks-to-enable-touch-typing-on-windows-laptops/"><u>Tricks to Enable Touch Typing on Windows Laptops</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/new-how-to-reach-more-users-by-using-instagram-live-shopping-for-2024/"><u>New How To Reach More Users by Using Instagram Live Shopping for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-huaweifrp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your HuaweiFRP Lock</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-management-cli-integration-into-taskmgr/"><u>Streamlining Windows Management: CLI Integration Into TaskMgr</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-fn-keys-functionality-on-windows-1011/"><u>Optimizing FN Keys' Functionality on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-revive-a-non-responsive-windows-notepad-application/"><u>How to Revive a Non-Responsive Windows Notepad Application</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-your-windows-11-installation-essential-settings-guide/"><u>Personalize Your Windows 11 Installation: Essential Settings Guide</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-microsoft-to-do-app-when-its-not-syncing/"><u>How to Fix the Microsoft To Do App When It’s Not Syncing</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-not-responsive-spotify-error-in-windows-oses/"><u>Resolving Not Responsive Spotify Error in Windows OSes</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-online-tiktok-watermark-remover-tools-no-logo-no-problem/"><u>Updated Online TikTok Watermark Remover Tools No Logo, No Problem</u></a></li>
<li><a href="https://win11.techidaily.com/winning-at-organizing-the-art-of-customizing-windows-outlook-calendars/"><u>Winning at Organizing: The Art of Customizing Window's Outlook Calendars</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-command-line-experience-with-terminal-preference/"><u>Enhance Your Command Line Experience with Terminal Preference</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-a-faulty-esc-key-in-windows-10-and-beyond/"><u>Troubleshoot a Faulty Esc Key in Windows 10 and Beyond</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-downloads-not-working-on-win-devices/"><u>How to Resolve Downloads Not Working on Win Devices</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-effective-ways-to-bypass-activation-lock-from-apple-iphone-15-pro-by-drfone-ios/"><u>3 Effective Ways to Bypass Activation Lock from Apple iPhone 15 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-windows-11-vm-reset/"><u>Guidelines for Windows 11 VM Reset</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-reimagining-blockbuster-films-ranked-7-1/"><u>[New] Reimagining Blockbuster Films, Ranked #7-1</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-unleash-creativity-top-screencast-tools-recommended-by-experts/"><u>[New] In 2024, Unleash Creativity  Top Screencast Tools Recommended by Experts</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-straightforward-guide-to-ios-screen-share-simplicity/"><u>[New] Straightforward Guide to IOS Screen Share Simplicity</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-browser-speed-discrepancy-across-devices/"><u>Bridging Browser Speed Discrepancy Across Devices</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-unlock-professional-graphics-custom-templates-on-the-house/"><u>[Updated] In 2024, Unlock Professional Graphics - Custom Templates on the House</u></a></li>
<li><a href="https://win11.techidaily.com/access-advanced-control-panel-to-change-screen-after-dark-mode/"><u>Access Advanced Control Panel to Change Screen After Dark Mode</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-samsung-galaxy-s21-fe-5g-2023-drfone-by-drfone-virtual-android/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Samsung Galaxy S21 FE 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/guiding-principles-for-altering-tone-without-sacrificing-sound-quality-using-audacity-for-2024/"><u>Guiding Principles for Altering Tone Without Sacrificing Sound Quality Using Audacity for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-3d-paint-efficiency-with-these-tricks/"><u>Boost Your 3D Paint Efficiency With These Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-secure-windows-sound-level-adjustments/"><u>Tips to Secure Windows Sound Level Adjustments</u></a></li>
<li><a href="https://win11.techidaily.com/decades-of-designs-the-windows-taskbars-journey/"><u>Decades of Designs: The Windows Taskbar's Journey</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ring-360-degree-videos-secure-youtube-uploads-for-2024/"><u>Mastering 360-Degree Videos  Secure YouTube Uploads for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlock-vivo-y27-5g-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>Unlock Vivo Y27 5G Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-the-audio-editors-handbook-6-methodical-steps-for-clearing-vocals-using-adobe-audition/"><u>In 2024, The Audio Editors Handbook 6 Methodical Steps for Clearing Vocals Using Adobe Audition</u></a></li>
<li><a href="https://win11.techidaily.com/revive-volume-control-preferences-in-your-windows-pc/"><u>Revive Volume Control Preferences in Your Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/stabilizing-visual-studio-code-on-windows-11/"><u>Stabilizing Visual Studio Code on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-the-barrier-installed-windows-11-on-mac-through-parallels/"><u>Breaking the Barrier: Installed Windows 11 on Mac Through Parallels</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-role-of-look-up-tables-in-cinematic-coloring/"><u>In 2024, The Role of Look-Up Tables in Cinematic Coloring</u></a></li>
<li><a href="https://facebook.techidaily.com/meta-unleashed-3-reasons-to-worry/"><u>Meta Unleashed: 3 Reasons to Worry</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-realme-11x-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On Realme 11X 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reactivate-missing-windows-phone-link-notifications/"><u>Steps to Reactivate Missing Windows Phone Link Notifications</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/linguistic-insights-into-turk-korean-exchange/"><u>Linguistic Insights Into Turk-Korean Exchange</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-examining-screen-capture-efficacy-obs-studio-vs-fraps-for-2024/"><u>[Updated] Examining Screen Capture Efficacy  OBS Studio vs Fraps for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-honor-magic-6-lite-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Honor Magic 6 Lite</u></a></li>
<li><a href="https://win11.techidaily.com/deceleration-dilemnas-quick-fixes-for-discord-lag/"><u>Deceleration Dilemnas: Quick Fixes for Discord Lag</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-revolutionizing-voice-capture-a-compreenas-guide-to-facetime-recording/"><u>In 2024, Revolutionizing Voice Capture  A Compreenas Guide to FaceTime Recording</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-missing-system-cooling-policy-on-windows/"><u>How to Fix a Missing System Cooling Policy on Windows</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-2024-approved-what-is-ai-generated-text-wondershare-virbo-glossary/"><u>Updated 2024 Approved What Is AI Generated Text? | Wondershare Virbo Glossary</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-invisible-icons-menu-on-modern-windows-11/"><u>Accessing Invisible Icons Menu on Modern Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-mail-apps-0x800713f-error-in-windows-11-and-11/"><u>How to Fix the Mail App’s 0X800713f Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-memory-hurdles-4-tips-for-better-windows-ram/"><u>Overcoming Memory Hurdles: 4 Tips for Better Windows RAM</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-transformative-tutorial-turning-vids-on-twitter-into-catchy-animated-memes-gifs/"><u>[New] Transformative Tutorial  Turning Vids on Twitter Into Catchy Animated Memes (GIFs)</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-swiftclick-retrorecall-video-for-2024/"><u>[New] SwiftClick RetroRecall Video for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-strategies-for-dispelling-blue-screen-of-operation-requires-elevation-in-winos/"><u>Efficient Strategies for Dispelling Blue Screen of Operation Requires Elevation in WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/handling-unable-to-open-file-for-writing-error-in-win-11/"><u>Handling Unable to Open File for Writing Error in Win 11</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ngs-expedition-navigating-your-way-to-wealth-with-youtube-mobile-content-for-2024/"><u>Earnings Expedition  Navigating Your Way to Wealth with YouTube Mobile Content for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/streamline-entertainment-incorporating-subtitles-into-wmp-for-2024/"><u>Streamline Entertainment  Incorporating Subtitles Into WMP for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/easy-steps-hide-search-icon-from-taskbar-in-win-11/"><u>Easy Steps: Hide Search Icon From Taskbar in Win 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-contacts-from-hot-30-5g-by-fonelab-android-recover-contacts/"><u>Best Android Data Recovery - Retrieve Lost Contacts from Hot 30 5G.</u></a></li>
<li><a href="https://win11.techidaily.com/terminal-vs-powershell-pinpointing-the-distinguishing-aspects/"><u>Terminal Vs. PowerShell: Pinpointing the Distinguishing Aspects</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-infinix-smart-8-hd-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your Infinix Smart 8 HD | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-java-failure-in-windows-installation/"><u>Troubleshooting Java Failure in Windows Installation</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-change-location-on-facebook-marketplace-for-poco-f5-pro-5g-drfone-by-drfone-virtual-android/"><u>3 Ways to Change Location on Facebook Marketplace for Poco F5 Pro 5G | Dr.fone</u></a></li>
</ul></div>
