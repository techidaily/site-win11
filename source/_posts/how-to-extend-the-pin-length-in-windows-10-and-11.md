---
title: How to Extend the PIN Length in Windows 10 & 11
date: 2024-09-05T08:37:48.657Z
updated: 2024-09-06T08:37:48.657Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Extend the PIN Length in Windows 10 & 11
excerpt: This Article Describes How to Extend the PIN Length in Windows 10 & 11
keywords: Extending PIN Length Windows,Maximize Windows Pincode Size,Increase Windows Security Code,Windows PIN Expansion Tips,Optimizing Windows Pin Length,Enhancing Windows Lock Screen,Adjusting Windows Keyboard Security
thumbnail: https://thmb.techidaily.com/cfaa471734b434d1f940355dfb1b76c8db9d162f456d0da8fe799d1c6ecd8924.jpg
---

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134500/19576" target="_top" id="2134500">
  <img src="//a.impactradius-go.com/display-ad/19576-2134500" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134500/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Extend the PIN Length in Windows 10 & 11

 Windows Hello enables users to sign into Windows 11/10 accounts with PINs. That feature restricts users to four-character PINs by default. There isn’t an option available within the Change your PIN box to set a longer PIN that includes more than four characters.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.

## How to Extend the PIN Length by Editing the Registry

 Windows 11/10 Home doesn’t have any built-in setting for extending the minimum PIN length. So, many users will have to extend PIN length by creating a new PINComplexity registry key. Then you can set a new minimum PIN length value within that key. You can extend the Windows Hello PIN length by editing the registry as follows:

1. To view the file finder tool, press that utility’s **Win + S** keyboard shortcut.
2. Type **regedit** in the file search box and select its result to [open Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Enter this path inside Registry Editor’s address bar and press **Return**:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\`
4. If the Microsoft key doesn’t have a PassportForWork subkey, you’ll need to set one up. To do so, right-click on the Microsoft key and select **New** \> **Key**.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/new-key-options3.jpg)
5. Type **PassportForWork** in the new key’s text box.

1. Next, right-click on the **PassportForWork** key to select the **New** and **Key** options on Registry Editor’s context menu.
2. Enter **PINComplexity** inside the key’s text box to set that name.
3. Right-click the **PINComplexity** key to select **New** \> **DWORD (32-bit) Value**.
4. Enter **MinimumPINLength** in the DWORD text box.  
![The MinimumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/minimum-pin-length-dword.jpg)
5. Double-click the new **MinimumPINLength** DWORD you’ve created.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118325/7443" target="_top" id="2118325">
  <img src="//a.impactradius-go.com/display-ad/7443-2118325" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118325/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Select the **Decimal** option.
2. Then input a number higher than four in the **Value data** box and click **OK**. The value you enter there will be the new minimum character length for the Windows Hello PIN.  
![The Edit DWORD window for the MinimumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window4.jpg)
3. You can also set a maximum PIN length. To do so, right-click **PINComplexity** again and select the **DWORD (32-bit) Value** option on the **New** submenu.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2135476/26400" target="_top" id="2135476">
  <img src="//a.impactradius-go.com/display-ad/26400-2135476" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2135476/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Type **MaximumPINLength** into the DWORD’s text box.  
![A MaximumPINLength DWORD text box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/maximum-pin-length-text-box.jpg)
5. Double-click **MaximumPINLength** to view the **Value box** for that DWORD.
6. Click on the **Decimal** radio button.
7. Enter a number higher than the one set for the **MinimumPINLength** DWORD and select **OK**.  
![The Edit DWORD window for the MaximumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window-for-maximum-pin-length.jpg)
8. Finally, exit the Registry Editor window and restart your PC.
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135366/19272" target="_top" id="2135366">
  <img src="//a.impactradius-go.com/display-ad/19272-2135366" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135366/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now you’ll see an “organization requires that you change your PIN message” when you try to sign in with the PIN usually entered. Click **OK** to view some options for setting a new PIN. Then input a longer identification number with the minimum number of characters required inside the **New** and **Confirm** PIN boxes.

![The change your PIN message](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sign-in-message.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136621/26400" target="_top" id="2136621">
  <img src="//a.impactradius-go.com/display-ad/26400-2136621" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136621/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you’ve not set a Windows Hello PIN before, you can do so via Settings. Our guide to [setting a PIN in Windows](https://www.makeuseof.com/setup-remove-pin-windows-11/) includes instructions for how to do so. Your PIN must have the minimum number of characters set with the **PINComplexity** registry key.

## How to Extend the PIN Length With Group Policy Editor

 Windows Pro and Enterprise editions have a Group Policy Editor tool that includes options for setting minimum and maximum PIN lengths. So, you don’t need to manually edit the registry to set a minimum PIN length if you can access Group Policy Editor. This is how to extend Windows Hello’s PIN length with Group Policy Editor:

1. Press **Windows** logo key + **R** and enter **gpedit.msc** in Run.
2. Click on Run’s **OK** button to [access Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
3. Double-click on **Computer Configuration** in the left sidebar.
4. Next, double-click **Administrative Templates** to extend it.  
![Administrative Templates in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/administrative-templates.jpg)
5. Then click the arrow by **System** and select **PIN Complexity**.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137214/26400" target="_top" id="2137214">
  <img src="//a.impactradius-go.com/display-ad/26400-2137214" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137214/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Double-click on the **Minimum PIN Length** policy.  
![The PIN Complexity policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/pin-complexity.jpg)
2. Click the **Enabled** radio button to activate a **Minimum PIN Length** box.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118321/7443" target="_top" id="2118321">
  <img src="//a.impactradius-go.com/display-ad/7443-2118321" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118321/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Then input a higher value in the **Minimum PIN Length** box.  
![The Minimum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/minimum-pin-length-policy.jpg)
4. Select **Apply** and **OK** to set the new PIN length policy.
5. You can also set a max PIN length much the same by clicking the **Maximum PIN Length** policy, selecting **Enabled**, and inputting a new value. Then click on **Apply** and **OK** within the Maximum PIN length window.  
![The Maximum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/maximum-pin-length-policy.jpg)

## Extend Your Windows PIN to Make It More Secure

 Extending the minimum PIN length for logging in to Windows with one of the methods above is a good security measure. The longer your Windows Hello PIN is, the more secure your PC will be. However, an overly long PIN will be harder to remember. So, don’t make your PIN too long!

 Windows Hello also enables users to set alternative biometric authentication. Fingerprint or retina authentication types are more advanced Windows Hello features than PINs. However, you’ll need a PC that supports such biometric security features to enable them.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-discovering-the-potential-of-next-gen-srt-systems/"><u>[New] Discovering the Potential of Next-Gen SRT Systems</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-how-to-angle-videos-for-improved-viewership-for-2024/"><u>[New] How to Angle Videos for Improved Viewership for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-architectural-marvels-best-6-mojave-homes/"><u>[Updated] Architectural Marvels  Best 6 Mojave Homes</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-asmr-app-selection-guide-for-phones/"><u>[Updated] In 2024, ASMR App Selection Guide for Phones</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-use-youtube-enhancements/"><u>[Updated] In 2024, How to Use YouTube Enhancements</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-best-5-chromebook-screen-capture-tools-unveiled/"><u>2024 Approved  Best 5 Chromebook Screen Capture Tools Unveiled</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-your-step-by-step-pathway-to-youtube-video-enhancement/"><u>2024 Approved  Your Step-By-Step Pathway to YouTube Video Enhancement</u></a></li>
<li><a href="https://win11.techidaily.com/deciding-on-the-usefulness-of-windows-11-s-mode/"><u>Deciding on the Usefulness of Windows 11 S Mode</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-filesize-metrics-with-powershell-techniques/"><u>Decoding Filesize Metrics with PowerShell Techniques</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/elevate-your-broadcast-impact-with-these-5-tips-for-twitch-streamers/"><u>Elevate Your Broadcast Impact with These 5 Tips for Twitch Streamers</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-data-management-combine-on-windows-11/"><u>Elevate Your Data Management: Combine on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-workflow-best-wsl-2-practices-in-windows/"><u>Elevate Your Workflow: Best WSL 2 Practices in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-autonomous-command-line-emergence-in-os/"><u>Eliminating Autonomous Command Line Emergence in OS</u></a></li>
<li><a href="https://extra-information.techidaily.com/engage-fully-with-podcasts-15-essential-tasks/"><u>Engage Fully with Podcasts  15 Essential Tasks</u></a></li>
<li><a href="https://win11.techidaily.com/enhanced-efficiency-integrating-to-dot-and-ifttt/"><u>Enhanced Efficiency: Integrating To-Dot & IFTTT</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-your-windows-snipping-experience-with-proven-fixes/"><u>Enhancing Your Windows Snipping Experience with Proven Fixes.</u></a></li>
<li><a href="https://common-error.techidaily.com/errcachemiss-error-solutions-for-a-smooth-chrome-experience/"><u>ERR_CACHE_MISS Error Solutions for a Smooth Chrome Experience</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-your-computers-core-creating-and-analyzing-reports/"><u>Exploring Your Computer's Core: Creating & Analyzing Reports</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-index-settings-on-windows/"><u>Fine-Tuning Index Settings on Windows</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/guard-your-video-calls-the-ultimate-list-of-free-security-enhanced-applications/"><u>Guard Your Video Calls  The Ultimate List of Free Security-Enhanced Applications</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-download-speed-suddenly-dropping-to-zero-on-steam-for-windows/"><u>How to Fix the Download Speed Suddenly Dropping to Zero on Steam for Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-get-out-of-recovery-on-apple-iphone-12-mini-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Get Out of Recovery on Apple iPhone 12 mini? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-oculus-setup-failures-in-windows-11-and-10/"><u>How to Overcome Oculus Setup Failures in Windows 11 & 10</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-unleashing-potential-top-8-efficiency-boosters-for-social-media-tasks/"><u>In 2024, Unleashing Potential  Top 8 Efficiency Boosters for Social Media Tasks</u></a></li>
<li><a href="https://win11.techidaily.com/launching-a-linux-vm-via-hyper-v-in-windows-environment/"><u>Launching a Linux VM via Hyper-V in Windows Environment</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/leading-cloud-data-platforms-ranked-your-guide-to-the-superior-options/"><u>Leading Cloud Data Platforms Ranked: Your Guide to the Superior Options</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-art-of-remote-pc-awakening-on-windows-11-using-wake-on-lan/"><u>Mastering the Art of Remote PC Awakening on Windows 11 Using Wake-on-LAN</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-resolving-preview-errors-in-windows-outlook/"><u>Mastering the Art of Resolving Preview Errors in Windows Outlook</u></a></li>
<li><a href="https://fake-location.techidaily.com/methods-to-change-gps-location-on-realme-10t-5g-drfone-by-drfone-virtual-android/"><u>Methods to Change GPS Location On Realme 10T 5G | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/naming-your-podcast-to-perfection-stepwise-guidance-plus-top-ideas-list-for-2024/"><u>Naming Your Podcast to Perfection  Stepwise Guidance + Top Ideas List for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-no-mistakes-top-10-windows-11-errors-to-evade/"><u>Navigating No Mistakes: Top 10 Windows 11 Errors to Evade</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-vac-failure-in-steam-gaming/"><u>Navigating Through VAC Failure in Steam Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/prime-time-deal-black-friday-612-endless-windows-10/"><u>Prime Time Deal: Black Friday - $6.12, Endless Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-failures-in-windows-defrag-process/"><u>Remedying Failures in Windows Defrag Process</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-unzipped-problems-with-these-easy-steps-for-win-11/"><u>Resolve Unzipped Problems with These Easy Steps for Win 11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/resolving-the-issue-solutions-when-you-cant-find-mapi32dll-file/"><u>Resolving the Issue: Solutions When You Can't Find MAPI32.DLL File</u></a></li>
<li><a href="https://fix-guide.techidaily.com/spotify-keeps-crashing-a-complete-list-of-fixes-you-can-use-on-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Spotify Keeps Crashing A Complete List of Fixes You Can Use on Xiaomi Redmi Note 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/stabilizing-your-mouse-pointer-on-windows-10/"><u>Stabilizing Your Mouse Pointer on Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-adding-bespoke-pattern-loops-for-windows-pin/"><u>Step-by-Step: Adding Bespoke Pattern Loops for Windows PIN</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-solve-windows-email-application-error-code-0x800713f/"><u>Steps to Solve Windows' Email Application Error (Code 0X800713F)</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-typing-how-to-adjust-windows-key-filters/"><u>Streamlining Typing: How to Adjust Windows' Key Filters</u></a></li>
<li><a href="https://win11.techidaily.com/taming-your-typhoon-mouse-traveling/"><u>Taming Your Typhoon Mouse Traveling</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-collection-6-top-notch-fps-software-for-windows-11/"><u>The Ultimate Collection: 6 Top-Notch FPS Software for Windows 11</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshooting-installation-issues-solving-age-of-empires-iv-download-errors/"><u>Troubleshooting Installation Issues: Solving 'Age of Empires IV' Download Errors</u></a></li>
<li><a href="https://fox-access.techidaily.com/turning-talk-into-top-tier-podcasts-writing-and-samples-included/"><u>Turning Talk Into Top-Tier Podcasts  Writing & Samples Included</u></a></li>
<li><a href="https://buynow-help.techidaily.com/ultimate-guide-sony-ps4-pro-4k-graphics-performance-analysis/"><u>Ultimate Guide: Sony PS4 Pro 4K Graphics Performance Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/uniting-two-network-types-a-comprehensive-windows-guide/"><u>Uniting Two Network Types: A Comprehensive Windows Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-11s-web-interface-controls/"><u>Unveiling Windows 11'S Web Interface Controls</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-icon-alignment-guide-unite-not-bind/"><u>Win 11 Icon Alignment Guide - Unite Not Bind</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-beta-access-the-insider-program-guide/"><u>Windows 11'S Beta Access: The Insider Program Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>