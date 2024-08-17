---
title: Troubleshooting Windows' High Resource Consumption Due to UnrealCEFSubprocess
date: 2024-08-16T00:42:57.557Z
updated: 2024-08-17T00:42:57.557Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Windows' High Resource Consumption Due to UnrealCEFSubprocess
excerpt: This Article Describes Troubleshooting Windows' High Resource Consumption Due to UnrealCEFSubprocess
keywords: Windows High ResConsume,Troubleshoot CEFSubusage,UnrealCEFResourceIssue,ReduceWindowsResourceLoss,FixHighCPUWindowsUsage,CEFsubprocessMemoryBloat,OptimizeWindowsResourceHalt
thumbnail: https://thmb.techidaily.com/39b1aa90cbe15af25eeef086af2b40b5abbe4ea0e44addc2aa4ec5af37792daa.jpg
---

## Troubleshooting Windows' High Resource Consumption Due to UnrealCEFSubprocess

 Is the UnrealCEFSubprocess process consuming hefty CPU and RAM resources in the Task Manager, causing your games to crash? Does it keep straining your hardware even after you close all the active programs and apps? You may also have seen it multiply in the Task Manager, which might have made you believe it's a virus.

 There's no need to worry; it's not a virus but a legitimate process belonging to Valorant. Below, we'll discuss why this process consumes many system resources and how you can reduce its resource usage to relieve the strain on your hardware.

## Why Does the UnrealCEFSubprocess Process Consume High CPU and RAM Resources?

 UnrealCEFSubprocess is a legitimate Valorant process, so it shouldn't overload your system resources. If this process starts to strain your hardware and cause CPU, RAM, or GPU usage to spike in the Task Manager, it's either not functioning correctly, or other processes are interfering with it.

 As many users pointed out in a[Reddit thread](https://www.reddit.com/r/ValorantTechSupport/comments/z66n1b/unrealcefsubprocessexe%5Fmultiplying%5Fand%5Fputting/) , one of the major causes of high resource consumption by this process is the interference from Windows' built-in security suite, Windows Defender, and third-party antivirus software, primarily AVG antivirus and Avast antivirus. If you are using security software, then it might be causing the issue.

## Can You Disable the UnrealCEFSubprocess Process via the Task Manager?

 Disabling the UnrealCEFSubprocess process could adversely affect your active gaming session in Valorant. The gaming elements this process controls or handles will crash and behave abnormally. Because of this, we do not advocate closing it down.

 Furthermore, Valorant or the Riot client will automatically relaunch this process the next time you open them, so disabling only the process won't solve the issue. Therefore, we recommend that you fix the underlying problem rather than only disabling this process.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
## How to Stop the UnrealCEFSubprocess Process From Taking Up Too Much RAM and CPU

 The easiest way to reduce UnrealCEFSubprocess's CPU and RAM consumption is to[permanently disable Windows Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/) , the built-in security software in Windows, and uninstall any third-party antivirus software you currently use. Even though doing this is easy and quick, we don't recommend it. Why is that?

 The Windows Defender and third-party antivirus software installed on your laptop are a solid defense against viruses and malware. They prevent any potentially harmful agents from wreaking havoc on your device. If you delete or disable them, you will remove your frontline fighters and allow enemies to attack your territory with no fear.

 These security suites would likely have already quarantined many threats and blocked potentially harmful files from affecting your computer. Disabling or deleting them can release these threats and remove restrictions on malicious files. Consequently, this could negatively affect your computer in the long run.

 Considering the risks associated with it, it would be wise not to disable security software right away. Instead of that, you can whitelist the UnrealCEFSubprocess process in them. Whitelisting any file instructs security software not to interfere with it. Therefore, whitelisting the file associated with this process will prevent antivirus programs from interfering with it.

 Consequently, you will be successful in reducing resource consumption without compromising your security.

### How to Whitelist UnrealCEFSubprocess From Windows Defender

 Follow these steps to whitelist UnrealCEFSubprocess from Windows Defender:

1. Type**"Windows Security"** in Windows Search and open the**Windows Security** app.  
![Open Windows Security from Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/1-open-windows-security-from-windows-search.jpg)
2. Go to the**Firewall and network protection** tab on the left.
3. Click on the**Allow an app through the firewall** link on the right side of the screen.  
![Click on the Allow an App Through the Firewall Link in Windows Security App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/2-click-on-the-allow-an-app-through-the-firewall-link-in-windows-security-app.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Click on**Change settings** .
5. Click on**Allow another app** .  
![Click on Allow Another App in the Windows Defender Firewall Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3-click-on-allow-another-app-in-the-windows-defender-firewall-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. In the**Add an app** window, click on the**Browse** button.  
![Click on the Browse Button in the Add an App Window in the Windows Defender Firewall Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/4-click-on-the-browse-button-in-the-add-an-app-window-in-the-windows-defender-firewall-settings.jpg)
2. Then, go to the following path:  
`C:\Program Files\Riot Games\VALORANT\live\Engine\Binaries\Win64`
3. Here, select**UnrealCEFSubProcess** from the list.  
![Select UnrealCEFSubprocess to Create an Exclusion for It](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-select-unrealcefsubprocess-to-create-an-exclusion-for-it.jpg)
4. Then, click on**Add** .  
![Click on the Add Button After Selecting the Relevant Process](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/6-click-on-the-add-button-after-selecting-the-relevant-process.jpg)
5. After that, check the**Public** and**Private** boxes next to the**UnrealCEFSubProcess** process and click**OK** .  
![Click OK After Checking the Public and Private Boxes Next to the UnrealCEFSubprocess in the Windows Firewall Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/7-click-ok-after-checking-the-public-and-private-boxes-next-to-the-unrealcefsubprocess-in-the-windows-firewall-settings.jpg)
6. Restart your computer after whitelisting this process.

**I** f you have installed Valorant in a different folder or your operating system resides on a different drive, change the path above to reflect the proper location.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### How to Whitelist UnrealCEFSubprocess From Avast Antivirus

 Follow these steps to whitelist UnrealCEFSubprocess from Avast Antivirus:

1. Launch Avast Antivirus.
2. Click the**Menu** button (represented by three horizontal lines stacked over each other) in the top-right of the screen.
3. Go to**Settings** .  
![Go to Settings in Avast Antivirus App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/8-go-to-settings-in-avast-antivirus-app.jpg)
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Go to the**Exceptions** tab in the**General** settings.
5. Click on**Add Exception** .  
![Click on Add Exception in the General Settings in Avast Antivirus App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/9-click-on-add-exception-in-the-general-settings-in-avast-antivirus-app.jpg)
6. Click**Browse** in the**Add exception** window.  
![Click Browse in the Add Exception Window in Avast Antivirus App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/10-click-browse-in-the-add-exception-window-in-avast-antivirus-app.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
7. Navigate to the following path if you haven't changed the default installation path when installing Valorant:  
`C:\Program Files\Riot Games\VALORANT\live\Engine\Binaries\Win64`
8. Check the box beside**UnrealCEFSubprocess** and click**OK** .  
![Click OK After Checking the Box Beside UnrealCEFSubprocess in Avast Antivirus App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/11-click-ok-after-checking-the-box-beside-unrealcefsubprocess-in-avast-antivirus-app.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. After that, restart your computer once, and hopefully, the process won't overtax your computer's resources anymore.

### How to Whitelist UnrealCEFSubprocess From AVG Antivirus

 The interface of AVG antivirus is almost identical to Avast antivirus. So, you can whitelist UnrealCEFSubprocess from it by following the steps outlined above. Once you have whitelisted the file,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) once, and hopefully, the resource consumption by this process will decrease significantly.

 According to some users, whitelisting the UnrealCEFSubprocess file from AVG antivirus doesn't always reduce its resource consumption. Due to this, users had to delete AVG antivirus from their computers. So, if whitelisting the file doesn't reduce the load on your hardware, you can delete the AVG antivirus.

 Before doing that,[turn on Windows Defender](https://www.makeuseof.com/turn-on-microsoft-defender/) if it's off, or install alternative antivirus software to replace AVG and keep your computer safe from incoming threats.

 If you use an antivirus software other than the two listed above and the UnrealCEFSubprocess process consumes more than half of your system resources, you need to whitelist the UnrealCEFSubprocess file there as well. If you are not familiar with the whitelisting process, visit the antivirus software's official website.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Don't Let the UnrealCEFSubprocess Process Overburden Your Hardware

 The UnrealCEFSubprocess process consumes a lot of resources, which leaves barely any resources for other processes. Consequently, your games and apps will take a long time to load and crash frequently—enough to ruin your gaming experience.

 You should now better understand why this process consumes a lot of resources and what you can do to fix it. Therefore, whitelist the UnrealCEFSubprocess process in your security program, and if that does not solve the issue, disable or uninstall your antivirus.


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
<li><a href="https://win11.techidaily.com/4-proven-strategies-for-enhancing-window-shot-taking-on-windows-os/"><u>4 Proven Strategies for Enhancing Window Shot Taking on Windows OS</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-tecno-spark-10-5g-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Tecno Spark 10 5G to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/androids-premier-gamers-app-an-in-depth-look-at-kinemaster-for-2024/"><u>Android's Premier Gamer's App  An In-Depth Look at KineMaster for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-failure-in-updates-due-to-0x800f0845/"><u>Avoiding Failure in Updates Due to 0X800f0845</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-upgrade-issue-error-xc004f050-on-windows-os/"><u>Bypassing Upgrade Issue: Error XC004f050 on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/check-physical-connections-make-sure-cables-are-firmly-connected-if-you-have-external-monitors-or-projectors-with-separate-brightness-controls/"><u>Check Physical Connections: Make Sure Cables Are Firmly Connected if You Have External Monitors or Projectors with Separate Brightness Controls</u></a></li>
<li><a href="https://win11.techidaily.com/correct-misplaced-second-display-on-windows-11/"><u>Correct Misplaced Second Display on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-mixed-user-microsoft-login-issues/"><u>Dealing with Mixed-User Microsoft Login Issues</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-your-pcs-core-generating-and-reviewing-data/"><u>Deciphering Your PC’s Core: Generating & Reviewing Data</u></a></li>
<li><a href="https://win11.techidaily.com/echoes-of-the-past-amplifying-vintage-games-with-shaders/"><u>Echoes of the Past: Amplifying Vintage Games with Shaders</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-entry-points-to-troubled-boots-in-win-writable-steps/"><u>Eliminate Entry Points to Troubled Boots in Win' Writable Steps</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-windows-colour-mismanagement-issues/"><u>Eliminate Windows Colour Mismanagement Issues</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-folder-context-menus-on-windows-11/"><u>Enhancing Folder Context Menus on Windows 11</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/-uninterrupted-viewing-top-20-youtube-download-apps/"><u>Enjoy Uninterrupted Viewing  Top 20 YouTube Download Apps</u></a></li>
<li><a href="https://win11.techidaily.com/expert-insights-into-windows-booting-system-customization/"><u>Expert Insights Into Windows Booting System Customization</u></a></li>
<li><a href="https://win11.techidaily.com/file-sharing-mastery-constructing-python-servers-in-windows/"><u>File Sharing Mastery: Constructing Python Servers in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fix-inflexible-scrollbar-issue-in-microsoft-excel-2016/"><u>Fix Inflexible Scrollbar Issue in Microsoft Excel 2016</u></a></li>
<li><a href="https://win11.techidaily.com/fix-steams-inaccessible-game-content-on-latest-windows-11/"><u>Fix Steam's Inaccessible Game Content on Latest Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-a-non-functional-printer-in-the-os-environment/"><u>Fixing a Non-Functional Printer in the OS Environment</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-overscan-in-windows-enhance-screen-fit/"><u>Fixing Overscan in Windows - Enhance Screen Fit</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-engage-immediate-assist-feature-windows-11/"><u>How to Engage Immediate Assist Feature: Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-this-app-has-been-blocked-by-your-system-administrator-error-in-windows/"><u>How to Fix This App Has Been Blocked by Your System Administrator Error in Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-vivo-t2-pro-5g-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix Vivo T2 Pro 5G Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-windows-files-writable-stop-read-only/"><u>How to Make Windows Files Writable: Stop Read-Only</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-prevent-sleep-state-in-windows-11s-usb-cores/"><u>How to Prevent Sleep State in Windows 11'S USB Cores</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-contacts-from-xperia-1-v-by-fonelab-android-recover-contacts/"><u>How to Rescue Lost Contacts from Xperia 1 V?</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-open-your-apple-iphone-8-without-a-home-button-drfone-by-drfone-ios/"><u>In 2024, How To Open Your Apple iPhone 8 Without a Home Button | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/instagram-video-troubleshooting-no-silence-full-sound/"><u>Instagram Video Troubleshooting - No Silence, Full Sound</u></a></li>
<li><a href="https://win11.techidaily.com/launching-quake-mode-using-windows-terminal/"><u>Launching Quake Mode: Using Windows Terminal</u></a></li>
<li><a href="https://tech-haven.techidaily.com/masterclass-crafting-unique-characters-for-dungeons-and-dragons-via-chatgpt-and-dall-e/"><u>Masterclass: Crafting Unique Characters for Dungeons & Dragons via ChatGPT and DALL-E</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-clickers-the-best-auto-click-cars-and-keys/"><u>Masterful Clickers: The Best Auto Click Cars & Keys</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-quick-access-uwp-apps-shortcuts-on-windows-11/"><u>Mastering Quick Access: UWP Apps Shortcuts on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-and-solve-frozen-shift-problems/"><u>Navigate and Solve Frozen Shift Problems.</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-no-fingerprint-detection-error-on-windows/"><u>Overcoming the No Fingerprint Detection Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unauthorized-access-errors-in-windows-environment/"><u>Overcoming Unauthorized Access Errors in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/quick-remedies-for-unsynchronized-google-drive-on-pc/"><u>Quick Remedies for Unsynchronized Google Drive on PC</u></a></li>
<li><a href="https://win11.techidaily.com/secure-uniqueness-5-ways-to-avoid-local-name-clashes-on-windows/"><u>Secure Uniqueness: 5 Ways to Avoid Local Name Clashes on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/simple-fixes-resetting-windows-setup-post-reboot/"><u>Simple Fixes: Resetting Windows Setup Post-Reboot</u></a></li>
<li><a href="https://win11.techidaily.com/simplified-steps-to-activate-windows-media-player/"><u>Simplified Steps to Activate Windows Media Player</u></a></li>
<li><a href="https://win-amazing.techidaily.com/solution-found-fixing-the-igfxem-module-failure-issue/"><u>Solution Found: Fixing the 'IgfxEM Module Failure' Issue</u></a></li>
<li><a href="https://program-issues.techidaily.com/step-by-step-solution-to-prevent-fifa-20-from-crashing-on-your-computer-detailed-guide/"><u>Step-by-Step Solution to Prevent FIFA 20 From Crashing on Your Computer [Detailed Guide]</u></a></li>
<li><a href="https://win11.techidaily.com/stepping-up-to-full-operating-system-windows-for-steam-deck/"><u>Stepping Up to Full Operating System: Windows for Steam Deck</u></a></li>
<li><a href="https://win11.techidaily.com/stop-windows-update-pushes-instantly-with-these-methods/"><u>Stop Windows Update Pushes Instantly With These Methods</u></a></li>
<li><a href="https://win11.techidaily.com/tapping-into-windows-settings-for-cpu-states/"><u>Tapping Into Windows Settings for CPU States</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-your-desktops-aesthetic-essential-theme-tips-for-win11/"><u>Transforming Your Desktop's Aesthetic: Essential Theme Tips for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-error-0x8007007e/"><u>Troubleshooting Windows Error 0X8007007E</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-low-power-modes/"><u>Understanding Windows' Low-Power Modes</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-changing-picture-preview-size/"><u>Windows 11: Changing Picture Preview Size</u></a></li>
<li><a href="https://win11.techidaily.com/windows-revenue-strategies-for-microsofts-profits/"><u>Windows Revenue Strategies for Microsoft's Profits</u></a></li>
</ul></div>
