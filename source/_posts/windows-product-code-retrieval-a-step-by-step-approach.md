---
title: "Windows Product Code Retrieval: A Step-by-Step Approach"
date: 2024-09-26T16:04:56.885Z
updated: 2024-10-03T19:55:09.775Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Product Code Retrieval: A Step-by-Step Approach"
excerpt: "This Article Describes Windows Product Code Retrieval: A Step-by-Step Approach"
keywords: Windows PC Retrieval,PC Code Extraction,Steps for PC ID,Identify Windows Model,Retrieve OS Product Code,Find PC Serial Number,System Identifier Fetching
thumbnail: https://thmb.techidaily.com/da7734e84e246f918bdf5e60b91499ba1ad1512932f71cc8b0057c6b83a1e49f.jpg
---

## Windows Product Code Retrieval: A Step-by-Step Approach

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137207/26400" target="_top" id="2137207">
  <img src="//a.impactradius-go.com/display-ad/26400-2137207" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137207/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What Is a Windows Product Key?

 A [Windows product key](https://www.makeuseof.com/windows-product-keys-guide/) is a 25-character code you use to activate your copy of Windows. Since Windows 11 and 10 use a digital license method for activation, you don’t need to manually enter the key each time you upgrade or [clean install Windows](https://www.makeuseof.com/important-things-remember-clean-installing-windows/).

 However, if you significantly change your device's hardware, Windows won't be able to detect the license tied to your device. A manual activation may also be necessary if you run into a Windows 11 activation error.

 To activate Windows in these cases, you'll need to enter the 25-character product key. As such, if you don't know your product key, we'll explain how to extract it from your Windows 11 or 10 system.

 Note that each edition of Windows uses its own unique product key. For example, if you have a license for the Windows 11/10 Home edition, you cannot use it to activate Windows Pro or other editions.

## 1\. How to Find Your Windows 11/10 Product Key Using the Command Prompt

![Command Prompt window running the wmic path SoftwareLicensingService get OA3xOriginalProductKey command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/command-prompt-windows-11-product-key.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123727/7443" target="_top" id="2123727">
  <img src="//a.impactradius-go.com/display-ad/7443-2123727" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123727/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

## 3\. Use a Third-Party Tool to Find Your Windows 11/10 Product Key

![showkeyplus tool showing the retrieved Windows product information.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/showkeyplus-tool-find-product-key.png)

 If you would rather avoid the hassle of typing commands or running scripts, third-party tools like ShowKeyPlus can help you find the Windows activation code with a few clicks. You can download this app from the Microsoft Store to retrieve Windows product key information. Here’s how:

1. Visit the Microsoft Store page for [ShowKeyPlus](https://apps.microsoft.com/detail/9PKVZCPRX9NV) and install the app.
2. Launch ShowKeyPlus, which will display information about the Windows license installed on your PC.
3. Click the **Save** button to save the product details in a text file.

 Also, you can use ShowKeyPlus to check your specific Windows edition using the product key and retrieve a key from a backup.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037334/7443" target="_top" id="2037334">
  <img src="//a.impactradius-go.com/display-ad/7443-2037334" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037334/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Check Your Purchase Receipt or Email

 If you bought a Windows license key from an online retailer like Amazon, you likely received the info via email. Use keywords like "Windows license", "Windows product", and "Windows activation" to search for the confirmation mail that you received. Or check the **Orders** section of your account with that online retailer to find information on how to retrieve the key, or how the key was initially delivered.

 As another option, look for physical stickers on your computer with information related to your computer hardware and software configuration. These may also include the Windows product key or other necessary details to help you locate it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135362/19272" target="_top" id="2135362">
  <img src="//a.impactradius-go.com/display-ad/19272-2135362" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135362/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Contact Microsoft Support

 If all else fails, try contacting Microsoft support for assistance. You can ask for a callback using the **Get Help** app on your computer:

1. Press **Win + I** to open **Settings**.  
![Windows 11 Settings app showing the activation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-settings-app-activation-shown.jpg)
2. Open the **System** tab and click on **Activation.**  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135375/19272" target="_top" id="2135375">
  <img src="//a.impactradius-go.com/display-ad/19272-2135375" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135375/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Windows 11 Settings app activation screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-settings-app-activation-screen.jpg)
3. Click **Get Help.**  

![Windows 11 get help app showing the Contact Support option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-get-help-app-contact-support-option.jpg)
4. Click **Contact Support** and then choose the product.  
![Windows 11 get help choose products and services screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-get-help-choose-products-and-services-screen.jpg)
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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-directly-upload-and-share-videos-to-twitter-from-your-phone/"><u>[New] 2024 Approved Directly Upload and Share Videos to Twitter From Your Phone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-instagrams-latest-trends-for-successful-influencer-journeys/"><u>[New] Instagram's Latest Trends for Successful Influencer Journeys</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-apples-pride-ios-10-best-no-cost-collages-and-photo-edits/"><u>[Updated] Apple's Pride IOS' 10 Best No-Cost Collages & Photo Edits</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-preventing-unwanted-filming-in-quicktime/"><u>[Updated] In 2024, Preventing Unwanted Filming in QuickTime</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-crafting-seamless-sounds-for-your-podcasts-using-garageband/"><u>2024 Approved Crafting Seamless Sounds for Your Podcasts Using GarageBand</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-mastering-sound-shifts-in-free-fire/"><u>2024 Approved Mastering Sound Shifts in Free Fire</u></a></li>
<li><a href="https://win-able.techidaily.com/fix-dota-2s-stalled-loading-scenes-a-step-by-step-guide-to-restarting-your-game/"><u>Fix Dota 2'S Stalled Loading Scenes - A Step-by-Step Guide to Restarting Your Game</u></a></li>
<li><a href="https://win-answers.techidaily.com/fix-godfall-crashing-on-pc-full-guide/"><u>Fix Godfall Crashing on PC [Full Guide]</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-cricket-apple-iphone-xs-max-for-free-by-drfone-ios/"><u>In 2024, How To Unlock Cricket Apple iPhone XS Max for Free</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/mastering-your-soundtrack-a-methodical-approach-to-choosing-a-digital-audio-recorder-beyond-apowersoft/"><u>Mastering Your Soundtrack A Methodical Approach to Choosing a Digital Audio Recorder Beyond Apowersoft</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-external-display-not-recognized-problem-in-windows/"><u>Overcoming External Display Not Recognized Problem in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/proven-methods-to-stop-display-glitches-on-windows-1011/"><u>Proven Methods to Stop Display Glitches on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-recovering-a-disabled-delete-functionality/"><u>Solutions for Recovering a Disabled Delete Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/stop-active-use-of-cortana-in-windows-11/"><u>Stop Active Use of Cortana in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-taming-troublesome-updates/"><u>The Ultimate Guide to Taming Troublesome Updates</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-resolving-windows-side-by-side-conflict/"><u>Troubleshooting: Resolving 'Windows Side-by-Side Conflict'</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-11s-next-gen-phone-integration/"><u>Unveiling Windows 11'S Next-Gen Phone Integration</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-update-impact-on-linux-subsystem/"><u>Windows 11 Update: Impact on Linux Subsystem</u></a></li>
<li><a href="https://win11.techidaily.com/windows-graphics-scheduler-control-explained/"><u>Windows Graphics Scheduler Control Explained</u></a></li>
</ul></div>

