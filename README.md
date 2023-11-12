# Programmable Block Linux
VSCode setup for intellisense for space engineers programmable blocks.

## Howto
Download the contents of the repo.
You will need `dotnet` installed (version 6.0 tmk) and C# vscode extensions active.
In `SE/SpaceEngineers.csproj` replace `/storage/SteamLibrary/steamapps/common/SpaceEngineers` with your se install folder.
Run `dotnet build`, it might error so try it again and see if the errors go away.
Open `SE/template.cs`, see if it has IntelliSense, if not, restart VSCode
