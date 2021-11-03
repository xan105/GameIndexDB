List of games having achievement data with their name (_game_), binary(ies) and platform(s) id

Data were aggregated and are used by [xan105/Achievement Watcher](https://github.com/xan105/Achievement-Watcher)

Example
=======

```json
[
  {
    "name": "Cyberpunk 2077",
    "id": {
      "steam": "1091500",
      "gog": "1423049311"
    },
    "bin": [
      "Cyberpunk2077.exe"
    ]
  },
  {
    "name": "LEGO® Jurassic World",
    "id": {
      "steam": "352400"
    },
    "bin": [
      "LEGOJurassicWorld.exe",
      "LEGOJurassicWorld_DX11.exe"
    ]
  }
]
```

Notice
======

- A game has a corresponding platform id **only** if it has achievements on said platform. Yes, they are games that are available on multiple platforms but have achievements only on one.
- "Uplay ID" is an **array** because uplay games aren't unique in the sense that they can have multiple ids based on ~~whatever~~ various reasons (regions, ...).