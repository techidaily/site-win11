---
title: Adjusting Quick Access for File Explorer Through OneDrive
date: 2024-07-13T11:19:00.307Z
updated: 2024-07-14T11:19:00.307Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Quick Access for File Explorer Through OneDrive
excerpt: This Article Describes Adjusting Quick Access for File Explorer Through OneDrive
keywords: Quick File Explorer Adjust,OneDrive Access Improve,Enhance Explorer Settings,Streamline OneDrive Views,Optimize Office Explorer,Direct OneDrive Access,Refine File Explorer Options
thumbnail: https://thmb.techidaily.com/805432a26a63c24a3ad7f94c306f1a1291a2364beb1c1710fc99d1f9d71ae26e.jpg
---

## Adjusting Quick Access for File Explorer Through OneDrive

 When you launch Windows File Explorer, it automatically takes you to the "Quick Access" view. This page displays shortcuts to recently accessed folders and files and lists your favorite folders. It might be convenient for some users but not for others who prefer easy access to their cloud storage.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.

## 1\. Use the Folder Options

 If you want to make OneDrive the starting point of your File Explorer, you can do so using folder options. Here's how to do it:

1. Open the Start menu and type **File Explorer** in the search box. When the File Explorer icon appears, click it to launch the app. You can also use **Win + E** to open the program quickly.
2. In the File Explorer window, look for **See more** (three dots) at the top. Clicking on it opens the Folder Options dialog box.  
![Open Folder Options in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-folder-options-in-file-explorer.jpg)
3. On the General tab, click the **Open File Explorer to** drop-down menu and select "Username Personal". Here, "Username" refers to your Windows account name.  
![Open File Explorer to OneDrive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive.jpg)
4. Click **Apply** \> **OK** to close the dialog box.

 From now on, opening File Explorer will automatically launch OneDrive rather than Quick Access.

## 2\. Using the Registry Editor

 You can also use the Registry Editor to set OneDrive as your default File Explorer view. But be warned: if you make an incorrect change to the system registry, you could damage your computer. We recommend [backing up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it.

 Once backed up, follow these steps to make OneDrive the default view:

1. [Open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the text box and hit **Enter**.
3. If you're prompted for permission, select **Yes** to continue. The Registry Editor window will open.
4. In the Registry Editor window, navigate to this path:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
5. In the right pane, locate and double-click the **LaunchTo** entry. If the entry isn't present, you'll need to create it. For that, right-click on the **Advanced** folder and select **New > DWORD (32-bit) Value**. Name the value "LaunchTo" and press Enter. Doing so will create a new DWORD in the registry.  
![Set File Explorer to Open OneDrive Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/set-file-explorer-to-open-onedrive-using-registry.jpg)
6. Double-click on this newly created value and set its value to **4**.
7. Click **OK** and close the registry window.

 After that, restart your computer for the changes to take effect. Once your PC restarts, launch File Explorer. With this method, you will launch File Explorer directly to your cloud storage without navigating through Quick Access.

## 3\. Using a Reg File

 The third and final method to set OneDrive as the default view involves using a reg file. It contains the necessary instructions that modify the registry on your behalf. So, if you're not comfortable using the registry editor, this is the right way to go.

 To create the reg file, follow these steps:

1. Right-click on your desktop and select **New > Text Document**.
2. Name the file **OneDrive.reg** and hit **Enter**.
3. Now open the file in a text editor such as Notepad.
4. Copy and paste the following code into the text document:  
`<code>Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced]  
"LaunchTo"=dword:00000004`
5. After pasting the given code, click **File** \> **Save as**.
6. In the Save as dialog box, select **All files** from the Save as type drop-down menu and hit Enter. Make sure the file is saved as a **.reg** file and not as a .txt file.  
![Open File Explorer to OneDrive Using REG File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/open-file-explorer-to-onedrive-using-reg-file.jpg)
7. Double-click the REG file you just created. If you're prompted for permission to change your computer, click **Yes**.
8. Finally, restart your computer for the changes to take effect.

 After your system restarts, launch File Explorer. You'll see OneDrive as the main view instead of Quick Access.

## Set File Explorer to Open OneDrive Instead of Quick Access

 There you have it; three different methods to make OneDrive your default File Explorer view. If you like, you can also change other folder views, such as Downloads or This PC, using the same techniques we discussed above. I hope this guide helped you get things done quickly and easily.

 Read this comprehensive guide if you want File Explorer to open OneDrive instead of Quick Access.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://easy-unlock-android.techidaily.com/top-4-sim-location-trackers-to-easily-find-your-lost-realme-gt-5-pro-device-by-drfone-android/"><u>Top 4 SIM Location Trackers To Easily Find Your Lost Realme GT 5 Pro Device</u></a></li>
<li><a href="https://win11.techidaily.com/win11-control-panel-lost-find-unlisted-system-configurations/"><u>Win11 Control Panel Lost, Find Unlisted System Configurations</u></a></li>
<li><a href="https://android-frp.techidaily.com/top-5-realme-c33-2023-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Realme C33 2023 Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-poco-c50-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Poco C50 Phone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/broadcast-brilliance-with-cost-effective-templates/"><u>Broadcast Brilliance with Cost-Effective Templates</u></a></li>
<li><a href="https://win11.techidaily.com/windows-guide-converting-mp3s-to-audio-cds-using-imgburn/"><u>Windows Guide: Converting MP3s to Audio CDs Using ImgBurn</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-essential-tech-skills-record-on-hangouts/"><u>[New] In 2024, Essential Tech Skills  Record on Hangouts</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-ultimate-explanation-of-youtube-keyword-optimization-for-2024/"><u>The Ultimate Explanation of YouTube Keyword Optimization for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-lensblend-elite-cohesive-image-composer/"><u>2024 Approved  LensBlend Elite  Cohesive Image Composer</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-getting-past-windows-update-hitches/"><u>Quick Fixes: Getting Past Windows Update Hitches</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-mastering-the-height-final-cut-pro-x-techniques-for-instagram-video-for-2024/"><u>[Updated] Mastering the Height  Final Cut Pro X Techniques for Instagram Video for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/protecting-the-default-windows-clock-configuration/"><u>Protecting the Default Windows Clock Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-way-to-windows-11-group-policies/"><u>Streamline Your Way to Windows 11 Group Policies</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-2024-approved-guide-of-8-photo-collage-apps-for-pc/"><u>Updated 2024 Approved Guide of 8 Photo Collage Apps for PC</u></a></li>
<li><a href="https://win11.techidaily.com/remedial-actions-for-incorrect-app-configuration/"><u>Remedial Actions for Incorrect App Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-robot-generated-passwords-for-win-11-access/"><u>Bypassing Robot-Generated Passwords for Win 11 Access</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-unidentified-component-in-windows-lsass/"><u>Quick Fixes for Unidentified Component in Windows Lsass</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-cutting-edge-videography-bordering-techniques-for-ig/"><u>In 2024, Cutting-Edge Videography  Bordering Techniques for IG</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-proven-methods-for-twitter-brand-awareness/"><u>[Updated] In 2024, Proven Methods for Twitter Brand Awareness</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-address-app-support-issues-on-newer-windows/"><u>Techniques to Address App Support Issues on Newer Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/rapid-ways-to-construct-a-mac-based-image-mosaic/"><u>Rapid Ways to Construct a Mac-Based Image Mosaic</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-campaign-tactics-for-enhancing-health-awareness/"><u>In 2024, Campaign Tactics for Enhancing Health Awareness</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-securing-your-snapshots-premium-and-budget-friendly-cloud-options/"><u>2024 Approved  Securing Your Snapshots  Premium and Budget-Friendly Cloud Options</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-effortless-capture-of-webcast-radios-your-practical-guide-for-2024/"><u>[New] Effortless Capture of Webcast Radios  Your Practical Guide for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guide-to-overcoming-silent-hp-network-printers/"><u>Guide to Overcoming Silent HP Network Printers</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-blue-screen-error/"><u>Strategies for Overcoming Blue Screen Error</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-top-free-ad-free-tools-for-android-screen-recording-for-2024/"><u>[Updated] Top Free, Ad-Free Tools for Android Screen Recording for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-pathway-to-using-windows-11-toolbars-effectively/"><u>The Pathway to Using Window's 11 Toolbars Effectively</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-iphone-techniques-for-video-opposite-playback/"><u>[New] IPhone Techniques for Video Opposite Playback</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-how-to-recover-lost-x-configuration/"><u>Unraveling the Mystery: How to Recover Lost X Configuration</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-discover-the-top-hand-drawing-whiteboard-animation-creators/"><u>Updated 2024 Approved Discover the Top Hand Drawing Whiteboard Animation Creators</u></a></li>
<li><a href="https://win11.techidaily.com/best-vm-options-compatible-with-windows-11-pcs/"><u>Best VM Options Compatible With Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-9-methods-for-altering-windows-sound-settings/"><u>Unlock 9 Methods for Altering Windows Sound Settings</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/insta-twist-techniques-for-turning-photos-into-viral-sensations-on-social-media-for-2024/"><u>Insta-Twist Techniques for Turning Photos Into Viral Sensations on Social Media for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/reactivate-windows-file-explorer-efficiently/"><u>Reactivate Windows File Explorer Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/refreshing-gpu-functionality-in-windows-10-and-11-easy-fixes/"><u>Refreshing GPU Functionality in Windows 10 & 11 Easy Fixes</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-vivo-t2x-5g-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Vivo T2x 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-quick-and-easy-conducting-instagram-stories-polls-today/"><u>In 2024, Quick & Easy  Conducting Instagram Stories Polls Today</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-is-it-that-easy-to-make-my-own-animated-character-in-2024/"><u>Updated Is It That Easy to Make My Own Animated Character, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/altering-network-addresses-on-win11/"><u>Altering Network Addresses on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-the-power-of-java-sdk-on-windows-11/"><u>Unleashing the Power of Java SDK on Windows 11</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-6-methods-for-switching-from-apple-iphone-x-to-samsung-drfone-by-drfone-transfer-from-ios/"><u>In 2024, 6 Methods for Switching from Apple iPhone X to Samsung | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/choco-vs-wslm-optimal-windows-software-downloader/"><u>Choco vs WSLM: Optimal Windows Software Downloader</u></a></li>
<li><a href="https://win11.techidaily.com/powerful-tactics-for-using-windows-explorer-not-ls/"><u>Powerful Tactics for Using Windows Explorer, Not LS</u></a></li>
<li><a href="https://win11.techidaily.com/top-12-redundant-windows-extras-for-removal/"><u>Top 12 Redundant Windows Extras for Removal</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-fixing-broken-internet-connections-6-strategies-for-windows-users/"><u>The Art of Fixing Broken Internet Connections - 6 Strategies for Windows Users</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-discover-the-best-glitch-video-editors-for-windows-mac-and-online-use-for-2024/"><u>Updated Discover the Best Glitch Video Editors for Windows, Mac, and Online Use for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/swift-keyboard-mastery-with-typingaid/"><u>Swift Keyboard Mastery with TypingAid</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-mastery-through-snips-unveiling-macs-top-5-tools/"><u>In 2024, Mastery Through Snips  Unveiling Mac's Top 5 Tools</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-windows-11s-security-six-pathways-for-safe-mode/"><u>Accessing Windows 11'S Security: Six Pathways for Safe Mode</u></a></li>
<li><a href="https://win11.techidaily.com/boost-pc-inquiry-speed-using-everythingapp/"><u>Boost PC Inquiry Speed Using EverythingApp</u></a></li>
<li><a href="https://win11.techidaily.com/regain-access-to-microsoft-store-features-on-pcs/"><u>Regain Access to Microsoft Store Features on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-reactivating-a-greyed-out-secure-boot-in-bios/"><u>Steps for Reactivating a Greyed Out Secure Boot in BIOS</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unlocking-the-secrets-of-turning-online-videos-into-desktop-music-files/"><u>2024 Approved  Unlocking the Secrets of Turning Online Videos Into Desktop Music Files</u></a></li>
<li><a href="https://extra-tips.techidaily.com/how-to-optimize-your-telegram-web-experience/"><u>How to Optimize Your Telegram Web Experience</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-voice-alteration-devices-explained-features-insights-and-alternatives/"><u>In 2024, Voice Alteration Devices Explained Features, Insights, and Alternatives</u></a></li>
<li><a href="https://win11.techidaily.com/reducing-cpuram-drain-from-consuming-video-content/"><u>Reducing CPU/RAM Drain From Consuming Video Content</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-peering-into-pixels-with-polaroids-camplus-action-device/"><u>2024 Approved  Peering Into Pixels with Polaroid's Cam+ Action Device</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steps-for-hardware-alerts-in-windows/"><u>Troubleshooting Steps for Hardware Alerts in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/taming-the-chaos-of-mbr-errors-with-data-interpretation/"><u>Taming the Chaos of MBR Errors with Data Interpretation</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-disabled-windows-firewall-4-methods-explored/"><u>Bypassing Disabled Windows Firewall: 4 Methods Explored</u></a></li>
<li><a href="https://win11.techidaily.com/reduce-delay-in-windows-11-keys-7-proven-methods/"><u>Reduce Delay in Windows 11 Keys: 7 Proven Methods</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-compilation-of-websites-offering-ridiculous-sounds/"><u>2024 Approved Compilation of Websites Offering Ridiculous Sounds</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-mastering-facebook-broadcasts-via-pc-and-mac-with-obs/"><u>[New] Mastering Facebook Broadcasts via PC & Mac with OBS</u></a></li>
</ul></div>
