# ORBITAL v6 — NASA / USGS planet texture sources

Downloaded 2026-07-11 for local WebGL use.

| Local file | Source | Provenance / caveat |
|---|---|---|
| `venus-magellan.jpg` | https://science.nasa.gov/3d-resources/venus/ | Magellan radar imagery stitched by JPL/Caltech. Radar-derived surface, not optical natural colour. |
| `mars-viking.jpg` | https://science.nasa.gov/3d-resources/mars/ | Viking imagery processed at USGS; NASA/JPL-Caltech. |
| `jupiter-voyager.jpg` | https://science.nasa.gov/3d-resources/jupiter/ | Voyager images; JPL/Caltech generated planetary map. |
| `pluto-new-horizons-1024.jpg` | https://astrogeology.usgs.gov/search/map/pluto_new_horizons_lorri_mvic_global_mosaic_300m | New Horizons LORRI/MVIC global mosaic, 300 m/pixel source; 1024 px browse derivative. Cite New Horizons Team / NASA / JHUAPL / SwRI / LPI / USGS. |
| `mercury-usgs-1024.jpg` | https://astrogeology.usgs.gov/search/map/mercury_messenger_mdis_global_color_mosaic_665m | MESSENGER MDIS global colour mosaic; 1024 px browse derivative if download endpoint remains available. |

Existing Earth day/cloud/night assets are retained from v5 to avoid a visible regression. Uranus and Neptune do not have complete natural-colour global mosaics comparable to rocky-body basemaps; v6 uses procedurally modelled atmospheres calibrated to official mission imagery instead of claiming fictional texture maps are observational truth. Saturn similarly keeps a procedural banded atmosphere and ring system rather than using NASA's explicitly labelled fictional 3D texture.
