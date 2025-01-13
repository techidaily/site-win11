---
title: Mastering the Art of Fixing D3D11 Errors on Windows 11
date: 2025-01-09T01:20:21.018Z
updated: 2025-01-12T18:54:45.952Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Art of Fixing D3D11 Errors on Windows 11
excerpt: This Article Describes Mastering the Art of Fixing D3D11 Errors on Windows 11
keywords: D3D11 Error Solutions,Win11 Graphics Fixes,D3D11 Troubleshooting Tips,Video Game SDK Issues,DirectX Error Resolution,Windows 11 Debugging Guide,OpenGL Fix Techniques
thumbnail: https://thmb.techidaily.com/55ff105adfb563907b6c1c05420f78a6c5ab084d04ebfcc926d77ca01d474b27.jpg
---

## Mastering the Art of Fixing D3D11 Errors on Windows 11

 The “D3D11-compatible GPU” error is a common game-related error for both Windows 10 and 11\. You usually see this error message when you try to start certain affected games. It will present an error message that reads “a D3D11-compatible GPU (feature level 11, shader model-5) is required to run the engine," and affected games don’t start.

 This error has been more widely reported for Fortnite but also occurs for other Windows game titles. If you're struggling with this same issue, here is how you can fix the “D3D11-compatible GPU” error in Windows 10 and 11\.

## 1\. Install Any Available Windows Updates

 When you update Windows, your computer will also update DirectX This is important, as DirectX is a gaming and multimedia API. The “D3D11-compatible GPU” error message references Direct3D 11, a part of DirectX. As the “D3D11-compatible GPU” error is linked with DirectX, it’s recommended that you install all available Windows updates and see if that solves the error.

 Here is how you can check for and install updates in Windows:

1. Click **Start** with the mouse’s right button to select Search.
2. Input the keyword **updates** in the search tool.
3. Select the **Check for updates** search result to open Settings.  
![The Check for updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-for-updates-button-1.jpg)
4. Click the **Windows Update** tab’s **Check for updates** option. Selecting that option will automatically download and install available patch updates in Windows.
5. Select **Restart now** if the Windows Update tab presents that option to you.

 If you see any optional updates listed there, click their **Download and install** buttons. That includes the current Windows 11, version 22H2 update, or any other new build version, which you should select to upgrade to if available.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Scan Your System Files With SFC

 To check for possible system file corruption causing the “D3D11-compatible GPU” error, run a System File Checker (SFC) scan. The SFC tool will scan for and repair corrupted system files in Windows. You can run an SFC scan like this:

1. Open Windows Search (see [how to find Windows Search](https://www.makeuseof.com/windows-search-use-guide/) if you need help opening it) and type **cmd** into it.
2. Right-click **Command Prompt** in the search results and select **Run as administrator**.
3. Run the SFC scan by typing in and executing this command:  
`sfc /scannow`  
![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/sfc-scannow-command-1.jpg)
4. Wait for the System File Checker to finish its scanning and show an outcome message.

## 3\. Set the Game to Utilize a Dedicated Graphics Card

 Does your PC have integrated and discrete (dedicated) graphics adapters? If it does, make sure the affected game is utilizing your PC’s dedicated GPU. To do so, you can select a **High-performance** graphics option for the game via Settings. Our [guide to choosing a preferred graphics card](https://www.makeuseof.com/windows-10-choose-preferred-gpu/) for an app tells you how to set a dedicated GPU for a game in Settings.

![The High performance radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/high-performance-radio-button.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Or you could select to disable your PC’s integrated GPU instead. That will ensure all your games utilize the PC’s superior dedicated graphics adapter. You can disable the integrated GPU like this:

1. Open Device Manager, which you can access by pressing the **Windows** key + **X** and clicking on that utility’s shortcut.
2. Double-click on the **Display adapters** category to view graphics adapters.  
![The Disable device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-device-option.jpg)
3. Click on your PC’s integrated graphics adapter to select **Disable**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Select **Yes** on the dialog box that asks you to provide additional confirmation.

## 4\. Update the Driver for Your Graphics Card

 Sometimes, updating your graphical processing unit (GPU) drivers fixes the “D3D11-compatible GPU” error. If your graphics card’s driver is outdated, updating it could be the solution.

 We recommend users manually download and install the latest drivers for their graphics cards from the NVIDIA, Intel, or AMD websites. Our guide on [how to update graphics drivers on Windows](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) has more info on the topic if you need help.

## 5\. Repair or Update Visual C++ Redistributables on Your PC

 The “D3D11-compatible GPU” error can sometimes be due to missing or corrupted Microsoft Visual C++ Redistributable runtime libraries. So, you may need to repair or install a runtime library on your PC.

 Here is how you can select to repair Visual C++ Redistributables via Apps & Features:

1. Open the **Apps & Features** Settings tab using one of the methods outlined in [how to open the Apps & features tool on Windows](https://www.makeuseof.com/9-ways-to-open-the-apps-features-tool-in-windows-11/).
2. Type **Microsoft Visual C++** in the search box at the top of Apps & features.
3. Then click the three-dot menu button for a Microsoft Visual C++ Redistributable to repair there.
4. Select the **Modify** option.  
![The Modify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-modify-option-1.jpg)
5. Press the **Repair** button in the Visual C++ window that opens.  
![The Repair button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-repair-option-1.jpg)
6. Repeat the previous two steps for all Microsoft Visual C++ Redistributables listed in Apps & features.

 Or you may need to install some missing Visual C++ Redistributables libraries. You can install the latest runtime libraries with the Microsoft Visual C++ 2015-2022 Redistributable pack like this:

1. Navigate to Microsoft’s [Visual C++ Redistributable](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170) download page.
2. Click the X64 download link for Visual Studio 2015-2022.  
![The X64 download link for Visual Studio 2015-2022](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-x64-download-link-1.jpg)
3. Your browser will likely include a tab or menu that shows downloaded files. Open that **Downloads** tab, which has a **Ctrl** + **J** hotkey in the Firefox, Opera, Edge, and Chrome browsers.  
![The Downloads tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-downloads-tab-1.jpg)
4. Then click **VC\_redist.x64.exe** to bring up the window shown below.  
![The Microsoft Visual C++ 2022 window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/microsoft-visual-C-window-1.jpg)
5. If your PC is missing some runtime libraries, the Microsoft Visual C++ 2015-2022 Redistributable window will have an **Install** option. Click that **Install** button.
6. Select the **Restart now** option after updating libraries.

## 6\. Install the DirectX Runtime Libraries

 The DirectX End-User Runtime Web Installer has helped some users resolve the “D3D11-compatible GPU” error. That installer replaces missing or corrupted DirectX files. These are the steps for installing runtime libraries with the DirectX End-User Runtime Web Installer:

1. Open Microsoft’s [DirectX End-User Runtime Web Installer](https://www.microsoft.com/en-gb/download/details.aspx?id=35) download webpage.
2. Select that page’s **Download** option.
3. Next, click the dxwebsetup.exe file in the download section of your browser.
4. Select the radio button for the **I accept the agreement** option inside the DirectX setup wizard.  
![The DirectX setup wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/directx-setup-wizard-1.jpg)
5. Click **Next** to view the Bing Bar offer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rBnnLFJbvr4?si=LlHYrYlOBp7NLMec" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. If you don’t want the extra software, uncheck the selected **Install the Bing Bar** option.
7. Press the DirectX Setup wizard’s **Next** button.
8. Click **Finish** in the wizard.
9. Restart your Windows laptop or desktop.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qbuund2HKOQ?si=NaGHqIrx8hSL7gWV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 7\. Set Affected Games to Run With DirectX 11

 If you can, try setting an affected game to run with DirectX 11 instead of DX12\. Of course, you won’t be able to do that though the game’s settings screen if it doesn’t start in the first place.

 However, you can set games to run with DirectX 11 with command line arguments in Epic Games and Steam. This is how to set an affected game to run with DirectX 11 in Epic Games and Steam:

### How to Force DirectX 11 on Epic Games

 For any titles on Epic Games:

1. Bring up Epic Games Launcher’s window.
2. Click the user account button near the top-right corner of the Epic Games Launcher window.
3. Select the **Settings** menu option.  
![The Settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-settings-option-1.jpg)
4. Click an affected game’s title to expand options for it.
5. Then select the game’s **Additional Command Line Arguments** checkbox.  
![The Additional Command Line Arguments checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/additonal-command-line-arguments-box-1.jpg)
6. Input **d3d11** in the text box for the command line argument.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### How to Force DirectX 11 on Steam

 Likewise, if you're a fan of Steam:

1. Bring up the Steam client software.
2. Select **Library** along the top of Steam’s window.
3. Right-click whatever game the “D3D11-compatible GPU” occurs for and select **Properties**.
4. Input **\-dx11** in the launch option text box on the **General** tab.  
![Steam Launch Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/steam-launch-options.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 8\. Expand the Page File for More Virtual Memory

 Expanding the page file will increase the amount of virtual memory available for games. That’s a recommended troubleshooting method for the “D3D11-compatible GPU” error since your PC can better handle system demands for graphically intensive games with a larger page file. Check out our [guide to extending virtual memory in Windows](https://www.makeuseof.com/tag/virtual-memory-low-heres-fix/) to apply this potential fix.

![The Virtual Memory window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/virtual-memory-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Enjoy Your Windows Games Again

 Many players have resolved the “D3D11-compatible GPU” error with the resolutions outlined in this guide. So, there’s a good likelihood that one of them will also get that issue sorted for your Windows 11/10 games. However, some players with PCs that have old GPUs might need to upgrade their graphics cards to fix the “D3D11-compatible GPU” issue.

 The “D3D11-compatible GPU” error is a common game-related error for both Windows 10 and 11\. You usually see this error message when you try to start certain affected games. It will present an error message that reads “a D3D11-compatible GPU (feature level 11, shader model-5) is required to run the engine," and affected games don’t start.

 This error has been more widely reported for Fortnite but also occurs for other Windows game titles. If you're struggling with this same issue, here is how you can fix the “D3D11-compatible GPU” error in Windows 10 and 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-webster.techidaily.com/each-new-heights-in-youtube-seo-top-tips-and-tricks-for-2024/"><u>[New] Reach New Heights in YouTube SEO Top Tips and Tricks for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/evel-in-the-rhythm-of-rising-text/"><u>[New] Revel in the Rhythm of Rising Text</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-remedying-silent-tweets-with-audio-integration/"><u>[Updated] 2024 Approved Remedying Silent Tweets with Audio Integration</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-front-row-diversions-beyond-sports-galore/"><u>2024 Approved Front Row Diversions Beyond Sports Galore</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-window-lock-down-timer/"><u>Customizing Window Lock-Down Timer</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-windows-error-code-0x80071a90/"><u>Demystifying Windows Error Code: 0X80071A90</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/grab-your-bargain-a-thor-darth-vader-motif-monitor-is-just-1e6-more-than-expected-retailer-selling-24-inch-ips-display-at-low-price/"><u>Grab Your Bargain: A 'Thor Darth Vader' Motif Monitor Is Just $1E6 More Than Expected - Retailer Selling 24-Inch IPS Display at Low Price</u></a></li>
<li><a href="https://program-issues.techidaily.com/how-to-fix-unable-to-connect-on-kodi-and-access-media-library-data/"><u>How To Fix 'Unable To Connect' On Kodi & Access Media Library Data</u></a></li>
<li><a href="https://fox-info.techidaily.com/illustration-ingenuity-3d-text-magic/"><u>Illustration Ingenuity 3D Text Magic</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-roblox-access-error-403-on-windows-os/"><u>Tackling Roblox Access Error 403 on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/turning-screen-position-around-easily/"><u>Turning Screen Position Around Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-and-fixing-the-application-was-unable-error/"><u>Understanding and Fixing The Application Was Unable Error</u></a></li>
</ul></div>

