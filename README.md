# CycleScape

A cycling route planner for Japan (and, from OpenStreetMap, anywhere): it finds the lowest-resistance bike route by traffic, climbing, road type and your own road notes, and plans multi-stop tours leg by leg. Everything runs in the browser.

Live: https://max-mapper.github.io/cyclescape/

This repository holds the built site and the regional road packs (`tileset/`): the OpenStreetMap road network of each part of Japan, with every road's tags, elevation and a traffic estimate, pre-built so a region is downloaded once and routed offline from the browser's storage.

## Data

- Roads in Japan and elsewhere: © OpenStreetMap contributors (ODbL). The region packs are built from Geofabrik's Japan extract; routes without a pack are built from VersaTiles map tiles.
- Elevation in Japan: 地理院タイル（標高タイル）を加工して作成 (Geospatial Information Authority of Japan).
- Traffic estimate: 出典：令和3年度全国道路・街路交通情勢調査（国土交通省）を加工して作成.
- Elevation outside Japan: Terrain Tiles (AWS Open Data). Place search: GSI / Photon.

Third-party licences for the bundled code are in `licenses/`.
