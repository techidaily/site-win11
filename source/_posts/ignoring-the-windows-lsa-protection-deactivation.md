---
title: Ignoring the Windows LSA Protection Deactivation
date: 2024-08-16T00:34:34.947Z
updated: 2024-08-17T00:34:34.947Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ignoring the Windows LSA Protection Deactivation
excerpt: This Article Describes Ignoring the Windows LSA Protection Deactivation
keywords: Windows Security Compliance,LSA Deactivation Risks,SysAdmin Caution Advised,Microsoft Windows Hardening,LSA Security Breach,Operating System Safeguards,Mitigate OS Vulnerabilities
thumbnail: https://thmb.techidaily.com/0838ac8f5f2d8f067138531cc9f4dfd905cfa9adb1733f1b9948bd185f0bb490.jpg
---

## Ignoring the Windows LSA Protection Deactivation

 Have you seen a warning saying, "Local Security Authority protection is off. Your device may be vulnerable" in the Core isolation settings of the Windows Security app? If so, the Local Security Authority (LSA) protection feature, which protects your login credentials, is turned off on your system.

 The feature could be off for numerous reasons; a problematic Windows update, the presence of malware in your system, interference from a recently installed third-party app, problems with the Windows Security app, improper Registry Editor settings, and more. If you want to fix this issue and activate the feature again, apply the following solutions.

## 1\. Perform Some Preliminary Checks

 First off, perform the following basic fixes to ensure temporary issues haven't caused the feature to turn off:

* Close all apps currently running on your device. Then, restart your device.
* Try to manually enable the feature in Core isolation settings. For that, open the Windows Security app, navigate to the **Device Security** tab, and turn on the toggle under **Local Security Authority Protection**.
* If the feature is already enabled in the security settings, but the warning message still appears, disable it once, re-enable it again, and restart your device.
* Temporarily turn off third-party security software you use to ensure its interference does not turn off the feature.

 If none of the above fixes resolves the issue, begin applying the remaining fixes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
## 2\. Ensure the Warning Isn't Just a False Flag

 Some users who encountered the error under discussion reported that the warning was simply a false flag triggered due to a Windows update issue. In other words, the warning appeared even though the feature was already enabled and functioning well.

 Therefore, you should ensure that the warning you have received isn't just a false alarm and that the feature is turned off. Follow these steps to check that:

1. Open the **Event Viewer** app by searching for **"Event Viewer"** in Windows Search.
2. On the left-hand sidebar, navigate to **Applications and Services Logs > Microsoft > Windows > LSA**.
3. Find the event with **ID 5004** associated with LSA protection and ensure it is enabled and operational.

 If there is no event with this ID in the Event Viewer app, the feature could be disabled. So, apply the remaining fixes and see if they fix the issue.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Install Any Pending Windows Updates

![A Windows laptop installing updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Install-Windows-11-Updates.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->

 Several users on a [Microsoft Community forum thread](https://answers.microsoft.com/en-us/windows/forum/all/the-local-security-authority-protection-is-off/6bd9dad0-9d25-4b6e-b101-eeacac9d3b3a) reported that the bug that turns off the Local Security Authority protection feature originated with a Windows update released in March 2023, specifically, the Update for Microsoft Defender antivirus antimalware platform KB5007651\.

 Fortunately, Microsoft has listened to the concerns of the users and fixed this issue in new updates. However, you will have to update your operating system to the latest version to fix this. Therefore, refer to our guide on [how to update Windows manually](https://www.makeuseof.com/update-windows-manually/), install the pending updates and check if that fixes the problem.

 In case that doesn't resolve the issue, uninstall the KB5007651 update. Refer to our guide on [how to uninstall any Windows update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) if you don't know how. If that doesn't resolve the issue, as some users continue to encounter it despite updating their operating system, apply the remaining fixes.

## 4\. Uninstall Recently Installed Third-Party Applications

 Have you recently installed a third-party app, especially from a shady source, and subsequently experienced the error mentioned above in the Windows Security app? If that is the case, the app could be malicious, designed to steal your login credentials, which could be why it has turned off this security feature.

 If you remember the app you installed recently, follow our guide on [how to uninstall any software on Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) to remove it. If you don't remember, open the Settings app and navigate to **Apps > Installed apps**. Here, sort the apps according to the **Date installed**, find the latest app, and uninstall it.

![Sort Installed Apps by Date Installed in the Windows Setiings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sort-installed-apps-by-date-installed-in-the-windows-setiings-app.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Repair and Reset the Windows Security Application

 The problematic Windows Security app can also turn off this security feature. If you've tweaked the app's settings recently, you're also more likely to get the "Local Security Authority protection is off" error. Repairing and resetting the Windows Security app is the best way to rule out these possibilities.

![Reset Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-windows-security.jpg)

 Resetting the app will restore its original default settings, eliminating the possibility that misconfigured settings are causing the problem. Repairing the app will fix any underlying issue with its functionality. Refer to our guide on [how to reset a Windows app](https://www.makeuseof.com/windows-reset-app/) (or [repair it)](https://www.makeuseof.com/windows-repair-apps-programs/) if this is your first time doing so.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Ensure Malware Isn't Responsible for Deactivating the Feature

 Malware designed to find a loophole in your device's security can also turn off this feature to access your credentials and hand them over to threat actors. Considering how serious this threat can be, ensuring your device is virus-free is essential. Running the [Windows Defender malware scan](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/) is probably the best way to find any threats.

 If any threats are detected, take the recommended actions to remove them. Once this is done, return to Core isolation settings and check if the warning has disappeared.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Use Other Methods to Enable Local Security Authority Protection

 If none of the above fixes and checks have resolved the issue, the toggle to enable this feature is grayed out in Windows Security, and enabling the feature from the Windows Security app does not eradicate the warning, use the alternative ways to enable Local Security Authority protection.

 There are mainly two alternative ways to enable this feature on Windows: using the Local Group Policy Editor, a Windows utility for managing group policy settings, and using the Registry Editor, which lets us access and edit the Windows operating system configuration settings.

 Our guide on [how to enable Local Security Authority protection](https://www.makeuseof.com/windows-11-enable-local-security-authority-protection/) explains the process to enable this security feature using each of these methods.

 Misconfiguring the Windows Registry Editor settings can completely ruin your system's performance and even make it unbootable. So, don't forget to [create a Windows Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes there.

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
<li><a href="https://facebook-video-share.techidaily.com/new-a-visual-hook-creating-captivating-youtube-thumbnails-to-drive-traffic-for-2024/"><u>[New] A Visual Hook  Creating Captivating YouTube Thumbnails to Drive Traffic for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-high-seas-of-soundtracking-leading-destinations-for-hearing-heroes-tts-downloads/"><u>[New] High Seas of Soundtracking  Leading Destinations for Hearing Heroes' TTS Downloads</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-smooth-streams-from-obs-to-insta/"><u>[New] In 2024, Smooth Streams From OBS to Insta</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-peering-into-the-pinnacle-of-4k-monitoring-with-lgs-ultrafine-display/"><u>[New] Peering Into the Pinnacle of 4K Monitoring with LG’s UltraFine Display</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-comedy-chorus-satirical-song-selections-for-2024/"><u>[Updated] Comedy Chorus  Satirical Song Selections for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-mastering-virtual-reality-recording-techniques-for-2024/"><u>[Updated] Mastering Virtual Reality Recording Techniques for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-avoid-shaky-footage-proper-tripod-usage-techniques-in-vlog-creation/"><u>2024 Approved  Avoid Shaky Footage  Proper Tripod Usage Techniques in Vlog Creation</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-capture-unbroken-webspace/"><u>2024 Approved  Capture Unbroken Webspace</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-shadow-elimination-for-dark-iphone-footage/"><u>2024 Approved  Shadow Elimination for Dark iPhone Footage</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-the-best-practices-for-silent-film-making/"><u>2024 Approved  The Best Practices for Silent Film Making</u></a></li>
<li><a href="https://win11.techidaily.com/5-simple-ways-to-tell-if-your-pc-needs-restarting/"><u>5 Simple Ways to Tell if Your PC Needs Restarting</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-from-windows-update-problems-quickly/"><u>Break Free From Windows Update Problems Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/clean-slate-for-windows-users-generative-erase-wonders/"><u>Clean Slate for Windows Users: Generative Erase Wonders</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-inaccessible-printmanagement-service-in-os/"><u>Dealing with Inaccessible 'PrintManagement' Service in OS</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-language-of-windows-updates/"><u>Decoding the Language of Windows Updates</u></a></li>
<li><a href="https://win11.techidaily.com/devhome-the-comprehensive-resource-for-w11-enthusiasts/"><u>DevHome: The Comprehensive Resource for W11 Enthusiasts</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-nokia-105-classic-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Nokia 105 Classic Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-installation-of-ai-tools-in-windows/"><u>Efficient Installation of AI Tools in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/establishing-enduring-trash-settings-in-the-windows-environment/"><u>Establishing Enduring Trash Settings in the Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-temporary-directory-error-win-error-1152/"><u>Fixing 'Temporary Directory Error' - Win Error 1152</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/game-changers-discovering-top-tier-gaming-webcam-technology/"><u>Game Changers  Discovering Top-Tier Gaming Webcam Technology</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-androidprocessmedia-has-stopped-on-honor-magic-v2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android.Process.Media Has Stopped on Honor Magic V2 | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-honor-magic-5-lite-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Honor Magic 5 Lite? | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/how-to-make-a-collage-on-iphone-handy-tips/"><u>How to Make a Collage on iPhone [Handy Tips]</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-oneplus-12r-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & OnePlus 12R | Dr.fone</u></a></li>
<li><a href="https://program-issues.techidaily.com/1722981900544-how-to-stop-your-pc-from-continuous-crashing-issues-resolved/"><u>How To Stop Your PC From Continuous Crashing Issues - Resolved!</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-oneplus-ace-2-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On OnePlus Ace 2 | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-delete-icloud-account-remove-your-apple-id-permanently-on-apple-iphone-7-by-drfone-ios/"><u>In 2024, How To Delete iCloud Account Remove Your Apple ID Permanently On Apple iPhone 7</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-samsung-galaxy-a24-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Samsung Galaxy A24 to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-spectral-perfection-program/"><u>In 2024, Spectral Perfection Program</u></a></li>
<li><a href="https://data-wizards.techidaily.com/macdatarescue-roundup-discovering-8-top-rated-apps/"><u>MacDataRescue Roundup: Discovering 8 Top-Rated Apps</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-the-maze-of-windows-11s-error-codes/"><u>Navigating Through the Maze of Windows 11'S Error Codes</u></a></li>
<li><a href="https://win11.techidaily.com/precision-note-taking-adopting-obsidian-written-canvas/"><u>Precision Note-Taking: Adopting Obsidian' Written Canvas</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-editing-profile-paths-in-w11/"><u>Quick Guide to Editing Profile Paths in W11</u></a></li>
<li><a href="https://win11.techidaily.com/reducing-windows-installer-cpu-spikes/"><u>Reducing Windows Installer CPU Spikes</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-predominant-rainmeter-malfunctions-in-windows/"><u>Remedying Predominant Rainmeter Malfunctions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-the-lost-link-a-comprehensive-guide-to-reinstating-defective-adapters-in-windows/"><u>Reviving the Lost Link: A Comprehensive Guide to Reinstating Defective Adapters in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/solving-disabled-network-visibility-in-windows/"><u>Solving Disabled Network Visibility in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-fixing-microsoft-store-installation-errors/"><u>Steps for Fixing Microsoft Store Installation Errors</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-handle-no-device-drivers-issue-in-system-setup/"><u>Steps to Handle 'No Device Drivers' Issue in System Setup</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-blank-screen-issues-after-attempting-to-connect/"><u>Tackling Blank Screen Issues After Attempting to Connect</u></a></li>
<li><a href="https://win11.techidaily.com/take-control-of-your-system-utilizing-alomware-tools-effectively/"><u>Take Control of Your System: Utilizing AlomWare Tools Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-incorporating-folders-in-win11-ui/"><u>Techniques for Incorporating Folders in Win11 UI</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-cutting-edge-ipad-lineup-exploring-apples-latest-innovation/"><u>The Cutting-Edge iPad Lineup: Exploring Apple’s Latest Innovation</u></a></li>
<li><a href="https://unlock-android.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-xiaomi-redmi-note-13-pro-5g-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Xiaomi Redmi Note 13 Pro 5G Device</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-12-prominent-xiaomi-redmi-note-13-5g-fingerprint-not-working-solutions-by-drfone-android/"><u>Top 12 Prominent Xiaomi Redmi Note 13 5G Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-7-phone-number-locators-to-track-oneplus-open-location-drfone-by-drfone-virtual-android/"><u>Top 7 Phone Number Locators To Track OnePlus Open Location | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-clustered-icon-issue-in-windows-11-taskbar/"><u>Troubleshooting Clustered Icon Issue in Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-tutorial-syncing-airpods-with-windows/"><u>Ultimate Tutorial: Syncing AirPods with Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-potential-setting-up-the-jdk-in-windows-11-efficiently/"><u>Unlocking Potential: Setting Up the JDK in Windows 11 Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-unlocked-effective-tpm-deactivation/"><u>Windows 11 Unlocked: Effective TPM Deactivation</u></a></li>
<li><a href="https://win11.techidaily.com/windows-auto-update-shutdown-guide/"><u>Windows Auto-Update Shutdown Guide</u></a></li>
</ul></div>
