# Music_Genre_Classifier
A group project for my 3rd year 'Intro to AI' university unit. I built a music genre classifier using Keras, trained on the [GTZAN](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification) dataset.

The group [report](Music_Genre_Classifier_Report.pdf) is included discussing the literature, methods, experimentation, and analysis of our results.


All the code in this repository is my part of the project:
- [data_spectrograms_mfccs.ipynb](data_spectrograms_mfccs.ipynb)
  - Data experimentation and pre-processing
  - Plotting waveforms
  - Creating my own spectrograms and mel-spectrograms
  - Extracting MFCCs
  - One way of saving the extracted data

- [inital_experimentation.ipynb](inital_experimentation.ipynb)
  - Pre-processes data
  - Other ways of saving the extracted data
  - Training and investigating accuracy of ANN and CNN models
  - Improving the models
  
- [melspect_models.ipynb](melspect_models.ipynb)
  - Saving the mel-spectrogram data
  - Training and analysisng different neural networks
  - Confusion matrices to analyse results

- [mfccfullsegment_models.ipynb](mfccfullsegment_models.ipynb) and [mfcc10segment_models.ipynb](mfcc10segment_models.ipynb)
  - Extracting data for full MFCCs, and MFCCs split into 10 segements
  - Trained and analysed different neural networks for both
  - Analysed accuracy using confusion matrices 
