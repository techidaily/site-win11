---
title: "Breath of Fresh Air: Reviving Outdated Microsoft Store Apps"
date: 2024-06-25T11:27:24.232Z
updated: 2024-06-26T11:27:24.232Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Breath of Fresh Air: Reviving Outdated Microsoft Store Apps"
excerpt: "This Article Describes Breath of Fresh Air: Reviving Outdated Microsoft Store Apps"
keywords: Fresh Store Updates,Old MS App Renewal,Modernize MS Store,Refresh App Lifecycle,Update Microsoft Suite,Redesign MS Apps,Clean OS App Revamp
thumbnail: https://thmb.techidaily.com/300b8b150f8464b487683b06984fcbd6662b4fb116965638afb915b9861f6dbd.jpg
---

## Breath of Fresh Air: Reviving Outdated Microsoft Store Apps

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

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

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

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
<li><a href="https://win11.techidaily.com/demystifying-processor-limits-in-power-options-menu/"><u>Demystifying Processor Limits in Power Options Menu</u></a></li>
<li><a href="https://win11.techidaily.com/epic-sign-in-solutions-for-non-responsive-launcher/"><u>Epic Sign-In Solutions for Non-Responsive Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-widget-integration-into-windows-11/"><u>Mastering the Art of Widget Integration Into Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resurrecting-hibernation-a-windows-users-guide/"><u>Resurrecting Hibernation: A Windows User's Guide</u></a></li>
<li><a href="https://win11.techidaily.com/avoidance-techniques-to-prevent-disconnect-errors-during-discord-setup/"><u>Avoidance Techniques to Prevent Disconnect Errors During Discord Setup</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-the-mechanics-guaranteeing-a-glitch-free-gaming-experience/"><u>Mastery of the Mechanics: Guaranteeing a Glitch-Free Gaming Experience</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-blue-screen-errors-with-vmware-on-win11/"><u>Strategies to Address Blue Screen Errors with VMware on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-device-recognition-failure-in-windows-installation/"><u>Overcoming Device Recognition Failure in Windows Installation</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-explore-the-finest-6-mobile-applications-for-instantaneous-voice-change/"><u>New 2024 Approved Explore the Finest 6 Mobile Applications for Instantaneous Voice Change</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-honor-90-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Honor 90 to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/ps5xbox-series-x-top-gaming-tvs-unveiled/"><u>PS5/Xbox Series X  Top Gaming TVs Unveiled</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-vidgrabmaster-mobilepc-app-downloads/"><u>In 2024, VidGrabMaster  Mobile/PC App Downloads</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-integrating-youtube-into-tv-sets-with-loop-features/"><u>In 2024, Integrating YouTube Into TV Sets with Loop Features</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/apples-role-in-simplifying-educational-audio-archives/"><u>Apple's Role in Simplifying Educational Audio Archives</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-screenflow-simplified-streamlining-your-video-projects-on-a-mac-for-2024/"><u>[Updated] ScreenFlow Simplified  Streamlining Your Video Projects on a Mac for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-realme-10t-5g-to-pc-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Realme 10T 5G to PC? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-ultimate-guide-to-samsung-galaxy-a05-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>The Ultimate Guide to Samsung Galaxy A05 Pattern Lock Screen Everything You Need to Know</u></a></li>
</ul></div>
