---
title: Enhance Windows Connectivity with Telnet (Ways 3)
date: 2024-08-16T00:43:39.074Z
updated: 2024-08-17T00:43:39.074Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enhance Windows Connectivity with Telnet (Ways 3)
excerpt: This Article Describes Enhance Windows Connectivity with Telnet (Ways 3)
keywords: Windows Telnet Enhancement,Improve Win Connections,Optimize Windows Links,Boost Windows Net Access,Telnet for Better WINDOWS,Efficient WINDOWS Connect,Streamline Windows Networking
thumbnail: https://thmb.techidaily.com/8eeffb0e6f2c9998156198f379aca60dcf8cc0a8121a8e9ad6701616d8eaae16.jpg
---

## Enhance Windows Connectivity with Telnet (Ways 3)

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

## 1\. Enable Telnet on Windows Using Control Panel

 You can enable Telnet Client using the Classic Control Panel. Since it is an optional feature, you can enable it using the Windows Optional Feature dialog. You can use it[add or remove other users' optional features on Windows](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) .

To enable Telnet Client using Control Panel:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**
3. In Control Panel, Click on**Uninstall a Program** under**Programs and Features.**  
![turn windows features on or off control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/turn-windows-features-on-or-off-control-panel.jpg)
4. In the left pane, click on the**Turn Windows feature on or off.**  
![enable telnet client windows features dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-windows-features-dialog.jpg)
5. In the Windows Features dialog, scroll down and select**Telnet Client.**
6. Click**OK** and wait for the feature to install. Once installed, restart your PC to apply the changes and enable the feature.

If you need to disable Telnet:

1. Open the**Windows Features** dialog and unselect**Telnet Client.**
2. Click**OK** and wait for the feature to uninstall.
3. Click on**Restart** now to reboot your PC and apply the changes.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Enable Telnet Client Using Windows PowerShell

![enable telnet client powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-powershell.jpg)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can use the Enable-WindowsOptionalFeature cmdlet to enable Telnet Client using Windows PowerShell. Useful if you are unable to turn on the feature using the Windows Features dialog and it is also faster than the GUI method.

To enable Telnet using Windows PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal(Admin)** and click**Yes** to open the terminal app as administrator. If you are using Windows 10, type**PowerShell** in**Windows Search** and open**Windows PowerShell** administrator.
3. In the PowerShell window, type the following command and press**Enter** to enable Telnet:  
`Enable-WindowsOptionalFeature -Online -FeatureName TelnetClient`
4. This process may take several minutes, so wait for it to complete and return a status report. If successful, you’ll see the result as**Online:True.**
5. If you want to disable Telnet Client, use the following command instead:  
`Disable-WindowsOptionalFeature -Online -FeatureName TelnetClient`
6. Close PowerShell and restart your PC.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->

 If you prefer Command Prompt over PowerShell, you can use the DISM /Online command to enable the optional features on your Windows 11 computer.

Follow these steps to install Telnet using Command Prompt:

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command Prompt** and select**Run as administrator.**
3. In the Command Prompt window, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName:TelnetClient`
4. Command Prompt will start enabling the feature and display the operation completed successfully message.
5. If you need to disable Telnet, type the following command and press**Enter** :  
`dism /Online /Disable-Feature /FeatureName:TelnetClient`
6. Wait for the success message.
7. Type**exit** and press**Enter** to close Command Prompt.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## All the Ways to Enable Telnet On Your Windows 11 Computer

 Telnet is a built-in remote access utility that you can use to troubleshoot firewall and network issues. While it is still part of Windows, system administrators now prefer the more secure SSH protocol to access computers over an unsecured network.

 The major disadvantage of Telnet is that it is not secure and prone to a man-in-the-middle attack. If not for particular situations, switch to a more secure network protocol such as SSH and Mosh with better password and public key authentication.


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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-unlocking-full-potential-share-videos-on-fb-effectively/"><u>[New] 2024 Approved  Unlocking Full Potential  Share Videos on FB Effectively</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-5-ways-to-record-vr-gameplay-for-2024/"><u>[New] 5 Ways to Record VR Gameplay for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-determining-vertical-or-horizontal-video-posts-on-fb-for-2024/"><u>[New] Determining Vertical or Horizontal Video Posts on FB for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-screencasting-simplified-compreehd-step-by-step-guide/"><u>[New] In 2024, Screencasting Simplified  Compreehd, Step-by-Step Guide</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-securing-top-viewership-unveiling-the-hidden-power-of-youtubes-featured-channels/"><u>[New] Securing Top Viewership  Unveiling the Hidden Power of YouTube’s Featured Channels</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-what-happens-to-your-facebook-live-if-its-flagged-for-copyright/"><u>[New] What Happens to Your Facebook Live if It’s Flagged for Copyright?</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-anime-aesthetics-made-simple-using-snapchats-cartoon-style/"><u>[Updated] 2024 Approved  Anime Aesthetics, Made Simple  Using Snapchat's Cartoon Style</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-fiscal-horizons-exploring-mr-beasts-income/"><u>[Updated] Fiscal Horizons  Exploring Mr. Beast's Income</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-end-screen-design-made-easy-with-our-templates-and-tutorials/"><u>2024 Approved  End-Screen Design Made Easy with Our Templates & Tutorials</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-online-concert-for-a-click-music-and-memories/"><u>2024 Approved  Online Concert for a Click  Music and Memories</u></a></li>
<li><a href="https://win11.techidaily.com/7-personal-touches-for-windows-11s-search-engine/"><u>7 Personal Touches for Windows 11'S Search Engine</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-comprehensive-examination-of-lg-27ud68-display-tech-for-2024/"><u>A Comprehensive Examination of LG 27UD68 Display Tech for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-guide-to-windows-11-customization-techniques/"><u>A Detailed Guide to Windows 11 Customization Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/bios-tips-combatting-the-problem-of-grayed-out-secure-boot-on-windows/"><u>BIOS Tips: Combatting the Problem of Grayed-Out Secure Boot on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/cant-find-copilot-on-windows-11-heres-what-to-do/"><u>Can't Find Copilot on Windows 11? Here's What To Do</u></a></li>
<li><a href="https://win11.techidaily.com/close-all-easy-as-1-2-3-windows-multi-app-command/"><u>Close All, Easy as 1-2-3: Windows Multi-App Command</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-eliminating-wsl-from-win-11-pcs/"><u>Comprehensive Guide: Eliminating WSL From Win 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/craft-your-own-secure-windows-pin-with-custom-patterns/"><u>Craft Your Own Secure Windows PIN with Custom Patterns</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-windows-odbc-configuration-basics/"><u>Delving Into Windows ODBC Configuration Basics</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-airplane-mode-turn-off-gps-location-on-tecno-spark-20-proplus-drfone-by-drfone-virtual-android/"><u>Does Airplane Mode Turn off GPS Location On Tecno Spark 20 Pro+? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-way-to-relaunch-printer-service/"><u>Efficient Way to Relaunch Printer Service</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-art-with-top-win-11-sketch-tools/"><u>Elevate Your Art with Top Win 11 Sketch Tools</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-user-interface-with-fn-key-modifications/"><u>Enhancing User Interface with FN Key Modifications</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-window-11s-secure-browsing-graphically/"><u>Enhancing Window 11'S Secure Browsing Graphically</u></a></li>
<li><a href="https://win11.techidaily.com/essentials-for-enabling-win11-on-5ghz-networks-effortlessly/"><u>Essentials for Enabling Win11 on 5GHz Networks Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/expert-insights-for-captivating-images-and-memorable-slideshows-in-win11s-photography-platform/"><u>Expert Insights for Captivating Images and Memorable Slideshows in Win11's Photography Platform</u></a></li>
<li><a href="https://howto.techidaily.com/fix-cant-take-screenshot-due-to-security-policy-on-vivo-x-fold-2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Cant Take Screenshot Due to Security Policy on Vivo X Fold 2 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-screen-hurdle-sonic-frontiers-win-on-w11/"><u>Fixing the Screen Hurdle: Sonic Frontiers Win on W11</u></a></li>
<li><a href="https://win11.techidaily.com/hiding-windows-11-taskbar-avoid-the-search/"><u>Hiding Windows 11 Taskbar: Avoid the Search</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-grant-permission-on-hidden-outlook-files-and-directories/"><u>How to Grant Permission on Hidden Outlook Files and Directories</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-essential-elements-error-on-win11win11/"><u>How to Rectify Essential Elements Error on Win11/Win11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-comparative-study-samsung-vs-traditional-photo-tools/"><u>In 2024, Comparative Study  Samsung vs Traditional Photo Tools</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-stream-anything-from-realme-gt-neo-5-se-to-apple-tv-drfone-by-drfone-android/"><u>In 2024, How To Stream Anything From Realme GT Neo 5 SE to Apple TV | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/insights-into-a-common-icon-what-is-fbs-blue-video-symbol/"><u>Insights Into a Common Icon  What Is FB’s Blue Video Symbol?</u></a></li>
<li><a href="https://win11.techidaily.com/key-practices-in-the-pursuit-of-a-pristine-windows-setup/"><u>Key Practices in the Pursuit of a Pristine Windows Setup</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/lenovos-latest-gem-a-detailed-review-of-the-thinkpad-x1-titanium-yoga-perfectly-blending-tradition-and-innovation/"><u>Lenovo's Latest Gem: A Detailed Review of the ThinkPad X1 Titanium Yoga, Perfectly Blending Tradition and Innovation</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-fix-directx-file-downloads/"><u>Methods to Fix DirectX File Downloads</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-ftdibussys-why-it-compromises-windows-memory/"><u>Navigating ftdibus.sys: Why It Compromises Windows Memory</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-restrictions-disabling-signatures-adding-unsigned-drivers/"><u>Navigating Windows' Restrictions: Disabling Signatures, Adding Unsigned Drivers</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-hits-of-the-airwaves-the-best-radio-sounds-for-2024/"><u>New Hits of the Airwaves The Best Radio Sounds for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-chrome-for-smooth-youtube-streaming/"><u>Optimizing Chrome for Smooth YouTube Streaming</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-limited-use-of-chatgpt-in-pc/"><u>Optimizing Limited Use of ChatGPT in PC</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-alt-code-not-responding-on-windows-pc/"><u>Overcoming ALT Code Not Responding on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/phoenix-rise-revive-gaming-pcs-with-atlasos/"><u>Phoenix Rise: Revive Gaming PCs with AtlasOS</u></a></li>
<li><a href="https://win11.techidaily.com/privacy-hacked-no-more-winning-encryption-tools-ranked-149-chars/"><u>Privacy Hacked No More: Winning Encryption Tools Ranked (149 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/quick-resolution-for-windows-dism-failure-code-0x800f082f/"><u>Quick Resolution for Windows' DISM Failure Code: 0X800F082F</u></a></li>
<li><a href="https://win11.techidaily.com/re-engaging-with-ms-store-a-stepwise-approach-to-windows-pcs/"><u>Re-Engaging with MS Store: A Stepwise Approach to Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/rejuvenating-inactive-recycle-bin-icon-on-win11/"><u>Rejuvenating Inactive Recycle Bin Icon on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-game-hub-error-code-0x800700e9-on-microsoft-devices/"><u>Resolving Game Hub Error Code 0X800700E9 on Microsoft Devices</u></a></li>
<li><a href="https://win11.techidaily.com/revitalize-your-pc-display-interactive-and-lively-windows-11-walls/"><u>Revitalize Your PC Display: Interactive and Lively Windows 11 Walls</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-operation-warhammer-40k-boltgun-windows-stutter-fixes/"><u>Smooth Operation Warhammer 40K Boltgun: Windows Stutter Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-experience-microsoft-store-file-types-msixbundle/"><u>Streamline Your Experience: Microsoft Store File Types (MSixBundle)</u></a></li>
<li><a href="https://win11.techidaily.com/the-windows-bar-evolution-story-1985present/"><u>The Windows Bar Evolution Story (1985–Present)</u></a></li>
<li><a href="https://win11.techidaily.com/triggering-driver-verifier-on-windows-11-pc/"><u>Triggering Driver Verifier on Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-heat-in-windows-11-pcs/"><u>Troubleshooting Heat in Windows 11 PCs</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unleash-your-creativity-the-leading-phone-apps-for-image-stickers-for-2024/"><u>Unleash Your Creativity  The Leading Phone Apps for Image Stickers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-global-scripts-a-windows-font-guide/"><u>Unleashing Global Scripts: A Windows Font Guide</u></a></li>
<li><a href="https://win11.techidaily.com/window-lockscreen-tips-engage-or-mute-spotlight-images/"><u>Window Lockscreen Tips: Engage or Mute Spotlight Images</u></a></li>
</ul></div>
