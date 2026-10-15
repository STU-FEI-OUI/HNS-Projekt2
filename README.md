# HNS-Projekt2
Repozitár ku Projektu 2 na predmete HNS, tu sa nachádzajú odkazy na datsety k projektu a literatúru

Zadanie: [Projekt 2](https://github.com/STU-FEI-OUI/HNS-test/blob/main/Zadania/HNS_Projekt2.pdf)

## Datasety:

### Dataset Vozidlá - Vehicles Dataset
Klasifikácia obrazov, 6 skupín (auto, autobus, bicykel, motorka, dodávka, pickup)
( [Dataset_Vozidla](https://drive.google.com/drive/folders/1ETYpjMKG3aPFdnf-RIiWp82HwKq1R4nX?usp=drive_link) )
Doplniť obrazy vozidiel je možné cez datasety MS COCO, ImageNet dataset, alebo Kaggle [Vehicles](https://www.kaggle.com/datasets/iamsandeepprasad/vehicle-data-set)

### Dataset Dopravné Značky - Traffic Sings Dataset
Klasifikácia obrazov, 12 skupín (vybrané typy značiek)
( [Dataset_Značky](https://drive.google.com/drive/folders/1JShYe8vmZv287GCPLxERNt2PP3C3hwZv?usp=drive_link) )

### Dataset Vnútorné prostredie - InDoor Dataset
Klasifikácia obrazov, 9 skupín (vnútorné priestory reštaurácia, obývačka, spálňa, kuchyňa, ...)
( [Dataset_Indoor](https://drive.google.com/drive/folders/1nWlwbR2opcynCSwm_WN97URv_WC-3MVy?usp=drive_link) )

### Dataset Ochorenia Paradajok - Plant Village 2
Klasifikácia obrazov, 9 skupín ochorenia listov paradajok (zdravé, 8 skupín ochorenia)
( [Dataset_PlantVillage2](https://drive.google.com/drive/folders/1sKmmi0L4KeSf5xgxXhldCrks4oF897DX?usp=drive_link) )
Tiež je k dispozícii na Kaggle [PlantDiseases](https://www.kaggle.com/datasets/emmarex/plantdisease)

### Dataset Počasie - Weather Dataset
Klasifikácia obrazov, 11 skupín počasia (dew, fogsmog, frost, glaze, hail, lightning, rain, rainbow, rime, sandstorm, snow)
( [Dataset_Weather](https://www.kaggle.com/code/adrianograms/weather-image-classification/input) )
Doplniť obrazy počasia je možné cez datasety na Kaggle [Weather1](https://drive.google.com/drive/folders/1XMSb5IRHJP8PhjMwVJNal7SmHFOduRij?usp=drive_link)  , 
[Weather2](https://www.kaggle.com/code/ramazanturann/weather-image-classification/input)

### Dataset Architektúry - Architecture Dataset
Klasifikácia obrazov, 25 skupín typov architektúr budov
( [Dataset_Architecture](https://drive.google.com/drive/folders/13hPJY3ZBmGQp1_AwKQUTMrs3ei2GhFvs?usp=drive_link) )

### Dataset Kvety 1 - Flowers Dataset
Klasifikácia obrazov, 5 druhov kvetov (daisy, dandelion, rose, sunflower, tulip)
( [Dataset_Flowers1](https://www.kaggle.com/code/nikhilmishra21/flowers-notebook-cnn/input) )

### Dataset Kvety 2 - Flowers Dataset - Oxford 102 flowers
Klasifikácia obrazov, 102 druhov kvetov 
( [Dataset_Flowers2](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/) )

### Dataset Jedlá - Foods Dataset
Klasifikácia obrazov jedál, 101 skupín obrazov jedál
( [Dataset_Foods](https://www.kaggle.com/datasets/kmader/food41) )

### Dataset Odpadky 1 - Garbage 1 Dataset
Klasifikácia obrazov odpadkov, 10 skupín obrazov odpadkov
( [Dataset_Garbage1](https://www.kaggle.com/datasets/sumn2u/garbage-classification-v2) )

### Dataset Odpadky 2 - Garbage 2 Dataset
Klasifikácia obrazov odpadkov, 6 skupín obrazov odpadkov
( [Dataset_Garbage2](https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification/data) )

### Dataset Odpadky 3 - Garbage 3 Dataset
Klasifikácia obrazov odpadkov, 12 skupín obrazov odpadkov
( [Dataset_Garbage3](https://www.kaggle.com/datasets/mostafaabla/garbage-classification) )

### Dataset na detekciu požiaru lesov - Forest Fire Smoke Dataset
Rozpoznávanie požiaru lesov, 3 skupiny Smoke, Fire, Not_Fire
( [Dataset_Smoke_Fire_NotFire](https://www.kaggle.com/datasets/amerzishminha/forest-fire-smoke-and-non-fire-image-dataset) )

### Dataset PC komponentov – PC components Dataset
Rozpoznávanie PC komponentov, 14 skupín (CPU, GPU, káble, RAM, HDD, monitor, klávesnica, ...)
( [Dataset_PCcomponents](https://www.kaggle.com/datasets/asaniczka/pc-parts-images-dataset-classification) )

### Dataset povrchových defektov oceľového pásu  – NEU Surface defect Dataset
Klasifikácia defektov oceľového plechu, 6 skupín (valcované okuje (RS), škvrny (Pa), praskliny (Cr), jamkovitý povrch (PS), inklúzie (In) a škrabance (Sc))
( [Dataset_Defects](https://www.kaggle.com/datasets/kaustubhdikshit/neu-surface-defect-database/data) )

## Návody:
- Pokyny k príprave prezentácie ( [Pokyny prezentácia](Datasets/Pokyny_projekt1.pdf) )

- Návod ako postupovať pri modeloch s attention vrstvou ( [Návod pre realizáciu transformerov](Datasets/HNS_navod_ukazky_kodu_projekt1.pdf) )

- Príklad fungovania attention vrstvy, pozornosť v transformeroch, príklad generovania textu: [01_attention_a_transformery.ipynb](Datasets/01_attention_a_transformery.ipynb)

- Príklady modelov s attention vrstvou : [02_vizualne_transformery.ipynb](Datasets/02_vizualne_transformery.ipynb)

- Porovnanie modelov CNN a ViT na redukovanom Food101 Datasete: [03_porovnanie_modelov.ipynb](Datasets/03_porovnanie_modelov.ipynb)

- Výsledky porovnania modelov CNN a ViT na redukovanom Food101 Datasete ( [Porovnanie_modelov_PDF_výstup](Datasets/HNS_Projekt1_porovnanie_modelov.pdf) )


## Literatúra:
- Fungovanie Attention mechanizmu v Transformeroch ( [Abnar and Zuldema, Attention flow](https://arxiv.org/abs/2005.00928) )

- Attention mechanizmus ( [Vaswani at all, Attention is all you need](https://arxiv.org/abs/1706.03762) )

- Attention vrstva - CBAM ( [Woo at all, CBAM: Convolutional Block Attention Module](https://arxiv.org/abs/1807.06521) )

- ConvNeXt - optimalizovaný CNN model ( [Zhuang Liu at all, A ConvNet for the 2020s](https://arxiv.org/abs/2201.03545) )

- ViT - transformery na rozpoznávanie obrazov ( [Alexey Dosovitskiy at all, Transformers for Image Recognition](https://arxiv.org/abs/2010.11929) )

- DeiT - vizuálny transformer ( [Hugo Touvron at all, Training data-efficient image transformers](https://arxiv.org/abs/2012.12877) )

- Swin - vizuálny transformer ( [Ze Liu at all, Swin Transformer](https://arxiv.org/abs/2103.14030) )

- CNN a ViT - hybridný model CoAtNet ( [Zihang Dai at all, CoAtNet: Marrying Convolution and Attention](https://arxiv.org/abs/2106.04803) )

