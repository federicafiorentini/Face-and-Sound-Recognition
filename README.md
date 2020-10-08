# Face-and-Sound-Recognition
A computer vision project developed in Python

![Cattura](https://user-images.githubusercontent.com/49710127/95504244-cd667180-09ac-11eb-8cb6-aab43bcd75ee.PNG)

Il progetto è sviluppato in python e utilizza algoritmi di Machine Learning per riconoscere i volti e gli audio. 
In questo progetto sono stati affrontati tre differenti task: 

- Processing di segnali monodimensionali (Audio signal)
  Relativi a questo task, sono disponibili i seguenti codici: 
  - '1_Audio_capturing.ipynb': acquisizione automatica di segnali audio tramite microfono del pc.
  - '2_Audio_augmenter.ipynb': augmentation (crop, noise, speed, tract) di segnali audio
  - '3.1_Audio_model_Monocanale.ipynb': feature extraction + modelli di classificazione (NNet e SVM con HPO-GridSearch)
  - '3.2_Audio_model_Bicanale.ipynb': estrazione dello spetrogramma + modello di classificazione (NNet)

- Processing di segnali bidimensionali (Photo signal)
  Relativi a questo task, sono disponibili i seguenti codici: 
  - '1_capturing_images.ipynb': acquisizione automatica di foto tramite webcam.
  - '2_Face_Augmentation_Recognition.ipynb': augmentation delle immagini (brightness, flip) e face detection.
  - '3_Face_classification.ipynb': feature extraction (VGGface net) + face classification (SVM con HPO-GridSearch)
  
- Image retrieval
  di cui è disponibile: 
  - '1_Retrieval': face detection + feature extraction (mobilenet) + costruzione dell'albero di ricerca.
  
Inoltre, è disponibile il codice per effettuare una demo-live.

Le slide del progetto sono disponibili al link: https://prezi.com/view/lyO6ZLI6zPc6pHvU10wN/
