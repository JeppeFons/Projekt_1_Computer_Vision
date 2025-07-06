<<<<<<< HEAD
**Projektbeskrivelse og formål**

**Installation og opsætning (fx miljø, dependencies)**

**Instruktioner til hvordan man kører koden eller notebooks**

**Forklaring af datasæt og kilde**

Dette projekt anvender datasættet **[PatchCamelyon]** fra Kaggle.

Datasættet kan findes her: [Metastatic Tissue Classification - PatchCamelyon](https://www.kaggle.com/datasets/andrewmvd/metastatic-tissue-classification-patchcamelyon)

Bemærk: Du skal have en Kaggle-konto for at kunne downloade datasættet.

**Resultater og konklusioner**

**Eventuelle referencer eller links**




**mappe struktur**

project-name/
│
├── data/
│   ├── raw/                <- Ubehandlede data (direkte fra kilden)
│   ├── processed/          <- Klargjorte data til modellering
│   └── interim/            <- Midlertidige filer (f.eks. efter cleaning)
│
├── notebooks/              <- Jupyter notebooks til EDA, prototyping
│   ├── 01_EDA.ipynb
│   ├── 02_FeatureEng.ipynb
│   └── 03_Model.ipynb
│
├── src/                    <- Python scripts til feature engineering, modeller mm.
│   ├── __init__.py
│   ├── data/               <- Scripts til at hente og forberede data
│   │   └── make_dataset.py
│   ├── features/           <- Feature engineering
│   │   └── build_features.py
│   ├── models/             <- Træning og evaluering af modeller
│   │   ├── train_model.py
│   │   └── evaluate_model.py
│   └── visualization/      <- Visualisering (plots, figurer)
│       └── visualize.py
│
├── models/                 <- Gemte modeller (.pkl, .pt osv.)
│
├── reports/                <- Genererede analyser og rapporter
│   ├── figures/            <- Visualiseringer
│   └── final_report.pdf
│
├── requirements.txt        <- Python dependencies
├── environment.yml         <- Alternativ til requirements.txt (Conda)
├── setup.py                <- Hvis du laver det til et installérbart modul
├── README.md               <- Projektbeskrivelse
├── .gitignore              <- Undgå at versionere fx `data/raw`, `.DS_Store`, `__pycache__` mm.
└── pyproject.toml          <- Moderne build-metadata (valgfrit)


cd C:\Job_og_eksamensbevis\Github\projekter\projekt_2_Computervision
git init
git remote add origin https://github.com/JeppeFons/Computer-Vision-Projekt.git
git add .
git commit -m "Initial commit"
=======
**Projektbeskrivelse og formål**

**Installation og opsætning (fx miljø, dependencies)**

**Instruktioner til hvordan man kører koden eller notebooks**

**Forklaring af datasæt og kilde**

Dette projekt anvender datasættet **[PatchCamelyon]** fra Kaggle.

Datasættet kan findes her: [Metastatic Tissue Classification - PatchCamelyon](https://www.kaggle.com/datasets/andrewmvd/metastatic-tissue-classification-patchcamelyon)

Bemærk: Du skal have en Kaggle-konto for at kunne downloade datasættet.

**Resultater og konklusioner**

**Eventuelle referencer eller links**




**mappe struktur**

project-name/
│
├── data/
│   ├── raw/                <- Ubehandlede data (direkte fra kilden)
│   ├── processed/          <- Klargjorte data til modellering
│   └── interim/            <- Midlertidige filer (f.eks. efter cleaning)
│
├── notebooks/              <- Jupyter notebooks til EDA, prototyping
│   ├── 01_EDA.ipynb
│   ├── 02_FeatureEng.ipynb
│   └── 03_Model.ipynb
│
├── src/                    <- Python scripts til feature engineering, modeller mm.
│   ├── __init__.py
│   ├── data/               <- Scripts til at hente og forberede data
│   │   └── make_dataset.py
│   ├── features/           <- Feature engineering
│   │   └── build_features.py
│   ├── models/             <- Træning og evaluering af modeller
│   │   ├── train_model.py
│   │   └── evaluate_model.py
│   └── visualization/      <- Visualisering (plots, figurer)
│       └── visualize.py
│
├── models/                 <- Gemte modeller (.pkl, .pt osv.)
│
├── reports/                <- Genererede analyser og rapporter
│   ├── figures/            <- Visualiseringer
│   └── final_report.pdf
│
├── requirements.txt        <- Python dependencies
├── environment.yml         <- Alternativ til requirements.txt (Conda)
├── setup.py                <- Hvis du laver det til et installérbart modul
├── README.md               <- Projektbeskrivelse
├── .gitignore              <- Undgå at versionere fx `data/raw`, `.DS_Store`, `__pycache__` mm.
└── pyproject.toml          <- Moderne build-metadata (valgfrit)


cd C:\Job_og_eksamensbevis\Github\projekter\projekt_2_Computervision
git init
git remote add origin https://github.com/JeppeFons/Computer-Vision-Projekt.git
git add .
git commit -m "Initial commit"
>>>>>>> 5b9b9be9816cf178451a7f0ebd2e26bbdce907ba
git push -u origin master