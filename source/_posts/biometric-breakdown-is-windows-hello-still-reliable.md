---
title: "Biometric Breakdown: Is Windows Hello Still Reliable?"
date: 2024-08-08T13:12:26.297Z
updated: 2024-08-09T13:12:26.297Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Biometric Breakdown: Is Windows Hello Still Reliable?"
excerpt: "This Article Describes Biometric Breakdown: Is Windows Hello Still Reliable?"
keywords: Biometric Security,Windows Login,Facial Recognition,Tech Reliability,Identity Verification,Microsoft Hello,Authentication Flaws
thumbnail: https://thmb.techidaily.com/e3e57dc288a15eebc6a087ce47534d889b154128f1cec9b763b947b83648c7c9.jpg
---

## Biometric Breakdown: Is Windows Hello Still Reliable?

 Logging into a Windows laptop with a fingerprint scanner is easy; just place your finger on a scanner, and the operating system lets you in. However, researchers have shown that, while this method is convenient, it's not hackproof.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Can People Hack Windows Hello Fingerprint Scanners?

![Lock Having Fingerprint in the Middle on Blue Background](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/passwords-are-a-thing-of-the-past-passwordless-logins-benefits.jpg)

 If a hacker wants to bypass a fingerprint scanner on a Windows machine, they're aiming to get past a service called Windows Hello. This service handles how you log into Windows, such as PINs, facial scans, and fingerprint scans.

 As part of research into Windows Hello's strength, two [white-hat hackers](https://www.makeuseof.com/white-hat-hacker/), Jesse D'Aguanno and Timo Teräs, posted a report on their website, [Blackwing HQ](https://blackwinghq.com/blog/posts/a-touch-of-pwn-part-i/). The report details how they breached three popular devices: the Dell Inspiron 15, Lenovo ThinkPad T14, and the Microsoft Surface Pro Type Cover.

### How the Hackers Breached Windows Hello on the Dell Inspiron 15

 For the Dell Inspiron 15, the hackers noticed they could boot into Linux on the laptop. Once logged into Linux, they can register their fingerprints in the system and give it the same ID as the Windows user they want to log into.

 Then, they perform a man-in-the-middle attack on the connection between the PC and the sensor. They set it up so that when Windows goes to double-check that a scanned fingerprint is legitimate, it ends up checking the Linux database of fingerprints instead of its own.

 To dodge Windows Hello, the hackers uploaded their fingerprints to the Linux database, assigned it the same ID as the user on Windows, and then tried to log into Windows with their fingerprints. During the authentication process, they redirected the packet to the Linux database, which told Windows that the user at the specified ID was ready to log in.

### How the Hackers Breached Windows Hello on the Lenovo ThinkPad T14

 For the Lenovo ThinkPad, the hackers discovered that the laptop used a custom encryption method to verify fingerprints. With some work, the hackers managed to decrypt it, giving them a way into the fingerprint verification process.

 Once done, the hackers could force the fingerprint database to accept their fingerprint as the user's. Then, all they had to do was scan their fingerprint to access the Lenovo ThinkPad.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
### How the Hackers Breached Windows Hello on the Microsoft Surface Pro Type Cover

 The hackers believed the Surface Pro would be the hardest device to crack, but they were surprised to find the Surface Pro lacked a lot of security measures for checking valid fingerprints. In fact, they discovered that they only had to dodge past one defense, then tell the Surface Pro that the fingerprint scan was successful, and the device let them in.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## What Do These Hacks Mean for You?

![Professional Thinking With Laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/professional-thinking-with-laptop.jpg)

 These hacks may sound pretty scary if you use fingerprints to log into your laptop. However, it's essential to remember some crucial things before you forgo fingerprint scans entirely.

### 1\. The Attacks Were Performed by Skilled Hackers

 The reason threats like [ransomware as a service](https://www.makeuseof.com/what-is-ransomware-as-a-service/) are so deadly is that anyone with minimal cybersecurity can use them. However, the above hacks require a high level of expertise, with a deep understanding of how devices authenticate fingerprints and how to avoid them.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
### 2\. The Attacks Require the Attacker to Physically Interact With the Device

 The hackers must have physical contact with the device to perform the above hacks. In the report, the hackers stated they might be able to create USB devices that can perform the attack once plugged in, but that means a potential attacker needs to plug something into your PC to hack it.

### 3\. The Attacks Only Work on Specific Devices

 You'll notice that each attack had to take a different path to achieve the same goal. Every device is unique, and a hack that works on one device may not work on another. As such, you shouldn't believe that Windows Hello has now been blown wide open on every device; it's just these three that failed.

 While these hacks may sound scary, they'll be challenging to perform against actual targets. The hacker will likely have to steal the device to perform these hacks, which would undoubtedly alert the previous owner.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Stay Safe From Fingerprint Hacking

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The face of a man wearing a hoodie](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hacher-hat.jpg)

 As stated above, the discovered hacks are complicated to perform and may require the hacker to remove the device to hack into it physically. As such, there's an extremely low chance that these attacks will personally target you.

 However, if you're still not satisfied, there are some ways to protect yourself from fingerprint scanner hacks:

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Do Not Leave Devices Unattended and Unprotected

 Because a hacker will need to interact with your device physically, you should ensure it doesn't fall into the wrong hands. For computers, you can [take steps to stop it from being stolen](https://www.makeuseof.com/tag/stop-entire-desktop-pc-home-office-stolen/). If you're using a laptop, never leave it alone in a public space, and use an [anti-theft laptop bag](https://www.makeuseof.com/tag/anti-theft-laptop-bags/) to stop people from tearing your bag open.

### 2\. Use a Different Login Method

 Windows Hello supports many different login methods, some more secure than others. If you've fallen out of love with fingerprint scans, check out if [face, iris, fingerprint, PIN, or password logins are more secure](https://www.makeuseof.com/face-iris-fingerprint-password-pin-most-secure/), and choose one that suits you best.

 If you're worried about these hacks, it's important to remember that there's a very low chance they'll target you specifically. As such, you should be safe using fingerprint scans; just don't allow people to steal your devices.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-blue.techidaily.com/new-essential-tips-for-creating-videos-with-windows-8-moviemaker-for-2024/"><u>[New] Essential Tips for Creating Videos with Windows 8 MovieMaker for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-unveiling-whatsapps-call-conversations/"><u>[New] Unveiling WhatsApp's Call Conversations</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-high-quality-capture-on-mac-a-review-of-top-10-software/"><u>[Updated] High-Quality Capture on Mac  A Review of Top 10 Software</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-snapshot-scribbles-10-top-writing-aids-for-image-capture-iosandroid/"><u>[Updated] Snapshot Scribbles  10 Top Writing Aids for Image Capture (iOS/Android)</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-easy-steps-for-designing-podcast-rss-structure/"><u>2024 Approved  Easy Steps for Designing Podcast RSS Structure</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-redefining-content-creation-beyond-vimeo-tools/"><u>2024 Approved  Redefining Content Creation Beyond Vimeo Tools</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-reel-them-in-a-step-by-step-approach-to-livestreaming-on-youtube/"><u>2024 Approved  Reel Them In  A Step-by-Step Approach to Livestreaming on Youtube</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-exploration-of-win11s-voice-control-shortcuts/"><u>A Detailed Exploration of Win11's Voice Control Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-failed-outlook-notification-popups/"><u>Addressing Failed Outlook Notification Popups</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-windows-disk-space-save-personal-files/"><u>Amplify Windows Disk Space, Save Personal Files</u></a></li>
<li><a href="https://win11.techidaily.com/breeze-through-blurred-taskbars-in-windows-11/"><u>Breeze Through Blurred Taskbars in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-a-comfortable-computing-environment-configuring-active-periods-and-managing-updates-in-windows-11/"><u>Crafting a Comfortable Computing Environment: Configuring Active Periods & Managing Updates in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-and-repairing-windows-enter-key-issues/"><u>Diagnosing and Repairing Windows Enter Key Issues</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-sony-device-sim-by-drfone-android/"><u>Easily Unlock Your Sony Device SIM</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-steam-connectivity-issues-with-quick-solutions/"><u>Enhancing Steam Connectivity Issues with Quick Solutions</u></a></li>
<li><a href="https://fox-helps.techidaily.com/essential-list-of-minuscule-uavs-2021/"><u>Essential List of Minuscule UAVs 2021</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-inaccessible-window-resolutions-8-simple-steps/"><u>Fixing Inaccessible Window Resolutions: 8 Simple Steps</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-silence-the-expiring-windows-license-message/"><u>How To Silence the Expiring Window's License Message</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-uninstall-programs-without-admin-privileges-on-windows/"><u>How to Uninstall Programs Without Admin Privileges on WINDOWS</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-samsung-galaxy-a15-4g-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Samsung Galaxy A15 4G? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-nokia-c02-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Nokia C02? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-tips-and-tricks-to-tell-if-your-iphone-12-mini-is-unlocked-by-drfone-ios/"><u>In 2024, Tips And Tricks To Tell if Your iPhone 12 mini Is Unlocked</u></a></li>
<li><a href="https://win11.techidaily.com/journey-to-greatness-your-ultimate-new-pc-apps/"><u>Journey to Greatness: Your Ultimate New PC Apps</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-correcting-virtualboxs-0x80004005-error/"><u>Mastering the Art of Correcting VirtualBox's 0X80004005 Error</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-process-to-remove-wsl-from-windows/"><u>Mastering the Process to Remove WSL From Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-troubled-waters-eliminating-error-code-80080300-in-win11-tech/"><u>Navigate Through Troubled Waters: Eliminating Error Code 80080300 in Win11 Tech</u></a></li>
<li><a href="https://win11.techidaily.com/orchestrated-workflows-joining-ifttt-and-to-do/"><u>Orchestrated Workflows: Joining IFTTT and To-Do</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-xbox-audio-hurdles-with-windows-11-system-upgrades/"><u>Overcoming Xbox Audio Hurdles with Windows 11 System Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-user-interaction-ai-integration-into-windows-11/"><u>Redefining User Interaction: AI Integration Into Windows 11</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/seamless-integration-of-dvd-playback-on-your-system/"><u>Seamless Integration of DVD Playback on Your System</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-integration-web-pages-as-windows-tools/"><u>Seamless Integration: Web Pages as Windows Tools</u></a></li>
<li><a href="https://win11.techidaily.com/securing-access-how-to-use-windows-11s-security-interface/"><u>Securing Access: How to Use Windows 11'S Security Interface</u></a></li>
<li><a href="https://win11.techidaily.com/securing-save-configurations-in-your-windows-pubg-game/"><u>Securing Save Configurations in Your Windows PUBG Game</u></a></li>
<li><a href="https://win11.techidaily.com/securing-windows-11-with-additional-firewall-options-via-context-menu/"><u>Securing Windows 11 with Additional Firewall Options via Context Menu</u></a></li>
<li><a href="https://win11.techidaily.com/skirting-enforced-driver-checks-for-easier-updates/"><u>Skirting Enforced Driver Checks for Easier Updates</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-intel-wi-fi-6a-driver-failure-in-windows-os/"><u>Solutions for Intel Wi-Fi 6A Driver Failure in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-directx-setup-failures/"><u>Steps to Resolve DirectX Setup Failures</u></a></li>
<li><a href="https://win11.techidaily.com/stepwise-guide-to-amplifying-virtual-memory-on-microsofts-latest-os/"><u>Stepwise Guide to Amplifying Virtual Memory on Microsoft's Latest OS</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-swiftly-finding-and-fixing-windows-update-problems/"><u>Strategies for Swiftly Finding and Fixing Windows Update Problems</u></a></li>
<li><a href="https://win11.techidaily.com/system-tray-simplified-the-art-of-minimizing-apps-on-windows/"><u>System Tray Simplified: The Art of Minimizing Apps on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/systematic-solutions-locating-and-correcting-windows-errors-via-the-power-of-command-prompt/"><u>Systematic Solutions: Locating & Correcting Windows Errors via the Power of Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/tailored-web-safety-including-reliable-domains-in-windows-11/"><u>Tailored Web Safety: Including Reliable Domains in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/taking-out-trash-onedrive-from-your-pcs-file-explorer/"><u>Taking Out Trash: OneDrive From Your PC's File Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/the-window-whisperers-guide-to-unveiling-off-screen-apps-in-win-1011-6-proven-steps/"><u>The Window Whisperer's Guide to Unveiling Off-Screen Apps in Win 10/11 (6 Proven Steps)</u></a></li>
<li><a href="https://win11.techidaily.com/tidy-up-your-machine-best-windows-software-to-ditch/"><u>Tidy Up Your Machine: Best Windows Software to Ditch</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-solving-error-code-31-in-windows-systems/"><u>Understanding and Solving Error Code 31 in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-simple-steps-for-correction-of-character-map-errors/"><u>Unveiling Simple Steps for Correction of Character Map Errors</u></a></li>
<li><a href="https://win11.techidaily.com/windows-mastery-directing-app-and-browser-traffic/"><u>Windows Mastery: Directing App and Browser Traffic</u></a></li>
</ul></div>
