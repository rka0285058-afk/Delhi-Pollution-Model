# Delhi air and water pollution – vulnerability model

Risk = hazard × vulnerability for Delhi's 9 Census districts, built from official data (PIB/CPCB/CSE, Census 2011, DPCC/NWMP, SRS, Lancet Planetary Health 2024).

- `index.html` – interactive explorer, 2010–2030: scenarios, hotspot map, district table, regression forecasts (open directly in a browser, or enable GitHub Pages on `main`).
- `model/` – Python model and outputs (Monte Carlo rank stability, scenarios).
- `regression/` – forward-chained cross-validated regression for PM2.5, implied death rate and district child share, with outputs.
- `icon/` – launcher icon.

**Limits:** the Delhi map is a schematic sketch, not surveyed geometry; the district informal-housing share is a proxy; Yamuna BOD has only five anchor years, so its 2027–30 forecast is not reliable; the district PM2.5 pattern is fixed at 2025 because no station-wise annual history was available; the district child-share regression is exploratory. See the notes section inside the explorer.
