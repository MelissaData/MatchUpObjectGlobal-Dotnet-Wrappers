# Melissa - MatchUp Object Global .NET Wrappers

## Purpose
This is the code for you to run MatchUp Object Global in .NET.

Please feel free to copy or embed this code to your own project. Happy coding!

For latest Melissa MatchUp Object Global release notes, please visit: https://releasenotes.melissa.com/on-premise-api/matchup-object-global/

For further details, please visit: https://docs.melissa.com/on-premise-api/matchup-object-global/matchup-object-global-quickstart.html

## Tested Environments
- Windows 10 64-bit .NET 7.0, Powershell 5.1
- Linux 64-bit .NET 7.0, Ubuntu 20.04.05 LTS
- Melissa MatchUp Object Global for 2024-Q2
- Wrapper file(s) have not changed since 2023-Q4

## Getting Started

### Download this project
```
$ git clone https://github.com/MelissaData/MatchUpObjectGlobal-Dotnet-Wrappers
$ cd MatchUpObjectGlobal-Dotnet-Wrappers
```

### Copy wrappers to your project folder
Import `mdMatchup_cSharpCode.cs` to your project/solution and include the following line in your code to begin using the wrapper.

```
using MelissaData;
```

## Build mdMatchupNET.dll (optional, legacy)

#### Visual Studio Developer Command Prompt
It is important to note that you must be able to initialize the Visual Studio Developer Command Prompt environment for `x86_x64`. The Visual Studio Developer Command Prompt should already be downloaded if you have Microsoft Visual Studio installed. 

To check if you are able to intialize the Visual Studio Developer Command Prompt for `x86_x64`, you can open the start menu and search for `x86_x64 Cross Tools Command Prompt for VS 2022`. If this program exists, then you may continue to the next steps.

Alternatively, you can check to see if the following filepath exists: `C:\Program Files\Microsoft Visual Studio\2022\Professional\VC\Auxiliary\Build\vcvarsall.bat` (with Visual Studio 2022 installed). If the filepath exists, then you may continue to the next steps.

#### Set up Melissa Updater 
Melissa Updater is a CLI application allowing the user to update their Melissa applications/data. 

- Download Melissa Updater here: <https://releases.melissadata.net/Download/Library/WINDOWS/NET/ANY/latest/MelissaUpdater.exe>
- Create a folder within the cloned repo called `MelissaUpdater`.
- Put `MelissaUpdater.exe` in `MelissaUpdater` folder you just created.

#### Run Script
Parameters:
- license (optional): a license key to run the powershell script

```
$ .\BuildMatchupNETdll.ps1
```

or

```
$ .\BuildMatchupNETdll.ps1 -license "<your_license_key>"
```

## See also
- [Melissa - MatchUp Object Global Windows Dotnet](https://github.com/MelissaData/MatchUpObjectGlobal-Dotnet)
- [Melissa - MatchUp Object Global Linux Dotnet](https://github.com/MelissaData/MatchUpObjectGlobal-Dotnet-Linux)
    
## Contact Us
For free technical support, please call us at 800-MELISSA ext. 4 (800-635-4772 ext. 4) or email us at tech@melissa.com.

To purchase this product, contact Melissa sales department at 800-MELISSA ext. 3 (800-635-4772 ext. 3).
