---
title: "Mastering Excel: A Step-by-Step Guide to Utilizing the RANK Function"
date: 2025-01-03T20:24:28.000Z
updated: 2025-01-06T17:20:49.838Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/8acaf4a476033f54e704f652076d0feb19e147f8c9f9e89ae440088035de6366.jpg
---

## Mastering Excel: A Step-by-Step Guide to Utilizing the RANK Function

### Quick Links

* [How to Use Excel's RANK Function](https://easy-unlock-android.techidaily.com/full-tutorial-to-bypass-your-realme-narzo-60-5g-face-lock-by-drfone-android/)
* [How to Use VLOOKUP in Excel to Create a League Table](https://snapchat-videos.techidaily.com/updated-2024-approved-quick-voice-fixes-for-your-snapchat-snaps-using-dual-methods/)

### Key Takeaways

* Excel's RANK function is useful for ranking data and can be used in various situations.
* By combining the RANK function with VLOOKUP, you can create a league table.

 Excel's RANK function tells you a statistical rank of a value within a set of data. This has a range of practical uses—teachers ranking their students, sports coaches ranking their players, and a whole host of other situations where you would want to rank data. Here's how to use it. 

##  How to Use Excel's RANK Function

 When you use RANK, it will return a digit that tells you where the cell you're referencing ranks within the chosen series of data. To do this, use the following formula:

=RANK(A,B:C,D)

 where A is the cell reference for the value you want to rank, B:C is the range of cells containing the data against which you are ranking value A, and D is either "0" for a descending ranking or "1" for an ascending ranking. Let's look into this in more detail.

 In this example, we have a list of employees and their sales data for the first six months of the year.

![Excel sheet with a table showing seven employees, their sales for each of the first six months, and their total sales.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/table-without-ranking.png) 

 We can use the RANK function to—you guessed it—rank the employees based on their total sales. To do this, we need to create a ranking column in our existing table. If you want to later create a league table for the ranking, it's important to place the rank at the start of your data, so the ranking column needs to be in column A. To do this, right click on the column "A" header (the part that says "A", "B", "C", etc.) and click "Insert".

![Excel sheet showing the 'Insert' option by right-clicking on the header of column A.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/insert-column-a.png) 

 You will then see a new, blank column appear at the left-hand side of your table. Format this column as you wish and name the column "Rank".

![Excel sheet showing the new column at the left-hand side of the table, renamed 'Rank'.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/extra-column-added.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 We're now ready to begin our RANK formula.

 Click on the first empty cell in your ranking column (in this case, A3), and type:

=RANK(

 Now, click or type the cell reference of the number you want to rank (in our case, it's I3), and add a comma:

=RANK(I3,

 You now need to reference all the data you want to include in your ranking [using an absolute reference](https://some-approaches.techidaily.com/in-2024-unveiling-3dr-a-personal-perspective-on-printing-alone/), followed by a comma. In our case, that's all the data from cells I3 to I9:

 If you don't use an absolute reference here, when you complete the remaining ranks for the other employees using AutoFill, the formulas will be incorrect.

=RANK(I3,$I$3:$I$9,

 Next, type "0" if you want your data to rank in descending order (that is, the highest value will be ranked first), or "1" if you want your data to rank in ascending order (with the lowest value ranked first). In our case, we want the highest value to rank first, so we will type "0", and then close the parentheses and press Enter:

=RANK(I3,$I$3:$I$9,0)

![Excel sheet showing the result of using the RANK function for the first total.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/rank-first-result.png) 

 This now tells us that Ken's total sales figure ranks third overall. Finally, [use Excel's AutoFill function](https://visual-screen-recording.techidaily.com/new-in-2024-top-5-best-hdmi-21-gaming-monitors-ps5-compatible/) to find the rankings for the remaining data in your table.

![Excel sheet with the 'Rank' column completed.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/rank-all-results.png) 

 Your table now clearly tells you where each value ranks within your set of data. For tidiness, you can [rename your worksheet](https://sim-unlock.techidaily.com/network-locked-sim-card-inserted-on-your-xiaomi-14-ultra-phone-unlock-it-now-by-drfone-android/) "Totals".

 If you want to make your rankings even clearer so that you can review the rankings at a quick glance, [apply conditional formatting to your table](https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-tecno-spark-10-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RvR5PNhspKE?si=uJcMYK9v-_Xq7fAg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

###  What are RANK.EQ and RANK.AVG?

 RANK.EQ tells Excel to rank all equal values together, while RANK.AVG tells Excel to average the ranking for all equal values. They both follow exactly the same syntax and processes as RANK in Excel.

##  How to Use VLOOKUP in Excel to Create a League Table

 Assuming you have already created the rankings using the method above, you can now reorder the data to produce a league table.

 First, create a new sheet in your Excel workbook by clicking the "+" symbol located to the right of your tab names at the bottom of your workbook, and rename it "LeagueTable".

 In your LeagueTable sheet, create the outline for your league table, including manually inputting the rankings into column A. In our example from the section above, we know we have seven employees to include in our league table, so we've typed the numbers one to seven.

![Excel sheet showing the layout for what will be the league table, with the rank numbers manually added to column A.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/league-blank.png) 

 We're now ready to create the league table. The first data we want to include from our Totals sheet is the name of the employee who is ranked first. To do this, we need to [use Excel's VLOOKUP function](https://extra-tips.techidaily.com/integrate-sound-and-sight-web-studio/). In cell B3, type

=VLOOKUP(

 The VLOOKUP function tells Excel that you're going to grab data from another source. In this case, we're sourcing data from the Totals sheet in our workbook.

 Next, we want to find the employee who ranks first overall, so we must reference the cell that contains the ranking "1" in our league table (in our case, that's cell A3), followed by a comma:

=VLOOKUP(A3,

 We now need to tell Excel what else it needs to consider within its VLOOKUP calculation. In this case, we want to tell it to consider all the data in the Totals table we have already created. With your cursor still blinking in the cell where you are typing the formula, go back to your Totals sheet and highlight the whole table. This will update your formula as follows:

=VLOOKUP(A3,Totals!A3:I9

 Each time we apply this formula, we want the same cells in the Totals sheet to be referenced, so [turn this reference into an absolute reference](https://visual-screen-recording.techidaily.com/in-2024-capturing-clarity-a-look-at-screensnapelite/), and then add a comma:

=VLOOKUP(A3,Totals!$A$3:$I$9,

 The penultimate part of this formula is to tell Excel where to look to find the detail we want to insert into the cell we're typing in. In this example, we want to see the name of the person who ranks first.

 In our Totals table, there are nine columns overall, and the names of the employees are in the second column of that table, so we type the number two, followed by a final comma:

=VLOOKUP(A3,Totals!$A$3:$I$9,2

 And finally, type "FALSE" to tell Excel to find an exact match, before closing your parentheses and pressing Enter:

=VLOOKUP(A3,Totals!$A$3:$I$9,2,FALSE)

![Excel sheet showing the result of using VLOOKUP to find the highest-ranked employee.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/league-first-result.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This now tells us that Regina is the highest-ranked employee. Use Excel's AutoFill function to complete the rest of the employees' names.

![Excel sheet showing the 'Employee' column filled in based on their rank, using VLOOKUP and AutoFill.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/league-all-results-1.png) 

 Now that we can see the employees in order based on their total sales from the Totals sheet, we can add their total sales using VLOOKUP in the same way.

 This would be the formula we place in cell C3:

=VLOOKUP(A3,Totals!$A$3:$I$9,9,FALSE)

 Notice that this time, we have input "9" as the penultimate part of our formula, as we want Excel to capture the total sales from the ninth column in our Totals table.

![Excel sheet showing the result of using VLOOKUP to find the highest-ranked employee's total sales.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/league-first-result-column-2-2.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Complete the table by using AutoFill down column C.

![Excel sheet showing the completed league table.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/league-all-results-2.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Instead of manually typing the VLOOKUP formula in any subsequent columns after you have completed column B, you could initially [use a mixed reference](https://screen-mirror.techidaily.com/how-realme-note-50-mirror-screen-to-pc-drfone-by-drfone-android/) with column A locked within your VLOOKUP formula, and then AutoFill to the right.

 If you were to change the data in your Totals sheet, the league table would automatically update to reflect the changes.

---

 That's it! You now have all the tools you need to use the RANK function in Excel, and combine this with VLOOKUP to create a league table. If you do indeed choose to add the league table to your workbook, after you have done this, you can tidy up your original Totals sheet by [hiding the column](https://fox-hovers.techidaily.com/the-complete-user-manual-to-facetunes-photo-fixes-for-2024/) containing the rankings.

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
<li><a href="https://some-knowledge.techidaily.com/new-identifying-premium-free-online-tools-for-efficient-srt-translations/"><u>[New] Identifying Premium Free Online Tools for Efficient SRT Translations</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-insiders-manual-reacting-on-twitter-videos/"><u>[New] In 2024, Insider’s Manual Reacting on Twitter Videos</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/he-spys-guide-to-unearthing-hidden-youtube-videos-for-2024/"><u>[New] The Spy's Guide to Unearthing Hidden YouTube Videos for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-unlock-your-pcs-potential-exciting-new-windows-10-games/"><u>[New] Unlock Your PC’s Potential Exciting New Windows 10 Games</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-a-complete-list-of-creative-and-catchy-youtube-channel-titles-for-modern-blogging-maximum-length-156-characters-for-2024/"><u>[Updated] A Complete List of Creative and Catchy YouTube Channel Titles for Modern Blogging (Maximum Length 156 Characters) for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-highlighted-viewer-insights-unveiled/"><u>[Updated] In 2024, Highlighted Viewer Insights Unveiled</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-best-deals-on-superior-asmr-microphone-technology/"><u>2024 Approved Best Deals on Superior ASMR Microphone Technology</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fixing-the-wacom-device-driver-not-installed-problem-in-windows-11-environments/"><u>Fixing the 'Wacom Device Driver Not Installed' Problem in Windows 11 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-transforming-your-blu-ray-collection-into-high-quality-mkv-files/"><u>Step-by-Step Guide: Transforming Your Blu-Ray Collection Into High-Quality MKV Files</u></a></li>
<li><a href="https://win11.techidaily.com/successful-strategies-for-streaming-your-dvd-collection-with-apple-tv/"><u>Successful Strategies for Streaming Your DVD Collection with Apple TV</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/tailoring-snaps-the-science-behind-compelling-advertising/"><u>Tailoring Snaps The Science Behind Compelling Advertising</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-freebies-for-streamlining-webm-video-files-speedy-easy-techniques-for-online-reduction/"><u>Top 5 Freebies for Streamlining WebM Video Files - Speedy, Easy Techniques for Online Reduction</u></a></li>
<li><a href="https://win11.techidaily.com/top-ranking-avcision-ultimate-guide-to-convert-dvds-to-avis-on-windows-10-and-11/"><u>Top-Ranking AVCision: Ultimate Guide to Convert DVDs to AVIs on Windows 10 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-asfmp4-conversion-tools-speeding-up-file-format-switching-with-best-practices/"><u>Ultimate ASF/MP4 Conversion Tools: Speeding Up File Format Switching with Best Practices</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-techniques-for-securely-acquiring-1440p-video-streams-from-youtube/"><u>Ultimate Techniques for Securely Acquiring 1440P Video Streams From YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/watch-on-the-go-how-to-effortlessly-save-movies-tv-episodes-and-songs-for-offline-enjoyment/"><u>Watch On the Go: How to Effortlessly Save Movies, TV Episodes & Songs for Offline Enjoyment</u></a></li>
</ul></div>

