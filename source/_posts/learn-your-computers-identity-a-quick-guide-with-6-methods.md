---
title: "Learn Your Computer’s Identity: A Quick Guide with 6 Methods"
date: 2024-08-16T00:56:09.466Z
updated: 2024-08-17T00:56:09.466Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Learn Your Computer’s Identity: A Quick Guide with 6 Methods"
excerpt: "This Article Describes Learn Your Computer’s Identity: A Quick Guide with 6 Methods"
keywords: Compute ID Learn Guide,Computer Identity Guide,How to Uncover Comp. Id,Computer Personality Find,Master Your PC ID,Quick Comp. Identity Tips,Methods for Identifying PC
thumbnail: https://thmb.techidaily.com/52b4eaebcfcbc6c7fedd891af89526f0d5ee168fe7bb540778411c3fb0605514.jpg
---

## Learn Your Computer’s Identity: A Quick Guide with 6 Methods

 Whether you want to find the correct hardware upgrade for your computer or want to fix an issue, knowing about your computer model name can come in handy in various situations. Here are 6 quick ways to check your computer model name on Windows.

## 1\. Using the Settings App

![Checking System Name in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-name.jpg)

 The quickest way to check your computer model name and number is through the Settings app. Simply, launch the**Settings app** (see[how to open the Settings app on Windows](https://www.makeuseof.com/windows-ways-to-open-system-settings/) ) and choose**System** from the left sidebar. You'll see your computer model name at the top of the System window.

## 2\. Using the System Information App

 The System Information is the go-to place to[check your system information on Windows 11](https://www.makeuseof.com/windows-11-check-system-information/) . You can use it to know about your computer's hardware resources, components, and software environment.

 To see your computer model name using the System Information app, follow the below instructions:

1. Press the**Win + S** hotkeys to open**Windows Search.**
2. In the search bar, type**System Information** and choose**Open** from the right pane.  
![Typing System Information in Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-information.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
3. Choose**System Summary** from the left sidebar.
4. Check the**System Model** row in the right pane to know about your computer model name.  
![Checking System Model in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-model.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Using the DirectX Diagnostic Tool

 The DirectX Diagnostic Tool contains information about the DirectX components and drivers installed on your computer. You can also use this tool to get information like System model, BIOS, Processor, Memory, Page file, and more.

 Here's how to use the DirectX Diagnostic Tool to know about your system model name:

1. Use one of the[many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. In the text field, type**dxdiag** and click**OK.**
3. Click the**System** tab in the DirectX Diagnostic Tool.
4. Under the System Information section, you can check your computer model name next to the**System Model** option.  
![System Model option in the DirectX Diagnostic Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-model-option.jpg)

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Using the Command-Line Tools

 If you're an advanced Windows user, you can use the command-line tools, Windows PowerShell and Command Prompt, to know everything about your computer. Here's how to use the Command Prompt to check your computer model name:

1. Open the Windows Search, type**Command Prompt** in the search bar, and press Enter.
2. In the Command Prompt window, type**wmic csproduct get name** , and press Enter.  
![System model checking command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-model-checking-command.jpg)

You'll see the model name on the console screen.

 Now, to view the model name using Windows PowerShell, launch Windows PowerShell, type the following command, and press Enter.

`Get-CimInstance -ClassName Win32_ComputerSystem`

![Command to Check System name in Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/command-to-check-system-name.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In case you want to check your computer serial number, execute the following command in the PowerShell window.

`Get-CimInstance -ClassName Win32_bios`

![Command to Check System Serial number in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/command-to-check-system-serial-number.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->

## 5\. Using the Manufacturer's Assistant App

![Checking System name using HP Support Assistant](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/hp-support-assistant.jpg)

 Most manufacturers nowadays offer an assistant app using which you can check your computer model name and number. For instance, if you're using an HP laptop, you can download the[HP Support Assistant app](https://support.hp.com/us-en/help/hp-support-assistant) to know everything about your computer.

 Similarly, you can download the assistant app of your manufacturer to check your computer's name.

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. By Entering the BIOS

 The Basic Input / Output System, aka BIOS, lets you configure basic computer settings like boot order, hardware components, and more. You can also use the BIOS menu to know every tiny detail about your computer.

 Here's how to[enter the BIOS menu on Windows](https://www.makeuseof.com/tag/enter-bios-computer/) and check your computer model name:

1. Open the Settings app, and choose**Windows Update** from the left sidebar.
2. Choose the**Advanced options.**
3. Under**Additional options,** select the**Recovery** option.
4. Click the**Restart now** button next to**Advanced startup.** Your computer will not boot into Recovery mode.  
![Restart now button next to Advanced startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/restart-now-button.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
5. Navigate to**Troubleshoot** \>**Advanced options** \>**UEFI Firmware Settings** \>**Restart.**
6. Usually, your computer will now boot straight into UEFI BIOS. But in some manufacturers like HP, you'll be welcomed with a**Startup** **Menu.** Choose**System Information** from the menu.  
![Choosing System Information from the Startup menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choosing-system-information.JPG)
7. You can check your computer name in the System Information section.  
![Checking Product name in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/checking-product-name.JPG)

## Get to Know Your Computer's Model on Windows

 These were all the working ways using which you can know your computer model name. However there are many other methods to check the name, but the ones mentioned above are among the quickest and easiest.

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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-easy-effective-strategy-immediate-clearance-of-unwanted-youtube-comments/"><u>[New] 2024 Approved  Easy, Effective Strategy  Immediate Clearance of Unwanted YouTube Comments</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-easy-steps-to-archive-vimeo-video-recordings/"><u>[New] Easy Steps to Archive Vimeo Video Recordings</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-high-definition-on-demand-samsungs-ue590-monitor-revisited/"><u>[New] High Definition on Demand  Samsung's UE590 Monitor Revisited</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastering-free-video-text-dynamics/"><u>[New] Mastering FREE Video Text Dynamics</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-secure-sharpening-hiding-unwanted-details/"><u>[New] Secure Sharpening  Hiding Unwanted Details</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-top-10-historical-youtube-hubs-essential-viewing-for-students-and-enthusiasts/"><u>[Updated] 2024 Approved  Top 10 Historical YouTube Hubs  Essential Viewing For Students & Enthusiasts</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-demystifying-complexities-a-guide-to-understanding-slug-lines/"><u>[Updated] In 2024, Demystifying Complexities  A Guide to Understanding Slug Lines</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-vivo-y100-drfone-by-drfone-virtual-android/"><u>10 Best Fake GPS Location Spoofers for Vivo Y100 | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-cutting-edge-methods-backing-up-iphone-photos-to-snapchat/"><u>2024 Approved  Cutting-Edge Methods  Backing Up iPhone Photos to Snapchat</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-full-range-kinetics-review/"><u>2024 Approved  Full Range Kinetics Review</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-is-picku-the-best-photo-editor-for-android-our-in-depth-review/"><u>2024 Approved  Is PickU The Best Photo Editor for Android? Our In-Depth Review</u></a></li>
<li><a href="https://win11.techidaily.com/3-keyways-to-refresh-file-explorer-in-win1011/"><u>3 Keyways to Refresh File Explorer in WIN10/11</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-transfer-music-from-nokia-c12-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Transfer Music from Nokia C12 to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-microsoft-can-improve-windows-11s-clipboard-history/"><u>9 Ways Microsoft Can Improve Windows 11'S Clipboard History</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-end-non-registered-user-sessions-on-windows-11/"><u>A Step-by-Step Guide to End Non-Registered User Sessions on WIndows 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/achieve-professionalism-in-sims-4-videography/"><u>Achieve Professionalism in Sims 4 Videography</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-optimal-msoffice-functionality-on-w11/"><u>Achieving Optimal MSOffice Functionality on W11</u></a></li>
<li><a href="https://win11.techidaily.com/basics-on-windows-exepe-files-an-overview/"><u>Basics on Windows EXE/PE Files: An Overview</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/build-your-dreamy-oriental-villas-in-minecraft/"><u>Build Your Dreamy Oriental Villas in Minecraft</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-cant-connect-nvidia-error-on-win-11-devices/"><u>Bypassing the Can't Connect Nvidia Error on Win 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-windows-for-secure-external-drive-handling/"><u>Configuring Windows for Secure External Drive Handling</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-long-start-ups-in-windows-11-easily-and-swiftly/"><u>Conquering Long Start-Ups in Windows 11 Easily and Swiftly</u></a></li>
<li><a href="https://win11.techidaily.com/curated-list-best-weather-trackers-for-w10w11/"><u>Curated List: Best Weather Trackers for W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/curbing-the-catastrophe-recycle-bin-errors-in-win1011/"><u>Curbing the Catastrophe: Recycle Bin Errors in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/cut-down-on-computing-power-spent-by-malware-scanners/"><u>Cut Down on Computing Power Spent by Malware Scanners</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-windows-programming-file-layout-pe/"><u>Deciphering the Windows Programming File Layout (PE)</u></a></li>
<li><a href="https://technical-tips.techidaily.com/detecting-false-connection-bids-on-your-profile-top-tips/"><u>Detecting False Connection Bids on Your Profile - Top Tips</u></a></li>
<li><a href="https://win11.techidaily.com/discover-file-systems-better-with-diskspace-added-to-windows-menu/"><u>Discover File Systems Better with Diskspace Added to Windows Menu</u></a></li>
<li><a href="https://win-solutions.techidaily.com/fixing-issues-how-to-restore-functionality-of-the-windows-11-taskbar/"><u>Fixing Issues: How to Restore Functionality of the Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/from-problem-to-perfection-tactics-to-install-missing-features-in-windows-11-and-11-pro/"><u>From Problem to Perfection: Tactics to Install Missing Features in Windows 11 & 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-open-the-private-character-editor-in-windows/"><u>How to Open the Private Character Editor in Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-in-ar-games-on-samsung-galaxy-f14-5g-drfone-by-drfone-virtual-android/"><u>How to Simulate GPS Movement in AR games On Samsung Galaxy F14 5G? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-about-vivo-t2-pro-5g-frp-bypass-by-drfone-android/"><u>In 2024, About Vivo T2 Pro 5G FRP Bypass</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-best-nubia-red-magic-9-pro-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>In 2024, Best Nubia Red Magic 9 Pro Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-discord-live-stream-recording-guide/"><u>In 2024, Discord Live Stream Recording Guide</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-xiaomi-redmi-k70-location-by-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Xiaomi Redmi K70 Location by Number | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-masterful-bordering-techniques-for-stellar-instagram-videos/"><u>In 2024, Masterful Bordering Techniques for Stellar Instagram Videos</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-quick-start-with-screencastify-video-recording/"><u>In 2024, Quick Start with Screencastify Video Recording</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-revolutionize-post-production-the-best-11-tutorials-on-color-workflow/"><u>In 2024, Revolutionize Post-Production  The Best 11 Tutorials on Color Workflow</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-sj4000-stylish-essentials-a-comprehensive-list/"><u>In 2024, SJ4000 Stylish Essentials  A Comprehensive List</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-superior-video-cutting-edge-tools-devices/"><u>In 2024, Superior Video Cutting-Edge Tools (Devices)</u></a></li>
<li><a href="https://win11.techidaily.com/instagrammable-pcs-how-to-add-your-chosen-weather-image-in-windows-11-status-bar/"><u>Instagrammable PCs: How to Add Your Chosen Weather Image in Windows 11 Status Bar</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-windows-taskmanager-on-top-techniques/"><u>Mastery Over Windows: TaskManager on Top Techniques</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-discover-the-power-of-final-cut-pro-90-days-free-no-strings-attached/"><u>New 2024 Approved Discover the Power of Final Cut Pro 90 Days Free, No Strings Attached</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-disconnect-fixing-gif-size-problems-in-discord-on-windows/"><u>Overcoming Disconnect: Fixing GIF Size Problems in Discord on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-error-e8024002e-for-smooth-updates/"><u>Overcoming Error E:8024002E for Smooth Updates</u></a></li>
<li><a href="https://win11.techidaily.com/post-update-woes-restoring-connection-after-a-failed-disco/"><u>Post-Update Woes: Restoring Connection After a Failed Disco</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-windows-ethernet-connection-access/"><u>Regaining Windows Ethernet Connection Access</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-frp-lock-on-s17-pro-by-drfone-android-unlock-remove-google-frp/"><u>Remove FRP Lock on S17 Pro</u></a></li>
<li><a href="https://facebook.techidaily.com/ripls-tips-for-making-viral-social-media-content/"><u>Ripl's Tips for Making Viral Social Media Content</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/six-ingenious-quizzes-to-pinpoint-your-perfect-youtube-persona/"><u>Six Ingenious Quizzes to Pinpoint Your Perfect YouTube Persona</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-unresponsive-process-in-windows/"><u>Steps to Resolve 'Unresponsive Process' In Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-desktop-no-overlaps/"><u>Streamline Your Desktop: No Overlaps</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-the-challenge-of-preview-failures-in-microsoft-mail/"><u>Tackling the Challenge of Preview Failures in Microsoft Mail</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-stop-net-core-error-message/"><u>Troubleshooting Windows: Stop .NET Core Error Message</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-potential-a-comprehensive-guide-to-windows-11s-in-place-upsurge/"><u>Unleashing Potential: A Comprehensive Guide to Windows 11'S In-Place Upsurge</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-potential-with-microsofts-pc-manager-in-win11/"><u>Unlocking Potential with Microsoft's PC Manager in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-potential-the-best-9-features-in-new-outlook/"><u>Unlocking Potential: The Best 9 Features in New Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/unseen-networks-windows-wi-fi-security-guide/"><u>Unseen Networks: Windows Wi-Fi Security Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unshackle-chromiums-network-access-via-windows-settings-blockers/"><u>Unshackle Chromium's Network Access via Windows Settings Blockers</u></a></li>
<li><a href="https://win11.techidaily.com/visual-virtuoso-top-tips-to-overcome-blurry-windows-11-displays/"><u>Visual Virtuoso: Top Tips to Overcome Blurry Windows 11 Displays</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-oppo-reno-8t-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For Oppo Reno 8T? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/which-window-suits-you-best-home-versus-pro-in-windows-11/"><u>Which Window Suits You Best? Home Versus Pro in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/win11-addressing-inaudible-wireless-speaker-issues/"><u>Win11: Addressing Inaudible Wireless Speaker Issues</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-quick-guide-to-open-sticky-notes/"><u>Windows 11: Quick Guide to Open Sticky Notes</u></a></li>
<li><a href="https://win11.techidaily.com/winning-over-full-screen-issues-in-sonic-adventure-on-windows-11/"><u>Winning Over Full-Screen Issues in Sonic Adventure on Windows 11</u></a></li>
</ul></div>
