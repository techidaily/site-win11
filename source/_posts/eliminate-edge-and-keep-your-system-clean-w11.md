---
title: Eliminate Edge and Keep Your System Clean (W11)
date: 2024-07-29T15:49:21.021Z
updated: 2024-07-30T15:49:21.021Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminate Edge and Keep Your System Clean (W11)
excerpt: This Article Describes Eliminate Edge and Keep Your System Clean (W11)
keywords: Clean W11 System,Edge Removal Guide,System Hygiene Tips,W11 Upkeep Secrets,Keep Systems Pure,Edgeless Computer Care,Maintain W11 Clarity
thumbnail: https://thmb.techidaily.com/d2d94c4e77b77ed0c83b7c2ce10b6132329d863043aff159270d3e923d41f323.jpg
---

## Eliminate Edge and Keep Your System Clean (W11)

 Although Microsoft Edge has made significant progress in recent years, it still lags far behind its biggest rival—Google Chrome. If you’re someone who does not like using Microsoft Edge, you may want to get rid of the browser entirely.

 It’s no secret that Microsoft wants users to use its own browser on Windows 11\. To that end, the company has made it difficult to remove the browser from Windows 11\. However, it’s still possible to do so. Here we'll show you three different ways to uninstall Microsoft Edge from your Windows 11 PC.

## 1\. How to Uninstall Microsoft Edge Using the Command Prompt

 You can uninstall Microsoft Edge from your PC by running a few commands in the command prompt. The process requires you to know the version number of Microsoft Edge on your computer. Once you have that, you can get rid of the browser.

Here are the steps you need to follow.

1. Open Microsoft Edge on your PC.
2. Click the**three-dot menu icon** in the top right corner and select**Help and feedback > About Microsoft Edge** .
3. Copy Microsoft Edge's version number from the**About** section.  
<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Check Microsoft Edge Version Number](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Microsoft-Edge-Version-Number.jpg)
4. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.
5. Select**Yes** when the User Account Control (UAC) prompt shows up.
6. In the console, run the following commands to navigate to the directory where Microsoft Edge is installed:  
`cd/  
cd %Program Files (x86)%\Microsoft\Edge\Application\EdgeVersion\Installer`  
 Replace**EdgeVersion** in the above command with the actual version number noted earlier.
7. Paste the following command and press**Enter** to uninstall Microsoft Edge.  
`setup --uninstall --force-uninstall --system-level`  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Uninstall Microsoft Edge Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Command-Prompt.jpg)

 Once you run the above commands, Microsoft Edge will be removed from your PC. If you want to install the browser in the future, you can do so by downloading it from the Microsoft Store.

 If you'd like to get more out of this tool, be sure to check out [the Windows Command Prompt commands you must know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. How to Uninstall Microsoft Edge Using Windows PowerShell

 Like Command Prompt, you can also use Windows PowerShell to uninstall Microsoft Edge from your Windows 11 PC. Unlike the previous method, this one does not require you to know Microsoft Edge's version number. Here's how it works.

1. Press**Win + S** to open the search menu. Type in**Windows PowerShell** and select**Run as administrator** .
2. Select**Yes** when the [User Account Control (UAC)](https://www.makeuseof.com/tag/user-account-control-windows-10/) prompt appears.
3. Paste the following command and press**Enter** .  
`get-appxpackage *edge*`  
![Uninstall Microsoft Edge With Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Windows-PowerShell-1.jpg)
4. Highlight the text next to**PackageFullName** and press**Ctrl + C** to copy it.
5. Run the following command to uninstall Microsoft Edge.  
`Remove-appxpackage <PackageFullName>`  
 Replace**<PackageFullName>** in the above command with the package name copied earlier.

 Once you execute the above command, Microsoft Edge will be uninstalled.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. How to Uninstall Microsoft Edge Beta, Dev, or Canary Channel Builds Using the Settings App

 Unlike the stable version, removing a preview build of Microsoft Edge is relatively simple. You can uninstall it just like any other app. Here's how to do it using [Windows 11 Settings app](https://www.makeuseof.com/windows-11-settings-whats-new/) .

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab and click on**Installed apps** .
3. Scroll down to locate Microsoft Edge's preview build.
4. Click the**three-dot menu icon** next to it and select**Uninstall** .
5. Select**Uninstall** again when the confirmation pop-up appears.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
![Uninstall Microsoft Edge Beta From Windows 11 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Beta-From-Windows-11-1.jpg)

 Aside from the Settings app, you can uninstall the browser from the Start menu or the Control Panel. See our guide to learn different [ways to uninstall built-in apps on Windows 11](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/) .

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
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
<li><a href="https://youtube-data.techidaily.com/024-approved-brightening-filmmaking-ranking-the-17-best-lights/"><u>[New] 2024 Approved  Brightening Filmmaking  Ranking the 17 Best Lights</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-dial-up-beats-easy-audio-posting-to-youtubes/"><u>[New] 2024 Approved  Dial-Up Beats  Easy Audio Posting to YouTubes</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-enhancing-video-success-top-8-yt-thumbnail-strategies/"><u>[New] 2024 Approved  Enhancing Video Success  Top 8 YT Thumbnail Strategies</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-keeping-your-creative-content-on-ios-with-ease/"><u>[New] 2024 Approved  Keeping Your Creative Content on iOS with Ease</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-changing-ringtones-on-an-iphone-a-user-friendly-approach/"><u>[New] Changing Ringtones on an iPhone  A User-Friendly Approach</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-libertycam-studio-a-user-friendly-review/"><u>[New] In 2024, LibertyCam Studio  A User-Friendly Review</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-which-screen-recorder-excels-obs-or-fraps-in-2024/"><u>[New] Which Screen Recorder Excels  OBS or Fraps, In 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-mastering-digital-screen-capture-techniques-for-2024/"><u>[Updated] Mastering Digital Screen Capture Techniques for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-mastering-rl-recording-techniques-for-2024/"><u>[Updated] Mastering RL Recording Techniques for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-top-picks-ultimate-gifs-and-images-as-zoomgoogle-meet-backdrops-for-2024/"><u>[Updated] Top Picks  Ultimate GIFs & Images as Zoom/Google Meet Backdrops for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-capturing-in-action-a-screen-recorders-journey/"><u>2024 Approved  Capturing in Action  A Screen Recorder's Journey</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-mastery-of-digital-recording-step-by-step-insight/"><u>2024 Approved  Mastery of Digital Recording - Step-by-Step Insight</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-transforming-scenes-with-ease-your-gopro-time-lapse-guide/"><u>2024 Approved  Transforming Scenes with Ease  Your GoPro Time-Lapse Guide</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-enable-compact-view-in-file-explorer-on-windows-11/"><u>3 Ways to Enable Compact View in File Explorer on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-remove-the-microsoft-store-app-from-windows-11/"><u>3 Ways to Remove the Microsoft Store App From Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/3-ways-to-unlock-your-apple-iphone-13-pro-max-for-free-by-drfone-ios/"><u>3 Ways to Unlock Your Apple iPhone 13 Pro Max for Free</u></a></li>
<li><a href="https://win11.techidaily.com/6-costly-misconceptions-about-affordable-windows-codes/"><u>6 Costly Misconceptions About Affordable Windows Codes</u></a></li>
<li><a href="https://win11.techidaily.com/7-common-concerns-against-moving-to-windows-11/"><u>7 Common Concerns Against Moving to Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-keyboard-input-lag-on-windows-10-and-11/"><u>7 Ways to Fix Keyboard Input Lag on Windows 10 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/8-simple-steps-for-unlocking-your-windows-hello-device/"><u>8 Simple Steps for Unlocking Your Windows Hello Device</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-fix-for-inaccessible-screen-settings-in-windows/"><u>A Comprehensive Fix for Inaccessible Screen Settings in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-windows-snap-configurations-via-powertoys/"><u>A Comprehensive Guide to Windows Snap Configurations via PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-tutorial-on-windows-11-hotspot-setup-procedures/"><u>A Comprehensive Tutorial on Windows 11 Hotspot Setup Procedures</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-fixing-windows-lsass-components-issue/"><u>A Guide to Fixing Windows Lsass Components Issue</u></a></li>
<li><a href="https://win11.techidaily.com/activating-hidden-taskbar-query-function-in-windows-11/"><u>Activating Hidden Taskbar Query Function in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/add-ons-for-the-classics-mastering-achievements-via-retroarch-software-guide/"><u>Add-Ons for the Classics: Mastering Achievements via Retroarch Software Guide</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-error-a00f429f-in-windows-camera-functionality/"><u>Addressing Error A00F429F in Windows' Camera Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unplugging-confirmation-failures-in-win/"><u>Addressing Unplugging Confirmation Failures in WIN</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-v22h2-update-installation-obstacle-in-win11/"><u>Addressing V22H2 Update Installation Obstacle in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-alt-code-malfunctions-48-characters/"><u>Addressing Windows ALT Code Malfunctions (48 Characters)</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-faults-with-proven-remedies/"><u>Addressing Windows Faults with Proven Remedies!</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-your-pc-a-guide-to-optimizing-windows-11-options/"><u>Adjusting Your PC: A Guide to Optimizing Windows 11 Options</u></a></li>
<li><a href="https://win11.techidaily.com/ameliorating-the-non-functional-windows-enter-key/"><u>Ameliorating the Non-Functional Windows Enter Key</u></a></li>
<li><a href="https://win11.techidaily.com/audioscapes-redefined-mastering-the-windows-driver-update-technique/"><u>Audioscapes Redefined: Mastering the Windows Driver Update Technique</u></a></li>
<li><a href="https://win11.techidaily.com/augment-windows-11-notebook-with-cognitive-companion/"><u>Augment Windows 11 Notebook with Cognitive Companion</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-overheat-proper-maintenance-during-gaming-sessions/"><u>Avoiding Overheat: Proper Maintenance During Gaming Sessions</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-the-deadly-javascript-error-from-discord-on-win-11/"><u>Banishing the Deadly JavaScript Error From Discord on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/bask-in-the-best-of-microsofts-winstore-treasures/"><u>Bask in the Best of Microsoft’s WinStore Treasures</u></a></li>
<li><a href="https://win11.techidaily.com/beating-the-system-uncrashing-win1011s-corrupt-bin-error/"><u>Beating the System: Uncrashing Win10/11's Corrupt Bin Error</u></a></li>
<li><a href="https://win11.techidaily.com/beginners-tutorial-starting-windows-media-player/"><u>Beginner's Tutorial: Starting Windows Media Player</u></a></li>
<li><a href="https://extra-tips.techidaily.com/custom-logo-blueprints-draw-your-identity-from-free-formats/"><u>Custom Logo Blueprints  Draw Your Identity From Free Formats</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-to-lava-blaze-2-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Lava Blaze 2 FRP Bypass With Best Methods</u></a></li>
<li><a href="https://youtube-help.techidaily.com/finding-the-balance-adding-videos-to-text-on-a-budget-for-2024/"><u>Finding the Balance  Adding Videos to Text on a Budget for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-error-1015-while-restoring-iphone-xs-max-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to fix error 1015 while restoring iPhone XS Max | Stellar</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-data-from-dead-iphone-14-plus-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to recover data from dead iPhone 14 Plus | Stellar</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-teleport-your-gps-location-on-samsung-galaxy-m34-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Samsung Galaxy M34? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-complete-guide-for-iphone-6s-lock-screen-by-drfone-ios/"><u>In 2024, Complete Guide For iPhone 6s Lock Screen</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-full-guide-on-mirroring-your-samsung-galaxy-a25-5g-to-your-pcmac-drfone-by-drfone-android/"><u>In 2024, Full Guide on Mirroring Your Samsung Galaxy A25 5G to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-oneplus-nord-n30-5gmirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can OnePlus Nord N30 5GMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-can-you-transfer-files-from-realme-c55-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How Can You Transfer Files From Realme C55 To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/larger-than-life-instagram-videos-tips-to-break-the-barrier-for-2024/"><u>Larger-than-Life Instagram Videos  Tips to Break the Barrier for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719335120399-python-package-installation/"><u>Python Package Installation:</u></a></li>
<li><a href="https://win11.techidaily.com/1719336618337-quick-fix-guide-overcome-incompatibility-in-windows-xp/"><u>Quick-Fix Guide: Overcome Incompatibility in Windows XP</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshooting-guide-fix-iphoneipad-keyboard-malfunctions/"><u>Troubleshooting Guide: Fix iPhone/iPad Keyboard Malfunctions</u></a></li>
</ul></div>
