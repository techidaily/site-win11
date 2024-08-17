---
title: Addressing Faulty Timed Lock Screen Issue Windows
date: 2024-08-15T23:19:26.703Z
updated: 2024-08-16T23:19:26.703Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Faulty Timed Lock Screen Issue Windows
excerpt: This Article Describes Addressing Faulty Timed Lock Screen Issue Windows
keywords: Fix Window Lock Delay,Solve Timeout Windows,Quick Windows Lock Resolve,Unlock Windows Timelock,Eradicate LockScreen Error,Windows Screen Time Fix,Eliminate LockTimeout Issue
thumbnail: https://thmb.techidaily.com/2a48b2247fe4fccf62c26b321b73686dd63d342e88315635def6454749492ddb.jpg
---

## Addressing Faulty Timed Lock Screen Issue Windows

 Have you ever left your computer unattended for a while, only to return and find that it was still unlocked? Several users have reported problems getting their Windows computers to lock automatically after a certain period of inactivity.

 To help out, we have listed some useful tips that should get the lock screen timeout to work on your Windows 10 or 11 PC.

## 1\. Check Screen Timeout Settings

 Before we get to any advanced troubleshooting tips, it’s a good idea to double-check the screen timeout settings on Windows. Here are the steps for the same.

1. Press **Win + I** to open the Settings app.
2. Navigate to **System > Power & battery**.
3. Click on **Screen and sleep** to expand it.
4. Click the drop-down menus next to **On battery power, turn off my screen after** and **When plugged in, turn off my screen after** to select your preferred timeout.  
![Screen and Sleep Settings in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/screen-and-sleep-settings-in-windows.jpg)

 After setting your preferred timeout, observe if Windows locks your PC after the specified period.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
## 2\. Configure Screen Saver Settings

 Incorrectly configured screen saver settings on Windows can also be the cause of this issue. Here's how you can configure Windows to display the lock screen after you resume from a screensaver.

1. Press **Win + S** to open the search menu.
2. Type **change screen saver** in the box and select the first result that appears.
3. In the Screen Saver Settings window, set the preferred wait time.
4. Tick the **On resume, display logon screen** checkbox.
5. Hit **Apply** followed by **OK**.  
![Screen Saver Settings on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/screen-saver-settings-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->

 Once you complete the above steps, Windows should lock your system once the screen saver activates.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
## 3\. Check Screen Saver Settings in the Local Group Policy

 If the issue remains even after you configure the screen saver settings, you will need to check the policies related to the screen saver and make sure they are configured correctly.

 As you may be aware, the Local Group Policy Editor is only available on Windows Pro, Enterprise, and Education editions. However, if you are using the Home edition, you can use a workaround to [access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To modify group policies related to screen saver, use these steps:

1. Press **Win + R** to open the Run dialog box.
2. Type **gpedit.msc** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **User Configuration > Administrative Templates > Control Panel > Personalization**.
5. Double-click the **Enable Screen Saver** policy on your right.
6. Select the **Enabled** option.
7. Hit **Apply** and then click **OK**.
8. Similarly, enable the **Password protect the screen saver** policy as well.  
![Password Protect Screen Saver Policy in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/password-protect-screen-saver-policy-in-group-policy-editor.jpg)
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

 Restart your PC after applying the above changes and check if the issue is still there.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Other Generic Fixes to Try

 If the above solutions do not work, you can try some generic Windows fixes to get the lock screen timeout working on Windows.

* **Disconnect External Devices:** It is possible that an external device connected to your system is keeping Windows awake. To test this, disconnect all external devices and see if the problem persists.
* **Reset Your Power Plan:** Issues with the power plan settings could also cause such problems. To fix this, you can try [resetting the power plan to default on Windows](https://www.makeuseof.com/reset-power-plans-to-default-in-windows/).
* **Install Windows Updates:** It's possible that the lock screen timeout problem is occurring due to a bug within the Windows build your PC is running. If that's the case, [installing Windows updates](https://www.makeuseof.com/update-windows-manually/) should help.
* **Try a Clean Boot:**[Performing a clean boot on Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/) can help you determine whether a third-party program or service is causing issues with the lock screen timeout. Once you find the problematic program, consider removing it from your system to avoid such issues in the future.
* **Perform a System Restore:** If the issue has only started occurring recently, you can [perform a system restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) to undo recent changes and fix the problem.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get the Lock Screen Timeout Working Again on Windows

 When the lock screen timeout fails to work as expected, it can potentially put your Windows computer at risk. Hopefully, one or more of the above tips have helped you solve the problem and you are at peace.

 To help out, we have listed some useful tips that should get the lock screen timeout to work on your Windows 10 or 11 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-film-fanatics-dream-the-ultimate-list-of-free-movies-streaming-on-youtube/"><u>[New] 2024 Approved  Film Fanatics' Dream – The Ultimate List of Free Movies Streaming on YouTube</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-in-depth-analysis-the-powerhouse-that-is-dji-phantom-3/"><u>[Updated] In-Depth Analysis  The Powerhouse That Is DJI Phantom 3</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-transform-everyday-alerts-into-signature-sounds-with-android-tips/"><u>[Updated] Transform Everyday Alerts Into Signature Sounds with Android Tips</u></a></li>
<li><a href="https://win11.techidaily.com/10-quick-tips-recognizing-your-xbox-controller-in-windows/"><u>10 Quick Tips: Recognizing Your Xbox Controller in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/10-substitutes-for-bitlocker-in-winxp-systems/"><u>10 Substitutes for BitLocker in WinXP Systems</u></a></li>
<li><a href="https://win11.techidaily.com/10-trusted-secure-windows-software-download-spots/"><u>10 Trusted, Secure Windows Software Download Spots</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-mastering-visual-storytelling-with-online-wallpaper-swap/"><u>2024 Approved  Mastering Visual Storytelling with Online Wallpaper Swap</u></a></li>
<li><a href="https://win11.techidaily.com/27-tips-for-personalizing-your-windows-11-experience/"><u>27 Tips for Personalizing Your Windows 11 Experience</u></a></li>
<li><a href="https://win11.techidaily.com/5-effective-ways-to-manipulate-image-size-on-windows-11/"><u>5 Effective Ways to Manipulate Image Size on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-fix-the-network-security-key-mismatch-error-on-windows-11/"><u>5 Ways to Fix the Network Security Key Mismatch Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensible-guide-for-reactivating-windows-photo-viewer-in-win11/"><u>A Comprehensible Guide for Reactivating Windows Photo Viewer in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/a-practical-approach-to-revamping-group-policy-settings/"><u>A Practical Approach to Revamping Group Policy Settings</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-update-speed-of-task-monitor-win-11/"><u>Accelerate Update Speed of Task Monitor Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-windows-tasks-with-top-5-car-drivers/"><u>Accelerate Windows Tasks with Top 5 Car Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/access-windows-greatness-through-microsoft-store/"><u>Access Windows Greatness Through Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-accelerated-troubleshooting-in-w11-interface/"><u>Accessing Accelerated Troubleshooting in W11 Interface</u></a></li>
<li><a href="https://win11.techidaily.com/adding-a-functional-system-update-alert-in-win11-pro/"><u>Adding a Functional System Update Alert in Win11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-excessive-memory-use-by-edges-view2-process/"><u>Addressing Excessive Memory Use by Edge's View2 Process</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-faulty-sound-controls-in-windows-os/"><u>Addressing Faulty Sound Controls in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-game-bar-issues-due-to-subpar-pcs/"><u>Addressing Game Bar Issues Due to Subpar PCs</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-displaying-notifications-of-phone-link-app-on-pc/"><u>Addressing Non-Displaying Notifications of Phone Link App on PC</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-utorrents-non-functionality-on-pc-systems/"><u>Addressing uTorrent's Non-Functionality on PC Systems</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-sam-mismanagement/"><u>Addressing Windows SAM Mismanagement</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-network-settings-with-precision-win11/"><u>Adjusting Network Settings with Precision (Win11)</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tactics-in-managing-windows-startup-procedures/"><u>Advanced Tactics in Managing Windows Startup Procedures</u></a></li>
<li><a href="https://win11.techidaily.com/alleviating-high-cpu-demands-in-setups/"><u>Alleviating High CPU Demands in Setups</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-the-implications-of-device-isolation-on-windows-audio/"><u>Assessing the Implications of Device Isolation on Windows Audio</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-0x0-failure-in-win11-setup-procedures/"><u>Avoid 0X0 Failure in Win11 Setup Procedures</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-no-more-space-on-windows-oses/"><u>Avoiding 'No More Space' On Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-slowness-essential-tricks-for-windows-11s-pace/"><u>Beat the Slowness: Essential Tricks for Windows 11'S Pace</u></a></li>
<li><a href="https://win11.techidaily.com/beware-the-traps-in-budget-friendly-windows-license-purchases/"><u>Beware the Traps in Budget-Friendly Windows License Purchases</u></a></li>
<li><a href="https://win11.techidaily.com/block-unwanted-startup-stop-snipping-tool-from-prtscan-on-win-11/"><u>Block Unwanted Startup: Stop Snipping Tool From PrtScan on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-efficiency-navigating-windows-11s-disk-management-quickly/"><u>Boost Efficiency: Navigating Windows 11'S Disk Management Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-system-tray-displaying-cpu-and-memory-usage/"><u>Boosting System Tray: Displaying CPU & Memory Usage</u></a></li>
<li><a href="https://win11.techidaily.com/1719265441814-change-power-saving-settings-adjust-the-screen-brightness-on-battery-saver-by-tweaking-the-power-plans-in-system-settings/"><u>Change Power Saving Settings: Adjust the Screen Brightness on Battery Saver by Tweaking the Power Plans in 'System Settings'</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/forgot-iphone-passcode-again-unlock-iphone-13-without-passcode-now-by-drfone-ios/"><u>Forgot iPhone Passcode Again? Unlock iPhone 13 Without Passcode Now</u></a></li>
<li><a href="https://tech-revival.techidaily.com/gpt-4-and-copilot-unite-revolutionize-your-tech-skills-for-free/"><u>GPT-4 and Copilot Unite: Revolutionize Your Tech Skills for Free!</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-change-country-on-app-store-for-apple-iphone-12-with-7-methods-drfone-by-drfone-ios/"><u>How To Change Country on App Store for Apple iPhone 12 With 7 Methods | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-a-comprehensive-guide-to-thumbnail-production/"><u>In 2024, A Comprehensive Guide to Thumbnail Production</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-fantasy-forays-a-decades-best-games/"><u>In 2024, Fantasy Forays  A Decade’s Best Games</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-xiaomi-redmi-note-12-5g-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Xiaomi Redmi Note 12 5G to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-infinix-hot-30i-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For Infinix Hot 30i Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-cab-files-usage-and-installation-insights/"><u>Mastering Windows CAB Files: Usage and Installation Insights</u></a></li>
<li><a href="https://win11.techidaily.com/1719251209823-overcome-wwinplusprint-hurdles-for-seamless-operations-in-windows/"><u>Overcome WWin+Print Hurdles for Seamless Operations in Windows.</u></a></li>
<li><a href="https://win11.techidaily.com/1719345925022-the-forgotten-tools-of-windows-11-dont-miss-them/"><u>The Forgotten Tools of Windows 11 - Don’t Miss Them</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-best-spy-watches-for-your-vivo-v29e-drfone-by-drfone-virtual-android/"><u>Top 10 Best Spy Watches For your Vivo V29e | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719281206376-win11-printer-woes-solutions-here/"><u>Win11 Printer Woes? Solutions Here!</u></a></li>
</ul></div>
