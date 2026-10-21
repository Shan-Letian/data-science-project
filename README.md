# Multi-Dataset Exploratory Data Analysis and Visualization

## Problem / Research Question
How can different statistical visualization techniques (box plots, heatmaps, violin plots, regression plots, etc.) be effectively applied to uncover hidden patterns, trends, and relationships across diverse real-world datasets? 

## Dataset Sources and Usage Permissions
This project utilizes multiple publicly available datasets for educational and analytical purposes:
1. **GISS Surface Temperature Analysis:** Global surface temperature anomalies (public domain).
2. **Flight Passengers Data:** Monthly airline passenger numbers (public domain).
3. **Rotten Tomatoes Movie Scores:** Movie critic and audience scores (public data).
4. **YouTube Top 30 Music Channels:** Subscriber and view counts (as of Jan 2020, public data).
5. **Animal Longevity & Body Mass Dataset:** Public biological dataset.
6. **NY State Education & Salary Data:** Survey data of 500 individuals (public educational dataset).

## Methods and Tools Used
- **Language:** Python
- **Libraries:** Pandas (data manipulation), Matplotlib (base plotting), Seaborn (statistical data visualization), Squarify (treemaps).
- **Techniques:** 
  - Categorical comparison (Box plots, Violin plots)
  - Correlation and regression analysis (Regplot)
  - Time-series and matrix visualization (Heatmaps)
  - Multi-panel visualization (FacetGrid)
  - Hierarchical data representation (Treemaps)

## Key Findings and Limitation
**Key Findings:**
- **Climate:** The heatmap reveals a clear upward trend in surface temperature anomalies over recent decades.
- **Demographics:** Violin plots indicate that higher education levels correlate with higher annual salaries but also wider variance in working hours.
- **Biology:** Linear regression shows a positive correlation between animal body mass and maximum longevity.

**Limitation:**
These exercises focus on exploratory visualization rather than rigorous statistical hypothesis testing or causal inference. The datasets are pre-cleaned for educational purposes; thus, the visualizations might not account for confounding variables present in the raw real-world data.

## Instructions for Running the Analysis
1. Clone this repository to your local machine.
2. Ensure you have Python installed (version 3.8+ recommended).
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
