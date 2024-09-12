---
title: Fixing Inadequate Memory Notifications in Virtual Machines
date: 2024-09-11T09:35:10.315Z
updated: 2024-09-12T09:35:10.315Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Inadequate Memory Notifications in Virtual Machines
excerpt: This Article Describes Fixing Inadequate Memory Notifications in Virtual Machines
keywords: VM Memory Alerts Fix,Boost VMM Notification,Enhance VM Memory Alarm,Correct VM Memory Halt,Improve VM Mem Notify,Optimize VM RAM Warnings,Amend Virtual Machine Notifications
thumbnail: https://thmb.techidaily.com/c8cdb9a666b994c5df18bf9fb906f435b3e886e46b814d7626bddc0615133ba1.jpg
---

## Fixing Inadequate Memory Notifications in Virtual Machines

 VMware Workstation is one of the best virtualization software packages for Windows. However, some users see an error message when they try to start virtual machines in VMware Workstation. That error message says, “not enough physical memory is available to power on this virtual machine,” and virtual machines won’t start up.

 This VMware issue can arise when there’s more than enough RAM available on a PC. However, there are numerous possible causes for the “not enough physical memory” error. This is how you can fix the “not enough physical memory” WMware error in Windows 10 and 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Configure VMware to Run as an Administrator

 Not running VMware as an administrator places restrictions on its system permissions and access to resources. So, run the software with elevated rights to ensure a lack of permissions isn’t causing any issues.

 You can check out[how to run any program as an administrator on Windows](https://www.makeuseof.com/tag/ways-to-run-a-program-as-administrator-in-windows/) for more help, or you can set VMware to always run as an administrator like this:

1. If there’s a VMware shortcut on your desktop, right-click it and select**Open** file location. Manually open VMware’s installation directory in File Explorer if you can’t right-click a shortcut for the software.
2. Then click the VMware EXE file with the right mouse button to select its**Properties** context menu option.
3. Select**Compatibility** to view that tab’s settings.
4. Click the checkbox for the**Run this program as administrator** option to select it.  
![The Compatibility tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-compatibility-tab2.jpg)
5. Select**Apply** to save the new administrator option for VMware.
6. Then select**OK** to close WMware’s properties window.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137976/21526" target="_top" id="2137976">
  <img src="//a.impactradius-go.com/display-ad/21526-2137976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137976/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Edit the Config File

 Lots of users have been able to fix the “not enough physical memory” by editing VMWare’s**config.ini** file. Those users disabled a Host parameter within the software’s configuration file. To disable that Host parameter, open and edit VMware’s**config.ini** file as follows:

1. Press**Win + E** to access File Explorer.
2. Open this VMware directory in Explorer:  
`C:\ProgramData\VMware\VMware Workstation`
3. Right-click the**config.ini** file and select**Open with** .  
![The Open with option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-open-with-option.jpg)
4. Select**Notepad** to view the configuration file in that text editor.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115926/19272" target="_top" id="2115926">
  <img src="//a.impactradius-go.com/display-ad/19272-2115926" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115926/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Then **input vmmon.disableHostParameters = “TRUE”** at the bottom of the configuration file as in the image below.  
![WMware's config.ini file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-config-ini-file.jpg)
6. Click**File** on Notepad’s menubar.

<!-- affiliate ads begin -->
<span id="1983539">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983539.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983539">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983539.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983539%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983539/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Select the menu’s**Save** option.  
![The Save option in Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-save-option-in-notepad.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132161/7443" target="_top" id="2132161">
  <img src="//a.impactradius-go.com/display-ad/7443-2132161" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132161/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Expand the Virtual Memory for the Virtual Machine

 The “not enough physical memory” error can occur because not enough virtual memory has been allocated to the virtual machine. You can expand a virtual machine’s memory allocation in VMWare like this:

1. Open your VMware software.
2. Right-click the virtual machine for which you need to fix the error and select**Settings** .
3. Increase the virtual machine’s memory allocation with the bar slider. That amount should always be higher than your PC’s available RAM.  
![The memory bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-memory-bar.jpg)
4. Click**OK** to apply.

## 4\. Update VMware

 The “not enough physical memory” error will more likely arise on outdated WMware versions. So, ensure you’re utilizing the latest version of the software. This is how you can update VMware:

1. Bring up the VMware window.
2. Click the**Help** menu.
3. Select**Software Updates** to view that window.  
![The Software Updates option in VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-software-updates-option.jpg)
4. Then click the**Check for Updates** button.  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137219/26400" target="_top" id="2137219">
  <img src="//a.impactradius-go.com/display-ad/26400-2137219" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137219/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Check for updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-check-for-updates-option4.jpg)
5. Press the**Get More Information** button for an available update.

1. Log into an account profile on the website that opens.
2. Select the**Download Now** option on the website for the latest VMware Workstation version.
3. Then you’ll need to select an**Accept** option for the EULA agreement.
4. Click another**Download Now** option.
5. Then click File Explorer’s taskbar shortcut.
6. Go to the downloads folder that includes the WMware setup wizard.
7. Double-click the downloaded VMware installer to open it. Go through the setup wizard to install the latest VMware version.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115935/19272" target="_top" id="2115935">
  <img src="//a.impactradius-go.com/display-ad/19272-2115935" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115935/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Delete a Recent Windows Update

 The “not enough physical memory” error can be caused by a Windows update that conflicts with VMware. So, uninstalling a recent update could fix that issue for some users. Check out our guide about[uninstalling Windows updates](https://www.makeuseof.com/windows-11-uninstall-updates/) for further details on how to apply this potential solution.

![The Installed Updates Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-uninstall-update-option.jpg)

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Perform a Clean Boot

 Performing a clean boot will disable non-essential apps and services from the Windows startup. Clean booting can potentially resolve the “not enough physical memory” in two ways. Applying this troubleshooting method will ensure there aren’t any third-party programs conflicting with VMware and free up RAM for the software.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-services-tab-in-msconfig.jpg)

 To disable all third-party startup programs and services, check out the guidelines in our guide on[how to clean boot in Windows](https://www.makeuseof.com/clean-boot-windows-11/) . This will perform a clean boot whenever you restart Windows.

 Try utilizing your VMware virtual machine after clean booting. If this works,

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135359/19272" target="_top" id="2135359">
  <img src="//a.impactradius-go.com/display-ad/19272-2135359" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135359/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Set Up a New Virtual Machine

 If the issue persists despite applying the resolutions above, consider setting up a new virtual machine to replace the one that needs fixing. Download the latest ISO for the virtual machine’s platform. Then you can set up the virtual machine again, as outlined on the[VMware support page](https://kb.vmware.com/s/article/1018415) .

## Jump Into Your WMware Virtual Machine Again

 Those Windows fixes for the “Not enough physical memory” error have worked for many VMware Workstation users. So, there’s a decent enough chance one will kick-start your VMWare virtual machine too. However, users who still need more possible fixes for this issue can submit a support request via the[VMware Customer Connect](https://customerconnect.vmware.com/home?bmctx=89E60DF848C641FD518EB9F6B9A6E5334F602FA3A762B409625CD531863AC847&password=secure%5Fstring&contextType=external&username=string&challenge%5Furl=https:%2F%2Fcustomerconnect.vmware.com%2Fhome&request%5Fid=-8453692679675997712&authn%5Ftry%5Fcount=0&locale=en%5FGB&resource%5Furl=https%253A%252F%252Fcustomerconnect.vmware.com%252Fweb%252Fvmware%252Fchecksession) page.

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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-elevate-your-snap-game-with-pro-level-boomerang-expertise/"><u>[New] 2024 Approved Elevate Your Snap Game with Pro-Level Boomerang Expertise</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-swift-to-stillness-the-art-of-timelapse-with-a-galaxy/"><u>[New] 2024 Approved Swift to Stillness The Art of Timelapse with a Galaxy</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-unlock-creative-filmmaking-instagrams-green-room-technique/"><u>[New] 2024 Approved Unlock Creative Filmmaking Instagram's Green Room Technique</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-expedited-pitch-modification-tools-repository/"><u>[New] Expedited Pitch Modification Tools Repository</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-quick-linking-sending-video-content-from-fb-to-whatsapp/"><u>[New] In 2024, Quick Linking Sending Video Content From FB to WhatsApp</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-samsungs-opponent-the-finest-non-gear-360-cameras/"><u>[New] Samsung's Opponent The Finest Non-Gear 360 Cameras</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-pro-tools-comparison-obs-and-twitch-studio/"><u>[Updated] 2024 Approved Pro Tools Comparison OBS and Twitch Studio</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-expert-tags-analyzer-software-fb-tweet-and-insta-edition/"><u>[Updated] Expert Tags Analyzer Software FB, Tweet & Insta Edition</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-comparing-easy-flexible-recording-tools-for-mac-users/"><u>[Updated] In 2024, Comparing Easy, Flexible Recording Tools for Mac Users</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-leading-8-mirrorless-cameras-for-youtube-creators/"><u>[Updated] In 2024, Leading 8 Mirrorless Cameras For YouTube Creators</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/4-ways-to-transfer-music-from-apple-iphone-15-pro-max-to-ipod-touch-drfone-by-drfone-transfer-from-ios/"><u>4 Ways to Transfer Music from Apple iPhone 15 Pro Max to iPod touch | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-cannot-create-window-errors-on-windows/"><u>Decoding the 'Cannot Create' Window Errors on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/disassembling-and-reassembling-windows-app-settings-for-success/"><u>Disassembling and Reassembling Windows App Settings for Success</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-data-from-huawei-nova-y71-by-fonelab-android-recover-data/"><u>Easy steps to recover deleted data from Huawei Nova Y71</u></a></li>
<li><a href="https://win11.techidaily.com/effective-booting-technique-startup-windows-unveil-notebooks/"><u>Effective Booting Technique: Startup Windows, Unveil Notebooks</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-your-workspace-individual-monitors-in-windows-11/"><u>Elevating Your Workspace: Individual Monitors in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/establish-prerequisites-before-vbox-installation/"><u>Establish Prerequisites Before VBox Installation</u></a></li>
<li><a href="https://win11.techidaily.com/fasten-the-toggling-of-microsofts-taskbar-integrated-chat/"><u>Fasten the Toggling of Microsoft’s Taskbar-Integrated Chat</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-failed-file-creation-on-win11s-camera-app/"><u>Fixing Failed File Creation on Win11's Camera App</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-open-the-driver-verifier-manager-in-windows-11/"><u>How to Open the Driver Verifier Manager in Windows 11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-mastering-past-facebook-feed-exploration-for-laptops-and-phones/"><u>In 2024, Mastering Past Facebook Feed Exploration for Laptops and Phones</u></a></li>
<li><a href="https://win11.techidaily.com/insight-guide-reviewing-and-removing-windows-history/"><u>Insight Guide: Reviewing & Removing Windows History</u></a></li>
<li><a href="https://fox-that.techidaily.com/iphone-muting-issues-a-comprehensive-guide-when-the-switch-fails-you/"><u>IPhone Muting Issues: A Comprehensive Guide When the Switch Fails You</u></a></li>
<li><a href="https://win11.techidaily.com/isolating-and-remedying-solo-sideheadphone-glitches-in-win/"><u>Isolating and Remedying Solo Sideheadphone Glitches in WIN</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-search-configurations-reset/"><u>Mastering Windows 11 Search Configurations Reset</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-pc-potential-through-processor-options/"><u>Maximizing PC Potential Through Processor Options</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-camera-error-a00f425d/"><u>Navigating Through Windows Camera Error A00F425D</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-subsystem-for-linux-solving-error-4294967295/"><u>Navigating Through Windows Subsystem for Linux: Solving Error 4294967295</u></a></li>
<li><a href="https://extra-skills.techidaily.com/next-gen-tech-talk-samsungs-bdplus-k850-ultra-review-for-2024/"><u>Next-Gen Tech Talk Samsung's BD+ K850 Ultra Review for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-windows-11-notes-for-universal-accessibility/"><u>Optimize Windows 11 Notes for Universal Accessibility</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-high-usage-chatgpt-alerts-on-pc/"><u>Overcoming High Usage ChatGPT Alerts on PC</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-blocked-by-admin-error-in-windows-setup/"><u>Overcoming the Blocked by Admin Error in Windows Setup</u></a></li>
<li><a href="https://win11.techidaily.com/shattered-scenery-9-ways-to-restore-win11-screen-snapshots/"><u>Shattered Scenery? 9 Ways to Restore Win11 Screen Snapshots</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-inactive-alerts-for-phone-link-app-on-windows-devices/"><u>Tackling Inactive Alerts for Phone Link App on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-microsoft-store-errors-the-quick-fix-for-0x80072efd/"><u>Tackling Microsoft Store Errors: The Quick Fix for 0X80072EFD</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-addressing-launch-failed-lunar-client-issues/"><u>Techniques for Addressing “Launch Failed Lunar Client” Issues</u></a></li>
<li><a href="https://win11.techidaily.com/temporary-user-profiles-avoiding-login-interruptions/"><u>Temporary User Profiles: Avoiding Login Interruptions</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-best-ispoofer-alternative-to-try-on-tecno-camon-20-pro-5g-drfone-by-drfone-virtual-android/"><u>The Best iSpoofer Alternative to Try On Tecno Camon 20 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/triggers-for-launching-system-restore-in-windows-11-environment/"><u>Triggers for Launching System Restore in Windows 11 Environment</u></a></li>
<li><a href="https://techidaily.com/unveiling-the-concept-of-wrapped-bitcoin-exploring-what-is-wbtc/"><u>Unveiling the Concept of Wrapped Bitcoin: Exploring What Is WBTC?</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/what-is-an-ai-avatar-in-2024/"><u>What Is an AI Avatar, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/win-11s-bluetooth-down-follow-these-9-simple-steps-to-fix-it/"><u>Win 11’S Bluetooth Down? Follow These 9 Simple Steps to Fix It</u></a></li>
<li><a href="https://win11.techidaily.com/windows-component-tools-accessing-and-operating-guide/"><u>Windows Component Tools: Accessing & Operating Guide</u></a></li>
</ul></div>

