---
title: Swiftly Overcoming Stuck Windows Update Fixer
date: 2024-06-25T10:07:38.057Z
updated: 2024-06-26T10:07:38.057Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Swiftly Overcoming Stuck Windows Update Fixer
excerpt: This Article Describes Swiftly Overcoming Stuck Windows Update Fixer
keywords: Quick Windows Fix,Unstuck Updates,Swift Update Help,Fast Windows Repair,Stop Update Failure,Speedy Windows Solve,Rapid Fixer Window
thumbnail: https://thmb.techidaily.com/87f89d3b15c9e03d195fa4c767fb7770437292a210562c1ab5e7ca0ee4b18377.jpg
---

## Swiftly Overcoming Stuck Windows Update Fixer

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

 But you can clear or flush the DNS cache to resolve security and internet connectivity issues. Check out[how to flush the DNS cache on Windows](https://www.makeuseof.com/flush-dns-cache-windows/) for more information on how to do this.

 If the process is successful, you will get the confirmation message of the DNS Resolver Cache being successfully flushed. Now try running the Windows Update Troubleshooter.

## 3\. Restart Windows Cryptographic Services

 At times, an erratic or stopped Windows Cryptographic Services can cause problems in the smooth running of the Windows Update Troubleshooter.

 Cryptographic Services is an inbuilt Windows feature that provides encryption, decryption, and verification services. If it doesn't work properly, Windows Update Troubleshooter may also malfunction.

To fix this, you can try restarting Cryptographic Services.

1. Search for**Services** in**Windows Search** and click on the**Services app** under**Best match** . Or use one of the[many ways to open Services](https://www.makeuseof.com/windows-11-open-services-app/) .
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

 You can quickly learn how to run the SFC and DISM, and also explore how they work. Check out our piece on the[differences between CHKDSK, SFC, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) for the full low-down.

 After these scans finish running, try running the Windows Update Troubleshooter again.

## 5\. Update System Drivers

 Computer drivers enable Windows and its components to communicate and function efficiently. So it's good for you to[know what drivers are and why you should keep them updated](https://www.makeuseof.com/computer-drivers-what-are-they-why-should-you-update/) .

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

 Though it's not available on Windows Home, you can still[access the Group Policy Editor by enabling it](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

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
<li><a href="https://win11.techidaily.com/breaking-barriers-easily-uninstall-applications-in-win-11/"><u>Breaking Barriers: Easily Uninstall Applications in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-advanced-backup-capabilities/"><u>Unlock Advanced Backup Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-d3d11-gpu-error-on-windows-11-and-10/"><u>Troubleshooting D3D11 GPU Error on Windows 11 & 10</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-10-file-organization-hacks-max-156/"><u>Streamlining Windows: 10 File Organization Hacks (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-chatgpt-is-at-capacity-right-now-error-on-windows/"><u>How to Fix the ChatGPT Is at Capacity Right Now Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-screen-brilliance-adjustments-in-windows-11/"><u>Mastering Screen Brilliance Adjustments in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-for-cannot-locate-gpeditmsc-windows-problems/"><u>Essential Fixes for Cannot Locate Gpedit.msc Windows Problems</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-mastering-unboxing-expert-tips-and-tricks/"><u>[New] Mastering Unboxing  Expert Tips and Tricks</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-permanently-quit-youtube-shorts-now/"><u>[Updated] Permanently Quit YouTube Shorts Now</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-in-2024-ways-on-how-to-liven-up-your-animate-website-on-scroll/"><u>New In 2024, Ways on How to Liven Up Your Animate Website on Scroll</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-in-2024-finding-luts-made-by-danny-gevirtz/"><u>New In 2024, Finding LUTs Made by Danny Gevirtz</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-broadcast-in-ultra-hd-on-the-social-network/"><u>In 2024, Broadcast in Ultra HD on the Social Network</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-fundamentals-the-core-terms-in-vr-worlds/"><u>2024 Approved  Fundamentals  The Core Terms in VR Worlds</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-ispoofer-on-oppo-f23-5g-drfone-by-drfone-virtual-android/"><u>How to use iSpoofer on Oppo F23 5G? | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/reduce-share-and-enjoy-top-5-shortened-urls-for-youtube/"><u>Reduce, Share and Enjoy  Top 5 Shortened URLs for YouTube</u></a></li>
</ul></div>
