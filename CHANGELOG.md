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