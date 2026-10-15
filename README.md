# HNS-Projekt2
Repozitár ku Projektu 2 na predmete HNS, tu sa nachádzajú odkazy na datsety k projektu a literatúru

Zadanie: [Projekt 2](https://github.com/STU-FEI-OUI/HNS-test/blob/main/Zadania/HNS_Projekt2.pdf)

## Datasety:

### Dataset - dobre nasadené rúško
Rozpoznávanie dobre nasadeného rúška – 2 skupiny (dobre nasadené, zle nasadené) 
alebo 3 skupiny (bez rúška, zle nasadené, dobre nasadené)
( [Dataset_Ruska](https://github.com/cabani/MaskedFace-Net) )

### Dataset - Hlasové povely
Rozpoznávanie hlasových povelov zo zvukových nahrávok – 8 skupín povelov (go, left, right, stop, up, down, on, off)
( [Dataset_HlasovePovely](https://www.kaggle.com/datasets/mok0na/speech-commands-v002) )

### Dataset - Stavy tváre
Rozpoznávanie natočenia tváre z RGB obrazu – 4 skupiny (LeftProfile, LightOn, RightProfile, OcclusionPaper)
Rozpoznávanie gest tváre z RGB obrazu – 5 skupín (Neutral, OcclusionEyes, OcclusionMouth, OpenMouth, Smile)
( [Dataset_Tvare](https://drive.google.com/drive/folders/1YwOCplpXusQXr7d9wsS7kTb9TGJAt5fW?usp=drive_link) )

### Dataset - Gestá ASL 1
Rozpoznávanie gest ruky z RGB obrazu a hĺbkovej mapy – 10 skupín (jednotlivé gestá).
( [Dataset_Gesta_ASL1](https://drive.google.com/drive/folders/1mpRo653YGYd4iuB-1t5sxog7rBnpaNob?usp=drive_link) )

### Dataset - Gestá ASL 2
Rozpoznávanie gest ruky z RGB obrazu a hĺbkovej mapy – 10 skupín (jednotlivé gestá).
( [Dataset_Gesta_ASL2](https://drive.google.com/drive/folders/1UDefZEX1hMszVGkDu04sFOX3yu9altu9?usp=drive_link) )

### Dataset - Defekty 1 (Jamy na ceste, Podložky)
Rozpoznávanie defektov (jám) na ceste - 2 skupiny (Ok, defect)
( [Dataset_Jamy](https://drive.google.com/drive/folders/1d3atNCQK9POrsjQJiVZ6M8HoPEfCaTn6?usp=drive_link) )

Kontrola kvality podložiek – 5 skupín (Ok, 4 typy defektov)
( [Dataset_Podlozky](https://drive.google.com/drive/folders/1PVE357M-8uburXtl5kFwjo_nowSup1Xx?usp=drive_link) )

### Dataset - Defekty 2 (Zvary, Casting)
Kontrola kvality zvarov kamery – 4 skupiny (Ok, 2025-kráterový lunker, 510-diera, 500-poškodený povrch zvaru)
( [Dataset_Zvary](https://drive.google.com/drive/folders/1SUivIX-uDGs74XNegNQp95wvQ78C5DIe?usp=drive_link) )

Kontrola kvality obrobkov (Casting)- 2 skupiny (Ok, defect)
( [Dataset_Casting](https://www.kaggle.com/datasets/ravirajsinh45/real-life-industrial-dataset-of-casting-product/data) )

### Dataset - Defekty 3 (NEU-DET, Pneumatiky)
Dataset povrchových defektov oceľového pásu  – NEU Surface defect Dataset
Klasifikácia defektov oceľového plechu, 6 skupín (valcované okuje (RS), škvrny (Pa), praskliny (Cr), jamkovitý povrch (PS), inklúzie (In) a škrabance (Sc))
( [Dataset_NEU_DET](https://www.kaggle.com/datasets/rdsunday/neu-urface-defect-database) )

Kontrola kvality pneumatík - 2 skupiny (Ok, defect)
( [Dataset_Pneumatiky](https://drive.google.com/drive/folders/1EO9dj8x2OM21ZSBs8xlqTLSzH-FDLOBB?usp=drive_link) )

### Dataset - Ludské činnosti - video sekvencie
Rozpoznávanie ľudských činností z videa
( [Dataset_HMDB51]() )

### Dataset – EKG anomálií
Rozpoznávanie anomálií EKG srdca, 2 skupiny (CPU, GPU, káble, RAM, HDD, monitor, klávesnica, ...)
( [Dataset_ECG5000](https://www.kaggle.com/datasets/devavratatripathy/ecg-dataset/data) )

### Dataset – Diabetická Retinopatia - Fundus obrazy
Rozpoznávanie Diabetickej Retinopatie (DR) na fundus snímkach očného pozadia. – 5 skupín 
(No DR – bez DR, Mild – mierna NDR, Moderate – stredne závažná NDR, Severe -  závažná NDR, Proliferative DR – Proliferatívna retinopatia)
( [Dataset_Diabetic_Rethinopathy](https://www.kaggle.com/datasets/sampathsaivamsimatha/diabetic-rethinopathy-dataset-new) )

### Dataset – KVASIR a  Aizheimer
Rozpoznávanie nálezov na hrubom čreve. (8 skupín nálezov) Dataset KVASIR
( [Dataset_KVASIR](https://www.kaggle.com/datasets/meetnagadia/kvasir-dataset) )

Rozpoznávanie ochorenie Aizheimer na MRI obrazoch – 2 skupiny (normal, positive)
( [Dataset_Aizheimer](https://drive.google.com/drive/folders/1ARzPYGbM_oUccYpTV9js5bKHGwuCYBTg?usp=drive_link) )


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

