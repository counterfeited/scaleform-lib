# scaleform-lib

Pictures and sounds from the 2018 CS:GO Scaleform UI.

## Contents

| Folder | Contents | Source |
| --- | --- | --- |
| `iconlib/vector` | named icon sprites, one SVG and one PNG each (`.fN` is the frame of a multi-frame sprite) | `iconlib.swf` |
| `iconlib/bitmaps` | the bitmaps embedded in the SWF: PNG (weapon pictures, grey and colour variants) and JPEG (country flags, `flag_XX.jpg`) | `iconlib.swf` |
| `money` | the sprites of the money display | `money.swf` |
| `cursor` | the mouse cursor: its sprite (`sprite-3`, SVG and PNG), the 32 x 32 bitmap it holds (`bitmap-1`) and that bitmap as raw RGBA (`cursor.rgba`, straight alpha) | `cursor.swf` |
| `hud` | HUD pictures cut or drawn for the 2018 HUD: plates, icons, arrows, flags, team select and pause menu art, the buy-zone cart | the HUD movies (`hud*.swf`, `scoreboard.swf`, `chooseteam.swf`, `pausemenu.swf`, `money.swf`); a few are drawn from a movie's numbers |
| `equipment` | the equipment icons by weapon name, SVG or PNG | `iconlib.swf` |
| `sound` | the 2018 UI sounds, 16-bit PCM WAV | `pak01_dir.vpk` of the 2018 client |

Names are the SWF's own symbol names. A sprite without one is `sprite-<character id>`.

## Disclaimers

- All artwork and sound in this repository is Valve Corporation's, from Counter-Strike: Global Offensive. It is not covered by any licence of this repository, and no licence to it is granted or implied.
- This repository is not affiliated with, endorsed by or sponsored by Valve Corporation. Counter-Strike, CS:GO, CS2 and Valve are trademarks or registered trademarks of Valve Corporation.
- The files are extracted from the game's own SWF and package files for study and interoperability. They are provided as they are, with no warranty of any kind.
- Anyone who owns the rights to a file here and wants it removed can open an issue, and it will be taken out.
