---
title: Altering Windows Installation Process via Registry
date: 2024-08-15T23:17:13.404Z
updated: 2024-08-16T23:17:13.404Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Altering Windows Installation Process via Registry
excerpt: This Article Describes Altering Windows Installation Process via Registry
keywords: WinInstallRegChange,RegEditForWindows,WindowSetupKeyEdit,ModifyWinRegistry,AlteredWinInstReg,EditWinOSReg,WindowsSetupCustomization
thumbnail: https://thmb.techidaily.com/6afde60cdf2c4ed08818a0c3bb279e1893a9ceb4675945a4f5d57ab92e9d6ef9.jpg
---

## Altering Windows Installation Process via Registry

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
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Use Local Group Policy Editor

 You can also use the group policy editor to enable or disable the Windows Installer service on your Windows computer system. However, it is important to note that this tool only works on Windows Pro and Enterprise editions. Therefore, if you are using Windows Home Edition, you must first [activate the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 To disable the service using the group policy editor, do the following:

1. Click on Start and type in**gpedit.msc** , then press**Enter** to [launch the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) .
2. On the left side of the window, navigate to the path:  
`Computer Configuration > Administrative Templates > Windows Components > Windows Installer`
3. Now move to the right and double-click on the policy named**Turn off Windows Installer** .  
![Disable Windows Installer Service Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-group-policy.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
4. In the window that opens, select**Enabled** in the radio box.
5. Under Options, click the drop-down menu and select**Always** .
6. Then click**Apply** and**OK** to save changes.

 That's all there is to it. The Windows Installer service will now be disabled on your system. To re-enable it, simply follow the same steps, but set "Turn off Windows Installer" to**Not Configured** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Use the Registry Editor

 Registry Editor is another method you can use to enable or disable the Windows Installer service on any version of Windows, even Home Edition. But make sure to proceed with caution as any incorrect changes can corrupt your system and force you to reinstall Windows. So be mindful and remember to back up your registry before making any modifications.

 To enable or disable this service using Registry Editor, follow these steps:

1. Press**Win + X** , type**regedit** , and press**Enter** to launch the Registry Editor. To learn more, see our guide on how to [open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. If prompted with a UAC warning, click**Yes** to continue.
3. Now once you're in, navigate to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\msiserver`
4. In the right panel, double-click on**Start** and change its value from**2** to**4** .  
![Disable Windows Installer Service Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you put the Value data, make sure the Base is set to**Hexadecimal** , then click**OK** . Now close the registry editor and restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
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
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-10-fastest-growing-youtube-channels-to-inspire-you/"><u>[Updated] 2024 Approved  10 Fastest Growing YouTube Channels to Inspire You</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-cutting-edge-content-creation-mastering-how-to-trim-videos-in-real-time-on-vimeo/"><u>[Updated] In 2024, Cutting-Edge Content Creation  Mastering How to Trim Videos in Real Time on Vimeo</u></a></li>
<li><a href="https://games-able.techidaily.com/a-lifeline-to-unparalleled-indie-gaming-experiences-on-itchio/"><u>A Lifeline to Unparalleled Indie Gaming Experiences on Itch.io</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-blink-quick-fixes-for-input-lag-on-latest-microsoft-os/"><u>Beat the Blink: Quick Fixes for Input Lag on Latest Microsoft OS</u></a></li>
<li><a href="https://fox-access.techidaily.com/become-a-windows-pro-learn-to-trim-videos-like-an-editor/"><u>Become a Windows Pro  Learn to Trim Videos Like an Editor</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-generations-old-games-with-dosbox-x/"><u>Bridging Generations: Old Games with DOSBox-X</u></a></li>
<li><a href="https://win11.techidaily.com/determining-the-ideal-nearby-networking-method-google-vs-windows/"><u>Determining the Ideal Nearby Networking Method: Google Vs. Windows</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-and-fixing-the-frozen-resource-monitor-app-in-win11/"><u>Diagnosing and Fixing the Frozen Resource Monitor App in Win11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/discover-robust-strong-studiofx-softbox-glow/"><u>Discover Robust, Strong StudioFX Softbox Glow</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dodge-the-null-error-resolving-win11-problems/"><u>Dodge the Null Error: Resolving Win11 Problems</u></a></li>
<li><a href="https://win11.techidaily.com/enable-microphone-and-camera-via-app-guard-in-windows-11/"><u>Enable Microphone & Camera via App Guard in Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enhance-compatibility-boosting-mf4770n-performance-in-win11win8w7/"><u>Enhance Compatibility: Boosting MF4770n Performance in Win11/Win8/W7</u></a></li>
<li><a href="https://win11.techidaily.com/enrich-your-galaxy-experience-utilizing-the-dex-app-in-windows/"><u>Enrich Your Galaxy Experience: Utilizing the DeX App in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/esd-file-transformation-mastery-your-pathway-to-windows-iso-success/"><u>ESD File Transformation Mastery: Your Pathway to Windows ISO Success</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-absent-windows-notification-icons/"><u>Fixes for Absent Windows Notification Icons</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-an-application-not-installed-via-microsofts-store/"><u>Fixing an Application Not Installed via Microsoft's Store</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-installer-access-rights-shortcomings/"><u>Fixing Windows Installer Access Rights Shortcomings</u></a></li>
<li><a href="https://win11.techidaily.com/from-emulator-to-operating-system-windows-for-steam-deck/"><u>From Emulator to Operating System: Windows for Steam Deck</u></a></li>
<li><a href="https://win11.techidaily.com/keyboard-proficiency-the-path-to-mastering-project/"><u>Keyboard Proficiency: The Path to Mastering Project</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-adding-folders-without-delays-in-windows-onedrive/"><u>Mastering the Art of Adding Folders without Delays in Windows OneDrive</u></a></li>
<li><a href="https://win11.techidaily.com/preventive-measures-for-windows-safescreensaver-alteration/"><u>Preventive Measures for Windows SafeScreensaver Alteration</u></a></li>
<li><a href="https://win11.techidaily.com/reset-and-reboot-your-way-back-into-the-ms-store-windows-11/"><u>Reset & Reboot Your Way Back Into the MS Store (Windows 11)</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-htc-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock HTC Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://win11.techidaily.com/six-easy-steps-to-knowing-the-model-behind-your-pc-windows-edition/"><u>Six Easy Steps To Knowing The Model Behind Your PC Windows Edition</u></a></li>
<li><a href="https://vp-tips.techidaily.com/streamline-your-vlc-experience-best-practices-for-macos-for-2024/"><u>Streamline Your VLC Experience  Best Practices for MacOS for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tech-guide-uninstalling-the-microsoft-store/"><u>Tech Guide: Uninstalling the Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/terminal-insight-discover-public-ip-in-windows-1110/"><u>Terminal Insight: Discover Public IP in Windows 11/10</u></a></li>
<li><a href="https://fox-links.techidaily.com/the-ultimate-action-camera-test-xs-100-i-inside-story-for-2024/"><u>The Ultimate Action Camera Test - XS 100 I Inside Story for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/triumph-in-speed-mastering-double-click-on-windows-pc/"><u>Triumph in Speed: Mastering Double-Click on Windows PC</u></a></li>
</ul></div>
