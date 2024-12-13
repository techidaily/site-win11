---
title: Step-by-Step DNS Flushing in Modern Windows
date: 2024-12-11T00:33:24.811Z
updated: 2024-12-13T07:24:30.774Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Step-by-Step DNS Flushing in Modern Windows
excerpt: This Article Describes Step-by-Step DNS Flushing in Modern Windows
keywords: WinDNS Flush,DNS Reset,Flush DNS Cache,DNS Update Windows,Clear DNS Settings,DNS Server Refresh,Network Resolution Reset
thumbnail: https://thmb.techidaily.com/0994f11e3b98aa050445b83a923c27f3f286a1f5302c7ff78d5008912b4d02f9.jpg
---

## Step-by-Step DNS Flushing in Modern Windows

 Facing internet connectivity issues on your Windows PC? DNS cache corruption is among the most common reasons for connectivity problems. The quickest fix for this problem is to flush the DNS cache and force the computer to recreate it.

 But do you know that there are multiple ways to flush the DNS cache on Windows 11? We will elaborate on the benefits of clearing the DNS cache along with the multiple methods which you can use on your Windows 11 PC. Without further ado, let’s dive into the post.

## What Is the DNS Cache and Why Should You Flush It?

 When you access a website, you usually do so by typing its URL in a browser. However, computers don't "understand" URLs, and each URL has a corresponding IP address that a computer can actually use. When you search for a website, your computer accesses a DNS server that contains records of URLs and their corresponding IP addresses.

 This process is known as DNS lookup, but it is time-consuming to search for an IP address every time, especially for websites that you visit repeatedly. So, the computer maintains a local copy of the DNS known as the DNS resolver cache. When you search for a URL, it checks the resolver cache first and then uses that information to find the website.

 The DNS resolver cache can become outdated or corrupt over time which can pose connectivity issues. There is also a looming risk of[DNS cache poisoning](https://www.makeuseof.com/tag/what-is-dns-cache-poisoning/) , which is why you should make it a habit to clean the DNS cache periodically.

## How to Flush the DNS Cache on Windows 11

 There are multiple methods to flush the DNS cache on Windows 11\. You can use the Run command box, Command Prompt, or even PowerShell. In addition, you can use a batch file to clear the DNS cache in a few clicks, any time you want. Here are the four ways to clear DNS on Windows 11:

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Using the Run Command Box

To flush the DNS cache using the Run command box, do as follows:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type “**ipconfig /flushdns** ” command.  
![Flush DNS Using the Run Command Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-the-run-command-box.jpg)
3. Press**Ctrl + Shift + Enter** keys at once. The Command Prompt will launch, execute the flush command, and close automatically.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QRaEdFMU-Xc?si=OjaiTvlogJy5wHhN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Using CMD

 To clear the DNS resolver cache using CMD, repeat the following steps:

1. Press**Win + R** to open the run dialog box. Type**cmd** and press**Ctrl + Shift + Enter** keys at once.
2. CMD will open with admin privileges.
3. Type “**ipconfig /flushdns** ” command and press the**Enter** key.  
![Flush DNS Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-cmd.jpg)
4. You will see a “**Successfully flushed the DNS Resolver Cache.** ” message after the command execution.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/793ViIxl4tI?si=DDBkjPlPX5bZ-f1Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. Using PowerShell

 PowerShell has a different command to flush the DNS cache on Windows 11\. Here’s how to do it:

1. Press**Win + S** and type**PowerShell** . Click on the**Run as administrator** option in the Start menu.
2. Now, type “**Clear-DnsClientCache** ” in the PowerShell window and press the**Enter** key.  
![Flush DNS Using Powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-powershell.jpg)
3. You won’t see a message after the command executes successfully. But you can open PowerShell again and view the DNS cache to confirm.

### 4\. Using a Batch File

 Opening an app is a slightly time-consuming process. You can save time by creating a batch file once and then running it whenever you need to flush DNS. No need to open the CMD or PowerShell app.

Repeat the following steps to create a DNS-clearing batch file:

1. Press**Win + S** to open Windows Search. Type**Notepad** and click on the first search result.
2. Type the following command in Notepad:**cmd.exe /k ipconfig /flushdns**  
![Flush DNS Using A Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/flush-dns-using-a-batch-file.jpg)
3. Press**Ctrl + S** to save the file. Enter the name “**flushDNS.bat** ” and keep the**Save as type** as**All Files** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Click on the**Save** button.
5. Now go to the batch file location and double-click on it.
6. The Command Prompt will launch and execute the "**/** flushdns" command.
7. Type**exit** and press the**Enter** key to close the command prompt window.

## How to Flush Your Browser's DNS Records

 Do you know that browsers maintain a DNS cache as well? If you face connectivity issues, you should clear the browser's DNS cache and force the browser to rebuild the cache.

 Repeat the following steps to clear Chrome browser’s DNS cache:

1. Launch the Chrome browser and press**Ctrl + T** to open a new tab.
2. Now, type “**chrome://net-internals/#dns** ” in the search bar and press the**Enter** key.
3. Navigate to the**Host resolver cache** section. Click on the**Clear host cache** button to clear cached DNS records in the Chrome browser.

 The process to clear a browser's DNS cache may differ with other browsers like Safari, Opera, and Mozilla. You will have to locate the DNS settings and then wipe out the DNS cache.

## Keep Your DNS Cache Clean on Windows

 Flushing the system's DNS cache periodically can reduce the risk of DNS spoofing and website connectivity issues. The simplest method is to use the ipconfig utility with appropriate parameters to flush the DNS cache. Alternatively, you can use the PowerShell method or create a batch file for the same.

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
<li><a href="https://article-helps.techidaily.com/new-2024-approved-m1s-impact-on-video-editing-software-performance/"><u>[New] 2024 Approved M1's Impact on Video Editing Software Performance</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-techniques-selecting-audioscapes-for-unveiling-videos-for-2024/"><u>[New] Techniques Selecting Audioscapes for Unveiling Videos for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-identifying-and-nurturing-your-brands-character/"><u>2024 Approved Identifying and Nurturing Your Brand's Character</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/2024-approved-masterclass-transforming-everyday-images-for-tiktok-vids/"><u>2024 Approved Masterclass Transforming Everyday Images for TikTok Vids</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-the-ultimate-blueprint-for-telegram-marketplace-success/"><u>2024 Approved The Ultimate Blueprint for Telegram Marketplace Success</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/diy-android-lock-screen-adjusting-and-styling-the-clock-display-for-a-personal-touch/"><u>DIY Android Lock Screen: Adjusting and Styling the Clock Display for a Personal Touch</u></a></li>
<li><a href="https://win11.techidaily.com/easing-software-crash-issues-with-amd-195/"><u>Easing Software Crash Issues with AMD 195</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722960794371-effortless-downloads-of-asus-display-drivers-get-started-now/"><u>Effortless Downloads of ASUS Display Drivers - Get Started Now!</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-photo-editing-flow-on-your-os/"><u>Elevating Photo Editing Flow on Your OS</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-update-defeating-error-code-0x800736cc/"><u>Mastering Windows Update: Defeating Error Code 0X800736CC</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/pc-audio-logging-made-simple-install-x-recorder-for-2024/"><u>Pc Audio Logging Made Simple Install X-Recorder for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-the-common-store-crash-error-0x80073cf3/"><u>Remedying the Common Store Crash: Error 0X80073CF3</u></a></li>
<li><a href="https://win11.techidaily.com/revitalizing-the-invisible-off-screen-window-resurrection-in-win10win11/"><u>Revitalizing the Invisible: Off-Screen Window Resurrection in Win10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-taskbar-pinning-on-w11/"><u>Streamline Taskbar: Pinning on W11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-operations-incorporating-submenus-into-desktop/"><u>Streamlined Operations: Incorporating Submenus Into Desktop</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshooting-and-solving-qualcomm-atheros-bluetooth-connectivity-problems-in-windows-10/"><u>Troubleshooting and Solving Qualcomm Atheros Bluetooth Connectivity Problems in Windows 10</u></a></li>
<li><a href="https://fox-place.techidaily.com/troubleshooting-non-functional-usb-ports-a-comprehve-guide-by-yl-software-experts/"><u>Troubleshooting Non-Functional USB Ports: A Comprehve Guide by YL Software Experts</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-process-to-access-wordpad-in-windows/"><u>Unveiling the Process to Access WordPad in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-when-youre-unable-to-download-any-files-on-a-windows-11-and-11/"><u>What to Do When You’re Unable to Download Any Files on a Windows 11 & 11</u></a></li>
</ul></div>

