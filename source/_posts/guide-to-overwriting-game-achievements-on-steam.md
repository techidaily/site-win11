---
title: Guide to Overwriting Game Achievements on Steam
date: 2024-09-28T20:05:56.961Z
updated: 2024-10-04T06:04:08.060Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide to Overwriting Game Achievements on Steam
excerpt: This Article Describes Guide to Overwriting Game Achievements on Steam
keywords: Steam Achievement Guide,Game Overwrite Tips,Steam Play Enhancements,Cheat Devices for Games,Save & Resume Glitches,Unlocking Gaming Features,Bypass In-Game Limits
thumbnail: https://thmb.techidaily.com/04c62b2f290b2c5f1899e5598ab465be77832cb08688d450e39f1038f772602c.png
---

## Guide to Overwriting Game Achievements on Steam

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
<a href="https://appsumo.8odi.net/c/5597632/2151883/7443" target="_top" id="2151883">
  <img src="//a.impactradius-go.com/display-ad/7443-2151883" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151883/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Achievements and Stat Commands

![screenshot of achievement clear in steam client console](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/screenshot_of_achievement_clear_in_steam_client_console.jpg)

 The command we'll need to use is **achievement\_clear**. On its own, it doesn't do anything. We need a couple of things first.

 Head over to [**SteamDB**, or the Steam Database](https://steamdb.info/apps/), and search for the game associated with the achievement you're resetting.

![screenshot of half life 2 in steam database](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/screenshot_of_hl2_in_steam_db.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135416/19272" target="_top" id="2135416">
  <img src="//a.impactradius-go.com/display-ad/19272-2135416" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135416/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Copy the **AppID** listed against your game. Note this down or paste it somewhere you'll remember. Scroll down the page and click on the **Achievements** tab.

![screenshot of half life 2 achievements in steam database](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/screenshot_of_hl2_achievements_in_steam_db.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148771/18498" target="_top" id="2148771">
  <img src="//a.impactradius-go.com/display-ad/18498-2148771" border="0" alt="https://techidaily.com" width="350" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148771/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This will list all the achievements and their **API Names**. Pick out the achievement you want to reset and note that name.

 Now you have your command. Input the information you've gathered like so.

`achievement_clear <AppID> <Achievement API Name>`

 Using the example in our screenshots, the code should look something like this. Remember to use the achievement name from SteamDB, and not simply the in-game name of the achievement.

![screenshot of the steam client console with an input command filled out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/screenshot_of_resetting_achievement_steam_client_console_filled_out.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037319/7443" target="_top" id="2037319">
  <img src="//a.impactradius-go.com/display-ad/7443-2037319" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037319/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You'll know it worked if you see the message **achievement\_clear success**.

 There is a second command that accompanies the above. Inputting **reset\_all\_stats** followed by an AppID will reset any stats Steam tracks for that game. For example, kills or time played. Be careful with this command, as it can behave differently depending on how any given game tracks those stats. For example, it might not function at all, or it may mess up crucial game statistics.

## Reset Steam Achievements With Steam Achievement Manager

![screenshot of the steam achievement manager main page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/screenshot_of_steam_achievement_manager_main_page.jpg)

 The above method is as close to an 'official' method as you can get. If you're after something a little easier, but also a little less 'legitimate,' consider the Steam Achievement Manager.

[Learning how to use the Steam Achievement Manager](https://www.makeuseof.com/how-to-use-steam-achievement-manager/) makes this process much easier, with a GUI to ensure you're resetting the right achievements. However, this method falls into a gray area of Steam's terms of service. It's easier, but it's not guaranteed to be a completely safe method.

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
<li><a href="https://fox-links.techidaily.com/2024-approved-periscope-techniques-for-effective-livestreams/"><u>2024 Approved Periscope Techniques for Effective Livestreams</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/assassins-creed-valhalla-review-an-epic-viking-adventure-across-the-medieval-world/"><u>Assassin's Creed: Valhalla Review: An Epic Viking Adventure Across the Medieval World</u></a></li>
<li><a href="https://win11.techidaily.com/dazzling-display-holiday-themed-window-wonders/"><u>Dazzling Display: Holiday Themed Window Wonders</u></a></li>
<li><a href="https://sound-issues.techidaily.com/diy-repair-getting-your-realtek-mic-to-work-again-a-step-by-step-guide/"><u>DIY Repair: Getting Your Realtek Mic to Work Again - A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-explorer-to-show-disk-space/"><u>Enhancing Windows Explorer to Show Disk Space</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-oppo-reno-11f-5g-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost Oppo Reno 11F 5G Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/instructions-to-prevent-unwanted-touchpad-input-in-windows-10-with-an-attached-mouse-device/"><u>Instructions to Prevent Unwanted Touchpad Input in Windows 10 with an Attached Mouse Device</u></a></li>
<li><a href="https://video-capture.techidaily.com/legal-aspects-and-ethical-considerations-of-recording-whatsapp-for-2024/"><u>Legal Aspects and Ethical Considerations of Recording WhatsApp for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/relaunching-file-explorer-a-step-bystep-guide/"><u>Relaunching File Explorer: A Step-Bystep Guide</u></a></li>
<li><a href="https://win-solutions.techidaily.com/solving-frame-rate-issues-in-rainbow-six-extraction-a-step-by-step-guide/"><u>Solving Frame Rate Issues in Rainbow Six Extraction: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-solution-matching-internet-on-mobile-and-desktop/"><u>Speedy Solution: Matching Internet on Mobile & Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/subtle-system-tweaks-windows-toolbars-unseen/"><u>Subtle System Tweaks: Windows Toolbars Unseen</u></a></li>
<li><a href="https://win11.techidaily.com/the-quest-to-resolve-skies-sse-woes/"><u>The Quest to Resolve Skies' SSE Woes</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-win-error-31-in-network-connections/"><u>Troubleshooting WIN Error 31 in Network Connections</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-your-pc-strategies-to-exit-s-mode/"><u>Unlocking Your PC: Strategies to Exit S Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/velocity-validation-precise-windows-steps-to-assess-internet-router-performance/"><u>Velocity Validation: Precise Windows Steps to Assess Internet Router Performance</u></a></li>
<li><a href="https://techidaily.com/xiaomi-redmi-a2-messages-recovery-recover-deleted-messages-from-xiaomi-redmi-a2-by-fonelab-android-recover-messages/"><u>Xiaomi Redmi A2 Messages Recovery - Recover Deleted Messages from Xiaomi Redmi A2</u></a></li>
</ul></div>

