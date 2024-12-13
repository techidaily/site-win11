---
title: Combatting Insufficient Privilege Error During Windows Setup
date: 2024-12-11T13:54:15.723Z
updated: 2024-12-12T16:05:44.945Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Combatting Insufficient Privilege Error During Windows Setup
excerpt: This Article Describes Combatting Insufficient Privilege Error During Windows Setup
keywords: Fixing Privilege Errors,WinSetup Access Issue,Resolve Privileged Error,Overcome Privilege Failure,Dealing with UAC Error,Unblock Setup Windows,Correcting Insufficient Privileges
thumbnail: https://thmb.techidaily.com/454a5d400e77a7a30fc6fb5cf37376c887407a08a4d33d69cb3dc289d466caa6.jpg
---

## Combatting Insufficient Privilege Error During Windows Setup

 Users report Windows software installation errors of various kinds on support forums. Some of those reports have been about an error message that says, “The installer has insufficient privileges to access this directory.” That error message pops up on some users’ Windows 11/10 PCs when they try to install desktop programs with setup files.

 The result of this installation error is the same as most others. Users can’t install the software packages they need to when it happens. This is how you can fix the “installer has insufficient privileges” error on a Windows 11/10 PC.

## 1\. Run the Affected Software’s Setup File With Admin Rights

 Running the setup file for an affected program with administrator rights is perhaps the simplest of potential fixes for the “installer has insufficient privileges” error.

 A few users say that’s all they needed to do to fix the “installer has insufficient privileges” error. So, try right-clicking the software’s installer file and selecting **Run as administrator**.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/run-as-administrator-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Unblock the Setup File

 In addition, check if the installer file is blocked before running it. To do that, right-click the program’s setup file and select **Properties**.

 If you can see an **Unblock** option on the **General** tab, deselect the checkbox and select **Apply**.

## 3\. Take Ownership of the Software’s Installation Directory

 One of the more widely confirmed solutions for fixing the “installer has insufficient privileges” error is to take ownership of the installation directory for the affected software.

 The “installer has sufficient privileges” error message specifies the path of the directory selected to install the software. Take ownership of the second to last folder of that path. The last folder is the one created during the installation that won’t currently exist on your PC.

 Alternatively, you can also apply this potential solution by manually creating the folder specified within the error message that doesn’t currently exist. Keep the error message open and create the last folder in the path. Then take ownership of the last folder in the installation path specified and click **Retry** within the error message.

 You can take ownership of a folder manually or by adding a new context menu option that does the job. This guide about [taking ownership of folders in Windows 11](https://www.makeuseof.com/windows-10-11-own-folder/) includes full instructions for both methods. It’s more straightforward to apply this potential solution by adding a **Take Ownership** option to the context menu with Winaero Tweaker.

![The Take Ownership option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/take-ownership-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Try Installing it in a Different Folder

 You might be able to bypass the “installer has insufficient privileges” error by selecting to install the software in a different directory. Many users install software packages in the Program Files folder. So, try selecting to install a program at a completely different folder path from the one specified in the error message.

## 5\. Start or Restart Windows Installer

 Installation issues can arise because of Windows Installer service issues. Or that service might not even be running. So, check that service and either start or restart it depending on whether it’s running or not. You can start or restart Windows Installer like this:

1. [Open Services](https://www.makeuseof.com/windows-11-open-services-app/), an app you can access by pressing the **Windows** logo + **R** hotkey and inputting a **service.msc** command.
2. Right-click Windows Installer and select **Start** if that service isn’t on and running.  
![windows installer option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-installer-option.jpg)
3. If Windows Installer is running, select its **Restart** context menu option.

 Alternatively, you can double-click the **Windows Installer** service to view its properties window and restart it from there. Click **Start** if the service is already stopped, or, select **Stop > Start** to restart.

## 6\. Disable UAC Before Installing

 User Account Control is one of the security features that can generate installation issues when set to its higher levels. Turn off UAC before attempting to install affected software to see if that resolves the “installer has insufficient privileges” error. Check out this guide about [disabling User Account Control](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) for details about how to turn off UAC.

![The Never notify option in UAC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/never-notify-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PKZUYice-ws?si=L8iMa9T3h7TMSWdQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 7\. Disable All User Account Control Policy Settings

 If you’re a Windows Pro or Enterprise user, you can disable all UAC security settings that might be causing this error by restricting software installation.

 The Group Policy Editor tool in Windows Pro and Enterprise editions enables users to disable more User Account Control settings. You can turn off all UAC policy settings with Group Policy Editor like this:

1. [Open the Group Policy Editor tool](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and double-click **Computer Configuration** in its sidebar.
2. Then double-click **Windows Settings** \> **Security Settings** \> **Local Policies** \> **Security Options** to access UAC policy settings.
3. Double-click **User Account Control: Admin Approval Mode** to bring up that policy setting window.  
![The UAP security policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-options.jpg)
4. Select **Disabled** to turn off that policy setting.
5. Click **Apply** \> **OK** to save the policy setting you’ve selected.  
![The Enabled radio button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-enabled-radio-button.jpg)

 Once done, repeat steps three to five above for all the User Account Control policy settings. Exit Group Policy Editor and restart your PC after disabling all UAC policy settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1KKovVi9epE?si=EF7KA7b4KsEpWA-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 8\. Turn Off Third-Party Security Apps

 If you’ve installed a third-party security app, such as antivirus or firewall software, that could be a possible cause for the “installer has insufficient privileges” error on your PC.

 Third-party antivirus tools have settings that can restrict or block the installation of suspicious programs when enabled. That’s more likely to happen when you’re trying to install unsigned software, which antivirus apps sometimes flag.

 You can prevent potential security app blocks when installing programs by temporarily disabling their antivirus shields.

 To find an option for disabling your antivirus app’s shield, right-click its system tray icon; select a setting to turn off your antivirus for a while on the right-click context menu that opens. Then have a go at installing affected software packages again with the antivirus shield disabled.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

## 9\. Try Installing Software After Clean Booting

 Clean booting means disabling all third-party apps and services that start with Windows. This troubleshooting method can prevent software conflicts by eliminating unneeded apps and services running in the background. In this case, a clean boot might disable an app or service that’s hindering the software installation process.

 We have a detailed guide on [performing a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) explaining how you can disable the startup items with System Configuration and Task Manager. Select to restart your PC after you’ve set a clean boot configuration. Install the software you need after restarting to see if the clean booting has made any difference.

![The Services tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-services-tab.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 10\. Uninstall Older Software Versions

 The “installer has insufficient privileges” has been reported to occur by users trying to install new versions of software already on their PCs.

 If there’s an older version of the software you can’t install already on your PC, then try uninstalling the preceding version first. This guide on [uninstalling software in Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) includes various methods for removing programs.

![The Uninstall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/the-uninstall-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get Your Windows 11/10 Software Installed

 The possible fixes covered here will probably resolve the “installer has insufficient privileges” Windows error in most cases but aren’t necessarily guaranteed.

 Resolution three, taking ownership of the installation directory, is the most widely confirmed solution. So, this error is usually a privilege (permission) issue for installing software, which the potential resolutions above will likely address.

 The result of this installation error is the same as most others. Users can’t install the software packages they need to when it happens. This is how you can fix the “installer has insufficient privileges” error on a Windows 11/10 PC.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-speedy-video-processing-for-youtube-tricks-to-render-and-upload-fast/"><u>[Updated] 2024 Approved Speedy Video Processing for YouTube Tricks to Render & Upload Fast</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-harnessing-skypes-voice-free-mp3-exclusive/"><u>[Updated] In 2024, Harnessing Skype's Voice - Free MP3 Exclusive</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-the-heart-of-vimeo-celebrating-independent-cinema/"><u>[Updated] The Heart of Vimeo Celebrating Independent Cinema</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-the-key-to-crisp-clear-cinematography/"><u>2024 Approved The Key to Crisp, Clear Cinematography</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-transfer-music-from-honor-100-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Transfer Music from Honor 100 to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/choosing-the-perfect-phone-for-your-child-expert-reviews-and-analysis-from-zdnet/"><u>Choosing the Perfect Phone for Your Child: Expert Reviews and Analysis From ZDNet</u></a></li>
<li><a href="https://win11.techidaily.com/delayed-start-how-to-stop-windows-edge-preloading/"><u>Delayed Start: How to Stop Windows Edge Preloading</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unable-to-access-camera-error-on-windows-11/"><u>Fixing Unable to Access Camera Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/ignite-liberated-conversations-using-freedomgpt/"><u>Ignite Liberated Conversations: Using FreedomGPT</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-xiaomi-redmi-note-12-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Xiaomi Redmi Note 12 4G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/instantly-gain-superuser-status-easy-fix/"><u>Instantly Gain Superuser Status - Easy Fix</u></a></li>
<li><a href="https://win11.techidaily.com/plug-free-gaming-setup-ps3-controller-on-win/"><u>Plug-Free Gaming: Setup PS3 Controller on Win</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-google-frp-lock-on-oneplus-nord-n30-5g-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP Lock on OnePlus Nord N30 5G</u></a></li>
<li><a href="https://article-files.techidaily.com/scribing-success-engaging-examples-for-podcasts-for-2024/"><u>Scribing Success Engaging Examples for Podcasts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/solving-windows-blue-screen-errors-quickly/"><u>Solving Windows Blue Screen Errors Quickly</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/up-steps-for-successful-youtubers-setting-up-channels-securing-sales-for-2024/"><u>Startup Steps for Successful Youtubers Setting Up Channels, Securing Sales for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/test-if-your-system-hits-windows-11-requirements/"><u>Test if Your System Hits Windows 11 Requirements</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-secrets-to-overcoming-steams-e84-obstacles/"><u>Unveiling Secrets to Overcoming Steam's E84 Obstacles</u></a></li>
<li><a href="https://win11.techidaily.com/zero-downtime-for-usb-connectivity-issues-in-windows-10/"><u>Zero Downtime for USB Connectivity Issues in Windows 10</u></a></li>
</ul></div>

