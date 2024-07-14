---
title: Mastering File Permissions to Prevent Read-Only Mode
date: 2024-07-13T11:05:21.325Z
updated: 2024-07-14T11:05:21.325Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering File Permissions to Prevent Read-Only Mode
excerpt: This Article Describes Mastering File Permissions to Prevent Read-Only Mode
keywords: File Permissions Mastery,Avoid Read-Only Status,Secure Access Controls,Prevent Read-Only Files,File Permission Best Practices,Security in File Management,Avoiding Locked Files
thumbnail: https://thmb.techidaily.com/5ba7b3f6e60e87bd15e4d0d59cd473305f169947afe8b79e803b03fc556698ce.jpg
---

## Mastering File Permissions to Prevent Read-Only Mode

 Do folders on your computer periodically revert to read-only mode, making it impossible to make changes? It can be frustrating, especially when you have to make final edits to your submission and the deadline is fast approaching.

 In this article, we'll explain why your folders revert to read-only mode and what you can do to prevent it.

## Why Are Your Folders Reverting to Read-Only Mode?

 Your folders revert to read-only mode for various reasons, including restrictions imposed by your administrator, an issue with a recent Windows update, or changes you make to Windows Defender or your antivirus settings. It can also happen due to possible restrictions from the security software you use to lock your folders.

 As you now understand why folders in your computer are reverting to read-only mode, let's look at some ways to fix it.

## 1\. Turn Off Folder Protection

 Do you use folder lock software to protect your data, but some of those protected folders become read-only at random? If so, the restrictions are likely imposed by the folder lock software. Thus, by turning off the security limitations for those folders, you might be able to fix the problem right away.

 If you don't use any folder lock software or turning off the protection doesn't help, move on to the next solution.

## 2\. Rule Out a Folder-Specific Issue

 Is only one folder reverting to read-only mode? If so, follow the below steps to remove the read-only attribute manually for that folder:

1. Go to the folder that is going read-only.
2. Right-click on it and select **Properties**.
3. In the **General** tab, uncheck the box for **Read-only**.
4. Click **Apply** and hit **OK**.  
![Unchecking the Box for Read-Only Option in the General Tab of Properties Window of the File on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/1-Unchecking-the-Box-for-Read-Only-Option-in-the-General-Tab-of-Properties-Window-of-the-File-on-Windows.jpg)

 If removing the attribute this way does not solve the problem, or if the problem involves multiple files, keep applying the remaining fixes.

 If you have encountered the issue on a work computer, you may not be able to apply a few fixes mentioned below. Thus, if you encounter an error saying you don't have permission to make any changes, it's best to let your IT admin handle it.

## 3\. Ensure an Administrator Hasn't Imposed Any Restrictions

 In Windows, administrators can restrict access to confidential data for specific users working on the same computer. If you see some files and folders in read-only mode, verify the administrator hasn't changed their permissions. Here's how you can find out:

1. Right-click the file or folder you see in read-only mode and select **Properties**.
2. In the **Properties** window, click the **Security** tab.
3. Choose your username from the available options.
4. Check the **Permissions for Users** section after selecting your account.  
![Checking the Permissions Window in the Security Tab in the File’s Properties on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-2-Checking-the-Permissions-Window-in-the-Security-Tab-in-the-File’s-Properties-on-Windows.jpg)

 You can't make changes to the files if you only have read-only permissions. If you believe the access was restricted by mistake, ask the administrator to grant you access.

 If you're an administrator, here's how you can change the access permissions of other users:

1. Log in with your administrator account.
2. Right-click the file or folder you see in read-only mode and select **Properties**.
3. In the **Properties** window, go to the **Security** tab.
4. Click the **Edit** button.  
![Clicking on Edit Button under Security Tab in Properties Window on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-3-Clicking-on-Edit-Button-under-Security-Tab-in-Properties-Window-on-Windows.jpg)
5. Choose the user you want to grant access to.
6. In the **Permissions for Users** window, check the box next to **Full control** under **Allow** column.  
![Checking the Box Next to Full Control under Allow Column in the Permissions for Users Window in Security Tab on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-4-Checking-the-Box-Next-to-Full-Control-under-Allow-Column-in-the-Permissions-for-Users-Window-in-Security-Tab-on-Windows.jpg)
7. After clicking **Apply**, hit **OK**.

 If you have multiple personal accounts on your computer, you can change permissions for each account using the administrator account similarly.

## 4\. Disable Ransomware Protection in the Windows Security Settings

 To combat ransomware threats and safeguard users' data, Microsoft has introduced a ransomware protection feature. By using this feature, users can prevent third-party apps from changing their files and folders without their permission.

 Although it's handy, it has a history of messing up file permissions. Therefore, if you've encountered the issue under discussion after enabling this feature, disabling it may help you fix it. The following steps will help you do that:

1. Open the Windows Security app by searching for **"Windows Security"** in Windows Search.
2. Go to **Virus and threat protection**.
3. Click on **Manage ransomware protection**.  
![Opening Manage Ransomware Protection Option under Virus and Threat Protection in Windows Security App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-5-Opening-Manage-Ransomware-Protection-Option-under-Virus-and-Threat-Protection-in-Windows-Security-App-on-Windows.jpg)
4. Turn off the toggle under **Controlled folder access**.  
![Disabling Ransomware Protection by Turning Off the Toggle under Controlled Folder Access in Windows Security App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-6-Disabling-Ransomware-Protection-by-Turning-Off-the-Toggle-under-Controlled-Folder-Access-in-Windows-Security-App-on-Windows.jpg)

 If disabling this feature doesn't resolve the problem, you may need to reset the entire Windows Defender Firewall settings.

## 5\. Reset the Windows Defender Firewall Settings

 Have you recently made changes to your Windows Defender Firewall settings and encountered this problem? If so, there's a good chance you've done something wrong. Therefore, resetting them may help you resolve the issue. Follow the below steps to reset Windows Defender Firewall settings:

1. Open the Control Panel app by searching for **"Control Panel"** in Windows Search.
2. Click **System and Security**.
3. Click **Windows Defender Firewall**.
4. In the left sidebar, click **Restore defaults**.  
![Opening Restore Defaults Option in Windows Defender Firewall Tab in System and Security Settings in Control Panel App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-7-Opening-Restore-Defaults-Option-in-Windows-Defender-Firewall-Tab-in-System-and-Security-Settings-in-Control-Panel-App-on-Windows.jpg)
5. Click **Restore defaults** button.
6. When the confirmation pop-up appears, select **Yes**.  
![Clicking on the Yes Button after Clicking on the Restore Defaults Button on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-8-Clicking-on-the-Yes-Button-after-Clicking-on-the-Restore-Defaults-Button-on-Windows.jpg)

## 6\. Disable Antivirus and Other Security Software

 If the folders that revert to read-only mode reside on the same drive where your operating system is installed, Microsoft Defender might temper the folder permissions.

 To rule out this potential cause, temporarily [turn off the Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) and see if your folders stop reverting to read-only mode after that. If they do, whitelist those folders from Microsoft Defender and turn on the security suite again. If you use any third-party security software, disable that as well since it can also restrict your access.

 Whether disabling the built-in or third-party security suites fixes the issue or not, you should enable them again to keep your device protected from viruses.

## 7\. Forcefully Remove the Read-Only Attribute

 If none of the fixes have resolved the issue of folders reverting to read-only mode, you should remove the read-only attribute forcibly using Command Prompt. Here's how:

1. Search for **"Command Prompt"** in Windows Search and open the Command Prompt app.
2. Enter the following command by specifying the drive and pasting the path to the read-only folder.  
`attrib -s -h -r "Drive:\path_to_folder\*.*" /s /d`
3. Hit **Enter**.  
![Removing the Read-Only Attribute by Running the Command in Windows Command Prompt App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Image-9-Removing-the-Read-Only-Attribute-by-Running-the-Command-in-Windows-Command-Prompt-App-on-Windows.jpg)

## 8\. Run the SFC and CHKDSK Scans

 Corrupted system files and bad hard drive sectors can also alter the folder's permission access. Run the SFC and Chkdsk scans to ensure that's not the case. SFC can help you search for and fix corrupted system files, whereas Chkdsk can find bad sectors on your hard drive that could be causing the issue.

 If you've never run these scans before, check out our guide on [how to run SFC](https://www.makeuseof.com/system-file-checker-sfc-windows/) and [Chkdsk scans](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/). Hopefully, running these scans will fix the underlying issue with your files and folders. If neither of these scans finds any problems, proceed to the next step.

## 9\. Uninstall Any Recent Windows Updates

 If the issue under discussion occurred after installing a Windows update, you should uninstall it and revert to the previous version of Windows. Check out our article on [manually uninstalling Windows 10 and 11 updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) if you're unfamiliar with the process.

## 10\. Relocate the Folders to Another Drive

 While it may initially seem strange, relocating the folders whose permissions get restricted to another drive also resolved the issue for some users. Therefore, move your folders from one drive to another, remove the read-only attribute, and see if they revert to read-only again. If relocating the folder to a different drive does not resolve the issue, go to the next fix.

## 11\. Go to Previous Restore Point

 A System Restore allows Windows users to restore their system to its current state if they accidentally mess something up in the future. It's a quick way to undo changes that mess up your system.

 Thus, if uninstalling the Windows update also doesn't work, apply the restore point you created previously. This will undo any system changes that may have resulted in the issue under discussion and return your device to its original state.

 If you're unfamiliar with the process, check out our article that explains [how to perform a system restore in Windows 11](https://www.makeuseof.com/windows-11-create-restore-point/#how-to-use-restore-point-to-restore-your-windows-11-system). For Windows 10, the process is nearly the same.

## Keep Your Files and Folders Editable

 Hopefully, applying the fixes mentioned in the article will help you prevent your folder from reverting to read-only mode. Moreover, to stop files from opening in read-only mode in a specific app, such as OneNote, you'll have to change the app settings.

 In this article, we'll explain why your folders revert to read-only mode and what you can do to prevent it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/updated-simplifying-iphoneipad-screen-captures-for-online-sharing/"><u>[Updated] Simplifying iPhone/iPad Screen Captures for Online Sharing</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-leave-a-life360-group-on-lava-blaze-2-5g-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How To Leave a Life360 Group On Lava Blaze 2 5G Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-securing-seamless-streams-troubleshooting-fb-live-glitches-for-2024/"><u>[New] Securing Seamless Streams  Troubleshooting FB Live Glitches for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-file-management-with-collective-windows-11-folder-making/"><u>Revolutionize File Management with Collective Windows 11 Folder Making</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-convert-avchd-mts-files-for-nova-y91-by-aiseesoft-video-converter-play-mts-on-android/"><u>How to convert AVCHD .mts files for Nova Y91? </u></a></li>
<li><a href="https://win11.techidaily.com/the-starting-line-in-diablo-basic-play-wisdom/"><u>The Starting Line in Diablo: Basic Play Wisdom</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-the-gap-top-methods-to-reconnect-your-usb-wi-fi-on-pcs/"><u>Bridge the Gap: Top Methods to Reconnect Your USB Wi-Fi on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-fixes-for-non-operational-voice-command-in-win11/"><u>Unveiling Fixes for Non-Operational Voice Command in Win11</u></a></li>
<li><a href="https://extra-information.techidaily.com/next-gen-tracker-seamless-camera-movement-coordination/"><u>Next-Gen Tracker  Seamless Camera Movement Coordination</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-optimal-free-tools-5-gif-to-video-conversion-websites-without-downloads-for-2024/"><u>[New] Optimal Free Tools  5 GIF-to-Video Conversion Websites Without Downloads for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-mac-visionaries-reveal-screenflow-secrets-and-benefits-for-2024/"><u>[Updated] Mac Visionaries Reveal ScreenFlow Secrets and Benefits for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/beginning-your-art-with-ms-paint-windows-11-way/"><u>Beginning Your Art with MS Paint - Windows 11 Way</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-slashing-dropbox-cpu-load-on-windows-devices/"><u>Solutions for Slashing Dropbox CPU Load on Windows Devices</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/free-youtube-download-methods-without-apps/"><u>Free YouTube Download Methods Without Apps</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-recording-techniques-gaming-screen-captures-with-intel/"><u>Advanced Recording Techniques: Gaming Screen Captures with Intel</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-technique-how-to-execute-a-clean-boot-on-windows-11/"><u>The Ultimate Technique: How to Execute a Clean Boot on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-restart-file-explorer-in-windows-10-and-11/"><u>4 Ways to Restart File Explorer in Windows 10 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/toolbox-tutorial-windows-core-components-management/"><u>Toolbox Tutorial: Windows' Core Components Management</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-the-aspect-ratio-effect-boosting-your-videos-production-value/"><u>2024 Approved The Aspect Ratio Effect Boosting Your Videos Production Value</u></a></li>
<li><a href="https://win11.techidaily.com/1719293621682-mastering-wwinplusprint-functionality-fixes-for-non-operational-printer-on-pc/"><u>Mastering WWin+Print Functionality: Fixes for Non-Operational Printer on PC.</u></a></li>
<li><a href="https://win11.techidaily.com/windowed-wonders-enhance-windows-11-explorer-visibility/"><u>Windowed Wonders: Enhance Windows 11 Explorer Visibility</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-voice-and-music-from-bluetooth-headset/"><u>Troubleshooting Windows: Voice & Music From Bluetooth Headset</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-correcting-unresponsive-video-files/"><u>Tips for Correcting Unresponsive Video Files</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-remedying-install-fail-in-wins-discord-setup/"><u>Understanding and Remedying Install Fail in Win's Discord Setup</u></a></li>
<li><a href="https://win11.techidaily.com/the-essentiality-of-runtime-brokers-for-modern-os-functionality/"><u>The Essentiality of Runtime Brokers for Modern OS Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-correcting-windows-store-failures-error-x80072f30-guide/"><u>Swiftly Correcting Windows Store Failures: Error X80072F30 Guide</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-choosing-between-vimeo-free-premium-and-pro-membership-levels/"><u>In 2024, Choosing Between Vimeo Free, Premium & Pro Membership Levels</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windowsstore-directory-secrets-for-users/"><u>Unveiling WindowsStore Directory Secrets for Users</u></a></li>
<li><a href="https://extra-information.techidaily.com/clear-images-made-easy-picart-backdrop-takedown-technique-for-2024/"><u>Clear Images Made Easy  PicArt Backdrop Takedown Technique for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-the-art-of-capturing-sound-via-mac-for-2024/"><u>[New] The Art of Capturing Sound via Mac for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/stop-recurring-file-explorer-autoload/"><u>Stop Recurring File Explorer Autoload</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-incorporation-of-virtual-gaming-archives-into-playnite-on-pc/"><u>Seamless Incorporation of Virtual Gaming Archives Into Playnite on PC</u></a></li>
<li><a href="https://win11.techidaily.com/win11-terminal-reset-procedure-essentials/"><u>Win11 Terminal Reset Procedure Essentials</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-premier-20-no-cost-pubg-thumbnail-assemblies/"><u>[Updated] Premier 20 No-Cost PUBG Thumbnail Assemblies</u></a></li>
</ul></div>
