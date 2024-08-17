---
title: "Unlock the Code: Navigating Through Lost Windows 11/10 Patches"
date: 2024-08-16T00:30:54.074Z
updated: 2024-08-17T00:30:54.074Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlock the Code: Navigating Through Lost Windows 11/10 Patches"
excerpt: "This Article Describes Unlock the Code: Navigating Through Lost Windows 11/10 Patches"
keywords: Win XP Fix Guide,WIN11 Patch Steps,Win10 Update Tips,LostWindows Support,Windows Patch Hacks,System Recovery Tools,OS Repaired Tutorials
thumbnail: https://thmb.techidaily.com/6ea42b82e55f6c668ff7a393a7539803912a1c23ef44a3dc870ec2d24d91150f.jpg
---

## Unlock the Code: Navigating Through Lost Windows 11/10 Patches

### Quick Links

* [What Is a Windows Product Key?](#what-is-a-windows-product-key)
* [How to Find Your Windows 11/10 Product Key Using the Command Prompt](#how-to-find-your-windows-11-10-product-key-using-the-command-prompt)
* [How to Recover a Windows 11/10 Product Key Using PowerShell](#how-to-recover-a-windows-11-10-product-key-using-powershell)
* [Use a Third-Party Tool to Find Your Windows 11/10 Product Key](#use-a-third-party-tool-to-find-your-windows-11-10-product-key)
* [Check Your Purchase Receipt or Email](#check-your-purchase-receipt-or-email)
* [Contact Microsoft Support](#contact-microsoft-support)

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
### Key Takeaways

* Find your Windows 10/11 product key using the Command Prompt by typing a specific command.
* Alternatively, you can use PowerShell to retrieve your Windows 10/11 product key.
* Third-party tools like ShowKeyPlus can also retrieve your Windows activation code.

 Knowing your Windows product key is often necessary to fix Windows activation issues. Even though the OEM or retail license key is tied to your device's hardware, you can easily find your Windows 10 or 11 product key using the Command Prompt and reactivate Windows.

## What Is a Windows Product Key?

 A [Windows product key](https://www.makeuseof.com/windows-product-keys-guide/) is a 25-character code you use to activate your copy of Windows. Since Windows 11 and 10 use a digital license method for activation, you don’t need to manually enter the key each time you upgrade or [clean install Windows](https://www.makeuseof.com/important-things-remember-clean-installing-windows/).

 However, if you significantly change your device's hardware, Windows won't be able to detect the license tied to your device. A manual activation may also be necessary if you run into a Windows 11 activation error.

 To activate Windows in these cases, you'll need to enter the 25-character product key. As such, if you don't know your product key, we'll explain how to extract it from your Windows 11 or 10 system.

 Note that each edition of Windows uses its own unique product key. For example, if you have a license for the Windows 11/10 Home edition, you cannot use it to activate Windows Pro or other editions.

## 1\. How to Find Your Windows 11/10 Product Key Using the Command Prompt

![Command Prompt window running the wmic path SoftwareLicensingService get OA3xOriginalProductKey command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/command-prompt-windows-11-product-key.png)

 You can use the ever-trustworthy Command Prompt to find the product key for your copy of Windows. Here’s how to do it:

1. Press **Win + S** on your keyboard to openthe search field on the Start menu.
2. Type **cmd** and then click on **Run as administrator** from the search result.
3. In the Command Prompt window, type the following command and hit **Enter** to execute:  
`wmic path SoftwareLicensingService get OA3xOriginalProductKey`
4. Your original product key will be displayed on the screen. Copy and save the key in a safe location, such as your Dropbox or Google Drive account, for future use.

 Once your copy of Windows is activated, it's a good idea to [link your Windows product key to a Microsoft account](https://www.makeuseof.com/link-windows-product-key-microsoft-account/). Doing so will ease the activation process if you need to do it again.

## 2\. How to Recover a Windows 11/10 Product Key Using PowerShell

![PowerShell console running the command to find Windows 11 and 10 product key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/powershell-windows-11-product-key.png)

 You also use PowerShell and the WMI cmdlet to find and display your Windows 11 or 10 product key. Here’s how to do this:

1. Press the **Window** key and type **powershell**.
2. Right-click on **PowerShell** and select **Run as administrator.**
3. In the PowerShell window, copy and paste, or type, the following command and press Enter:  
`(Get-WmiObject -query 'select * from SoftwareLicensingService').OA3xOriginalProductKey`
4. The command may take a few seconds to execute. Upon successful execution, it will display the product key for your copy of Windows.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Use a Third-Party Tool to Find Your Windows 11/10 Product Key

![showkeyplus tool showing the retrieved Windows product information.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/showkeyplus-tool-find-product-key.png)
<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you would rather avoid the hassle of typing commands or running scripts, third-party tools like ShowKeyPlus can help you find the Windows activation code with a few clicks. You can download this app from the Microsoft Store to retrieve Windows product key information. Here’s how:

1. Visit the Microsoft Store page for [ShowKeyPlus](https://apps.microsoft.com/detail/9PKVZCPRX9NV) and install the app.
2. Launch ShowKeyPlus, which will display information about the Windows license installed on your PC.
3. Click the **Save** button to save the product details in a text file.

 Also, you can use ShowKeyPlus to check your specific Windows edition using the product key and retrieve a key from a backup.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
## 4\. Check Your Purchase Receipt or Email

 If you bought a Windows license key from an online retailer like Amazon, you likely received the info via email. Use keywords like "Windows license", "Windows product", and "Windows activation" to search for the confirmation mail that you received. Or check the **Orders** section of your account with that online retailer to find information on how to retrieve the key, or how the key was initially delivered.

 As another option, look for physical stickers on your computer with information related to your computer hardware and software configuration. These may also include the Windows product key or other necessary details to help you locate it.

## 5\. Contact Microsoft Support

 If all else fails, try contacting Microsoft support for assistance. You can ask for a callback using the **Get Help** app on your computer:

1. Press **Win + I** to open **Settings**.  
![Windows 11 Settings app showing the activation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-settings-app-activation-shown.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. Open the **System** tab and click on **Activation.**  
![Windows 11 Settings app activation screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-settings-app-activation-screen.jpg)
3. Click **Get Help.**  
![Windows 11 get help app showing the Contact Support option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-get-help-app-contact-support-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
4. Click **Contact Support** and then choose the product.  
![Windows 11 get help choose products and services screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-get-help-choose-products-and-services-screen.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
5. Click on **Provide your phone number and the support agent will call you** and follow on-screen instructions.

 In Windows 10 and 11, Microsoft has streamlined the license activation process. Irrespective of how you got your license, once activated, the product key is tied to your system hardware. Whether you upgrade to the next version or clean install the OS, Windows should automatically detect and verify the ownership.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-playlists-that-dominate-spotify/"><u>[New] 2024 Approved  Playlists That Dominate Spotify</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-your-step-by-step-guide-to-successful-lol-streaming-for-2024/"><u>[New] Your Step-by-Step Guide to Successful LOL Streaming for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-channel-compendium-best-of-the-bunch-historical-youtubes-for-study-for-2024/"><u>[Updated] Channel Compendium  Best of the Bunch - Historical YouTubes For Study for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-excellent-video-chat-solutions-for-mobile-and-desktops/"><u>[Updated] Excellent Video Chat Solutions for Mobile & Desktops</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-screen-capture-mastery-a-closer-look-at-recmeister-tech/"><u>[Updated] Screen Capture Mastery  A Closer Look at Recmeister Tech</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-keyword-optimization-for-higher-youtube-viewership/"><u>2024 Approved  Keyword Optimization for Higher YouTube Viewership</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-pioneering-editing-snapseed-for-the-newcomer/"><u>2024 Approved  Pioneering Editing  Snapseed for the Newcomer</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-pushing-creative-boundaries-utilizing-advanced-techniques-for-luts-in-after-effects/"><u>2024 Approved  Pushing Creative Boundaries  Utilizing Advanced Techniques for LUTs in After Effects</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-the-ace-screen-recorders-list-for-the-winning-setup/"><u>2024 Approved  The Ace Screen Recorders List - For the Winning Setup</u></a></li>
<li><a href="https://win11.techidaily.com/4-early-stages-of-pc-failure-know-when-to-act/"><u>4 Early Stages of PC Failure, Know When To Act</u></a></li>
<li><a href="https://win11.techidaily.com/6-risks-of-using-cheap-windows-activation-keys/"><u>6 Risks of Using Cheap Windows Activation Keys</u></a></li>
<li><a href="https://win11.techidaily.com/a-dual-screen-dream-realized-android-plus-windows-11-collaboration/"><u>A Dual-Screen Dream Realized: Android + Windows 11 Collaboration</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-startup-launching-windows-and-notebooks-effortlessly/"><u>Accelerated Startup: Launching Windows and Notebooks Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/banish-keystroke-chaos-an-effective-guide-to-repair-common-windows-shortcut-issues/"><u>Banish Keystroke Chaos! An Effective Guide to Repair Common Windows Shortcut Issues</u></a></li>
<li><a href="https://win11.techidaily.com/countering-dxgideviceremoved-failsafe-techniques/"><u>Countering DXGI_DEVICE_REMOVED Failsafe Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-the-mystery-of-the-blank-steam-window/"><u>Dealing With the Mystery of the Blank Steam Window</u></a></li>
<li><a href="https://win11.techidaily.com/easy-access-mastering-folders-and-files-props/"><u>Easy Access: Mastering Folders and Files Props</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-data-discovery-on-pc-via-everythingapp/"><u>Effortless Data Discovery on PC via EverythingApp</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-error-code-3-in-nvidia-opengl-win10-and-11/"><u>Eliminating Error Code 3 in NVIDIA OpenGL (Win10 & 11)</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-taskbar-tweaks-in-windows-11/"><u>Expert Guide to Taskbar Tweaks in Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-itel-a05s-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Itel A05s | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-vivo-v30-pro-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Vivo V30 Pro Phone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-vivo-t2x-5g-screen-sharing-drfone-by-drfone-android/"><u>How To Do Vivo T2x 5G Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-prevent-samurai-warriors-5-from-freezing-and-crashing-on-your-computer/"><u>How to Prevent Samurai Warriors 5 From Freezing and Crashing on Your Computer</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-leave-a-life360-group-on-vivo-y100a-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How To Leave a Life360 Group On Vivo Y100A Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-xiaomi-14-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Xiaomi 14 FRP Without Computer</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-magix-acid-pro-review-and-alternatives/"><u>In 2024, Magix ACID Pro Review & Alternatives</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-iphone-xs-max-by-drfone-ios/"><u>In 2024, Top 11 Free Apps to Check IMEI on iPhone XS Max</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-printer-friendly-presentations-on-windows/"><u>Mastering the Art of Printer-Friendly Presentations on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11s-elusive-theme-options-through-registry/"><u>Mastering Windows 11'S Elusive Theme Options Through Registry</u></a></li>
<li><a href="https://win11.techidaily.com/probing-the-heart-of-windows-systems-generating-insightful-reports/"><u>Probing the Heart of Windows Systems: Generating Insightful Reports</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-to-prevent-windows-control-center-crashes/"><u>Quick-Fix Guide to Prevent Windows Control Center Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-steam-login-delays-windows-and-rust-edition/"><u>Resolving Steam Login Delays: Windows & Rust Edition</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-vms-from-windows-host-to-linux-guest-with-hyper-v/"><u>Setting Up VMs: From Windows Host to Linux Guest with Hyper-V</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-altering-file-deletion-alerts-in-win/"><u>Steps for Altering File Deletion Alerts in Win</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-fix-upgrade-failure-in-windows-11-error-0x800f0922/"><u>Steps to Fix Upgrade Failure in Windows 11 - Error 0X800f0922</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-solving-d3d11-gpu-issues-on-microsofts-latest-oses/"><u>Swiftly Solving D3D11 GPU Issues on Microsoft's Latest OSes</u></a></li>
<li><a href="https://win11.techidaily.com/sync-windows-display-avoiding-overscan-limitations/"><u>Sync Windows Display: Avoiding Overscan Limitations</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-efficient-file-management-customizing-explorer-comments/"><u>Tips for Efficient File Management: Customizing Explorer Comments</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-chaos-powerrename-for-files/"><u>Transforming Chaos: PowerRename for Files</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-non-functional-usb-ports-on-windows-11/"><u>Troubleshooting and Fixing Non-Functional USB Ports on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-lock-screen-stop-timer-glitch/"><u>Troubleshooting Windows Lock Screen Stop-Timer Glitch</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-the-security-of-windows-11s-s-mode/"><u>Unpacking the Security of Windows 11'S 'S Mode'</u></a></li>
<li><a href="https://win11.techidaily.com/why-the-shift-from-windows-10-to-version-11-fails/"><u>Why the Shift From Windows 10 to Version 11 Fails</u></a></li>
<li><a href="https://win11.techidaily.com/win32keygen-understanding-identifying-and-neutralizing-its-threat-to-windows/"><u>Win32/Keygen: Understanding, Identifying & Neutralizing Its Threat to Windows</u></a></li>
<li><a href="https://win11.techidaily.com/winning-with-linux-the-windows-integration-edge/"><u>Winning with Linux: The Windows Integration Edge</u></a></li>
<li><a href="https://win11.techidaily.com/yearly-best-offer-buy-now-at-612-for-eternal-win10-life/"><u>Yearly Best Offer: Buy Now at $6.12 for Eternal Win10 Life</u></a></li>
<li><a href="https://extra-tips.techidaily.com/zap-the-blackout-top-tips-for-facebook-videos-on-secure-browsers/"><u>Zap the Blackout  Top Tips for Facebook Videos on Secure Browsers</u></a></li>
</ul></div>
