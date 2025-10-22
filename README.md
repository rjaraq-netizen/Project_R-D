# Firm-level R&D and Export Database

## Project Overview
This project develops the foundations and tooling to construct a **firm-level database** that brings together companies’ **research & development (R&D)** information and their **export activity** records.  

The resulting dataset will combine firm identifiers, R&D indicators (e.g., intramural and extramural expenditures, R&D personnel, patent counts), and export information (e.g., product classifications, export values, destination countries, HS or SITC codes).  

Exports included in the source data are **not required to be explicitly R&D-derived**; instead, the objective is to host both innovation indicators and export flows at the firm level so researchers can study links between **innovation capacity** and **international engagement**.

---

## Motivation
Understanding how firm-level innovation translates into international market presence is central to policies on competitiveness, industrial upgrading, and global value chain participation.  

However, available microdata is often fragmented across statistical offices, trade registries, patent offices, and administrative sources.  

This repository aims to:
1. Catalog relevant data sources.  
2. Document data gaps and matching challenges.  
3. Provide reproducible scripts and methods to harmonize and merge these heterogeneous datasets.

---

## Objectives
- Identify and document candidate data sources for firm-level R&D and exports.  
- Build reproducible pipelines for cleaning, standardizing, and linking datasets.  
- Produce a harmonized, privacy-aware firm-level database containing R&D metrics and export records.  
- Provide exploratory analyses demonstrating data coverage, potential biases, and matching rates.  
- Share code, metadata, and methodological notes to facilitate reproducibility and further research.

---

## Scope and Assumptions
- The repository focuses on **firm-level linkage** (not plant- or establishment-level, unless data permits).  
- Export flows in source datasets may include all exported products; they are **not pre-filtered** for R&D-origin goods.  
- Linking relies on shared identifiers (tax IDs, business registry codes) or **probabilistic matching** when direct identifiers are absent.  
- The project emphasizes **transparency**: all transformations, assumptions, and matching heuristics are documented.

---

## Data Sources  

- **National Customs Service of Chile (Servicio Nacional de Aduanas)** – [Export Records 2025](https://datos.gob.cl/dataset/registro-de-exportaciones-2025)  
  Official portal: [https://www.aduana.cl](https://www.aduana.cl/aduana/site/edic/base/port/inicio.html)  

- **Ministry of Science, Technology, Knowledge and Innovation** – [Survey on Research and Development (R&D) Expenditure and Personnel](https://observa.minciencia.gob.cl/encuesta/encuesta-sobre-gasto-y-personal-en-investigacion-y-desarrollo-id)

---

## Deliverables
- `data_catalog/` — metadata for each data source.  
- `scripts/` — ETL and matching code (Python/R).  
- `notebooks/` — exploratory analyses and diagnostics.  
- `output/` — anonymized sample harmonized datasets and summary tables.  
- Documentation on matching procedures, variable harmonization, and limitations.

---

## Repository Structure
