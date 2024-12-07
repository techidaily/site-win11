---
title: "Tech Tip: Bid Farewell to MS Edge in W11"
date: 2024-12-04T22:02:31.289Z
updated: 2024-12-07T11:20:49.676Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tech Tip: Bid Farewell to MS Edge in W11"
excerpt: "This Article Describes Tech Tip: Bid Farewell to MS Edge in W11"
keywords: Goodbye MicrosoftEdgeW11,EndingMSEdgeUpgrade,RetireOldMicrosoftEdge,PhaseOutEdgeBrowsing,SwitchFromEdgeW11,DitchEdgew11Browser,W11LeaveBehindEdgeTech
thumbnail: https://thmb.techidaily.com/6c068dd9c7ff9ad108362423509c28dd6ffe162b74770b33b89afebc380bcbd4.png
---

## Tech Tip: Bid Farewell to MS Edge in W11

 Although Microsoft Edge has made significant progress in recent years, it still lags far behind its biggest rival—Google Chrome. If you’re someone who does not like using Microsoft Edge, you may want to get rid of the browser entirely.

 It’s no secret that Microsoft wants users to use its own browser on Windows 11\. To that end, the company has made it difficult to remove the browser from Windows 11\. However, it’s still possible to do so. Here we'll show you three different ways to uninstall Microsoft Edge from your Windows 11 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Uninstall Microsoft Edge Using the Command Prompt

 You can uninstall Microsoft Edge from your PC by running a few commands in the command prompt. The process requires you to know the version number of Microsoft Edge on your computer. Once you have that, you can get rid of the browser.

Here are the steps you need to follow.

1. Open Microsoft Edge on your PC.
2. Click the**three-dot menu icon** in the top right corner and select**Help and feedback > About Microsoft Edge** .
3. Copy Microsoft Edge's version number from the**About** section.  
![Check Microsoft Edge Version Number](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Microsoft-Edge-Version-Number.jpg)
4. Press**Win + X** and select**Terminal (Admin)** from the menu that appears.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Select**Yes** when the User Account Control (UAC) prompt shows up.
6. In the console, run the following commands to navigate to the directory where Microsoft Edge is installed:  
`cd/  
cd %Program Files (x86)%\Microsoft\Edge\Application\EdgeVersion\Installer`  
 Replace**EdgeVersion** in the above command with the actual version number noted earlier.
7. Paste the following command and press**Enter** to uninstall Microsoft Edge.  
`setup --uninstall --force-uninstall --system-level`  
![Uninstall Microsoft Edge Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Command-Prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f-yPCh24EsA?si=3z8FAd_lMZeAjug7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you run the above commands, Microsoft Edge will be removed from your PC. If you want to install the browser in the future, you can do so by downloading it from the Microsoft Store.

 If you'd like to get more out of this tool, be sure to check out[the Windows Command Prompt commands you must know](https://www.makeuseof.com/tag/15-cmd-commands-every-windows-user-know/) .

## 2\. How to Uninstall Microsoft Edge Using Windows PowerShell

 Like Command Prompt, you can also use Windows PowerShell to uninstall Microsoft Edge from your Windows 11 PC. Unlike the previous method, this one does not require you to know Microsoft Edge's version number. Here's how it works.

1. Press**Win + S** to open the search menu. Type in**Windows PowerShell** and select**Run as administrator** .
2. Select**Yes** when the[User Account Control (UAC)](https://www.makeuseof.com/tag/user-account-control-windows-10/) prompt appears.
3. Paste the following command and press**Enter** .  
`get-appxpackage *edge*`  
![Uninstall Microsoft Edge With Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Using-Windows-PowerShell-1.jpg)
4. Highlight the text next to**PackageFullName** and press**Ctrl + C** to copy it.
5. Run the following command to uninstall Microsoft Edge.  
`Remove-appxpackage <PackageFullName>`  
 Replace**<PackageFullName>** in the above command with the package name copied earlier.

 Once you execute the above command, Microsoft Edge will be uninstalled.

## 3\. How to Uninstall Microsoft Edge Beta, Dev, or Canary Channel Builds Using the Settings App

 Unlike the stable version, removing a preview build of Microsoft Edge is relatively simple. You can uninstall it just like any other app. Here's how to do it using[Windows 11 Settings app](https://www.makeuseof.com/windows-11-settings-whats-new/) .

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab and click on**Installed apps** .
3. Scroll down to locate Microsoft Edge's preview build.
4. Click the**three-dot menu icon** next to it and select**Uninstall** .
5. Select**Uninstall** again when the confirmation pop-up appears.  
![Uninstall Microsoft Edge Beta From Windows 11 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Uninstall-Microsoft-Edge-Beta-From-Windows-11-1.jpg)

 Aside from the Settings app, you can uninstall the browser from the Start menu or the Control Panel. See our guide to learn different[ways to uninstall built-in apps on Windows 11](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Stop Microsoft Edge From Reinstalling on Windows 11

 Although uninstalling Edge from your computer is easy, it does not prevent newer Windows updates from potentially reinstalling the browser. To get around this, you need to[edit a few registry files](https://www.makeuseof.com/windows-registry-file-guide/) on your PC. For that, use the following steps:

1. Press**Win + R** to open the Run dialog box.
2. Type**regedit** in the box and press**Enter** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the Registry Editor window that appears, navigate to**HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft** key.
5. Right-click on the**Microsoft** key, go to**New** , and select**Key** from the submenu. Rename the key to**EdgeUpdate** .
6. Right-click on the**EdgeUpdate** key and select**New > DWORD (32-bit) Value** . Rename the DWORD to**DoNotUpdateToEdgeWithChromium** .
7. Double-click on the newly created DWORD and change its value data to**1** . Then, hit**OK** .  
![Edit DWORD in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/edit-dword-in-registry-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, Windows will not reinstall Microsoft Edge with future updates.

## Get Rid of Microsoft Edge

 With Windows 11, Microsoft tried everything possible to entice users to switch to Microsoft Edge. Unfortunately, it hasn't worked out very well, as many people still prefer to use alternatives like Google Chrome. If you are one of them, you can get rid of Microsoft Edge using the steps outlined above.

 Now that you've uninstalled Microsoft Edge, you might want to make your preferred web browser the default option on Windows 11.

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-best-free-open-source-video-conferencing-software-ranked-by-industry/"><u>[New] 2024 Approved Best Free Open Source Video Conferencing Software Ranked by Industry</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-expertly-ranked-best-internet-sound-recorders-2023/"><u>[Updated] 2024 Approved Expertly Ranked Best Internet Sound Recorders 2023</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-dichotomy-how-microsoft-and-native-windows-accounts-contrast/"><u>Exploring the Dichotomy: How Microsoft and Native Windows Accounts Contrast</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-functional-windows-thx-audio/"><u>Fixing Non-Functional Windows THX Audio</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-side-by-side-assembly-version-mismatch-error-on-windows-11/"><u>Fixing the 'Side-by-Side Assembly Version' Mismatch Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/leading-alternatives-to-microsofts-snipping-feature-in-os-xlinux/"><u>Leading Alternatives to Microsoft's Snipping Feature in OS X/Linux</u></a></li>
<li><a href="https://win11.techidaily.com/silencing-security-qanda-for-local-admin-users-in-windows-11/"><u>Silencing Security Q&A for Local Admin Users in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-dark-mode-in-paint/"><u>The Ultimate Guide to Dark Mode in Paint</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/top-ten-youtube-regulations-to-abide-by/"><u>Top Ten YouTube Regulations to Abide By</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/understanding-the-significance-of-microsofts-monthly-security-updates/"><u>Understanding the Significance of Microsoft's Monthly Security Updates</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-to-do-if-your-iphone-14-pro-max-has-bad-esn-or-blacklisted-imei-by-drfone-ios/"><u>What to do if your iPhone 14 Pro Max has bad ESN or blacklisted IMEI?</u></a></li>
</ul></div>

