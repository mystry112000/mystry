# mystry

## Loadstring

```lua
local Params = {
    RepoURL = "https://raw.githubusercontent.com/mystry112000/mystry/main/",
    SSI = "mystry",
}
local mystry = loadstring(game:HttpGet(Params.RepoURL .. Params.SSI .. ".luau", true), Params.SSI)()
mystry({})
```

## Credit

mystry https://discord.gg/Mppf6wXe