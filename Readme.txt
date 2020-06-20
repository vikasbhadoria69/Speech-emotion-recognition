In this Python mini project, I have used the libraries librosa, soundfile, and sklearn (among others) to build a model using an MLPClassifier. This will be able to recognize emotion from sound files. I will load the data, extract features from it, then split the dataset into training and testing sets. Then, I’ll initialize an MLPClassifier and train the model. Finally, I’ll calculate the accuracy of my model.

 Defining a function extract_feature to extract the mfcc, chroma, and mel features from a sound file. This function takes 4 parameters- the file name and three Boolean parameters for the three features:

##mfcc: Mel Frequency Cepstral Coefficient, represents the short-term power spectrum of a sound
##chroma: Pertains to the 12 different pitch classes
##mel: Mel Spectrogram Frequency

Download the dataset from this link: https://drive.google.com/file/d/1wWsrN2Ep7x6lWqOXfr4rpKGYrJhWc8z7/view