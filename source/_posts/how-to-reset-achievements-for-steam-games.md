---
title: How to Reset Achievements for Steam Games
date: 2024-10-16T22:59:36.978Z
updated: 2024-10-21T06:38:39.032Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Reset Achievements for Steam Games
excerpt: This Article Describes How to Reset Achievements for Steam Games
keywords: Steam Game Reset,Achievement Redo,Game Score Change,Steam Scores Fix,Restart Achievements,Unlock Games Fast,Reset Steam Points
thumbnail: https://thmb.techidaily.com/e8d273b848143c340000d0079f7c83e7faa1151d78bf679fca424eb3bb1ead67.jpg
---

## How to Reset Achievements for Steam Games

 Unlocking achievements is fun. Locking them again isn't so fun, especially if the developer hasn't offered the player an option to do so in the first place.

 Thankfully, Steam has a catch-all solution to resetting achievements for individual games.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Resetting Steam Achievements

![screenshot of a steam achievement list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/screenshot_of_steam_achievements_list.jpg)

 There's no simple switch for resetting Steam achievements. Some games offer the option to reset player progress, and this may include Steam achievements as well.

 You'll want to make sure this simpler, in-game method isn't available first.

 To reset your progress for Steam achievements, we'll need to use something called the Steam Client Console.

## Enable Steam Client Console

 The easiest way to open the Steam Client Console is by hitting **Win + R** to open the Windows Run Command Dialog.

 If you can't use this method to open the Run window, have a look at our guide on [ways to open the Run Command Dialog](https://www.makeuseof.com/windows-open-run-command-dialog-box/).

 With the Run window open, input the following command.

`steam://open/console`

 This will open Steam with a new tab available from the main window. The **Console** tab.

![screenshot of the steam client console](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/screenshot_of_steam_client_console_overview-1.jpg)

 This is where we'll input our commands to reset achievements.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043617/7443" target="_top" id="2043617">
  <img src="//a.impactradius-go.com/display-ad/7443-2043617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043617/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Achievements and Stat Commands

![screenshot of achievement clear in steam client console](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/screenshot_of_achievement_clear_in_steam_client_console.jpg)

 The command we'll need to use is **achievement\_clear**. On its own, it doesn't do anything. We need a couple of things first.

 Head over to [**SteamDB**, or the Steam Database](https://steamdb.info/apps/), and search for the game associated with the achievement you're resetting.

![screenshot of half life 2 in steam database](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/screenshot_of_hl2_in_steam_db.jpg)

 Copy the **AppID** listed against your game. Note this down or paste it somewhere you'll remember. Scroll down the page and click on the **Achievements** tab.

![screenshot of half life 2 achievements in steam database](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/screenshot_of_hl2_achievements_in_steam_db.jpg)

<!-- affiliate ads begin -->
<span id="1484963">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1484963.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1484963">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1484963.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1484963%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1484963/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This will list all the achievements and their **API Names**. Pick out the achievement you want to reset and note that name.

 Now you have your command. Input the information you've gathered like so.

`achievement_clear <AppID> <Achievement API Name>`

 Using the example in our screenshots, the code should look something like this. Remember to use the achievement name from SteamDB, and not simply the in-game name of the achievement.

![screenshot of the steam client console with an input command filled out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/screenshot_of_resetting_achievement_steam_client_console_filled_out.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886044/19272" target="_top" id="1886044">
  <img src="//a.impactradius-go.com/display-ad/19272-1886044" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886044/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You'll know it worked if you see the message **achievement\_clear success**.

 There is a second command that accompanies the above. Inputting **reset\_all\_stats** followed by an AppID will reset any stats Steam tracks for that game. For example, kills or time played. Be careful with this command, as it can behave differently depending on how any given game tracks those stats. For example, it might not function at all, or it may mess up crucial game statistics.

## Reset Steam Achievements With Steam Achievement Manager

![screenshot of the steam achievement manager main page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/screenshot_of_steam_achievement_manager_main_page.jpg)

 The above method is as close to an 'official' method as you can get. If you're after something a little easier, but also a little less 'legitimate,' consider the Steam Achievement Manager.

[Learning how to use the Steam Achievement Manager](https://www.makeuseof.com/how-to-use-steam-achievement-manager/) makes this process much easier, with a GUI to ensure you're resetting the right achievements. However, this method falls into a gray area of Steam's terms of service. It's easier, but it's not guaranteed to be a completely safe method.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139108/17108" target="_top" id="2139108">
  <img src="//a.impactradius-go.com/display-ad/17108-2139108" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139108/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## A Complicated Process

 Ideally, there would be an easier way to reset achievements for any Steam game, as you never know when you'll want to replay a game from the ground up.

 At least we have the option with the Steam Client Console.

 Thankfully, Steam has a catch-all solution to resetting achievements for individual games.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/addressing-frozen-ctrl-key-functionality-in-windows-11-pcs/"><u>Addressing Frozen CTRL Key Functionality in Windows 11 PCs</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/bridging-video-and-gif-a-practical-path-from-vimeo-to-animation/"><u>Bridging Video and GIF A Practical Path From Vimeo to Animation</u></a></li>
<li><a href="https://win11.techidaily.com/constructing-an-audio-experience-beyond-boundaries-in-windows-11/"><u>Constructing an Audio Experience Beyond Boundaries in Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/cut-the-haze-sharpen-your-photos-with-topeditstools/"><u>Cut the Haze, Sharpen Your Photos with #TopEditsTools</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-installation-of-asus-touchpad-drivers-on-windows-10-devices/"><u>Easy Installation of ASUS Touchpad Drivers on Windows 10 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/quick-access-diskspace-tools-for-windows-context-menu/"><u>Quick Access DiskSpace: Tools for Window's Context Menu</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/silent-blades-and-righteous-honor-your-next-game-adventure-awaits-in-2024/"><u>Silent Blades & Righteous Honor Your Next Game Adventure Awaits, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steering-the-path-of-your-onedrive-file-space-in-windows/"><u>Steering the Path of Your OneDrive File Space in Windows</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unveiling-the-capabilities-comprehensive-review-of-the-dji-phantom-4-pro-version-20/"><u>Unveiling the Capabilities: Comprehensive Review of the DJI Phantom 4 Pro Version 2.0</u></a></li>
</ul></div>

