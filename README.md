# 🚀 Data-Driven Decision Making in Sustainable Construction and Resource Optimization

## The Architecture of a Sustainable Future: BIM + LCA + Machine Learning

This repository is the knowledge core for a project aimed at transforming construction decisions through sustainability. By aggregating critical embodied carbon data with advanced methodologies like **Machine Learning (ML)** and **Building Information Modeling (BIM)**, we provide a faster and more accurate pathway for **Life Cycle Assessment (LCA)** and resource optimization.

The project's goal is to demonstrate how data-driven analysis can:

1. **Accurately Assess** the environmental impact of various construction practices and materials.
2. **Guide** material selection during the early design stages.
3. **Enable** real-time sustainable decision-making, overcoming the limitations of traditional LCA methods.

`ATI PoC SOBIGDATA++ Presentation 24Nov.pdf` (stored at the repository root) captures the overarching narrative of this proof of concept and illustrates how ML accelerates LCA-driven design loops.

-----

## ✨ The Solution: ML-Enabled Life Cycle Assessment (LCA)

Machine Learning is not just used to calculate LCA; it makes the process **predictive, automated, and integrated**.

| Feature | ML Method | Sustainability Advantage |
| :--- | :--- | :--- |
| **Rapid Prediction** | Regression/ANN Models | Predicts the environmental impact (e.g., GWP) of a building from the early design phases, where the influence is maximal. |
| **Material Optimization** | ML applied to Data Mining | Analyzes BIM data (geometry, materials) and ICE databases to suggest material compositions that are optimal for cost, durability, and low carbon impact. |
| **LCA Automation** | Data Processing & Pattern Recognition | Reduces human error and automates the extraction of impact factors, transforming LCA from a retrospective exercise into a dynamic decision-making tool. |
| **BIM Analysis** | Leverages IFC files, project metrics, and energy certification data as ML input *features*. | Unlocks granular comparisons between design options without manual recalculation. |

-----

## 🏗️ Repository Contents: Your Single Source of Truth

This repository consolidates two core resources essential for embodied carbon analysis and methodological research.

### 1. Data (ICE DB V3.0) - `data/ICE_DB_V3.0/`

The official **Inventory of Carbon & Energy (ICE) V3.0** dataset from the University of Bath, which is fundamental for calculating embodied carbon factors for construction materials.

| File | Description | Project Use |
| :--- | :--- | :--- |
| `ICE DB V3.0 - 10 Nov 2019.xlsx` | Official release of embodied carbon factors. | Primary reference for LCA impact factors. |
| `ICE DB Machine Readable V3.0a Beta...` | Flattened tables suitable for direct integration into ML workflows or data pipelines. | Direct input for Machine Learning models. |
| `ICE Cement, Mortar and Concrete Model...` | Detailed breakdown of cementitious mixes. | Modeling specific material scenarios. |

### 2. Curated Literature - `literature/`

A collection of approximately **25 publications** on BIM, LCA, and data-driven optimization, organized by theme:

- **BIM–LCA Synthesis:** Comparative reviews of BIM-based LCA workflows and integration strategies.
- **Methodological Guidance:** Standard documents (e.g., EN 15978, ILCD handbooks) on emission methodologies and circular footprint.
- **Benchmarks & Databases:** Environmental benchmark datasets and construction material LCA databases.
- **ML & Analytics:** Research on applying ML algorithms for lifecycle energy and carbon prediction in buildings.

-----

## 💻 Getting Started

To clone the repository and begin your analysis:

```bash
# Change directory to your working folder
cd "C:\Users\R&D\Desktop\01_ML_LCA-Support"

# Clone the repository
git clone https://github.com/GiacomoMarani/Data-Driven-Decision-Making-in-Sustainable-Construction-and-Resource-Optimization.git

# Navigate into the project directory
cd Data-Driven-Decision-Making-in-Sustainable-Construction-and-Resource-Optimization
```

-----

## 🎯 Next Steps & Contribution

If you are interested in contributing or expanding the project, priority development areas include:

1. **Data Pre-processing:** Exporting ICE tables to **CSV** format to facilitate validation and usage within ML notebooks.
2. **Data Enrichment:** Extracting *abstracts* and *key insights* for each document in the `literature/` folder to accelerate researcher onboarding.
3. **Initial ML Models:** Developing a *Proof of Concept* (PoC) based on ICE data to predict Global Warming Potential (GWP) based on material composition.
