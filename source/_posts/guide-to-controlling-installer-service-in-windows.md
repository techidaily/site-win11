---
title: Guide to Controlling Installer Service in Windows
date: 2024-06-25T10:14:50.910Z
updated: 2024-06-26T10:14:50.910Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Controlling Installer Service in Windows
excerpt: This Article Describes Guide to Controlling Installer Service in Windows
keywords: Windows Installer Control,Installer Service Guide,Windows Service Management,Managing Windows Installers,Controller for Windows Setup,Service Regulation WINDOWS,Windows Installation Monitoring
thumbnail: https://thmb.techidaily.com/48dc7fa7b04b0f7445d8755963cdda5ac93794a2c8dd3de60bc0fcf279454931.jpg
---

## Guide to Controlling Installer Service in Windows

 Are you looking for a way to disable the Windows Installer Service on your device? This essential component of your operating system performs all necessary installation processes, but can sometimes interfere with other programs.

 Fortunately, there are three ways in which it can be disabled—using the Windows Service tool, Group Policy Editor, or Registry Editor. Check out our guide below to learn how.

## 1\. Use Windows Services

 Windows services are critical programs that typically initiate when you start your computer. It runs silently in the background and provides essential features to run the operating system. If you're looking to enable or disable Windows Installer service using this tool, do the following.

 To begin, press**Win + R** on your keyboard to launch the Run dialog box. In the text box, type**services.msc** , and hit enter. This will open the Services window.

![Disable Windows Installer Service Using Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-services-window.jpg)

 In the window that opens, scroll down until you find**Windows Installer** service then double-click on it for a properties window to open.

 Once you're in the Properties window, click the**Startup type** drop-down menu and select**Automatic** . Now move over towards the**Service status** section and click**Stop** .

![Disable Windows Installer Service Using Windows Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-windows-services.jpg)

 After you've done that, click**Apply** and then**OK** to save the changes. You have now successfully disabled the Windows Installer service on Windows 11.

 If you ever need to re-enable the service, follow the same procedure and click**Start** in the Service status section.

## 2\. Use Local Group Policy Editor

 You can also use the group policy editor to enable or disable the Windows Installer service on your Windows computer system. However, it is important to note that this tool only works on Windows Pro and Enterprise editions. Therefore, if you are using Windows Home Edition, you must first[activate the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 To disable the service using the group policy editor, do the following:

1. Click on Start and type in**gpedit.msc** , then press**Enter** to[launch the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) .
2. On the left side of the window, navigate to the path:  
`Computer Configuration > Administrative Templates > Windows Components > Windows Installer`
3. Now move to the right and double-click on the policy named**Turn off Windows Installer** .  
![Disable Windows Installer Service Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-group-policy.jpg)
4. In the window that opens, select**Enabled** in the radio box.
5. Under Options, click the drop-down menu and select**Always** .
6. Then click**Apply** and**OK** to save changes.

 That's all there is to it. The Windows Installer service will now be disabled on your system. To re-enable it, simply follow the same steps, but set "Turn off Windows Installer" to**Not Configured** .

## 3\. Use the Registry Editor

 Registry Editor is another method you can use to enable or disable the Windows Installer service on any version of Windows, even Home Edition. But make sure to proceed with caution as any incorrect changes can corrupt your system and force you to reinstall Windows. So be mindful and remember to back up your registry before making any modifications.

 To enable or disable this service using Registry Editor, follow these steps:

1. Press**Win + X** , type**regedit** , and press**Enter** to launch the Registry Editor. To learn more, see our guide on how to[open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. If prompted with a UAC warning, click**Yes** to continue.
3. Now once you're in, navigate to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\msiserver`
4. In the right panel, double-click on**Start** and change its value from**2** to**4** .  
![Disable Windows Installer Service Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-registry-editor.jpg)

 Once you put the Value data, make sure the Base is set to**Hexadecimal** , then click**OK** . Now close the registry editor and restart your computer for the changes to take effect.

## Turning Off the Windows Installer Service Made Easy

 If Windows Installer Service is creating issues or hindering another application, you can easily turn it off with one of the three methods outlined in our guide. See which method works best for you and get back to what matters most.


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
<li><a href="https://win11.techidaily.com/unveiling-interruptexception-solution-for-win11/"><u>Unveiling INTERRUPT_EXCEPTION Solution for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-system-performance-wins-top-diagnostic-list/"><u>Smooth System Performance: Win's Top Diagnostic List</u></a></li>
<li><a href="https://win11.techidaily.com/correct-the-dimmed-extend-option-on-windows-explorer/"><u>Correct the Dimmed Extend Option on Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-tips-for-your-windows-predicaments/"><u>Troubleshooting Tips for Your Windows Predicaments</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-tech-epochs-windows-7-key-to-boot-windows-11/"><u>Bridging the Tech Epochs: Windows 7 Key to Boot Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unsuccessful-message-loads-on-discord-pc/"><u>Troubleshooting Unsuccessful Message Loads on Discord PC</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-chaos-into-clarity-with-obsidian-visual-techniques/"><u>Transforming Chaos Into Clarity with Obsidian Visual Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-screen-unresponsive-message-in-windows-1111/"><u>Fixing Screen Unresponsive Message in Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/batch-terminate-programs-in-windows-effortlessly/"><u>Batch Terminate Programs in Windows Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-re-establish-bluetooth-linkage-on-windows-1011/"><u>How To Re-Establish Bluetooth Linkage on Windows 10/11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-tecno-spark-10-4g-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Tecno Spark 10 4G PC | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-maximize-fun-5-windows-11-gamers-recording-tactics/"><u>[Updated] Maximize Fun  5 Windows 11 Gamers' Recording Tactics</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-bring-forth-forgotten-vids-unlock-the-power-of-these-12-secrets-fb-2023/"><u>[Updated] 2024 Approved  Bring Forth Forgotten Vids  Unlock the Power of These 12 Secrets, FB, 2023</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-discover-the-top-free-and-paid-android-video-editing-apps-for-2024/"><u>Updated Discover the Top Free and Paid Android Video Editing Apps for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-elite-selection-optimal-video-downloading-for-tiktok-no-watermark/"><u>In 2024, Elite Selection  Optimal Video Downloading for TikTok (No Watermark)</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-value-oriented-pc-visual-logging-suites/"><u>[New] Value-Oriented PC Visual Logging Suites</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-income-impact-of-sharing-on-youtube-shorts/"><u>[Updated] The Income Impact of Sharing on YouTube Shorts</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-lava-blaze-pro-5g-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Lava Blaze Pro 5G Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-overcoming-the-challenge-of-hidden-youtube-shorts-thumbnails/"><u>In 2024, Overcoming the Challenge of Hidden YouTube Shorts Thumbnails</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-realme-11-pro-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Realme 11 Pro to Any iOS Devices | Dr.fone</u></a></li>
</ul></div>
