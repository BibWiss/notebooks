# notebooks
A collection of Jupyter Notebooks.

## [ner4xml](ner4xml/ner4xml.ipynb)
Dieses Notebook ist im Rahmen der Fortbildungsreihe "Vom Dokument zur Edition" und konkret des Workshops [Editionsdaten semantisch anreichern – XML-Parsing und Named Entity Recognition (NER) mit Python](https://www.fu-berlin.de/kalender/2026/01/20260127-editionsdaten-semantisch-anreichern.html) im WiSe 2025/26 an der FU Berlin entstanden. Das Notebook thematisiert, wie XML-Dateien mit Python eingelesen sowie der enthaltene Text extrahiert, weiterverarbeitet und ins ursprüngliche XML zurückgeführt werden kann.

### Inhalte 
* XML-Dateien mit [ElementTree](https://docs.python.org/3/library/xml.etree.elementtree.html) einlesen, aktualisieren und exportieren
* [pandas](https://pandas.pydata.org/) DataFrames erstellen und verwenden
* [spaCy](https://spacy.io/) NER-Modell laden sowie auf XML-Textknoten und plaintext anwenden
* Part-of-Speech-Tagging und Normalisierung mit spaCy
* Sentiment-, Kollokations- und KWIC-Analysen mit [NLTK](https://www.nltk.org/)

### Beitragende und ihre Rollen anhand der [Contributor Role Taxonomy (CRediT) taxonomy](https://doi.org/10.1002/leap.1210)
* Sophie Schneider ([@BibWiss](https://github.com/BibWiss)): Conceptualization, Software/Writing - Original Draft (Teil 1 & 2), Writing - Review & Editing (Teil 3)
* Catherine Anne Seveke ([@cati-gitling](https://github.com/cati-gitling)): Conceptualization, Software/Writing - Original Draft (Teil 3)

## [nlpbasics](nlpbasics/nlpbasics.ipynb)
Dieses Notebook ist im Rahmen der Fortbildungsreihe "Panorama Text: Maschinelle Erfassung, Verarbeitung und Kontextualisierung von geschriebener Sprache für die Geisteswissenschaften" und konkret des Workshops [Einführung in die Grundlagen der natürlichen Sprachverarbeitung mit Python](https://www.it.fu-berlin.de/unsere-services/kompetenzentwicklung/fortbildungen/workshops/E-Research/2026-04-20-Python.html) im Sommersemester 2026 an der FU Berlin entstanden.

### Inhalte
* Daten einlesen, transformieren und exportieren
* Data Cleaning (Noise & Stopword Removal, Stemming & Lemmatization, Segmentation - Tokenization, Sentence Splitting)
* Feature Extraction (One-hot-Encoding, Bag-of-Words, TF-IDF)
* Semantic Analysis (Named Entity Recognition, Entity Linking, Sentiment Analysis)

### Tools
* Python 3.14.3
* conda/pip
* Jupyter Notebook
* Python standard library: re, collections, string, random
* NLP: spacy, nltk
* Data Analysis and Transformation, ML: pandas, numpy, sklearn
* Visualization: plotly, wordcloud, matplotlib

### Beitragende und ihre Rollen anhand der Contributor Role Taxonomy (CRediT) taxonomy:
* Sophie Schneider ([@BibWiss](https://github.com/BibWiss)): Conceptualization, Software, Writing - Original Draft
