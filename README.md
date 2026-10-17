# Tech / AI Advancements for the Nature Around Us

A Marp-based slide deck exploring modern artificial intelligence, computer vision, robotics, and IoT applications across indoor and outdoor ecosystems.

---

## 📋 Structure: Residential Focus with Commercial Benchmarks

The presentation traces the 5-stage life cycle of nature and cultivation, with primary emphasis on **Residential Environments** (homes, gardens, yards, and companion animals) alongside **Commercial Counterparts** (broadacre farming, industrial forestry, and city planning):

1. **Why Residential Nature?**
   - 80%+ of personal human-nature interactions occur in our living rooms, backyards, and neighborhoods.
   - Democratization of bio-intelligence: enterprise-grade computer vision and bioacoustics brought directly to consumer devices.
2. **Phase 1: Plan / Observe**:
   - 🏡 **Residential (Focus):** Smartphone botany (PlantNet), backyard bioacoustics (Merlin Bird ID), companion animal health telemetry.
   - 🏢 **Commercial:** Sentinel-2 satellite NDVI passes, soil metagenomics (Biome Makers), municipal LiDAR canopy twins.
   - 🔍 **Real-World Spotlight:** [Bird Safe Philly & iNaturalist](https://www.birdsafephilly.org/report-a-collision) (crowdsourced collision monitoring).
3. **Phase 2: Prepare / Plant**:
   - 🏡 **Residential (Focus):** Indoor hydroponic towers (Rise Gardens), bio-encapsulated seed pods, zip-code native rewilding kits.
   - 🏢 **Commercial:** RTK-GPS autonomous no-till tractors, 40k seed-pod/day drone reforestation swarms.
   - 🔍 **Real-World Spotlight:** [FarmBot](https://farm.bot/) (open-source CNC automated raised-bed farming).
4. **Phase 3: Weed / Trim / Prune**:
   - 🏡 **Residential (Focus):** Boundary-wire-free robotic mowers with wildlife/pet protection, houseplant leaf diagnostic pruning alerts.
   - 🏢 **Commercial:** Carbon Robotics CO₂ laser weeders (5,000 shots/min), See & Spray micro-spray booms.
   - 🔍 **Real-World Spotlights:** [BESTMOW](https://www.bestmow.com/) (autonomous lawn care) & [Tertill](https://tertill.com/) (solar garden weeding robot).
5. **Phase 4: Feed / Fertilize / Water**:
   - 🏡 **Residential (Focus):** Evapotranspiration weather-predictive irrigation (Rachio), in-pot wireless dielectric soil probes.
   - 🏢 **Commercial:** Multispectral drone nitrogen prescription mapping (VRT), tree trunk sap-flow sensors.
   - 🔍 **Real-World Spotlight:** [UgMO Technologies at Longwood Gardens](https://ugmo.com/case-studies/longwood-gardens/) (subsurface root-zone sensor mesh).
6. **Phase 5: Harvest & Post-Harvest Preservation**:
   - 🏡 **Residential (Focus):** Smartphone vine-ripeness and brix alerts, Apeel plant-derived shelf-life extension (2x–3x countertop freshness), smart kitchen composting (Lomi), circular yard mulching.
   - 🏢 **Commercial:** Soft-robotic pneumatic berry pickers, Apeel biomimetic lipid coatings reducing supply chain waste and plastic shrink-wrap, NIR spectroscopy conveyor lines, combine yield telemetry.
   - 🔍 **Real-World Spotlight:** [Burro](https://burro.ai/burro/) (collaborative autonomous harvest mobile robot; Founder & CEO: Charlie Andersen).
7. **Synthesis & Everyday Toolkit**:
   - Direct comparison table and practical, accessible tools under $0, $100, and home system upgrades.

---

## 🚀 How to View & Present

### Option 1: VS Code / Antigravity IDE (Easiest)
1. Install the official **Marp for VS Code** extension (`marp-team.marp-vscode`).
2. Open [`slides.md`](slides.md).
3. Click the **Marp icon** in the top-right corner to toggle real-time preview or export to PDF, HTML, or PPTX.

### Option 2: Marp CLI (Node.js)
Run directly with `npx` (requires an active internet connection to fetch the CLI package on first run):

```bash
# Live preview server with auto-reload
npm run preview
# or:
npx @marp-team/marp-cli -p slides.md

# Export to standalone HTML
npm run build:html

# Export to PDF (requires Chrome / Chromium installed)
npm run build:pdf
```

---

## 🎨 Slide Customization

All styling is embedded cleanly within the frontmatter of [`slides.md`](slides.md):
- **Nature-inspired Color Palette**: Forest greens, emerald highlights, sage accents, and clean card containers.
- **Custom Classes**:
  - `<!-- _class: lead -->` for title / closing splash slides.
  - `<!-- _class: section-divider -->` for high-contrast section intros.
  - `<div class="grid-2">` and `<div class="grid-3">` for modern multi-column card layouts.
  - `<div class="card">` / `<div class="card emerald">` / `<div class="card accent">` for clean content grouping.
  - `<!-- Note: ... -->` for presenter notes.

---
