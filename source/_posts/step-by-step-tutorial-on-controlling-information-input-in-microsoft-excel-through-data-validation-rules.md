---
title: Step-by-Step Tutorial on Controlling Information Input in Microsoft Excel Through Data Validation Rules
date: 2024-08-28T00:49:37.773Z
updated: 2024-08-29T00:49:37.773Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/you-dun-goofed.png
---

## Step-by-Step Tutorial on Controlling Information Input in Microsoft Excel Through Data Validation Rules

If you use Excel spreadsheets to collect data from other people, but find that they often fill your carefully-planned cells with the wrong kind of information, data validation can help.

 This tool lets you restrict specific cells to only allow properly-formatted data. If someone enters anything that’s not supposed to be there---like “lunch at airport” instead of “$15.68” on an expense report---Excel rejects the input until they get it right. Think of it as a passive-aggressive way to make sure people don’t waste your time.

 As an example, here’s the basic expense report worksheet for How-To Geek. Let's say we want to make sure that people only enter numerical values that are formatted as currency (i.e., some digits, followed by a decimal point, followed by two more digits) into certain cells.

 First, select all the cells you want to restrict.

![expense report](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/expense-report.png) 

 Switch over to the "Data" tab on the Ribbon, and then click the “Data Validation” button. If your window isn't full size and you can’t see the labels, it’s the icon with two horizontal boxes, a green check mark, and a red crossed circle.

![arrow](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/arrow.png) 

 In the Data Validation window, on the "Settings" tab, click the “Allow” dropdown menu. Here, you can set a specific type of input to allow for your selected cells. For our expense report, we’re going to insist that users put in a number with two decimal values, so we would select the “Decimal” option. You can also select other criteria, like making sure a cell contains text, a time or date, text of a specific length, or even your own custom validation.

![decimal](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/decimal.png) 

 Whatever type of data you select on the “Allow” dropdown changes the options available to you on the rest of the "Settings" tab. Since we want a numerical value corresponding to currency, we're setting the "Data" dropdown to the “between” setting. Then, we're configuring a minimum value of 0.00 and a maximum value of 10000.00, which is way more than enough to cover our needs.

![data range](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/data-range.png) 

 To test it our, click “OK” to apply the validation settings, and then try putting in an improper value. For example, if we type “pancakes” for the Breakfast value instead of the cost of the meal, we'll get an error message.

![value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/value.png) 

 While that does restrict people to entering only the correct type of data, it doesn't give them any feedback on what type of data is required. So, let's set that up, too.

 Head back to the Data Validation window (Data > Data Validation on the Ribbon). You've got two options here (and you can use both of them if you want). You can use the "Input Message" tab to have a pop-up tool tip show people the type of data you want whenever they select a cell for which data validation is turned on. You can also use the "Error Alert" tab to customize the error they see when they enter the wrong type of data.

 Let's switch over to the "Input Message" tab first. Here, make sure the "Show input message when cell is selected" option is turned on. Then, give your input tooltip a title and some text. As you can see below, just clicking in one of the cells pops up the message letting people know what's expected.

![input message](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/input-message.png) 

 On the "Error Alert" tab, you can customize the error message people see when they enter the wrong type of data. Make sure the "Show error alert after invalid data is entered" option is turned on. Pick a style for your error message from the "Style" dropdown. You can go with a Stop (the red circle with the X), Warning (yellow triangle with an exclamation point), or Information (blue circle with a lowercase "i"), depending on how strong you want the message to come across.

 Type a title for your message, the text of the message itself, and then hit "OK" to finish up.

![error alert](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/error-alert.png) 

 Now, if someone tries to enter improper data, that error message is a little more helpful (or sarcastic, if you prefer).

![excel_1](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/excel_1.png) 

 It's a bit of extra legwork setting up data validation, but it can save you a lot of time later on if you use spreadsheets for collecting data from other people. It's even useful for preventing your own mistakes. And this is doubly true if you’ve set up formulas or any kind of automation tasks that rely on that data.

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
<li><a href="https://extra-skills.techidaily.com/new-masters-tutorial-total-deep-dive-into-xmedia-suite-workshop/"><u>[New] Master's Tutorial  Total Deep Dive Into XMedia Suite Workshop</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-boosting-earnings-in-cosmetic-videography-for-2024/"><u>[Updated] Boosting Earnings in Cosmetic Videography for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-bring-your-vision-to-life-incorporating-free-lut-filters-into-obs-projects/"><u>[Updated] Bring Your Vision to Life  Incorporating Free LUT Filters Into OBS Projects</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-ignite-your-channels-engagement-with-targeted-youtube-links/"><u>[Updated] Ignite Your Channel's Engagement with Targeted YouTube Links</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-beginners-handbook-to-vimeo-footage-capture/"><u>[Updated] In 2024, Beginner's Handbook to Vimeo Footage Capture</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-top-3ips-most-acclaimed-ipad-audio-capturing-tools/"><u>[Updated] In 2024, Top 3iP's Most Acclaimed iPad Audio Capturing Tools</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-the-most-trending-templates-transforming-social-video/"><u>[Updated] The Most Trending Templates Transforming Social Video</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-for-aspiring-filmmakers-the-best-cameras-from-35mm-to-pands/"><u>2024 Approved  For Aspiring Filmmakers, The Best Cameras From 35Mm to P&S</u></a></li>
<li><a href="https://win11.techidaily.com/echoes-of-files-past-navigating-windows-11-history/"><u>Echoes of Files Past: Navigating Windows 11 History</u></a></li>
<li><a href="https://win11.techidaily.com/essential-non-windows-tools-for-quick-and-precise-screen-sniping-techniques/"><u>Essential Non-Windows Tools For Quick and Precise Screen Sniping Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/essential-windows-cmd-shortcuts-for-streamlined-workflow/"><u>Essential Windows Cmd Shortcuts for Streamlined Workflow</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/explore-our-top-recommendations-of-lgbtq-films-streaming-on-netflix-this-july-2024/"><u>Explore Our Top Recommendations of LGBTQ Films Streaming On Netflix This July 2024</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-restoring-lost-wifi-connections-on-windows/"><u>Guidelines for Restoring Lost WiFi Connections on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-through-the-uninstalling-and-restoring-process-of-windows-apps/"><u>Guiding Through the Uninstalling & Restoring Process of Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/hidden-actions-for-context-menus-on-windows-editions/"><u>Hidden Actions for Context Menus on Windows Editions</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-block-windows-11-from-collecting-data/"><u>How to Block Windows 11 From Collecting Data</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-correct-the-non-operational-windows-search-error/"><u>How to Correct the Non-Operational Windows Search Error</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-system-restore-to-revert-windows/"><u>How to Use System Restore to Revert Windows</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-best-online-webm-video-compressors/"><u>In 2024, Best Online WebM Video Compressors</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-an-airtag-from-your-apple-id-account-on-iphone-8-by-drfone-ios/"><u>In 2024, How to Remove an AirTag from Your Apple ID Account On iPhone 8?</u></a></li>
<li><a href="https://win11.techidaily.com/installation-procedures-windows-11-and-vmware-workstation-17/"><u>Installation Procedures: Windows 11 & VMWare Workstation 17</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-textbooks-top-8-effective-learning-techniques-for-windows/"><u>Master the Textbooks: Top 8 Effective Learning Techniques for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-windows-11-password-management-top-11-easy-steps-unveiled/"><u>Masterful Windows 11 Password Management: Top 11 Easy Steps Unveiled</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-tech-trends-through-toms-equipment-analysis/"><u>Mastering Tech Trends Through Tom's Equipment Analysis</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-the-art-of-audio-fading-2-pro-tips-for-final-cut-pro-users/"><u>New The Art of Audio Fading 2 Pro Tips for Final Cut Pro Users</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-windows-settings-for-flawless-valorant/"><u>Optimizing Windows Settings for Flawless Valorant</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-obstacles-battlenet-not-opening-issue/"><u>Overcoming Obstacles: Battle.net Not Opening Issue</u></a></li>
<li><a href="https://win11.techidaily.com/rejuvenate-old-pcs-with-windows-11-to-go-and-rufus-tutorial/"><u>Rejuvenate Old PCs with Windows 11, To Go & Rufus Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-league-disconnects-in-windows-os/"><u>Resolving League Disconnects in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-multi-zip-operations-on-windows-systems/"><u>Seamless Multi-Zip Operations on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-prime-viewing-fixing-windows-11-audio-subtitle-discrepancies/"><u>Seamless Prime Viewing: Fixing Windows 11 Audio-Subtitle Discrepancies</u></a></li>
<li><a href="https://win11.techidaily.com/securing-steam-readwrite-success-in-os-x/"><u>Securing Steam Read/Write Success in OS X</u></a></li>
<li><a href="https://win11.techidaily.com/securing-your-windows-11-ui-master-end-task-options/"><u>Securing Your Windows 11 UI: Master End Task Options</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-function-keys-not-adjusting-display-brighness-on-win-11/"><u>Solutions for Function Keys Not Adjusting Display Brighness on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-the-steam-lag-in-windows-11-gaming-environment/"><u>Solutions to the Steam Lag in Windows 11 Gaming Environment</u></a></li>
<li><a href="https://tech-haven.techidaily.com/step-by-step-instructions-for-a-full-factory-restart-of-your-toshiba-computer/"><u>Step-by-Step Instructions for a Full Factory Restart of Your Toshiba Computer</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-salvaging-deleted-files-from-your-system/"><u>Swiftly Salvaging Deleted Files From Your System</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-clearing-black-pixels-in-winsteam/"><u>Techniques for Clearing Black Pixels in WinSteam</u></a></li>
<li><a href="https://win11.techidaily.com/the-obsidian-edge-cutting-edge-visual-notes-methodology/"><u>The Obsidian Edge: Cutting-Edge Visual Notes Methodology</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-buying-windows-11-keys/"><u>The Ultimate Guide to Buying Windows 11 Keys</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-solutions-for-overcoming-hypervisorbsod-in-windows/"><u>Top 5 Solutions for Overcoming HYPERVISOR_BSOD in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-windows-11-select-6-must-install-android-apps/"><u>Transforming Windows 11: Select 6 Must-Install Android Apps</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-your-potential-with-top-notch-fps-counters-for-windows-11-gamers/"><u>Unleashing Your Potential with Top-Notch FPS Counters for Windows 11 Gamers</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-11-adding-the-jdk-efficiently/"><u>Unlock Windows 11: Adding the JDK Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-pc-potential-top-tips-to-troubleshoot-broken-keyboard-commands-in-windows/"><u>Unlocking PC Potential: Top Tips to Troubleshoot Broken Keyboard Commands in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-potential-of-a-fresh-windows-update-start/"><u>Unlocking the Potential of a Fresh Windows Update Start</u></a></li>
<li><a href="https://win11.techidaily.com/unplugging-issues-keeping-usbs-active-on-windows-11/"><u>Unplugging Issues: Keeping USBs Active on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-character-viewer-in-windows-11/"><u>Unveiling the Character Viewer in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-if-googles-nearby-share-app-is-not-working-on-windows/"><u>What to Do if Google’s Nearby Share App Is Not Working on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-0x800f0922-update-fix-strategies/"><u>Windows 11'S 0X800F0922 Update Fix Strategies</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->