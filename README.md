## Analyse characteristics of the voice in a sample

[The first notebook](S_Sprechstile_Anghelescu.ipynb) contains a code that analyses characteristics of the voice such as fundamental frequency, formants, Harmonics-to-Noise Ratio (HNR) and shows how you can find correlations between these.

First step was to record a voice sample and split it into [segments](Angehelescu), 3-7 seconds each. The segments have been annotated afterwards with the program Speechalyser. [The labels](labels.txt) show the valence of each segment, on a scale from 1 to 5, where 1=negative, 5=positive.
The valence is analysed and compared in the code, using different visualizations form the libraries Pandas and Seaborn.

Next step was to measure the characteristics of the voice. These are measured in another two notebooks, [Measure Pitch and HNR.ipynb](Measure Pitch and HNR.ipynb) and [Measure Pitch, HNR, Jitter, Shimmer, and Formants.ipynb](Measure Pitch, HNR, Jitter, Shimmer, and Formants.ipynb), which contain Praat Scripts (author: David R. Feinberg). [The dataframe with the results](anghelescu_df.pkl) is saved as a zip file and analysed in the first notebook, with more visual representations (histogram, box plots, etc) and by finding correlations between the characteristics.    

[The second notebook](S_Sprechstile_all_dataframes.ipynb) constitutes a comparison between the dataframes with characteristics of the voice from more speakers. The code creates in the beginning a big dataframe with the [data measured by all speakers](Dataframes). This is analysed again with the same tools as in the first notebook: visualizations, comparisons, finding correlations. 

**How to use it**
<ul>
<li>record a speech segment it</li>
<li>annotate the segments with Speechalyser or another similar program</li>
<li>in a terminal open "Measure Pitch and HNR.ipynb" and/or "Measure Pitch, HNR, Jitter, Shimmer, and Formants.ipynb" (depending on which characteristics you want to measure) with a Notebook IDE (eg  Jupyter Notebook or Google Collab)</li>
<li>in the code, change the path with the folder from your computer, in which you have the segements</li>  
<li>run all (the zip file with the measured characteristics will be created and saved to your computer</li>
<li>open "S_Sprechstile_Anghelescu.ipynb"</li>  
<li>run all</li>
<li>look at how the charts and plots look like</li>
<li>if you want to make a comparison between the data from more speakers, repeat the process of measuring the characteristics with the Praat Scripts</li>
<li>create a folder with all the zip files</li>
<li>open "S_Sprechstile_all_dataframes.ipynb"</li>  
<li>change the path</li>
<li>run all</li>  
<li>look at how the visualizations look like and see what conclusions you can draw</li>
</ul>

**Installations**
<ul>
<li> [Speechalyser](https://github.com/felixbur/Speechalyzer) or another program for speech data files labeling</li>
<li> [Labeltool](https://github.com/felixbur/Labeltool) (you need to install it as well if you want to use Speechalyser for labeling the data)</li>
<li> [Jupyter Notebook](https://jupyter.org/install)</li>  
</ul>

**Author**: Irina Anghelescu 

