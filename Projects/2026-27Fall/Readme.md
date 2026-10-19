# Term Project: Climate Action & Sustainable Development

## Topic

This term's overarching theme is **"Global Climate Action: Targets, Risks, and Sustainable Transformation"**, framed around the core agenda of **COP31** and the **United Nations Sustainable Development Goals (SDGs)**. 

You are expected to design an **A1 vertical academic poster** that delivers an engaging data-driven story on a specific challenge within this theme. Rather than producing disconnected descriptive plots, your project should present a clear statistical narrative—connecting commitments, historical trajectories, structural inequalities, or environmental impacts.

### Thematic Focus Areas

Your project must connect to **SDG 13 (Climate Action)** as the core umbrella, optionally combined with one or more intersecting development goals:

- **Emissions, Mitigation & Energy Transition:** Tracking historical emissions, decarbonization pathways, clean energy adoption, or sector-level transitions (**SDG 13 & SDG 7**).
- **Climate Justice, Risk & Finance:** Evaluating global climate vulnerability, loss and damage distribution, historical emission responsibilities, and adaptation funding flows (**SDG 13 & SDG 17**).
- **Urban Resilience & Infrastructure:** Heat island dynamics, air pollution indices, green spaces, and sustainable municipal transit (**SDG 13 & SDG 11**).
- **Resource Cycles & Industrial Decarbonization:** Circular economy metrics, industrial emissions, waste recovery, and material footprints (**SDG 13 & SDG 12**).
- **Ecosystem Dynamics & Land Use:** Extreme climate anomalies, droughts, deforestation rates, ocean temperatures, or biodiversity loss (**SDG 13, SDG 14 & SDG 15**).

---

## Evaluation

Posters and repositories will be evaluated out of **100 points** based on the following criteria:

1. **Content and Data Storytelling (20 points):**  
   Clarity of the core analytical question, coherence of the narrative, statistical interpretation of patterns, and alignment with the climate theme.
2. **Use of Diverse Visual Encodings (30 points):**  
   Incorporation of at least **3 to 4 distinct graph types** (e.g., temporal trends, bivariate/multivariate distributions, spatial distributions, composition/flow plots, or uncertainty visualizations).
3. **Appropriate Graph Selection & Aesthetic Polish (30 points):**  
   Adherence to graphic grammar principles: optimal data-to-ink ratio, perceptual color palette choices (e.g., accessible/colorblind-safe palettes), appropriate coordinate scaling, explicit handling of uncertainty/variability, and legibility at poster viewing distance.
4. **Reproducible GitHub Repository (20 points):**  
   A fully structured, reproducible project repository documenting the complete analysis pipeline.

The repository must include:
- `README.md` containing the project overview, key takeaways, rendered high-resolution visuals, data dictionary, and exact provenance citations.
- `R/` or scripts directory containing documented, clean `.R` or `.qmd` code files used to extract, process, and plot the data.
- `data/` directory containing raw/tidy datasets (in `.csv` or accessible compressed formats), or executable acquisition scripts for large-scale API pulls.
- `output/` directory containing stand-alone figure exports (in vector `.pdf` or high-dpi `.png` format).

---

## Presentation

* **Date & Time:** Friday, December 25, 2026 | 14:00 – 16:00  
* **Location:** Faculty Foyer  
* **Setup:** All posters must be mounted on the allocated boards at least 15 minutes prior to the session start (**13:45**).

---

## Poster Guidelines

- **Format:** Standard **A1 vertical** ($594 \times 841\text{ mm}$).
- **Identification:** Ensure your **Full Name, Department/Institution, and Contact Email** are visibly positioned in the header area.
- **Attribution:** Dataset sources and reference frameworks must be explicitly credited on the poster canvas.
- **Visual Legibility:** Verify typography scales and vector exports. Avoid blurry raster snapshots; inspect the PDF export at 100% zoom to confirm that axis marks, labels, and legends remain crisp and legible from a standard viewing distance (1–2 meters).
- **Layout Engines:** You may use **Quarto (`typst` or `poster`), R Markdown (`posterdown`), Canva, Illustrator, or PowerPoint** to compose the final layout.
- **Structural Best Practices:** Consult the [BetterPoster framework](https://github.com/GerkeLab/betterposter) for modular, audience-focused visual hierarchies.

---

## Suggested Data Sources

*(You are encouraged to explore any credible, open-access official repository beyond this list.)*

### Curated Domain Data for the Theme
- [Our World in Data – CO2 and Greenhouse Gas Emissions Database](https://github.com/owid/co2-data): Clean, historical country-level emission series, energy mixes, and per-capita indicators.
- [UNFCCC Greenhouse Gas Data Interface](https://di.unfccc.int/detailed_data_by_party): Official national greenhouse gas inventory submissions and historical sectoral breakdowns.
- [World Bank Climate Change Knowledge Portal & Open Data](https://climateknowledgeportal.worldbank.org/): Country-level climate vulnerability, projections, socio-economic risk metrics, and development indicators.
- [Copernicus Climate Change Service (C3S) / ERA5 Reanalysis](https://cds.climate.copernicus.eu/): Gridded surface temperature, precipitation anomalies, and extreme weather datasets.
- [ND-GAIN Matrix (Notre Dame Global Adaptation Initiative)](https://gain.nd.edu/our-work/country-index/): Quantitative country indices comparing climate vulnerability against adaptation readiness.
- [Global Carbon Project (GCP)](https://www.globalcarbonproject.org/): Global, regional, and national carbon budgets, consumption vs. production emissions, and land-use flux.

### Course & General R Repositories
- [Open Datasets Accessible via R Packages](https://github.com/mcavs/R-open-dataset-packages)
- [ITU Mathematical Engineering Data Science Repository](https://github.com/MAT381E-Fall21#data-related-links)

---

### Resources for Visual Design & Inspiration

- **Visualization Techniques & Projects:** [PW-MINI Data Visualization Course Projects](https://github.com/mini-pw/2021Z-DataVisualizationTechniques/tree/master/projects/project1)  
- **Novel R Chart Types & Ideas:** [Awesome R Data Visualization Showcase](https://github.com/krzjoa/awesome-r-dataviz)  
- **Tidyverse & ggplot2 Extensions:** [Awesome ggplot2 Extensions & Toolkits](https://github.com/erikgahner/awesome-ggplot2)  
- **Color Palettes for Scientific Graphics:** [MetBrewer](https://github.com/BlakeRMills/MetBrewer/tree/main) | [PNWColors](https://github.com/jakelawlor/PNWColors) | [wesanderson](https://github.com/karthik/wesanderson) | [scico (Crameri Perceptually Uniform Palettes)](https://github.com/thomasp85/scico)