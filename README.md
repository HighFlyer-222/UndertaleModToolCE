# UndertaleModTool: Community Edition

A fork of [UndertaleModTool](https://github.com/krzys-h/UndertaleModTool) with a lot of features for Pizza Tower modding and stuff.

## Features
- Features from AwfulNasty's [UTMT Usable](https://github.com/AwfulNasty/UndertaleModTool/tree/RoomEditorChanges):
  - Can open scr_player_mach3
  - Button to add creation code to rooms and objects in rooms
- Features from [SrPerez's UTMT fork](https://github.com/GithubSPerez/UndertaleModTool/):
  - Additional functions for structs and stuff
- Features from CST1229's [UTMT Super Usable](https://github.com/CST1229/UndertaleModTool/tree/super-usable) (which is a fork of Usable):
  - Types for some Pizza Tower stuff, like `spr_*` variables for characterspr and state IDs
  - Automatic selection/creation of instance layers and grid snapping when dragging objects into rooms
- And more to come in the future!

## Download

Theres some options for getting UndertaleModTool: Community Edition
1: Github Actions's Artifacts
2: Compiling it yourself with dotnet or visual studio
3: tell someone to compile it for you

## Compiling

[Same as vanilla UTMT.](https://github.com/krzys-h/UndertaleModTool#compilation-instructions)

<!--
  commandline building:

  dotnet publish UndertaleModTool -c Release -r win-x64 --self-contained false -p:PublishSingleFile=True --output bin/non-sc
  dotnet publish UndertaleModTool -c Release -r win-x64 --self-contained true -p:PublishSingleFile=True --output bin/sc
  dotnet publish UndertaleModCli -c Release -r win-x64 --self-contained false -p:PublishSingleFile=True --output bin/cli

-->
