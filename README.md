# Europen Named Entities

## Overview

The `unique_entities.csv` dataset is a collection of over 4,000 named entities derived from a comprehensive analysis of major European business newspapers. Each entity in the dataset is associated with a specific country or region, reflecting the geographic or institutional context most closely related to it. This dataset was created using simple Named Entity Recognition (NER) techniques, specifically employing Spacy's NER models.

## Dataset Composition

The dataset encompasses a diverse array of entities, including but not limited to individuals, organizations, locations, and EU institutions. These entities were extracted from an extensive corpus of articles published between January 2001 and August 2023, providing a rich historical perspective on the European economic discourse. To keep the analysis feasable, we chose a random sample of 50,000 docs per country.

**Included Newspapers:**
- CincoDias (Spain): A leading Spanish business daily
- Handelsblatt (Germany): Germany's premier business newspaper
- Il Sole 24 Ore (Italy): Italy's leading source on financial news
- Les Echos (France): France's primary business newspaper
- The Financial Times (UK): *The* international business newspaper based in the UK (not EU, obviously, but hard to ignore when analyzing business daylies)
- WirtschaftsBlatt (Austria): Austria's key business daily

## Methodology

The dataset was generated through the extraction of named entities using Spacy's NER models. The association of each entity with a country or region label was performed manually, ensuring a high degree of accuracy and relevance. The list contains all entities that occured more than 100 times in the respective corpus. The country/region labels follow the list of [Standard country or area codes for statistical use](https://unstats.un.org/unsd/methodology/m49/overview/) provided by the UN.   

## Potential Applications

The dataset is intended to serve as a foundational resource for researchers, journalists, and policymakers. It can be used to:

- Select documents that are associated with a country/region of interest from a large text dataset
- Analyze trends in the representation of (European) countries and institutions in business media
- Investigate the degree of Europeanization of the public sphere as reflected in diverse texts


## Accessing the Dataset

The dataset is freely available for academic and research purposes. We encourage its use for studies related to European public sphere, media analysis, and computational linguistics.

## Disclaimer, Contribution and Support

Please note that this is an early stage dataset that will be corrected/updated in the future. For now, it is based only on the newspapers mentioned above, so it is still missing data from the majority of European countries. We make no claim to completeness or absence of misclassifications.
We welcome contributions from the community, including updates to the dataset, methodological improvements, or corrections. For support or to contribute, please open an issue or a pull request in this repository.

