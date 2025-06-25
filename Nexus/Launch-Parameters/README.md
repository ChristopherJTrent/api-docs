# `-ggvanilla`
Fully disables Nexus as if it wasn't installed.
Any DirectX call, will simply be passed on to the actual D3D11.dll.

# `-ggaddons <PATH>`
Usage: `-ggaddons "C:\MyFiles\AddonConfigAccount1.json"`

Specifies a custom config path for `AddonConfig.json` normally located at `<GW2>/addons/Nexus/AddonConfig.json`.

This path will be used to save the config. Useful for multiboxing.

# `-ggaddons <IDLIST>`
Usage: `-ggaddons 1, 2`

You can pass a list of addon IDs. This means only the addons with the ID 1 and 2 will be loaded - if they are even installed.

The addon config will **NOT** be saved.

## `-ggaddons 0`
Does not load any addon on startup, as the ID 0 does not exist.

The addon config will **NOT** be saved.

# `-ggconsole`
Opens a console window for the log output. Useful for debugging.
