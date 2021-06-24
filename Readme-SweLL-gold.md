# ReadMe: SweLL-gold collection
(Elena Volodina, 2021-06-24)

*The most recent version of this ReadMe file is available at https://spraakbanken.github.io/swell-release-v1/Readme-SweLL-gold*

SweLL-gold corpus is a corpus of essays written by adult learners of Swedish. It was collected during the period of 20017-2021, and contains 502 essays that have been pseudonymized, normalized and correction annotated. 
More information about this corpus can be found in the *Metadata section* below, and in the articles in the *References* section (e.g. Volodina et al., 2019)


### SweLL-gold.zip contains

1. metadata.xlsx - a spreadsheet containing all metadata ordered by essay-ID. Attributes and variables are described in the Metadata file below.
2. swelldata.json - all SweLL-gold essays (502) in a json format (aka SVALA format), see Wirén et al (2019) for the description. The json representation contains three objects: "source", "target" and "edges". Edges are links going between token-id in the source to token-id in the target, with tags describing the difference between one and another. Additionally, pseudonymization tags may be attached to the links.
3. swelldata.txt - raw texts, both  original and target versions, in one file 
4. swellOriginal-folder contains    
    * sourceSwell.txt - raw text files with original essays
    * sourceSwell.xml - an xml version of the original essays following Korp format. Attributes and variables are described in the Metadata file below.
5. swellTarget-folder contains    
    * targetSwell.txt - raw text files with normalized essays
    * targetSwell.xml - an xml version of the normalized essays following Korp format. Attributes and variables are described in the Metadata file below.
6. the current readme file 

Note that no linguistic annotation is added to the essays. 
Each format includes a so-called SVALA-link (or full-text link) for each essay. Using that link you can open an essay in a full-text version in a parralel representation (original, target, tags on the links between original and target tokens) using SVALA tool. In SVALA, you will be able to play with various annotation modes and tagsets. However, please be aware that the added annotations are not saved to any database. 

* To use SVALA, please have a look at the video: https://gubox.box.com/s/tp5gm8dua0avs7luqbgxwicws5dl0jh5
* Currently, SVALA manual is available only in Swedish 


## Metadata description:
* https://spraakbanken.github.io/swell-release-v1/Metadata-SweLL


## Reminder of the access agreement
* Please note the agreement conditions: 
   * the access is individual following an application
   * the user needs to be affiliated in EU and work in the context of second language (research, teaching, or development)
   * the data cannot be re-distributed, copied or sold
   * the use of the data has to be acknowledged by citing proper publications, e.g. see References below

## Cite one of the following when using this corpus


## References
Cite one or several of the following when using this corpus:

* Beáta Megyesi, Sofia Johansson, Dan Rosén,Carl-Johan Schenström, Gunlög Sundberg, Mats Wirén & Elena Volodina. (2018). Learner Corpus Anonymization in the Age of GDPR: Insights from the Creation of a Learner Corpus of Swedish. Proceedings of the 7th NLP4CALL workshop.
* Elena Volodina, Lena Granstedt, Arild Matsson, Beáta Megyesi, Ildikó Pilán, Julia Prentice, Dan Rosén, Lisa Rudebeck, Carl-Johan Schenström, Gunlög Sundberg and Mats Wirén (2019). The SweLL Language Learner Corpus: From Design to Annotation. Northern European Journal of Language Technology, Special Issue.
* Wirén Mats, Arild Matsson, Dan Rosén, Elena Volodina. 2019. SVALA: Annotation of Second-Language Learner Text Based on Mostly Automatic Alignment of Parallel Corpora. CLARIN-2018 post-conference volume. LiUP Press.
* ...more references can be found at https://spraakbanken.gu.se/en/projects/swell

