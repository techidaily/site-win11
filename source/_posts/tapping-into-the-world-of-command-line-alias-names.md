---
title: Tapping Into the World of Command Line Alias Names
date: 2024-09-05T08:32:30.780Z
updated: 2024-09-06T08:32:30.780Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tapping Into the World of Command Line Alias Names
excerpt: This Article Describes Tapping Into the World of Command Line Alias Names
keywords: Command Line Alias Basics,Aliasing in Terminal Commands,CLI Alias Shortcuts,Efficient Cmd Execution,Alias Creation Tips,Simplifying Cmd Inputs,Mastering Command Line ALIAS
thumbnail: https://thmb.techidaily.com/f6689b1ce3b098830c1181e612252ff5b928460b4d7d4122dbd300e015bd5d6c.jpg
---

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134493/18498" target="_top" id="2134493">
  <img src="//a.impactradius-go.com/display-ad/18498-2134493" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134493/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Tapping Into the World of Command Line Alias Names

 If you're trying to open an app like Microsoft Paint in the Run Dialog and see an error message, it could be caused by your app aliases. But what exactly are App Execution Aliases, where do you find them, and how do you use them?

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135357/19272" target="_top" id="2135357">
  <img src="//a.impactradius-go.com/display-ad/19272-2135357" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135357/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Are App Execution Aliases?

 An alias is an alternative name given to something. The most obvious example is the codename given to a spy or undercover agent. On Windows, aliases have nothing to do with spying. Instead, they are used for streamlining tasks, such as entering commands.

 Windows 10 and 11 both allow aliases to be declared for some apps by default. The available apps vary but are often those commonly associated with command line tools. Giving an app an alias allows it to be executed using a shorter title rather than the full name or path.

 App aliases can be used in several[Windows Command Line Interfaces](https://www.makeuseof.com/what-is-cli-what-does-it-stand-for/) (CLI), including the Run Dialog, Command Prompt, and[PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) . If you use these tools with any regularity, app aliases can help to streamline entering commands.

<!-- affiliate ads begin -->
<span id="1983539">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983539.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983539">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983539.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983539%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983539/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Enable App Execution Aliases in Settings

 You can enable and disable aliases for compatible apps in the main settings in both Windows 10 and 11\. If more than one app uses the same alias name, you can choose which has the alias applied to it.

In Windows 11:

1. Open**Settings > Apps** , and look for**Advanced app settings** .
2. In the advanced app settings, click**App execution aliases** to see the list of compatible apps.
3. Use the slider switches to enable or disable the alias for each app. You can see the alias name below each app.

![app aliases in windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win11.jpg)

In Windows 10:

1. If you're using Windows 10, you'll find the aliases in**Settings > Apps & features** .
2. Click the**App execution aliases** link near the top of the Apps & features page.
3. You can then enable and disable aliases using the switches.

![app aliases in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-win10.jpg)

 By default, in both Windows 10 and 11, you can only enable or disable existing app aliases. But if you don't mind editing the Registry, you can create new aliases for many other apps.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135403/19272" target="_top" id="2135403">
  <img src="//a.impactradius-go.com/display-ad/19272-2135403" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135403/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Create App Execution Aliases in Registry Editor

 Before editing or creating registry keys, it is advisable to[create a full backup of the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . Of course, you should also ensure you understand how to restore the Registry from that backup.

 The process below for creating app execution aliases in the Registry Editor should be the same in both Windows 10 and 11.

1. Open**Windows Search** , type**Registry Editor** , and click on the search result to open it.
2. In the editor, navigate to **HKEY\_CURRENT\_USER\\Software\\Microsoft\\Windows\\CurrentVersion\\App Paths** .
3. Next, right-click on the**App Paths** key in the left-hand pane, and select**New > Key** .
4. Give the new key an alias name that relates to the app and ends with .exe. For example, if the alias is for Calendar, call it something like cal.exe.
5. With the alias selected, double-click the**Default** value in the right-hand pane.  
![editing app aliases in registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-alias-regedit.jpg)
6. In the Value data field, you will need to enter the full path to the app executable file. For example**C:\\Program Files (x86)\\Calendar.exe** .
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132161/7443" target="_top" id="2132161">
  <img src="//a.impactradius-go.com/display-ad/7443-2132161" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132161/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Right-click in the right pane and select**New > String value** . Name the string**path** . The change the Value data to the same path as above, but without the app filename.

 You can now close the Registry Editor. The new App Execution Alias will now be available to use in the Windows CLIs.

<!-- affiliate ads begin -->
<span id="1938136">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938136.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938136">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938136.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938136%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938136/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Using and Creating App Execution Aliases

 Entering commands into tools such as Command Prompt and PowerShell can be laborious. You can streamline that process by enabling or creating aliases for apps that commonly feature in those commands. Why type out a full path to an executable file when you can point to it with a few keystrokes?


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
<li><a href="https://extra-information.techidaily.com/new-aetherial-acts-the-vr-stage/"><u>[New] Aetherial Acts  The VR Stage</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-reviewing-the-core-of-magix-photo-framework/"><u>[New] Reviewing the Core of MAGIX Photo Framework</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ve-financial-success-with-youtube-ad-profit-techniques-for-2024/"><u>Achieve Financial Success with YouTube Ad Profit Techniques for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/commanding-victory-a-quick-guide-to-voice-commands-on-windows-11/"><u>Commanding Victory: A Quick Guide to Voice Commands on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-error-0xc0000001-expert-tips/"><u>Correcting Windows Error 0xC0000001: Expert Tips</u></a></li>
<li><a href="https://win11.techidaily.com/deciding-on-the-usefulness-of-windows-11-s-mode/"><u>Deciding on the Usefulness of Windows 11 S Mode</u></a></li>
<li><a href="https://win11.techidaily.com/dive-deep-how-to-navigate-the-mspcm-bar-in-win11-systems/"><u>Dive Deep: How to Navigate the MSPCM Bar in Win11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-your-windows-snipping-experience-with-proven-fixes/"><u>Enhancing Your Windows Snipping Experience with Proven Fixes.</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-the-boundaries-why-chatgpt-may-not-be-suitable-for-predicting-crypto-trends/"><u>Exploring the Boundaries: Why ChatGPT May Not Be Suitable for Predicting Crypto Trends</u></a></li>
<li><a href="https://win11.techidaily.com/from-blank-screen-to-focused-workspace-reviving-hidden-panes-with-these-6-effortless-methods/"><u>From Blank Screen to Focused Workspace: Reviving Hidden Panes with These 6 Effortless Methods</u></a></li>
<li><a href="https://win11.techidaily.com/guidance-to-rectify-microsoft-store-error-0x80072efd/"><u>Guidance to Rectify Microsoft Store Error 0X80072EFD</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-get-help-app-not-working-on-windows-11/"><u>How to Fix the Get Help App Not Working on Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-best-webcams-for-podcast/"><u>In 2024, Best Webcams for Podcast</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-expert-advice-on-tailoring-game-sounds-to-stand-out-in-the-virtual-arena-of-free-fire/"><u>In 2024, Expert Advice on Tailoring Game Sounds to Stand Out in the Virtual Arena of Free Fire</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-intercept-text-messages-on-tecno-spark-20-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Intercept Text Messages on Tecno Spark 20 Pro | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/insta-a-lister-secrets-unveiling-the-fastest-way-to-fame-with-our-expert-guide-for-2024/"><u>Insta A-Lister Secrets  Unveiling the Fastest Way to Fame with Our Expert Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/instructions-to-launch-google-play-on-w11/"><u>Instructions to Launch Google Play on W11</u></a></li>
<li><a href="https://win11.techidaily.com/launching-a-linux-vm-via-hyper-v-in-windows-environment/"><u>Launching a Linux VM via Hyper-V in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/legacy-software-understanding/"><u>Legacy Software Understanding</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/loop-video-magic-keep-your-followers-hooked-with-instagram-boomers-for-2024/"><u>Loop Video Magic  Keep Your Followers Hooked with Instagram Boomers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-windows-taskbar-showing-internet-speed/"><u>Maximizing Windows Taskbar: Showing Internet Speed</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-no-mistakes-top-10-windows-11-errors-to-evade/"><u>Navigating No Mistakes: Top 10 Windows 11 Errors to Evade</u></a></li>
<li><a href="https://extra-tips.techidaily.com/navigating-virtual-territories-metaverse-and-multiverse-guide/"><u>Navigating Virtual Territories  Metaverse & Multiverse Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-updates-error-0x80246007-roadblock-on-1011/"><u>Navigating Windows Update's Error 0X80246007 Roadblock on 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-system-load-visualizers/"><u>Optimal System Load Visualizers</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-failures-in-windows-defrag-process/"><u>Remedying Failures in Windows Defrag Process</u></a></li>
<li><a href="https://win11.techidaily.com/reveal-and-recognize-six-ways-to-discover-your-pc-model/"><u>Reveal & Recognize - Six Ways To Discover Your PC Model</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-gaining-windows-high-level-control/"><u>Steps for Gaining Windows' High-Level Control</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/switching-file-extensions-for-your-mac-snapshots-for-2024/"><u>Switching File Extensions for Your Mac Snapshots for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-memory-couldnt-be-written-in-windows/"><u>Tackling 'Memory Couldn’t Be Written' In Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-list-of-uninstall-routes-in-windows-11-118-chars/"><u>The Ultimate List of Uninstall Routes in Windows 11 (118 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-eradicating-breakpoint-exception-error-on-pc/"><u>Tips for Eradicating Breakpoint Exception Error on PC</u></a></li>
<li><a href="https://win11.techidaily.com/uniting-two-network-types-a-comprehensive-windows-guide/"><u>Uniting Two Network Types: A Comprehensive Windows Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-11s-web-interface-controls/"><u>Unveiling Windows 11'S Web Interface Controls</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-icon-alignment-guide-unite-not-bind/"><u>Win 11 Icon Alignment Guide - Unite Not Bind</u></a></li>
</ul></div>
