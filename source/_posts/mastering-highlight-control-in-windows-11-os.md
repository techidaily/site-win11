---
title: Mastering Highlight Control in Windows 11 OS
date: 2025-01-01T18:23:49.990Z
updated: 2025-01-06T17:34:01.213Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Highlight Control in Windows 11 OS
excerpt: This Article Describes Mastering Highlight Control in Windows 11 OS
keywords: Win11 HC Mastery,HC Control Guide,Windows 11 Light Control,Optimal HC Windows 11,Advanced HC Techniques,HC Tips for Win11,Mastering OS Highlights
thumbnail: https://thmb.techidaily.com/0e4e69a266c0e21cfaa72121cb274553aaa959ab8154e71b42e7a2317f1338de.png
---

## Mastering Highlight Control in Windows 11 OS

 Search highlights is a feature that helps you discover interesting content whenever you launch Windows Search. If you find that they aren’t popping up, there are several ways for you to turn them on. And if you find them to be bothersome, well, you can turn them off and continue enjoying Windows as if they never existed.

 So, keep on reading to find out three ways to turn search highlights on and off.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Turn Search Highlights On and Off in the Settings App

 Press **Win + I** to open the Settings app. Then, select **Privacy & security** on the left side menu, and then click on **Search permissions** in the right panel.

![the privacy and security page on Windows with Search permissions showing in the right panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/grbt-5VvbuI?si=qnoirlmljslpqcQj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Scroll down to the **More settings** section, and then click the toggle under **Show search highlights** to turn the feature on or off.

![the Seach permissions page on Windows 11 with the More settings section showing and the toggle for Show search highlights set to on](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-search-permissions-settings.jpg)

 You should no longer see search lights now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qbuund2HKOQ?si=NaGHqIrx8hSL7gWV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Turn Search Highlights On and Off in the Local Group Policy Editor

 Press **Win + R** to open the Windows Run dialog box, type **gpedit.msc** in the text box, and then hit the **Enter** key. For more ways to launch the tool, read our guide on [ways to open the Local Group Policy Editor on Windows 11](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).

 On the left side menu, navigate to **Computer Configuration > Administrative Templates > Windows Components > Search**. Then, in the right panel, double-click the **Allow search highlights** policy to edit it.

![the Local Group Policy Editor on Windows with the Allow search highlights policy highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/lgpe-windows-allow-search-highlights-policy.jpg)

 To show search highlights, make sure the **Not Configured** or **Enabled** radio button is checked, and then click **OK**.

![the Allow search highlights policy being edited on Windows and it is set to Not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/allow-search-highlights-not-configured-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K7fATC_lI7o?si=UFotPJqflDRZr-mv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To disable search highlights, check the **Disabled** radio button, and then click **OK**.

## 3\. Turn Search Highlights On and Off in the Registry Editor

 Press **Win + R** to open the Windows Run dialog box, type **regedit** in the text box, and then hit the **Enter** key. Click **Yes** in the UAC prompt to finally launch the Registry Editor.

 Before you proceed, we recommend that you read our guide on [how to back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). This may come in handy in case you accidentally break the Windows Registry.

 In the address bar of the Registry Editor, copy and paste the below text, and then press **Enter**:

`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\SearchSettings`

 Right-click the **SearchSettings** key on the left side menu and select **New > DWORD (32-bit) Value** in the menu that appears. Then, name the value **IsDynamicSearchBoxEnabled**.

![creating a dword value in the Windows registry for the SearchSettings key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/creating-dword-windows-registry.jpg)

 In the right panel, double-click **IsDynamicSearchBoxEnabled** (the value you just created) and then enter **1** in the **Value data** text box to turn search highlights on. Then, click **OK** to apply the change.

![the IsDynamicSearchBoxEnabled value in the Registry Editor and Value data has been set to 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/editing-isdynamicsearchboxenabled-value-windows-registry.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To turn search highlights off, enter **0** in the **Value data** text box, and then click **OK**.

## Control Your Search Highlights on Windows 11

 Windows 11 being customizable is what makes interacting with the OS enjoyable. The power is in your hands whether you want to see search highlights or not in Windows Search. And now you know three ways to enable or disable them.

 So, keep on reading to find out three ways to turn search highlights on and off.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/nduring-removal-protocol-say-no-to-youtube-shorts-for-2024/"><u>[New] Enduring Removal Protocol Say No to YouTube Shorts for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-what-is-virtual-reality-and-how-does-it-work/"><u>[New] In 2024, What Is Virtual Reality and How Does It Work?</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-tick-tock-restoring-windows-time-service/"><u>Fixing the Tick-Tock: Restoring Windows Time Service</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/how-to-track-and-blur-faces-in-premiere-pro/"><u>How To Track and Blur Faces in Premiere Pro</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-6-to-others-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 6 to others devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-exception-breakpoint-hit-on-windows-issues/"><u>Overcoming Exception Breakpoint Hit on Windows Issues</u></a></li>
<li><a href="https://win11.techidaily.com/pathways-to-troubleshooting-with-winrm-utility/"><u>Pathways to Troubleshooting with WinRM Utility</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-windows-assertion-of-an-unempty-directory-error-x80070091/"><u>Remedying Windows' Assertion of an Unempty Directory (Error X80070091)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/reviving-the-fn-keys-on-a-dell-laptop-the-definitive-guide-to-restoration-and-maintenveeance/"><u>Reviving the Fn Keys on a Dell Laptop: The Definitive Guide to Restoration and Maintenveeance</u></a></li>
<li><a href="https://tech-revival.techidaily.com/step-by-step-guide-clearing-your-chatgpt-conversation-records/"><u>Step-by-Step Guide: Clearing Your ChatGPT Conversation Records</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-common-freezing-issues-with-steam-and-games-on-windows/"><u>Tackling Common Freezing Issues with Steam and Games on Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unleashing-imagination-with-these-grading-techniques-7-must-try-tips/"><u>Unleashing Imagination with These Grading Techniques 7 Must-Try Tips</u></a></li>
<li><a href="https://win11.techidaily.com/victory-over-visual-vexations-solve-sonic-adventures-full-screen-crash-issues-in-windows-11/"><u>Victory over Visual Vexations: Solve Sonic Adventure's Full-Screen Crash Issues in Windows 11</u></a></li>
</ul></div>

