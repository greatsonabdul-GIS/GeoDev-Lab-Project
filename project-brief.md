# My project brief

## The question
Which wards in Igabi Local Government Area, Kaduna State, are more than 5 km from a health facility?

## Why it matters
Igabi sits on the edge of Kaduna metropolis, with settlement spreading outward from the city while other wards stay rural. A ward-level view of facility gaps could help the LGA health department, or an NGO planning outreach, decide where a new primary health centre or mobile clinic would help the most.

## The data I need
- Ward boundaries — Igabi LGA, Kaduna State
- Health facility locations — Kaduna State, points
- Roads — Igabi LGA, for context now and a possible travel-time upgrade later

## Where each dataset comes from
- Ward boundaries — GRID3 NGA Operational Wards v3.0 — https://data.grid3.org/datasets/GRID3::grid3-nga-operational-wards-v3-0/explore — GeoPackage, statewide, filter to Igabi
- Health facilities — GRID3 NGA Health Facilities v3.0 — search "Nigeria health facilities" at https://data.grid3.org — GeoPackage, statewide, clip to Igabi
- Roads — OpenStreetMap, extracted with the QuickOSM plugin in QGIS — no separate download link, pulled directly for the Igabi extent

## What I would build
A map of Igabi showing which wards fall more than 5 km from a health facility, with the uncovered areas shaded. Longer term this could become a small dashboard for the LGA health department, and the straight-line distance could be upgraded to real travel time once I have a road network with speeds.
