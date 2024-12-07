---
title: Tactics for Dodging 'Enter Credentials' Message in Windows
date: 2024-12-01T09:02:07.547Z
updated: 2024-12-06T17:36:01.706Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tactics for Dodging 'Enter Credentials' Message in Windows
excerpt: This Article Describes Tactics for Dodging 'Enter Credentials' Message in Windows
keywords: Avoid Windows Credential Entry Errors,Bypass 'Enter Passwords' Prompt,Skip Password Input on PC,Evasion From Windows Login Screen,Stealthy User Sign-In Method,Hide Login Information Request,Securely Access Windows Without Credentials
thumbnail: https://thmb.techidaily.com/2921f580a005bca983d6da9a3afb73cd46b3297303a92739f51d69c3aa21056e.jpg
---

## Tactics for Dodging 'Enter Credentials' Message in Windows

 The network credentials on your PC are important because they prevent others from using your computer across the network. While this feature is essential to protect your important files and improve the overall security of your system, it can sometimes cause issues as well.

 A common problem is when the network credential manager keeps displaying the "Enter network credentials" dialog, even when you enter the correct credentials. In this guide, we will walk you through some troubleshooting methods you can try to fix this issue for good.

## 1\. Modify the Advanced Sharing Settings

 An incorrectly set Advanced Sharing setting is one of the most common causes of this error. Ideally, your PC should be allowed to manage homegroup connections. You can also use the Advanced Sharing settings page to disable password-protected sharing, which will allow you to share files without needing to log in.

 Here is how you can configure the Advanced Sharing settings correctly:

1. Locate the network icon on your taskbar and right-click on it.
2. Choose **Network and Internet settings** from the context menu.  
![Network and Internet settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/network-and-internet-settings.jpg)
3. In the following window, select **Network and Sharing Center**.
4. Choose **Change advanced sharing settings** option in the left pane.
5. Now, enable the **Allow Windows to manage homegroup connections (recommended)** option under Homegroup connections.
6. Click **Save changes** (you will need administrative access for this).
7. Now, expand the **All Networks** section and enable the **Turn off password protected sharing** option.  
![Turn off password sharing option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/turn-off-pasword-sharing.jpg)
8. Hit the **Save changes** button to complete the process.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After you've transferred the files, re-enable password-protected sharing so that others don't get easy access to your PC.

## 2\. Use Your Microsoft Account Credentials or the Computer's Name

 You can also try logging onto the target PC using the Microsoft account credentials instead of the local username and password.

 Alternatively, you can also try using the name of the computer you are using alongside your username in the text field associated with the Username. Do not enter a space, bar, or any other symbol between the names.

 If the problem is associated with the credentials, one of these two methods is likely to help you get rid of it for good.

## 3\. Manually Add the Credentials of the Target Computer to the Credential Manager

 Another way to fix the issue is by manually adding the credentials of the targeted computer in the Credential Manager and seeing if that makes a difference.

 Here is how you can do that:

1. Type "Credential Manager" into Windows Search and click **Open**.
2. Select **Windows Credential** and click on **Add a Windows Credential**.  
![Windows credentials](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/windows-credentials-1.jpg)
3. Now, add the username, computer name, and password of the computer you are trying to access. Check if you can now share files with the other device successfully.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Create a New User Account on Both Devices

 There are times when user accounts become corrupt and stop you from performing certain actions. If this has happened, either on your PC or the target computer, it can interrupt the file-sharing process.

 To fix this problem, first, try [switching to a different user account](https://www.makeuseof.com/windows-11-switch-user-accounts/) on your own computer and see if that works. If this strategy fails, then we recommend [creating a new user account](https://www.makeuseof.com/windows-11-create-local-user-account/) on both devices with the same username and password. Make sure that both accounts have administrative privileges. While you are at it, we also suggest temporarily disabling any third-party antivirus program that you might be using, as it can sometimes block network access.

 If the root of your issue was a corrupt user account, this should be enough to fix the issue.

## 5\. Restart the Credential Manager Service

 The issue might also be with the Credential Manager service itself instead of the targeted computer or the network settings of your device. In this method, we will first enable the Credential Manager service if the service is disabled.

 If it is working already, then we will proceed with restarting the service and see if that does the trick.

 Here is what you need to do:

1. Press **Win** \+ **R** to open Run.
2. Type services.msc in the Run and click **Enter**.
3. In the following window, look for the Credential Manager service and right-click on it.
4. Choose **Properties** from the context menu.
5. If the service is disabled, click on the **Start button** to enable it.
6. In case it is working already, click on the **Stop button**, wait for a few seconds, and then hit the **Start button**.
7. ![Credential Manager properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/credential-manager-properties.jpg)  
 Make sure that the Startup type is set to **Automatic**.  
![Credential Manager service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/credential-manager-service.jpg)
8. Click **Apply** \> **OK** to save the changes.

 Now try connecting to the targeted computer and see if you can do so without any problems.

## 6\. Make Changes to the Local Security Policy

 Several users also managed to fix the problem by modifying the settings of the "Accounts: Limit local account use of blank passwords to console logon only" policy. Here is how you can give it a try too:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "secpol.msc" in Run and click **Enter**.
3. In the following window, navigate to the following location:  
Local Policies > Security Options > Accounts: Limit local account use of blank passwords to console logon only
4. Choose **Disabled** and click **Apply** \> **OK** to save the changes.  
![Make changes to the Local Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-security-policy.jpg)
5. Restart your computer and check if the issue is resolved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/grbt-5VvbuI?si=qnoirlmljslpqcQj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 7\. Try Using Safe Mode With Networking

 If the credentials you are entering and all the network configurations on the system are correct, something might have gone wrong on a system level.

 In this case, you can boot into Safe Mode to determine the cause of the issue. Safe Mode starts Windows with only the basic set of drivers and apps — the ones that are essential for the operating system to function.

 There are several types of Safe Mode including Minimal, Alternate Shells, Active Directory Repair, and Network. In this method, we will be booting Windows into Safe Mode with Networking. This mode launches Windows with the drivers and programs required to connect the system to the internet or other devices over the network.

 If the error at hand does not appear in Safe Mode, then there is a chance that malware or other software issues are causing the problem.

 Here is what you need to do:

1. Head over to the Start menu and click on the **Power button**.
2. Choose **Restart** while holding the **Shift key**.
3. Wait for the Windows to boot into the recovery mode and then choose **Troubleshoot** \> **Advanced Options**.
4. Navigate to **Startup Settings** \> **Restart**.
5. In the following window, press the **F5 key** on your keyboard to boot into Safe Mode with Networking.  
![Pick safe mode with Networking option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/Tweak-Startup-Settings-1.jpg)
6. Once you are logged into Safe Mode, try connecting to the device you were previously trying to connect to. If the error does not appear in Safe Mode, then you might want to report this issue to Microsoft’s official support team and wait for a fix from their side.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In case you cannot access this Windows state using the steps outlined above, you can try [other ways of booting into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OmJZ4Z8jgk?si=YIoEaPI8geoiFSYE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Share Data Over Network Without Issues

 Windows has made it simpler to share your files and other data across networks, but there are times when you run into unexpected errors. Hopefully, one of the methods mentioned above did the trick for you in fixing the issue under consideration.

 A common problem is when the network credential manager keeps displaying the "Enter network credentials" dialog, even when you enter the correct credentials. In this guide, we will walk you through some troubleshooting methods you can try to fix this issue for good.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/control-data-cost-monitoring-on-your-wi-fi-network-with-win11/"><u>Control Data Cost Monitoring on Your Wi-Fi Network with Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-and-solving-m365-error-code-30015-26-on-windows/"><u>Deciphering and Solving M365 Error Code 30015-26 on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-gaming-capture-with-intels-pc-graphics-hub/"><u>Effortless Gaming Capture with Intel's PC Graphics Hub</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-photocapture-errors-on-win11-system/"><u>Eliminating PhotoCapture Errors on Win11 System</u></a></li>
<li><a href="https://buynow-info.techidaily.com/g7x-mark-ii-fewer-pixels-more-power/"><u>G7X Mark II: Fewer Pixels, More Power?</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-motorola-moto-g-stylus-5g-2023-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your Motorola Moto G Stylus 5G (2023) Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/how-to-choose-the-best-android-and-ios-timers-for-your-dream-wedding-for-2024/"><u>How to Choose the Best Android & iOS Timers for Your Dream Wedding for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-set-up-custom-volume-control-hotkeys-in-windows-11/"><u>How to Set Up Custom Volume Control Hotkeys in Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-xiaomi-redmi-13c-drfone-by-drfone-virtual-android/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Xiaomi Redmi 13C | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-motorola-edge-40-neo-location-on-twitter-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change your Motorola Edge 40 Neo Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-12-prominent-xiaomi-14-pro-fingerprint-not-working-solutions-by-drfone-android/"><u>In 2024, Top 12 Prominent Xiaomi 14 Pro Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/mac-methods-for-cleaner-instagram-video-edits/"><u>Mac Methods for Cleaner Instagram Video Edits</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-display-disruptions-on-windows-11/"><u>Preventing Display Disruptions on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-dual-programs-error-in-windows-os/"><u>Remedy for 'Dual Programs Error in Windows OS'</u></a></li>
<li><a href="https://win11.techidaily.com/solidify-your-linux-subsystem-with-win-11s-arrival/"><u>Solidify Your Linux Subsystem with Win 11'S Arrival</u></a></li>
</ul></div>

