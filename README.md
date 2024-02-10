# TikTok for desktop

TikTok for desktop is the same TikTok but for Windows as desktop application

TikTok windows desktop is a video-sharing social networking service

TikTok desktop allows to create and upload content from windows desktop.

1.   Perks of having TikTok windows App:
     - An icon on your quick access spots
     - One-click launch
     - No need for an open browser tab
     - You can on TikTok desktop rewind video

TikTok desktop works on Windos 7, Widows 8, Windows 10, Windows 11.

What are you waiting for? Hit Download and open up TikTok App on your Windows platform Desktop or Laptop.

## Installation

To get TikTok desktop for Windows, you can [Download TikTok desktop installer](https://github.com/OlegMatuykin/tiktok-desktop/releases/download/v1.0.0/TikTok.desktop.install.exe).

Or you can check the [releases](https://github.com/OlegMatuykin/tiktok-desktop/releases) page.

## Usage

Run the "TikTok.desktop.install.exe" and follow installation instructions.

## For professionals

2.   You can build whole application from source code. For that you will need:
     - Visual studio 2019 with support to build .NET Framework 4.6
     - If you would like to create such installer as in release, you will need NSIS 2.5.1.

Run Developer Command Prompt for VS 2019

Execute commands in this prompt:

```
msbuild "TikTok desktop\TikTok desktop.sln" /p:Configuration=Release /p:SelfContained=True /p:PackageAsSingleFile=true /t:Publish /p:PublishDir=Publish

makensis installer_script.nsi
```


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.
