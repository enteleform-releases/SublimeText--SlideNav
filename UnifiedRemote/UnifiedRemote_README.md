
#Setup

###Install UnifiedRemote on your mobile device & computer:  
http://www.unifiedremote.com/

###Install the preset @ UnifiedRemote:

Copy the "SublimeSlides" directory contained within the zip file to your UnifiedRemote custom remotes directory  

Unified Remote custom remotes directory @  
https://github.com/unifiedremote/Docs/blob/master/intro/whats-included.md

More Info @  
https://github.com/unifiedremote/Docs/blob/master/intro/getting-started.md

#Layout
```
┌────────────────────────────┐  ┌────────────────────────────┐
│ Switch Windows ( Alt+Tab ) │  │  Exit Current Application  │
└────────────────────────────┘  └────────────────────────────┘
┌────────────────────────────┐  ┌────────────────────────────┐
│          Zoom Out          │  │           Zoom In          │
└────────────────────────────┘  └────────────────────────────┘
┌────────────────────────────┐  ┌────────────────────────────┐
│       Previous Slide       │  │         Next Slide         │
└────────────────────────────┘  └────────────────────────────┘
┌────────────────────────────┐  ┌────────────────────────────┐
│     Previous MediaLink     │  │       Next MediaLink       │
└────────────────────────────┘  └────────────────────────────┘
```
#Key Bindings

All keybindings @ "remote.lua" are set up using default SublimeSlides hotkeys  

The following commands are set up for Windows & may require modification to work on non-Windows computers:  
```
exit   == Alt + F4
alttab == Alt + Tab
```

#Additional Feature

Also - on my personal copy of this, I have an additional button in the top row which:  

 • loads SublimeText whether it is running or not  
 • removes window borders  
 • sets the window size to full screen  

The button & it's function `sublimetext` are commented out in `layout.xml` & `remote.lua`  

I commented it out in the release because it is a custom AutoHotkey function & requires additional setup  

If you are interested in using the original function, I have included the AutoHotkey script @ `Launch_SublimeText.ahk`

