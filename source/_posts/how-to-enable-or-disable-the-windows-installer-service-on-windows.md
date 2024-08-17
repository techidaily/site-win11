---
title: How to Enable or Disable the Windows Installer Service on Windows
date: 2024-08-16T00:43:36.832Z
updated: 2024-08-17T00:43:36.832Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Enable or Disable the Windows Installer Service on Windows
excerpt: This Article Describes How to Enable or Disable the Windows Installer Service on Windows
keywords: Windows Installer Control,Windows Setup Modifier,Disable Windows Servicer,Enable Windows Install,Installer Service Switch,Windows Installer Enable,Windows MSI Registration
thumbnail: https://thmb.techidaily.com/b458df85a4bb141857a3c4d2de6e35b07f50e405e5e03af8173f938324bb194b.png
---

## How to Enable or Disable the Windows Installer Service on Windows

 Are you looking for a way to disable the Windows Installer Service on your device? This essential component of your operating system performs all necessary installation processes, but can sometimes interfere with other programs.

 Fortunately, there are three ways in which it can be disabled—using the Windows Service tool, Group Policy Editor, or Registry Editor. Check out our guide below to learn how.

## 1\. Use Windows Services

 Windows services are critical programs that typically initiate when you start your computer. It runs silently in the background and provides essential features to run the operating system. If you're looking to enable or disable Windows Installer service using this tool, do the following.

 To begin, press**Win + R** on your keyboard to launch the Run dialog box. In the text box, type**services.msc** , and hit enter. This will open the Services window.

![Disable Windows Installer Service Using Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-services-window.jpg)

 In the window that opens, scroll down until you find**Windows Installer** service then double-click on it for a properties window to open.

 Once you're in the Properties window, click the**Startup type** drop-down menu and select**Automatic** . Now move over towards the**Service status** section and click**Stop** .

![Disable Windows Installer Service Using Windows Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-windows-services.jpg)

 After you've done that, click**Apply** and then**OK** to save the changes. You have now successfully disabled the Windows Installer service on Windows 11.

 If you ever need to re-enable the service, follow the same procedure and click**Start** in the Service status section.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Use Local Group Policy Editor

 You can also use the group policy editor to enable or disable the Windows Installer service on your Windows computer system. However, it is important to note that this tool only works on Windows Pro and Enterprise editions. Therefore, if you are using Windows Home Edition, you must first[activate the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 To disable the service using the group policy editor, do the following:

1. Click on Start and type in**gpedit.msc** , then press**Enter** to[launch the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) .
2. On the left side of the window, navigate to the path:  
`Computer Configuration > Administrative Templates > Windows Components > Windows Installer`
3. Now move to the right and double-click on the policy named**Turn off Windows Installer** .  
![Disable Windows Installer Service Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-group-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
4. In the window that opens, select**Enabled** in the radio box.
5. Under Options, click the drop-down menu and select**Always** .
6. Then click**Apply** and**OK** to save changes.

 That's all there is to it. The Windows Installer service will now be disabled on your system. To re-enable it, simply follow the same steps, but set "Turn off Windows Installer" to**Not Configured** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
## 3\. Use the Registry Editor

 Registry Editor is another method you can use to enable or disable the Windows Installer service on any version of Windows, even Home Edition. But make sure to proceed with caution as any incorrect changes can corrupt your system and force you to reinstall Windows. So be mindful and remember to back up your registry before making any modifications.

 To enable or disable this service using Registry Editor, follow these steps:

1. Press**Win + X** , type**regedit** , and press**Enter** to launch the Registry Editor. To learn more, see our guide on how to[open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. If prompted with a UAC warning, click**Yes** to continue.
3. Now once you're in, navigate to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\msiserver`
4. In the right panel, double-click on**Start** and change its value from**2** to**4** .  
![Disable Windows Installer Service Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-registry-editor.jpg)
<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you put the Value data, make sure the Base is set to**Hexadecimal** , then click**OK** . Now close the registry editor and restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## Turning Off the Windows Installer Service Made Easy

 If Windows Installer Service is creating issues or hindering another application, you can easily turn it off with one of the three methods outlined in our guide. See which method works best for you and get back to what matters most.


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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-mastering-google-meet-easy-backdrop-swap-for-pc-and-phones/"><u>[New] 2024 Approved  Mastering Google Meet  Easy Backdrop Swap for PC & Phones</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-the-ultimate-guide-to-live-streaming-on-facebook/"><u>[New] 2024 Approved  The Ultimate Guide to Live Streaming on Facebook</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-leveraging-built-in-recorders-on-mate-1020-and-p2010-series-to-screen-capture/"><u>[New] Leveraging Built-In Recorders on Mate 10/20 & P20/10 Series to Screen Capture</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-masters-building-marvels-virtual-horizons/"><u>[New] Masters Building Marvel's Virtual Horizons</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-in-2024-boosting-your-tiktok-following-a-selection-of-engaging-username-ideas/"><u>[Updated] In 2024, Boosting Your TikTok Following - A Selection of Engaging Username Ideas</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-understanding-the-meaning-of-facebooks-blue-emoji/"><u>[Updated] In 2024, Understanding the Meaning of Facebook's Blue Emoji</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-secret-to-striking-visuals-optimal-video-aspect-ratios/"><u>[Updated] The Secret to Striking Visuals  Optimal Video Aspect Ratios</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-ultimate-guide-to-drone-racers-and-top-5-fpv-drones/"><u>2024 Approved  Ultimate Guide to Drone Racers & Top 5 FPV Drones</u></a></li>
<li><a href="https://win11.techidaily.com/5-clear-signals-its-time-for-windows-reset/"><u>5 Clear Signals It's Time for Windows Reset</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-nubia-z50s-pro-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Nubia Z50S Pro</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-seamless-warhammer-gaming-on-windows-stop-stuttering/"><u>Achieving Seamless Warhammer Gaming on Windows: Stop Stuttering</u></a></li>
<li><a href="https://win11.techidaily.com/analyzing-surface-laptop-go-3-processor-boost-and-critique/"><u>Analyzing Surface Laptop Go 3: Processor Boost and Critique</u></a></li>
<li><a href="https://win11.techidaily.com/balancing-work-and-play-in-windows-11-schedules/"><u>Balancing Work and Play in Windows 11 Schedules</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-android-and-windows-gameplay-unification-with-google-play/"><u>Bridge Android and Windows: Gameplay Unification with Google Play</u></a></li>
<li><a href="https://tech-hub.techidaily.com/building-virtual-companionship-with-chatgpt-tips-and-tricks/"><u>Building Virtual Companionship with ChatGPT: Tips & Tricks</u></a></li>
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-xiaomi-mix-fold-3-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Xiaomi Mix Fold 3 | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-install-latest-sas-software-on-windows-11-8-or-7-free-updates/"><u>Download & Install Latest SAS Software on Windows 11, 8 or 7 - Free Updates</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-11-quality-over-novelties/"><u>Enhancing Windows 11: Quality over Novelties</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-winuac-new-techniques-for-administrators/"><u>Enhancing WinUAC: New Techniques for Administrators</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-to-run-the-sfc-tool-successfully/"><u>Essential Tips to Run the SFC Tool Successfully</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-updater-error-0x80246007-in-windows-versions-1011/"><u>Fixing Updater Error 0X80246007 in Windows Versions 10/11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/framemaster-hd-recording-suite/"><u>FrameMaster HD Recording Suite</u></a></li>
<li><a href="https://android-frp.techidaily.com/full-guide-to-bypass-motorola-razr-40-ultra-frp-by-drfone-android/"><u>Full Guide to Bypass Motorola Razr 40 Ultra FRP</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-nokia-c12-plus-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Nokia C12 Plus | Dr.fone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/how-to-create-and-grow-an-online-space-for-beauty-product-reviews/"><u>How To Create and Grow an Online Space for Beauty Product Reviews</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/o-maximize-video-reach-with-effective-tags-titles/"><u>How to Maximize Video Reach with Effective Tags, Titles</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-vivo-y100i-power-5g-to-mac-drfone-by-drfone-android/"><u>How to Mirror Vivo Y100i Power 5G to Mac? | Dr.fone</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-a-compreenas-guide-to-auto-and-advanced-camera-exposure-methods/"><u>In 2024, A Compreenas Guide to Auto and Advanced Camera Exposure Methods</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-oppo-a1-5g-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>In 2024, Does Oppo A1 5G Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-remove-or-bypass-knox-enrollment-service-on-oppo-reno-9a-by-drfone-android/"><u>In 2024, How To Remove or Bypass Knox Enrollment Service On Oppo Reno 9A</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-techniques-for-designing-and-extracting-your-own-mobile-tunes/"><u>In 2024, Techniques for Designing and Extracting Your Own Mobile Tunes</u></a></li>
<li><a href="https://win11.techidaily.com/incorporating-quick-access-tools-into-the-win11-taskbar-easily/"><u>Incorporating Quick Access Tools Into the Win11 Taskbar Easily</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-pristine-windows-image-display/"><u>Mastering the Art of Pristine Windows Image Display</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-the-not-responsive-window-software-problem/"><u>Mastery over the Not Responsive Window Software Problem</u></a></li>
<li><a href="https://win11.techidaily.com/microphone-missing-reclaim-your-voice-in-windows-google-meet/"><u>Microphone Missing? Reclaim Your Voice in Windows Google Meet</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-update-problem-with-error-0xca00a009/"><u>Mitigating Update Problem with Error 0xCA00A009</u></a></li>
<li><a href="https://win11.techidaily.com/must-know-factors-a-consumers-checklist-for-buying-a-win-laptop/"><u>Must-Know Factors: A Consumer's Checklist for Buying a Win Laptop</u></a></li>
<li><a href="https://win11.techidaily.com/notetaking-nirvana-mastering-visual-organization-in-obsidian/"><u>Notetaking Nirvana: Mastering Visual Organization in Obsidian</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/optimal-mp4-to-fb-video-solution-for-2024/"><u>Optimal MP4-to-FB Video Solution for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/overcoming-hurdles-how-to-get-davinci-resolve-working-again-on-your-pc-with-windows/"><u>Overcoming Hurdles: How to Get DaVinci Resolve Working Again on Your PC with Windows</u></a></li>
<li><a href="https://win11.techidaily.com/removing-default-homescreen-from-windows-11-setup/"><u>Removing Default Homescreen From Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-dism-failure-0x800f082f/"><u>Resolving Windows' DISM Failure 0X800F082F</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-stalled-email-notifications-in-windows-environment/"><u>Reviving Stalled Email Notifications in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-windows-experience-7-fixes-for-broken-apps/"><u>Seamless Windows Experience: 7 Fixes for Broken Apps</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-disabling-of-windows-11-alerts/"><u>Speedy Disabling of Windows 11 Alerts</u></a></li>
<li><a href="https://screen-recording.techidaily.com/step-by-step-guide-to-ken-burns-effect-with-camtasia-9-for-2024/"><u>Step-by-Step Guide to Ken Burns Effect with Camtasia 9 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-activating-newly-redesigned-widget-tool/"><u>Step-by-Step Guide: Activating Newly Redesigned Widget Tool</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-setting-up-dns-on-windows-11/"><u>Step-by-Step: Setting Up DNS on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-recognize-non-appearing-hdd/"><u>Strategies to Recognize Non-Appearing HDD</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-a-productive-win-11-taskbar/"><u>The Ultimate Guide to a Productive Win 11 Taskbar</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-messages-from-honor-90-gt-by-fonelab-android-recover-messages/"><u>The way to get back lost messages from Honor 90 GT</u></a></li>
<li><a href="https://win11.techidaily.com/top-4-techniques-for-mac-address-discovery-in-windows-11/"><u>Top 4 Techniques for Mac Address Discovery in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-pc-graphics-with-optimal-vram-settings/"><u>Transform Your PC Graphics with Optimal VRAM Settings</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-responsive-touchpad-gestures-on-windows/"><u>Troubleshooting Non-Responsive Touchpad Gestures on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-rpc-failures-with-ease/"><u>Troubleshooting Windows RPC Failures with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/turbo-windows-11-app-opening-secrets-revealed/"><u>Turbo Windows 11 App Opening Secrets Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-fixed-gif-sizes-in-discord-for-windows-11-users/"><u>Unraveling the Mystery of Fixed GIF Sizes in Discord (for Windows 11 Users)</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-navigating-the-best-8-free-audio-files-of-natural-rain-sounds-your-guide-for-2024/"><u>Updated Navigating the Best 8 Free Audio Files of Natural Rain Sounds - Your Guide for 2024</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-samsung-galaxy-s21-fe-5g-2023-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of Samsung Galaxy S21 FE 5G (2023) on Windows?</u></a></li>
<li><a href="https://win11.techidaily.com/windows-save-location-glitch-quick-guide/"><u>Windows Save Location Glitch: Quick Guide</u></a></li>
</ul></div>
