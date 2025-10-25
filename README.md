# Sector R&D and Export Database

## Project Overview
This project develops the foundations and tools to build a firm/sector-level database that combines companies’ research and development (R&D), production, and export activity records.

The resulting dataset will integrate sector identifiers with detailed R&D indicators (such as intramural and extramural expenditures, R&D personnel, and patent counts) and export-related information (including product classifications, export values, destination countries, and HS codes).

---

## Motivation
Understanding how sector level innovation translates into international market presence is central to policies on competitiveness, industrial upgrading, and global value chain participation.  

However, available microdata is often fragmented across statistical offices, trade registries, patent offices, and administrative sources.  

This repository aims to:
1. Catalog relevant data sources.  
2. Document data gaps and matching challenges.  
3. Provide reproducible scripts and methods to harmonize and merge these heterogeneous datasets.

---

## Objectives
- Identify and document candidate data sources for firm-level R&D and exports for Customs Service of Chile.  
- Build reproducible pipelines for cleaning, standardizing, and linking datasets.  
- Provide exploratory analyses demonstrating data coverage, potential biases, and matching rates.  
---

## Data Sources  

- **National Customs Service of Chile (Servicio Nacional de Aduanas)** – [Export Records 2025](https://datos.gob.cl/dataset/registro-de-exportaciones-2025)  
  Official portal: [https://www.aduana.cl](https://www.aduana.cl/aduana/site/edic/base/port/inicio.html)  

- **Ministry of Science, Technology, Knowledge and Innovation** – [Survey on Research and Development (R&D) Expenditure and Personnel](https://observa.minciencia.gob.cl/encuesta/encuesta-sobre-gasto-y-personal-en-investigacion-y-desarrollo-id)

