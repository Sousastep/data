# data
This is the data folder for `/sousastep/SousaFX/data/` and `/sousastep/SousaVFX/data/`. It contains all of Sousastep's personal presets for SousaFX and SousaVFX.

The sousastep repository does not include this data repository as gitmodules.

SousaFX and SousaVFX initialize with the default presets stored in `/sousastep/default/presets/`. 

The default presets are overridden by any jsons in SousaFX's `data` folder thanks to Max searching global paths before project paths. `/sousastep/` must be added to to Max’s global search path for this to work: Go to Max > Menubar > Options... > File Preferences..., “Add Path” +, “choose”, and select `~/Documents/​Max 8/​Project/​sousastep`.

The data repository's `SousaVFX` branch may be cloned to `/sousastep/SousaVFX/`.

The data repository's `main2` branch may be cloned to `/sousastep/SousaFX/`.
