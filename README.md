# Spotify Top30 Visualization

<p align="center">
    <img src="https://i.imgur.com/mPb3Qbd.gif" width="180" alt="Politecnico di Milano"/>
</p>

[![Open All Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1W-m-ub4bFGmV7F01aa0MWEdGV1Py_iko)
![Spotify](https://img.shields.io/badge/Spotify-1ED760?style=flat&logo=spotify&logoColor=white)

Spotify is a Swedish music streaming and media services provider that was founded in 2006. Since then, its popularity has grown year after year, reaching 299 million active monthly users and being available in 92 countries. These numbers, together with the ability to easily access a large amount of raw data and related services, make Spotify the perfect candidate for an analysis focused on world music preferences and their evolution over time.


## Building the dataset

Since no previous source is shaped according to our will, we started scraping from [Spotify Charts](https://spotifycharts.com/regional), a website which collects the daily regional Top200 charts for 65 countries in the world. Then, to enrich the available information for each song, we exploited the [Spotify for Developers API](https://developer.spotify.com/), which provided us additional songs' attributes, such as danceability, energy, loudness, instrumentalness and tempo.

## Data exploration

In the preliminary phase, the problem was introduced, showing on the map the states under investigation and the number of streams for each of them, considering also the relative population. Annual spotify statistics were also highlighted, delving into the contributions of each continent. Finally, the trend of the number of streams revealed peaks attributable to the release of albums by major international artists, such as **Drake**, **Ariana Grande** and **Post Malone**.

<p align="center">
    <img src="https://i.imgur.com/VVYnzK7.png" width="800" alt="time analysis"/>
</p>

## Spread analysis

In this section we have selected some interesting case studies to show how national hits can impact on the global audience. We started with **Tilidin**, a german success, which was not able to cross borders, except for neighboring Austria. Same behaviour also for the italian **Soldi** which, however, differs for the peak of streams across Europe due to the Eurovision contest. If **In My Feelings** was an instant hit everywhere, much more interesting is the trend of **Dance Monkey** (in picture) which has conquered the top of the worldwide charts over the course of months.

<p align="center">
    <img src="" width="800" alt="spread map"/>
</p>

## Country study

In this section, we explored national music tastes based on song attributes, seeking to understand if there were any interesting relationships. For example, it turns out that in South America, songs exhibit higher **energy** and **loudness**, while **acousticness** seems accentuated in Eastern countries. Finally, Brazil clearly stands out for songs with high levels of **liveness**.

<p align="center">
    <img src="https://i.imgur.com/zpyYOdR.png" width="800" alt="country features"/>
</p>

## Seasonality

In the last section, we looked for possible relationships between song characteristics and the time of the year in which they were released and entered the charts. Considering the songs that had a worldwide success, it is possible to find more **energy** in spring and summer, while in winter are more frequent more **acoustic** and **sadder** songs.

<p align="center">
    <img src="https://i.imgur.com/Z3MhYkf.png" width="800" alt="seasonality"/>
</p>

## Team

- Samuele Meta [[Github](https://github.com/SamueleMeta)] [[Email](mailto:samuele.meta@mail.polimi.it)]
- Stiven Metaj [[Github](https://github.com/StivenMetaj)] [[Email](mailto:stiven.metaj@mail.polimi.it)]
- Manuel Salamino [[Github](https://github.com/manuelsalamino)] [[Email](mailto:manuel.salamino@mail.polimi.it)]
- Giuseppe Serna [[Github](https://github.com/armando2603)] [[Email](mailto:giuseppe.serna@mail.polimi.it)]
