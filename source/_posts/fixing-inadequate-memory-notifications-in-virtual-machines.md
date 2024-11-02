---
title: Fixing Inadequate Memory Notifications in Virtual Machines
date: 2024-10-31T18:10:09.724Z
updated: 2024-11-01T21:31:02.509Z
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

## 2\. Edit the Config File

 Lots of users have been able to fix the “not enough physical memory” by editing VMWare’s**config.ini** file. Those users disabled a Host parameter within the software’s configuration file. To disable that Host parameter, open and edit VMware’s**config.ini** file as follows:

1. Press**Win + E** to access File Explorer.
2. Open this VMware directory in Explorer:  
`C:\ProgramData\VMware\VMware Workstation`
3. Right-click the**config.ini** file and select**Open with** .  
![The Open with option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-open-with-option.jpg)
4. Select**Notepad** to view the configuration file in that text editor.

5. Then **input vmmon.disableHostParameters = “TRUE”** at the bottom of the configuration file as in the image below.  
![WMware's config.ini file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-config-ini-file.jpg)
6. Click**File** on Notepad’s menubar.

7. Select the menu’s**Save** option.  
![The Save option in Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-save-option-in-notepad.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006946/19272" target="_top" id="2006946">
  <img src="//a.impactradius-go.com/display-ad/19272-2006946" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006946/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Expand the Virtual Memory for the Virtual Machine

 The “not enough physical memory” error can occur because not enough virtual memory has been allocated to the virtual machine. You can expand a virtual machine’s memory allocation in VMWare like this:

1. Open your VMware software.
2. Right-click the virtual machine for which you need to fix the error and select**Settings** .
3. Increase the virtual machine’s memory allocation with the bar slider. That amount should always be higher than your PC’s available RAM.  
![The memory bar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-memory-bar.jpg)
4. Click**OK** to apply.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037351/7443" target="_top" id="2037351">
  <img src="//a.impactradius-go.com/display-ad/7443-2037351" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037351/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Update VMware

 The “not enough physical memory” error will more likely arise on outdated WMware versions. So, ensure you’re utilizing the latest version of the software. This is how you can update VMware:

1. Bring up the VMware window.
2. Click the**Help** menu.
3. Select**Software Updates** to view that window.  
![The Software Updates option in VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-software-updates-option.jpg)
4. Then click the**Check for Updates** button.  

![The Check for updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-check-for-updates-option4.jpg)
5. Press the**Get More Information** button for an available update.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151856/7443" target="_top" id="2151856">
  <img src="//a.impactradius-go.com/display-ad/7443-2151856" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151856/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Log into an account profile on the website that opens.
2. Select the**Download Now** option on the website for the latest VMware Workstation version.
3. Then you’ll need to select an**Accept** option for the EULA agreement.
4. Click another**Download Now** option.
5. Then click File Explorer’s taskbar shortcut.
6. Go to the downloads folder that includes the WMware setup wizard.
7. Double-click the downloaded VMware installer to open it. Go through the setup wizard to install the latest VMware version.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139111/17108" target="_top" id="2139111">
  <img src="//a.impactradius-go.com/display-ad/17108-2139111" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139111/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Delete a Recent Windows Update

 The “not enough physical memory” error can be caused by a Windows update that conflicts with VMware. So, uninstalling a recent update could fix that issue for some users. Check out our guide about[uninstalling Windows updates](https://www.makeuseof.com/windows-11-uninstall-updates/) for further details on how to apply this potential solution.

![The Installed Updates Control Panel applet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-uninstall-update-option.jpg)

## 6\. Perform a Clean Boot

 Performing a clean boot will disable non-essential apps and services from the Windows startup. Clean booting can potentially resolve the “not enough physical memory” in two ways. Applying this troubleshooting method will ensure there aren’t any third-party programs conflicting with VMware and free up RAM for the software.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/the-services-tab-in-msconfig.jpg)

 To disable all third-party startup programs and services, check out the guidelines in our guide on[how to clean boot in Windows](https://www.makeuseof.com/clean-boot-windows-11/) . This will perform a clean boot whenever you restart Windows.

 Try utilizing your VMware virtual machine after clean booting. If this works,

## 7\. Set Up a New Virtual Machine

 If the issue persists despite applying the resolutions above, consider setting up a new virtual machine to replace the one that needs fixing. Download the latest ISO for the virtual machine’s platform. Then you can set up the virtual machine again, as outlined on the[VMware support page](https://kb.vmware.com/s/article/1018415) .

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098704/14409" target="_top" id="2098704">
  <img src="//a.impactradius-go.com/display-ad/14409-2098704" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098704/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-unveiling-six-techniques-to-screen-record-your-streamed-movies-on-macos/"><u>[New] 2024 Approved Unveiling Six Techniques to Screen Record Your Streamed Movies on MacOS</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-controlling-who-sees-your-youtube-productions/"><u>2024 Approved Controlling Who Sees Your Youtube Productions</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/catch-em-all-in-no-time-learn-to-play-pokemon-go-now/"><u>Catch 'Em All in No Time - Learn to Play Pokemon Go Now!</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-a-personalized-context-menu-with-windows-11/"><u>Crafting a Personalized Context Menu with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/easing-the-way-through-printer-error-messages/"><u>Easing the Way Through Printer Error Messages</u></a></li>
<li><a href="https://win11.techidaily.com/expert-insight-for-thriving-at-ps1-on-win-a-detailed-guide-by-duckstation/"><u>Expert Insight for Thriving at PS1 on WIN - A Detailed Guide by Duckstation</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/forgot-locked-iphone-8-plus-password-learn-the-best-methods-to-unlock-by-drfone-ios/"><u>Forgot Locked iPhone 8 Plus Password? Learn the Best Methods To Unlock</u></a></li>
<li><a href="https://some-guidance.techidaily.com/harnessing-the-power-of-cookiebot-for-customized-web-interactions/"><u>Harnessing the Power of Cookiebot for Customized Web Interactions</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-mac-graphics-revolution-top-10-freeware-drawings/"><u>In 2024, Mac Graphics Revolution Top 10 Freeware Drawings</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/mastering-hevch265-a-comprehensive-guide-for-mac-users/"><u>Mastering HEVC/H.265: A Comprehensive Guide for Mac Users</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/navigating-the-nuances-of-gamers-channel-templates/"><u>Navigating the Nuances of Gamers' Channel Templates</u></a></li>
<li><a href="https://win11.techidaily.com/outsmarting-google-chromes-webp-image-saving-on-windows/"><u>Outsmarting Google Chrome's WebP Image Saving on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-full-functional-capacity-of-ctrl-key-in-windows-11/"><u>Restoring Full Functional Capacity of CTRL Key in Windows 11</u></a></li>
<li><a href="https://win-able.techidaily.com/say-goodbye-to-flickering-screens-with-these-easy-fixes/"><u>Say Goodbye to Flickering Screens with These Easy Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-the-process-repairing-setup-glitches-in-winx/"><u>Streamlining the Process: Repairing Setup Glitches in WinX</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-permission-based-save-errors-in-windows-os/"><u>Tackling Permission-Based Save Errors in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-detecting-hidden-bluetooth-clients-devices-mgr/"><u>Tips for Detecting Hidden Bluetooth Clients Devices Mgr</u></a></li>
<li><a href="https://win11.techidaily.com/top-9-differences-showing-why-pc-is-superior-to-mac/"><u>Top 9 Differences Showing Why PC Is Superior to Mac</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-oppo-find-n3-flip-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Oppo Find N3 Flip Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
</ul></div>

