# siamosommelier

Il valore di una bottiglia di vino di annata e' un investimento difficile da decidere e la qualita' del vino e' qualcosa di misterioso affidato alla decisione dei Sommelier.

Nel 1990 un professore di economia si improvvisa Sommelier: 
guardando i dati delle aste del vino Bordeaux e i parametri ambientali legati alla vendemmia e alla fase di maturazione dei vigneti, il prof. Ashenfelter, dell'universita' di Princeton,  mette a punto un modello predittivo in grado di predire la qualita' del vino e il valore che potra’ acquistare con l'invecchiamento. 
Questo il link alla pubblicazione originale:

http://media.terry.uga.edu/documents/economics/ashenfelter_predicting_quality.pdf

In questo laboratorio proviamo a costruire questo modello. 
Utilizzeremo tecniche di Machine Learning che, esaminando i dati delle aste passate, imparano ad associare il prezzo di vendita del vino, preso come valutazione di qualita’, ai parametri meteo che hanno caratterizzato la maturazione e vendemmia del vino stesso.  

Per mettere a punto il modello useremo due strade:  

1) scriveremo un Jupyter Notebook in linguaggio R. Il codice avra’ il compito di leggere il dataset delle aste passate, capire quali sono I parametri rilevanti per il modello e costruira’ un modello di regressione lineare che collega andamento prezzi con anni di invecchiamento e dati meteo relative alla specifica bottiglia di vino.

2) useremo il servizio di Modeler Flows e Watson Machine Learning. Costruiremo Un Modeler Flow che prende il dataset di input, specificheremo quali sono le variabili/Indipendente e faremo il training di un modello di regressione lineare.

Le istruzioni per il laboratorio sono contenute in due file:

la prima parte e' contenuta in handsonthink_part1.pdf 
qui trovi le istruzioni per creare utenza in IBM Cloud, per fare il provisioning dei servizi che ti servono per eseguire il Jupyter Notebook, 
per fare download del Notebook ed eseguirlo

la seconda parte e' contenuta in handsonthink_part2.pdf
qui trovi le istruzioni per lavorare con il Modeler Flow e l'interfaccia di programmazione grafica
