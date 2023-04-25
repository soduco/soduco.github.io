---
layout: page
title:  Datasets
rank: 5
---

# Open datasets, benchmarks and other resources

### Benchmark dataset for NER models used on noisy OCR predictions

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

### Benchmark dataset for historical maps segmentation

A benchmark dataset for historical maps segmentation has been created and used to organise a commetition at the ICDAR 2021 conference: https://icdar21-mapseg.github.io/

