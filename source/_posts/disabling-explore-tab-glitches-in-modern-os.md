---
title: Disabling Explore Tab Glitches in Modern OS
date: 2024-07-29T15:47:45.238Z
updated: 2024-07-30T15:47:45.238Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Explore Tab Glitches in Modern OS
excerpt: This Article Describes Disabling Explore Tab Glitches in Modern OS
keywords: Fix Explore Tab Issue,Disable OS Glitches,Resolve Modern OS Bug,Stop OS Explorer Errors,Eliminate OS Navigation Flaws,End Glitch in OS Search,Counteract OS Explorer Crash
thumbnail: https://thmb.techidaily.com/6eaf9b365a6361451b5795d958332fe971bf3b2af37ac8e9e5c055811b75ea47.jpg
---

## Disabling Explore Tab Glitches in Modern OS

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Disable File Explorer Tabs Using the ViVeTool

 Since it is a command line tool, you can access it from a terminal window. Here’s how to do it:

1. Press**Win + R** to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**CMD** in the text input area and press**Ctrl + Shift + Enter** key to launch the command prompt with administrator privileges.
3. Type**cd Drive Name:\\path** . Here, you need to enter the exact location where you extracted the tool after downloading it. For example, we extracted it to a folder name Vive in C drive. So, our command is**cd C:\\Vive** .
4. Now, you will be in the directory where ViVeTool exists. Type**vivetool** and press the**Enter** key. You will see a bunch of parameters you can use with the tool.  
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
![Disable File Explorer Tabs Using the ViVeTool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool.jpg)
5. Type the following two commands, one by one in the CMD and press the**Enter** key.  
vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.
5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Disable Any Windows 11 Feature Using ViVeTool

 File Explorer tabs are more useful than you think. But if you use another File Explorer program or can make do without it, ViVeTool is a great utility to disable/enable it. Moreover, it is completely free, and you can even enable other experimental features of Windows 11.


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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-gamecast-viewers-take/"><u>[New] 2024 Approved  GameCast Viewer's Take</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-the-path-to-autoplay-configuring-youtube-content-for-uninterrupted-streaming/"><u>[New] 2024 Approved  The Path to Autoplay  Configuring Youtube Content for Uninterrupted Streaming</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-master-psd-saturation-tweaks/"><u>[New] Master PSD Saturation Tweaks</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-ultimate-guide-easycapture-v2-analysis/"><u>[Updated] In 2024, Ultimate Guide  EasyCapture V2 Analysis</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-permitted-practices-for-saving-youtube-videos/"><u>[Updated] Permitted Practices for Saving YouTube Videos</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-virtual-playstation-experience-at-your-fingertips-top-5/"><u>2024 Approved  Virtual PlayStation Experience at Your Fingertips (Top 5)</u></a></li>
<li><a href="https://win11.techidaily.com/6-effective-techniques-to-resurrect-off-screen-windows-in-windows-11/"><u>6 Effective Techniques to Resurrect Off-Screen Windows in Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-motorola-moto-g73-5g-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Motorola Moto G73 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-app-install-failure-on-microsofts-marketplace/"><u>Addressing App Install Failure on Microsoft's Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-life-into-stalled-win11-license-numbers/"><u>Breathing Life Into Stalled Win11 License Numbers</u></a></li>
<li><a href="https://win11.techidaily.com/command-prompt-wizardry-admin-skills-unveiled/"><u>Command Prompt Wizardry: Admin Skills Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/end-of-windows-subsystem-preparing-for-androids-future/"><u>End of Windows Subsystem: Preparing For Android's Future</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-correct-invalid-identifier-error-in-win11/"><u>Guide to Correct 'Invalid Identifier' Error in Win11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-google-frp-on-honor-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass Google FRP on Honor</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-repairing-disk-errors-issue-on-windows/"><u>How to Fix the Repairing Disk Errors Issue on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-install-dolby-atmos-in-windows-1111/"><u>How to Install Dolby Atmos in Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reset-and-redo-store-registrations-in-win-11/"><u>How to Reset and Redo Store Registrations in Win 11</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-9-best-phone-monitoring-apps-for-apple-iphone-11-drfone-by-drfone-virtual-ios/"><u>In 2024, 9 Best Phone Monitoring Apps for Apple iPhone 11 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changefake-your-apple-iphone-15-location-on-viber-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change/Fake Your Apple iPhone 15 Location on Viber | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-14-without-passcode-or-face-id-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 14 without Passcode or Face ID</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/innovating-in-the-digital-age-making-stellar-fb-reels-on-youtube/"><u>Innovating in the Digital Age  Making Stellar FB Reels on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-windows-11-harnessing-background-blur-in-photos-app/"><u>Masterful Windows 11: Harnessing Background Blur in Photos App</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-windows-11-registry-file-layout/"><u>Mastering the Windows 11 Registry File Layout</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-savings-with-windows-11-pro-secure-top-deals/"><u>Maximize Savings with Windows 11 Pro: Secure Top Deals</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-intelligence-of-microsofts-marketplace/"><u>Navigating the Intelligence of Microsoft's Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11s-compatibility-checklist-tool/"><u>Navigating Windows 11'S Compatibility Checklist Tool</u></a></li>
<li><a href="https://win11.techidaily.com/paperless-posting-essential-notebook-replacements-for-windows/"><u>Paperless Posting: Essential Notebook Replacements for Windows</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/premier-asian-tongues-leading-three-countries/"><u>Premier Asian Tongues: Leading Three Countries</u></a></li>
<li><a href="https://win11.techidaily.com/quick-route-to-purchase-adobe-reader-in-microsoft-marketplace/"><u>Quick Route to Purchase Adobe Reader in Microsoft Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-functional-shortcuts-cure-errors-in-win-11/"><u>Rectify: Functional Shortcuts - Cure Errors in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/reinstalling-windows-11-step-by-step-guide/"><u>Reinstalling Windows 11: Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/swift-strategies-for-fixing-dism-error-0x800f082f-in-windows/"><u>Swift Strategies for Fixing DISM Error: 0X800F082F in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tech-savvy-collectors-dream-essential-612lifetime-windows-11-deal-awaits/"><u>Tech-Savvy Collectors' Dream: Essential $6.12/Lifetime Windows 11 Deal Awaits</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-merging-your-guide-to-windows-efficiency/"><u>The Art of Merging: Your Guide to Windows Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/tips-and-tricks-for-overcoming-the-msvcr120dll-deficiency-issue/"><u>Tips and Tricks for Overcoming the Msvcr120dll Deficiency Issue</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-user-experience-in-windows-11/"><u>Transforming User Experience in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/triumph-in-windows-pricing-acquiring-top-product-keys/"><u>Triumph in Windows Pricing: Acquiring Top Product Keys</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ultimate-guide-to-get-the-meltan-box-pokemon-go-for-poco-x6-pro-drfone-by-drfone-virtual-android/"><u>Ultimate guide to get the meltan box pokemon go For Poco X6 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unable-to-install-the-microsoft-pc-manager-on-windows-try-these-7-fixes/"><u>Unable to Install the Microsoft PC Manager on Windows? Try These 7 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-troubleshooting-winerror-0x80071a90/"><u>Understanding & Troubleshooting WinError 0X80071A90</u></a></li>
<li><a href="https://win11.techidaily.com/uniting-devices-android-and-windows-with-nearby-share/"><u>Uniting Devices: Android & Windows With Nearby Share</u></a></li>
<li><a href="https://win11.techidaily.com/windows-enthusiasts-how-dxvk-shapes-your-gameplay/"><u>Windows Enthusiasts - How DXVK Shapes Your Gameplay</u></a></li>
</ul></div>
