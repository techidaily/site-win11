---
title: Eliminating Windows Hello Login Fingerprint Failure
date: 2024-07-13T09:57:15.265Z
updated: 2024-07-14T09:57:15.265Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating Windows Hello Login Fingerprint Failure
excerpt: This Article Describes Eliminating Windows Hello Login Fingerprint Failure
keywords: Fix Fingerprint Error,Stop Hello Logout Fail,Wipe Welcome Failures,Eradicate Hello Locks,Dismiss Windows Failsafe,Overcome Login Mistakes,Prevent Hello Pause
thumbnail: https://thmb.techidaily.com/66f3cf36e141a02ee3ef4f8fc90997bfb9adc390279a16b539b7e76e0dc798e2.jpg
---

## Eliminating Windows Hello Login Fingerprint Failure

 If you receive an error message that says, "we couldn't find a fingerprint scanner compatible with Windows Hello Fingerprint" when trying to set up Windows Hello fingerprint login, then your device either doesn't support fingerprint recognition, the fingerprint scanner (or reader) isn't working correctly, or Windows is unable to detect it.

 Windows may not detect the fingerprint scanner for several reasons: the fingerprint reader may have malfunctioned, the biometric drivers could be outdated or corrupted, or biometric recognition could be disabled in the BIOS. If you're tired of dealing with this problem, try these solutions.

## 1\. Ensure Your Device Supports Fingerprint Recognition

![blue graphic of digital fingerprint scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/blue-finger-scan.jpg)

 The Windows Hello fingerprint recognition feature requires your device to have a fingerprint reader. If you encounter the error "we could not find a fingerprint scanner compatible with Windows Hello Fingerprint" when setting up fingerprint recognition for the first time, make sure your device is equipped with a fingerprint reader compatible with Windows Hello.

 Usually, it is located near (or on) the power button or in the empty space above or below the keyboard. Look around and see if you can find a fingerprint reader. If you fail to find it, check your device's specifications on the manufacturer's website to see if it has a fingerprint scanner.

 If your device does not have a fingerprint reader, you cannot enable biometric authentication on it. However, if your device has a scanner, and you've used it many times before, ensure that it is working correctly.

## 2\. Make Sure the Fingerprint Reader Is Working Properly

![security fingerprint on keyboard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/data-1590455_1920-1.jpg)

 If your device has a fingerprint sensor, but Windows is unable to detect it, ensure the sensor hasn't gone bad. To test the fingerprint reader, sign in to another app where you've set up biometric login. If that app fails to accept biometric verification, use a dry cloth to wipe the dust off your fingerprint scanner.

 After that, try scanning your finger again. If the app fails to recognize the fingerprint scan even after thoroughly cleaning it, there is probably an issue with the scanner. So, have your device inspected by a technician. However, if the scanner works fine on other apps but not when you set up Windows Hello fingerprint login, then apply the remaining fixes.

## 3\. Roll Back the Driver or the Latest Windows Update

 Have you encountered the error under discussion after updating the biometric driver or installing a Windows update recently? If this is the case, you should roll back these updates. Don't know how to do that? Our guide on [how to roll back a driver update on Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) describes the process. If you want to roll back a Windows update, then you need to [uninstall the most recent Windows Update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) .

 Once you've undone both driver and Windows updates, try setting up Windows Hello biometric login again. If you continue to experience the same problem after rolling back these updates, it suggests that undoing these updates hasn't made a difference. In that case, you should reinstall the drivers and Windows update.

## 4\. Ensure the Windows Biometric Service Is Configured Properly

 When the Windows biometric service is disabled, Windows Hello fingerprint recognition won't work. To ensure this service is enabled and configured correctly, follow these steps:

1. Type**"Services"** in Windows Search and open the**Services** app.  
![Open Services App From Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/1-open-services-app-from-windows-search.jpg)
2. Locate**Windows Biometric Service** .  
![Locate Windows Biometric Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/2-locate-windows-biometric-service-in-windows-services-app.jpg)
3. If you see**"Running"** next to this service in the**Status** column, it's already running. If not, it's disabled.
4. In either case, right-click the service and select**Properties** .  
![Go to Properties of Windows Biometric Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3-go-to-properties-of-windows-biometric-service-in-windows-services-app.jpg)
5. Click on the dropdown menu next to**Startup type** and select**Automatic** .  
![Select Automatic From the Startup Type Dropdown Menu in the Properties Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/4-select-automatic-from-the-startup-type-dropdown-menu-in-the-properties-window.jpg)
6. If it's already selected, click the**Stop** button to stop the service and then click**Start** again to restart it.  
![Click Start Button to Restart the Service in Windows Services App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-click-start-button-to-restart-the-service-in-windows-services-app.jpg)

## 5\. Update or Reinstall the Biometric Drivers

 If the biometric service is already enabled, yet the fingerprint recognition feature isn't working, the biometric drivers could be outdated or corrupt. To ensure that isn't the case, update the biometric device drivers. To do so, follow these steps:

1. Type**"Device Manager"** in Windows Search and open the**Device Manager** app.
2. Expand the**Biometric devices** category.
3. Right-click on your fingerprint scanner device and select**Update driver** .  
![Update the Fingerprint Scanner Device in Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/6-update-the-fingerprint-scanner-device-in-windows-device-manager.jpg)
4. Then, click on**Search automatically for drivers** .

 If updating the drivers does not fix the problem, right-click the biometric device again and select**Uninstall device** . After uninstalling the drivers, reboot your device, and Windows will automatically install them again. If you prefer, you can also download the relevant drivers from the manufacturer's website and install them manually.

## 6\. Disable Fast Startup

 According to some users on a [Microsoft community thread](https://answers.microsoft.com/en-us/windows/forum/all/fingerprint-reader-not-working/95cc0aef-2822-4b51-9f77-8697e6ace897) , disabling the Fast Startup feature has solved fingerprint recognition issues on their devices. Although Fast Startup speeds up your device's boot process, turning it on is known to cause unforeseen problems.

 So, if you also keep this feature enabled on your device, disable it to see if it makes a difference. Don't know how to do that? Refer to our guide on [enabling or disabling Fast Startup on Windows 11](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) .

## 7\. Ensure the Biometric Reader Isn't Disabled in BIOS

 Some laptops allow users to disable the fingerprint reader in BIOS. If you're setting up a fingerprint login for the first time and getting the error, ensure the fingerprint scanner isn't disabled in BIOS. Accessing BIOS and navigating to the option to enable or disable the biometric device varies between manufacturers.

 If you need guidance on accessing the BIOS and enabling the biometric device, visit your laptop manufacturer's website.

## 8\. When Nothing Else Works…

 If nothing else works, run the Hardware and Devices troubleshooter, enable biometrics in the Local Group Policy Editor, and check for account-specific issues. If these steps fail to resolve the issue, perform a system restore as a last resort. Our guide on [fixing Windows Hello fingerprint recognition](https://www.makeuseof.com/windows-hello-fingerprint-not-working/) explains how to make the above-mentioned changes.

## Get Rid of Annoying Fingerprint Recognition Errors

 If you encounter an error when setting up Windows Hello fingerprint recognition, it does not mean the feature can't be used. If your device supports biometric authentication, the above fixes will help you resolve the annoying error.

 If you are setting up a fingerprint login for the first time, make sure you do it correctly. Otherwise, you'll be constantly annoyed by the bothersome errors when using this fantastic feature.


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
<li><a href="https://win11.techidaily.com/how-to-fix-stuttering-in-warhammer-40000-boltgun-on-windows/"><u>How to Fix Stuttering in Warhammer 40,000: Boltgun on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-compression-command-prompt-and-powershell-techniques/"><u>Mastering File Compression: Command Prompt & PowerShell Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-color-management-not-working-on-windows/"><u>How to Fix Color Management Not Working on Windows</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/stop-screen-shiver-in-windows-11/"><u>Stop Screen Shiver in Windows 11</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-make-every-moment-epic-add-slow-motion-effects-to-your-videos-for-free/"><u>Updated In 2024, Make Every Moment Epic Add Slow Motion Effects to Your Videos for Free</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-accelerated-learning-path-with-final-cut-pro/"><u>In 2024, Accelerated Learning Path with Final Cut Pro</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unlock-linux-capabilities-on-windows-10/"><u>How to Unlock Linux Capabilities on Windows 10</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-malfunctioning-your-drivers-with-windows-device-manager-on-windows-7-by-drivereasy-guide/"><u>Use Device Manager to identify malfunctioning your drivers with Windows Device Manager on Windows 7</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-qt-engine-initialization-problem-in-software/"><u>Rectifying Qt Engine Initialization Problem in Software</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-windows-security-add-safe-websites-now/"><u>Optimize Windows Security: Add Safe Websites Now</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-mastering-creativity-top-10-yt-reaction-hacks/"><u>2024 Approved  Mastering Creativity  Top 10 YT Reaction Hacks</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-3-effective-ways-to-bypass-activation-lock-on-iphone-14-plus-by-drfone-ios/"><u>In 2024, 3 Effective Ways to Bypass Activation Lock on iPhone 14 Plus</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-videos-from-your-honor-play-40c-by-fonelab-android-recover-video/"><u>How to recover old videos from your Honor Play 40C</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-fixing-0x0000004e-on-windows-xp7/"><u>Decoding and Fixing 0X0000004E on Windows XP/7</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-productivity-configuring-multimonitors-in-win11/"><u>Maximize Productivity: Configuring Multimonitors in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-offline-setup-path-of-win11/"><u>Navigating the Offline Setup Path of Win11</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-ordering-clumped-taskbar-icons/"><u>Guidelines for Ordering Clumped Taskbar Icons</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unauthorized-save-errors-in-windows/"><u>Overcoming Unauthorized Save Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-windows-11-wait-longer-when-shutting-down-if-you-have-running-tasks/"><u>How to Make Windows 11 Wait Longer When Shutting Down if You Have Running Tasks</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-visual-delight-windows-wallpapers-guidebook/"><u>Fine-Tuning Visual Delight: Windows Wallpapers Guidebook</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-sony-vegas-not-your-cup-of-tea-discover-top-alternatives-for-windows/"><u>New In 2024, Sony Vegas Not Your Cup of Tea? Discover Top Alternatives for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/revitalize-gpu-settings-on-windows-11-pcs/"><u>Revitalize GPU Settings on Windows 11 PCs</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-realme-12-proplus-5g-by-drfone-android/"><u>The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Realme 12 Pro+ 5G</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-temporarily-turn-off-your-pcs-firewall/"><u>How to Temporarily Turn Off Your PC's Firewall</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-into-iis-manager-top-8-approaches/"><u>Breaking Into IIS Manager: Top 8 Approaches</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-defender-written-by-michael-cramer/"><u>Navigating Windows Defender' Written by Michael Cramer</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-unraveling-the-sixest-methods-for-copying-file-and-folders-locations/"><u>Mastering Windows 11: Unraveling the Sixest Methods for Copying File & Folders' Locations</u></a></li>
<li><a href="https://win11.techidaily.com/fix-guide-to-troubleshoot-function-keys-in-win-11/"><u>Fix: Guide to Troubleshoot Function Keys in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-tackling-winos-isdonedll-errors/"><u>Comprehensive Guide to Tackling WinOS ISDone.dll Errors</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-access-tackling-onedrive-logins-in-windows/"><u>Reviving Access: Tackling OneDrive Logins in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-steam-cloud-error-in-windows/"><u>How to Fix the Steam Cloud Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/innovation-at-your-fingertips-windows-erase-feature/"><u>Innovation at Your Fingertips: Window's Erase Feature</u></a></li>
<li><a href="https://win11.techidaily.com/nix-the-need-for-speedy-pointers-on-windows-11/"><u>Nix the Need for Speedy Pointers on Windows 11</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-from-avi-to-mkv-streaming-any-video-format-to-google-chromecast/"><u>Updated In 2024, From AVI to MKV Streaming Any Video Format to Google Chromecast</u></a></li>
</ul></div>
