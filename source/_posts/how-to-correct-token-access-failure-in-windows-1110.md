---
title: How to Correct Token Access Failure in Windows 11/10
date: 2024-10-08T21:36:09.764Z
updated: 2024-10-15T22:13:15.648Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Correct Token Access Failure in Windows 11/10
excerpt: This Article Describes How to Correct Token Access Failure in Windows 11/10
keywords: Fixing Token Issues in Win11,Resolving Access Tokens Errors,Token Recovery Steps for Windows OS,Addressing Token Failure Windows,Correcting Token Access Error,Overcoming Windows Token Denied,Remedy Windows 10/11 Token Error
thumbnail: https://thmb.techidaily.com/5dda734007d0cce4f616f2328d041526d598c5a6fb318adf671f70aacd812852.jpg
---

## How to Correct Token Access Failure in Windows 11/10

 Windows includes numerous pre-installed apps and tools like File Explorer, Device Manager, and Microsoft Management Console users often need to access. However, some users have reported they can’t access those pre-installed apps or others because of an error that says, “an attempt was made to reference a token that does not exist.” That error pops up when some users try to open Explorer or other native tools.

 Does the same error message pop up when you try to access Explorer, Device Manager, or another native Windows tool? If yes, try applying these potential remedies for the “reference a token” error.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. End and Restart File Explorer

 If the “reference a token” error occurs when you try to access File Explorer or folders, try restarting the Explorer process. Some users who’ve needed to fix the token reference error have said ending that Windows Explorer process and starting it again worked for them. You can end and restart Explorer as follows:

1. [Launch Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) by simultaneously pressing the **Ctrl** \+ **Shift** \+ **Esc** keyboard keys.
2. Scroll down to the Windows Explorer on the **Processes** tab.
3. Then right-click Windows Explorer and select **End task**.  
![The End task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/end-task-option.jpg)
4. Select **End process** to confirm. The background Windows desktop will go blank when you do that, and restarting Explorer will restore it.
5. Click **File** at the top of Task Manager.  
![The Run new task option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/run-new-task.jpg)
6. Select **Run new task** to access a Create new task box.
7. Input **Explorer.exe** inside the **Open** text box.  
![The Create new task window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/create-new-task.jpg)
8. Select **Create this task with administrative privileges** and click **OK** to restart Explorer.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880927/19272" target="_top" id="1880927">
  <img src="//a.impactradius-go.com/display-ad/19272-1880927" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880927/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Reregister Windows DLL Files

 Users who’ve needed to fix the “reference a token” error have confirmed reregistering the Windows DLL (Dynamic Link Library) files works. That highlights the token reference error can occur because some Windows DLL files aren’t correctly registered. This is how you can reregister Windows DLL files:

1. Bring up the **Type here to search** text box for finding files with the **Windows** logo key + **S** hotkey.
2. Next, type a **CMD** search phrase in the file finder text box.
3. Right-click on **Command Prompt** inside the file search tool to select **Run as administrator**.
4. Now enter and execute this command for reregistering DLL files:  
`for /f %s in ('dir /b *.dll') do regsvr32 /s %s`  
![The reregister DLL command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/reregister-dll-commands.jpg)
5. Wait for the command to finish reregistering DLLs.

6. Close your Command Prompt app, bring up the Start menu, and select **Restart**.

## 3\. Try Some More Generic Windows Fixes

 If nothing has worked, try these Windows fixes that can fix a wide variety of errors, including this one.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012406/19272" target="_top" id="2012406">
  <img src="//a.impactradius-go.com/display-ad/19272-2012406" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012406/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Scan and Repair System Files With SFC

 The “reference a token” error is often a result of corrupted Windows system files. So, repairing system files is a likely potential solution for that error. You can check for and repair corrupted system files by [running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) within the Command Prompt.

![The sfc /scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sfc-scannow-command5.jpg)

### Go Back to a Previous Windows Build Version

 If the “reference a token” error occurs after a recent Windows feature update, restoring the previous build version might resolve that issue. However, you can only restore a previous build version for a limited period. This is how you can restore a previous Windows build version:

1. Activate the file search box and input the keyword **recovery options**.
2. Select **Recovery** **options** to bring up Settings.
3. Click the **Go back** or **Get started** button for restoring the previous Windows version.  
![The Get started button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/get-started-button.jpg)

 If that option is grayed out, you can also try restoring the previous Windows build from the **Advanced options** menu. Open recovery options in Settings as outlined in steps one and two above and click **Restart** **now**. Then select **Troubleshoot** \> **Advanced** options and the **Go back** **to previous build** option if available.

### Go Back to a Previous Restore Point

 System Restore is another tool that can resolve system file issues causing the “reference a token” error, but only if you have that utility enabled on your PC. If there’s a suitable restore point on your PC, you can roll back Windows to a previous point in time that predates the token reference error. Doing so might undo updates and other system changes that triggered the issue.

![The System Restore tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/system-restore-point.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134498/18498" target="_top" id="2134498">
  <img src="//a.impactradius-go.com/display-ad/18498-2134498" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134498/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To apply this resolution, check out our [article about creating and utilizing restore points](https://www.makeuseof.com/windows-11-create-restore-point/). Choose a restore point that will roll Windows back to when you didn’t need to fix the token reference error. However, note that a system restore point will remove software packages installed after its date.

### Reset Windows

 Resetting Windows 11/10 is a last resort for fixing the “reference a token” error that will probably work. It’s best to save this probable resolution until last because you’ll need to reinstall all third-party UWP and desktop apps installed before the reset. You can apply this possible resolution as instructed within method one of our [how to factory reset Windows](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/#:~:text=To%20run%20a%20Windows%20factory,%3E%20Update%20%26%20Security%20%3E%20Recovery.) guide.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105877/7443" target="_top" id="2105877">
  <img src="//a.impactradius-go.com/display-ad/7443-2105877" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105877/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get the “Reference a Token” Error Sorted Out

 The “reference a token” error is serious when users can’t access essential native apps like File Explorer because of it. In many cases, corrupted Windows files are usually the culprit. Most of the resolutions in this guide will address that cause, and restarting File Explorer can also work when the issue affects that app or folders.

 Does the same error message pop up when you try to access Explorer, Device Manager, or another native Windows tool? If yes, try applying these potential remedies for the “reference a token” error.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/024-approved-unveiling-allure-comprehensive-beauty-how-tos-on-youtube/"><u>[New] 2024 Approved Unveiling Allure Comprehensive Beauty How-Tos on Youtube</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-instant-reddit-archives-retrieval-with-ease/"><u>[New] Instant Reddit Archives Retrieval with Ease</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-deciphering-the-latest-instagram-posting-rules-for-2024/"><u>[Updated] Deciphering the Latest Instagram Posting Rules for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-how-to-incrementally-lower-decibels-in-logic-pro/"><u>[Updated] How to Incrementally Lower Decibels in Logic Pro</u></a></li>
<li><a href="https://driver-download.techidaily.com/canon-pixma-mx490-driver-installation-guide-and-updates-for-windows-users/"><u>Canon PIXMA MX490 Driver Installation Guide and Updates for Windows Users</u></a></li>
<li><a href="https://extra-tips.techidaily.com/creating-a-channel-focused-on-reviewing-marketplace-items/"><u>Creating a Channel Focused on Reviewing Marketplace Items</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-absence-of-monitor-post-bootup/"><u>Eliminating Absence of Monitor Post-Bootup</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-interrupted-by-breakpoint-error-in-windows/"><u>Eliminating Interrupted by Breakpoint Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-techniques-to-launch-windows-11s-restore-mode/"><u>Exploring Techniques to Launch Windows 11'S Restore Mode</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-notepad-strategies-for-a-responsive-windows-companion-app/"><u>Fixing Notepad: Strategies for a Responsive Windows Companion App</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unclog-the-secondary-user-writes-access-issue/"><u>How to Unclog the Secondary User' Writes Access Issue</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-construct-a-homemade-google-vr-helmet-for-cost-effective-fun/"><u>In 2024, Construct a Homemade Google VR Helmet for Cost-Effective Fun</u></a></li>
<li><a href="https://win11.techidaily.com/minimizing-options-in-the-win-11-context-list/"><u>Minimizing Options in the Win 11 Context List</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-based-inaccessibility-to-roblox-experience/"><u>Resolving Windows-Based Inaccessibility to Roblox Experience</u></a></li>
<li><a href="https://win-answers.techidaily.com/solving-doom-eternal-crashes-effective-troubleshooting-steps/"><u>Solving DOOM Eternal Crashes: Effective Troubleshooting Steps</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/the-ultimate-guide-producing-exceptional-igtv-content-on-mobile-and-dslrs/"><u>The Ultimate Guide Producing Exceptional IGTV Content on Mobile & DSLRs</u></a></li>
<li><a href="https://win11.techidaily.com/winway-login-tips-removing-personal-emails/"><u>Winway Login Tips: Removing Personal Emails</u></a></li>
</ul></div>

