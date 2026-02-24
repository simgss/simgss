<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=700&size=32&duration=3000&pause=1000&color=4FC3F7&center=true&vCenter=true&multiline=true&repeat=false&width=700&height=80&lines=Simcha+Levental" alt="Simcha Levental" />
</h1>

<h3 align="center">Full-Stack GeoAI Engineer Â· Spatial Systems Â· Applied AI Â· Builder</h3>

<p align="center">
  <a href="https://geospatialsolutions.co"><img src="https://img.shields.io/badge/geospatialsolutions.co-0A0A0A?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website"/></a>
  <a href="https://github.com/simgss"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  <a href="mailto:simcha@geospatialsolutions.co"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Washington,_DC-blue?style=for-the-badge&logo=google-maps&logoColor=white" alt="Location"/>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=simgss&style=flat-square&color=4FC3F7" alt="Profile Views"/>
</p>

---

## `> whoami`

I build **spatial intelligence systems** that move from raw geographic data to deployable, AI-powered products.

My work lives at the intersection of **spatial databases**, **computer vision**, **async backend systems**, and **map-first product interfaces**. I am deeply curious about how physical reality becomes structured dataâ€”and how that data becomes decisions at scale.

> *I don't just analyze maps. I engineer systems that reason over geography.*

---

## âš¡ Philosophy

```
I believe two things can be true at the same time:

  1. Engineering should be playful, curious, and experimental.
  2. Results are non-negotiable.
```

I experiment aggressively. I measure ruthlessly. I ship systems that work in the real world.

**Curiosity drives exploration. Results decide what survives.**

---

## ðŸ—ï¸ What I Build

I design production systems where **geography is not a visualization layerâ€”it is the data model.**

```
Raw spatial data
  â†’ Structured spatial contracts
    â†’ AI inference
      â†’ Operational decisions
        â†’ Exportable, measurable outcomes
```

| Domain | What I Ship |
|---|---|
| **Spatial Databases** | Scalable PostGIS architectures with GiST indexing, CRS discipline, geometry contracts |
| **GeoAI Pipelines** | End-to-end inference: imagery â†’ segmentation â†’ detection â†’ entity binding |
| **Async Backends** | FastAPI + workers + webhooks for non-blocking, event-driven orchestration |
| **Map-First Products** | Interactive UX built on Mapbox GL & Leaflet with drill-down analytics |
| **Automation** | n8n + scheduled pipelines + Power Automate for repeatable spatial workflows |
| **Decision Dashboards** | Routing engines, lead intelligence, and operational tools for non-GIS users |

> *I don't build demos. I build infrastructure disguised as products.*

---

## ðŸš€ Case Study: LeadZone
### GeoAI Lead Intelligence Platform

**`Imagery â†’ AI Detection â†’ Address-Level Prospect Lists`**

LeadZone transforms satellite imagery and building footprints into verified, export-ready, address-linked leads. The core engineering challenge: **turning pixels into business-ready entities.**

<details>
<summary><b>ðŸ“Š Performance Signals</b></summary>
<br>

| Metric | Value |
|---|---|
| AOI coverage per job | Up to **0.5 sq mi** |
| Geometries per run | **Thousands** of building-level classifications |
| Solar detection confidence | **85â€“95%** |
| Pool detection confidence | **90â€“95%** |
| Spatial filtering (GiST) | **Sub-second** |
| UX blocking | **Zero** â€” fully async inference |

</details>

<details>
<summary><b>ðŸ”§ Engineering Challenges Solved</b></summary>
<br>

- Converting pixels into address-linked business entities
- Maintaining reproducibility for identical AOIs
- Normalizing CRS inconsistencies across datasets
- Binding model inference to real-world parcels
- Designing export schemas usable by non-GIS teams

</details>

<details>
<summary><b>ðŸ›ï¸ Architecture</b></summary>
<br>

```
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€ FRONTEND â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚  React + TypeScript Â· Mapbox GL      â”‚
â”‚  AOI Drawing Â· Building Drill-Down   â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¬â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
               â”‚
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â–¼â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚           BACKEND (FastAPI)          â”‚
â”‚  Async Endpoints Â· Job Workers       â”‚
â”‚  PostGIS Spatial Core                â”‚
â”‚  Webhook Orchestration               â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¬â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
               â”‚
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â–¼â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚             GeoAI LAYER              â”‚
â”‚  SAM Segmentation Â· YOLO Detection   â”‚
â”‚  Confidence Calibration              â”‚
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
```

</details>

<details>
<summary><b>ðŸ” Example Flow â€” Solar Detection</b></summary>
<br>

```
1. User geocodes location
2. Draws AOI polygon on map
3. System fetches imagery + building footprints
4. Runs SAM segmentation + YOLO detection
5. Matches detections to parcel/address data
6. Persists classification in PostGIS
7. Renders color-coded geometry on map
8. Generates CSV / GeoJSON export
```

```sql
-- Spatial index query powering sub-second filtering
SELECT b.building_id, b.geom
FROM buildings b
WHERE ST_Intersects(
  b.geom,
  ST_GeomFromText(:aoi_wkt, 4326)
);
```

</details>

---

## ðŸ§  Experimentation Lab

I treat engineering like structured play. I prototype fast, discard quickly, and keep what produces **measurable improvement.**

> *Curiosity without metrics is wandering. Metrics without curiosity is stagnation.*

| Experiment | Domain |
|---|---|
| AOI tiling strategies for inference scaling | ðŸ—ºï¸ Spatial |
| PostGIS performance benchmarking under heavy geometry load | âš¡ Performance |
| GeoParquet vs PostGIS tradeoff analysis | ðŸ“Š Data |
| Async orchestration latency measurements | ðŸ”§ Backend |
| Spatial clustering explainability tests | ðŸ¤– AI |
| LLM-generated spatial summaries for executives | ðŸ¤– AI |
| Map rendering stress tests under high feature density | ðŸ—ºï¸ Spatial |
| Agentic GIS pipelines (n8n + LLM + PostGIS) | ðŸ¤– Automation |
| Human-in-the-loop QA feedback loops for model validation | âœ… Quality |

I design every system with: **stable API contracts Â· schema discipline Â· logging & audit trails Â· performance instrumentation Â· repeatable workflows Â· clear export formats.**

*Everything should be explainable. Everything should be reproducible.*

---

## ðŸ› ï¸ Technical Stack

<table>
<tr>
<td align="center" width="20%">

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Mapbox](https://img.shields.io/badge/Mapbox_GL-000000?style=flat-square&logo=mapbox&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white)

</td>
<td align="center" width="20%">

**Backend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

</td>
<td align="center" width="20%">

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![PostGIS](https://img.shields.io/badge/PostGIS-336791?style=flat-square&logoColor=white)
![GDAL](https://img.shields.io/badge/GDAL-5CAE58?style=flat-square&logoColor=white)

</td>
<td align="center" width="20%">

**AI / CV**

![SAM](https://img.shields.io/badge/SAM-FF6F00?style=flat-square&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=flat-square&logoColor=black)
![CVAT](https://img.shields.io/badge/CVAT-0000FF?style=flat-square&logoColor=white)

</td>
<td align="center" width="20%">

**DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI/CD-2088FF?style=flat-square&logo=github-actions&logoColor=white)

</td>
</tr>
</table>

---

## ðŸ“ˆ GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=simgss&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=4FC3F7&icon_color=4FC3F7&text_color=C9D1D9" width="49%" alt="GitHub Stats"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=simgss&theme=tokyonight&hide_border=true&background=0D1117&ring=4FC3F7&fire=4FC3F7&currStreakLabel=4FC3F7" width="49%" alt="GitHub Streak"/>
</p>

---

## ðŸ¤ Let's Connect

I'm looking for **high-caliber engineering teams** that value deep systems thinking, measured experimentation, and real-world accountability.

**If you're working on:**

`AI Infrastructure` Â· `Applied ML Products` Â· `Spatial Systems` Â· `High-Scale Backend Architecture` Â· `Routing & Logistics Engines` Â· `Data-Heavy Platforms`

<p align="center">
  <a href="mailto:simcha@geospatialsolutions.co">
    <img src="https://img.shields.io/badge/Let's_Talk-4FC3F7?style=for-the-badge&logo=gmail&logoColor=white" alt="Let's Talk"/>
  </a>
</p>

---

<p align="center"><sub>âš¡ <i>"I experiment aggressively. I measure ruthlessly. I ship systems that work in the real world."</i></sub></p>
