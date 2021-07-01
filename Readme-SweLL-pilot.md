# SweLL-pilot collection

SweLL-pilot corpus is a corpus of essays written by adult learners of Swedish. It was collected during the period of 2007-2016, and contains 502 essays that have been anonymized and graded with CEFR labels. There are three subcorpora:
* SpIn - 256 essays collected from Language Introduction course (mid-term exams) for newly arrived refugees. Some of the students are recurrent. 
* Sw1203 - 141 essays collected from university students in exam setting, most of who wrote three essays each
* TISUS - 105 essays written as a part of a Test In Swedish for University Studies. All essays are on the same topic, "Stress"

More information about each subcorpus can be found in the metadata files, and a few more details in Volodina et al. (2016). ***Note***, however, that Volodina et al. (2016) cite a bit different number of essays. This is due to the fact that some of the essays have been transcribed and added to the collection at a later stage. 


### SweLL-pilot.zip contains

1. files for TISUS, SW1203 and SpIn in three formats: 
    * json (SVALA format), see Wirén et al (2019) for the description. The "source" and "target" versions; the "edges" may contain anonymization tags (depends on a subcorpus)
    * xml (Korp format), attributes and variables are described in the Metadata file(s) 
    * raw text
2. metadata in an excel file, ordered by essay-IDs; divided into subcorpora per spreadsheet
3. [the current readme file](https://spraakbanken.github.io/swell-release-v1/Readme-SweLL-pilot)

Note that no linguistic annotation is added to the essays. 
Each format includes a so-called SVALA-link (or full-text link) for each essay. Using that link you can open an essay in a full-text version in a parralel representation (original, target, tags on the links between original and target tokens) using SVALA tool. In SVALA, you will be able to play with various annotation modes and tagsets. However, please be aware that the added annotations are not saved to any database.

## Metadata descriptions:
* [SpIn (part of SweLL-pilot)](https://spraakbanken.github.io/swell-release-v1/Metadata-SpIn)
* [SW1203 (part of SweLL-pilot)](https://spraakbanken.github.io/swell-release-v1/Metadata-SW1203)
* [TISUS 2007 (part of SweLL-pilot)](https://spraakbanken.github.io/swell-release-v1/Metadata-TISUS)

## Reminder of the access agreement
* Access is individual, free of charge and is administered via an [application](https://sunet.artologik.net/gu/swell)
* GDPR restrictions: geographical principle & research-and-development context
* License: CLARIN - ID, -PRIV, -NORED, -BY ([explanations](https://www.kielipankki.fi/support/clarin-eula/#res)) 

# Always cite 
* ... Volodina et al. (2016) if you use this corpus

## References

* Elena Volodina, Ildikó Pilán, Ingegerd Enström, Lorena Llozhi, Peter Lundkvist, Gunlög Sundberg, Monica Sandell. 2016. SweLL on the rise: Swedish Learner Language corpus for European Reference Level studies. Proceedings of LREC 2016, Slovenia. [[pdf]](http://arxiv.org/pdf/1604.06583v1.pdf)
* Wirén Mats, Arild Matsson, Dan Rosén, Elena Volodina. 2019. SVALA: Annotation of Second-Language Learner Text Based on Mostly Automatic Alignment of Parallel Corpora. CLARIN-2018 post-conference volume. LiUP Press. [[pdf]](http://www.ep.liu.se/ecp/159/023/ecp18159023.pdf)


