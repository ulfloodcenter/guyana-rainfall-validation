# Guyana IMERG Rainfall Validation — interactive dashboard

This repository hosts the static interactive dashboard developed by the University of Louisiana at Lafayette and Louisiana Watershed Flood Center for IMERG rainfall validation in Guyana.

## Publish with GitHub Pages

1. Create a public GitHub repository (e.g., `guyana-rainfall-validation`).
2. Upload `index.html` and `README.md` to the repository root.
3. Under **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
4. Open `https://YOUR-USERNAME.github.io/guyana-rainfall-validation/` and verify charts, station controls, and map tiles.

## HydroShare archival workflow

1. Create a HydroShare resource with the dashboard HTML, this README, and, if appropriate, underlying data/method documentation.
2. Describe data provenance, gauge observations, IMERG product/version, study period, quality control, and limitations in the resource metadata.
3. Publish the resource and obtain its permanent DOI.
4. Replace **both** placeholders in `index.html` (`HydroShare DOI: pending assignment.` and `HydroShare resource link to be added after publication.`) with the actual DOI and resource URL. Do not invent a DOI.
5. Add the live GitHub Pages URL to the HydroShare resource description.

## Citation

Suggested citation, to be finalized with the resource's official authors and DOI:

Habib, E., Morsy, M., and Williams, G. (2026). *Guyana IMERG Rainfall Validation: Interactive Dashboard*. University of Louisiana at Lafayette and Louisiana Watershed Flood Center. HydroShare. DOI: [to be assigned].

## Dependencies and reproducibility

The dashboard embeds its visualization data and logos, and loads Plotly 2.35.2 and Leaflet 1.9.4 from external CDNs. Online map tiles may also be required. It is not fully offline-capable. Static hosting does not require a backend. Validate browser behavior before sharing publicly.

## Version

1.0 — November 11, 2026 (GitHub Pages packaging; original scientific dashboard code and embedded data preserved).
