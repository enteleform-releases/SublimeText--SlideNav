
# ST_SublimeSlides

Easily create slide presentations in Sublime Text with SublimeSlides

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
* Define applications & extensions @ SublimeSlides.sublime-settings

* Textlinks allow you to define segments of text to hightlight during the presentation

* LinkNav allows you to automatically move through your presentation by MediaLink & TextLink sections

![LinkDemo](http://i.imgur.com/0UxRYbf.gif?1)

### Remote Control

Included in [/UnifiedRemote](https://github.com/Enteleform/ST_SublimeSlides/tree/master/UnifiedRemote) is a custom preset for Unified Remote

Unified Remote can be installed on your Android/IOS devices to control your PC/Mac computer!

Here is a screenshot of the preset:

![UnifiedRemote](http://i.imgur.com/kruMIhu.png?1)

More info at [UnifiedRemote_README.md](https://github.com/Enteleform/ST_SublimeSlides/blob/master/UnifiedRemote/UnifiedRemote_README.md)

### Snippets

* Slide dividers, MediaLinks, & TextLinks are generated automatically via hotkey
* MediaLinks can be generated with or without path ( use with path to define MediaLink, use without path to launch MediaLink anywhere else in the document )

![SnippetDemo](http://i.imgur.com/RUvj93C.gif?1)

## USAGE

These are the included commands & default keybindings:

### Navigate Slides

* Both NavigateSlides commands will automatically show the first slide when they are first used

NavigateSlides_Down ( show next Slide )
<kbd>ctrl</kbd>+<kbd>super</kbd>+<kbd>alt</kbd>+<kbd>=</kbd>

NavigateSlides_Up ( show previous Slide )
<kbd>ctrl</kbd>+<kbd>super</kbd>+<kbd>alt</kbd>+<kbd>-</kbd>

### Navigate MediaLinks

* Both NavigateMediaLinks commands are limited to MediaLinks that are currently Visible, meaning you can use them without accidentally moving into the next slide

NavigateMediaLinks_Down ( open next MediaLink )
<kbd>ctrl</kbd>+<kbd>alt</kbd>+<kbd>=</kbd>

NavigateMediaLinks_Up ( open previous MediaLink )
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

Insert_Slide ( insert Slide divider )
<kbd>ctrl</kbd>+<kbd>super</kbd>+<kbd>alt</kbd>+<kbd>.</kbd>

Insert_MediaFile ( insert MediaLink + path )
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>super</kbd>+<kbd>.</kbd>

Insert_MediaLink ( insert MediaLink + wrapper )
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>.</kbd>

### MediaLink

Open_MediaLink
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>o</kbd>

Toggle_MediaLink ( enable/disable automatically opening MediaLinks on click )
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>alt</kbd>+<kbd>.</kbd>

### Slides

Align ( resizes all Slide titles to same length )
<kbd>ctrl</kbd>+<kbd>super</kbd>+<kbd>.</kbd>

## CUSTOMIZATION

Modifications available @ [SublimeSlides.sublime-settings](https://github.com/Enteleform/ST_SublimeSlides/blob/master/SublimeSlides.sublime-settings)

* Define Snippet Visual Styles
* Define MediaLink Applications & Their Associated Extensions
* Define Presentation FileTypes & Comment Characters ( required for any filetype you want to use SublimeSlides with )

## KNOWN LIMITATIONS

In order to get the most functionality out of SublimeSlides, read the comments @ [SublimeSlides.sublime-settings](https://github.com/Enteleform/ST_SublimeSlides/blob/master/SublimeSlides.sublime-settings)

## FEEDBACK

So far, SublimeSlides has only been tested with Windows & SublimeText 3.

This is my first release! Feel free to contact me at enteleform@gmail.com with any feedback!
