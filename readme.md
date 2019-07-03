# Medieval Vernacular Corpora and Digital Textual Analysis

This repository contains some materials for the workshop held at the IMC in Leeds 2019 by Gustavo Fernández Riva and David Joseph Wrisley. Below is a brief description of the content of the repository and links and instructions on how to access the software that will be used during the session.

## Contents

- **matieres**: Corpus of the so-called *matières* of France (fra), Rome (rom) and Bretagne (bre). They texts are lemmatised and scrambled, but can be used for bag of words models.

- **OpenMedFr**: A copy of the Open Medieval French corpus.

- **villehardouin**: [French text](https://fr.wikisource.org/wiki/M%C3%A9moires_de_Geoffroi_de_Villehardouin) of the Conquest of Constantinople by Geoffroy de Villehardouin from wikisource and [English translation](https://sourcebooks.fordham.edu/basis/villehardouin.asp) from the Medieval Sourcebook at Fordham University.

- **stopwords.txt**: Stopwords list for Old French based on the Open Medieval French corpus.


## Set-Up Instructions

This are a simple list of instructions to access/download the tools we will use during the workshop at the IMC Leeds on 3 July 2019. We will help with download and installation during the session if needed, but this guide should make it easier for you to find your way around. If you have this document before the session, you could try to get ahead and already install or explore some of this resources.

### Open Medieval French
This is the GitHub page where our projects shares materials: https://github.com/OpenMedFr
The most important repository is “texts”, where the transcribed sources can be found:
https://github.com/OpenMedFr/texts

### Transkribus
Transkribus is a text recognition software powered with deep learning. It is able to train models that identify handwritten or printed characters on images . We'll use it mainly during the first session of the workshop. You will first need to register and download the program at: https://transkribus.eu 
Detailed instructions on installation and how the program works here:
https://transkribus.eu/wiki/images/7/77/How_to_use_TRANSKRIBUS_-_10_steps.pdf

### Voyant Tools
Voyant is a suite of tools for quantitative textual analysis. Required for the second session. Online access at: https://voyant-tools.org/
It's possible to download a local version to run from your computer without relying on the internet (recommended): http://docs.voyant-tools.org/resources/run-your-own/voyant-server/#download

### Recogito
Recogito is an online interface for (mainly geographical) annotation of texts. We will use it during the second session. Can be accessed at: https://recogito.pelagios.org/
It's necessary to create an account to use it, which can be done from the main page. In order to collaboratively work on the same document, it has to be shared, which can be done using the collaborator's user name.

### R + Stylo
Stylo is a library written in the programming language R designed to perform different tasks in the field of stylometric analysis. It's fairly complex and we might not be able to actively use it during the workshop, but just in case:
To download R go to: https://www.r-project.org/ and select the download option. Then choose any of the mirrors offered. As we are in the UK you might want to go for one of those. 
Then you need to install Stylo. Open R and type install.packages("stylo"). You will probably need to install some other auxiliary R libraries, so the best way would be to just follow the instructions here: https://sites.google.com/site/computationalstylistics/stylo
If you then want to try a richer environment to work with Stylo, you can download RStudio at: https://www.rstudio.com/products/rstudio/download/