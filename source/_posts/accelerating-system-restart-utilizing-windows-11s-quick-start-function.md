---
title: "Accelerating System Restart: Utilizing Windows 11'S Quick Start Function"
date: 2024-08-15T23:17:24.974Z
updated: 2024-08-16T23:17:24.974Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Accelerating System Restart: Utilizing Windows 11'S Quick Start Function"
excerpt: "This Article Describes Accelerating System Restart: Utilizing Windows 11'S Quick Start Function"
keywords: Win11 QuickRestart,QuickStart Windows,FastSystemInit,RestartBoostWin,Accelerate BootW11,RapidWindowsStartup,W11 QuickBoot
thumbnail: https://thmb.techidaily.com/8e684e3736085a42393dd155a637e8f217c26c390b45353b04f9ee1e79b6412e.jpg
---

## Accelerating System Restart: Utilizing Windows 11'S Quick Start Function

 Windows 11 has kept many of the useful features from its predecessor, including Fast Startup. As the name suggests, Fast Startup allows your computer to start up faster after a shutdown.

 Hibernate-capable Windows 11 systems come with Fast Startup enabled by default. If you want to turn on or off Fast Startup in Windows 11 manually, this guide will show you how.

## Why Should You Enable or Disable Fast Startup?

 With the release of Windows 8, Microsoft updated and renamed the default shutdown scenario as Fast Startup. It begins with the shutdown process by writing data to disk, similar to the hibernate process.

 However, unlike hibernation, it logs off all the user sessions and writes the remaining boot information to the hiberfil file. So, instead of loading everything from scratch, Windows loads data from the Hiberfil.sys file into memory when you restart your computer, significantly reducing the boot time.

 That said, Fast Startup is not without its shortcomings. For example, [according to Microsoft](http://docs.microsoft.com/en-us/troubleshoot/windows-client/deployment/updates-not-install-with-fast-startup), you may face difficulties installing Windows updates on Fast Startup-enabled systems. Another reason is the [missing dual boot option because of the disabled delayed start function](https://www.makeuseof.com/windows-10-dual-boot-option-not-showing/). To learn more, read our explainer on [how Fast Startup works and why you should disable it](https://www.makeuseof.com/what-is-windows-fast-startup-why-disable-it/).

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Check if Fast Startup Is On or Off

![check fast startup status windows 11 powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/check-fast-startup-status-windows-11-powershell.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

 Often, a major Windows feature update may overwrite the power settings and disable Hibernate, thus disabling Fast Startup. Or you may experience unusual boot behavior even when you think Fast Startup is on. Before attempting to troubleshoot your computer, check if Fast Startup is on or off.

 You can use Command Prompt to check the Fast Startup status:

1. Press the **Win** key and type **powershell**.
2. Right-click on **PowerShell** and select **Run as administrator**. Click **Yes** if prompted by User Account Control.
3. In the PowerShell console, copy and paste the following command and press Enter:  
`(GP "HKLM:\SYSTEM\CurrentControlSet\Control\Session Manager\Power")."HiberbootEnabled"`
4. The above command uses the **Get-Item (GP)** cmdlet to retrieve power-related settings and information about the **HiberBootEnabled** value in the Windows Registry.
5. A returned value of **1** means Fast Startup is On. A **0** would indicate Fast Startup as Off.

 If the hybrid boot is off, you can follow the steps below to enable Hibernation and then Fast Startup on your computer.

 To turn on Fast Startup, you must have Hibernate feature enabled on your computer. To check if Hibernate is enabled on your PC:

1. Press the **Win** key to open the **Start menu**.
2. Next, click on **Power** (power icon) and check if **Hibernate** is shown among other power options.
3. If disabled, the **Hibernate** option will not appear in the Power menu.

 Alternatively, check if Hibernate, while available, is hidden in the Control Panel. To do this:

1. Press **Win + R** to open **Run**.
2. Type **powercfg.cpl** and click **OK** to open Power Options in Control Panel.  
![choose what the power buttons do control panel windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/choose-what-the-power-buttons-do-control-panel-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
3. In the **Control Panel** dialog, click **Choose what the power buttons do** in the left pane.
4. Click **Change settings that are currently unavailable**.  
![enable disable fast startup control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/enable-disable-fast-startup-control-panel.png)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Under **Shutdown settings**, check if **Hibernate** is available. If available, select **Hibernate** and click **Save changes** to show **Hibernate** in the Power menu.

 If the Hibernate option is missing, you can enable it using a Command Prompt command.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Enable Hibernation in Windows 11

![turn on hibernate Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/turn-on-hibernate-Windows-11.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->

 Fast Startup is only available on systems compatible with the Hibernate feature available on almost all modern computers. However, this option is often disabled by default on lower-end systems.

 To enable Hibernate on Windows 11:

1. Type **cmd** in the Windows search bar.
2. Right-click on Command Prompt and select **Run as Administrator.**
3. In the Command Prompt window, type the following command and hit enter to turn on Hibernate:  
`Powercfg -h on`

 Now that you have enabled the hibernate feature, below are the various ways to enable and disable Fast Startup on your Windows computer.

## How to Turn On or Off Fast Startup in the Control Panel

![enable disable fast startup control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/enable-disable-fast-startup-control-panel.png)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->

 The easiest way to turn on Fast Startup is via the Control Panel's power settings. Here’s how to do it.

1. Press **Win + R** to open **Run**.
2. Type **control** and click **OK** to open the Control Panel.
3. Go to **System and Security** and then click on **Power Options**.
4. In the left pane, click on **Choose what the power buttons do.**
5. Next, click the **Change settings that are currently unavailable** link.
6. Under the **Shutdown settings** section, check the **Turn on fast startup (recommended)** option to turn on the feature.
7. Uncheck the **Turn on fast startup option** to disable Fast Startup.
8. Click **Save changes** to apply the changes.

## How to Turn On or Off Fast Startup Using the Registry Editor

![turn on off fast startup registry register](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/turn-on-off-fast-startup-registry-register.png)

 The next set of methods involves modifying the Windows registry. If something goes wrong, restoring your system to a functioning state can become difficult. So, [create a restore point](https://www.makeuseof.com/tag/create-system-restore-point/) before attempting to edit your registry entries. This will allow you to undo the changes if your system breaks during the process.

 Once done, do the following:

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**. Click **Yes** when prompted by UAC.
3. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Power`
4. You can also copy/paste the above path for quicker navigation.
5. In the right-pane, scroll down and locate the DWORD value **HiberbootEnabled.**
6. Right-click on **HiberbootEnabled** and select **Modify**.
7. Type **1** in the **Value data** field and click **OK** to save the changes.
8. To turn off Fast Startup, enter **0** in the **Value data** field and click **OK**.
9. Close the Registry Editor and reboot your computer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
## How to Turn On or Off Fast Startup Using a Registry File

![turn on off registry file fast startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/turn-on-off-registry-file-fast-startup.png)

 If you don’t want to work with the Registry Editor, you can create a REG file and run it to achieve the same. Here’s how to do it.

1. Press the **Win** key, search for the **Notepad** app and open it.
2. To enable Fast Startup, copy and paste the following code in the Notepad file:  
`Windows Registry Editor Version 5.00  
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Power]  
"HiberbootEnabled"=dword:00000001`
3. To disable fast startup, copy and paste the following code instead.  
`Windows Registry Editor Version 5.00  
[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Power]  
"HiberbootEnabled"=dword:00000000`
4. Click on **File** and select **Save As.**
5. Enter file name as **Enable\_fast\_startup.reg** or **Disable\_fast-startup.reg**.
6. Click on **Save as** type drop-down and select **All Files.**
7. Next, click **Save**.
8. Double-click on the **Enable\_fast-startup.reg** file to run. Then click **Yes**, and **Yes** to confirm the action.

## How to Enable or Disable Fast Startup in the Group Policy Editor

![require use of fast startup group policy editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/require-use-of-fast-startup-group-policy-editor-1.png)

 Group Policy Editor allows you to configure your Group Policy settings to allow or restrict features as required. You can use it to enable or disable the Fast Startup feature on your Windows computer.

 Note that the Group Policy Editor is only available in Windows Edu, Pro, and Enterprise editions of the OS. If you are running Home, here's how to [access the Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 Follow these steps to turn on Fast Startup on Windows 11:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open Group Policy Editor.
3. In Group Policy Editor, navigate to the following location:  
`Computer Configuration\Administrative Templates\System\Shutdown`
4. In the right pane, right-click on **Require use of fast startup** and select **Edit**.
5. Select **Enabled** to turn on Fast Startup.
6. Or Select **Disabled** to turn off Fast Startup.
7. Click **Apply** and **OK** to save the changes.

## How to Turn Off Fast Startup Using the Command Prompt

![disable fast startup hibernate Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/disable-fast-startup-hibernate-Windows-2.png)

 Since fast startup depends on the Hibernate feature, you can disable Hibernate to turn off Fast start. However, this will also turn off Hibernate in Power options, so tread carefully.

1. Press **Win + R** to open **Run**.
2. Type **cmd** into the box and then press **Ctrl + Shift + Enter** to open the Command Prompt as administrator.
3. In the Command Prompt window, type the following command and hit enter:  
`Powercfg -h off`
4. This will disable the Hibernate feature and also turn off Fast Startup.

## Making Your Windows 11 PC Boot Better

 The Fast Startup feature works like a charm on the older and slower systems with traditional HDDs or hybrid configurations. While you can shave off a few seconds even on an SSD, the incompatibility with dual boot and issues with Windows updates is an annoyance for many.

 Whether you want to turn Fast Startup on or off depends on what problem you are trying to solve. Try experimenting with the feature to see if it works for you. If not, you can always undo the changes.

 Hibernate-capable Windows 11 systems come with Fast Startup enabled by default. If you want to turn on or off Fast Startup in Windows 11 manually, this guide will show you how.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-design-thinking-for-content-creators-crafting-impactful-facebook-reels/"><u>[New] 2024 Approved  Design Thinking for Content Creators  Crafting Impactful Facebook Reels</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-how-to-archive-snaps-from-android-plus-mac-systems-for-2024/"><u>[New] How to Archive Snaps From Android + Mac Systems for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-understanding-and-applying-youtube-markup/"><u>[New] Understanding & Applying YouTube Markup</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-video-platforms-at-a-glance-comparing-vimeo-and-youtube/"><u>[New] Video Platforms at a Glance  Comparing Vimeo & YouTube</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-buffer-to-broadcast-learn-how-to-convert-your-youtube-viewing-into-a-screenshot-for-free/"><u>[Updated] 2024 Approved  From Buffer to Broadcast  Learn How to Convert Your YouTube Viewing Into a Screenshot for Free</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-efficient-obs-usage-live-skype-capture-tips-for-2024/"><u>[Updated] Efficient OBS Usage  Live Skype Capture Tips for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-leading-tag-tracker-software-on-major-platforms-like-fb-tweet-and-insta-for-2024/"><u>[Updated] Leading Tag Tracker Software on Major Platforms Like FB, Tweet & Insta for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-standing-out-strategies-for-top-users-on-snapchat/"><u>[Updated] Standing Out  Strategies for Top Users on Snapchat</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-clocking-down-the-big-day-10-best-mobile-apps-revealed/"><u>2024 Approved  Clocking Down the Big Day  10 Best Mobile Apps Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-image-snapshots-for-win-11-pcs/"><u>Adjusting Image Snapshots for Win 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-image-editing-techniques-for-subject-isolation/"><u>Advanced Image Editing: Techniques for Subject Isolation</u></a></li>
<li><a href="https://win11.techidaily.com/copying-powertoys-preferences-to-another-pc/"><u>Copying PowerToys Preferences to Another PC</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-clone-without-third-party-reliance-in-windows/"><u>Crafting Clone Without Third-Party Reliance in Windows</u></a></li>
<li><a href="https://tech-haven.techidaily.com/discover-how-to-leverage-chatgpts-capabilities-within-visual-studio-code/"><u>Discover How to Leverage ChatGPT's Capabilities Within Visual Studio Code</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-windows-error-0x80070522-enhance-client-access-control/"><u>Eliminate Window's Error 0X80070522: Enhance Client Access Control</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-x80072f30-quick-fix-for-windows-store-problems/"><u>Eliminate X80072F30: Quick Fix for Windows Store Problems</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-pre-use-disk-formatting-notice-on-windows/"><u>Eliminating Pre-Use Disk Formatting Notice on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-password-strength-in-windows-11-with-longer-pins/"><u>Enhancing Password Strength in Windows 11 with Longer Pins</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/cing-video-impact-interpreting-youtube-metrics-wisely-for-2024/"><u>Enhancing Video Impact  Interpreting YouTube Metrics Wisely for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-for-non-complying-windows-scripts/"><u>Essential Fixes for Non-Complying Windows Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-win-compatible-free-media-devices/"><u>Essential Guide: Win-Compatible Free Media Devices</u></a></li>
<li><a href="https://win11.techidaily.com/filter-irrelevant-notification-feedback-in-windows-11/"><u>Filter Irrelevant Notification Feedback in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/from-vanished-panes-to-visible-windows-essential-steps-for-recovering-hidden-screens-6-ways/"><u>From Vanished Panes to Visible Windows: Essential Steps for Recovering Hidden Screens (6 Ways)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-shortcuts-next-to-the-power-button-on-windows-11/"><u>How to Add Shortcuts Next to the Power Button on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-code-a-secure-window-for-hardware-unhook-in-win11/"><u>How to Code a Secure Window for Hardware Unhook in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-a-perfect-replica-of-your-drive/"><u>How to Make a Perfect Replica of Your Drive</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-the-updated-method-to-bypass-vivo-v27-pro-frp-by-drfone-android/"><u>In 2024, The Updated Method to Bypass Vivo V27 Pro FRP</u></a></li>
<li><a href="https://win11.techidaily.com/insight-into-windows-11s-new-automated-data-safeguarding/"><u>Insight Into Windows 11’S New Automated Data Safeguarding</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-window-pc-always-unlocked/"><u>Keep Your Window PC Always Unlocked</u></a></li>
<li><a href="https://win11.techidaily.com/key-techniques-for-win10-blue-screen-resolution/"><u>Key Techniques for Win10 Blue Screen Resolution</u></a></li>
<li><a href="https://win11.techidaily.com/microsofts-ai-hub-enhancing-shopping-experience/"><u>Microsoft’s AI Hub – Enhancing Shopping Experience</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-accessibility-features/"><u>Navigating Through Windows' Accessibility Features</u></a></li>
<li><a href="https://win11.techidaily.com/notetaking-renaissance-discovering-obsidians-visuality/"><u>Notetaking Renaissance: Discovering Obsidian's Visuality</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-installer-errors-in-windows-10-and-11/"><u>Overcoming Windows Installer Errors in Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/personalized-pixels-designing-unique-displays-on-each-monitor-of-windows/"><u>Personalized Pixels: Designing Unique Displays on Each Monitor of Windows</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-modify-indexer-in-windows/"><u>Step-by-Step: Modify Indexer in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-eliminate-server-stumbled-errors-in-microsoft-store/"><u>Steps to Eliminate Server Stumbled Errors in Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-android-fun-for-windows-users-through-google-play/"><u>Streamlining Android Fun for Windows Users Through Google Play</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-git-operations-with-github-desktop-and-windows-1011/"><u>Streamlining Git Operations with GitHub Desktop & Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/swift-keystrokes-in-win-os-a-guide-to-eliminate-delay/"><u>Swift Keystrokes in WIN OS: A Guide to Eliminate Delay</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-search-service-not-available-on-windows/"><u>Tackling Search Service Not Available on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-web-sites-becoming-win-desktops/"><u>The Art of Web Sites Becoming Win Desktops</u></a></li>
<li><a href="https://win11.techidaily.com/the-sound-surge-5-apps-to-take-windows-volume-well-above-100/"><u>The Sound Surge: 5 Apps to Take Windows' Volume Well Above 100%%</u></a></li>
<li><a href="https://win11.techidaily.com/trouble-removing-epic-games-hub-from-windows-11-a-quick-guide/"><u>Trouble Removing Epic Games Hub From Windows 11: A Quick Guide</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-realme-12-proplus-5g-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Realme 12 Pro+ 5G Screen | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-office-outlook-alerts-in-windows/"><u>Troubleshooting Non-Functional Office Outlook Alerts in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-speed-setback-by-apps-with-innocuous-exteriors/"><u>Windows 11’S Speed Setback by Apps with Innocuous Exteriors</u></a></li>
</ul></div>
