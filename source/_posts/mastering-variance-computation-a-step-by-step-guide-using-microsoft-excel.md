---
title: "Mastering Variance Computation: A Step-by-Step Guide Using Microsoft Excel"
date: 2024-08-28 15:54:56
updated: 2024-08-29 11:33:33
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/f5c71e67a7e48026b76caae61fa224d5139bed7177e712ed911926c5fc53a785.jpg
---

## Mastering Variance Computation: A Step-by-Step Guide Using Microsoft Excel

### Quick Links

* [What is Variance?](https://youtube-webster.techidaily.com/024-approved-the-ultimate-pathway-to-prominence-on-youtube-channel-showcase/)
* [How Variance Functions Are Used in Excel](https://graphic-issues.techidaily.com/how-to-fix-asus-laptop-black-screen-easily/)
* [How to Calculate Sample Variance in Excel Using VAR, VAR.S, or VARA](https://snapchat-videos.techidaily.com/new-2024-approved-snapchats-money-making-opportunities-exposed/)
* [How to Calculate Population Variance in Excel using VARP, VAR.P, or VARPA](https://some-approaches.techidaily.com/new-ultimate-avc-player-on-devices/)

### Key Takeaways

 You can calculate sample variance in Excel using a VAR, VAR.S, or VARA function. For population variance VARP, VAR.P, or VARPA. Just put your the cell range containing your dataset in the formula, like "VAR(B2:B12)", and you'll get the calculated variance.

 Variance is used to measure the spread of data values against the mean in a data set. Microsoft Excel can be used to calculate this variance to help you [analyse your data](https://extra-information.techidaily.com/symphonic-streams-exclusive-sites-for-downloadable-tones/), determine its quality, and make important decisions.

##  What is Variance?

 Variance measures how far the values in a data set are against the mean (average) value. The higher the variance, the more spread out your data is. In contrast, if the variance is low, it means there isn't much of a spread in your data.

 If you're calculating the variance manually, you'll first need to calculate the mean value for your data set. Next, you'll calculate the difference between each number in your set and the mean value, and then square the result. You'll then add the squared values together and divide them by the total number of values in the set to find the variance.

 It's possible to calculate the variance in a data set like this by using a small subset of your large data set (sample variance) or by calculating the variance using the entire data set as a whole (population variance).

 Variance (and the statistical topics that surround it) can be quite difficult concepts to understand. To make it easier, let's use a basic scenario. Let's assume you have a list of enrolled pupils in a school.

 You can use population variance to determine the spread of ages against the average age of the entire class. Alternatively, you can use sample variance by taking the list of pupils in a single class and using that smaller subset to determine the spread.

 You use population variance to consider all of the pupils at once, while sample variance uses the smaller subset (in this example, a class). Depending on the size of your data set, it can be quicker and more practical to calculate the sample variance using a smaller subset of data to [work out the mean](https://win-able.techidaily.com/fixing-overwatch-startup-issues-how-to-get-rid-of-the-persistent-black-screen/).

##  How Variance Functions Are Used in Excel

 In Excel, it's simple to calculate either sample or population variance (as long as the data is available for you to use). There are six main functions you can use.

Related: [Excel for Beginners: The 6 Most Important Tasks to Know](https://vp-tips.techidaily.com/professional-stability-essentials-for-youtube-videographers/) 

 For sample variance using numerical values only, you can use VAR, or VAR.S. VAR was the original function, but this has been deprecated in favor of VAR.S in newer Excel versions. However, VAR is still available in Excel for compatibility reasons, including the version of Excel included with [Microsoft 365 subscriptions](https://games-able.techidaily.com/ultimate-console-content-psplus-or-xbox-game-pass/).

 To calculate population variance, you'll need to use VARP or VAR.P. Like VAR and VAR.S, VARP is the original (deprecated) function, while VAR.P is the newer (and currently supported) function.

 If your data set contains text strings or a logical test, you'll need to use VARA (for sample variation) or VARP (for population variance) instead.

##  How to Calculate Sample Variance in Excel Using VAR, VAR.S, or VARA

 To help you calculate sample variance in Excel, we'll use an example data set below. You'll need to replace any data we're using here with your own.

 Make sure to choose the correct function before you begin. For instance, you should use VAR.S for data that only contains numerical values, VARA for data sets that contain a variety of other forms of data, and VAR to maintain compatibility with older spreadsheets.

 To begin, open your Excel spreadsheet and select an empty cell. Select the formula bar and begin to type your VAR, VAR.S, or VARA function. For example:

=VAR(=VAR.S(=VARA(

![To calculate sample variation in Excel, select the formula bar and type your VAR.S formula (eg. =VAR.S(B2:B10).](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/07/excel-vars-formula-example.png) 

 After the opening parenthesis, type the [cell range](https://fox-blue.techidaily.com/2024-approved-mastering-chroma-key-techniques-in-live-broadcasts/) containing your sample subset (eg. B2:B10 for cells between B2 and B10) or select it manually using your mouse. For example:

=VAR(B2:B10)=VAR.S(B2:B10)=VARA(B2:B10)

 Once the formula is complete, close the formula with a closing parenthesis, and press the Enter key.

![Use the VAR, VAR.S, or VARA function in Excel to calculate sample variation.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/07/excel-var-formula-complete.png) 

 The value returned (in this example, 11.11) is the sample variance. You can increase the range of values used, which may improve the accuracy of the result, depending on how large your sample is compared to your full data set.

##  How to Calculate Population Variance in Excel using VARP, VAR.P, or VARPA

 Excel calculates sample and population variance differently. For the user, however, there isn't much difference between the functions you use to calculate sample and population variance in your spreadsheet. The only difference (for you) is the size of the data set you're referring to and the functions you'll use.

 Make sure to choose VAR.P to calculate population variance with a data set that only contains numbers. Alternatively, use VARPA for a data set that contains numbers, text, and logical operators, or VARP to maintain compatibility in an older spreadsheet.

 To start, open your Excel spreadsheet and select an empty cell. From the formula bar, begin to type your formula using VARP, VAR.P, or VARPA:

=VARP(=VAR.P(=VARPA(

![To calculate population variation in Excel, select the formula bar and type your VAR.P formula (eg. =VAR.P(B2:B21) for the full range of cells between B2 and B21).](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/07/excel-varp-formula-example.png) 

 After the opening parenthesis, enter the cell range that contains your full data set (eg. B2:B21 for cells between B2 and B21). Alternatively, use your mouse to select the data manually. For example:

=VAR(B2:B21)=VAR.P(B2:B21)=VARPA(B2:B21)

 When you're ready, close the formula with a closing parenthesis and press the Enter key or select another cell to view the result.

![An example of functions used to calculation population variance (VARP, VAR.P, and VARPA) in Excel.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/07/excel-varp-formula-complete.png) 

 The value returned is the population variance for the full data set.

Related: [13 Essential Excel Functions for Data Entry](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/)

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
