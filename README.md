````md
# RimWorld Georgian Translation

Community Georgian translation for **RimWorld**.

This project provides Georgian localization files for RimWorld and DLC content (XML language files only).  
It includes translated **Keyed** and **DefInjected** entries, with ongoing cleanup and QA.

## Status

- **Playable:** Yes
- **Translation status:** Work in progress (large coverage, final polish still ongoing)
- **Current focus:** fixing awkward machine-translated lines, remaining English strings, and UI text length issues

## Supported Content

This repository includes Georgian localization files for:

- Core
- Royalty
- Ideology
- Biotech
- Anomaly
- Odyssey

> Coverage varies by category. Most UI and a large portion of in-game content are already translated.

## Installation

1. Download this repository (or the latest release ZIP).
2. Make sure the archive/folder contains a top-level `Data/` folder.
3. Copy the `Data` folder into your RimWorld installation directory.
4. Launch RimWorld.
5. Go to **Options → Language** and select **ქართული**.

### Expected folder structure

```text
RimWorld/
└─ Data/
   ├─ Core/
   │  └─ Languages/
   │     └─ Georgian/
   ├─ Royalty/
   │  └─ Languages/
   │     └─ Georgian/
   ├─ Ideology/
   ├─ Biotech/
   ├─ Anomaly/
   └─ Odyssey/
````

## Known Issues

* Some strings may still appear in English
* Some lines may sound unnatural (machine-translation artifacts)
* A few UI strings may be too long and overflow buttons/labels
* Terminology is still being unified in some categories

If you find issues, please open an Issue and include a screenshot if possible.

## Credits

**Georgian Translation:**
Levan Khutsishvili (Sallyvan)

## Contributing

Contributions are welcome, especially for:

* leftover English strings
* better Georgian phrasing
* UI-friendly shorter wording
* terminology consistency (traits, health, skills, storyteller texts, etc.)

If you want to help:

1. Fork the repository
2. Make your changes
3. Open a Pull Request

## Notes

* This repository contains **translation files only** (no game binaries/assets).
* RimWorld is developed by **Ludeon Studios**.

## License

Translation files in this repository are provided for community use and improvement.
If needed, a more explicit license can be added later (for example, MIT for the translation text/files).
