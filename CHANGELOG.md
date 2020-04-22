# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [0.2.1] 2020-04-22

### Fixed

- Use PowerShellBuild v0.5.1 with psake Test task modifications for how modules are loaded during testing.

### Changed

- Do not load project module from within `Help.tests.ps1` as they are now loaded correctly in PowerShellBuild v0.5.1.
- Use AppVeyor worker image that supports PowerShell Version 7

## [0.2.0] 2019-11-09

### Added

- **#11** - Added support for GitLab CI in module template (via [@sk82jack](https://github.com/sk82jack))
- Added support for GitHub Actions in module template

### Changed

- Bumped versions of dependent modules [Pester](https://github.com/pester/Pester), [BuildHelpers](https://github.com/RamblingCookieMonster/BuildHelpers), and [PowerShellBuild](https://github.com/psake/PowerShellBuild)

### Fixed

- **#11** - Fixed casing of `tests` folder and for `public/private` folders in psm1 (via [@sk82jack](https://github.com/sk82jack))

## [0.1.1] 2019-04-23

### Fixed

- Azure Pipelines yaml file wasn't being output if it was chosen during Plaster execution

## [0.1.0] 2019-04-23

### Added

- Initial release
