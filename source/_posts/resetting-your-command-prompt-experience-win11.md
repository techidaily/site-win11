---
title: Resetting Your Command Prompt Experience (Win11)
date: 2024-08-16T00:05:13.031Z
updated: 2024-08-17T00:05:13.031Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resetting Your Command Prompt Experience (Win11)
excerpt: This Article Describes Resetting Your Command Prompt Experience (Win11)
keywords: Win11 CmdPrompt Reset Guide,Reset Windows Terminal,Cleaner CMD Environment,Update Command Prompt,Enhance PC Cmd Experience,Fix Command Errors,Streamline CMD Settings
thumbnail: https://thmb.techidaily.com/b60c76ffc589ae0e04ed8d9626d309109b105480cf9bd2a5898ac2cac1fa41f0.jpg
---

## Resetting Your Command Prompt Experience (Win11)

 Windows Terminal is the next-generation command line platform in Windows 11\. It provides an improved user experience with modern command line tools that enable you to access multiple command lines in a single window. The tool is essential for developers and administrators alike, but sometimes your terminal settings need to be reset to default.

 In this article, we will explain how to reset your Windows Terminal settings back to their original state.

## Why Would You Reset Your Windows Terminal?

 Windows Terminal is an amazing tool for power users and developers. It allows you to access a variety of tools, all in one place, with custom settings and themes that make it easy to work from anywhere. But over time, your Windows Terminal may become cluttered with old settings or themes that have become redundant or are no longer relevant.

 It also helps clear out any potentially harmful malware or corrupt files that might be lurking in the background of your system, hindering your productivity. By doing so, you will ensure that your computer works as fast and as smoothly as possible - giving you the most optimal experience when using this powerful tool.

 Let's now move to the below sections and see how it can be reset.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
## How to Reset Windows Terminal Settings Using Command Prompt

 The Command Prompt is a command line tool that can help you accomplish a number of tasks on your computer. It lets you run programs, manage files, and even troubleshoot problems with the operating system. We covered a lot of its functionality in our [beginner's guide to the Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) , but for now, we'll just explore resetting the Windows Terminal settings.

 To reset Windows Terminal Settings back to their defaults, follow these steps:

1. Open the Command Prompt. For this, use the Taskbar search or type "cmd" in the Run dialog.
2. In the Command Prompt window, copy and paste the following command:  
![Reset Windows Terminal Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-command-prompt.jpg)  
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
del /f /s /q /a "%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json"
3. Now press the**Enter** key to delete the settings.json file.
4. You can now exit the command prompt.

## How to Reset Windows Terminal Settings Using Windows PowerShell

 Windows PowerShell is another command line application that you can use to restore Windows Terminal Settings to their default state. To figure out how, follow these steps:

1. Open Windows PowerShell. You can do this by pressing**Win + R** , typing "PowerShell", and then pressing**Enter** . You can also one of the other [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
2. In the PowerShell window, copy and paste the following command:  
![Reset Windows Terminal Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-powershell.jpg)  
Remove-Item -Path "$env:LOCALAPPDATA\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json" -Force
3. Press**Enter** to execute the command.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Reset Windows Terminal Settings From File Explorer

 If you don't prefer the command line process, you can use Windows File Explorer to reset the settings. In this way, the Terminal will be reset to its default settings, and you can continue using it. Here's how to do it:

1. Open Windows File Explorer. For this, right-click Start and choose**File Explorer** , or press**Win + E** on your keyboard.
2. Copy and paste the following path into the address bar:  
![Reset Windows Terminal Using File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-windows-terminal-using-file-explorer.jpg)  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
%LocalAppData%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState
3. On the next page, right-click on**settings.json** and select**Delete** from the context menu.

 Once you perform the above steps, Settings.json will automatically be created with the default settings.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://twitter-videos.techidaily.com/new-crafting-captivating-real-time-tweets-for-maximum-impact/"><u>[New] Crafting Captivating Real-Time Tweets for Maximum Impact</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-elevate-your-influence-mastering-instagram-engagement/"><u>[New] Elevate Your Influence  Mastering Instagram Engagement</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-how-to-streamline-your-vimeo-video-subtitles-for-2024/"><u>[New] How to Streamline Your Vimeo Video Subtitles for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-unleash-your-inner-animator-easily-share-gifs-on-snapchat/"><u>[New] In 2024, Unleash Your Inner Animator  Easily Share Gifs on Snapchat</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-precision-capturing-the-art-of-ps4-gaming-recordings-with-obs/"><u>[New] Precision Capturing  The Art of PS4 Gaming Recordings with OBS</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-the-pinnacle-of-live-tweeting-on-social-media/"><u>[New] The Pinnacle of Live Tweeting on Social Media</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-a-complete-breakdown-of-lgs-premium-4k-screen-experience/"><u>[Updated] A Complete Breakdown of LG’s Premium 4K Screen Experience</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-global-viewership-kings-youtubes-viral-royalty-for-2024/"><u>[Updated] Global Viewership Kings  YouTube's Viral Royalty for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-free-visual-templates-to-upgrade-your-profile/"><u>[Updated] In 2024, Free Visual Templates to Upgrade Your Profile</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-next-frontier-of-classroom-technology-vr/"><u>2024 Approved  The Next Frontier of Classroom Technology - VR</u></a></li>
<li><a href="https://win11.techidaily.com/a-window-into-future-skies-top-weather-apps-for-pc/"><u>A Window Into Future Skies: Top Weather Apps for PC</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-oppo-reno-8t-drfone-by-drfone-virtual-android/"><u>A Working Guide For Pachirisu Pokemon Go Map On Oppo Reno 8T | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/combat-windows-11-lags-top-strategies-to-boost-speed/"><u>Combat Windows 11 Lags: Top Strategies to Boost Speed</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-secure-boot-the-ultimate-rufus-guidebook/"><u>Conquering Secure Boot: The Ultimate Rufus Guidebook</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/converting-your-cellphone-to-a-diy-video-recorder-for-2024/"><u>Converting Your Cellphone to a DIY Video Recorder for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-vm-management-hosting-linux-on-a-windows-system-with-hyper-v/"><u>Efficient VM Management: Hosting Linux on a Windows System with Hyper-V</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-digital-sketching-with-microsoft-paint-updates/"><u>Elevating Digital Sketching with Microsoft Paint Updates</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-not-enough-privileges-error-during-installation-on-windows/"><u>Eliminating Not Enough Privileges Error During Installation on Windows</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/essential-frames-from-apples-display-max-length-156-for-2024/"><u>Essential Frames From Apple's Display (Max Length  156) for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/ethernet-efficiency-top-tips-to-test-your-networks-pace-on-windows/"><u>Ethernet Efficiency: Top Tips to Test Your Network's Pace on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tune-auto-lock-and-screensaver-on-pc/"><u>Fine-Tune Auto-Lock & Screensaver on PC</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-of-the-best-pokemon-discord-servers-to-join-on-nokia-xr21-drfone-by-drfone-virtual-android/"><u>Here are Some of the Best Pokemon Discord Servers to Join On Nokia XR21 | Dr.fone</u></a></li>
<li><a href="https://ai-topics.techidaily.com/how-to-generate-speech-from-text-the-top-text-to-speech-converters-for-2024/"><u>How To Generate Speech From Text | The Top Text-to-Speech Converters for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-modify-calculators-color-scheme-dark/"><u>How To Modify Calculator's Color Scheme (Dark)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-battlenet-desktop-client-successfully/"><u>How to Reactivate Battle.net Desktop Client Successfully</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-lost-data-of-apple-iphone-15-plus-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Lost Data of Apple iPhone 15 Plus? | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-dive-deep-into-the-world-of-creator-studio/"><u>In 2024, Dive Deep Into the World of Creator Studio</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-navigating-instagram-copyright/"><u>In 2024, Navigating Instagram Copyright</u></a></li>
<li><a href="https://extra-resources.techidaily.com/innovative-shooting-the-best-cinematographic-tips-and-ideas/"><u>Innovative Shooting  The Best Cinematographic Tips & Ideas</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-track-windows-10-and-11-note-hacks/"><u>Keeping Track: Windows 10 & 11 Note Hacks</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-realme-11x-5g-device-by-drfone-android/"><u>Mastering Android Device Manager The Ultimate Guide to Unlocking Your Realme 11X 5G Device</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-error-0x8007251d-windows-activation-demystified/"><u>Mastery over Error 0X8007251D: Windows Activation Demystified</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-prevalent-windows-rainmeter-troubles/"><u>Navigating Through Prevalent Windows Rainmeter Troubles</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-win11-startup-options-a-comprehensive-guide/"><u>Navigating Win11 Startup Options: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/operating-unity-windows-rolls-out-across-apple-pc-mac-android-world/"><u>Operating Unity: Windows Rolls Out Across Apple, PC, Mac, Android World</u></a></li>
<li><a href="https://win-able.techidaily.com/overcome-technical-hurdles-effective-ways-to-fix-the-directx-error-in-modern-warfare-2/"><u>Overcome Technical Hurdles: Effective Ways to Fix the DirectX Error in Modern Warfare 2</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-5ghz-wireless-hurdles/"><u>Overcoming Windows 11 5GHz Wireless Hurdles</u></a></li>
<li><a href="https://win11.techidaily.com/protocols-to-enter-windows-administrative-hub/"><u>Protocols to Enter Windows' Administrative Hub</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-the-conflict-between-apps-and-computers-default-audio/"><u>Remedying the Conflict Between Apps and Computer's Default Audio</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-missing-thermal-policy-in-windows-environment/"><u>Restoring Missing Thermal Policy in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-windows-services-command-line-tool-with-these-7-steps/"><u>Restoring Window's Services Command Line Tool with These 7 Steps</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/revolutionize-data-capture-using-advanced-cookiebot-tools/"><u>Revolutionize Data Capture Using Advanced Cookiebot Tools</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-your-pc-with-apples-imessage/"><u>Setting Up Your PC with Apple's iMessage</u></a></li>
<li><a href="https://tech-revival.techidaily.com/snapchats-ai-compared-with-microsofts-bing-on-skype-unveiling-the-top-8-distinctions/"><u>Snapchat's AI Compared with Microsoft's Bing on Skype: Unveiling the Top 8 Distinctions</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-choices-activating-filters-on-windows-11-files/"><u>Streamline Choices: Activating Filters on Windows 11 Files</u></a></li>
<li><a href="https://win11.techidaily.com/swift-methods-how-to-determine-hard-drivessd-status-in-windows-system/"><u>Swift Methods: How to Determine Hard Drive/SSD Status in Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/the-10-best-apps-to-replace-windows-11s-default-apps/"><u>The 10 Best Apps to Replace Windows 11'S Default Apps</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-leading-7-android-apps-to-cut-out-intrusive-ads-for-2024/"><u>The Leading 7 Android Apps to Cut Out Intrusive Ads for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-error-exception-breaking-point-achieved-in-windows/"><u>Troubleshooting Error: Exception Breaking Point Achieved in Windows</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-success-eliminating-starfields-cutting-sounds/"><u>Troubleshooting Success: Eliminating Starfield's Cutting Sounds</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-messages-from-oppo-find-x6-pro-by-fonelab-android-recover-messages/"><u>Undelete lost messages from Oppo Find X6 Pro</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-how-chatbots-engage-in-humanlike-interactions-the-technology-explained/"><u>Unveiling How Chatbots Engage in Humanlike Interactions: The Technology Explained</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-guide-reactivate-disabled-slack-notifications/"><u>Win 11 Guide: Reactivate Disabled Slack Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/win-over-webp-saving-chrome-image-format-change-guide/"><u>Win Over WebP Saving: Chrome Image Format Change Guide</u></a></li>
</ul></div>
