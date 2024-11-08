---
title: Scheme for Activating/Deactivating Setup Service on PCs
date: 2024-11-05T20:19:42.262Z
updated: 2024-11-07T19:58:18.806Z
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
<a href="https://appsumo.8odi.net/c/5597632/2043856/7443" target="_top" id="2043856">
  <img src="//a.impactradius-go.com/display-ad/7443-2043856" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043856/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135417/19272" target="_top" id="2135417">
  <img src="//a.impactradius-go.com/display-ad/19272-2135417" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135417/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2094480/7443" target="_top" id="2094480">
  <img src="//a.impactradius-go.com/display-ad/7443-2094480" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094480/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you put the Value data, make sure the Base is set to**Hexadecimal** , then click**OK** . Now close the registry editor and restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137215/26400" target="_top" id="2137215">
  <img src="//a.impactradius-go.com/display-ad/26400-2137215" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137215/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-techniques.techidaily.com/new-fastest-on-ice-olympic-highlights-in-short-track-events/"><u>[New] Fastest on Ice Olympic Highlights in Short Track Events</u></a></li>
<li><a href="https://article-files.techidaily.com/new-in-2024-elevating-your-workflow-optimizing-googles-podcast-submission-system/"><u>[New] In 2024, Elevating Your Workflow Optimizing Google's Podcast Submission System</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-complete-guide-to-optimizing-your-picsart-experience/"><u>[Updated] In 2024, Complete Guide to Optimizing Your PicsArt Experience</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-avoiding-upside-down-videos-in-your-instagram-feed/"><u>2024 Approved Avoiding Upside-Down Videos in Your Instagram Feed</u></a></li>
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-nokia-c12-plus-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Nokia C12 Plus | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/delayed-windows-11-shutdown-techniques-amidst-running-programs/"><u>Delayed Windows 11 Shutdown Techniques Amidst Running Programs</u></a></li>
<li><a href="https://discover-hacks.techidaily.com/enhance-your-livestreams-using-manycam-features-of-a-professional-webcam-plugin/"><u>Enhance Your Livestreams Using ManyCam - Features of a Professional Webcam Plugin</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-a-smooth-in-place-windows-11-update/"><u>Expert Tips for a Smooth, In-Place Windows 11 Update</u></a></li>
<li><a href="https://win11.techidaily.com/fix-hidden-additional-monitor-in-windows/"><u>Fix Hidden Additional Monitor in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-cortana-on-windows-using-vivetool-guide/"><u>How to Enable Cortana on Windows Using ViveTool Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-empty-directory-assertion-eradicate-error-0x80070091/"><u>Mastering Windows' Empty Directory Assertion - Eradicate Error 0X80070091</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/second-chance-languages-embrace-polyglot-living/"><u>Second Chance Languages: Embrace Polyglot Living</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-pick-gaming-systems-ultimate-ranking-guide/"><u>Top Pick Gaming Systems : Ultimate Ranking Guide</u></a></li>
<li><a href="https://tech-haven.techidaily.com/transform-your-dandd-adventures-with-chatgpt-enhancements/"><u>Transform Your D&D Adventures with ChatGPT Enhancements</u></a></li>
<li><a href="https://win11.techidaily.com/win-11s-swift-apk-installation-how-to-do-it/"><u>Win 11'S Swift APK Installation: How to Do It</u></a></li>
</ul></div>

