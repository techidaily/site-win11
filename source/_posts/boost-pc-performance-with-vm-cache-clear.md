---
title: Boost PC Performance with VM Cache Clear
date: 2024-07-13T10:39:09.766Z
updated: 2024-07-14T10:39:09.766Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Boost PC Performance with VM Cache Clear
excerpt: This Article Describes Boost PC Performance with VM Cache Clear
keywords: Boost PC Speed,Enhance Computer PERF,Optimize System BOOST,Increase PC EFFICIENCY,Accelerate PC SPEED,Improve System PERFORMANCE,Enhance CPU Performance
thumbnail: https://thmb.techidaily.com/a8a2eae7840110809ce01981ae6ddd7381e7680b0d93e29805eecd4b92108f79.jpg
---

## Boost PC Performance with VM Cache Clear

 Are you having trouble with virtual memory on Windows 11? Resetting virtual memory on Windows can improve system performance or free up extra hard drive space. So, we'll show you exactly how to reset the virtual memory on your Windows 11 computer.

## What Is Virtual Memory and How Does It Work?

 Virtual memory, also known as a paging file, is a technology used in computers to allow programs to use more memory than what's physically available on it. When you run out of RAM, your operating system relies on virtual memory to continue running programs.

 The computer creates a special file called a page or swap file on the hard drive. It stores some data temporarily removed from RAM and written to the hard drive. This way, the computer can access more memory than what's installed.

 Although virtual memory allows programs to operate smoothly, it can also hurt overall performance. For example, if your computer runs out of RAM, it will use more of the hard drive to store data. This also significantly slows overall performance as HDDs and SSDs are much slower than RAM.

 Let's now see how to reset Virtual Memory on Windows.

## 1\. Use the System Properties window

 If you want to reset virtual memory settings on your Windows device, you can use the System Properties window. To do this, press **Win + R** on your keyboard to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).

 In the text box, type **sysdm.cpl**, and hit Enter. A system properties window will open up. Then, go to the **Advanced** tab and click the **Settings** button in the Performance section.

![How to Reset Virtual Memory on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-reset-virtual-memory-on-windows-11.jpg)

 This will open up the Performance Options window, where you can manage virtual memory settings. For this, switch to the **Advanced** tab and click on **Change** in the Virtual Memory section.

![Reset Page Size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-page-size.jpg)

 On the next screen, uncheck the **Automatically manage paging file size for all drives** checkbox and select the drive you want to configure virtual memory. Normally, this will be the drive on which Windows is installed.

 Set the custom size for virtual memory. Then, check the **No paging file** radio button and click **Set**. If you see a warning message, click **Yes** to confirm.

 After following the above steps, click **OK** to save your changes. Now close the System Properties and Settings windows and restart your computer. The new virtual memory settings should now be in effect.

## 2\. Use Group Policy Editor

 You can also use the Local Group Policy Editor to reset virtual memory settings on your Windows device. But remember that this method is only available on Pro and Enterprise editions.

 If you're using a Home edition, you should first [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To get started, open the Run dialog box and type **gpedit.msc** into the text box. Then click **OK** or press Enter to open the Local Group Policy Editor window.

![Clear virtual memory pagefile Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clear-virtual-memory-pagefile-using-group-policy.jpg)

 Then navigate to the following location:

Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Option

 Scroll down and double-click **Shutdown: Clear virtual memory pagefile** policy. In the Properties window, select Enabled and then click **Apply**. Next, click **OK** to save it.

## 3\. Use Registry Editor

 If you don't have access to the Local Group Policy Editor, you can also use the Registry Editor to reset virtual memory settings on Windows. Before proceeding, you should [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) in case something gets wrong.

![Reset Virtual Memory Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-virtual-memory-using-registry.jpg)

 To get started, search for **Registry Editor** in the Start menu and click on it. Once you open the Registry Editor, navigate to the following path:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management

 Next, double-click on the **ClearPageFileAtShutdown** key and set its value to **1**. Click on the **OK** button to save your changes.

## Reset Virtual Memory To Get Better Performance

 Resetting virtual memory settings improves Windows computer performance. This guide introduces three methods to learn how to reset virtual memory on Windows. Give it a try and see which methods work best for you. If you face any issues while doing this, you can always use system restore to revert to the previous settings.


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
<li><a href="https://win11.techidaily.com/bridge-android-and-windows-gameplay-unification-with-google-play/"><u>Bridge Android and Windows: Gameplay Unification with Google Play</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-vivo-v27e-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Vivo V27e FRP</u></a></li>
<li><a href="https://win11.techidaily.com/analyzing-surface-laptop-go-3-processor-boost-and-critique/"><u>Analyzing Surface Laptop Go 3: Processor Boost and Critique</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-fixed-gif-sizes-in-discord-for-windows-11-users/"><u>Unraveling the Mystery of Fixed GIF Sizes in Discord (for Windows 11 Users)</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-soar-high-and-stream-straight-dji-drone-techniques-for-facebook-live/"><u>In 2024, Soar High & Stream Straight - DJI Drone Techniques for Facebook Live</u></a></li>
<li><a href="https://vp-tips.techidaily.com/10-memetic-engineering-techniques-for-2024/"><u>10 Memetic Engineering Techniques for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unlocking-viral-potential-with-ai-driven-video-titles/"><u>In 2024, Unlocking Viral Potential with AI-Driven Video Titles</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-pc-recordings-win-5-budget-friendly-filters/"><u>Enhance PC Recordings: Win 5 Budget-Friendly Filters</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-to-run-the-sfc-tool-successfully/"><u>Essential Tips to Run the SFC Tool Successfully</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-to-vivo-y27-5g-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Vivo Y27 5G FRP Bypass With Best Methods</u></a></li>
<li><a href="https://win11.techidaily.com/5-clear-signals-its-time-for-windows-reset/"><u>5 Clear Signals It's Time for Windows Reset</u></a></li>
<li><a href="https://win11.techidaily.com/jumpstart-your-pc-quick-steps-into-windows-11s-safe-mode/"><u>Jumpstart Your PC: Quick Steps Into Windows 11'S Safe Mode</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-windows-1011-installing-a-unique-lock-pattern/"><u>Guide to Windows 10/11: Installing a Unique Lock Pattern</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-11-quality-over-novelties/"><u>Enhancing Windows 11: Quality over Novelties</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-screens-enhanced-brightness-controls/"><u>Mastering Windows Screens: Enhanced Brightness Controls</u></a></li>
<li><a href="https://win11.techidaily.com/controlling-delete-dialogues-for-secure-computing/"><u>Controlling Delete Dialogues for Secure Computing</u></a></li>
<li><a href="https://win11.techidaily.com/combat-winerror-0x800f0831-with-ease/"><u>Combat WinError 0X800F0831 with Ease</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-lava-blaze-curve-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Lava Blaze Curve 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-seamless-warhammer-gaming-on-windows-stop-stuttering/"><u>Achieving Seamless Warhammer Gaming on Windows: Stop Stuttering</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-capturing-stories-the-best-cinematographic-techniques/"><u>[New] Capturing Stories  The Best Cinematographic Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-network-diagnostics-timely-application-of-windows-ping/"><u>Navigating Network Diagnostics: Timely Application of Windows Ping</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-pc-what-to-do-when-windows-11-loses-a-tab/"><u>Enhance Your PC: What to Do When Windows 11 Loses a Tab?</u></a></li>
<li><a href="https://win11.techidaily.com/removing-default-homescreen-from-windows-11-setup/"><u>Removing Default Homescreen From Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-network-access-for-chrome-amidst-windows-security-barriers/"><u>Enabling Network Access for Chrome Amidst Windows Security Barriers</u></a></li>
<li><a href="https://win11.techidaily.com/defeating-inaccessible-program-uninstall-in-microsofts-latest-os/"><u>Defeating Inaccessible Program Uninstall in Microsoft's Latest OS</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-updater-error-0x80246007-in-windows-versions-1011/"><u>Fixing Updater Error 0X80246007 in Windows Versions 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-1011s-recycle-bin-crashes/"><u>Navigating Through Windows 10/11'S Recycle Bin Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/does-your-pc-tick-all-boxes-for-windows-11-upgrade/"><u>Does Your PC Tick All Boxes for Windows 11 Upgrade?</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/get-your-pcs-sound-recorded-download-x-recorder-for-2024/"><u>Get Your PC's Sound Recorded – Download X-Recorder for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-unwanted-files-from-your-c-drive/"><u>Banishing Unwanted Files From Your C: Drive</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-terminal-mastering-focus-mode-transitions/"><u>Navigating Windows Terminal: Mastering Focus Mode Transitions</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-inquiry-how-to-view-all-media-sharing-in-app-messages-for-2024/"><u>[Updated] Inquiry  How to View All Media Sharing in App Messages for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/explaining-and-correcting-the-msvcr110dll-deficit/"><u>Explaining & Correcting the msvcr110.dll Deficit</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-dism-failure-0x800f082f/"><u>Resolving Windows' DISM Failure 0X800F082F</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-a-detailed-overview-whats-new-with-nero-waveedit-2024-edition/"><u>Updated A Detailed Overview Whats New with Nero WaveEdit 2024 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/removing-updater-code-0x8019-issue-on-xp/"><u>Removing Updater Code 0X8019 Issue on XP</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-update-problem-with-error-0xca00a009/"><u>Mitigating Update Problem with Error 0xCA00A009</u></a></li>
</ul></div>
