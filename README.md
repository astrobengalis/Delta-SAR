# DeltaSAR: Bangladesh Surface Change Intelligence

> **See the change, understand the impact.**  
> An integrated satellite radar and hydrological intelligence platform providing early warnings for flood inundation and riverbank erosion across Bangladesh. Developed for the NASA Space Apps Challenge by **Team Astro Bengalis**.

---

## 📋 Table of Contents
- [Overview](#-overview)
- [The Challenge & Impact](#-the-challenge--impact)
- [Our Solution: DeltaSAR](#-our-solution-deltasar)
- [Key Features](#-key-features)
- [System Architecture](#-system-architecture)
- [Technology Stack](#-technology-stack)
- [Team Astro Bengalis](#-team-astro-bengalis)
- [Getting Started](#-getting-started)
- [Roadmap & Future Scope](#-roadmap--future-scope)
- [Acknowledgments](#-acknowledgments)

---

## 🌊 Overview

Bangladesh is known as the land of rivers, but severe flood inundation and riverbank erosion swallow farmland and displace families every year. Over the past five decades, satellite data reveals that the **Jamuna and Padma rivers alone have eroded nearly 1,585 square kilometers of land**—more than five times the area of Dhaka, the capital of Bangladesh.

While satellite imagery, hydrological sensor records, and local infrastructure maps exist, they remain scattered across uncoordinated institutions without early warning integration.

**DeltaSAR** bridges this critical gap. Utilizing Synthetic Aperture Radar (SAR) data from **NASA's NISAR mission**, DeltaSAR tracks riverbank movement and flood extents through thick monsoon cloud cover, day or night. By fusing satellite radar intelligence with local hydrological records and infrastructure mapping, DeltaSAR provides actionable risk warnings to protect vulnerable riverine communities.

---

## 🎯 The Challenge & Impact

### The Problem
* **Mass Displacement & Socio-Economic Loss:** Riverbank erosion swallows farmland and homes, displacing families into temporary roadside shelters.
* **Massive Erosion Scale:** Over 1,585 km² of land eroded along major river systems over the past 50 years.
* **Information Silos:** Satellite data, water level records, and town/infrastructure maps are uncoordinated.
* **Optical Satellite Limitations:** Heavy cloud cover during monsoon seasons blocks standard optical satellites right when disaster monitoring is needed most.

### The DeltaSAR Solution
* **All-Weather Penetration:** Uses NASA's NISAR SAR radar to observe surface changes day and night through cloud cover.
* **Actionable Intelligence:** Maps surface changes directly to infrastructure and settlements to show *who* and *what* is threatened.
* **Early Warnings:** Converts complex satellite observations into accessible early warnings before communities lose everything.

---

## ⚡ Our Solution: DeltaSAR

DeltaSAR integrates multi-source geospatial data into a unified pipeline:

1. **Continuous SAR Monitoring:** Processes NASA NISAR radar data to track riverbank shifts and flood inundation boundaries in near-real-time.
2. **Multi-Source Data Fusion:** Merges radar data with ground-based hydrological records (water levels, discharge rates) and infrastructure maps (roads, homes, farmland).
3. **Predictive Vulnerability Analytics:** Employs explainable machine learning models to assess structural and community risk along vulnerable riverbanks.

---

## ✨ Key Features

* 📡 **All-Weather Flood & Erosion Mapping:** Cloud-penetrating radar monitoring for uninterrupted monsoon surveillance.
* 🗺️ **Interactive Spatial Dashboard:** Web-based GIS platform displaying river movement, flood zones, and exposed infrastructure.
* 🧠 **Explainable AI Risk Engine:** Machine learning models providing transparent, trusted predictions for riverbank erosion risk.
* 🚨 **Localized Early Warnings:** Priority risk scoring to notify vulnerable riverine settlements early.

---

## 🛠️ Technology Stack

* **Remote Sensing & GIS:** NASA NISAR Radar, Synthetic Aperture Radar (SAR) Processing, Spatial Analysis.
* **Machine Learning & AI:** Python, Explainable Machine Learning Models, Predictive Analytics.
* **Frontend & Visualization:** Interactive Web GIS, Spatial Data Visualization Libraries.
* **Systems Engineering:** Satellite Data Integration, Spatial Analytics Pipelines.

---

## 👥 Team Astro Bengalis

| Member Name | Role & Specialization | Background & Affiliation |
| :--- | :--- | :--- |
| **Muhammad Safiullah Bin Motahar (Safiullah)** | **Team Lead**<br>Technology & Satellite Planning | Assistant Manager (Tech Planning & Implementation), Bangladesh Satellite Company Limited (BSCL). Former Project Control Manager (South Asia) in global telco. |
| **Muaza Munir** | **Socio-Economic Analyst**<br>Economic & Community Impact | Master's in Economics, University of Dhaka. |
| **Mohammad Ehsan** | **Remote Sensing & AI Lead**<br>GIS, SAR Analysis & AI | Satellite Technology Development Specialist for Bangladesh's Earth Observation (AIS, Comms) satellites. |
| **Wadiel Rahman** | **Data Science & ML Lead**<br>Explainable AI & Risk Models | Computer Science Student, United International University (UIU). Specialist in explainable ML and risk prediction models. |
| **Tajwar Tahjir Tanzim** | **Software & Visualization Lead**<br>Frontend & Data Visualization | 3rd Year Computer Science & Engineering Student, University of Dhaka. NASA Space Apps software developer and visualization expert. |
| **Muhammad Sanaullah Bin Motahar** | **Systems & Engineering Lead**<br>Mechatronics & Embedded Systems | 3rd Year Mechatronics Engineering Student, Universiti Teknologi Malaysia (UTM). Robotics & systems specialist. |

---

## 🚀 Getting Started

### Prerequisites
* Python 3.9 or higher
* GDAL / Rasterio / GeoPandas (for spatial data processing)

### Usage & Setup

1. **Repository Setup:**
   Clone the DeltaSAR repository to your local machine and navigate into the project directory.

2. **Environment Configuration:**
   Create a virtual environment and install project dependencies listed in .

3. **Data Ingestion:**
   Place local hydrological records and NISAR SAR granules in the data processing directory.

4. **Run Application:**
   Execute  to launch the interactive visualization dashboard.

---

## 🗺️ Roadmap & Future Scope

- [x] Ingestion and pre-processing pipeline for NASA NISAR radar data.
- [x] Multi-source integration of hydrological and riverbank erosion records for the Jamuna and Padma basins.
- [x] Explainable ML risk assessment model for riverbank vulnerability.
- [ ] Integration of real-time automated mobile alerts for at-risk communities.
- [ ] Expansion of satellite coverage across all major coastal and riverine regions in Bangladesh.

---

## 🙏 Acknowledgments

* **NASA Space Apps Challenge** for the competition platform and inspiration.
* **NASA NISAR Mission** for open Synthetic Aperture Radar (SAR) data access.


---
*Developed by **Team Astro Bengalis** for Bangladesh and vulnerable riverine communities worldwide.*
