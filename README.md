# Tab Kit 2nd Edition
[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/tabkit/tabkit2?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

The original [Tab Kit(TK)](https://addons.mozilla.org/en-us/firefox/addon/tab-kit/) is an extension of Firefox that many people are using.  
It was last updated September 26, 2010, and the author has been silent after that.  
The most updated version (0.6) is not compatible with FF4+, since FF3->4 has a HUGE change especially in tab bar DOM structure.

This project aims to change modify the original TK to make it FF4+ compatible (and drop the support for pre-FF4).  
The name for the new(not quite) extension is *Tab Kit 2nd Edition*(You can still call it *Tab Kit 2* or *TK2* for short)

**Classic Theme Restorer is required!! See section `Dependent Extensions` below**


## Description from original Tab Kit (modified)
Tab Kit makes tabs more efficient for power users, allowing a wide variety of tweaks, all of which are optional, notably:

- Group tabs, by domain or opener (parent) tab, manually or automatically
- Vertical tab tree (with splitter), like Tree Style Tab
- Multi-row tabs
- Sort tabs, by address, last loaded, last viewed, order of creation, origin or title
- Control new tab position and close order
- Easily duplicate tabs and groups and copy/move them between windows by dragging
- Scrollwheel tab switch (Extracted to [Tab Kit - Mouse Gestures](https://github.com/tabkit/mouse-gestures))
- 'Mouse rocker' to go back/forward in history (Extracted to [Tab Kit - Mouse Gestures](https://github.com/tabkit/mouse-gestures))
- Highlight unread tabs (and emphasise current tab) (Extracted to [Tab Kit - Tab Highlighter](https://github.com/tabkit/tab-highlighter))
- Scrollbar instead of scroll arrows in over-long Bookmarks and All Tabs popups
- Open Selected Links feature
- Switch tabs on hover (Extracted to [Tab Kit - Mouse Gestures](https://github.com/tabkit/mouse-gestures))
- Options for urls, searches and/or bookmarks to open in new tabs by default


## Dependent Extensions

### Classic Theme Restorer (since Firefox `29.0`)
You should install it **BEFORE** installing this extension at https://addons.mozilla.org/en-US/firefox/addon/classicthemerestorer/  
Required options for proper style: (extracted from `Classic Theme Restorer` `1.2.3`, please kindly notify me if they have changed)
- Select `Tabs not on top - set [tabsontop=false]` in `Tabs` page: fix the vertical tabbar direction  
- Uncheck `Use Firefox titlebar instead of OS titlebar` in `Firefix button` page: fix the totally unusable layout and strange click behaviour  


## Extension since `0.12.0`
Only support Firefox 31 ESR  
(Firefox of other versions can still install the extension, but issues for those will be ignored)


## Extension since `0.10.0`
Some features are extracted into other extensions (which can be used separately):
- Some coloring features extracted into [Tab Kit - Tab Highlighter](https://github.com/tabkit/tab-highlighter)
- Some mouse gesture features extracted into [Tab Kit - Mouse Gestures](https://github.com/tabkit/mouse-gestures)


## Download / Installation
- [Mozilla Add-ons](https://addons.mozilla.org/en-US/firefox/addon/tabkit-2nd-edition/)  


## Issue
- [Github (here)](https://github.com/tabkit/tabkit2/issues)  
I have moved a few issues from Google Code, move more if you think it's necessary


## Changes
See https://github.com/tabkit/tabkit2/blob/master/CHANGELOG.md


## Tab Kit Series Extensions
- [Tab Kit 2nd Edition](https://github.com/tabkit/tabkit2)
- [Tab Kit - Tab Highlighter](https://github.com/tabkit/tab-highlighter)
- [Tab Kit - Mouse Gestures](https://github.com/tabkit/mouse-gestures)


## News & Discussion
- [Google Group (For more general discussion)](http://groups.google.com/group/tabkit-2nd-edition)


## Project Helper Needed!
If you want some feature added, then it might be faster to do it yourself! :P  
I am working as Web Developer and don't really have time to develop Tab Kit :d


## Collaboration
Since we are on GitHub  
Just fork, change and send pull request  
I will check frequently (since I also use GitHub at work)

## Download from Mozilla Addon Site if possible  
The one on their site is reviewed  
But if you don't want to wait, then use the Custom download one :P


## Compatibility with other extensions
- Firebug: Incompatible  
(But it seems OK since Fx10 o_0)


## Compatibility with new features in Fx4+
- TabsOnTop: Not allowed by Tab Kit, unless you change it in options
- App/Pin Tabs: Use it at your own risk, no support provided
- Tab Groups: Not allowed by Tab Kit, unless you change it in options


### False incompatibility with newer Firefox
Summary:  
If newer Firefox say it is incompatible, install one of the following:  
- https://addons.mozilla.org/en-US/firefox/addon/add-on-compatibility-reporter/
- https://addons.mozilla.org/en-us/firefox/addon/checkcompatibility/

But it should not be a problem since Fx 12


## License

Tab Kit 2nd Edition(Tab Kit 2 for short)

Copyright (c) 2011-2017 Leung Ho Kuen <pikachuexe@gmail.com>

This file is part of Tab Kit 2.
Tab Kit is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

Tab Kit 2 is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA.
