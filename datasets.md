---
layout: page
title:  Open datasets
rank: 5
---

<div class="collapsible" id="benchmarkNER"><h2>Benchmark dataset for NER models used on noisy OCR predictions</h2></div>
<div class="collapsible-content" id="benchmarkNERdata" markdown="1">

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

This dataset has been used in the work described in the article: [![⟨10.1007/978-3-031-06555-2_30⟩](/assets/img/DOI_logo.svg.png){:.myicon}](https://doi.org/10.1007/978-3-031-06555-2_30 "doi:10.1007/978-3-031-06555-2_30") [![⟨hal-03698609⟩](/assets/img/hal-logo-header.png){:.myicon}](https://hal.science/hal-03698609 "hal:hal-03698609") [![pdf](/assets/img/file-pdf.svg){:.myicon}](https://hal.science/hal-03698609v1/file/preprint_das_2022_abadie_carlinet_chazalon_dumenieu.pdf "pdf").

The dataset is described in more detail and can be downloaded on the Zenodo repository: [![this Zenodo repository](/assets/img/database.svg){:.myicon}](https://zenodo.org/record/6394464 "Zenodo repository").
</div>

<div class="collapsible" id="benchmarkNestedNER"><h2>Benchmark dataset for Nested NER models used on noisy OCR predictions</h2></div>
<div class="collapsible-content" id="benchmarkNestedNERdata" markdown="1">

A benchmark dataset for Nested Named Entity Recognition has been created using the initial dataset for NER models (see <i>Benchmark dataset for NER models used on noisy OCR predictions</i> at the top this page):
- Suitable for evaluating nested named entity recognition approaches (fine-tuning) with a two-levels hierarchy of named entities;
- Includes for each entry :
    - the manually corrected OCR text;
    - PERO OCR output;
    - Tesseract output.

This dataset was used in the [following work presented at ICDAR 2023](https://link.springer.com/chapter/10.1007/978-3-031-41682-8_8): [![<10.1007/978-3-031-41682-8_8>](/assets/img/DOI_logo.svg.png){:.myicon}](https://doi.org/10.1007/978-3-031-41682-8_8 "doi:10.1007/978-3-031-41682-8_8") [![⟨hal-03994759⟩](/assets/img/hal-logo-header.png){:.myicon}](https://hal.science/hal-03994759 "hal:hal-03994759") [![pdf](/assets/img/file-pdf.svg){:.myicon}](https://hal.science/hal-03994759v2/file/Nested_NER_ICDAR_2023_preprint_submit%20%281%29.pdf "pdf").

The dataset is fully described and can be downloaded from Zenodo: : [![this Zenodo repository](/assets/img/database.svg){:.myicon}](https://zenodo.org/record/8167628 "Zenodo repository").
</div>

<div class="collapsible" id="benchmarkSegmentation"><h2>Benchmark dataset for historical maps segmentation</h2></div>
<div class="collapsible-content" id="benchmarkSegmentationdata" markdown="1">

A benchmark dataset for historical maps segmentation has been created and used to organise a [competition at the ICDAR 2021 conference](https://icdar21-mapseg.github.io/): [![Zenodo repository](/assets/img/database.svg){:.myicon}](https://zenodo.org/record/4817662 "Zenodo repository").

[![Teaser for the competition results](/assets/img/play-circle.svg){:.myicon}](https://icdar21-mapseg.github.io/res/Comp-ST_04-teaser.mp4 "Teaser for the competition results")
[![Slides of the teaser for the competition results presentation](/assets/img/file-slides.svg){:.myicon}](https://icdar21-mapseg.github.io/res/teaser_slides_v20210729-1106.pdf "Slides of the teaser for the competition results presentation")
[![Slides of the competition results presentation](/assets/img/file-slides.svg){:.myicon}](https://icdar21-mapseg.github.io/res/presentation_slides_v20210729-1106.pdf "Slides of the competition results presentation")
[![Poster of the competition](/assets/img/images.svg){:.myicon}](https://icdar21-mapseg.github.io/res/poster_v3_A1_compressed.pdf "Poster of the competition")

</div>

<div class="collapsible" id="annuaires"><h2>Dataset "Annuaires historiques parisiens, 1798-1914"</h2></div>
<div class="collapsible-content" id="annuairesdata" markdown="1">

Réf. Annuaires historiques parisiens, 1798-1914. _Extraction structurée et géolocalisée à l’adresse des listes nominatives [par ordre alphabétique et par activité] dans les volumes numérisés_, SoDUCo Team, V.4 - novembre 2023, Paris DataSet Nakala: [![DataSet Nakala](/assets/img/database.svg){:.myicon}](https://nakala.fr/10.34847/nkl.98eem49t "DataSet Nakala")

For more information about this dataset, see the 2nd Session of the SoDUCo-BnF seminar: _Relocating addresses from commerce directories, Paris, XIXth century. A corpus of urban locations at a large scale_, 10 novembre 2022, Paris, Bibliothèque nationale de France. cf. Session Program [![Session Program](/assets/img/file-pdf.svg){:.myicon}](https://soduco.github.io/public/images/Atelier_Soduco_Bnf_Programme_Journee_10novembre.pdf "Session Program") and [related presentations](https://soduco.github.io/soduco_bnf_seminars/#seance2)

</div>

<div class="collapsible" id="knowledgeGraph"><h2>The geohistorical knowledge graph of shops and businesses</h2></div>
<div class="collapsible-content" id="knowledgeGraphdata" markdown="1">

An approach was proposed to create a geohistorical knowledge graph that would enable the evolution of shops and businesses in Paris to be tracked over time, based on named entities extracted from trade directories and addresses extracted from old maps processed as part of the project. 
A first knowledge graph about the activities related to photography has been constructed and published on the Web of Data. 
Among other things, it can be used to answer the following questions:
- What was the address of business X in 1861?
- How many shops or businesses of this type were located in the rue de Rivoli in 1856?
- Which shops or businesses were located in an area defined by a bounding box or polygon in 1875?
- Which shops or businesses moved during their existence?
- Which shops or businesses were taken over by another owner carrying on the same activity?

This geohistorical knowledge graph can be queried either though a [cartographic interface ![cartographic interface](/assets/img/app.svg){:.myicon}](https://soduco.github.io/ic_2023_photographes_parisiens/ "cartographic interface") or through a [SPARQL endpoint ![SPARQL endpoint](/assets/img/app.svg){:.myicon}](https://dir.geohistoricaldata.org/ "SPARQL endpoint").
It can also be downloaded from the [Github repository ![Github repository](/assets/img/file-code.svg){:.myicon}](https://github.com/soduco/ic_2023_photographes_parisiens "Github repository") related to the [article ![⟨hal-04121643⟩](/assets/img/hal-logo-header.png){:.myicon}](https://hal.science/hal-04121643/ "hal:hal-04121643") [![pdf](/assets/img/file-pdf.svg){:.myicon}](https://hal.science/hal-04121643v2/file/Photographes_IC_2023%20%283%29.pdf "pdf") describing the geohistorical knowledge graph creation process.

This knowledge graph was created automatically: it necessarily contains errors resulting from the various processes used to produce it (directory entries segmentation, OCR, NER, geocoding, linking, etc.).

We plan to publish more data about other activities and business types by the end of the project.
</div>

<div class="collapsible" id="popQuartiers"><h2>Datasets "Population des quartiers de Paris (1801-1911)" and "Quartiers de Paris (1860-1919)"</h2></div>
<div class="collapsible-content" id="popQuartiersdata" markdown="1">

Two data sets designed to further contextualize the data contained in the directories. The first is the census of the population at the level of Paris districts (domiciled and de facto population), while the second is spatial data of districts.
- [Population on ![Nakala dataset](/assets/img/database.svg){:.myicon}](https://doi.org/10.34847/nkl.e173c93p "Nakala dataset")
- [Districts on ![Nakala dataset](/assets/img/database.svg){:.myicon}](https://doi.org/10.34847/nkl.a57506s3 "Nakala dataset")

</div>
