# Toronto Civic Vitality & Urban Inequality Dashboard 🏙️📊

[![Live App](https://img.shields.io/badge/Live_Demo-View_App-blue?style=for-the-badge)](https://civic6.shinyapps.io/sta313_final/)

An interactive, web-based data visualization product built with **R** and **Shiny**. This dashboard provides a responsive platform for stakeholders to explore the multidimensional relationships between cultural funding, museum access, and community demographics across Toronto.

## 🚀 Project Overview

Urban vitality relies on equitable access to civic resources. This project transforms complex municipal datasets into an accessible analytical tool. By leveraging reactive programming and dynamic UI components, the application empowers policymakers and researchers to visually investigate patterns of urban inequality and resource distribution.

## 🗄️ Data Engineering & Sources

The analytical framework is powered by integrated public datasets:
*   **Toronto Open Data:** Utilized for mapping community demographics, neighborhood profiles, and civic infrastructure.
*   **Ontario Arts Council Datasets:** Processed to track the allocation of cultural funding and arts grants across different urban zones.

Extensive data cleaning, relational merging, and aggregations were performed to structure the data for real-time reactivity within the Shiny server environment.

## 🛠️ Technical Architecture

*   **Language:** R
*   **Web Framework:** Shiny
*   **UI/UX Design:** `bslib` (for modern, modular, and responsive user interfaces)
*   **Data Wrangling:** `tidyverse` (`dplyr`, `tidyr`)
*   **Core Concepts:** Reactive programming, interactive data visualization, full-stack data product deployment.

## 👥 Collaborative Engineering

This dashboard was engineered as a collaborative effort by a specialized data visualization team of six members. Key structural and developmental phases included:
*   Establishing the project roadmap and delegating technical workflows.
*   Executing rigorous data cleaning pipelines to merge disparate municipal datasets into a cohesive analytical base.
*   Architecting the Shiny application logic (UI & Server) to handle dynamic user inputs and render real-time graphical outputs.

## 📂 Repository Structure

```text
├── app.R                  # Core Shiny application script (UI & Server logic combined)
├── data/                  # Cleaned and aggregated datasets (Toronto Open Data & OAC)
├── www/                   # Static web assets (CSS, images)
└── README.md
