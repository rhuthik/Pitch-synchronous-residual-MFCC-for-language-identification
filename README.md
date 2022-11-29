# Pitch-synchronous-residual-MFCC-for-language-identification

Language Identification is the problem of identifying the language given an audio clip of a speaker irrespective of their Physical attributes(gender, accent etc.).​ Generally, we use fixed window length during framing, but in Pitch synchronous analysis, we extract the locations of pitch and get frames between the pitch cycles.​Residual is the error obtained between the predicted and the actual speech signal using LP analysis.​MFCC is used as the feature extraction step, which is done by using mel frequency filters and cepstral analysis.​ MFCC features are then supplied to a GMM model for training.
The overall pipeline follows as such:
![alt text](https://github.com/rhuthik/Pitch-synchronous-residual-MFCC-for-language-identification/blob/dd2d548ef2f4fb95ae2dd77bf3e401b06664a9d2/pipeline.png)
Model is tested with 7 Indian languages having an overall accuracy of 96.42 %
![alt text](https://github.com/rhuthik/Pitch-synchronous-residual-MFCC-for-language-identification/blob/787865e0168ef9c69df270ca9a257af90259567c/Screenshot%20from%202022-11-29%2014-19-00.png)
