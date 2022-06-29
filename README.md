# Cyber Intelligence - Final Project
- Master Cyber Security 2022/2023
- University of Pisa

## Dataset
Original dataset (final_project.csv):

https://www.kaggle.com/datasets/devendra416/ddos-datasets

La spiegazione delle colonne è riportata al seguente link, sezione 3:

https://www.unb.ca/cic/datasets/ids-2018.html

## Docs
Articolo scientifico scritto dagli autori che hanno elaborato il dataset:

https://www.ijcseonline.org/pdf_paper_view.php?paper_id=4011&28-IJCSE-06600.pdf

## Nifi processors

CINT_Project_2022.xml:
Riproduzione di https://www.projectpro.io/recipes/read-csv-files-and-convert-data-into-json-format-using-nifi-controller-services
Dataset cars.csv

CINT_Project_2022_Rev01.xml:
Lettura, conversione da csv a json e scrttura su disco e su elastisearch
Dataset final_dataset.csv o final_dataset_100.csv (ridotto per test, prime 100 righe)
