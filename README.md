# Environmental Overshoot Data Story

This is a sophomore-friendly data science project that combines environmental footprint data with sustainable energy indicators.

## Research Question

Do wealthier and more energy-intensive countries tend to have larger ecological deficits?

## Datasets

Download these from Kaggle:

1. **2016 Global Ecological Footprint**  
   https://www.kaggle.com/datasets/footprintnetwork/ecological-footprint

2. **Global Data on Sustainable Energy 2000-2020**  
   https://www.kaggle.com/datasets/anshtanwar/global-data-on-sustainable-energy

The ecological footprint dataset is the main dataset. The sustainable energy dataset is optional but makes the project more impressive because it lets you connect ecological overshoot to energy use, renewable energy, CO2 emissions, and GDP.

## How to Use

1. Download the CSV files from Kaggle.
2. Put the CSV files in the same folder as `environmental_overshoot_data_story.ipynb`, or create a `data/` folder next to the notebook and put them there.
3. Open the notebook in Jupyter, Kaggle Notebooks, or Google Colab.
4. Run the cells from top to bottom.
5. If a package import fails, run the notebook's install cell.

## What the Notebook Does

- Loads and auto-detects the Kaggle CSV files
- Cleans country names and numeric columns
- Calculates ecological deficit and ecological reserve
- Visualizes countries with the largest deficits and reserves
- Shows ecological footprint vs. biocapacity
- Examines the role of carbon footprint
- Optionally merges energy data for 2016
- Creates GDP, energy use, renewable energy, and CO2 visualizations
- Includes an optional simple machine learning model
- Produces draft findings for the final write-up

## Suggested Project Title

**Global Ecological Overshoot: How Energy Use and Economic Development Relate to Environmental Deficits**

## Final Claim to Explore

Many countries that appear economically developed may still be environmentally unsustainable because their consumption exceeds local ecological capacity. The project explores how much of that pressure is connected to carbon emissions, energy use, and income.
