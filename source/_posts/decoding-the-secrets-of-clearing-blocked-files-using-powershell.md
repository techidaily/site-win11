---
title: Decoding the Secrets of Clearing Blocked Files Using PowerShell
date: 2024-10-12T20:50:43.892Z
updated: 2024-10-15T18:31:30.014Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Decoding the Secrets of Clearing Blocked Files Using PowerShell
excerpt: This Article Describes Decoding the Secrets of Clearing Blocked Files Using PowerShell
keywords: PowerShell File Unblock,Clear Blocked Files PS,Unblock Files PSScripts,Decrypt Blocked Data Powershell,Remove Hidden Executables PS,PowerShell Cleanup Tools,Unhide Files Using Powershell
thumbnail: https://thmb.techidaily.com/799a97879dd8a90baa6e969f4bb05fcde15523a2765ac1b15d1b78fad2268973.jpg
---

## Decoding the Secrets of Clearing Blocked Files Using PowerShell

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  
![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

<!-- affiliate ads begin -->
<span id="1983575">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983575.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983575">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983575.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983575%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983575/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Now You Know How to Unblock Files You Know Are Safe

 With the instruction above unlocking a bunch of downloaded files in a directory should be easier. Keep in mind that you shouldn’t do this on files you don’t trust. The last thing you want to do is put your Windows PC at risk unnecessarily

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-essential-guide-to-documenting-macs-roblox-playthroughs/"><u>[New] Essential Guide to Documenting Mac's Roblox Playthroughs</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-a-strategic-plan-for-top-tier-advertising-results/"><u>2024 Approved A Strategic Plan for Top-Tier Advertising Results</u></a></li>
<li><a href="https://tech-revival.techidaily.com/comparing-ai-models-understanding-gpt-4-gpt-nturbo-and-gpt-phi-variants/"><u>Comparing AI Models: Understanding GPT-4, GPT-nTurbo & GPT-Phi Variants</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-down-unnecessary-workload-in-windows-system/"><u>Cutting Down Unnecessary Workload in Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/direct-steps-to-activatedisable-wifi-cost-metering-in-win11/"><u>Direct Steps to Activate/Disable Wifi Cost Metering in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-all-chromium-notifications-in-windows-pc/"><u>Disabling All Chromium Notifications in Windows PC</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-vivo-v30-pro-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-ideal-no-cost-screen-grabber-toolset/"><u>In 2024, Ideal No-Cost Screen Grabber Toolset</u></a></li>
<li><a href="https://techtrends.techidaily.com/navigating-the-digital-age-laptops-smartphones-and-literary-treasures-galore/"><u>Navigating the Digital Age: Laptops, Smartphones & Literary Treasures Galore!</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-workspace-viewing-switch-wmdesk-way/"><u>Optimize Workspace Viewing: Switch WmDesk Way</u></a></li>
<li><a href="https://win11.techidaily.com/proficient-techniques-for-managing-win-registry-from-cmd/"><u>Proficient Techniques for Managing Win Registry From CMD</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/steps-to-resolve-issues-with-apples-ios-email-functionality-on-iphones/"><u>Steps to Resolve Issues with Apple's iOS Email Functionality on iPhones</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/unveiling-todays-hot-gems-a-guide-to-facebooks-favorites-for-2024/"><u>Unveiling Today’s Hot Gems A Guide to Facebook's Favorites for 2024</u></a></li>
</ul></div>

