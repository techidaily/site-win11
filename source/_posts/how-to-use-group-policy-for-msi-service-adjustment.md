---
title: How to Use Group Policy for MSI Service Adjustment
date: 2024-10-31T21:06:37.077Z
updated: 2024-11-07T21:51:03.923Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Use Group Policy for MSI Service Adjustment
excerpt: This Article Describes How to Use Group Policy for MSI Service Adjustment
keywords: GroupPolicyMSISvcAdj,MSIServiceGroupControl,GroupPolicyMSIService,ServiceAdjustmentGPO,ManageMSIServices,GPOMSIConfigure,PolicyForMSIService
thumbnail: https://thmb.techidaily.com/c88c76635d5e0629581e4fd4108916cee892ed1d438b3013953d19ca906db797.jpg
---

## How to Use Group Policy for MSI Service Adjustment

 Are you looking for a way to disable the Windows Installer Service on your device? This essential component of your operating system performs all necessary installation processes, but can sometimes interfere with other programs.

 Fortunately, there are three ways in which it can be disabled—using the Windows Service tool, Group Policy Editor, or Registry Editor. Check out our guide below to learn how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Use Windows Services

 Windows services are critical programs that typically initiate when you start your computer. It runs silently in the background and provides essential features to run the operating system. If you're looking to enable or disable Windows Installer service using this tool, do the following.

 To begin, press**Win + R** on your keyboard to launch the Run dialog box. In the text box, type**services.msc** , and hit enter. This will open the Services window.

![Disable Windows Installer Service Using Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-services-window.jpg)

 In the window that opens, scroll down until you find**Windows Installer** service then double-click on it for a properties window to open.

 Once you're in the Properties window, click the**Startup type** drop-down menu and select**Automatic** . Now move over towards the**Service status** section and click**Stop** .

![Disable Windows Installer Service Using Windows Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-windows-services.jpg)

 After you've done that, click**Apply** and then**OK** to save the changes. You have now successfully disabled the Windows Installer service on Windows 11.

 If you ever need to re-enable the service, follow the same procedure and click**Start** in the Service status section.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135410/19272" target="_top" id="2135410">
  <img src="//a.impactradius-go.com/display-ad/19272-2135410" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135410/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Use Local Group Policy Editor

 You can also use the group policy editor to enable or disable the Windows Installer service on your Windows computer system. However, it is important to note that this tool only works on Windows Pro and Enterprise editions. Therefore, if you are using Windows Home Edition, you must first[activate the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) .

 To disable the service using the group policy editor, do the following:

1. Click on Start and type in**gpedit.msc** , then press**Enter** to[launch the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) .
2. On the left side of the window, navigate to the path:  
`Computer Configuration > Administrative Templates > Windows Components > Windows Installer`
3. Now move to the right and double-click on the policy named**Turn off Windows Installer** .  
![Disable Windows Installer Service Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-group-policy.jpg)
4. In the window that opens, select**Enabled** in the radio box.
5. Under Options, click the drop-down menu and select**Always** .
6. Then click**Apply** and**OK** to save changes.

 That's all there is to it. The Windows Installer service will now be disabled on your system. To re-enable it, simply follow the same steps, but set "Turn off Windows Installer" to**Not Configured** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886044/19272" target="_top" id="1886044">
  <img src="//a.impactradius-go.com/display-ad/19272-1886044" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886044/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Use the Registry Editor

 Registry Editor is another method you can use to enable or disable the Windows Installer service on any version of Windows, even Home Edition. But make sure to proceed with caution as any incorrect changes can corrupt your system and force you to reinstall Windows. So be mindful and remember to back up your registry before making any modifications.

 To enable or disable this service using Registry Editor, follow these steps:

1. Press**Win + X** , type**regedit** , and press**Enter** to launch the Registry Editor. To learn more, see our guide on how to[open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. If prompted with a UAC warning, click**Yes** to continue.
3. Now once you're in, navigate to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\msiserver`
4. In the right panel, double-click on**Start** and change its value from**2** to**4** .  
![Disable Windows Installer Service Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-installer-service-using-registry-editor.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148636/16836" target="_top" id="2148636">
  <img src="//a.impactradius-go.com/display-ad/16836-2148636" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148636/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you put the Value data, make sure the Base is set to**Hexadecimal** , then click**OK** . Now close the registry editor and restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139113/17108" target="_top" id="2139113">
  <img src="//a.impactradius-go.com/display-ad/17108-2139113" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139113/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Turning Off the Windows Installer Service Made Easy

 If Windows Installer Service is creating issues or hindering another application, you can easily turn it off with one of the three methods outlined in our guide. See which method works best for you and get back to what matters most.

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
<li><a href="https://fox-glue.techidaily.com/new-in-2024-ultimate-avi-player-the-perfect-match-for-pcmobile/"><u>[New] In 2024, Ultimate AVi Player The Perfect Match for PC/Mobile</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-unrestricted-display-save-tool/"><u>[Updated] 2024 Approved Unrestricted Display Save Tool</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ai-writes-the-future-top-5-unseen-power-ups-for-conversations/"><u>AI' Writes the Future: Top 5 Unseen Power-Ups for Conversations</u></a></li>
<li><a href="https://extra-resources.techidaily.com/competing-camerasdrones-gopro-max-dji-action-insta360/"><u>Competing Cameras/Drones GoPro Max, DJi Action, Insta360</u></a></li>
<li><a href="https://win11.techidaily.com/curtail-self-starting-file-explorer-behavior/"><u>Curtail Self-Starting File Explorer Behavior</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-addressing-windows-error-code-0xc0000001/"><u>Decoding and Addressing Windows Error Code 0XC0000001</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-leading-4-windows-apps-for-easy-webp-viewing/"><u>Discover the Leading 4 Windows Apps for Easy WebP Viewing</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unlock-and-fix-frozen-screensaver-on-pc/"><u>How to Unlock and Fix Frozen Screensaver on PC</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-turn-off-google-location-to-stop-tracking-you-on-apple-iphone-13-mini-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Turn Off Google Location to Stop Tracking You on Apple iPhone 13 mini | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-the-dxgi-device-removal-issue/"><u>Mitigating the DXGI Device Removal Issue</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/1726027075413-pc/"><u>PCやスマートフォンでビデオの音量調整 -音なし/無音設定ガイド</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/pivoting-from-srt-to-subtitle-format-for-2024/"><u>Pivoting From SRT to Subtitle Format for 2024</u></a></li>
<li><a href="https://fox-ssl.techidaily.com/restore-accidentally-deleted-files-a-guide-to-efficient-methods-in-windows-operating-systems/"><u>Restore Accidentally Deleted Files: A Guide to Efficient Methods in Windows Operating Systems</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-file-merging-techniques-for-modern-windows-users/"><u>Seamless File Merging Techniques for Modern Windows Users</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/share-wisdom-4-proven-methods-to-tie-fb-stories-for-2024/"><u>Share Wisdom 4 Proven Methods to Tie FB Stories for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-overcoming-package-access-problems-in-ws11ws10/"><u>Step-by-Step Guide to Overcoming Package Access Problems in WS11/WS10</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-reset-tutorial-for-your-pc-graphics-driver/"><u>Step-by-Step Reset Tutorial for Your PC Graphics Driver</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/tivo-or-comcast-the-ultimate-guide-to-choosing-the-best-dvr-for-your-needs-for-2024/"><u>TiVo or Comcast The Ultimate Guide to Choosing the Best DVR for Your Needs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-access-adobe-ps-not-opening-in-latest-windows/"><u>Unblocking Access: Adobe PS Not Opening in Latest Windows</u></a></li>
</ul></div>

