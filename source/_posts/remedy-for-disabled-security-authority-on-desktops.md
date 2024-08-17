---
title: Remedy for Disabled Security Authority on Desktops
date: 2024-08-15T23:28:55.971Z
updated: 2024-08-16T23:28:55.971Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedy for Disabled Security Authority on Desktops
excerpt: This Article Describes Remedy for Disabled Security Authority on Desktops
keywords: Disabled Auth Access,Security Lockout Fix,Desktop Security Remedies,Authority Restoration Tools,Regain Admin Rights,Reset Security Controls,Override Lockout Issue
thumbnail: https://thmb.techidaily.com/b40abdafc85906cdf8c505af7da6e2b6de5b2e3882be4cc44ae2eb5b5e3f9c4a.jpg
---

## Remedy for Disabled Security Authority on Desktops

 Have you seen a warning saying, "Local Security Authority protection is off. Your device may be vulnerable" in the Core isolation settings of the Windows Security app? If so, the Local Security Authority (LSA) protection feature, which protects your login credentials, is turned off on your system.

 The feature could be off for numerous reasons; a problematic Windows update, the presence of malware in your system, interference from a recently installed third-party app, problems with the Windows Security app, improper Registry Editor settings, and more. If you want to fix this issue and activate the feature again, apply the following solutions.

## 1\. Perform Some Preliminary Checks

 First off, perform the following basic fixes to ensure temporary issues haven't caused the feature to turn off:

* Close all apps currently running on your device. Then, restart your device.
* Try to manually enable the feature in Core isolation settings. For that, open the Windows Security app, navigate to the **Device Security** tab, and turn on the toggle under **Local Security Authority Protection**.
* If the feature is already enabled in the security settings, but the warning message still appears, disable it once, re-enable it again, and restart your device.
* Temporarily turn off third-party security software you use to ensure its interference does not turn off the feature.

 If none of the above fixes resolves the issue, begin applying the remaining fixes.

## 2\. Ensure the Warning Isn't Just a False Flag

 Some users who encountered the error under discussion reported that the warning was simply a false flag triggered due to a Windows update issue. In other words, the warning appeared even though the feature was already enabled and functioning well.

 Therefore, you should ensure that the warning you have received isn't just a false alarm and that the feature is turned off. Follow these steps to check that:

1. Open the **Event Viewer** app by searching for **"Event Viewer"** in Windows Search.
2. On the left-hand sidebar, navigate to **Applications and Services Logs > Microsoft > Windows > LSA**.
3. Find the event with **ID 5004** associated with LSA protection and ensure it is enabled and operational.

 If there is no event with this ID in the Event Viewer app, the feature could be disabled. So, apply the remaining fixes and see if they fix the issue.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Install Any Pending Windows Updates

![A Windows laptop installing updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Install-Windows-11-Updates.jpg)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Several users on a [Microsoft Community forum thread](https://answers.microsoft.com/en-us/windows/forum/all/the-local-security-authority-protection-is-off/6bd9dad0-9d25-4b6e-b101-eeacac9d3b3a) reported that the bug that turns off the Local Security Authority protection feature originated with a Windows update released in March 2023, specifically, the Update for Microsoft Defender antivirus antimalware platform KB5007651\.

 Fortunately, Microsoft has listened to the concerns of the users and fixed this issue in new updates. However, you will have to update your operating system to the latest version to fix this. Therefore, refer to our guide on [how to update Windows manually](https://www.makeuseof.com/update-windows-manually/), install the pending updates and check if that fixes the problem.

 In case that doesn't resolve the issue, uninstall the KB5007651 update. Refer to our guide on [how to uninstall any Windows update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) if you don't know how. If that doesn't resolve the issue, as some users continue to encounter it despite updating their operating system, apply the remaining fixes.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Uninstall Recently Installed Third-Party Applications

 Have you recently installed a third-party app, especially from a shady source, and subsequently experienced the error mentioned above in the Windows Security app? If that is the case, the app could be malicious, designed to steal your login credentials, which could be why it has turned off this security feature.

 If you remember the app you installed recently, follow our guide on [how to uninstall any software on Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) to remove it. If you don't remember, open the Settings app and navigate to **Apps > Installed apps**. Here, sort the apps according to the **Date installed**, find the latest app, and uninstall it.

![Sort Installed Apps by Date Installed in the Windows Setiings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sort-installed-apps-by-date-installed-in-the-windows-setiings-app.jpg)
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Repair and Reset the Windows Security Application

 The problematic Windows Security app can also turn off this security feature. If you've tweaked the app's settings recently, you're also more likely to get the "Local Security Authority protection is off" error. Repairing and resetting the Windows Security app is the best way to rule out these possibilities.

![Reset Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-windows-security.jpg)

 Resetting the app will restore its original default settings, eliminating the possibility that misconfigured settings are causing the problem. Repairing the app will fix any underlying issue with its functionality. Refer to our guide on [how to reset a Windows app](https://www.makeuseof.com/windows-reset-app/) (or [repair it)](https://www.makeuseof.com/windows-repair-apps-programs/) if this is your first time doing so.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
## 6\. Ensure Malware Isn't Responsible for Deactivating the Feature

 Malware designed to find a loophole in your device's security can also turn off this feature to access your credentials and hand them over to threat actors. Considering how serious this threat can be, ensuring your device is virus-free is essential. Running the [Windows Defender malware scan](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/) is probably the best way to find any threats.

 If any threats are detected, take the recommended actions to remove them. Once this is done, return to Core isolation settings and check if the warning has disappeared.

## 7\. Use Other Methods to Enable Local Security Authority Protection

 If none of the above fixes and checks have resolved the issue, the toggle to enable this feature is grayed out in Windows Security, and enabling the feature from the Windows Security app does not eradicate the warning, use the alternative ways to enable Local Security Authority protection.

 There are mainly two alternative ways to enable this feature on Windows: using the Local Group Policy Editor, a Windows utility for managing group policy settings, and using the Registry Editor, which lets us access and edit the Windows operating system configuration settings.

 Our guide on [how to enable Local Security Authority protection](https://www.makeuseof.com/windows-11-enable-local-security-authority-protection/) explains the process to enable this security feature using each of these methods.

 Misconfiguring the Windows Registry Editor settings can completely ruin your system's performance and even make it unbootable. So, don't forget to [create a Windows Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes there.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## Enable LSA to Foolproof Your Security

 Buggy Windows updates often give rise to unforeseen problems now and then. The "Local Security Authority protection is off. Your device may be vulnerable" error can also result from a faulty Windows update. Hopefully, you can now take the necessary steps to ensure the warning isn't a false alarm and resolve the problem using the recommended fixes.

 If the issue persists, use the abovementioned alternative methods to enable the LSA feature forcefully.

 The feature could be off for numerous reasons; a problematic Windows update, the presence of malware in your system, interference from a recently installed third-party app, problems with the Windows Security app, improper Registry Editor settings, and more. If you want to fix this issue and activate the feature again, apply the following solutions.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-windows-snapshot-mastery-3-easy-approaches/"><u>[New] 2024 Approved  Windows Snapshot Mastery (3 Easy Approaches)</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-boost-your-revenue-yielding-earnings-from-youtube-at-500-followers/"><u>[Updated] 2024 Approved  Boost Your Revenue  Yielding Earnings From YouTube at 500 Followers</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-avoiding-blur-on-instagram-with-smart-zooms/"><u>[Updated] Avoiding Blur on Instagram with Smart Zooms</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-peak-performance-tools-best-4k-cameras-for-professionals/"><u>[Updated] Peak Performance Tools  Best 4K Cameras for Professionals</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-unpacking-the-essence-of-digital-tales/"><u>2024 Approved  Unpacking the Essence of Digital Tales</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-lava-yuva-2-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Lava Yuva 2 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/a-comprehensive-examination-of-simple-hdr-methods/"><u>A Comprehensive Examination of Simple HDR Methods</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-windows-1011-login-lockout-interval/"><u>Adjusting Windows 10/11 Login Lockout Interval</u></a></li>
<li><a href="https://extra-information.techidaily.com/audioadvisor-dacast-and-what-it-should-be-for-2024/"><u>AudioAdvisor  DaCast & What It Should Be for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-into-iis-manager-top-8-approaches/"><u>Breaking Into IIS Manager: Top 8 Approaches</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-tackling-winos-isdonedll-errors/"><u>Comprehensive Guide to Tackling WinOS ISDone.dll Errors</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-fixing-0x0000004e-on-windows-xp7/"><u>Decoding and Fixing 0X0000004E on Windows XP/7</u></a></li>
<li><a href="https://tech-revival.techidaily.com/discover-the-foremost-ai-computing-devices-today/"><u>Discover the Foremost AI Computing Devices Today</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-visual-delight-windows-wallpapers-guidebook/"><u>Fine-Tuning Visual Delight: Windows Wallpapers Guidebook</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-color-management-not-working-on-windows/"><u>How to Fix Color Management Not Working on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-temporarily-turn-off-your-pcs-firewall/"><u>How to Temporarily Turn Off Your PC's Firewall</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unlock-linux-capabilities-on-windows-10/"><u>How to Unlock Linux Capabilities on Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/immersive-education-experience-windows-11-tutorials/"><u>Immersive Education Experience: Windows 11 Tutorials</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-visual-perfection-in-videos-implementing-black-bar-and-box-on-fb/"><u>In 2024, Visual Perfection in Videos  Implementing Black Bar & Box on FB</u></a></li>
<li><a href="https://buynow-info.techidaily.com/lg-stylo-6-review/"><u>LG Stylo 6 Review</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-compression-command-prompt-and-powershell-techniques/"><u>Mastering File Compression: Command Prompt & PowerShell Techniques</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/mastering-srt-file-creation-a-comprehensive-manual/"><u>Mastering SRT File Creation  A Comprehensive Manual</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-unraveling-the-sixest-methods-for-copying-file-and-folders-locations/"><u>Mastering Windows 11: Unraveling the Sixest Methods for Copying File & Folders' Locations</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-offline-setup-path-of-win11/"><u>Navigating the Offline Setup Path of Win11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-defender-written-by-michael-cramer/"><u>Navigating Windows Defender' Written by Michael Cramer</u></a></li>
<li><a href="https://win11.techidaily.com/nix-the-need-for-speedy-pointers-on-windows-11/"><u>Nix the Need for Speedy Pointers on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-windows-security-add-safe-websites-now/"><u>Optimize Windows Security: Add Safe Websites Now</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-qt-engine-initialization-problem-in-software/"><u>Rectifying Qt Engine Initialization Problem in Software</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-discords-critical-js-error-on-windows-1011-systems/"><u>Resolving Discord's Critical JS Error on Windows 10/11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-access-tackling-onedrive-logins-in-windows/"><u>Reviving Access: Tackling OneDrive Logins in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-asana-app-performance-on-windows-systems/"><u>Reviving Asana App Performance on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/say-goodbye-to-troubleshooting-woes-on-vistawindows-7/"><u>Say Goodbye to Troubleshooting Woes on Vista/Windows 7</u></a></li>
<li><a href="https://win11.techidaily.com/securely-storing-windows-uac-prompt-pictures/"><u>Securely Storing Windows UAC Prompt Pictures</u></a></li>
<li><a href="https://win11.techidaily.com/set-personalized-idle-lock-on-windows/"><u>Set Personalized Idle Lock on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-your-image-snap-shot-size/"><u>Setting Up Your Image Snap Shot Size</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-successfully-reconnecting-win11-to-5g-wi-fi/"><u>Steps for Successfully Reconnecting Win11 to 5G Wi-Fi</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-avoid-dwarf-fortress-freezes-on-windows-systems/"><u>Steps to Avoid Dwarf Fortress Freezes on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-eliminate-windows-1011-camera-app-error-a00f429f/"><u>Steps to Eliminate Windows 10/11 Camera App Error A00F429F</u></a></li>
<li><a href="https://win11.techidaily.com/stop-the-stutter-start-the-flow-top-9-tactics-to-enhance-video-on-pcs/"><u>Stop the Stutter, Start the Flow: Top 9 Tactics to Enhance Video on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-and-personalize-windows-11-files-via-added-movecopy/"><u>Streamline and Personalize Windows 11 Files via Added 'Move'/'Copy'</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-workflow-coloring-without-conflict-on-windows/"><u>Streamlining Your Workflow: Coloring Without Conflict on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-top-windows-11-challenges-with-ease/"><u>Tackling Top Windows 11 Challenges with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/tactics-to-overcome-windows-lunar-client-launch-problem/"><u>Tactics to Overcome Windows Lunar Client Launch Problem</u></a></li>
<li><a href="https://win11.techidaily.com/top-6-window-brighter-controls-the-ultimate-guide-for-multiscreen-enthusiasts/"><u>Top 6 Window Brighter Controls: The Ultimate Guide for Multiscreen Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/trimming-down-excessive-ntoskrnlexe-utilization/"><u>Trimming Down Excessive Ntoskrnl.exe Utilization</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-risks-ignoring-windows-11-push-notifications/"><u>Understanding Risks: Ignoring Windows 11 Push Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-the-risks-of-keygen-malware-in-modern-windows-systems/"><u>Understanding the Risks of Keygen Malware in Modern Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-safe-slumber-techniques/"><u>Understanding Window's Safe Slumber Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-value-in-vcplusplus-release-packages/"><u>Unlocking the Value in VC++ Release Packages</u></a></li>
<li><a href="https://techidaily.com/will-mov-files-play-on-14-pro-by-aiseesoft-video-converter-play-mov-on-android/"><u>Will MOV files play on 14 Pro ?</u></a></li>
<li><a href="https://win11.techidaily.com/windows-guide-spotting-active-tcp-connections/"><u>Windows Guide: Spotting Active TCP Connections</u></a></li>
<li><a href="https://win11.techidaily.com/windows-terminal-tailoring-the-visual-experience/"><u>Windows Terminal: Tailoring the Visual Experience</u></a></li>
</ul></div>
