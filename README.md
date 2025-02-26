# Waste-analysis-worldwide
**Report: Analysis of Waste Composition and Management Trends**

<h2 align="left"></h2>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="30" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="30" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="30" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="30" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" height="30" alt="jupyter logo"  />
</div>

###

<div align="left">
</div>

###

###

**1. Data Acquisition and Initial Exploration**  
The analysis begins by importing essential data manipulation and visualization libraries. The dataset on municipal waste composition is loaded, and initial exploration includes displaying the first few rows, dataset dimensions, data types, missing values, and descriptive statistics. This step ensures a foundational understanding of the dataset's structure, including variables like country, waste materials (e.g., plastics, paper), and their quantities.

**2. Data Cleaning and Preparation**  
Redundant columns (e.g., footnotes) are removed to streamline the dataset. Duplicate column names are resolved by appending suffixes, ensuring clarity. Columns representing waste quantities are converted to numeric types, and missing values are replaced with zeros to facilitate numerical analysis. This phase ensures data consistency and reliability for downstream tasks.

**3. Country-Level Waste Production Analysis**  
Data is aggregated by country to calculate total production for each waste material. A stacked bar chart visualizes these totals, highlighting countries with the highest waste generation. Top-performing countries for specific materials (e.g., plastics) are identified, offering insights into regional waste patterns. A correlation matrix reveals relationships between material types, such as whether higher paper waste correlates with glass waste.

**4. Hazardous Waste Trend Analysis**  
Additional datasets on hazardous waste (per capita and total) and municipal waste collection are integrated. Time-series data for hazardous waste is reshaped into a long format, enabling trend analysis. Line charts illustrate per capita hazardous waste trends across countries, emphasizing changes over time and variations between nations.

**5. Recycling and Treatment Correlation Study**  
Municipal waste composition data is merged with recycling rates to explore linkages. Key metrics (e.g., plastic waste percentage vs. recycling rates) are converted to numeric formats, and missing values are addressed. A heatmap visualizes correlations, identifying whether higher proportions of specific materials correspond to increased recycling efforts.

**6. Focus on Plastic Waste and Final Visualizations**  
The latest available year's plastic waste data is highlighted in a bar chart, showcasing country-specific contributions. Hazardous waste trends are replotted with enhanced formatting for clarity. Visualizations include rotated labels, legends, and titles to improve readability.

**7. Robustness and Error Handling**  
Throughout the analysis, checks ensure critical columns (e.g., "Country") are present. File availability is verified, and errors are gracefully handled to prevent runtime interruptions. Numeric conversions and missing value checks further enhance data integrity.

###

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=ayushiiGeoradverse3&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false" height="150" alt="languages graph"  />
</div>

###

