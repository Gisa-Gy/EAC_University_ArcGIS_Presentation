# Geospatial Technology in Higher Education

**Integrating Esri's ArcGIS Ecosystem into Teaching, Research and Professional Practice**

An interactive, 10-slide HTML presentation prepared by **Esri Rwanda | GIS Specialist** for **EAC University** (10 November 2026).

It explains why GIS matters, how the ArcGIS ecosystem fits together and how lecturers and students can use it in three programmes:

- Bachelor of Education in History and Geography
- Transport and Logistics Management
- Procurement and Supply Chain Management

It also addresses the proposed **150-licence** package.

---

## Quick start

1. Download or clone this repository.
2. Open `EAC_University_ArcGIS_Presentation.html` in a modern browser (Chrome, Edge, Firefox or Safari).
3. Press **F** for full screen and use the **arrow keys** to move between slides.

No installation, server, internet connection or account login is needed. Everything (HTML, CSS, JavaScript and icons) is in the single file. Internet access is only needed to open the external reference links.

### Publish online with GitHub Pages (optional)

1. Rename the file to `index.html` (or keep the name and link to it directly).
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute the presentation is available at `https://<your-username>.github.io/<repository-name>/`.

---

## Controls

| Action | Keyboard | Mouse / touch |
|---|---|---|
| Next slide | `→` or `Page Down` | `›` button, or swipe left |
| Previous slide | `←` or `Page Up` | `‹` button, or swipe right |
| First / last slide | `Home` / `End` | Progress dots |
| Full screen | `F` | Full-screen button |
| Slide list | `M` | Menu button |
| Close slide list | `Esc` | `×` or click outside |

You can also link to a specific slide by adding its number to the address, for example `...Presentation.html#6`.

---

## Slide overview

| # | Slide | Interactive content |
|---|---|---|
| 1 | From Geographic Information to Intelligent Decision-Making | Location → Data → Spatial analysis → Information → Decision workflow, applied to Geography, Transport and Procurement questions |
| 2 | From GIS Fundamentals to the ArcGIS Platform | Ecosystem diagram (ArcGIS Pro, Online, Enterprise, Living Atlas, apps) and a Pro vs Online vs Enterprise comparison |
| 3 | Different Applications. One Connected Geospatial Environment. | 12 application tiles showing function, connections, programme use and example output; Network Analyst shown as a Pro extension |
| 4 | Connecting Applications to Deliver Complete Solutions | Integration architecture, a 5-step urban transport accessibility scenario and the hosted data → service → feature layer → web map → apps chain |
| 5 | From Geographical Theory to Spatial Investigation | Module-to-capability table with example exercises and a schematic land-cover and building-change demonstration |
| 6 | From Transport Networks to Optimised Operations | Route, closest facility, service area, vehicle routing, location-allocation and OD cost matrix, each solved on a schematic network |
| 7 | From Procurement Information to Spatial Supply Chain Intelligence | Warehouse suitability model with adjustable weights and a flood constraint; GIS compared with ERP, inventory and procurement systems |
| 8 | Proven Geospatial Applications: From Professional Practice to Academic Learning | Esri solution areas, the Esri Rwanda project portfolio and seven tangible student outputs |
| 9 | Building a Sustainable Geospatial Learning Environment at EAC University | Institutional model, seven implementation deliverables, ArcGIS user types and a 150-licence allocation planner |
| 10 | Building Geospatial Competence Through Academic Partnership | Key messages, next steps and official Esri references |

---

## Customisation

Open the HTML file in a text editor and search for these settings near the top of the script.

**Official Esri application icons** — the tiles use generic icons by default. If you hold authorised icon files, place them in the repository and map them:

```js
var OFFICIAL_APP_ICONS = {
  pro: 'icons/arcgis-pro.svg',
  online: 'icons/arcgis-online.svg'
  // keys: pro, online, story, dash, exb, instant, s123, fm, la, ce, urban, na
};
```

**Esri Rwanda project visuals (slide 8)** — add authorised screenshots:

```js
var PROJECT_IMAGES = {
  vision: 'images/vision-city.png'
  // keys: vision, bus, signs, bcd, insp, forest
};
```

Only add images you are authorised to share publicly, especially if the repository is public.

---

## Accuracy notes

- Maps, networks, routes, site scores and building counts are **illustrative or schematic** and are labelled as such. They are not results from live data or Kigali's real road network.
- Licensing statements follow Esri's published user-type documentation, including the June 2025 user-type update. Final licence allocation, extensions, credits and premium services should be confirmed with Esri Rwanda.
- The 150-licence allocation planner shows an **example for discussion only**, not a quotation.
- Esri Rwanda projects are described only by capability area. No project results or figures are reported.

---

## Official references

| Topic | Link |
|---|---|
| ArcGIS Pro documentation | https://pro.arcgis.com/en/pro-app/latest/ |
| Introduction to ArcGIS Online | https://doc.arcgis.com/en/arcgis-online/get-started/what-is-agol.htm |
| ArcGIS Enterprise documentation | https://enterprise.arcgis.com/en/ |
| ArcGIS Living Atlas of the World | https://livingatlas.arcgis.com/ |
| ArcGIS StoryMaps | https://doc.arcgis.com/en/arcgis-storymaps/ |
| Dashboard data sources | https://doc.arcgis.com/en/dashboards/latest/get-started/understand-data-sources.htm |
| ArcGIS Experience Builder | https://doc.arcgis.com/en/experience-builder/ |
| Introduction to ArcGIS Instant Apps | https://doc.arcgis.com/en/instant-apps/latest/get-started/about-instant-apps.htm |
| ArcGIS Survey123 | https://doc.arcgis.com/en/survey123/ |
| ArcGIS Field Maps | https://doc.arcgis.com/en/field-maps/ |
| ArcGIS Urban | https://doc.arcgis.com/en/urban/ |
| ArcGIS CityEngine | https://doc.arcgis.com/en/cityengine/ |
| ArcGIS Network Analyst extension | https://pro.arcgis.com/en/pro-app/latest/help/analysis/networks/what-is-network-analyst-.htm |
| Network Analyst credit consumption | https://pro.arcgis.com/en/pro-app/3.4/help/analysis/networks/credit-consumption-and-analysis-limits.htm |
| World Imagery Wayback | https://livingatlas.arcgis.com/wayback/ |
| Esri Land Cover | https://livingatlas.arcgis.com/landcover |
| ArcGIS Online user types | https://doc.arcgis.com/en/arcgis-online/administer/user-types-orgs.htm |
| 2025 ArcGIS user type updates | https://www.esri.com/en-us/c/product/2025-user-type-updates |
| ArcGIS Solutions | https://www.esri.com/en-us/arcgis/products/arcgis-solutions/overview |
| Esri Education | https://www.esri.com/en-us/industries/education/overview |
| Esri Higher Education Licensing | https://www.esri.com/en-us/industries/higher-education/licensing |

---

## Technical details

- Single self-contained HTML file (about 200 KB) with embedded CSS and JavaScript; no frameworks or external libraries.
- 16:9 layout designed at 1600 × 900 and scaled to fit laptops, desktop monitors and projectors.
- Tested at 1280 × 800, 1366 × 768, 1600 × 900 and 1920 × 1080 with no layout overflow or JavaScript errors.
- Hidden slides are made inert so keyboard focus stays on the current slide; animations respect the system "reduce motion" setting.

---

## Credits and trademarks

- Prepared by **Esri Rwanda | GIS Specialist** for **EAC University**.
- Interface icons: [Lucide](https://lucide.dev) (ISC licence). They are generic icons, not official Esri product logos.
- Esri, ArcGIS, ArcGIS Pro, ArcGIS Online, ArcGIS Enterprise, ArcGIS StoryMaps, ArcGIS Survey123, ArcGIS Field Maps, ArcGIS Living Atlas, ArcGIS CityEngine, ArcGIS Urban and related names are trademarks or registered trademarks of Esri. This presentation is an educational resource and does not imply endorsement by EAC University.
