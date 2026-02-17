This project is currently closed source and private for the time being.

# Atlas
A Minecraft **1.21.8**->**1.21.11** Ghost Client, designed for legit gameplay and staying hidden.

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/ea088e51-8cf4-4601-997b-4fbd2b6e5729" />

## Features
### Config/Friend Managers
- Save files to a config hidden in the TEMP directory.
- Add/remove players as friends, to not be targetted by modules.
### SOCKS Proxy System
- Connect to Multiplayer servers through a SOCKS5/SOCKS4 proxy, masking your IP.
### Self Destruct
- Self destruct system with file replacement, modified date persistance, config file removal and memory pool string deletion.

## Modules
### Client
- ClickGUI
- MiddleClickFriend
- SelfDestruct
- SocksProxy
- Targets
### Combat
- AimAssist
- AttributeSwap
- Hitboxes
- Reach
- ShieldDisable
- TriggerBot
### Movement
- JumpReset
- KeepSprint
- NoJumpDelay
- SpeedBridge
### Player
- AutoFish
- FakeLag
- NoBreakDelay
- PingSpoof
- RefillPot
- ThrowPot
### Visuals
- ESP (WIP)

## Info
The project shadow includes ImGui to draw it's menu and (future) visual modules, has a robust self destruct feature that replaces the mod file and cleans all traces, and has a built in SOCKS proxy system for an in-game IP change.

## TODO
- Make menu/visuals "stream proof" (overlay),
- Port to 26.1.
