X-Ray Fixes
==========================
A compilation of fixes for S.T.A.L.K.E.R. Clear Sky from multitude of other projects. Source code based on ForserX's VS 2022 X-Ray port.

## What's beyond the scope of the project
* New features
* Modding resources
* Quality of Life changes
* Refactoring
* Optimizations
* Fixes for bugs not reproducable in vanilla game

## Fixes ported

### Graphical fixes
* Fixed visual artifacts occasionally occuring during the rain. ([original commit](https://github.com/OpenXRay/xray-15/commit/b8fd8b925c8593e75addd158deed327c0aff8d0b) by [Xottab_DUTY](https://github.com/Xottab-DUTY) for [OpenXRay 1.5](https://github.com/OpenXRay/xray-15/))
* Fixed the sun not properly moving from west to east on dynamic lighting due to a mistake in the formula. ([original commit](https://github.com/abramcumner/xray15/commit/42737bfa3e8a3d3df9b927ce34ffa91a27a14faf) by [abramcumner](https://github.com/abramcumner/) for [abramcumner's X-Ray 1.5](https://github.com/abramcumner/xray15/))

### Audio fixes
* Fixed controller roars persisting into loaded savegames. ([original commit](https://github.com/OpenXRay/xray-15/commit/3fec6f648c3a4de558a01a89cc4304ce95c4e920) by [Decane](https://github.com/Decane) for [OpenXRay 1.5](https://github.com/OpenXRay/xray-15))

### UI fixes
* Fixed Shock protection being mislabeled as Strike in outfit immunities. ([original commit](https://github.com/ixray-team/ixray-1.5-stcs/commit/4372f70fa5d9e3c18c0ce1d848bf52063fbabdf0) by [Hrusteckiy](https://github.com/Hrusteckiy) for [IX-Ray 1.5](https://github.com/ixray-team/ixray-1.5-stcs))
* Fixed map spots for squads, quests, important NPCs and the player being stretched and occasionally misplaced on 16:9 aspect ratio. ([original commit](https://github.com/ixray-team/ixray-1.5-stcs/commit/7a5de7a6cd3cbfffa10b17dd6d778fd07bfba01c) by [Hrusteckiy](https://github.com/Hrusteckiy) for [IX-Ray 1.5](https://github.com/ixray-team/ixray-1.5-stcs))

## Installation
1. Paste *bin* into the game's root directory, overwrite files.
2. Paste *gamedata* into the game's root directory, overwrite files.

## Known issues
See: [FunXRay/xray-csky](https://github.com/FunXRay/xray-csky)'s readme.
