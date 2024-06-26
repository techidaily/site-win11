---
title: "Stop Windows Update Freeze: Implementing Effective Fixes"
date: 2024-06-25T09:56:13.023Z
updated: 2024-06-26T09:56:13.023Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Stop Windows Update Freeze: Implementing Effective Fixes"
excerpt: "This Article Describes Stop Windows Update Freeze: Implementing Effective Fixes"
keywords: Stop Freeze Updates,Windows Update Fixes,End Windows Stall,Update Issue Solutions,Prevent Update Crash,Smooth Windows Updates,Fixing Windows Freeze
thumbnail: https://thmb.techidaily.com/f48216f44870658586ad3ccce716597fb01e77f0820fb3295ce715c935d7c91e.jpg
---

## Stop Windows Update Freeze: Implementing Effective Fixes

 Update errors are nothing new for Windows users. In some cases, the updates simply do not start, while in others, they start fine, but become stuck at some point.

 There have been reports by users that the system updates get stuck at 100% and prevent the PC from restarting automatically. This issue can be caused by a number of reasons such as unexpected hardware changes, malware, interference of a third-party program, and corruption errors.

 Below, we have listed the most effective troubleshooting methods you can try to fix this issue for good.

## 1\. Wait for the Process to Complete

 It may take longer for some Windows updates to install, so before you begin troubleshooting, ensure that the update is stuck and not in between operations.

 The best way to do this is by waiting for the process to complete on its own. You should give the update process at least 3-4 hours before proceeding with the troubleshooting methods if you can. Some users left their computers overnight for the updates to be installed.

 We understand that waiting this long might not be possible for everyone and if it does not suit you as well, go ahead with the methods below. It is also important to note that before proceeding with the methods in this guide that require you to access your system, you will need to break the update loop that is causing the issue. To do this, reboot your PC to perform the steps listed.

## 2\. Remove Any USB Peripherals and Restart Your PC

 Start by removing any USB peripherals that may be connected to your PC. When you have extra external devices connected, your PC thinks of it as a change in the default hardware settings, leading to issues like the one at hand.

 Once you have removed all peripherals, wait for a few minutes and see if it makes any difference. If not, you can try force restarting the PC. However, this method involves removing the battery from your laptop, so we recommend you only proceed if you have some experience doing so.

 Here is how you can force restart your PC:

1. Press and hold the power button of your PC to shut it down.
2. Once it shuts down, remove the power supply and battery.
3. Then, wait for a few minutes before inserting it back.
4. Now, boot your PC and see if the issue is resolved.

## 3\. Restart the Windows Update Service

 The Windows Update service handles the download, installation, and removal of updates on your system. If this service is disabled or not working as it is supposed to, you are likely to encounter issues while updating your operating system and its applications.

 If removing the external peripherals did not help, then you can try restarting the Windows Update service.

 Here is how you can make sure that the update service is running properly:

1. Press **Win** \+ **R** to open Run.
2. Type "services.msc" in Run and press **Enter**.
3. In the following window, look for the Windows Update service and right-click on it.
4. Choose **Properties** from the context menu.  
![Windows update service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/services-windows-update-properties.jpg)
5. In the Properties dialog, click on the **Stop** button.  
![Stop button in Properties dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/win10-windows-update-properties-stop.jpg)
6. Wait for a few seconds before hitting the **Start** button again.
7. Expand the dropdown for Startup type and choose **Automatic** from the list.  
![Startup type of service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/windows-update-automatic-startup-type.jpg)
8. Click **Apply** \> **OK** to save the changes.

## 4\. Scan for Viruses

 Your operating system might also be infected with a virus or corruption error that is preventing you from installing the latest updates.

 To check if this is the case, try running a system scan using the security program you have installed on your PC. If you do not have a third-party security program, you can [run built-in troubleshooting utilities like SFC, DISM, and CHKDSK](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) via Command Prompt.

 However, if you are unable to use the basic Windows features and applications installed, then you must first [boot into Repair Mode](https://www.makeuseof.com/fix-windows-11-stuck-preparing-windows/). Once you are in the Repair Mode, head over to **Troubleshoot** \> **Advanced options**. Then, choose **Command Prompt** from the list of options and run the scans.

![Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win10-command-prompt.jpg)

 If these utilities find any issues, they will attempt to resolve them without requiring your input. After the scans, check if the issue is resolved.

## 5\. Run the Windows Update Troubleshooter

 Another troubleshooting method that has helped users fix the issue is running the Windows Update troubleshooter. This is a built-in utility that is specifically designed by Microsoft to fix issues regarding Windows updates.

 Here is how you can run it:

1. Press **Win** \+ **I** to open Windows Settings.
2. Choose **Troubleshoot** from the left pane and click on **Other troubleshooters** on the right side of the window.  
![other troubleshooters](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/other-troubleshooters-1.jpg)
3. In the following window, look for Windows Update troubleshooter and click on the **Run** button associated with it.  
![Run button for Windows Update troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/windows-update-troubleshooter.jpg)
4. The troubleshooter will now begin scanning the system for potential errors. If it finds issues, it will recommend fixes. In that case, click on **Apply this fix**.
5. If not, click **Close the troubleshooter** and move to the next method below.

## 6\. Boot Into Safe Mode

 Safe Mode is a Windows mode that launches Windows with only the basic drivers and programs. This troubleshooting mode helps users determine if a background process is causing issues within the system.

 In this method, we will first boot into Safe Mode using the Repair Mode and then restart the PC normally. Hopefully, this will fix the problem at hand.

 Here is what you need to do:

1. Boot Windows and during the process, press the F11 key repeatedly till Windows displays the Advanced Startup screen.
2. Head over to navigate to **Troubleshoot** \> **Advanced options** \> **Startup settings**.  
![Startup settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win10-startup-settings.jpg)
3. Click on the **Restart** button in the following window.  
![Restart button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win10-startup-settings-restart.jpg)
4. Hit the F5 key on the keyboard to proceed. This will launch the Safe Mode successfully.
5. In Safe Mode, restart your PC the normal way (**Start menu** \> **Sign out** \> **Restart**).  
![Restart Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/win11-safe-mode-restart.jpg)

 Upon reboot, the issue should no longer appear. You can now check if the updates are successfully installed. If not, you can try any one of [the different methods to update Windows manually](https://www.makeuseof.com/update-windows-manually/).

## Resume the Update Process on Windows 11

 We hope that at least one of the methods listed above was able to help you. Nevertheless, if you have come this far without finding a solution, you should consider performing a complete system reset since the issue is likely caused by a component that conventional troubleshooting methods cannot fix.

 There have been reports by users that the system updates get stuck at 100% and prevent the PC from restarting automatically. This issue can be caused by a number of reasons such as unexpected hardware changes, malware, interference of a third-party program, and corruption errors.

 Below, we have listed the most effective troubleshooting methods you can try to fix this issue for good.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/secure-and-cost-free-windows-password-gen-options-listed/"><u>Secure & Cost-Free Windows Password Gen Options Listed</u></a></li>
<li><a href="https://win11.techidaily.com/top-6-windows-tools-optimize-multi-screen-brightness/"><u>Top 6 Windows Tools: Optimize Multi-Screen Brightness</u></a></li>
<li><a href="https://win11.techidaily.com/keyboard-techniques-to-effectively-modify-software-sizes-in-win11/"><u>Keyboard Techniques to Effectively Modify Software Sizes in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-hyper-v-error-0x8009030e/"><u>Overcoming Windows Hyper-V Error 0X8009030E</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-unresponsive-windows-11-printer-ports-and-devices/"><u>Tackling Unresponsive Windows 11 Printer Ports & Devices</u></a></li>
<li><a href="https://win11.techidaily.com/1719365130359-mastery-over-malfunctioning-windows-easy-fixes-at-hand/"><u>Mastery Over Malfunctioning Windows: Easy Fixes at Hand</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-interruptexceptionnothandled-in-w11-bsods/"><u>Resolving INTERRUPT_EXCEPTION_NOT_HANDLED in W11 BSODs</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/accelerate-engagement-implementing-the-top-12-video-growth-strategies/"><u>Accelerate Engagement - Implementing the Top 12 Video Growth Strategies</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Oppo Reno 11F 5G | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-do-you-unlock-your-iphone-6s-learn-all-4-methods-drfone-by-drfone-ios/"><u>In 2024, How Do You Unlock your iPhone 6s? Learn All 4 Methods | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-remove-screen-lock-pin-on-nubia-red-magic-9-proplus-like-a-pro-5-easy-ways-by-drfone-android/"><u>In 2024, How To Remove Screen Lock PIN On Nubia Red Magic 9 Pro+ Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-level-up-your-auditory-game-in-valorant-with-this-must-try-free-tool/"><u>[Updated] Level Up Your Auditory Game in Valorant with This Must-Try, Free Tool</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-still-using-pattern-locks-with-vivo-v27-pro-tips-tricks-and-helpful-advice-by-drfone-android/"><u>In 2024, Still Using Pattern Locks with Vivo V27 Pro? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-snapchat-boomerangs-demystified-your-comprehensive-guide/"><u>2024 Approved  Snapchat Boomerangs Demystified  Your Comprehensive Guide</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-6-youtuber-quizzes-to-know-which-youtuber-you-are/"><u>[New] 2024 Approved  6 YouTuber Quizzes to Know Which YouTuber You Are</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-unmasking-silence-how-to-speak-up-and-document-toxicity-in-virtual-communities-like-discord-for-2024/"><u>[Updated] Unmasking Silence  How to Speak Up and Document Toxicity in Virtual Communities Like Discord for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>