---
title: Shifting Control Rights for Common Windows Accounts
date: 2025-01-29T16:27:40.491Z
updated: 2025-02-04T04:32:48.945Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Shifting Control Rights for Common Windows Accounts
excerpt: This Article Describes Shifting Control Rights for Common Windows Accounts
keywords: Window User Rights Change,Access Shift in Windows,Windows Account Privileges,Rights Transfer Windows Users,Altering Account Permissions,Modify User Controls Windows,Transitioning Windows Authority
thumbnail: https://thmb.techidaily.com/1b4d426689bd18514a96cb95968cc5a755b1ea7a22bc00e9feef5b8e8bfa78d1.jpg
---

## Shifting Control Rights for Common Windows Accounts

 By default, standard users on Windows can run programs with elevated privileges if they enter an administrator password when prompted by User Access Control (UAC).

 However, this is not the only behavior that the UAC has for standard user accounts, and you can change it depending on how secure these accounts are and the environment the computer is in. We're going to show you how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## The UAC Behaviors Available for Standard User Accounts

 Unlike when [changing UAC behaviors for administrator accounts](https://www.makeuseof.com/change-user-access-control-works-administrators-windows/), the behaviors for standard user accounts are a little more limited. According to the [Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/threat-protection/security-policy-settings/user-account-control-behavior-of-the-elevation-prompt-for-standard-users) website, here are the behaviors you can choose and what they mean:

* **Automatically deny elevation requests**: This option returns an **Access denied** error message to standard users when they try to perform an operation that requires elevation of privilege. Most organizations that run desktops as standard users configure this policy to reduce help desk calls.
* **Prompt for credentials on the secure desktop**: When an operation requires elevation of privilege, the user is prompted on the secure desktop to enter a different username and password. If the user enters valid credentials, the operation continues with the applicable privilege.
* **Prompt for credentials**: An operation that requires elevation of privilege prompts the user to type an administrative username and password. If the user enters valid credentials, the operation continues with the applicable privilege.

 The default UAC behavior for standard user accounts is **Prompt for credentials**, but Microsoft recommends you change it to **Automatically deny elevation requests**. That way, only users with administrator accounts can decide how the UAC behaves and make choices that will keep the computer safe.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NTQGoOOiJzs?si=zbZwflEfXgBY3qbs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the UAC Behavior for Standard Users in the Local Group Policy Editor

 The easiest way to change the way UAC behaves for standard users is to tweak the **User Account Control: Behavior of the elevation prompt for standard users** policy. To do that, [open the Local Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and follow the steps below.

 The Local Group Policy Editor isn't available by default on Windows Home. As such, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Head to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options**.
2. Right-click the **User Account Control: Behavior of the elevation prompt for standard users** policy and select **Properties** in the menu.  
![modifying the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
3. Expand the dropdown and choose a different UAC behavior.  

![editing the policy for UAC behavior in Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/editing-policy-for-uac-behavior-in-local-group-policy-editor.jpg)
4. Click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KdpTAZ9zonQ?si=5Nd5SPW1axA7GPuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Keep in mind that only administrators can change the behavior of the UAC. If a standard user tried to change it using the Local Group Policy Editor, for example, they'd probably get an **Access denied** error message.

## How to Change the UAC Behavior for Standard Users in the Registry Editor

 If you're looking for another way to change UAC behavior for standard users, or the [Local Group Policy is not working](https://www.makeuseof.com/windows-local-group-policy-unresponsive/) on your computer, you can make changes in the Windows registry instead.

 Before you do that, however, we recommend you [create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) to protect your computer in case you make a mistake. Once you do that, [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) and follow the steps below:

1. Copy **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System** and paste it into the address bar at the top of the Registry Editor.  
![the System key in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-key-registry-editor.jpg)
2. Press **Enter** on your keyboard to go to the **System** key.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/epKTCSREjhI?si=Ez_hObK1FZrmEE7f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Right-click the **ConsentPromptBehaviorUser** value in the right panel and select **Modify**.  
![modifying the ConsentPromptBehaviorUser value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/modifying-consentpromptbehavioruser-in-registry-editor.jpg)
4. In the **Value data** text box, enter **0** for **Automatically deny elevation requests**, **1** for **Prompt for credentials on the secure desktop**, or **3** for **Prompt for credentials**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![setting Value data for ConsentPromptbehavior Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/setting-value-data-for-consentpromptbehavior-registry-editor.jpg)
5. Click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-unlocking-your-creative-potential-style-and-niche/"><u>[Updated] In 2024, Unlocking Your Creative Potential Style & Niche</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-a-comprehensive-look-at-benq-sw320s-4k-features/"><u>2024 Approved A Comprehensive Look at BenQ SW320's 4K Features</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/boosting-views-essential-hashtags-for-trending-shorts-for-2024/"><u>Boosting Views Essential Hashtags for Trending Shorts for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/chronology-conundrum-best-podcast-times-for-2024/"><u>Chronology Conundrum Best Podcast Times for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-delete-visual-fluff-from-win-search-ui/"><u>How to Delete Visual Fluff From Win Search UI</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-smooth-cuts-ahead-3-ways-to-master-transitions-in-fcp/"><u>New In 2024, Smooth Cuts Ahead 3 Ways to Master Transitions in FCP</u></a></li>
<li><a href="https://win11.techidaily.com/notepadnightvisionswitchtutorialwin1011/"><u>NotepadNightVisionSwitchTutorialWin10/11</u></a></li>
<li><a href="https://win11.techidaily.com/sync-your-swat-team-tips-to-stop-mouse-delay-in-bf2/"><u>Sync Your Swat Team: Tips to Stop Mouse Delay in BF2</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tips-resolving-win-access-denials-swiftly/"><u>Tech Tips: Resolving Win Access Denials Swiftly</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/the-complete-2023-bandicam-insight-and-tips-for-2024/"><u>The Complete 2023 Bandicam Insight & Tips for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-insights-in-depth-reviews-and-news/"><u>Tom's Tech Insights: In-Depth Reviews and News</u></a></li>
<li><a href="https://buynow-info.techidaily.com/unboxing-the-lamicall-ss-innovative-features-in-this-thoughtful-tablet-mount-review/"><u>Unboxing the Lamicall S's Innovative Features in This Thoughtful Tablet Mount Review</u></a></li>
<li><a href="https://article-files.techidaily.com/unveiling-srts-potential-in-subtitle-format-sub-for-2024/"><u>Unveiling SRT's Potential in Subtitle Format (SUB) for 2024</u></a></li>
</ul></div>

