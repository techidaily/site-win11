---
title: How to Enable Firewall when It's Disabled on Windows
date: 2024-10-22T10:23:00.537Z
updated: 2024-10-26T22:44:33.283Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Enable Firewall when It's Disabled on Windows
excerpt: This Article Describes How to Enable Firewall when It's Disabled on Windows
keywords: Windows Firewall Activation,Turn On Windows Security,Enabling Firewall,Windows Firewall Settings,Activate Windows Defender Firewall,Restart Firewall on PC,Firewall Back Online Windows
thumbnail: https://thmb.techidaily.com/30c3f68025cf60445ca0af9503de0d05421151fac72dff09f39b3449e1fcd630.jpg
---

## How to Enable Firewall when It's Disabled on Windows

 Windows Firewall is crucial to ensure the security of your computer and protect it from potential threats. However, sometimes you may encounter issues while enabling it.

 Below, we explore the different solutions you can try to fix this issue for good.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Firewall Troubleshooter

 If you are having trouble enabling Firewall in Windows, it is a good idea to start troubleshooting using the official Firewall troubleshooter released by Microsoft Automated Troubleshooting Services.

 This utility will scan your system for underlying problems that might be preventing Firewall from functioning. If an issue is identified, it will suggest relevant fixes that you can either apply manually or from within the troubleshooter.

 Here is how you can run the troubleshooter:

1. Head over to the [official Microsoft page for the troubleshooter](https://support.microsoft.com/en-us/windows/automatically-diagnose-and-fix-problems-with-windows-firewall-513e9cf8-19ae-d579-2092-d5e64fe06f5f) and download it.  
![Download firewall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/download-troubleshooter.jpg)
2. Click on the downloaded file and proceed with the on-screen instructions to start the scan.  
![Firewall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/firewall-troubleshooter.jpg)
3. Once the scan completes, check the results and apply the solutions suggested by the troubleshooter.

 You can now close the troubleshooter and check if the issue is resolved.

## 2\. Check if Another Security Software Is Active

 Are you using a third-party security program on your computer? If so, there is a good chance that it is conflicting with Windows Firewall and stopping it from working. As such, if you have installed another antivirus app recently, we recommend temporarily disabling or uninstalling the third-party security program and then enabling Windows Firewall.

 Disabling the third-party antivirus software may vary depending on the program you have installed. However, a common approach is to right-click on the antivirus icon located in the taskbar. From the context menu that appears, you should find an option to disable the antivirus temporarily until you restart your computer.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123508/26400" target="_top" id="2123508">
  <img src="//a.impactradius-go.com/display-ad/26400-2123508" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123508/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After disabling the antivirus, try enabling the Windows Firewall and check if it functions properly now.

## 3\. Reset the Windows Firewall settings

 The issue might also be with the Firewall settings. You can fix any such issues by resetting Windows Firewall settings, as it will restore the firewall configuration to its default state, undoing any customizations or changes that might be causing conflicts.

 Here is how you can proceed:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type “control” in Run and click **Enter**.
3. In the Control Panel, expand the View by option and choose **Category**.
4. Click on **System and Security** \> **Windows Defender Firewall**.  
![Defender Firewall in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/defender-firewall.jpg)
5. Head over to the left pane and choose **Restore defaults**.  
![Restore defaults for firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-defaults.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2148127/17093" target="_top" id="2148127">
  <img src="//a.impactradius-go.com/display-ad/17093-2148127" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2148127/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Confirm the action in the following prompt and proceed with the on-screen instructions to proceed.
2. Once done, open Run again.
3. Type "cmd" in the text field and press **Ctrl** \+ **Shift** \+ **Enter** keys together. This will open Command Prompt with administrator privileges.
4. Click **Yes** in the User Account Control prompt.
5. Once you are inside the Command Prompt window, type the command mentioned below and click **Enter** to execute it. This will force enable the Firewall component.  
`netsh firewall set opmode mode=ENABLE exceptions=enable`
6. Wait for the command to execute and then restart your computer. Check if the problem is now fixed.

## 4\. Modify the Registry Editor

 There is also a chance that a Registry key DisableAntiSpyware is enabled, which is preventing you from enabling Firewall on your computer.

 To check if this is the case in your situation, you can access the Registry Editor and check the status of the DisableAntiSpyware key.

 However, before you proceed, we highly recommend [creating a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just to be safe.

 Once that is done, proceed with the steps below:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "regedit" in Run and click **Enter**.
3. Click **Yes** in the User Account Control prompt.
4. In the Registry Editor, navigate to the location below.  
`​​​​​​​HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender`
5. Move to the right side and look for the DisableAntiSpyware key. If you locate it, delete it. You can also double-click on it and change its value to 0 if you do not want to delete it.  
![Disable or delete the registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/antispyware-key.jpg)

1. Once done, head over to the following location:  
`​​​​​​​​​​​​​​HKEY_LOCAL_MACHINE/SYSTEM/CurrentControlSet/Services/BFE`
2. Right-click on the **BFE** key and choose **Permissions** from the context menu.  
![Access permissions of the key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/access-permissions.jpg)
3. Under "Group or user names", click on **Add**.
4. Type "Everyone" in the "Enter the object names to select" and click **OK**.  
![Modify permissions of the key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/modify-permissions.jpg)
5. Now, head over to the "Permissions for Everyone" section and checkmark the box associated with **Full Control** under Allow.
6. Click **Apply** to save the changes and check if the issue is now resolved.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137221/26400" target="_top" id="2137221">
  <img src="//a.impactradius-go.com/display-ad/26400-2137221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137221/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Additional Generic Fixes to Try

 Apart from the fixes we have listed above, here are some additional solutions that you can try to fix the Firewall problem.

* **Ensure relevant services are running**: Windows Firewall relies on several services to function properly. Ensure that the Windows Defender Firewall, Windows Defender Advanced Threat Protection, Windows Defender Antivirus Network Inspection, and Windows Defender Antivirus services are working fine in the Windows Services utility.
* **Scan with SFC**: You can also scan the system for underlying corruption errors that might be leading to the problem using the [System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/). You can run it via Command Prompt and analyze the results to find the culprit.
* **Clean install Windows**: If nothing works and it is essential for you to enable Firewall, you can [perform a clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) of Windows. It will wipe the existing installation and download a new one without any underlying problems.

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2141684/17092" target="_top" id="2141684">
  <img src="//a.impactradius-go.com/display-ad/17092-2141684" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettide.pxf.io/i/5597632/2141684/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Protect Your System With Windows Firewall

 The steps above should help you fix issues with Windows Firewall easily. If the error persists and you do not want to clean install the system yet, you can report the issue to Microsoft and wait for them to suggest a fix.

 Below, we explore the different solutions you can try to fix this issue for good.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-helps.techidaily.com/2024-approved-charting-the-financial-landscape-of-youtube-marketing/"><u>2024 Approved Charting the Financial Landscape of YouTube Marketing</u></a></li>
<li><a href="https://win-able.techidaily.com/defeating-the-bugs-a-guide-to-smooth-sounds-in-starfield-gaming/"><u>Defeating the Bugs: A Guide to Smooth Sounds in Starfield Gaming</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/enhance-yt-experience-the-most-outstanding-reaction-ideas-for-2024/"><u>Enhance YT Experience The Most Outstanding Reaction Ideas for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/epic-launcher-stability-stop-crashes-and-freezes-on-pcs/"><u>Epic Launcher Stability: Stop Crashes & Freezes on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-perfection-of-surface-laptop-studio-2-creativity/"><u>Exploring the Perfection of Surface Laptop Studio 2 Creativity</u></a></li>
<li><a href="https://discover-dash.techidaily.com/free-online-conversion-transform-your-wma-files-into-high-quality-flac-format-with-ease-movavi/"><u>Free Online Conversion: Transform Your WMA Files Into High-Quality FLAC Format with Ease - Movavi</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-realme-get-deleted-photos-back-with-ease-and-safety-by-fonelab-android-recover-photos/"><u>How to Realme Get Deleted photos Back with Ease and Safety?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-share-on-apple-iphone-13-drfone-by-drfone-ios/"><u>In 2024, How to Screen Share on Apple iPhone 13? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/master-quick-change-of-windows-dashboard-background/"><u>Master Quick Change of Window's Dashboard Background</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-are-you-looking-for-a-filmora-discount-code-or-promo-coupon-code-here-are-5-trusted-and-genuine-solutions-to-get-a-discount-on-your-filmora-subscription/"><u>New Are You Looking for a Filmora Discount Code or Promo Coupon Code? Here Are 5 Trusted and Genuine Solutions to Get a Discount on Your Filmora Subscription</u></a></li>
<li><a href="https://win11.techidaily.com/project-prowess-with-powerful-key-combinations/"><u>Project Prowess with Powerful Key Combinations</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-frp-lock-on-infinix-zero-30-5g-by-drfone-android-unlock-remove-google-frp/"><u>Remove FRP Lock on Infinix Zero 30 5G</u></a></li>
<li><a href="https://win-able.techidaily.com/resolving-performance-errors-for-fallout-3-gameplay-in-windows-11/"><u>Resolving Performance Errors for Fallout 3 Gameplay in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/scribble-to-screen-find-the-best-notes-tools-on-windows/"><u>Scribble to Screen: Find the Best Notes Tools on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-unblocking-steam-play-link-errors/"><u>Steps for Unblocking Steam Play Link Errors</u></a></li>
<li><a href="https://techidaily.com/this-is-how-you-can-recover-deleted-pictures-from-oppo-reno-11-pro-5g-by-fonelab-android-recover-pictures/"><u>This is how you can recover deleted pictures from Oppo Reno 11 Pro 5G.</u></a></li>
<li><a href="https://win11.techidaily.com/unison-vs-phone-link-top-windows-phone-app-ranking/"><u>Unison Vs. Phone Link: Top Windows Phone App Ranking</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-past-cortana-activity-on-a-computer-system/"><u>Unlocking Past Cortana Activity on a Computer System</u></a></li>
<li><a href="https://win11.techidaily.com/win-tech-tip-repair-razer-synapse-in-1110/"><u>Win Tech Tip: Repair Razer Synapse in 11/10</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    