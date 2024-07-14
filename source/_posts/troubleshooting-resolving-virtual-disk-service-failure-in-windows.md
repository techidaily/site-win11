---
title: "Troubleshooting: Resolving Virtual Disk Service Failure in Windows"
date: 2024-07-13T10:47:56.641Z
updated: 2024-07-14T10:47:56.641Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting: Resolving Virtual Disk Service Failure in Windows"
excerpt: "This Article Describes Troubleshooting: Resolving Virtual Disk Service Failure in Windows"
keywords: Fix Virtual Disk Errors,DBTSVDISK Win Trouble,Bypass VDisk Service Fails,Resolve DV-Service Crashes,Stop Windows VDisk Failures,Correcting VDisk Services,Overcome VDisk Windows Errors
thumbnail: https://thmb.techidaily.com/b7fdec82e5e2a50f89b07a18bb64e205705f93d7819f0fe370579d848f9daaea.jpg
---

## Troubleshooting: Resolving Virtual Disk Service Failure in Windows

 Disk Management is a Windows utility with which users can partition and rename drives. However, some users have reported this Windows error message pops up when they try to access Disk Management: “Disk Management could not start Virtual Disk Service (VDS).” A variation of that error message also says, “Unable to connect to Virtual Disk Service.”

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

## 1\. Disconnect External Drives From Your PC

 First, try disconnecting all non-essential USB devices from your PC. Make sure there aren’t any external drives, USB sticks, mobile phones, or card readers connected to your PC. Then try [opening the Disk Management utility](https://www.makeuseof.com/ways-open-disk-management-windows-10/) again.

## 2\. Run System File and Image Repair Scans

 System file corruption could feasibly cause the Disk Management Virtual Disk Service error. So, check the integrity of system files on your PC with the Windows System File Checker command-line tool. That utility will also usually repair corrupted system files detected. This [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide includes instructions for utilizing that tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command.jpg)

 If SFC detects corrupted system files but can’t repair them, you may need to run a Deployment Image Service Management scan. That’s a tool for fixing issues with the Windows system image. You can run that utility by executing this Deployment Image command within the Command Prompt:

`DISM /Online /Cleanup-Image /RestoreHealth`

## 3\. Enable and Run the Virtual Disk Service

 A disabled Virtual Disk service is a common cause of the Disk Management VDS error. Disk Management can’t connect to VDS when the Virtual Disk service is disabled. So, try enabling and running the Virtual Disk service like this:

1. To access Run, press **Win + R**.
2. Enter **services.msc** inside the Run command dialog and press **Return**.
3. Scroll down and double-click on **Virtual Disk** within the Services window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/services-window.jpg)
4. Select the **Automatic** setting on the **Startup type** menu.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-type-drop-down-menu.jpg)
5. Press **Start** within the Virtual Disk Properties window.

1. Select the window’s **Log on** tab.
2. Next, click the **Allow service to interact with desktop** checkbox to select that option.  
![The Log On tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/log-on-tab.jpg)
3. Click **Apply** to save your new Virtual Disk service settings.
4. Select the Virtual Disk Properties window’s **OK** option.
5. If you encounter the Disk Management VDS error within a remote connection environment, repeat the above steps to check the Virtual Disk service is enabled on both the local and remote PCs.

## 4\. Allow Remote Volume Management Through Windows Defender Firewall

 Windows Defender Firewall can cause the Disk Management VDS error by blocking that utility from connecting with Virtual Disk. So, make sure Remote Volume Management is allowed through that firewall on both local and remote PCs. Our [guide to allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) includes instructions for applying this resolution.

![The allowed apps firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/firewall-options.jpg)

## 5\. Turn Off Third-Party Security Software

 If your PC includes a third-party security (antivirus) app, that software could be blocking Disk Management from establishing a VDS connection. Remember that many third-party security apps also incorporate firewalls along with antivirus components. So, try temporarily disabling both the firewall and antivirus module within your third-party security software.

 To disable the firewall part, look for a turn-off firewall option within the settings tab of your antivirus software. You can usually turn off antivirus shields by right-clicking on security apps’ system tray icons and selecting disable options on their context menus. Select to turn off the antivirus shield for about an hour if you can, and try accessing Disk Management again to see if the issue persists.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

## Manage Your Drives With Disk Management Again

 The potential solutions in this guide aren’t totally guaranteed, but they’re the most likely ways to fix the Disk Management VDS error on a Windows PC. So, maybe one will get the Disk Management VDS issue sorted on your PC. Then you can manage and partition your drives with Disk Management again.

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/unveiling-top-windows-11-fps-monitors-and-counter-tools/"><u>Unveiling Top Windows 11 FPS Monitors & Counter Tools</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-and-fixing-absence-of-hypervisor-on-windows-sandbox/"><u>Identifying and Fixing Absence of Hypervisor on Windows Sandbox</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-pcs-wi-fi-woes-six-effective-steps-from-fixing-adapter-failure/"><u>Reviving Your PC's Wi-Fi Woes - Six Effective Steps From Fixing Adapter Failure</u></a></li>
<li><a href="https://win11.techidaily.com/unwrapping-and-solving-isdonedll-failures-in-w10w11-oses/"><u>Unwrapping and Solving ISDone.dll Failures in W10/W11 OSes</u></a></li>
<li><a href="https://win11.techidaily.com/1719350994094-winshift-stuck-heres-how-to-tackle-it/"><u>WinShift Stuck? Here's How to Tackle It</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-unveiling-the-secrets-of-striking-highlight-image-creation/"><u>[New] 2024 Approved  Unveiling the Secrets of Striking Highlight Image Creation</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-maze-quickly-entering-windows-support-space/"><u>Avoiding the Maze: Quickly Entering Windows' Support Space</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-blocked-experience-in-roblox-addressing-account-restrictions/"><u>Fixing Blocked Experience in Roblox: Addressing Account Restrictions</u></a></li>
<li><a href="https://win11.techidaily.com/stabilizing-win-os-cease-df-glitching-issues/"><u>Stabilizing Win OS: Cease DF Glitching Issues</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-analyzing-major-editions-and-phases-of-windows-movie-maker/"><u>In 2024, Analyzing Major Editions and Phases of Windows Movie Maker</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-open-source-audacity-alternatives-top-5-free-audio-editors-compared-on-windows/"><u>New In 2024, Open-Source Audacity Alternatives Top 5 Free Audio Editors Compared on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/switch-calculator-color-scheme-to-dark/"><u>Switch Calculator Color Scheme to Dark</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/discreetly-discover-anonymously-observe/"><u>Discreetly Discover, Anonymously Observe</u></a></li>
<li><a href="https://win11.techidaily.com/turning-onoff-phishing-filter-in-microsoftinas-windows-oses/"><u>Turning On/Off Phishing Filter in Microsoft’inas Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-legacy-ribbon-to-windows-explorer/"><u>Restoring Legacy Ribbon to Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-window-image-display-windows-11-style/"><u>Maximizing Window Image Display: Windows 11 Style</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-pros-cons-and-guide-to-utilizing-samsung-photo-editor/"><u>2024 Approved  Pros, Con's, and Guide to Utilizing Samsung PHOTO EDITOR</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-cutting-edge-pc-editing-techniques-enhancing-your-youtube-presence/"><u>In 2024, Cutting-Edge PC Editing Techniques  Enhancing Your YouTube Presence</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/ultimate-list-of-low-cost-desktop-encoder-software/"><u>Ultimate List of Low-Cost Desktop Encoder Software</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-convert-youtubes-audios-to-mp3-safely-step-by-step-guide-for-2024/"><u>[New] How To Convert YouTube's Audios to MP3 Safely - Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-the-failed-file-synchronization-on-steam/"><u>Remedy for the Failed File Synchronization on Steam</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-chrome-freeze-issue-for-windows-users/"><u>Tackling Chrome Freeze Issue for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/expanding-pin-code-length-in-windows-11-and-11/"><u>Expanding Pin Code Length in Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-your-yuzu-experience-on-windows/"><u>Supercharge Your Yuzu Experience on Windows</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-journey-through-data-storage-saving-fb-chats-as-video-files/"><u>[Updated] 2024 Approved  Journey Through Data Storage  Saving FB Chats as Video Files</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-s24-ultra-phone-without-any-data-loss-by-drfone-android/"><u>In 2024, How to Unlock Samsung Galaxy S24 Ultra Phone without Any Data Loss</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-rank-the-best-fb-video-downloaders-heres-how-for-2024/"><u>[Updated] Rank the Best FB Video Downloaders - Here's How for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/go-pure-with-linux-avoid-wsl/"><u>Go Pure with Linux - Avoid WSL</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-product-id-from-windows-with-ms-online-service/"><u>Integrating Product ID From Windows with MS Online Service</u></a></li>
<li><a href="https://win11.techidaily.com/processors-and-windows-discovering-your-cpus-generation-in-8-steps/"><u>Processors & Windows: Discovering Your CPU's Generation in 8 Steps</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-discovering-instagram-de-follows-quickly/"><u>In 2024, Discovering Instagram De-Follows Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-guide-to-security-focused-dialogue-shortcuts/"><u>Windows 11: Guide to Security-Focused Dialogue Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-the-hurdles-winplusprint-mishaps-in-windows/"><u>Navigating Through the Hurdles: Win+Print Mishaps in Windows</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-sonic-innovation-unleashed-navigating-through-the-seventh-wave-of-audio-manipulation/"><u>New In 2024, Sonic Innovation Unleashed Navigating Through the Seventh Wave of Audio Manipulation</u></a></li>
<li><a href="https://win11.techidaily.com/ten-terminal-tricks-you-can-try-today/"><u>Ten Terminal Tricks You Can Try Today</u></a></li>
<li><a href="https://win11.techidaily.com/successful-virtualbox-setup-in-winscape/"><u>Successful VirtualBox Setup in Winscape</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/viral-velocity-15-dynamic-steps-to-skyrocketing-follower-count-and-fame-on-instagram/"><u>Viral Velocity  15 Dynamic Steps to Skyrocketing Follower Count and Fame on Instagram</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-rectify-virtualboxs-efail-windows-issue-0x80004005/"><u>Tips to Rectify Virtualbox's E_FAIL (Windows) Issue: 0X80004005</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-flv-file-symphony-creating-a-single-youtube-playlist/"><u>[New] FLV File Symphony  Creating a Single YouTube Playlist</u></a></li>
<li><a href="https://win11.techidaily.com/prioritizing-and-optimizing-windows-11-service-usage-wisely/"><u>Prioritizing and Optimizing Windows 11 Service Usage Wisely</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-central-points-for-virtual-world-engagement/"><u>2024 Approved  Central Points for Virtual World Engagement</u></a></li>
<li><a href="https://extra-information.techidaily.com/explore-oceans-anew-top-camcorders-for-divers-and-snorkelers/"><u>Explore Oceans Anew - Top Camcorders for Divers & Snorkelers</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-quick-recording-keyboard-shortcut-tips-for-win-11/"><u>Mastering the Art of Quick Recording: Keyboard Shortcut Tips for Win 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-best-samsung-galaxy-xcover-7-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>In 2024, Best Samsung Galaxy XCover 7 Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-installation-of-arm-based-windows-11-from-iso/"><u>Mastering the Installation of ARM-Based Windows 11 From ISO</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-the-workflow-of-windows-11s-backup-feature/"><u>Understanding The Workflow of Windows 11'S Backup Feature</u></a></li>
<li><a href="https://extra-resources.techidaily.com/budget-conscious-skydrive-keepers-mass-file-basket-savings/"><u>Budget-Conscious Skydrive Keepers  Mass File Basket Savings</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-retro-video-magic-easy-ways-to-add-vhs-effects-in-fcp/"><u>New Retro Video Magic Easy Ways to Add VHS Effects in FCP</u></a></li>
<li><a href="https://network-issues.techidaily.com/laptops-lamentable-light-lapse/"><u>Laptop's Lamentable Light Lapse</u></a></li>
<li><a href="https://win11.techidaily.com/personalized-system-palette-placing-this-pc-on-screen/"><u>Personalized System Palette: Placing 'This PC' On Screen</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/boosting-visibility-igtv-and-facebook-connection-techniques/"><u>Boosting Visibility  IGTV & Facebook Connection Techniques</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-art-of-visual-storytelling-with-iphone-xs-new-lens/"><u>The Art of Visual Storytelling with iPhone X's New Lens</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-crashes-during-xbox-app-update-process/"><u>Resolving Crashes During Xbox App Update Process</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-error-403-in-roblox-space/"><u>Navigating Through Windows Error 403 in Roblox Space</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-unlock-the-secrets-of-facebook-live-a-beginners-manual/"><u>In 2024, Unlock the Secrets of Facebook Live  A Beginner's Manual</u></a></li>
<li><a href="https://win11.techidaily.com/locate-and-launch-windows-11-access-control-panel/"><u>Locate and Launch Windows 11 Access Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/speak-up-troubleshooting-and-fixing-microphone-errors-on-microsoft-powered-google-meet/"><u>Speak Up! Troubleshooting and Fixing Microphone Errors on Microsoft-Powered Google Meet</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-secrets-to-removing-windows-extract-error-1152/"><u>Unlocking Secrets to Removing Windows Extract Error 1152</u></a></li>
<li><a href="https://ai-topics.techidaily.com/new-how-to-define-ai-video-in-2024/"><u>New How to Define AI Video, In 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-xiaomi-14-pro-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Xiaomi 14 Pro? | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-strategies-for-muting-unwanted-sounds-in-multimedia/"><u>New In 2024, Strategies for Muting Unwanted Sounds in Multimedia</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/streamlining-social-media-posting-vimeo-on-instagram/"><u>Streamlining Social Media  Posting Vimeo on Instagram</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-captivate-and-enchant-explore-the-best-creative-reactions-on-yt/"><u>[New] In 2024, Captivate and Enchant  Explore the Best Creative Reactions on YT</u></a></li>
<li><a href="https://win11.techidaily.com/winexe-enhancement-convert-batch-to-powerful-formats/"><u>WinEXE Enhancement: Convert Batch to Powerful Formats</u></a></li>
<li><a href="https://win11.techidaily.com/3-methods-to-shorten-windows-11-boot-time-effectively/"><u>3 Methods to Shorten Windows 11 Boot Time Effectively</u></a></li>
<li><a href="https://video-capture.techidaily.com/simple-guides-for-recording-vimeo-content-for-2024/"><u>Simple Guides for Recording Vimeo Content for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-navigating-video-conferencing-with-ease-on-your-win10-pc/"><u>In 2024, Navigating Video Conferencing with Ease on Your Win10 PC</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-essential-strategies-for-effective-content-management-in-creator-studio/"><u>2024 Approved  Essential Strategies for Effective Content Management in Creator Studio</u></a></li>
</ul></div>
