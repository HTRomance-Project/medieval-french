HTRomance, Medieval French corpus of ground-truth for Handwritten Text Recognition
  and Layout Segmentation
=====================
![characters badge](badges/characters.svg) ![regions badge](badges/regions.svg) ![lines badge](badges/lines.svg) ![files badge](badges/files.svg) [![Tests](https://github.com/HTRomance-Project/medieval-french/actions/workflows/test.yml/badge.svg)](https://github.com/HTRomance-Project/medieval-french/actions/workflows/test.yml)

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

| Shelfmark                                                                  | Links                          | Range       | Type       |   Century | Color   |   Pages |   Main Zones |   Lines |   Characters | Genre      | Content                                                   |
|----------------------------------------------------------------------------|--------------------------------|-------------|------------|-----------|---------|---------|--------------|---------|--------------|------------|-----------------------------------------------------------|
| [BnF, fr. 104](https://gallica.bnf.fr/ark:/12148/btv1b90588354)            | [📁](data/bnf-fr-104)          | 1r-2v       | prose      |        13 | ✗       |       4 |           10 |     376 |        15398 |            | Roman de Tristan                                          |
| [BnF, fr. 747](https://gallica.bnf.fr/ark:/12148/btv1b52503704t)           | [📁](data/bnf-fr-747)          | 1v-2v       | prose      |        13 | ✓       |       1 |            2 |      91 |         4351 |            | Estoire du Roman del Saint Graal                          |
| [BnF, fr. 1669](https://gallica.bnf.fr/ark:/12148/btv1b9059692s)           | [📁](data/bnf-fr-1669)         | 1r-3v       | prose      |        13 | ✗       |       3 |           15 |     484 |        10182 | Narratives | roman                                                     |
| [BnF, fr. 20050](https://gallica.bnf.fr/ark:/12148/btv1b60009580)          | [📁](data/bnf-fr-20050)        | 4r-5v       | vers       |        13 | ✓       |       4 |            4 |      84 |         3793 |            | Le chansonnier de saint Germain                           |
| [BnF, fr. 2168](https://gallica.bnf.fr/ark:/12148/btv1b525135854)          | [📁](data/bnf-fr-2168)         | 88rb        | vers       |        13 | ✓       |       5 |           20 |     370 |         7964 |            | Le sacristain                                             |
| [BnF, NAF 10039](https://gallica.bnf.fr/ark:/12148/btv1b52500695k)         | [📁](data/bnf-naf-10039)       | 1r-3r       | verse      |        13 | ✓       |       4 |           12 |     116 |         3165 |            | Roman d'Aspremont                                         |
| [BnF, fr. 1450](https://gallica.bnf.fr/ark:/12148/btv1b8415202d)           | [📁](data/bnf-fr-1450)         | 1r-2v       | verse      |        13 | ✓       |       4 |           13 |     709 |        14817 |            | Roman de Troie                                            |
| [BnF, fr. 17229](https://gallica.bnf.fr/ark:/12148/btv1b9061254h)          | [📁](data/bnf-fr-17229)        | 127r-129r   | prose      |        13 | ✗       |       3 |           12 |     479 |        12511 |            | Legendier                                                 |
| [BnF, fr. 23117](https://gallica.bnf.fr/ark:/12148/btv1b90639749)          | [📁](data/bnf-fr-23117)        | 299vc-304rb | prose      |        13 | ✗       |       5 |           21 |     736 |        19852 |            | Vie de saint Martin                                       |
| [BnF, fr. 6447](https://gallica.bnf.fr/ark:/12148/btv1b90075392)           | [📁](data/bnf-fr-6447)         | 270r-271v   | prose      |        13 | ✗       |       4 |           12 |     383 |        13246 |            | Vie de saint Martin                                       |
| [BnF, fr. 12581](https://gallica.bnf.fr/ark:/12148/btv1b53000323h)         | [📁](data/bnf-fr-12581)        | 373r-375v   | vers       |        13 | ✓       |       4 |            8 |     306 |         9289 |            | Li Fabliaus des Treces                                    |
| [BnF, fr. 1635](https://gallica.bnf.fr/ark:/12148/btv1b105253083)          | [📁](data/bnf-fr-1635)         | fol. 4v-5v  | vers       |        13 | ✓       |       3 |            7 |     219 |         4838 |            | Testament de l'âne                                        |
| [BnF, fr. 1553](https://gallica.bnf.fr/ark:/12148/btv1b8454669r)           | [📁](data/bnf-fr-1553)         | 506r-508v   | vers       |        13 | ✓       |       5 |           10 |     506 |        11153 |            | Le Meunier d'Arleux                                       |
| [BnF, fr. 1443](https://gallica.bnf.fr/ark:/12148/btv1b52510692j)          | [📁](data/bnf-fr-1443)         | 1ra-3rb     | vers       |        13 | ✓       |       5 |           14 |     418 |        10840 |            | Garin le Loherain                                         |
| [BnF, NAF 23686](https://gallica.bnf.fr/ark:/12148/btv1b8446925z)          | [📁](data/bnf-naf-23686)       | 112ra-114rb | prose      |        13 | ✓       |       5 |           10 |     424 |        17817 |            | Vie de saint Alexis                                       |
| [BnF, fr. 12603](https://gallica.bnf.fr/ark:/12148/btv1b104673329)         | [📁](data/bnf-fr-12603)        | 203ra-205ra | vers       |        13 | ✓       |       5 |           16 |     442 |        14126 |            | Fierabras                                                 |
| [BnF, fr. 2173](https://gallica.bnf.fr/ark:/12148/btv1b10022504n)          | [📁](data/bnf-fr-2173)         | 96r-97v     | vers       |        13 | ✓       |       4 |            8 |     240 |         5269 |            | La Mal Honte                                              |
| [BnF, fr. 19152](https://gallica.bnf.fr/ark:/12148/btv1b52513419n)         | [📁](data/bnf-fr-19152)        | 120vd-122rc | vers       |        13 | ✓       |       4 |           13 |     529 |        11087 |            | C'est li Romanz des Braies                                |
| [BnF, fr. 12615](https://gallica.bnf.fr/ark:/12148/btv1b60007945)          | [📁](data/bnf-fr-12615)        | 230v-231r   | vers       |        13 | ✓       |       2 |            5 |      62 |         3336 |            | chansonnier de Noailles _ Chanson d'amour d'Adam le bossu |
| [BnF, fr. 13568](https://gallica.bnf.fr/ark:/12148/btv1b8447868p)          | [📁](data/bnf-fr-13568)        | 1r-5r       | prose      |        14 | ✓       |       5 |           10 |     199 |         3371 |            | Mémoires de Froissart                                     |
| [BnF, fr. 13568](https://gallica.bnf.fr/ark:/12148/btv1b8447868p)          | [📁](data/bnf-fr-13568)        | 1r-3v       | historique |        14 | ✓       |       4 |           24 |     154 |         2610 |            | Mémoires de saint Louis                                   |
| [BnF, fr. 5024](https://gallica.bnf.fr/ark:/12148/btv1b9059518w)           | [📁](data/bnf-fr-5024)         | 1r-3r       | prose      |        14 | ✗       |       4 |           17 |     204 |        10631 |            | Le formulaire d'Odart Morchesne                           |
| [BnF, fr. 12554](https://gallica.bnf.fr/ark:/12148/btv1b90615215)          | [📁](data/bnf-fr-12554)        | 1r-2v       | prose      |        14 | ✗       |       4 |            2 |     178 |         7181 | Narratives | roman                                                     |
| [BnF, fr. 574](https://gallica.bnf.fr/ark:/12148/btv1b84526412)            | [📁](data/bnf-fr-574)          | 4v-5v       | religieux  |        14 | ✓       |       3 |           11 |     113 |         2022 |            | Image du monde                                            |
| [BnF, Arsenal, ms. 3525](https://gallica.bnf.fr/ark:/12148/btv1b550008195) | [📁](data/bnf-arsenal-ms-3525) | 88v-91v     | vers       |        14 | ✓       |       7 |           18 |     185 |         4377 |            | Dit des trois Dames de Paris_                             |
| [BnF, fr. 12558](https://gallica.bnf.fr/ark:/12148/btv1b100261089)         | [📁](data/bnf-fr-12558)        | 1ra-3ra     | vers       |        14 | ✓       |       5 |           10 |     440 |        14017 |            | Chevalier du cygne                                        |
| [BnF, fr. 840](https://gallica.bnf.fr/ark:/12148/btv1b105375900)           | [📁](data/bnf-fr-840)          | 266r-267v   | didactique |        14 | ✓       |       4 |           11 |     257 |         6381 |            | Art de Dictier                                            |
| [BnF, fr. 619](https://gallica.bnf.fr/ark:/12148/btv1b55006072j)           | [📁](data/bnf-fr-619)          | 1ra-4vb     | prose      |        14 | ✓       |       6 |           12 |     356 |        11147 |            | Gaston Phébus, Livre de chasse                            |
| [BnF, Arsenal, ms. 3350](https://gallica.bnf.fr/ark:/12148/btv1b10467112q) | [📁](data/bnf-arsenal-ms-3350) | 1v-3v       | -          |        15 | ✗       |       4 |            9 |     271 |         7959 | Narratives | _                                                         |
| [BnF, fr. 2701](https://gallica.bnf.fr/ark:/12148/btv1b100327752)          | [📁](data/bnf-fr-2701)         | 121r-121v   | prose      |        15 | ✗       |       2 |            5 |     274 |        11654 |            | Epitre de Juvénal des ursins                              |
| [BnF, fr. 1357](https://gallica.bnf.fr/ark:/12148/btv1b90599151)           | [📁](data/bnf-fr-1357)         | 1v-5r       | prose      |        15 | ✗       |       4 |           10 |     320 |        12680 |            | Simon de Phares, Recueil des plus celebres astrologues    |
| [BnF, Arsenal, ms. 3346](https://gallica.bnf.fr/ark:/12148/btv1b52503762d) | [📁](data/bnf-arsenal-ms-3346) | 1r-3v       | prose      |        15 | ✓       |       5 |           12 |     285 |         7194 |            | Garin le lorrain                                          |
| [BnF, fr. 11610](https://gallica.bnf.fr/ark:/12148/btv1b8451110g)          | [📁](data/bnf-fr-11610)        | 1r-4r       | prose      |        15 | ✓       |       7 |           10 |     167 |         5435 |            | Roman du comte d’Artois.                                  |
| [BnF, fr. 1881](https://gallica.bnf.fr/ark:/12148/btv1b9060530t)           | [📁](data/bnf-fr-1881)         | 93r-96r     | vers       |        16 | ✗       |       4 |           11 |     194 |         3941 | Narratives | chanson                                                   |
| [BnF, fr. 1881](https://gallica.bnf.fr/ark:/12148/btv1b9060530t)           | [📁](data/bnf-fr-1881)         | 93r-95r     | verse      |        16 | ✗       |       3 |            8 |     111 |         2031 | Narratives | Vie de saint Alexis                                       |

<!-- EndTable -->

## Metrics

<!-- StartMetric -->

### Total number of pages

145

### Regions

- MainZone (392)
- MarginTextZone (40)
- StampZone (10)
- Not specified (20)
- NumberingZone (56)
- DropCapitalZone (250)
- GraphicZone (3)
- RunningTitleZone (27)
- text (8)
- Illustration (1)
- DecorationZone (11)
- QuireMarksZone (1)
- MusicZone (6)

### Lines

- DefaultLine (10508)
- InterlinearLine (39)
- Numbering (4)
- Not specified (73)
- HeadingLine (13)
- default (45)

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

