
# ST_SublimeSlides

Easily create slide presentations in Sublime Text with SublimeSlides

Also includes a customizable file launcher

## FEATURES

### Slides

* Divide your document with Slides
* Navigate through the document slide by slide ( any content not in the current slide is folded )

![SlideDemo](http://i.imgur.com/q02FrPm.gif?1)

### MediaLink

* Launch files during your presentation with MediaLinks
* MediaLinks can be launched automatically upon clicking, or with a hotkey
* List your MediaLink+Path at the beginning of the document, and access it anywhere else in the document
* Define applications & extensions @ SublimeSlides.sublime-settings

![MediaLinkDemo](http://i.imgur.com/0UxRYbf.gif?1)

### Snippets

* Slide dividers & MediaLinks are generated automatically via hotkey
* MediaLinks can be generated with or without path ( use with path to define MediaLink, use without path to launch MediaLink anywhere else in the document )

![SnippetDemo](http://i.imgur.com/RUvj93C.gif?1)

## USAGE

These are the included commands & keybindings


Insert_MediaFile ( insert medialink + path )  
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>super</kbd>+<kbd>period</kbd>

Insert_MediaLink ( insert medialink + wrapper )  
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>period</kbd>

Open_MediaLink  
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>o</kbd>

Toggle_MediaLink ( enable/disable automatically opening medialinks on click )  
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>alt</kbd>+<kbd>period</kbd>

Reset ( exit slideview & show full document )  
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>minus</kbd>

Zoom  ( zoom to selected slide - slide title line must be selected )  
<kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>equals</kbd>

NavigateDown ( show next slide )  
<kbd>ctrl</kbd>+<kbd>super</kbd>+<kbd>alt</kbd>+<kbd>equals</kbd>

NavigateUp ( show previous slide )  
<kbd>ctrl</kbd>+<kbd>super</kbd>+<kbd>alt</kbd>+<kbd>minus</kbd>

Insert_Title ( insert slide divider )  
<kbd>ctrl</kbd>+<kbd>super</kbd>+<kbd>alt</kbd>+<kbd>period</kbd>

Collapse ( remove endcaps from slide titles for easy editing )  
<kbd>super</kbd>+<kbd>alt</kbd>+<kbd>period</kbd>

Build ( restore endcaps to slide titles )  
<kbd>ctrl</kbd>+<kbd>super</kbd>+<kbd>period</kbd>
