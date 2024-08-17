---
title: Techniques to Mend Failed JVM Initialization in WINDOWS
date: 2024-08-16T00:16:33.106Z
updated: 2024-08-17T00:16:33.106Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques to Mend Failed JVM Initialization in WINDOWS
excerpt: This Article Describes Techniques to Mend Failed JVM Initialization in WINDOWS
keywords: Fix JVM Init Windows,JVM Startup Errors,Java Runtime Repair,JVM Launch Issue Win,Resolve JVM Failure,Correcting JVM Initialization,Java VM Correction Methods
thumbnail: https://thmb.techidaily.com/d02ecec5426e8e1f2da5e128e095f9718e5fc3c1177707ff5abe66e708ea725f.jpg
---

## Techniques to Mend Failed JVM Initialization in WINDOWS

 Your Windows 11 computer may require the latest version of Java installed for some applications to work. However, sometimes some Java apps may abruptly crash with the error Could not create the Java virtual machine.

 This error is often a case of insufficient memory allocation for Java apps. Additionally, check for permission issues and glitches with the Java release itself. If you are using it on your work computer for programming purposes, check if you have the correct version of Java IDE installed.

 Here we show you a few troubleshooting steps to fix the could not create the java virtual machine error on Windows.

## 1\. Verify Your Java Installation

![verify java installation command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/verify-java-intallation-command-prompt.jpg)

 Verifying your Java installation can help you determine issues with the release itself. You can use the**java -version** command in Command Prompt to check the current version of Java installed along with the date of installation.

To check the Java version installed on Windows:

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command Prompt** and select**Run as administrator** .
3. In the Command Prompt window, type the following command and press**Enter** :  
`java -version`
4. The output will list the JDK version installed on your computer and the installation date.
5. If you have recently installed an update, check if the information checks out. If not, try to install the latest version available from the [Java website](https://www.oracle.com/in/java/technologies/downloads/) .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## 2\. End the Java Process in Task Manager

![end java process task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/end-java-process-task-manager.jpg)

 If the error is triggered when installing Java, check if a Java process is running in the background. You can use Task Manager to find and end background processes that may prevent you from installing the Java Runtime Environment or the development kit.

1. Press**Win + X** to open the**WinX menu** and select**Task Manager** .
2. In Task Manager, open the**Processes** tab and locate instances of**Java Virtual Machine** .
3. Select and click**End Task** to close the process.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
## 3\. Run Java as an Administrator

 Insufficient permission can prevent some Java apps from running on your computer. To fix the problem, run Java with administrative privilege. To run Java as an administrator on Windows, right-click on**Java.exe** and select**Run as administrator** .

 Alternatively, you can set the Java.exe to always run as administrator. This way, you don’t need to run Java with administrative privileges each time you want to launch it. Check out [how to always run a program as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) for more information.

## 4\. Increase the System Memory for Java

 A common reason for the Could not create the Java virtual machine error is insufficient memory allocation, also known as Java heaps. Insufficient memory allocation can throttle the performance or cause the app to crash.

 To remedy this issue, you can increase the Java heap size. You can do this by modifying the**Runtime Parameters** from**Java Runtime Environment Settings** or changing the**\_JAVA\_OPTIONS** variable value to your preference.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
### How to Increase Java Heap Size by Manually Modifying Variables

To change Java heap size by modifying the \_JAVA\_OPTIONS variable:

1. Press the**Win** key and type**environmental variables** .  
![edit the system environmental variables](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/edit-the-system-environmental-variables.jpg)
2. Next, select**Edit the system environment variables** to open**System Properties** .
3. In the**Advanced** tab, click**Environment Variables** .  
![The Environment Variables button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/environment-variables-button.jpg)
4. In the**System Variables** section, click**New** . It is important to select the correct section.  
![Windows new system variable java options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-new-system-variable-java-options.jpg)
5. Type**\-JAVA\_OPTIONS** in the**Variable name** field.
6. Next, type**\-Xmx512M** in the**Variable value** field. Here,**\-Xmx512M** defines the amount of memory you want to allocate. In this case, it is**512MB** of system memory.
7. Click**OK** , and**OK** once more to save the changes.

 Next, launch the app that shows the error and check if the error is resolved. If not, open**Environmental Variables** again. Select the -**JAVA\_OPTIONS** variable and click**Edit** . In the**Value data** field, type**\-Xmx1024M** to increase the memory size to 1**024 MB (1GB)** . Click**OK** and check for any improvements.

### How to Increase Java Heap Size Using the Java Control Panel

 You can also modify the default Java heap size from Java Runtime Environment Settings. Here’s how to do it.

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open Control Panel.
3. Next, click on**Programs** and click on**Java (32-bit)** .  
![windows control panel Java 32 bit programs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-control-panel-java-32-bit-programs.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
4. In the**Java Control Panel** dialog, open the**Java** tab.
5. Click the**View** button.  
![java control panel java tab view](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/java-control-panel-java-tab-view.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
<!-- affiliate ads end -->
6. Double-click on the**Runtime Parameters** column and type**\-Xmx512m** to assign 512 MB memory for the Java apps.  
![Java runtime environment settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/java-runtime-environment-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
7. Click**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Uninstall and Reinstall Java

![uninstall java Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/uninstall-java.jpg)

 If the issue persists, a reinstall may be necessary. You can uninstall and reinstall Java to fix any issues with the release. These issues may remain even if you install a newer version. To fix the issue, uninstall Java using the Java uninstaller and then reinstall the latest version available.

To clean install Java:

1. Go to the [Java Uninstall Tool page](https://www.java.com/en/download/uninstalltool.jsp) and download the uninstaller.
2. Run the executable and click**Agree** .
3. Select all the versions of Java detected by the tool and click**Next** .
4. Click**Yes** and wait as the uninstaller removes Java from your computer. Click**Close** .
5. Restart your computer to apply the changes.
6. Next, go to the [Java Downloads page](https://www.java.com/en/download/manual.jsp/) and download the latest version available for your operating system. Make sure to download the correct version (32-bit/64-bit), depending on the system architecture.
7. Run the installer and click**Install** . Follow the on-screen instructions to complete the installation and restart your computer.

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Install Java in a WindowsClean Boot State

 In Clean Boot State, Windows starts with only essential Microsoft services and apps. It’s a troubleshooting method to determine and find third-party app conflicts causing system errors. If you continue to see the error when installing Java,[start your Windows computer in a clean boot state](https://www.makeuseof.com/clean-boot-windows-11/) and try installing it again.

## Fixing the "Could Not Create the Java Virtual Machine" Error on Windows

 Insufficient Java heap size is what often triggers the Java virtual machine error. To fix the issue, modify the default heap size to be able to run Java apps without any problems.

 If the error occurs when installing Java, try to install the app in a clean boot state. Installing pending Windows updates can also help fix compatibility issues with the release.


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
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-capture-the-action-easy-steps-for-overwatch-players/"><u>[Updated] 2024 Approved  Capture the Action  Easy Steps for Overwatch Players</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-midgard-alliance-the-ragnarok-saga-begins/"><u>[Updated] In 2024, Midgard Alliance  The Ragnarök Saga Begins</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-pictomixer-dynamic-media-player-for-macos-for-2024/"><u>[Updated] PictoMixer  Dynamic Media Player for macOS for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-the-ultimate-handbook-for-swapping-music-libraries/"><u>[Updated] The Ultimate Handbook for Swapping Music Libraries</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-screen-pleasures-for-all-top-10-free-movies-available-on-youtube/"><u>2024 Approved  Screen Pleasures for All – Top 10 Free Movies Available on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/5-apps-that-elevate-your-desktop-writing-game/"><u>5 Apps That Elevate Your Desktop Writing Game</u></a></li>
<li><a href="https://win11.techidaily.com/6-disappearing-windows-traits-explained/"><u>6 Disappearing Windows Traits Explained</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-check-which-intel-processor-generation-you-have-on-windows/"><u>8 Ways to Check Which Intel Processor Generation You Have on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-comparative-study-of-cloud-and-physical-methods-for-windows-setup/"><u>A Comparative Study of Cloud & Physical Methods for Windows Setup</u></a></li>
<li><a href="https://win11.techidaily.com/a-new-era-for-windows-users-understanding-copilot-key-impact/"><u>A New Era for Windows Users: Understanding Copilot Key Impact</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-keyboard-skills-using-windows-powertoys/"><u>Accelerate Keyboard Skills Using Windows PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/accurate-guide-transforming-heic-images-into-jpeg-format-with-w11-ease/"><u>Accurate Guide: Transforming HEIC Images Into JPEG Format with W11 Ease</u></a></li>
<li><a href="https://win11.techidaily.com/activate-dark-theme-for-windows-calc/"><u>Activate Dark Theme for Windows Calc</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-media-player-for-a-streamlined-start/"><u>Activating Windows Media Player for a Streamlined Start</u></a></li>
<li><a href="https://win11.techidaily.com/activatingdeactivating-windows-11s-anti-phishing-filter/"><u>Activating/Deactivating Windows 11'S Anti-Phishing Filter</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-cannot-access-errors-for-files-in-win1011/"><u>Addressing 'Cannot Access' Errors for Files in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-device-failure-notifications-in-w10w11-pcs/"><u>Addressing 'Device Failure' Notifications in W10/W11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-share-glitches-with-nvidia/"><u>Addressing Windows 11 Share Glitches with NVIDIA</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-windows-filters-enable-or-disable-safeguard/"><u>Adjusting Windows Filters: Enable or Disable SafeGuard</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-file-system-interactions-a-step-bystep-guide/"><u>Advanced File System Interactions: A Step-Bystep Guide</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-imaging-separating-subjects-from-surroundings/"><u>Advanced Imaging: Separating Subjects From Surroundings</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tips-for-seamless-windows-partition-merging/"><u>Advanced Tips for Seamless Windows Partition Merging</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tricks-for-pinpointing-lost-windows-keys/"><u>Advanced Tricks for Pinpointing Lost Windows Keys</u></a></li>
<li><a href="https://location-fake.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Apple iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-time-honored-directx-experiences-through-dxvk/"><u>Augmenting Time-Honored DirectX Experiences Through DXVK</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-not-working-mishaps-on-your-devices-windows-apps/"><u>Avoiding 'Not Working' Mishaps on Your Device’s Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-clutter-smart-note-management-for-windows/"><u>Avoiding Clutter: Smart Note Management for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-rapid-clicks-turn-off-mouse-accel-in-win-11/"><u>Avoiding Rapid Clicks: Turn Off Mouse Accel in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-windows-11-crashes-interrupt-fixation/"><u>Avoiding Windows 11 Crashes: Interrupt Fixation</u></a></li>
<li><a href="https://win11.techidaily.com/awaken-your-windows-11-to-create-stunning-ai-images-with-paint-tool-sai/"><u>Awaken Your Windows 11 to Create Stunning AI Images with Paint Tool SAI</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-defender-tracings-in-windows-1011-environments/"><u>Banishing Defender Tracings in Windows 10/11 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/beneath-the-surface-tools-for-win-1011s-dropdowns/"><u>Beneath-the-Surface Tools for Win 10/11'S Dropdowns</u></a></li>
<li><a href="https://win11.techidaily.com/bigger-capacity-but-lagging-in-little-pcs-mp60/"><u>Bigger Capacity but Lagging in Little PCs (MP60)</u></a></li>
<li><a href="https://win11.techidaily.com/bitshield-busted-but-wait-a-beat-before-switch/"><u>BitShield Busted, But Wait a Beat Before Switch</u></a></li>
<li><a href="https://win11.techidaily.com/blending-elegance-with-utility-the-asus-vivobook-s-15-edition/"><u>Blending Elegance with Utility: The ASUS Vivobook S 15 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-gameplay-flush-and-optimize-steam-dns-cache/"><u>Boost Your Gameplay: Flush and Optimize Steam DNS Cache</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-top-7-tips-for-mastering-windows-11-49/"><u>Boosting Productivity: Top 7 Tips for Mastering Windows 11 (49)</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-the-barriers-to-customizing-windows-11-apps/"><u>Breaking Down the Barriers to Customizing Windows 11 Apps</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-itel-p55-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Itel P55 to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/crafting-compelling-movie-previews/"><u>Crafting Compelling Movie Previews</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-samsung-galaxy-a54-5g-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Samsung Galaxy A54 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719351823246-fresh-start-for-stuck-chrome-try-these-remedies-for-win11/"><u>Fresh Start for Stuck Chrome: Try These Remedies For Win11</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-clear-iphones-network-configuration-a-step-by-step-guide/"><u>How to Clear iPhone's Network Configuration: A Step-by-Step Guide</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-a-locked-oppo-a79-5g-phone-by-drfone-android/"><u>How to Reset a Locked Oppo A79 5G Phone</u></a></li>
<li><a href="https://techtrends.techidaily.com/introducing-apples-newest-macbook-a-look-at-the-latest-upgrade/"><u>Introducing Apple's Newest MacBook: A Look at the Latest Upgrade</u></a></li>
<li><a href="https://win11.techidaily.com/1719367447353-multiplying-malware-defenses-think-again-windows/"><u>Multiplying Malware Defenses? Think Again, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719374180426-navigate-through-faulty-shift-in-windows/"><u>Navigate Through Faulty Shift in Windows.</u></a></li>
<li><a href="https://win11.techidaily.com/1719367274054-overcoming-snip-and-sketchs-screen-shot-limitations-4-essential-fixes/"><u>Overcoming Snip & Sketch's Screen Shot Limitations: 4 Essential Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/1719358882925-solve-your-windows-dilemma-help-strategies-revealed/"><u>Solve Your Windows Dilemma: Help Strategies Revealed</u></a></li>
</ul></div>
