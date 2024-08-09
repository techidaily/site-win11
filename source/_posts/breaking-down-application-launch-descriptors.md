---
title: Breaking Down Application Launch Descriptors
date: 2024-08-08T13:15:17.627Z
updated: 2024-08-09T13:15:17.627Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Breaking Down Application Launch Descriptors
excerpt: This Article Describes Breaking Down Application Launch Descriptors
keywords: App Launch Guide,Launch Process Steps,Launch Descriptor Use,Application Deployment Tips,Launching App Efficiently,Launch Protocols for Apps,Descriptors in App Launch
thumbnail: https://thmb.techidaily.com/26237c0b8cf6f930c119cd7d58abe423d11d796e2ad6cf886d90c9a4679357e1.jpg
---

## Breaking Down Application Launch Descriptors

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several [Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Create App Execution Aliases in Registry Editor

 Before editing or creating registry keys, it is advisable to [create a full backup of the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . Of course, you should also ensure you understand how to restore the Registry from that backup.

 The process below for creating app execution aliases in the Registry Editor should be the same in both Windows 10 and 11.

1. Open**Windows Search** , type**Registry Editor** , and click on the search result to open it.
2. In the editor, navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\App Paths** .
3. Next, right-click on the**App Paths** key in the left-hand pane, and select**New > Key** .
4. Give the new key an alias name that relates to the app and ends with .exe. For example, if the alias is for Calendar, call it something like cal.exe.
5. With the alias selected, double-click the**Default** value in the right-hand pane.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
![editing app aliases in registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-regedit.jpg)
6. In the Value data field, you will need to enter the full path to the app executable file. For example**C:\\Program Files (x86)\\Calendar.exe** .
7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## Using and Creating App Execution Aliases

 Entering commands into tools such as Command Prompt and PowerShell can be laborious. You can streamline that process by enabling or creating aliases for apps that commonly feature in those commands. Why type out a full path to an executable file when you can point to it with a few keystrokes?


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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-the-ultimate-zenith-of-pc-gameplay/"><u>[New] 2024 Approved  The Ultimate Zenith of PC Gameplay</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-transform-personal-experiences-through-direct-webcam-capture-using-vlc/"><u>[New] 2024 Approved  Transform Personal Experiences Through Direct Webcam Capture Using VLC</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-a-step-by-step-guide-to-stunning-image-artistry-mosaics/"><u>[New] A Step-By-Step Guide to Stunning Image Artistry Mosaics</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-harness-the-power-of-youtube-shorts-expert-filming-and-editing-techniques-for-2024/"><u>[New] Harness the Power of YouTube Shorts  Expert Filming and Editing Techniques for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-harnessing-hashtags-for-hitting-video-hotspots-on-fb/"><u>[New] In 2024, Harnessing Hashtags for Hitting Video Hotspots on FB</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-top-15-youtube-recording-software-for-gamers/"><u>[New] In 2024, Top 15 YouTube Recording Software for Gamers</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-precision-workflow-tackling-backdrops-in-affinity-photo-to-perfection/"><u>[New] Precision Workflow  Tackling Backdrops in Affinity Photo to Perfection</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-stand-out-in-the-crowd-logo-creation-for-podcasts/"><u>[New] Stand-Out in the Crowd  Logo Creation for Podcasts</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/tep-by-step-backlink-blueprint-for-channel-growth-for-2024/"><u>[New] Step-by-Step Backlink Blueprint for Channel Growth for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-clockwise-conundrum-video-undo-for-iphone-users/"><u>[Updated] Clockwise Conundrum  Video Undo for iPhone Users</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-discovering-top-tools-the-2023-guide-to-browser-capture-tech/"><u>[Updated] Discovering Top Tools  The 2023 Guide to Browser Capture Tech</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-streamlined-qanda-guide-for-attractive-podcasts-for-2024/"><u>[Updated] Streamlined Q&A Guide for Attractive Podcasts for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-stunning-iphone-portraits-through-water-imagery-techniques/"><u>[Updated] Stunning iPhone Portraits Through Water Imagery Techniques</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-uncover-top-8-spots-to-find-free-3d-text-psdfiles/"><u>[Updated] Uncover Top 8 Spots to Find Free 3D Text PSDFiles</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-advanced-conversion-mp4-to-facebook-2023/"><u>2024 Approved  Advanced Conversion  MP4 to FaceBook 2023</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-essential-14-text-based-motion-graphics/"><u>2024 Approved  Essential 14 Text-Based Motion Graphics</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-gopro-hero5-black-vs-gopro-hero4-silver/"><u>2024 Approved  GoPro Hero5 Black vs GoPro Hero4 Silver</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-inject-audio-harmony-to-premiere-pro-videos/"><u>2024 Approved  Inject Audio Harmony to Premiere Pro Videos</u></a></li>
<li><a href="https://win11.techidaily.com/6-high-performance-windows-video-editors-unveiled/"><u>6 High-Performance Windows Video Editors Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/6-methods-to-supercharge-virtual-machine-speed-in-windows/"><u>6 Methods to Supercharge Virtual Machine Speed in Windows</u></a></li>
<li><a href="https://android-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-oppo-a78-5g-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Oppo A78 5G</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-overheating-prevention-on-windows-pcs/"><u>Adjusting Overheating Prevention on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/aesthetic-desk-customization-displaying-this-pc-image/"><u>Aesthetic Desk Customization: Displaying 'This PC' Image</u></a></li>
<li><a href="https://win11.techidaily.com/changing-windows-read-only-settings-easily/"><u>Changing Windows Read-Only Settings Easily</u></a></li>
<li><a href="https://win11.techidaily.com/clarifying-windows-memory-management-via-pagefilesys-files/"><u>Clarifying Windows' Memory Management via Pagefile.sys Files</u></a></li>
<li><a href="https://fox-glue.techidaily.com/closer-look-easy-methods-to-zoom-in-minecraft/"><u>Closer Look  Easy Methods to Zoom in Minecraft</u></a></li>
<li><a href="https://win11.techidaily.com/coding-a-deity-command-into-system-menu/"><u>Coding a Deity Command Into System Menu</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-resolving-inbox-notifications-on-pcs/"><u>Comprehensive Guide to Resolving Inbox Notifications on PCs</u></a></li>
<li><a href="https://program-issues.techidaily.com/diagnosing-and-correcting-microphone-issues-during-gameplay-among-us-on-pc/"><u>Diagnosing and Correcting Microphone Issues During Gameplay: Among Us on PC</u></a></li>
<li><a href="https://fake-location.techidaily.com/dose-life360-notify-me-when-someone-checks-my-location-on-realme-narzo-60-pro-5g-drfone-by-drfone-virtual-android/"><u>Dose Life360 Notify Me When Someone Checks My Location On Realme Narzo 60 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/eliminate-stutter-and-improve-framerate-for-a-fluid-experience-in-red-dead-redemption-2/"><u>Eliminate Stutter and Improve Framerate for a Fluid Experience in Red Dead Redemption 2</u></a></li>
<li><a href="https://win11.techidaily.com/eradicate-stranded-status-from-xbox-console-experience-on-pc/"><u>Eradicate ‘Stranded’ Status From Xbox Console Experience on PC</u></a></li>
<li><a href="https://buynow-info.techidaily.com/expert-insights-into-the-netgear-nighthawk-rax120-a-top-choice-for-lightning-fast-internet/"><u>Expert Insights Into the Netgear Nighthawk RAX120: A Top Choice for Lightning-Fast Internet</u></a></li>
<li><a href="https://win11.techidaily.com/fix-windows-11s-random-shutdown-phenomenon/"><u>Fix Windows 11'S Random Shutdown Phenomenon</u></a></li>
<li><a href="https://fox-that.techidaily.com/fix-your-iphone-dictation-problems-with-these-five-steps/"><u>Fix Your iPhone Dictation Problems with These Five Steps</u></a></li>
<li><a href="https://win11.techidaily.com/foster-innovation-for-privacy-protection-explore-cutting-edge-technologies-like-onboard-anonymization-systems-or-secure-data-transmission-techniques-to-mini44/"><u>Foster Innovation for Privacy Protection: Explore Cutting-Edge Technologies Like Onboard Anonymization Systems or Secure Data Transmission Techniques to Minimize the Risk of Violating Customer's Privacy During Cookie Deliveries.</u></a></li>
<li><a href="https://win11.techidaily.com/ftdibussys-in-the-windows-ecosystem-a-dive-into-memory-shields/"><u>Ftdibus.sys in the Windows Ecosystem: A Dive Into Memory Shields</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-completely-get-rid-of-wsl-on-windows-11-pcs/"><u>How To Completely Get Rid of WSL on Windows 11 PCs</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-reset-your-iphone-14-plus-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Reset Your iPhone 14 Plus Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-solve-active-directory-issues-impacting-print-in-windows-11/"><u>How to Solve Active Directory Issues Impacting Print in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-the-mouse-without-borders-and-peek-features-in-powertoys/"><u>How to Use the Mouse Without Borders and Peek Features in PowerToys</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-efficient-roblox-gaming-save-techniques-on-macs/"><u>In 2024, Efficient Roblox Gaming Save Techniques on Macs</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-iphone-is-disabled-here-is-the-way-to-unlock-disabled-apple-iphone-13-pro-drfone-by-drfone-ios/"><u>In 2024, iPhone Is Disabled? Here Is The Way To Unlock Disabled Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-tutorial-to-change-samsung-galaxy-f04-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>In 2024, Tutorial to Change Samsung Galaxy F04 IMEI without Root A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/instantaneous-app-opener-tips-for-windows-11/"><u>Instantaneous App Opener Tips for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-installation-in-vmware-17-player/"><u>Mastering Windows 11 Installation in VMWare 17 Player</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-tackle-misdirected-token-call-on-windows/"><u>Methods to Tackle Misdirected Token Call” On Windows</u></a></li>
<li><a href="https://win11.techidaily.com/modify-homescreen-without-altering-windows-11-start-menu/"><u>Modify Homescreen without Altering Windows 11 Start Menu</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-highlight-settings-in-windows-11/"><u>Navigating Highlight Settings in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-win11-22h2-for-older-systems/"><u>Navigating Win11 22H2 for Older Systems</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-telnet-activation-on-modern-windows/"><u>Quick Guide to Telnet Activation on Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reducing-wasteful-usage-by-core-system-processes/"><u>Reducing Wasteful Usage by Core System Processes</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-java-installer-problems-on-a-windows-pc/"><u>Remedying Java Installer Problems on a Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/rescue-your-browser-fix-google-chrome-in-w11-today/"><u>Rescue Your Browser: Fix Google Chrome in W11 Today!</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-connectivity-problems-with-fall-guys-on-pc/"><u>Resolving Connectivity Problems with Fall Guys on PC</u></a></li>
<li><a href="https://win11.techidaily.com/revamp-your-window-11-experience-with-these-6-desired-android-apps/"><u>Revamp Your Window 11 Experience with These 6 Desired Android Apps</u></a></li>
<li><a href="https://extra-information.techidaily.com/snapshot-innovations-an-exploration-of-samsung-photo-editor/"><u>Snapshot Innovations  An Exploration of Samsung PHOTO EDITOR</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-to-delete-onedrive-icon-in-windows-explore/"><u>Step-by-Step to Delete OneDrive Icon in Windows Explore</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-inverted-text-input-windows-wise/"><u>Strategies for Fixing Inverted Text Input Windows-Wise</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-workflow-mastering-window-commands-and-shortcuts/"><u>Streamline Your Workflow: Mastering Window Commands & Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/surges-subdued-mastering-the-art-of-cpu-management-in-rm/"><u>Surges Subdued: Mastering the Art of CPU Management in RM</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-tutorial-to-edit-windows-files-metadata-dates/"><u>The Complete Tutorial to Edit Windows Files' Metadata Dates</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-tips-how-to-solve-opengl32dll-errors-effectively/"><u>Troubleshooting Tips: How To Solve OpenGL32.dll Errors Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-potential-top-free-must-have-for-win11/"><u>Unleash Potential: Top Free Must-Have for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-11-sticky-note-access/"><u>Unlocking Windows 11 Sticky Note Access</u></a></li>
<li><a href="https://win11.techidaily.com/winning-back-your-gameplay-fixed-windows-wow-connectivity/"><u>Winning Back Your Gameplay: Fixed Windows WoW Connectivity</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/youtube-shorts-description-everything-you-need-to-know-for-2024/"><u>YouTube Shorts Description  Everything You Need to Know for 2024</u></a></li>
</ul></div>
