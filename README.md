# ricaun.HelixToolkit.Wpf

[![Visual Studio 2022](https://img.shields.io/badge/Visual%20Studio-2022-blue)](https://github.com/ricaun-io/ricaun.HelixToolkit.Wpf)
[![Nuke](https://img.shields.io/badge/Nuke-Build-blue)](https://nuke.build/)
[![Build](https://github.com/ricaun-io/ricaun.HelixToolkit.Wpf/actions/workflows/Build.yml/badge.svg)](https://github.com/ricaun-io/ricaun.HelixToolkit.Wpf/actions)
[![Release](https://img.shields.io/nuget/v/ricaun.HelixToolkit.Wpf?logo=nuget&label=release&color=blue)](https://www.nuget.org/packages/ricaun.HelixToolkit.Wpf)

This project is a `ILRepack` of the [HelixToolkit.Wpf](https://www.nuget.org/packages/HelixToolkit.Wpf/) and [HelixToolkit.Core.Wpf](https://www.nuget.org/packages/HelixToolkit.Core.Wpf/) package.

## Installation

Install the package using the `NuGet` package manager or using `PackageReference`.

```xml
<PackageReference Include="ricaun.HelixToolkit.Wpf" Version="*" />
```

## ILRepack

This project uses the [ricaun.ILRepack](https://www.nuget.org/packages/ricaun.ILRepack/) to merge the original assemblies into the `ricaun.HelixToolkit.Wpf` assembly.

The main reason for this is to remove the dependency on the `HelixToolkit` assemblies to avoid conflicts with other versions of the `HelixToolkit` assemblies in the same application.

The .NET Framework version uses the `HelixToolkit.Wpf` reference and the .NET Core version uses the `HelixToolkit.Core.Wpf` reference.

## Release

* [Latest release](https://github.com/ricaun-io/ricaun.HelixToolkit.Wpf/releases/latest)

## License

This project is [licensed](LICENSE) under the [MIT License](https://en.wikipedia.org/wiki/MIT_License).

---

Do you like this project? Please [star this project on GitHub](https://github.com/ricaun-io/ricaun.HelixToolkit.Wpf/stargazers)!