# scaleform-lib

Pictures and sounds from the 2018 CS:GO Scaleform UI.

## Contents

| Folder | Contents | Source |
| --- | --- | --- |
| `iconlib/vector` | named icon sprites, one SVG and one PNG each (`.fN` is the frame of a multi-frame sprite): JPEXS FFDec 26.5.0's SVG, and its render at zoom 2 | `iconlib.swf` of 21 August 2018 |
| `iconlib/bitmaps` | the bitmaps embedded in the SWF: PNG (weapon pictures, grey and colour variants) and JPEG (country flags, `flag_XX.jpg`) | `iconlib.swf` of 21 August 2018 |
| `money` | the sprites of the money display | `money.swf` |
| `cursor` | the mouse cursor: its sprite (`sprite-3`, SVG and PNG), the 32 x 32 bitmap it holds (`bitmap-1`) and that bitmap as raw RGBA (`cursor.rgba`, straight alpha) | `cursor.swf` |
| `hud` | HUD pictures cut or drawn for the 2018 HUD: plates, icons, arrows, flags, team select, pause menu and main menu art (the top bar's icons, the background and its clouds and grain, the friends box's icons, the XP ranks, the credits' pictures), the buy-zone cart | the HUD movies (`hud*.swf`, `scoreboard.swf`, `chooseteam.swf`, `pausemenu.swf`, `money.swf`, `mainmenuselectpanel.swf`, `background.swf`, `credits.swf`, `mainmenuwarningspanel.swf`) and the 2018 client's `resource/flash/images/ui_icons` and `econ/status_icons`; a few are drawn from a movie's numbers |
| `equipment` | the equipment icons by weapon name, SVG or PNG: each icon at its own size, centred in the ink of CS2's icon of the same name on CS2's canvas scaled to hold it | `iconlib.swf` of 21 August 2018 |
| `sound` | the 2018 UI sounds, 16-bit PCM WAV | `pak01_dir.vpk` of the 2018 client |

Every other movie is CS:GO 1.36.3.7's (depot 731, 31 May 2018). Names are the SWF's own symbol names, spaces as hyphens. A sprite without one is `sprite-<character id>`, a bitmap without one `<character id>`.

## Disclaimers

- All artwork and sound in this repository is Valve Corporation's, from Counter-Strike: Global Offensive. It is not covered by any licence of this repository, and no licence to it is granted or implied.
- This repository is not affiliated with, endorsed by or sponsored by Valve Corporation. Counter-Strike, CS:GO, CS2 and Valve are trademarks or registered trademarks of Valve Corporation.
- The files are extracted from the game's own SWF and package files for study and interoperability. They are provided as they are, with no warranty of any kind.
- Anyone who owns the rights to a file here and wants it removed can open an issue, and it will be taken out.
