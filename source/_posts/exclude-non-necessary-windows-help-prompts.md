---
title: Exclude Non-Necessary Windows Help Prompts
date: 2024-09-14T02:47:44.319Z
updated: 2024-09-17T04:20:17.618Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Exclude Non-Necessary Windows Help Prompts
excerpt: This Article Describes Exclude Non-Necessary Windows Help Prompts
keywords: Avoid Unwanted Windows Guides,Skip Extra Windows Messages,Reduce Window Interruptions,Minimize Non-Essential Windows Tips,Eliminate Superfluous Win Help,Disregard Irrelevant Win Alerts,Filter Out Unneeded Win Assistance
thumbnail: https://thmb.techidaily.com/6c0a15a3d6083cf4363045e7514d3f4e9e6ab2b47b75aab4b7af36cf0fe09749.jpg
---

## Exclude Non-Necessary Windows Help Prompts

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

## How to Disable Tips and Suggestions Notifications in Windows 11

 If you prefer to disable tips and suggestions notifications on your computer completely, there are several options available. You can utilize the Group Policy Editor, modify the registry editor, or create a REG file. Let's explore each method in detail to disable this feature.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135413/19272" target="_top" id="2135413">
  <img src="//a.impactradius-go.com/display-ad/19272-2135413" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135413/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123731/7443" target="_top" id="2123731">
  <img src="//a.impactradius-go.com/display-ad/7443-2123731" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123731/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://bluettius.sjv.io/c/5597632/2139121/17108" target="_top" id="2139121">
  <img src="//a.impactradius-go.com/display-ad/17108-2139121" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139121/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Stop the Windows Tips and Suggestions Notifications

 We hope that this article helped you understand how to turn off or disable tips and suggestions notifications in Windows 11\. All it takes are a few clicks or a simple REG file to enable or disable this feature.

 In this article, we’ll discuss how to turn off or disable tips and suggestions notifications on Windows 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/new-uniting-visuals-the-art-of-video-sequence-composition/"><u>[New] Uniting Visuals The Art of Video Sequence Composition</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-bringing-anime-characters-to-life-jujutsu-kaisen-for-tiktok-for-2024/"><u>[Updated] Bringing Anime Characters to Life Jujutsu Kaisen for TikTok for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-funny-faces-for-iphone-users/"><u>2024 Approved Funny Faces for iPhone Users</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-ultimate-guide-to-valheim-sowing-seeds/"><u>2024 Approved Ultimate Guide to Valheim Sowing Seeds</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/exploring-the-features-and-performance-of-the-open-source-linksys-wrt1900acs-wifi-router/"><u>Exploring the Features and Performance of the Open Source Linksys WRT1900ACS WiFi Router</u></a></li>
<li><a href="https://win11.techidaily.com/flacipad/"><u>FLAC形式の音楽ファイルをiPad上でどのように再生しますか？</u></a></li>
<li><a href="https://win11.techidaily.com/free-theme-song-downloads-a-hassle-free-guide/"><u>Free Theme Song Downloads: A Hassle-Free Guide</u></a></li>
<li><a href="https://win11.techidaily.com/from-disc-to-cloud-master-the-art-of-free-dvd-to-digital-copy-creation/"><u>From Disc to Cloud: Master the Art of Free DVD-to-Digital Copy Creation</u></a></li>
<li><a href="https://win11.techidaily.com/get-crystal-clear-images-anytime-the-ultimate-guide-to-dvd-upgrading-for-high-definition-enjoyment/"><u>Get Crystal Clear Images Anytime: The Ultimate Guide to DVD Upgrading for High Definition Enjoyment</u></a></li>
<li><a href="https://win11.techidaily.com/guide-capturing-audio-and-video-together-on-windows-1011/"><u>Guide: Capturing Audio and Video Together on Windows 10/11</u></a></li>
<li><a href="https://tech-haven.techidaily.com/humor-algorithms-at-play-can-tech-tickle-funny-bone/"><u>Humor Algorithms at Play: Can Tech Tickle Funny Bone?</u></a></li>
<li><a href="https://win11.techidaily.com/import-your-mov-videos-hassle-free-expert-tips-for-using-windows-movie-maker-on-a-budget/"><u>Import Your MOV Videos Hassle-Free: Expert Tips for Using Windows Movie Maker on a Budget</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-instagram-filters-a-2023-guide-to-enhanced-photography/"><u>In 2024, Instagram Filters A 2023 Guide to Enhanced Photography</u></a></li>
<li><a href="https://win11.techidaily.com/installing-the-crew-add-on-successfully-a-step-by-step-guide-for-kodi-users-nexusmatrix/"><u>Installing the Crew Add-On Successfully: A Step-by-Step Guide for Kodi Users (Nexus/Matrix)!</u></a></li>
<li><a href="https://driver-download.techidaily.com/update-your-rtx-ablishing-a-safe-environment-in-which-individuals-can-express-their-emotions-and-offering-coping-strategies-to-manage-intense-feelings-const107/"><u>Update Your RTX Ablishing a Safe Environment in Which Individuals Can Express Their Emotions, and Offering Coping Strategies to Manage Intense Feelings Constructively without Resorting to Self-Harm</u></a></li>
<li><a href="https://blog-min.techidaily.com/verwandeln-sie-ihre-videos-schnell-fur-instagram-professionelle-instagram-video-konverter-in-mp4-format/"><u>Verwandeln Sie Ihre Videos Schnell Für Instagram – Professionelle Instagram Video Konverter in MP4 Format</u></a></li>
</ul></div>

