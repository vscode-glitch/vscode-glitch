# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.3] - 2019-08-07
### Added
- "Show Diagnostic Information" command: opens a read-only document with environment information to include in issue reports
- "Export Extension Logs" command: saves VS Code logs to a compressed archive to include in issue reports (with options for how much to include)

### Fixed
- Terminal text width not set/updated to width of terminal in UI
- Rewind fails silently on errors
- Uninformative error and bad state when reopening VS Code to a project that has been deleted or moved (now displays open project options)

## [0.1.2] - 2019-07-29
### Fixed
- VS Code crash on large or rapid input

## [0.1.1] - 2019-07-17
### Fixed
- Cache file notice not showing on Windows
- Folders with non-text files not loading
- Slow "open project" menu display after signing in

### Changed
- Automatically make Glitch the default formatter (and document in readme)

## [0.1.0] - 2019-07-09]
### Added
- Everything (initial release)
