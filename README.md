
# ST_SlideNav

Easily create slide presentations in Sublime Text with SlideNav

Also includes a file launcher to quickly open media files during your presentation

## FEATURES

### Slides

* Divide your document with Slides
* Navigate through the document slide by slide ( any content not in the current slide is folded )

![SlideDemo](http://i.imgur.com/q02FrPm.gif?1)

### MediaLink, TextLink, & LinkNav

* Launch files during your presentation with MediaLinks
* MediaLinks can be launched automatically upon clicking, with LinkNav, or with a hotkey
* List your MediaLink+Path at the beginning of the document, and access it anywhere else in the document
* Define applications & extensions @ SlideNav.sublime-settings

* Textlinks allow you to define segments of text to hightlight during the presentation
* LinkNav automatically moves through your presentation by MediaLink & TextLink sections

![LinkDemo](http://i.imgur.com/0UxRYbf.gif?1)

### Remote Control

Included in [/UnifiedRemote](https://github.com/Enteleform/ST_SlideNav/tree/master/UnifiedRemote) is a custom preset for Unified Remote

Unified Remote can be installed on your Android/IOS devices to control your PC/Mac computer!

Here is a screenshot of the preset:

![UnifiedRemote](http://i.imgur.com/WYe2Cf6.png?1)

More info at [UnifiedRemote/README.md](https://github.com/Enteleform/ST_SlideNav/blob/master/UnifiedRemote/README.md)

### Snippets

* Slide dividers, MediaLinks, & TextLinks are generated automatically via hotkey
* MediaLinks can be generated with or without path ( use with path to define MediaLink, use without path to launch MediaLink anywhere else in the document )

![SnippetDemo](http://i.imgur.com/RUvj93C.gif?1)

## USAGE

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

### Insert Snippets

* All Snippet commands can be used 2 ways
 * on blank lines ( new text area will automatically be selected )
 * on lines with text ( text area will automatically use line's text )

Insert_Slide
<kbd>ctrl</kbd>+<kbd>super</kbd>+<kbd>alt</kbd>+<kbd>.</kbd>

Insert_TextLink
<kbd>ctrl</kbd>+<kbd>alt</kbd>+<kbd>.</kbd>

Insert_MediaFile ( MediaLink + path )
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>super</kbd>+<kbd>.</kbd>

Insert_MediaLink
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>.</kbd>

### MediaLink

Open_MediaLink
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>o</kbd>

Toggle_MediaLink ( enable/disable automatically opening MediaLinks on click )
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>alt</kbd>+<kbd>.</kbd>

### Slides

Align ( resizes all Slide titles to same length )
<kbd>ctrl</kbd>+<kbd>super</kbd>+<kbd>.</kbd>

## GETTING STARTED

To get started, see:
[How do I create new presentation?](https://github.com/Enteleform/ST_SlideNav/issues/1)

## CUSTOMIZATION

Modifications available @ [SlideNav.sublime-settings](https://github.com/Enteleform/ST_SlideNav/blob/master/SlideNav.sublime-settings)

* Define Snippet Visual Styles
* Define MediaLink Applications & Their Associated Extensions
* Define Presentation FileTypes & Comment Characters ( required for any filetype you want to use SlideNav with )

## KNOWN LIMITATIONS

In order to get the most functionality out of SlideNav, read the comments @ [SlideNav.sublime-settings](https://github.com/Enteleform/ST_SlideNav/blob/master/SlideNav.sublime-settings)

## FEEDBACK

So far, SlideNav has only been tested with Windows 10 & SublimeText 3.

This is my first release! Feel free to contact me at enteleform@gmail.com with any feedback!

