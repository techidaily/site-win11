---
title: Resetting Microsoft Store on Windows 11 & 11
date: 2024-11-16T23:23:40.391Z
updated: 2024-11-17T21:49:14.813Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resetting Microsoft Store on Windows 11 & 11
excerpt: This Article Describes Resetting Microsoft Store on Windows 11 & 11
keywords: Reset MS Store Windows 11,Win11 Microsoft Store Fix,Windows 11 Store Reset,MSVRestore Windows 11,Reinstall Windows Store,Cleanup Windows 11 Store,Restore Buy Now Button
thumbnail: https://thmb.techidaily.com/08f2c817ace11f52f69518bb589ba81c382ee3c50cca52847005eac86a562eee.jpg
---

## Resetting Microsoft Store on Windows 11 & 11

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the[Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134227/18498" target="_top" id="2134227">
  <img src="//a.impactradius-go.com/display-ad/18498-2134227" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134227/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526">
  <img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027195/19272" target="_top" id="2027195">
  <img src="//a.impactradius-go.com/display-ad/19272-2027195" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027195/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.

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
<li><a href="https://youtube-blog.techidaily.com/n-2024-unleashing-potential-strategic-hashtags-for-video-success/"><u>[New] In 2024, Unleashing Potential Strategic Hashtags for Video Success</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-mental-marathon-best-trivia-videos-online/"><u>[Updated] Mental Marathon Best Trivia Videos Online</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-xiaomi-redmi-a2-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Xiaomi Redmi A2 to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/best-screen-reporter-toolkit-for-youtube-streamers-for-2024/"><u>Best Screen Reporter Toolkit for YouTube Streamers for 2024</u></a></li>
<li><a href="https://discover-docs.techidaily.com/convertir-imagenes-tiff-y-jpg-sin-costo-guia-simple/"><u>Convertir Imágenes TIFF Y JPG Sin Costo: Guía Simple</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-problem-with-this-windows-installer-package-error-on-windows-11-and-11/"><u>How to Fix the Problem With This Windows Installer Package Error on Windows 11 & 11</u></a></li>
<li><a href="https://common-error.techidaily.com/improve-your-workflow-advanced-file-explorer-techniques-for-windows-11-users/"><u>Improve Your Workflow: Advanced File Explorer Techniques for Windows 11 Users</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-apple-iphone-8-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, Additional Tips About Sinnoh Stone For Apple iPhone 8 Plus | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/musks-breakdown-understanding-the-function-and-financial-aspects-of-grok-ai/"><u>Musk's Breakdown: Understanding the Function and Financial Aspects of Grok AI</u></a></li>
<li><a href="https://win11.techidaily.com/revival-strategies-for-net-on-your-pc-max-156/"><u>Revival Strategies for .NET on Your PC (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/scheme-for-activatingdeactivating-setup-service-on-pcs/"><u>Scheme for Activating/Deactivating Setup Service on PCs</u></a></li>
<li><a href="https://win-guides.techidaily.com/schritt-fur-schritt-tutorial-einen-bootfahigen-windows-11-usb-von-grund-auf-erzeugen/"><u>Schritt-Für-Schritt-Tutorial: Einen Bootfähigen Windows 11 USB Von Grund Auf Erzeugen</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-typography-across-languages-on-windows-pcs/"><u>Seamless Typography Across Languages on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-stop-microsoft-teams-crashes-tips-for-wins-11-and-10/"><u>Steps to Stop Microsoft Teams Crashes: Tips for Wins 11 & 10</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-troubleshooting-task-sequence-failures-winos-edition/"><u>Strategies for Troubleshooting Task Sequence Failures: WinOS Edition</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-mysteries-of-windows-group-policies-3-different-perspectives/"><u>Unlocking the Mysteries of Windows Group Policies: 3 Different Perspectives</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-unleash-your-creativity-best-reaction-video-maker-tools-for-2024/"><u>Updated Unleash Your Creativity Best Reaction Video Maker Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-when-youre-unable-to-download-any-files-on-a-windows-10-and-11/"><u>What to Do When You’re Unable to Download Any Files on a Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/winning-strategy-against-update-error-x712/"><u>Winning Strategy Against Update Error X712</u></a></li>
</ul></div>

