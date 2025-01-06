---
title: The Definitive Walkthrough on Systematically Assessing Formulas in MS Excel
date: 2025-01-04T20:46:21.970Z
updated: 2025-01-06T16:22:29.705Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/09/microsoft_excel_hero_1200x675.jpg
---

## The Definitive Walkthrough on Systematically Assessing Formulas in MS Excel

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [Use the Evaluate Formula Tool in Excel](https://youtube-videos.techidaily.com/epic-audio-essentials-top-10-for-trending-yt-shorts-for-2024/)

 If you're collaborating on a spreadsheet, you may want to break down a formula someone entered. While many times this easy, there are others where the formula is more complicated. Excel provides a tool to evaluate formulas step-by-step.

 For nested or lengthy formulas, you can see how they work one step at a time from the inside out. This not only helps you to [understand the formula](https://youtube-docs.techidaily.com/n-2024-automate-playlist-retrieval-from-youtube-directly/) and its arguments but can also assist you in troubleshooting formula errors.

 As of May 2022, the feature is available on Windows with Excel for Microsoft 365, Excel 2019, Excel 2016, Excel 2013, Excel 2010, and Excel 2007.

##  Use the Evaluate Formula Tool in Excel

 Open your Excel sheet and select the cell containing the formula you want to evaluate. Go to the Formulas tab and choose "Evaluate Formula" in the Formula Auditing section of the ribbon.

![Evaluate Formula on the Formulas tab](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/FormulasEvaluate-ExcelEvaluateFormulas.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1KKovVi9epE?si=EF7KA7b4KsEpWA-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You'll see your formula placed in the center box. Click "Evaluate" to begin. The tool evaluates the formula from the inside out, so you'll first notice it explaining the underlined portion.

 Let's walk through our nested formula example: 

        `=IF(SUM(A1:A5)>20,AVERAGE(A1:A5),"No")`
    
 . This formula says, if the sum of cells A1 through A5 is greater than 20, [average the cells](https://win-able.techidaily.com/fixing-overwatch-startup-issues-how-to-get-rid-of-the-persistent-black-screen/) in A1 through A5, otherwise, display "No."

![Evaluate underlined portion](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/StartEvaluate-ExcelEvaluateFormulas.png) 

 When you click "Evaluate," the underlined part of the [formula shows the result](https://extra-lessons.techidaily.com/is-inshot-a-game-changer-in-video-editing-tools/). In our formula, it [sums](https://instagram-videos.techidaily.com/updated-steps-to-instagram-verification-and-fan-growth-in-under-150-characters/) the cells A1 through A5 and sees if the result is greater than 20.

![Evaluate next underlined portion](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/EvaluateSumGreaterThan-ExcelEvaluateFormulas.png) 

 Then when you click "Evaluate" again, the next underlined portion is evaluated and shows the result. For us, the result is False because the sum is not greater than 20.

![Underlined portion evaluated and result is False](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/EvaluateNotGreaterThan-ExcelEvaluateFormulas.png) 

 When you reach the end, you'll see the final result that displays in your cell. For our formula this is "No" because the [IF function's formula](https://facebook-video-recording.techidaily.com/updated-2024-approved-integrating-instant-video-playback-within-the-social-media-webspace/) displays the if-not-then result.

![Final evaluation result is the formula result](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/EvaluateNotGreaterThanNo-ExcelEvaluateFormulas.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GU08CQVsZz0?si=V-SvPfzRsQysMS0e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can then select "Restart" to see the step-by-step evaluation again or "Close" to exit the tool.

 Let's look at another example where you can use the Step In and Step Out features of the tool. For this we'll use a basic [IF function](https://extra-skills.techidaily.com/in-2024-spark-engagement-the-ultimate-list-of-video-text-effects/) formula rather than a nested formula: 

        `=IF(A1=5,"Yes","No")`
    
 . This says, if the value in cell A1 equals 5, display "Yes," otherwise, display "No."

 Here we see our formula with the underlined portion and the Step In button available.

![Evaluate with Step In available](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/EvaluateStepIn-ExcelEvaluateFormulas.png) 

 Click that button to display the constant for the formula. It will appear in its own box. You can see here it's 1 because that's the value in cell A1.

![Step In value displays](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/EvaluateStepOut-ExcelEvaluateFormulas.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can then click "Step Out" to close that box and continue with "Evaluate" to work through the formula. The next step evaluates if 1 is equal to 5, per our formula.

![Evaluate equal to result](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/EvaluateEqualTo-ExcelEvaluateFormulas.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click "Evaluate" to see that the result is False, 1 is not equal to 5.

![Evaluate equal to result](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/EvaluateNotEqualTo-ExcelEvaluateFormulas.png) 

 Therefore, the formula's result is "No."

![Final evaluation result is the formula result](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/EvaluateNotEqualToNo-ExcelEvaluateFormulas.png) 

 When you see a formula that you're trying to understand, the Evaluate Formula feature in Excel can help. For more, look at [these basic Excel functions](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/).

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
<li><a href="https://youtube-webster.techidaily.com/024-approved-mastering-the-art-of-partial-youtube-extraction/"><u>[New] 2024 Approved Mastering the Art of Partial YouTube Extraction</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/easy-ways-for-mac-enthusiasts-to-get-started-with-whatsapp-messaging/"><u>Easy Ways for Mac Enthusiasts to Get Started with WhatsApp Messaging</u></a></li>
<li><a href="https://solve-lab.techidaily.com/envoyez-une-commande-online-gratuit-achetez-mediatrans-a-prix-reduit/"><u>Envoyez Une Commande Online Gratuit: Achetez MediaTrans À Prix Réduit!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722853495092-exploring-telecom-giants-what-is-a-carrier-responsible-for-in-the-world-of-mobile-connectivity/"><u>Exploring Telecom Giants: What Is a Carrier Responsible for in the World of Mobile Connectivity?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/full-guide-to-catch-100-iv-pokemon-using-a-map-on-tecno-phantom-v-flip-drfone-by-drfone-virtual-android/"><u>Full Guide to Catch 100 IV Pokémon Using a Map On Tecno Phantom V Flip | Dr.fone</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/in-depth-analysis-of-the-stanley-j5c09-powerful-and-spacious/"><u>In-Depth Analysis of the Stanley J5C09: Powerful and Spacious</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-concealing-local-wi-fi-signals/"><u>Mastering Windows: Concealing Local Wi-Fi Signals</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-removing-custom-kodi-modifications-and-restoring-default-settings/"><u>Step-by-Step Guide: Removing Custom Kodi Modifications & Restoring Default Settings</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-setting-up-the-latest-enzo-plugins-on-kodi-leia-and-krypton-for-reliable-live-tv/"><u>Step-by-Step Guide: Setting Up the Latest Enzo Plugins on Kodi (Leia and Krypton) for Reliable Live TV</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-list-of-top-11-youtube-downloaders-latest-version/"><u>The Ultimate List of Top 11 YouTube Downloaders - Latest Version</u></a></li>
<li><a href="https://win11.techidaily.com/top-3-no-cost-solutions-for-seamless-xvid-to-avi-conversion-across-windows-macos-and-web-services/"><u>Top 3 No-Cost Solutions for Seamless Xvid to AVI Conversion Across Windows, MacOS, and Web Services</u></a></li>
<li><a href="https://win11.techidaily.com/top-lossless-audio-compression-tools-how-to-shrink-audio-file-size-without-losing-quality/"><u>Top Lossless Audio Compression Tools: How to Shrink Audio File Size Without Losing Quality</u></a></li>
<li><a href="https://win11.techidaily.com/transform-cloudy-with-a-chance-of-meatballs-2-into-a-lively-food-frenzy-saga/"><u>Transform Cloudy with a Chance of Meatballs 2 Into a Lively Food Frenzy Saga</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-editing-audio-files-in-windows-operating-systems-windows-11-10-81-and-earlier/"><u>Ultimate Guide: Editing Audio Files in Windows Operating Systems (Windows 11, 10, 8.1, and Earlier)</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-the-future-of-music-creation-explore-the-best-iphone-and-android-audio-processing-apps/"><u>Updated In 2024, The Future of Music Creation – Explore the Best iPhone and Android Audio Processing Apps</u></a></li>
</ul></div>

