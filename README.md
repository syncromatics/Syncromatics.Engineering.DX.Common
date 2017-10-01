# Common languge-agnostic documents for a consistent developer experience

This is a template containing developer experience documentation: README, a code of conduct, a contributor's guide, and a license. This is a quick way to ensure an open source project has enough information for those interested in it.

## Quickstart

[Install .NET Core](https://www.microsoft.com/net/core) then install this template:

```bash
dotnet new -i Syncromatics.Engineering.DX.Common
```

Use this template in your project's root directory:

```bash
dotnet new syncdx-common --projectName 'My Project' --githubOwner 'username' --githubRepo 'reponame' --contactEmail 'maintainer@example.com'
```

See what other parameters are supported in this template:

```bash
dotnet new syncdx-common -h
```

## Building

[![Travis](https://img.shields.io/travis/syncromatics/Syncromatics.Engineering.DX.Common.svg)]()
[![NuGet](https://img.shields.io/nuget/v/Syncromatics.Engineering.DX.Common.svg)]()
[![NuGet Pre Release](https://img.shields.io/nuget/vpre/Syncromatics.Engineering.DX.Common.svg)]()

1. Ensure you have [installed .NET Core](https://www.microsoft.com/net/core)
2. Ensure `nuget` is up to date with `nuget update -self`
3. Run `nuget pack Syncromatics.Engineering.DX.Common.nuspec` in the root directory

This will build a `Syncromatics.Engineering.DX.Common.0.0.0.nupkg` file that you can test locally by installing with the `dotnet new` command:

```bash
dotnet new -i Syncromatics.Engineering.DX.Common.0.0.0.nupkg
```

## Code of Conduct

We are committed to fostering an open and welcoming environment. Please read our [code of conduct](CODE_OF_CONDUCT.md) before participating in or contributing to this project.

## Contributing

We welcome contributions and collaboration on this project. Please read our [contributor's guide](CONTRIBUTING.md) to understand how best to work with us.

## License and Authors

[![Syncromatics Engineering logo](https://en.gravatar.com/userimage/100017782/89bdc96d68ad4b23998e3cdabdeb6e13.png?size=16) Syncromatics Engineering](https://github.com/syncromatics)

[![license](https://img.shields.io/github/license/syncromatics/Syncromatics.Engineering.DX.Common.svg)]()
[![GitHub contributors](https://img.shields.io/github/contributors/syncromatics/Syncromatics.Engineering.DX.Common.svg)]()

This software is made available by Syncromatics Engineering under the MIT license.