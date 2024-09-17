---
title: Ignoring Unwanted Windows 11 Advice Popups
date: 2024-09-11T23:07:14.072Z
updated: 2024-09-16T19:21:34.760Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ignoring Unwanted Windows 11 Advice Popups
excerpt: This Article Describes Ignoring Unwanted Windows 11 Advice Popups
keywords: IgnoreAdWarnings,WindowsUpdates,AvoidUWAges,PopupBlocking,SafeUpdateTips,Windows11Ads,CyberSafetyGuide
thumbnail: https://thmb.techidaily.com/aa39b0c8b4b398091d4035d320c4791ea5b2efa57b569d8f39427b85787484d2.jpg
---

## Ignoring Unwanted Windows 11 Advice Popups

 Are you tired of constantly seeing tips and suggestions on your computer screen? Want to mute them and concentrate on your work uninterrupted? Don’t worry - the process is quick and straightforward.

 In this article, we’ll discuss how to turn off or disable tips and suggestions notifications on Windows 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Turn Off or Disable Tips and Suggestions Notifications in Windows 11

 Tips and suggestions provide quick guides to Windows and its features. But if you find them annoying, you can turn them off. Here are two easy methods to turn off tips and suggestions notifications on Windows 11\.

### 1\. How to Turn Off Tips and Suggestions Using System Settings

 To turn off tips and suggestions on your computer, you can use the System Settings. This is the easiest and quickest way to mute these notifications. Here's how to do it:

1. Press **Win + I** to open the Settings window.
2. From the left panel, click on the **System** tab.
3. In the System Settings sub-panel, click on the **Notifications** section.  
![Open System Notification Section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/open-system-notification-section.jpg)
4. Next, scroll down to the bottom and expand **Additional settings**.  
![Get tips and suggestions when using Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/get-tips-and-suggestions-when-using-windows.jpg)
5. You will see a checkbox labeled **Get tips and suggestions when using Windows**. Uncheck it to turn off this feature.

 Now, you will not see any tips and suggestions notifications on your computer. If later you wish to re-enable this feature, follow the same steps outlined above and check the "Get tips and suggestions when using Windows" checkbox. Doing this will enable tips and suggestions notifications on your computer.

### 2\. Turn Off Tips and Suggestions Using a REG File

 If the system setting is unresponsive, you can use a REG file instead. This procedure creates a REG file with the necessary commands. Although it may seem complex, it is actually quite simple.

 Here are the steps to follow:

1. [Open the Notepad application](https://www.makeuseof.com/windows-11-open-notepad/).
2. Copy and paste the following code into it:  
`Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\ContentDeliveryManager]  
"SubscribedContent-338389Enabled"=dword:00000000`
3. Now save the file with the **.reg** extension.
4. Double-click on the file you just created to open it, and click **Yes** in the confirmation dialog box that appears.

 This will turn off tips and suggestions notifications in Windows 11\. To enable these notifications once again, delete the file you just created. Alternatively, double-click on it and click **No** in the confirmation dialog.

<!-- affiliate ads begin -->
<span id="1265663">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1265663.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/4482-1265663">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1265663.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmartinic.evyy.net%2Fc%2F5597632%2F1265663%2F4482'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1265663/4482" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Disable Tips and Suggestions Notifications in Windows 11

 If you prefer to disable tips and suggestions notifications on your computer completely, there are several options available. You can utilize the Group Policy Editor, modify the registry editor, or create a REG file. Let's explore each method in detail to disable this feature.

### 1\. Disable Tips and Suggestions Notifications Using Group Policy Editor

 To turn off notifications for tips and suggestions, access the Group Policy Editor. This tool is available for Windows Pro, Education, and Enterprise users. However, it won't work if you use Windows Home Edition.

 In such cases, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). Once done, follow the steps below to disable notifications for tips and suggestions:

1. Press **Win + R** to open the Run window.
2. Type **gpedit.msc** in the Run dialog box and press Enter. This will launch the Group Policy Editor window on your screen.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > Windows Components > Cloud Content​
4. On the right side of the window, double-click on the **Do not show Windows tips** policy.  
![Do not Show Windows Tips](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/do-not-show-windows-tips.jpg)
5. From the box that appears, select the **Enabled** radio button.

<!-- affiliate ads begin -->
<span id="1982456">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982456.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982456">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982456.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982456%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982456/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Click **Apply** \> **OK** to save the changes.

 Now, tips and suggestions notifications will be completely disabled on your computer. To re-enable the feature, follow the same steps and select the **Not Configured** or **Disabled** radio button instead.

### 2\. Disable Tips and Suggestions Notifications Using the Registry Editor

 If you can’t access the Group Policy Editor or activate it, you can modify the registry editor to disable these notifications. The procedure is slightly more technical and requires caution while making changes. It may even wreck your computer system, so proceed cautiously.

 To avoid risks, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first. That way, you can restore the original settings if required. Once you have taken these precautionary steps, follow the instructions below to disable tips and suggestions notifications:

1. Press the **Windows** key to open the Start Menu.
2. Type **regedit** in the search box and select the **Registry Editor** app from the search results.
3. If the UAC window appears, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following path:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\CloudContent
5. If the **CloudContent** key is missing, create a new one. To do this, right-click on the Windows folder and select **New** \> **Key**. Name it **CloudContent**.
6. On the right side of the window, right-click on an empty area and select **New** \> **DWORD (32-bit) Value**.
7. Name the value **DisableSoftLanding** and hit Enter.  
![Disable Tips and Suggestions Notifications Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-tips-and-suggestions-notifications-using-the-registry-editor.jpg)
8. Double-click on this newly created entry and set its Value data to **1**.
9. Click **OK** to save the changes. Now, exit the registry editor window and restart your computer.

 After restarting, tips and suggestions notifications will be disabled on your computer. If you want to enable the feature, follow the same steps and change the Value data to **0**.

### 3\. Disable Tips and Suggestions Notifications Using a REG File

 You can also create a REG file to turn off tips and suggestions notifications on your Windows PC. This method is quite similar to the one we discussed above. However, the process is easier for those with little experience editing registry files.

 To disable tips and suggestions notifications using a REG file, follow the steps outlined below:

1. Search for **Notepad** and select the result from the list.
2. Copy and paste the code below into the Notepad window.  
`Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\Software\Policies\Microsoft\Windows\CloudContent]  
"DisableSoftLanding"=dword:00000001`
3. Save the file with the .reg extension. Make sure that the Save as type field is set to **All files**.
4. Now, double-click on the file and click **Yes** at the prompt.

 That’s it! Tips and suggestions feature is now disabled on your computer.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115909/19272" target="_top" id="2115909">
  <img src="//a.impactradius-go.com/display-ad/19272-2115909" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115909/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Stop the Windows Tips and Suggestions Notifications

 We hope that this article helped you understand how to turn off or disable tips and suggestions notifications in Windows 11\. All it takes are a few clicks or a simple REG file to enable or disable this feature.

 In this article, we’ll discuss how to turn off or disable tips and suggestions notifications on Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-unleash-your-devices-potential-how-to-download-and-customize-whatsapp-ringtones/"><u>[New] In 2024, Unleash Your Device's Potential How to Download and Customize WhatsApp Ringtones</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-preserve-precision-4-advanced-screen-recording-for-gamers/"><u>[New] Preserve Precision 4 Advanced Screen Recording for Gamers</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-20-hit-tiktok-rhymes-you-cant-miss-for-2024/"><u>[Updated] 20 Hit TikTok Rhymes You Can't Miss for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/elevate-discussion-volume-on-your-social-media-hub/"><u>Elevate Discussion Volume on Your Social Media Hub</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-direct-approaches-to-documenting-google-voice-interactions/"><u>In 2024, Direct Approaches to Documenting Google Voice Interactions</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-recovering-individual-snap-secrets/"><u>In 2024, Recovering Individual Snap Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/itunes-iphoneandandroid/"><u>ITunesにダビング！カメラ撮影動画から音楽へ - iPhone&Android利用者向けガイド</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/revolutionize-your-workflow-top-8-chrome-with-ai/"><u>Revolutionize Your Workflow: Top 8 Chrome with AI</u></a></li>
<li><a href="https://win11.techidaily.com/simple-tricks-capturing-and-downloading-your-favorite-instagram-live-sessions/"><u>Simple Tricks: Capturing and Downloading Your Favorite Instagram Live Sessions</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-transforming-mkv-videos-into-high-quality-av1-format/"><u>Step-by-Step Guide: Transforming MKV Videos Into High-Quality AV1 Format</u></a></li>
<li><a href="https://win11.techidaily.com/top-4-remedies-to-resolve-the-0xc00d36c4-error-during-videoaudio-playback/"><u>Top 4 Remedies to Resolve the '0xC00D36C4' Error During Video/Audio Playback</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    