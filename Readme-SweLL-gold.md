# ReadMe: SweLL-gold collection
*(Elena Volodina, August, 17, 2021)*

*Contact info: swell@svenska.gu.se*

*The most recent version of this ReadMe file is available at [https://spraakbanken.github.io/swell-release-v1/Readme-SweLL-gold](https://spraakbanken.github.io/swell-release-v1/Readme-SweLL-gold)*

SweLL-gold corpus is a corpus of essays written by adult learners of Swedish. It was collected during the period of 20017-2021 in the SweLL project [https://spraakbanken.gu.se/en/projects/swell/](https://spraakbanken.gu.se/en/projects/swell/), and contains 502 essays that have been pseudonymized, normalized and correction annotated. 
More information about this corpus can be found in the *Metadata section* below, and in the articles in the *References* section (e.g. Volodina et al., 2019).


## SweLL-gold folder contains
Descriptive files:
1. the current *ReadMe* file [https://spraakbanken.github.io/swell-release-v1/Readme-SweLL-gold](https://spraakbanken.github.io/swell-release-v1/Readme-SweLL-gold)
2. *swell_metadataDescription.pdf* -- a pdf version (as of August 2021) of the metadata-description available at the link https://spraakbanken.github.io/swell-release-v1/Metadata-SweLL. The information available at the link is continuously updated, which means it could be useful to check it for later updates.
3. *swell_metadata.xlsx* - a spreadsheet containing all metadata ordered by essay-ID. Attributes and variables are described in the Metadata file below.
4. *stats_pseudoLABEL.xlsx* - a spreadsheet containing all pseudonymization labels ordered by essay-ID.
5. *stats_corrLABEL.xlsx* - a spreadsheet containing all correction (aka error) labels ordered by essay-ID.

Data files:

6. *swelldata.json* - all SweLL-gold essays (502) in a json format (aka SVALA format), see Wirén et al. (2019) for the description. The json representation contains three objects: "source", "target" and "edges". Edges are links going between token-id in the source to token-id in the target, with tags describing the difference between one and another. Additionally, pseudonymization tags may be attached to the links.
7.  *swelldata.txt* - raw texts, both  original and target versions, in one file 
8. *swellOriginal*-folder contains    
    8.1 *sourceSweLL.txt* - raw text files with original essays (pseudonymized versions)
    
    8.2 *sourceSweLL.xml* - an xml version of the original essays following Korp format. Attributes and variables are described in the Metadata file below. No linguistic annotation is added to this version
    
    8.3 *sourceSweLL_Ling_annotated.xml* -- an xml version (Korp format) of the original essays with linguistic annotation using Sparv-pipeline.
9. *swellTarget*-folder contains    
    9.1 *targetSweLL.txt* - raw text files with normalized essays
    
    9.2 *targetSweLL.xml* - an xml version of the normalized essays following Korp format. Attributes and variables are described in the Metadata file below. No linguistic annotation is added to this version
    
    9.3 *targetSweLL_Ling_annotated.xml* -- an xml version (Korp format) of the original essays with linguistic annotation using Sparv-pipeline.
 

**Note!** Each format includes a so-called SVALA-link (or full-text link) for each essay. Using that link you can open an essay in a full-text version in a parralel representation (original, target, tags on the links between original and target tokens) using SVALA tool (Wirén et al. 2019). In SVALA, you will be able to play with various annotation modes and tagsets. However, please be aware that the added annotations are not saved to any database. 

* To use SVALA, please have a look at the video: [https://gubox.box.com/s/tp5gm8dua0avs7luqbgxwicws5dl0jh5](https://gubox.box.com/s/tp5gm8dua0avs7luqbgxwicws5dl0jh5)
* Currently, SVALA manual is available only in Swedish 

## Metadata description:
* https://spraakbanken.github.io/swell-release-v1/Metadata-SweLL

## Reminder of the access agreement
Please note the agreement conditions: 
* Access is individual, free of charge and is administered via an application: [https://sunet.artologik.net/gu/swell](https://sunet.artologik.net/gu/swell)
* Acc. to the GDPR restrictions, the user needs to be affiliated in EU and work in the context of second language (research, teaching, or development)
* License information: CLARIN - ID, -PRIV, -NORED, -BY (explanations: [https://www.kielipankki.fi/support/clarin-eula/#res](https://www.kielipankki.fi/support/clarin-eula/#res))
   * -ID: The access is individual on authentification
   * -PRIV: There are personal data in the resource
   * -NORED: The data cannot be re-distributed, copied or sold
   * -BY: the use of the data has to be acknowledged by citing proper publications, e.g. see *References* below

## Always cite 
* ... Volodina et al. (2019) if you use this corpus

## References
Cite one or several of the following when using this corpus:

* Beáta Megyesi, Sofia Johansson, Dan Rosén,Carl-Johan Schenström, Gunlög Sundberg, Mats Wirén & Elena Volodina. (2018). Learner Corpus Anonymization in the Age of GDPR: Insights from the Creation of a Learner Corpus of Swedish. Proceedings of the 7th NLP4CALL workshop. [https://ep.liu.se/en/conference-article.aspx?series=ecp&issue=152&Article_No=6](pdf)

* Elena Volodina, Lena Granstedt, Arild Matsson, Beáta Megyesi, Ildikó Pilán, Julia Prentice, Dan Rosén, Lisa Rudebeck, Carl-Johan Schenström, Gunlög Sundberg and Mats Wirén (2019). The SweLL Language Learner Corpus: From Design to Annotation. Northern European Journal of Language Technology, Special Issue. [https://nejlt.ep.liu.se/article/view/1374](https://nejlt.ep.liu.se/article/view/1374)

* Wirén Mats, Arild Matsson, Dan Rosén, Elena Volodina. 2019. SVALA: Annotation of Second-Language Learner Text Based on Mostly Automatic Alignment of Parallel Corpora. CLARIN-2018 post-conference volume. LiUP Press. [https://ep.liu.se/en/conference-article.aspx?series=ecp&issue=159&Article_No=23](pdf)

* ...more references can be found at https://spraakbanken.gu.se/en/projects/swell

