# Hunspell binaries for Win32/Win64

A [DPM](https://github.com/DelphiPackageManager/DPM) package that provides the [Hunspell](https://github.com/hunspell/hunspell) DLLs for Windows, making it simple to add them to your Delphi project.

The DLLs are built by VSoft Technologies locally using the original source 

## Installation

Install into your project using the DPM client:

```
dpm install VSoft.Hunspell.Binaries
```

## What's included

| Platform | DLL |
| --- | --- |
| win32 | `binaries/win32/hunspell.dll` |
| win64 | `binaries/win64/hunspell.dll` |

When the package is installed, DPM will:

- Copy the correct `hunspell.dll` to your output (bin) folder for each platform.
- Add the package's `binaries\$platform$` folder to the `PATH` environment variable used when running from the IDE.

## Supported compilers

Delphi XE2 through Delphi 13.x, for the `win32` and `win64` platforms.

## License

Hunspell is licensed under the LGPL-2.1 license. See the [hunspell repo](https://github.com/hunspell/hunspell) for full license detail.
