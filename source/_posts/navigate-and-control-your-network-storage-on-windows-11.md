---
title: Navigate and Control Your Network Storage on Windows 11
date: 2024-08-15T23:33:25.552Z
updated: 2024-08-16T23:33:25.552Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigate and Control Your Network Storage on Windows 11
excerpt: This Article Describes Navigate and Control Your Network Storage on Windows 11
keywords: Win11 Storage Navigation,Windows 11 Storage Management,Network Storage on Windows 11,Manage Windows 11 NAS,Control NFS/SMB Windows 11,11X Windows Storage Guide,SMB/NFS Windows 11 Storage
thumbnail: https://thmb.techidaily.com/e61ec8b8b6fcdc5ae49f80ff7f35fd26c15f5f9f26e0670f639723e26a96ce2a.jpeg
---

## Navigate and Control Your Network Storage on Windows 11

 Mapping a network drive helps you access shared folders and files on a network. It allows you to access such resources as if they were on your local computer, making it easy to work with files stored on a network.

 This can be particularly useful for businesses or organizations with multiple computers or servers that want to share files and resources between them easily.

 But is it really that simple to set up mapping? Keep reading to learn how to map a network drive in Windows 11 using different methods.

## Configure Network Discovery in Windows

 Windows has a feature called [network discovery](https://www.makeuseof.com/windows-network-discovery-turn-on-off/) that allows your computer to discover and access other devices on the same network, such as computers, servers, and printers.

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

 Therefore, it's crucial to ensure that you have a strong password and [customize your default Windows Firewall](https://www.makeuseof.com/windows-firewall-control-guide/) to protect your device in case something goes wrong.

## 1\. Map a Network Drive Using File Explorer

 Once you have turned on network discovery, you can map a network drive in Windows 11 using File Explorer.

Here's what you need to do to use File Explorer for mapping:

1. Press**Win + E** to open File Explorer directly, and click on**This PC** in the left pane.
2. Right-click on**This PC** and select the**Map network drive...** button in the context menu that appears.  
![This PC Context Menu In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/this-pc-context-menu-in-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Choose a unique drive letter in the**Map Network Drive** window. This is the drive you'll use to access the shared folder from your computer. As an example, we've selected**A:** as the drive letter.
4. Enter the path to the shared folder you want to map in the**Folder:** field. This can be a local path on the computer, such as**\\\\YourComputer\\SharedFolder** , or a network path, such as**\\\\ServerName\\SharedFolder** .  
![Windows Shared Network Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-shared-network-folder.jpg)
5. If you need a username and password to access the shared folder, check the**Connect using different credentials** box and enter the required information.
6. Click**Finish** to complete the mapping process.  
![Map Network Drive In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/map-network-drive-in-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->

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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
4. If the shared folder requires a username and password to access, you can add the -Credential parameter to the command, followed by a username and password in the format username and password. For example:  
New-PSDrive -Name X -PSProvider FileSystem -Root \\ServerName\SharedFolder -Credential username password
5. Hit**Enter** to allow PowerShell to map the network drive. You can access the mapped drive from File Explorer now.

 Besides mapping, you can do a wide range of things, like managing and automating tasks on Windows. For that, you must know some [useful PowerShell commands](https://www.makeuseof.com/windows-powershell-commands-cmdlets/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
## 3\. Use Command Prompt for Mapping

 Just like you used PowerShell earlier, you can use the Windows Command Prompt tool to map a network drive.

So, follow these simple instructions:

1. Open [Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
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
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. In the next window, choose the drive letter or name of the network drive you want to disconnect. Click**OK** to disconnect it from your system.

 The mapped network drive will now disappear from File Explorer, and you can no longer access it from the drive letter you created earlier.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://youtube-data.techidaily.com/0-best-intro-maker-apps-for-iphone-and-android-for-2024/"><u>[New] 10 Best Intro Maker Apps for iPhone and Android for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-conquer-social-media-with-savvy-fb-video-choices/"><u>[New] 2024 Approved  Conquer Social Media with Savvy FB Video Choices</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-journey-through-ingenious-text-animation-ideas/"><u>[New] 2024 Approved  Journey Through Ingenious Text Animation Ideas</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-gaining-momentum-how-igtv-hashtags-drive-fan-base-expansion/"><u>[Updated] 2024 Approved  Gaining Momentum  How IGTV Hashtags Drive Fan Base Expansion</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-a-guide-to-high-quality-slow-motion-images-for-instagram-sharing/"><u>[Updated] A Guide to High-Quality Slow Motion Images for Instagram Sharing</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-how-to-edit-youtube-videos-in-sony-vegas-for-2024/"><u>[Updated] How to Edit YouTube Videos in Sony Vegas for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-instructional-guide-modify-comment-accessibility-on-youtube/"><u>[Updated] Instructional Guide  Modify Comment Accessibility on YouTube</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-boosting-video-engagement-using-zooms-snap-feature/"><u>2024 Approved  Boosting Video Engagement Using Zoom's Snap Feature</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-enhance-your-videography-youtube-studio-edition-techniques/"><u>2024 Approved  Enhance Your Videography  YouTube Studio Edition Techniques</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-top-techniques-for-capturing-ps3-gaming-moments/"><u>2024 Approved  Top Techniques for Capturing PS3 Gaming Moments</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unparalleled-hands-on-gear-in-the-vr-world/"><u>2024 Approved  Unparalleled Hands-On Gear in the VR World</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-repeated-sign-in-alerts-team-collaboration-edition/"><u>Avoiding Repeated Sign-In Alerts: Team Collaboration Edition</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/best-practices-for-screen-recording-phones/"><u>Best Practices for Screen Recording Phones</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/beyond-the-myths-authentic-strategies-for-language-acquisition/"><u>Beyond the Myths: Authentic Strategies for Language Acquisition</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-dual-users-conflict-with-one-ms-login/"><u>Bypassing Dual Users’ Conflict with One MS Login</u></a></li>
<li><a href="https://win11.techidaily.com/correction-of-errors-in-organization-managed-windows-11-settings/"><u>Correction of Errors in Organization-Managed Windows 11 Settings</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-managing-setup-host-cpu-use/"><u>Efficiently Managing Setup Host CPU Use</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-your-winning-streak-with-fps-techniques/"><u>Elevating Your Winning Streak with FPS Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/enthrall-homes-embrace-the-spirit-of-yuletide/"><u>Enthrall Homes, Embrace the Spirit of Yuletide</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/exclusive-offers-on-electronics-during-the-2024-amazon-prime-day-event/"><u>Exclusive Offers on Electronics During the 2024 Amazon Prime Day Event</u></a></li>
<li><a href="https://win11.techidaily.com/fix-the-gap-how-to-locate-and-utilize-hidden-windows-11-enhancements/"><u>Fix the Gap: How to Locate & Utilize Hidden Windows 11 Enhancements</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-faulty-windows-keys-in-a-minute/"><u>Fixing Faulty Windows Keys in a Minute!</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-no-signs-on-screen-when-booting-windows/"><u>Fixing No Signs on Screen When Booting Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-address-non-starting-issues-with-obs-on-pc/"><u>How to Address Non-Starting Issues with OBS on PC</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-pictures-from-a18-by-fonelab-android-recover-pictures/"><u>How to recover deleted pictures from A18.</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-screen-lock-pin-on-nubia-red-magic-9-pro-like-a-pro-5-easy-ways-by-drfone-android/"><u>How To Remove Screen Lock PIN On Nubia Red Magic 9 Pro Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-poco-m6-5g-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Poco M6 5G online without jailbreak</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-maximize-storage-essential-xbox-drive-picks-reviewed/"><u>In 2024, Maximize Storage  Essential Xbox Drive Picks Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/instituting-a-new-pdf-reader-standard-on-os/"><u>Instituting a New PDF Reader Standard on OS</u></a></li>
<li><a href="https://tech-revival.techidaily.com/is-chatgpt-secure-for-everyday-use-a-comprehensive-look/"><u>Is ChatGPT Secure for Everyday Use: A Comprehensive Look</u></a></li>
<li><a href="https://win11.techidaily.com/master-keyboard-flair-with-typingaid-techniques/"><u>Master Keyboard Flair with TypingAid Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-transfer-in-google-chrome-now-easier-on-windows/"><u>Mastering File Transfer in Google Chrome, Now Easier on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-invisible-images-with-encrypted-zips-win/"><u>Mastering the Art of Invisible Images with Encrypted Zips (WIN)</u></a></li>
<li><a href="https://extra-support.techidaily.com/mobility-boosted-video-stability-device-for-2024/"><u>Mobility Boosted Video Stability Device for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-and-altering-windows-registry-using-cli/"><u>Navigating and Altering Windows Registry Using CLI</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-streaming-on-windows-counteracting-zero-speed-phenomenon/"><u>Optimize Streaming on Windows: Counteracting Zero-Speed Phenomenon</u></a></li>
<li><a href="https://win11.techidaily.com/prime-virtually-powered-platforms-for-windows-11-users/"><u>Prime Virtually-Powered Platforms for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-disconnect-error-for-malwarebytes-services-in-windows-11/"><u>Remedying Disconnect Error for Malwarebytes Services in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-media-player-server-crashes/"><u>Remedying Media Player Server Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-your-windows-backup-preferences/"><u>Resetting Your Windows Backup Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-access-post-error-code-22-fixing-a-locked-down-pc-in-windows-11/"><u>Restoring Access Post-Error Code 22: Fixing a Locked Down PC in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-seamless-link-for-windows-steam-streaming/"><u>Restoring Seamless Link for Windows Steam Streaming</u></a></li>
<li><a href="https://win11.techidaily.com/say-goodbye-to-clutter-windows-generative-erasure/"><u>Say Goodbye to Clutter: Windows' Generative Erasure</u></a></li>
<li><a href="https://win-answers.techidaily.com/solutions-for-restoring-windows-spotlight-display-errors-in-windows-11/"><u>Solutions for Restoring Windows Spotlight Display Errors in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/sound-superchargers-4-applications-boosting-windows-audio-capacity/"><u>Sound Superchargers: 4 Applications Boosting Windows' Audio Capacity</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-day-wins-best-time-management-solutions/"><u>Streamline Your Day: Win's Best Time Management Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/stutter-no-more-essential-9-tips-to-ensure-fluid-video-on-pcs/"><u>Stutter No More: Essential 9 Tips to Ensure Fluid Video on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-enabling-additional-av-software-on-windows/"><u>Techniques for Enabling Additional AV Software on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/top-tips-for-effective-app-packages-control-using-winget-on-win11/"><u>Top Tips for Effective App Packages Control Using Winget on Win11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-windows-11-error-0x8024401c-during-updates/"><u>Troubleshooting Steps for Windows 11 Error 0X8024401c During Updates</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unsuccessful-message-loads-on-discord-pc/"><u>Troubleshooting Unsuccessful Message Loads on Discord PC</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-secure-windows-server-settings/"><u>Unlocking Secure Windows Server Settings</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-honor-magic-v2-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Honor Magic V2? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/win11-and-dxgidll-quick-fixes-for-the-missing-file/"><u>Win11 & Dxgi.dll: Quick Fixes for the Missing File</u></a></li>
</ul></div>
