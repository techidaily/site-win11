---
title: Combatting Security Account Manager Failures
date: 2024-08-15T23:44:32.102Z
updated: 2024-08-16T23:44:32.102Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Combatting Security Account Manager Failures
excerpt: This Article Describes Combatting Security Account Manager Failures
keywords: SAM Fix Strategies,Security SAM Errors,Manage SAM Proactively,Prevent SAM Fails,Secure SAM Access,SAM Failure Mitigation,Hardening SAM Security
thumbnail: https://thmb.techidaily.com/e7f1cad7a399e71169efcdbd386bd0d5b12f456c3f589c4c694fba40159c8b6c.jpg
---

## Combatting Security Account Manager Failures

 LSA protection is a vital security feature on Windows that prevents unauthorized access to system resources. However, corrupt system files or malware infections may lead to an error stating "this change requires you to restart your device". This error persists even after enabling Local Security Authority (LSA) protection or restarting the computer.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

## What Causes the LSA Protection Error?

 The exact cause of the “this change requires you to restart your device” error can vary, but it may be due to corrupted system files or malware infections. Malware can install malicious services and components that interfere with Windows' smooth functioning, including disabling Local Security Authority (LSA) protection. It can also occur if antivirus software incorrectly removes system files and causes instability.

 This error is usually triggered when Windows attempts to enable Local Security Authority (LSA) protection and fails. In some cases, the error may also appear after you enabled LSA protection and restarted your computer.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Select **Full scan** and click **Scan now**.

 Now wait for the scan to finish. If malicious programs are detected, Windows Security will remove them from your system automatically.

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

 After making the above changes, restart your computer and check if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. If the confirmation window pops up, click **Reset** to continue.

 Wait for the reset process to finish and restart your computer. After restarting, check if the error is still present.

## 6\. Perform Some Generic Fixes

 There are also some generic fixes to resolve the issue. First, [run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) command to repair incorrect or damaged system files. You may also want to use the Deployment Image Servicing and Management tool to diagnose issues with local system images. If the problem persists, try [updating Windows to the latest version](https://www.makeuseof.com/update-windows-manually/) to resolve any glitches or bugs.

 Some antivirus and security programs can be too aggressive in protecting your system. They could prevent access to the LSA feature, leading to this problem. To be sure, you can [temporarily disable your security software](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and check if it solves the issue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
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
<li><a href="https://some-approaches.techidaily.com/new-top-unrestricted-data-saver-solutions/"><u>[New] Top Unrestricted Data Saver Solutions</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-decoding-the-marketplace-where-to-invest-in-monetized-channels/"><u>[Updated] 2024 Approved  Decoding the Marketplace  Where to Invest in Monetized Channels</u></a></li>
<li><a href="https://extra-resources.techidaily.com/cost-effective-sky-gadgets-frugal-flight-devices-ranking-for-2024/"><u>Cost-Effective Sky Gadgets  Frugal Flight Devices Ranking for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/discover-the-top-6-chatgpt-utilities-interact-with-your-files-doc-or-pdf/"><u>Discover the Top 6 ChatGPT Utilities: Interact with Your Files, Doc or PDF</u></a></li>
<li><a href="https://win11.techidaily.com/ditch-the-focus-spotlight-icon-on-win11-desktop/"><u>Ditch the Focus: Spotlight Icon on Win11 Desktop</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1721857706079-dont-delay-get-your-hands-on-advanced-open-source-conversational-ai-tools-skip-the-desktop-chatgpt-waitlist/"><u>Don't Delay, Get Your Hands on Advanced Open Source Conversational AI Tools - Skip the Desktop ChatGPT Waitlist</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-asus-realtek-audiophile-driver-at-no-cost/"><u>Download ASUS Realtek Audiophile Driver at No Cost</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-setup-failures-windows-10-and-11-edition/"><u>Fixing Windows Setup Failures: Windows 10 & 11 Edition</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-remove-nokia-pin-by-drfone-android-unlock-android-unlock/"><u>How to remove Nokia PIN</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-15-plus-system-issues-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 15 Plus System Issues? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fix-my-google-pixel-fold-location-is-wrong-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix My Google Pixel Fold Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-how-to-harness-youtubes-creative-commons-in-video-making/"><u>In 2024, How to Harness YouTube's Creative Commons in Video Making</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-guide-to-setting-up-windows-11-calendar/"><u>In-Depth Guide to Setting Up Windows 11 Calendar</u></a></li>
<li><a href="https://win11.techidaily.com/master-artistic-creation-with-windows-11-make-amazing-ai-images-using-paint-tool-sai/"><u>Master Artistic Creation with Windows 11: Make Amazing AI Images Using Paint Tool SAI</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-window-settings-for-optimal-space-in-win11/"><u>Master the Window Settings for Optimal Space in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fixes-for-the-exception-has-been-reached-on-pcs/"><u>Mastering Fixes for The Exception Has Been Reached on PCs</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/mastering-pinterest-videos-to-mp3s-essential-strategies-for-2024/"><u>Mastering Pinterest Videos to MP3s  Essential Strategies for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-the-managerial-maze-free-old-championship-soccer-management-guide/"><u>Navigate the Managerial Maze: Free Old Championship Soccer Management Guide</u></a></li>
<li><a href="https://tech-haven.techidaily.com/new-era-post-altman-predicted-shift-for-gpt-users/"><u>New Era Post-Altman: Predicted Shift for GPT Users</u></a></li>
<li><a href="https://win11.techidaily.com/nexus-controller-down-regain-control-with-these-fixes/"><u>Nexus Controller Down? Regain Control with These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-cross-device-use-harnessing-the-power-of-dex/"><u>Optimizing Cross-Device Use: Harnessing the Power of DeX</u></a></li>
<li><a href="https://win11.techidaily.com/pinnacle-speed-5-expertly-engineered-pc-enhancements/"><u>Pinnacle Speed: 5 Expertly Engineered PC Enhancements</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-unpreviewed-documents-error-in-office-outlook/"><u>Quick Fixes for Unpreviewed Documents Error in Office Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-not-found-rockalldlldll-on-windows/"><u>Rectifying 'Not Found' Rockalldll.dll on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-usability-ai-transformations-in-windows/"><u>Redefining Usability: AI Transformations in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-directories-not-empty-error-on-win11-with-0x80070091/"><u>Remedying Directories Not Empty Error on Win11 with #0X80070091</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-a-dormant-tab-key-for-seamless-typing/"><u>Reviving a Dormant Tab Key for Seamless Typing</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-windows-interface-with-alignment/"><u>Streamline Windows Interface with Alignment</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-corrupted-recycle-bin-on-win-11/"><u>Tackling Corrupted Recycle Bin on Win 11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unlock-the-secrets-of-efficiently-locating-pictures-with-a-facebook-search/"><u>Unlock the Secrets of Efficiently Locating Pictures with a Facebook Search</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-not-found-in-windows-environments/"><u>Unraveling 'Not Found' In Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-approach-to-turn-off-gpgpu-prioritization-on-winos/"><u>Unveiling the Approach to Turn Off GPGPU Prioritization on WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-virtualbox-to-70-in-win11-a-comprehensive-tutorial/"><u>Upgrading VirtualBox to 7.0 in Win11: A Comprehensive Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/where-are-win11-control-panel-settings-locate-missing-keys/"><u>Where Are Win11 Control Panel Settings? Locate Missing Keys</u></a></li>
<li><a href="https://win11.techidaily.com/xbox-not-launching-fix-it-with-these-tips/"><u>Xbox Not Launching? Fix It with These Tips</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-honor-x8b-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Honor X8b | Dr.fone</u></a></li>
</ul></div>
