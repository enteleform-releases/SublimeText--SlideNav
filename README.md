
# SlideNav

Easily create slide presentations in Sublime Text with SlideNav

Also includes a file launcher to quickly open media files during your presentation

### DEMO

This GIF has 3 components:
* __Top-Left:__ A Vysor clone of my Android phone screen.  I am running the entire demo from my phone, using the included preset for UnifiedRemote.
* __Bottom-Left:__ A key-capture window displaying all commands which are being executed by UnifiedRemote
* __Right:__ SlideNav in action

![Overview](https://raw.githubusercontent.com/Enteleform/_README_RESOURCES/master/ST_SlideNav/Overview.gif)
( click to zoom in )

## FEATURES

### Slides

* Divide your document with Slides
* Navigate through the document slide by slide ( any content not in the current slide is folded )

### MediaFiles, MediaLinks, TextLinks, & LinkNav

* Launch files during your presentation with MediaLinks
 * MediaLinks can be launched automatically with LinkNav, upon clicking, or with a hotkey
 * List your MediaFiles before your first slide, and access them from any of your slides via MediaLink
 * Define applications & extensions @ __[SlideNav.sublime-settings](https://github.com/Enteleform/ST_SlideNav/blob/master/SlideNav.sublime-settings#L127)__

* Textlinks allow you to define segments of text to highlight during the presentation  

* LinkNav automatically moves through your presentation by MediaLink & TextLink sections

### Remote Control

Included in __[/UnifiedRemote](https://github.com/Enteleform/ST_SlideNav/tree/master/UnifiedRemote)__ is a custom preset for Unified Remote

Unified Remote can be installed on your Android/IOS devices to control your PC/Mac computer!

More info at __[UnifiedRemote/README.md](https://github.com/Enteleform/ST_SlideNav/blob/master/UnifiedRemote/README.md)__

### Snippets

* Slide dividers, MediaFiles, MediaLinks, & TextLinks are generated automatically via hotkey

![Snippets](https://raw.githubusercontent.com/Enteleform/_README_RESOURCES/master/ST_SlideNav/Snippets.gif)

## GETTING STARTED

To get started, see:
* __[SlideNav Interactive Tutorial](https://github.com/Enteleform/ST_SlideNav/blob/master/Tutorial/%5BSlideNav%5D%20Tutorial.py)__
* __[How do I create new presentation?](https://github.com/Enteleform/ST_SlideNav/issues/1)__

In order to get the most functionality out of SlideNav, read the comments @ __[SlideNav.sublime-settings](https://github.com/Enteleform/ST_SlideNav/blob/master/SlideNav.sublime-settings)__

## COMMANDS

These are the included commands & default keybindings:

### Navigate Slides

* Both SlideNav commands will automatically show the first slide when they are first used

SlideNav_Down ( show next Slide )  
<kbd>ctrl</kbd>+<kbd>super</kbd>+<kbd>alt</kbd>+<kbd>=</kbd>

SlideNav_Up ( show previous Slide )  
<kbd>ctrl</kbd>+<kbd>super</kbd>+<kbd>alt</kbd>+<kbd>-</kbd>

### Navigate Links

* Both LinkNav commands are limited to Links that are currently Visible, meaning you can use them without accidentally moving into the next slide

LinkNav_Down  
<kbd>ctrl</kbd>+<kbd>alt</kbd>+<kbd>=</kbd>

LinkNav_Up  
<kbd>ctrl</kbd>+<kbd>alt</kbd>+<kbd>-</kbd>

### Zoom

Zoom_In  ( zoom to selected Slide - Slide title line must be selected )  
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>=</kbd>

Zoom_Out ( exit Slide & show full document )  
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>-</kbd>

Reset_Zoom ( removes zoom level & shows text @ default font size )  
<kbd>ctrl</kbd>+<kbd>alt</kbd>+<kbd>0</kbd>

### Insert Snippets

* Slide, MediaFile, & MediaLink snippet commands can be used:
 * on blank lines ( new text area will automatically be selected )
 * on lines with text ( text area will automatically use line's text )
* The TextLink snippet command can be used:
 * on single lines ( LinkNav will select the affected line )
 * on multiple lines ( LinkNav will select the affected lines )

Insert_Slide  
<kbd>ctrl</kbd>+<kbd>super</kbd>+<kbd>alt</kbd>+<kbd>.</kbd>

Insert_MediaFile ( MediaLink + path )  
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>super</kbd>+<kbd>.</kbd>

Insert_MediaLink  
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>.</kbd>

Insert_TextLink  
<kbd>ctrl</kbd>+<kbd>alt</kbd>+<kbd>.</kbd>

### MediaLink

Open_MediaLink  
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>o</kbd>

Toggle_MediaLink ( enable/disable automatically opening MediaLinks on click )  
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>alt</kbd>+<kbd>.</kbd>

### Slides

Align ( resizes all Slide titles to same length )  
<kbd>ctrl</kbd>+<kbd>super</kbd>+<kbd>.</kbd>

## CUSTOMIZATION

Modifications available @ __[SlideNav.sublime-settings](https://github.com/Enteleform/ST_SlideNav/blob/master/SlideNav.sublime-settings)__

* Define Snippet Visual Styles
* Define MediaLink Applications & Their Associated Extensions
* Define Presentation FileTypes & Comment Characters ( required for any filetype you want to use SlideNav with )

## EXTRAS

I recommend using __[ASCII Decorator](https://packagecontrol.io/packages/ASCII%20Decorator)__ paired with my __[Sublime-Settings](https://github.com/Enteleform/ST_SlideNav/blob/master/ASCII%20Decorator/ASCII%20Decorator.sublime-settings)__ file.
It's a quick & easy way to add visual contast and emphasis to your presentations.

This __[Image To ASCII Converter](http://www.text-image.com/convert/ascii.html)__ is great for turning your favorite [ memes | images | whatever ] into text that you can include in your presentations.

## FEEDBACK

So far, SlideNav has only been tested with Windows 10 & SublimeText 3.

This is my first release! Feel free to contact me at enteleform@gmail.com with any feedback!
