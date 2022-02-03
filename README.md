# LBA Metadata

This repository contains metadata information (names, descriptions, ...) for the various LBA 1 and LBA 2 game data files. It aims to describe content from the game in a human-friendly way.

This is needed because the asset files distributed with the games are lacking naming information: the game engine accesses them by numbers. For example, the game engine knows that entry 0 of the `RESS.HQR` file is the game's color palettes.

All metadata files are in _JSON_ format for being easily parsed by tools in various programming languages, while remaining human readable.

The metadata is split in two folders, one for each game, plus an additional `common` folder for more general descriptions. From there you can find various folders containing differnt types of metadata.

## Metadata types

### HQR Metadata

The _JSON_ files found in these subfolders describe the content of the various [HQR files][hqr-info-url] found in both games.
The structure of the `LBA1/HQR` and `LBA2/HQR` folders is mimicking the game folders structure, with just a `.json` extension appended to the original games file names.

These metadata can be visualized by opening the original game's HQR files in [LBA Packager][lba-packager-site].

[lba-packager-site]: https://lbalab.github.io/lba-packager/
[hqr-info-url]: http://lbafileinfo.kaziq.net/index.php/High_quality_resource
