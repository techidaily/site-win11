---
title: How to Map a Network Drive in Windows 11
date: 2024-06-25T11:29:40.799Z
updated: 2024-06-26T11:29:40.799Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Map a Network Drive in Windows 11
excerpt: This Article Describes How to Map a Network Drive in Windows 11
keywords: Navigate Drives Windows 11,Connect External Device Windows 11,Mapping Drives Procedure Windows,Windows 11 Network Drive Map,Link Drives in W11 OS,Establish Network Drive W11,Setup W11 Remote Repository
thumbnail: https://thmb.techidaily.com/33028f93fa14d69bbcfce2acf14136a66954cb281abb62aff639869e465c0177.jpg
---

## How to Map a Network Drive in Windows 11

 Mapping a network drive helps you access shared folders and files on a network. It allows you to access such resources as if they were on your local computer, making it easy to work with files stored on a network.

 This can be particularly useful for businesses or organizations with multiple computers or servers that want to share files and resources between them easily.

 But is it really that simple to set up mapping? Keep reading to learn how to map a network drive in Windows 11 using different methods.

## Configure Network Discovery in Windows

 Windows has a feature called[network discovery](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) that allows your computer to discover and access other devices on the same network, such as computers, servers, and printers.

 This allows you to share any file or folder with other devices on the same network. Before mapping a network drive, make sure that network discovery is enabled on your computer.

Follow the sets below to enable network discovery on Windows:

1. Press**Win + I** to open the Settings app.
2. Head over to**Network & internet** from the left pane and click on**Advanced network settings** on the right.
3. Next, click on the**Advanced sharing settings** option under**More Settings** .  
![Windows Advanced Network Sharing Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-advanced-network-settings.jpg)
4. Open the**Private networks** settings and set the toggle next to**Network discovery** to**On** .  
![Windows Advanced Sharing Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-advanced-sharing-settings.jpg)
5. If you're looking to access a printer on the network, make sure to enable**File and printer sharing** .

 Once you turn on network discovery, other devices on the same network can see your computer and access it.

 Select**Private networks** if you are connected to a trusted network, such as your home network. But if you're connected to an unfamiliar network, you should select the**Public networks** option.

 Remember that enabling network discovery may make your computer more vulnerable to security risks as it allows other devices on the network to access your computer.

 Therefore, it's crucial to ensure that you have a strong password and[customize your default Windows Firewall](https://www.makeuseof.com/windows-firewall-control-guide/) to protect your device in case something goes wrong.

## 1\. Map a Network Drive Using File Explorer

 Once you have turned on network discovery, you can map a network drive in Windows 11 using File Explorer.

Here's what you need to do to use File Explorer for mapping:

1. Press**Win + E** to open File Explorer directly, and click on**This PC** in the left pane.
2. Right-click on**This PC** and select the**Map network drive...** button in the context menu that appears.  
![This PC Context Menu In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/this-pc-context-menu-in-windows.jpg)
3. Choose a unique drive letter in the**Map Network Drive** window. This is the drive you'll use to access the shared folder from your computer. As an example, we've selected**A:** as the drive letter.
4. Enter the path to the shared folder you want to map in the**Folder:** field. This can be a local path on the computer, such as**\\\\YourComputer\\SharedFolder** , or a network path, such as**\\\\ServerName\\SharedFolder** .  
![Windows Shared Network Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-shared-network-folder.jpg)
5. If you need a username and password to access the shared folder, check the**Connect using different credentials** box and enter the required information.
6. Click**Finish** to complete the mapping process.  
![Map Network Drive In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/map-network-drive-in-windows.jpg)

 Once you have completed these steps, it'll map the folder to the specified drive letter in File Explorer. You can access the shared folder at any time by double-clicking on the drive.

 Want to access the shared folder in milliseconds? You can create a shortcut to the mapped network drive on your desktop for quick access.

## 2\. Use Windows PowerShell for Mapping

 Windows PowerShell is a Windows command-line utility that provides a powerful set of tools and commands. One of the tasks you can perform using PowerShell is to map a network drive.

Follow these instructions to map a drive using Windows PowerShell:

1. Open the Start menu and type**PowerShell** into the search bar.
2. Select the best match and choose**Run as administrator.**
3. In the PowerShell window, type the following command, replacing**DRIVE** with the drive letter you want to use and**\\** **\\ServerName\\SharedFolder** with the path to the shared folder:  
New-PSDrive -Name DRIVE -PSProvider FileSystem -Root \\ServerName\SharedFolder  
![PowerShell Mapping Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/powershell-mapping-command.jpg)
4. If the shared folder requires a username and password to access, you can add the -Credential parameter to the command, followed by a username and password in the format username and password. For example:  
New-PSDrive -Name X -PSProvider FileSystem -Root \\ServerName\SharedFolder -Credential username password
5. Hit**Enter** to allow PowerShell to map the network drive. You can access the mapped drive from File Explorer now.

 Besides mapping, you can do a wide range of things, like managing and automating tasks on Windows. For that, you must know some[useful PowerShell commands](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) .

## 3\. Use Command Prompt for Mapping

 Just like you used PowerShell earlier, you can use the Windows Command Prompt tool to map a network drive.

So, follow these simple instructions:

1. Open[Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. Type the command line given below, but replace**DRIVE** with any drive letter and**\\\\ServerName\\SharedFolder** with the shared folder's path:  
net use DRIVE \\ServerName\SharedFolder
3. If the shared folder requires a username and password to access, you can add the /user parameter to the command, followed by a username and password in the format**username** and**pass** . For example:  
net use DRIVE \\ServerName\SharedFolder /user:username pass  
![Mapping In Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/mapping-in-command-prompt.jpg)
4. Once you've made the required changes, hit**Enter** to execute the command.

 That's it. It'll take a few seconds, and then you can access the mapped drive from File Explorer with one click.

## How to Disconnect a Mapped Network Drive

 Disconnecting the network drive is a no-brainer if you no longer need access to the files on it.

 Here's how you can disconnect a mapped network drive in a few steps:

1. Press**Win + E** to open File Explorer.
2. Right-click on**Network** in the left pane and choose**Disconnect network drive** from the context menu.  
![Disconnect Mapped Drive In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/disconnect-mapped-drive.jpg)
3. In the next window, choose the drive letter or name of the network drive you want to disconnect. Click**OK** to disconnect it from your system.

 The mapped network drive will now disappear from File Explorer, and you can no longer access it from the drive letter you created earlier.

## Map Network Drives Easily in Windows 11

 Mapping a network drive in Windows 11 is a great way to access shared folders on other computers or servers. This can save you time and make managing and organizing your files easier.

 While mapping is only useful in the case of network drives, there are many other methods to share files without a network setup. For example, you can use external storage, cloud storage services, a data transfer cable, etc.


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
<li><a href="https://win11.techidaily.com/windows-warnings-identifying-critical-processes-for-malware-detection/"><u>Windows Warnings: Identifying Critical Processes for Malware Detection</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-windows-taskmanager-on-top-techniques/"><u>Mastery Over Windows: TaskManager on Top Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/9-fixes-to-try-when-steam-is-stuck-on-verifying-installation-for-windows/"><u>9 Fixes to Try When Steam Is Stuck on Verifying Installation for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-windows-system-preferences-to-adjust-after-dark-mode/"><u>Mastery of Windows System Preferences to Adjust After Dark Mode</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-reasons-for-preserving-your-win-11-alerts/"><u>Discover the Reasons for Preserving Your Win 11 Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-secrets-to-windows-11-success/"><u>Unlocking the Secrets to Windows 11 Success</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-live-interaction-on-windows-discord-app/"><u>Enhancing Live Interaction on Windows Discord App</u></a></li>
<li><a href="https://win11.techidaily.com/is-the-outlook-app-not-syncing-on-windows-heres-how-to-fix-it/"><u>Is the Outlook App Not Syncing on Windows? Here’s How to Fix It</u></a></li>
<li><a href="https://win11.techidaily.com/key-techniques-for-win10-blue-screen-resolution/"><u>Key Techniques for Win10 Blue Screen Resolution</u></a></li>
<li><a href="https://apple-account.techidaily.com/3-ways-of-how-to-get-someones-apple-id-off-iphone-xs-without-password-by-drfone-ios/"><u>3 Ways of How to Get Someones Apple ID Off iPhone XS without Password</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-optimal-free-cam-viewer-with-snatch-feature/"><u>[Updated] In 2024, Optimal Free Cam Viewer with Snatch Feature</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-full-tutorial-to-bypass-your-realme-narzo-60-pro-5g-face-lock-by-drfone-android/"><u>In 2024, Full Tutorial to Bypass Your Realme Narzo 60 Pro 5G Face Lock?</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-online-video-editing-essentials-download-edit-and-publish-like-a-pro/"><u>New In 2024, Online Video Editing Essentials Download, Edit, and Publish Like a Pro</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/7-best-apps-to-go-live-on-youtube-from-iphone-or-android-for-2024/"><u>7 Best Apps to Go Live on YouTube From iPhone or Android for 2024</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/2024-approved-10-best-free-websites-to-watch-cartoons-online/"><u>2024 Approved 10 Best Free Websites to Watch Cartoons Online</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-simplify-your-workflow-incorporating-luts-into-pscc-projects/"><u>2024 Approved  Simplify Your Workflow  Incorporating LUTs Into PSCC Projects</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/free-electronic-signatures-for-word-2013-by-ldigisigner-sign-a-word-sign-a-word/"><u>Free electronic signatures for Word 2013</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-the-finest-5-mp3-fusion-applications-to-enhance-your-macs-sound-quality/"><u>In 2024, The Finest 5 MP3 Fusion Applications to Enhance Your Macs Sound Quality</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-altering-playback-speed-in-songs-while-maintaining-musical-tuning-and-harmony/"><u>New 2024 Approved Altering Playback Speed in Songs While Maintaining Musical Tuning and Harmony</u></a></li>
</ul></div>
