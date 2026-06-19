# Spatial Data Operations — John Snow's 1854 Cholera Outbreak

Graduate coursework — Emory MPH, BIOS 532 (Spatial Analysis). Core spatial data-wrangling in R, using the classic John Snow cholera dataset.

## What it covers
- Importing Excel/CSV data with `rio`
- Converting coordinate tables into `sf` spatial data and projecting to British National Grid (EPSG:27700)
- Stacking/concatenating layers, table joins, and attribute-based selection

## Tools
R · Quarto · `sf` · `rio` · `tmap` · `tidyverse`

## Data
John Snow cholera deaths by outbreak period, water-pump locations, and Soho neighborhood polygons + census (`data/`). Source: data shared by Dr. Julie Clennon, Emory University.

## How to run
Open `project.Rproj` in RStudio and render `data_operations_Abdul-Rahman.qmd`. Rendered output: `data_operations_Abdul-Rahman.html`.

## Credit
Completed as a course lab. Lecture/template scaffolding provided by course staff (A. Edwards); lab analysis by Omar Abdul-Rahman.
