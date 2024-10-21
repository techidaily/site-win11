---
title: Mastering USB Regulation in Windows Environment
date: 2024-10-17T22:30:55.036Z
updated: 2024-10-21T01:22:23.423Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering USB Regulation in Windows Environment
excerpt: This Article Describes Mastering USB Regulation in Windows Environment
keywords: USB Mastery in WinOS,USB Control Windows,Windows USB Compliance,WinUSB Standards,USB Interface Windows,USB Guidelines WIN,Managing USB Windows
thumbnail: https://thmb.techidaily.com/069b298bfedee9c280f30a09eb725e41e8884f90fc111239be7bdf14c7e0c06b.jpg
---

## Mastering USB Regulation in Windows Environment

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

### Using the Local Group Policy Editor

![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123732/7443" target="_top" id="2123732">
  <img src="//a.impactradius-go.com/display-ad/7443-2123732" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123732/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111981/7443" target="_top" id="2111981">
  <img src="//a.impactradius-go.com/display-ad/7443-2111981" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111981/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997680/19272" target="_top" id="1997680">
  <img src="//a.impactradius-go.com/display-ad/19272-1997680" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997680/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Registry Editor is another reliable tool you can use for tweaking system settings and troubleshooting PC issues.

 However, this tool is quite sensitive. So, it’s often worth [backing up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before editing its keys.

 Now, here’s how to use the Registry Editor to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **Enter** to open the Registry Editor.
3. Copy-paste the following command into the address bar and press **Enter**:

HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows

 From there, follow these steps:

1. Right-click on the **Windows** folder and select **New > Key**. From there, name this key as **DeviceInstall** and press **Enter**.
2. Right-click on the **DeviceInstall** key and select **New > Key**. Next, name the key as **Restrictions** and press **Enter**.
3. Click the **Restrictions** folder, right-click on a blank space on the right, and then select **New > DWORD (32-bit) Value**. From there, name the value as **DenyRemovableDevices** and press **Enter**.

![Clicking the DenyRemovableDevices value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-DenyRemovableDevices-value.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528689/16446" target="_top" id="1528689">
  <img src="//a.impactradius-go.com/display-ad/16446-1528689" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528689/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

## How to Prevent Others From Installing Specific Removable Storage Devices

 In some instances, you might want to prevent others from installing specific removable storage devices. So, let’s show you how you can do that using either the LGPE or the Registry Editor.

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-apeaks-leap-forward-in-screen-capture-review-and-results-for-2024/"><u>[New] Apeak’s Leap Forward in Screen Capture – Review and Results for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-superior-pfv-optimization-in-tardy-action/"><u>[New] Superior PFV Optimization in Tardy Action</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-win11s-power-button-for-swift-access/"><u>Customizing Win11's Power Button for Swift Access</u></a></li>
<li><a href="https://extra-hints.techidaily.com/echoes-expanse-a-compreshift-of-best-speech-to-text-applications/"><u>Echoes Expanse A Compreshift of Best Speech-to-Text Applications</u></a></li>
<li><a href="https://win-extraordinary.techidaily.com/ensuring-safe-backups-a-guide-to-using-windows-server-2012-r2-on-synology-network-attached-storage-nas/"><u>Ensuring Safe Backups: A Guide to Using Windows Server 2012 R2 on Synology Network Attached Storage (NAS)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-onedrive-sign-in-error-0x8004dec5-on-windows-11/"><u>How to Fix the OneDrive Sign In Error 0X8004dec5 on Windows 11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-use-ispoofer-on-poco-m6-5g-drfone-by-drfone-virtual-android/"><u>How to use iSpoofer on Poco M6 5G? | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/illustrate-instantly-image-to-illustration-on-any-device-for-2024/"><u>Illustrate Instantly Image to Illustration on Any Device for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-10-best-tools-to-bypass-icloud-activation-lock-on-iphone-12-mini-you-should-try-out-by-drfone-ios/"><u>In 2024, The 10 Best Tools to Bypass iCloud Activation Lock On iPhone 12 mini You Should Try Out</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/mastering-mobile-vertical-panoramas-in-action-for-2024/"><u>Mastering Mobile Vertical Panoramas in Action for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-tasks-5-top-tier-windows-car-drivers/"><u>Optimize Tasks: 5 Top-Tier Windows Car Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-daily-tasks-with-top-windows-to-do-apps/"><u>Optimizing Daily Tasks with Top Windows To-Do Apps</u></a></li>
<li><a href="https://win11.techidaily.com/smarter-network-management-timely-ping-command-deployment/"><u>Smarter Network Management: Timely Ping Command Deployment</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/stellar-unveils-game-changing-imagery-salvage-program-leading-the-market-worldwide/"><u>Stellar Unveils Game-Changing Imagery Salvage Program, Leading the Market Worldwide</u></a></li>
<li><a href="https://win11.techidaily.com/uncover-the-root-of-dxgierror-in-windows-11/"><u>Uncover the Root of DXGI_ERROR in Windows 11</u></a></li>
</ul></div>

