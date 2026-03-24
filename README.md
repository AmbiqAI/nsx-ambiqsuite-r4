# nsx-ambiqsuite-r4

`nsx-ambiqsuite-r4` is the raw AmbiqSuite R4 SDK provider repo used by NSX.

This repo keeps the imported vendor SDK under `sdk/` and exposes a thin NSX
provider target through `CMakeLists.txt` and `nsx-module.yaml`.

The default branch tracks the latest validated R4 line for NSX. Older validated
R4 releases can live on versioned branches when needed.
