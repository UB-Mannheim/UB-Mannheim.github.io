# Open Source Projects at UB Mannheim

## Optical Character Recognition (OCR)

1. **OCR-fileformat** validates and transforms various OCR file formats (hOCR, ALTO, PAGE, FineReader): [[code](https://github.com/UB-Mannheim/ocr-fileformat)], [[GUI](https://digi.bib.uni-mannheim.de/ocr-fileformat/)], [[MIT License](https://github.com/UB-Mannheim/ocr-fileformat/blob/master/LICENSE)].
2. **ocr-gt-tools** is an ergonomic line-by-line transcription of scanned text: [[code](https://github.com/UB-Mannheim/ocr-gt-tools)], [[GNU Affero General Public License v3.0](https://github.com/UB-Mannheim/ocr-gt-tools/blob/master/LICENSE)].
3. **Zotero OCR** adds the functionality to perform an OCR for the PDFs selected in Zotero: [[code](https://github.com/UB-Mannheim/zotero-ocr)], [[GNU Affero General Public License v3.0](https://github.com/UB-Mannheim/zotero-ocr/blob/master/LICENSE)].
4. **ocrd-pagetopdf** is an OCR-D wrapper for prima-pagetopdf. It transforms all PAGE-XML+IMG to PDF with text layer and (optionally) polygon outlines: [[code](https://github.com/UB-Mannheim/ocrd_pagetopdf)], [[Apache License 2.0](https://github.com/UB-Mannheim/ocrd_pagetopdf/blob/master/LICENSE)].
5. **TesseractXplore** is an easy-to-use graphical interface to tesseract with full control: [[code](https://github.com/JKamlah/tesseractXplore)], [[MIT License](https://github.com/JKamlah/tesseractXplore/blob/main/LICENSE)].
6. **PagePlus** is a command-line tool for processing and analyzing PAGE XML files: [[code](https://github.com/UB-Mannheim/PagePlus)], [[MIT License](https://github.com/UB-Mannheim/PagePlus/blob/main/LICENSE.txt)].
7. **Churro** is an OCR toolkit for historical document transcription (UB fork of [Stanford's Churro](https://github.com/stanford-oval/Churro)): [[code](https://github.com/UB-Mannheim/Churro)], [[Apache License 2.0](https://github.com/UB-Mannheim/Churro/blob/main/LICENSE)].
8. **blatt** is an NLP helper for OCR-ed pages in PAGE XML format: [[code](https://github.com/UB-Mannheim/blatt)], [[MIT License](https://github.com/UB-Mannheim/blatt/blob/main/LICENSE)].
9. **keyboardBuilder4eScriptorium** builds virtual keyboards for eScriptorium: [[code](https://github.com/UB-Mannheim/keyboardBuilder4eScriptorium)], [[MIT License](https://github.com/UB-Mannheim/keyboardBuilder4eScriptorium/blob/main/LICENSE)].
10. **ocr-models** is a registry of models for OCR engines (UB fork of [kba/ocr-models](https://github.com/kba/ocr-models)): [[code](https://github.com/UB-Mannheim/ocr-models)], [[MIT License](https://github.com/UB-Mannheim/ocr-models/blob/master/LICENSE)].
11. **Tesseract_Dokumentation** provides German documentation relating to the text recognition software Tesseract: [[code](https://github.com/UB-Mannheim/Tesseract_Dokumentation)].

Archived: **ocromore** (tool for processing, enhancing and evaluating multiple OCR outputs, [[code](https://github.com/UB-Mannheim/ocromore)]), **crass** (tool to crop and splice segments of scanned pages, [[code](https://github.com/UB-Mannheim/crass)]), **Mocrin** (coordinates multiple OCR engines into a uniform workflow and folder structure, [[code](https://github.com/UB-Mannheim/mocrin)]).

## Ground truth data for OCR

Transcriptions (mostly PAGE XML, often created with eScriptorium or Transkribus) for training and validating OCR recognition models.

1. **digi-gt** ground truth for the digitized historic collections of UB Mannheim: [[code](https://github.com/UB-Mannheim/digi-gt)], [[CC0 1.0 Universal License](https://github.com/UB-Mannheim/digi-gt/blob/main/LICENSE)].
2. **reichsanzeiger-gt** ground truth for the digital edition of the *Deutscher Reichsanzeiger und Preußischer Staatsanzeiger*: [[code](https://github.com/UB-Mannheim/reichsanzeiger-gt)], [[CC0 1.0 Universal License](https://github.com/UB-Mannheim/reichsanzeiger-gt/blob/main/LICENSE)].
3. **hkb-gt** ground truth for the digitised newspaper *Hakenkreuzbanner* (Mannheim region, 1931–1945): [[code](https://github.com/UB-Mannheim/hkb-gt)], [[CC0 1.0 Universal License](https://github.com/UB-Mannheim/hkb-gt/blob/main/LICENSE.md)].
4. **AustrianNewspapers** the NewsEye/READ OCR training dataset of the Austrian National Library (19th-c. Austrian newspapers; original dataset published under CC BY 4.0): [[code](https://github.com/UB-Mannheim/AustrianNewspapers)].
5. **digitue-gt** ground truth for digitized books and journals of the University Library of Tübingen: [[code](https://github.com/UB-Mannheim/digitue-gt)], [[CC0 1.0 Universal License](https://github.com/UB-Mannheim/digitue-gt/blob/main/LICENSE)].
6. **stabi-berlin-gt** ground truth for digitized publications of Staatsbibliothek zu Berlin: [[code](https://github.com/UB-Mannheim/stabi-berlin-gt)], [[CC0 1.0 Universal License](https://github.com/UB-Mannheim/stabi-berlin-gt/blob/main/LICENSE)].
7. **tudigi-gt** ground truth for digitized publications of ULB TU Darmstadt: [[code](https://github.com/UB-Mannheim/tudigi-gt)], [[CC0 1.0 Universal License](https://github.com/UB-Mannheim/tudigi-gt/blob/main/LICENSE)].
8. **MannheimerZeitungen** ground truth for historic newspapers, generated with GTMake: [[code](https://github.com/UB-Mannheim/MannheimerZeitungen)], [[CC0 1.0 Universal License](https://github.com/UB-Mannheim/MannheimerZeitungen/blob/main/LICENSE)].
9. **charlottenburger-amtsschrifttum** ground truth from the collection *Charlottenburger Amtsschrifttum* (1879–1919, Fraktur): [[code](https://github.com/UB-Mannheim/charlottenburger-amtsschrifttum)], [[CC0 1.0 Universal License](https://github.com/UB-Mannheim/charlottenburger-amtsschrifttum/blob/main/LICENSE)].
10. **NZZ-black-letter-ground-truth** ground truth for 167 front pages of the *Neue Zürcher Zeitung* (1780–1947). Fork of the original dataset published by [impresso](https://github.com/impresso/NZZ-black-letter-ground-truth): [[code](https://github.com/UB-Mannheim/NZZ-black-letter-ground-truth)], [[CC BY-NC 4.0 License](https://github.com/UB-Mannheim/NZZ-black-letter-ground-truth/blob/master/LICENSE.txt)].
11. **mkn-kurrent-gt** ground truth for Kurrent handwritten periodicals from the Moravian Knowledge Network. Fork of [bertsky/mkn-kurrent-gt](https://github.com/bertsky/mkn-kurrent-gt): [[code](https://github.com/UB-Mannheim/mkn-kurrent-gt)], [[CC BY-SA 4.0 License](https://github.com/UB-Mannheim/mkn-kurrent-gt/blob/main/LICENSE.md)].
12. **dach-gt** ground truth and full text for selected prints of German archives and libraries: [[code](https://github.com/UB-Mannheim/dach-gt)], [[CC0 1.0 Universal License](https://github.com/UB-Mannheim/dach-gt/blob/main/LICENSE)].
13. **gt-fraktur** ground truth for Fraktur/Gothic prints of the 19th century. Fork of the original data by UB Tübingen ([ubtue/gt-fraktur](https://github.com/ubtue/gt-fraktur), CC0): [[code](https://github.com/UB-Mannheim/gt-fraktur)].
14. **Weisthuemer** transcriptions of Jacob Grimm's *Weisthümer* (Middle High German), for training or validating OCR models: [[code](https://github.com/UB-Mannheim/Weisthuemer)], [[CC0 1.0 Universal License](https://github.com/UB-Mannheim/Weisthuemer/blob/master/LICENSE)].
15. **Fibeln** transcriptions of 19th-century primers (Fibeln), for training or validating OCR models: [[code](https://github.com/UB-Mannheim/Fibeln)], [[CC0 1.0 Universal License](https://github.com/UB-Mannheim/Fibeln/blob/master/LICENSE)].

Related tools: **Reichsanzeiger** (software and data for the newspaper's digital edition, [[code](https://github.com/UB-Mannheim/Reichsanzeiger)]), **ra-scripts** (scripts used during the Reichsanzeiger project, [[code](https://github.com/UB-Mannheim/ra-scripts)]), **reichsanzeiger-nlp** (NER/NEL corpus for the *Deutscher Reichsanzeiger*, [[code](https://github.com/UB-Mannheim/reichsanzeiger-nlp)], [[CC0 1.0 Universal License](https://github.com/UB-Mannheim/reichsanzeiger-nlp/blob/main/LICENSE))) and **VisualAnzeights** (analysis of Reichsanzeiger advertisements, [[code](https://github.com/UB-Mannheim/VisualAnzeights)]).

## OCR projects

Software and data from DFG and other digitization projects:

1. **BeTrial** is a Bernoulli trial generator for OCR result validation, part of the *Aktienführer-Datenarchiv* DFG project: [[code](https://github.com/UB-Mannheim/BeTrial)], [[Apache License 2.0](https://github.com/UB-Mannheim/BeTrial/blob/master/LICENSE)].
2. **GTCheck** validates modifications of OCR ground truth in a git repository, showing original text, modified version and image: [[code](https://github.com/UB-Mannheim/GTCheck)], [[Apache License 2.0](https://github.com/UB-Mannheim/GTCheck/blob/master/LICENSE)].
3. **DCC** is the software and data for the digitalization, OCR and structuring of the books *The Descendants of the Colonial Clergy*: [[code](https://github.com/UB-Mannheim/DCC)].

## Data management & bibliographic tools

1. **Zotkat** is an extension of Zotero for cataloguing in a broad sense and contains also some experimental approaches: [[Zotkat](https://github.com/UB-Mannheim/zotkat)], [[GNU Affero General Public License v3.0](https://github.com/UB-Mannheim/zotkat/blob/master/LICENSE)].
2. **malibu** (**Mannheim library utilities**) is a collection of lightweight web-based tools to work with bibliographic metadata from various sources on the web, aimed at supporting the workflows of subject librarians and acquisitions librarians: [[code](https://github.com/UB-Mannheim/malibu)], [[GUI](https://data.bib.uni-mannheim.de/malibu/)].
3. **uma_publist** a TYPO3 extension to include publication lists from an EPrints repository in TYPO3 websites where the lists are generated and synced automatically: [[code](https://github.com/UB-Mannheim/uma_publist)], [[GNU General Public License v2.0](https://github.com/UB-Mannheim/uma_publist/blob/master/LICENSE)].
4. **MArs** is a web application for seat booking in Mannheim University Library: [[code](https://github.com/UB-Mannheim/MArs)], [[GNU Affero General Public License v3.0](https://github.com/UB-Mannheim/MArs/blob/main/LICENSE)].
5. **ape** (ALMA Print Extension) prints custom letters and notifications from Alma: [[code](https://github.com/UB-Mannheim/ape)], [[GNU General Public License v3.0](https://github.com/UB-Mannheim/ape/blob/main/LICENSE.md)].
6. **ucompanies** downloads PDF forms from ucompanies, extracts the texts (including check marks) and structures them into CSV and DTA files: [[code](https://github.com/UB-Mannheim/ucompanies)].
7. **validate-mets** validates METS files: [[code](https://github.com/UB-Mannheim/validate-mets)], [[Apache License 2.0](https://github.com/UB-Mannheim/validate-mets/blob/main/LICENSE)].

## Digital libraries

1. **Kitodo.Presentation** is a feature-rich TYPO3 extension for building a METS- or IIIF-based digital library. UB Mannheim maintains a fork with development work (a no-Docker demo site, viewer theming and further features); the fork's documentation, which also covers that non-upstream work, is published separately: [[upstream](https://github.com/kitodo/kitodo-presentation)], [[code](https://github.com/UB-Mannheim/kitodo-presentation)], [[docs](https://ub-mannheim.github.io/kitodo-presentation/)], [[live demo](https://digi.bib.uni-mannheim.de/demo/)], [[GNU General Public License v3.0](https://github.com/UB-Mannheim/kitodo-presentation/blob/main/LICENSE.txt)].
2. **omeka-matomo** is a plugin that integrates [Matomo Analytics](https://matomo.org/) into Omeka Classic installations: [[code](https://github.com/UB-Mannheim/omeka-matomo)], [[GNU General Public License v3.0](https://github.com/UB-Mannheim/omeka-matomo/blob/main/LICENSE)].

## AI applications

1. **UBi** is an agentic AI-powered assistant (chatbot) for UB Mannheim: [[code](https://github.com/UB-Mannheim/UBi)], [[MIT License](https://github.com/UB-Mannheim/UBi/blob/main/LICENSE.md)].
2. **FAIRplexica** is an open source AI assistant for research data management (RDM), a fork of [Vane](https://github.com/ItzCrazyKns/Vane) (formerly Perplexica): [[code](https://github.com/UB-Mannheim/FAIRplexica)], [[MIT License](https://github.com/UB-Mannheim/FAIRplexica/blob/master/LICENSE)].
3. **FAIR-GPT** is a documentation for FAIR GPT, a virtual RDM consultant: [[code](https://github.com/UB-Mannheim/FAIR-GPT)], [[CC0 1.0 Universal License](https://github.com/UB-Mannheim/FAIR-GPT/blob/main/LICENSE)].
4. **maidisco** is the Mannheim Intelligent Discovery System, an experimental web application that adds AI assisted search to discovery systems like Primo or VuFind: [[code](https://github.com/UB-Mannheim/maidisco)], [[GNU Affero General Public License v3.0](https://github.com/UB-Mannheim/maidisco/blob/main/LICENSE)].

## Research data management

1. **data-journals-dashboard** is a web dashboard for searching and filtering a community-curated list of data journals: [[code](https://github.com/UB-Mannheim/data-journals-dashboard)].
2. **awesome-research-software** is a curated list of production-ready open-source research software: [[code](https://github.com/UB-Mannheim/awesome-research-software)], [[CC0 1.0 Universal License](https://github.com/UB-Mannheim/awesome-research-software/blob/main/LICENSE)].
3. **madabi** (Mannheim Data Bibliography) is a registry of metadata of all data created or collected by the university: [[code](https://github.com/UB-Mannheim/madabi)], [[MIT License](https://github.com/UB-Mannheim/madabi/blob/main/LICENSE)].
4. **madata** is a tool for syncing the dataset metadata between MADATA and Wikidata: [[code](https://github.com/UB-Mannheim/madata)], [[MIT License](https://github.com/UB-Mannheim/madata/blob/main/LICENSE)].
5. **theme-madataplan** is an RDMO theme for [madataplan](https://fdz.bib.uni-mannheim.de/madataplan): [[code](https://github.com/UB-Mannheim/theme-madataplan)].
6. **awesome-RDM** is a curated list of awesome RDM resources for researchers and organisations: [[code](https://github.com/UB-Mannheim/awesome-RDM)], [[CC BY 4.0 License](https://github.com/UB-Mannheim/awesome-RDM/blob/main/LICENSE)].

## Knowledge graphs & Natural Language Processing (NLP)

1. **bbw** is an automatic semantic annotator for tabular data using a Wikibase instance and metasearch in SearX: [[code](https://github.com/UB-Mannheim/bbw)], [[GUI](https://mybinder.org/v2/gh/UB-Mannheim/bbw/main?urlpath=proxy/8501/)], [[tutorial](https://mybinder.org/v2/gh/UB-Mannheim/bbw/main?filepath=bbw.ipynb)], [[MIT License](https://github.com/UB-Mannheim/bbw/blob/main/LICENSE)].
2. **spacyopentapioca** is a spaCy wrapper of OpenTapioca for named entity linking on Wikidata: [[code](https://github.com/UB-Mannheim/spacyopentapioca)], [[MIT License](https://github.com/UB-Mannheim/spacyopentapioca/blob/main/LICENSE)].
3. **kg-enricher** is a library for enriching strings, entities and knowledge graphs using Wikibase knowledge: [[code](https://github.com/UB-Mannheim/kg-enricher)], [[MIT License](https://github.com/UB-Mannheim/kg-enricher/blob/main/LICENSE)].
4. **MBI-KG** is a knowledge graph of structured and linked economic research data extracted from *Monatsschrift für Wirtschaft und Konjunktur*: [[code](https://github.com/UB-Mannheim/MBI-KG)], [[MIT License](https://github.com/UB-Mannheim/MBI-KG/blob/main/LICENSE.md)].
5. **Amtsgericht-KG** analyzes and visualizes a knowledge graph of company registrations across German district courts: [[code](https://github.com/UB-Mannheim/Amtsgericht-KG)].
6. **check-fake-references** is a script to check references for plausibility: [[code](https://github.com/UB-Mannheim/check-fake-references)], [[MIT License](https://github.com/UB-Mannheim/check-fake-references/blob/main/LICENSE)].
7. **cas2iob** converts UIMA CAS XMI files exported from INCEpTION into IOB TSV files, handling nested NER tags, NEL tags and components: [[code](https://github.com/UB-Mannheim/cas2iob)], [[MIT License](https://github.com/UB-Mannheim/cas2iob/blob/main/LICENSE)].

Archived: **RaiseWikibase** (tool for fast data import and knowledge graph construction with Wikibase, [[code](https://github.com/UB-Mannheim/RaiseWikibase)], [[docs](https://ub-mannheim.github.io/RaiseWikibase/)]).

## Screen sharing & team work

1. **PalMA** enables people to share several contents on one monitor: [[code](https://github.com/UB-Mannheim/PalMA)], [[GNU General Public License](https://github.com/UB-Mannheim/PalMA/blob/master/LICENSE)].

## Third-party forks

Forks of third-party projects used by UB Mannheim:

1. **eScriptorium** is an open source transcription platform developed as part of the [Scripta](https://www.psl.eu/en/scripta), [RESILIENCE](https://www.resilience-ri.eu) and [Biblissima+](https://projet.biblissima.fr/) projects. The UB Mannheim repository is a fork of [scripta/eScriptorium](https://gitlab.com/scripta/escriptorium) with updates from UB Mannheim: [[code](https://github.com/UB-Mannheim/eScriptorium)], [[German documentation](https://ub-mannheim.github.io/eScriptorium_Dokumentation/)], [[MIT License](https://github.com/UB-Mannheim/eScriptorium/blob/develop/LICENSE)].
2. **Kitodo** — digitization workflow software: **kitodo-presentation** ([upstream](https://github.com/kitodo/kitodo-presentation), [[code](https://github.com/UB-Mannheim/kitodo-presentation)], [[docs](https://ub-mannheim.github.io/kitodo-presentation/)], [[GNU General Public License v3.0](https://github.com/UB-Mannheim/kitodo-presentation/blob/main/LICENSE.txt)]), **kitodo-production** ([upstream](https://github.com/kitodo/kitodo-production), [[code](https://github.com/UB-Mannheim/kitodo-production)], [[docs](https://ub-mannheim.github.io/kitodo-production/)], [[GNU General Public License v3.0](https://github.com/UB-Mannheim/kitodo-production/blob/main/LICENSE)]), **kitodo-workflow-editor** ([upstream](https://github.com/Erikmitk/kitodo-workflow-editor), [[code](https://github.com/UB-Mannheim/kitodo-workflow-editor)], [[Camunda License](https://github.com/UB-Mannheim/kitodo-workflow-editor/blob/master/Camunda-License.txt)]), plus the UB's own docker configurations **kitodo-presentation-docker** ([[code](https://github.com/UB-Mannheim/kitodo-presentation-docker)], [[GNU General Public License v3.0](https://github.com/UB-Mannheim/kitodo-presentation-docker/blob/main/LICENSE.txt)]) and **kitodo-production-docker** ([[code](https://github.com/UB-Mannheim/kitodo-production-docker)]), and **slub_digitalcollections** (Kitodo.Presentation-based templates for SLUB digital collections, [[code](https://github.com/UB-Mannheim/slub_digitalcollections)]).
3. **Churro** (UB fork of Stanford's Churro, [[code](https://github.com/UB-Mannheim/Churro)]) — see also the OCR section.
4. **DataCiteDoi** (UB fork of [eprintsug/DataCiteDoi](https://github.com/eprintsug/DataCiteDoi), DOI registration via DataCite, [[code](https://github.com/UB-Mannheim/DataCiteDoi)], [[GNU General Public License](https://github.com/UB-Mannheim/DataCiteDoi/blob/main/LICENSE)]).
5. **FAIR-farfalle** and **FAIR-sensei** (Perplexity analogues for RDM based on [farfalle](https://github.com/mattjohnsonpint/farfalle) and [sensei](https://github.com/Brainland/sensei), [[FAIR-farfalle](https://github.com/UB-Mannheim/FAIR-farfalle)], [[FAIR-sensei](https://github.com/UB-Mannheim/FAIR-sensei)], both Apache License 2.0).
6. **ocrd_pagetopdf** (UB fork of [OCR-D/ocrd-pagetopdf](https://github.com/OCR-D/ocrd-pagetopdf), [[code](https://github.com/UB-Mannheim/ocrd_pagetopdf)]) — see also the OCR section.
7. **theme-maobjects** and **theme-maobjects-nikephoros** (customizable Omeka Classic themes for MAObjects, [[theme-maobjects](https://github.com/UB-Mannheim/theme-maobjects)], [[theme-maobjects-nikephoros](https://github.com/UB-Mannheim/theme-maobjects-nikephoros)]).
8. **rdmo-docs** (English documentation for [rdmo](https://github.com/rdmo/rdmo), [[code](https://github.com/UB-Mannheim/rdmo-docs)]).
9. **handbuch-it-in-bibliotheken** (working version of the *Handbuch IT in Bibliotheken*, [[code](https://github.com/UB-Mannheim/handbuch-it-in-bibliotheken)]).
10. **eprints-create_sitemap** (optional script for EPrints, [[code](https://github.com/UB-Mannheim/eprints-create_sitemap)], [[GNU General Public License](https://github.com/UB-Mannheim/eprints-create_sitemap/blob/master/LICENSE)]).
11. **ocr-model-repo-template** (UB fork of [OCR-D/gt-repo-template](https://github.com/OCR-D/gt-repo-template), [[code](https://github.com/UB-Mannheim/ocr-model-repo-template)]) and **ocr-model-metadata** (UB fork of [OCR-D/gt-metadata](https://github.com/OCR-D/gt-metadata), [[code](https://github.com/UB-Mannheim/ocr-model-metadata)]).
