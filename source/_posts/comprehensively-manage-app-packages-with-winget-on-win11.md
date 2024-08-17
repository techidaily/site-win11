---
title: Comprehensively Manage App Packages with Winget on Win11
date: 2024-08-16T00:46:10.974Z
updated: 2024-08-17T00:46:10.974Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Comprehensively Manage App Packages with Winget on Win11
excerpt: This Article Describes Comprehensively Manage App Packages with Winget on Win11
keywords: Package Management W/Win11,Winget Tool for Windows,Winget Installation Command,Winget App Packaging,Win11 Software Deployment,Automated Package Update,Winget PowerShell Cmd
thumbnail: https://thmb.techidaily.com/4f408d1e600338fdfbc4fe3abf110c58fed31529d9f9f53c6cd72af0ec21a5e5.jpg
---

## Comprehensively Manage App Packages with Winget on Win11

 Winget is a command-line tool that can download and install app packages from MS Store and the apps available in its repository. Windows users yearned for a dedicated package manager built into the OS until Microsoft decided to give them one. It is better than using an additional package manager but not all users love the terminal.

 If you have used Winget even once, you know that knowing the correct commands is of absolute importance if you want to avoid errors. But what if you had a GUI version of Winget? WingetUI is one such app that slaps a coat of UI on Winget. Curious? Let’s begin.

## What Is WingetUI, and How Is It Different From Winget?

 WingetUI is a GUI implementation of the [Winget](https://www.makeuseof.com/how-to-download-install-and-use-the-windows-package-manager-winget/)tool that makes it super easy to manage app packages. It also supports Scoop and Chocolatey and can act as GUI forefront for all these three tools. If you'd like to know more about those, check out our [comparison between Chocolatey and Windows Package Manager](https://www.makeuseof.com/chocolatey-vs-windows-package-manager/), and [how to install Scoop on Windows](https://www.makeuseof.com/windows-install-scoop/).

 Currently, WingetUI offers more than 4700 packages for Winget. If you combine the package list for all three package managers (including Chocolatey and [Scoop](https://www.makeuseof.com/windows-install-scoop/)), the numbers stand at a staggering 14000\.

 So, you can directly access 14000 packages without leaving the app and will have to rarely search the web. WingetUI can help you to manage all the installed packages, discover and install new ones, [batch install multiple packages](https://www.makeuseof.com/export-import-apps-winget-in-windows-11/), export or import package list, search for packages inside the app, and more.

 The fun doesn’t stop there. You can switch to dark mode in the app, and it even notifies you about the app updates whenever you launch the app and can even auto-update them. Furthermore, you can even view the package details, and its commands, and can share the packages with your friends.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
## How to Download and Install WingetUI on Windows11

 WingetUI is available on GitHub and also has a dedicated website to keep you updated about the new features. However, you will find the download links on [GitHub](https://github.com/marticliment/WingetUI/releases/latest), Softpedia, and Uptodown only. Download the installer file from any of these hosts and then install it on your PC. Make note that WingetUI only works with Windows 10 and Windows 11 (64-bit versions only).

 After the installation completes, the app will ask you to select the package managers you want to use. Select the **Enable Winget** option for now, and click on the **Apply and Start WingetUI** button.

![Install WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-wingetui.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
## How to Manage App Packages Using WingetUI on Windows 11

 WingetUI divides the whole app into three sections: Discover Packages, Software Updates, and Installed packages. You can view all the available packages in the app using the Discover Packages section, while the Software Updates section list all the app that have a new version available. Lastly, the Installed Packages section allows you to manage the app packages on your PC.

 Here are the following things you can do using WingetUI:

### 1\. Browse List

 To browse the app list, click on the **Discover Packages** button on the top. WingetUI will list all the available packages with the source Winget. You will also see a counter indicating the total number of apps listed in the repository.

 Click on the search bar and type the name of the app package that you want to install on your PC. It will list all the available versions of the app package along with its package ID and version.

![Browse List in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/browse-list-in-wingetui.jpg)

### 2\. Install a Package

 To install a package, you will have to use the Discover Package tab:

1. After searching and locating the package, click on it to select it.
2. Then, right-click on it to open the context menu. Before starting the installation, you must configure the installation.
3. Select the **Package details** option from the context menu.  
![Install a Package in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-a-package-in-wingetui.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
4. Check the **source** of the package. Also, check the **image gallery** to get an idea of the app’s UI.
5. Move down to the **Installation options**. Keep the **Skip hash check** and **Interactive installation** unchecked. If you enable the interactive installation, you will have to manually perform the installation which can take longer.

1. Some apps cannot install on your PC without administrator rights. So, select the **Run as admin** checkbox.  
![Install a Package in WingetUI 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-a-package-in-wingetui-2.jpg)
2. You can also select a particular version of the app you are trying to install. Expand the **Version to install** dropdown list. You can select any version from here. Keep the **Ignore future updates for this package** option untouched.  
![Install a Package in WingetUI 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-a-package-in-wingetui-3.jpg)
3. Next, you can pick the **package architecture**: x64, x86, or arm65, depending upon your OS and CPU architecture.
4. Lastly, pick the **Scope** of the package installation. If you want to do a machine-wide install, pick the **local machine** option. Or pick the **Current user** if you want to install the app only for one user profile.  
![Install a Package in WingetUI 4](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-a-package-in-wingetui-4.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
5. Click on the **Install** button. UAC will pop up. Click on the **Yes** button.  
![Install a Package in WingetUI 5](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-a-package-in-wingetui-5.jpg)

 You will see the installation status at the button of the WingetUI window. Windows will produce a notification when the installation completes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
### 2\. Uninstall a Package

 Repeat the following steps to uninstall a package using WingetUI:

1. Switch to the **Installed Packages** tab. Right-click on the package you want to uninstall.
2. Select the **Uninstall as administrator** option.  
![unInstall a Package in WingetUI 5](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/uninstall-a-package-in-wingetui-5.jpg)
3. UAC will pop up. Click on the **Yes** button.
4. WingetUI will remove the installed package.

### 3\. Batch Install or Uninstall Packages

 Batch installation and uninstallation are a breeze with WingetUI. Here’s how to do it:

1. Individually select each package you want to install.
2. Then click on the **Install the selected packages** button on the top.  
![batch Install a Package in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/batch-install-a-package-in-wingetui.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
3. WingetUI will install these apps one by one.

 To batch uninstall packages, repeat the following steps:

1. Switch to the **Installed Packages** tab. Then, click and select all the packages you want to remove from your PC.
2. Click on the **Uninstall selected packages** button to remove the selected packages one by one.  
![batch unInstall Packages in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/batch-uninstall-packages-in-wingetui.jpg)

### 4\. Import Export Packages List

 You can create a custom package export list and store them in a JSON or Txt file. Here’s how:

1. Firstly, select all the packages you want to export either from the **Discover Packages** section or the **Installed Packages** section.
2. Then, click on the **Export selected packages to a file** option.  
![Export Packages List in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/export-packages-list-in-wingetui.jpg)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
3. Enter a **name** for the export file and save it to any location on your PC.  
![Export Packages List in WingetUI 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/export-packages-list-in-wingetui-2.jpg)
4. You can later import this file to another PC or even your PC using Winget or Winget UI.

 Repeat the following steps to import a Winget JSON file in WingetUI:

1. Switch to the **Discover Packages** section in the app.
2. Click on the **Import packages from a file** option.
3. **Browse** your PC for the Winget import file and select it. Click on the **Open** button.  
![import Packages List in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/import-packages-list-in-wingetui.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. WingetUI will automatically start installing all the packages listed in the import file.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
### 5\. Check Software Updates

 Switch to the **Software Updates** section. WingetUI will list all the packages which have an update available. To update a single app, right-click on it and select the **Update as administrator** option.

![Check Software Updates in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/check-software-updates-in-wingetui.jpg)

 If you want to update all packages at once, click on the **tick mark** icon to select all the packages. Then, click on the **Update selected packages** button.

![Check Software Updates in WingetUI 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/check-software-updates-in-wingetui-2.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->

## No More Terminal Woes

 WingetUi makes it easy for the average Joe to manage app packages on a Windows PC. There is a similar web-based GUI package manager called Winstall for batch-installing apps, but it only generates codes for it. You will have to manually run the commands in the Terminal. So, you can use WingetUI instead if you want zero interaction with Windows Terminal.

 If you have used Winget even once, you know that knowing the correct commands is of absolute importance if you want to avoid errors. But what if you had a GUI version of Winget? WingetUI is one such app that slaps a coat of UI on Winget. Curious? Let’s begin.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-2023s-fb-url-vault-securely-access-8-free-downloads-online/"><u>[New] 2024 Approved  2023'S FB URL Vault  Securely Access 8 Free Downloads Online</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-from-one-off-to-firm-follower-an-ethical-approach/"><u>[New] 2024 Approved  From One-Off to Firm Follower  An Ethical Approach</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-breaking-down-complex-gif-concepts-for-beginners/"><u>[New] Breaking Down Complex GIF Concepts for Beginners</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-crafting-engaging-youtube-end-credits/"><u>[New] In 2024, Crafting Engaging YouTube End Credits</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-golden-grounds-of-terrafirma-top-treasure-hunts/"><u>[New] In 2024, Golden Grounds of Terrafirma  Top Treasure Hunts</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-crafting-the-perfect-sonic-storytelling-on-social-media/"><u>[Updated] 2024 Approved  Crafting the Perfect Sonic Storytelling on Social Media</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-achieve-stunning-visual-impact-top-color-grading-tutorials/"><u>2024 Approved  Achieve Stunning Visual Impact - Top Color Grading Tutorials</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-improve-timestamp-accuracy-for-social-media-posts/"><u>2024 Approved  Improve Timestamp Accuracy for Social Media Posts</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-windows-security-patches/"><u>Demystifying Windows Security Patches</u></a></li>
<li><a href="https://driver-install.techidaily.com/drive-enhancement-lenovo-w11-drivers-for-windows-11/"><u>Drive Enhancement: Lenovo W11 Drivers for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-approach-nullifying-onedrive-presence-on-explore/"><u>Efficient Approach: Nullifying OneDrive Presence on Explore</u></a></li>
<li><a href="https://win11.techidaily.com/embracing-change-installing-and-utilizing-themes-from-the-ms-store/"><u>Embracing Change: Installing and Utilizing Themes From the MS Store</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-winning-video-coders-for-editing/"><u>Expert Tips: Winning Video Coders for Editing</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unresponsive-adobe-photoshop-in-windows-11-and-11/"><u>Fixing Unresponsive Adobe Photoshop in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/fundamental-concepts-in-windows-display-idleness/"><u>Fundamental Concepts in Windows Display Idleness</u></a></li>
<li><a href="https://win11.techidaily.com/hiding-or-showing-time-and-date-on-win-11-ui-bar/"><u>Hiding or Showing Time & Date on Win 11 UI Bar</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/hot-tips-for-business-indispensable-items-you-cant-afford-to-miss/"><u>Hot Tips for Business  Indispensable Items You Can't Afford To Miss</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-bypass-android-lock-screen-using-emergency-call-on-vivo-v30-pro-by-drfone-android/"><u>How to Bypass Android Lock Screen Using Emergency Call On Vivo V30 Pro?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-failed-vms-from-vmware-in-windows-11/"><u>How to Resolve Failed VMs From VMware in Windows 11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-iphone-x-passcode-without-itunes-without-knowing-passcode-by-drfone-ios/"><u>How to Unlock iPhone X Passcode without iTunes without Knowing Passcode?</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-craving-a-companion-top-discord-dating-spots/"><u>In 2024, Craving a Companion? Top Discord Dating Spots</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-oppo-reno-11f-5g-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Oppo Reno 11F 5G by Phone Number | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-humor-highlights-top-20-hilarious-tiktok-jokes-and-riddles/"><u>In 2024, Humor Highlights  Top 20 Hilarious TikTok Jokes and Riddles</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-windows-gaming-with-playnite-and-emulators/"><u>Maximizing Windows Gaming with Playnite and Emulators</u></a></li>
<li><a href="https://win11.techidaily.com/muting-file-explorer-tabs-in-windows-11-guide/"><u>Muting File Explorer Tabs in Windows 11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-and-resolving-active-directory-printer-failures/"><u>Navigating and Resolving Active Directory Printer Failures</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/online-video-scaling-service-for-2024/"><u>Online Video Scaling Service for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-windows-for-rapid-epic-games-access/"><u>Optimizing Windows for Rapid Epic Games Access</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-microsoft-store-access-blockades/"><u>Overcoming Microsoft Store Access Blockades</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-for-missing-file-updates-on-windows-error-code-0x80070003/"><u>Quick Fix for Missing File Updates on Windows (Error Code: 0X80070003)</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-strategies-for-error-262-in-roblox-games/"><u>Quick-Fix Strategies for Error 262 in Roblox Games</u></a></li>
<li><a href="https://win11.techidaily.com/revealing-windows-11s-system-tray-secrets/"><u>Revealing Windows 11'S System Tray Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-sticky-windows-credential-puzzle/"><u>Reversing Sticky Windows Credential Puzzle</u></a></li>
<li><a href="https://win11.techidaily.com/speeding-up-keys-in-windows-10-and-11-with-7-hacks/"><u>Speeding Up Keys in Windows 10 & 11 with 7 Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-storage-efficiently-identifying-large-disk-users/"><u>Streamline Your Storage: Efficiently Identifying Large Disk Users</u></a></li>
<li><a href="https://win11.techidaily.com/tailored-shortcuts-for-rapid-insertion-of-pre-defined-text-snippets/"><u>Tailored Shortcuts for Rapid Insertion of Pre-Defined Text Snippets</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-windows-11-interface-for-maximum-comfort/"><u>Tailoring Your Windows 11 Interface for Maximum Comfort</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-guide-to-local-users-and-groups-on-win1110/"><u>The Complete Guide to Local Users and Groups on WIN11/10</u></a></li>
<li><a href="https://apple-account.techidaily.com/top-notch-solutions-for-disabled-apple-id-from-iphone-12-mini-making-it-possible-by-drfone-ios/"><u>Top-Notch Solutions for Disabled Apple ID From iPhone 12 mini Making It Possible</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unseen-drives-in-windows/"><u>Troubleshooting: Unseen Drives in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-rectifying-vac-refusal-on-windows/"><u>Understanding and Rectifying VAC Refusal on Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/unlocking-creative-potential-instagram-collage-simplified/"><u>Unlocking Creative Potential  Instagram Collage Simplified</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-microsofts-copilot-key-insights-for-windows-11-users/"><u>Unlocking Microsoft's Copilot Key: Insights for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-successful-oculus-installer-on-ws11ws10/"><u>Unlocking Successful Oculus Installer on WS11/WS10</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-the-mystery-of-windows-error-0xca00a009/"><u>Unpacking the Mystery of Windows Error 0xCA00A009</u></a></li>
<li><a href="https://win11.techidaily.com/win11s-control-panel-customizing-made-simple/"><u>Win11's Control Panel: Customizing Made Simple</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-custom-shortcut-for-safe-hardware-disconnect/"><u>Windows 11: Custom Shortcut for Safe Hardware Disconnect</u></a></li>
<li><a href="https://win11.techidaily.com/windows-users-explore-these-8-great-video-editors/"><u>Windows Users, Explore These 8 Great Video Editors</u></a></li>
<li><a href="https://win11.techidaily.com/winstall-workflows-for-smooth-windows-11-app-installation/"><u>Winstall Workflows for Smooth Windows 11 App Installation</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>