---
title: Step-by-Step DNS Flushing in Modern Windows
date: 2024-09-05T08:27:37.495Z
updated: 2024-09-06T08:27:37.495Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Step-by-Step DNS Flushing in Modern Windows
excerpt: This Article Describes Step-by-Step DNS Flushing in Modern Windows
keywords: WinDNS Flush,DNS Reset,Flush DNS Cache,DNS Update Windows,Clear DNS Settings,DNS Server Refresh,Network Resolution Reset
thumbnail: https://thmb.techidaily.com/0994f11e3b98aa050445b83a923c27f3f286a1f5302c7ff78d5008912b4d02f9.jpg
---

## Step-by-Step DNS Flushing in Modern Windows

 Facing internet connectivity issues on your Windows PC? DNS cache corruption is among the most common reasons for connectivity problems. The quickest fix for this problem is to flush the DNS cache and force the computer to recreate it.

 But do you know that there are multiple ways to flush the DNS cache on Windows 11? We will elaborate on the benefits of clearing the DNS cache along with the multiple methods which you can use on your Windows 11 PC. Without further ado, let’s dive into the post.

## What Is the DNS Cache and Why Should You Flush It?

 When you access a website, you usually do so by typing its URL in a browser. However, computers don't "understand" URLs, and each URL has a corresponding IP address that a computer can actually use. When you search for a website, your computer accesses a DNS server that contains records of URLs and their corresponding IP addresses.

 This process is known as DNS lookup, but it is time-consuming to search for an IP address every time, especially for websites that you visit repeatedly. So, the computer maintains a local copy of the DNS known as the DNS resolver cache. When you search for a URL, it checks the resolver cache first and then uses that information to find the website.

 The DNS resolver cache can become outdated or corrupt over time which can pose connectivity issues. There is also a looming risk of[DNS cache poisoning](https://www.makeuseof.com/tag/what-is-dns-cache-poisoning/) , which is why you should make it a habit to clean the DNS cache periodically.

<!-- affiliate ads begin -->
<span id="1983474">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983474.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983474">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983474.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983474%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983474/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Flush the DNS Cache on Windows 11

 There are multiple methods to flush the DNS cache on Windows 11\. You can use the Run command box, Command Prompt, or even PowerShell. In addition, you can use a batch file to clear the DNS cache in a few clicks, any time you want. Here are the four ways to clear DNS on Windows 11:

<!-- affiliate ads begin -->
<span id="1938136">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938136.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938136">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938136.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938136%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938136/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Using the Run Command Box

To flush the DNS cache using the Run command box, do as follows:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type “**ipconfig /flushdns** ” command.  
![Flush DNS Using the Run Command Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-the-run-command-box.jpg)
3. Press**Ctrl + Shift + Enter** keys at once. The Command Prompt will launch, execute the flush command, and close automatically.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137203/26400" target="_top" id="2137203">
  <img src="//a.impactradius-go.com/display-ad/26400-2137203" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137203/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Using CMD

 To clear the DNS resolver cache using CMD, repeat the following steps:

1. Press**Win + R** to open the run dialog box. Type**cmd** and press**Ctrl + Shift + Enter** keys at once.
2. CMD will open with admin privileges.
3. Type “**ipconfig /flushdns** ” command and press the**Enter** key.  
![Flush DNS Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-cmd.jpg)
4. You will see a “**Successfully flushed the DNS Resolver Cache.** ” message after the command execution.

### 3\. Using PowerShell

 PowerShell has a different command to flush the DNS cache on Windows 11\. Here’s how to do it:

1. Press**Win + S** and type**PowerShell** . Click on the**Run as administrator** option in the Start menu.
2. Now, type “**Clear-DnsClientCache** ” in the PowerShell window and press the**Enter** key.  
![Flush DNS Using Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-powershell.jpg)
3. You won’t see a message after the command executes successfully. But you can open PowerShell again and view the DNS cache to confirm.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118313/7443" target="_top" id="2118313">
  <img src="//a.impactradius-go.com/display-ad/7443-2118313" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118313/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115929/19272" target="_top" id="2115929">
  <img src="//a.impactradius-go.com/display-ad/19272-2115929" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115929/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 4\. Using a Batch File

 Opening an app is a slightly time-consuming process. You can save time by creating a batch file once and then running it whenever you need to flush DNS. No need to open the CMD or PowerShell app.

Repeat the following steps to create a DNS-clearing batch file:

1. Press**Win + S** to open Windows Search. Type**Notepad** and click on the first search result.
2. Type the following command in Notepad:**cmd.exe /k ipconfig /flushdns**  
![Flush DNS Using A Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-a-batch-file.jpg)
3. Press**Ctrl + S** to save the file. Enter the name “**flushDNS.bat** ” and keep the**Save as type** as**All Files** .
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134489/18498" target="_top" id="2134489">
  <img src="//a.impactradius-go.com/display-ad/18498-2134489" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134489/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Click on the**Save** button.
5. Now go to the batch file location and double-click on it.
6. The Command Prompt will launch and execute the "**/** flushdns" command.
7. Type**exit** and press the**Enter** key to close the command prompt window.

## How to Flush Your Browser's DNS Records

 Do you know that browsers maintain a DNS cache as well? If you face connectivity issues, you should clear the browser's DNS cache and force the browser to rebuild the cache.

 Repeat the following steps to clear Chrome browser’s DNS cache:

1. Launch the Chrome browser and press**Ctrl + T** to open a new tab.
2. Now, type “**chrome://net-internals/#dns** ” in the search bar and press the**Enter** key.
3. Navigate to the**Host resolver cache** section. Click on the**Clear host cache** button to clear cached DNS records in the Chrome browser.

 The process to clear a browser's DNS cache may differ with other browsers like Safari, Opera, and Mozilla. You will have to locate the DNS settings and then wipe out the DNS cache.

## Keep Your DNS Cache Clean on Windows

 Flushing the system's DNS cache periodically can reduce the risk of DNS spoofing and website connectivity issues. The simplest method is to use the ipconfig utility with appropriate parameters to flush the DNS cache. Alternatively, you can use the PowerShell method or create a batch file for the same.


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
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-assemble-films-for-streaming-organization/"><u>[New] 2024 Approved  Assemble Films for Streaming Organization</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-effortless-techniques-for-streamlined-ipad-video-recording/"><u>[New] Effortless Techniques for Streamlined iPad Video Recording</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-free-video-conferencing-excellence-plus-screen-sharing-guide/"><u>[New] In 2024, Free Video Conferencing Excellence + Screen Sharing Guide</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-gameplay-transformations-roguelikes-vs-roguiles/"><u>[Updated] 2024 Approved  Gameplay Transformations  Roguelikes Vs. Roguiles</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-heaviest-aerial-transporters-top-10-drones-reviewed/"><u>[Updated] Heaviest Aerial Transporters  Top 10 Drones Reviewed</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-step-by-step-livestreaming-to-facebook-from-iphonestablets/"><u>[Updated] In 2024, Step-by-Step  Livestreaming to Facebook From iPhones/Tablets</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-master-vlc-tips-revealing-unknown-features/"><u>[Updated] Master VLC Tips  Revealing Unknown Features</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-childs-delight-greatest-drone-selections/"><u>2024 Approved  Child's Delight  Greatest Drone Selections</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-elevate-every-frame-the-best-practices-in-11-video-grading-guides/"><u>2024 Approved  Elevate Every Frame  The Best Practices in 11 Video Grading Guides</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-microsoft-hololens-demo-tomorrows-tech-today/"><u>2024 Approved  Microsoft HoloLens Demo – Tomorrow’s Tech Today</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/adjusting-google-meet-display-mobile-and-laptop-focus/"><u>Adjusting Google Meet Display  Mobile and Laptop Focus</u></a></li>
<li><a href="https://win-answers.techidaily.com/clearing-up-the-permission-denied-issue-for-smooth-fortnite-gameplay/"><u>Clearing Up the Permission Denied Issue for Smooth Fortnite Gameplay</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-removing-x80300024-from-pcs/"><u>Deciphering and Removing X80300024 From PCs</u></a></li>
<li><a href="https://win11.techidaily.com/discovering-the-best-of-win11s-feb-2023-update/"><u>Discovering the Best of Win11's Feb 2023 Update</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-develop-with-wsl-2-core-practices-for-dev-on-windows/"><u>Efficiently Develop with WSL 2: Core Practices for Dev on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-win11-audio-problem-code-0xc00d36b4/"><u>Eliminating Win11 Audio Problem: Code 0xC00D36B4</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-typing-precision-in-windows-11-sidestep-key-lag-pitfalls/"><u>Enhance Typing Precision in Windows 11: Sidestep Key Lag Pitfalls</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-razer-device-compatibility-in-windows-1011/"><u>Enhancing Razer Device Compatibility in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/expose-hidden-components-in-windows-11-display/"><u>Expose Hidden Components in Windows 11 Display</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-privilege-access-denial-error-error-0x80070522-on-modern-windows-pcs/"><u>Fixing Privilege Access Denial Error (Error 0X80070522) on Modern Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/from-mobile-to-stationary-setting-up-your-android-as-a-windows-webcam/"><u>From Mobile to Stationary: Setting Up Your Android as a Windows Webcam</u></a></li>
<li><a href="https://win11.techidaily.com/full-fledged-quest-mastery-classics-full-hd-and-the-power-of-scummvm-windows/"><u>Full-Fledged Quest Mastery: Classics, Full HD, and the Power of ScummVM Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-nokia-c300-bootloader-easily-by-drfone-android/"><u>How to Unlock Nokia C300 Bootloader Easily</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-infinix-smart-7-hd-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Infinix Smart 7 HD to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-still-using-pattern-locks-with-lava-blaze-2-5g-tips-tricks-and-helpful-advice-by-drfone-android/"><u>In 2024, Still Using Pattern Locks with Lava Blaze 2 5G? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://win11.techidaily.com/keyways-to-activate-windows-11s-backup-and-restore-options/"><u>Keyways to Activate Windows 11'S Backup and Restore Options</u></a></li>
<li><a href="https://win11.techidaily.com/maintaining-windows-volume-control-configuration/"><u>Maintaining Windows Volume Control Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/master-control-unscheduling-gpgpu-on-windows-platforms/"><u>Master Control: Unscheduling GPGPU on Windows Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-passwords-in-windows-11-with-the-four-best-guardians/"><u>Master Your Passwords in Windows 11 with The Four Best Guardians</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-attributes-on-windows-a-practical-guide/"><u>Mastering File Attributes on Windows: A Practical Guide</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-the-basics-how-to-perform-a-factory-reset-on-your-samsung-tv/"><u>Mastering the Basics: How to Perform a Factory Reset on Your Samsung TV</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-windows-11-safe-mode-in-6-steps/"><u>Navigate to Windows 11 Safe Mode in 6 Steps</u></a></li>
<li><a href="https://win11.techidaily.com/nvidias-geforce-error-on-windows-heres-the-fix/"><u>Nvidia's GeForce Error on Windows? Here’s the Fix</u></a></li>
<li><a href="https://win11.techidaily.com/pace-up-decoding-your-graphics-spec-in-windows-11/"><u>Pace Up: Decoding Your Graphics Spec in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/premium-windows-emulators-for-nintendos-switch-library/"><u>Premium Windows Emulators for Nintendo's Switch Library</u></a></li>
<li><a href="https://win11.techidaily.com/pro-naming-schemes-for-windows-files-max-156/"><u>Pro Naming Schemes for Windows Files (Max 156)</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722974717880-quick-download-hp-envy-5055-laptop-drivers-get-them-fast/"><u>Quick Download: HP ENVY 5055 Laptop Drivers – Get Them Fast</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-adobe-photoshop-closure-issues-on-latest-oses/"><u>Resolving Adobe Photoshop Closure Issues on Latest OSes</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-tasks-using-ifttt-for-microsoft-to-do/"><u>Simplifying Tasks: Using IFTTT for Microsoft To-Do</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-capturing-windows-based-chats/"><u>The Art of Capturing Windows-Based Chats</u></a></li>
<li><a href="https://win11.techidaily.com/the-conquerors-guide-taking-back-control-over-windows-11-themes/"><u>The Conquerors Guide: Taking Back Control over Windows 11 Themes</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/top-5k-tcl-tvs-in-depth-look-at-the-tcl-50s425-50-inch-smart-roku-tv-of-2019/"><u>Top 5K TCL TVs: In-Depth Look at the TCL 50S425 50-Inch Smart Roku TV of 2019</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-lock-in-experience-longer-passwords-in-win1011/"><u>Transform Your Lock-In Experience: Longer Passwords in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-one-side-headphone-output-in-windows-10/"><u>Troubleshooting One-Side Headphone Output in Windows 10</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-pictures-from-lava-storm-5g-by-fonelab-android-recover-pictures/"><u>Undelete lost pictures from Lava Storm 5G.</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-solving-virtualbox-usb-attachment-failures/"><u>Understanding and Solving VirtualBox USB Attachment Failures</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-update-9-tactics-against-steady-verify-failures/"><u>Unlock Windows Update: 9 Tactics Against Steady Verify Failures</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-the-mystery-fixing-missing-updates-on-windows-os-code-0x80070003/"><u>Unpacking the Mystery: Fixing Missing Updates on Windows OS (Code: 0X80070003)</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-bsod-log-files-in-microsoft-os/"><u>Unveiling BSOD Log Files in Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/win11-and-11-a-comprehensive-directdraw-troubleshooting-manual/"><u>Win11 & 11: A Comprehensive DirectDraw Troubleshooting Manual</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-enabling-immersive-sound-experience/"><u>Windows 11: Enabling Immersive Sound Experience</u></a></li>
</ul></div>
