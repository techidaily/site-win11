---
title: "Enriching Text Input Experience: Integrating WordPad Triggers in Windows 11"
date: 2024-08-16T00:51:45.504Z
updated: 2024-08-17T00:51:45.504Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enriching Text Input Experience: Integrating WordPad Triggers in Windows 11"
excerpt: "This Article Describes Enriching Text Input Experience: Integrating WordPad Triggers in Windows 11"
keywords: Window 11 Wizards,Enhance Text Entry,WordPad Integration,WinText User Input,Windows Advanced I/O,Triggered WordEntry,UI Text Dynamics
thumbnail: https://thmb.techidaily.com/0ac17e49979c72a050b377ffc6f63723ef10196944c0e4d0e8d090140eaead92.jpg
---

## Enriching Text Input Experience: Integrating WordPad Triggers in Windows 11

 Windows' WordPad app is either a limited word processor or an advanced text editor depending on how you look at it. Unlike Notepad, WordPad is a rich text editor that incorporates formatting and styling options for content. Therefore, it is a preferable alternative to Notepad for opening and editing TXT and RTF files.

 As such, you might want to add WordPad shortcuts to Windows 11’s context menu, so you can quickly access WordPad and open TXT/RTF documents with it. This is how you can set up context menu shortcuts for launching WordPad and opening files in it.

## How to Add a WordPad Shortcut to Windows 11’s Context Menu

 To create WordPad shortcuts on the right-click menu, you’ll need to do a bit of manual registry tweaking. The editing required is relatively straightforward, but you can back up the Windows registry beforehand if preferred. See[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) if you need help.

You can add a basic WordPad shortcut to the context menu like this:

1. Click inside the**Type here to search** box at the top of Windows 11’s Start menu.
2. Type the keyword**regedit** in the search box to open the Registry Editor (see[how to open the Registry Editor for more methods](https://www.makeuseof.com/windows-11-open-registry-editor/) ).
3. Erase the current location from the Registry Editor’s address bar.
4. Enter this shell key location inside the registry address bar and hit**Return** :  
`Computer\HKEY_CLASSES_ROOT\Directory\Background\shell\`
5. Right-click**shell** in the Registry Editor’s sidebar to select a**New** option.

1. Select**Key** to add a new registry key.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-new-key-options.jpg)
2. Enter**WordPad** in the text box for the new key.
3. Then right-click the new**WordPad** key and select the**New** \>**Key** options again.
4. Input**command** for the subkey’s title.  
![The WordPad key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-command-subkey.jpg)
5. Select the command key in the sidebar, and then double-click its**(Default)** string.
6. Input this path in the**Value** box:  
`"C:\Program Files\Windows NT\Accessories\wordpad.exe"`
7. Click**OK** to save the value, and exit the Registry Editor.  
![An Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/an-edit-string-window2.jpg)

 Now you can open WordPad from the desktop context menu in Windows 11\. Right-click anywhere on the desktop background and select**Show more options** to access the classic menu. Selecting the new**WordPad** option on that menu will open the app’s window.

![The WordPad context menu shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-shortcut.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## How to Add an Open with WordPad Shortcut to Windows 11’s Context Menu

 The basic WordPad shortcut launches the app, but you’ll need to open documents from its**File** tab manually. Instead, you can add a second context menu option for opening files with WordPad. That right-click option will provide a shortcut for opening documents in WordPad directly from File Explorer. This is how to add an**Open with WordPad** option to the context menu:

1. Open Registry Editor as outlined in the first three steps for adding a WordPad shortcut to the context menu.
2. Then clear out the address bar, and input this location path there:  
`HKEY_CLASSES_ROOT\*\shell`
3. Next, click the**shell** key with the right mouse button and select**New** .
4. Click the**Key** option for adding new registry entries.
5. Input**Open with WordPad** for the new key’s title.
6. Right-click**Open with Wordpad** and select**New** \>**Key** to add a subkey.
7. Type**command** in the text box for the subkey.  
![The Open with WordPad key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-with-wordpad-key.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Double-click the**(Default)** string for the new command subkey you just added.
9. Enter**wordpad.exe %1** in the**Value** box, and click**OK** to apply.  
![The wordpad.exe value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-wordpad-exe-value-data.jpg)
<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now you can close the Registry Editor and try out the**Open with WordPad** context menu shortcut. Launch File Explorer (see[how to launch File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) ), and navigate to a folder containing some TXT or RTF files. Right-click an RTF or TXT document and select**Show more options** . Click**Open with WordPad** to bring up the right-clicked document in that app.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Erase the WordPad Context Menu Shortcuts

 If you ever change your mind about having WordPad context menu options, you can remove them by deleting their keys. To do so, you’ll need to open the following key locations in the Registry Editor:

`Computer\HKEY_CLASSES_ROOT\*\shell\Open with WordPad\command  
Computer\HKEY_CLASSES_ROOT\Directory\Background\shell\WordPad\command`

 Then right-click the**Open with WordPad** or**WordPad** key to select a**Delete** option. A dialogue box will open requesting confirmation to erase. Select**Yes** if you’re sure about deleting the key.

![The Delete option for registry keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-delete-option2.jpg)
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
## Make the Most of Your WordPad Context Menu Shortcuts

 So, why add Notepad to Windows 11’s context menu when you set up WordPad shortcuts on it instead? Such shortcuts will give you direct access to a somewhat overlooked and underrated advanced text editor that can handle documents with images in them. You can utilize WordPad as a lightweight document viewer for looking at and even editing ODT, DOCX, TXT, and RTF files.

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
<li><a href="https://youtube-docs.techidaily.com/nveiling-the-hidden-treasures-youtubes-top-makeup-talents/"><u>[New] Unveiling the Hidden Treasures  YouTube's Top Makeup Talents</u></a></li>
<li><a href="https://win-howtos.techidaily.com/post-system-stabilizes-post-gameplay/"><u>[POST] System Stabilizes Post-Gameplay</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-aspect-ratios-in-action-facebooks-video-direction/"><u>[Updated] 2024 Approved  Aspect Ratios in Action  Facebook's Video Direction</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-apex-of-scripting-soundscapes/"><u>[Updated] Apex of Scripting Soundscapes</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-copyright-protection-for-instatunes-for-2024/"><u>[Updated] Copyright Protection for InstaTunes for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-essential-emulators-reviving-sonys-ps1-games/"><u>[Updated] In 2024, Essential Emulators Reviving Sony's PS1 Games</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-pairing-facebook-playback-with-home-theaters/"><u>[Updated] In 2024, Pairing Facebook Playback With Home Theaters</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-what-is-instagram-story-highlight/"><u>[Updated] In 2024, What Is Instagram Story Highlight?</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-apocalypse-alert-the-ultimate-list-of-thrilling-zombie-games/"><u>2024 Approved  Apocalypse Alert  The Ultimate List of Thrilling Zombie Games</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-primary-movie-document-review-and-backup-titles/"><u>2024 Approved  Primary Movie Document Review and Backup Titles</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-the-impact-and-innovations-in-vegaspro-a-2019-review/"><u>2024 Approved  The Impact and Innovations in VegasPro  A 2019 Review</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-your-guide-to-the-top-5-chromebook-sniping-software/"><u>2024 Approved  Your Guide to the Top 5 Chromebook Sniping Software</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-realme-note-50-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-easy-ways-to-change-location-on-youtube-tv-on-samsung-galaxy-s24-ultra-drfone-by-drfone-virtual-android/"><u>5 Easy Ways to Change Location on YouTube TV On Samsung Galaxy S24 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-devices-performance-naturally-with-wintoys/"><u>Accelerate Your Device's Performance Naturally with WinToys</u></a></li>
<li><a href="https://win11.techidaily.com/bolstering-older-directx-applications-through-dxvk-transformation/"><u>Bolstering Older DirectX Applications Through DXVK Transformation</u></a></li>
<li><a href="https://win11.techidaily.com/construct-a-stunning-slide-show-with-windows-11s-free-methods/"><u>Construct a Stunning Slide Show with Windows 11'S FREE Methods</u></a></li>
<li><a href="https://win11.techidaily.com/cpu-age-determination-for-pc-users-8-effective-methods/"><u>CPU Age Determination for PC Users: 8 Effective Methods</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-cross-language-interactions-with-keyboard-shortcuts-on-windows-11/"><u>Enhance Cross-Language Interactions with Keyboard Shortcuts on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-wi-fi-connectivity-in-windows-11-after-disruptions/"><u>Enhancing Wi-Fi Connectivity in Windows 11 After Disruptions</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/expedite-channel-growth-surpass-the-10k-view-threshold-now/"><u>Expedite Channel Growth  Surpass the 10K View Threshold Now</u></a></li>
<li><a href="https://buynow-info.techidaily.com/experience-superior-connectivity-the-mighty-netgear-nighthawk-x6wi-fi-extender/"><u>Experience Superior Connectivity: The Mighty Netgear Nighthawk X6Wi-Fi Extender</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/free2x-webcam-recorder-software-review/"><u>Free2X Webcam Recorder Software Review</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-tecno-camon-30-pro-5g-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Tecno Camon 30 Pro 5G 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/handling-the-mysterious-windows-subsystem-for-linux-error-4294967295/"><u>Handling the Mysterious Windows Subsystem for Linux Error 4294967295</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-realme-gt-neo-5-se-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Realme GT Neo 5 SE Phones with/without a PC</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-spark-10-4gs-lock-screen-pattern-pin-or-password-by-drfone-android-unlock-android-unlock/"><u>How to bypass Spark 10 4G’s lock screen pattern, PIN or password</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-install-dolby-atmos-in-windows-1111/"><u>How to Install Dolby Atmos in Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-lighten-load-time-for-epic-games-on-windows/"><u>How to Lighten Load Time for Epic Games on Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-pictures-from-vivo-s17t-by-fonelab-android-recover-pictures/"><u>How to recover deleted pictures from Vivo S17t.</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-set-up-advanced-security-features-ms-defender-aguard-for-windows-11-edge/"><u>How to Set Up Advanced Security Features: MS Defender Aguard for Windows 11 Edge</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-solution-for-frozen-keys-in-snipping-tool/"><u>Immediate Solution for Frozen Keys in Snipping Tool</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-samsung-galaxy-s23-ultra-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Samsung Galaxy S23 Ultra Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-full-tutorial-to-bypass-your-vivo-x-fold-2-face-lock-by-drfone-android/"><u>In 2024, Full Tutorial to Bypass Your Vivo X Fold 2 Face Lock?</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-can-i-unlock-my-iphone-15-plus-after-forgetting-my-pin-code-drfone-by-drfone-ios/"><u>In 2024, How Can I Unlock My iPhone 15 Plus After Forgetting my PIN Code? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-pause-life360-location-sharing-for-oppo-a78-drfone-by-drfone-virtual-android/"><u>In 2024, How To Pause Life360 Location Sharing For Oppo A78 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oppo-reno-10-pro-5g-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Oppo Reno 10 Pro 5G to Outlook | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-perfect-harmony-strategies-for-top-tier-audio-recording/"><u>In 2024, Perfect Harmony  Strategies for Top-Tier Audio Recording</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-sky-high-results-the-creme-de-la-liste-of-drone-editors/"><u>In 2024, Sky-High Results  The Crème De La Liste of Drone Editors</u></a></li>
<li><a href="https://extra-hints.techidaily.com/mastering-low-volume-transitions-within-fl-studio/"><u>Mastering Low-Volume Transitions Within FL Studio</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-windows-11-registry-file-layout/"><u>Mastering the Windows 11 Registry File Layout</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-vintage-pc-gaming-using-dosbox-x/"><u>Mastering Vintage PC Gaming: Using DOSBox-X</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-savings-with-windows-11-pro-secure-top-deals/"><u>Maximize Savings with Windows 11 Pro: Secure Top Deals</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/minimalist-approach-to-podcast-livestream-for-2024/"><u>Minimalist Approach to Podcast Livestream for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-mcuicnt-file-access-problem-on-pcs/"><u>Mitigating McUICnt File Access Problem on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-the-maze-of-unspecified-obs-error-in-windows/"><u>Navigate Through the Maze of Unspecified OBS Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-intelligence-of-microsofts-marketplace/"><u>Navigating the Intelligence of Microsoft's Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-common-roadblocks-in-windows-app-functionality/"><u>Overcoming Common Roadblocks in Windows App Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-hyper-v-error-0x8009030e/"><u>Overcoming Windows Hyper-V Error 0X8009030E</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-samsung-galaxy-a34-5g-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Samsung Galaxy A34 5G Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-functional-shortcuts-cure-errors-in-win-11/"><u>Rectify: Functional Shortcuts - Cure Errors in Win 11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reliable-user-guide-to-fix-tecno-camon-20-running-slow-and-freezing-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reliable User Guide to Fix Tecno Camon 20 Running Slow and Freezing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-system-call-failure-in-win1011-systems/"><u>Remedying System Call Failure in Win10/11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-normalcy-after-windows-video-failures/"><u>Restoring Normalcy After Windows Video Failures</u></a></li>
<li><a href="https://fix-guide.techidaily.com/simple-solutions-to-fix-android-systemui-has-stopped-error-for-realme-c55-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Simple Solutions to Fix Android SystemUI Has Stopped Error For Realme C55 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-fixing-unrecoverable-software-failures/"><u>Solutions for Fixing Unrecoverable Software Failures</u></a></li>
<li><a href="https://win11.techidaily.com/solving-mfc71udll-absence-in-windows-os/"><u>Solving Mfc71u.dll Absence in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-change-your-windows-11-username/"><u>Steps to Change Your Windows 11 Username</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-sticky-notebook-convergence-on-win11/"><u>Streamlining Sticky Notebook Convergence on Win11</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-xiaomi-redmi-note-12-pro-4g-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Xiaomi Redmi Note 12 Pro 4G Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/tailor-windows-screenshot-feature-to-suit-your-preferences/"><u>Tailor Windows Screenshot Feature to Suit Your Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/tech-savvy-collectors-dream-essential-612lifetime-windows-11-deal-awaits/"><u>Tech-Savvy Collectors' Dream: Essential $6.12/Lifetime Windows 11 Deal Awaits</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-keep-word-reading-mode-active-when-handling-email-attachments/"><u>Tips to Keep Word Reading Mode Active When Handling Email Attachments</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-user-experience-in-windows-11/"><u>Transforming User Experience in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/triumph-in-windows-pricing-acquiring-top-product-keys/"><u>Triumph in Windows Pricing: Acquiring Top Product Keys</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-inability-to-remove-apps/"><u>Troubleshooting Windows' Inability to Remove Apps</u></a></li>
<li><a href="https://win11.techidaily.com/unhighlight-your-windows-11-desktop-with-ease/"><u>Unhighlight Your Windows 11 Desktop with Ease</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/unidentified-video-images-strategies-for-blurring-private-sections-for-2024/"><u>Unidentified Video Images  Strategies for Blurring Private Sections for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-solutions-for-error-0x800704b3-in-windows-11-and-11/"><u>Unlocking Solutions for Error 0X800704B3 in Windows 11 & 11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/unveiling-youtubes-monetization-process/"><u>Unveiling YouTube's Monetization Process</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-rapid-notification-curbing-guide/"><u>Windows 11: Rapid Notification Curbing Guide</u></a></li>
<li><a href="https://win11.techidaily.com/winter-wonderland-offering-apps-from-microsofts-store/"><u>Winter Wonderland: Offering Apps From Microsoft's Store</u></a></li>
</ul></div>
