# PDH .Stat to CKAN data pacakges mappings
In this repository we define the CKAN data packages that are harvested from PDH .Stat

The package mapping is defined in the file ckaneery.csv. It started as a straight dump from the PSQL done on the 2025-09-02 and is read by the `dotstat` harvester in [pdh-ckan-toolkit](https://github.com/PacificCommunity/pdh-ckan-toolkit).

All SDMX links point to the latest dataflow version: REST URLs leave the version empty (`SPC,DF_SDG,/<key>`) and Data Explorer links omit `df[vs]`. Keys are positional, so they must still match the latest DSD; see `AGENTS.md` for the checks.
