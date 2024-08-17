---
title: Step-by-Step Guide for Deleting MS Edge Win11
date: 2024-08-15T23:57:58.963Z
updated: 2024-08-16T23:57:58.963Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Step-by-Step Guide for Deleting MS Edge Win11
excerpt: This Article Describes Step-by-Step Guide for Deleting MS Edge Win11
keywords: Delete MS Edge,Win11 Edge Removal,Edge Browser Uninstall,Deleting Win11 Edge,Remove MS Edge Win11,Win11 Edge Delete Guide,MS Edge Uninstallation
thumbnail: https://thmb.techidaily.com/035705869a176d12c457c62dcd5ac8433382a242da2e6ee8d5c9aeccc24af52d.jpg
---

## Step-by-Step Guide for Deleting MS Edge Win11

 Although Microsoft Edge has made significant progress in recent years, it still lags far behind its biggest rival—Google Chrome. If you’re someone who does not like using Microsoft Edge, you may want to get rid of the browser entirely.

 It’s no secret that Microsoft wants users to use its own browser on Windows 11\. To that end, the company has made it difficult to remove the browser from Windows 11\. However, it’s still possible to do so. Here we'll show you three different ways to uninstall Microsoft Edge from your Windows 11 PC.

## 1\. How to Uninstall Microsoft Edge Using the Command Prompt

 You can uninstall Microsoft Edge from your PC by running a few commands in the command prompt. The process requires you to know the version number of Microsoft Edge on your computer. Once you have that, you can get rid of the browser.

Here are the steps you need to follow.

1. Open Microsoft Edge on your PC.
2. Click the**three-dot menu icon** in the top right corner and select**Help and feedback > About Microsoft Edge** .
3. Copy Microsoft Edge's version number from the**About** section.  
![Check Microsoft Edge Version Number](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Microsoft-Edge-Version-Number.jpg)
4. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.
5. Select**Yes** when the User Account Control (UAC) prompt shows up.
6. In the console, run the following commands to navigate to the directory where Microsoft Edge is installed:  
`cd/  
cd %Program Files (x86)%\Microsoft\Edge\Application\EdgeVersion\Installer`  
 Replace**EdgeVersion** in the above command with the actual version number noted earlier.
7. Paste the following command and press**Enter** to uninstall Microsoft Edge.  
`setup --uninstall --force-uninstall --system-level`  
![Uninstall Microsoft Edge Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Command-Prompt.jpg)

 Once you run the above commands, Microsoft Edge will be removed from your PC. If you want to install the browser in the future, you can do so by downloading it from the Microsoft Store.

 If you'd like to get more out of this tool, be sure to check out [the Windows Command Prompt commands you must know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) .

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Uninstall Microsoft Edge Using Windows PowerShell

 Like Command Prompt, you can also use Windows PowerShell to uninstall Microsoft Edge from your Windows 11 PC. Unlike the previous method, this one does not require you to know Microsoft Edge's version number. Here's how it works.

1. Press**Win + S** to open the search menu. Type in**Windows PowerShell** and select**Run as administrator** .
2. Select**Yes** when the [User Account Control (UAC)](https://www.makeuseof.com/tag/user-account-control-windows-10/) prompt appears.
3. Paste the following command and press**Enter** .  
`get-appxpackage *edge*`  
![Uninstall Microsoft Edge With Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Windows-PowerShell-1.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
4. Highlight the text next to**PackageFullName** and press**Ctrl + C** to copy it.
5. Run the following command to uninstall Microsoft Edge.  
`Remove-appxpackage <PackageFullName>`  
 Replace**<PackageFullName>** in the above command with the package name copied earlier.

 Once you execute the above command, Microsoft Edge will be uninstalled.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Uninstall Microsoft Edge Beta, Dev, or Canary Channel Builds Using the Settings App

 Unlike the stable version, removing a preview build of Microsoft Edge is relatively simple. You can uninstall it just like any other app. Here's how to do it using [Windows 11 Settings app](https://www.makeuseof.com/windows-11-settings-whats-new/) .

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab and click on**Installed apps** .
3. Scroll down to locate Microsoft Edge's preview build.
4. Click the**three-dot menu icon** next to it and select**Uninstall** .
5. Select**Uninstall** again when the confirmation pop-up appears.  
![Uninstall Microsoft Edge Beta From Windows 11 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Beta-From-Windows-11-1.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->

 Aside from the Settings app, you can uninstall the browser from the Start menu or the Control Panel. See our guide to learn different [ways to uninstall built-in apps on Windows 11](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/) .

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Stop Microsoft Edge From Reinstalling on Windows 11

 Although uninstalling Edge from your computer is easy, it does not prevent newer Windows updates from potentially reinstalling the browser. To get around this, you need to [edit a few registry files](https://www.makeuseof.com/windows-registry-file-guide/) on your PC. For that, use the following steps:

1. Press**Win + R** to open the Run dialog box.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window that appears, navigate to**HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft** key.
5. Right-click on the**Microsoft** key, go to**New** , and select**Key** from the submenu. Rename the key to**EdgeUpdate** .
6. Right-click on the**EdgeUpdate** key and select**New > DWORD (32-bit) Value** . Rename the DWORD to**DoNotUpdateToEdgeWithChromium** .
7. Double-click on the newly created DWORD and change its value data to**1** . Then, hit**OK** .  
![Edit DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-dword-in-registry-editor.jpg)

 Once you complete the above steps, Windows will not reinstall Microsoft Edge with future updates.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Rid of Microsoft Edge

 With Windows 11, Microsoft tried everything possible to entice users to switch to Microsoft Edge. Unfortunately, it hasn't worked out very well, as many people still prefer to use alternatives like Google Chrome. If you are one of them, you can get rid of Microsoft Edge using the steps outlined above.

 Now that you've uninstalled Microsoft Edge, you might want to make your preferred web browser the default option on Windows 11.


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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-capture-fb-hd-footage-easily/"><u>[New] 2024 Approved  Capture FB HD Footage Easily</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-a-beginners-guide-to-elevating-auditory-experiences-on-youtube/"><u>[New] In 2024, A Beginner's Guide to Elevating Auditory Experiences on YouTube</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-stepwise-integration-technique-for-youtube-playlists-on-web/"><u>[New] Stepwise Integration Technique for YouTube Playlists on Web</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-deciphering-screens-a-comprehensive-review-of-recording-apps-for-2024/"><u>[Updated] Deciphering Screens  A Comprehensive Review of Recording Apps for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-instant-video-visionary/"><u>[Updated] Instant Video Visionary</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-photo-perfection-on-iphones-and-androids-blurring-basics/"><u>[Updated] Photo Perfection on iPhones & Androids  Blurring Basics</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-standard-to-spectacular-your-guide-to-choosing-a-high-res-screen/"><u>2024 Approved  From Standard to Spectacular  Your Guide to Choosing a High-Res Screen</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-photographic-fusion-at-full-speeds-google-collage-techniques/"><u>2024 Approved  Photographic Fusion at Full Speeds  Google Collage Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/7-noteworthy-changes-in-the-windows-11-file-explorer/"><u>7 Noteworthy Changes in the Windows 11 File Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-frustrating-fails-correcting-windows-error-1152/"><u>Avoiding Frustrating Fails: Correcting Windows' Error 1152</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1721996183037-boost-your-online-research-game-with-perplexity-the-unrivaled-ai-google-search-assistant-you-havent-tried-yet/"><u>Boost Your Online Research Game with Perplexity – The Unrivaled AI Google Search Assistant You Haven't Tried Yet!</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/code-mastery-for-effective-gpt-3-integration/"><u>Code Mastery for Effective GPT-3 Integration</u></a></li>
<li><a href="https://win11.techidaily.com/direct-pc-access-through-smb-protocols-mobile/"><u>Direct PC Access Through SMB Protocols (Mobile)</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/easy-gaming-memories-start-recording-now-in-2024/"><u>Easy Gaming Memories  Start Recording Now, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-file-lifecycle-in-windows-11-set-up-autodelete-protocols/"><u>Efficient File Lifecycle in Windows 11: Set Up Autodelete Protocols</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-creativity-discovering-the-latest-in-microsoft-paint/"><u>Elevate Creativity: Discovering the Latest in Microsoft Paint</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/-gala-2017-an-illuminated-expedition-into-yt-data/"><u>Graph Gala 2017  An Illuminated Expedition Into YT Data</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-could-not-create-the-java-virtual-machine-error-on-windows/"><u>How to Fix the “Could Not Create the Java Virtual Machine” Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-keep-windows-11s-search-bar-unseen/"><u>How to Keep Windows 11'S Search Bar Unseen</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-7-to-other-iphone-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 7 to other iPhone devices? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-apple-iphone-14-pro-max-without-passcode-4-easy-methods-drfone-by-drfone-ios/"><u>How To Unlock Apple iPhone 14 Pro Max Without Passcode? 4 Easy Methods | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-explore-revolutionary-meeting-platforms-that-cost-nothing/"><u>In 2024, Explore Revolutionary Meeting Platforms That Cost Nothing</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-oppo-a58-4g-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Oppo A58 4G Phones with/without a PC</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-infinix-note-30-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Infinix Note 30 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-approaches-for-temporary-profiles-on-windows/"><u>Innovative Approaches for Temporary Profiles on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/instant-spooler-restart-methods-for-windows/"><u>Instant Spooler Restart Methods for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11s-program-compatibility-troubleshooter/"><u>Mastering Windows 11'S Program Compatibility Troubleshooter</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-wsreset-troubleshooting-in-windows-environments/"><u>Mastering WSReset Troubleshooting in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-shutdown-of-windows-privacy-tools/"><u>Navigating the Shutdown of Windows Privacy Tools</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/new-how-to-use-capcut-translate-to-transform-video-content/"><u>New How To Use CapCut Translate to Transform Video Content</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-to-stabilize-windows-configuration-app/"><u>Quick Fixes to Stabilize Windows Configuration App</u></a></li>
<li><a href="https://win11.techidaily.com/reboot-routes-for-customizing-windows-11-settings-app/"><u>Reboot Routes for Customizing Windows 11 Settings App</u></a></li>
<li><a href="https://win11.techidaily.com/reconfiguring-fn-keys-for-optimal-windows-performance/"><u>Reconfiguring FN Keys for Optimal Windows Performance</u></a></li>
<li><a href="https://win11.techidaily.com/remove-hyper-v-from-windows-11-setup/"><u>Remove Hyper-V From Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/removing-hitchhiking-devices-win-1011-printer-uninstallation/"><u>Removing Hitchhiking Devices: Win 10/11 Printer Uninstallation</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-no-compatible-fingerprint-in-windows/"><u>Troubleshooting No Compatible Fingerprint in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-silencing-windows-11-operations/"><u>Ultimate Guide: Silencing Windows 11 Operations</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-rdp-connection-issues-in-modern-oses/"><u>Unblocking RDP Connection Issues in Modern OSes</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-full-control-of-windows-panel-settings/"><u>Unlock Full Control of Windows Panel Settings</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-oppo-a58-4g-drfone-by-drfone-virtual-android/"><u>Unova Stone Pokémon Go Evolution List and How Catch Them For Oppo A58 4G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-why-you-cant-see-drive-letters-on-your-windows-system/"><u>Unveiling Why You Can't See Drive Letters on Your Windows System</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-foundations-of-lexisaudioscript-your-first-steps-into-audio-editing/"><u>Updated In 2024, Foundations of LexisAudioScript Your First Steps Into Audio Editing</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-visual-flow-color-matching-and-grading-in-powerdirector-for-beginners-for-2024/"><u>Updated Visual Flow Color Matching and Grading in PowerDirector for Beginners for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/win-volume-adjustment-reviving-dull-edges/"><u>Win Volume Adjustment: Reviving Dull Edges</u></a></li>
</ul></div>
