# Analyse-rapide-Python-1
Analyse rapide de  Base de donnée

pip install ydata_profiling
pip install ipywidgets --upgrade

from ydata_profiling import ProfileReport 
import pandas as pd

df = pd.read_excel("ton_fichier.xlsx") ou df = pd.read_cvs("")
rapport = ProfileReport(df, title="Analyse exploratoire")
rapport.to_file("rapport_data.html")

Afficher la traduction
