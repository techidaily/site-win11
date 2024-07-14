---
title: "A Step-by-Step Approach: Extracting Device IDs From Windows PCs"
date: 2024-07-13T11:11:13.200Z
updated: 2024-07-14T11:11:13.200Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes A Step-by-Step Approach: Extracting Device IDs From Windows PCs"
excerpt: "This Article Describes A Step-by-Step Approach: Extracting Device IDs From Windows PCs"
keywords: Extract Device ID,Windows Device ID,PC Device ID,Steps for Device ID,Windows PC Device ID,Device Extraction Guide,PC Device Identification
thumbnail: https://thmb.techidaily.com/7fab9a6185158d097b206408c1b02e98fd2b514b00431bdf0c9ec5881d711d0e.jpg
---

## A Step-by-Step Approach: Extracting Device IDs From Windows PCs

 A hardware ID is a unique identification number given to hardware components. It’s associated with the devices that you attach to your PC or the ones already connected to it.

 This identification number can be helpful when you want to download the correct device drivers. That's because if you know the hardware ID, then you can use it to search for a specific driver online.

 Let’s discover the various ways to check your hardware IDs on Windows.

## 1\. Use the Device Manager

 The Device Manager is a tool that helps you tweak the settings for almost all the devices that are connected to your PC. You can also use this tool to update or reinstall the device drivers.

 Now, let’s check out how you can use the Device Manager to search for the hardware IDs:

1. Press**Win + Run** to open the Run command dialog box. Alternatively, check out [the various ways to access the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**devmgmt.msc** and press**Enter** to open the Device Manager.
3. Expand the category for the device you want to look up. For example, expand the**Keyboards** category if you want the hardware ID for your keyboard.
4. Right-click on the relevant device and select**Properties** .
5. Navigate to the**Details** tab.
6. Click the**Property** drop-down menu and select**Hardware Ids** . You should see the hardware ID results in the "Value" box.

![Clicking the Property drop-down menu and selecting Hardware Ids](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/clicking-the-property-drop-down-menu-and-selecting-hardware-ids.jpg)

 You might often see more than one ID in the "Value" box. In such instances, you should only focus on the hardware ID that appears at the top.

 Don’t confuse a hardware ID with a compatible ID. A hardware ID is a unique identification number given to a specific device. Meanwhile, a compatible ID is a generic identification number given to a group of devices.

## 2\. Use the Command Prompt

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 The Command Prompt is an incredible tool that helps you access most apps, configure system settings, and troubleshoot device issues. You can also perform other tricks with it, such as checking the hardware IDs for your devices.

Let’s check out the steps you need to follow:

1. Press**Win + R** to open the Run command dialog box.
2. Type**CMD** and press**Ctrl + Shift + Enter** to open an elevated Command Prompt.
3. Type the following command to get a list of all your drivers and devices:

`Dism /Online /Get-Drivers /all /Format:Table`

![Displaying device information on the Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/displaying-device-information-on-the-command-prompt.jpg)

 Now, let’s say you want the hardware ID for the mouse. Here’s how you can search for it:

1. Scroll down on the Command Prompt results and locate**Mouse** in the "Class Name" category.
2. In the same row, check the option that appears in the "Published Name" category.

![Selecting the mouse option "msmouse" in the Command Prompt results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-mouse-option-in-the-command-prompt-results-1.jpg)

 In this case, the option in the "Published Name" category is**msmouse.inf** .

 Now that you've found the "Published Name" result for the mouse, here's how you can use it to find the hardware ID:

1. Open a new**Command Prompt** window by following the previous steps.
2. Type the following command and replace**Published Name** with the relevant command:

`Dism /Online /Get-DriverInfo /Driver:Published Name`

 For example, we discovered earlier that the "Published Name" result for the mouse is**msmouse.inf** . If we insert this into the command above, then the result should be as follows:

`Dism /Online /Get-DriverInfo /Driver:msmouse.inf`

 Now, press**Enter** once you’ve typed in the correct command. From there, locate the "Hardware ID" option from the results.

![Selecting the Hardware ID option in the Command Prompt screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-hardware-id-option-in-the-command-prompt-screen.jpg)

## 3\. Use PowerShell

 Alternatively, you can also check the hardware IDs using [Windows PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . It’s another incredible tool that allows you to run various commands.

 Let’s explore how you can check the hardware IDs using this tool:

1. Press**Win + R** to open the Run command dialog box.
2. Type**PowerShell** and press**Ctrl + Shift + Enter** to open the elevated PowerShell window.
3. Type the following command to get a list of your drivers and devices:

`Get-PnpDevice -PresentOnly | Sort-Object -Property &ldquo;Class&rdquo; | Format-Table -AutoSize`

![PowerShell window displaying device information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/powershell-window-displaying-device-information.jpg)

 Now, look for your target device under the "FriendlyName" category.

 For example, let’s say your target device is the keyboard. In this case, the option that appears in the "FriendlyName" category for the keyboard is**Standard PS/2 Keyboard** .

 After finding your target device, check the**Instance ID** (the value that appears in the last column).

![Selecting the Keyboard option from the PowerShell command options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-keyboard-option-from-the-powershell-command-options.jpg)

 For the keyboard, the Instance ID is**ACPI\\IDEA0102\\4&15E808EC&0** .

 Now that you've found the Instance ID, here’s how you can use it to find the hardware ID:

1. Open an**elevated PowerShell window** as per the previous steps.
2. Type the following command and replace the**Instance Id** command with the relevant option:

`Get-PnpDeviceProperty -InstanceId "Instance Id" | Format-Table -AutoSize`

 If we use the Instance ID for the keyboard (ACPI\\IDEA0102\\4&15E808EC&0), then the command should be as follows:

`Get-PnpDeviceProperty -InstanceId "ACPI\IDEA0102\4&15E808EC&0" | Format-Table -AutoSize`

 Now, press**Enter** to run the command. From there, look for the**DEVPKEY\_Device\_HardwareIds** option under the**KeyName** category.

 Next, look for the corresponding value in the "Data" category. The value that appears in this section is the hardware ID.

![Selecting the hardware ID option on PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-hardware-id-option-on-powershell.jpg)

 In this case, the hardware ID for the keyboard (which appears in the "Data" category) is**ACPI\\VEN\_IDEA&DEV\_0102** .

## 4\. Use the Windows Device Console

 The Device Console (DevCon) is a feature that shows you detailed information about the devices on your computer. This tool can also help you configure, install, remove, enable, or disable devices.

 Interestingly, this tool allows you to view the hardware IDs of multiple apps simultaneously. Unfortunately, the Device Console isn’t built-in on your device. This means you need to download and install it first.

 Let’s check out how you can install this tool and use it to check the hardware IDs:

1. Download and install the [Windows Drivers Kit](https://learn.microsoft.com/en-us/windows-hardware/drivers/other-wdk-downloads) from the Microsoft website. When you're on the site, head to the**Step 2: Install the WDK** section and pick an app that’s compatible with your device.
2. Once you’ve installed the tool, open**File Explorer** and navigate to **This PC > Local Disk (C:) > Program Files (x86) > Windows Kits > 10 > Tools** . If you’re using Windows 11, the path should be **This PC > Local Disk (C:) > Program Files (x86) > Windows Kits > 11 > Tools** .
3. Access the**x64** (64-bit) folder if you're using a 64-bit device or the**x86** (32-bit) folder if you use a 32-bit PC. If you’re unsure what to pick,[check your Windows PC specs](https://www.makeuseof.com/ways-to-check-your-windows-10-essential-pc-specs/) first.

![Selecting the x64 folder in the Tools section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-x64-folder-in-the-tools-section.jpg)

Once you’re in the correct folder, follow these steps:

1. Click the**File Explorer address bar** .
2. Type**CMD** and then press**Enter** . This will run the Command Prompt within the current folder.

![Typing the CMD command in the File Explorer address bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/typing-the-cmd-command-in-the-file-explorer-address-bar.jpg)

 From there, type the following command into the Command Prompt and press**Enter** :

`devcon hwids *`

![Displaying hardware IDs using DevCon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/displaying-hardware-ids-using-devcon.jpg)

 This will show you the details of all the devices on your computer. The results will also contain the hardware IDs.

 For example, we've highlighted the hardware ID for the**Standard PS/2 Keyboard** in the image below.

![Selecting the hardware ID for the Standard PS2 Keyboard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/selecting-the-hardware-id-for-the-standard-ps2-keyboard.jpg)

 Remember, if there’s more than one hardware ID, always pick the first option. This means the hardware ID for the keyboard, in the example above, is**ACPI\\VEN\_IDEA&DEV\_0102** .

 If you want to explore the Device Console in detail, check out [the various ways to use Dev Con](https://learn.microsoft.com/en-us/windows-hardware/drivers/devtest/devcon-examples) on the Microsoft website.

## You've Successfully Found the Hardware IDs of Your Devices

 Hardware IDs make it easy for you to identify all your devices and drivers. The good news is that it's quite easy to find these IDs.

 If you want to check your hardware IDs quickly, try the Device Manager method in this article. Otherwise, any of the other methods we’ve covered should help.


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
<li><a href="https://win11.techidaily.com/decoding-and-fixing-frequent-rainmeter-setbacks-an-easy-guide/"><u>Decoding and Fixing Frequent Rainmeter Setbacks: An Easy Guide</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-the-windows-activation-error-0x8007251d-and-how-do-you-fix-it/"><u>What Is the Windows Activation Error 0X8007251D and How Do You Fix It?</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-decoding-fbs-interface-how-to-find-just-watched-content-for-2024/"><u>[Updated] Decoding FB's Interface  How To Find Just-Watched Content for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-losses-commit-to-daily-windows-data-archiving/"><u>Avoid Losses: Commit to Daily Windows Data Archiving</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-deleted-characters-a-guide-for-windows-users/"><u>Restoring Deleted Characters: A Guide for Windows Users</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/2024-approved-windows-video-editing-top-imovie-alternatives-for-pc-users/"><u>2024 Approved Windows Video Editing Top iMovie Alternatives for PC Users</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-honor-x8b-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Honor X8b Devices | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/perfect-your-playback-implementing-a-countdown-in-obs/"><u>Perfect Your Playback  Implementing a Countdown in OBS</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-into-the-depths-of-screen-capture-a-youtube-perspective-for-idevices/"><u>In 2024, Into the Depths of Screen Capture  A YouTube Perspective for iDevices</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-rediscovering-missing-panes-top-tips-and-hacks-for-windows-users/"><u>The Ultimate Guide to Rediscovering Missing Panes: Top Tips and Hacks for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-address-dying-function-keys-adjusting-screen-brightness/"><u>Solutions to Address Dying Function Keys Adjusting Screen Brightness</u></a></li>
<li><a href="https://win11.techidaily.com/post-install-windows-heres-how-to-get-online/"><u>Post-Install Windows? Here's How to Get Online</u></a></li>
<li><a href="https://techidaily.com/repair-video-tool-repair-all-your-damaged-video-files-of-xiaomi-14-pro-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>Repair Video Tool - Repair all your damaged video files of Xiaomi 14 Pro on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/averting-steam-library-write-errors-on-modern-windows-pcs/"><u>Averting Steam Library Write Errors on Modern Windows PCs</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-a-comprehensive-guide-to-locating-and-creating-superb-instagram-alarms/"><u>[New] 2024 Approved  A Comprehensive Guide to Locating and Creating Superb Instagram Alarms</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-overcome-microsoft-store-crash-0x80073d26/"><u>Strategies to Overcome Microsoft Store Crash: 0X80073D26</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-there-are-so-many-music-recording-software-in-the-market-today-free-and-paid-which-makes-it-tough-to-choose-therefore-we-gather-10-best-free-music-r/"><u>Updated There Are so Many Music Recording Software in the Market Today, Free and Paid, Which Makes It Tough to Choose. Therefore, We Gather 10 Best Free Music Recording Software for You</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-elevate-needed-errors-with-ease-in-windows-os/"><u>Bypassing 'Elevate Needed' Errors with Ease in Windows OS</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-stream-anything-from-realme-12-5g-to-apple-tv-drfone-by-drfone-android/"><u>In 2024, How To Stream Anything From Realme 12 5G to Apple TV | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-crafting-perfect-tones-with-curvature-techniques/"><u>In 2024, Crafting Perfect Tones with Curvature Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/1719338109987-windows-desk-icons-clashing-find-harmony/"><u>Windows Desk Icons Clashing - Find Harmony</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/energy-savings-calculations-while-not-directly-impacting-installation-cost-understanding-potential-energy-savings-is-crucial-for-long-term-roi-analysis-for-/"><u>__Energy Savings Calculations__  While Not Directly Impacting Installation Cost, Understanding Potential Energy Savings Is Crucial for Long-Term ROI Analysis. For 2024</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-and-thrive-harnessing-the-power-of-wintoys/"><u>Optimize and Thrive: Harnessing the Power of Wintoys</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-resource-utilization-in-wsl-android/"><u>Best Practices for Resource Utilization in WSL-Android</u></a></li>
<li><a href="https://win11.techidaily.com/reinvigorating-the-stuck-windows-start-menu-symbol/"><u>Reinvigorating the Stuck Windows Start Menu Symbol</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-space-windows-11s-disk-defragmentation-guide/"><u>Maximizing Space: Windows 11'S Disk Defragmentation Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-shadows-tackling-wacatacbml-on-microsoft-windows/"><u>Unveiling the Shadows: Tackling Wacatac.B!ml on Microsoft Windows</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-full-screen-display-defeating-windows-overscan/"><u>Optimize Full-Screen Display: Defeating Windows Overscan</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-essential-tiktok-to-gif-convertors-reviewed-for-2024/"><u>[Updated] Essential TikTok-to-GIF Convertors Reviewed for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-dormant-slack-alerts-on-modern-windows-pcs/"><u>Reinstating Dormant Slack Alerts on Modern Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/the-unseen-file-transfer-integrating-zip-into-image-files-win/"><u>The Unseen File Transfer: Integrating ZIP Into Image Files (WIN)</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-instructions-for-setting-up-dolby-atmos-in-windows-1111/"><u>In-Depth Instructions for Setting Up Dolby Atmos in Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-dynamic-walls-in-windows-11-for-enhanced-aesthetics/"><u>The Art of Dynamic Walls in Windows 11 for Enhanced Aesthetics</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/nvidia-and-intel-synchro-on-win10-end-of-switchable-graphics-woes/"><u>NVIDIA & Intel Synchro on Win10: End of Switchable Graphics Woes</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-the-fast-lane-to-excellent-captioning-a-guide-to-impressive-fb-media-posts/"><u>In 2024, The Fast Lane to Excellent Captioning  A Guide to Impressive FB Media Posts</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-snapshot-surge-no-money-required-image-uplift/"><u>[New] Snapshot Surge  No Money Required Image Uplift</u></a></li>
<li><a href="https://win11.techidaily.com/guides-to-fix-non-opening-photoshop-on-latest-windows-11/"><u>Guides to Fix Non-Opening Photoshop on Latest Windows 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastering-chromatics-a-practical-approach/"><u>[New] Mastering Chromatics  A Practical Approach</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-instagram-story-upgrade-how-to-add-music-effectively/"><u>[New] In 2024, Instagram Story Upgrade  How to Add Music Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-multi-selection-activating-windows-11s-checkboxes/"><u>Efficient Multi-Selection: Activating Windows 11'S Checkboxes</u></a></li>
<li><a href="https://some-guidance.techidaily.com/strategies-for-securing-youtubers-as-sponsors-for-2024/"><u>Strategies for Securing YouTubers as Sponsors for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-past-fatal-js-error-in-discord-on-modern-windows-11/"><u>Navigating Past Fatal JS Error in Discord on Modern Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-tecno-pop-7-pro-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Tecno Pop 7 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-continuous-connection-stop-usb-sleep-in-win-11/"><u>Ensuring Continuous Connection: Stop USB Sleep in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-store-error-0x800704cf-in-win11/"><u>Troubleshooting Store Error 0X800704CF in Win11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/online-video-blur-without-breaking-the-bank/"><u>Online Video Blur without Breaking the Bank</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-drive-detect-and-delete-null-space-in-windows/"><u>Streamline Your Drive: Detect and Delete Null Space in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-page-denial-challenges/"><u>Overcoming Windows Page Denial Challenges</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-average-payout-for-a-million-view-youtube-video/"><u>[New] 2024 Approved  Average Payout for a Million-View YouTube Video</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/enhance-your-audio-experience-a-critical-look-at-the-5-premium-voice-recorders-for-mp3s/"><u>Enhance Your Audio Experience A Critical Look at the 5 Premium Voice Recorders for MP3s</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-windows-exception-breakpoint-errors/"><u>Strategies to Address Windows Exception Breakpoint Errors</u></a></li>
<li><a href="https://win11.techidaily.com/master-window-11s-icon-arrangement/"><u>Master Window 11'S Icon Arrangement</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-tiny-titans-top-games-anthology-for-2024/"><u>[Updated] Tiny Titans' Top Games Anthology for 2024</u></a></li>
</ul></div>
