# Anomaly Detection in Social Networks

## Project Overview
This project implements **anomaly detection in social network graphs** using structural graph metrics and power-law fitting. 
The goal is to identify anomalous users in large-scale social networks based on graph behavior patterns.

The analysis is performed on **Advogato** and **Facebook** datasets using Python and Jupyter Notebooks.
## Note:

Open the .ipynb files in Google Colab.
Mount Google Drive when prompted.
Ensure the dataset CSV files are placed in your Drive at:
My Drive/Dataset/

## Project Structure
```
Final NewProject(Advogato).ipynb              -> Complete anomaly detection workflow on Advogato dataset
NewProject(facebook)Graph matrics.ipynb       -> Graph metric computation for Facebook dataset
NewProject(facebook)Fitting.ipynb             -> Power-law fitting and model building
NewProject(facebook)Testing.ipynb             -> Model testing and anomaly detection results
```

## Key Features
- Graph structural metric computation (degree, clustering, centrality, etc.)
- Power-law fitting for network behavior modeling
- Machine learning based anomaly detection
- Visualization of network patterns and detected anomalies

## Technologies Used
- Python
- Jupyter Notebook
- NetworkX
- NumPy
- Pandas
- Matplotlib / Seaborn
- Scikit-learn

## How to Run
1. Clone the repository  
2. Install required libraries:
   ```
   pip install -r requirements.txt
   ```
3. Open notebooks in Jupyter:
   ```
   jupyter notebook
   ```
4. Run notebooks in the listed order

## Author
**Prathika S J**  
GitHub: prathikasj  
LinkedIn: prathikasj
