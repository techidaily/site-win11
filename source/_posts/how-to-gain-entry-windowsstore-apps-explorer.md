---
title: "How To Gain Entry: WindowsStore Apps Explorer"
date: 2024-07-13T10:48:23.763Z
updated: 2024-07-14T10:48:23.763Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes How To Gain Entry: WindowsStore Apps Explorer"
excerpt: "This Article Describes How To Gain Entry: WindowsStore Apps Explorer"
keywords: Windows Store Tips,Entering WinStore,App Explorer Guide,Enhancing WinApp Access,WindowsStore Optimization,Secure WinStore Entry,Insightful WinStore Search
thumbnail: https://thmb.techidaily.com/f858bf5f9e0327b42a985f450fae85190a7aad26feb7ee5b800247a93a2f3bb0.png
---

## How To Gain Entry: WindowsStore Apps Explorer

 The Windows Operating System has a hidden folder called "WindowsApps." It stores Microsoft application files and other important files to enhance your Windows experience. The folder usually contains a large amount of reusable space. This is because it also contains those application files you uninstalled from your PC earlier.

 Thankfully, you can remove unnecessary files from the WindowsApps folder to free up some space. But it's a little hard to get to this folder because it's protected and hidden in Windows File Explorer. Here are some ways to access the WindowsApps Folder on Windows and make necessary changes to it.

## What Is the WindowsApps Folder?

 You can find the WindowsApps folder under the **C:\\Program Files** directory in Windows 10 and 11\. This folder has all the files related to UWP packages or Windows apps that you get from the Microsoft Store or that come preinstalled on Windows OS.

 The problem is that a basic Windows user or even a system administrator user account can't access or change the files in the folder. This is because it is owned by a Microsoft account named "TrustedInstaller." We've already covered [everything about TrustedInstaller](https://www.makeuseof.com/tag/what-is-trustedinstaller-and-why-does-it-keep-me-from-renaming-files/) and how to disable it in detail.

![WindowsApps Hidden Folder In Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/WindowsApps-Hidden-Folder.jpg)

 Even if you uninstall or debloat some of the apps on Windows, the core application files are not removed from the WindowsApps folder. So, there are chances that such apps will reappear after a new Windows update.

 This is why we recommend using one of the [popular software uninstallers for Windows](http://www.makeuseof.com/windows-11-uninstallers-stubborn-apps/). Because these tools not only uninstall an app completely but also clean up any leftovers and traces from all the secured folders.

 If you don't know what you're doing—modifying or deleting the files in the WindowsApps folder could cause system errors or even cause the Windows operating system to crash.

 There are many ways to access the WindowsApps folder and bypass the protection to gain access to the necessary files.

## Method 1\. How to Access WindowsApps via File Explorer

 You can easily find the WindowsApps folder in the Windows File Explorer by unhiding the respective folder first. However, to access the folder and make changes to the files—you need to gain some extra rights by changing the ownership.

 Follow these steps to view the WindowsApps folder first:

1. Open the Windows File Explorer (**Win + E**) and go to the **C:\\Program Files** directory.  
![Program Files Directory In Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Program-Files-Directory-In-Explorer.jpg)
2. Now, click the **View** options button at the top of the File Explorer.
3. Click or hover over the **Show** button and select the **Hidden items** option to enable it.  
![File Explorer View Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/file-explorer-view-options.jpg)

 That's it. Now, you can see theWindowsApps folder in the same directory.

 If you try to open it, you'll see an information popup saying, "You have been denied permission." So, to actually access that folder and gain exclusive read and write rights—you've got to do a bit more.

### Change Ownership Properties to Get Access

 For the next steps, you need a user account with administrative rights. If you're a beginner, you must know [everything about the Administrator account](https://www.makeuseof.com/tag/windows-administrator-account-everything-need-know/) to understand the steps better.

 Follow the steps mentioned below to change the ownership rights and access the required folder:

1. Select the **WindowsApps** folder and right-click on it.
2. Once the context menu appears, select **Properties** from the list. You can also use a quick shortcut to open the folder properties, i.e., **Alt + Enter**.  
![WindowsApps Properties Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/WindowsApps-Properties-Option.jpg)
3. Now, under the **Properties** window. Click the **Security** tab and then the **Advanced** option locatedright at the bottom.  
![WindowsApps Security Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/WindowsApps-Security-Properties.jpg)
4. Once you've opened the Advanced Security Settings window, click the **Change** text next to Owner.
5. Now, click **Advanced > Find Now > Administrator on the following screen**.  
![Advanced Security Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/advanced-security-properties.jpg)
6. Finally, click **OK** to select the Administrator as the owner and again **OK** to save the changes.  
![User Group Selection Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/User-Group-Selection-Window.jpg)
7. Then, tick the checkbox before the **Replace owner on sub containers and objects** text.
8. Now, click the **Apply** button, followed by the **OK** button, to initiate the process of transferring ownership.  
![WindowsApps Advanced Security Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/WindowsApps-Advanced-Security-Settings.jpg)
9. Once done, click the **OK** button on the next pop-up.

 If you followed the steps above to take ownership of the WindowsApps folder, you can now move or delete files from that folder.

 When you don't pause automatic software installations from the Microsoft store, the WindowsApps folder occupies a considerable bit of disc space. So, it becomes essential for you to access this folder once and check for the files that you no longer need.

 Moreover, you can also check out some [free tools for taking control of files and folders](https://www.makeuseof.com/take-ownership-of-windows-files-and-folders-with-these-tools/) on Windows. Such tools allow you to take full ownership of all your files and folders with a single click.

## Method 2\. How to Access WindowsApps via a PowerShell Command

 The File Explorer-based method is pretty complicated for a newbie. Use PowerShell to complete your job if you're looking for an easy-to-go method. Using Windows PowerShell is a pretty straightforward and automated way of doing the same thing.

 Follow these steps to access the WindowsApps folder using PowerShell:

 1\. Launch the Windows start menu or Windows search by pressing **Win + Q**.

 2\. Type in **PowerShell** and click the **Run as Administrator** option to run PowerShell with administrator rights. Besides, you must also know some other [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) for future usage.

![PowerShell In Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/PowerShell-In-Windows-Search.jpg)

 4\. In Powershell, run the following command and press the Enter key:

`takeown /f &ldquo;C:\Program Files\WindowsApps&rdquo; /r`

![Change Ownership Command In Shell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Change-Ownership-Command-In-Shell.jpg)

 The above command will restore all the files or folder ownership to the system administrator. It will take some time for your administrator user account to become the owner of the WindowsApps folder and everything in it.

 The access you gain by executing the above process is similar to that of the Windows File Explorer-based method. You have just automated the process and eliminated the unhiding of system files. Now, you can back up, clear some space, or make changes to the Windows apps' back-end files.

 If you're facing crashes while executing the file, make sure to check out some [effective ways to fix PowerShell crash errors](http://www.makeuseof.com/windows-powershell-has-stopped-working-error-fix/).

## 3\. How to Access WindowsApps via a Registry Hack

 There's another quick way to do the same thing with just a few steps. If you cannot use the PowerShell method stated above, you can use a simple registry hack to access the files in one go.

 Here's how you can take full ownership of the context menu for your files and folders and get to the WindowsApps folder:

1. Download the [Take Ownership registry](https://www.majorgeeks.com/files/details/take%5Ffull%5Fownership%5Fof%5Ffiles%5Ffolders%5Fregistry%5Fhack.html) file.
2. Extract the zip and open the **Add Take Ownership to Context menu** registry file.  
![Take Ownership Registry File In Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Take-Ownership-Registry-File.jpg)
3. On the next screen, click **Yes** to add it to the registry.
4. Next, exit the popup by clicking **OK** and navigate to the **C:\\Program Files** directory.
5. Select the **WindowsApps** folder and right-click on it.
6. From the context menu, click the **Take Ownership** option.  
![Take Ownership Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Take-Ownership-Context-Menu.jpg)
7. In the Command Prompt, you must [give User Account Control Administrator rights](https://www.makeuseof.com/tag/user-account-control-windows-10/) for the registry hack to work. After that, please wait a few minutes for the window to close. Soon, it will display success messages constantly in the Command Prompt.

 Once finished, you'll no longer face the "You've been denied permission" error on clicking the WindowsApps folder.

## Enjoy Unrestricted Access to the WindowsApps Folder

 Using one of the provided methods, you should now be able to view the hidden files and folders inside the WindowsApps folder. Now that you know everything about it, you can easily make changes to the UWP packages that are safe.

 Moreover, in the WindowsApps folder—you can remove Windows app remnants, open any software directly from the .EXE file, and inspect all removed packages, among other things.

 The Windows Operating System has a hidden folder called "WindowsApps." It stores Microsoft application files and other important files to enhance your Windows experience. The folder usually contains a large amount of reusable space. This is because it also contains those application files you uninstalled from your PC earlier.

 Thankfully, you can remove unnecessary files from the WindowsApps folder to free up some space. But it's a little hard to get to this folder because it's protected and hidden in Windows File Explorer. Here are some ways to access the WindowsApps Folder on Windows and make necessary changes to it.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/techniques-stop-discord-initial-launch-and-searching-at-boot/"><u>Techniques: Stop Discord Initial Launch & Searching at Boot</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-charmap-incompatibility-challenges/"><u>Overcoming Windows CharMap Incompatibility Challenges</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-individual-gpo-settings-for-windows-users-1111-edition/"><u>Implementing Individual GPO Settings for Windows Users 11/11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-new-strategies-behind-extended-updates-in-windows-11-h2/"><u>Exploring the New Strategies Behind Extended Updates in Windows 11 H2</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-0x80d03801-issue-in-windows-shop/"><u>Remedying 0X80D03801 Issue in Windows Shop</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-exclusive-screen-savers-best-12-with-unlimited-recording/"><u>2024 Approved  Exclusive Screen Savers  Best 12 with Unlimited Recording</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-alternative-methods-in-windows-exploration-no-ls/"><u>Deciphering Alternative Methods in Windows Exploration (No LS)</u></a></li>
<li><a href="https://win11.techidaily.com/how-runtime-broker-enhances-system-efficiency-and-security/"><u>How Runtime Broker Enhances System Efficiency & Security</u></a></li>
<li><a href="https://win11.techidaily.com/quelling-the-0x800736cc-dilemran-in-windows-update/"><u>Quelling the 0X800736CC Dilemran in Windows Update</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-10-best-tools-to-bypass-icloud-activation-lock-on-iphone-12-mini-you-should-try-out-by-drfone-ios/"><u>The 10 Best Tools to Bypass iCloud Activation Lock On iPhone 12 mini You Should Try Out</u></a></li>
<li><a href="https://win11.techidaily.com/restore-peace-of-mind-with-these-5-family-safety-fixes/"><u>Restore Peace of Mind with These 5 Family Safety Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tip-converting-esd-to-iso-without-compromising-data-integrity-on-windows/"><u>Tech Tip: Converting ESD to ISO without Compromising Data Integrity on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-error-codes-when-installing-windows-apps/"><u>Understanding Error Codes When Installing Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-hello-login-fingerprint-failure/"><u>Eliminating Windows Hello Login Fingerprint Failure</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-solid-state-drive-speed-on-windows-via-ssd-fresh/"><u>Elevate Solid State Drive Speed on Windows via SSD Fresh</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-premiere-visual-document-evaluation/"><u>[Updated] 2024 Approved  Premiere Visual Document Evaluation</u></a></li>
<li><a href="https://win11.techidaily.com/whats-behind-yourphoneexe-in-modern-windows-systems/"><u>What's Behind YourPhone.exe in Modern Windows Systems?</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-enhance-your-digital-footprint-upload-tiktoks-on-twitter-for-2024/"><u>[Updated] Enhance Your Digital Footprint  Upload TikToks on Twitter for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/dive-into-efficiency-utilizing-windows-11s-taskbar-search/"><u>Dive Into Efficiency: Utilizing Windows 11'S Taskbar Search</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-expertly-curated-list-of-premier-audio-trimming-software-websites/"><u>In 2024, Expertly Curated List of Premier Audio Trimming Software Websites</u></a></li>
<li><a href="https://win11.techidaily.com/the-convenience-of-uwp-shortcuts-in-windows-11/"><u>The Convenience of UWP Shortcuts in Windows 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-next-generation-youtubers-8-accelerating-growth/"><u>2024 Approved  Next Generation Youtubers 8  Accelerating Growth</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-unresponsive-windows-11-printer-ports-and-devices/"><u>Tackling Unresponsive Windows 11 Printer Ports & Devices</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-apps-from-vivo-v27-pro-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Apps from Vivo V27 Pro to Another | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-stop-infinite-data-depletion-in-windows/"><u>5 Ways to Stop Infinite Data Depletion in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/surface-laptop-studio-review-the-quest-for-perfection-continues/"><u>Surface Laptop Studio Review: The Quest for Perfection Continues</u></a></li>
<li><a href="https://win11.techidaily.com/sweeping-away-windows-access-errors-effectively/"><u>Sweeping Away Windows' Access Errors Effectively</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-leveraging-color-grading-using-luts-in-ae/"><u>In 2024, Leveraging Color Grading Using LUTs in AE</u></a></li>
<li><a href="https://win11.techidaily.com/selecting-the-best-downloader-choco-vs-windows-package-tool/"><u>Selecting the Best Downloader: Choco Vs. Windows Package Tool</u></a></li>
<li><a href="https://win11.techidaily.com/secure-clipchamp-install-on-windows-11-with-these-steps/"><u>Secure ClipChamp Install on Windows 11 with These Steps</u></a></li>
<li><a href="https://win11.techidaily.com/essential-windows-microcomputers-reviewed/"><u>Essential Windows Microcomputers Reviewed</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-vivo-v29-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Vivo V29 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-instantaneous-folder-upload-failures-in-the-windows-onedrive-environment/"><u>Quick Fixes for Instantaneous Folder Upload Failures in the Windows OneDrive Environment</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-home-screen-norm-setting-default-position-of-win-11-keyboards/"><u>Achieving Home Screen Norm: Setting Default Position of Win 11 Keyboards</u></a></li>
<li><a href="https://win11.techidaily.com/locate-vanished-settings-a-guide-to-finding-them-on-win11/"><u>Locate Vanished Settings: A Guide to Finding Them on Win11</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-top-handheld-stabilizers-to-elevate-your-vlogging-game/"><u>In 2024, Top Handheld Stabilizers to Elevate Your Vlogging Game</u></a></li>
<li><a href="https://win11.techidaily.com/revitalize-pc-three-methods-for-a-clean-windows-boot/"><u>Revitalize PC: Three Methods for a Clean Windows Boot</u></a></li>
<li><a href="https://win11.techidaily.com/key-apps-to-bring-your-windows-pc-and-android-together/"><u>Key Apps to Bring Your Windows PC and Android Together</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-complete-control-over-clips-with-powerdirectors-latest-24-updates/"><u>In 2024, Complete Control Over Clips with PowerDirector's Latest '24 Updates</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-pc-experience-on-windows-11-devices/"><u>Tailoring Your PC Experience on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-repairing-code-0x0000004e-on-pcs/"><u>Step-by-Step: Repairing Code 0X0000004E on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/windows-adjusting-user-permissions-for-regular-accounts/"><u>Windows: Adjusting User Permissions for Regular Accounts</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-revamped-widget-picker-in-win11/"><u>Configuring Revamped Widget Picker in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-screen-savers-a-guide-to-win11/"><u>Tailoring Screen Savers: A Guide to Win11</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-clipboard-problems-in-windows-11/"><u>Diagnosing Clipboard Problems in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-folders-reverting-to-read-only-mode-in-windows-10-and-11/"><u>How to Fix Folders Reverting to Read-Only Mode in Windows 10 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/re-establishing-normal-operations-of-netflix-window/"><u>Re-Establishing Normal Operations of Netflix Window</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-correct-display-not-available-error-in-windows-11/"><u>How to Correct 'Display Not Available' Error in Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-huawei-p60-drfone-by-drfone-virtual-android/"><u>Will Pokémon Go Ban the Account if You Use PGSharp On Huawei P60 | Dr.fone</u></a></li>
</ul></div>
