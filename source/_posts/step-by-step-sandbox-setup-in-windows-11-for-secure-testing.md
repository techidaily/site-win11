---
title: Step-by-Step Sandbox Setup in Windows 11 for Secure Testing
date: 2024-11-21T00:38:51.316Z
updated: 2024-11-28T04:21:03.811Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Step-by-Step Sandbox Setup in Windows 11 for Secure Testing
excerpt: This Article Describes Step-by-Step Sandbox Setup in Windows 11 for Secure Testing
keywords: Win11 Sandbox Guide,Secure Testing Box,Security Sandbox,Windows Secure Sys,Setup Secured Tests,Secure Dev Env Set,Safe Windows Sandbox
thumbnail: https://thmb.techidaily.com/e3cf30b4720656ba32f87d0a36d739d3e594003c967c2e7d28e98120dd95b14e.jpg
---

## Step-by-Step Sandbox Setup in Windows 11 for Secure Testing

 Microsoft Windows 11 features multiple virtualization solutions out of the box. While Hyper-V is an excellent tool, Windows Sandbox is an easy alternative to Windows virtual machines. It lets you run untrusted apps in an isolated environment without the hassle of setting up a complete virtualization tool.

 Unfortunately, Windows Sandbox is not available on the Home edition of the OS. If you are running the Pro, Enterprise, and Education edition, here is how to enable and set up Windows Sandbox in Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Set Up Windows Sandbox in Windows 11

 Windows Sandbox is an optional feature, which means you'll have to install it from the Optional features section. You can[add and remove optional features from the Windows Features dialog](http://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) . Alternatively, you can use PowerShell or Command Prompt for a swift installation of Windows Sandbox.

 While the setup process is easier, your computer must meet some system requirements. Windows 11 Pro, Education, or Enterprise running computers with virtualization support are Windows Sandbox compatible. In most cases,[if your system can run Windows Hyper-V](https://www.makeuseof.com/windows-11-enable-hyper-v/) , it should also run Windows Sandbox.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Enable Windows Sandbox Using the Windows Features Dialog

 You can install Windows Sandbox using the Windows Features dialog. This dialog houses most of the optional Windows features that are ready to be installed on your PC.

 Follow these steps to install Windows Sandbox using the Windows Features dialog:

1. Press**Win + R** to open**Run** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**
3. In the left panel, click on**Turn Windows features on or off.**  
![control panel turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/control-panel-turn-windows-features-on-or-off.jpg)
4. In the**Turn Windows features on or off dialog** , scroll down and locate**Windows Sandbox.**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Check the**Windows Sandbox** option and click**OK** .  
![enable Windows sandbox turn windows features on or off](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-Windows-sandbox-turn-windows-features-on-or-off.jpg)
6. Windows will search for the files and install the required dependencies to run Windows Sandbox scenarios. Once the changes are applied, close the Windows features dialog and restart your PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=lhdUUVYMVQjzHXBh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. After the restart, press**Win + S** to open**Windows search.**
8. Type**sandbox** and click on**Windows Sandbox** from the search result to launch the virtualization tool.

## 3\. Install Windows Sandbox Using PowerShell

![enable windows sandbox powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-powershell.jpg)

 You can use the Enable WindowsOptionalFeature command in PowerShell to install Windows Sandbox in Windows. This method is useful if you find the sandbox option greyed out or unable to install it from the Windows Feature dialog.

To install Windows Sandbox using PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal (Admin)** to open the Windows Terminal with administrative privilege. Since PowerShell is assigned as the default profile upon launch, you can execute your PowerShell cmdlets straight away in Windows Terminal.
3. In the Windows Terminal window, copy and paste the following command and press Enter:  
Enable-WindowsOptionalFeature -Online -FeatureName "Containers-DisposableClientVM" -All
4. If no error occurs, Windows will install the required files to enable Windows Sandbox.
5. Once done, press**Y** and hit**Enter** to restart your PC.
6. After the restart, you can launch Windows Sandbox from Windows Search.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Install Windows SandBox Using Command Prompt

![enable windows sandbox command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-windows-sandbox-command-prompt.jpg)

 Deployment Image Servicing and Management (DISM) is a command-line utility that facilitates the installation of optional features using the Command Prompt. To install Windows Sandbox, you will need to use the Enable-Feature command in Command Prompt. Here's how to do it.

1. Press**Win + R** to open**Run** .
2. Type**cmd** in the**Run** dialog. Press and hold**Ctrl + Shift** and click**OK** to open Command Prompt as administrator.
3. In the Command Prompt, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName: "Containers-DisposableClientVM" -All`
4. Wait for the process to complete. Once done, press**Y** and**Enter** to restart your PC.

## How to Use Windows Sandbox

![Windows Sandbox Open](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Windows-Sandbox-Open.jpg)

 Now that you have Windows Sandbox installed, you can start using it to test untrusted apps in isolation. To launch the app, press**Win + S** to open**Windows Search** and type**Windows Sandbox.** Click on the app from the search result to open it.

 Upon its launch, Windows Sandbox looks like a lightweight version of your Windows machine. You can copy files from your host system or download them from the Internet using the built-in web browser. Any actions you perform in the sandbox will not affect your host system.

 Once the testing is complete, close the Sandbox and click**OK** to confirm the action. Unlike a VM, Sandbox will delete all the data (including apps and files) upon exit. So, you'll get a clean, isolated environment running the same Windows OS build as your host machine each time.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Set Up and Use Windows Sandbox in Windows 11

 Windows Sandbox provides an excellent way to test apps and files in an isolated environment without the hassle of setting up a virtual machine. While the virtual machines have distinct advantages, Sandbox is lighter, faster, and loads a fresh copy of Windows OS each time it's run.

 Windows 11 Home users, however, have missed out on this excellent feature. But if you must use a sandbox, consider using third-party alternatives such as Sandboxie Plus and SHADE Sandbox. These alternatives offer a similar set of functionalities with no complicated setup involved.

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
<li><a href="https://youtube-tips.techidaily.com/024-approved-learn-the-low-cost-way-of-designing-winning-youtube-ad-campaigns/"><u>[New] 2024 Approved Learn the Low-Cost Way of Designing Winning YouTube Ad Campaigns</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-best-live-stream-tools-xsplit-or-obs/"><u>[New] Best Live Stream Tools XSplit or OBS?</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-streamlined-methods-for-documenting-overwatch-engagements/"><u>2024 Approved Streamlined Methods for Documenting Overwatch Engagements</u></a></li>
<li><a href="https://win11.techidaily.com/convergence-mastery-the-ultimate-win-11-file-guide/"><u>Convergence Mastery: The Ultimate Win 11 File Guide</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/discover-how-to-enhance-your-nes-classic-experience-with-additional-titles/"><u>Discover How to Enhance Your NES Classic Experience With Additional Titles</u></a></li>
<li><a href="https://driver-install.techidaily.com/elevating-performance-guiding-through-msi-driver-enhancements-on-windows-7810/"><u>Elevating Performance: Guiding Through MSI Driver Enhancements on Windows 7/8/10</u></a></li>
<li><a href="https://win11.techidaily.com/empowering-your-pc-navigation-with-apple-maps/"><u>Empowering Your PC Navigation with Apple Maps</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-audio-integrating-dolby-atmos-in-windows/"><u>Enhance Your Audio: Integrating Dolby Atmos in Windows</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/get-a-huge-discount-save-up-to-550-on-samsung-odyssey-neo-g8-grab-yours-from-best-buy-before-prime-day-ends-review/"><u>Get a Huge Discount: Save Up To $550 on Samsung Odyssey Neo G8 - Grab Yours From Best Buy Before Prime Day Ends! Review</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-implementing-google-play-in-win11-os/"><u>Guide to Implementing Google Play in Win11 OS</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-boost-your-home-project-film-quality-fast-and-simple/"><u>In 2024, Boost Your Home Project Film Quality Fast and Simple</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-oneplus-ace-2-drfone-by-drfone-virtual-android/"><u>In 2024, Is pgsharp legal when you are playing pokemon On OnePlus Ace 2? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-windows-auto-lock-setting/"><u>Quick Guide to Windows Auto-Lock Setting</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-vitality-to-slow-moving-windows-batches/"><u>Restoring Vitality to Slow-Moving Windows Batches</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-blueprint-for-customizing-windows-startup/"><u>The Complete Blueprint for Customizing Windows Startup</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-vivo-y17s-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Vivo Y17s Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-time-tangle-solved-unify-system-dates/"><u>Windows Time Tangle Solved: Unify System Dates</u></a></li>
</ul></div>

