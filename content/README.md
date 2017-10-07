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

[![Travis](https://img.shields.io/travis/$githubOwner/$githubRepo.svg)](https://travis-ci.org/$githubOwner/$githubRepo)
[![Docker Build Status](https://img.shields.io/docker/build/$dockerOwner/$dockerRepo.svg)](https://hub.docker.com/r/$dockerOwner/$dockerRepo/)
[![npm](https://img.shields.io/npm/v/$npmPackage.svg)](https://www.npmjs.com/package/$npmPackage)
[![NuGet](https://img.shields.io/nuget/v/$nugetPackage.svg)](https://www.nuget.org/packages/$nugetPackage/)
[![NuGet Pre Release](https://img.shields.io/nuget/vpre/$nugetPackage.svg)](https://www.nuget.org/packages/$nugetPackage/)

Write a few sentences on how to set up a build environment for this software. These instructions should include prerequisites like required tools, frameworks, and libraries that the reader will need to successfully build this software.

## Code of Conduct

We are committed to fostering an open and welcoming environment. Please read our [code of conduct](CODE_OF_CONDUCT.md) before participating in or contributing to this project.

## Contributing

We welcome contributions and collaboration on this project. Please read our [contributor's guide](CONTRIBUTING.md) to understand how best to work with us.

## License and Authors

[![$authorName logo]($authorLogo) $authorName]($authorUrl)

[![license](https://img.shields.io/github/license/$githubOwner/$githubRepo.svg)](https://github.com/$githubOwner/$githubRepo/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/$githubOwner/$githubRepo.svg)](https://github.com/$githubOwner/$githubRepo/graphs/contributors)

This software is made available by $authorName under the MIT license.