# <p align="center">Morgenshtern Album NLP</p> 

<p align="center">
  <img src=https://img.golos.io/proxy/http://lk.aldmi.ru/wp-content/uploads/2016/04/Divider_03-1.png width="600" height="80">
</p>

## Problem formulation

<p align="justify"> 
  "Million Dollar Business" is the fifth studio album by Russian rap artist and musician Morgenstern, released on May 28, 2021. According to the rapper, for this album he received an advance payment of one million dollars — the same as for the previous one. Let's analyze this album.
</p>

## Data
<p align="justify"> 
  Source data is Morgenstern's tracks from the album "Million Dollar Business" saved in the format ".txt". 
</p>

 Album with lyrics by [link](https://genius.com/albums/Morgenshtern/Million-dollar-business)


## Solution description

<p align="justify"> 
  For analyzing tracks will look at wordclouds and calculate various statistics. The final stage of the analysis is consideration of semantic proximity of the songs to each other and overall mood of the album. An example of a wordcloud is shown in Figure 1.
</p>

<p align="center">
  <img src=pictures/WI_sales.png "Wordcloud for track "ARISTOCRAT"" width="750" height="500">
</p>

*<p align="center">
  Fig. 1 Wordcloud for track "ARISTOCRAT"
</p>* 
                

### Models
<p align="justify">
  Using the Word2Vec model and the cosine measure, we can look at the semantic proximity of songs to each other and calculate the overall mood of the album. 
</p>

Here we use a ready-made model trained in the National Corpus of the Russian Language from [Rusvectōrēs community] (https://rusvectores.org/ru/models/) 
The results of comparing the texts of all pairs of tracks are shown in Figure 2.


<p align="center">
  <img src=pictures/WI_sales.png "Tracks comparison" width="750" height="500">
</p>

*<p align="center">
  Fig. 2 Tracks comparison
</p>* 
