# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [2.25.0] / 2025-11-08
### Features
- Support `.NET Framework` and `.NET Core`.
- Update ILRepack to use `ricaun.ILRepack`.
- Update to HelixToolkit.Wpf to version `2.25.0`.
### Updated
- Update build CI/CD pipeline.
- Add `netcoreapp3.1` to use `HelixToolkit.Core.Wpf` reference.
- Change `net45` to `net462` to support `HelixToolkit.Wpf` version `2.25.0`.

## [2.23.0] / 2023-08-20
### Updated
- Update to [HelixToolkit.Wpf version 2.23.0](https://www.nuget.org/packages/HelixToolkit.Wpf/2.23.0)
### Changed
- Remove Revit reference in csproj
- Update to csproje to `net45`
- Test with compile with `netcoreapp3.1`

## [2.20.2] / 2022-03-03
### Changed
- Add AllowMultiple
- Remove Attribute

## [2.20.2] / 2022-02-23
### Fixed
- Add ILRepacker
### Changed
- Update ricaun.Nuke
- Problem with Attribute not found
- Add Build
- First Release

[2.25.0]: ../../compare/2.23.0...2.25.0
[2.23.0]: ../../compare/2.20.2...2.23.0
[2.20.2]: ../../compare/2.20.2