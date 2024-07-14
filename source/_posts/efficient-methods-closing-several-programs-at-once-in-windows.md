---
title: "Efficient Methods: Closing Several Programs at Once in Windows"
date: 2024-07-13T09:44:58.980Z
updated: 2024-07-14T09:44:58.980Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Efficient Methods: Closing Several Programs at Once in Windows"
excerpt: "This Article Describes Efficient Methods: Closing Several Programs at Once in Windows"
keywords: Quick Close Procs Windows,Multi-Close App Windows,Group Shutdown Windows,Unite Closure Tasks PC,Simultaneous Program Exit,Twin Close Windows Easy,Mass Application Terminate
thumbnail: https://thmb.techidaily.com/0838ac8f5f2d8f067138531cc9f4dfd905cfa9adb1733f1b9948bd185f0bb490.jpg
---

## Efficient Methods: Closing Several Programs at Once in Windows

 Running multiple apps simultaneously can usually affect your PC’s performance. This means you might often want to close some programs to speed up your device. But here’s the thing—closing your apps one by one can be quite tedious.

 So, how can you simplify things and close your multiple apps simultaneously on Windows? Let’s find out.

## 1\. Use the Taskbar

 The Windows taskbar displays all your active and pinned programs. This means you can easily close your active apps by scrolling to the relevant taskbar icon and clicking the “close” button.

 The good news is that you can also use the taskbar to close multiple windows of the same program. However, you won’t be able to close different apps simultaneously using the taskbar.

 Here's how to close multiple windows of the same program on the taskbar:

1. Navigate to the taskbar and locate an app that has multiple active windows.
2. Right-click on the app and select the **Close all windows** option.

![Closing multiple windows on the taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/closing-multiple-windows-on-the-taskbar.jpg)

## 2\. Use the Resource Monitor

 You probably know that you can [force close your PC programs](https://www.makeuseof.com/tag/how-to-kill-unresponsive-programs-without-the-task-manager/) using the Task Manager. But the problem is that this tool doesn’t let you close your programs simultaneously.

 Wondering if there's an alternative tool you can use? Try the Resource Monitor!

 Here are the steps for closing multiple apps simultaneously using the Resource Monitor:

1. Type **Resource Monitor** in the Start menu search bar and select the **Best match**.
2. Navigate to the **Overview** tab.
3. Check the boxes of the apps you want to close.
4. Right-click on one of the results and select the **End Process** option. This should simultaneously close all the programs you selected.

![Closing multiple apps using the Resource Monitor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/closing-multiple-apps-using-the-resource-monitor.jpg)

 Want to know the best part about using the Resource Monitor? This tool allows you to re-open multiple apps simultaneously with just a few clicks!

 Here's how to reopen your apps with the Resource Monitor:

1. Access the **Resource Monitor** by applying the previous steps.
2. Check the boxes of all the apps you want to re-open.
3. Right-click on one of the results and select **Resume Process**.

## 3\. Use the Command Prompt

![Person using a Windows PC while placing it on a lap](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Person-using-a-Windows-PC-while-placing-it-on-a-lap.jpg)

 The Command Prompt can help you troubleshoot PC issues, configure some system settings, and run your Windows apps.

 Interestingly, this tool can also help you simultaneously close multiple windows of the same app. However, the Command Prompt might not be the best option if you want to close different apps simultaneously.

 Here’s how you can close multiple windows of the same app using the Command Prompt:

1. Type **Command Prompt** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.

![Opening the Command Prompt using the Start menu search bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/opening-the-command-prompt-using-the-start-menu-search-bar.jpg)

 Let’s say you want to close multiple File Explorer windows simultaneously. To do that, type the following command in the Command Prompt and press **Enter**:

taskkill /f /im explorer.exe

 The “taskkill /f /im” command is the one that closes the program, and the “explorer.exe” command is the name of the app. To close multiple windows of your other apps, replace the “explorer.exe” part with the relevant command.

## 4\. Create a Batch Script for Closing Multiple Apps Simultaneously

![A person using a Windows device on a desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-person-using-a-Windows-device-on-a-desk.jpg)

 We’ve already discovered that the Command Prompt can only help you close multiple windows of the same app.

 But if you apply a few tricks, you can close multiple apps using some commands. However, you’d need to [create a batch script](https://www.makeuseof.com/tag/write-simple-batch-bat-file/) for that.

 Here's how you can create a batch script for closing multiple apps on Windows:

1. Press **Win + D** to access the desktop. Alternatively, check out the [various ways to access the Windows desktop](https://www.makeuseof.com/windows-quickly-access-desktop/).
2. Right-click on a blank space and select **New > Text Document**. This will create an untitled document on your desktop.

 Now, let’s say you want to close the **Snipping Tool** and the **Paint.net** app simultaneously. Here are the steps you need to follow:

1. Navigate to the desktop and double-click on the text document you’ve just created.
2. Type the following command to close the Snipping Tool:

taskkill /f /im SnippingTool.exe /T > nul

 Next, type the following command to close the Paint.net app:

taskkill /f /im paintdotnet.exe /T > nul

![Creating a Batch Script for Closing Multiple Apps Simultaneously](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/creating-a-batch-script-for-closing-multiple-apps-simultaneously.jpg)

 From there, follow these steps:

1. Press the **File** tab in the top-left corner of the text file.
2. Select the **Save As** option.
3. Type **Close Multiple Apps Simultaneously.bat** in the **File name** box.
4. Press the **Save** button.

 Now, you can close the Snipping Tool and the Paint.net app simultaneously by following these steps:

1. Press **Win + E** to access File Explorer.
2. Select the **Desktop** option on the left.
3. Click the **Close Multiple Apps Simultaneously.bat** batch file.

![Clicking a batch script on the desktop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/clicking-a-batch-script-on-the-desktop.jpg)

 You can add as many apps as you want to your batch script.

 And when using the batch script, ensure that it doesn’t end up closing some important apps by mistake. This means it might be worth regularly checking what’s on the script first before running it.

## 5\. Use the Close All Windows Tool

![The Close All Windows Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-close-all-windows-tool.jpg)

 You can also quickly close your multiple active apps using a third-party program like the [Close All Windows tool](https://www.softpedia.com/get/System/System-Miscellaneous/AA-Close-All-Windows.shtml). The tool is lightweight, which means it won’t take up much of your disk space.

 This app works almost like the Windows built-in Resource Monitor. However, it comes with a basic and easy-to-understand interface. When you open the tool, it immediately displays all your active apps. All you need to do is tick the relevant boxes and then click the **OK** button to close those apps.

 The tool displays all your apps and places them under a specific category. For example, it displays all your Google Chrome windows under the Google Chrome category.

 To select all the apps on the screen, press **Ctrl + A** or navigate to the **Command** tab and click **Select All**. And if you want to uncheck all the apps, press **Ctrl + D** or click the **Deselect All** option from the **Command** tab.

 You can customize the Close All Windows tool by clicking the **View** tab and ticking the relevant boxes. And if the tool seems a bit too complicated to use, then you can navigate to the **Help** tab to get some assistance.

**Download**: Close All Windows for [Windows](https://www.softpedia.com/get/System/System-Miscellaneous/AA-Close-All-Windows.shtml) (Free, subscription available)

## Close Your Multiple Apps Simultaneously With Just a Few Clicks

 It’s always frustrating when your Windows device suddenly becomes slow or buggy. In most cases, such issues are caused by running tons of apps simultaneously.

 Want a quick way to speed up your device? Close your multiple active programs simultaneously using the tips we’ve covered. And if you end up closing some apps by mistake, you can apply some quick tricks to restore them again.


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
<li><a href="https://youtube-help.techidaily.com/instant-grooves-lasting-stories-making-sense-of-music-shorts-for-2024/"><u>Instant Grooves, Lasting Stories  Making Sense of Music Shorts for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-shooting-for-greatness-iphones-10-vital-composition-guidelines/"><u>[Updated] Shooting for Greatness  IPhone's 10 Vital Composition Guidelines</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-the-ultimate-avs-companion-a-deep-dive-into-audio-editing-tools-key-traits-reviews-and-options-to-consider/"><u>Updated 2024 Approved The Ultimate AVS Companion A Deep Dive Into Audio Editing Tools, Key Traits, Reviews & Options to Consider</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-enabling-your-pen-on-windows-os/"><u>Quick Fix: Enabling Your Pen on Windows OS</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-elevate-your-video-presence-with-swiftly-created-captions-and-text-on-fb-for-2024/"><u>[New] Elevate Your Video Presence with Swiftly Created Captions and Text on FB for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-windows-11-priority-over-entertainment/"><u>Optimizing Windows 11: Priority over Entertainment</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-unknown-value-issue-in-windows-tech-environment/"><u>Remedy for Unknown Value Issue in Windows Tech Environment</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-meizu-21-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Meizu 21 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-for-deleting-ms-edge-win11/"><u>Step-by-Step Guide for Deleting MS Edge Win11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-noir-world-of-microsoft-paint/"><u>Navigating the Noir World of Microsoft Paint</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-edges-unending-task-on-windows-11-pcs/"><u>Exploring Edge's Unending Task on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/realigning-windows-error-solutions-for-efficiency/"><u>Realigning Windows Error Solutions for Efficiency</u></a></li>
<li><a href="https://extra-hints.techidaily.com/pro-filmmakers-guide-to-speedy-shot-techniques/"><u>Pro Filmmaker's Guide to Speedy Shot Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/solving-windows-11-menu-glitches-a-step-by-step-guide/"><u>Solving Windows 11 Menu Glitches: A Step-by-Step Guide</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/delete-gmail-account-withwithout-password-on-realme-narzo-60-pro-5g-by-drfone-android/"><u>Delete Gmail Account With/Without Password On Realme Narzo 60 Pro 5G</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/tips-to-keep-tiktok-videos-on-mobile-devices/"><u>Tips to Keep TikTok Videos on Mobile Devices</u></a></li>
<li><a href="https://some-techniques.techidaily.com/eye-shadow-and-lips-tutorials-for-2024/"><u>Eye Shadow & Lips Tutorials for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/solve-yellow-tint-issue-in-windows-monitorage/"><u>Solve Yellow Tint Issue in Windows Monitorage</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-fix-auto-lock-greyed-out-on-apple-iphone-13-pro-by-drfone-ios/"><u>How To Fix Auto Lock Greyed Out on Apple iPhone 13 Pro</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-digitally-sign-svd-file-online-free-tutorial-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to Digitally Sign .svd file online free - (Tutorial)</u></a></li>
<li><a href="https://win11.techidaily.com/locating-group-policies-a-users-guide-for-win-users/"><u>Locating Group Policies: A User's Guide for Win Users</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-lan-gaming-challenges-on-pc-winsminecraft/"><u>Overcoming LAN Gaming Challenges on PC, WinsMinecraft</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-the-path-to-precision-sound-step-by-step-audio-normalization-in-davinci-resolve/"><u>New 2024 Approved The Path to Precision Sound Step-by-Step Audio Normalization in DaVinci Resolve</u></a></li>
<li><a href="https://win11.techidaily.com/device-agnostic-operating-system-windows-for-iphonesipads-macs-pcs-launched/"><u>Device-Agnostic Operating System: Windows for iPhones/iPads, Macs, PCs Launched</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-secure-tcp-protocols-in-windows-os/"><u>Ensuring Secure TCP Protocols in Windows OS</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-elevate-viewer-response-crafting-engaging-ig-story-qandas/"><u>[Updated] In 2024, Elevate Viewer Response  Crafting Engaging IG Story Q&As</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-prevent-and-fix-winscombsvrdll-crashes-on-pcs/"><u>Steps to Prevent and Fix WinscombSvr.dll Crashes on PCs</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-understanding-and-mastering-google-chromes-pip-functionality/"><u>[Updated] Understanding and Mastering Google Chrome’s PIP Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/ideal-replacements-for-windows-snipping-functionality-in-other-oses/"><u>Ideal Replacements for Windows' Snipping Functionality in Other OSes</u></a></li>
<li><a href="https://win11.techidaily.com/mend-your-guard-easy-steps-to-making-family-safe-work-again/"><u>Mend Your Guard: Easy Steps to Making Family Safe Work Again</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-concoct-clever-caricatures/"><u>2024 Approved  Concoct Clever Caricatures</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-contacts-from-xiaomi-mix-fold-3-by-fonelab-android-recover-contacts/"><u>Undelete lost contacts from Xiaomi Mix Fold 3.</u></a></li>
<li><a href="https://win11.techidaily.com/full-method-to-turn-off-wsl-in-windows-1011/"><u>Full Method to Turn Off WSL in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/safe-harbor-for-windows-free-software-selections/"><u>Safe Harbor for Windows Free Software Selections</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-infinix-note-30-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Infinix Note 30? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/directx-installation-guide-easy-downloads-and-updates/"><u>DirectX Installation Guide: Easy Downloads & Updates</u></a></li>
<li><a href="https://win11.techidaily.com/secure-and-cost-free-windows-password-gen-options-listed/"><u>Secure & Cost-Free Windows Password Gen Options Listed</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-6-appsservices-to-trace-any-vivo-v30-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>Top 6 Apps/Services to Trace Any Vivo V30 Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-samsung-galaxy-a25-5g-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos From Samsung Galaxy A25 5G to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/pro-wls-2-strategies-optimizing-linux-experience-in-windows/"><u>Pro WLS 2 Strategies: Optimizing Linux Experience in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/five-tips-to-prevent-already-used-name-conflicts-in-networking/"><u>Five Tips to Prevent 'Already Used' Name Conflicts in Networking</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Xiaomi Redmi Note 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reveal-windows-secrets-to-handbrake-use/"><u>Reveal Windows' Secrets to HandBrake Use</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-accessibility-of-your-offline-printer-on-windows/"><u>Regaining Accessibility of Your Offline Printer on Windows</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-break-through-noise-effective-utilization-of-video-templates-for-2024/"><u>[Updated] Break Through Noise  Effective Utilization of Video Templates for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-recover-from-windows-11s-zero-a00f-camera-blunder/"><u>How to Recover From Windows 11'S Zero-A00F Camera Blunder</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-top-8-best-daw-app-for-android-to-accelerate-your-music-production/"><u>Updated Top 8 Best DAW App for Android to Accelerate Your Music Production</u></a></li>
<li><a href="https://win11.techidaily.com/solving-the-jittery-cursor-problem-on-windows-xp/"><u>Solving the Jittery Cursor Problem on Windows XP</u></a></li>
<li><a href="https://win11.techidaily.com/guide-setting-up-google-play-on-w11-os/"><u>Guide: Setting Up Google Play on W11 OS</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-gigglygraphics-mememakers-haven/"><u>In 2024, GigglyGraphics  MemeMaker's Haven</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-expert-director-sound-and-picture-synthesis/"><u>[New] In 2024, Expert Director  Sound & Picture Synthesis</u></a></li>
<li><a href="https://win11.techidaily.com/guarding-against-hidden-threats-in-these-7-windows-processes/"><u>Guarding Against Hidden Threats in These 7 Windows Processes</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-leveraging-obs-establishing-an-efficient-countdown-clock-for-2024/"><u>[Updated] Leveraging OBS  Establishing an Efficient Countdown Clock for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/setting-custom-keys-for-windows-applications/"><u>Setting Custom Keys for Windows Applications</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-transform-your-youtube-venture-from-free-to-earnings-at-the-500-mark/"><u>2024 Approved  Transform Your YouTube Venture  From Free to Earnings at the 500 Mark</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-win11-lineups-finest-videomodding-software/"><u>Discover the Win11 Lineup's Finest Videomodding Software</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-watch-out-these-are-the-8-most-popular-facebook-videos-right-now-for-2024/"><u>[New] Watch Out! These Are the 8 Most Popular Facebook Videos Right Now for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-motorola-moto-g34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Additional Tips About Sinnoh Stone For Motorola Moto G34 5G | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-illustrator-way-adding-realistic-blur-to-your-pics/"><u>In 2024, The Illustrator Way  Adding Realistic Blur to Your Pics</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-dark-knight-versus-shining-savior/"><u>[New] 2024 Approved  Dark Knight Versus Shining Savior</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-ms-store-repairs-overcoming-server-slip-ups-on-windows-os/"><u>Mastering MS Store Repairs: Overcoming Server Slip-Ups on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/prepare-for-airplane-mode-installation-of-win11/"><u>Prepare for Airplane Mode: Installation of Win11</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-solve-the-non-operational-escape-button-on-your-desktop/"><u>Swiftly Solve the Non-Operational Escape Button on Your Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/novices-guide-to-folder-fabrication-in-win11/"><u>Novice's Guide to Folder Fabrication in Win11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-discovering-social-medias-top-5-innovations-in-fb/"><u>In 2024, Discovering Social Media’s Top 5 Innovations in FB</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-microsoft-store-error-solving-in-windows/"><u>Mastery of Microsoft Store Error Solving in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/easy-steps-setup-google-play-store-on-win11/"><u>Easy Steps: Setup Google Play Store on Win11</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-unleash-your-creativity-the-best-mobile-video-editing-software-for-iphone-and-android/"><u>New Unleash Your Creativity The Best Mobile Video Editing Software for iPhone and Android</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-missing-display-after-power-on/"><u>Overcoming Missing Display After Power On</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-gaming-glitches-keeping-df-playtime-uninterrupted/"><u>Navigating Gaming Glitches: Keeping DF Playtime Uninterrupted</u></a></li>
<li><a href="https://extra-hints.techidaily.com/crafting-cinematic-content-with-video-enhance-v22/"><u>Crafting Cinematic Content with Video Enhance V2.2</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-revealing-the-undisclosed-in-instagram-story-observation/"><u>In 2024, Revealing the Undisclosed in Instagram Story Observation</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlock-your-disabled-apple-iphone-se-2022-without-itunes-in-5-ways-drfone-by-drfone-ios/"><u>Unlock Your Disabled Apple iPhone SE (2022) Without iTunes in 5 Ways | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-the-ultimate-guide-to-youtube-screen-recording/"><u>[New] In 2024, The Ultimate Guide to YouTube Screen Recording</u></a></li>
</ul></div>
