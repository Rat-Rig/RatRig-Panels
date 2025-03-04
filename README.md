<a href="https://ratrig.com/">
    <img src="https://ratrig.com/media/athlete2/default/RR_Logo_White.png" alt="RatRig logo" title="RatRig" height="74" />
</a>

# Panel Repository

## Overview
This repository contains DXF and STEP files pertaining to all existing, as well as obsolete, enclosure panels used in our products.

Each design is uniquely named to distinguish it, along with a version number and a date. In the case where a fresh revision becomes necessary (such as rectifying an issue with a panel or a significant design enhancement), a new file is released with an incremented version number and the previous version is relocated into a subfolder labeled "deprecated".

## Repository Layout
- Panels for each project are stored in the named project subfolder
- Deprecated parts are stored within a 'Deprecated' subfolder
```
├── CNC-Enclosure-Mill/
│   ├── panel_cnc_enclosure_mill_back_V01_20250218.dxf
│   ├── panel_cnc_enclosure_mill_back_V01_20250218.step
│   ├── panel_cnc_enclosure_mill_base_V01_20250218.dxf
│   ├── panel_cnc_enclosure_mill_base_V01_20250218.step
│   └── ...
├── ...
└── V-Core-4.0/
    ├── Deprecated/
    │   ├── vc4_panel_door_300_V02_20240510.dxf
    │   └── vc4_panel_door_300_V02_20240510.step
    ├── vc4_panel_door_300_V03_20240730.dxf
    ├── vc4_panel_door_300_V03_20240730.step
    └── ...
```

## License
All files contained within this repository are licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License](https://creativecommons.org/licenses/by-nc-sa/4.0/). See LICENSE for the full details.
