---
title: "Unlocking PC Access: Windows 11/10 Key Retrieval Methods"
date: 2024-09-10T08:55:02.727Z
updated: 2024-09-17T00:26:43.310Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking PC Access: Windows 11/10 Key Retrieval Methods"
excerpt: "This Article Describes Unlocking PC Access: Windows 11/10 Key Retrieval Methods"
keywords: WIN11KeyRetrieval,WIN10AccessMethods,RetrieveWindowsKeys,PCUnlockTechniques,KeyRecoveryWinOS,OSUpdateKeys,WindowsKeyFinder
thumbnail: https://thmb.techidaily.com/1ddec9a0b5a6c3e1804c33a43db9c91ffd9d92f92510209406429341a2fb6bc6.jpg
---

## Unlocking PC Access: Windows 11/10 Key Retrieval Methods

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Quick Links

* [What Is a Windows Product Key?](#what-is-a-windows-product-key)
* [How to Find Your Windows 11/10 Product Key Using the Command Prompt](#how-to-find-your-windows-11-10-product-key-using-the-command-prompt)
* [How to Recover a Windows 11/10 Product Key Using PowerShell](#how-to-recover-a-windows-11-10-product-key-using-powershell)
* [Use a Third-Party Tool to Find Your Windows 11/10 Product Key](#use-a-third-party-tool-to-find-your-windows-11-10-product-key)
* [Check Your Purchase Receipt or Email](#check-your-purchase-receipt-or-email)
* [Contact Microsoft Support](#contact-microsoft-support)

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
<a href="https://aligracehair.sjv.io/c/5597632/2135359/19272" target="_top" id="2135359">
  <img src="//a.impactradius-go.com/display-ad/19272-2135359" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135359/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Use a Third-Party Tool to Find Your Windows 11/10 Product Key

![showkeyplus tool showing the retrieved Windows product information.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/showkeyplus-tool-find-product-key.png)

 If you would rather avoid the hassle of typing commands or running scripts, third-party tools like ShowKeyPlus can help you find the Windows activation code with a few clicks. You can download this app from the Microsoft Store to retrieve Windows product key information. Here’s how:

1. Visit the Microsoft Store page for [ShowKeyPlus](https://apps.microsoft.com/detail/9PKVZCPRX9NV) and install the app.
2. Launch ShowKeyPlus, which will display information about the Windows license installed on your PC.
3. Click the **Save** button to save the product details in a text file.

 Also, you can use ShowKeyPlus to check your specific Windows edition using the product key and retrieve a key from a backup.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134228/18498" target="_top" id="2134228">
  <img src="//a.impactradius-go.com/display-ad/18498-2134228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134228/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Check Your Purchase Receipt or Email

 If you bought a Windows license key from an online retailer like Amazon, you likely received the info via email. Use keywords like "Windows license", "Windows product", and "Windows activation" to search for the confirmation mail that you received. Or check the **Orders** section of your account with that online retailer to find information on how to retrieve the key, or how the key was initially delivered.

 As another option, look for physical stickers on your computer with information related to your computer hardware and software configuration. These may also include the Windows product key or other necessary details to help you locate it.

<!-- affiliate ads begin -->
<span id="1484963">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1484963.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1484963">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1484963.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1484963%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1484963/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Contact Microsoft Support

 If all else fails, try contacting Microsoft support for assistance. You can ask for a callback using the **Get Help** app on your computer:

1. Press **Win + I** to open **Settings**.  
![Windows 11 Settings app showing the activation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-settings-app-activation-shown.jpg)
2. Open the **System** tab and click on **Activation.**  
![Windows 11 Settings app activation screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-settings-app-activation-screen.jpg)
3. Click **Get Help.**  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118305/7443" target="_top" id="2118305">
  <img src="//a.impactradius-go.com/display-ad/7443-2118305" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118305/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Windows 11 get help app showing the Contact Support option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-get-help-app-contact-support-option.jpg)
4. Click **Contact Support** and then choose the product.  
![Windows 11 get help choose products and services screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-get-help-choose-products-and-services-screen.jpg)
5. Click on **Provide your phone number and the support agent will call you** and follow on-screen instructions.

 In Windows 10 and 11, Microsoft has streamlined the license activation process. Irrespective of how you got your license, once activated, the product key is tied to your system hardware. Whether you upgrade to the next version or clean install the OS, Windows should automatically detect and verify the ownership.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-videos.techidaily.com/new-remedying-silent-tweets-with-audio-integration/"><u>[New] Remedying Silent Tweets with Audio Integration</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-scrutinizing-active-presenters-record-quality-for-2024/"><u>[New] Scrutinizing Active Presenter's Record Quality for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-apple-music-and-video-harmony-explained/"><u>[Updated] Apple Music and Video Harmony Explained</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-samsung-galaxy-m14-5g-drfone-by-drfone-virtual-android/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Samsung Galaxy M14 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/g-youtube-captionssubtitles-made-simple-and-fast-for-2024/"><u>Adding YouTube Captions/Subtitles Made Simple and Fast for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/defying-conformity-a-journey-through-edges-microphonecamera-restrictions/"><u>Defying Conformity: A Journey Through Edge's Microphone/Camera Restrictions</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-connectivity-hurdles-bluetooth-pin-problems-in-win11win10/"><u>How To Overcome Connectivity Hurdles: Bluetooth Pin Problems in Win11/Win10</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-latest-insights-on-facebook-whats-new/"><u>In 2024, Latest Insights on Facebook - What's New?</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-accidental-keyboard-hotkeys-at-desktop/"><u>Overcoming Accidental Keyboard Hotkeys at Desktop</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/pathfinding-your-way-from-adsense-to-accounts-aplenty-for-2024/"><u>Pathfinding Your Way From AdSense to Accounts Aplenty for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-windows-11-screens-9-fixes-for-blurry-views/"><u>Perfecting Windows 11 Screens: 9 Fixes for Blurry Views</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/step-by-step-guide-retrieving-and-applying-windows-sound-card-drivers-free-of-charge/"><u>Step-by-Step Guide: Retrieving and Applying Windows Sound Card Drivers Free of Charge</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-data-corruption-fixes-in-windows-1011/"><u>Streamlining Data Corruption Fixes in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-surface-upgrade-compendium-for-improved-functionality/"><u>The Ultimate Surface Upgrade Compendium for Improved Functionality</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/top-10-leading-image-repair-tools-to-revive-your-pictures-on-macpc/"><u>Top 10 Leading Image Repair Tools to Revive Your Pictures on Mac/PC</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    