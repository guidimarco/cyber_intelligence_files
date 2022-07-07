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

## NiFi
Template NiFi:
- DDoS_Project.xml

Caricato nella repo.

## Mapping elasticSearch
PUT /ddos_attack_1
```
{
  "mappings": {
    "properties": {
      "Timestamp": {
        "type":   "date",
        "format": "dd/MM/yyyy hh:mm:ss a || dd/MM/yyyy hh:mm:ss"
      },
      "Dst IP location": {
        "type": "geo_point"
      },
      "Src IP location": {
        "type": "geo_point"
      }
    }
  }
}
```

## Kibana
Dashboard Kibana:
- DDoS_Attack.ndjson

Caricato nella repo. 
