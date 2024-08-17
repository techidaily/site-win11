---
title: Simple Steps to Acquire & Implement Microsoft Store's Application Bundles
date: 2024-08-16T00:00:59.037Z
updated: 2024-08-17T00:00:59.037Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Simple Steps to Acquire & Implement Microsoft Store's Application Bundles
excerpt: This Article Describes Simple Steps to Acquire & Implement Microsoft Store's Application Bundles
keywords: Microsoft App Store,Bundle Adoption,App Installation,Microsoft Stores,Implementation Strategies,App Bundles Process,Digital Distribution Steps
thumbnail: https://thmb.techidaily.com/876b4cf01691e6a76beb54576565375ccfec6aaf58375585e8d7cab9fd27ade4.jpg
---

## Simple Steps to Acquire & Implement Microsoft Store's Application Bundles

 The new Microsoft Store on Windows 11 works great for the most part. But, for the times it doesn’t, Windows lets you sideload Microsoft Store apps in appx, appxBundle, msixbundle app files on your computer.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 You can download the appx or msix package from the app developer’s website, GitHub, or directly from the Microsoft Store server using third-party utilities. Here we show how to download appx/appxbundle and msixbundle package files from Microsoft Store and install them on your Windows computer.

## 1\. How to Download Appx/AppxBundle Files Using Adguard

![adguard msixbundle download](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/adguard-msixbundle-download.jpg)

 Adguard is a third-party web service and an online link generator for Microsoft Store. It makes it easy to download appx and appxbundle files from the Microsoft Store for sideloading them on your Windows computer.

To download appx, appxbundle or msixbundle using Adguard:

1. Go to [Microsoft Store](https://apps.microsoft.com/store/apps) on your browser, search, and open the app you want to download.
2. Copy the app URL, including the product ID, from the address bar. For example, the app URL for the Xbox app on Microsoft Store will look like this:  
`https://apps.microsoft.com/store/detail/xbox/9MV0B5HZVK9Z`
3. Next, go to the [Adguard page](https://store.rg-adguard.net/) and paste the app URL.
4. On the right side, click the**RP** drop-down and select**Retail** .
5. Click the**Check mark** button to generate a direct download link. It will populate the page with msixbundle, appx or appxbundle, and other associated files.
6. You only need to download the full app package. The rest are app dependencies that you don’t need to download in most cases. For example, in this instance, we only need to download**msixbundle** , which is also the largest file in the list.
7. Make sure to check the architecture compatibility (**x64, x86, Arm**) for the files depending on your system architecture.
8. Next, click on the msixbudle link to download. Microsoft Edge may sometimes block the download as not secure. You can use alternative browsers like Google Chrome and Firefox to compelete the download.

## 2\. Generate Microsoft Store Apps Direct Download Links Using Fiddler

 Fiddler Classic is a network tracking and monitoring tool to log HTTP(s) traffic from web browsers and installed apps. You can use this app to track Microsoft Store network when downloading an app to your computer. Then use the URL as a direct download link to download appx, msixbundle, and appxbundle files using any web browser.

To generate a Microsoft Store app downloading link using Fiddler:

1. Download and install the [Fidler Classic app](https://www.telerik.com/download/fiddler) . You’ll need to enter your email and territory to download the app.
2. Open**Fiddler** , and click the**WinConfig** button in the top left corner. Click**Yes** if prompted by User Account Control.  
![Fiddler_WinConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/fiddler_winconfig.jpg)
3. In the**AppContainer Lookback** **Exception Utility** dialog, scroll down and check the**Microsoft Store** box.  
![Fiddler app container loopback exception utlility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/fiddler-app-container-loopback-exception-utlility.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
4. Click on**Save Changes.**
5. Next, click on**Edit** and go to**Remove** , and select**All Sessions** . Alternatively, press**Ctrl + X** to do the same.  
![Filddler remove all sessions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/filddler-remove-all-sessions.jpg)

1. Next, launch**Microsoft Store,** search for the app you want to download, and click**Install** . Wait for the app to download and install completely. Fiddler will start capturing the traffic as the necessary files for the app download and install.
2. Once the download is complete, open the**Fiddler** app and press**Ctrl + F** to open**Find** .
3. Type**appx** in the**Find** dialog. Leave the rest options as default and click**Find Sessions** . It will scan through the recently captured Microsoft Store traffic and highlight the matching entries in yellow.  
![fiddler find session](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/fiddler-find-session.jpg)
4. If no entries are highlighted, open**Find (Ctrl+F)** and type**msixbundle, appx** or**appxbundle** in the**Find** field, and click on**Find Sessions** .  
![Fiddler copy just url](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/fiddler-copy-just-url.jpg)
<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Right-click on any entry highlighted in yellow and select**Copy > Just URL.**
6. Open**Google Chrome** or**Firefox** and paste the copied URL in the address bar. Press**Enter** and click**Save** to download the file. On Microsoft Edge, you may face a connection is not secure error. If so, switch to a different browser to complete the download.

 To install the downloaded appx, appxbundle, or msixbundle file, you can use PowerShell or the App Installer.

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Install Appx, Appxbundle and Msixbundle Apps

 In an ideal situation, you can double-click on the app file package to install it on your Windows computer. However, if that does not work, you can sideload the apps using PowerShell and the official App Installer. Here are the three ways to install the appxbundle and msixbundle file packages on Windows 10 and 11.

### 1\. Install Appx/Appxbundle/Msixbundle App By Running the File

![install appxbundle double click](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/install-appxbundle-double-click.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->

 You can install some appx, appxbundle, and msixbundle files like you would do with any .exe file. Follow these steps to sideload and install Universal Windows Platform apps.

1. Locate the saved app package in the**Downloads** folder.
2. Next, double-click on the file to open the installation wizard and click on the**Install** button to install the software.

 Unfortunately, this installation method does not work always. You are likely to run into errors like [this app package is not support installation](https://www.makeuseof.com/app-package-not-supported-installation-app-installer/) . What you can do instead is try to install the app using the App Installer app or PowerShell. You can use PowerShell to install apps not signed by Microsoft Store.

### 2\. Install Appx, Appxbundle, and Msixbundle using App Installer

![microsoft app installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/microsoft-app-installer.jpg)
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Microsoft offers an official App Installer to sideload Windows 10 apps. However, this app installer also works on Windows 11\. If you encounter an error when sideloading apps using the convention double-click method, the App Installer will do the trick.

 Make sure to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before installing App Installer. Once installed, you may not be able to uninstall the app. And it can also fiddle with Windows PowerShell’s ability to sideload apps.

To install App Installer:

1. Launch**Microsoft Store** and search for the app installer.
2. Click on**App** **Installer** from the search results. The description reads the app lets you sideload Windows 10 apps.
3. Click on Install and wait for it to complete the process.
4. Once installed, click on the appx, appxbundle, or msixbundle file to open it in**App Installer.**
5. Click**Install** and wait for the app installation to finish.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 3\. Install Appx, Msixbundle, and Appxbundle Using PowerShell

![install msixbundle sideload powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/install-msixbundle-sideload-powershell.jpg)

 You can use Windows PowerShell to sideload Microsoft Store app on Windows. This is an efficient way to sideload apps on multiple computers or when you get an error while running the msixbundle or other package files.

To install appx, msixbudnle, and appxbundle apps using PowerShell:

1. Press the**Win** key and**powershell** .
2. Right-click on**Windows PowerShell** and select**Run as administrator.**
3. Next, type the following command and press**Enter** to install the app:  
`Add-AppxPackage -Path $AppFilePath`
4. In the above command, replace AppFilePath with the appx, msixbundle, or appxbundle file path. To get the file path, right-click on the file and select**Copy as path.**
5. For example, if you want to install msixbundle for Files Apps, the full command will be something like this:  
`Add-AppxPackage -Path $C:\Users\Username\Downloads\Files.Package.msixbundle`
6. PowerShell will show a progress bar to indicate the installation. Once done, you can launch the app from the Start menu.

 In addition, if you want to install a non-Microsoft Store app file package, you may also need to enable Developer Mode to install UWP apps from third-party sources.

To enable Developer Mode on Windows 11

![enable developer mode windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-developer-mode-windows-11.jpg)

1. Press**Win + I** to open**Settings** .
2. Open the**Privacy & Security** tab in the left pane,
3. Click on**For Developers** and then toggle the switch for**Developer Mode.**

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## Download and Install Appx, Appxbundle, and Msixbundle from Microsoft Store on Windows

 Thanks to the built-in sideload support on Windows, you can easily install Microsoft Store and non-store apps on your computer. Adguard and Fiddler handle the important aspect of allowing to download app package files for sideload.

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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-cubic-cottages-for-newcomers-to-mc-world/"><u>[New] 2024 Approved  Cubic Cottages for Newcomers to MC World</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-perfect-pc-playthrough-captures-6-tips-and-tricks/"><u>[New] In 2024, Perfect PC Playthrough Captures  6 Tips and Tricks</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-snap-into-position-handhran-balancing-tricks/"><u>[New] In 2024, Snap Into Position  Handhran Balancing Tricks</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-the-ultimate-metrics-guide-to-monetize-and-mobilize-youtube-audiences/"><u>[New] In 2024, The Ultimate Metrics Guide to Monetize and Mobilize YouTube Audiences</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-masterful-gameplay-transmission-with-obs-studio-for-2024/"><u>[Updated] Masterful Gameplay Transmission with OBS Studio for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/10-ways-to-fix-steam-not-detecting-your-controller-on-windows/"><u>10 Ways to Fix Steam Not Detecting Your Controller on Windows</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-free-10-high-quality-passport-photos-available-here/"><u>2024 Approved  Free 10 High-Quality Passport Photos Available Here</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-innovative-techniques-for-a-dynamic-win11-display/"><u>2024 Approved  Innovative Techniques for a Dynamic Win11 Display</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-itel-a60-drfone-by-drfone-virtual-android/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Itel A60 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/audio-amplifiers-4-essential-tools-that-push-pc-sounds-past-100/"><u>Audio Amplifiers: 4 Essential Tools that Push PC Sounds Past 100%%</u></a></li>
<li><a href="https://win11.techidaily.com/augment-windows-taskbar-with-numeric-key-and-caps-indicator-symbols/"><u>Augment Windows Taskbar with Numeric Key & Caps Indicator Symbols</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-windows-ui-cli-features-for-taskmgr-windowed-console/"><u>Augmenting Windows UI: CLI Features for TaskMgr Windowed Console</u></a></li>
<li><a href="https://win11.techidaily.com/cease-alerts-for-unrequested-system-recommendations/"><u>Cease Alerts for Unrequested System Recommendations</u></a></li>
<li><a href="https://win11.techidaily.com/creating-a-personalized-calendar-experience-with-windows-outlook/"><u>Creating a Personalized Calendar Experience with Windows Outlook</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/elevating-perspectives-unboxing-and-testing-the-groundbreaking/"><u>Elevating Perspectives: Unboxing and Testing the Groundbreaking</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-null-associated-app-error-on-windows-systems/"><u>Fixing Null Associated App Error on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-iphone-images-problem-in-windows-environments/"><u>How to Rectify iPhone Images Problem in Windows Environments</u></a></li>
<li><a href="https://buynow-help.techidaily.com/immerse-yourself-in-crystal-clear-viewing-with-the-lg-65-4k-oled-smart-tv-an-in-depth-review-by-tech-savvies/"><u>Immerse Yourself in Crystal-Clear Viewing with The LG 65 4K OLED Smart TV: An In-Depth Review by Tech Savvies.</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-audiovisual-fusion-incorporating-songs-in-ig-media/"><u>In 2024, Audiovisual Fusion  Incorporating Songs in IG Media</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-change-location-on-yik-yak-for-your-oppo-a59-5g-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>In 2024, Change Location on Yik Yak For your Oppo A59 5G to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-edit-and-send-fake-location-on-telegram-for-your-apple-iphone-13-mini-in-3-ways-drfone-by-drfone-virtual-ios/"><u>In 2024, Edit and Send Fake Location on Telegram For your Apple iPhone 13 mini in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-honor-magic-6-mirror-screen-to-pc-drfone-by-drfone-android/"><u>In 2024, How Honor Magic 6 Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-the-power-of-two-networks-a-window-guide-to-dual-connectivity/"><u>Leveraging the Power of Two Networks: A Window Guide to Dual Connectivity</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-cannot-open-file-problems-in-win1110/"><u>Mastering the Art of Fixing 'Cannot Open File' Problems in Win11/10</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-android-studio-on-windows-for-faster-compilation/"><u>Optimizing Android Studio on Windows for Faster Compilation</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-inability-to-link-with-nvidia-experience-on-pcs/"><u>Overcoming the Inability to Link with NVIDIA Experience on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/pinpointing-windows-model-chronology/"><u>Pinpointing Windows Model Chronology</u></a></li>
<li><a href="https://win11.techidaily.com/protecting-windows-safescreen-state-against-user-tweaks/"><u>Protecting Windows SafeScreen State Against User Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/rewind-records-key-tools-to-modify-files-creation-dates/"><u>Rewind Records: Key Tools to Modify File's Creation Dates</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-11s-camera-issue-fixing-a00f425d-error/"><u>Tackling Windows 11'S Camera Issue: Fixing A00F425D Error</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-more-disk-room-in-windows-here-are-the-7-best-aids/"><u>Unleash More Disk Room in Windows - Here Are the 7 Best Aids</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-extracting-sids-from-users-on-windows-11/"><u>Unraveling the Mystery: Extracting SIDs From Users on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/win11s-dns-cache-how-to-clear-and-maintain-efficiency/"><u>Win11's DNS Cache: How to Clear and Maintain Efficiency</u></a></li>
</ul></div>
