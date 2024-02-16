# **OCR_comparison**

## **Il seguente archivio contiene tutti i materiali necessari per la riproduzione dello studio che ho condotto all’interno del mio elaborato finale presso l’Università degli Studi di Verona, dal titolo “I sistemi di riconoscimento ottico dei caratteri: confronto tra Keras Ocr, Tesseract e Easy Ocr”.**

Il progetto si propone il confronto di tre diversi programmi OCR di tipo general purpose: Keras Ocr, Tesseract e Easy Ocr. Viene fornito un dataset di venti immagini, divise per classi di appartenenza. Le classi prese in considerazione sono: testo strutturato, testo non strutturato, targhe automobilistiche e scrittura a mano. Le immagini vengono prese in analisi in due dimensioni differenti (high quality e low quality) e dal punto di vista di tre trasformazioni (offuscamento, rotazione di 90º e conversione in scala di grigi). In una prima fase, il ridimensionamento e la pre-elaborazione delle immagini nelle diverse trasformazioni, è stata effettuata all'interno del codice sorgente attraverso la libreria Keras. Questa operazione non ha prodotto i risultati sperati e i dati raccolti sono stati considerati inattendibili. Per questa ragione le immagini del dataset sono state pre-elaborate esternamente attraverso il programma Gimp e sono state create le cartelle corrispondenti, per ogni qualità e per ogni trasformazione.

Le metriche di valutazione a cui si fa riferimento sono le metriche CER e WER che determinano l'accuratezza dei sistemi nel riconoscimento dei caratteri all'interno delle immagini.

### **Materiali:**
##### *• dataset_immagini_high:* 
Contiene tutte le cartelle delle trasformazioni nella qualità high. Ogni cartella, al suo interno, contiene le quattro classi di immagini.

##### *• dataset_immagini_low:* 
Contiene tutte le cartelle delle trasformazioni nella qualità low. Ogni cartella al suo interno contiene le quattro classi di immagini.

##### *•	golden_text:*
Contiene al suo interno i file .csv di ogni categoria di immagine contenente il testo corretto presente nelle immagini, che verrà confrontato con i caratteri predetti dai programmi OCR.

### **I notebook KerasOcr.ipynb, Tesseract.ipynb, EasyOcr.ipynb:**
Contengono i codici sorgente dei programmi utilizzati per condurre lo studio. 

### **Riferimenti:**
Keras Ocr 
• https://keras-ocr.readthedocs.io/en/latest/ 
• https://github.com/faustomorales/keras-ocr
• https://github.com/Devashree21/Extract-Text-From-Images-Quickly-Using-Keras-OCR-Pipeline/blob/main/Keras_ocr.ipynb
• https://colab.research.google.com/github/bhattbhavesh91/keras-ocr-demo/blob/main/keras-ocr-notebook.ipynb#scrollTo=29bAoTk7c2Z-

Tesseract
• https://tesseract-ocr.github.io/tessdoc/#source-code
• https://pypi.org/project/pytesseract/
• https://nanonets.com/blog/ocr-with-tesseract/

Easy Ocr
• https://github.com/JaidedAI/EasyOCR
• https://documentation.euresys.com/Products/Open_eVision/Open_eVision_2_5/en-us/Content/03_Using_Open_eVision/D1_EasyOCR_-_Reading_Texts/EasyOCR_-_Reading_Texts.htm



