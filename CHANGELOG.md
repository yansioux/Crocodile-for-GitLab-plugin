<!-- Keep a Changelog guide -> https://keepachangelog.com -->

# Crocodile for GitLab Changelog

## [2.2] - 22 September 2025
### Added
- Ability to create branches (all in one button Create tag/branch)
- Commit information tooltip for Create tag/branch dialog
- Ability to use the name of an existing tag/branch with automatic version incrementing 

### Fixed
- "Container Project@impl services was disposed" error when switching projects by closing one and opening another

## [2.1] - 10 September 2025
### Added
- Color correction for the font of Commit's dialog
- Anti-aliasing hint for the graphic of Stage component
- The size of the Stage panel has increased

## [2.0] - 05 September 2025
### Added
- PIPELINES!!! (That's why version 2 is here!)
- Mode switch button (V <--> P)
- More improvements and stability
### Fixed
- bugs of the previous 1 version

## [1.1.0] - 10 June 2025
### Added
- NEW FEATURE: Import variables from file!!!
### Fixed
- Refreshing variables by right click menu 'Reload'
- Selecting a Null environment after the environment creation->deletion procedure


## [1.0.12] - 3 June 2025
### Fixed
- Core algorithm for GitLab host & Project id definition
- Color of selected items in variable table
- Size for 'Create variable' & 'Add variable from collection' buttons
### Added
- Automatic hiding of sensitive data for the 'Collection of variables' window
### Changed
- Icon for 'Add variables to collection' button
- UI for variable's right click menu

## [1.0.11] - 29 May 2025
### Added
- Compatibility with upcoming IDEA 252.* release

## [1.0.10] - 26 May 2025
### Added
- Automatic hiding of sensitive data for variable values
### Fixed
- Appearance and text length of help balloon for variable search field
- Variable table flickering after update

## [1.0.9] - 14 May 2025
### Fixed
- Variable's table cell rendering
- EnvScope's chooser cell rendering
- Variable collection's table cell rendering
- Name of Delete environment action in main menu
### Changed
- Order of actions in main menu list
- Notification balloon showing time

## [1.0.8] - 12 May 2025
### Added
- Bracket autocomplete for search field
- Logic for excluding github.com server

## [1.0.7] - 11 May 2025
### Added
- IBM Plex Mono font for variable value field in Create / Edit variable dialog
### Fixed
- Create / Edit variable dialog's height insufficient due to arbitrary monospace font

## [1.0.6] - 09 May 2025
### Fixed
- Message for dialog

## [1.0.5] - 09 May 2025
### Added
- Extended search for variables
### Fixed
- Layout of environment scope menu items for the right-click popup window

## [1.0.4] - 08 May 2025
### Fixed
- Layout of environment scope menu items for the right-click popup window

## [1.0.3] - 08 May 2025
### Added
- Correct order of environments in chooser
### Fixed
- Recursive call to create variable when exception occurs

## [1.0.2] - 08 May 2025
### Added
- Link to help on configuring IDE password storage in some dialogs

## [1.0.1] - 08 May 2025
### Fixed
- Error updating variables after changing project
### Added
- Plugin stability with multiple open projects

## [1.0.0]
### Added
- Core service functions for the GitLab Rest API
- Variable managing logic
- Environments managing logic
- User interface elements (dialogs, ToolWindow, Balloons and so on)
- Plugin-specific UI elements (EnvScope's labels, variable description tooltips and so on)
- License
