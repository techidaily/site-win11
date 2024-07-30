---
title: "Win11's DNS Cache: How to Clear and Maintain Efficiency"
date: 2024-07-29T15:45:09.223Z
updated: 2024-07-30T15:45:09.223Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win11's DNS Cache: How to Clear and Maintain Efficiency"
excerpt: "This Article Describes Win11's DNS Cache: How to Clear and Maintain Efficiency"
keywords: Win11DNSClearance,DNSCacheMaintenance,Win11EfficiencyOptimize,NetworkSpeedUpWin11,ResolveSlowWindows,WinDNSRefreshTips,FlushDNSPerformanceBoost
thumbnail: https://thmb.techidaily.com/90c049846794e5aed031591412d4826aac7c7bd6532c5bd0d695b676cbba88c9.jpg
---

## Win11's DNS Cache: How to Clear and Maintain Efficiency

 Facing internet connectivity issues on your Windows PC? DNS cache corruption is among the most common reasons for connectivity problems. The quickest fix for this problem is to flush the DNS cache and force the computer to recreate it.

 But do you know that there are multiple ways to flush the DNS cache on Windows 11? We will elaborate on the benefits of clearing the DNS cache along with the multiple methods which you can use on your Windows 11 PC. Without further ado, let’s dive into the post.

## What Is the DNS Cache and Why Should You Flush It?

 When you access a website, you usually do so by typing its URL in a browser. However, computers don't "understand" URLs, and each URL has a corresponding IP address that a computer can actually use. When you search for a website, your computer accesses a DNS server that contains records of URLs and their corresponding IP addresses.

 This process is known as DNS lookup, but it is time-consuming to search for an IP address every time, especially for websites that you visit repeatedly. So, the computer maintains a local copy of the DNS known as the DNS resolver cache. When you search for a URL, it checks the resolver cache first and then uses that information to find the website.

 The DNS resolver cache can become outdated or corrupt over time which can pose connectivity issues. There is also a looming risk of [DNS cache poisoning](https://www.makeuseof.com/tag/what-is-dns-cache-poisoning/) , which is why you should make it a habit to clean the DNS cache periodically.

## How to Flush the DNS Cache on Windows 11

 There are multiple methods to flush the DNS cache on Windows 11\. You can use the Run command box, Command Prompt, or even PowerShell. In addition, you can use a batch file to clear the DNS cache in a few clicks, any time you want. Here are the four ways to clear DNS on Windows 11:

### 1\. Using the Run Command Box

To flush the DNS cache using the Run command box, do as follows:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type “**ipconfig /flushdns** ” command.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Flush DNS Using the Run Command Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-the-run-command-box.jpg)
3. Press**Ctrl + Shift + Enter** keys at once. The Command Prompt will launch, execute the flush command, and close automatically.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
### 2\. Using CMD

 To clear the DNS resolver cache using CMD, repeat the following steps:

1. Press**Win + R** to open the run dialog box. Type**cmd** and press**Ctrl + Shift + Enter** keys at once.
2. CMD will open with admin privileges.
3. Type “**ipconfig /flushdns** ” command and press the**Enter** key.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Flush DNS Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-cmd.jpg)
4. You will see a “**Successfully flushed the DNS Resolver Cache.** ” message after the command execution.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 3\. Using PowerShell

 PowerShell has a different command to flush the DNS cache on Windows 11\. Here’s how to do it:

1. Press**Win + S** and type**PowerShell** . Click on the**Run as administrator** option in the Start menu.
2. Now, type “**Clear-DnsClientCache** ” in the PowerShell window and press the**Enter** key.  
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Flush DNS Using Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-powershell.jpg)
3. You won’t see a message after the command executes successfully. But you can open PowerShell again and view the DNS cache to confirm.

### 4\. Using a Batch File

 Opening an app is a slightly time-consuming process. You can save time by creating a batch file once and then running it whenever you need to flush DNS. No need to open the CMD or PowerShell app.

Repeat the following steps to create a DNS-clearing batch file:

1. Press**Win + S** to open Windows Search. Type**Notepad** and click on the first search result.
2. Type the following command in Notepad:**cmd.exe /k ipconfig /flushdns**  
![Flush DNS Using A Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-a-batch-file.jpg)
3. Press**Ctrl + S** to save the file. Enter the name “**flushDNS.bat** ” and keep the**Save as type** as**All Files** .
4. Click on the**Save** button.
5. Now go to the batch file location and double-click on it.
6. The Command Prompt will launch and execute the "**/** flushdns" command.
7. Type**exit** and press the**Enter** key to close the command prompt window.

## How to Flush Your Browser's DNS Records

 Do you know that browsers maintain a DNS cache as well? If you face connectivity issues, you should clear the browser's DNS cache and force the browser to rebuild the cache.

 Repeat the following steps to clear Chrome browser’s DNS cache:

1. Launch the Chrome browser and press**Ctrl + T** to open a new tab.
2. Now, type “**chrome://net-internals/#dns** ” in the search bar and press the**Enter** key.
3. Navigate to the**Host resolver cache** section. Click on the**Clear host cache** button to clear cached DNS records in the Chrome browser.

 The process to clear a browser's DNS cache may differ with other browsers like Safari, Opera, and Mozilla. You will have to locate the DNS settings and then wipe out the DNS cache.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
## Keep Your DNS Cache Clean on Windows

 Flushing the system's DNS cache periodically can reduce the risk of DNS spoofing and website connectivity issues. The simplest method is to use the ipconfig utility with appropriate parameters to flush the DNS cache. Alternatively, you can use the PowerShell method or create a batch file for the same.


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
<li><a href="https://youtube-data.techidaily.com/024-approved-from-raw-to-masterpiece-the-premier-free-mobile-editors-for-android/"><u>[New] 2024 Approved  From Raw to Masterpiece  The Premier Free Mobile Editors for Android</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-beginners-path-vrecord-instalment-manual-for-2024/"><u>[New] Beginners' Path  VRecord Instalment Manual for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-revel-in-richness-of-ranks-the-top-25-instagram-titans-unveiled-for-2024/"><u>[New] Revel in Richness of Ranks  The Top 25 Instagram Titans Unveiled for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-culinary-connoisseurs-must-watch-food-content-for-2024/"><u>[Updated] Culinary Connoisseurs  Must-Watch Food Content for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-elite-no-cost-fb-imagemovie-design-toolkit/"><u>[Updated] In 2024, Elite No-Cost FB Image/Movie Design Toolkit</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-excelling-at-content-creation-a-guide-to-gamers-success/"><u>[Updated] In 2024, Excelling at Content Creation  A Guide to Gamers' Success</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-expert-strategies-for-clear-communication-on-google-meet/"><u>[Updated] In 2024, Expert Strategies for Clear Communication on Google Meet</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-selective-sharpening-tips-for-modern-image-editors/"><u>[Updated] Selective Sharpening Tips for Modern Image Editors</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-delving-into-the-meaning-of-a-mysterious-blue-marker-in-fb-chats/"><u>2024 Approved  Delving Into the Meaning of a Mysterious Blue Marker in FB Chats</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exploring-sources-of-high-quality-insta-soundtracks-and-crafting-noteworthy-chimes/"><u>2024 Approved  Exploring Sources of High-Quality Insta Soundtracks and Crafting Noteworthy Chimes</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-pushing-boundaries-the-9-most-advanced-mobile-filmmaking-accessories/"><u>2024 Approved  Pushing Boundaries  The 9 Most Advanced Mobile Filmmaking Accessories</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-sony-xperia-10-v-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Sony Xperia 10 V | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-a-mouse-wheel-that-keeps-zooming-instead-of-scrolling-on-windows/"><u>7 Ways to Fix a Mouse Wheel That Keeps Zooming Instead of Scrolling on Windows</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-vivo-v30-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-comprehensible-guide-to-mastering-pixelated-photography-for-2024/"><u>A Comprehensible Guide to Mastering Pixelated Photography for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-blackout-getting-out-of-dark-mode/"><u>Bypassing The Blackout: Getting Out Of Dark Mode</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/constructing-unique-instagram-post-images/"><u>Constructing Unique Instagram Post Images</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-incorporate-google-maps-into-windows/"><u>Effortlessly Incorporate Google Maps Into Windows</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-hurdles-of-error-0x80040610-a-comprehensive-approach/"><u>Eliminating the Hurdles of Error 0X80040610: A Comprehensive Approach</u></a></li>
<li><a href="https://win11.techidaily.com/excel-in-windows-top-5-productivity-enhancers-you-cant-miss/"><u>Excel in Windows: Top 5 Productivity Enhancers You Can't Miss</u></a></li>
<li><a href="https://win11.techidaily.com/expert-strategies-to-manage-files-and-tabs-windows-11/"><u>Expert Strategies to Manage Files and Tabs (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-handling-winservicesexe-errors/"><u>Expert Tips for Handling Winservices.exe Errors</u></a></li>
<li><a href="https://extra-resources.techidaily.com/free-easy-online-downloader-for-your-pin-videos/"><u>Free, Easy Online Downloader for Your Pin Videos</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-nokia-c12-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Nokia C12 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fundamentals-of-windows-executable-files-pe/"><u>Fundamentals of Windows Executable Files (PE)</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-resetting-and-changing-login-credentials-in-win-11/"><u>Guide to Resetting and Changing Login Credentials in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-visual-upgrades-with-themes-from-microsoft-store/"><u>Harnessing Visual Upgrades with Themes From Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-icons-bunching-up-on-the-windows-11-taskbar/"><u>How to Fix Icons Bunching Up on the Windows 11 Taskbar</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-identify-malfunctioning-drivers-with-windows-device-manager-in-windows-11-by-drivereasy-guide/"><u>How to identify malfunctioning drivers with Windows Device Manager in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-re-establish-bluetooth-linkage-on-windows-1011/"><u>How To Re-Establish Bluetooth Linkage on Windows 10/11</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-iphone-se-2020-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update iPhone SE (2020) without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-solution-fixing-windows-auto-detect-proxy-errors/"><u>Immediate Solution: Fixing Windows' Auto Detect Proxy Errors</u></a></li>
<li><a href="https://some-techniques.techidaily.com/impact-of-visual-client-reviews-on-business-image-for-2024/"><u>Impact of Visual Client Reviews on Business Image for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-a-working-guide-for-pachirisu-pokemon-go-map-on-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/"><u>In 2024, A Working Guide For Pachirisu Pokemon Go Map On Realme Narzo 60x 5G | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-the-key-to-memorable-tiktok-opens-mac-edition/"><u>In 2024, The Key to Memorable TikTok Opens - Mac Edition</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/infinix-hot-40-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>Infinix Hot 40 ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/innovative-cameras-for-circular-coverage-for-2024/"><u>Innovative Cameras for Circular Coverage for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-imessage-for-windows-expert-techniques-revealed/"><u>Leveraging iMessage for Windows: Expert Techniques Revealed</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/lightweight-obs-adjustments-for-thriftier-systems/"><u>Lightweight OBS Adjustments for Thriftier Systems</u></a></li>
<li><a href="https://win11.techidaily.com/masterclass-on-mending-windows-1011-corrupted-recycle-bin/"><u>Masterclass on Mending Windows 10/11 Corrupted Recycle Bin</u></a></li>
<li><a href="https://win11.techidaily.com/method-to-resolve-audacitys-device-open-error-on-pc/"><u>Method to Resolve Audacity's Device Open Error on PC</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/pedagogical-picks-the-most-effective-video-recording-tools-for-instructors-for-2024/"><u>Pedagogical Picks  The Most Effective Video Recording Tools for Instructors for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-your-pc-saving-spotlight-pictures-as-wallpapers/"><u>Personalizing Your PC: Saving Spotlight Pictures as Wallpapers</u></a></li>
<li><a href="https://win11.techidaily.com/power-buttons-ahead-crafting-shortcuts-on-windows-11/"><u>Power Buttons Ahead: Crafting Shortcuts on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/powertoys-integration-into-win11-systems/"><u>PowerToys Integration Into Win11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-systemsettingsexe-failure-on-windows-11/"><u>Preventing SystemSettings.exe Failure on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-disconnect-solution-non-operative-printer-removal-in-win-1011/"><u>Quick Disconnect Solution: Non-Operative Printer Removal in Win 10/11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/reestablishing-iphone-x-trust-restoring-biometric-lock/"><u>Reestablishing iPhone X Trust  Restoring Biometric Lock</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-full-enter-key-capabilities-in-win-os/"><u>Regaining Full Enter Key Capabilities in Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/reinstate-your-favorite-microsoft-store-for-windows-devices/"><u>Reinstate Your Favorite Microsoft Store for Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-direct-voice-communication-for-xbox-on-windows-11/"><u>Reinstating Direct Voice Communication for Xbox on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-unable-to-open-on-ges-sharing-feature/"><u>Remedy for Unable to Open on GE's Sharing Feature</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/revive-playstation-classics-the-5-best-android-emulation-software-for-2024/"><u>Revive PlayStation Classics  The 5 Best Android Emulation Software for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-setup-for-icloud-users-with-windows-pcs/"><u>Seamless Setup for iCloud Users with Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-common-vscode-crash-causes-on-winw11/"><u>Sidestep Common VSCode Crash Causes on WinW11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-reactivating-razer-device-detection-by-synapse-software/"><u>Solutions for Reactivating Razer Device Detection by Synapse Software</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-telnet-enablement-in-win11/"><u>Step-by-Step: Telnet Enablement in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-improve-usb-interaction-points/"><u>Steps to Improve USB Interaction Points</u></a></li>
<li><a href="https://win11.techidaily.com/sticky-note-savvy-in-the-world-of-windows-11/"><u>Sticky Note Savvy in the World of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-disrupted-photo-packaging-in-windows-10-and-11/"><u>Tackling Disrupted Photo Packaging in Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-reverse-color-issue-with-windows-marketplace/"><u>Techniques to Reverse Color Issue with Windows Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-dolby-atmos-integration-in-windows-1011/"><u>The Ultimate Guide to Dolby Atmos Integration in Windows 10/11</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/top-5-tracking-apps-to-track-apple-iphone-x-without-them-knowing-drfone-by-drfone-virtual-ios/"><u>Top 5 Tracking Apps to Track Apple iPhone X without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/top-7-icloud-activation-bypass-tools-for-your-iphone-15-pro-by-drfone-ios/"><u>Top 7 iCloud Activation Bypass Tools For your iPhone 15 Pro</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-game-screens-for-ps5-and-xbox-series-x-revealed/"><u>Top Game Screens for PS5 and Xbox Series X Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/uninstalling-wsl-a-complete-guide-for-win-1011-users/"><u>Uninstalling WSL: A Complete Guide for Win 10/11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-secret-of-your-computers-ram-type/"><u>Unlocking the Secret of Your Computer's RAM Type</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-error-0x80300024-problems/"><u>Unraveling Windows' Error 0X80300024 Problems</u></a></li>
<li><a href="https://win11.techidaily.com/windows-basics-easy-access-aids-for-novices/"><u>Windows Basics: Easy-Access Aids for Novices</u></a></li>
<li><a href="https://win11.techidaily.com/winning-smoothly-eradicate-lags-from-star-wars-bf2-on-pc/"><u>Winning Smoothly: Eradicate Lags From Star Wars BF2 on PC</u></a></li>
</ul></div>
