HTRomance, Medieval French corpus of ground-truth for Handwritten Text Recognition
  and Layout Segmentation
=====================
![characters badge](badges/characters.svg) ![regions badge](badges/regions.svg) ![lines badge](badges/lines.svg) ![files badge](badges/files.svg)

<!-- Custom Zone -->

## Introduction

This ground-truth dataset has been carefully built around the idea of having generic data for building a strong and reliable model for HTR of Latin manuscripts. Each manuscript should have around 10 columns (5 bi-columns pages or 10 pages of single column).

Data follow the Segmonto guidelines.

> [!NOTE]
> The repository contains two XML files per image. The ones suffixed with `.chocomufin.xml` are normalized in order to be compliant with other datasets following the same guidelines. The others are more specific to this repository. We recommend using the normalized documents.

## Credits

- Transcriptions: Noé Leroy
- Supervision and manuscript selection: Ariane Pinche & Jean-Baptiste Camps.
- Project management: Thibault Clérice & Alix Chagué.

<!-- Rien ne doit être modifié manuellement après la balise Start Auto -->

<!-- Start Auto -->

## Transcription guidelines

The transcription guidelines are described in a paper available on [HAL](https://hal-enc.archives-ouvertes.fr/hal-03828353) and published in the Journal for Open Humanities Data. The paper provides specific details about the selection process, the transcription methods and choices, as well as details about the output (mainly the [Generic CREMMA Model for Medieval Manuscripts (Latin and Old French)](https://zenodo.org/record/7234166#.Y7f69afMJhE) for [Kraken](https://kraken.re))

## Data

ALTO and images can be found in the directory called `data/`. Each subfolder of `data/` corresponds to a 
single manuscript, identified by its shelfmark.

<!-- BeginTable -->

| Shelfmark                                                                 | Links                                                                               | Range       | Type       |   Century | Color   |   Pages |   Main Zones |   Lines |   Characters | Genre             | Content                                                   |
|---------------------------------------------------------------------------|-------------------------------------------------------------------------------------|-------------|------------|-----------|---------|---------|--------------|---------|--------------|-------------------|-----------------------------------------------------------|
| [BnF fr. 20050](https://gallica.bnf.fr/ark:/12148/btv1b60009580)          | [📁](data/bnf-fr.-20050)  [**B**](https://data.biblissima.fr/w/Item:Q48258)         | 4r-5v       | vers       |        13 | ✓       |       4 |            4 |      84 |         3793 | chansonnier       | Le chansonnier de saint Germain                           |
| [BnF fr 2168](https://gallica.bnf.fr/ark:/12148/btv1b525135854)           | [📁](data/bnf-fr.-2168)  [**B**](https://data.biblissima.fr/w/Item:Q48571)           | 88rb        | vers       |        13 | ✓       |       5 |           20 |     370 |         7964 | Fabliau           | Le sacristain                                             |
| [BnF NAF 10039](https://gallica.bnf.fr/ark:/12148/btv1b52500695k)         | [📁](data/bnf-naf-10039)                                                            | 1r-3r       | verse      |        13 | ✓       |       4 |           12 |     116 |         3165 | ROman             | Roman d'Aspremont                                         |
| [BnF fr. 1450](https://gallica.bnf.fr/ark:/12148/btv1b8415202d)           | [📁](data/bnf-fr.-1450)                                                             | 1r-2v       | verse      |        13 | ✓       |       4 |           13 |     709 |        14817 | roman             | Roman de Troie                                            |
| [BnF fr. 17229](https://gallica.bnf.fr/ark:/12148/btv1b9061254h)          | [📁](data/bnf-fr.-17229)  [**B**](https://data.biblissima.fr/entity/Q47514)         | 127r-129r   | prose      |        13 | ✗       |       3 |           12 |     479 |        12511 | légendier         | Legendier                                                 |
| [BnF fr. 23117](https://gallica.bnf.fr/ark:/12148/btv1b90639749)          | [📁](data/bnf-fr.-23117)  [**B**](https://data.biblissima.fr/w/Item:Q49086)         | 299vc-304rb | prose      |        13 | ✗       |       5 |           21 |     736 |        19852 | légendier         | Vie de saint Martin                                       |
| [BnF fr. 6447](https://gallica.bnf.fr/ark:/12148/btv1b90075392)           | [📁](data/bnf-fr.-6447)  [**B**](https://data.biblissima.fr/w/Item:Q51965)          | 270r-271v   | prose      |        13 | ✗       |       4 |           12 |     383 |        13246 | légendier         | Vie de saint Martin                                       |
| [BnF fr. 12581](https://gallica.bnf.fr/ark:/12148/btv1b53000323h)         | [📁](data/bnf-fr.-12581)  [**B**](https://data.biblissima.fr/w/Item:Q48011)         | 373r-375v   | vers       |        13 | ✓       |       4 |            8 |     306 |         9289 | Fabliau           | Li Fabliaus des Treces                                    |
| [BnF fr. 1635](https://gallica.bnf.fr/ark:/12148/btv1b105253083)          | [📁](data/bnf-fr.-1635)                                                             | fol. 4v-5v  | vers       |        13 | ✓       |       3 |            7 |     219 |         4838 | Fabliau           | Testament de l'âne                                        |
| [BnF fr. 1553](https://gallica.bnf.fr/ark:/12148/btv1b8454669r)           | [📁](data/bnf-fr.-1553)  [**B**](https://data.biblissima.fr/w/Item:Q51630)          | 506r-508v   | vers       |        13 | ✓       |       5 |           10 |     506 |        11153 | Fabliau           | Le Meunier d'Arleux                                       |
| [BnF fr. 1443](https://gallica.bnf.fr/ark:/12148/btv1b52510692j)          | [📁](data/bnf-fr.-1443)  [**B**](https://data.biblissima.fr/w/Item:Q46585)          | 1ra-3rb     | vers       |        13 | ✓       |       5 |           14 |     418 |        10840 | chanson de geste  | Garin le Loherain                                         |
| [BnF NAF 23686](https://gallica.bnf.fr/ark:/12148/btv1b8446925z)          | [📁](data/bnf-naf-23686)  [**B**](https://data.biblissima.fr/w/Item:Q68314)         | 112ra-114rb | prose      |        13 | ✓       |       5 |           10 |     424 |        17817 | légendier         | Vie de saint Alexis                                       |
| [BnF fr. 12603](https://gallica.bnf.fr/ark:/12148/btv1b104673329)         | [📁](data/bnf-fr.-12603)  [**B**](https://data.biblissima.fr/w/Item:Q46033)         | 203ra-205ra | vers       |        13 | ✓       |       5 |           16 |     442 |        14126 | chanson de geste  | Fierabras                                                 |
| [BnF fr. 2173](https://gallica.bnf.fr/ark:/12148/btv1b10022504n)          | [📁](data/bnf-fr.-2173)  [**B**](https://data.biblissima.fr/w/Item:Q48587)          | 96r-97v     | vers       |        13 | ✓       |       4 |            8 |     240 |         5269 | Fabliau           | La Mal Honte                                              |
| [BnF fr. 19152](https://gallica.bnf.fr/ark:/12148/btv1b52513419n)         | [📁](data/bnf-fr.-19152)  [**B**](https://data.biblissima.fr/w/Item:Q48011)         | 120vd-122rc | vers       |        13 | ✓       |       4 |           13 |     529 |        11087 | Fabliau           | C'est li Romanz des Braies                                |
| [BnF fr. 12615](https://gallica.bnf.fr/ark:/12148/btv1b60007945)          | [📁](data/bnf-fr.-12615)  [**B**](https://data.biblissima.fr/w/Item:Q46037)         | 230v-231r   | vers       |        13 | ✓       |       2 |            5 |      62 |         3336 | chansonnier       | chansonnier de Noailles _ Chanson d'amour d'Adam le bossu |
| [BnF, fr. 13568](https://gallica.bnf.fr/ark:/12148/btv1b8447868p)         | [📁](data/bnf,-fr.-13568)                                                           | 1r-3v       | historique |        14 | ✓       |       4 |           24 |     154 |         2610 | historique        | Mémoires de saint Louis                                   |
| [BnF fr. 5024](https://gallica.bnf.fr/ark:/12148/btv1b9059518w)           | [📁](data/bnf-fr.-5024)  [**B**](https://data.biblissima.fr/w/Item:Q51380)          | 1r-3r       | prose      |        14 | ✗       |       4 |           17 |     204 |        10631 | Formulaire        | Le formulaire d'Odart Morchesne                           |
| [BnF fr. 12554](https://gallica.bnf.fr/ark:/12148/btv1b90615215)          | [📁](data/bnf-fr.-12554)                                                            | 1r-2v       | prose      |        14 | ✗       |       4 |            2 |     178 |         7181 | roman             | roman                                                     |
| [BnF, ms fr. 574](https://gallica.bnf.fr/ark:/12148/btv1b84526412)        | [📁](data/bnf-fr.574)                                                          | 4v-5v       | religieux  |        14 | ✓       |       3 |           11 |     113 |         2023 | religieux         | Image du monde                                            |
| [BnF arsenal 3525](https://gallica.bnf.fr/ark:/12148/btv1b550008195)      | [📁](data/bnf-arsenal-3525)  [**B**](https://data.biblissima.fr/w/Item:Q34101)      | 88v-91v     | vers       |        14 | ✓       |       7 |           18 |     185 |         4377 | Fabliau           | Dit des trois Dames de Paris_                             |
| [BnF fr. 12558](https://gallica.bnf.fr/ark:/12148/btv1b100261089)         | [📁](data/bnf-fr.-12558)  [**B**](https://data.biblissima.fr/w/Item:Q45992)         | 1ra-3ra     | vers       |        14 | ✓       |       5 |           10 |     440 |        14017 | chanson de geste  | Chevalier du cygne                                        |
| [BnF fr. 840](https://gallica.bnf.fr/ark:/12148/btv1b105375900)           | [📁](data/bnf-fr.-840)  [**B**](https://data.biblissima.fr/entity/Q52525)           | 266r-267v   | didactique |        14 | ✓       |       4 |           11 |     257 |         6381 | Didactique        | Art de Dictier                                            |
| [BnF fr. 619](https://gallica.bnf.fr/ark:/12148/btv1b55006072j)           | [📁](data/bnf-fr.-619)  [**B**](https://data.biblissima.fr/w/Item:Q51833)           | 1ra-4vb     | prose      |        14 | ✓       |       6 |           12 |     356 |        11147 | traité de chasse  | Gaston Phébus, Livre de chasse                            |
| [BnF, fr. 13568](https://gallica.bnf.fr/ark:/12148/btv1b8447868p)         | [📁](data/bnf-fr.-13568)                                                           | 1r-5r       | prose      |        14 | ✓       |       5 |           10 |     199 |         3371 | historique        | Mémoires de Froissart                                     |
| [BnF fr. 1357](https://gallica.bnf.fr/ark:/12148/btv1b90599151)           | [📁](data/bnf-fr.-1357)  [**B**](https://data.biblissima.fr/w/Item:Q46380)          | 1v-5r       | prose      |        15 | ✗       |       4 |           10 |     320 |        12680 | traité astronomie | Simon de Phares, Recueil des plus celebres astrologues    |
| [BnF, Arsenal, ms-3346](https://gallica.bnf.fr/ark:/12148/btv1b52503762d) | [📁](data/bnf,-arsenal,-ms-3346)  [**B**](https://data.biblissima.fr/w/Item:Q33125) | 1r-3v       | prose      |        15 | ✓       |       5 |           12 |     285 |         7194 | chanson de geste  | Garin le lorrain                                          |
| [BnF fr. 11610](https://gallica.bnf.fr/ark:/12148/btv1b8451110g)          | [📁](data/bnf-fr.-11610)  [**B**](https://data.biblissima.fr/w/Item:Q45651)         | 1r-4r       | prose      |        15 | ✓       |       7 |           10 |     167 |         5435 | roman             | Roman du comte d’Artois.                                  |
| [BnF fr. 1881](https://gallica.bnf.fr/ark:/12148/btv1b9060530t)           | [📁](data/bnf-fr.-1881)  [**B**](https://data.biblissima.fr/w/Item:Q47893)          | 93r-96r     | vers       |        16 | ✗       |       4 |           11 |     194 |         3941 | hagiographie      | chanson                                                   |
| [BnF fr. 1881](https://gallica.bnf.fr/ark:/12148/btv1b9060530t)           | [📁](data/bnf-fr.-1881)  [**B**](https://data.biblissima.fr/w/Item:Q47893)          | 93r-95r     | verse      |        16 | ✗       |       3 |            8 |     111 |         2031 | hagiographie      | Vie de saint Alexis                                       |

<!-- EndTable -->

## Metrics

<!-- StartMetric -->

### Total number of pages

131

### Regions

- MainZone (351)
- MarginTextZone (30)
- DropCapitalZone (246)
- RunningTitleZone (27)
- NumberingZone (51)
- Not specified (18)
- StampZone (8)
- text (8)
- Illustration (1)
- DecorationZone (14)
- QuireMarksZone (1)
- MusicZone (6)

### Lines

- Not specified (71)
- DefaultLine (9018)
- InterlinearLine (38)
- HeadingLine (13)
- default (45)
- Numbering (1)

<!-- EndMetric -->

## Funding

This project was funded by the Bibliothèque nationale de France through the 2022 project calls from
[Datalab](https://www.bnf.fr/fr/bnf-datalab) for 2023.

## Cite the project

> Clérice, T., Chagué, A., Gille-Levenson, M., Brisville-Fertin, O., Pinche, A., Camps, J., Fischer, F., Boschetti, F., Guadagnini, E., Guilhem Couffignal, G., Canteaut, O., Romary, L., Reboul, M., Perreaux, N., Poibeau, T., Smith, M., Norindr, J., Glaise, A., Navas Farré, M., Bordier, J., Leroy, N., Alba, R., & Rubin, G. *HTRomance* [Data set]. https://htromance-project.github.io/
```
@misc{Clerice_HTRomance,
author = {Clérice, Thibault and Chagué, Alix and Gille-Levenson, Matthias and Brisville-Fertin, Olivier and Pinche, Ariane and Camps, Jean-Baptiste and Fischer, Franz and Boschetti, Federico and Guadagnini, Elisa  and Guilhem Couffignal, Gilles and Canteaut, Olivier and Romary, Laurent and Reboul, Marianne and Perreaux, Nicolas and Poibeau, Thierry and Smith, Marc and Norindr, Jade and Glaise, Anthony and Navas Farré, Marina and Bordier, Julie and Leroy, Noé and Alba, Rachele and Rubin, Giorgia},
title = {{HTRomance}},
url = {https://htromance-project.github.io/}
}
```

## Infrastructure

This project relied on the [CREMMA infrastructure](https://www.dim-map.fr/projets-soutenus/cremma/).

