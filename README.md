## Analyse characteristics of the voice in a sample

[The first notebook](S_Sprechstile_Anghelescu.ipynb) contains a code that analyses characteristics of the voice such as fundamental frequency, formants, Harmonics-to-Noise Ratio (HNR). 

First step was to record a voice sample and split it into [segments](Angehelescu), 3-7 seconds each. The segments have been annotated afterwards with the program Speechalyser. [The labels](labels.txt) show the valence of each segment, on a scale from 1 to 5, where 1=negative, 5=positive.
The valence is analysed in the code, using different visualizations form the libraries Pandas and Seaborn.

The characteristics of the voice are measured in another two notebooks, [Measure Pitch and HNR.ipynb](Measure Pitch and HNR.ipynb) and [Measure Pitch, HNR, Jitter, Shimmer, and Formants.ipynb](Measure Pitch, HNR, Jitter, Shimmer, and Formants.ipynb), which contain Praat Scripts (author: David R. Feinberg). [The dataframe with the results](anghelescu_df.pkl) is saved as a zip file and used in the first notebook for more visual representations (histogram, box plots, etc) and for finding correlations between the characteristics.    

[The second notebook](S_Sprechstile_all_dataframes.ipynb) constitutes a comparison between the dataframes with characteristics of the voice from more speakers. The code creates in the beginning a big dataframe with the [data measured by all speakers](Dataframes). This is analysed again with the same tools as in the first notebook: visualizations, comparisons, finding correlations. 

**How to use it**
<ul>
<li>record a speech segment it</li>
<li>annotate it with Speechalyser or another similar program</li>
<li>in a terminal open "Measure Pitch and HNR.ipynb" and/or "Measure Pitch, HNR, Jitter, Shimmer, and Formants.ipynb" with a Notebook IDE (eg  Jupyter Notebook or Google Collab)</li>
<li>in the code, change the path with the folder from your computer (where you have the recordings) </li>  
<li>run all (the zip file with the measured characteristics will be created and saved in your computer</li>
<li>open "S_Sprechstile_Anghelescu.ipynb" and run all</li>  
</ul>

**Installations**
<ul>
<li>[Speechalyser](https://github.com/felixbur/Speechalyzer) or another program for speech data files labeling</li>
<li>[Labeltool](https://github.com/felixbur/Labeltool) (you need to install it as well if you want to use Speechalyser for labeling the data)</li>
<li>[Jupyter Notebook](https://jupyter.org/install)</li>  
</ul>

**Author**: Irina Anghelescu 

