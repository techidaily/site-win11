---
title: Renewal of Erased Windows 11 Energy Profiles
date: 2024-08-23T06:08:26.176Z
updated: 2024-08-24T06:08:26.176Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Renewal of Erased Windows 11 Energy Profiles
excerpt: This Article Describes Renewal of Erased Windows 11 Energy Profiles
keywords: Win11EnergyProf Renew,Win11ProProfile Update,EnergySaveWin11 Renew,Win11PowerProf Fresh,ProfilesWin11 Reboot,Windows11 Revamp Eco,ProfileUpdate11 WinEnergy
thumbnail: https://thmb.techidaily.com/d04a298cb4efeef55fca68d7eaf14aa0f3c43f69fcef497082e91bf17afd4582.jpg
---

## Renewal of Erased Windows 11 Energy Profiles

 Windows 11 and 10 come with preset power plans: High Performance, Power Saver, Balanced, and sometimes Ultimate Performance. You can switch between these plans to get the best performance, more battery life or a bit of both worlds. Some laptop manufacturers, like HP, have their own power plan, like HP Recommended.

 However, often after installing a Windows update, default power plans can go missing, or you may see only one power plan. This can also happen if you have made changes to your power plans recently. In any case, here are a few troubleshooting steps to help restore the missing default power plans on Windows 11 and 10 running systems.

## How to Check Which Power Plan Is Missing

![check missing power plans control panel windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/check-missing-power-plans-control-panel-windows-11.jpg)

 Depending on your system hardware specification, you may see three or four power plans in the Power Options panel. Balanced, Power Saver and High Performance are the most common in all Windows computers.

 However, higher-end hardware running Windows 11\\10 Pro can have the Ultimate Performance Power plan as well. It is a preset power plan to help boost your system performance in a professional setup. Even if available, enabling the[Ultimate Performance power plan may not be necessary for most users](https://www.makeuseof.com/should-you-enable-ultimate-performance-power-plan-windows-10/) .

 You can check the available and missing power plans on Windows from Control Panel:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK**
3. In the**Control Panel** , open**Hardware and Sound.**
4. Next, click on**Power Options** .
5. Expand the**Show additional plans** section.

## 1\. Change Power Mode From the Settings Panel

![change power mode windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-power-mode-windows-11.jpg)

[On Windows 11, you can change the power mode from the Settings app](https://www.makeuseof.com/windows-11-change-power-plan/) . You can choose between the Best power efficiency, Balanced, and Best performance power modes in the Power & battery settings.

To change power mode on Windows 11:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Power & battery** .
3. Click the drop-down for**Power mode** and select your preferred power plan.

 If the Power Mode doesn’t show any or some power schemes, you’ll need to restore it using the powercfg command-line utility.

## 2\. Reset the Default Power Plan Settings Using Power PowerShell

![](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reset-default-power-plans-windows-11-powershell.jpg)

 Before you try to restore the power plans, reset all the power plan settings to factory default. A reset will only fix issues that occurred due to incorrect configuration.

To reset Windows default power plans:

1. [Open PowerShell with administrator rights.](https://www.makeuseof.com/windows-11-powershell-administrator/)
2. In the PowerShell window, type the following command and press**Enter** :  
`powercfg -restoredefaultschemes`
3. The above command will reset default power schemes. Close PowerShell and check for any improvements.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Restore the Missing Power Plan Using the Command Prompt

![restore default power plan windows 11 command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restore-default-power-plan-windows-1-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
 You can restore the missing default power plans on Windows using the Command Prompt. We’ll use the**powercfg** command-line feature to duplicate the existing but missing power plans.

 Follow these steps to restore the missing control power schemes. Make sure to only execute the commands for the power control schemes that are missing. Otherwise, it will create duplicate entries for the same power plan in Power Options.

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command Prompt** and select**Run as administrator** .
3. In the Command Prompt window, type the following command and press Enter:  
`[High Performance]  
powercfg -duplicatescheme 8c5e7fda-e8bf-4a96-9a85-a6e23a8c635c  
[Balanced]  
powercfg -duplicatescheme 381b4222-f694-41f0-9685-ff5bb260df2e  
[Power Saver]  
powercfg -duplicatescheme a1841308-3541-4fab-bc81-f71556f20b4a  
[Ultimate Performance]  
powercfg -duplicatescheme e9a42b02-d5df-448d-aa00-03f14749eb61`
4. If successfully executed, type**exit** and press**Enter** to close Command Prompt.

 Next, open**Control Panel** and go to**Power Options** to check if the missing power plans are restored on your Windows computer.

## 4\. Enable the High Performance Power Plan Using Command Prompt

![enable high performance plan windows command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-high-performance-plan-windows-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
 You can use a different**powercfg** command to enable the High Performance power plan on Windows. This is useful if your system is missing only the High Performance power scheme. Here’s how to do it.

1. [Open Command Prompt with administrator rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. In the Command Prompt window, type the following command and press**Enter** :  
`powercfg /s SCHEME_MIN`
3. After the command is executed, close the Command Prompt window.
4. Next, go to **Control Panel > Hardware and Sound > Power Options** . Here, you can use the**High Performance** power plan.

 If the power plans are still missing, check if Modern Standby (S0) is enabled. If yes, you’ll need to disable Modern Standby to restore the missing power plans.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Disable Modern Standby (S0) to Restore Default Power Plans

 If you have a Modern Standby (S0) compatible system, check if this sleep state is enabled. When enabled, the default power plans may be disabled to prevent any conflict when the system is in a low-power idle state.

 As you may have guessed already, in this situation, you’ll need to[disable Modern Standby (S0) on Windows](https://www.makeuseof.com/windows-disable-modern-standby/) to restore the default power plans on Windows. After you disable Modern Standby (S0), open Power Options to use the default power plans.

 Conversely, you may encounter BSOD and other critical errors after disabling Modern Standby (S0). If yes, enable Modern Standby again to fix the issues.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Manually Create the Power Plans

 If you don’t want to use the preset power plans, you can create your own power plans on Windows. This should work irrespective of the Modern Standby state of your computer.

To create a custom Power Plan on Windows:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**
3. Go to**Hardware and Sound.**
4. Next, click on**Power Options** .  
![control panel create power plan windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/control-panel-create-power-plan-windows-11.jpg)
5. In the left pane, click on**Create a Power Plan.**  
![control panel create power plan power saver windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/control-panel-create-power-plan-power-saver-windows-11.jpg)
6. Next, select the power plan you want to restore and enter a name for the plan under the**Plan name field.**  
![control panel create power plan configure](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/control-panel-create-power-plan-configure.jpg)
7. Next, configure the settings for the new power plan.
8. Click**Create** .\`

 Your new custom power plan will appear in Power Options. To remove the power plan, unselect the plan and click on**Change plan** settings. Next, click on**Delete this plan** and click**OK** .

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
## Restore the Missing Default Power Plans on Windows

 Power plans on your Windows laptops help you manage how your device uses power. If you don’t see the power schemes on Windows, try to reset the default power plans using PowerShell. Similarly, you can also use PowerShell to duplicate and restore the existing power plans.

 That said, not seeing the Ultimate Performance power plan in Power Options is not unusual. By default, it is only available on high-end Windows hardware and disabled to prevent battery draining. But you can still enable it using a PowerShell cmdlet. For most users, however, the balanced power plan offers a great balance between performance and battery life.


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
<li><a href="https://youtube-docs.techidaily.com/024-approved-unveiling-the-secrets-of-popularity-a-guide-to-15-best-opener-plans/"><u>[New] 2024 Approved  Unveiling the Secrets of Popularity  A Guide to 15 Best Opener Plans</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-flash-fixing-fame-is-it-youtubes-shorts-or-tiktok-for-quick-content-conquest/"><u>[New] In 2024, Flash-Fixing Fame  Is It YouTubes Shorts or TikTok for Quick Content Conquest?</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-mastering-the-game-tiktoks-most-notable-players/"><u>[New] In 2024, Mastering the Game  TikTok's Most Notable Players</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-no-limit-visual-capturer-device/"><u>[New] In 2024, No-Limit Visual Capturer Device</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-premium-free-service-craft-your-own-discord-emblem/"><u>[New] Premium Free Service  Craft Your Own Discord Emblem</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-deciphering-youtube-monetization-success-codes-for-2024/"><u>[Updated] Deciphering YouTube Monetization Success Codes for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-achieve-seamless-video-playback-by-removing-bars-in-youtube/"><u>2024 Approved  Achieve Seamless Video Playback by Removing Bars in YouTube</u></a></li>
<li><a href="https://games-able.techidaily.com/9-remedies-troubleshoot-steams-unwritable-library/"><u>9 Remedies: Troubleshoot Steam's Unwritable Library</u></a></li>
<li><a href="https://ai-video.techidaily.com/breaking-language-barriers-elevate-your-content-with-the-best-free-video-translator-apps/"><u>Breaking Language Barriers Elevate Your Content with the Best Free Video Translator Apps</u></a></li>
<li><a href="https://tech-hub.techidaily.com/comparative-edge-of-ai-titans-pitting-gpt-against-microsoftgoogles-contenders/"><u>Comparative Edge of AI Titans: Pitting GPT Against Microsoft/Google's Contenders</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-inaccessible-recycle-bin-status-in-win11/"><u>Correcting Inaccessible Recycle Bin Status in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-system-monitoring-add-analyzer-to-windows-context-menu/"><u>Enhance System Monitoring: Add Analyzer to Windows Context Menu</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-security-by-safe-disabling-of-windows-11-features/"><u>Enhancing Security by Safe Disabling of Windows 11 Features</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-successful-utorrent-deployment-on-windows-pcs/"><u>Enhancing Successful uTorrent Deployment on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-system-accessibility-with-elevated-privileges/"><u>Enhancing System Accessibility with Elevated Privileges</u></a></li>
<li><a href="https://change-location.techidaily.com/here-are-some-of-the-best-pokemon-discord-servers-to-join-on-samsung-galaxy-z-fold-5-drfone-by-drfone-virtual-android/"><u>Here are Some of the Best Pokemon Discord Servers to Join On Samsung Galaxy Z Fold 5 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-apple-iphone-se-2020-without-anyone-knowing-drfone-by-drfone-virtual-ios/"><u>How To Leave a Life360 Group On Apple iPhone SE (2020) Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-utilize-windows-hello-biometric-lock-in-windows-11/"><u>How to Utilize Windows Hello Biometric Lock in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-system-efficiency-through-cpu-settings/"><u>Maximizing System Efficiency Through CPU Settings</u></a></li>
<li><a href="https://tech-haven.techidaily.com/nonewchatter-when-will-open-again/"><u>NoNewChatter: When Will Open Again?</u></a></li>
<li><a href="https://win11.techidaily.com/open-component-services-on-windows-11-an-insiders-view/"><u>Open Component Services on Windows 11: An Insider's View</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-system-failure-windows-error-0x8007045d/"><u>Overcoming System Failure - Windows Error 0X8007045D</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/overcoming-typographical-troubles-resetting-spellcheck-on-microsoft-outlook/"><u>Overcoming Typographical Troubles: Resetting Spellcheck on Microsoft Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/powershell-for-professionals-automated-archive-operations/"><u>PowerShell for Professionals: Automated Archive Operations</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-delete-functionality-on-windows-systems/"><u>Reinstating Delete Functionality on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-ms-store-error-code-0x80073d26-on-windows-11-os/"><u>Remedying MS Store Error Code 0X80073D26 on Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-path-errors-on-windows-810-systems/"><u>Remedying PATH Errors on Windows 8/10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-0x80070194-on-onedrive-and-windows-oses/"><u>Resolving 0X80070194 on OneDrive & Windows OSes</u></a></li>
<li><a href="https://hardware-help.techidaily.com/shop-now-experience-crystal-clear-4k-gaming-with-alienwares-aw3225qf-secure-a-100-discount-on-the-ultimate-curved-oled-monitor-at-240-hz-refresh-rate/"><u>Shop Now: Experience Crystal Clear 4K Gaming with Alienware's AW3225QF - Secure a $100 Discount on the Ultimate Curved OLED Monitor at 240 Hz Refresh Rate</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-your-click-process-with-mouse-settings-tweak/"><u>Simplify Your Click Process with Mouse Settings Tweak</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-selecthighlight-problems-in-windows-pdfs/"><u>Solutions for Select/Highlight Problems in Windows PDFs</u></a></li>
<li><a href="https://win11.techidaily.com/solving-non-operational-keys-on-your-windows-machine/"><u>Solving Non-Operational Keys on Your Windows Machine</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-fix-for-invalid-system-id-alert-in-win11/"><u>Step-by-Step Fix for Invalid System ID Alert in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-prevent-csgo-launch-issues-on-windows-11/"><u>Strategies to Prevent CS:GO Launch Issues on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-online-journey-with-gesture-controls-in-ms-edge-win-11-edition/"><u>Streamline Your Online Journey with Gesture Controls in MS Edge, Win 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-application-transfer-onto-windows-11-systems/"><u>Streamlining Application Transfer Onto Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/the-path-to-perfected-notes-on-obsidian-canvas/"><u>The Path to Perfected Notes on Obsidian Canvas</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-nvidias-geforce-error-in-windows-os/"><u>Troubleshooting Nvidia's GeForce Error in Windows OS</u></a></li>
<li><a href="https://techtrends.techidaily.com/twitch-service-outage-platform-or-personal-connection-issue/"><u>Twitch Service Outage: Platform or Personal Connection Issue?</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-11s-full-gaming-potential-directdraw-tips/"><u>Unlocking Windows 11'S Full Gaming Potential: DirectDraw Tips</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/whats-the-best-voice-changer-for-youtubers-in-2024/"><u>What’s the Best Voice Changer for YouTubers, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-sales-how-does-microsoft-earn/"><u>Windows 11 Sales - How Does Microsoft Earn?</u></a></li>
<li><a href="https://win11.techidaily.com/windows-networks-decoded-arp-cache-understanding/"><u>Windows Networks Decoded: ARP Cache Understanding</u></a></li>
</ul></div>
