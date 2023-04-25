---
layout: page
title:  Tools and Web services
rank: 6
---


# Semi-automatic annotation tool

A semi-automatic text annotation tool is developped by the project. It takes PDF documents as input and processes them automatically by applying the three following steps:
- layout detection,
- optical characters recognition (with PERO OCR),
- named entities recognition (fine-tuned CamemBERT model).

Users can then check and manually correct each automatically detected and processed text section.

| ![SODUCO corpus of directories](./public/images/SODUCO_Corpus.png) |
|:--:|
| <b>The trade directories from the 19<sup>th</sup> century are a challenging dataset with very heterogeneous layouts, fonts, and contents. Source: gallica.bnf.fr / Bibliothèque nationale de France</b>|


| ![SODUCO text annotation tool](./public/images/AnnotationTool.png) |
|:--:|
| <b>SODUCO text annotation tool</b>|

# Geohistorical geocoding tool

| ![SODUCO geohistorical geocoding tool](./public/images/GeocoderHistorique.png) |
|:--:|
| <b>The historical geocoder takes both addresses and dates into account</b>|

# Old maps vectorisation tool

Add a description here.

| ![SODUCO vectorisation tool](./public/images/Example.png) |
|:--:|
| <b>Caption for the image</b>|

# Vector data validation and correction tool

A collaborative tool to validate and edit geospatial data and more is developped to improve data quality by getting a human validation of any type of geospatial data. It allows users to improve this quality by creating, removing, modifying or validating any feature (geometry and attributes).

| ![SODUCO validation tool](./public/images/data-validation_general-view.png) | ![SODUCO validation tool](./public/images/data-validation_update_attrs.png) |
|:--:|:--:|
| <b>General view of the tool with uploaded data</b>|<b>Edit mode, creation of the geometry of a new feature</b>|

| ![SODUCO validation tool](./public/images/data-validation_draw_mode.png) | ![SODUCO validation tool](./public/images/data-validation_check_feature_status.png) |
|:--:| :--:|
| <b>Edit mode, change of attributes of an existing feature</b>|<b>Status mode to see what features were created, removed or modified</b>|

# Data and historical sources catalogue

A [catalog](https://soduco.github.io/catalog/) has been developped to store, reference and retrieve archival records and digital data used and produced throughout the project.

| ![SODUCO catalogue](./public/images/catalog_searchpage.png) |
|:--:|
| <b>SODUCO catalog</b>|
