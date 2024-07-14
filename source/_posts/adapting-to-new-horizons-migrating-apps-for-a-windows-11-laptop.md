---
title: "Adapting to New Horizons: Migrating Apps for a Windows 11 Laptop"
date: 2024-07-13T11:20:24.880Z
updated: 2024-07-14T11:20:24.880Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Adapting to New Horizons: Migrating Apps for a Windows 11 Laptop"
excerpt: "This Article Describes Adapting to New Horizons: Migrating Apps for a Windows 11 Laptop"
keywords: Windows 11 Migration,Laptop App Updates,App Compatibility Windows,New OS App Adoption,Transitioning Apps,Modernize Apps Windows,Software Migrate Windows11
thumbnail: https://thmb.techidaily.com/2d978f83661066646581916767cce9455414cb9d5d96eedafaf817e164937e77.jpg
---

## Adapting to New Horizons: Migrating Apps for a Windows 11 Laptop

 Setting up Windows 11 on your PC, or another PC is a laborious task. After installing the operating system and the OEM drivers, there is still a lot of work left. You need to reconfigure your system settings, re-download, and install all the Microsoft Store apps. Along with that, you need to individually download and install each third-party software, which makes it more challenging.

 But what if you could eliminate the hours spent in finding and installing every single app, and configuring every setting? We will discuss two methods to effortlessly migrate most of your old apps to your new PC.

## 1\. Using Microsoft Account

 If you used a Microsoft account on your old PC, Windows 11 offers multiple options to back up your App list, Preferences, and use OneDrive for personal files. To do that, you must enable [OneDrive](https://www.makeuseof.com/what-is-onedrive/) and back up all your personal files and folders to it. It will only take care of the files part but the apps and preferences are still left. But you must also enable the backup of these two things on your old PC before [reinstalling Windows 11](https://www.makeuseof.com/windows-11-reinstall-without-deleting-apps/) or migrating to a new PC.

 Repeat the following steps to enable apps and settings backup:

1. Press **Win + I** to launch the Settings app. Navigate to **Accounts > Windows backup** section.
2. Go to the **Remember my apps** option and click on the toggle next to it to enable the settings.
3. Next, click on the toggle next to **Remember my preferences** option to back up your settings as well.  
![Backup Apps and Preferences to Microsoft Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/backup-apps-and-preferences-to-microsoft-account.jpg)
4. You will notice that the top section of the Windows backup page will mark each of these features as “**backed up**”.

 After you reinstall Windows 11, the OOBE page will ask you to [sign in with a Microsoft account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/). Enter your credentials, and you will see a “Welcome back, User!” message with an option to restore all apps, settings, and files present on your previous machine. Click on the **Next** button and proceed setup up your new PC

![Install Old Apps Using Microsoft Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-old-apps-using-microsoft-account.jpg)

 As soon as you boot to the desktop, you will see a popup that Windows is trying to restore the most used apps from before. It will ask you to open Microsoft Store to restore additional apps from your old PC. Click on the **Restore my apps** button.

![Install Old Apps Using Microsoft Account 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-old-apps-using-microsoft-account-2.jpg)

 Microsoft Store will display all the remaining apps available for restoration. Click on the **Restore All** button if you want to bring back every app. Wait for the apps to install and then close Microsoft Store.

![Install Old Apps Using Microsoft Account 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-old-apps-using-microsoft-account-3.jpg)

## 2\. Using a Winget JSON File

 The first method of using Microsoft Account has its limitations. It only includes Windows apps and settings but leaves many other third-party apps that you installed from the Winget repository or from the web. So you can use Winget to export the app list into a JSON file and then import it to your new Windows 11 PC. You must execute this method after Windows 11 brings back all the settings and Microsoft apps, and you boot to the desktop.

 Repeat the following steps to import a Winget JSON file:

1. Download or copy the Winget export file on your system.
2. Press **Win + R** to open the **Run dialog box**. Type **cmd** and press **Ctrl + Shift + Enter** to [open Command Prompt with administrator privileges](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/).
3. Now, use the **winget import -i** command to import the JSON file. Type the following command and press the **Enter** key:  
`winget import -i C:\apps.json --accept-source-agreements --accept-package-agreements`
4. Replace the folder location and name with the storage location and name of the winget export file on your system.  
![Import Apps Using Winget in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/import-apps-using-winget-in-windows-11.jpg)
5. Patiently wait while winget downloads and installs all the packages in the JSON file one by one. Then, close the Command Prompt window.

## What About Any Left Out Apps?

 Even after using both methods, some apps will still be left out. It is because Microsoft Account sign-in only brings back Windows settings and Microsoft Store apps. The winget export file can restore only the apps listed in its official repository.

 As such, you still need to download the programs that aren’t included in both of these methods. But it will be a very short list compared to the effort you would have to put in if you just performed a normal installation.

## Save Time When Setting Up Windows 11

 Make sure to enable files, apps, and preferences backup on your PC and create a winget export file beforehand. After you have both these backups in place, you can begin reinstalling Windows 11 on a different PC or reinstalling on the same PC.

 But what if you could eliminate the hours spent in finding and installing every single app, and configuring every setting? We will discuss two methods to effortlessly migrate most of your old apps to your new PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-approaches.techidaily.com/in-2024-streamline-your-multi-tasking-pip-settings-in-safari/"><u>In 2024, Streamline Your Multi-Tasking  PIP Settings in Safari</u></a></li>
<li><a href="https://win11.techidaily.com/taskbar-transformation-through-38-years/"><u>Taskbar Transformation Through 38 Years</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-the-best-free-online-movie-making-software/"><u>New 2024 Approved The Best Free Online Movie Making Software</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-joining-live-shows-a-tiktok-perspective/"><u>[New] Joining Live Shows  A TikTok Perspective</u></a></li>
<li><a href="https://win11.techidaily.com/close-all-easy-as-1-2-3-windows-multi-app-command/"><u>Close All, Easy as 1-2-3: Windows Multi-App Command</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-activating-newly-redesigned-widget-tool/"><u>Step-by-Step Guide: Activating Newly Redesigned Widget Tool</u></a></li>
<li><a href="https://win11.techidaily.com/self-contained-strategies-for-hardware-duplication/"><u>Self-Contained Strategies for Hardware Duplication</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-samsung-galaxy-a25-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Methods to Change GPS Location On Samsung Galaxy A25 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-strategies-to-overcome-access-barriers-on-win-pcs/"><u>Top 8 Strategies to Overcome Access Barriers on Win PCs</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-the-empty-directory-faux-pas-in-windows-a-guide-to-error-x80070091/"><u>Demystifying the 'Empty Directory' Faux Pas in Windows - A Guide to Error X80070091</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-battle-for-best-action-camera-sony-fdr-x1000v-meets-hero-4-black/"><u>[Updated] Battle for Best Action Camera  Sony FDR-X1000V Meets Hero 4 Black</u></a></li>
<li><a href="https://win11.techidaily.com/demonstrating-the-power-of-powershell-removing-restrictions-on-windows/"><u>Demonstrating the Power of PowerShell: Removing Restrictions on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-eliminating-wsl-from-win-11-pcs/"><u>Comprehensive Guide: Eliminating WSL From Win 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/windows-save-location-glitch-quick-guide/"><u>Windows Save Location Glitch: Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steam-backup-mishaps/"><u>Troubleshooting Steam Backup Mishaps</u></a></li>
<li><a href="https://win11.techidaily.com/7-personal-touches-for-windows-11s-search-engine/"><u>7 Personal Touches for Windows 11'S Search Engine</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-your-desktop-opt-for-smart-window-arrangement/"><u>Revolutionize Your Desktop: Opt for Smart Window Arrangement</u></a></li>
<li><a href="https://extra-skills.techidaily.com/premier-thumbnail-packs-free-pubg-montages-for-2024/"><u>Premier Thumbnail Packs  Free PUBG Montages for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-ensure-audible-feedback-in-screen-captures/"><u>Techniques to Ensure Audible Feedback in Screen Captures</u></a></li>
<li><a href="https://extra-tips.techidaily.com/masterful-mashups-our-picks-for-10-premium-audio-amplifiers/"><u>Masterful Mashups  Our Picks for 10 Premium Audio Amplifiers</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-ultimate-guide-to-lgs-advanced-4k-visual-display/"><u>[New] The Ultimate Guide to LG’s Advanced 4K Visual Display</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-recognize-non-appearing-hdd/"><u>Strategies to Recognize Non-Appearing HDD</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-navigating-blank-login-page-fixes/"><u>Windows 11: Navigating Blank Login Page Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-windows-experience-7-fixes-for-broken-apps/"><u>Seamless Windows Experience: 7 Fixes for Broken Apps</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-responsive-touchpad-gestures-on-windows/"><u>Troubleshooting Non-Responsive Touchpad Gestures on Windows</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-dissecting-the-digital-language-meanings-of-fb-messengers-blue-emoji/"><u>[Updated] 2024 Approved  Dissecting the Digital Language  Meanings of FB Messenger’s Blue Emoji</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-steam-performance-overcoming-degraded-download-rates/"><u>Skyrocket Steam Performance: Overcoming Degraded Download Rates</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-best-free-online-video-editors-for-movie-creation/"><u>Updated In 2024, Best Free Online Video Editors for Movie Creation</u></a></li>
<li><a href="https://win11.techidaily.com/top-4-techniques-for-mac-address-discovery-in-windows-11/"><u>Top 4 Techniques for Mac Address Discovery in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/craft-your-own-secure-windows-pin-with-custom-patterns/"><u>Craft Your Own Secure Windows PIN with Custom Patterns</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/skyrocket-views-unique-tiktok-bio-formats-to-triple-your-followers-on-filmora/"><u>Skyrocket Views  Unique TikTok Bio Formats to Triple Your Followers on Filmora</u></a></li>
<li><a href="https://win11.techidaily.com/windows-warnings-identifying-critical-processes-for-malware-detection/"><u>Windows Warnings: Identifying Critical Processes for Malware Detection</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-stalled-email-notifications-in-windows-environment/"><u>Reviving Stalled Email Notifications in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-windows-odbc-configuration-basics/"><u>Delving Into Windows ODBC Configuration Basics</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-boot-on-windows-sound-service-reboot-needs/"><u>Troubleshooting Boot-On Windows Sound Service Reboot Needs</u></a></li>
<li><a href="https://win11.techidaily.com/silent-restarts-a-windows-1011-guide-to-going-dark/"><u>Silent Restarts: A Windows 10/11 Guide to Going Dark</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-add-logo-or-watermark-to-youtube-video-for-2024/"><u>[New] How to Add Logo or Watermark to YouTube Video for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/turbo-windows-11-app-opening-secrets-revealed/"><u>Turbo Windows 11 App Opening Secrets Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-a-productive-win-11-taskbar/"><u>The Ultimate Guide to a Productive Win 11 Taskbar</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-revolutionize-your-snaps-with-innovative-boomerang-tactics/"><u>[New] 2024 Approved  Revolutionize Your Snaps with Innovative Boomerang Tactics</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-androids-heartfelt-3ds-gaming-alternatives-for-2024/"><u>[New] Android's Heartfelt 3DS Gaming Alternatives for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tips-simply-recognize-your-computers-ram-type/"><u>Tech Tips: Simply Recognize Your Computer's RAM Type</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-disabling-of-windows-11-alerts/"><u>Speedy Disabling of Windows 11 Alerts</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-soundtracking-whatsapp-statues/"><u>[New] Soundtracking WhatsApp Statues</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-mastering-video-success-on-facebook-platforms-for-2024/"><u>[New] Mastering Video Success on Facebook Platforms for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-way-to-relaunch-printer-service/"><u>Efficient Way to Relaunch Printer Service</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-controlling-windows-key-status/"><u>Understanding and Controlling Windows Key Status</u></a></li>
<li><a href="https://win11.techidaily.com/cant-find-copilot-on-windows-11-heres-what-to-do/"><u>Can't Find Copilot on Windows 11? Here's What To Do</u></a></li>
<li><a href="https://win11.techidaily.com/bios-tips-combatting-the-problem-of-grayed-out-secure-boot-on-windows/"><u>BIOS Tips: Combatting the Problem of Grayed-Out Secure Boot on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-guide-to-windows-11-customization-techniques/"><u>A Detailed Guide to Windows 11 Customization Techniques</u></a></li>
</ul></div>
