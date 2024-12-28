---
title: Steps to Address Post-Win 11 Upgrade Linux Issues
date: 2024-12-22T07:35:11.221Z
updated: 2024-12-28T06:32:33.613Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Address Post-Win 11 Upgrade Linux Issues
excerpt: This Article Describes Steps to Address Post-Win 11 Upgrade Linux Issues
keywords: Win 11 Linux Fix,Win 11 Boot Failure,Win 11 Update Linux,Win 11 System Repair,Post-Win Upgrade Issues,Win 11 OS Troubleshoot,Fixing Win 11 Linux
thumbnail: https://thmb.techidaily.com/e937c769751b4b8235d825da190a8de514c18ce6c728b4bc630fa21c8db2efdc.jpg
---

## Steps to Address Post-Win 11 Upgrade Linux Issues

 There are several potential reasons why Windows Subsystem for Linux (WSL) stopped working after your PC was upgraded to Windows 11\. Thankfully, the breakdown is unlikely to be terminal, although you might have to try a few different fixes to get it working once again.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 Here are several ways to get the Windows Subsystem for Linux working again after upgrading to Windows 11.

## 1\. Check That WSL Is Enabled

 It isn't unusual that upgrading to a newer version of the OS will break some apps and features. So although it might sound obvious, checking WSL hasn't simply been disabled during the upgrade process should be your first step. Here's how to check:

![checking if WSL is enabled in Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-enabled.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. In Windows Search, type**Turn Windows features on or off** and click the search result that should appear at the top.
2. In the Windows System dialog, scroll down until you see**Windows Subsystem for Linux** .
3. If the checkbox for the feature is not selected, do so now. Then click**Ok** .
4. You might also need to restart your computer before checking to see if that fixed the problem.

 Hopefully, WSL is now working, and you can begin using the tool. If not, read on for some other possible solutions.

 Learn more about the[things you can do with WSL and Linux](https://www.makeuseof.com/pros-cons-windows-subsystem-for-linux/) on your Windows computer.

## 2\. Enable Hyper-V and Virtual Machine Platform

 If you want to use a subsystem such as WSL in Windows, you'll also need to enable the virtualization tools. These include Hyper-V and the Virtual Machine Platform.

![Error message in the command line interface](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-feature-missing.jpg)

 If a command line interface opens, telling you a required feature is not installed, when you try to run your Linux distribution, this is likely what it refers to.

1. Search for**Turn Windows features on or off** and click the search result.
2. In Windows Features, scroll down to find**Virtual Machine Platform** and**Windows Hypervisor Platform** .
3. Check the boxes next to each of these features and then click**Ok** .
4. You will need to restart your computer to complete the installation of these tools.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RCYs8keh-Vs?si=uDC28-9yh-k6HLj4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UUPt2zKtJ5k?si=LLHdsFDLzVByJsKj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a[full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

## Fixing WSL After Upgrading to Windows 11

 Upgrading to Windows 11 usually goes smoothly, but apps and features can occasionally break. If you find that WSL is no longer working after upgrading to the newest Windows OS, don't worry, there is usually an easy fix. You might only need to re-enable the feature in the Windows system settings, but if not, running through the other fixes here will usually solve the problem.

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
<li><a href="https://fox-glue.techidaily.com/new-in-2024-cadence-captors-embrace-free-online-tempo-apps/"><u>[New] In 2024, Cadence Captors – Embrace Free Online Tempo Apps</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-quickest-quads-2022-olympics-skate-for-2024/"><u>[New] The Quickest Quads 2022 Olympics Skate for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-updated-youtube-income-guidelines/"><u>[Updated] In 2024, Updated YouTube Income Guidelines</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-the-finest-chromebook-pencil-stores-you-need-to-know-about-for-2024/"><u>[Updated] The Finest Chromebook Pencil Stores You Need to Know About for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/contribution-margin-cm-750000/"><u>Contribution Margin (CM) = $750,000</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/direct-screen-capture-chromium-version-for-2024/"><u>Direct Screen Capture Chromium Version for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/fixing-netflix-connectivity-problems-on-roku-a-step-by-step-guide/"><u>Fixing Netflix Connectivity Problems on Roku - A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/managing-system-resources-for-effective-remote-device-operations/"><u>Managing System Resources for Effective Remote Device Operations</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-telnet-setup-in-wins-10-and-11/"><u>Mastering Telnet Setup in Wins 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-key-missteps-a-comprehensive-guide-to-rectify-windows-non-working-shortcuts/"><u>Overcome Key Missteps: A Comprehensive Guide to Rectify Windows Non-Working Shortcuts</u></a></li>
<li><a href="https://win-rankings.techidaily.com/prepare-your-budget-microsoft-announces-costly-windows-11-updates-beginning-next-year-insights-from-zdnet/"><u>Prepare Your Budget: Microsoft Announces Costly Windows 11 Updates Beginning Next Year - Insights From ZDNet</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-vlc-input-unaccessible-error-in-windows/"><u>Remedy VLC Input Unaccessible Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-restrictive-windows-shield-on-win-11/"><u>Repairing Restrictive Windows Shield on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-1011-requests-old-passcode/"><u>Tackling Windows 10/11 Requests Old Passcode</u></a></li>
<li><a href="https://win11.techidaily.com/trick-easy-emoji-15-integration-for-windows-11-users/"><u>Trick: Easy Emoji 15 Integration for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-and-fixing-directdraw-errors-in-win1011-systems/"><u>Unraveling and Fixing DirectDraw Errors in WIN10/11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-widget-masterclass-the-ultimate-guide/"><u>Windows 11 Widget Masterclass: The Ultimate Guide</u></a></li>
</ul></div>

