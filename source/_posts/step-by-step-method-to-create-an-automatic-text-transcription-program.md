---
title: Step-by-Step Method to Create an Automatic Text Transcription Program
date: 2024-08-08T13:19:50.640Z
updated: 2024-08-09T13:19:50.640Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Step-by-Step Method to Create an Automatic Text Transcription Program
excerpt: This Article Describes Step-by-Step Method to Create an Automatic Text Transcription Program
keywords: AutoTranscribe Guide,TextToSpeech Conversion,Speech Recognition Tutorial,EasyText-to-Audio Programming,Automatic Text Transcription Toolkit,Build Speech-to-Text Software,Create Audio Text Converter
thumbnail: https://thmb.techidaily.com/82ace019181fb90d20c533db44f7982f837c984d09bf52bb3d1445c9e89ae06d.jpg
---

## Step-by-Step Method to Create an Automatic Text Transcription Program

 OpenAI's Whisper is one of the most powerful solutions for turning your voice into text. However, Whisper can also be annoying to use, since you have to type commands to transcribe an audio file into text. But why do that when we've got AutoHotkey?

 With AutoHotkey, we can effortlessly create a basic GUI for command-line apps like Whisper. So, let's do that and see how you can create your own transcription app by combining AutoHotkey's GUI-making superpowers with OpenAI's Whisper as the "brain" behind the buttons.

## Laying the Foundations for Whisper and AutoHotkey

[You can make cool scripts with AutoHotkey](https://www.makeuseof.com/tag/10-cool-autohotkey-scripts-make/), but that's not all it can do. For this project, we'll use AutoHotkey to create a GUI for Whisper. This will allow us to use OpenAI's voice recognition AI tool by clicking buttons and customizing its functionality using menus instead of typing commands.

 However, this means that you'll need to have both AutoHotkey and Whisper installed to follow along.

 For the first part of the equation, you can [download AutoHotkey from its official site](https://www.AutoHotkey.com/), then run its installer and follow the presented steps.

 Note that we'll use the older "v1" version of the scripting language, not the new v2\. That's important because the two versions use a somewhat different syntax. What we'll see here might not work if using the new v2\.

 The second part is more complicated, but you can learn how to do it by checking our article on [how to turn your voice into text with OpenAI's Whisper for Windows](https://www.makeuseof.com/dictate-documents-openai-whisper/).

 With both installed, our plan of action is as follows:

1. Create a GUI with elements for Whisper's variables and values.
2. Create functions to grab values from the interface, select files and folders, and assemble everything into a usable Whisper command.
3. Run the Whisper command to produce results.

 Of course, you could always use Windows built-in support for Voice Typing, as we saw in our article on [how to start Voice Typing on Windows 11](https://www.makeuseof.com/how-to-start-voice-typing-on-windows-11/). Still, as you'll see while using it, Whisper is much more accurate (but also slower).

 On a more personal note, I should explain that I am not a programmer, and this project is a "remix" of a solution made for personal use.

## How to Make a New AutoHotkey Script

 The first step is to create a new blank script file. Keep it in its own folder, just in case you decide to tweak or build on it, creating more files.

1. Run your favorite file manager (or press **Windows Key** \+ **E** to launch Windows Explorer) and create a folder for your transcription app anywhere you like.  
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Creating Project Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/creating-project-folder-1.jpg)
2. Right-click on a blank spot of the window and select **New** \> **AutoHotkey Script** to create an empty script file.  
<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
![Right Click New Autohotkey Script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/right-click-new-autohotkey-script-1.jpg)
3. Shift + Right Click on the file to access the full context menu and select to open it with your favorite code or text editor. Windows' own **Notepad** will do.  
![Shift Right Click Open With Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/shift-right-click-open-with-editor-1.jpg)
4. Despite being "an empty script", your AHK file will already be pre-populated with some "stuff". Those are useful AutoHotkey variables and flags that define how it should work on your desktop. Ignore them, leave them as they are, and do all your future typing underneath them.  
![Blank Autohotkey Script In Vs Code](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/blank-autohotkey-script-in-vs-code-1.jpg)

## Getting to Know Whisper's Flags

 Since we're making a GUI for a command line app, it's handy to have a reference to its major variables and flags that we'll be using in our project. You can check them out by reading Whisper's documentation, visiting [its official Github page](https://github.com/openai/whisper), and running it in your terminal.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
![Whisper Flags Note In Script](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/whisper-flags-note-in-script-1.jpg)

 We'll list the ones we'll use in this project for convenience. We suggest you add them to your script as comments (in separate lines, each beginning with a ";" character followed by a space).

`; Whisper Flags:; --initial_prompt PROMPT_TEXT; --output_format txt; -o OUTPUT_FOLDER; --model MODEL_TO_USE; --task TRANSCRIBE/TRANSLATE; --language EN/EL`

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
## Creating the GUI With AutoHotkey

 We suggest you split your script into sections using comments like we did to keep it organized. We'll start by defining some variables, continue to the actual GUI, and end by defining its functions.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Establishing the Hidden Variables

 We begin with a section where we'll define variables we may want to change in the future, but not so often that we'd like to expose them through the GUI, over-complicating it. You can type "Variable\_Name = Content or value of the variable" with one variable and value pair per line.

 For this project, we've defined a **OutputFormat** variable that we set to the "**txt**" value and a **WhisperExecutable** variable stating **Whisper's executable file name**. This way, if we want to use the same solution in the future to create SRT subtitle files instead of TXT documents or upgrade Whisper/switch to an alternative app, we can adjust the values of those variables on that single spot instead of throughout the script.

`OutputFormat = txtWhisperExecutable = whisper`

![Defining Script Variables](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/defining-script-variables-1.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
### Setting Up the User Options

 When using Whisper on the command line, three of its flags allow you to define:

* If you're doing **translation** or **transcription**
* The audio file's **language**
* The language **model** you want to use (various sizes are available, each affecting performance VS quality of results).

 The easiest way to offer the same functionality through a GUI is through tried and tested drop-down lists. The syntax for adding a drop-down list to an AutoHotkey GUI is as follows:

`Gui, Add, DropDownList, xPosition yPosition wWidth hHeight vVariable_that_will_hold_selected_value, optionA|optionB|default_optionC||optionD|`

 Based on that, let's add three drop-down lists to our script for selecting Whisper's language (between English/en and Greek/el), model (tiny, base, small, medium, large), and task type (transcribe or translate).

`Gui, Add, DropDownList, x5 y5 w165 h50 vSelectedLanguage, en||el  
Gui, Add, DropDownList, x175 y5 w165 h100 vSelectedModel, tiny|base|small||medium|large|  
Gui, Add, DropDownList, x345 y5 w165 h100 vTaskType, transcribe||translate|`

 To set an option as the default selection, use a double pipe symbol ("|") after it. You can see that, in our example, we've set our language to **en**, SelectedModel to **small**, and TaskType to **transcribe**.

![Defining Gui Drop Down Lists](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/defining-gui-drop-down-lists-1.jpg)

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
### How to Guide Whisper

 Since Whisper is AI-based, there's no way to have absolute control over how Whisper transcribes audio. It's free to choose what it considers optimal.

 However, like other AI solutions, Whisper can accept user prompts. By crafting a prompt, you can "guide" how it transcribes your audio.

 Did the solution we're making fail to Transcribe something correctly? You can try "explaining" to Whisper "what the voice file is about", including the syntax of words, acronyms, and phrases in your prompt as you want them to appear in the transcription. For that, we'll add an AutoHotkey Text Edit field.

 The syntax is not too different than what we used for adding drop-down lists above:

`Gui, Add, Edit, x5 w505 h400 vPromptText, %PromptText%`

 The "%PromptText%" at the end "tells" AHK to show the PromptText variable's content (if it's already assigned a value) within the text field. It won't show anything in the script we're making, but consider it a placeholder for when you eventually tweak the script in the future also to save and load prompts!

 Would you prefer to assign a predefined value to the **PromptText** variable? Add something like the following to the **Variables** section of the script. Remember to replace "Your Name's" with your actual name.

`PromptText = Transcription of Your Name's notes`

<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Defining Prompt Text Edit Field](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/defining-prompt-text-edit-field-1.jpg)

### Setting Up the Action Buttons

 For choosing files, folders, and running Whisper after we've set everything up, it's better to use buttons. You can add buttons to an AHK-made interface using the following:

`Gui, Add, Button, xPosition yPosition wWidth hHeight gFunction_To_Perform, Button Text`

![Adding Action Buttons](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-action-buttons-1.jpg)

 Notice that unlike variables in GUI elements, which begin with the letter "v", function names start with "g", for "Go (to this spot of the script)".

 A single button of an AHK interface can also be deemed "the default one", which will be activated if you don't click anywhere on the GUI and press **Enter**. This is defined by adding "**default**" in the coordinates-and-function section, as you'll notice in our "OK" button:

`Gui, Add, Button, x5 w505 h50 gSelectFile, Load FileGui, Add, Button, x5 w505 h50 gSelectFolder, Choose Output Folder  
​​​​​​​Gui, Add, Button, Default x5 w505 h50 gButtonSubmit, OK`

 With the above, we're defining three buttons:

* One labeled "**Load File**" that, when clicked, will run the **SelectFile** function.
* One labeled "**Choose Output Folder**", which will run the **SelectFolder** function.
* One labeled "**OK**", selected by default, "calling" the **ButtonSubmit** function.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
### How to Show Your GUI

 Our GUI is ready but won't appear on our screen because we haven't "told" AutoHotkey to show it or what each button should do.

![Autohotkey Gui Show And Return](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/autohotkey-gui-show-and-return-1.jpg)

 For that, add the following two lines below those that define your GUI:

`Gui, ShowReturn`

 The first line "tells" AHK to show the GUI's window, while the second marks the section's end.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
## The Functions and Functionality of Our App

 Although we've completed the GUI section, if you try to run the script, it will crash. That's because we're referencing non-existing functions in it. So, our next move is to create those functions.

![Button Functions Highlighted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/button-functions-highlighted-1.jpg)

 The three functions we want are:

* Select an input file.
* Select the output folder where the transcribed file will be stored.
* Craft a command that will "assemble" all variables into a usable Whisper command, akin to what we'd type ourselves in a terminal, and then run it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
### Input File Selection

 The first function, which we've already named "**SelectFile**" when we added its button to the GUI, is:

`SelectFile:FileSelectFile, SelectedFileReturn`

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Adding Troubleshooting Message Box To Select File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-troubleshooting-message-box-to-select-file-1.jpg)

**FileSelectFile** is an AutoHotkey function that displays a typical file requester, allowing the user to select a file. **SelectedFile** is the variable in our script that will "hold" the path to the file the user selected.

 However, as you'll see in our screenshots, we've also added the following line right above the function-ending "return":

`MsgBox, %SelectedFile%`

 This will have AHK show a **Message Box** with the selected file after we choose it, which is useful when troubleshooting your script. If this message box shows your selected file's path and name, it's not your file-selecting button or function that requires fixing.

### Output Folder Selection

 The function for selecting a folder is almost identical, with only the command's name and variable changing, to show we're dealing with folders instead of files:

`SelectFolder:FileSelectFolder, SelectedFolderMsgBox, %SelectedFolder%Return`

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
![Select Folder Function](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/select-folder-function-1.jpg)

### The Final Function

 The final function will be the most complicated. Mapped to the OK button, this will "gather" all variable values from the GUI, morph them into a usable command, and then run it.

 We begin by stating the function's beginning and end:

`ButtonSubmit:Return`

![Button Submit Empty Function](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/button-submit-empty-function-1.jpg)

 To "grab" all of the GUI's values, add the following under the **ButtonSubmit** line:

`Gui Submit, nohide`

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Button Submit Gui Submit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/button-submit-gui-submit-1.jpg)

 The following line creates a new variable called "**WhisperFlags**". It then adds to it all of the GUI's variables as flags for the Whisper command.

`WhisperFlags = --initial_prompt "%PromptText%" --task %TaskType% --model %SelectedModel% --language %SelectedLanguage% --output_format %OutputFormat% -o "%SelectedFolder%" "%SelectedFile%"`

![Button Submit Collecting Whisper Flags](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/button-submit-collecting-whisper-flag-1.jpg)

 Next, we'll "tell" AHK to use the default terminal (CMD.exe) to run Whisper's executable (that we defined with the **WhisperExecutable** variable) with the GUI's variables (that are now "assembled" in the single **WhisperFlags** variable).

`RunWait, cmd.exe /c %WhisperExecutable% %WhisperFlags%`

![Button Submit Runwait Whisperexecutable And Flag](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/button-submit-runwait-whisperexecutable-and-flag-1.jpg)

 For even easier troubleshooting we've also added a msgbox, as before, but also added the following line:

`Clipboard = %WhisperExecutable% %WhisperFlags%`

 This will copy to the **Clipboard** the complete command issued to CMD. So, if something fails, instead of only seeing the command in one of AHK's message boxes, you'll also have it available in your Clipboard.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Button Submit Troubleshooting Copy Command To Clipboard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/button-submit-troubleshooting-copy-command-to-clipboard-1.jpg)

 Open a terminal, paste the command from the Clipboard, and check the errors that pop up to locate potential problems.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![Checking Out The Command In Cmd](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/checking-out-the-command-in-cmd-1.jpg)

 For example, while working on the script, I initially forgot to have the prompt enclosed within quotation marks. Thus, the command failed, since Whisper tried to parse the prompt as flags.

## Testing and Final Tweaks

 That was it—we've just created a transcription app using AutoHotkey's GUI-making capabilities and a ready-to-use AI transcription solution.

 Try running your script (double-click its file), and you should see your GUI on your screen.

* Change Whisper's settings using the drop-down lists at the top.
* Type a short description of your transcription (and some terms) in the **Prompt** field.
* Click the **Load File** button and choose the audio file you want to transcribe.
* Click the **Choose Output Folder** button and select where the produced text file should be stored.
* Click on **OK** to unleash Whisper, as configured by your GUI, on your selected audio file, and save its transcription as a text file in the folder you selected.

 If everything worked, go back to your script and either delete or Comment out (by adding a ";" at their beginning) all the troubleshooting functionality (message boxes and copy-to-Clipboard lines).

## Taking Whisper Further With AutoHotkey

 By correctly setting the default values of your GUI and maybe adding a generic prompt, you can turn Whisper into a three-clicks-to-transcribe solution: No paying for commercial solutions, third-party services, fiddling with complicated interfaces, or typing in a terminal.

 With AutoHotkey, we can effortlessly create a basic GUI for command-line apps like Whisper. So, let's do that and see how you can create your own transcription app by combining AutoHotkey's GUI-making superpowers with OpenAI's Whisper as the "brain" behind the buttons.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>