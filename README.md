# AMIA 2021 Workshop on Clinical Information Extraction for Collaborative EHR-based Clinical Research

The following materials are designed for AMIA 2021 workshop on Clinical Information Extraction for Collaborative EHR-based Clinical Research (W26).

## Handouts

The slides used in our workshop and pre-recorded videos could be downloaded from AMIA workshop [Handout Downloads](https://s4.goeshow.com/amia/annual/2021/handout_downloads.cfm?) page.

## Backbone

[Backbone](https://github.com/OHNLP/Backbone) aims to simplify scalable ETL (Extract-Transform-Load) processes by transforming such operations into a sequence of simple user-accessible JSON configurations, with a particular focus on Healthcare NLP-related tasks.

The backbone input database URL 

## MedTagger

[MedTagger](https://github.com/OHNLP/MedTagger) contains a suite of programs that the Mayo Clinic NLP program developed. 
It includes three major components: 

- MedTagger for indexing based on dictionaries
- MedTaggerIE for information extraction based on patterns
- MedTaggerML for machine learning-based named entity recognition.


## Data Annotation

We offer several materials for you to experience the data annotation process in the case study section, which includes:

1. [MedTator](https://github.com/OHNLP/MedTator). MedTator is a serverless web tool for data annotation. We use this tool in our case study section. For more detailed documents about MedTator, you can visit [MedTator Wiki](https://github.com/OHNLP/MedTator/wiki)
2. [Annotation Guideline](https://github.com/OHNLP/AMIA2021Workshop/blob/main/annotation_sample/Annotation_Guideline.pdf). The annotation guideline describes what we want to annotate in this task.
3. [Annotation Schema](https://github.com/OHNLP/AMIA2021Workshop/blob/main/annotation_sample/COVID_AES_AMIA.dtd). This file defines the entity tags and relation tags to be extracted in the annotation.
4. Sample data. The `annotation_sample/` folder of this repo contains the sample data for case study. The `raw_txt` folder contains the raw text file, and the `ann_xml` folder contains the our annotated samples.
