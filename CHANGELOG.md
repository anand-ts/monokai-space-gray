# Change Log

All notable changes to the "demo-theme" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [0.0.1]

- Initial release

## [0.0.2]

- Removed almost all italics
- Added method/function call colors

## [0.0.3]

- Added meta function call color

## [0.0.4]

- Changed bunch of stuff (mostly highlights and consistent coloring)

## [0.0.5]

- Consistent coloring now, #1f1f1f on all borders
- meta.function-call.generic is now green, previously blue
- Changed the debugging status bar changed to gray (#363636)
- Other general cleanups

## [0.1.0]

- Official first release to VSCode Marketplace!

## [0.1.1]

- Fixed thumbnail images on GitHub repo and VSCode Marketplace

## [0.1.2]

- Changed comments foreground color to #E6DB74 for better visibility
- Corrected publisher and version number in JSON theme file (hotfix)

## [0.1.3]

- Added border and highlight colors

## [0.1.4]

- Active line numbers and indent lines dynamically change
- Changed debugging status bar to white
- HOTFIX [0.1.5]: Selection highlights were not visible while StrongHighlight was active because it was not transparent

## [1.5.1]

- VERSION FORMAT CHANGE: Changed version number format to align with major, minor, and hotfix updares (sorry for the confusion!)
- HOTFIX: editor.findMatchHighlightBackground fixed to transparent, so the matches are not turned into blocks of background
- Inherited class italics are removed
- Cursor line highlight is removed

## [1.6.0]

- Hover highlight background is reverted to gray #363636
- Selection highlight is changed to transparent
- Bracket match color is now ansiBrightRed #f92672
- Steamlined overall color scheme with Visual Studio Code Default Monokai scheme for consistency
- Semantic highlighting is enabled! (finally)

## [1.7.0]

- Replaced all #262626 with #363636
- editor.Widget (search/find bar) now has consistent coloring
- Panel and terminal background is now all black #000000
- Added borders on activity bar, side bar, status bar, title bar, and panel bar

## [1.7.1]

- Added split view, group header, tab (between files) border
- Unfocused tabs foreground is white (does not gray out)

## [1.7.2]

- BUGFIX: Command Pallette hover and cursos selection is now bright and readable (previously was overlapping)
- Widget and scroll bar shadows are now black! (for clarity purposes)
- Hovering highlight is now brighter
- Line highlight is re-enabled
- Widget background is same as editor background

## [1.7.3]

- CHANGED: editorBracketMatch is now redish color (#fe413f)
- Added tab hover background highlight
- Split view and inactive tabs now correctly dim in color
- Inactive window title bar also dims in color

## [1.7.4]

- FIXED: "editorSuggestWidget.selectedBackground" now properly has selected background color (previously was overlapping with the suggest widget drowdown menu color, such as trying to access methods using dot notation)
- FIXED: "tab.hoverBorder" now properly shows the white outline below tab when hovering over (previously was overriding)

## [1.7.5]

- FIXED: "extensionButton.prominentBackground" now has white and black colors for more clarity. For example: sidebar buttons are more clear and visible

## [1.7.6]
- FIXED: "extensionButton.prominentBackground" and "extensionButton.prominentForeground" colors are now fixed (dropdown button)
- FIXED: added "button.secondaryForeground": "#000000", "button.secondaryBackground": "#ffffff" for consistency across all buttons
- CHANGED: Disabled changing colors while hovering a button

## [1.7.6]
- CHANGED: Turned off semantic highlighting 

## [1.7.7 - 1.7.8]
- FIXED: list, tree, and button hovers and selections are now consistent
- CHANGED: changed activity bar badge color to white, previosuly it was showing default blue
- CHANGED: turn off button border because it was making the buttons large
- CHANGED: changed default blue #007acc to #0099ff for a brighter appearance
- CHANGED: activity bar notifications are now white instead of blue
- FIXED: "extensionButton.prominentBackground" now has white and black colors for more clarity. For example: sidebar buttons are more clear and visible
## [1.7.9]
- REVERTED: turned on semantic highlighting

## [1.7.10]
- REVERTED: turned off semantic highlighting
- The reason why is on the method header, the return type is green instead of blue. Green stands for class, not for return type

## [1.7.11]
- FIXED: Turned on the "scope": "meta.function-call.generic" for function calls. Calling functions with a dot notation, the function color was not properly shown (sorry, accidentally disabled it)
- CHANGED: Terminal split border is now #363636 instead of #1f1f1f which is consistent with all border colors
- UPDATED: Terminal ansi colors are now consistent with VSCode's monokai colors

## [1.7.12]
- CHANGED: Semantic highlighting is now on due to issues with other files, such as Angular modules not correctly highlighting. However, it should be noted that there should be a way to find a workaround for choosing only return type and class of a method and other modules. Will look into it later in the future
- CHANGED: Status bar debugging color is now gray instead of white, and hovering looks proper
- CHANGED: Activity bar badge is now gray instead of white, looks flush with status bar

## [1.7.13]
- UPDATE: Theme now support Jupyter Notebooks!

## [1.8]
- UPDATE: Overhauled how the theme looks. Editor color now changed from #1f1f1f to #1c1c1c. Menu UI color now changed from #363636 to #111111, and #636363 to #808080.
- UPDATE: Monokai color scheme comments changed from #88846f (yellow-ish color) to #808080.
- REMOVED: Unnecessary lines of code, defaults everything.
- REMOVED: Removed shadows, made them transparent (#00000000)

## [1.8.1]
- FIXED: "editor.lineHighlightBackground" and "editor.selectionBackground" is now properly set to #f2f2f236. Previously, it was the same color as the comments, which overlapped when selected and disappeared.
- FIXED: borders now properly show around boxes, selections, and drop down menus (#808080)

## [1.9]
- FIXED: Dropdown, suggest widget, hover widget, tab, status bar, hover selections and line highlights are now more brighter with #f2f2f218.
- FIXED: Active selections are now all consistent with #f2f2f218.
- FIXED: Hover and selections highlights are now all consistent with #f2f2f236, previously it was too white and was overlapping comments' color making it disappear.
- FIXED: Split view border is now brighter (#808080).
- FIXED: Notifications are now colored consistent with the theme.
- FIXED: Settings is now color consistent with the theme.
- FIXED: Peek view editor now has more clarity.
- CHANGED: Changed color from #f2f2f216 to #f2f2f218.
- MISC: Overall consistent coloring across the UI.

## [1.9.1]
- FIXED: Current selected find match now is brighter than the rest (sorry, this was an oversight).
- CHANGED: Indent guides are now #f2f2f236. It was too bright with #808080.

## [1.9.2]
- FIXED: Find/Replace buttons had no indication when it was turned on or off, now there is a border around if it is turned on.
- CHANGED: Comments are changed to #E6DB74 (same yellow as string) because the highlighting from find and selection was overpowering the faint gray, making it disappear.

## [1.9.3]
- FIXED: Find/replace, selection, hover, and line number highlights now works properly with respective highlight colors.
- FIXED: rangeHighlightBackground/Border is now transparent and no longer overlaps and removes the indent guide lines.
- CHANGED: Comments reverted back to lighter shade of gray #acacac (realized yellow looks ugly). 

## [1.9.4]
- CHANGED: Find/replace highlight now is red, just like bracket matching. I realized gray color is too faint to distinguish.
- CHANGED: Gutter line highlight/number more consistent colors, rangeHighlightBackground set to transparent, and comments are #808080.

## [1.9.5]
- CHANGED: Line highlights are changed and has more clarity (also gutter line highlight).
- CHANGED: Bracket match highlight is now blue (#0000ff) instead of red (#ff0000) (it was overlapping with brackets that have red colors).

## [1.9.6]
- CHANGED: Selection background (selection inside input fields such as cmd+f) also has the same line highlight color (sorry this was an oversight of 1.9.5).

## [1.9.7]
- CHANGED: Find match background changed to blue.
- CHANGED: Split view border is now white.
- CHANGED: Settings header foreground and modified settings border to white.
- CHANGED: "tokenColors" set all #f8f8f2 to #ffffff.

## [1.9.8]
- FIXED: Editor word, range, hover, and selection highlights are now consistent.

## [1.9.9]
- FIXED: Jupyter notebooks now have better clarity.

## [1.10]
- NEW: Logo has been updated!
- CHANGED: ReadMe file.