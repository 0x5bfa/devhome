<p align="center">
  <a href="https://aka.ms/devhome">
    <img src="https://github.com/microsoft/devhome/blob/main/src/Assets/Preview/StoreDisplay-150.png" alt="DevHome Logo" />
  </a>
</p>

<h1 align="center">Dev Home</h1>

<h3 align="center">
  <a href="https://aka.ms/devhome">About Dev Home</a>
  <span> · </span>
  <a href="https://github.com/microsoft/devhome/releases">Release notes</a>
</h3>

Dev Home is a new experience from Microsoft aiming to give developers more power on Windows.

This repository contains the source code for:

* [Dev Home]()
* Dev Home core widgets

Related repositories include:

* [Dev Home GitHub Extension](https://github.com/microsoft/devhomegithubextension)
* [Dev Home Azure Extension](https://github.com/microsoft/devhomeazureextension)

## Installing and running

Windows|Availability
---|---
Windows 10 22H1 or earlier|❌
Windows 10 22H2 or later|✅
Windows 11 21H2 ~ 23H1|✅
Windows 11 23H2 or later|✅ (pre-installed)

### Via Microsoft Store (recommended)

Microsoft Store allows you to always be on the latest version when we release new builds with automatic upgrades. Note that widgets may not work on older versions of Windows.

<a style="text-decoration:none" href="https://apps.microsoft.com/detail/9n8mhtphngvv?launch=true&mode=full">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://get.microsoft.com/images/en-us%20dark.svg" width="200" />
    <img src="https://get.microsoft.com/images/en-us%20light.svg" width="200" />
</picture></a>

### Via GitHub

For users who are unable to install Dev Home from the Microsoft Store, released builds can be manually downloaded from this repository's [Releases page](https://github.com/microsoft/devhome/releases).

### Via WinGet CLI

[winget](https://github.com/microsoft/winget-cli) users can download and install the latest Dev Home release by installing the `Microsoft.DevHome` package:

```powershell
winget install --id Microsoft.DevHome -e
```

## Getting started with Dev Home

- [Roadmap](docs/roadmap.md)
- [Documentation](https://aka.ms/devhomedocs)

## Contributing

We are excited to work alongside you, our amazing community, to build and enhance Dev Home!

***BEFORE you start work on a feature/fix,*** please read & follow our [Contributor's Guide](CONTRIBUTING.md) to help avoid any wasted or duplicate effort.

## Data collection

This project collects usage data and sends it to Microsoft to help improve our products and services. Note, however, that no data collection is performed when using your private builds.

Privacy information can be found at https://privacy.microsoft.com

## Code of Conduct

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct).

For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
