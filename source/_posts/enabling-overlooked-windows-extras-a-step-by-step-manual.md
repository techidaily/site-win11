---
title: "Enabling Overlooked Windows Extras: A Step-by-Step Manual"
date: 2024-08-16T00:00:23.628Z
updated: 2024-08-17T00:00:23.628Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Enabling Overlooked Windows Extras: A Step-by-Step Manual"
excerpt: "This Article Describes Enabling Overlooked Windows Extras: A Step-by-Step Manual"
keywords: Windows Extra Access,Enable Window Tools,Overlooked Windows Guide,Steps to Extras Functions,Extra Features in WinXP,Mastering XP Extras,XP Unseen Utilities Tutorial
thumbnail: https://thmb.techidaily.com/3c096ca7006d9a28f3f7e555f29e64435eb73c0052911cf681dfac2286fbe4f4.jpg
---

## Enabling Overlooked Windows Extras: A Step-by-Step Manual

 Optional features are those that you can add to get more functionality or support for certain file formats. For example, you can install different font packs or old Windows utilities like Paint and WordPad.

 If you're having trouble installing optional features, you're not alone. Sometimes optional features may fail to install due to corrupt system files, an outdated Windows version, or incorrect configuration settings.

 Fortunately, there are several ways to fix this problem and get the optional features running again. So, how can you fix the optional features not installing issue?

## 1\. Use the DISM Tool

 One of the first things you can try is using the Deployment Image Servicing and Management (DISM) tool. This tool is part of Windows, and you can use it to fix corrupt system files, including ones that could be causing problems when installing optional features.

To use the DISM tool, follow these steps:

1. Press**Win + Q** to bring up the Windows search dialogue box.
2. Type**cmd** and click**Run as administrator** to open the Command Prompt.
3. Type**dism /online /cleanup-image /restorehealth** and press**Enter** .  
![DISM Windows Utility Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/dism-windows-utility.jpg)

 This will start the DISM tool and begin scanning your system for any corrupt or missing files. If it finds any issues with your computer, it will automatically repair them.

 Once the process is complete, you can restart your computer and try installing the optional feature again. If DISM does not work or throws an error code, make sure to go through the [DISM not working fixes](https://www.makeuseof.com/windows-11-dism-error-2-fix/) .

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Run the System File Checker or SFC Utility

 Another tool you can use to fix issues with optional feature installation is the System File Checker (SFC) utility.

 SFC is a command-line utility on Windows, which means you can use it from the Command Prompt itself. It is a useful tool for troubleshooting and repairing problems with the system files on your computer, similar to the DISM tool.

To check your system using SFC, follow these steps:

1. Open the Command Prompt with administrative rights using any of the [ways to open CMD as an admin on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. Type**sfc /scannow** and press**Enter** .  
![SFC Utility In Windows Overview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-utility-in-windows.jpg)
3. Once SFC scans for errors, make sure to restart your computer.

Want to know the best part?

 The best part is that the System File Checker not only helps you fix the optional features problem but also any other Windows issues. In fact, it's one of the best [ways to repair corrupted Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/) .

## 3\. Reset the Windows Update Components

 Windows Update Components include all the services, tasks, and programs that work together to make sure your Windows system is up-to-date and secure.

 Resetting the Windows Update components might help solve the issue with optional feature installation. Here's how you can reset the Windows Update components easily:

1. Open the Command Prompt utility as an administrator.
2. Type the following commands one after the other, pressing**Enter** after each one:

`net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver  
ren C:\Windows\SoftwareDistribution SoftwareDistribution.old  
ren C:\Windows\System32\catroot2 catroot2.old  
net start wuauserv  
net start cryptSvc  
net start bits  
net start msiserver`

 This command will stop the Windows Update services, rename the**SoftwareDistribution** and**catroot2** folders, and then restart the services. This can help reset the update process and fix any issues that might be causing problems with optional feature installation.

![Update Components Reset In CMD Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/update-components-reset-in-cmd.jpg)
<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 While the commands may look intimidating, you don't need to worry, as all the commands mentioned above will not cause any harm to your system.​​​​

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Run the Windows Update Troubleshooter

 If the Command Prompt method did not work for you, you can use the Windows Update Troubleshooter to reset update components. This tool can help identify and fix problems with the update process, including issues that might be preventing optional features from installing.

Follow these steps to run the update troubleshooter on Windows:

1. Press**Win + I** to launch the Settings app.
2. Scroll down and click**Troubleshoot > Other troubleshooters.**  
![Troubleshooter Settings In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/troubleshooter-settings-in-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
3. Click**Run** next to**Windows Update** to run the troubleshooter.  
![Other Troubleshooters In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/other-troubleshooters-in-windows.jpg)
4. Follow the prompts to complete the troubleshooting process.

 If you're using Windows 10, the Windows Update Troubleshooter is in**Settings > Update & Security >** **Troubleshoot > Windows Update** .

 The troubleshooter will begin scanning your system for any issues with the update process and will offer suggestions for how to fix them. So, you just need to follow the prompts, and then try [installing the optional features](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) again.

## 5\. Update Windows to the Latest Version

 If the issue with optional feature installation is related to outdated system files, you may be able to fix it by updating Windows to the latest version.

 Updating Windows can help ensure that you have the latest security patches, bug fixes, and system files, which can help resolve any issues you may be experiencing.

Here's how you can update Windows to the latest version:

1. Press**Win + I** to open the Settings app.
2. Click on**Windows** **Update > Check for updates** on Windows 11\. For Windows 10, click on **Update & Security > Windows Update > Check for Updates** .  
![Windows Update In Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-update-in-windows-11.jpg)

 That's it. Now, you can install any update that is available for your computer.

 By default, Windows automatically downloads and installs updates, but you can also check for updates manually by following the steps above.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Restart the Windows Module Installer Service

 The Windows Module Installer service allows you to install, change, and remove Windows features and optional components. If it is not working properly, it can make it difficult to install optional features.

 Follow the below-given steps to restart the Windows Module Installer service:

1. Open Windows search and type**services** .
2. Select the best match to open the**Services** app.
3. Scroll down and find the**Windows Module Installer** service.
4. Right-click on the service and select**Restart** .  
![Windows Modules Installer Service In Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-modules-installer-service.jpg)

 When you reset the module installer service, Windows tries to stop it and then start it again, which can help reset the installation process of optional features and fix any issues that might be causing problems.

 Once the service restarts, try installing the optional feature again, and it should work now.

## 7\. Restore Windows Features Using PowerShell

 If all the above methods fail to work, restoring Windows features is your last resort. So, if you are unable to use or install an optional Windows feature, you might be able to fix the problem by using PowerShell to restore a particular feature.

 Here are the steps for restoring Windows features using the PowerShell:

1. Press**Win + X** to open the Power User menu.
2. Click on**Windows PowerShell (Admin)** or**Terminal (Admin)** .
3. Type the following command and press**Enter** :  
Get-WindowsOptionalFeature -Online  
![Get Optional Feature Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/get-optional-feature-command.jpg)  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 This command will show you the**FeatureName** and**State** of every optional Windows feature that you can use. Make sure to copy the "**FeatureName** " of the feature that you want to enable on Windows.
4. To turn on a certain feature, use the following command and replace "**FEATURENAME** " with the feature's name that you copied earlier:  
Enable-WindowsOptionalFeature -Online -FeatureName FEATURENAME  
![Enable Optional Feature Command In PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/optional-feature-in-powershell.jpg)
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Restart your computer for the changes to take effect.

 This will add the feature back to your system and should make it available for you to enable or disable in the features window.

 This method only allows you to restore a specific feature and, not all the features at once. So, you need to copy and paste the same command and edit the**FEATURENAME** every time.

 If these steps don't fix the problem, you may need to ask Microsoft or a technical support professional for more help.

## Get Back the Windows Optional Features

 Hopefully, the issue with optional features not installing on your system should be fixed now. In any case, it is important to keep your system up-to-date and to follow best practices for maintaining your computer properly to help prevent issues like this from occurring.


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
<li><a href="https://article-tips.techidaily.com/new-2024-approved-magix-acid-pros-successors-in-vector-editing/"><u>[New] 2024 Approved  Magix ACID Pro's Successors in Vector Editing</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-innovative-tactics-for-stellar-facebook-ad-videos/"><u>[New] Innovative Tactics for Stellar Facebook Ad Videos</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-step-by-step-tutorial-to-create-engaging-valorant-videos-with-thumbnails/"><u>[New] Step-by-Step Tutorial to Create Engaging Valorant Videos with Thumbnails</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/treamline-your-youtube-experience-shareable-playlists/"><u>[New] Streamline Your YouTube Experience  Shareable Playlists</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-video-amounts-stored-64-vs-128gb-comparison/"><u>[New] Video Amounts Stored  64 vs 128GB Comparison</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-crafting-impressive-instagram-reels-quickly/"><u>[Updated] In 2024, Crafting Impressive Instagram Reels Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-make-windows-11-start-up-faster/"><u>3 Ways to Make Windows 11 Start Up Faster</u></a></li>
<li><a href="https://win11.techidaily.com/4-keys-to-reviving-a-device-stuck-in-night-setting/"><u>4 Keys to Reviving a Device Stuck in Night Setting</u></a></li>
<li><a href="https://win11.techidaily.com/5-immediate-actions-reviving-disabled-windows-defender-protection/"><u>5 Immediate Actions: Reviving Disabled Windows Defender Protection</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-lava-blaze-curve-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Lava Blaze Curve 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/7-strong-arguments-against-switching-from-win10-to-win11-immediately/"><u>7 Strong Arguments Against Switching From Win10 to Win11 Immediately</u></a></li>
<li><a href="https://win11.techidaily.com/a-complete-unveiling-affordable-windows-10-mastery/"><u>A Complete Unveiling: Affordable Windows 10 Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-clearing-defender-history-on-windows-pcs/"><u>A Comprehensive Guide to Clearing Defender History on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-policy-settings-with-windows-11-expertise/"><u>Accelerate Policy Settings with Windows 11 Expertise</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-sluggish-windows-based-excel-processes/"><u>Accelerate Sluggish Windows-Based Excel Processes</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-driver-verifier-manager-w11-edition/"><u>Accessing Driver Verifier Manager W11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-errors-when-transferring-images-from-iphone-to-pc/"><u>Addressing Errors When Transferring Images From iPhone to PC</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-cannot-locate-gpeditmsc-error-in-windows/"><u>Addressing the Cannot Locate Gpedit.msc Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-onedrives-incorrect-tag-issue/"><u>Addressing Windows Error: OneDrive’s Incorrect Tag Issue</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-photo-preview-sizes-on-windows-11/"><u>Adjusting Photo Preview Sizes on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/amd-graphics-update-essentials-for-windows-11-users/"><u>AMD Graphics Update Essentials for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-missed-messages-solutions-to-windows-mail-alert-issues/"><u>Avoiding Missed Messages: Solutions to Windows Mail Alert Issues</u></a></li>
<li><a href="https://win11.techidaily.com/breached-bytebandit-ponder-the-path-for-a-possible-pivot/"><u>Breached ByteBandit: Ponder the Path for a Possible Pivot</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/forgot-iphone-passcode-again-unlock-apple-iphone-15-without-passcode-now-by-drfone-ios/"><u>Forgot iPhone Passcode Again? Unlock Apple iPhone 15 Without Passcode Now</u></a></li>
<li><a href="https://win11.techidaily.com/1719218317457-gpt4all-windows-guide-to-free-on-premise-chatbots/"><u>GPT4All Windows Guide to Free, On-Premise ChatBots.</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-honor-90-lite-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the Honor 90 Lite Screen Black But Still Works? | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-15-melodic-matchmakers-tailoring-audio-to-each-videos-characteristic-mood/"><u>In 2024, 15 Melodic Matchmakers Tailoring Audio to Each Videos Characteristic Mood</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-samsung-galaxy-s23-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Pokémon Emerald Master Ball Cheat On Samsung Galaxy S23 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719271169588-reclaim-your-browser-quick-fixes-to-unlock-chrome-on-win11/"><u>Reclaim Your Browser: Quick Fixes to Unlock Chrome on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/1719375739489-relaunch-google-chrome-on-win11-fixes-and-tips-here/"><u>Relaunch Google Chrome on Win11 – Fixes and Tips Here.</u></a></li>
<li><a href="https://apple-account.techidaily.com/top-notch-solutions-for-disabled-apple-id-from-iphone-15-pro-making-it-possible-by-drfone-ios/"><u>Top-Notch Solutions for Disabled Apple ID From iPhone 15 Pro Making It Possible</u></a></li>
<li><a href="https://win11.techidaily.com/1719328494393-uninstalling-epic-launcher-on-w11-solutions-present/"><u>Uninstalling Epic Launcher on W11 - Solutions Present!</u></a></li>
</ul></div>
