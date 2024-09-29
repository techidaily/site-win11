---
title: "Excel Essentials: Unlocking Efficiency with the XLOOKUP Function Demystified"
date: 2024-08-28T00:47:53.571Z
updated: 2024-08-29T00:47:53.571Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/4f66184ac0a8648b46c6ad4d0861ce71f7dbc55baf3e5392923e05f30fb00ef3.jpg
---

## Excel Essentials: Unlocking Efficiency with the XLOOKUP Function Demystified

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

##  What is XLOOKUP?

 The new XLOOKUP function has solutions for some of the biggest limitations of [VLOOKUP](https://extra-tips.techidaily.com/integrate-sound-and-sight-web-studio/). Plus, it also replaces HLOOKUP. For example, XLOOKUP can look to its left, defaults to an exact match, and allows you to specify a range of cells instead of a column number. VLOOKUP is not this easy to use or as versatile. We'll show you how it all works.

 For the moment, XLOOKUP is only available to users on the Insiders program. Anyone can [join the Insiders program](https://insider.office.com/en-us/) to access the newest Excel features as soon as they become available. Microsoft will soon begin to roll it out to all Office 365 users.

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
##  How to Use the XLOOKUP Function

 Let's dive straight in with an example of XLOOKUP in action. Take the example data below. We want to return the department from column F for each ID in column A.

![Sample data for XLOOKUP example](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/09/exact-match-data.png) 

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

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
###  No More Column Index Number

 The infamous third argument of VLOOKUP was to specify the column number of the information to return from a table array. This is no longer an issue because XLOOKUP enables you to select the range to return from (column F in this example).

![The column index number argument of VLOOKUP](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/09/vlookup-arguments.png) 

 And don't forget, XLOOKUP can view the data left of the selected cell, unlike VLOOKUP. More on this below.

 You also no longer have the issue of a broken formula when new columns are inserted. If that happened in your spreadsheet, the return range would adjust automatically.

![Inserted column does not break XLOOKUP](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/09/inserted-column.png) 

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
###  Exact Match is the Default

 It was always confusing when learning VLOOKUP why you had to specify an exact match was wanted.

 Fortunately, XLOOKUP defaults to an exact match---the far more common reason to use a lookup formula). This reduces the need to answer that fifth argument and ensures fewer mistakes by users new to the formula.

 So in short, XLOOKUP asks fewer questions than VLOOKUP, is more user-friendly, and is also more durable.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
##  XLOOKUP can Look to the Left

 Being able to select a lookup range makes XLOOKUP more versatile than VLOOKUP. With XLOOKUP, the order of the table columns does not matter.

 VLOOKUP was constrained by searching the left-most column of a table and then returning from a specified number of columns to the right.

 In the example below, we need to lookup an ID (column E) and return the person's name (column D).

![Example data for a lookup formula to the left](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/09/lookup-left-data.png) 

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
 The following formula can achieve this:

        `=XLOOKUP(A2,$E$2:$E$8,$D$2:$D$8)`
    
![XLOOKUP function returning a value to its left](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/09/lookup-left-complete.png) 

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  What to Do If Not Found

 Users of lookup functions are very familiar with the #N/A error message that greets them when their VLOOKUP or their MATCH function cannot find what it needs. And often there is a logical reason for this.

 Therefore, users quickly research how to hide this error because it is not correct or useful. And, of course, there are ways to do so.

 XLOOKUP comes with its own built-in "if not found" argument to handle such errors. Let's see it in action with the previous example, but with a mistyped ID.

 The following formula will display the text "Incorrect ID" instead of the error message: 

        `=XLOOKUP(A2,$E$2:$E$8,$D$2:$D$8,"Incorrect ID")`
    
![Alternative text if not found with XLOOKUP](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/11/if-not-found-1.png) 

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
 However, there is a mistake in cell C7 where the #N/A error is returned (the 'if not found' argument was not used). This should have returned a 0% discount because spending 64 does not reach the criteria for any discount.

 Another advantage of the XLOOKUP function is that it does not require the lookup range to be in ascending order as VLOOKUP does.

 Enter a new row at the bottom of the lookup table and then open up the formula. Expand the used range by clicking and dragging the corners.

![Fix the mistake by expanding the used range](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/11/expand-lookup-table.png) 

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
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


