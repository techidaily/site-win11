---
title: Unlocking MS Store Programs on Windows 11 with Ease
date: 2024-10-24T23:01:33.793Z
updated: 2024-10-26T16:56:47.993Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking MS Store Programs on Windows 11 with Ease
excerpt: This Article Describes Unlocking MS Store Programs on Windows 11 with Ease
keywords: Windows 11 Unlock Features,Access MS Store Easily,Enhance Win 11 Experience,Simplify Store Programs,Secure Win 11 Content,Unveil Win 11 Apps Quickly,Streamline Win 11 Updates
thumbnail: https://thmb.techidaily.com/f66305bee95e2c8cfda71737bc488d60f6c275330b2e729ec458216f465e024e.png
---

## Unlocking MS Store Programs on Windows 11 with Ease

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
<a href="https://appsumo.8odi.net/c/5597632/2049363/7443" target="_top" id="2049363">
  <img src="//a.impactradius-go.com/display-ad/7443-2049363" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049363/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105876/7443" target="_top" id="2105876">
  <img src="//a.impactradius-go.com/display-ad/7443-2105876" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105876/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118306/7443" target="_top" id="2118306">
  <img src="//a.impactradius-go.com/display-ad/7443-2118306" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118306/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-next-gen-webcams-a-deep-dive-into-live-videography-gear/"><u>[New] In 2024, Next-Gen WebCams A Deep Dive Into Live Videography Gear</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-unlock-the-full-potential-of-video-content-with-studios-power/"><u>[New] In 2024, Unlock the Full Potential of Video Content with Studio's Power</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-picture-puns-smilesketchers-for-2024/"><u>[New] Picture Puns SmileSketchers for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-ultimate-list-of-8-youtube-mistakes-to-evade/"><u>[New] The Ultimate List of 8 Youtube Mistakes to Evade</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-insights-into-a-common-icon-what-is-fbs-blue-video-symbol/"><u>[Updated] Insights Into a Common Icon What Is FB’s Blue Video Symbol?</u></a></li>
<li><a href="https://blog-min.techidaily.com/1726224589395-ai-12/"><u>AI 얼굴 만들기를 위한 12가지 획기적인 프로그램 선보기</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-windows-11s-backbone-the-registry-explained/"><u>Exploring Windows 11'S Backbone: The Registry Explained</u></a></li>
<li><a href="https://discover-comparisons.techidaily.com/in-depth-comparison-how-does-veeam-stack-up-against-cohesity/"><u>In-Depth Comparison: How Does Veeam Stack Up Against Cohesity?</u></a></li>
<li><a href="https://win11.techidaily.com/installment-challenge-overcoming-mspm-errors/"><u>Installment Challenge: Overcoming MSPM Errors</u></a></li>
<li><a href="https://win11.techidaily.com/saving-success-fixing-volume-mixer-glitches/"><u>Saving Success: Fixing Volume Mixer Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/security-spotlight-top-7-windows-procedures-vigilant-against-viruses/"><u>Security Spotlight: Top 7 Windows Procedures Vigilant Against Viruses</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-device-not-initialized-error-in-win-11/"><u>Troubleshooting 'Device Not Initialized' Error in Win 11</u></a></li>
</ul></div>

