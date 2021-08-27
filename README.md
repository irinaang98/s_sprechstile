## Analyse characteristics of the voice in a sample

[The first notebook](S_Sprechstile_Anghelescu.ipynb) contains a code that analyses characteristics of the voice such as fundamental frequency, formants, Harmonics-to-Noise Ratio. 

First step was to record a voice sample and split it into [segments](Angehelescu), 3-7 seconds each. The segments have been annotated afterwards with the program Speechalyser. [The labels](labels.txt) show the valence of the segment, on a scale from 1 to 5, where 1=negative, 5=positive).
The valence is analysed in the code, represented with different visualizations form the libraries Pandas and Seaborn.

The characteristics of the voice are measured in another two notebooks, [Measure Pitch and HNR.ipynb](Measure Pitch and HNR.ipynb) and [Measure Pitch, HNR, Jitter, Shimmer, and Formants.ipynb](Measure Pitch, HNR, Jitter, Shimmer, and Formants.ipynb), which contain Praat Scripts (author: David R. Feinberg). [The dataframe with the results](anghelescu_df.pkl) is saved as a zip file and used in the first notebook for more visual representations (histogram, box plots, etc) and for finding correlations between the characteristics.    

[The second notebook](S_Sprechstile_all_dataframes.ipynb) constitutes a comparison between the dataframes with the characteristics of the voice from more speakers. 
