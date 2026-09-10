## Analyse des données Spotify — Dashboard Streamlit


## Lien du Streamlit

[Accéder à l'application Streamlit](https://spotifydata.streamlit.app/)


## Synthèse de l'analyse

[Lire la synthèse (HTML)](https://shillingford-laurie.github.io/streamlit-spotify/)


## Objectifs

Explorer et nettoyer le jeu de données Spotify
Identifier les tendances musicales (popularité, genres, artistes, caractéristiques audio)
Mettre en évidence des corrélations entre les variables (danseabilité, énergie, tempo…)
Construire un dashboard interactif permettant de filtrer et visualiser les données
Conclure sur des insights métiers exploitables


## Technologies utilisées

    Pyhton / Pandas / NumPy
    Plotly / Matplotlib /Seaborn
    Streamlit 


## Installation et lancement

    Cloner le dépôt : git clone https://github.com/shillingford-laurie/streamlit-spotify.gitcd streamlit-spotify

    Créer et activer un environnement virtuel : 
    python -m venv venv
    source venv/bin/activate      # Mac / Linux
    venv\Scripts\activate         # Windows
 

    Installer les dépendances : pip install -r requirements.txt
 

    Lancer le dashboard : streamlit run app.py
 
 

Le dashboard s'ouvre automatiquement dans le navigateur (http://localhost:8501).


## Structure du projet

```
streamlit-spotify/
│
├── .ipynb_checkpoints/            # Update du notebook (travail collaboratif)
├──  anaconda_projects/            # Configuration des environnements Anaconda
├── archive/                       # Fichiers csv
├── data/                          # Jeu de données Spotify
├── docs/                          # Synthèse (individuelle) du projet
├── notebooks/                     # Notebook d'exploration (travail collaboratif)
├── pages/                         # Pages multi-app du dashboard
├── Data_Spotify.ipynb             # Notebook (personnel)
├── README.md
├── app.py                         # Application Streamlit principale
├── index.html                     # Synthèse sous format HTML
├── requirements.txt               # Dépendances du projet                 
└── track_data_final_propre.ods
```


