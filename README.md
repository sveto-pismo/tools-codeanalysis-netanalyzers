
<center style="padding: 2rem">
    <img src="../tools-branding/assets/packageIcon.png" alt="SvetoPismo" width="128">
    <h1>SvetoPismo.Tools.CodeAnalysis.NetAnalyzers</h1>
</center>

A NuGet package that sets the MSBuild properties such as Authors, PackageIcon, PackageLicenseFile, PackageReadmeFile, Copyright, and puts assets for Package Icon, License, and Readme files.

## Installation

To install this package, use the NuGet Package Manager Console:

```powershell
PM> Install-Package SvetoPismo.Tools.Branding
```

Or you can search for "SvetoPismo.Tools.Branding" in the NuGet Package Manager UI and install it from there.

## Usage

After installing the package, the MSBuild properties will be set automatically. You can modify the properties by updating the values in your .csproj or .vbproj file.

For example, to set the Authors property, add the following to your .csproj or .vbproj file:

```xml
<PropertyGroup>
    <Authors>$(Authors);John Doe;Jane Smith</Authors>
</PropertyGroup>
```

## MSBuild Properties

This package sets the following MSBuild properties:

- Authors
- PackageIcon
- PackageLicenseFile
- PackageReadmeFile
- Copyright

You can modify these properties by updating your .csproj or .vbproj file as described in the Usage section.

## Assets

This package includes the following assets:

- A Package Icon: `assets/packageIcon.png`
- A License: `assets/LICENSE`
- A Readme: `README.md`

To access the assets, use the relative paths shown above.

## Contributing

If you find a bug or have a feature request, please create an issue in the GitHub repository.

To contribute code, fork the repository and submit a pull request. Please ensure that your code follows the project's coding standards and is thoroughly tested.

## License
This package is released under the Apache 2.0 License. See the [LICENSE](LICENSE) file for details.
