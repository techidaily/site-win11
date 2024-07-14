---
title: "Troubleshooting Techniques: Windows Sandbox Lacks Hyprocvisor"
date: 2024-07-13T10:36:50.297Z
updated: 2024-07-14T10:36:50.297Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting Techniques: Windows Sandbox Lacks Hyprocvisor"
excerpt: "This Article Describes Troubleshooting Techniques: Windows Sandbox Lacks Hyprocvisor"
keywords: Windows Sandbox Woes,Hyproc Manager Missing,Sandbox Troubleshoot,Zero-Vulnerability Test,Non-Hyproc Window Sys,Tech Issue Resolution,Vulnerability Free Workspace
thumbnail: https://thmb.techidaily.com/6631d02aad6297e4d6f700e032b5f1a6df7f0a4821dff69d11f95fe1acb0191f.jpg
---

## Troubleshooting Techniques: Windows Sandbox Lacks Hyprocvisor

 Windows Sandbox is a handy utility to test untrusted apps and files in a secure virtual environment. The setup process is pretty straightforward for Windows Sandbox. However, when you try to launch the app, you may encounter the "No Hypervisor was found code 0XC0351000" error.

 The error message indicates that Windows Sandbox was unable to detect Hypervisor. This can happen due to many reasons, including incorrectly configured virtual machine-related features in Windows Features.

 Follow the steps in the article below to troubleshoot this error on your Windows PC.

## 1\. Check and Enable Virtualization Technology in BIOS

![virtualization status windows task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/virtualization-status-windows-task-manager.jpg)

 All the virtualization-based tools need hardware virtualization enabled in BIOS to work. If you haven’t configured your hardware virtualization, check if it is enabled in Task Manager. If not, you can manually enable it in BIOS to support virtualization tools.

To check the virtualization status:

1. Right-click on**Start** and open**Task Manager.**
2. In Task Manager, open the**Performance** tab.
3. Next, make sure the**CPU** tab is selected.
4. Locate the**Virtualization** section. If**Enabled** , skip to the next method.
5. If**Disabled** , follow the steps below to enable hardware virtualization on your computer.

 Now we'll cover how to enable Hardware Virtualization in BISO on an HP computer. The instructions to enable hardware virtualization may vary depending on your computer manufacturer. You can find specific instructions on your computer manufacturer's website, or check out [how to enter the BIOS in Windows 10/11](https://www.makeuseof.com/tag/enter-bios-computer/) .

1. Shut down your PC.
2. Press the**Power** button and then start pressing the**Esc** key to view the**Start menu** .
3. Press**F10** to enter**BIOS Setup.**  
![startup menu bios setup utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/startup-menu-bios-setup-utility.jpg)
4. In the**BIOS Setup Utility,** use the right-left arrow keys to locate and open the**Configuration** tab.
5. Next, use the down-up arrow keys to select**Virtualization Technology** or anything with similar terms.  
![enable hardware virtualization bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enable-hardware-virtualization-bios.jpg)
6. With the option highlighted, press**Enter** and select**Enabled** from the options. Now the Virtualization Technology status will show as**Enabled** .
7. Press**F10** again to save the changes and exit BIOS.

 Wait for your computer to restart. Open Task Manager to see the Virtualization status in the CPU tab. If it says "Enabled," try to open Windows Sandbox to see if it works without the error.

## 2\. Enable Virtual Machine Platform Features

 Windows Sandbox is available as an optional feature that you can install from the Windows Features dialog, and we've covered how to do this in our guide on [how to enable and set up Windows Sandbox in Windows 11](https://www.makeuseof.com/enable-set-up-windows-sandbox-windows-11/) . Similarly, you may need to enable a few additional optional features essential to run the virtualization tool successfully.

 The two optional features you need to enable are**Virtual Machine Platform** and**Windows Hypervisor Platform** . These tools enable platform support for virtual machines and provide the necessary API to run virtualization software on Windows.

To enable virtualization features:

1. Press**Win + I** to open**Settings** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**  
![turn windows features on off windows 11 control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-windows-featureson-off-windows-11-control-panel.jpg)
3. In the left pane, click on**Turn Windows features on or off.**  
![turn on virtual machine platform windows hypervisor platform](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-on-virtual-machine-platform-windows-hypervisor-platform.jpg)
4. In the**Windows Features** dialogue, scroll down and locate**Virtual Machine Platform** and**Windows Hypervisor Platform.**
5. Select both options and click**OK** .
6. Windows will start installing the necessary files. So, wait for the process to complete. Once done, click on**Restart Now** to restart your system and apply the changes.

## 3\. Set Hypervisor to Run at System Startup

 Windows Sandbox may not work if Hypervisor fails to start during system startup. To fix this issue, you can modify your Boot Configuration Data (BCD) file to launch Hypervisor automatically at system startup.

To set Hypervisor to launch at system startup:

1. Press the**Win** key and type**cmd** . Then, right-click on**Command Prompt** and select**Run as administrator.**
2. In the Command Prompt window, type the following command and press Enter:  
`BCDEDIT /Set {current} hypervisorlaunchtype auto`
3. Wait for the success message and restart your PC.
4. After the restart, open Command Prompt as administrator and run the following command:  
`bcdedit`
5. Next, scroll down to the**Hypervisorlaunchtype** entry and make sure it is set to**Auto** .
6. Try to launch Windows Sandbox and check if the No Hypervisor was found error is resolved.

 Note that with the Hypervisor set to launch at startup, virtual machines running on third-party virtualization tools such as VMWare may not work correctly.

 To disable Hypervisor at startup, type the following command in the elevated Command Prompt:

`bcdedit /set hypervisorlaunchtype off`

Once done, restart your computer to apply the changes.

## Get Set With Your Sandbox Again

 While only available on the Pro, Enterprise, and Education editions of the Windows 10 and 11 running systems, Sandbox is an excellent lightweight virtualization solution to test unsafe files and apps on your PC.

 However, if this virtualization option is unavailable, consider using a Windows Sandbox alternative such as Sandboxie-Plus. It is free to use and works on all the editions of Windows OS.


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
<li><a href="https://facebook-clips.techidaily.com/new-perfect-playback-overcoming-mutes-on-linkedin-video-posts-for-2024/"><u>[New] Perfect Playback  Overcoming Mutes on LinkedIn Video Posts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/ditching-taskbar-chatting-in-windows-11-how-will-it-influence-your-experience/"><u>Ditching Taskbar Chatting in Windows 11: How Will It Influence Your Experience?</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-fixing-failed-file-creation-by-camera-app/"><u>Solutions for Fixing Failed File Creation by Camera App</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastering-reddit-posts-a-stepwise-strategy-for-engagement/"><u>2024 Approved  Mastering Reddit Posts  A Stepwise Strategy for Engagement</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-your-computers-msvcr110dll-void/"><u>Remedying Your Computer’s Msvcr110.dll Void</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-color-management-glitches/"><u>Navigating Through Windows' Color Management Glitches</u></a></li>
<li><a href="https://change-location.techidaily.com/here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-xiaomi-redmi-note-12-pro-4g-drfone-by-drfone-virtual-android/"><u>Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Xiaomi Redmi Note 12 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/learn-afrikaans-the-smart-way-mondlys-top-7-advantages-for-you/"><u>Learn Afrikaans the Smart Way: Mondly’s Top 7 Advantages for You</u></a></li>
<li><a href="https://win11.techidaily.com/altering-windows-lockout-duration-post-failed-logon/"><u>Altering Windows Lockout Duration Post-Failed Logon</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-amazon-prime-and-twitter-most-shared-and-liked-shows-23/"><u>[New] 2024 Approved  Amazon Prime and Twitter  Most Shared & Liked Shows, '23</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-mycam-reviewed-does-it-deliver-on-performance-promises-for-2024/"><u>[New] MyCam Reviewed  Does It Deliver on Performance Promises for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-top-7-skype-hacker-to-hack-any-skype-account-on-your-sony-xperia-1-v-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Skype Hacker to Hack Any Skype Account On your Sony Xperia 1 V | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-best-8-linux-apps-for-professional-editing-for-2024/"><u>[Updated] Best 8 Linux Apps for Professional Editing for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-overcoming-windows-1011s-isdonedll-errors/"><u>Deciphering and Overcoming Windows 10/11'S ISDone.dll Errors</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-access-barriers-top-solutions/"><u>Navigating Through Windows Access Barriers: Top Solutions</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-essential-tips-for-adapting-to-facebooks-algorithm-update/"><u>In 2024, Essential Tips for Adapting to Facebook's Algorithm Update</u></a></li>
<li><a href="https://win11.techidaily.com/the-13-step-blueprint-to-reactivating-your-windows/"><u>The 13-Step Blueprint to Reactivating Your Windows</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-adobe-advice-brighten-up-faded-iphone-videos-using-four-critical-techniques/"><u>2024 Approved  [Adobe Advice] Brighten Up Faded iPhone Videos Using Four Critical Techniques</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-twitter-media-upload-instruction-manual/"><u>In 2024, Twitter Media Upload Instruction Manual</u></a></li>
<li><a href="https://win11.techidaily.com/embrace-a-distraction-free-start-with-win-11/"><u>Embrace a Distraction-Free Start with Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-steam-network-access-on-pc-windows/"><u>Unlocking Steam Network Access on PC Windows</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-classic-gaming-journey-add-trophy-features-through-retroarch/"><u>Transform Your Classic Gaming Journey - Add Trophy Features Through Retroarch</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-printer-network-errors-in-windows/"><u>Steps to Resolve Printer Network Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-device-recognition-failure-in-windows-installation/"><u>Overcoming Device Recognition Failure in Windows Installation</u></a></li>
<li><a href="https://win11.techidaily.com/fast-setupuninstall-bings-ai-on-win-11-taskbar/"><u>Fast Setup/Uninstall: Bing's AI on Win 11 Taskbar</u></a></li>
<li><a href="https://extra-information.techidaily.com/all-encompassing-review-the-hero4-black-guide/"><u>All-Encompassing Review  The Hero4 Black Guide</u></a></li>
<li><a href="https://win11.techidaily.com/top-windows-compatible-nds-emulators/"><u>Top Windows Compatible NDS Emulators</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-the-role-of-windows-cab-files-in-system-setup/"><u>Dissecting the Role of Windows CAB Files in System Setup</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-to-optimal-windows-11-search-performance/"><u>Navigating to Optimal Window's 11 Search Performance</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-everlasting-file-elimination-on-your-desktop-bin-with-windows-11/"><u>Simplifying Everlasting File Elimination on Your Desktop Bin with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-user-interface-incorrante-windows-with-portables/"><u>Augmenting User Interface: Incorrante Windows with Portables</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-video-content-battle-who-wins-with-vimeo-youtube-or-dailymotion/"><u>[New] Video Content Battle  Who Wins with Vimeo, YouTube, or DailyMotion?</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-dive-deep-into-the-world-of-tiktok-emojis-discover-7-favorites-and-hidden-messages/"><u>[New] In 2024, Dive Deep Into the World of TikTok Emojis - Discover #7 Favorites and Hidden Messages</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-realme-c55-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Realme C55</u></a></li>
<li><a href="https://win11.techidaily.com/the-invisible-handshake-direct-pc-links-in-windows-11-rdp/"><u>The Invisible Handshake: Direct PC Links in Windows 11 RDP</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-error-windows-security-cut-by-admin-policies/"><u>Deciphering Error: Windows Security Cut by Admin Policies</u></a></li>
<li><a href="https://win11.techidaily.com/smoothly-switching-programs-for-your-first-win-11-experience/"><u>Smoothly Switching Programs for Your First Win 11 Experience</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-saving-instagram-songs-a-beginners-guide/"><u>New In 2024, Saving Instagram Songs A Beginners Guide</u></a></li>
<li><a href="https://win11.techidaily.com/essential-advice-to-supercharge-your-wsl-2-and-docker-use/"><u>Essential Advice to Supercharge Your WSL 2 and Docker Use</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-dedicated-ram-win-11-edition-guide/"><u>Augmenting Dedicated RAM: Win 11 Edition Guide</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-thumbnail-wizardry-top-8-tools-to-boost-view-counts/"><u>[New] Thumbnail Wizardry  Top 8 Tools to Boost View Counts</u></a></li>
<li><a href="https://win11.techidaily.com/increase-visible-pins-on-windows-11-desktop-ui/"><u>Increase Visible Pins on Windows 11 Desktop UI</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-making-spherical-videos-the-iphone-way/"><u>[New] Making Spherical Videos  The iPhone Way</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-discord-gifs-made-simple-a-step-by-step-reference-guide/"><u>[Updated] 2024 Approved  Discord Gifs Made Simple  A Step-by-Step Reference Guide</u></a></li>
<li><a href="https://win11.techidaily.com/zero-entry-login-remote-desktop-innovations-on-win-11/"><u>Zero-Entry Login: Remote Desktop Innovations on Win 11</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-oneplus-ace-2v-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on OnePlus Ace 2V | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-ccleaner-in-win11/"><u>Troubleshooting Non-Functional CCleaner in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-process-how-to-setup-google-maps-on-pc/"><u>A Step-by-Step Process: How to Setup Google Maps on PC</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-comprehensive-srt-handbook-for-enthusiasts/"><u>In 2024, The Comprehensive SRT Handbook for Enthusiasts</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-sony-xperia-1-v-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Sony Xperia 1 V is off? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/deletion-risks-for-windows-bt-folder-expert-advice/"><u>Deletion Risks for Windows ~BT Folder: Expert Advice</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-windows-experience-filter-key-settings/"><u>Customize Your Windows Experience: Filter Key Settings</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-ultimate-converters-handbook-from-srt-to-multiple-formats/"><u>[New] Ultimate Converter's Handbook  From SRT to Multiple Formats</u></a></li>
<li><a href="https://some-skills.techidaily.com/unlock-creative-potential-smart-b-roll-incorporation-for-2024/"><u>Unlock Creative Potential  Smart B Roll Incorporation for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/employing-rufus-to-navigate-windows-11s-security-barriers/"><u>Employing Rufus to Navigate Windows 11'S Security Barriers</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-the-username-switch-on-windows-11/"><u>Streamlining the UserName Switch on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-turn-off-overlay-effects-in-nvidia-graphics/"><u>How to Turn Off Overlay Effects in NVIDIA Graphics</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/live-methods-for-quieter-track-output-for-2024/"><u>Live Methods for Quieter Track Output for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-xiaomi-redmi-13c-to-mac-drfone-by-drfone-android/"><u>How to Mirror Xiaomi Redmi 13C to Mac? | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-androids-ultimate-guide-to-best-wildlife-games/"><u>In 2024, Android's Ultimate Guide to Best Wildlife Games</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-accessing-win-11s-call-center/"><u>Quick Guide: Accessing Win 11'S Call Center</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-elevate-earnings-through-effective-facebook-page-practices-for-2024/"><u>[New] Elevate Earnings Through Effective Facebook Page Practices for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-simplified-tutorial-mastering-meets-background-blur/"><u>[Updated] Simplified Tutorial  Mastering Meet's Background Blur</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-adding-gmaps-in-windows-os/"><u>The Ultimate Guide to Adding GMaps in Windows OS</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-discover-the-best-5-devices-to-stream-and-record-sessions/"><u>[New] Discover the Best 5 Devices to Stream & Record Sessions</u></a></li>
<li><a href="https://win11.techidaily.com/winmc-lan-connectivity-woes-solutions-explored/"><u>WinMC LAN Connectivity Woes: Solutions Explored</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-restore-missing-desktop-icons-on-windows-11/"><u>8 Ways to Restore Missing Desktop Icons on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-window-preview-failures-in-win-810/"><u>Addressing Window Preview Failures in Win 8/10</u></a></li>
</ul></div>
