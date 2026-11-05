# Tamale-urban-growth-sentinel2
Mapping urban growth in Tamale, Ghana using Sentinel-2 imagery and U-Net segmentation(dry season 2019/20 vs 2025/26)

# Mapping urban growth in Tamale, Ghana with Sentinel-2 and deep learning

A small remote sensing project comparing built-up land in Tamale between the
2019/20 and 2025/26 dry seasons, using Sentinel-2 imagery from Google Earth
Engine and a U-Net segmentation model.

## Question
How much has Tamale's built-up area grown over the last six years, and where?

## Status
Work in progress. Six-week plan:
- [ ] Week 1: Earth Engine setup and study area
- [ ] Week 2: Sentinel-2 composites for both years
- [ ] Week 3: Labelled dataset
- [ ] Week 4: Model training (U-Net and Random Forest baseline)
- [ ] Week 5: Evaluation and change analysis
- [ ] Week 6: Write-up and publishing

## Study area
About 15 x 15 km around central Tamale, Northern Region, Ghana.

## Data
Sentinel-2 Level-2A surface reflectance (COPERNICUS/S2_SR_HARMONIZED),
December to February composites, cloud masked.

## Repo layout
- `data/` labels and chips (large files kept outside the repo)
- `notebooks/` Colab notebooks
- `src/` scripts
- `figures/` maps and plots
