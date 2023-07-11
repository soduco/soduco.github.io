---
layout: page
title:  Open datasets
rank: 5
---

## Benchmark dataset for NER models used on noisy OCR predictions

 A benchmark dataset for NER models and noisy OCR predictions has been created based on our corpus of directories and is freely available:
- suitable for OCR evaluation,
- suitable for NER fine-tuning self-supervised and supervised,
- suitable for NER evaluation.

8, 765 reference entries from a selection of directories were manually corrected and annotated with 34, 242 entities. Entries contain 3.9 entities on average.
Reference tagged entities were then projected on OCR predictions done by tree different OCR systems. This resulted in a variable loss of entries:
- for PERO OCR: 8, 392 valid entries were generated, 
- for Tesseract: 8, 700 valid entries were generated, 
- for Kraken: 7, 990 valid entries were generated. 

The resulting intersection of the sets of valid entries contains 7, 725 entries for the tree OCR systems (and the reference), or 8, 341 entries if we consider PERO OCR and Tesseract only.

The dataset is described in more detail and can be dowloaded at https://zenodo.org/record/6394464

## Benchmark dataset for historical maps segmentation

A benchmark dataset for historical maps segmentation has been created and used to organise a competition at the ICDAR 2021 conference: https://icdar21-mapseg.github.io/

## Dataset "Annuaires historiques parisiens, 1798-1914"

Réf. Annuaires historiques parisiens, 1798-1914. Extraction structurée et géolocalisée à l’adresse des listes nominatives [par ordre alphabétique et par activité] dans les volumes numérisés*, SoDUCo Team, V.01 - mai 2023, Paris.

Comming soon...

For more information, see the 2th Session of the SoDUCo-BnF seminar : *Relocating addresses from commerce directories, Paris, XIXth century. A corpus of urban locations at a large scale*, 10 novembre 2022, Paris, Bibliothèque nationale de France.
cf. https://soduco.github.io/public/images/Atelier_Soduco_Bnf_Programme_Journee_10novembre.pdf 

## The geohistorical knowledge graph of shops and businesses

An approach was proposed to create a geohistorical knowledge graph that would enable the evolution of shops and businesses in Paris to be tracked over time, based on named entities extracted from trade directories and addresses extracted from old maps processed as part of the project. 
A first knowledge graph about the activities related to photography has been constructed and published on the Web of Data. 
Among other things, it can be used to answer the following questions:
- What was the address of business X in 1861?
- How many shops or businesses of this type were located in the rue de Rivoli in 1856?
- Which shops or businesses were located in an area defined by a bounding box or polygon in 1875?
- Which shops or businesses moved during their existence?
- Which shops or businesses were taken over by another owner carrying on the same activity?

This geohistorical knowledge graph can be queried either though a [cartographic interface](https://soduco.github.io/ic_2023_photographes_parisiens/) or through a [SPARQL endpoint](https://dir.geohistoricaldata.org/). 
It can also be downloaded from the [Github repository](https://github.com/soduco/ic_2023_photographes_parisiens) related to the [article](https://hal.science/hal-04121643/) describing the geohistorical knowledge graph creation process.

This knowledge graph was created automatically: it necessarily contains errors resulting from the various processes used to produce it (directory entries segmentation, OCR, NER, geocoding, linking, etc.).

We plan to publish more data about other activities and business types by the end of the project.



