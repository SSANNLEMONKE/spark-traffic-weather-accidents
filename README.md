# Invloed van verkeers- en weerscondities op wegverkeersongevallen in België

In dit project onderzoek ik hoe verkeersintensiteit en weercondities samenhangen met de frequentie en ernst van wegverkeersongevallen in België. Dit gebeurt in Apache Spark, via een Jupyter Notebook.

## Open datasets

- **Ongevallen (België, 2017–2022)**  
  Geolocatie van wegverkeersongevallen met letsel.  
  Link: [https://statbel.fgov.be/fr/open-data/geolocalisation-des-accidents-de-la-circulation-2017-2024]

- **Verkeerstellingen (Brussels Gewest)**  
  Verkeersintensiteit (voertuigen) per meetpunt in Brussel.  
  Link: [[datasetlink hier](https://data.mobility.brussels/en/info/traffic_live_geom/)]

- **Weergegevens (RMI)**  
  Weerdata en/of waarschuwingen van het KMI/RMI.  
  Link: [https://opendata.meteo.be/api_documentation_download]

> De ruwe data wordt niet in deze repository opgeslagen. Enkel verwijzingen naar de originele bronnen zijn aanwezig.

## Projectstructuur

- `notebooks/analysis.ipynb` – hoofdnotebook met alle Spark-analyse en visualisaties  
- `data/` – lokale map (niet gecommit) waar de gedownloade datasets worden opgeslagen  


