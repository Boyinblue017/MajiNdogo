# Maji Ndogo Water Access & Safety Dashboard

An interactive Power BI report exploring water access in the fictional country of **Maji Ndogo**, covering water source types, queue times, well contamination, and the gender dimension of crime linked to water collection.

> **Live report:** [View on Power BI Service](#) [<!-- TODO: add link -->](https://app.powerbi.com/links/ENBYBE2JbW?ctid=7d9bbdf0-cda7-4b0c-9941-0006b9007fa7&pbi_source=linkShare)

---

## Overview

Access to safe, reachable water shapes daily life: who walks to collect it, how long they wait, and what risks they face along the way. This project brings together data on water sources, queues, well quality, and crime to tell that story across five provinces: **Kilimani, Akatsi, Sokoto, Amanzi, and Hawassa**.

The report is organised into four themes, each answering a different question:

1. **Who bears the burden?** Gender trails in water collection and crime
2. **Where does water come from?** Source types, people served, and rural vs urban split
3. **How long do people wait?** Queue times by province, day, and hour
4. **How safe is the water?** Well pollution status by province

## Key Findings

| Theme | Insight |
|---|---|
| Gender | **69%** of water collectors are women, and **64%** of victims in water-collection-related crimes are women |
| Crime by gender | Female victims account for ~64% of recorded crimes, male ~25%, and the **C** category ~10% |
| Crime types | Harassment and sexual assault show the widest gender gaps, with far more female victims than male |
| Provinces | **Kilimani** and **Akatsi** record the most crimes; **Amanzi** is the only province where male victims outnumber female |
| Timing | Crimes dip around midday and **climb through the evening**, peaking near 10 PM; Friday is the highest day |
| Water sources | **Wells** are the most common source type (~17.5K), followed by broken in-home taps, shared taps, and rivers |
| Rural vs urban | Roughly two thirds of people served are in **rural** areas |
| Queues | **Saturday** has the longest average queue (~246 min) and **Sunday** the shortest (~82 min); Kilimani has the highest total queue time (~1M minutes) |
| Well quality | Only **~28%** of wells are clean; **~41%** are chemically contaminated and **~31%** biologically contaminated |
| Province quality | Akatsi has the most clean wells, while Kilimani and Hawassa have a high share of biological contamination |

*Figures are read from the dashboard visuals and rounded.*

## Dashboard Pages

### 1. Maji Ndogo Report: Gender Trails
- Headline KPIs on women's share of water collection and of crime victimisation
- Crimes by hour of day, by province, and gender disparity by crime type (harassment, theft, sexual assault, public intoxication, severe assault, vandalism, murder)

### 2. Water Sources
- Province map
- Treemap of people served by water source type
- Rural vs urban split of people served
- Number of water sources by type
- Water source type breakdown across 24 towns

### 3. Queue Times
- Queue composition (donut chart)
- Total time spent in queues by province
- Average shared-tap queue times by hour, split by day of week
- Average queue time per day of week

### 4. Well Pollution
- Share of wells that are clean, chemically contaminated, or biologically contaminated
- Well status by province

### 5. Crime Deep Dive
- Crimes by province, crime type, hour of day, and day of week, broken down by gender/category
- Overall gender disparity in crime

## Tools & Skills

- **Power BI Desktop** for data modelling, DAX measures, and visual design
- **Power BI Service** for publishing and sharing
- <!-- TODO: add anything else you used, e.g. SQL, Power Query, Excel, Python -->

Techniques demonstrated: custom shape-map visuals, stacked and clustered charts, treemaps, time-series line charts, KPI cards, and multi-page report design.

## Data

The data is from the Maji Ndogo water access project dataset. <!-- TODO: add source/course name and link, plus a note on what the C/F/M categories stand for -->

## Repository Contents

```
├── README.md
├── MajiNdogo.pbix        <!-- TODO: add if sharing the file -->
├── MajiNdogo1.pdf        # Static export of the report
└── screenshots/          <!-- TODO: add page screenshots -->
```

## How to View

- **Online:** open the Power BI Service link at the top of this README
- **Locally:** download the `.pbix` file and open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
- **Quick look:** see the PDF export or the screenshots folder

## Author

**Gid** · Data Science Student, Kenya
<!-- TODO: add GitHub, LinkedIn, and portfolio website links -->

## Acknowledgements

Built as an academic project. <!-- TODO: add course, institution, or instructor credit if applicable -->
