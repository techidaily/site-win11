---
title: "Secure Your Snaps: Windows Strategies for Sticky Notes"
date: 2024-08-15T23:35:33.885Z
updated: 2024-08-16T23:35:33.885Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Secure Your Snaps: Windows Strategies for Sticky Notes"
excerpt: "This Article Describes Secure Your Snaps: Windows Strategies for Sticky Notes"
keywords: Secure Snap Tips,Note Security Guide,Windows Sticky Hacks,Safe Note Settings,Protecting Snaps Windows,Sync Sticky Notes,Privacy Note Strategies
thumbnail: https://thmb.techidaily.com/74045d9d6303c7a70563d004d7c7b11c2909530a50d24fd1a27318344d95b256.jpg
---

## Secure Your Snaps: Windows Strategies for Sticky Notes

 Sticky Notes on Windows turn your computer into a virtual board for posting notes, reminders, lists, and pretty much anything that you need to remember at a glance. So it makes sense that you wouldn't want to lose them, whether you're switching computers or a problem with your PC has caused you to lose your data.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.

## How to Back Up and Restore YourSticky Notes Using a Microsoft Account

 The easiest way to back up your sticky notes is to use a Microsoft account, which stores the notes on the cloud. If you don't have one already, then you can [learn how to create a Microsoft account](https://www.makeuseof.com/your-microsoft-account-things-windows-user-should-know/) or skip to the next section to learn how to back up the notes manually.

 If you've been using Windows with your Microsoft account all along, the notes could be synced to the cloud already. If you're not, you can [switch from a local account to a Microsoft account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/) for that to happen.

 To be sure if Sticky Notes is syncing your notes already or, if you're using a local account, give the app the ability to do so, follow the steps below:

1. Connect your Windows PC to the internet and open Sticky Notes.
2. Click on **Settings** (the gear icon) in the top right corner.
3. If you've already signed in, you'll see the details of your Microsoft account at the top with a **Sign out** link. If that's the case, you can skip to step #7 to sync the notes. If you're not signed in, click **Sign in**.
4. In the **Use one of these accounts** section, select the Microsoft account you want to sign in with. If there are no accounts there, select either **Microsoft account** or **Work or school account** in the **Use a different account** section.
5. Click **Continue** and follow the instructions to complete the sign-in process.
6. Once you're signed in, click on **Settings** again in the top right corner.
7. Scroll down and click **Sync now**.  
![the Sync Now button in Sticky Notes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/sync-now-button-in-sticky-notes.jpg)

 To restore the notes on another computer, open the Sticky Notes app (make sure the PC is connected to the internet) and sign in with your Microsoft account. Once signed in, the app will load all the notes you previously synced. Furthermore, every time you finish writing a Sticky Note or edit one, the app will automatically back it up to the cloud.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Manually Back Up and Restore Your Sticky Notes

 If you don't want to use a Microsoft account or want to have an extra backup of your sticky notes, then you can manually back them up yourself. While it's not as easy as just syncing them to the cloud, it can definitely come in handy when you don't have internet access and want to restore the notes.

 To manually back up your sticky notes, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.  
![opening tne Local State folder in Windows Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/opening-local-state-folder-in-windows-run.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
3. In the **LocalState** folder, copy the **plum.sqlite** file.  
![the plum database for Sticky Notes on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/the-plum-database-for-sticky-notes-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Paste the **plum.sqlite** file to an external drive, such as a flash drive or external SDD, or upload it to cloud storage, such as OneDrive or Google Drive, for safekeeping.

 To manually restore your sticky notes on another Windows computer, follow the steps below:

1. Copy the following file path: **%LocalAppData%\\Packages\\Microsoft.MicrosoftStickyNotes\_8wekyb3d8bbwe\\LocalState**.
2. Press **Win + R** to open Windows Run, paste the file path in the text box, and hit the **Enter** key.
3. Go to where you saved the backup of your sticky notes (the **plum.sqlite** file) and copy it.
4. In the **LocalState** folder, delete the current **plum.sqlite** file.
5. Paste the backup **plum.sqlite** file in the **LocalState** folder.

 Now when you open Sticky Notes, it will load the **plum.sqlite** file, and you should see all your notes appear in the app.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
## Never Lose Your Sticky Notes Again

 Losing your sticky notes means you could lose potentially important information. So it makes sense to always have a copy stored somewhere in case you need to restore them. We recommend using your Microsoft account to back up the notes, considering it's convenient to both sync and restore them later on, but it's also a good idea to know that there's a manual option available.

 In this guide, we're going to show you a couple of ways to back up your sticky notes on Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-the-weavers-codex-looms-screen-capture-secrets/"><u>[New] 2024 Approved  The Weaver’s Codex  Loom's Screen Capture Secrets</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-5-must-do-things-before-tiktok-usage-on-macos/"><u>[New] 5 Must-Do Things Before TikTok Usage on macOS</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-classification-of-fb-video-sizes/"><u>[New] Classification of FB Video Sizes</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/lite-alternative-edits-skip-youtube-not-just-content/"><u>[New] Elite Alternative Edits  Skip Youtube, Not Just Content</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-from-novice-to-experienced-6-strategies-for-quick-verification-on-instagram/"><u>[New] From Novice to Experienced  6 Strategies for Quick Verification on Instagram</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-leading-lists-premium-bdr-software-on-windows-macos/"><u>[New] In 2024, Leading Lists  Premium BDR Software on Windows, macOS</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-humorous-vines-the-ultimate-10-list-for-2024/"><u>[Updated] Humorous Vines  The Ultimate 10 List for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-the-art-of-curating-memories-on-social-media/"><u>[Updated] The Art of Curating Memories on Social Media</u></a></li>
<li><a href="https://win11.techidaily.com/12-common-windows-11-aesthetic-oddities/"><u>12 Common Windows 11 Aesthetic Oddities</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-analytics-mastery-measuring-success-on-your-instagram-videos/"><u>2024 Approved  Analytics Mastery  Measuring Success on Your Instagram Videos</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-harnessing-the-power-of-followers-for-impactful-advertising-campaigns/"><u>2024 Approved  Harnessing the Power of Followers for Impactful Advertising Campaigns</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-top-10-free-slideshow-designs-for-easy-presentations/"><u>2024 Approved  Top 10 Free Slideshow Designs for Easy Presentations</u></a></li>
<li><a href="https://win11.techidaily.com/5-actionable-steps-to-solve-gpeditmsc-disappearance/"><u>5 Actionable Steps to Solve Gpedit.msc Disappearance</u></a></li>
<li><a href="https://win11.techidaily.com/5-early-warnings-to-consider-windows-restart/"><u>5 Early Warnings to Consider Windows Restart</u></a></li>
<li><a href="https://win11.techidaily.com/8-easy-ways-to-unlock-windows-screen-setup-problems/"><u>8 Easy Ways to Unlock Windows Screen Setup Problems</u></a></li>
<li><a href="https://win11.techidaily.com/8-essential-techniques-for-improved-cs-go-play/"><u>8 Essential Techniques for Improved CS Go Play</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-realme-11-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Realme 11 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-restoring-lost-windows-update/"><u>A Beginner's Guide to Restoring Lost Windows Update</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreayers-guide-accessing-windows-web-services-manager/"><u>A Compreayer's Guide: Accessing Windows Web Services Manager</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-for-overcoming-the-pink-flash/"><u>A Comprehensive Guide for Overcoming the Pink Flash</u></a></li>
<li><a href="https://win11.techidaily.com/a-deep-dive-into-the-negative-side-of-low-end-windows-licenses/"><u>A Deep Dive Into the Negative Side of Low-End Windows Licenses</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-adding-secure-websites-in-windows-11/"><u>A Step-by-Step Guide to Adding Secure Websites in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-old-school-gaming-with-retroarcs-tools/"><u>A Step-by-Step Guide to Old-School Gaming with RetroArc's Tools</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-system-restart-utilizing-windows-11s-quick-start-function/"><u>Accelerating System Restart: Utilizing Windows 11'S Quick Start Function</u></a></li>
<li><a href="https://win11.techidaily.com/action-plan-if-powershell-isnt-displayed-by-windows/"><u>Action Plan if PowerShell Isn’t Displayed by Windows</u></a></li>
<li><a href="https://win11.techidaily.com/adding-visual-disk-space-analyzer-to-windows-explorer-menu/"><u>Adding Visual Disk Space Analyzer to Windows Explorer Menu</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-options-in-windows-nvidia-control-panel/"><u>Addressing Missing Options in Windows Nvidia Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-open-failed-error-on-ges-sharing-feature/"><u>Addressing Open Failed Error on GE's Sharing Feature</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-pubg-setup-failures-a-windows-guide/"><u>Addressing PUBG Setup Failures: A Windows Guide</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-store-glitch-code-0x80073cf3/"><u>Addressing Windows Store Glitch: Code 0X80073CF3</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-the-cost-monitor-functionality-of-your-wifi-network/"><u>Adjusting the Cost Monitor Functionality of Your Wifi Network</u></a></li>
<li><a href="https://article-helps.techidaily.com/advanced-techniques-in-developing-compelling-customer-success-narratives-for-2024/"><u>Advanced Techniques in Developing Compelling Customer Success Narratives for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-windows-navigation-methods-without-ls-command/"><u>Advanced Windows Navigation Methods Without LS Command</u></a></li>
<li><a href="https://screen-capture.techidaily.com/agricultural-bliss-the-10-perfect-gaming-friends-for-farmers/"><u>Agricultural Bliss  The 10 Perfect Gaming Friends for Farmers</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-your-ssds-potential-with-win-plus-fresh-strategies/"><u>Amplify Your SSD's Potential with Win + Fresh Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/an-intuitive-roadmap-for-installing-java-development-kit-on-windows-11/"><u>An Intuitive Roadmap for Installing Java Development Kit on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/asus-s15-oled-unveiled-power-and-style-in-one-package/"><u>ASUS S15 OLED Unveiled: Power & Style in One Package</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-missed-opportunities-top-9-outlook-enhancements-in-windows/"><u>Avoid Missed Opportunities: Top 9 Outlook Enhancements in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/avoidance-of-protected-windowsapps-folder-boundary/"><u>Avoidance of Protected WindowsApps Folder Boundary</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-xbox-game-pass-0x00000001-troubleshooting-for-windows-11/"><u>Avoiding Xbox Game Pass 0X00000001: Troubleshooting for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-glitches-a-guide-to-fixing-error-code-0x800700e9-in-xbox-game-pass-and-windows-11/"><u>Banishing Glitches: A Guide to Fixing Error Code 0X800700E9 in Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/beating-blue-screens-a-guide-to-system-recovery/"><u>Beating Blue Screens: A Guide to System Recovery</u></a></li>
<li><a href="https://win11.techidaily.com/big-bulky-minipcs-with-brainy-bare-performance/"><u>Big, Bulky Minipcs with Brainy Bare Performance</u></a></li>
<li><a href="https://win11.techidaily.com/boost-windows-performance-and-functionality-via-improved-run-toolset/"><u>Boost Windows Performance and Functionality via Improved Run Toolset</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-computer-skills-keyboard-shortcuts-for-success/"><u>Boost Your Computer Skills: Keyboard Shortcuts for Success</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-type-speed-harnessing-windows-powertoys/"><u>Boost Your Type-Speed: Harnessing Windows PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-the-barrier-5-apps-to-increase-volume-on-windows-past-100/"><u>Breaking the Barrier: 5 Apps to Increase Volume on Windows Past 100%%</u></a></li>
<li><a href="https://tech-haven.techidaily.com/discover-the-top-twenty-innovative-prompts-for-chatbots-on-github-repositories/"><u>Discover the Top Twenty Innovative Prompts for Chatbots on GitHub Repositories</u></a></li>
<li><a href="https://driver-install.techidaily.com/effective-method-to-reinstall-wireless-nic-drivers/"><u>Effective Method to Reinstall Wireless NIC Drivers</u></a></li>
<li><a href="https://tech-revival.techidaily.com/excel-powered-by-ai-unlocking-potential-with-chatgpt-insights/"><u>Excel Powered by AI: Unlocking Potential with ChatGPT Insights</u></a></li>
<li><a href="https://some-techniques.techidaily.com/explore-1-5-iphone-podcast-platforms-for-all-for-2024/"><u>Explore #1-#5 iPhone Podcast Platforms for All for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-fetch-latest-updates-for-your-dell-d3100-graphics-device-driver/"><u>How to Fetch Latest Updates for Your DELL D3100 Graphics Device Driver</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-lock-apps-on-vivo-v27e-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Vivo V27e to Protect Your Individual Information</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-a-comprehensive-guide-to-icloud-unlock-from-iphone-6-online-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to iCloud Unlock From iPhone 6 Online</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-asus-proart-pa-329q-unveiled-a-critical-perspective-on-a-high-end-monitor/"><u>In 2024, Asus ProArt PA 329Q Unveiled  A Critical Perspective on a High-End Monitor</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-best-oppo-reno-9a-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>In 2024, Best Oppo Reno 9A Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-comprehensive-review-and-overview-of-du-recorder/"><u>In 2024, Comprehensive Review and Overview of Du Recorder</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-full-tutorial-to-bypass-your-nokia-face-lock-by-drfone-android/"><u>In 2024, Full Tutorial to Bypass Your Nokia Face Lock?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-motorola-moto-g34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Come up With the Best Pokemon Team On Motorola Moto G34 5G? | Dr.fone</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/master-data-cleansing-techniques-top-guides-from-stellar-experts/"><u>Master Data Cleansing Techniques - Top Guides From Stellar Experts</u></a></li>
<li><a href="https://extra-support.techidaily.com/merging-melodies-and-memories-online-for-2024/"><u>Merging Melodies and Memories Online for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/optimize-your-phones-efficiency-by-pausing-android-apps-in-the-backend-operations/"><u>Optimize Your Phone's Efficiency by Pausing Android Apps in the Backend Operations</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/precision-in-storyboard-planning-for-2024/"><u>Precision in Storyboard Planning for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719347919938-skip-steps-just-admin-command-prompt-anytime-now/"><u>Skip Steps, Just Admin Command Prompt Anytime Now!</u></a></li>
<li><a href="https://vp-tips.techidaily.com/step-by-step-methods-for-amassing-tiktok-videos/"><u>Step-by-Step Methods for Amassing TikTok Videos</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-seamless-blend-enhancing-your-ae-projects-with-luts/"><u>The Seamless Blend  Enhancing Your AE Projects with LUTs</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/top-5-cloud-based-voice-customizers-for-chrome-os-vocal-transformation-tools-reviewed/"><u>Top 5 Cloud-Based Voice Customizers for Chrome OS  Vocal Transformation Tools Reviewed</u></a></li>
</ul></div>
