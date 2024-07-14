---
title: Deciphering and Dismantling a Blocked Update
date: 2024-07-13T10:49:17.915Z
updated: 2024-07-14T10:49:17.915Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deciphering and Dismantling a Blocked Update
excerpt: This Article Describes Deciphering and Dismantling a Blocked Update
keywords: Deciphering Updates,Unblocking Software,Disassembled Patches,Update Rejection,Clear Update Hurdles,Blocked Update Solve,Dismantling Obstruction
thumbnail: https://thmb.techidaily.com/fed3ffae9229ff3a7d3580519bb324f0e6bad8a6cd96fa55cbded24321f049a3.jpg
---

## Deciphering and Dismantling a Blocked Update

 Sometimes, the Windows Update Troubleshooter gets stuck while diagnosing and resolving problems. A slow or unstable internet connection, a stuck application, outdated drivers, or corrupt system files could cause this error.

 But, it is not difficult to get the Windows Update Troubleshooter working again—as you will discover by exploring the following fixes.

## 1\. Restart Your Computer

 You may have rebooted your phone at times to fix some lags and stuck applications. And you probably know that restarting your Windows PC works in the same way—it can fix issues like an unresponsive app and glitches too.

 When you restart your PC, the system shuts down temporarily and then turns on again. The RAM is cleaned up and refreshed, and so is the processor cache. So when your PC reboots, you will get a clean start all over again.

 Restarting your PC should be the first thing you do when the Windows Update Troubleshooter gets stuck on a "resolving problems" loop.

 Then try running the Windows Update Troubleshooter to see if it works.

## 2\. Clear the DNS Cache

 When you run the Windows Update Troubleshooter, it checks for Windows update issues, diagnoses, and resolves problems, resets Windows Update components, clears temporary files, and more. To do all this, it needs a stable internet connection.

 Often the Windows Update Troubleshooter malfunctions due to an unstable internet connection caused by an outdated or corrupt DNS (Domain Name System) cache.

 The DNS cache uses stored information like IP addresses and DNS Records to load websites and pages faster. However, the DNS cache can get corrupted.

 But you can clear or flush the DNS cache to resolve security and internet connectivity issues. Check out [how to flush the DNS cache on Windows](https://www.makeuseof.com/flush-dns-cache-windows/) for more information on how to do this.

 If the process is successful, you will get the confirmation message of the DNS Resolver Cache being successfully flushed. Now try running the Windows Update Troubleshooter.

## 3\. Restart Windows Cryptographic Services

 At times, an erratic or stopped Windows Cryptographic Services can cause problems in the smooth running of the Windows Update Troubleshooter.

 Cryptographic Services is an inbuilt Windows feature that provides encryption, decryption, and verification services. If it doesn't work properly, Windows Update Troubleshooter may also malfunction.

To fix this, you can try restarting Cryptographic Services.

1. Search for**Services** in**Windows Search** and click on the**Services app** under**Best match** . Or use one of the [many ways to open Services](https://www.makeuseof.com/windows-11-open-services-app/) .
2. In the**Services** app, look for**Cryptographic** **Services** and double-click on it to open its**Properties** .  
![Windows Cryptographic Services in the Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-cryptographic-services.jpg)
3. In**Properties** , click the**Stop** button to stop Cryptographic Services.  
![Cryptographic Services Stopped](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/stop-cryptographic-services.jpg)
4. Now, wait a few seconds and then click on the**Start** button. Also, ensure that the**Startup type** is set to**Automatic** .  
![Cryptographic Services Started With Automatic Startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/start-cryptographic-services.jpg)
5. Then click**Apply** and then**OK** .

 Now close Services and try running the Windows Update Troubleshooter again.

## 4\. Run System File Checker and DISM Command

 The Windows Update Troubleshooter can also get stuck in a loop if system files have gotten corrupted. Fortunately, you can resolve this issue by running the SFC scan. It scans, repairs, and replaces these damaged files automatically.

 Sometimes you may experience that the SFC is not working properly. To overcome that, you should run the DISM command that will service and repair Windows images.

 You can quickly learn how to run the SFC and DISM, and also explore how they work. Check out our piece on the [differences between CHKDSK, SFC, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) for the full low-down.

 After these scans finish running, try running the Windows Update Troubleshooter again.

## 5\. Update System Drivers

 Computer drivers enable Windows and its components to communicate and function efficiently. So it's good for you to [know what drivers are and why you should keep them updated](https://www.makeuseof.com/computer-drivers-what-are-they-why-should-you-update/) .

 If you're regularly keeping your Windows PC updated, the drivers your system needs would automatically be getting installed with the updates.

 But since the working of the Windows Update Troubleshooter may be affected by outdated or corrupt drivers, it's best if you check for driver updates and install them manually.

1. Right-click the**Windows icon** on the taskbar and select**Settings** from the menu.
2. Click**Windows Update** in**Settings** and then on the right pane select**Advanced options** .  
![Advanced Options in Windows Update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/advanced-options-windows-update.jpg)
3. In**Advanced options** , under the**Additional options** section, click on**Optional updates** .  
![Optional Updates in Advanced Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/optional-updates-windows-update.jpg)
4. If there are driver updates available they would be listed under the**Driver Updates** option. Select all the driver updates and click on**Download & install** .

 After you've updated the drivers, try running the Windows Troubleshooter and see if it works properly.

## 6\. Configure Troubleshooting in Group Policy Editor

 The Windows Update Troubleshooter may be stuck if the troubleshooting service is disabled in the Group Policy Editor.

 If you're using Windows 10 Pro or Windows 11 Pro editions, you can try tweaking the Scripted Diagnostics policy in Troubleshooting and Diagnostics in the Group Policy Editor.

 Though it's not available on Windows Home, you can still [access the Group Policy Editor by enabling it](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

To edit and enable the Scripted Diagnostics policy:

1. Press the**Windows** +**R** keys together to open the**Run** box.
2. Type**gpedit.msc** in the navigation bar and click**Enter** .  
![Open Group Policy Editor Via Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-group-policy-editor-via-run.jpg)
3. Click**Yes** on the UAC prompt. The**Group Policy Editor** will open.
4. In the**Group Policy Editor** , navigate to**Scripted Diagnostics** using the following path:  
`Computer Configuration > Administrative Templates > System > Troubleshooting and Diagnostics > Scripted Diagnostics`
5. In the left pane, click on**Scripted Diagnostics** to open its three items.  
![Open Scripted Diagnostics Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-scripted-diagnostics-policy.jpg)
6. Double-click on the first item and select the**Enable** option in the window that opens.  
![Enable Each Item in Scripted Diagnostics Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enable-items-of-scripted-diagnostics-policy.jpg)
7. Finally, tap on**Apply** and then**OK** .
8. Repeat steps 5 and 6 for the other two items of Scripted Diagnostics.

 Now close the Group Policy Editor and run the Windows Update Troubleshooter.

## Get the Windows Update Troubleshooter Working Again to Fix Update Errors

 It's important to have the Windows Update Troubleshooter running fine. Try the above fixes if it ever gets stuck or stops working. And ensure you can install essential updates to enjoy a smooth and secure Windows experience.

 You can also know more about security updates and why it makes sense to install them quickly.

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
<li><a href="https://win11.techidaily.com/unable-to-install-the-microsoft-pc-manager-on-windows-try-these-7-fixes/"><u>Unable to Install the Microsoft PC Manager on Windows? Try These 7 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-solutions-for-error-0x800704b3-in-windows-11-and-11/"><u>Unlocking Solutions for Error 0X800704B3 in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-fixing-unrecoverable-software-failures/"><u>Solutions for Fixing Unrecoverable Software Failures</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-spectacular-indulgent-pc-pastimes/"><u>[New] 2024 Approved  Spectacular Indulgent PC Pastimes</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-merging-your-guide-to-windows-efficiency/"><u>The Art of Merging: Your Guide to Windows Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/tailor-windows-screenshot-feature-to-suit-your-preferences/"><u>Tailor Windows Screenshot Feature to Suit Your Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/solving-mfc71udll-absence-in-windows-os/"><u>Solving Mfc71u.dll Absence in Windows OS</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-restart-tecno-spark-20c-without-power-button-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Restart Tecno Spark 20C Without Power Button | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/setup-wi-fi-extender-just-like-that-for-w7/"><u>Setup Wi-Fi Extender, Just Like That for W7</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-vivo-v27e-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset Vivo V27e | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-normalcy-after-windows-video-failures/"><u>Restoring Normalcy After Windows Video Failures</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-oppo-reno-9a-drfone-by-drfone-virtual-android/"><u>In 2024, Simple and Effective Ways to Change Your Country on YouTube App Of your Oppo Reno 9A | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-troubleshooting-winerror-0x80071a90/"><u>Understanding & Troubleshooting WinError 0X80071A90</u></a></li>
<li><a href="https://android-frp.techidaily.com/top-5-meizu-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Meizu Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-effortless-youtube-playback-downloading-content-to-idevices/"><u>[Updated] In 2024, Effortless Youtube Playback  Downloading Content to iDevices</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/apple-video-editing-essentials-top-software-choices/"><u>Apple Video Editing Essentials Top Software Choices</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-keep-word-reading-mode-active-when-handling-email-attachments/"><u>Tips to Keep Word Reading Mode Active When Handling Email Attachments</u></a></li>
<li><a href="https://win11.techidaily.com/tips-and-tricks-for-overcoming-the-msvcr120dll-deficiency-issue/"><u>Tips and Tricks for Overcoming the Msvcr120dll Deficiency Issue</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-essential-tips-for-youtube-shorts-success/"><u>[New] Essential Tips for YouTube Shorts Success</u></a></li>
<li><a href="https://win11.techidaily.com/6-high-performance-windows-video-editors-unveiled/"><u>6 High-Performance Windows Video Editors Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/winter-wonderland-offering-apps-from-microsofts-store/"><u>Winter Wonderland: Offering Apps From Microsoft's Store</u></a></li>
<li><a href="https://win11.techidaily.com/windows-enthusiasts-how-dxvk-shapes-your-gameplay/"><u>Windows Enthusiasts - How DXVK Shapes Your Gameplay</u></a></li>
<li><a href="https://win11.techidaily.com/triumph-in-windows-pricing-acquiring-top-product-keys/"><u>Triumph in Windows Pricing: Acquiring Top Product Keys</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-sticky-notebook-convergence-on-win11/"><u>Streamlining Sticky Notebook Convergence on Win11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/exploring-trending-video-reactions/"><u>Exploring Trending Video Reactions</u></a></li>
<li><a href="https://win11.techidaily.com/swift-strategies-for-fixing-dism-error-0x800f082f-in-windows/"><u>Swift Strategies for Fixing DISM Error: 0X800F082F in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/6-methods-to-supercharge-virtual-machine-speed-in-windows/"><u>6 Methods to Supercharge Virtual Machine Speed in Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-realme-note-50-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from Realme Note 50 to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-rapid-notification-curbing-guide/"><u>Windows 11: Rapid Notification Curbing Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unhighlight-your-windows-11-desktop-with-ease/"><u>Unhighlight Your Windows 11 Desktop with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/tech-savvy-collectors-dream-essential-612lifetime-windows-11-deal-awaits/"><u>Tech-Savvy Collectors' Dream: Essential $6.12/Lifetime Windows 11 Deal Awaits</u></a></li>
<li><a href="https://win11.techidaily.com/changing-windows-read-only-settings-easily/"><u>Changing Windows Read-Only Settings Easily</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-the-confusion-five-windows-cures-to-unsupported-boots/"><u>Clearing Up the Confusion: Five Windows Cures to Unsupported Boots</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-user-experience-in-windows-11/"><u>Transforming User Experience in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-system-call-failure-in-win1011-systems/"><u>Remedying System Call Failure in Win10/11 Systems</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-tips-for-finding-cracks-and-crunches-sounds-in-media-production/"><u>New Tips for Finding Cracks and Crunches Sounds in Media Production</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/virtual-horizons-on-android-a-guide-to-the-top-15-games-for-2024/"><u>Virtual Horizons on Android  A Guide to the Top 15 Games for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-final-cut-pro-for-students-unbeatable-prices-you-wont-want-to-miss/"><u>New Final Cut Pro for Students Unbeatable Prices You Wont Want to Miss</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-inability-to-remove-apps/"><u>Troubleshooting Windows' Inability to Remove Apps</u></a></li>
<li><a href="https://extra-resources.techidaily.com/cutting-edge-editing-tiktok-edition-unveiled/"><u>Cutting-Edge Editing  TikTok Edition Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-change-your-windows-11-username/"><u>Steps to Change Your Windows 11 Username</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-xiaomi-redmi-note-12-pro-5g-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Xiaomi Redmi Note 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-step-by-step-idevice-guide-for-youtube-video-upload/"><u>[New] Step-by-Step iDevice Guide for YouTube Video Upload</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-spotify-location-after-moving-to-another-country-on-tecno-spark-go-2023-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Spotify Location After Moving to Another Country On Tecno Spark Go (2023) | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/uniting-devices-android-and-windows-with-nearby-share/"><u>Uniting Devices: Android & Windows With Nearby Share</u></a></li>
</ul></div>
