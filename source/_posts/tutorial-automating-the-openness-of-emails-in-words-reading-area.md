---
title: "Tutorial: Automating the Openness of Emails in Word's Reading Area"
date: 2024-12-23T20:40:06.815Z
updated: 2024-12-28T02:21:02.266Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tutorial: Automating the Openness of Emails in Word's Reading Area"
excerpt: "This Article Describes Tutorial: Automating the Openness of Emails in Word's Reading Area"
keywords: Word OpenEmail Tutorial,Auto Mail Readability,Words Email Automaption,Reading Area Optimization,Word Openness Guide,Emails Automation Technique,Word Read Area Tips
thumbnail: https://thmb.techidaily.com/a770835b076eb6b9f15ef9eaa24a0d7865dfb16a5caaa3e52196c91037b09546.jpg
---

## Tutorial: Automating the Openness of Emails in Word's Reading Area

 Microsoft Word comes with a lot of security features that protect your computer from malicious files. One of these options allows you to open all email attachments in Word's reading view by default.

 If you want an extra layer of protection against email attachments, there are several ways to always open attached Word documents in reading view on Windows. Let’s go over them one by one.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0nGlyEL5K6Y?si=3KZhTTBvKcPmyS68" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Change Microsoft Word Startup Settings to Always Open Email Attachments in Reading View

 You can modify Word's startup settings to specify how your documents are handled. From there, you can set Word to open all email attachments in reading mode by default. Here's how:

1. Open Microsoft Word on your PC using the search menu.
2. Click the**File** menu in the top left corner.
3. Select**Options** from the left pane. This will open the**Word Options** window.
4. In the**General** tab, scroll down to**Start up options** .
5. Check the box that reads **Open e-mail attachments and other uneditable files in reading view** and click on**OK** .  
![Word Startup Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Word-Startup-Options.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aRMCbJxLuwE?si=E5sfJvoqkv1qCMWz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, Word will open email attachments in reading view by default.

## 2\. How to Change the Local Group Policy to Open Email Attachments in Reading View in Microsoft Word

 Another way to configure Word to open email attachments in reading view is to use the Group Policy Editor. It’s worth noting that you can only access the Group Policy Editor if you’re running the Professional, Education, or Enterprise edition of Windows. If you're on Windows Home, be sure to check out[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Click the magnifying icon on the taskbar or press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the box and select the first result that appears. This will[open the Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/) .
3. Use the left pane to navigate to **User Configuration > Administrative Templates > Microsoft Word 2016 > Word Options > General** .
4. Double-click the**Open e-mail attachments in Reading View** policy on your right.
5. Select the**Enabled** option.
6. Hit**Apply** followed by**OK** .  
![Configure Word to Open Email Attachments in Reading View Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Group-Policy-Editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Tweak the Windows Registry to Open Email Attachments in Reading View in Microsoft Word

 The Registry Editor in Windows stores important settings for Windows and its apps. If you're comfortable editing registry files, you can also use the following method to configure Word to open email attachments in reading view.

 Since modifying registry files is risky, you should proceed with caution. Also, make sure you back up all the registry files first. If you need help, refer to our guide on[how to back up and restore the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and follow the steps outlined there.

 Once you’ve done that, here’s what you need to configure Word to open email attachments in reading view.

1. Press**Win + R** to open the Run dialog.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > Software > Microsoft > Office > 16.0 > Word > Options** .
5. Right-click on the**Options** key and select**New > DWORD (32-bit) Value** . Name it**AutoReadingMode** .
6. Double-click the newly created DWORD and set the**Value data** to**1** .
7. Click**OK** .  
![Configure Word to Open Email Attachments in Reading View Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Configure-Word-to-Open-Email-Attachments-in-Reading-View-Using-Registry-Editor.jpg)

 Restart your PC for the changes to take effect. Following that, Word will open all your email attachments in reading view.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Opening Email Attachments in Microsoft Word's Reading View

 Email remains a prominent attack vector for hackers and cybercriminals. Configuring Microsoft Word to open email attachments in reading view is just one of many methods for avoiding malware. Another option is to check suspicious files for malware before opening them.

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
<li><a href="https://vp-tips.techidaily.com/new-premium-psd-free-3d-text-treasure-hunt/"><u>[New] Premium PSD Free 3D Text Treasure Hunt</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-download-screen-recorder-pro-for-windows-11/"><u>[Updated] 2024 Approved Download Screen Recorder Pro for Windows 11</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-tips-for-finding-christian-choir-songs-online-and-personalizing-them-for-2024/"><u>[Updated] Tips for Finding Christian Choir Songs Online & Personalizing Them for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/5-most-prominent-driverless-car-companies-to-watch-in-2024-teslas-dominance-as-the-no1-autonomous-vehicle-manufacturer/"><u>5 Most Prominent Driverless Car Companies to Watch in 202#4 Tesla's Dominance as the No.1 Autonomous Vehicle Manufacturer</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/best-recorders-for-lecture-recording/"><u>Best Recorders for Lecture Recording</u></a></li>
<li><a href="https://win11.techidaily.com/leading-edge-drawing-pads-dominating-the-digital-canvas/"><u>Leading Edge Drawing Pads Dominating the Digital Canvas</u></a></li>
<li><a href="https://win-able.techidaily.com/mastering-elden-ring-expert-strategies-for-smoothing-out-frame-rates-and-eliminating-stutters/"><u>Mastering Elden Ring: Expert Strategies for Smoothing Out Frame Rates and Eliminating Stutters</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-pro-video-editor-convert-casual-clips-into-cinematic-masterpieces/"><u>New Pro Video Editor Convert Casual Clips Into Cinematic Masterpieces</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-webcam-failure-in-windows-11-code-0xa00f4289-fixes/"><u>Overcoming Webcam Failure in Windows 11: Code 0xA00F4289 Fixes</u></a></li>
<li><a href="https://technical-tips.techidaily.com/solving-the-dilemma-of-missing-rockalldlldll-error-messages/"><u>Solving the Dilemma of Missing RockallDLL.dll Error Messages</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-sound-failure-resolving-error-xc00d36b4/"><u>Tackling Sound Failure: Resolving Error XC00D36B4</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-the-challenge-of-application-crashes-due-to-unhandled-errors/"><u>Tackling the Challenge of Application Crashes Due to Unhandled Errors</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unlinked-file-apps-on-windows/"><u>Troubleshooting Unlinked File Apps on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-phone-link-why-disable-yourphoneexe/"><u>Windows Phone Link: Why Disable YourPhoneExe?</u></a></li>
</ul></div>

