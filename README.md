# California Housing – Machine Learning

## Beskrivning  
Detta projekt använder California Housing-datasetet för att bygga en maskininlärningsmodell som uppskattar bostadsvärden i olika områden. Fokus ligger på att skapa en reproducerbar ML-pipeline, jämföra flera modeller och analysera vilka faktorer som påverkar prisnivåer.

Utöver regression genomförs även en oövervakad analys med KMeans för att identifiera olika typer av bostadsområden och ge ytterligare stöd för datadrivna beslut

## Innehåll  

1. **EDA**  
Översikt av datasetet, hantering av saknade värden samt analys av samband mellan variabler.
2. **Feature engineering & KMeans**  
Skapande av nya variabler och klustring av områden för att identifiera olika typer av bostadsområden.
3. **Modellering**  
Train/test-split, preprocessing med pipelines samt träning och jämförelse av regressionsmodeller med cross-validation.  
4. **Utvärdering & slutsats**  
Slutlig testutvärdering med RMSE, MAE och R² samt analys av modellens styrkor, svagheter och användningsområde.

## Filstruktur

- ML_Uppgift1_Shara_Hysen.pdf – Rapport
- housing.csv - Dataset
- california_housing_ml.ipynb – Jupyter Notebook med analys, visualiseringar och slutsatser
- README.md – Projektbeskrivning
- .gitignore – Ignorerade filer för Git
- requirements.txt – Lista över Pythonpaket som behövs för att köra projektet

## Miljö

Python version 3.13.7

## Installation och körning  

1. **Klona repo:**  
git clone https://github.com/Shara-Hysen/California-Housing-ML-Assignment.git

2. **Skapa och aktivera virtuell miljö:**    
python -m venv .venv    
.venv\Scripts\Activate # Windows    
source .venv/bin/activate # Linux/macOS   

3. **Installera beroenden:**  
pip install -r requirements.txt  

4. **Kör Jupyter Notebook:**    
jupyter notebook california_housing_ml.ipynb 


## Källor  

Projektet är utvecklat som en examinationsuppgift med utgångspunkt i kursmaterial och laborationer, med stöd av AI-verktyg för kodoptimering