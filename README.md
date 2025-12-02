# HWK #5 – Homicides

Author: **Melanie Luu**  
Course: R Programming for Research  

This repository contains my work for **Homework #5**, using the Washington Post homicide dataset.

---

## Homework choice

I completed **Choice 2**:

> Recreate the graph of monthly homicides in **Baltimore**, with:
> - A vertical reference line for the arrest of Freddie Gray  
> - Color indicating colder months (November–April) vs warmer months (May–October)  
> - A smooth line to highlight seasonal and long-term trends

The final figure and all code are in `writing/hwk5-homicides.Rmd`, and the rendered PDF is `writing/hwk5-homicides.pdf`.

---

## Repository structure

- `data/`  
  - `homicide-data.csv` – Washington Post homicide dataset  
- `figures/`  
  - (empty in this homework – plots are rendered inside the R Markdown/PDF)
- `writing/`  
  - `hwk5-homicides.Rmd` – main analysis and code for the homework  
  - `hwk5-homicides.pdf` – knitted PDF output
- `hw5-homicides.Rproj` – RStudio project file  
- `.gitignore` – ignores temporary and IDE files

---

## How to reproduce the analysis

1. Clone this repository:

   ```bash
   git clone https://github.com/me0wanie/hwk5-homicides.git
   cd hwk5-homicides
