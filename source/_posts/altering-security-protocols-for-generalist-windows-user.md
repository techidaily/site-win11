---
title: Altering Security Protocols for Generalist Windows User
date: 2024-08-16T00:41:12.364Z
updated: 2024-08-17T00:41:12.364Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Altering Security Protocols for Generalist Windows User
excerpt: This Article Describes Altering Security Protocols for Generalist Windows User
keywords: Windows Security Update,Protocol Adjustment Tips,Secure Win User Access,General User Protocol,Enhanced Windows Protection,Optimize Window's Safety,Streamlining User Security
thumbnail: https://thmb.techidaily.com/8b5881e327b9c1ba2eb90535b5e52b8fb37d29efd85f95b1f8c43ff4375091ae.jpg
---

## Altering Security Protocols for Generalist Windows User

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

## The UAC Behaviors Available for Standard User Accounts

 Unlike when [changing UAC behaviors for administrator accounts](https://www.makeuseof.com/change-user-access-control-works-administrators-windows/), the behaviors for standard user accounts are a little more limited. According to the [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-standard-users) website, here are the behaviors you can choose and what they mean:

* **Automatically deny elevation requests**: This option returns an **Access denied** error message to standard users when they try to perform an operation that requires elevation of privilege. Most organizations that run desktops as standard users configure this policy to reduce help desk calls.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a different username and password. If the user enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the user to type an administrative username and password. If the user enters valid credentials, the operation continues with the applicable privilege.

 The default UAC behavior for standard user accounts is **Prompt for credentials**, but Microsoft recommends you change it to **Automatically deny elevation requests**. That way, only users with administrator accounts can decide how the UAC behaves and make choices that will keep the computer safe.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
3. Expand the dropdown and choose a different UAC behavior.  
![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
2. Press **Enter** on your keyboard to go to the **System** key.
3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  
![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

 Now restart your computer to allow the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-who-likes-what-deciphering-instagram-stats-and-screenshots/"><u>[New] 2024 Approved  Who Likes What? Deciphering Instagram Stats & Screenshots</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-unlocking-the-secrets-to-instagram-post-replicas/"><u>[New] In 2024, Unlocking the Secrets to Instagram Post Replicas</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-masterful-descriptions-for-impactful-podcast-intros/"><u>[New] Masterful Descriptions for Impactful Podcast Intros</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-streamline-creativity-with-1-to-5-mac-editors-for-sierra-users/"><u>[New] Streamline Creativity with #1 to #5 Mac Editors for Sierra Users</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-trimming-the-bends-correcting-gopro-fish-eye-effect/"><u>[New] Trimming the Bends  Correcting GoPro Fish Eye Effect</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-video-expertise-elevated-streamline-your-edits-with-these-vimeo-shortening-techniques/"><u>[Updated] In 2024, Video Expertise Elevated  Streamline Your Edits with These Vimeo Shortening Techniques</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-learn-to-produce-fb-video-ads-using-free-kit/"><u>[Updated] Learn to Produce FB Video Ads Using Free Kit</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-the-art-of-enticing-instagram-followers-a-puzzle-post-primer/"><u>[Updated] The Art of Enticing Instagram Followers  A Puzzle Post Primer</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-action-avalon-10-thrilling-titles-comparable-to-gta-v/"><u>2024 Approved  Action Avalon  10 Thrilling Titles Comparable To GTA V</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-how-to-record-gameplay-on-xbox-one/"><u>2024 Approved  How to Record Gameplay on Xbox One</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-seamless-collaboration-the-top-5-video-call-recorder-choices/"><u>2024 Approved  Seamless Collaboration  The Top 5 Video Call Recorder Choices</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-change-location-on-facebook-marketplace-for-realme-v30-drfone-by-drfone-virtual-android/"><u>3 Ways to Change Location on Facebook Marketplace for Realme V30 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-fix-the-local-device-name-is-already-in-use-error-on-windows/"><u>5 Ways to Fix the Local Device Name Is Already in Use Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-recover-an-off-screen-window-in-windows-11-and-11/"><u>6 Ways to Recover an Off-Screen Window in Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/7-reasons-why-most-users-havent-upgraded-to-windows-11/"><u>7 Reasons Why Most Users Haven’t Upgraded to Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-motorola-g24-power-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Motorola G24 Power | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensible-guide-to-managing-windows-11-default-applications/"><u>A Comprehensible Guide to Managing Windows 11 Default Applications</u></a></li>
<li><a href="https://win11.techidaily.com/a-concise-guide-to-windows-11-user-grievances-and-gripes/"><u>A Concise Guide to Windows 11 User Grievances and Gripes</u></a></li>
<li><a href="https://win11.techidaily.com/a-practical-guide-to-accessing-the-windows-iscsi-initiator/"><u>A Practical Guide to Accessing the Windows iSCSI Initiator</u></a></li>
<li><a href="https://win11.techidaily.com/a-simplified-guide-to-jdk-setup-for-modern-windows-11-users/"><u>A Simplified Guide to JDK Setup for Modern Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-breakdown-of-entering-and-exiting-terminals-zen-space/"><u>A Step-by-Step Breakdown of Entering & Exiting Terminal's Zen Space</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-linux-vms-within-windows-via-hyper-v/"><u>A Step-by-Step Guide to Linux VMs Within Windows via Hyper-V</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-solution-to-eradicate-error-code-740-on-win-11/"><u>A Step-by-Step Solution to Eradicate Error Code 740 on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-and-starting-verifier-manager-in-win11-os/"><u>Accessing and Starting Verifier Manager in Win11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/ace-the-art-of-completing-a-perfect-windows-update/"><u>Ace the Art of Completing a Perfect Window's Update</u></a></li>
<li><a href="https://win11.techidaily.com/activate-and-personalize-your-pcs-audio-with-windows-11-mixer/"><u>Activate and Personalize Your PC's Audio with Windows 11 Mixer</u></a></li>
<li><a href="https://win11.techidaily.com/activate-secure-windows-scripting-navigating-execution-policies/"><u>Activate Secure Windows Scripting: Navigating Execution Policies</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-invalid-token-usage-in-modern-windows-systems/"><u>Addressing Invalid Token Usage in Modern Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-powershell-from-windows-command-prompt/"><u>Addressing Missing PowerShell From Windows Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-screen-driver-crash-in-windows-11/"><u>Addressing Screen Driver Crash in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-activation-issue-with-error-0x803f700f/"><u>Addressing Windows Activation Issue with Error 0X803F700f</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-disk-fragmentation-issue/"><u>Addressing Windows Disk Fragmentation Issue</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-gameplay-recording-harnessing-intel-graphics-hub/"><u>Advanced Gameplay Recording: Harnessing Intel Graphics Hub</u></a></li>
<li><a href="https://win11.techidaily.com/advancing-classic-games-in-hd-best-practices-with-scummvm-and-windows-os/"><u>Advancing Classic Games in HD: Best Practices with ScummVM and Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/affordable-access-securing-low-cost-windows-11-vcs/"><u>Affordable Access: Securing Low-Cost Windows 11 VCs</u></a></li>
<li><a href="https://win11.techidaily.com/altering-windows-standard-pdf-display/"><u>Altering Window's Standard PDF Display</u></a></li>
<li><a href="https://win11.techidaily.com/altering-windows-installation-process-via-registry/"><u>Altering Windows Installation Process via Registry</u></a></li>
<li><a href="https://win11.techidaily.com/asuss-innovation-unleashed-exploring-s15-oled-and-bape-edition/"><u>Asus's Innovation Unleashed: Exploring S15 OLED and BAPE Edition</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-compatibility-woes-with-surface-firmware-upgrade-tips/"><u>Avoid Compatibility Woes with Surface Firmware Upgrade Tips</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-challenges-of-windows-steam-content-blocks/"><u>Avoiding the Challenges of Windows Steam Content Blocks</u></a></li>
<li><a href="https://win11.techidaily.com/blackview-mp60-mini-pc-expandable-storage-but-unremarkable-performance/"><u>Blackview MP60 Mini PC: Expandable Storage but Unremarkable Performance</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-disk-capacity-7-affordable-tricks-for-windows-enthusiasts/"><u>Boosting Disk Capacity: 7 Affordable Tricks for Windows Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-ease-of-use-with-mouse-settings-in-win11/"><u>Boosting Ease of Use with Mouse Settings in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-key-steps-to-tackle-windows-blue-screen/"><u>Breaking Down Key Steps to Tackle Windows Blue Screen</u></a></li>
<li><a href="https://win11.techidaily.com/1719336940768-cant-open-chrome-try-these-win11-solutions-now/"><u>Can't Open Chrome? Try These Win11 Solutions Now.</u></a></li>
<li><a href="https://fox-http.techidaily.com/excellent-html5-video-tools-you-must-check-for-2024/"><u>Excellent HTML5 Video Tools You Must Check for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/honor-x50i-unlock-tool-remove-android-phone-password-pin-pattern-and-fingerprint-by-drfone-android-unlock-android-unlock/"><u>Honor X50i Unlock Tool - Remove android phone password, PIN, Pattern and fingerprint</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-watch-hulu-outside-us-on-samsung-galaxy-s23-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Samsung Galaxy S23 | Dr.fone</u></a></li>
<li><a href="https://program-issues.techidaily.com/improved-performance-of-dragon-age-origins-after-fixing-compatibility-with-windows-11/"><u>Improved Performance of Dragon Age: Origins After Fixing Compatibility with Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-samsung-galaxy-s24-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Samsung Galaxy S24 Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-motorola-moto-g84-5g-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Motorola Moto G84 5G? | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-quick-and-reliable-image-captures-pcs-top-5-apps/"><u>In 2024, Quick and Reliable Image Captures  PC's Top 5 Apps</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-create-stunning-3d-videos-top-makers-for-every-budget/"><u>New In 2024, Create Stunning 3D Videos Top Makers for Every Budget</u></a></li>
<li><a href="https://techidaily.com/remove-google-frp-lock-on-vivo-v29e-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP lock on Vivo V29e</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-motorola-moto-g24-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Motorola Moto G24 for Streaming | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-the-top-5-hits-where-to-get-royalty-evading-laugh-tracks-online/"><u>Updated The Top 5 Hits Where to Get Royalty-Evading Laugh Tracks Online</u></a></li>
<li><a href="https://win11.techidaily.com/1719275577489-winshift-troubles-how-to-resolve-them/"><u>WinShift Troubles: How to Resolve Them</u></a></li>
</ul></div>
