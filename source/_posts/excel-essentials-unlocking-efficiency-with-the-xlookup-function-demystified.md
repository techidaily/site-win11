---
title: "Excel Essentials: Unlocking Efficiency with the XLOOKUP Function Demystified"
date: 2025-01-01T20:19:29.453Z
updated: 2025-01-06T18:25:46.360Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/4f66184ac0a8648b46c6ad4d0861ce71f7dbc55baf3e5392923e05f30fb00ef3.jpg
---

## Excel Essentials: Unlocking Efficiency with the XLOOKUP Function Demystified

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [What is XLOOKUP?](https://youtube-videos.techidaily.com/best-practices-choosing-youtubes-most-popular-video-formats/)
* [How to Use the XLOOKUP Function](https://remote-screen-capture.techidaily.com/updated-from-playtime-to-production-sims-4-video-capturing/)
* [XLOOKUP can Look to the Left](https://fox-cloud.techidaily.com/new-minds-on-trial-best-general-knowledge-channels/)
* [What to Do If Not Found](https://remote-screen-capture.techidaily.com/updated-screen-capture-without-a-penny-the-top-apps-reviewed-for-2024/)
* [Using XLOOKUP for a Range Lookup](https://article-helps.techidaily.com/in-2024-becoming-an-srt-creation-virtuoso-a-complete-manual/)
* [XLOOKUP Replaces the HLOOKUP Function Too](https://facebook-video-share.techidaily.com/tailoring-video-resolution-and-size-a-must-know-guide-to-youtube-uploads-for-2024/)
* [XLOOKUP Can Look From the Bottom-Up](https://win-amazing.techidaily.com/asus-bluetooth-drivers-quick-downloads-and-easy-update-tutorials/)
* [Round-Up](https://extra-approaches.techidaily.com/new-masterclass-guide-15-tripods-perfect-for-gopro/)

 Excel's new XLOOKUP will replace VLOOKUP, providing a powerful replacement to one of Excel's most popular functions. This new function solves some of VLOOKUP's limitations and has extra functionality. Here's what you need to know.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  What is XLOOKUP?

 The new XLOOKUP function has solutions for some of the biggest limitations of [VLOOKUP](https://extra-tips.techidaily.com/integrate-sound-and-sight-web-studio/). Plus, it also replaces HLOOKUP. For example, XLOOKUP can look to its left, defaults to an exact match, and allows you to specify a range of cells instead of a column number. VLOOKUP is not this easy to use or as versatile. We'll show you how it all works.

 For the moment, XLOOKUP is only available to users on the Insiders program. Anyone can [join the Insiders program](https://insider.office.com/en-us/) to access the newest Excel features as soon as they become available. Microsoft will soon begin to roll it out to all Office 365 users.

##  How to Use the XLOOKUP Function

 Let's dive straight in with an example of XLOOKUP in action. Take the example data below. We want to return the department from column F for each ID in column A.

![Sample data for XLOOKUP example](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/09/exact-match-data.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This is a classic exact match lookup example. The XLOOKUP function requires just three pieces of information.

 The image below shows XLOOKUP with six arguments, but only the first three are necessary for an exact match. So let's focus on them:

* **Lookup\_value:** What you are looking for.
* **Lookup\_array:** Where to look.
* **Return\_array:** the range containing the value to return.

![Information required by the XLOOKUP function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/11/xlookup-arguments.png) 

 The following formula will work for this example:

        `=XLOOKUP(A2,$E$2:$E$8,$F$2:$F$8)`
    
![XLOOKUP for an exact match](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/09/exact-match-complete.png) 

 Let's now explore a couple of advantages XLOOKUP has over VLOOKUP here.

###  No More Column Index Number

 The infamous third argument of VLOOKUP was to specify the column number of the information to return from a table array. This is no longer an issue because XLOOKUP enables you to select the range to return from (column F in this example).

![The column index number argument of VLOOKUP](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/09/vlookup-arguments.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 And don't forget, XLOOKUP can view the data left of the selected cell, unlike VLOOKUP. More on this below.

 You also no longer have the issue of a broken formula when new columns are inserted. If that happened in your spreadsheet, the return range would adjust automatically.

![Inserted column does not break XLOOKUP](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/09/inserted-column.png) 

###  Exact Match is the Default

 It was always confusing when learning VLOOKUP why you had to specify an exact match was wanted.

 Fortunately, XLOOKUP defaults to an exact match---the far more common reason to use a lookup formula). This reduces the need to answer that fifth argument and ensures fewer mistakes by users new to the formula.

 So in short, XLOOKUP asks fewer questions than VLOOKUP, is more user-friendly, and is also more durable.

##  XLOOKUP can Look to the Left

 Being able to select a lookup range makes XLOOKUP more versatile than VLOOKUP. With XLOOKUP, the order of the table columns does not matter.

 VLOOKUP was constrained by searching the left-most column of a table and then returning from a specified number of columns to the right.

 In the example below, we need to lookup an ID (column E) and return the person's name (column D).

![Example data for a lookup formula to the left](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/09/lookup-left-data.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The following formula can achieve this:

        `=XLOOKUP(A2,$E$2:$E$8,$D$2:$D$8)`
    
![XLOOKUP function returning a value to its left](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/09/lookup-left-complete.png) 

##  What to Do If Not Found

 Users of lookup functions are very familiar with the #N/A error message that greets them when their VLOOKUP or their MATCH function cannot find what it needs. And often there is a logical reason for this.

 Therefore, users quickly research how to hide this error because it is not correct or useful. And, of course, there are ways to do so.

 XLOOKUP comes with its own built-in "if not found" argument to handle such errors. Let's see it in action with the previous example, but with a mistyped ID.

 The following formula will display the text "Incorrect ID" instead of the error message: 

        `=XLOOKUP(A2,$E$2:$E$8,$D$2:$D$8,"Incorrect ID")`
    
![Alternative text if not found with XLOOKUP](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/11/if-not-found-1.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Using XLOOKUP for a Range Lookup

 Although not as common as the exact match, a very effective use of a lookup formula is to look for a value in ranges. Take the following example. We want to return the discount dependent upon the amount spent.

 This time we are not looking for a specific value. We need to know where the values in column B fall within the ranges in column E. That will determine the discount earned.

![Table data for a range lookup](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/09/range-lookup-data.png) 

 XLOOKUP has an optional fifth argument (remember, it defaults to the exact match) named match mode.

![Match mode argument for a range lookup](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/11/match-mode-1.png) 

 You can see that XLOOKUP has greater capabilities with approximate matches than that of VLOOKUP.

 There is the option to find the closest match smaller than (-1) or closest greater than (1) the value looked for. There is also an option to use wildcard characters (2) such as the ? or the \*. This setting is not on by default like it was with VLOOKUP.

 The formula in this example returns the closest less than the value looked for if an exact match is not found:

        `=XLOOKUP(B2,$E$3:$E$7,$F$3:$F$7,,-1)`
    
![A range lookup with a mistake](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/09/range-lookup-mistake.png) 

 However, there is a mistake in cell C7 where the #N/A error is returned (the 'if not found' argument was not used). This should have returned a 0% discount because spending 64 does not reach the criteria for any discount.

 Another advantage of the XLOOKUP function is that it does not require the lookup range to be in ascending order as VLOOKUP does.

 Enter a new row at the bottom of the lookup table and then open up the formula. Expand the used range by clicking and dragging the corners.

![Fix the mistake by expanding the used range](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/11/expand-lookup-table.png) 

 The formula immediately corrects the error. It is not a problem with having the "0" at the bottom of the range.

![Error fixed by expanding lookup table](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/11/error-fixed.png) 

 Personally, I would still sort the table by the lookup column. Having "0" at the bottom would drive me crazy. But the fact that the formula didn't break is brilliant.

##  XLOOKUP Replaces the HLOOKUP Function Too

 As mentioned, the XLOOKUP function is also here to replace [HLOOKUP](https://ai-voice.techidaily.com/new-2024-approved-top-6-mickey-mouse-voice-generators-providing-efficient-results/). One function to replace two. Excellent!

 The HLOOKUP function is the horizontal lookup, used for searching along rows.

 Not as well known as its sibling VLOOKUP, but useful for examples like below where the headers are in column A, and the data is along rows 4 and 5.

 XLOOKUP can look in both directions - down columns and also along rows. No longer do we need two different functions.

 In this example, the formula is used to return the sales value relating to the name in cell A2\. It looks along row 4 to find the name, and returns the value from row 5:

        `=XLOOKUP(A2,B4:E4,B5:E5)`
    
![XLOOKUP as a HLOOKUP function replacement](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/09/hlookup.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/o-sRtqHdEYY?si=NMTMQVxJsUaoguqh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  XLOOKUP Can Look From the Bottom-Up

 Typically, you need to hunt down a list to find the first (often only) occurrence of a value. XLOOKUP has a sixth argument named search mode. This enables us to switch the lookup to start at the bottom and look up a list to find the last occurrence of a value instead.

 In the example below, we would like to find the stock level for each product in column A.

 The lookup table is in date order, and there are multiple stock checks per product. We want to return the stock level from the last time it was checked (last occurrence of the Product ID).

![Sample data for a backwards lookup](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/09/last-occurrence-data.png) 

 The sixth argument of the XLOOKUP function provides four options. We are interested in using the "Search last-to-first" option.

![Search mode options with XLOOKUP](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/11/last-to-first.png) 

 The completed formula is shown here:

        `=XLOOKUP(A2,$E$2:$E$9,$F$2:$F$9,,,-1)`
    
![XLOOKUP looking bottom-up a list of values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/09/look-backwards.png) 

 In this formula, the fourth and fifth argument were ignored. It is optional, and we wanted the default of an exact match.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Round-Up

 The XLOOKUP function is the [eagerly awaited successor](https://techcommunity.microsoft.com/t5/Excel-Blog/Announcing-XLOOKUP/ba-p/811376) to both the VLOOKUP and HLOOKUP functions.

 A variety of examples were used in this article to demonstrate the advantages of XLOOKUP. One of which is that XLOOKUP can be used across sheets, workbooks and also with tables. The examples were kept simple in the article to help our understanding.

 Due to [dynamic arrays being introduced into Excel](https://techcommunity.microsoft.com/t5/Excel-Blog/Preview-of-Dynamic-Arrays-in-Excel/ba-p/252944) soon, it can also return a range of values. This is definitely something worth exploring further.

 The days of VLOOKUP are numbered. XLOOKUP is here and will soon be the de facto lookup formula.

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
<li><a href="https://fox-http.techidaily.com/new-2024-approved-top-kid-safe-toy-quadcopters-unveiled/"><u>[New] 2024 Approved Top Kid-Safe Toy Quadcopters Unveiled</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-essential-know-how-record-ipad-display/"><u>[New] Essential Know-How Record iPad Display</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-refine-your-beauty-videos-with-youtubes-palette-tweaking/"><u>[New] Refine Your Beauty Videos with Youtube's Palette Tweaking</u></a></li>
<li><a href="https://win11.techidaily.com/5yq55p6c55qe44gq6zplusz5qw944ov44kh44kk44or5zyn57iu5pa55rovic0g44cm44kq44o844oh44kj44kq5zyn57iu44k944ov44oi44km44kn44ki44cn44ks5yip55so44gx44gf5oml5byv44gn.45/"><u>効果的な音楽ファイル圧縮方法 - 「オーディオ圧縮ソフトウェア」を利用した手引き</u></a></li>
<li><a href="https://win11.techidaily.com/5yan55sf5lin6io944gr44gq44gj44gf44ot44oh44kq44ks44gp44gg44ke44gj44gm6kaw6ig044gz44kl44gl/"><u>再生不能になったビデオをどうやって視聴するか</u></a></li>
<li><a href="https://win11.techidaily.com/access-and-enjoy-christian-melodies-anytime-download-free-yt-mp3s/"><u>Access and Enjoy Christian Melodies Anytime: Download Free YT Mp3s!</u></a></li>
<li><a href="https://win11.techidaily.com/audacity-youtube-recording-mastery-easy-tutorial-for-capturing-video-clips/"><u>Audacity YouTube Recording Mastery: Easy Tutorial for Capturing Video Clips</u></a></li>
<li><a href="https://youtube-data.techidaily.com/d-the-scenes-filmmaking-tips-from-youtube-experts-for-2024/"><u>Behind-the-Scenes Filmmaking Tips From YouTube Experts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/best-high-quality-audio-formats-which-offers-smaller-sizes/"><u>Best High-Quality Audio Formats: Which Offers Smaller Sizes?</u></a></li>
<li><a href="https://win11.techidaily.com/best-top-rated-flac-audio-software-for-windows-11-a-comprehensive-guide/"><u>Best Top-Rated FLAC Audio Software for Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-tutorial-on-capturing-your-slide-show-in-action-using-powerpoint/"><u>Comprehensive Tutorial on Capturing Your Slide Show in Action Using PowerPoint</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-online-with-leading-platforms-facebook-twitter-instagram-and-yt/"><u>Connect Online with Leading Platforms: Facebook, Twitter, Instagram & YT</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-nokia-g22-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Nokia G22? | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-elevate-your-biz-game-youtube-channels-that-succeeded/"><u>In 2024, Elevate Your Biz Game YouTube Channels That Succeeded</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-simulate-gps-movement-with-location-spoofer-on-google-pixel-fold-drfone-by-drfone-virtual-android/"><u>In 2024, How To Simulate GPS Movement With Location Spoofer On Google Pixel Fold? | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/inside-the-videography-realm-xstudio-study/"><u>Inside the Videography Realm XStudio Study</u></a></li>
</ul></div>

