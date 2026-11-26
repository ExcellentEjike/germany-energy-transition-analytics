# Germany's Energy Transition Analytics
> **Central Analytical Question:** How are renewable electricity generation, electricity consumption, and wholesale market prices related in Germany?

This repository tracks and analyzes the intersection of renewable energy penetration, national grid demand, and pricing dynamics within the German wholesale electricity market.

## Project Structure

├── data/          # Raw and processed energy data (parquets, CSVs)

├── figures/       # Visualizations, trend lines, and correlation plots

├── notebooks/     # Jupyter Notebooks for EDA and statistical workflows

├── presentation/  # Final slides, dashboards, and reporting summaries

└── sql/           # Query scripts for data aggregation and ETL

## Key Investigative Questions
1. **Generation Mix Transformation:** How has the electricity generation mix changed between 2023 and 2024?
2. **Consumption Dynamics:** What are the daily, monthly, and seasonal electricity consumption patterns?
3. **Pricing Correlations:** How does renewable generation market share relate to wholesale electricity prices?
4. **Market Volatility:** When do negative electricity prices occur most frequently, and what triggers them?
5. **Strategic Insights:** What data-driven recommendations can be derived for energy planning and flexible electricity consumption?

## Data Sources
*Data used in this project is collected from public energy reporting APIs and transparency platforms:*
* **SMARD.de** (Federal Network Agency / Bundesnetzagentur) for actual generation, consumption, and market prices.
* **ENTSO-E** Transparency Platform for cross-border physical electricity flows.

## Tech Stack & Tooling
* **Storage & Infrastructure:** DuckDB / SQLite (via `/sql` workflows)
* **Analysis & Analytics:** Python 3.x, Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn, Plotly

## Quick Start & Setup
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/ExcellentEjike/germany-energy-transition-analytics.git
