<p align="center">
  <img height="400px" style="margin: 0; padding: 0" src=".moonwave\static\logo.png" />
</p>


# Loadstring

```lua
local Params = {
 RepoURL = "https://raw.githubusercontent.com/mystry112000/mystry/main/",
 SSI = "mystry",
}
local mystry = loadstring(game:HttpGet(Params.RepoURL .. Params.SSI .. ".luau", true), Params.SSI)()
local Options = {} -- Documentation here https://luau.github.io/mystry/api/mystry
mystry(Options)
```

# mystry

A project aimed at providing saveinstance function for Roblox.<br />
Reason: Many tools fail miserably at providing good user experience when it comes to tinkering with saving instances.

> [!WARNING]
> As stated under the Section 7 (b) in the LICENSE:
> - You **MUST** always include the following Credit string: `mystry https://discord.gg/Mppf6wXe`
> - You are **NOT** allowed to claim authorship of the source code provided in this repository
> - You **MUST** always include the following [License](https://github.com/mystry112000/mystry/blob/main/LICENSE)

## Disclaimer

This project is provided for development, debugging, archival, and research purposes within the Roblox platform.

It is not intended for misuse, including violating platform rules, unauthorized access, or redistribution of content without permission.

Users are responsible for ensuring their usage complies with all applicable rules, including Roblox's Terms of Use.

The maintainers do not support or condone misuse of this software and are not responsible for how it is used.

> [!TIP]
> Important part about this mystry is that it doesn't modify game state, which helps maintain stability and compatibility.<br />
> You can also enable the `SafeMode` option to improve compatibility and ensure more reliable saving across a wide range of experiences.<br /><br /> You can read more about it here [Documentation]<br /><br /> If this script is helpful to you, please click `⭐ Star` in the upper right corner of the page to support it, thank you!

# Documentation

[Documentation]

# Support

<a href='https://ko-fi.com/M4M1JNH5G' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi2.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' title='KO-FI' /></a>
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/M4M1JNH5G "KO-FI")
<br/>
[![ko-fi](https://user-images.githubusercontent.com/95628489/231759262-25661006-b7ca-4967-a79d-2b465cd9575a.png)](https://ko-fi.com/M4M1JNH5G "KO-FI QR-CODE")

# Discord Server:

https://discord.gg/Mppf6wXe

[<img src="https://discordapp.com/api/guilds/1022465460517740654/widget.png?style=banner2" alt="Our Official Discord Server!"></img>](https://discord.gg/Mppf6wXe)

# TO-DOs

- [ ] Add Support for Binary Format Output (rbxl/rbxm)
- [ ] Speed things up as much as possible

# Acknowledgments

> [!IMPORTANT]
> This document is based largely on the efforts of [@Anaminus] & [@Dekkonot], authors of the [Roblox Format Specifications]. Additional resources include:
>
> - [Syngp Synapse X Source code 2019][Synapse X Source 2019] for base saveinstance code (extended by [@mblouka] & [@Acrillis])
> - [@LorekeeperZinnia] for being the original creator of saveinstance that was used in Synapse X, Elysian and many others.
> - [Rojo Rbx Dom Xml] for being a fallback documentation
> - [Roblox Client Tracker] for an extended & close to full JSON Api Dump

[Documentation]: https://luau.github.io/mystry/api/mystry
[@Acrillis]: https://github.com/Acrillis
[@Anaminus]: https://github.com/Anaminus
[@Dekkonot]: https://github.com/Dekkonot
[@mblouka]: https://github.com/mblouka
[@LorekeeperZinnia]: https://github.com/LorekeeperZinnia
[Roblox Client Tracker]: https://github.com/MaximumADHD/Roblox-Client-Tracker
[Roblox File Format]: https://github.com/MaximumADHD/Roblox-File-Format
[Roblox Format Specifications]: https://github.com/RobloxAPI/spec/
[Synapse X Source 2019]: https://github.com/Acrillis/SynapseX
[Rojo Rbx Dom Xml]: https://github.com/rojo-rbx/rbx-dom/blob/master/docs/xml.md