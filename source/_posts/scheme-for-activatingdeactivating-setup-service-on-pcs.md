---
title: Scheme for Activating/Deactivating Setup Service on PCs
date: 2024-11-11T22:50:07.657Z
updated: 2024-11-17T20:55:35.630Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Scheme for Activating/Deactivating Setup Service on PCs
excerpt: This Article Describes Scheme for Activating/Deactivating Setup Service on PCs
keywords: Setup Service On PC,PC Service Activation,Deactivate PC Service,Enable PC Service,Disable PC Service,System Service Control,PC Service Scheme
thumbnail: https://thmb.techidaily.com/bbf8dc401e219ae9c8c406079b4bb91863628883caa9b7dda7f853c7436ac508.jpg
---

## Scheme for Activating/Deactivating Setup Service on PCs

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
<a href="https://25home.pxf.io/c/5597632/2148635/16836" target="_top" id="2148635">
  <img src="//a.impactradius-go.com/display-ad/16836-2148635" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148635/16836" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134221/18498" target="_top" id="2134221">
  <img src="//a.impactradius-go.com/display-ad/18498-2134221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134221/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Under Options, click the drop-down menu and select**Always** .
6. Then click**Apply** and**OK** to save changes.

 That's all there is to it. The Windows Installer service will now be disabled on your system. To re-enable it, simply follow the same steps, but set "Turn off Windows Installer" to**Not Configured** .

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
<a href="https://homestyler.sjv.io/c/5597632/1943750/22993" target="_top" id="1943750">
  <img src="//a.impactradius-go.com/display-ad/22993-1943750" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://homestyler.sjv.io/i/5597632/1943750/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you put the Value data, make sure the Base is set to**Hexadecimal** , then click**OK** . Now close the registry editor and restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082533/7443" target="_top" id="2082533">
  <img src="//a.impactradius-go.com/display-ad/7443-2082533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082533/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-daily-dharma-the-best-yoga-channels-for-self-growth/"><u>[New] 2024 Approved Daily Dharma The Best Yoga Channels for Self-Growth</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-elevate-your-video-visibility-11-secrets-of-successful-seo-for-2024/"><u>[New] Elevate Your Video Visibility 11 Secrets of Successful SEO for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-trendsetting-techniques-going-viral-in-the-digital-world/"><u>[New] In 2024, Trendsetting Techniques Going Viral in the Digital World</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-miniature-homes-6-top-oriental-designs-for-mcers/"><u>[New] Miniature Homes 6 Top Oriental Designs for MCers</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-brainless-battles-top-8-zombie-shooter-contenders/"><u>[Updated] 2024 Approved Brainless Battles Top 8 Zombie Shooter Contenders</u></a></li>
<li><a href="https://win11.techidaily.com/concealing-clock-and-dates-on-window-11s-bar/"><u>Concealing Clock & Dates on Window 11'S Bar</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-windows-blue-screen-alerts-an-in-depth-study/"><u>Dissecting Windows Blue Screen Alerts: An In-Depth Study</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-workflow-with-psoft-tools-in-win11/"><u>Enhance Your Workflow with PSoft Tools in Win11</u></a></li>
<li><a href="https://techtrends.techidaily.com/fix-your-frozen-chromebook-with-these-8-proven-techniques/"><u>Fix Your Frozen Chromebook with These 8 Proven Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/guide-enabling-access-in-windows-11-credentials/"><u>Guide: Enabling Access in Windows 11 Credentials</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-your-cursor-a-star-on-windows-devices/"><u>How to Make Your Cursor a Star on Windows Devices</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-compliance-in-recording-video-streams-on-youtube/"><u>In 2024, Compliance in Recording Video Streams on YouTube</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/kindle-oasis-2019-review-a-paper-like-reading-experience/"><u>Kindle Oasis (2019) Review: A Paper-Like Reading Experience</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-shutdown-of-startup-programs-via-revo-uninstaller-tutorial/"><u>Mastering the Shutdown of Startup Programs via Revo Uninstaller Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/method-for-deactivating-hyper-v-on-win11/"><u>Method for Deactivating Hyper-V on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-snip-and-sketchs-screen-shot-limitations-4-essential-fixes/"><u>Overcoming Snip & Sketch's Screen Shot Limitations: 4 Essential Fixes.</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-w11s-erroneous-temporary-files/"><u>Reviving Your W11's Erroneous Temporary Files</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-headphone-hum-steps-to-remove-annoying-buzz-from-audio-devices/"><u>Troubleshooting Headphone Hum: Steps to Remove Annoying Buzz From Audio Devices</u></a></li>
<li><a href="https://win11.techidaily.com/turn-on-calculators-night-mode/"><u>Turn On Calculator's Night Mode</u></a></li>
</ul></div>

