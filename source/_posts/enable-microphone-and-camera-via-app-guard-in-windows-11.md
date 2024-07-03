---
title: Enable Microphone & Camera via App Guard in Windows 11
date: 2024-07-02T13:01:35.010Z
updated: 2024-07-03T13:01:35.010Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enable Microphone & Camera via App Guard in Windows 11
excerpt: This Article Describes Enable Microphone & Camera via App Guard in Windows 11
keywords: Windows 11 Security Update,App Guard Enablement,Microphone Access Control,Camera Permission Management,Device Integration Through Apps,Windows Settings Customization,Privacy-Focused System Feature
thumbnail: https://thmb.techidaily.com/0fde8be80e602ff65625842ff908df27188b320349e0a53c08ea2eca9a5b67ed.jpg
---

## Enable Microphone & Camera via App Guard in Windows 11

 Microsoft's Application Guard for Edge is a great tool to shield your browsing from malicious interference. For extra protection, both the camera and microphone are deactivated by default in this environment; however, there may be times when you need these features enabled to utilize certain web applications.

 If that’s the case, follow this guide which will show you how to enable the camera and microphone in Application Guard for Edge on Windows 11\. ​​​​​​

## 1\. How to Enable the Camera and Microphone via Windows Settings

 To enable the camera and microphone in Application Guard for Edge, follow the steps below:

1. Click on Start, type**Settings** and press**Enter** .
2. On the left side of the screen, select**Privacy & security** .
3. Click the**Windows Security** option on the right.
4. Then, on the next screen, select**App & browser control** .
5. In the new window that opens, click**Change Application Guard settings** under Isolated browsing.
6. Look for the**Camera and microphone** option, and then toggle it on.  
![Enable Camera and Microphone in Application Guard Using Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-windows-settings.jpg)
7. If the UAC prompt appears, click**Yes** to continue.

 After you perform the above action, restart your computer for the changes to take effect. Upon restarting, all your camera and microphone settings should now be applied to the Application Guard for Edge.

 In case you need to turn off the feature again, just follow the same steps and toggle the Camera and microphone option to Off. That’s all there is to it.

## 2\. How to Enable the Camera and Microphone Using Registry Editor

 If you are more comfortable using the registry editor, you can enable your camera and microphone for Application Guard for Edge. All you need to do is open up the registry folder, make a few easy modifications, and restart your computer so that they can take effect.

 However, before you make any changes, it's essential that you [create a backup of the registry file](https://www.makeuseof.com/tag/backup-restore-windows-registry/) just in case something goes wrong.

 To enable your mic & camera with the help of this tool, follow these steps:

1. Search for**regedit** in the Windows search bar and click on the result to open the registry editor. To find out more, see [how to open the registry](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. When the UAC prompt appears, click**Yes** to confirm.
3. In the Registry Editor window, go to the following location:  
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi  
 Copy and paste the given location into the address bar at the top of the registry window and press Enter to quickly jump to the folder.
4. If you don't see the**Hvsi** key there, you need to create it first. In order to do this, right-click on the**Microsoft** folder and select**New > Key** .
5. Name the file**Hvsi** , then hit**Enter** to save it.  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
6. Right-click on Hvsi, choose**New > DWORD (32-bit) Value** , then name it**EnableCameraMicrophoneRedirection** .
7. Now double-click on the newly created DWORD key, and you will see a pop-up window appear.
8. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Camera and Microphone in Application Guard Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-camera-and-microphone-in-application-guard-using-registry-editor.jpg)
9. Then click**OK** to save the changes.

 Once you've done editing the registry, restart your computer to apply the changes. After restarting, Edge's Application Guard will be able to access your camera and microphone hardware for websites that require it.

 If you want to revert the changes, simply set the EnableCameraMicrophoneRedirection key’s value back to**0** and restart your computer.

## Your Camera and Mic Is Now Supported in Edge Application Guard

 Application Guard for Edge is a tool that serves as an extra layer of protection from malicious websites and other threats. By default, your camera and microphone are disabled to ensure maximum security. In this guide, we've explained two quick ways in which you can easily activate these features - via Windows Settings or Registry Editor.


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
<li><a href="https://win11.techidaily.com/winning-over-full-screen-issues-in-sonic-adventure-on-windows-11/"><u>Winning Over Full-Screen Issues in Sonic Adventure on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-resolving-common-anydesk-errors-on-windows/"><u>Mastering the Art of Resolving Common AnyDesk Errors on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reduce-or-increase-software-size-on-windows-11-the-easy-way/"><u>Reduce or Increase Software Size on Windows 11 – The Easy Way</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-file-management-with-windows-automatic-deletion/"><u>Revolutionize File Management with Windows' Automatic Deletion</u></a></li>
<li><a href="https://win11.techidaily.com/separate-onedrive-and-microsoft-accounts-on-desktop-windows/"><u>Separate OneDrive & Microsoft Accounts on Desktop Windows</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-hidden-login-screens-in-windows-11/"><u>Eradicating Hidden Login Screens in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/alert-systems-top-7-windows-processes-for-infection-scrutiny/"><u>Alert Systems: Top 7 Windows Processes for Infection Scrutiny</u></a></li>
<li><a href="https://win11.techidaily.com/swift-surfing-steps-for-windows-based-network-speed-verification/"><u>Swift Surfing: Steps for Windows-Based Network Speed Verification</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-change-your-windows-11-username/"><u>Steps to Change Your Windows 11 Username</u></a></li>
<li><a href="https://extra-resources.techidaily.com/top-tips-for-meme-magic-with-kinemaster/"><u>Top Tips for Meme Magic with KineMaster</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-step-up-your-slow-mo-game-expert-guide-for-amazing-android-videos/"><u>[New] Step Up Your Slow Mo Game  Expert Guide for Amazing Android Videos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-harnessing-digital-artistry-top-6-nft-makers-reviewed/"><u>2024 Approved  Harnessing Digital Artistry - Top 6 NFT Makers Reviewed</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-boosting-bank-balance-crafting-commercial-video-content/"><u>[Updated] Boosting Bank Balance  Crafting Commercial Video Content</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-mastering-insta-photo-and-video-reposts/"><u>[New] In 2024, Mastering Insta Photo & Video Reposts</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-samsung-galaxy-m34-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Samsung Galaxy M34 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-ultimate-top-10-tools-for-professional-tiktok-editors-pc-for-2024/"><u>[Updated] Ultimate Top 10 Tools for Professional TikTok Editors (PC) for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-inspire-audiences-with-these-high-quality-free-sound-files/"><u>[Updated] Inspire Audiences with These High-Quality, Free Sound Files</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-compact-mp3-skype-archive-on-the-cheap/"><u>[New] In 2024, Compact MP3 Skype Archive on the Cheap</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/stepwise-guide-integrating-subtitles-into-your-vimeo-content-for-2024/"><u>Stepwise Guide  Integrating Subtitles Into Your Vimeo Content for 2024</u></a></li>
</ul></div>
