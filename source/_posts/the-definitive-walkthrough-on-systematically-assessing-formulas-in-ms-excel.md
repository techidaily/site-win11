---
title: The Definitive Walkthrough on Systematically Assessing Formulas in MS Excel
date: 2024-08-28T00:49:03.192Z
updated: 2024-08-29T00:49:03.192Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/09/microsoft_excel_hero_1200x675.jpg
---

## The Definitive Walkthrough on Systematically Assessing Formulas in MS Excel

### Quick Links

* [Use the Evaluate Formula Tool in Excel](https://youtube-videos.techidaily.com/epic-audio-essentials-top-10-for-trending-yt-shorts-for-2024/)

 If you're collaborating on a spreadsheet, you may want to break down a formula someone entered. While many times this easy, there are others where the formula is more complicated. Excel provides a tool to evaluate formulas step-by-step.

 For nested or lengthy formulas, you can see how they work one step at a time from the inside out. This not only helps you to [understand the formula](https://youtube-docs.techidaily.com/n-2024-automate-playlist-retrieval-from-youtube-directly/) and its arguments but can also assist you in troubleshooting formula errors.

 As of May 2022, the feature is available on Windows with Excel for Microsoft 365, Excel 2019, Excel 2016, Excel 2013, Excel 2010, and Excel 2007.

##  Use the Evaluate Formula Tool in Excel

 Open your Excel sheet and select the cell containing the formula you want to evaluate. Go to the Formulas tab and choose "Evaluate Formula" in the Formula Auditing section of the ribbon.

![Evaluate Formula on the Formulas tab](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/FormulasEvaluate-ExcelEvaluateFormulas.png) 

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

 You can then select "Restart" to see the step-by-step evaluation again or "Close" to exit the tool.

 Let's look at another example where you can use the Step In and Step Out features of the tool. For this we'll use a basic [IF function](https://extra-skills.techidaily.com/in-2024-spark-engagement-the-ultimate-list-of-video-text-effects/) formula rather than a nested formula: 

        `=IF(A1=5,"Yes","No")`
    
 . This says, if the value in cell A1 equals 5, display "Yes," otherwise, display "No."

 Here we see our formula with the underlined portion and the Step In button available.

![Evaluate with Step In available](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/EvaluateStepIn-ExcelEvaluateFormulas.png) 

 Click that button to display the constant for the formula. It will appear in its own box. You can see here it's 1 because that's the value in cell A1.

![Step In value displays](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/EvaluateStepOut-ExcelEvaluateFormulas.png) 

 You can then click "Step Out" to close that box and continue with "Evaluate" to work through the formula. The next step evaluates if 1 is equal to 5, per our formula.

![Evaluate equal to result](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/05/EvaluateEqualTo-ExcelEvaluateFormulas.png) 

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



<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->