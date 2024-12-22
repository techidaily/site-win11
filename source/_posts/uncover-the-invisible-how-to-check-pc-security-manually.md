---
title: "Uncover the Invisible: How to Check PC Security Manually"
date: 2024-12-18T17:07:38.714Z
updated: 2024-12-22T17:06:24.014Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Uncover the Invisible: How to Check PC Security Manually"
excerpt: "This Article Describes Uncover the Invisible: How to Check PC Security Manually"
keywords: PC Safety Tips,Secure PC Checks,Manual Patch Testing,PC Threat Scanning,Cyber Security Self-Assess,Malware Inspection Guide,System Vulnerability Assess
thumbnail: https://thmb.techidaily.com/9828bf793f93780e9596bdf90064698c2faf8ab4424f88be5c51fa1662b48994.jpg
---

## Uncover the Invisible: How to Check PC Security Manually

 Keyloggers, cryptojackers, spyware, and rootkits are all types of malware that hackers use to infect victims' devices. While some of these infections let hackers remotely connect to the victim's computer, others monitor the person's keystrokes, use the system's resources, or simply spy on the targeted person's activity.

 If you suspect that your Windows device might have been hacked, here are some practical steps you can take to check that.

## Before We Get Started…

 Before investigating whether your device has been compromised, close all third-party and Windows applications. This will reduce the entries Task Manager or other[any alternatives to the Task Manager](https://www.makeuseof.com/tag/5-powerful-alternatives-windows-task-manager/) you might be using and allow you to effectively identify suspicious connections established on your computer.

 Afterward,[run a malware scan on your device using Microsoft Defender](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/) or any reliable third-party antivirus software you usually use. This step will help you detect and automatically remove light infections inside your device, and they won't distract you when searching for more severe infections or security breaches.

 Once you have closed down all nonessential processes and carried out a malware scan, you can start looking for any malicious programs lurking on your system.

## How to Inspect Your Device for Spyware or Hacking Attempts

 In the modern era, malware infections are usually programmed to actively (but secretly) operate on the victim's computer. For instance,[cryptojackers](https://www.makeuseof.com/what-is-cryptojacking-how-to-detect-it/) use victims' computer resources for crypto mining, keyloggers gather login credentials by monitoring keystrokes, and spyware tracks users' activity in real-time and shares it with the hackers.

 Each of these malware types relies on a remote connection to the hacker's server where the data is sent, the mining software runs, or whatever else the hacker is trying to accomplish. By identifying those suspicious connections established on our device, we can determine whether our device has actually been compromised.

### 1\. Check for Suspicious Connections

 You can check for suspicious connections on your computer in several ways, but the method we'll show you will use a built-in utility in Windows called the Command Prompt. Here's how you can find the remote connections set up with your device using Command Prompt:

1. Type**"Command Prompt"** in Windows Search.
2. Right-click the**Command Prompt** app and click**Run as administrator** .
3. Simply type the following command and hit**Enter** .  
netstat -ano

![Run Netstat-ano Command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/1-run-netstat-ano-command-in-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The above command will show you all the TCP connections the apps, programs, and services have established to remote hosts.

 Pay attention mainly to the**State** column, where you'll find three main terms:**Established** ,**Listening** , and**Time\_Wait** . From these three, focus on the connections whose state identifies as**Established** . The**"Established"** state indicates a real-time connection between your computer and the remote IP address.

![Find the Suspicious Process with Established Connection in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/2-find-the-suspicious-process-with-established-connection-in-command-prompt.jpg)

 Don't panic if you see a lot of established connections. Most of the time, these connections are made to a company server whose services you use, like Google, Microsoft, etc. However, you need to analyze each of these connections separately. This will help you determine if there are suspicious connections being made to a hacker's server.

 Do not close the Command Prompt; we will use the netstat information in the next steps.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Analyze Any Connections That Seem Suspicious

Here's how you can analyze the suspicious connections:

1. Copy the IP address from the**Foreign Address** column in the**Command Prompt** .
2. Go to a popular IP location lookup site, such as IPLocation.net.
3. Paste your copied IP address here and click the**IP Lookup** button.  
![click on the ip lookup button after pasting the copied ip address on ip location website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/click-on-the-ip-lookup-button-after-pasting-the-copied-ip-address-on-ip-location-website.jpg)

 This website will provide you with information about the IP address. Check the ISP and organization that use this IP address. If the IP address belongs to a well-known company whose services you use, such as Google LLC, Microsoft Corporation, etc., there is nothing to worry about.

 However, if you see a suspicious company listed here whose services you don't use, there is a good chance that someone is spying on you. Thus, you will need to identify the process or service using this address for remote connection to ensure it isn't malicious.

### 3\. Find and Analyze Any Malicious Processes

 To locate the malicious program scammers may have been using to snoop on your device, you have to identify the associated process. Here's how to find it:

1. Note the**PID** next to the suspicious**Established** connection in Command Prompt.  
![Note the PID Next to the Suspicious Established Connection in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/4-note-the-pid-next-to-the-suspicious-established-connection-in-command-prompt.jpg)
2. Open Task Manager. (See the[different ways to open Task Manager in Windows 10](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) and[11](https://www.makeuseof.com/how-to-access-task-manager-on-windows-11/) )
3. Go to the**Details** tab.
4. Click the**PID column** to sort processes according to their PIDs.
5. Find the process with the same**PID** that you noted down earlier.  
![Find the Process with Relevant PID in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/5-find-the-process-with-relevant-pid-in-windows-task-manager.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-0Ww1YIIUe4?si=cQ-Gkh9UCJABuPZU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If the process belongs to a third-party service that you frequently use, you don't need to close it. However, you should still verify that this process belongs to the company you believe it does,as a hacker can hide their malicious processes under the guise of a malicious one. So, right-click on the suspicious process and select**Properties** .

![Select Properties by Right-clicking on the Suspicious Process in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/6-select-properties-by-right-clicking-on-the-suspicious-process-in-windows-task-manager.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cC-HtDQVoG0?si=nQcoa7q8q2IL8U0m" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then, navigate to the**Details** tab for more information about the process.

![Navigate to Details Tab in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/7-navigate-to-details-tab-in-windows-task-manager.jpg)

 If there is any discrepancy in process details or the process itself seems suspicious, it is best to remove the associated program.

### 4\. Remove Any Suspicious Programs

 To identify and remove the malicious apps behind these suspicious processes, follow these steps:

1. Right-click the shady process and select**Open file location** .  
![Click on Open File Location by Right-clicking on Malicious Process in Windows Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/8-click-on-open-file-location-by-right-clicking-on-malicious-process-in-windows-task-manager.jpg)
2. Once again, ensure the file is not associated with Windows or any other critical application.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. If you're sure it's malware, right-click it and delete it.  
![Delete the Suspicious File After Locating it in Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/9-delete-the-suspicious-file-after-locating-it-in-windows-file-explorer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 5\. Take Professional Help When Necessary

 Hopefully, following the above process will help you detect and remove the malicious program, thereby preventing hackers from spying on or stealing your personal information.

 However, you should be aware that hackers can conceal their malware from netstat output by programming it that way. Likewise, they can code the program so it does not appear in Task Manager. Seeing no suspicious connections in the netstat output or not finding the suspicious process in Task Manager doesn't mean your device is safe.

 Therefore, if you see signs of a hacked device in your system, such as high resource consumption in Task Manager, system slowdowns, unknown apps getting installed, Windows Defender turning off frequently, the creation of suspicious new user accounts, and similar, you should consult a professional. Only then can you be sure that your device is completely secure.

## Don't Let Hackers Spy on You for Long

 Microsoft consistently updates the Windows operating system to make it more secure, but hackers still find loopholes and hack into Windows devices. Hopefully, our guide will help you identify if any suspicious hacker is monitoring your activity. If you follow the tips correctly, you'll be able to remove the suspicious app and disconnect the connection to the hacker's server.

 If you're still suspicious and don't want to risk your precious data, you should seek professional assistance.

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
<li><a href="https://driver-download.techidaily.com/get-the-most-recent-intel-iris-plus-g7-gt4e-655-gpu-drivers-for-windows-operating-systems/"><u>Get the Most Recent Intel® Iris Plus G7 (GT4e) 655 GPU Drivers for Windows Operating Systems</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-restore-a-bricked-vivo-y100a-back-to-operation-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Restore a Bricked Vivo Y100A Back to Operation | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-se-to-other-iphone-13-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone SE to other iPhone 13 devices? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-vivo-t2-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Vivo T2 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-nubia-red-magic-8s-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location On Facebook Dating for your Nubia Red Magic 8S Pro+ | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/outlook-notification-breakdown-identifying-and-solving-issues/"><u>Outlook Notification Breakdown: Identifying and Solving Issues</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-operating-systems-artific-written-by-user/"><u>Redefining Operating Systems: Artific Written by User</u></a></li>
<li><a href="https://win11.techidaily.com/swift-recovery-of-error-code-31-on-windows-systems/"><u>Swift Recovery of Error Code 31 on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/the-bygone-elements-of-modern-windows/"><u>The Bygone Elements of Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-comprehensive-guide-to-office-2019-in-windows-1011/"><u>The Comprehensive Guide to Office 2019 in Windows 10/11</u></a></li>
<li><a href="https://win-dash.techidaily.com/updated-drivers-for-nvidia-geforce-210-on-windows-10-enhanced-performance-and-stability/"><u>Updated Drivers for Nvidia GeForce 210 on Windows 10: Enhanced Performance and Stability</u></a></li>
</ul></div>

