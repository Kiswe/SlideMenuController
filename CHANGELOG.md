# Changelog
All notable changes to this project will be documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

DateTime Format (UTC): `yyyy-mm-ddThh:mm:ssZ`

##### Allowed Subsections:
- Added for new features.
- Changed for changes in existing functionality.
- Deprecated for soon-to-be removed features.
- Removed for now removed features.
- Fixed for any bug fixes.
- Security in case of vulnerabilities.

## [Unreleased]
### Changed
- Internal: Hide opacityView when panel is closed and show when panel is
  open. This is a subtle change with little effect to the user but for internal
  purposes it means opacityView will not handle touch events when the left or
  right panels are closed.

### Fixed
- General: Fixed an issue where the shadow was not removed from the right panel
  when closed.

## [0.1.0] - 2023-03-08T17.39.55Z
### Added
- General: Initial Release
