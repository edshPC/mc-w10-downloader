# MCDownloader

This tool allows you to *download* several versions of Minecraft: Windows 10 Edition (Bedrock).
This is useful if you want to keep different versions of Minecraft APPX packages, switching simply between them.

This is a fork of [MCLauncher](https://github.com/MCMrARM/mc-w10-version-launcher)
which *only* downloads a package of any version of Minecraft Bedrock to the `downloads` folder,
which you can install later by opening the downloaded version.

## Disclaimer
This tool will **not** help you to pirate the game; it requires that you have a Microsoft account which can be used to download Minecraft from the Store.

## Prerequisites
- A Microsoft account connected to Microsoft Store which **owns Minecraft for Windows 10**
- **Developer mode** enabled for app installation in Windows 10 Settings
- If you want to be able to use beta versions, you'll additionally need to **subscribe to the Minecraft Beta program using Xbox Insider Hub**.
- [Microsoft Visual C++ Redistributable](https://aka.ms/vs/16/release/vc_redist.x64.exe) installed.

## Setup
- Download the latest release from the [Releases](https://github.com/edshPC/mc-w10-downloader/releases) section. Unzip it somewhere.
- Run `MCDownloader.exe` to start the launcher.

## Compiling the launcher yourself
You'll need Visual Studio with Windows 10 SDK version 10.0.17763 and .NET Framework 4.6.1 SDK installed. You can find these in the Visual Studio Installer if you don't have them out of the box.
The project should build out of the box with VS as long as you haven't done anything bizarre.

## Frequently Asked Questions
**Does this allow running multiple instances of Minecraft: Bedrock at the same time?**

At the time of writing, no. It allows you to _install_ multiple versions, but only one version can run at a time.
