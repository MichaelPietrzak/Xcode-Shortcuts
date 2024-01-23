# Xcode/Swift - Shortcuts
Xcode and Swift shortcuts noted to speed up iOS Development.


<br />

## Table of contents

- [Keyboard keys Cheatsheet](#keyboard-keys-cheatsheet)
- [Navigation - Workspace](#navigation---workspace)
- [Code Formatting](#code-formatting)
- [Debugging](#debugging)
- [Building](#building)
- [Simulator](#simulator)
- [Adding markers to the jump bar](#adding-markers-to-the-jump-bar)
- [MacOS Finder Shortcuts](#macos-finder-shortcuts)
- [Xcode Source control symbols status](#xcode-source-control-symbols-status)
- [Debugging - Setting breakpoints](#debugging---setting-breakpoints)

<br />

## Keyboard keys Cheatsheet

<br />

Command: ⌘\
Shift: ⇧\
Option/Alt: ⌥\
Control: ⌃\
Left/Right Arrow Keys: ⇠⇢\
Up/Down Arrow Keys: ⇡⇣    
Escape: ⎋\
Tab: ⇥\
Return : ⏎

<br />

## Navigation - Workspace

<br />

Show quick help (Declaration): ⌥ + Touchpad Click

Xcode’s jump bar: ⌃  + 6

Documenting code Xcode: ⌘ + ⌥ + /

Access Developer Documentation Xcode: ⌘ + ⇧ + 0

Hide / Show Navigation Area: ⌘ + 0

Hide / Show Debugging Area: ⌘ + ⇧ + Y

Show Activity Console Area: ⌘ + ⇧ + C

Hide / Show Utility Area: ⌘ + ⌥ + 0

Split screen / open Assistant Editor in the Editor Area: ⌘ + ⌥ + ⏎

Opens a new tab above the navigator, editor & utility area: ⌘ + T

Close the current tab: ⌘ + W

Switching Tabs: ⇧ + ⌘ + }

Show / Hide Minimap: ⌃ + ⇧ + ⌘ + M

Show Library of code snippets, assets etc : ⇧ + ⌘ + L

Show Document Items: ⌘ + 6

Quick Open: ⇧ + ⌘ + 0

Highlight File in Project Navigator: ⇧ + ⌘ + J

Left panel tabs switch: ⌘ + (1–9)

<span style= "Color: red"> CUSTOM SHORTCUTS: </span> <br>
<span style= "Color: red"> Navigators -> Project: </span> ⌘ + F17 <br>
<span style= "Color: red"> Navigators -> Source Controls: </span> ⌘ + F18 <br>
<span style= "Color: red"> Navigators -> Symbols: </span> ⌘ + F19 <br>

Open the Issue Navigator: ⌘ + 5

Right panel tabs switch: ⌘ +⌥ + 1-6

Search for lines of text in your files: ⌘ + ⇧ + F

Show / Hide Preview: ⌥ + ⌘ + ⏎

Show / Hide Assistant: ⌃ + ⌥ + ⌘ + ⏎

Show / Hide Code Review: ⌥ + ⇧ + ⌘ + ⏎

Zoom out (Editor Menu for Interface Builder - Storyboard): ⌃ + ⌘ + -

Zoom 100% (Editor Menu for Interface Builder - Storyboard): ⌃ + ⌘ + =


<br />
<br />

## Code Formatting

<br />

Jump to Definition: ⌃ + ⌘ + J

Go Back: ⌃ + ⌘ + ⏎

Go To previous or Next file: ⌘ + ⌃ + left/right

List out file functions: ⌃ + 6

Edit All in Scope: ⌃ + ⌘ + E

Refactor -> Rename: ⌃ + ⌘ + `

Delete line: ⌃ + K

Re-Indent the whole function: ⌃ + I

Confirms the auto-completion suggestion: ⇥ OR ⌃ + /

Highlight a line (with cursor at the end):  ⌃ + ⇧ + A

Jump to beginning of the line: ⌃ + A

Comment or Uncomment: ⌘ + /

Hides / expands a class or method body:⌥ + ⌘ + ⇢ OR ⌥ + ⌘ + ⇠

Auto documentation: ⌘ +⌥ + /

Jump to a line: ⌘ + L

Copy/duplicate:    ⌥ + drag item with left mouse click


<br />
<br />

## Debugging

<br />

Add and Remove breakpoints: ⌘ + \

Disable / Enable all breakpoints: ⌘ + Y

<br />
<br />


##  Building

<br />

Build Project: ⌘ + B

Run & Build Project if necessary: ⌘ + R

Stop the current build/run/testing: ⌘ + .

Run tests & Build if necessary: ⌘ + U

Clean: ⌘ + K

Clean All files and build folder: ⇧ + ⌘ + K

Profile (Instruments): ⌘ + I

Choose scheme: ⌃ + 0

Choose Destination: ⌃ + ⇧ + 0

Re-run the last run tests: ⇧ + ⌘ + ⌥ + G

<br />
<br />

## Simulator

<br />

Copy current screen: ⌃ + ⌘ + C

Take Screenshot: ⌘ + S

Go to Home: ⇧ + ⌘ + H

Shake Gesture: ⌃ + ⌘ +  Z

Toggle software keyboard: ⌘ + K

<br />
<br />

## Adding markers to the jump bar

<br />

```
//  TODO: This isn’t finished yet

//  FIXME: This code is awful.

//  MARK: UITableViewDataSource methods
```

<br />
<br />

## MacOS Finder Shortcuts

<br />

Go to Folder: ⇧ + ⌘ + G

<br />
<br />

## Xcode Source control symbols status

<br />

M: Locally modified file

U: Updated in repository

A: Locally added

D: Locally deleted

I: Ignored

R: Replaced in the repository

-: The contents of the folder have mixed status: display the contents to see individual status

?: Not under source control

<br />
<br />

## Debugging - Setting breakpoints

<br />

Continue: Resumes code execution until the next breakpoint is reached.

Step over: Executes the selected line and pauses execution on the next line.

Step into: If clicked on a line with a function call, advances to the first line of the function, then pauses execution again.

Step out: Executes all remaining lines in the function call and pauses execution on the line after the function.