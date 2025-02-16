---
title: Bypassing Windows' Signature Checks for Easy Updates
date: 2025-02-08T18:04:16.831Z
updated: 2025-02-15T21:47:06.247Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing Windows' Signature Checks for Easy Updates
excerpt: This Article Describes Bypassing Windows' Signature Checks for Easy Updates
keywords: Bypass Signature Update,Windows Quick Update,Skip Verification Process,Update Without Windows Signatures,Unblock Software Upgrades,Ease-Updater Compliance,Fast Windows Patching Methods
thumbnail: https://thmb.techidaily.com/796380b2f6e477c41fdb5986a336623e799bf688b4a29cd4a3d817de3e2d744c.jpg
---

## Bypassing Windows' Signature Checks for Easy Updates

 Sometimes, Windows will block you from installing an unsigned driver, which is a driver you've downloaded elsewhere other than through a Windows Update or the device manufacturer's website. But if you need the driver, and you know it is perfectly safe, you can turn off driver signature enforcement and let it through.

 In this guide, we're going to show you several ways to do it.

## How to Disable Driver Signature Enforcement in the Startup Settings

 A temporary way to disable driver signature enforcement is through Startup Settings, allowing you to install the unsigned drivers. However, the moment you restart your PC, Windows will re-enable driver signature enforcement. The unsigned drivers you've installed will still work, but you may not be able to install new ones.

 To disable driver signature enforcement this way, you'll have to [access the Startup Settings screen](https://www.makeuseof.com/windows-startup-settings/). The **Disable driver signature enforcement** option will be the seventh one, so press **F7** or **7** on your keyboard to select it.

![windows 11 startup settings safe mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-startup-settings-safe-mode.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PNw3Lb26wFA?si=5NR1XRVSp41EQYMy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Your computer will then restart, and when it reboots, you'll be able to install those unsigned drivers.

## How to Disable Driver Signature Enforcement in the Local Group Policy Editor

 You can also disable driver signature enforcement by tweaking the **Code signing for driver packages** policy in the Local Group Policy Editor (LGPE). Doing this will allow you to install unsigned drivers even if you restart your computer.

 Unfortunately, you can only natively access the LGPE if you're on Windows Pro or Enterprise Edition. However, there is a way to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

1. Press **Win + S** to bring up Windows Search, enter **group policy** in the Search box, and select **Edit group policy** in the Search results.  
![Open Group Policy Editor Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/open-group-policy-editor-using-windows-search.jpg)
2. Once the LGPE opens up, head to **User Configuration > Administrative Templates > System > Driver Installation**.
3. Right-click **Code signing for driver packages** and select **Edit**.  
![editing the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/editing-the-code-signing-for-driver-packages-policy.jpg)
4. Click the **Enabled** radio button, and then, in the **Options** section, click on the dropdown and select **Ignore**.  
![enabling the Code signing for driver packages policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/enabling-the-code-signing-for-driver-packages-policy.jpg)
5. Click on **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PKZUYice-ws?si=L8iMa9T3h7TMSWdQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to enable driver signature enforcement again, go back to step #4 and set the radio button to **Not configured**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cC-HtDQVoG0?si=nQcoa7q8q2IL8U0m" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Disable Driver Signature Enforcement in PowerShell

 Another way to disable driver signature enforcement is by running the command to turn off integrity checks in PowerShell (you'll have to run it as an administrator). And just like with the Local Group Policy Editor, it will remain disabled until you enable it again.

 Follow the steps below to turn off driver signature enforcement in PowerShell:

 You can disable driver signature enforcement by [opening Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) if you prefer it over PowerShell.

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set nointegritychecks on** and paste it into PowerShell.  
![turning off driver signature enforcement in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-off-driver-signature-enforcement-in-terminal.jpg)
4. Hit **Enter** to run the command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To turn on driver signature enforcement again, replace the command in step #3 with **bcdedit /set nointegritychecks off**.

 One potential problem you can run into when trying to turn off driver signature enforcement this way is an error stating **The value is protected by Secure Boot policy and cannot be modified or deleted**.

![Secure Boot error in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/secure-boot-error-powershell.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If that is the case, you can try [turning off Secure Boot](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) and trying again. But if you don't want to do this, using Startup Settings and the Local Group Policy Editor is perfectly okay.

 You can also put Windows in test mode, which disables driver signature enforcement, allowing you to install those unsigned drivers. To enter test mode, follow the steps below (keep in mind that you may run into the Secure Boot error):

1. Right-click **Start** and select **Terminal (Admin)** on Windows 11 or **Windows PowerShell (Admin)** on Windows 10\.
2. Click **Yes** on the UAC prompt.
3. Copy **bcdedit /set testsigning on** and paste it into PowerShell.  
![turning on Test Mode in Terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/07/turning-on-test-mode-in-terminal.jpg)
4. Hit **Enter** to run the command.

 Now restart your computer, and when it boots back up, it will be in test mode. After you're done installing those drivers, don't forget to disable test mode. The command to do that is **bcdedit /set testsigning off**.

## Now You Can Install Unsigned Drivers on Windows

 Installing unsigned drivers on Windows is not recommended, since they can lead to unexpected behavior. However, if you trust the driver, there's no reason why the OS should block you from installing it. Just use one of the methods mentioned above, and you should be able to install and use unsigned drivers on your Windows PC.

 In this guide, we're going to show you several ways to do it.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-screen-recording-on-mac-a-comprehensible-method/"><u>[New] 2024 Approved Screen Recording on Mac A Comprehensible Method</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-harnessing-free-clip-art-legally/"><u>[New] In 2024, Harnessing Free Clip Art Legally</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-photoshop-for-beginners-top-editing-hacks-revealed/"><u>[New] Photoshop For Beginners Top Editing Hacks Revealed</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-plotting-precise-promotional-reels/"><u>[Updated] 2024 Approved Plotting Precise Promotional Reels</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-enhancing-collaboration-whiteboard-tactics-for-all-zoom-users/"><u>2024 Approved Enhancing Collaboration Whiteboard Tactics for All Zoom Users</u></a></li>
<li><a href="https://win11.techidaily.com/distinctions-in-windows-setup-the-role-of-cloud-versus-hardware/"><u>Distinctions in Windows Setup: The Role of Cloud Versus Hardware</u></a></li>
<li><a href="https://win11.techidaily.com/essential-zero-cost-gems-for-flourishing-windows-11-pcs/"><u>Essential Zero-Cost Gems for Flourishing Windows 11 PCs</u></a></li>
<li><a href="https://techtrends.techidaily.com/exclusive-info-alert-discover-psvr2-release-timeline-pricing-structure-and-advanced-hardware-details/"><u>Exclusive Info Alert: Discover PSVR2 Release Timeline, Pricing Structure and Advanced Hardware Details</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/exploring-toms-hardware-comprehensive-reviews-and-insights/"><u>Exploring Tom's Hardware: Comprehensive Reviews & Insights</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/free-television-experience-with-antop-at-127-an-in-depth-product-analysis-and-review/"><u>Free Television Experience with Antop AT-127: An In-Depth Product Analysis and Review</u></a></li>
<li><a href="https://win11.techidaily.com/preserving-progress-epic-games-backup-essentials/"><u>Preserving Progress: Epic Games Backup Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-how-to-solve-error-0x00000001-with-xbox-game-pass-and-windows-11/"><u>Quick Guide: How to Solve Error 0X00000001 with Xbox Game Pass and Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/reactivating-outlook-overcoming-one-way-startup-glitches/"><u>Reactivating Outlook: Overcoming One-Way Startup Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-the-phone-pc-connection-with-windows-11/"><u>Streamlining the Phone-PC Connection with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/taking-charge-of-yourphoneexe-on-windows-xpvista/"><u>Taking Charge of YourPhoneExe on Windows XP/Vista</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/turn-your-webcam-into-a-broadcast-device-with-vlc/"><u>Turn Your Webcam Into a Broadcast Device with VLC</u></a></li>
</ul></div>

