---
title: "Windows Mastery: Illuminating Peak & Trough States"
date: 2024-10-13T20:42:21.470Z
updated: 2024-10-15T17:54:51.947Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Mastery: Illuminating Peak & Trough States"
excerpt: "This Article Describes Windows Mastery: Illuminating Peak & Trough States"
keywords: Windows Skill,Power Windows,System Optimization,Trend Analysis,Tech Proficiency,Mastery Guide,Peak Performance
thumbnail: https://thmb.techidaily.com/5d226635edaf435094da0cef0471d4f2b3210c149d391d468a9425edc03d4511.png
---

## Windows Mastery: Illuminating Peak & Trough States

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many[ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

![Cmd in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-cmd.jpg)

To show the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c -ATTRIB_HIDE`

To hide the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c +ATTRIB_HIDE`

To show the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec -ATTRIB_HIDE`

To hide the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec +ATTRIB_HIDE`

 After you have typed in the command you want in the CMD window, hit the**Enter** key on your keyboard to run it.

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135348/19272" target="_top" id="2135348">
  <img src="//a.impactradius-go.com/display-ad/19272-2135348" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135348/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123735/7443" target="_top" id="2123735">
  <img src="//a.impactradius-go.com/display-ad/7443-2123735" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123735/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123728/7443" target="_top" id="2123728">
  <img src="//a.impactradius-go.com/display-ad/7443-2123728" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123728/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151855/7443" target="_top" id="2151855">
  <img src="//a.impactradius-go.com/display-ad/7443-2151855" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151855/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Add or Remove the Minimum and Maximum Processor States From Power Options

 Setting the minimum or maximum processor state on your Windows computer is vital to helping you get the performance you want from it. If you can’t see these options in the Power Options menu, you can easily reveal them with either Command Prompt or the Registry Editor. And after you’re done tweaking the states, you can hide them for their protection.

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
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-premier-4k-laptop-choices-for-gamers/"><u>[New] 2024 Approved Premier 4K Laptop Choices for Gamers</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-a-guide-to-navigating-posting-on-altered-instagram-landscape-for-2024/"><u>[New] A Guide to Navigating Posting on Altered Instagram Landscape for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-halt-autoplay-youtube-recommendations-for-2024/"><u>[Updated] Halt Autoplay YouTube Recommendations for 2024</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/5-fast-methods-monitoring-your-pc-games-fps-in-under-a-minute/"><u>5 Fast Methods: Monitoring Your PC Game's FPS in Under a Minute!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/bezplatny-prevoze-wmv-v-soucasti-mov-onlineskypni-a-nesmirny-latky-konverter/"><u>Bezplatný Prevoze Wmv V Součásti MOV - Onlineskypní A Nesmírný Látky Konverter</u></a></li>
<li><a href="https://win-answers.techidaily.com/effective-techniques-to-address-minecraft-error-with-the-crossbow-feature/"><u>Effective Techniques to Address Minecraft Error with the Crossbow Feature</u></a></li>
<li><a href="https://extra-resources.techidaily.com/how-to-make-reels-on-instagram/"><u>How to Make Reels on Instagram</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-best-3-nokia-c12-plus-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>In 2024, Best 3 Nokia C12 Plus Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/infuse-windows-ui-with-supernatural-shortcuts/"><u>Infuse Windows UI with Supernatural Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-approaches-to-attach-reminders-in-win11win10/"><u>Innovative Approaches to Attach Reminders in Win11/Win10</u></a></li>
<li><a href="https://win11.techidaily.com/instant-guide-forcibly-disable-windows-11-print-devices/"><u>Instant Guide: Forcibly Disable Windows 11 Print Devices</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/maximize-conversions-using-cookiebot-seo-solutions/"><u>Maximize Conversions Using Cookiebot SEO Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-a-computer-name-mistake-on-windows-11/"><u>Reversing a Computer Name Mistake on Windows 11</u></a></li>
</ul></div>

