# Awesome Fishing Data [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of open datasets, APIs, and tools for fishing, fish species,
> marine biodiversity, and ocean conditions.

Whether you're building a fishing app, doing fisheries research, training a
species classifier, or mapping the ocean, this list points to **open and
freely usable** data sources. It is maintained by [FishRadar](https://fishradar.ai),
the live fishing-conditions app, alongside two open datasets we publish (see
[Regulations](#regulations) and [Species](#species--taxonomy)).

Contributions welcome — see [Contributing](#contributing).

## Contents

- [Species & Taxonomy](#species--taxonomy)
- [Biodiversity & Occurrence Records](#biodiversity--occurrence-records)
- [Regulations](#regulations)
- [Ocean & Weather Conditions](#ocean--weather-conditions)
- [Bathymetry & Marine GIS](#bathymetry--marine-gis)
- [Fisheries & Stock Assessment](#fisheries--stock-assessment)
- [Apps & Tools](#apps--tools)
- [Contributing](#contributing)
- [License](#license)

## Species & Taxonomy

- [FishBase](https://www.fishbase.se/) — The global biodiversity information
  system on finfishes; taxonomy, ecology, distribution, growth, and more for
  ~35,000 species. The de facto reference for fish biology.
- [World Register of Marine Species (WoRMS)](https://www.marinespecies.org/) —
  Authoritative, curated list of names of marine organisms, with stable
  AphiaID identifiers and a public REST API.
- [Catalog of Fishes (California Academy of Sciences)](https://researcharchive.calacademy.org/research/ichthyology/catalog/fishcatmain.asp) —
  The authoritative taxonomic database of fish species names and nomenclature.
- [ITIS — Integrated Taxonomic Information System](https://www.itis.gov/) —
  Authoritative taxonomic information on plants, animals, fungi, and microbes,
  with TSN identifiers and an open API.
- [FAO ASFIS List of Species](https://www.fao.org/fishery/en/collection/asfis/en) —
  Standardized 3-alpha codes, scientific and common names for aquatic species
  used in fishery statistics.
- [**fishing-species-catalog**](https://github.com/linkanlabs-ctrl/fishing-species-catalog)
  (this org) — A compact, multilingual catalog of 196 sport-fishing species
  with stable ids, aliases, environment, latitude band, and conservation flags.
  CC BY 4.0. Also on
  [🤗 Hugging Face](https://huggingface.co/datasets/Ali4333/fish-species-catalog).

## Biodiversity & Occurrence Records

- [GBIF — Global Biodiversity Information Facility](https://www.gbif.org/) —
  Billions of free and open species-occurrence records aggregated from
  thousands of datasets, with a powerful public API.
- [iNaturalist](https://www.inaturalist.org/) — Crowdsourced, geotagged species
  observations with photos; research-grade records are exported to GBIF.
  [API docs](https://api.inaturalist.org/v1/docs/).
- [OBIS — Ocean Biodiversity Information System](https://obis.org/) — A global
  open-access database of marine species distribution, hosted by IOC-UNESCO.
- [IUCN Red List](https://www.iucnredlist.org/) — The global standard for the
  conservation status of species, with an API for status and range data.
- [CITES Checklist & Trade Database](https://checklist.cites.org/) — Species
  listed under the Convention on International Trade in Endangered Species,
  including many sharks, rays, eels, and sturgeon.

## Regulations

- [**open-fishing-regulations**](https://github.com/linkanlabs-ctrl/open-fishing-regulations)
  (this org) — Machine-readable recreational fishing regulations (bag/size/slot
  limits, seasons, licences) for 12 jurisdictions across 9 countries, each with
  an official `sourceUrl`. CC BY 4.0. Also on
  [🤗 Hugging Face](https://huggingface.co/datasets/Ali4333/fishing-regulations).
- [NOAA Fisheries — Recreational Fishing Regulations](https://www.fisheries.noaa.gov/recreational-fishing-regulations) —
  Official U.S. federal recreational fishing rules by region and species.
- [RecFishing rules by U.S. state](https://www.takemefishing.org/how-to-fish/fishing-license/) —
  Index of state fish & wildlife agencies, each the authoritative source for
  that state's licence and regulations.
- [EU Fishing Rules (TACs and Quotas)](https://oceans-and-fisheries.ec.europa.eu/fisheries/rules/fishing-rules_en) —
  European Commission rules on catch limits and management measures.

## Ocean & Weather Conditions

- [Open-Meteo](https://open-meteo.com/) — Free, open weather and **marine**
  forecast APIs (waves, sea-surface temperature, currents, wind) with no API
  key for non-commercial use. Excellent for fishing-condition apps.
- [NOAA / NWS API](https://www.weather.gov/documentation/services-web-api) —
  Official U.S. weather forecasts, alerts, and observations.
- [NOAA Tides & Currents (CO-OPS)](https://tidesandcurrents.noaa.gov/) — Water
  levels, tide predictions, and real-time currents for U.S. coastal stations.
- [NDBC — National Data Buoy Center](https://www.ndbc.noaa.gov/) — Real-time and
  historical marine observations (waves, wind, water temperature) from buoys
  worldwide.
- [Copernicus Marine Service](https://marine.copernicus.eu/) — Free, open
  European ocean-state data: currents, temperature, salinity, sea level,
  biogeochemistry (chlorophyll), forecasts and reanalysis.
- [NASA OceanColor](https://oceancolor.gsfc.nasa.gov/) — Satellite ocean-color
  products including chlorophyll-a, a useful proxy for productivity.

## Bathymetry & Marine GIS

- [GEBCO](https://www.gebco.net/) — Global bathymetric grid of ocean and land
  elevation, freely downloadable.
- [EMODnet](https://emodnet.ec.europa.eu/) — The European Marine Observation and
  Data Network: open bathymetry, geology, seabed habitats, human activities,
  and more, with WMS/WFS services.
- [GMRT — Global Multi-Resolution Topography](https://www.gmrt.org/) — A
  continuously updated, multi-resolution global elevation/bathymetry synthesis
  with a public web service.
- [Marine Regions](https://www.marineregions.org/) — Standard georeferenced
  marine place names and boundaries (EEZs, seas, ecoregions) with stable MRGIDs.
- [Natural Earth](https://www.naturalearthdata.com/) — Free public-domain vector
  and raster map data, including coastlines and ocean polygons.

## Fisheries & Stock Assessment

- [RAM Legacy Stock Assessment Database](https://www.ramlegacy.org/) — A
  compilation of stock-assessment results for commercially exploited marine
  populations worldwide.
- [Sea Around Us](https://www.seaaroundus.org/) — Reconstructed global fisheries
  catch data by country, taxon, and fishing sector.
- [Global Fishing Watch](https://globalfishingwatch.org/) — Open data and APIs
  on apparent fishing effort and vessel activity, derived from AIS.
- [FAO FishStat](https://www.fao.org/fishery/en/statistics) — Global capture and
  aquaculture production statistics.

## Apps & Tools

- [FishRadar](https://fishradar.ai) — Live fishing conditions, location-aware
  regulations, and species guidance. Browse
  [regulations](https://fishradar.ai/fishing/) and
  [species](https://fishradar.ai/fishing/species/) on the web, or get the app on
  [iOS](https://apps.apple.com/us/app/fishradar/id6764589903).
- [pygbif](https://github.com/gbif/pygbif) — Python client for the GBIF API.
- [rfishbase](https://github.com/ropensci/rfishbase) — R interface to FishBase
  and SeaLifeBase.
- [obistools](https://github.com/iobis/obistools) — R tools for data quality
  control against OBIS.

## Contributing

Found a great open fishing/marine dataset or tool that's missing? Please open a
pull request — see [CONTRIBUTING.md](CONTRIBUTING.md). Keep entries open or
freely usable, accurately described, and alphabetical-ish within each section.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](LICENSE)

To the extent possible under law, the maintainers have waived all copyright and
related rights to **this list** (the curation) under
[CC0 1.0](LICENSE). The linked resources retain their own respective licenses.

---

Curated by [FishRadar](https://fishradar.ai).
