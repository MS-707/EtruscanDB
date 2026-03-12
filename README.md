# EtruscanDB

**Archaeological Research Explorer for Etruscan Civilization**

Live: [etruscan-db.vercel.app](https://etruscan-db.vercel.app)

## About

Interactive geographic database of Etruscan archaeological sites, museum collections, and significant artifacts. Built for accessible exploration by casual visitors and structured enough for academic research.

Inspired by [SlaveVoyages.org](https://www.slavevoyages.org/) — the gold standard for structured archaeological/historical databases with geographic visualization.

## Features

- **Interactive Map** — Leaflet + CartoDB Dark Matter tiles with color-coded markers (sites, collections, artifacts)
- **Filterable Sidebar** — Search and filter by type, period, location, institution
- **Detail Panel** — Rich metadata, descriptions, images, provenance for each record
- **Timeline** — Drag-to-filter timeline spanning 1100 BCE to 200 CE with Etruscan period labels
- **72 Records** — 31 sites, 13 collections, 28 artifacts, all with coordinates

## Data Sources

- Curated from academic sources, museum catalogs, and Wikidata
- Images from Wikimedia Commons (via API thumbnails)
- Sites verified against published archaeological literature

## Stack

- Static SPA — single `index.html`, no build step, no dependencies beyond CDN
- Leaflet.js for mapping
- CartoDB Dark Matter tiles (free, no API key)
- JSON data files
- Deployed on Vercel

## Categories

| Type | Count | Description |
|------|-------|-------------|
| Sites | 31 | Archaeological sites — cities, necropoleis, sanctuaries, settlements |
| Collections | 13 | Museums and digital archives holding Etruscan material |
| Artifacts | 28 | Significant objects — bronzes, paintings, inscriptions, jewelry |

## Periods Covered

- **Villanovan** (1100–750 BCE) — Proto-Etruscan Iron Age culture
- **Orientalizing** (750–580 BCE) — Near Eastern artistic influence
- **Archaic** (580–480 BCE) — Peak of Etruscan city-state power
- **Classical** (480–320 BCE) — Greek influence, Roman expansion begins
- **Hellenistic** (320–100 BCE) — Gradual Roman absorption
- **Roman** (100 BCE–) — Etruscan identity absorbed into Roman culture

## License

Data is compiled from public sources. Images are from Wikimedia Commons under their respective licenses.
