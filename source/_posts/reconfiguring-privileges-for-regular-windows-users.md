---
title: Reconfiguring Privileges for Regular Windows Users
date: 2024-12-06T08:47:37.203Z
updated: 2024-12-06T16:51:16.484Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reconfiguring Privileges for Regular Windows Users
excerpt: This Article Describes Reconfiguring Privileges for Regular Windows Users
keywords: User Privilege Adjustment,Windows Role Permissions,Access Control Revision,Security Group Updates,Accounting Privileges Alteration,Regular Users Rights Management,Windows Access Configuration
thumbnail: https://thmb.techidaily.com/78573d1d50e3fe1a208211e6210a893de5cb63383e5008c1e4699b06b4a4f916.jpg
---

## Reconfiguring Privileges for Regular Windows Users

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## The UAC Behaviors Available for Standard User Accounts

 Unlike when [changing UAC behaviors for administrator accounts](https://www.makeuseof.com/change-user-access-control-works-administrators-windows/), the behaviors for standard user accounts are a little more limited. According to the [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-standard-users) website, here are the behaviors you can choose and what they mean:

* **Automatically deny elevation requests**: This option returns an **Access denied** error message to standard users when they try to perform an operation that requires elevation of privilege. Most organizations that run desktops as standard users configure this policy to reduce help desk calls.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a different username and password. If the user enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the user to type an administrative username and password. If the user enters valid credentials, the operation continues with the applicable privilege.

 The default UAC behavior for standard user accounts is **Prompt for credentials**, but Microsoft recommends you change it to **Automatically deny elevation requests**. That way, only users with administrator accounts can decide how the UAC behaves and make choices that will keep the computer safe.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
3. Expand the dropdown and choose a different UAC behavior.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.

3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now restart your computer to allow the changes to take effect.

## Control UAC's Behavior for Standard Users on Windows

 UAC is an integral part of protecting your Windows computer from malicious programs that want to run with elevated privileges. While you can't make it elevate programs without prompting, you can make it stricter by setting it to **Automatically deny elevation requests**. And, as you can see, it is quite easy to do, whether you're using the Local Group Policy Editor or the Registry Editor.

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-guidance.techidaily.com/new-unlock-your-lost-iphone-xs-potentials-with-these-tricks/"><u>[New] Unlock Your Lost iPhone X's Potentials with These Tricks</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ideo-traffic-triumph-key-youtube-seo-tools-for-2024/"><u>[New] Video Traffic Triumph - Key YouTube SEO Tools for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-the-definitive-guide-for-choosing-best-youtube-visual-elements/"><u>[Updated] 2024 Approved The Definitive Guide for Choosing Best YouTube Visual Elements</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-best-of-breed-exceptional-webcam-supports/"><u>2024 Approved Best Of Breed Exceptional Webcam Supports</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-securely-snapshot-streaming-top-6-techniques-for-netflix-on-mac/"><u>2024 Approved Securely Snapshot Streaming Top 6 Techniques for Netflix on Mac</u></a></li>
<li><a href="https://apple-account.techidaily.com/apple-id-is-greyed-out-from-apple-iphone-7-how-to-bypass-by-drfone-ios/"><u>Apple ID is Greyed Out From Apple iPhone 7 How to Bypass?</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-0x800f0845-error-in-windows-updates/"><u>Correcting 0X800f0845 Error in Windows Updates</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-quick-launch-to-begin-with-onedrive-and-file-explorer/"><u>Customizing Quick Launch to Begin with OneDrive and File Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-visibility-of-pinned-apps-on-windows-11/"><u>Enhance Visibility of Pinned Apps on Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-sharefake-gps-on-uber-for-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to share/fake gps on Uber for Samsung Galaxy F15 5G | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-master-mac-gifs-top-10-recording-tools/"><u>In 2024, Master Mac GIFs Top 10 Recording Tools</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unlocking-the-power-of-panoramic-videography-with-premieres-tools/"><u>In 2024, Unlocking the Power of Panoramic Videography with Premiere's Tools</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-microsoft-store-error-code-0x800704cf-in-windows/"><u>Mastery over Microsoft Store Error: Code 0X800704CF in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-and-fix-common-microsoft-store-login-issues/"><u>Navigate and Fix Common Microsoft Store Login Issues</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-honor-100-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Honor 100? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-failed-connections-to-nvidia-geforce-ex/"><u>Troubleshooting Failed Connections to NVIDIA GeForce Ex</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-lan-access-issues-on-windows-mc/"><u>Troubleshooting LAN Access Issues on Windows MC</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-socket-programming-in-python-for-windows-files/"><u>Understanding Socket Programming in Python for Windows Files</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-connections-fixes-for-failed-nvidia-experience-in-windows-11/"><u>Unlocking Connections: Fixes for Failed Nvidia Experience in Windows 11</u></a></li>
</ul></div>

