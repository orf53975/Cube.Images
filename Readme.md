Cube.Images
====

[![NuGet](https://img.shields.io/nuget/v/Cube.Images.svg)](https://www.nuget.org/packages/Cube.Images/)
[![AppVeyor](https://ci.appveyor.com/api/projects/status/ffsk5mc9i8o9iy72?svg=true)](https://ci.appveyor.com/project/clown/cube-images)
[![Codecov](https://codecov.io/gh/cube-soft/Cube.Images/branch/master/graph/badge.svg)](https://codecov.io/gh/cube-soft/Cube.Images)

Cube.Images is an image library.
The library is available for .NET Framework 3.5, 4.5 or more.

## Installation

You can install using NuGet like this:

    PM> Install-Package Cube.Images

Or select it from the NuGet packages UI on Visual Studio.

## Dependencies

* [Cube.Core](https://github.com/cube-soft/Cube.Core)
* [Cube.FileSystem](https://github.com/cube-soft/Cube.FileSystem)

## Contributing

1. Fork [Cube.Images](https://github.com/cube-soft/Cube.Images/fork) repository.
2. Create a feature branch from the [stable](https://github.com/cube-soft/Cube.Images/tree/stable) branch (git checkout -b my-new-feature origin/stable). The [master](https://github.com/cube-soft/Cube.Images/tree/master) branch may refer some pre-released NuGet packages. See [AppVeyor.yml](https://github.com/cube-soft/Cube.Images/blob/master/AppVeyor.yml) if you want to build and commit in the master branch.
3. Commit your changes.
4. Rebase your local changes against the stable (or master) branch.
5. Run test suite with the [NUnit](https://nunit.org/) console or the Visual Studio (NUnit 3 test adapter) and confirm that it passes.
6. Create new Pull Request.

## License

Copyright © 2010 [CubeSoft, Inc.](https://www.cube-soft.jp/)
The project is licensed under the [Apache 2.0](https://github.com/cube-soft/Cube.Images/blob/master/License.txt).