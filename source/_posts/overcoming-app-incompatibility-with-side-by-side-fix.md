---
title: Overcoming App Incompatibility with Side-by-Side Fix
date: 2024-11-03T19:46:21.569Z
updated: 2024-11-07T18:59:22.089Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming App Incompatibility with Side-by-Side Fix
excerpt: This Article Describes Overcoming App Incompatibility with Side-by-Side Fix
keywords: App Compat Fixed,Side by Side Resolve,Overcome Incompat,Sync Side Fix,Unite Apps Easy,Incompat Bypass,Seamless App Duo
thumbnail: https://thmb.techidaily.com/c91ef4997081e65543be4ed1e14a92e0b1b11ea3fa4aac3ca09a237127556c70.png
---

## Overcoming App Incompatibility with Side-by-Side Fix

 It's frustrating when you can't launch your favorite apps and programs on Windows due to the "Side-by-side configuration is incorrect" error. While determining the exact cause of this error can be difficult, it is possible to resolve it.

 In most cases, the “Side-by-side configuration is incorrect” error occurs due to a damaged Visual C++ package or a compatibility issue. However, there can be other reasons for it. So, what can you do to resolve this unforeseen error on Windows? Let's find out.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Reinstall Microsoft Visual C++ Packages

 Problems with the current Visual C++ packages on your PC can often result in the “Side-by-side configuration is incorrect” error on Windows. If that's the case, you must reinstall the problematic Visual C++ package on your computer. To do so, you'll need to find its version number using Event Viewer. Here's how you can go about it.

1. Press**Win + S** to open the search menu.
2. Type**event viewer** in the search box and select the first result that appears.
3. Use the left pane to navigate to**Custom Views > Summary page events** .  
![Event Viewer on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Event-Viewer-on-Windows.jpg)
4. Choose the most recent side-by-side error from the middle pane and note down the version number under the**General** tab.
5. Open up your web browser and head over to the[Microsoft Visual C++ Redistributable download page](https://learn.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170) .
6. Download and install the Visual C++ package corresponding to your version number.

 Restart your PC after this (see[how to restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/) ) and try to launch your app or program one more time.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139115/17108" target="_top" id="2139115">
  <img src="//a.impactradius-go.com/display-ad/17108-2139115" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139115/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Run the SFC and DISM Scans

 Corrupted or missing system files on your computer can also trigger such errors. Fortunately, Windows includes a useful command-line utility called SFC (or System File Checker) scan for such occasions. It can automatically detect any damaged system files on your PC and replace them with their cached versions.

To run the SFC scan on your computer:

1. Press**Win + X** to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt shows up.
4. In the console, type**sfc /scannow** and press**Enter** .  
![Run SFC Scan on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-SFC-Scan-on-Windows.jpg)

 Wait for the scan to complete and then run the DISM (or Deployment Image Servicing and Management) scan by entering the following command:

`DISM.exe /Online /Cleanup-image /Restorehealth`

 After the process is complete, exit the Command Prompt window and restart your PC. The error should not appear anymore after the reboot.

## 3\. Run the Program Compatibility Troubleshooter

 If the “Side-by-side configuration is incorrect” error only appears when you try to launch a specific program, you can run the program compatibility troubleshooter on Windows. It’ll try to fix any compatibility issues with your program and help you fix the error. Here’s how you can run it.

1. Right-click on your app or program that’s producing the error and select**Troubleshoot compatibility** .
2. In the Program Compatibility Troubleshooter window, select**Troubleshoot program** .
3. Mark the checkbox that reads **The program worked in earlier versions of Windows but won’t install or run now** and hit**Next** .
4. Follow the on-screen prompts to run the troubleshooter and see if the error occurs again.  
![Program Compatibility Troubleshooter Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Program-Compatibility-Troubleshooter-Windows.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148650/16836" target="_top" id="2148650">
  <img src="//a.impactradius-go.com/display-ad/16836-2148650" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148650/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Repair the Problematic App

 If the Windows troubleshooter fails to find any problems, you can try repairing the problematic app on Windows. Here's how to do it.

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab.
3. Go to**Installed apps** .
4. Scroll down to locate the problematic app on the list. Click the**three-dot menu icon** next to it and select**Advanced options** .
5. Scroll down to the Reset section and click on**Repair** .  
![Repair App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Repair-App-on-Windows.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134233/18498" target="_top" id="2134233">
  <img src="//a.impactradius-go.com/display-ad/18498-2134233" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134233/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You should see a right checkmark next to the Repair button once the process is complete.

 Alternatively, you can repair your apps and programs from Control Panel. To learn more about this, check our guide on[how to repair apps and programs on Windows](https://www.makeuseof.com/windows-repair-apps-programs/) and follow the steps outlined there.

## 5\. Reinstall the Problematic App

 Repairing the app may not help much if the existing app data is corrupted or missing. In that case, your only option is to uninstall the problematic app and install it again.

1. Press**Win + S** to open the search menu.
2. Type in the name of your app or program and select**Uninstall** from the right pane.
3. Select**Uninstall** again to confirm.  
![Uninstall App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Uninstall-App-on-Windows.jpg)

 Head over to Microsoft Store and install the app again. Following this, the error should not bother you.

## 6\. Scan for Malware

 If your computer is infected with malware, you may encounter such errors when launching apps and programs. To check for this possibility, you can run a full system scan of your PC with Windows Defender. You can also use one of the[best third-party antivirus programs for Windows](https://www.makeuseof.com/tag/best-antivirus-for-windows-10/) for this.

 If the scan uncovers anything suspicious, take the recommended steps to fix the issue and reboot your PC after that.

## 7\. Install Pending Windows Updates

 Microsoft regularly releases updates for the Windows operating system. Aside from new features and security patches, these updates also bring much-needed fixes for bugs and other errors. You can try updating Windows to its most recent version to see if that makes a difference.

 Press**Win + I** to open the Settings app and navigate to the**Windows Update** section. Click on**Check for updates** to download and install pending updates.

![Check for System Updates on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-for-System-Updates-on-Windows.jpg)

<!-- affiliate ads begin -->
<span id="701707">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/701707.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/7443-701707">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/701707.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fappsumo.8odi.net%2Fc%2F5597632%2F701707%2F7443'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/701707/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Perform a System Restore

 Windows System Restore performs a backup of the entire system on a regular basis. You can use it to revert your system to a point before the error first started appearing.

To perform a system restore on Windows:

1. Press**Win + R** to open the Run dialog box.
2. Type**sysdm.cpl** in the box and press**Enter** .
3. In the System Properties window, switch to the**System Protection** tab.
4. Click on**System Restore** .
5. Click**Next** .
6. Select a restore point before the first appeared and hit**Next** .
7. Check all the details and hit**Finish** .  
![System Restore Dialog on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/System-Restore-Dialog-on-Windows.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037346/7443" target="_top" id="2037346">
  <img src="//a.impactradius-go.com/display-ad/7443-2037346" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037346/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Windows will restart and revert to the specified restore point. Following that, the error should be resolved.

## Start Using Your Apps Again

 By applying the above fixes, you should be able to fix the “Side-by-side configuration is incorrect” error in no time. However, if none of the solutions work, you may have to reset your Windows computer as a last resort.

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
<li><a href="https://youtube-web.techidaily.com/024-approved-rapid-fire-guide-to-successful-double-exposures/"><u>[New] 2024 Approved Rapid-Fire Guide to Successful Double Exposures</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-effortless-capture-and-storage-pro-guide-to-digital-sound-recording-for-2024/"><u>[Updated] Effortless Capture & Storage Pro Guide to Digital Sound Recording for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-drive-engagement-not-farewells-top-strategies-to-keep-your-audience-hooked-on-youtube/"><u>2024 Approved Drive Engagement, Not Farewells Top Strategies to Keep Your Audience Hooked on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/drive-performance-gains-with-optimized-android-studio-on-windows/"><u>Drive Performance Gains with Optimized Android Studio on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/easing-the-burden-of-faulty-windows-character-map/"><u>Easing the Burden of Faulty Windows Character Map</u></a></li>
<li><a href="https://win11.techidaily.com/easy-steps-to-bluetooth-link-airpods-on-windows/"><u>Easy Steps to Bluetooth-Link AirPods on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-file-transfers-remedy-for-utorrent-on-windows/"><u>Enabling File Transfers: Remedy for uTorrent on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/high-fidelity-gaming-hacked-top-strategies-for-classic-adventures-with-scummvm/"><u>High Fidelity Gaming Hacked: Top Strategies for Classic Adventures with ScummVM</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-can-you-transfer-files-from-vivo-v29e-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How Can You Transfer Files From Vivo V29e To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-tecno-pova-5-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Tecno Pova 5 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-thinking-about-changing-your-netflix-region-without-a-vpn-on-vivo-x100-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Thinking About Changing Your Netflix Region Without a VPN On Vivo X100 Pro? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/nexus-development-summary-pinnacle-studio-audit-2023-for-2024/"><u>Nexus Development Summary Pinnacle Studio Audit, 2023 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/parse-fix-for-windows-error-0xc00ce556-woes/"><u>PARSE-FIX for WINDOWS Error 0xC00CE556 Woes</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/quick-and-simple-4-ways-to-take-screenshots-on-chromebook/"><u>Quick & Simple 4 Ways To Take Screenshots On Chromebook</u></a></li>
<li><a href="https://win11.techidaily.com/quiet-down-windows-update-reminders-and-alerts/"><u>Quiet Down Windows' Update Reminders and Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/rediscover-lost-features-within-windows-11s-control-panel/"><u>Rediscover Lost Features Within Windows 11'S Control Panel</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolve-silent-pc-problems-easy-solutions-for-windows-10-sound-failures/"><u>Resolve Silent PC Problems: Easy Solutions for Windows 10 Sound Failures</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/understanding-the-benefits-and-limitations-of-the-smart-ring-doorbell-plus-detailed-insights/"><u>Understanding the Benefits and Limitations of the Smart Ring Doorbell Plus – Detailed Insights</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-taskbars-timed-features-on-win-1011/"><u>Unlocking Taskbar's Timed Features on Win 10/11</u></a></li>
</ul></div>

