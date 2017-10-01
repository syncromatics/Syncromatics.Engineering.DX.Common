# $projectName

Write a single-paragraph explanation of this project. It should describe what the software does and why it exists. Finish the paragraph with a compelling reason to use the software.

_Consider a spiffy animated GIF or screenshot here_

## Quickstart

This section should get the reader into using the software as quickly as possible. Favor examples over exposistion. For example:

Add the `ThingClient` package to your project:

```bash
dotnet add package ThingClient
```

Then use it to do a thing:

```csharp
var client = new ThingClient.Client();
var result = await client.DoThing();
if (result.HasThing)
{
    Console.WriteLine($"The result is {result.Message}");
}
```

If available, add a link to other documentation for this software. Avoid documenting the entire project in this README.

## Building

_Remove any shields below that do not apply_

[![Travis](https://img.shields.io/travis/$githubOwner/$githubRepo.svg)]()
[![Docker Build Status](https://img.shields.io/docker/build/$dockerOwner/$dockerRepo.svg)]()
[![npm](https://img.shields.io/npm/v/$npmPackage.svg)]()
[![NuGet](https://img.shields.io/nuget/v/$nugetPackage.svg)]()
[![NuGet Pre Release](https://img.shields.io/nuget/vpre/$nugetPackage.svg)]()

Write a few sentences on how to set up a build environment for this software. These instructions should include prerequisites like required tools, frameworks, and libraries that the reader will need to successfully build this software.

## Code of Conduct

We are committed to fostering an open and welcoming environment. Please read our [code of conduct](CODE_OF_CONDUCT.md) before participating in or contributing to this project.

## Contributing

We welcome contributions and collaboration on this project. Please read our [contributor's guide](CONTRIBUTING.md) to understand how best to work with us.

## License and Authors

[![license](https://img.shields.io/github/license/$githubOwner/$githubRepo.svg)]()
[![GitHub contributors](https://img.shields.io/github/contributors/$githubOwner/$githubRepo.svg)]()

This software is made available by $authorName under the MIT license.