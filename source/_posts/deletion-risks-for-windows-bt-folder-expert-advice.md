---
title: "Deletion Risks for Windows ~BT Folder: Expert Advice"
date: 2024-07-13T10:56:10.913Z
updated: 2024-07-14T10:56:10.913Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Deletion Risks for Windows ~BT Folder: Expert Advice"
excerpt: "This Article Describes Deletion Risks for Windows ~BT Folder: Expert Advice"
keywords: Win BT Deletion Risk,Folder Safety Windows,IT BT Delete Tips,Preventing Windows Loss,BT Files Security Guide,Safe Deletion Windows,Protect Windows Folders
thumbnail: https://thmb.techidaily.com/a5dde8e23432eb9faea6481b1841af4ec33dc75da64317f31b7964d607abcd74.jpg
---

## Deletion Risks for Windows ~BT Folder: Expert Advice

 Deleting the hidden "$Windows.\~BT" folder and recovering gigabytes of space on your hard drive is tempting. But what is this cryptically named folder for, and how critical is it to your Windows installation?

## What Is the “$Windows.\~BT” Folder, and Should You Delete It?

 Windows creates the "$Windows.\~BT" folder when you upgrade the operating system to a newer build. This folder contains all the essential files for the upgrade process, like temporary installation files and logs from the previous Windows installation.

 Windows automatically removes the "$Windows.\~BT" folder after 10 days. As manually deleting this folder will [remove old Windows installation files](https://www.makeuseof.com/tag/delete-old-windows-update-files/), you won't be able to roll back to the previous Windows build using the **Go back** option in the Recovery menu within that time (for example, to [downgrade from Windows 11 to Windows 10](https://www.makeuseof.com/windows-11-downgrade-to-windows-10/)). Hence, you should only get rid of this folder if you are satisfied with the current Windows build on your PC. You can also safely delete the massive folder if Windows fails to do it automatically after the grace period.

 But you shouldn't just delete this hidden folder like any other folder on the desktop. Instead, you should turn to the Disk Cleanup tool or the Command Prompt.

## How to Find and Delete the "$Windows.\~BT" Folder

 As "$Windows.\~BT" is a hidden folder, you need to [configure Windows to show hidden files and folders](https://www.makeuseof.com/windows-11-show-hidden-files-folders/) to find it in File Explorer. Once you do, the **C:\\$Windows.\~BT** directory will become visible.

 You can’t delete the "$Windows.\~BT" folder directly, though. To do so, you need to run the Disk Cleanup tool. Here's how:

1. Press **Win + R** to open the Run dialog box.
2. Type **cleanmgr** in the box and press **Enter**.
3. Use the dropdown menu to select the system drive (usually **C:**) and click **OK**.
4. Click the **Clean up system files** button.
5. Under **Files to delete**, use the checkboxes to select these options: **Previous Windows Installations**, **Windows Update Cleanup**, **Windows upgrade log files**, **Temporary Windows installation files**, and **Temporary files**.
6. Click **OK**.
7. Choose **Delete Files** to confirm.  
![Delete the $Windows.~BT Folder Using the Disk Cleanup Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/delete-the-windows-bt-folder-using-the-disk-cleanup-tool.jpg)

 If the "$Windows.\~BT" folder shows up even after you run the Disk Cleanup tool, you'll need to execute a few commands in Command Prompt. For that, [open Command Prompt with administrative rights](https://www.makeuseof.com/windows-run-command-prompt-admin/) and then run the following commands one by one.

`takeown /F C:\$Windows.~BT\* /R /A
icacls C:\$Windows.~BT\*.* /T /grant administrators:F
rmdir /S /Q C:\$Windows.~BT\`

 Once you run the above commands, the "$Windows.\~BT" folder will be deleted for good.

 Now that you understand the purpose of the "$Windows.\~BT" folder, you can decide how to handle it. Beyond the "$Windows.\~BT" folder, you may also come across folders like "Windows.old," "$WinREAgent," "$SysReset," and others which can also be deleted safely using the Disk Cleanup tool.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/how-does-microsofts-copilot-key-transform-windows-11/"><u>How Does Microsoft's Copilot Key Transform Windows 11?</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-rescuing-flaky-windows-programs/"><u>Mastering the Art of Rescuing Flaky Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-vanished-hardware-on-windows/"><u>Resolving Vanished Hardware on Windows</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-from-ordinary-to-outstanding-unveiling-the-secrets-of-engaging-biographies/"><u>[Updated] From Ordinary to Outstanding  Unveiling the Secrets of Engaging Biographies</u></a></li>
<li><a href="https://win11.techidaily.com/reorient-your-windows-a-guide-to-90-degree-display-adjustment/"><u>Reorient Your Windows: A Guide to 90-Degree Display Adjustment</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-11s-hidden-data-files/"><u>Navigating Through Windows 11'S Hidden Data Files</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-how-to-save-your-video-tweets-as-high-quality-mp3-files/"><u>[Updated] How to Save Your Video Tweets as High-Quality MP3 Files</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-best-buys-for-your-digital-chime-preferences-in-snapchat/"><u>[New] Best Buys for Your Digital Chime Preferences in SnapChat</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-2024-approved-the-ultimate-guide-to-sourcing-premium-background-images/"><u>[New] 2024 Approved  The Ultimate Guide to Sourcing Premium Background Images</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-why-is-ipogo-not-working-on-samsung-galaxy-m14-5g-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, Why is iPogo not working On Samsung Galaxy M14 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/hunting-down-crafted-metallic-chime-echoes-for-2024/"><u>Hunting Down Crafted Metallic Chime Echoes for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/elite-screen-grabbers-5-non-windows-counterparts-to-snipping-tool/"><u>Elite Screen Grabbers: 5 Non-Windows Counterparts to Snipping Tool</u></a></li>
<li><a href="https://win11.techidaily.com/rescue-your-browser-fix-google-chrome-in-w11-today/"><u>Rescue Your Browser: Fix Google Chrome in W11 Today!</u></a></li>
<li><a href="https://win11.techidaily.com/rebooting-strategies-your-file-explorer-fixes/"><u>Rebooting Strategies: Your File Explorer Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/modify-homescreen-without-altering-windows-11-start-menu/"><u>Modify Homescreen without Altering Windows 11 Start Menu</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-workflow-mastering-window-commands-and-shortcuts/"><u>Streamline Your Workflow: Mastering Window Commands & Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-enhancing-interface-through-ms-store-themes/"><u>Effortlessly Enhancing Interface Through MS Store Themes</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-enhancing-user-experience-combining-instagram-and-facebook/"><u>In 2024, Enhancing User Experience  Combining Instagram & Facebook</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionary-driver-solutions-at-no-cost-to-optimize-windows-cars/"><u>Revolutionary Driver Solutions at No Cost to Optimize Windows Cars</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-delaying-windows-10-shutdown-processes/"><u>Mastering the Art of Delaying Windows 10 Shutdown Processes</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-scripts-in-windows-quick-fixes-for-loading-powershell-failures/"><u>Enabling Scripts in Windows: Quick Fixes for Loading PowerShell Failures</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-the-activation-lock-on-your-ipad-and-iphone-xr-without-apple-account-by-drfone-ios/"><u>In 2024, How to Remove the Activation Lock On your iPad and iPhone XR without Apple Account</u></a></li>
<li><a href="https://win11.techidaily.com/foster-innovation-for-privacy-protection-explore-cutting-edge-technologies-like-onboard-anonymization-systems-or-secure-data-transmission-techniques-to-mini44/"><u>Foster Innovation for Privacy Protection: Explore Cutting-Edge Technologies Like Onboard Anonymization Systems or Secure Data Transmission Techniques to Minimize the Risk of Violating Customer's Privacy During Cookie Deliveries.</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-splitscreen-designer/"><u>In 2024, SplitScreen Designer</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-time-lapse-photography-made-easy-top-apps-for-iphone-and-android/"><u>Updated In 2024, Time-Lapse Photography Made Easy Top Apps for iPhone and Android</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-the-mouse-without-borders-and-peek-features-in-powertoys/"><u>How to Use the Mouse Without Borders and Peek Features in PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/skilled-tactics-bypassing-windows-11s-security-measures/"><u>Skilled Tactics: Bypassing Windows 11'S Security Measures</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-unleash-your-creativity-how-to-edit-nikon-video-files-with-ease/"><u>Updated 2024 Approved Unleash Your Creativity How to Edit Nikon Video Files with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-video-memory-crashes-in-hogwarts-legacy-windows-edition/"><u>Remedying Video Memory Crashes in 'Hogwarts: Legacy' Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-installation-in-vmware-17-player/"><u>Mastering Windows 11 Installation in VMWare 17 Player</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-motorola-frp-in-3-different-ways-by-drfone-android/"><u>In 2024, How To Bypass Motorola FRP In 3 Different Ways</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-win11-22h2-for-older-systems/"><u>Navigating Win11 22H2 for Older Systems</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-shifting-printer-preferences-in-windows/"><u>Overcoming Shifting Printer Preferences in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-error-0x80040610-restoring-smooth-functionality-to-outlook/"><u>Tackling Error 0X80040610: Restoring Smooth Functionality to Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-retain-calculator-top-status-on-win-os/"><u>Methods to Retain Calculator Top Status on Win OS</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-unleash-your-voice-budget-friendly-tools-to-clear-out-background-noise/"><u>Updated 2024 Approved Unleash Your Voice Budget-Friendly Tools to Clear Out Background Noise</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-essential-audio-transforming-software-for-streamers-for-2024/"><u>[Updated] Essential Audio Transforming Software for Streamers for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-image-size-made-simple-a-beginners-guide-to-ratio-calculators/"><u>Updated 2024 Approved Image Size Made Simple A Beginners Guide to Ratio Calculators</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-for-error-0x800700e1-in-windows-11-os/"><u>Essential Fixes for Error 0X800700E1 in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/from-simple-logon-to-strong-authentication-changing-your-windows-11-login-habit/"><u>From Simple Logon to Strong Authentication: Changing Your Windows 11 Login Habit</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-media-player-disruptions/"><u>Overcoming Windows Media Player Disruptions</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-clear-obstacles-no-access-allowed-windows-errors/"><u>Methods to Clear Obstacles: No Access Allowed Windows Errors</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/interactive-display-armada-on-lenovo-fixed/"><u>Interactive Display Armada on Lenovo Fixed</u></a></li>
<li><a href="https://win11.techidaily.com/peering-into-windows-essence-crafting-and-evaluating-system-data/"><u>Peering Into Windows Essence: Crafting & Evaluating System Data</u></a></li>
<li><a href="https://win11.techidaily.com/file-locations-decoded-win11s-best-practices-for-retrieving-file-and-folder-paths-6-methods/"><u>File Locations Decoded: Win11's Best Practices for Retrieving File & Folder Paths (6 Methods)</u></a></li>
<li><a href="https://win11.techidaily.com/is-steam-unable-to-connect-to-the-internet-on-windows-heres-how-to-fix-it/"><u>Is Steam Unable to Connect to the Internet on Windows? Here's How to Fix It</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-pros-recommendations-for-free-and-paid-drawing-software-on-pc/"><u>In 2024, Pro's Recommendations for Free & Paid Drawing Software on PC</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-infinix-smart-8-pro-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Infinix Smart 8 Pro | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-maximizing-efficiency-in-rl-video-recordings/"><u>2024 Approved  Maximizing Efficiency in RL Video Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-solve-active-directory-issues-impacting-print-in-windows-11/"><u>How to Solve Active Directory Issues Impacting Print in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-tackle-misdirected-token-call-on-windows/"><u>Methods to Tackle Misdirected Token Call” On Windows</u></a></li>
<li><a href="https://win11.techidaily.com/revamp-your-window-11-experience-with-these-6-desired-android-apps/"><u>Revamp Your Window 11 Experience with These 6 Desired Android Apps</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-modern-techniques-for-incorporating-lame-encoder-with-audacity/"><u>In 2024, Modern Techniques for Incorporating Lame Encoder with Audacity</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-6-free-daw-software-for-beginners-to-use-for-2024/"><u>Updated 6 Free DAW Software for Beginners to Use for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-nubia-z50s-pro-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Nubia Z50S Pro | Dr.fone</u></a></li>
</ul></div>
