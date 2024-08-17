---
title: Win11 Terminal Reset Procedure Essentials
date: 2024-08-16T00:41:07.780Z
updated: 2024-08-17T00:41:07.780Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Win11 Terminal Reset Procedure Essentials
excerpt: This Article Describes Win11 Terminal Reset Procedure Essentials
keywords: Win11 Terminal Fix,Terminal Reset Guide,Win11 Terminal Restart,Terminus Windows Reset,Win11 Command Prompt,Terminal Procedure Basics,Win11 CmdReset Essentials
thumbnail: https://thmb.techidaily.com/ddfdfc8e69381106d1b66c2809b663a8f7e41d96d0a4215acf2250fc3083c5a7.jpg
---

## Win11 Terminal Reset Procedure Essentials

 Windows Terminal is the next-generation command line platform in Windows 11\. It provides an improved user experience with modern command line tools that enable you to access multiple command lines in a single window. The tool is essential for developers and administrators alike, but sometimes your terminal settings need to be reset to default.

 In this article, we will explain how to reset your Windows Terminal settings back to their original state.

## Why Would You Reset Your Windows Terminal?

 Windows Terminal is an amazing tool for power users and developers. It allows you to access a variety of tools, all in one place, with custom settings and themes that make it easy to work from anywhere. But over time, your Windows Terminal may become cluttered with old settings or themes that have become redundant or are no longer relevant.

 It also helps clear out any potentially harmful malware or corrupt files that might be lurking in the background of your system, hindering your productivity. By doing so, you will ensure that your computer works as fast and as smoothly as possible - giving you the most optimal experience when using this powerful tool.

 Let's now move to the below sections and see how it can be reset.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Reset Windows Terminal Settings by Clearing JSON Files

 In order to reset the settings back to the original defaults, you will need to delete the settings.json file. Here's how to do it.

1. Right click on Start and select**Terminal** from the menu list.
2. Next, click the down-arrow icon and select**Settings** .
3. From the left pane of the Settings page, click**Open JSON file** .  
![Open JSON file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-json-file.jpg)
4. If you're asked which app to use to open the file, then double-click on**Notepad** .
5. On the next page, select all the contents and**Delete** them.
6. Now press**Ctrl + S** on your keyboard to save it.

 Next time you open the app, a new configuration with all the default settings will be created automatically.

## How to Reset Windows Terminal Settings Using Command Prompt

 The Command Prompt is a command line tool that can help you accomplish a number of tasks on your computer. It lets you run programs, manage files, and even troubleshoot problems with the operating system. We covered a lot of its functionality in our [beginner's guide to the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) , but for now, we'll just explore resetting the Windows Terminal settings.

 To reset Windows Terminal Settings back to their defaults, follow these steps:

1. Open the Command Prompt. For this, use the Taskbar search or type "cmd" in the Run dialog.
2. In the Command Prompt window, copy and paste the following command:  
![Reset Windows Terminal Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-command-prompt.jpg)  
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
del /f /s /q /a "%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json"
3. Now press the**Enter** key to delete the settings.json file.
4. You can now exit the command prompt.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## How to Reset Windows Terminal Settings Using Windows PowerShell

 Windows PowerShell is another command line application that you can use to restore Windows Terminal Settings to their default state. To figure out how, follow these steps:

1. Open Windows PowerShell. You can do this by pressing**Win + R** , typing "PowerShell", and then pressing**Enter** . You can also one of the other [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
2. In the PowerShell window, copy and paste the following command:  
![Reset Windows Terminal Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-powershell.jpg)  
Remove-Item -Path "$env:LOCALAPPDATA\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json" -Force
3. Press**Enter** to execute the command.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## How to Reset Windows Terminal Settings From File Explorer

 If you don't prefer the command line process, you can use Windows File Explorer to reset the settings. In this way, the Terminal will be reset to its default settings, and you can continue using it. Here's how to do it:

1. Open Windows File Explorer. For this, right-click Start and choose**File Explorer** , or press**Win + E** on your keyboard.
2. Copy and paste the following path into the address bar:  
![Reset Windows Terminal Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-file-explorer.jpg)  
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState
3. On the next page, right-click on**settings.json** and select**Delete** from the context menu.

 Once you perform the above steps, Settings.json will automatically be created with the default settings.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Resetting the Windows Terminal, Made Easy

 After reading this post, you now know some useful tips that will help you reset the terminal to default settings in Windows 11\. Try them out and find out which one works best for you.


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
<li><a href="https://extra-approaches.techidaily.com/new-revving-into-excellence-winning-10-srt-converter-titles/"><u>[New] Revving Into Excellence  Winning 10 SRT Converter Titles</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-unraveling-instagrams-policies-on-sharing-songs-for-2024/"><u>[New] Unraveling Instagram's Policies on Sharing Songs for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-10-kid-friendly-drone-recommendations/"><u>[Updated] 10 Kid-Friendly Drone Recommendations</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-unleash-creativity-designing-awe-inspiring-covers-for-instagram-highlights/"><u>[Updated] 2024 Approved  Unleash Creativity  Designing Awe-Inspiring Covers for Instagram Highlights</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-dissecting-apowersoft-an-in-depth-screen-recorder-study-for-2024/"><u>[Updated] Dissecting Apowersoft  An In-Depth Screen Recorder Study for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-master-controls-navigating-the-world-of-switch-pro-and-steam-gaming/"><u>[Updated] Master Controls  Navigating the World of Switch Pro and Steam Gaming</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-pro-photographers-choices-ranking-the-top-6-4k-dslrs/"><u>[Updated] Pro Photographers’ Choices  Ranking the Top 6 4K DSLRs</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-twitter-to-tween-creating-free-animated-videos/"><u>[Updated] Twitter to Tween  Creating FREE Animated Videos</u></a></li>
<li><a href="https://win11.techidaily.com/5-precise-steps-to-rectify-your-screen-res-in-windows/"><u>5 Precise Steps to Rectify Your Screen Res in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-microsoft-should-improve-the-windows-11-taskbar/"><u>6 Ways Microsoft Should Improve the Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-resize-images-in-windows-11/"><u>6 Ways to Resize Images in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-shut-down-windows-11/"><u>9 Ways to Shut Down Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-winning-bittorrent-clients/"><u>A Comprehensive Guide to Winning BitTorrent Clients</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreran-guide-resolving-source-disk-errors-in-microsoft-oses/"><u>A Compreran Guide: Resolving Source Disk Errors in Microsoft OSes</u></a></li>
<li><a href="https://win11.techidaily.com/a-photographers-companion-fixing-your-windows-camera/"><u>A Photographer’s Companion: Fixing Your Window's Camera</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-silencing-of-windows-11-pings/"><u>Accelerated Silencing of Windows 11 Pings</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-and-fixing-the-call-not-invoked-issue-in-malwarebytes/"><u>Addressing and Fixing the Call Not Invoked Issue in Malwarebytes</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-chrome-downloads-disruptions-in-the-windows-os/"><u>Addressing Chrome Downloads Disruptions in the Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-roblox-inaccessibility-via-user-restrictions/"><u>Addressing Windows Error: Roblox Inaccessibility via User Restrictions</u></a></li>
<li><a href="https://win11.techidaily.com/1719376423944-addressing-windows-faults-with-proven-remedies/"><u>Addressing Windows Faults with Proven Remedies</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-wsl-2s-error-4294967295-on-a-win-os/"><u>Addressing WSL 2'S ERROR 4294967295 on a Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-quick-access-for-file-explorer-through-onedrive/"><u>Adjusting Quick Access for File Explorer Through OneDrive</u></a></li>
<li><a href="https://win11.techidaily.com/ais-impact-on-modern-windows-os-innovation/"><u>AI's Impact on Modern Windows OS Innovation</u></a></li>
<li><a href="https://win11.techidaily.com/anonymizing-file-transfer-methods-for-ws11w10-enthusiasts/"><u>Anonymizing File Transfer: Methods for WS11/W10 Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/approaches-for-correcting-err-87-invalid-parameters-on-winos/"><u>Approaches for Correcting Err 87: Invalid Parameters on WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-linux-excellence-through-windows/"><u>Augmenting Linux Excellence Through Windows</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-disruption-bypass-game-glitches-immediately/"><u>Avoid Disruption - Bypass Game Glitches Immediately</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-the-looks-like-youre-stranded-error-from-xbox/"><u>Banishing the ‘Looks Like You’re Stranded’ Error From Xbox</u></a></li>
<li><a href="https://win11.techidaily.com/best-fit-choosing-the-perfect-vms-for-your-windows-11-pc/"><u>Best Fit: Choosing the Perfect VMs for Your Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/black-friday-offer-best-price-keys-fan-unlocked-for-all-year-lifetime-windows-11/"><u>Black Friday Offer: Best Price Keys Fan Unlocked for All-Year Lifetime Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bluescreenview-explained-with-ease-and-clarity/"><u>BlueScreenView Explained with Ease and Clarity</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-activation-error-0x8007251d-fixes-and-tips/"><u>Breaking Down Windows Activation Error 0X8007251D: Fixes and Tips</u></a></li>
<li><a href="https://win-forum.techidaily.com/easy-steps-to-determine-your-windows-10s-powershell-compatibility-and-version/"><u>Easy Steps to Determine Your Windows 10'S PowerShell Compatibility and Version</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-6-proven-ways-to-unlock-itel-a05s-phone-when-you-forget-the-password-by-drfone-android/"><u>In 2024, 6 Proven Ways to Unlock Itel A05s Phone When You Forget the Password</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-huawei-nova-y91-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Huawei Nova Y91 to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-photo-magic-weaving-text-into-your-imagery-journey/"><u>In 2024, Photo Magic  Weaving Text Into Your Imagery Journey</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/limited-offer-alienware-aurora-r16-upgrade-rtx-4080-super-and-i9-14900kf-at-a-500-discount/"><u>Limited Offer: Alienware Aurora R16 Upgrade - RTX 4080 Super & I9-14900KF at a $500 Discount</u></a></li>
<li><a href="https://win11.techidaily.com/1719322695938-new-windows-11-users-beware-of-these-top-8-errors/"><u>New Windows 11 Users, Beware of These Top 8 Errors</u></a></li>
<li><a href="https://win11.techidaily.com/1719218745181-panels-in-peril-bring-them-back-with-these-hacks/"><u>Panels in Peril? Bring Them Back with These Hacks!</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/pic-perfect-ranking-the-best-photo-stickering-apps-for-iphonesandroids/"><u>Pic Perfect  Ranking the Best Photo Stickering Apps for iPhones/Androids</u></a></li>
<li><a href="https://win11.techidaily.com/1719284853027-ready-set-gain-administrator-status/"><u>Ready, Set, Gain Administrator Status!</u></a></li>
<li><a href="https://win11.techidaily.com/1719330765099-troubleshooting-tips-for-your-windows-predicaments/"><u>Troubleshooting Tips for Your Windows Predicaments!</u></a></li>
<li><a href="https://win11.techidaily.com/1719258150800-win-rpc-problems-here-are-5-fixes-you-need/"><u>Win RPC Problems? Here Are 5 Fixes You Need</u></a></li>
</ul></div>
