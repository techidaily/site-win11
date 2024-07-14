---
title: 4 Fixes to Try if You Can’t Enable the Windows Firewall
date: 2024-07-13T11:13:45.880Z
updated: 2024-07-14T11:13:45.880Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes 4 Fixes to Try if You Can’t Enable the Windows Firewall
excerpt: This Article Describes 4 Fixes to Try if You Can’t Enable the Windows Firewall
keywords: Enable Windows Firewall,Troubleshooting Firewall Issue,Windows Security Settings,Activating Firewall Service,Disabled Firewall Fixes,Firewall On/Off Tips,Restarting Firewall Services
thumbnail: https://thmb.techidaily.com/88bfebb08e4cbb8d0a68e78c0297b8f1e363343f342702915251fd121c5a13e0.jpg
---

## 4 Fixes to Try if You Can’t Enable the Windows Firewall

 Windows Firewall is crucial to ensure the security of your computer and protect it from potential threats. However, sometimes you may encounter issues while enabling it.

 Below, we explore the different solutions you can try to fix this issue for good.

## 1\. Run the Firewall Troubleshooter

 If you are having trouble enabling Firewall in Windows, it is a good idea to start troubleshooting using the official Firewall troubleshooter released by Microsoft Automated Troubleshooting Services.

 This utility will scan your system for underlying problems that might be preventing Firewall from functioning. If an issue is identified, it will suggest relevant fixes that you can either apply manually or from within the troubleshooter.

 Here is how you can run the troubleshooter:

1. Head over to the [official Microsoft page for the troubleshooter](https://support.microsoft.com/en-us/windows/automatically-diagnose-and-fix-problems-with-windows-firewall-513e9cf8-19ae-d579-2092-d5e64fe06f5f) and download it.  
![Download firewall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/download-troubleshooter.jpg)
2. Click on the downloaded file and proceed with the on-screen instructions to start the scan.  
![Firewall troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/firewall-troubleshooter.jpg)
3. Once the scan completes, check the results and apply the solutions suggested by the troubleshooter.

 You can now close the troubleshooter and check if the issue is resolved.

## 2\. Check if Another Security Software Is Active

 Are you using a third-party security program on your computer? If so, there is a good chance that it is conflicting with Windows Firewall and stopping it from working. As such, if you have installed another antivirus app recently, we recommend temporarily disabling or uninstalling the third-party security program and then enabling Windows Firewall.

 Disabling the third-party antivirus software may vary depending on the program you have installed. However, a common approach is to right-click on the antivirus icon located in the taskbar. From the context menu that appears, you should find an option to disable the antivirus temporarily until you restart your computer.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 After disabling the antivirus, try enabling the Windows Firewall and check if it functions properly now.

## 3\. Reset the Windows Firewall settings

 The issue might also be with the Firewall settings. You can fix any such issues by resetting Windows Firewall settings, as it will restore the firewall configuration to its default state, undoing any customizations or changes that might be causing conflicts.

 Here is how you can proceed:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type “control” in Run and click **Enter**.
3. In the Control Panel, expand the View by option and choose **Category**.
4. Click on **System and Security** \> **Windows Defender Firewall**.  
![Defender Firewall in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/defender-firewall.jpg)
5. Head over to the left pane and choose **Restore defaults**.  
![Restore defaults for firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-defaults.jpg)

1. Confirm the action in the following prompt and proceed with the on-screen instructions to proceed.
2. Once done, open Run again.
3. Type "cmd" in the text field and press **Ctrl** \+ **Shift** \+ **Enter** keys together. This will open Command Prompt with administrator privileges.
4. Click **Yes** in the User Account Control prompt.
5. Once you are inside the Command Prompt window, type the command mentioned below and click **Enter** to execute it. This will force enable the Firewall component.  
`netsh firewall set opmode mode=ENABLE exceptions=enable`
6. Wait for the command to execute and then restart your computer. Check if the problem is now fixed.

## 4\. Modify the Registry Editor

 There is also a chance that a Registry key DisableAntiSpyware is enabled, which is preventing you from enabling Firewall on your computer.

 To check if this is the case in your situation, you can access the Registry Editor and check the status of the DisableAntiSpyware key.

 However, before you proceed, we highly recommend [creating a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just to be safe.

 Once that is done, proceed with the steps below:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "regedit" in Run and click **Enter**.
3. Click **Yes** in the User Account Control prompt.
4. In the Registry Editor, navigate to the location below.  
`​​​​​​​HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender`
5. Move to the right side and look for the DisableAntiSpyware key. If you locate it, delete it. You can also double-click on it and change its value to 0 if you do not want to delete it.  
![Disable or delete the registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/antispyware-key.jpg)

1. Once done, head over to the following location:  
`​​​​​​​​​​​​​​HKEY_LOCAL_MACHINE/SYSTEM/CurrentControlSet/Services/BFE`
2. Right-click on the **BFE** key and choose **Permissions** from the context menu.  
![Access permissions of the key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/access-permissions.jpg)
3. Under "Group or user names", click on **Add**.
4. Type "Everyone" in the "Enter the object names to select" and click **OK**.  
![Modify permissions of the key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/modify-permissions.jpg)
5. Now, head over to the "Permissions for Everyone" section and checkmark the box associated with **Full Control** under Allow.
6. Click **Apply** to save the changes and check if the issue is now resolved.

## Additional Generic Fixes to Try

 Apart from the fixes we have listed above, here are some additional solutions that you can try to fix the Firewall problem.

* **Ensure relevant services are running**: Windows Firewall relies on several services to function properly. Ensure that the Windows Defender Firewall, Windows Defender Advanced Threat Protection, Windows Defender Antivirus Network Inspection, and Windows Defender Antivirus services are working fine in the Windows Services utility.
* **Scan with SFC**: You can also scan the system for underlying corruption errors that might be leading to the problem using the [System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/). You can run it via Command Prompt and analyze the results to find the culprit.
* **Clean install Windows**: If nothing works and it is essential for you to enable Firewall, you can [perform a clean install](https://www.makeuseof.com/how-to-clean-install-windows-11/) of Windows. It will wipe the existing installation and download a new one without any underlying problems.

## Protect Your System With Windows Firewall

 The steps above should help you fix issues with Windows Firewall easily. If the error persists and you do not want to clean install the system yet, you can report the issue to Microsoft and wait for them to suggest a fix.

 Below, we explore the different solutions you can try to fix this issue for good.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/enhancing-pc-repair-access-with-windows-troubleshooting-hotkeys/"><u>Enhancing PC Repair Access with Windows Troubleshooting Hotkeys</u></a></li>
<li><a href="https://android-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-nokia-c12-pro-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Nokia C12 Pro</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-vivo-y78t-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Vivo Y78t Phone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-final-cut-pro-tutorial-adding-emotional-depth-with-the-ken-burns-effect-updated-2023/"><u>In 2024, Final Cut Pro Tutorial Adding Emotional Depth with the Ken Burns Effect (Updated 2023)</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-your-apple-iphone-xr-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Reset Your Apple iPhone XR Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/create-stunning-video-invites-for-free-top-online-makers-for-2024/"><u>Create Stunning Video Invites for Free Top Online Makers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-in-use-errors-unique-device-names-on-windows-pcs/"><u>Clearing Up In Use Errors: Unique Device Names on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-your-windows-experience-the-power-of-winstall-for-app-groups/"><u>Optimizing Your Windows Experience: The Power of Winstall for App Groups</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-windows-mouse-experience/"><u>Customize Your Windows Mouse Experience</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-non-changeable-energy-modes-in-windows-11/"><u>Navigating Non-Changeable Energy Modes in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/from-sealed-boxes-to-digital-realm-unlocking-windows-11-with-a-window-7-key/"><u>From Sealed Boxes to Digital Realm: Unlocking Windows 11 With a Window 7 Key</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-honor-x50-by-drfone-android/"><u>In 2024, AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Honor X50</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/successfully-sending-videos-in-facebook-chat-a-quick-fix-guide-for-iphoneandroid-for-2024/"><u>Successfully Sending Videos in Facebook Chat  A Quick Fix Guide for iPhone/Android for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/a-comprehensive-review-of-the-lightroom-app-on-android-for-2024/"><u>A Comprehensive Review of the Lightroom App on Android for 2024</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-apple-iphone-14-drfone-by-drfone-virtual-ios/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Apple iPhone 14 | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/unlocking-engagement-the-importance-of-properly-sized-vertical-videos-for-2024/"><u>Unlocking Engagement The Importance of Properly Sized Vertical Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/ignite-your-pc-bypassing-windows-11-lag-and-latency/"><u>Ignite Your PC: Bypassing Windows 11 Lag & Latency</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-user-authentication-management-for-domains-in-w11/"><u>Perfecting User Authentication Management for Domains in W11</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-taskbar-space-on-windows-11-os/"><u>Customizing Taskbar Space on Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/gpt4all-free-chatbot-clones-at-home-for-windows/"><u>GPT4All: Free ChatBot Clones at Home for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/in-place-upgrade-mastery-simplify-your-transition-to-windows-11/"><u>In-Place Upgrade Mastery: Simplify Your Transition to Windows 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-livescreen-capture-halt-guidebook/"><u>[Updated] In 2024, LiveScreen Capture Halt Guidebook</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-top-audio-transformation-software-magic-and-more/"><u>2024 Approved  Top Audio Transformation Software  Magic and More</u></a></li>
<li><a href="https://win11.techidaily.com/master-guide-winning-strategies-for-selecting-best-windows-emulators/"><u>Master Guide: Winning Strategies for Selecting Best Windows Emulators</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-screen-to-oppo-a1x-5g-phones-drfone-by-drfone-android/"><u>In 2024, How to Mirror PC Screen to Oppo A1x 5G Phones? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-antivirus-conflicts-with-ms-defender/"><u>Navigating Through Antivirus Conflicts with MS Defender</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-nubia-red-magic-8s-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Nubia Red Magic 8S Pro+? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhancing-real-time-response-on-windows-discord/"><u>Enhancing Real-Time Response on Windows Discord</u></a></li>
<li><a href="https://win11.techidaily.com/reboot-your-esc-key-woes-in-a-flash-with-this-guide/"><u>Reboot Your Esc Key Woes in a Flash With This Guide</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-behind-the-screen-essential-post-vidcon-gatherings/"><u>2024 Approved  Behind the Screen  Essential Post-VidCon Gatherings</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-read-only-on-windows-folders-amidst-issues/"><u>Bypassing Read-Only on Windows Folders Amidst Issues</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-common-windows-camera-app-malfunctions/"><u>Fixing Common Windows Camera App Malfunctions</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reset-chromes-erroneous-virus-protection-alerts/"><u>How to Reset Chrome's Erroneous Virus Protection Alerts</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-navigating-through-post-production-color-nuances/"><u>[New] Navigating Through Post-Production Color Nuances</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-unlock-creative-potential-crafting-tiktok-videos-using-templates/"><u>In 2024, Unlock Creative Potential  Crafting TikTok Videos Using Templates</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-without-mishap-avoiding-errors-in-windows-11/"><u>Navigating Without Mishap: Avoiding Errors in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-bypassing-defender-firewall-in-win11/"><u>Mastering the Art of Bypassing Defender Firewall in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/grasping-group-policies-in-windows-environments/"><u>Grasping Group Policies in Windows Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-productivity-essential-win11-and-command-tips-for-efficiency/"><u>Elevate Productivity: Essential Win11 and Command Tips for Efficiency</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-embrace-cold-choosing-heated-backdrops-for-youtube/"><u>[Updated] Embrace Cold  Choosing Heated Backdrops for YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/gpt4alls-local-window-companion-a-cost-free-chatbot-clone/"><u>GPT4All's Local Window Companion - A Cost-Free ChatBot Clone</u></a></li>
<li><a href="https://win11.techidaily.com/pixel-perfection-embedding-zip-files-in-windows-images-unseen/"><u>Pixel Perfection: Embedding Zip Files in Windows Images Unseen</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/why-is-ipogo-not-working-on-honor-90-pro-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On Honor 90 Pro? Fixed | Dr.fone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-elevate-your-storytelling-easy-online-video-creation-with-wevideo/"><u>Updated In 2024, Elevate Your Storytelling Easy Online Video Creation with WeVideo</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-file-properties-a-windowayers-manual/"><u>Fine-Tuning File Properties: A Window'ayer's Manual</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-videos-from-iphone-14-without-backup-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Deleted Videos from iPhone 14 Without Backup? | Stellar</u></a></li>
<li><a href="https://win11.techidaily.com/break-the-code-a-list-of-quick-access-techniques-for-credentials-in-win11/"><u>Break the Code: A List of Quick Access Techniques for Credentials in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/historical-code-to-contemporary-computing-windows-7-to-11-activation/"><u>Historical Code to Contemporary Computing: Windows 7 to 11 Activation</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-mp4-play-on-sony-xperia-1-v-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Does MP4 play on Sony Xperia 1 V?</u></a></li>
<li><a href="https://techidaily.com/samsung-galaxy-m34-5g-tutorial-bypass-lock-screen-security-password-pin-fingerprint-pattern-by-drfone-android-unlock-android-unlock/"><u>Samsung Galaxy M34 5G Tutorial - Bypass Lock Screen,Security Password Pin,Fingerprint,Pattern</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-change-realme-narzo-60x-5g-lock-screen-clock-in-seconds-by-drfone-android/"><u>In 2024, How To Change Realme Narzo 60x 5G Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-the-art-of-streaming-saved-media-easy-igtv-downloads-on-pc-and-mac/"><u>In 2024, The Art of Streaming Saved Media  Easy IGTV Downloads on PC & Mac</u></a></li>
<li><a href="https://win11.techidaily.com/correction-procedure-for-windows-error-0xca00a009/"><u>Correction Procedure for Windows Error 0xCA00A009</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-open-the-snipping-tool-in-windows-11/"><u>How to Open the Snipping Tool in Windows 11</u></a></li>
</ul></div>
