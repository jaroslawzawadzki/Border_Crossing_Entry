# 🚛 US Border Crossing Freight \& Logistics Analysis (EDA)

An end-to-end Exploratory Data Analysis (EDA) examining commercial truck freight volume across US land borders (US-Mexico \& US-Canada). The project investigates high-volume bottlenecks, annual seasonality trends, and geographic freight corridors to provide actionable supply-chain recommendations for freight operators.

\---

## 📌 Executive Summary \& Key Findings

### 1\. Critical Chokepoints (Top 10 Ports)

* **Southern Border Dominance:** Cross-border freight on the US-Mexico border is heavily concentrated in a few high-throughput ports: **Laredo**, **Otay Mesa**, and **El Paso**, with **Laredo, TX** serving as the primary commercial gateway.
* **Northern Border Distribution:** US-Canada truck freight shows a more balanced geographic distribution across key hubs such as **Detroit (MI)**, **Buffalo-Niagara Falls (NY)**, and **Port Huron (MI)**.

### 2\. Seasonality \& Operational Planning

* **Q1 Lull (January – February):** Traffic reaches its annual trough during the first two months of the year.

  * *Business Action:* Optimal window for fleet maintenance, carrier capacity adjustments, and driver vacation scheduling.
* **Bi-Modal Volume Peaks (March \& October):** Significant spikes occur in March (spring inventory restocking) and October (holiday season / Black Friday pre-fulfillment).

  * *Business Action:* Buffer lead times must be expanded during these months to mitigate cross-border clearance delays and contractual SLA penalties.
* **December Drop-off:** Rapid deceleration in freight movements due to fiscal year closures and manufacturing shutdowns.

### 3\. Geographic Hubs vs. Resilient Relief Corridors

* **Texas \& Michigan** represent the core operational pillars of cross-border trade, absorbing the vast majority of volume.
* Under-utilized transit states (e.g., New Mexico, Idaho, Montana) serve as strategic secondary/emergency bypass corridors during customs strikes, congestion surges, or severe weather disruptions.

\---

## 🛠️ Tech Stack \& Methodology

* **Language:** Python 3.x
* **Libraries:** `pandas`, `matplotlib`, `seaborn`
* **Data Quality \& Integrity:**

  * Analyzed a comprehensive dataset of 346,000+ records.
  * Verified 100% data completeness (zero unhandled `NaN` or `Unknown` entries across critical categorical features).
  * Standardized multi-format timestamp parsing for time-series extraction.

\---

## 📊 Visualizations Included

1. **Top 10 Busiest Truck Ports:** Comparative bar plots highlighting market share by border.
2. **Annual Seasonality Curve:** Aggregated monthly average truck count identifying peak freight cycles.
3. **State-Level Corridor Distribution:** State-by-state commercial traffic comparison.

\---

## 🚀 How to Run Locally

```bash
# 1. Clone the repository
git clone \[https://github.com/jaroslawzawadzki/Border\_Crossing\_Entry.git](https://github.com/jaroslawzawadzki/Border\_Crossing\_Entry.git)
cd Border\_Crossing\_Entry

# 2. Install dependencies
pip install pandas matplotlib seaborn jupyter

# 3. Launch the notebook
jupyter notebook

