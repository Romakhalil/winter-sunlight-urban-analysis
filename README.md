
## 🌞 Winter Sunlight Analysis in Urban Public Spaces

This project analyzes winter sunlight availability in urban environments using Python and geospatial data. The goal is to evaluate how urban morphology and building shadows affect sunlight exposure in public spaces, supporting data-driven urban planning, climate adaptation, and smart city development.

---

## 📌 Motivation

Winter sunlight is a key factor influencing thermal comfort, public space usability, and social activity in cities. In dense urban environments, building geometry often limits sunlight exposure during winter. This project aims to quantify sunlight accessibility and identify shaded areas in urban public spaces to support more inclusive and climate-responsive design.

---

## ⚙️ Project Workflow

This project follows an end-to-end geospatial data science pipeline:

1. Study area definition and spatial boundary extraction
2. Data cleaning and preprocessing of buildings and public spaces
3. Building height estimation and spatial modelling
4. Solar position and geometry computation for winter conditions
5. Shadow projection and spatial simulation
6. Classification of sunny and shaded areas
7. Public space and bench-level sunlight evaluation
8. Multi-temporal winter sunlight scenario analysis

---

## 🧰 Tools and Technologies

* Python
* GeoPandas
* Shapely
* Pandas
* NumPy
* Matplotlib
* GIS and Spatial Analysis

---
## 🚀 Quick Start  

1. Clone the repository  
2. Install dependencies  
   ```bash
   pip install -r requirements.txt
3. 3. Open the `notebooks` folder and run the notebooks sequentially from `00` to `08`.

## 📊 Results

The project generates spatial visualizations and quantitative insights that support decision-making in urban design and planning.

### Spatial Sunlight Classification

This map shows areas exposed to winter sunlight and shaded zones across the study area.

### Bench-level Sunlight Analysis

Detailed evaluation of sunlight exposure at micro-scale public space elements.

### Multi-temporal Scenario Analysis

Comparison of sunlight availability across different winter time scenarios.

👉 See the **figures** folder for visual outputs.

---

## 🌍 Applications

* Urban planning and public space design
* Climate adaptation and resilience
* Smart cities and sustainability
* Mobility and livability research
* Data-driven urban policy and governance

---
## ⚠️ Limitations  

- Building heights are estimated and may introduce uncertainty.  
- Seasonal variability beyond winter was not explored.  
- The model assumes static urban morphology.

## 📂 Data

Due to the large size of geospatial datasets, the full raw data is not included in this repository. The project uses open geospatial data sources such as:

* OpenStreetMap building footprints
* Public space datasets
* Open spatial and urban datasets

Users can replicate the analysis by downloading similar datasets for their study area.

---

## 📂 Repository Structure

```
winter-sunlight-urban-analysis
│
├── notebooks
├── figures
├── README.md
├── requirements.txt
```

---

## 🚀 Future Improvements

* Interactive dashboards for planners
* Real-time seasonal and hourly simulation
* Integration with climate and weather datasets
* Extension to multiple cities and comparative studies
* Automated workflows and scalable spatial pipelines

---

## 👩‍💻 Author

Roma Khalil Bhurgri
Master’s Student in Data Science
Berlin University of Applied Sciences and Technology (BHT)




