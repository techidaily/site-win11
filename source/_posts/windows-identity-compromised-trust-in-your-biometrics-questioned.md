---
title: "Windows Identity Compromised: Trust in Your Biometrics Questioned"
date: 2024-08-28T00:50:17.367Z
updated: 2024-08-29T00:50:17.367Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Identity Compromised: Trust in Your Biometrics Questioned"
excerpt: "This Article Describes Windows Identity Compromised: Trust in Your Biometrics Questioned"
keywords: Windows Security Breach,Bio-Compromise Risk,Identity Theft Alert,Biometric Vulnerability,Fingerprint Hacking,Facial Recognition Flaw,Safe Browsing Tips
thumbnail: https://thmb.techidaily.com/afda68c97ad8ab431f217d1a649d9d5c1081b7b5e12422de4ab2672dba23567f.jpg
---

## Windows Identity Compromised: Trust in Your Biometrics Questioned

 Logging into a Windows laptop with a fingerprint scanner is easy; just place your finger on a scanner, and the operating system lets you in. However, researchers have shown that, while this method is convenient, it's not hackproof.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?

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
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
### How the Hackers Breached Windows Hello on the Microsoft Surface Pro Type Cover

 The hackers believed the Surface Pro would be the hardest device to crack, but they were surprised to find the Surface Pro lacked a lot of security measures for checking valid fingerprints. In fact, they discovered that they only had to dodge past one defense, then tell the Surface Pro that the fingerprint scan was successful, and the device let them in.

## What Do These Hacks Mean for You?

![Professional Thinking With Laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/professional-thinking-with-laptop.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
 These hacks may sound pretty scary if you use fingerprints to log into your laptop. However, it's essential to remember some crucial things before you forgo fingerprint scans entirely.

### 1\. The Attacks Were Performed by Skilled Hackers

 The reason threats like [ransomware as a service](https://www.makeuseof.com/what-is-ransomware-as-a-service/) are so deadly is that anyone with minimal cybersecurity can use them. However, the above hacks require a high level of expertise, with a deep understanding of how devices authenticate fingerprints and how to avoid them.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
### 2\. The Attacks Require the Attacker to Physically Interact With the Device

 The hackers must have physical contact with the device to perform the above hacks. In the report, the hackers stated they might be able to create USB devices that can perform the attack once plugged in, but that means a potential attacker needs to plug something into your PC to hack it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
### 3\. The Attacks Only Work on Specific Devices

 You'll notice that each attack had to take a different path to achieve the same goal. Every device is unique, and a hack that works on one device may not work on another. As such, you shouldn't believe that Windows Hello has now been blown wide open on every device; it's just these three that failed.

 While these hacks may sound scary, they'll be challenging to perform against actual targets. The hacker will likely have to steal the device to perform these hacks, which would undoubtedly alert the previous owner.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Stay Safe From Fingerprint Hacking

![The face of a man wearing a hoodie](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hacher-hat.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
 As stated above, the discovered hacks are complicated to perform and may require the hacker to remove the device to hack into it physically. As such, there's an extremely low chance that these attacks will personally target you.

 However, if you're still not satisfied, there are some ways to protect yourself from fingerprint scanner hacks:

### 1\. Do Not Leave Devices Unattended and Unprotected

 Because a hacker will need to interact with your device physically, you should ensure it doesn't fall into the wrong hands. For computers, you can [take steps to stop it from being stolen](https://www.makeuseof.com/tag/stop-entire-desktop-pc-home-office-stolen/). If you're using a laptop, never leave it alone in a public space, and use an [anti-theft laptop bag](https://www.makeuseof.com/tag/anti-theft-laptop-bags/) to stop people from tearing your bag open.

### 2\. Use a Different Login Method

 Windows Hello supports many different login methods, some more secure than others. If you've fallen out of love with fingerprint scans, check out if [face, iris, fingerprint, PIN, or password logins are more secure](https://www.makeuseof.com/face-iris-fingerprint-password-pin-most-secure/), and choose one that suits you best.

 If you're worried about these hacks, it's important to remember that there's a very low chance they'll target you specifically. As such, you should be safe using fingerprint scans; just don't allow people to steal your devices.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-friendly.techidaily.com/updated-evaluating-visual-dynamics-the-power-of-luminances-hdr/"><u>[Updated] Evaluating Visual Dynamics  The Power of Luminance's HDR</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-detailed-framework-elevating-your-mobile-screenshots-using-mobizen/"><u>2024 Approved  Detailed Framework  Elevating Your Mobile Screenshots Using Mobizen</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-pinnacle-10-battle-royale-experiences/"><u>2024 Approved  Pinnacle 10 Battle Royale Experiences</u></a></li>
<li><a href="https://screen-recording.techidaily.com/apex-legends-gameplay-reimagined-for-solo-devotees-without-cross-play-for-2024/"><u>Apex Legends Gameplay Reimagined for Solo Devotees without Cross-Play for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/connecting-with-ease-understanding-microsofts-phone-link-app/"><u>Connecting with Ease: Understanding Microsoft's Phone Link App</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/eliminating-frame-discrepancies-in-obs-recordings/"><u>Eliminating Frame Discrepancies in OBS Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/essential-adjustments-for-disabled-windows-defense/"><u>Essential Adjustments for Disabled Window's Defense</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/essential-tips-for-correcting-the-advrcntr2dll-absent-problem-with-nero-programs/"><u>Essential Tips for Correcting the 'AdvRcntr2.dll Absent' Problem with Nero Programs</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-clear-out-a-no-logo-screen-in-win1011/"><u>How to Clear Out a No-Logo Screen in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unblock-and-connect-chrome-in-your-os-firewallantivirus-settings/"><u>How to Unblock and Connect Chrome in Your OS Firewall/Antivirus Settings</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-honor-x9b-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Honor X9b</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-bypass-android-lock-screen-using-emergency-call-on-nokia-c22-by-drfone-android/"><u>In 2024, How to Bypass Android Lock Screen Using Emergency Call On Nokia C22?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-pro-level-insights-transforming-your-instagram-feed/"><u>In 2024, Pro-Level Insights  Transforming Your Instagram Feed</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-tecno-spark-10-5gfrp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Tecno Spark 10 5GFRP Lock</u></a></li>
<li><a href="https://unlock-android.techidaily.com/lock-your-infinix-note-30-vip-racing-edition-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>Lock Your Infinix Note 30 VIP Racing Edition Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-microsofts-filter-key-functionality/"><u>Mastering Microsoft's Filter Key Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-frozen-windows-update-issue/"><u>Mastery Over Frozen Windows Update Issue</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-search-service-error-on-pcs/"><u>Overcoming Windows Search Service Error on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-wow-error-132-a-step-by-step-guide/"><u>Overcoming WoW Error #132: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-windows-drivers-a-step-by-step-guide/"><u>Overhauling Windows Drivers: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/prime-fps-count-apps-to-enhance-your-win-11-gameplay/"><u>Prime FPS Count Apps to Enhance Your Win 11 Gameplay</u></a></li>
<li><a href="https://win11.techidaily.com/quiet-windows-11-ceasing-background-tasks/"><u>Quiet Windows 11: Ceasing Background Tasks</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-misdirected-mouse-motion-in-windows-systems/"><u>Rectify Misdirected Mouse Motion in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-frustrating-apex-legends-crashes-in-win11/"><u>Resolving Frustrating Apex Legends Crashes in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-vanishing-steam-icon-graphics/"><u>Reviving Vanishing Steam Icon Graphics</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-photo-correction-mastering-background-removal/"><u>Seamless Photo Correction: Mastering Background Removal</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-ai-risks-when-crafting-your-win-11-code/"><u>Sidestep AI Risks When Crafting Your Win 11 Code</u></a></li>
<li><a href="https://win11.techidaily.com/simple-steps-customizing-windows-explorer-again/"><u>Simple Steps: Customizing Windows Explorer Again</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-unlock-device-driver-access-in-windows-11/"><u>Strategies to Unlock Device Driver Access in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-upgrades-with-windows-11-in-place-protocols/"><u>Streamlining Upgrades with Windows 11 In-Place Protocols</u></a></li>
<li><a href="https://win11.techidaily.com/sync-issue-resolved-windows-time-coordination/"><u>Sync Issue Resolved: Windows Time Coordination</u></a></li>
<li><a href="https://win11.techidaily.com/the-7-best-free-desktop-password-generators-for-windows/"><u>The 7 Best Free Desktop Password Generators for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/transition-tactics-replacing-older-software-with-windows-11/"><u>Transition Tactics: Replacing Older Software with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-control-panel-errors/"><u>Troubleshooting Windows Control Panel Errors</u></a></li>
<li><a href="https://win11.techidaily.com/windows-terminal-and-powershell-unveiling-their-differences/"><u>Windows Terminal & PowerShell: Unveiling Their Differences</u></a></li>
<li><a href="https://win11.techidaily.com/windows-tips-for-distinguishing-between-hdd-and-ssd/"><u>Windows Tips for Distinguishing Between HDD and SSD</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>