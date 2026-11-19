> [!IMPORTANT]
> Independent, unofficial project. Not affiliated with, endorsed by, or officially connected to Roblox Corporation. "Luau" is a trademark of Roblox Corporation.

# Sebqq's Save Instance

Fixed & personal fork of [UniversalSynSaveInstance](https://github.com/luau/UniversalSynSaveInstance).

Fixes applied:
- Fixed `StreamBuffer` missing methods (`writeLenString`, `allocRegion`, `pokeu8`, `tostring`, `fill`)
- Fixed `buffer access out of bounds` crash in binary mode
- Fixed `.len` property on `StreamBuffer`

# Loadstring

```lua
local Params = {
 RepoURL = "https://raw.githubusercontent.com/itssebqq-dev/UniversalSynSaveInstance/refs/heads/main/",
 SSI = "saveinstance",
}
local synsaveinstance = loadstring(game:HttpGet(Params.RepoURL .. Params.SSI .. ".luau", true), Params.SSI)()
local Options = {}
synsaveinstance(Options)
```

# Credits

Based on [UniversalSynSaveInstance](https://github.com/luau/UniversalSynSaveInstance) by the luau team.

> [!WARNING]
> As stated under the Section 7 (b) in the LICENSE:
> - You **MUST** always include the following Credit string: `UniversalSynSaveInstance https://discord.gg/wx4ThpAsmw`
> - You are **NOT** allowed to claim authorship of the source code provided in this repository
> - You **MUST** always include the following [License](https://github.com/luau/UniversalSynSaveInstance/blob/main/LICENSE)
