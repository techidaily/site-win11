---
title: Solving LSA Protection Errors, Step by Step
date: 2024-09-22T17:55:47.657Z
updated: 2024-09-28T19:43:49.378Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solving LSA Protection Errors, Step by Step
excerpt: This Article Describes Solving LSA Protection Errors, Step by Step
keywords: LSA Error Fix Guide,Steps to Correct LSA Errors,Solve LSA Security Issues,Tackle LSA Protection Mistakes,Stepwise LSA Problem Resolution,Overcoming LSA Encryption Errors,Addressing LSA Compliance Faults
thumbnail: https://thmb.techidaily.com/3e42d7d3d66b1bb7fc10d0f6ca519d43c3162c70fd1186bee34b5c05700af6e2.jpg
---

## Solving LSA Protection Errors, Step by Step

 LSA protection is a vital security feature on Windows that prevents unauthorized access to system resources. However, corrupt system files or malware infections may lead to an error stating "this change requires you to restart your device". This error persists even after enabling Local Security Authority (LSA) protection or restarting the computer.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Causes the LSA Protection Error?

 The exact cause of the “this change requires you to restart your device” error can vary, but it may be due to corrupted system files or malware infections. Malware can install malicious services and components that interfere with Windows' smooth functioning, including disabling Local Security Authority (LSA) protection. It can also occur if antivirus software incorrectly removes system files and causes instability.

 This error is usually triggered when Windows attempts to enable Local Security Authority (LSA) protection and fails. In some cases, the error may also appear after you enabled LSA protection and restarted your computer.

## 1\. Restart Your PC

 As the error message suggests, you first restart your Windows system. This minor step can fix several system-level errors and is worth a try. Restarting your computer involves shutting down all running programs and starting it up again.

## 2\. Scan for Malicious Programs

 If restarting the computer doesn't solve the issue, check your system for malicious software. Malware infections may corrupt system files and prevent LSA protection from working.

 To check if any malicious programs are on your system, do the following.

1. Press **Win + Q** on your keyboard to open the Taskbar search window.
2. Type **Windows Security** in the search bar and hit Enter.
3. On the left pane of Windows Security, click the **Virus & threat protection** tab.
4. Click **Scan options** on the right side of the screen.  
![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)
5. Select **Full scan** and click **Scan now**.

<!-- affiliate ads begin -->
<span id="1982570">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982570.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982570">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982570.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982570%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982570/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now wait for the scan to finish. If malicious programs are detected, Windows Security will remove them from your system automatically.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134498/18498" target="_top" id="2134498">
  <img src="//a.impactradius-go.com/display-ad/18498-2134498" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134498/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Change the Group Policy Settings

 If the above steps don't help, you might need to configure LSA manually. It involves editing the Local Group Policy Editor and setting some specific settings. However, this tool only works with Windows 11 Professional and Enterprise editions.

 So, if you're running Windows Home Edition, you won't have access to Local Group Policy. To make this work, [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), then follow these steps:

1. Press **Win + R** on your keyboard to open the Run dialogue box.
2. Type **gpedit.msc** in the search box and hit Enter.
3. In the Local Group Policy Editor, expand **Computer Configuration** on the left side.
4. Then navigate to the following:  
Administrative Templates > System > Local Security Authority
5. Double-click **Configure LSASS to run as a protected process** in the right pane.  
![Change the Group Policy Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-group-policy-settings.jpg)
6. Now, in the window that appears, alter the settings from **Not Configured** to **Enabled**.
7. Under the Options section, click the drop-down menu for **Configure LSASS to run as a protected process** and select **Enabled with UEFI Lock**.  
![Set as Enabled with UEFI Lock](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-as-enabled-with-uefi-lock.jpg)
8. Now click **Apply > OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151859/7443" target="_top" id="2151859">
  <img src="//a.impactradius-go.com/display-ad/7443-2151859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151859/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After making the above changes, restart your computer and check if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123735/7443" target="_top" id="2123735">
  <img src="//a.impactradius-go.com/display-ad/7443-2123735" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123735/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Tweak the Registry Editor

 If you're running Windows Home edition, you can tweak the Registry Editor to modify Local Security Authority protection values. The steps are pretty straightforward, but be aware that making incorrect changes to the registry can cause serious problems. To be safe, [back up the Windows Registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes.

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and press the Enter key.
3. If UAC prompts appear on the screen, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following location:  
Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa  
 You can also copy and paste the given path into the address bar at the top of the Registry window. Then, hit Enter to jump directly to the folder.
5. In the right pane, double-click on **RunAsPPL** to open Edit DWORD (32-bit) Value.  
![Change RunAsPPL regsitry values](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-runasppl-regsitry-values.jpg)
6. Change the Value data from 0 to **2** and click **OK**.
7. Similarly, find the **RunAsPPLBoot** key and set its value to **2**.  
 If you don't find the **RunAsPPL** and **RunAsPPLBoot** keys in the LSA folder, you'll need to create them manually. To do this, right-click on the LSA folder and select **New > DWORD (32-bit) Value**. Name the new value **RunAsPPL** and set its value to 2\. Then repeat this process for the **RunAsPPLBoot** key.

 Once you're done, close the Registry Editor and restart your computer. This should fix the problem.

## 5\. Reset the Windows Security App

 Windows Security is an integrated antivirus program built into the Windows OS. It's responsible for scanning your system and removing malicious content. If there's something wrong with the Windows Security app, it might trigger this error. To fix the issue, reset the app and see if it helps. Here's how to do it:

1. Press **Win + I** on your keyboard to open the system settings.
2. Select **Apps** on the left side of the window.
3. Click **Installed apps** in the right pane
4. Scroll down the list of apps until you see **Windows Security**. You can also type Windows Security into the search bar to find it quickly.
5. Now click the three dots icon and select **Advanced options** from the menu.
6. On the next page, scroll down to the **Reset** section and click **Reset**.  
![Reset Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-windows-security.jpg)
7. If the confirmation window pops up, click **Reset** to continue.

 Wait for the reset process to finish and restart your computer. After restarting, check if the error is still present.

## 6\. Perform Some Generic Fixes

 There are also some generic fixes to resolve the issue. First, [run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) command to repair incorrect or damaged system files. You may also want to use the Deployment Image Servicing and Management tool to diagnose issues with local system images. If the problem persists, try [updating Windows to the latest version](https://www.makeuseof.com/update-windows-manually/) to resolve any glitches or bugs.

 Some antivirus and security programs can be too aggressive in protecting your system. They could prevent access to the LSA feature, leading to this problem. To be sure, you can [temporarily disable your security software](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and check if it solves the issue.

## Fixing the LSA Protection Error on Windows

 Local Security Authority protection safeguards unauthorized access to system resources, such as passwords or other sensitive information. However, this feature might not work as expected due to LSA Protection Error. Thanks to the potential solutions discussed in this guide, solving the problem is easy.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/new-navigating-the-nuances-of-streaming-and-saving-on-facebook-for-2024/"><u>[New] Navigating the Nuances of Streaming and Saving on Facebook for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-mastering-video-size-adjustments-on-igtv/"><u>[Updated] In 2024, Mastering Video Size Adjustments on IGTV</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-stream-selection-simplified-top-10-actionable-tips-for-2024/"><u>[Updated] Stream Selection Simplified Top 10 Actionable Tips for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-beautiful-beginnings-creating-your-personalized-glam-vlog/"><u>2024 Approved Beautiful Beginnings Creating Your Personalized Glam Vlog</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-ken-burns-effect-techniques-for-camtasia-users/"><u>2024 Approved Ken Burns Effect Techniques for Camtasia Users</u></a></li>
<li><a href="https://win11.techidaily.com/balancing-act-equalizing-pc-and-mobile-internet-speeds/"><u>Balancing Act: Equalizing PC & Mobile Internet Speeds</u></a></li>
<li><a href="https://tech-hub.techidaily.com/creating-a-consistent-meditation-routine-with-chatgpt-a-step-by-step-guide/"><u>Creating a Consistent Meditation Routine with ChatGPT: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-reasons-for-preserving-your-win-11-alerts/"><u>Discover the Reasons for Preserving Your Win 11 Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/from-a-simple-pin-a-comprehensive-approach-to-switching-passwords-in-windows-11/"><u>From a Simple PIN: A Comprehensive Approach to Switching Passwords in Windows 11</u></a></li>
<li><a href="https://buynow-help.techidaily.com/galaxy-vs-ford-trucks-downsized-to-rc-glory-who-reigns-supreme/"><u>Galaxy vs Ford Trucks Downsized to RC Glory: Who Reigns Supreme?</u></a></li>
<li><a href="https://blog-min.techidaily.com/gratis-mpeg-to-mkv-konverter-online-professioneel-en-eenvoudig-met-movavi/"><u>Gratis MPEG-to-MKV Konverter Online: Professioneel en Eenvoudig Met Movavi</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-samsung-galaxy-s23-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Samsung Galaxy S23 to iPhone | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-novatech-series-unified-4k-all-in-one-workstations/"><u>In 2024, NovaTech Series Unified 4K, All-in-One Workstations</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-insights-new-folder-formation-in-windows-11/"><u>Innovative Insights: New Folder Formation in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-1011s-recycle-bin-issues/"><u>Navigating Through Windows 10/11'S Recycle Bin Issues</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-startup-changing-boot-timeout-in-windows-11/"><u>Optimize Startup: Changing Boot Timeout in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-code-0xc0000142-in-winos/"><u>Resolving Code 0XC0000142 in WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/sketch-mastery-for-desktop-users-in-windows-11/"><u>Sketch Mastery for Desktop Users in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-screens-boost-your-pcs-performance-with-hotkeys/"><u>Streamlined Screens: Boost Your PC's Performance with Hotkeys</u></a></li>
</ul></div>

