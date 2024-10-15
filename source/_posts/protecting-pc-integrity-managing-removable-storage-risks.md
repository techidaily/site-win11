---
title: "Protecting PC Integrity: Managing Removable Storage Risks"
date: 2024-10-13T18:43:50.669Z
updated: 2024-10-15T19:59:02.518Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Protecting PC Integrity: Managing Removable Storage Risks"
excerpt: "This Article Describes Protecting PC Integrity: Managing Removable Storage Risks"
keywords: PC Security,Remove Risk,Data Safety,USB Protection,Secure Storages,Hardware Integrity,Removable Storage Management
thumbnail: https://thmb.techidaily.com/371f85ea9dfa1babb000dca91773b4eb09149fff5b762b5c34efcbd5187b5306.jpg
---

## Protecting PC Integrity: Managing Removable Storage Risks

 Want to prevent others from stealing your PC data through removable storage devices? Or do you want to protect your device from harmful files contained on removable storage devices?

 In this article, we’ll explore how you can prevent others from installing removable storage devices on Windows. That way, your device won't read any removable storage devices without your permission. Lastly, we’ll also show you how to allow others to install specific removable storage devices.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Prevent Others From Installing Any Removable Storage Devices

 Let's start by checking out how you can prevent others from installing any removable storage device into your PC. You can do this using either the Local Group Policy Editor or the Registry Editor.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2044583/7443" target="_top" id="2044583">
  <img src="//a.impactradius-go.com/display-ad/7443-2044583" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044583/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Using the Local Group Policy Editor

![Using a Windows laptop on a brown desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Using-a-Windows-laptop-on-a-brown-desk.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915805/19272" target="_top" id="1915805">
  <img src="//a.impactradius-go.com/display-ad/19272-1915805" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915805/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The Local Group Policy Editor (LGPE) is a reliable tool for troubleshooting system errors. Interestingly, you can also use it for other tasks such as [preventing others from changing your Windows desktop background](https://www.makeuseof.com/stop-others-change-windows-desktop-background/).

 Now, here’s how to use the LGPE to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **gpedit.msc** and press **Enter** to open the LGPE.
3. Navigate to **Computer Configuration > Administrative Templates > System > Device Installation > Device Installation Restrictions**.
4. Double-click on the **Prevent installation of removable devices** option on the right-hand side.

![Clicking the prevent installation of removable devices option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-prevent-installation-of-removable-devices-option.jpg)

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098701/14409" target="_top" id="2098701">
  <img src="//a.impactradius-go.com/display-ad/14409-2098701" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098701/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Select **Enabled** on the next screen to prevent others from installing removable storage devices into your PC. Alternatively, select **Disabled** or **Not Configured** to restore the default settings.

 Finally, press **Apply** and then press **OK** to save these changes.

 Struggling to access the LGPE on Windows Home? There are a few tricks you can apply to [access the LGPE on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). But if that sounds complicated to you, then skip to the Registry Editor method.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144271/7443" target="_top" id="2144271">
  <img src="//a.impactradius-go.com/display-ad/7443-2144271" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144271/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Using the Registry Editor

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 The Registry Editor is another reliable tool you can use for tweaking system settings and troubleshooting PC issues.

 However, this tool is quite sensitive. So, it’s often worth [backing up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first before editing its keys.

 Now, here’s how to use the Registry Editor to prevent others from installing removable storage devices on Windows:

1. Press **Win + R** to open the Run command dialog box.
2. Type **Regedit** and press **Enter** to open the Registry Editor.
3. Copy-paste the following command into the address bar and press **Enter**:

HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows

 From there, follow these steps:

1. Right-click on the **Windows** folder and select **New > Key**. From there, name this key as **DeviceInstall** and press **Enter**.
2. Right-click on the **DeviceInstall** key and select **New > Key**. Next, name the key as **Restrictions** and press **Enter**.
3. Click the **Restrictions** folder, right-click on a blank space on the right, and then select **New > DWORD (32-bit) Value**. From there, name the value as **DenyRemovableDevices** and press **Enter**.

![Clicking the DenyRemovableDevices value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Clicking-the-DenyRemovableDevices-value.jpg)

 Now, follow these steps:

1. Double-click on the **DenyRemovableDevices** value.
2. Set the **Value data** as **1** and then press **OK** to prevent others from installing storage devices into your PC. Alternatively, set the **Value data** as **0** and press **OK** to allow others to install removable storage devices on your PC.
3. Close the Registry Editor and restart your device to save these changes.

## How to Prevent Others From Installing Specific Removable Storage Devices

 In some instances, you might want to prevent others from installing specific removable storage devices. So, let’s show you how you can do that using either the LGPE or the Registry Editor.

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
<li><a href="https://article-tips.techidaily.com/new-2024-approved-captivating-readers-with-the-top-5-engaging-book-trailers/"><u>[New] 2024 Approved Captivating Readers with the Top 5 Engaging Book Trailers</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-mindful-meandering-leisurely-pc-games/"><u>[New] Mindful Meandering Leisurely PC Games</u></a></li>
<li><a href="https://tech-hub.techidaily.com/2024s-elite-iphones-unveiled-in-depth-expert-evaluations-and-rankings-zdnet/"><u>2024'S Elite iPhones Unveiled: In-Depth Expert Evaluations and Rankings | ZDNET</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/3-solutions-to-find-your-apple-iphone-14-plus-current-location-of-a-mobile-number-drfone-by-drfone-virtual-ios/"><u>3 Solutions to Find Your Apple iPhone 14 Plus Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/elevate-your-computer-game-learning-windows-shorthand/"><u>Elevate Your Computer Game: Learning Windows Shorthand</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/in-2024-2023s-leading-cameras-for-samsung-gear-360-successors/"><u>In 2024, 2023'S Leading Cameras for Samsung Gear 360 Successors</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-step-toward-balance-best-yoga-series-to-watch-and-learn-from/"><u>In 2024, Step Toward Balance Best Yoga Series to Watch and Learn From</u></a></li>
<li><a href="https://win11.techidaily.com/quick-track-to-success-5-straightforward-strategies-to-speed-up-your-youtube-content-sharing-process/"><u>Quick-Track to Success: 5 Straightforward Strategies to Speed up Your YouTube Content Sharing Process</u></a></li>
<li><a href="https://win11.techidaily.com/simple-guide-to-transforming-your-pds-videos-from-cyberlinks-powerdirector-into-popular-codecs-such-as-mp4-avi-or-wmv/"><u>Simple Guide to Transforming Your PDS Videos From Cyberlink's PowerDirector Into Popular Codecs Such as MP4, AVI or WMV</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-on-shortening-your-zoom-captures-managing-both-online-streams-and-offline-archives/"><u>Step-by-Step Guide on Shortening Your Zoom Captures - Managing Both Online Streams and Offline Archives</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-setting-up-gaia-version-610-on-your-kodi-nexus-and-matrix-units/"><u>Step-by-Step Guide to Setting Up Gaia Version 6.1.0 on Your Kodi Nexus and Matrix Units</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-securely-retrieve-and-save-private-video-clips-from-vimeo-online/"><u>Steps to Securely Retrieve and Save Private Video Clips From Vimeo Online</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-plex-playbook-setup-usage-and-optimization-tips/"><u>The Essential Plex Playbook: Setup, Usage & Optimization Tips</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/the-perfect-blend-stylish-form-with-crystal-clear-sound/"><u>The Perfect Blend: Stylish Form with Crystal Clear Sound</u></a></li>
<li><a href="https://win11.techidaily.com/top-11-video-converter-tools-compatible-with-windows-11-desktop-and-web-options/"><u>Top 11 Video Converter Tools Compatible with Windows 11: Desktop & Web Options</u></a></li>
<li><a href="https://win11.techidaily.com/top-25-best-free-online-movie-streaming-services-after-vumoo/"><u>Top 25 Best Free Online Movie Streaming Services After Vumoo</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unleash-the-power-of-digital-beats-with-our-free-tools-for-2024/"><u>Unleash the Power of Digital Beats with Our Free Tools for 2024</u></a></li>
</ul></div>

