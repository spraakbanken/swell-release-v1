# ReadMe: SweLL-pilot collection

*(Elena Volodina, August 17, 2021)*

*Contact info: swell@svenska.gu.se*

*The most recent version of this ReadMe file is available at https://spraakbanken.github.io/swell-release-v1/Readme-SweLL-pilot*

SweLL-pilot corpus is a corpus of essays written by adult learners of Swedish. It was collected during the period of 2007-2016, and contains 502 essays that have been anonymized and graded with CEFR labels. In 2020-2021 the SweLL-pilot collection has been added to the SweLL portal to ensure comparable format and attributes with the SweLL-gold collection. 

There are three subcorpora in the SweLL-pilot collection:

* SpIn - 256 essays collected from Language Introduction course (mid-term exams) for newly arrived refugees. Some of the students are recurrent. 
* Sw1203 - 141 essays collected from university students in exam setting, most of who wrote three essays each
* TISUS - 105 essays written as a part of a Test In Swedish for University Studies. All essays are on the same topic "Stress" and of argumentative genre

More information about each subcorpus can be found in the *Metadata* files below, and a few more details in Volodina et al. (2016). ***Note!***, however, that Volodina et al. (2016) cite a bit different number of essays. This is due to the fact that some of the essays have been transcribed and added to the collection at a later stage. 


### SweLL-pilot.zip contains

1. the current ReadMe file [https://spraakbanken.github.io/swell-release-v1/Readme-SweLL-pilot](https://spraakbanken.github.io/swell-release-v1/Readme-SweLL-pilot)

2. SpIn-folder

   2.1 spIn_metadataDescription.pdf - a pdf version (as of August 2021) of the metadata-description available at the link https://spraakbanken.github.io/swell-release-v1/Metadata-SpIn. The information available at the link is continuously updated, which means it could be useful to check it for later updates.
   
   2.2. spIn_metadata.xlsx - a spreadsheet containing all metadata ordered by essay-ID. Attributes and variables are described in the *Metadata* file below.

   2.3 spIn.json - all SpIn essays (256) in a json format (aka SVALA format), see Wirén et al. (2019) for the description. The json representation contains three objects: "source", "target" and "edges". Edges are links going between token-id in the source to token-id in the target, with tags describing the difference between one and another. Additionally, pseudonymization tags may be attached to the links.
   
   2.4 spIn.txt - raw essay texts (i.e. containing no annotation)
   
   2.5 spIn.xml - an xml version of the original essays following Korp format. Attributes and variables are described in the *Metadata* file below.
   
   2.6 spIn_Ling_annotated - an xml version (Korp format) of the original essays with linguistic annotation using Sparv-pipeline.

3. SW1203-folder

   3.1 sw_metadataDescription.pdf - a pdf version (as of August 2021) of the metadata-description available at the link https://spraakbanken.github.io/swell-release-v1/Metadata-SW1203. The information available at the link is continuously updated, which means it could be useful to check it for later updates.
   
   3.2 sw_metadata.xlsx - a spreadsheet containing all metadata ordered by essay-ID. Attributes and variables are described in the *Metadata* file below.
   
   3.3 sw.json - all SpIn essays (141) in a json format (aka SVALA format), see Wirén et al. (2019) for the description. The json representation contains three objects: "source", "target" and "edges". Edges are links going between token-id in the source to token-id in the target, with tags describing the difference between one and another. Additionally, pseudonymization tags may be attached to the links.
   
   3.4 sw.txt - raw essay texts (i.e. containing no annotation)
   
   3.5 sw.xml - an xml version of the original essays following Korp format. Attributes and variables are described in the *Metadata* file below.
   
   3.6 sw_Ling_annotated - an xml version (Korp format) of the original essays with linguistic annotation using Sparv-pipeline.

4. TISUS-folder

   4.1 tisus_metadataDescription.pdf - a pdf version (as of August 2021) of the metadata-description available at the link https://spraakbanken.github.io/swell-release-v1/Metadata-TISUS. The information available at the link is continuously updated, which means it could be useful to check it for later updates.
   
   4.2 metadata_TISUS.xlsx - a spreadsheet containing all metadata ordered by essay-ID. Attributes and variables are described in the *Metadata* file below.
   
   4.3 tisus.json - all SpIn essays (105) in a json format (aka SVALA format), see Wirén et al. (2019) for the description. The json representation contains three objects: "source", "target" and "edges". Edges are links going between token-id in the source to token-id in the target, with tags describing the difference between one and another. Additionally, pseudonymization tags may be attached to the links.
   
   4.4 tisus.txt - raw essay texts (i.e. containing no annotation)
   
   4.5 tisus.xml - an xml version of the original essays following Korp format. Attributes and variables are described in the *Metadata* file below.
   
   4.6 sw_Ling_annotated - an xml version (Korp format) of the original essays with linguistic annotation using Sparv-pipeline.

***Note!*** that each format includes a so-called SVALA-link (or full-text link) for each essay. Using that link you can open an essay in a full-text version in a parallel representation (original, target, tags on the links between original and target tokens) using SVALA tool  (Wirén et al. 2019). In SVALA, you will be able to play with various annotation modes and tagsets. However, please be aware that the added annotations are not saved to any database.

* To use SVALA, please have a look at the video: [https://gubox.box.com/s/tp5gm8dua0avs7luqbgxwicws5dl0jh5](https://gubox.box.com/s/tp5gm8dua0avs7luqbgxwicws5dl0jh5)
* Currently, SVALA manual is available only in Swedish

## Metadata descriptions:
* SpIn (part of SweLL-pilot): [https://spraakbanken.github.io/swell-release-v1/Metadata-SpIn](https://spraakbanken.github.io/swell-release-v1/Metadata-SpIn)
* SW1203 (part of SweLL-pilot): [https://spraakbanken.github.io/swell-release-v1/Metadata-SW1203](https://spraakbanken.github.io/swell-release-v1/Metadata-SW1203)
* TISUS 2007 (part of SweLL-pilot): [https://spraakbanken.github.io/swell-release-v1/Metadata-TISUS](https://spraakbanken.github.io/swell-release-v1/Metadata-TISUS)

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
* ... Volodina et al. (2016) if you use this corpus

## References
* Elena Volodina, Ildikó Pilán, Ingegerd Enström, Lorena Llozhi, Peter Lundkvist, Gunlög Sundberg, Monica Sandell. 2016. SweLL on the rise: Swedish Learner Language corpus for European Reference Level studies. Proceedings of LREC 2016, Slovenia. [[http://arxiv.org/pdf/1604.06583v1.pdf](http://arxiv.org/pdf/1604.06583v1.pdf)]
* Wirén Mats, Arild Matsson, Dan Rosén, Elena Volodina. 2019. SVALA: Annotation of Second-Language Learner Text Based on Mostly Automatic Alignment of Parallel Corpora. CLARIN-2018 post-conference volume. LiUP Press. [[http://www.ep.liu.se/ecp/159/023/ecp18159023.pdf](http://www.ep.liu.se/ecp/159/023/ecp18159023.pdf)]


