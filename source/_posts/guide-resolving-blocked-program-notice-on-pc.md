---
title: "Guide: Resolving Blocked Program Notice on PC"
date: 2024-12-01T03:26:52.455Z
updated: 2024-12-07T03:15:31.719Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Guide: Resolving Blocked Program Notice on PC"
excerpt: "This Article Describes Guide: Resolving Blocked Program Notice on PC"
keywords: Fix PC Program Block,Unblock Blocked Notice,Remove Program Alert,Clear Program Error,Stop Blocked App Stop,Disable Program Halt,Revoke Warning Notice
thumbnail: https://thmb.techidaily.com/99c9865a6c9c6ec80635e573e65ff37309dc9b7d70208081aa77b6f0d087fbe7.jpg
---

## Guide: Resolving Blocked Program Notice on PC

 While Windows is designed to keep your computer secure, sometimes it can be overly zealous in its protection and block an app you know is safe. If you’re seeing the “This app has been blocked for your protection” error on Windows, your system has restricted the application from running for security reasons. This article clarifies the reasons behind the problem and guides you toward resolving it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Restart Your Computer

 When you experience the “This app has been blocked for your protection” error, the first step is to restart your computer. A simple reboot can often do the trick and allow you run a previously blocked application.

 If you don’t experience the error after rebooting, then it is likely a temporary glitch on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LdVT_-3gESA?si=_HfjpbUEHSRKTXjt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Scan for Malicious Programs

 If restarting your computer doesn’t work, the next step is to run a full antivirus scan on your system. Chances are that the application is blocked due to a virus, malware or another malicious program.

 To be sure it's not the case, check whether a file is infected with a virus. If you find one, [scan your computer for viruses](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and remove them.

 If you prefer command line tools, you can [scan and remove malicious components using Windows PowerShell](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/). You should also use a [reputable anti-spyware program](https://www.makeuseof.com/windows-11-antivirus-apps/) to check for malicious programs that could be causing the error.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Run the Program as an Administrator

 Some programs require administrator privileges to function properly. If you try to launch them without elevated access, Windows will block their execution and display the error message. In such a case, you can right-click on the app’s shortcut or the executable file and select **Run as administrator**.

 If it runs successfully, you can adjust the app properties to [always run as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/). Don't forget to save the changes.

## 4\. Disable the SmartScreen Filter

 SmartScreen is a security feature that protects your computer from unknown and potentially malicious applications. If it’s enabled, SmartScreen may block an application from running. To disable the feature, follow these steps.

1. Open the **Start** menu and search for _Windows Security_.
2. Click on **Windows Security** in the search results.
3. In the Windows Security app, select **App & browser control**.
4. On the right side of the window, click **Reputation-based protection settings**.  
![Disable the SmartScreen Filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-the-smartscreen-filter.jpg)
5. Toggle off **Potentially unwanted app blocking** and **SmartScreen for Microsoft Store apps**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This will stop the system from blocking apps, but you should be careful with any programs you download. Once you do it, close the Windows Security app and try running the application again.

## 5\. Modify the Group Policy Settings

 The group policy editor allows you to adjust security settings on Windows and control which applications are blocked. If the other steps didn’t work, you can try to modify the group policy settings and unblock the application that triggered the error. Here's how to do it:

1. Press **Win + X** on your keyboard and select **Run** from the menu list.
2. Type **gpedit.msc** and press Enter to open the Local Group Policy Editor.  
![User Account Control Run all administrators in Admin Approval Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/user-account-control-run-all-administrators-in-admin-approval-mode.jpg)
3. Once you're in the Local Group Policy Editor window, navigate to the following:  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options.`
4. From the list of settings, double-click on **User Account Control: Run all administrators in Admin Approval Mode** and set it to **Disabled**.
5. After making the changes, click **Apply > OK** and restart your computer to apply it.

 Keep in mind that modifying group policy settings can leave your computer vulnerable to malicious applications. Therefore, you should only do it as a last resort and revert the change as soon as you’re done.

## 6\. Tweak the Registry Editor

 If you're running Windows Home edition, you can tweak the Registry Editor to adjust the User Account Control settings and unblock the application. Here's what you need to do:

1. [Open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** and press Enter to open the Registry Editor window.
3. If UAC prompts you for permission, click **Yes**.
4. Navigate to the following key location.  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System`
5. In the right pane, double-click on **EnableLUA** and set its value to **0** (zero).  
![Disable the EnableLUA key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-the-enablelua-key-in-registry-editor.jpg)
6. Click **OK** to save the changes.

 After making the changes, close the Registry Editor and restart your computer.

## 7\. Reset Windows Update Components

 If the issue persists, you can reset the Windows Update components, which means restarting certain services that manage the update process and enable you to launch the application.

 To reset Windows Update components, do the following:

1. Click on Start and search for **Notepad**.
2. Right-click on the Notepad icon and select **Run as administrator**.
3. Copy and paste the following code into Notepad:  
`<code>net stop bits  
net stop wuauserv  
net stop appidsvc  
net stop cryptsvc  
Del "%ALLUSERSPROFILE%\Application Data\Microsoft\Network\Downloader\*.*"  
rmdir %systemroot%\SoftwareDistribution /S /Q  
rmdir %systemroot%  
system32\catroot2 /S /Q  
sc.exe sdset bits D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
sc.exe sdset wuauserv D:(A;;CCLCSWRPWPDTLOCRRC;;;SY)(A;;CCDCLCSWRPWPDTLOCRSDRCWDWO;;;BA)(A;;CCLCSWLOCRRC;;;AU)(A;;CCLCSWRPWPDTLOCRRC;;;PU)  
cd /d %windir%  
system32  
regsvr32.exe /s atl.dll  
regsvr32.exe /s urlmon.dll  
regsvr32.exe /s mshtml.dll  
regsvr32.exe /s shdocvw.dll  
regsvr32.exe /s browseui.dll  
regsvr32.exe /s jscript.dll  
regsvr32.exe /s vbscript.dll  
regsvr32.exe /s scrrun.dll  
regsvr32.exe /s msxml.dll  
regsvr32.exe /s msxml3.dll  
regsvr32.exe /s msxml6.dll  
regsvr32.exe /s actxprxy.dll  
regsvr32.exe /s softpub.dll  
regsvr32.exe /s wintrust.dll  
regsvr32.exe /s dssenh.dll  
regsvr32.exe /s rsaenh.dll  
regsvr32.exe /s gpkcsp.dll  
regsvr32.exe /s sccbase.dll  
regsvr32.exe /s slbcsp.dll  
regsvr32.exe /s cryptdlg.dll  
regsvr32.exe /s oleaut32.dll  
regsvr32.exe /s ole32.dll  
regsvr32.exe /s shell32.dll  
regsvr32.exe /s initpki.dll  
regsvr32.exe /s wuapi.dll  
regsvr32.exe /s wuaueng.dll  
regsvr32.exe /s wuaueng1.dll  
regsvr32.exe /s wucltui.dll  
regsvr32.exe /s wups.dll  
regsvr32.exe /s wups2.dll  
regsvr32.exe /s wuweb.dll  
regsvr32.exe /s qmgr.dll  
regsvr32.exe /s qmgrprxy.dll  
regsvr32.exe /s wucltux.dll  
regsvr32.exe /s muweb.dll  
regsvr32.exe /s wuwebv.dll  
netsh winsock reset  
netsh winsock reset proxy  
net start bits  
net start wuauserv  
net start appidsvc  
net start cryptsvc`
4. Now click **File** in the top left corner.
5. Then select **Save as** from the options list.
6. In the Save as window, name your script **Reset.bat** and set the Save as type to **All Files**.
7. Select **Desktop** from the left menu and click **Save**.
8. Double-click on the **Reset.bat** file to run it as an administrator.
9. If the UAC window pops up on the screen, click **Yes** to continue.

 Wait for the process to finish and restart your computer. After the reboot, try running the blocked app again. It should now work without issues.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get Access to Your Apps and Files on Windows

 Windows is known for its tight security which prevents malicious applications from launching and infecting your PC. However, sometimes even legitimate programs are blocked by the operating system and leave an error message saying “This app has been blocked for your protection.”

 There are several reasons why this error occurs. It includes outdated security software, the firewall interfering with the program, or the application not trusted by Windows. Read this guide to learn more about this error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-files.techidaily.com/new-smart-video-alteration-for-mac-users-seeking-insta-perfect-posts/"><u>[New] Smart Video Alteration for Mac Users Seeking Insta-Perfect Posts</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-bridging-the-gap-transitioning-youtube-to-televisions-smoothly/"><u>[Updated] 2024 Approved Bridging the Gap Transitioning YouTube to Televisions Smoothly</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-how-to-extract-gif-content-seamlessly-on-various-devices/"><u>[Updated] 2024 Approved How To Extract GIF Content Seamlessly on Various Devices</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-common-blue-screens-in-windows-os/"><u>Conquering Common Blue Screens in Windows OS</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/creating-polished-composites-with-skillful-modes-use/"><u>Creating Polished Composites with Skillful Modes Use</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/effortless-connection-how-to-ensure-your-ps4-dualshock-works-perfectly/"><u>Effortless Connection: How To Ensure Your PS4 DualShock Works Perfectly</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-ways-to-find-unlocking-codes-for-vivo-y200e-5g-phones-by-drfone-android/"><u>In 2024, Ways To Find Unlocking Codes For Vivo Y200e 5G Phones</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/nine-techniques-for-reversing-livestream-engagement/"><u>Nine Techniques for Reversing Livestream Engagement</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-team-meeting-blank-screens/"><u>Resolve Team Meeting Blank Screens</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-frozen-grammarly-errors-on-windows-systems/"><u>Resolving Frozen Grammarly Errors on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/securely-altering-admin-credentials-a-guide-for-windows-11-users/"><u>Securely Altering Admin Credentials: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/sonic-social-media-merging-melodies-and-memes-on-instagram-for-2024/"><u>Sonic Social Media Merging Melodies and Memes on Instagram for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-windows-expiry-notification-issue/"><u>Steps to Overcome Windows Expiry Notification Issue</u></a></li>
<li><a href="https://win11.techidaily.com/thorough-guide-to-completely-uninstall-wsl-in-win-1011/"><u>Thorough Guide to Completely Uninstall WSL in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/upgrade-your-click-efficiency-with-customized-mouse-settings-on-win11/"><u>Upgrade Your Click Efficiency with Customized Mouse Settings on Win11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    