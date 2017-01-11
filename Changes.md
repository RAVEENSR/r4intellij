Version History
===============

## Changeshanges in v1.0*

Restarted devlopment by forking. This gives the following feature set
*   Lexer-based syntax highlighting
*   Parser
*   Interactive console
*   Builtin help
*   Package manager
*   Debugger


The following features were merged in from previous version of r4intellij
* More recent R logo




## Changeshanges in v0.12

*   New R icon
*   Fixed: parser fails to work for higher dimensional arrays #53
*   Fixed: functions declared with = don't show up in structure view #72
*   Allow for leading commas in functions invokations (e.g. `myFun(,5)`) which seem bad practice (use named arg

## Changeshanges in v0.10

*   Improved Intellij v15 compatibility

## Changeshanges in v0.9

*   Fixed PyCharm Support
*   (Experimental) Reformatter
*   Parser improvements

## Changeshanges in v0.9

*   Added R color setting page
*   Named vector support
*   Support for more magrittr operators
*   Added live-templates for dplyr
*   Improved send to R/terminal

## Changeshanges in v0.8.4

*   Added iTerm support for HongKee

## Changeshanges in v0.8.3

*   Added support for pipe operator from magrittr package

## Changeshanges in v0.8.2

*   Changed plugin definition to support also other Jetbrains products like PhpStorm, PyCharm, etc.

## Changeshanges in v0.8.1

*   Improved compatibility to Intellij IDEA 13

## Changeshanges in v0.8.2

*   Added support for more operators (like %+% or <<-

## Changeshanges in v0.8

*   Added option to keep focus in editor after submitting code to R

## Changeshanges in v0.7

*   Dramatically improved parser performance
*   Code evaluation bugfixes (macos)

## Changeshanges in v0.6

*   Highlight usages of functions and variables in file
*   Advanced navigation (structure view, go to declaration)
*   Code section folding
*   Code evaluation connectors for Windows (Rgui) and MacOS (R, R64 and Terminal)
*   Customizable code evaluation snippets
*   Auto-import of functions
*   Simple function help

## Changeshanges in v0.5

*   New shortcut action to call str() for the current word or selection (MacOS only)
*   Function body folding
*   More robust lexer
*   Finished (my first) parser --> allows for growing selection using "Select for word at caret" action
*   bug fixes

## Changeshanges in v0.4

*   Basic code completion
*   Better shortcuts for code evaluation (MacOS only)

## Changeshanges in version 0.3

*   Evaluate selection of current line in R (MacOS only)
*   Improved code highlighting
*   Added first live-templates

## Changeshanges in version 0.2* Initial release of the plugin. :-)

*   Syntax highlighting
*   Comment code blocks with usual shortcut ⌘/
*   Register .R as file type