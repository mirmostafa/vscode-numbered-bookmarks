## [7.0.0] - 2020-02-07
### Added
- Support `workbench.colorCustomizations` (issue [#61](https://github.com/alefragnani/vscode-numbered-bookmarks/issues/61))

### Internal
- Support VS Code package split
- Use `vscode-ext-decoration` package

## [6.2.1] - 2019-05-27
### Fixed
- Security Alert: tar

## [6.2.0] - 2019-03-25
### Added
- Improvements to README, describing commands and shortcuts (issue [#52](https://github.com/alefragnani/vscode-numbered-bookmarks/issues/52))
- Improvements to README, describing shortcut conflicts for MacOS users (issue [#40](https://github.com/alefragnani/vscode-numbered-bookmarks/issues/40))

### Fixed
- Selection issue when cutting text (issue [#48](https://github.com/alefragnani/vscode-numbered-bookmarks/issues/48))

## [6.1.1] - 2019-03-15
### Fixed
- What's New page broken in VS Code 1.32 due to CSS API changes

## [6.1.0] - 2018-12-17
### Added
- New settings to choose gutter icon colors (icon fill and number) (Thanks to @vasilev-alex [PR #45](https://github.com/alefragnani/vscode-numbered-bookmarks/pull/45))

## [6.0.0] - 2018-11-26
### Added
- What's New

## [5.2.0] - 2018-09-14
### Added
- New Setting to choose background color of bookmarked lines (Thanks to @ibraimgm [PR #44](https://github.com/alefragnani/vscode-numbered-bookmarks/pull/44))
- New Version Numbering based on `semver`

## [0.12.0 - 5.1.0] - 2018-09-14
### Added
- Patreon button

## [0.11.1 - 5.0.1] - 2018-03-09
### Fixed
- Error activating extension without workspace (folder) open (issue [#35](https://github.com/alefragnani/vscode-numbered-bookmarks/issues/35))

## [0.11.0 - 5.0.0] - 2017-11-13
### Added
- Multi-root support (issue [#30](https://github.com/alefragnani/vscode-numbered-bookmarks/issues/30))

## [0.10.0 - 4.0.0] - 2017-05-27
### Changed
- **TypeScript** and **VS Code engine** updated
- Source code moved to `src` folder
- Enabled **TSLint**
- Source code organization

### Fixed
- Error opening files outside the project in `List from All Files`  (issue [#26](https://github.com/alefragnani/vscode-numbered-bookmarks/issues/26))
- `List from All Files` command not working since VS Code 1.12 (issue [#25](https://github.com/alefragnani/vscode-numbered-bookmarks/issues/25))

## [0.9.1 - 3.1.1] - 2017-05-11
### Fixed
- Bookmarks disapearing/incorrectly moving when new lines are added above (issue [#23](https://github.com/alefragnani/vscode-numbered-bookmarks/issues/23))

## [0.9.0 - 3.1.0] - 2017-04-23
### Added
- New Setting to choose how bookmarks _Navigate Through All Files_ (issue [#6](https://github.com/alefragnani/vscode-numbered-bookmarks/issues/6))

## [0.8.0 - 3.0.0] - 2017-04-02
### Added
- New Setting to allow Bookmarks to be saved in the project (inside `.vscode` folder)

### Changed
- Bookmarks are now _always_ Sticky

## [0.7.0 - 2.4.0] - 2017-03-06
### Added
- Avoid unnecessary scrolling (issue [#18](https://github.com/alefragnani/vscode-numbered-bookmarks/issues/18))

## [0.6.0 - 2.3.0] - 2017-01-03
### Added
- Toggle Bookmark 0 and Jump to Bookmark 0 (PR [#16](https://github.com/alefragnani/vscode-numbered-bookmarks/pull/16) - kudos to @DeegC)

## [0.5.2 - 2.2.2] - 2016-12-03
### Added
- Tags added for Marketplace presentation

## [0.5.1 - 2.2.1] - 2016-12-03
### Fixed
- Bookmarks becomes invalid when documents are modified outside VSCode

## [0.5.0 - 2.2.0] - 2016-09-26
### Added
- New Command `List from all files`
- New Command `Clear from all files`

## [0.4.2 - 2.1.2] - 2016-09-19
### Fixed
- Bookmarks missing in _Insider release 1.6.0_ (issue [#11](https://github.com/alefragnani/vscode-numbered-bookmarks/issues/11))

## [0.4.1 - 2.1.1] - 2016-09-03
### Fixed
- Remove extension activation log (issue [#10](https://github.com/alefragnani/vscode-numbered-bookmarks/issues/10))

## [0.4.0 - 2.1.0] - 2016-06-17
### Added
- New Setting to Sticky Bookmarks 

## [0.3.0 - 2.0.0] - 2016-03-08
### Added
- Bookmarks are also rendered in the overview ruler

### Fixed
- Incompatibility with **Code February Release** 0.10.10 (issue [#4](https://github.com/alefragnani/vscode-numbered-bookmarks/issues/4))

## [0.2.0 - 1.0.0] - 2016-02-15
### Added
- New Command `List`

## [0.1.0 - 0.9.0] - 2016-02-06

* Initial release
