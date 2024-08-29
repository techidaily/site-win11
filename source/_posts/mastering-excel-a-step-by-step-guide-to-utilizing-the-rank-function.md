---
title: "Mastering Excel: A Step-by-Step Guide to Utilizing the RANK Function"
date: 2024-08-28T00:47:58.371Z
updated: 2024-08-29T00:47:58.371Z
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

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
 Your table now clearly tells you where each value ranks within your set of data. For tidiness, you can [rename your worksheet](https://sim-unlock.techidaily.com/network-locked-sim-card-inserted-on-your-xiaomi-14-ultra-phone-unlock-it-now-by-drfone-android/) "Totals".

 If you want to make your rankings even clearer so that you can review the rankings at a quick glance, [apply conditional formatting to your table](https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-tecno-spark-10-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
###  What are RANK.EQ and RANK.AVG?

 RANK.EQ tells Excel to rank all equal values together, while RANK.AVG tells Excel to average the ranking for all equal values. They both follow exactly the same syntax and processes as RANK in Excel.

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
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
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
 This now tells us that Regina is the highest-ranked employee. Use Excel's AutoFill function to complete the rest of the employees' names.

![Excel sheet showing the 'Employee' column filled in based on their rank, using VLOOKUP and AutoFill.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/league-all-results-1.png) 

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
 Now that we can see the employees in order based on their total sales from the Totals sheet, we can add their total sales using VLOOKUP in the same way.

 This would be the formula we place in cell C3:

=VLOOKUP(A3,Totals!$A$3:$I$9,9,FALSE)

 Notice that this time, we have input "9" as the penultimate part of our formula, as we want Excel to capture the total sales from the ninth column in our Totals table.

![Excel sheet showing the result of using VLOOKUP to find the highest-ranked employee's total sales.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/league-first-result-column-2-2.png) 

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
 Complete the table by using AutoFill down column C.

![Excel sheet showing the completed league table.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/league-all-results-2.png) 

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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-detailed-analysis-and-overview-of-du-recorders-capabilities/"><u>[New] 2024 Approved  Detailed Analysis and Overview of Du Recorder’s Capabilities</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-creating-accessibility-your-guide-to-an-intuitive-youtube-signup-for-2024/"><u>[New] Creating Accessibility  Your Guide to an Intuitive YouTube Signup for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-unlink-from-youtube-shorts-follow-this-plan/"><u>[Updated] 2024 Approved  Unlink From YouTube Shorts - Follow This Plan</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-decoding-video-thread-embellishments-for-2024/"><u>[Updated] Decoding Video Thread Embellishments for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-from-clicks-to-cash-the-systematic-triple-pathway-for-youtube-revenue-tracking/"><u>[Updated] From Clicks to Cash  The Systematic Triple Pathway for YouTube Revenue Tracking</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-step-into-the-archive-old-stories-on-facebook/"><u>[Updated] In 2024, Step Into the Archive  Old Stories on Facebook</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-mastering-youtube-views-secrets-for-a-million-followers/"><u>[Updated] Mastering Youtube Views  Secrets for a Million Followers</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-cloud-storage-expenses-made-simple-comparison-guide/"><u>2024 Approved  Cloud Storage Expenses Made Simple  Comparison Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-elite-crews-essential-sierra-video-editors/"><u>2024 Approved  Elite Crews  Essential Sierra Video Editors</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-what-makes-vimeo-special-a-look-inside/"><u>2024 Approved  What Makes Vimeo Special? A Look Inside</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-nokia-105-classic-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On Nokia 105 Classic | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/7-online-tools-to-improve-your-prompt-engineering-skills/"><u>7 Online Tools to Improve Your Prompt Engineering Skills</u></a></li>
<li><a href="https://fake-location.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-samsung-galaxy-s24-ultra-drfone-by-drfone-virtual-android/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Samsung Galaxy S24 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/conquer-windows-10-blues-a-fix-it-manual/"><u>Conquer Windows 10 Blues: A Fix-It Manual</u></a></li>
<li><a href="https://win11.techidaily.com/creating-unique-keys-for-winapps-and-tools/"><u>Creating Unique Keys for WinApps and Tools</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-through-frozen-windows-update-snags-quickly/"><u>Cutting Through Frozen Windows Update Snags Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-and-repairing-windows-11-wireless-network-failure/"><u>Diagnosing and Repairing Windows 11 Wireless Network Failure</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-top-9-techniques-for-tweaking-sounds-on-windows-11/"><u>Discover the Top 9 Techniques for Tweaking Sounds on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/dismantling-store-obstruction-error-code-0x80073cf3/"><u>Dismantling Store Obstruction: Error Code 0X80073CF3</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-sound-levels-for-disconnected-wirespeakers/"><u>Enhancing Sound Levels for Disconnected Wirespeakers</u></a></li>
<li><a href="https://techtrends.techidaily.com/exclusive-info-alert-discover-psvr2-release-timeline-pricing-structure-and-advanced-hardware-details/"><u>Exclusive Info Alert: Discover PSVR2 Release Timeline, Pricing Structure and Advanced Hardware Details</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-error-code-0x0000004e-breakdown/"><u>Fixing Windows Error Code: 0X0000004E Breakdown</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-oppo-f23-5g-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From Oppo F23 5G to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-oppo-reno-10-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Oppo Reno 10 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/jest-jacket-picture-fabricator/"><u>Jest Jacket  Picture Fabricator</u></a></li>
<li><a href="https://extra-skills.techidaily.com/m1-dominance-video-editors-rejoice-in-seamless-experience-for-2024/"><u>M1 Dominance  Video Editors Rejoice in Seamless Experience for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/making-headway-with-windows-mail-error-x-0x80072746/"><u>Making Headway with Windows Mail Error X: 0X80072746</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-workspace-customizing-w11-settings/"><u>Master Your Workspace: Customizing W11 Settings</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-projector-screens-without-pin-in-win11/"><u>Mastering Projector Screens Without PIN in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-secure-passcodes-longer-windows-11-and-11-pins/"><u>Mastering Secure Passcodes: Longer Windows 11 and 11 PINs</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-steam-pace-boosting-windows-download-efficiency/"><u>Mastering Steam Pace: Boosting Windows Download Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-past-blue-screen-errors-in-windows-10/"><u>Navigate Past Blue Screen Errors in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/new-era-of-connectivity-windows-for-iphones-ipads-and-pcs-just-dropped/"><u>New Era of Connectivity: Windows for iPhones, iPads and PCs Just Dropped!</u></a></li>
<li><a href="https://extra-information.techidaily.com/optimize-media-consumption-with-picture-in-progress-screen-chrome/"><u>Optimize Media Consumption with Picture In Progress Screen Chrome</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-missing-entry-on-windows-system/"><u>Overcoming Missing Entry on Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-challenge-of-invalid-onedrive-tags/"><u>Overcoming the Challenge of Invalid OneDrive Tags</u></a></li>
<li><a href="https://extra-support.techidaily.com/powerdirector-pro-detailed-reviews-and-step-by-step-guides-for-2024/"><u>PowerDirector Pro  Detailed Reviews and Step-by-Step Guides for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/proven-winning-techniques-for-ps1-gameplay-a-detailed-windows-and-duckstation-manual/"><u>Proven Winning Techniques for PS1 Gameplay: A Detailed Windows and Duckstation Manual</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-windows-still-requires-password-faults/"><u>Quick Fixes for “Windows Still Requires Password” Faults</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-for-overcoming-error-8007000e-in-windows-updates/"><u>Quick Solutions for Overcoming Error 8007000E in Windows Updates</u></a></li>
<li><a href="https://win11.techidaily.com/reactivating-regular-launch-procedure-in-outlook-despite-safe-mode-lockdown/"><u>Reactivating Regular Launch Procedure in Outlook Despite Safe Mode Lockdown</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-windows-update-error-code-0x8024800c/"><u>Rectifying Windows Update: Error Code 0X8024800C</u></a></li>
<li><a href="https://win11.techidaily.com/reliable-solutions-to-end-file-explorer-crashes-in-win11/"><u>Reliable Solutions to End File Explorer Crashes in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-missing-directory-indicators/"><u>Reversing Missing Directory Indicators</u></a></li>
<li><a href="https://win11.techidaily.com/simplified-steps-to-access-windows-11s-printer-features-max-48-chars/"><u>Simplified Steps to Access Windows 11’S Printer Features (Max 48 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-for-adjacent-and-non-adjacent-windows-partition-merging/"><u>Step-by-Step Guide for Adjacent and Non-Adjacent Windows Partition Merging</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-secure-sticky-notes-on-modern-oses/"><u>Steps to Secure Sticky Notes on Modern OSes</u></a></li>
<li><a href="https://extra-information.techidaily.com/syncing-soundscapes-to-pixelated-portraits/"><u>Syncing Soundscapes to Pixelated Portraits</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-guide-to-combining-folders-and-files-in-win-11/"><u>The Essential Guide to Combining Folders & Files in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-farewell-of-windows-features-whats-gone/"><u>The Farewell of Windows Features: What's Gone?</u></a></li>
<li><a href="https://win11.techidaily.com/the-innovations-that-define-ai-pcs-and-beyond/"><u>The Innovations That Define AI PCs and Beyond</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-strategy-for-combining-multiple-fortnite-accounts/"><u>The Ultimate Strategy for Combining Multiple Fortnite Accounts</u></a></li>
<li><a href="https://win11.techidaily.com/turbocharging-your-pcs-download-speed-with-steam/"><u>Turbocharging Your PC's Download Speed with Steam</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-driver-verifier-within-win11-control-panel/"><u>Unveiling Driver Verifier Within Win11 Control Panel</u></a></li>
</ul></div>
