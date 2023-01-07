
# Covid-19 Detection using Cough Analysis

This project is focuses on development of a machine learning algorithm that detects the covid-19 disease in the patient using patient's cough. This approach is 

# Road Map
 ## Data Collection
The first step of the project is that the patient has to upload the cough audio file either in .wav or .mp3 format.
 ## Training
 A machine learning algorithm is selected for training on the both infected and un-infected patient's data. 
 ## Feature Extraction
 Applying the noise filters the noise from the audio file is removed. Later, many features neccesary for the analysis are extracted these are MFCC, spectral bandwidth, spectral roll-off, spectral centroid.
 ## Predicition
 In the final step, these extracted features are fed into the algorithm to predict the change of patient suffering from covid. 


## Deployment

To ensure the successful operation of this project, there are some aspects one should look at.
The python libraries that I used have some dependency issues. So, after downloading required libraries to run the algorithm successfully the following commands should be executed in the terminal.

```python
pip install speaker-verification-toolkit
pip install numba==0.48
pip install resampy==0.3.1
```




## Screenshots

![](/melspectrogram.png)

## Authors

[Bharadwaj](https://github.com/Bharadwaj75-ceo)
