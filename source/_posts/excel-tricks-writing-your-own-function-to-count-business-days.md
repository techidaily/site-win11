---
title: "Excel Tricks: Writing Your Own Function to Count Business Days"
date: 2024-12-30T20:00:14.786Z
updated: 2025-01-06T17:13:58.640Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/029ba41f4072a625a12663e242fe0241f864e3cc7e4fb5de060add9d7faf8df5.jpg
---

## Excel Tricks: Writing Your Own Function to Count Business Days

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [Find the Workdays Between Two Dates in Excel](https://tech-recovery.techidaily.com/troubleshooting-the-pc-reset-failed-message-on-windows/)

 With Microsoft Excel's 

        `NETWORKDAYS`
    
 function, you can [count the number of workdays](https://youtube-web.techidaily.com/ed-2024-approved-ultimate-guide-to-the-best-10-video-saving-devices/) that fall between two specified dates. This function excludes Saturdays, Sundays, and optionally the specified holidays. We'll show you how to use it.

 This function can account for holidays in its calculation, but you must specify those holidays in a column, so be ready with a list of your holiday dates. Also, it's important you keep in mind that this function counts both the starting date and the ending [date in the calculation](https://extra-lessons.techidaily.com/kickstart-your-telegram-promotion-journey-tips-for-newbies/).

Related: [Use Excel to Calculate How Many Days Until an Event](https://youtube-web.techidaily.com/ed-2024-approved-ultimate-guide-to-the-best-10-video-saving-devices/) 

##  Find the Workdays Between Two Dates in Excel

 To get the number of workdays that fall between two dates, first, open your spreadsheet with Microsoft Excel.

 In your spreadsheet, click the cell where you want to display the resulting workday number.

![Select a cell to display the NETWORKDAYS result.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/1-select-networkdays-result-cell.png) 

 In the selected cell, type the following function and press Enter. In the function, replace `B2` with the cell that contains the starting date and `C2` with the cell containing the ending date.

=NETWORKDAYS(B2,C2)

![Type the NETWORKDAYS function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/2-enter-networkdays-function.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Excel will calculate the number of workdays between your dates and display the result in the selected cell. Note that this number includes both the starting date and the ending date.

![The result of the NETWORKDAYS function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/3-excel-networkdays-function-result.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you'd like to exclude any holidays from your calculation, then first, specify your holidays in a column. Like so:

![Enter the holidays in a column.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/4-specify-holidays.png) 

 Click the cell where you want to get the result, type the following function, and press Enter. In this function, replace `B2` with the cell that contains the starting date, `C2` with the cell that contains the ending date, and `E2:E6` with the range where you've specified your holidays.

=NETWORKDAYS(B2,C2,E2:E6)

![Use NETWORKDAYS with holidays.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/5-networkdays-with-holidays.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Excel will display the result in your selected cell. Note that this count excludes your specified holidays but includes the starting and the ending date.

![NETWORKDAYS' result with holidays.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/6-networkdays-with-holidays-result.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 And that's how you can use an Excel function to quickly find the number of days someone has worked between any two dates. Very useful!

---

 Do you want to [find the number of full days between two dates in Excel](https://some-approaches.techidaily.com/new-top-10-hidden-gems-for-enhancing-canva-images/)? If so, there's a quick way to do that.

Related: [How to Find the Number of Days Between Two Dates in Microsoft Excel](https://some-approaches.techidaily.com/new-top-10-hidden-gems-for-enhancing-canva-images/)

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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-top-6-hdmi-21-monitor/"><u>[New] 2024 Approved Top 6 HDMI 2.1 Monitor</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-a-step-by-step-guide-through-youtubes-aspect-ratio-landscapes/"><u>[Updated] A Step-by-Step Guide Through YouTube's Aspect Ratio Landscapes</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/effortlessly-convert-avi-videos-to-wav-audio-on-the-web-for-free-try-movavis-expert-service-now/"><u>Effortlessly Convert AVI Videos to WAV Audio on the Web for Free - Try Movavi's Expert Service Now!</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210133190-9781644112939-forgotten-civilization-2nd-ed/"><u>Forgotten Civilization (2nd ed.) | Free Book</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/your-digital-life-streamlined-blocking-youtube-channels-smartly-for-2024/"><u>Keep Your Digital Life Streamlined Blocking Youtube Channels Smartly for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/lenovos-eclipse-how-to-banish-the-shadow/"><u>Lenovo's Eclipse: How to Banish the Shadow</u></a></li>
<li><a href="https://win11.techidaily.com/shield-windows-from-nonstop-updates/"><u>Shield Windows From Nonstop Updates</u></a></li>
<li><a href="https://win11.techidaily.com/stepwise-customization-how-to-innovate-with-pattern-locks-on-pc/"><u>Stepwise Customization: How to Innovate with Pattern Locks on PC</u></a></li>
<li><a href="https://fox-info.techidaily.com/strategy-envelope-market-success-inside-out-for-2024/"><u>Strategy Envelope Market Success Inside Out for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-addressing-upgrade-issues-windows-11s-0x80246007/"><u>Swiftly Addressing Upgrade Issues: Windows 11'S 0X80246007</u></a></li>
<li><a href="https://win11.techidaily.com/text-tweaking-mastery-in-the-latest-win-11s-snip-app/"><u>Text Tweaking Mastery in the Latest Win 11'S Snip App</u></a></li>
<li><a href="https://win-answers.techidaily.com/ultimate-troubleshooting-tips-if-witcher-3-doesnt-start-up-correctly/"><u>Ultimate Troubleshooting Tips If 'Witcher 3' Doesn't Start Up Correctly</u></a></li>
<li><a href="https://win11.techidaily.com/windows-activation-key-pitfalls-a-closer-look-at-risks/"><u>Windows Activation Key Pitfalls: A Closer Look at Risks</u></a></li>
</ul></div>

