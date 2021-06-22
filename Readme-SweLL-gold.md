# ReadMe: SweLL-gold collection

SweLL-gold corpus is a corpus of essays written by adult learners of Swedish. It was collected during the period of 20017-2021, and contains 502 essays that have been pseudonymized, normalized and correction annotated. 
More information about this corpus can be found in the *Metadata section* below, and in the articles in the *References* section (Volodina et al., 2019)

### SweLL-gold.zip contains

1. SweLL-gold corpus files (502 essays) in three formats: 
    * json (SVALA format), see Wirén et al (2019) for the description. The json representation contains three objects: "source", "target" and "edges". Edges are links going between token-id in the source token to token-id in the target token, with tags describing the difference between one and another. Additionally, pseudonymization tags may be attached to the links.   
    * two xml files (Korp format), one for the original version and one for the normalized version. Attributes and variables are described in the Metadata file 
    * two files with raw texts, one for the original version and one for the normalized version
2. metadata in an excel file, ordered by essay-IDs
3. the current readme file 

Note that no linguistic annotation is added to the essays. 
Each format includes a so-called SVALA-link (or full-text link) for each essay. Using that link you can open an essay in a full-text version in a parralel representation (original, target, tags on the links between original and target tokens) using SVALA tool. In SVALA, you will be able to play with various annotation modes and tagsets. However, please be aware that the added annotations are not saved to any database. 

*(Currently, SVALA manual is available only in Swedish.)

## Reminder of the access agreement
* 

## Metadata description:
* https://spraakbanken.github.io/swell-release-v1/Metadata-SweLL

## Cite one of the following when using this corpus
* ... Volodina et al. (2019) if you use this corpus
* ...

## References

* Volodina et al 2019 SweLL on the rise
* Wirén et al. (2019) SVALA
* 

