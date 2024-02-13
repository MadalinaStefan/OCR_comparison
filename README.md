# **OCR_comparison**

## **Il seguente archivio contiene tutti i materiali necessari per la riproduzione dello studio che ho condotto all’interno del mio elaborato finale presso l’Università degli Studi di Verona, dal titolo “I sistemi di riconoscimento ottico dei caratteri: confronto tra Keras Ocr, Tesseract e Easy Ocr”.**

Il progetto si propone il confronto di tre diversi programmi OCR di tipo general purpose: Keras Ocr, Tesseract e Easy Ocr. Viene fornito un dataset di venti immagini, divise per classi di appartenenza. Le classi prese in considerazione sono: testo strutturato, testo non strutturato, targhe automobilistiche e scrittura a mano. Le immagini vengono fornite in dimensione high quality, successivamente saranno ridimensionate del 25% con l'obiettivo di analizzare il funzionamento dei programmi su due risoluzioni d'immagine. Durante la fase di elaborazione le immagini vengono offuscate, ruotate di 90° e convertite in negativo, per il confronto degli output forniti dai programmi nelle diverse situazioni in cui possono essere riscontarte le immagini.
Le metriche di valutazione a cui si fa riferimento sono le metriche CER e WER che determinano l'accuratezza dei sistemi nel riconoscimento dei caratteri all'interno delle immagini.

### **Materiali presenti nella cartella “Data”:**
##### *• dataset_immagini:* 
contiene il dataset utilizzato per l’esperimento. Contiene al suo interno le quattro categorie di immagini analizzate: car_plates, structured texts, unstructured texts e handwritten texts. 
##### *•	golden_text:*
contiene al suo interno i file .csv di ogni categoria di immagine contenente il testo corretto presente nelle immagini, che verrà confrontato con i caratteri predetti dai programmi OCR

I notebook: …… contengono 


