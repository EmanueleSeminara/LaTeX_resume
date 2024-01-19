# [![emanueleseminara.it](https://github.com/EmanueleSeminara/images/blob/main/logo_e_20x20.png?raw=true)](https://emanueleseminara.it/) AltaCV - CV in LaTeX a Singola Pagina [![emanueleseminara.it](https://github.com/EmanueleSeminara/images/blob/main/logo_e_20x20.png?raw=true)](https://emanueleseminara.it/)

v1.3 (20 Gennaio 2024) di Emanuele Seminara

[Per la versione inglese Clicca Qui](https://github.com/EmanueleSeminara/LaTeX_resume/tree/ENG)
## Introduzione

Questo repository è pensato per te, amante di LaTeX, per darti un'idea interessante per un curriculum vitae.
Puoi utilizzare questo modello per creare in pochi minuti il tuo curriculum personale.

Di seguito troverai una selezione di passi da seguire per personalizzare il tuo curriculum, divertiti.
Per qualsiasi domanda puoi scrivermi a [seminara.emanuele96@gmail.com](mailto:seminara.emanuele96@gmail.com).

Puoi trovarmi anche su:

[![LinkedIn](https://github.com/EmanueleSeminara/images/blob/main/icon_square_linkedin_50.png?raw=true)](https://www.linkedin.com/in/emanuele-seminara/)
[![Instagram](https://github.com/EmanueleSeminara/images/blob/main/icon_square_instagram_50.png?raw=true)](https://www.instagram.com/emanuele_seminara/)
[![emanueleseminara.it](https://github.com/EmanueleSeminara/images/blob/main/icon_square_emanueleseminara_50.png?raw=true)](https://emanueleseminara.it/)
[![tech-fusion.it](https://github.com/EmanueleSeminara/images/blob/main/icon_square_tech-fusion_50.png?raw=true)](https://tech-fusion.it/)

## Aspetto del Curriculum
![Screenshot_CV](./Emanuele_Seminara_CV_ITA.jpg)

## Editor
Nel caso tu non conosca LaTeX, non preoccuparti, puoi utilizzare [Overleaf](https://overleaf.com), un editor online gratuito e fantastico,
basta creare un account, avviare un nuovo progetto e caricare i file di questo repository.

Per avere i file sul tuo PC, clona semplicemente questo repository:

1) Seleziona la posizione in cui desideri memorizzare il file nel tuo terminale

   ```bash
   cd Progetti/curriculum
   ```

2) Clona il repository

   ```bash
   git clone https://github.com/EmanueleSeminara/LaTeX_resume.git
   ```

Dopo aver caricato i file, dovrai solo modificare il contenuto dei file per scrivere ciò che desideri nel tuo curriculum.
È davvero intuitivo, nel caso tu abbia bisogno di ulteriori informazioni su cosa modificare, puoi consultare le sezioni seguenti.

## Requisiti e Compilazione

* Alla riga 76 di main.tex puoi inserire le tue informazioni personali.
* page1sidebar.tex contiene il codice per la parte destra del curriculum.
* Ricorda di sostituire l'immagine con la tua foto e utilizza un formato png.
* Se desideri cambiare i colori, vai alla riga 48 di main.tex.
* AltaCV utilizza [`fontawesome`](http://www.ctan.org/pkg/fontawesome) e [`academicons`](http://www.ctan.org/pkg/academicons); sono inclusi sia in TeX Live 2016 che in MikTeX 2.9.
* Il caricamento di `academicons` è facoltativo: attivalo aggiungendo l'opzione `academicons` a `\documentclass`.
* Ora può essere compilato con pdflatex, XeLaTeX e LuaLaTeX!
* Tuttavia, se stai utilizzando `academicons`, _devi_ usare XeLaTeX o LuaLaTeX. Se il documento viene compilato ma le icone non appaiono nel PDF finale, prova a compilare con LuaLaTeX invece.
* Negli esempi qui mostrati viene utilizzato il carattere [Lato](http://www.latofonts.com/lato-free-fonts/).

## Donazioni
Il codice è qui per essere letto, modificato, adattato, riutilizzato, gratuitamente, fai quello che vuoi!
Tuttavia, se desideri offrirmi un caffè o una birra, allora cin cin! =D

[![button Buy me a coffee](https://github.com/EmanueleSeminara/images/blob/main/bmc-button_small2.png?raw=true)](https://www.buymeacoffee.com/emanueleseminara)