---
title: Steps to Address Post-Win 11 Upgrade Linux Issues
date: 2024-08-28T00:52:35.735Z
updated: 2024-08-29T00:52:35.735Z
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
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads end -->
4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a[full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-footage.techidaily.com/new-audiovisual-authority-the-finest-computers-for-professional-edits-for-2024/"><u>[New] Audiovisual Authority  The Finest Computers for Professional Edits for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-maximizing-b-roll-effective-techniques/"><u>[New] Maximizing B-Roll  Effective Techniques</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-nurturing-nature-in-the-metropolis-a-new-paradigm-for-cities/"><u>[New] Nurturing Nature in the Metropolis  A New Paradigm for Cities</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-a-step-by-step-approach-to-snapchat-video-communication-for-2024/"><u>[Updated] A Step-By-Step Approach to Snapchat Video Communication for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-the-beginners-blueprint-for-dynamic-illustration/"><u>2024 Approved  The Beginner's Blueprint for Dynamic Illustration</u></a></li>
<li><a href="https://extra-hints.techidaily.com/chronology-of-success-best-release-schedule/"><u>Chronology of Success  Best Release Schedule</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/control-youtube-audio-mobiledesktop-approach-for-2024/"><u>Control YouTube Audio  Mobile/Desktop Approach for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/cracking-the-code-locating-blue-screens-in-log-files/"><u>Cracking the Code: Locating Blue Screens in Log Files</u></a></li>
<li><a href="https://win11.techidaily.com/customize-win11-optimal-predefined-window-sizes/"><u>Customize Win11: Optimal Predefined Window Sizes</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-dismantling-error-0x80246007-in-w10w11/"><u>Deciphering and Dismantling Error 0X80246007 in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-interface-with-three-column-widgets-in-win11/"><u>Elevate Your Interface with Three-Column Widgets in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-ui-quality-with-dpi-tuning/"><u>Elevating UI Quality with DPI Tuning</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-file-management-and-editing-learn-to-use-text-actions-in-snip/"><u>Enhance File Management & Editing: Learn to Use Text Actions in Snip</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/get-up-close-with-the-cycwagen-cargo-e-bike-an-in-depth-experience-report/"><u>Get Up Close with the CycWagen Cargo E-Bike: An In-Depth Experience Report</u></a></li>
<li><a href="https://win11.techidaily.com/hibernate-havoc-heres-how-to-quell-the-chaos/"><u>Hibernate Havoc? Here's How to Quell the Chaos</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-adopt-educational-aesthetics-in-win-11/"><u>How to Adopt Educational Aesthetics in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-common-rainmeter-issues-on-windows/"><u>How to Fix Common Rainmeter Issues on Windows</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-icloud-lock-from-your-apple-iphone-15-and-ipad-by-drfone-ios/"><u>How to fix iCloud lock from your Apple iPhone 15 and iPad</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-successfully-shut-down-your-pc-running-windows-n-11-when-faced-with-problems/"><u>How To Successfully Shut Down Your PC Running Windows N 11 When Faced With Problems</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-tackle-the-killer-javascript-issue-on-discord-windows-11/"><u>How to Tackle the Killer Javascript Issue on Discord Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-use-phone-clone-to-migrate-your-oppo-find-x6-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Use Phone Clone to Migrate Your Oppo Find X6 Data? | Dr.fone</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/e-tips-for-maximizing-your-creator-studio-potential-for-2024/"><u>Inside Tips for Maximizing Your Creator Studio Potential for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/locate-and-engage-with-windows-11-privilege-center/"><u>Locate and Engage with Windows 11 Privilege Center</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-kali-linux-setup-on-windows/"><u>Mastering Kali Linux Setup on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-stopping-self-generating-chromium-tabs/"><u>Mastering the Art of Stopping Self-Generating Chromium Tabs</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-savings-on-windows-11-keys/"><u>Maximizing Savings on Windows 11 Keys</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-fullscreen-challenges-with-sonic-gameplay-w11-version/"><u>Navigating Fullscreen Challenges with Sonic Gameplay, W11 Version</u></a></li>
<li><a href="https://win11.techidaily.com/quick-and-effective-windows-note-tips-and-tricks/"><u>Quick and Effective Windows Note Tips & Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-correcting-the-isdonedll-error-on-windows-11/"><u>Quick Fix: Correcting the ISDone.dll Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-remedy-restoring-functionality-to-your-windows-pen-device/"><u>Quick Remedy: Restoring Functionality to Your Windows Pen Device</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-your-roadmap-to-printer-success-in-windows-11/"><u>Quick-Fix Guide: Your Roadmap to Printer Success in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/recovering-from-frozen-windows-itunes-a-step-by-step-approach/"><u>Recovering From Frozen Windows iTunes: A Step-by-Step Approach</u></a></li>
<li><a href="https://win11.techidaily.com/reignite-the-joy-of-win-11-gaming-master-these-seven-game-changing-tweaks/"><u>Reignite the Joy of Win 11 Gaming: Master These Seven Game-Changing Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/removing-unwanted-html-from-your-windows-11-mail-previews/"><u>Removing Unwanted HTML From Your Windows 11 Mail Previews</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-windows-adjustments-through-quick-key-tricks/"><u>Seamless Windows Adjustments Through Quick Key Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resurrect-ccleaner-in-windows-11/"><u>Steps to Resurrect CCleaner in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-elevating-taskmanager-position/"><u>Techniques for Elevating TaskManager Position</u></a></li>
<li><a href="https://win11.techidaily.com/the-fusion-of-ages-seven-windows-characteristics-persisting-into-11/"><u>The Fusion of Ages: Seven Windows Characteristics Persisting Into 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-subtle-art-of-hidden-storage-in-windows-1110/"><u>The Subtle Art of Hidden Storage in Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-integrating-alternate-antivirus-without-defenders-restrictions/"><u>Tips for Integrating Alternate Antivirus without Defender’s Restrictions</u></a></li>
<li><a href="https://win11.techidaily.com/top-7-strategies-for-successful-folders-management-in-win-11/"><u>Top 7 Strategies for Successful Folders Management in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/transform-videos-on-windows-discover-these-8-outstanding-apps/"><u>Transform Videos on Windows - Discover These 8 Outstanding Apps</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-ai-in-windows-11-the-co-pilot-effect/"><u>Understanding AI in Windows 11: The Co-Pilot Effect</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-potential-virus-clues-in-windows-task-scheduling/"><u>Understanding Potential Virus Clues in Window's Task Scheduling</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-screens-activatingdeactivating-windows-spotlight-features/"><u>Unlocking Screens: Activating/Deactivating Windows' Spotlight Features</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-roblox-error-403-on-windows/"><u>Unraveling Roblox Error 403 on Windows</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-peer-to-peer-dialogue-hubs-a-review-of-reliable-user-friendly-and-amusing-applications/"><u>Updated 2024 Approved Peer-to-Peer Dialogue Hubs A Review of Reliable, User-Friendly & Amusing Applications</u></a></li>
<li><a href="https://win11.techidaily.com/windows-wisdom-3-strategies-for-directory-expedition/"><u>Windows Wisdom: 3 Strategies for Directory Expedition</u></a></li>
</ul></div>
