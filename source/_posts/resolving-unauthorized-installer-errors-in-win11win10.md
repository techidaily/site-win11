---
title: Resolving Unauthorized Installer Errors in Win11/Win10
date: 2024-10-13T20:21:29.239Z
updated: 2024-10-15T16:36:17.959Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Unauthorized Installer Errors in Win11/Win10
excerpt: This Article Describes Resolving Unauthorized Installer Errors in Win11/Win10
keywords: Fixing Windows Install Issues,Win11 Error Resolution,Win10 Setup Troubleshooting,Unauthorized Installer Stop,Removing Boot Errors Win11,Fixing OS Install Glitches,Correcting Windows Install Fails
thumbnail: https://thmb.techidaily.com/ff4b473fea2e89c79aee76abe0eab2251a21420b8834da223e912daed0885bd1.jpg
---

## Resolving Unauthorized Installer Errors in Win11/Win10

 Users report Windows software installation errors of various kinds on support forums. Some of those reports have been about an error message that says, “The installer has insufficient privileges to access this directory.” That error message pops up on some users’ Windows 11/10 PCs when they try to install desktop programs with setup files.

 The result of this installation error is the same as most others. Users can’t install the software packages they need to when it happens. This is how you can fix the “installer has insufficient privileges” error on a Windows 11/10 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Affected Software’s Setup File With Admin Rights

 Running the setup file for an affected program with administrator rights is perhaps the simplest of potential fixes for the “installer has insufficient privileges” error.

 A few users say that’s all they needed to do to fix the “installer has insufficient privileges” error. So, try right-clicking the software’s installer file and selecting**Run as administrator** .

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/run-as-administrator-option.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136612/26400" target="_top" id="2136612">
  <img src="//a.impactradius-go.com/display-ad/26400-2136612" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136612/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Unblock the Setup File

 In addition, check if the installer file is blocked before running it. To do that, right-click the program’s setup file and select**Properties** .

 If you can see an**Unblock** option on the**General** tab, deselect the checkbox and select**Apply** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135350/19272" target="_top" id="2135350">
  <img src="//a.impactradius-go.com/display-ad/19272-2135350" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135350/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Take Ownership of the Software’s Installation Directory

 One of the more widely confirmed solutions for fixing the “installer has insufficient privileges” error is to take ownership of the installation directory for the affected software.

 The “installer has sufficient privileges” error message specifies the path of the directory selected to install the software. Take ownership of the second to last folder of that path. The last folder is the one created during the installation that won’t currently exist on your PC.

 Alternatively, you can also apply this potential solution by manually creating the folder specified within the error message that doesn’t currently exist. Keep the error message open and create the last folder in the path. Then take ownership of the last folder in the installation path specified and click**Retry** within the error message.

 You can take ownership of a folder manually or by adding a new context menu option that does the job. This guide about[taking ownership of folders in Windows 11](https://www.makeuseof.com/windows-10-11-own-folder/) includes full instructions for both methods. It’s more straightforward to apply this potential solution by adding a**Take Ownership** option to the context menu with Winaero Tweaker.

![The Take Ownership option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/take-ownership-option.jpg)

## 4\. Try Installing it in a Different Folder

 You might be able to bypass the “installer has insufficient privileges” error by selecting to install the software in a different directory. Many users install software packages in the Program Files folder. So, try selecting to install a program at a completely different folder path from the one specified in the error message.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135362/19272" target="_top" id="2135362">
  <img src="//a.impactradius-go.com/display-ad/19272-2135362" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135362/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Start or Restart Windows Installer

 Installation issues can arise because of Windows Installer service issues. Or that service might not even be running. So, check that service and either start or restart it depending on whether it’s running or not. You can start or restart Windows Installer like this:

1. [Open Services](https://www.makeuseof.com/windows-11-open-services-app/) , an app you can access by pressing the**Windows** logo +**R** hotkey and inputting a**service.msc** command.
2. Right-click Windows Installer and select**Start** if that service isn’t on and running.  
![windows installer option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-installer-option.jpg)
3. If Windows Installer is running, select its**Restart** context menu option.

 Alternatively, you can double-click the**Windows Installer** service to view its properties window and restart it from there. Click**Start** if the service is already stopped, or, select**Stop > Start** to restart.

## 6\. Disable UAC Before Installing

 User Account Control is one of the security features that can generate installation issues when set to its higher levels. Turn off UAC before attempting to install affected software to see if that resolves the “installer has insufficient privileges” error. Check out this guide about[disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) for details about how to turn off UAC.

![The Never notify option in UAC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/never-notify-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105876/7443" target="_top" id="2105876">
  <img src="//a.impactradius-go.com/display-ad/7443-2105876" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105876/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Disable All User Account Control Policy Settings

 If you’re a Windows Pro or Enterprise user, you can disable all UAC security settings that might be causing this error by restricting software installation.

 The Group Policy Editor tool in Windows Pro and Enterprise editions enables users to disable more User Account Control settings. You can turn off all UAC policy settings with Group Policy Editor like this:

1. [Open the Group Policy Editor tool](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and double-click**Computer Configuration** in its sidebar.
2. Then double-click**Windows Settings** \>**Security Settings** \>**Local Policies** \>**Security Options** to access UAC policy settings.
3. Double-click**User Account Control: Admin Approval Mode** to bring up that policy setting window.  
![The UAP security policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-options.jpg)
4. Select**Disabled** to turn off that policy setting.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915830/19272" target="_top" id="1915830">
  <img src="//a.impactradius-go.com/display-ad/19272-1915830" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915830/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Click**Apply** \>**OK** to save the policy setting you’ve selected.  
![The Enabled radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-enabled-radio-button.jpg)

 Once done, repeat steps three to five above for all the User Account Control policy settings. Exit Group Policy Editor and restart your PC after disabling all UAC policy settings.

## 8\. Turn Off Third-Party Security Apps

 If you’ve installed a third-party security app, such as antivirus or firewall software, that could be a possible cause for the “installer has insufficient privileges” error on your PC.

 Third-party antivirus tools have settings that can restrict or block the installation of suspicious programs when enabled. That’s more likely to happen when you’re trying to install unsigned software, which antivirus apps sometimes flag.

 You can prevent potential security app blocks when installing programs by temporarily disabling their antivirus shields.

 To find an option for disabling your antivirus app’s shield, right-click its system tray icon; select a setting to turn off your antivirus for a while on the right-click context menu that opens. Then have a go at installing affected software packages again with the antivirus shield disabled.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

## 9\. Try Installing Software After Clean Booting

 Clean booting means disabling all third-party apps and services that start with Windows. This troubleshooting method can prevent software conflicts by eliminating unneeded apps and services running in the background. In this case, a clean boot might disable an app or service that’s hindering the software installation process.

 We have a detailed guide on[performing a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) explaining how you can disable the startup items with System Configuration and Task Manager. Select to restart your PC after you’ve set a clean boot configuration. Install the software you need after restarting to see if the clean booting has made any difference.

![The Services tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-services-tab.jpg)

## 10\. Uninstall Older Software Versions

 The “installer has insufficient privileges” has been reported to occur by users trying to install new versions of software already on their PCs.

 If there’s an older version of the software you can’t install already on your PC, then try uninstalling the preceding version first. This guide on[uninstalling software in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) includes various methods for removing programs.

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-uninstall-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123732/7443" target="_top" id="2123732">
  <img src="//a.impactradius-go.com/display-ad/7443-2123732" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123732/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Your Windows 11/10 Software Installed

 The possible fixes covered here will probably resolve the “installer has insufficient privileges” Windows error in most cases but aren’t necessarily guaranteed.

 Resolution three, taking ownership of the installation directory, is the most widely confirmed solution. So, this error is usually a privilege (permission) issue for installing software, which the potential resolutions above will likely address.

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
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-download-youtube-videos-directly/"><u>[Updated] 2024 Approved Download YouTube Videos Directly</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-captivating-imagery-with-these-20-top-video-thumbnail-fonts-for-2024/"><u>[Updated] Captivating Imagery with These 20 Top Video Thumbnail Fonts for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-maximizing-visibility-do-paid-views-enhance-channels-effectively/"><u>[Updated] Maximizing Visibility Do Paid Views Enhance Channels Effectively?</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/boosting-system-capabilities-converting-32-bit-to-64-bit-win10/"><u>Boosting System Capabilities: Converting 32-Bit to 64-Bit Win10</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-disabled-obstacles-for-executing-powershell-scripts/"><u>Eliminating 'Disabled' Obstacles for Executing PowerShell Scripts</u></a></li>
<li><a href="https://win-dash.techidaily.com/grab-the-latest-free-asrock-ab350-pro4-drivers-today-easy-installation-on-your-pc-running-windows/"><u>Grab the Latest Free ASRock AB350 Pro4 Drivers Today: Easy Installation on Your PC Running Windows</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/luminous-designs-examination-pinnacle-studio-audit/"><u>Luminous Designs Examination Pinnacle Studio Audit</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-system-recovery-conquering-blue-screen-errors/"><u>Mastering System Recovery: Conquering Blue Screen Errors</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-the-solution-to-windows-error-0x80070570-step-by-step-fixes/"><u>Mastering the Solution to Windows 'Error 0X80070570': Step-by-Step Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-login-block-after-failure/"><u>Overcoming Windows Login Block After Failure</u></a></li>
<li><a href="https://fox-info.techidaily.com/racing-cameras-face-off-is-gopro-the-ultimate-champion-in-2024/"><u>Racing Cameras Face Off Is GoPro the Ultimate Champion, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-brightness-overcoming-dark-screen-problems/"><u>Restoring Brightness: Overcoming Dark Screen Problems</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-15-ways-to-reach-windows-settings/"><u>Simplify: 15 Ways to Reach Windows Settings</u></a></li>
<li><a href="https://win11.techidaily.com/step-up-windows-security-today-with-free-desktop-pass-gen-apps/"><u>Step Up Windows Security Today With Free Desktop Pass Gen Apps</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-windows-experience-resetting-apps/"><u>Streamlining Your Windows Experience: Resetting Apps</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-tips-for-stabilizing-resident-evil-4-remastered/"><u>Troubleshooting Tips for Stabilizing Resident Evil 4 Remastered</u></a></li>
</ul></div>

