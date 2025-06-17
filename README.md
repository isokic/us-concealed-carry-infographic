# # us-concealed-carry-infographic

"The Great Gun Law Experiment," Visualizing the evolution of U.S. concealed carry laws (1981–2021) alongside violent crime trends. Includes choropleth maps, historical timeline, and a multi-layered time series chart.

**Authors**: Nejc Kolčarš, Ivan Šokić ([@isokic](https://github.com/isokic)

---

## 📌 Overview

"The Great Gun Experiment" visualizes the liberalization of U.S. concealed carry (CCW) laws from 1981 to 2021, mapping state-level policy shifts alongside national violent crime trends. This infographic project explores whether expanded gun rights correlate with changes in crime rates, shedding light on public perception, legislative drivers, and the debate over causality. It aims to inform discussions on gun policy through data-driven storytelling.

---

## 📊 Visualizations Included

- **Choropleth Maps** (1981, 1991, 2001, 2011, 2021):  
  Illustrate the spread of CCW laws across U.S. states, from 5 shall-issue states in 1981 to 22 permitless states in 2021, highlighting liberalization trends.
- **Legal Trajectory Line Plot**:  
  Tracks the number of states in each CCW category (prohibited, may-issue, shall-issue, permitless) over time, showing policy shifts.
- **Historical Timeline**:  
  Marks key events (e.g., Florida’s 1987 shall-issue law, *Heller* 2008) shaping gun law debates.
- **Multi-line Crime Trend Chart**:  
  Compares gun circulation with murder, robbery, rape, and aggravated assault rates, exploring crime trends alongside CCW expansion.

**Key Insight**:  
> *"Most gun crime is likely committed by those who illegally possess guns."* — *PolitiFact, 2018*

---

## 🧰 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `geopandas`
- `matplotlib.colors`
- `os`
- `math`

---

## 📁 File Structure

| File | Description |
|------|-------------|
| `The Great Gun Law Experiment.pdf` | Final full infographic |
| `map_1981.svg` to `map_2021.svg` | Individual vector maps |
| `crime_trend_chart.svg` | Violent crime and gun trend line graph |
| `data/` | Processed CSVs (crime, laws, population) |
| `README.md` | This documentation |
| `sources.md` *(optional)* | Full source citations if not embedded |

---
 
## 📊 Data Sources

- **Concealed Carry Laws**  
  [RAND Corporation Gun Policy in America](https://www.rand.org/research/gun-policy.html)
  [National Rifle Association - Institute for Legislative Action](https://www.nraila.org/gun-laws/state-gun-laws/)
  [United States Concealed Carry Association](https://www.usconcealedcarry.com/resources/ccw_reciprocity_map/)
  [Wikipedia: Concealed Carry in the United States](https://en.wikipedia.org/wiki/Concealed_carry_in_the_United_States)
  [Giffords Law Center to Prevent Gun Violence](https://giffords.org/lawcenter/gun-laws/policy-areas/guns-in-public/concealed-carry/)
  [Everytown for Gun Safety](URL: https://www.everytown.org/issues/concealed-carry/)

* **Crime Data**
  [DisasterCenter: U.S. Crime Rates](https://www.disastercenter.com/crime/uscrime.htm)
  [FBI Uniform Crime Reports](https://bjs.ojp.gov/data-collection/ucr-uniform-crime-reporting-program)
  [Politifact](https://www.politifact.com/factchecks/2018/mar/12/john-faso/do-illegal-gun-owners-commit-most-gun-crime-rep-fa/)

* **U.S. Population Estimates**
  [Wikipedia Summary Table](https://en.wikipedia.org/wiki/List_of_U.S._states_and_territories_by_population)
  [U.S. Census Bureau](https://www.census.gov/data.html)

* **Firearm Production and Circulation**
  [ATF Firearms Commerce Reports](https://www.atf.gov/resource-center/firearms-commerce-united-states)
  [The Trace Analysis of ATF Firearms Data](https://www.thetrace.org/2023/03/guns-america-data-atf-total/)

* **State Gun Law Descriptions**
  [NRA-ILA State Gun Law Summaries](https://www.nraila.org/gun-laws/state-gun-laws/)

* **Geospatial Data**
  [Natural Earth – Admin 1 States & Provinces](https://www.naturalearthdata.com/downloads/10m-cultural-vectors/)

---

## 🔗 QR Code Access

The infographic includes a QR code linking to this repository ([github.com/your-username/us-concealed-carry-infographic](https://github.com/your-username/us-concealed-carry-infographic)) for open access and data exploration.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the work with proper attribution.
