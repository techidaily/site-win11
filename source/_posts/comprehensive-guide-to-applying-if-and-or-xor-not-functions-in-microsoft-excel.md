---
title: Comprehensive Guide to Applying IF, AND, OR, XOR, Not Functions in Microsoft Excel
date: 2025-01-02T17:13:49.735Z
updated: 2025-01-06T20:34:58.658Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/office_excel_lede-5.png
---

## Comprehensive Guide to Applying IF, AND, OR, XOR, Not Functions in Microsoft Excel

### Quick Links

* [How to Use the IF Function](https://vp-tips.techidaily.com/bypass-samsungs-vr-camera-here-are-your-top-alternatives/)
* [The AND and OR Logical Functions](https://win-blog.techidaily.com/insufficient-cpu-specs-how-to-update-for-optimal-vanguard-performance/)
* [The XOR Function](https://iphone-unlock.techidaily.com/4-ways-to-unlock-iphone-14-to-use-usb-accessories-without-passcode-drfone-by-drfone-ios/)
* [The NOT Function](https://extra-resources.techidaily.com/2024-approved-beyond-basic-editing-innovative-use-of-luts-for-photography/)

 Logical functions are some of the most popular and useful in Excel. They can test values in other cells and perform actions dependent upon the result of the test. This helps us to automate tasks in our spreadsheets.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  How to Use the IF Function

 The IF function is the main logical function in Excel and is, therefore, the one to understand first. It will appear numerous times throughout this article.

 Let's have a look at the structure of the IF function, and then see some examples of its use.

 The IF function accepts 3 bits of information:

=IF(logical_test, [value_if_true], [value_if_false])

* **logical\_test:** This is the condition for the function to check.
* **value\_if\_true:** The action to perform if the condition is met, or is true.
* **value\_if\_false:** The action to perform if the condition is not met, or is false.

###  Comparison Operators to Use with Logical Functions

 When performing the logical test with cell values, you need to be familiar with the comparison operators. You can see a breakdown of these in the table below.

![Comparison operators for logical functions](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/comparison-operators.png) 

 Now let's look at some examples of it in action.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

###  IF Function Example 1: Text Values

 In this example, we want to test if a cell is equal to a specific phrase. The IF function is not case-sensitive so does not take upper and lower case letters into account.

 The following formula is used in column C to display "No" if column B contains the text "Completed" and "Yes" if it contains anything else.

=IF(B2="Completed","No","Yes")

![IF function to test text values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/if-example-text.png) 

 Although the IF function is not case sensitive, the text must be an exact match.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

###  IF Function Example 2: Numeric Values

 The IF function is also great for comparing numeric values.

 In the formula below we test if cell B2 contains a number greater than or equal to 75\. If it does, then we display the word "Pass," and if not the word "Fail."

=IF(B2>=75,"Pass","Fail")

![If condition with numeric values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/if-example-numbers-1.png) 

 The IF function is a lot more than just displaying different text on the result of a test. We can also use it to run different calculations.

 In this example, we want to give a 10% discount if the customer spends a certain amount of money. We will use £3,000 as an example.

=IF(B2>=3000,B2*90%,B2)

![Conditional formula by using the IF function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/if-with-formula.png) 

 The B2\*90% part of the formula is a way that you can subtract 10% from the value in cell B2\. There are many ways of doing this.

 What's important is that you can use any formula in the `value_if_true` or `value_if_false` sections. And running different formulas dependent upon the values of other cells is a very powerful skill to have.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

###  IF Function Example 3: Date Values

 In this third example, we use the IF function to track a list of due dates. We want to display the word "Overdue" if the date in column B is in the past. But if the date is in the future, calculate the number of days until the due date.

 The formula below is used in column C. We check if the due date in cell B2 is less than today's date (The TODAY function returns today's date from the computer's clock).

=IF(B2<TODAY(),"Overdue",B2-TODAY())

![Testing if dates are due](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/due-dates.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

###  What are Nested IF Formulas?

 You may have heard of the term nested IFs before. This means that we can write an IF function within another IF function. We may want to do this if we have more than two actions to perform.

 One IF function is capable of performing two actions (the `value_if_true` and `value_if_false`). But if we embed (or nest) another IF function in the `value_if_false` section, then we can perform another action.

 Take this example where we want to display the word "Excellent" if the value in cell B2 is greater than or equal to 90, display "Good" if the value is greater than or equal to 75, and display "Poor" if anything else.

=IF(B2>=90,"Excellent",IF(B2>=75,"Good","Poor"))

![nested-ifs](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/nested-ifs-1.png) 

 We have now extended our formula to beyond what just one IF function can do. And you can nest more IF functions if necessary.

 Notice the two closing brackets on the end of the formula---one for each IF function.

 There are alternative formulas that can be cleaner than this nested IF approach. One very useful alternative is [the SWITCH function in Excel](https://support.office.com/en-us/article/switch-function-47ab33c0-28ce-4530-8a45-d532ec4aa25e).

##  The AND and OR Logical Functions

 The AND and OR functions are used when you want to perform more than one comparison in your formula. The IF function alone can only handle one condition, or comparison.

 Take an example where we discount a value by 10% dependent upon the amount a customer spends and how many years they have been a customer.

 On their own, the AND and OR functions will return the value of TRUE or FALSE.

 The AND function returns TRUE only if every condition is met, and otherwise returns FALSE. The OR function returns TRUE if one or all of the conditions are met, and returns FALSE only if no conditions are met.

 These functions can test up to 255 conditions, so are certainly not limited to just two conditions like is demonstrated here.

 Below is the structure of the AND and OR functions. They are written the same. Just substitute the name AND for OR. It is just their logic which is different.

=AND(logical1, [logical2] ...)

 Let's see an example of both of them evaluating two conditions.

###  AND Function example

 The AND function is used below to test if the customer spends at least £3,000 and has been a customer for at least three years.

=AND(B2>=3000,C2>=3)

![AND function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/and-function.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8Y-k_3N-0OI?si=1J-aFBXLJl5b3x4h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can see that it returns FALSE for Matt and Terry because although they both meet one of the criteria, they need to meet both with the AND function.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

###  OR Function Example

 The OR function is used below to test if the customer spends at least £3,000 or has been a customer for at least three years.

=OR(B2>=3000,C2>=3)

![The OR logical function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/or-function.png) 

 In this example, the formula returns TRUE for Matt and Terry. Only Julie and Gillian fail both conditions and return the value of FALSE.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

###  Using AND and OR with the IF Function

 Because the AND and OR functions return the value of TRUE or FALSE when used alone, it's rare to use them by themselves.

 Instead, you'll typically use them with the IF function, or within an Excel feature such as Conditional Formatting or Data Validation to perform some retrospective action if the formula evaluates to TRUE.

 In the formula below, the AND function is nested inside the IF function's logical test. If the AND function returns TRUE then 10% is discounted from the amount in column B; otherwise, no discount is given and the value in column B is repeated in column D.

=IF(AND(B2>=3000,C2>=3),B2*90%,B2)

![Excel formula with IF and AND functions](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/if-and-and.png) 

##  The XOR Function

 In addition to the OR function, there is also an exclusive OR function. This is called the XOR function. The XOR function was introduced with the Excel 2013 version.

 This function can take some effort to understand, so a practical example is shown.

 The structure of the XOR function is the same as the OR function.

=XOR(logical1, [logical2] ...)

 When evaluating just two conditions the XOR function returns:

* TRUE if either condition evaluates to TRUE.
* FALSE if both conditions are TRUE, or neither condition is TRUE.

 This differs from the OR function because that would return TRUE if both conditions were TRUE.

 This function gets a little more confusing when more conditions are added. Then the XOR function returns:

* TRUE if an **odd** number of conditions return TRUE.
* FALSE if an **even** number of conditions result in TRUE, or if **all** conditions are FALSE.

 Let's look at a simple example of the XOR function.

 In this example, sales are split over two halves of the year. If a salesperson sells £3,000 or more in both halves then they are assigned Gold standard. This is achieved with an AND function with IF like earlier in the article.

 But if they sell £3,000 or more in either half then we want to assign them Silver status. If they don't sell £3,000 or more in both then nothing.

 The XOR function is perfect for this logic. The formula below is entered into column E and shows the XOR function with IF to display "Yes" or "No" only if either condition is met.

=IF(XOR(B2>=3000,C2>=3000),"Yes","No")

![The XOR Function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/xor.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RvR5PNhspKE?si=uJcMYK9v-_Xq7fAg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  The NOT Function

 The final logical function to discuss in this article is the NOT function, and we have left the simplest for last. Although sometimes it can be hard to see the 'real world' uses of the function at first.

 The NOT function reverses the value of its argument. So if the logical value is TRUE, then it returns FALSE. And if the logical value is FALSE, it will return TRUE.

 This will be easier to explain with some examples.

 The structure of the NOT function is;

=NOT(logical)

###  NOT Function Example 1

 In this example, imagine we have a head office in London and then many other regional sites. We want to display the word "Yes" if the site is anything except London, and "No" if it is London.

 The NOT function has been nested in the logical test of the IF function below to reverse the TRUE result.

=IF(NOT(B2="London"),"Yes","No")

![not-function-example-1](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/not-function1.png) 

 This can also be achieved by using the NOT logical operator of <>. Below is an example.

=IF(B2<>"London","Yes","No")

###  NOT Function Example 2

 The NOT function is useful when working with information functions in Excel. These are a group of functions in Excel that check something, and return TRUE if the check is a success, and FALSE if it is not.

 For example, the ISTEXT function will check if a cell contains text and return TRUE if it does and FALSE if it does not. The NOT function is helpful because it can reverse the result of these functions.

 In the example below, we want to pay a salesperson 5% of the amount they upsell. But if they did not upsell anything, the word "None" is in the cell and this will produce an error in the formula.

 The ISTEXT function is used to check for the presence of text. This returns TRUE if there is text, so the NOT function reverses this to FALSE. And the IF performs its calculation.

=IF(NOT(ISTEXT(B2)),B2*5%,0)

![NOT function example 2](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/not-function2.png) 

 Mastering logical functions will give you a big advantage as an Excel user. To be able to test and compare values in cells and perform different actions based on those results is very useful.

---

 This article has covered the best logical functions used today. Recent versions of Excel have seen the introduction of more functions added to this library, such as the XOR function mentioned in this article. Keeping up to date with these new additions will keep you ahead of the crowd.

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
<li><a href="https://location-social.techidaily.com/does-find-my-friends-work-on-tecno-camon-20-pro-5g-drfone-by-drfone-virtual-android/"><u>Does find my friends work on Tecno Camon 20 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-add-your-digital-signature-to-a-docx-document-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to Add Your Digital Signature to a .docx Document</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-overcome-hal-initialization-errors-and-get-your-pc-running-smoothly-again/"><u>How to Overcome HAL Initialization Errors and Get Your PC Running Smoothly Again</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-achieving-muted-audibility-with-effortless-fading-in-lumafusion/"><u>In 2024, Achieving Muted Audibility with Effortless Fading in Lumafusion</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-breaking-down-the-elements-of-a-youtube-shorts-template/"><u>In 2024, Breaking Down the Elements of a YouTube Shorts Template</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-realme-v30t-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Realme V30T to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-pinnacle-studio-for-mac-top-competitors-and-options-for-2024/"><u>New Pinnacle Studio for Mac Top Competitors and Options for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/quick-setup-of-intel-hdgraphics-520/"><u>Quick Setup of Intel HDGraphics 520</u></a></li>
<li><a href="https://technical-tips.techidaily.com/transferring-picture-memories-how-to-shift-google-photos-to-icloud/"><u>Transferring Picture Memories: How to Shift Google Photos to iCloud</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-how-to-troubleshoot-video-issues-in-your-android-device/"><u>Ultimate Guide: How to Troubleshoot Video Issues in Your Android Device</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-step-by-step-tutorial-cropping-footage-with-davinci-resolve/"><u>Ultimate Step-by-Step Tutorial: Cropping Footage with DaVinci Resolve</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-techniques-for-securely-managing-digital-copies-of-dvds-and-cds-rip-burn-and-duplicate/"><u>Ultimate Techniques for Securely Managing Digital Copies of DVDs and CDs - Rip, Burn, and Duplicate</u></a></li>
<li><a href="https://win11.techidaily.com/uncovering-leaked-clip-insights-and-teasers-for-the-affordable-next-generation-iphone/"><u>Uncovering Leaked Clip Insights & Teasers for the Affordable Next Generation iPhone</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-pls-files-a-comprehensive-guide-on-opening-and-conversion/"><u>Understanding PLS Files: A Comprehensive Guide on Opening & Conversion</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-the-ultimate-list-5-free-online-tone-generators/"><u>Updated The Ultimate List 5 Free Online Tone Generators</u></a></li>
<li><a href="https://win11.techidaily.com/video/"><u>Videoダウンロードハンドラーの効果的な利用法を学ぶ</u></a></li>
<li><a href="https://win11.techidaily.com/watch-youre-next-a-top-recommendation-for-fans-seeking-a-thrilling-horror-experience/"><u>Watch 'You're Next': A Top Recommendation for Fans Seeking a Thrilling Horror Experience</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11stereo-mix/"><u>Windows 11でStereo Mixによる単音声録音手法</u></a></li>
<li><a href="https://win11.techidaily.com/wonderfox-navigation-error-why-you-cant-find-the-content-anymore-new-link-text/"><u>WonderFox Navigation Error: Why You Can’t Find the Content Anymore – New Link Text</u></a></li>
</ul></div>

