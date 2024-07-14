---
title: Unlocking the Secret of Your Computer's RAM Type
date: 2024-07-13T10:32:42.437Z
updated: 2024-07-14T10:32:42.437Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking the Secret of Your Computer's RAM Type
excerpt: This Article Describes Unlocking the Secret of Your Computer's RAM Type
keywords: RAM Guide,RAM Types Explained,Memory Configuration,Understanding RAM,CPU RAM Relationship,RAM Speed Optimization,System RAM Usage
thumbnail: https://thmb.techidaily.com/25814137ff2b0c0573cec745d5d0a7576d58b816448c60f70b991c5a0f3d865d.jpeg
---

## Unlocking the Secret of Your Computer's RAM Type

 Knowing the type of RAM installed on your Windows PC can help you make more informed decisions when upgrading or diagnosing performance issues. Thankfully, it’s possible to check the RAM type on your Windows PC without opening the computer case and getting your hands dirty.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.

## 1\. How to Check the RAM Type With Command Prompt

 The most straightforward to check the RAM type on your Windows PC is via Command Prompt. You can use this method even [if you're a beginner with the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/), as it only requires you to run a single command.

 Here's how you can check the RAM type on Windows using the Command Prompt:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the menu that appears.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. In the console, type the command mentioned below and press **Enter**.  
`wmic memorychip get devicelocator, memorytype`
4. Note down the code number under the **MemoryType** column.  
![Check Memory Type Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-command-prompt.jpg)

 Compare the numerical value from the **MemoryType** column with the following table to identify the RAM type. For instance, if the code number is **24**, it means your computer has **DDR3** RAM.

![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)

## 2\. How to Check the RAM Type With PowerShell

 Like Command Prompt, you can use PowerShell to find out the type of RAM installed on your Windows computer. Here are the steps for the same.

1. Press **Win + S** to open the search menu.
2. Type **powershell** in the box.
3. Select **Run as administrator**.
4. When the User Account Control (UAC) prompt appears, select **Yes** to continue.
5. Type the following command in the PowerShell window and hit **Enter**.  
`Get-CimInstance -ClassName Win32_PhysicalMemory | Format-Table SMBIOSMemoryType`  
![Check RAM Type Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-ram-type-using-powershell.jpg)

 Under the **SMBIOSMemoryType** column, note down the code number and compare it with the following table to determine the RAM type.

![A Table Showing RAM Type and Numeric Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/a-table-showing-ram-type-and-numeric-value.jpg)

## 3\. How to Check the RAM Type Using the Task Manager App

 Windows Task Manager can provide you with all the necessary hardware information you need about your PC, including the type of RAM installed. However, it's important to note that Task Manager does not show the memory type if your PC has [DDR4 or DDR5 RAM](https://www.makeuseof.com/ddr4-vs-ddr5-should-you-upgrade/). So, this method will only work for PCs with DDR3 or lower-generation RAM.

 To check the RAM type using Windows Task Manager, follow these steps:

1. Press **Ctrl + Shift + Esc** to open the Task Manager.
2. Switch to the **Performance** tab.
3. Select **Memory** from the left pane. You should see the amount and type of RAM your PC has in the top right corner of the screen.  
![Check Memory Type Using Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-windows-task-manager.jpg)

 The Windows Task Manager does more than show hardware information. You also use it to manage running programs, end tasks, and view resource usage. To learn more, read our guide on the best [Windows Task Manager tips that you may not know](https://www.makeuseof.com/tag/10-windows-task-manager-tricks-didnt-know/).

## 4\. How to Check the RAM Type Using CPU-Z

 If you're seeking a relatively uncomplicated method to check the RAM type along with other hardware details, you can use a third-party app like CPU-Z. It is available for free and allows you to access various sets of information about your computer, including details about both the CPU and the RAM.

 Download and open the [CPU-Z](https://www.cpuid.com/softwares/cpu-z.html) app on your PC. Click on the **Memory** tab to get a detailed breakdown of the installed RAM. Under the **General** section, look for the value in the **Type** field to know the type of RAM installed on your PC.

![Check Memory Type Using CPU-Z App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-memory-type-using-cpu-z-app.jpg)

## Know the Type of RAM Installed on Your Windows PC

 The performance of your computer is affected not only by the amount of RAM installed but also by the type of RAM. Fortunately, identifying the RAM type on your Windows PC is a quick and painless process with the methods mentioned above.

 This guide will walk you through some easy methods for identifying the type of RAM housed within your computer.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/unlocking-storage-potential-with-windows-iscsi-initiator/"><u>Unlocking Storage Potential with Windows iSCSI Initiator</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-text-interaction-emoji-15-on-windows-11-explained/"><u>Tailoring Text Interaction: Emoji 15 on Windows 11 Explained</u></a></li>
<li><a href="https://unlock-android.techidaily.com/the-ultimate-guide-to-infinix-smart-8-hd-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>The Ultimate Guide to Infinix Smart 8 HD Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/safe-harbor-for-windows-free-software-selections/"><u>Safe Harbor for Windows Free Software Selections</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/streamlined-processes-transforming-mac-videos-into-snaps/"><u>Streamlined Processes  Transforming Mac Videos Into Snaps</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-accessibility-of-your-offline-printer-on-windows/"><u>Regaining Accessibility of Your Offline Printer on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/taming-the-cloud-using-microsoft-onedrive-offline/"><u>Taming the Cloud: Using Microsoft OneDrive Offline</u></a></li>
<li><a href="https://win11.techidaily.com/pro-wls-2-strategies-optimizing-linux-experience-in-windows/"><u>Pro WLS 2 Strategies: Optimizing Linux Experience in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/solving-windows-11-menu-glitches-a-step-by-step-guide/"><u>Solving Windows 11 Menu Glitches: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/asus-vivobook-s-15-the-ultimate-student-friendly-laptop/"><u>ASUS Vivobook S 15: The Ultimate Student-Friendly Laptop</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-how-to-make-tiktok-dance-on-mac/"><u>In 2024, How to Make TikTok Dance on Mac</u></a></li>
<li><a href="https://win11.techidaily.com/setting-custom-keys-for-windows-applications/"><u>Setting Custom Keys for Windows Applications</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-swift-sketches-of-fortnite-game-screenshots/"><u>[Updated] Swift Sketches of Fortnite Game Screenshots</u></a></li>
<li><a href="https://win11.techidaily.com/solving-the-jittery-cursor-problem-on-windows-xp/"><u>Solving the Jittery Cursor Problem on Windows XP</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-lan-gaming-challenges-on-pc-winsminecraft/"><u>Overcoming LAN Gaming Challenges on PC, WinsMinecraft</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-the-complete-users-manual-to-extract-sound-from-videos-on-various-operating-systems-winmaciosandroid-2023-edition/"><u>Updated 2024 Approved The Complete Users Manual to Extract Sound From Videos on Various Operating Systems (Win/Mac/iOS/Android - 2023 Edition)</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-mastering-facebook-cover-videos-essential-insights/"><u>[New] 2024 Approved  Mastering Facebook Cover Videos  Essential Insights</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-fix-microsoft-powerpoint-not-printing-correctly-on-windows/"><u>9 Ways to Fix Microsoft PowerPoint Not Printing Correctly on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/solve-yellow-tint-issue-in-windows-monitorage/"><u>Solve Yellow Tint Issue in Windows Monitorage</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-addressing-stalled-video-transmission-tips-and-tricks-for-messenger-users-iosandroid/"><u>[Updated] Addressing Stalled Video Transmission  Tips and Tricks for Messenger Users iOS/Android</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-enhancing-instagram-experience-with-in-story-captions/"><u>[Updated] In 2024, Enhancing Instagram Experience with In-Story Captions</u></a></li>
<li><a href="https://screen-capture.techidaily.com/unleash-your-adventure-essential-tactics-for-saving-your-vr-gaming-experience-for-2024/"><u>Unleash Your Adventure  Essential Tactics for Saving Your VR Gaming Experience for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/top-tier-video-coders-for-windows-a-comparative-review/"><u>Top-Tier Video Coders for Windows: A Comparative Review</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-pc-non-compliance-intel-hd-graphics-setback/"><u>Addressing PC Non-Compliance: Intel HD Graphics Setback</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-comprehensive-movement-study-2023/"><u>[New] Comprehensive Movement Study 2023</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-missing-display-after-power-on/"><u>Overcoming Missing Display After Power On</u></a></li>
<li><a href="https://win11.techidaily.com/realigning-windows-error-solutions-for-efficiency/"><u>Realigning Windows Error Solutions for Efficiency</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-apple-iphone-12-pro-max-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-ios/"><u>How to Change Your Apple iPhone 12 Pro Max Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-in-2024-revolutionize-creative-tasks-with-proficiency-ai-voice-cloning/"><u>New In 2024, Revolutionize Creative Tasks With Proficiency AI Voice Cloning</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-methods-to-remove-restrictions-on-blocked-windows-files/"><u>Advanced Methods to Remove Restrictions on Blocked Windows Files</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-how-to-purge-personal-youtube-history-records/"><u>[New] How to Purge Personal YouTube History Records</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-peak-windows-11-performance-with-these-adjustments/"><u>Achieve Peak Windows 11 Performance with These Adjustments</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/forgot-iphone-passcode-again-unlock-apple-iphone-12-mini-without-passcode-now-by-drfone-ios/"><u>Forgot iPhone Passcode Again? Unlock Apple iPhone 12 mini Without Passcode Now</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-get-ready-for-dramatic-effects-add-slow-mo-to-your-videos-for-free/"><u>New 2024 Approved Get Ready for Dramatic Effects Add Slow Mo to Your Videos for Free</u></a></li>
<li><a href="https://win11.techidaily.com/a-closer-look-how-win11-collects-your-personal-data/"><u>A Closer Look: How Win11 Collects Your Personal Data</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-6s-to-others-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 6s To Others devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-prevent-and-fix-winscombsvrdll-crashes-on-pcs/"><u>Steps to Prevent and Fix WinscombSvr.dll Crashes on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/reveal-windows-secrets-to-handbrake-use/"><u>Reveal Windows' Secrets to HandBrake Use</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-a-non-operational-windows-netflix-service/"><u>Troubleshooting a Non-Operational Windows Netflix Service</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-file-privilege-hiccup-with-steam-and-win11-gameplay/"><u>Tackling File Privilege Hiccup with Steam & Win11 Gameplay</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-solve-the-non-operational-escape-button-on-your-desktop/"><u>Swiftly Solve the Non-Operational Escape Button on Your Desktop</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-gif-looping-made-easy-best-free-software/"><u>Updated 2024 Approved GIF Looping Made Easy Best Free Software</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-open-a-games-directory-on-windows/"><u>3 Ways to Open a Game's Directory on Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-photo-to-pixellated-panels-pro-windows-and-mac-edition/"><u>[Updated] Photo to Pixellated Panels Pro  Windows & Mac Edition</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-editors-almanac-key-takeaways-from-filmora-editioning/"><u>2024 Approved  The Editor’s Almanac  Key Takeaways From Filmora Editioning</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-unknown-value-issue-in-windows-tech-environment/"><u>Remedy for Unknown Value Issue in Windows Tech Environment</u></a></li>
<li><a href="https://win11.techidaily.com/secure-and-cost-free-windows-password-gen-options-listed/"><u>Secure & Cost-Free Windows Password Gen Options Listed</u></a></li>
<li><a href="https://win11.techidaily.com/prepare-for-airplane-mode-installation-of-win11/"><u>Prepare for Airplane Mode: Installation of Win11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-for-deleting-ms-edge-win11/"><u>Step-by-Step Guide for Deleting MS Edge Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/demystifying-windowsapps-get-inside/"><u>Demystifying WindowsApps: Get Inside</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-fake-snapchat-location-on-honor-play-40c-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Honor Play 40C | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-enabling-your-pen-on-windows-os/"><u>Quick Fix: Enabling Your Pen on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/windows-subsystem-for-android-is-going-away-what-should-you-do-now/"><u>Windows Subsystem for Android Is Going Away: What Should You Do Now?</u></a></li>
</ul></div>
