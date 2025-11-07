\# MLOps Pipeline - DVS + Git + Jenkins



\## Proje Yapisi

\- data/raw/ - Ham veri (DVC ile)

\- data/processed/ - Islenmis veri

\- models/ - Egitilmis modeller

\- src/ - Kaynak kodlar

\- notebooks/ - Jupyter notebook'lar

\- tests/ - Test dosyalari

\- scripts/ - Yardimci scriptler



\## Kurulum

```bash

pip install -r requirements.txt

dvc init

```



\## Kullanim

```bash

dvc add data/raw/dataset.csv

git add data/raw/dataset.csv.dvc .gitignore

git commit -m "Add dataset"

dvc push

```

