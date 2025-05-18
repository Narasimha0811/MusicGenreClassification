# MusicGenresClassification
Utilized the GTZAN dataset and developed preprocessing pipelines in python to handle missing files and balance classes. 
Converted the audio files to Mel-spectrograms and extracted frequency, time-domain features. 
Then, we applied log-Mel transformation, gaussian smoothing and edge detection to enrich model inputs. 
Designed and trained a CNN model on raw and feature engineering spectrograms in TensorFlow which achieved 96.5% test accuracy and 57% validation accuracy surpassing standard CNN and Random Forest baseline models.  
Evaluated the model with metrics like accuracy, precision, recall and deployed the CNN model via a Gradio web interface for real-time predictions. 
Prepared and presented detailed performance reports and visualizations of the model. 
