---
title: "Windows Product Code Retrieval: A Step-by-Step Approach"
date: 2024-09-13T20:37:29.004Z
updated: 2024-09-17T01:29:43.093Z
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

## What Is a Windows Product Key?

 A [Windows product key](https://www.makeuseof.com/windows-product-keys-guide/) is a 25-character code you use to activate your copy of Windows. Since Windows 11 and 10 use a digital license method for activation, you don’t need to manually enter the key each time you upgrade or [clean install Windows](https://www.makeuseof.com/important-things-remember-clean-installing-windows/).

 However, if you significantly change your device's hardware, Windows won't be able to detect the license tied to your device. A manual activation may also be necessary if you run into a Windows 11 activation error.

 To activate Windows in these cases, you'll need to enter the 25-character product key. As such, if you don't know your product key, we'll explain how to extract it from your Windows 11 or 10 system.

 Note that each edition of Windows uses its own unique product key. For example, if you have a license for the Windows 11/10 Home edition, you cannot use it to activate Windows Pro or other editions.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130870/7443" target="_top" id="2130870">
  <img src="//a.impactradius-go.com/display-ad/7443-2130870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130870/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115938/19272" target="_top" id="2115938">
  <img src="//a.impactradius-go.com/display-ad/19272-2115938" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115938/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You also use PowerShell and the WMI cmdlet to find and display your Windows 11 or 10 product key. Here’s how to do this:

1. Press the **Window** key and type **powershell**.
2. Right-click on **PowerShell** and select **Run as administrator.**
3. In the PowerShell window, copy and paste, or type, the following command and press Enter:  
`(Get-WmiObject -query 'select * from SoftwareLicensingService').OA3xOriginalProductKey`
4. The command may take a few seconds to execute. Upon successful execution, it will display the product key for your copy of Windows.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135406/19272" target="_top" id="2135406">
  <img src="//a.impactradius-go.com/display-ad/19272-2135406" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135406/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Use a Third-Party Tool to Find Your Windows 11/10 Product Key

![showkeyplus tool showing the retrieved Windows product information.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/showkeyplus-tool-find-product-key.png)

 If you would rather avoid the hassle of typing commands or running scripts, third-party tools like ShowKeyPlus can help you find the Windows activation code with a few clicks. You can download this app from the Microsoft Store to retrieve Windows product key information. Here’s how:

1. Visit the Microsoft Store page for [ShowKeyPlus](https://apps.microsoft.com/detail/9PKVZCPRX9NV) and install the app.
2. Launch ShowKeyPlus, which will display information about the Windows license installed on your PC.
3. Click the **Save** button to save the product details in a text file.

 Also, you can use ShowKeyPlus to check your specific Windows edition using the product key and retrieve a key from a backup.

## 4\. Check Your Purchase Receipt or Email

 If you bought a Windows license key from an online retailer like Amazon, you likely received the info via email. Use keywords like "Windows license", "Windows product", and "Windows activation" to search for the confirmation mail that you received. Or check the **Orders** section of your account with that online retailer to find information on how to retrieve the key, or how the key was initially delivered.

 As another option, look for physical stickers on your computer with information related to your computer hardware and software configuration. These may also include the Windows product key or other necessary details to help you locate it.

## 5\. Contact Microsoft Support

 If all else fails, try contacting Microsoft support for assistance. You can ask for a callback using the **Get Help** app on your computer:

1. Press **Win + I** to open **Settings**.  
![Windows 11 Settings app showing the activation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-settings-app-activation-shown.jpg)
2. Open the **System** tab and click on **Activation.**  
![Windows 11 Settings app activation screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-settings-app-activation-screen.jpg)
3. Click **Get Help.**  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137206/26400" target="_top" id="2137206">
  <img src="//a.impactradius-go.com/display-ad/26400-2137206" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137206/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Windows 11 get help app showing the Contact Support option.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-get-help-app-contact-support-option.jpg)
4. Click **Contact Support** and then choose the product.  
![Windows 11 get help choose products and services screen](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-get-help-choose-products-and-services-screen.jpg)
5. Click on **Provide your phone number and the support agent will call you** and follow on-screen instructions.

 In Windows 10 and 11, Microsoft has streamlined the license activation process. Irrespective of how you got your license, once activated, the product key is tied to your system hardware. Whether you upgrade to the next version or clean install the OS, Windows should automatically detect and verify the ownership.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-knowledge.techidaily.com/new-do-consumer-feedbacks-get-paid-in-vlogs-for-2024/"><u>[New] Do Consumer Feedbacks Get Paid in Vlogs for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-youtube-video-aspect-ratio-guide-optimal-upload-sizes/"><u>[Updated] YouTube Video Aspect Ratio Guide Optimal Upload Sizes</u></a></li>
<li><a href="https://win11.techidaily.com/1726028360556-7/"><u>「最適なビデオ寸法変更サイト・上位7推奨」</u></a></li>
<li><a href="https://win11.techidaily.com/44cm44km44kn44ow44ox44os44k844oz44og44o844k344on44oz44gu44gf44kb44gr44k544op44kk44oj44k344on44o844ot44oh44kq44ks5yq55p6c55qe44gr57eo6zug44gz44kl5oqa6kgt44cn1/"><u>「ウェブプレゼンテーションのためにスライドショービデオを効果的に編集する技術」</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-cinematic-basics-unveiled-fundamental-shots-explained-clearly/"><u>2024 Approved Cinematic Basics Unveiled Fundamental Shots Explained Clearly</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-converting-dvd-content-into-avi-format-with-minimal-hassle/"><u>A Beginner's Guide to Converting DVD Content Into AVI Format with Minimal Hassle</u></a></li>
<li><a href="https://win11.techidaily.com/alcwavmp3/"><u>ALCフォーマットを効率的にWAVやMP3に変換する方法 | ハイレゾ音質移行手順</u></a></li>
<li><a href="https://win11.techidaily.com/1726028106781-dvd/"><u>DVDの正常再生を保証する!理解しやすく簡単に修復する方法</u></a></li>
<li><a href="https://extra-resources.techidaily.com/experience-like-never-before-leading-10-vr-devices/"><u>Experience Like Never Before Leading 10 VR Devices</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-can-we-bypass-oppo-frp-by-drfone-android/"><u>How Can We Bypass Oppo FRP?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-a-tecno-spark-20c-easily-by-drfone-android/"><u>How To Unlock a Tecno Spark 20C Easily?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-change-lock-screen-wallpaper-on-tecno-spark-10-5g-by-drfone-android/"><u>In 2024, How to Change Lock Screen Wallpaper on Tecno Spark 10 5G</u></a></li>
<li><a href="https://win11.techidaily.com/1726029205926-iphone/"><u>IPhoneにおける「読み込めない動画エラー」を克服する方法</u></a></li>
<li><a href="https://win11.techidaily.com/1726028985392-mp3/"><u>MP3音量比率変更ツールをご利用いただける場所と使い方ガイド</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/personalized-vr-retail-journeys-for-2024/"><u>Personalized VR Retail Journeys for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/realigning-your-personal-soundtracks-from-spotify-to-youtube-music-for-2024/"><u>Realigning Your Personal Soundtracks From Spotify to YouTube Music for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    