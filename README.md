# Exploratory Data Analysis with Python

Materials for the **Python in Practice** workshop series, Dartmouth Research Computing.

## Contents

| File | What it is |
|---|---|
| `eda_workshop.ipynb` | Follow-along notebook with prompts and empty code cells. Open this one during the workshop. |
| `eda_workshop_complete.ipynb` | Finished notebook with all code and explanations. |
| `data/penguins.csv` | Palmer Penguins dataset (344 penguins, 8 variables). |

## Getting started on Discovery (Open OnDemand)

1. Log in to Open OnDemand and start a Jupyter session.
2. Open a terminal (File → New → Terminal) and run:

   ```bash
   git clone <REPO-URL>
   ```

3. In the Jupyter file browser, open the cloned folder, then open `eda_workshop.ipynb`.

## About the data

The Palmer Penguins data were collected by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER,
a member of the Long Term Ecological Research Network.

Horst AM, Hill AP, Gorman KB (2020). *palmerpenguins: Palmer Archipelago (Antarctica) penguin data.*
R package version 0.1.0. https://allisonhorst.github.io/palmerpenguins/

| Variable | Description |
|---|---|
| `species` | Penguin species (Adelie, Chinstrap, Gentoo) |
| `island` | Island in the Palmer Archipelago (Biscoe, Dream, Torgersen) |
| `bill_length_mm` | Bill length (millimeters) |
| `bill_depth_mm` | Bill depth (millimeters) |
| `flipper_length_mm` | Flipper length (millimeters) |
| `body_mass_g` | Body mass (grams) |
| `sex` | Penguin sex (female, male) |
| `year` | Study year (2007, 2008, 2009) |
