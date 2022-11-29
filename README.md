# Pitch-synchronous-residual-MFCC-for-language-identification

Language Identification is the problem of identifying the language given an audio clip of a speaker irrespective of their Physical attributes(gender, accent etc.).​ Generally, we use fixed window length during framing, but in Pitch synchronous analysis, we extract the locations of pitch and get frames between the pitch cycles.​Residual is the error obtained between the predicted and the actual speech signal using LP analysis.​MFCC is used as the feature extraction step, which is done by using mel frequency filters and cepstral analysis.​ MFCC features are then supplied to a GMM model for training.
Model is tested with 7 languages having an overall accuracy of 96.42 %
