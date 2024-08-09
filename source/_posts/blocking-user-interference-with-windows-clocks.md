---
title: Blocking User Interference with Windows Clocks
date: 2024-08-08T13:16:03.355Z
updated: 2024-08-09T13:16:03.355Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Blocking User Interference with Windows Clocks
excerpt: This Article Describes Blocking User Interference with Windows Clocks
keywords: Block Time Changes,Secure Windows Hours,Prevent Clock Tampering,Lock Windows Calendar,Nocturnal Clock Control,Anti-Interference Windows,Untampered System Clocks
thumbnail: https://thmb.techidaily.com/bc22e110eacd1143aa0bdeeb05b2f88960a893ae5ff7866bf9fbfc4c2eddab7b.jpg
---

## Blocking User Interference with Windows Clocks

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
## 1\. Use the Group Policy Editor

 If your computer is part of an organization and users often change the date and time, use Group Policy Editor to stop it. This will prevent those with limited access to the computer from altering the date and time. However, this method only works for Windows Pro, Enterprise, or Education Editions.

 So, if you have Windows Home Edition, this won’t work. In that case, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). If it seems complicated, skip it and try the next solution instead.

 Follow these steps to prevent users from changing the date and time:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **gpedit.msc** in the text box and press Enter. This will open the Group Policy Editor window.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > System > Locale Services
4. In the right-side pane, double-click on **Disallow user override of locale settings**.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
![Disallow user override of locale settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disallow-user-override-of-locale-settings.jpg)
5. In the pop-up window, check the **Enabled** radio button.
6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Tweak the Registry Editor

 If you’re using Windows Home Edition or have disabled the Group Policy Editor, use the Registry Editor to protect date and time settings. This method is more advanced and has a higher risk of system damage.

 In that case, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it. Doing so will restore settings if something goes wrong.

 Follow these steps to stop users from changing the time and date via the registry:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the field and press Enter. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. In the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Software\Policies\Microsoft\Control Panel\International\
4. If the International folder doesn’t exist, create one. To do that, right-click on Control Panel and select **New** \> **Key**. Name it **International**.
5. Then right-click on **International** and select New > DWORD (32-bit) Value.
6. Name the newly created value **PreventUserOverrides**.
7. Double-click on the **PreventUserOverrides** DWORD value.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
![Use Registry Editor to Prevent Users From Chaning date and time settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-registry-editor-to-prevent-users-from-chaning-date-and-time-settings.jpg)
8. In the pop-up window, change the Value data to **1** and click **OK**.

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-step-up-your-gameplay-with-these-5-best-rated-ps2-android-emulators/"><u>[New] 2024 Approved  Step Up Your Gameplay with These 5 Best-Rated PS2 Android Emulators</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-a-new-era-advanced-webcam-techniques/"><u>[Updated] In 2024, A New Era  Advanced Webcam Techniques</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-the-aspiring-asmr-producers-guide-to-video-excellence/"><u>[Updated] In 2024, The Aspiring ASMR Producer's Guide to Video Excellence</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-voice-maestros-toolkit-free-applications-to-enrich-your-auditory-palette/"><u>2024 Approved  The Voice Maestro's Toolkit  Free Applications to Enrich Your Auditory Palette</u></a></li>
<li><a href="https://win11.techidaily.com/a-walkthrough-for-transferring-old-games-to-windows-gallery/"><u>A Walkthrough for Transferring Old Games to Windows Gallery</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-bluetooth-headphones-playing-sound-without-volume-control/"><u>Addressing Windows Bluetooth Headphones Playing Sound Without Volume Control</u></a></li>
<li><a href="https://win11.techidaily.com/awakening-the-veiled-query-power-in-windows-11/"><u>Awakening the Veiled Query Power in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-admins-rights-issue-in-win-os/"><u>Bypassing Admins Rights Issue in Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-group-policy-intricacies-through-gpresult/"><u>Deciphering Group Policy Intricacies Through GPResult</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-issue-code-0x80071a90/"><u>Decoding Windows Issue: Code 0X80071a90</u></a></li>
<li><a href="https://win11.techidaily.com/devhome-unveiled-a-deep-dive-into-w11s-core/"><u>DevHome Unveiled: A Deep Dive Into W11's Core</u></a></li>
<li><a href="https://win-amazing.techidaily.com/effortless-downloads-of-asus-display-drivers-get-started-now/"><u>Effortless Downloads of ASUS Display Drivers - Get Started Now</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-windows-steam-speed-eliminating-zero-downloads/"><u>Elevate Windows Steam Speed: Eliminating Zero-Downloads</u></a></li>
<li><a href="https://win11.techidaily.com/enhanced-energy-visibility-personalized-notifications-for-fully-charged-batteries-on-win11/"><u>Enhanced Energy Visibility: Personalized Notifications for Fully Charged Batteries on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-non-ad-focused-start-menu-win-11/"><u>Exclusive, Non-Ad Focused Start Menu Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-microsoft-ai-hub-features/"><u>Exploring Microsoft AI Hub Features</u></a></li>
<li><a href="https://win11.techidaily.com/file-compression-excellence-utilizing-cli-commands-in-windows/"><u>File Compression Excellence: Utilizing CLI Commands in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-mend-the-win-network-access-issue/"><u>How to Mend the WIN Network Access Issue</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-paste-issues-across-popular-browsers/"><u>How to Rectify Paste Issues Across Popular Browsers</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-revive-vanishing-steam-game-images/"><u>How to Revive Vanishing Steam Game Images</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-with-location-spoofer-on-honor-v-purse-drfone-by-drfone-virtual-android/"><u>How To Simulate GPS Movement With Location Spoofer On Honor V Purse? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-realme-11-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Realme 11 Pro? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/insights-into-procuring-freeness-in-frame-vids/"><u>Insights Into Procuring Freeness in Frame Vids</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-fix-bluetooth-attempt-error-in-windows/"><u>Mastering the Fix: Bluetooth Attempt Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-new-windows-11-taskbar-features/"><u>Mastering the New Windows 11 Taskbar Features</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-pcs-powertoys-10-essential-tips/"><u>Mastering Windows PCs: PowerToys' 10 Essential Tips</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/izing-video-moolah-anywhere-via-youtube-studios-tools-for-2024/"><u>Maximizing Video Moolah Anywhere via YouTube Studio's Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/nullify-non-compliance-notifications-in-win11/"><u>Nullify Non-Compliance Notifications in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/offline-process-for-extra-users-in-windows-11/"><u>Offline Process for Extra Users in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-mail-service-halt-fixing-0x800713f-in-win11/"><u>Overcoming Mail Service Halt: Fixing 0X800713F in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-admin-control-in-windows-os-security/"><u>Redefining Admin Control in Windows OS Security</u></a></li>
<li><a href="https://win11.techidaily.com/revitalizing-gpos-ensuring-compliance-on-modern-windows/"><u>Revitalizing GPOs: Ensuring Compliance on Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/scrutinizing-password-ingress-windows-pass-and-no-pass-outcomes/"><u>Scrutinizing Password Ingress: Windows Pass & No-Pass Outcomes</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-giants-how-facebook-stacks-up-against-twitter-instagram-and-youtube/"><u>Social Media Giants: How Facebook Stacks Up Against Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-spectrum-of-ai-analyzing-the-contrast-between-robust-strong-ai-and-basic-weak-ai/"><u>The Spectrum of AI: Analyzing the Contrast Between Robust (Strong) AI and Basic (Weak) AI</u></a></li>
<li><a href="https://win11.techidaily.com/top-desk-features-add-your-favorite-apps-to-the-taskbar/"><u>Top Desk Features: Add Your Favorite Apps to the Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/transitioning-heic-pictures-to-jpeg-in-w10w11/"><u>Transitioning HEIC Pictures to JPEG in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-responsive-windows-pin-entry/"><u>Troubleshooting Non-Responsive Windows PIN Entry</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-11-unresponsive-voice-commands/"><u>Troubleshooting Windows 11: Unresponsive Voice Commands</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-bt-folder-functionality/"><u>Understanding Windows ~BT Folder Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-importance-in-preserving-win-11-notifications/"><u>Unveiling the Importance in Preserving Win 11 Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-set-default-touch-input-placement/"><u>Win 11: Set Default Touch Input Placement</u></a></li>
<li><a href="https://win11.techidaily.com/yourdevice-link-assessing-risks-and-benefits-in-w10-systems/"><u>YourDevice Link - Assessing Risks and Benefits in W10 Systems</u></a></li>
</ul></div>
