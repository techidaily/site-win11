---
title: Navigating Disabling GPGPU Task Ordering in WinOS
date: 2024-08-28T00:50:48.064Z
updated: 2024-08-29T00:50:48.064Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Disabling GPGPU Task Ordering in WinOS
excerpt: This Article Describes Navigating Disabling GPGPU Task Ordering in WinOS
keywords: GPUTaskOrderWinOS,DisableGPGPUWin,WindowsGPUOptimization,OSGPUControlTask,GPGPUWindowsManagement,TaskOrderingDisablingWin,OptimizeGPUTasksWinOS
thumbnail: https://thmb.techidaily.com/45a1f9697d2bdeb16116c56d8bb656d37d6c88757987caf5e6bad0d2243c55f0.jpg
---

## Navigating Disabling GPGPU Task Ordering in WinOS

 If you were looking for new ways to get more out of your hardware, chances are you’ve enabled the Hardware accelerated GPU scheduling feature on your computer. While it’s supposed to improve your computer’s performance, it might have a negative effect, if your GPU is a bit older.

 In this case, should you disable it? But how can you turn off Hardware accelerated GPU scheduling in Windows 10 and 11?

## What Is Hardware Accelerated GPU Scheduling?

 Hardware-accelerated GPU scheduling is a feature designed to reduce the load on your CPU during intensive tasks. Usually, the CPU assigns the graphics-intensive data to the GPU, so games, media-playing apps, or editing software run smoothly. To do so, the CPU gathers, assigns, and sets the priority for each task so the GPU can render it.

 When the hardware-accelerated GPU scheduling feature is enabled, the dedicated GPU-based scheduler will handle the high-priority tasks. This way, the CPU can execute more tasks in the same amount of time.

## Should You Disable Hardware Accelerated GPU Scheduling?

![Discrete GPU made by NVIDIA](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Discrete-GPU-by-NVIDIA.jpg)

 Most of the time, [GPU hardware scheduling is worth turning on in Windows](https://www.makeuseof.com/windows-10-gpu-hardware-scheduling-worth-turning-on/), especially if your computer isn’t equipped with one of the latest GPU models. But enabling the GPU scheduling feature can also backfire, and have a negative impact on your computer’s performance. For example, on an older GPU, it might cause latency between the frames or even significant lag while gaming.

 Also, GPU scheduling is known for causing conflict with Windows services, such as dxgmms2.sys, which helps render graphics, especially during gaming sessions. So, if you keep running into the [dxgmms2.sys error in Windows 11](https://www.makeuseof.com/windows-11-dxgmms2-sys-error-fix/), you’ll have to disable the Hardware- accelerated GPU scheduling feature.

 In addition to this, the feature might encounter compatibility issues with specific hardware or software. So, you have to turn off GPU scheduling to keep your computer running smoothly.

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Disable Hardware Accelerated GPU Scheduling

 If the cons outweigh the pros, it’s time to disable Windows GPU scheduling. We’ll walk you through two different methods, so you can choose the one that works best for you.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Disable Hardware Accelerated GPU Scheduling Through Windows Settings

 The easiest way to disable the Hardware Accelerated GPU Scheduling feature is through Windows Settings. Here’s how you can do it on a Windows 11 computer:

1. Press **Win + I** to bring up the Settings menu.
2. Go to **System > Display**.
3. From the **Related settings** list, click on **Graphics**.
4. Click **Change default graphics settings**.
5. At the top of the page, turn off the toggle for **Hardware-accelerated GPU scheduling**.
6. Reboot your system.

![The Optimizations for windowed games setting option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/optimizations-for-windowed-games-setting.jpg)

 If you’re using Windows 10, here’s how you can disable the GPU hardware scheduling feature:

1. Right-click the **Start** button and select **Settings**.
2. Head to **System > Display**.
3. From the **Multiple Displays** menu, click on **Graphics settings**.
4. Turn off the toggle below **Hardware-accelerated GPU scheduling**.
5. Restart your computer for the change to take place.

![How to disable hardware accelerated gpu-scheduling in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/hardware-acc-win10-1.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Disable Hardware Accelerated GPU Scheduling Through Windows Registry

 If your graphics driver is outdated or corrupted, the hardware accelerated feature might be missing from the Settings menu. If you don’t have the time to replace or [update the graphics driver](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) right now, you can still disable hardware-accelerated GPU scheduling through Windows Registry.

1. Press **Win + R** to bring up a Run dialog.
2. Type **regedit** and press **Enter**.
3. In the Registry Editor window, head to **HKEY\_LOCAL\_MACHINE > SYSTEM > CurrentControlSet > Control > GraphicsDrivers**.
4. In the right pane, open the **HwSchMode** value.
5. Set **Value data** to **1**.
6. Click **OK** and restart your computer.

![How to disable hardware accelerated GPU scheduling through Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/registry-acc-1.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## GPU Scheduling Is Good, but It’s Not Perfect

 We’ve taken a look at how Hardware accelerated GPU scheduling works and when you should disable it. As we’ve mentioned, it may cause system issues, so it might be better to turn it off and look for alternatives. Fortunately, Windows comes with more built-in features to help you improve your gaming experience.

 In this case, should you disable it? But how can you turn off Hardware accelerated GPU scheduling in Windows 10 and 11?

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-blog.techidaily.com/024-approved-nine-crucial-strategies-to-elevate-your-youtube-presence/"><u>[New] 2024 Approved  Nine Crucial Strategies to Elevate Your Youtube Presence</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-non-vimeo-showstoppers-for-online-content-creators/"><u>[New] 2024 Approved  Non-Vimeo Showstoppers for Online Content Creators</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-select-6-best-iphone-slide-show-creation-apps/"><u>[New] 2024 Approved  Select 6 Best iPhone Slide Show Creation Apps</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-a-step-by-step-for-delving-into-fb-archives-for-2024/"><u>[New] A Step-by-Step for Delving Into FB Archives for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-decoding-automatic-clips-in-imovie/"><u>[New] Decoding Automatic Clips in iMovie</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-free-image-haven-best-10-sites-reviewed/"><u>[New] Free Image Haven  Best 10 Sites Reviewed</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-iphone-and-android-tips-direct-video-sharing-to-twitter-no-retweets/"><u>[New] IPhone & Android Tips  Direct Video Sharing to Twitter No Retweets</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-troubleshoot-mute-audio-in-tweeted-vids-for-2024/"><u>[New] Troubleshoot Mute Audio in Tweeted Vids for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-essential-screen-capture-best-mac-apps-reviewed-and-rated-for-2024/"><u>[Updated] Essential Screen Capture  Best Mac Apps Reviewed & Rated for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-immersive-editing-unveiling-the-top-15-cine-luts-for-action-cam/"><u>[Updated] Immersive Editing  Unveiling the Top 15 Cine LUTs for Action Cam</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-clearpathstoexpertisewithyoucamcapture/"><u>[Updated] In 2024, ClearPathsToExpertiseWithYouCamCapture</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-the-complete-haul-video-manual-from-shopping-to-screen-time-for-2024/"><u>[Updated] The Complete Haul Video Manual  From Shopping to Screen Time for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-the-ultimate-link-from-instas-photos-to-tiks-videos/"><u>[Updated] The Ultimate Link  From Insta's Photos to Tik's Videos</u></a></li>
<li><a href="https://extra-tips.techidaily.com/10-premier-websites-for-mystery-box-shopping-delights/"><u>10 Premier Websites for Mystery Box Shopping Delights</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-basic-building-blocks-simplest-mc-dwellings-for-novices/"><u>2024 Approved  Basic Building Blocks  Simplest MC Dwellings for Novices</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-free-top-10-subtitles-tools-srt-file-transformers/"><u>2024 Approved  Free Top 10 Subtitles Tools  SRT File Transformers</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-optimal-vr-headset-choice-embracing-the-freedom-of-mobile-or-the-tethered-experience/"><u>2024 Approved  Optimal VR Headset Choice  Embracing the Freedom of Mobile Or The Tethered Experience?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/a-complete-guide-to-oem-unlocking-on-vivo-y100i-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Vivo Y100i</u></a></li>
<li><a href="https://screen-recording.techidaily.com/comprehensive-strategies-for-overwatch-gaming-saves-for-2024/"><u>Comprehensive Strategies for Overwatch Gaming Saves for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/connected-healing-telemedicine-evolved/"><u>Connected Healing  Telemedicine Evolved</u></a></li>
<li><a href="https://win11.techidaily.com/connecting-with-ease-understanding-microsofts-phone-link-app/"><u>Connecting with Ease: Understanding Microsoft's Phone Link App</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ing-compelling-freefire-vids-with-strategy-guide-for-2024/"><u>Crafting Compelling FreeFire Vids with Strategy Guide for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/digital-dreamland-gamers-income-evolution/"><u>Digital Dreamland  Gamers' Income Evolution</u></a></li>
<li><a href="https://win11.techidaily.com/discovering-substitute-methods-for-the-ls-command-in-windows/"><u>Discovering Substitute Methods for the LS Command in Windows</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-enjoy-seamless-printing-brother-hl-l2340d0-printer-for-your-windows-device/"><u>Download & Enjoy Seamless Printing - Brother HL-L2340D0 Printer for Your Windows Device</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-listening-game-setup-of-win-1011s-atmos/"><u>Elevate Your Listening Game: Setup of Win 10/11'S Atmos</u></a></li>
<li><a href="https://win11.techidaily.com/essential-adjustments-for-disabled-windows-defense/"><u>Essential Adjustments for Disabled Window's Defense</u></a></li>
<li><a href="https://some-techniques.techidaily.com/fundamentals-for-newcomers-on-screen-quality-measures-for-2024/"><u>Fundamentals for Newcomers on Screen Quality Measures for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/honorable-highlights-elite-endorsements-for-snapping-alert-songs-for-2024/"><u>Honorable Highlights  Elite Endorsements for Snapping Alert Songs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-clear-out-a-no-logo-screen-in-win1011/"><u>How to Clear Out a No-Logo Screen in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-bluetooth-speaker-volume-control-not-working-in-windows-11/"><u>How to Fix the Bluetooth Speaker Volume Control Not Working in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unblock-and-connect-chrome-in-your-os-firewallantivirus-settings/"><u>How to Unblock and Connect Chrome in Your OS Firewall/Antivirus Settings</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-cameras-unveiled-the-beginners-guide-to-action-shooting/"><u>In 2024, Cameras Unveiled  The Beginner's Guide to Action Shooting</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-sony-xperia-1-v-phone-by-drfone-android/"><u>In 2024, How to Use Google Assistant on Your Lock Screen Of Sony Xperia 1 V Phone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mastering-photo-background-removal-techniques/"><u>In 2024, Mastering Photo Background Removal Techniques</u></a></li>
<li><a href="https://vp-tips.techidaily.com/instant-upload-solutions-top-5-free-online-converter-services-for-2024/"><u>Instant Upload Solutions  Top 5 Free Online Converter Services for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-systems-refusal-to-run-latest-windows-version/"><u>Overcoming System's Refusal to Run Latest Windows Version</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-update-issue-code-0x800f0845/"><u>Overcoming Update Issue: Code 0X800F0845</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-search-service-error-on-pcs/"><u>Overcoming Windows Search Service Error on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-wow-error-132-a-step-by-step-guide/"><u>Overcoming WoW Error #132: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-windows-drivers-a-step-by-step-guide/"><u>Overhauling Windows Drivers: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/perfectly-pairing-words-and-images-emoji-15-in-win11/"><u>Perfectly Pairing Words and Images: Emoji 15 in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/prime-fps-count-apps-to-enhance-your-win-11-gameplay/"><u>Prime FPS Count Apps to Enhance Your Win 11 Gameplay</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-frustrating-apex-legends-crashes-in-win11/"><u>Resolving Frustrating Apex Legends Crashes in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-no-sound-issues-with-usb-headphones-on-a-windows-7-system-guide/"><u>Resolving No-Sound Issues with USB Headphones on a Windows 7 System [Guide]</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-vanishing-steam-icon-graphics/"><u>Reviving Vanishing Steam Icon Graphics</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-photo-correction-mastering-background-removal/"><u>Seamless Photo Correction: Mastering Background Removal</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-ai-risks-when-crafting-your-win-11-code/"><u>Sidestep AI Risks When Crafting Your Win 11 Code</u></a></li>
<li><a href="https://win11.techidaily.com/solving-printmanagement-msc-error-a-step-by-step-guide/"><u>Solving 'PrintManagement' MSC Error: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/speed-up-deletions-with-customized-context-menus-in-windows/"><u>Speed up Deletions with Customized Context Menus in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-unlock-device-driver-access-in-windows-11/"><u>Strategies to Unlock Device Driver Access in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-upgrades-with-windows-11-in-place-protocols/"><u>Streamlining Upgrades with Windows 11 In-Place Protocols</u></a></li>
<li><a href="https://win11.techidaily.com/sync-issue-resolved-windows-time-coordination/"><u>Sync Issue Resolved: Windows Time Coordination</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-dism-failure-0x800f082f-with-ease/"><u>Tackling Windows' DISM Failure 0X800F082F with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tip-quiet-down-windows-hardware-keys/"><u>Tech Tip: Quiet Down Windows' Hardware Keys</u></a></li>
<li><a href="https://win11.techidaily.com/the-7-best-free-desktop-password-generators-for-windows/"><u>The 7 Best Free Desktop Password Generators for Windows</u></a></li>
<li><a href="https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-vivo-y36i-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 10 Fixes for Phone Keep Disconnecting from Wi-Fi On Vivo Y36i | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/transition-tactics-replacing-older-software-with-windows-11/"><u>Transition Tactics: Replacing Older Software with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-secrets-to-recover-lost-gpeditmsc-access/"><u>Unlocking Secrets to Recover Lost Gpedit.msc Access</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-best-video-editing-programs-for-gopro-users-looking-beyond-studio-for-2024/"><u>Updated Best Video Editing Programs for GoPro Users Looking Beyond Studio for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/why-isolating-audio-devices-may-be-a-windows-feature/"><u>Why Isolating Audio Devices May Be a Windows Feature?</u></a></li>
<li><a href="https://win11.techidaily.com/windows-control-panel-hacks-usb-access-management/"><u>Windows Control Panel Hacks: USB Access Management</u></a></li>
<li><a href="https://win11.techidaily.com/windows-terminal-and-powershell-unveiling-their-differences/"><u>Windows Terminal & PowerShell: Unveiling Their Differences</u></a></li>
<li><a href="https://win11.techidaily.com/windows-tips-for-distinguishing-between-hdd-and-ssd/"><u>Windows Tips for Distinguishing Between HDD and SSD</u></a></li>
<li><a href="https://win11.techidaily.com/winning-over-not-written-memory-error-on-pc/"><u>Winning Over Not Written Memory Error on PC</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>