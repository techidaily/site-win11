---
title: Troubleshooting WinMedia Server Error
date: 2024-08-16T00:31:57.221Z
updated: 2024-08-17T00:31:57.221Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting WinMedia Server Error
excerpt: This Article Describes Troubleshooting WinMedia Server Error
keywords: WmsError Troubleshoot,WinMdServer Fix Errors,Resolve WMSError,WinMedia Server Err,Windows Media Server Troubleshooting,WinMdServer Problem-Solving,WMSError Diagnosis Steps
thumbnail: https://thmb.techidaily.com/ac6fcc85e0fde61250c72c7455cdeba283035fd7fed1fa3496121c2d71b4b3d4.jpg
---

## Troubleshooting WinMedia Server Error

 Windows Media Player is old software, but many users still utilize it for playing music and video. However, some WMP users have reported a “server execution failed” error message pops up when they try to play media files in Windows Media Player. Consequently, users can’t listen to music or watch videos in Windows Media Player.

 Windows Media Player isn’t much good when it doesn’t play music or video. There are plenty of alternative media players, but you don’t have to ditch WMP because of the “server execution failed” error. This is how you can fix the “server execution failed” error.

## 1\. Try Restarting the Windows Media Player Process

 Some WMP users have confirmed that ending the Windows Media Player process in Task Manager can fix the “Server execution failed” error. That’s a very simple potential resolution that amounts to little more than restarting the software, albeit via Task Manager. You can end the Windows Media Player process in Task Manager like this:

1. Open Task Manager by simultaneously pressing the **Ctrl** \+ **Shift** \+ **Esc** key combination for launching that utility.
2. Click **Processes** to view that tab if it doesn’t open with Task Manager.
3. Select the **Windows Media Player** process in Task Manager.  
![The Processes tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-process-tab.jpg)
4. Press the **End task** button to terminate the selected WMP process.
5. Then exit Task Manager and open Windows Media Player to see if the error persists.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## 2\. Run the Video Playback Troubleshooter

 Windows 11 and 10 both include a Video Playback troubleshooter that might be useful for resolving the “Server execution failed” error. That’s a troubleshooter for resolving video playback issues, and some users have said it helped them fix this issue. These are the steps for running the Video Playback troubleshooting tool:

1. First, [bring up Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) the quick way by holding the **Windows** logo key and pressing **I**.
2. Then select **System** and the **Troubleshoot** navigation option included within that tab.
3. Click **Other trouble-shooters** to proceed to a list of troubleshooting utilities.
4. Open the Video Playback troubleshooter by clicking its **Run** option.  
![The Run button for the Video Playback troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-video-playback-troubleshooter.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
5. Select **I want to continue** **with this troubleshooter** in Video Playback.  
![The Video Playback troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/video-playback-troubleshooter.jpg)
6. Apply any possible fixes the Video Playback troubleshooter offers.

 To utilize the same Video Playback troubleshooter in Windows 10, select the Update & Security settings category. Then you can reach the Video Playback repair utility by selecting **Troubleshoo**t > **Additional troubleshooters**. Select Video Playback and click **Run the troubleshooter**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## 3\. Register DLL Files

 Registering the jscript and vbscript DLL files is a widely confirmed fix for the “Server execution failed” error. You can register those files by executing a couple of simple regsvr commands like this:

1. [Open Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/#:~:text=In%20the%20Run%20dialog%20box,Command%20Prompt%20with%20administrative%20privileges.) to utilize that app with elevated privileges.
2. Then input this regsvr command and hit **Enter**: regsvr32 jscript.dll  
![The regsvr32 jscript.dll](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-regsvr32-command.jpg)
3. Click **OK** on RegSvr32 confirmation box.
4. Next, execute this command to register the VBScript file: regsvr32 vbscript.dll  
![The regsvr32 vbscript.dll command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-regsver32-vbscript-command.jpg)
<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Then select **OK** again.
6. Go to your Start menu and select **Restart** from there.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
## 4\. Disable the Windows Media Player Network Sharing Service

 Windows Media Player Network Sharing is a service required for sharing WMP libraries via the UPnP protocol. That’s not a service needed for playing media files on one PC, and some WMP users have fixed the “Server execution failed” error by disabling that service. This is how you can disable that service:

1. Click on the taskbar’s magnifying glass icon or search box.
2. Enter a **services** keyword to find the app that matches that search phrase.
3. Run Services by clicking that app within your search results.
4. Double-click **Windows Media Player Network Sharing** to access that service’s property settings.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-services-window2.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Select the **Disabled** option on the **Startup** menu.  
![The Disabled option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-disabled-option.jpg)
6. Click **Stop** just below the **Startup type** menu.
7. Select **Apply** \> **OK** to save settings and exit the Windows Media Player Network Sharing Service Properties window.

## 5\. Apply Full Access to Your Local User Folder

 Another possibility is that Windows Media Player can’t access media files in your user folder because of permission changes. Re-establishing full access to your local user folder will resolve such an issue. These are the steps for applying full access to a user folder:

1. [Open File Explorer](https://www.makeuseof.com/windows-open-file-explorer/) and go to the following folder path:  
`C:\Users`
2. Right-click your user folder that includes media files and select **Properties**.  
![The Properties context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/properties-option.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
3. Select **Security** on the properties window.
4. Click **Advanced** to bring up more security settings.
5. Next, click the **Change** option for the owner.  
![The Advanced Security Settings for Users window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/advanced-security-window.jpg)

1. Click **Advanced** \> **Find now** on the Select User or Group window.
2. Then choose your user account from there and click **OK** twice.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/select-user-or-group.jpg)
<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Press **Add** on the Advanced Security Settings window.
4. Click **Select a Principal** to bring up a user group selection window.
5. Select your user account again, as covered in steps six and seven.
6. Click the **Full control** checkbox to select that basic permission setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-full-control-option.jpg)
7. Select **OK** on the Permissions Entry window and others open.

## 6\. Disable Third-Party Startup Items

 Disabling all third-party startup items (apps and services) is called clean booting. The purpose of clean booting is to prevent software conflicts by stopping third-party background programs and services from starting automatically. This troubleshooting method is recommended to check if a third-party app or service conflict with Windows Media Player is causing the “Server execution failed” error on your PC.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/services-tab-in-msconfig.jpg)

 Our guide to [clean-booting Windows](https://www.makeuseof.com/clean-boot-windows-11/) tells you how to apply this potential fix by disabling third-party apps and services with Task Manager and MSConfig. When you’ve done that, you’ll need to restart your PC open for a clean boot to take effect. Then open Windows Media Player and try playing some media files again.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 7\. Reinstall Windows Media Player

 Reinstalling Windows Media Player is a last resort potential resolution to try if none of the above works for you. However, you can’t reinstall WMP like regular software by uninstalling with Programs and Features and downloading a setup file. Instead, you’ll need to disable and re-enable WMP via Windows Features as follows:

1. Bring up the Windows uninstaller tool with a method within this article about [how to open Programs and Features](https://www.makeuseof.com/windows-open-programs-and-features-tool/).
2. Then click **Turn Windows features on or off** to bring up a utility for enabling/disabling features.  
![Programs and Features Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/programs-and-features-window.jpg)
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Double-click Media Features to extend it.
4. Deselect the **Windows Media Player** checkbox and select **Yes**.  
![The Windows Media Player checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-windows-media-player-checkbox.jpg)
5. Click **OK** to disable Windows Media Player.
6. Restart Windows after disabling WMP.
7. Then reopen the Windows Features window.
8. Select the **Windows Media Player** checkbox.
9. Click **OK** to reinstall the software.

## Enjoy Your Music and Videos in Windows Media Player

 Many WMP users have fixed the “Server execution failed” error with the potential solutions outlined in this guide. So, don’t ditch Windows Media Player until you’ve at least tried applying most of those potential fixes. One will probably get the “Server execution failed” WMP error fixed on your Windows PC. Then you can enjoy all the music and videos in your Windows Media Player playlists again.

 Nevertheless, there are still plenty of freely available alternatives to Windows Media Player you can always consider. Software like VLC, 5KPlayer, and KMPlayer are among the best freeware media players for Windows.

 Windows Media Player isn’t much good when it doesn’t play music or video. There are plenty of alternative media players, but you don’t have to ditch WMP because of the “server execution failed” error. This is how you can fix the “server execution failed” error.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-tips.techidaily.com/new-beijings-frost-touched-games-highlights-from-2022/"><u>[New] Beijing's Frost-Touched Games, Highlights From 2022</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-capture-your-pc-hp-laptop-screen-recording-guide-for-2024/"><u>[New] Capture Your PC  HP Laptop Screen Recording Guide for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-essential-insights-how-to-choose-among-the-top-9-free-youtube-makers/"><u>[Updated] In 2024, Essential Insights  How to Choose Among the Top 9 Free YouTube Makers</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-nubia-red-magic-8s-proplus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On Nubia Red Magic 8S Pro+ | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-cmd-skills-with-these-20-must-learn-commands/"><u>Boost Your CMD Skills with These 20 Must-Learn Commands</u></a></li>
<li><a href="https://screen-recording.techidaily.com/camtasia-9-unlock-the-art-of-ken-burns-easing/"><u>Camtasia 9  Unlock the Art of Ken Burns Easing</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-pc-hardware-mismatch-in-windows-captures/"><u>Correcting PC Hardware Mismatch in Windows Captures</u></a></li>
<li><a href="https://win11.techidaily.com/creating-harmony-between-android-tablets-and-windows-11-desktops/"><u>Creating Harmony Between Android Tablets and Windows 11 Desktops</u></a></li>
<li><a href="https://win11.techidaily.com/dual-display-designs-crafting-individual-monitor-ambiance-in-win-1011/"><u>Dual Display Designs: Crafting Individual Monitor Ambiance in WIN 10/11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/essential-hashtag-strategies-on-instagram-for-boosting-your-posts/"><u>Essential Hashtag Strategies on Instagram for Boosting Your Posts</u></a></li>
<li><a href="https://facebook.techidaily.com/fbs-commitment-to-privacy-when-will-we-see-encrypted-chats/"><u>FB's Commitment to Privacy: When Will We See Encrypted Chats?</u></a></li>
<li><a href="https://win11.techidaily.com/finding-the-absent-hypervisor-fix-for-xc0351000-error/"><u>Finding the Absent Hypervisor - Fix for XC0351000 Error</u></a></li>
<li><a href="https://win11.techidaily.com/from-here-to-innovation-the-post-11-windows-journey/"><u>From Here to Innovation: The Post-11 Windows Journey</u></a></li>
<li><a href="https://youtube-help.techidaily.com/gain-control-over-yt-calls-start-gs-focused-for-2024/"><u>Gain Control Over YT Calls, Start GS-Focused for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-access-and-use-windows-11s-home-space/"><u>How to Access and Use Windows 11'S Home Space</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bridge-the-disconnect-gap-windows-11-and-printers/"><u>How to Bridge the Disconnect Gap: Windows 11 & Printers</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-can-i-bypass-a-forgotten-phone-password-of-itel-p55plus-by-drfone-android/"><u>In 2024, Can I Bypass a Forgotten Phone Password Of Itel P55+?</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-real-time-tips-to-dominate-twitter-broadcasts/"><u>In 2024, Real-Time Tips to Dominate Twitter Broadcasts</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-your-itel-p55ts-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>In 2024, Unlock Your Itel P55Ts Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-is-a-sim-network-unlock-pin-get-your-samsung-galaxy-m34-5g-phone-network-ready-by-drfone-android/"><u>In 2024, What Is a SIM Network Unlock PIN? Get Your Samsung Galaxy M34 5G Phone Network-Ready</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-look-at-windows-11-admin-interface/"><u>In-Depth Look at Windows 11 Admin Interface</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-service-failures-fixing-steam-errors-on-windows-11/"><u>Mastery Over Service Failures: Fixing Steam Errors on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/modifying-the-primary-web-portal-on-w11/"><u>Modifying the Primary Web Portal on W11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-the-0x80860010-a-guide-to-fixes-for-windows/"><u>Navigating Through The 0X80860010: A Guide to Fixes for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-your-windows-photo-workflow-with-keys/"><u>Optimizing Your Windows Photo Workflow with Keys</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-your-hover-over-sensitivity-and-trail-in-windows-11/"><u>Perfect Your Hover Over Sensitivity and Trail in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/prevent-non-genuine-adobe-app-warning/"><u>Prevent Non-Genuine Adobe App Warning</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-external-access-to-insider-developer-sets/"><u>Preventing External Access to Insider Developer Sets</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/refurbished-apple-iphone-13-mini-everything-you-need-to-know-drfone-by-drfone-transfer-from-ios/"><u>Refurbished Apple iPhone 13 mini Everything You Need to Know | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-functionality-to-missing-phone-link-notifications-on-pc/"><u>Restoring Functionality to Missing Phone Link Notifications on PC</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-add-on-of-portable-software-to-windows-oses/"><u>Seamless Add-On of Portable Software to Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-limit-microsoft-edge-processes/"><u>Strategies to Limit Microsoft Edge Processes</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/the-best-methods-to-unlock-the-iphone-locked-to-owner-for-apple-iphone-x-drfone-by-drfone-ios/"><u>The Best Methods to Unlock the iPhone Locked to Owner for Apple iPhone X | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/the-comprehensive-blueprint-for-capturing-whatsapp-calls/"><u>The Comprehensive Blueprint for Capturing WhatsApp Calls</u></a></li>
<li><a href="https://fox-blue.techidaily.com/the-ultimate-guide-to-theta-s-features/"><u>The Ultimate Guide to Theta S Features</u></a></li>
<li><a href="https://driver-install.techidaily.com/the-ultimate-guide-to-usb-mouse-drivers-renewal/"><u>The Ultimate Guide to USB-Mouse Drivers Renewal</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-tablets-enhancing-user-experience-with-a-taskbar/"><u>Windows 11 Tablets: Enhancing User Experience with a Taskbar</u></a></li>
</ul></div>
