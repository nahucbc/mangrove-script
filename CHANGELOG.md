# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.3.0] - 2024-9-5

### Removed

- Removed dot, comma, colon, double colon for clarify in the syntax
- Removed parentheses for clarify in the syntax
- Removed square brackets for clarify in the syntax
- Removed single quote and double quote for clarify in the syntax
- Removed term from expression

### Fixed

- Fixed number range format in EBNF
- Fixed incorrect grammar for if-else and while
- Fixed comma to literal
- Fixed double colon to literal
- Fixed missing block
- Fixed missing semicolon

### Added

- Added missings brackets
- Added lexer.rs
- Added comparison ops and clean syntax
- Added basic language constructs and utilities, cleaned EBNF and restructured

### Changed

- Changed .gitignore
- Changed quotes, simplify the rule
- Changed key brackets to block in statments to simplify and clarify syntax
- Changed arithmetic syntax
- Changed expression and statement, replaced commas with pipes for clean syntax and clarify
- Changed for clean

## [0.2.0] - 2024-1-10 - 6089b9c

### Added

- Added support.md
- Added readme.md in datapack, explain why to use the datapack.
- Added grammar.ebnf

### Changed

- Changed readme.md, update to v0.2.0
- Changed .gitignore, include Cargo.lock
- Changed changelog.md, updated this file
- Changed grammar.ebnf, created first version of the lenguage
- Changed support.md, datapack support details and changelog changes

## [0.1.0] - 2023-11-27 - e70fd0d

### Fix

- Title in readme.md

### Set up

- Initialized cargo

## [0.0.1] - 2023-11-27 - cb9356d

### Added

- Badges in README.md

- .gitignore
- CHANGELOG.md
- LICENSE
- README.md
