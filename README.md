# CycleScape

A cycling route planner for Japan (and, from OpenStreetMap, anywhere): it finds the lowest-resistance bike route by traffic, climbing, road type and your own road notes, and plans multi-stop tours leg by leg. Everything runs in the browser.

Live: https://max-mapper.github.io/cyclescape/

This repository holds the built site and the regional road packs (`tileset/`): the road network of each part of Japan, pre-built so a region is downloaded once and routed offline from the browser's storage.

## Data

- Roads and elevation in Japan: 地理院タイル (Geospatial Information Authority of Japan, GSI vector tiles and elevation tiles), processed (加工して作成).
- Road classes, bike paths, tracks and surfaces: © OpenStreetMap contributors (ODbL), via VersaTiles.
- Traffic estimate: 出典：令和3年度全国道路・街路交通情勢調査（国土交通省）を加工して作成.
- Elevation outside Japan: Terrain Tiles (AWS Open Data). Place search: GSI / Photon.

Third-party licences for the bundled code are in `licenses/`.
