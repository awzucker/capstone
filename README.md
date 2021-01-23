![](./images/bunker_sontec.jpeg)
Photo: [*The Bunker*](https://www.thebunkerstudio.com/)

# Project Title

### The Problem

The advent of affordable tools for home recording over the last 20 years has made music creation more accessible than ever before. Simultaneously, social media platforms such as Instagram and Facebook have made it similarly cheap and easy to advertise yourself to a targeted audience. However, most budding musicians, and even seasoned industry veterans, don't always know the best way to reach new fans; the *how*, *who*, and *where* questions always loom tall when it's time for a new release.

**In this study, I intend to create a recommender system to show similarities between the music of a new artist and that of popular artists around the globe, in order to generate basic recommendations to best connect new artists with new fans. I'll base this model on data from hundreds of thousands of songs hosted on the popular streaming platform Spotify, along with metrics I'll extract from a new artist's music using a Python library called Librosa.**

---

### Contents
| Notebook | File Name | Description |
|----|----|----|
|**1**|[01_data_collection_and_cleaning.ipynb](code/01_data_collection_and_cleaning.ipynb)|Spotify data imports, collection, and cleaning, and final Spotify dataframe export|
|**2**|[02_feature_engineering_and_comparisons.ipynb](code/02_feature_engineering_and_comparisons.ipynb)|Spotify dataframe feature selection and engineering; metric comparisons between Spotify and Librosa|
|**3**|[03_EDA.ipynb](code/03_EDA.ipynb)|Exploratory data analysis and visualizations|
|**4**|[04_recommeder_sys.ipynb](code/04_recommeder_sys.ipynb)|Recommender system based on Spotify metrics and Librosa-generated metrics|
|**5**|[05_appendix.ipynb](code/05_appendix.ipynb)|Appendix with examples of questionable Spotify and Librosa metrics, caveats, and glossary|

---

### Datasets Used

* Spotify Song Data from [Kaggle](https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks?select=data.csv)
* Data I collected via [Librosa](https://librosa.org/doc/latest/index.html#), a Python library for audio and digital signal processing (*DSP*)

---
### Background & Research

With over 15 years of experience in the music industry, first as a musician and performer, and later as a sound designer, audio engineer, and producer, I believe I'm in a unique position to address this problem. I have an intimate knowledge of the process of creating music and much of the theory behind it on both sides of the mixing board, as well as the struggles of finding and connecting with your target audience as a new artist. You can find more information about my history in the industry on [LinkedIn](https://www.linkedin.com/in/awzucker/), and samples of my recent work as part of a collaborative project called [NO EVENS](https://noevens.com/).

I'm also fortunate enough to have many long-time friends in the industry, two of whom I spoke to regarding this project: [Jacob Bergson](https://www.tautmusic.com/), an independent musician and audio engineer at [The Bunker](https://www.thebunkerstudio.com/) recording studio in Brooklyn, NY, and [Joseph Kelley](https://www.linkedin.com/in/jjkelley/), the former Executive Director of Artist Relations at [Billboard](https://www.billboard.com/). Jacob was able to provide me with excellent insight on his extensive experience engineering multiple genres of music, which helped immensely as I decided how to engineer my own metrics to represent some of the more intangible qualities of music. Joe, on the other hand, has a wealth of knowledge to offer on the business landscape of the music industry: where and among what demographics artists are trending, what makes artists stand out in a digital landscape where anyone can easily post their music online, and so on.


---

### Analysis Summary



---

### Conclusions & Considerations



---

### Sources:
* Spotify Track Data from [Kaggle](https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks?select=data.csv) (generated by Spotify)
* [Spotify API](https://developer.spotify.com/documentation/web-api/reference/)
* [Librosa & Librosa Documentation](https://librosa.org/doc/latest/index.html)
* [Every Noise At Once](http://everynoise.com/engenremap.html)
* [*Recommendation Systems: Principles, Methods and Evaluation*](https://www.sciencedirect.com/science/article/pii/S1110866515000341), F.O. Isinkaye, Y.O. Folajimi, B.A. Ojokoh
* Jacob Bergson (engineer at [The Bunker](https://www.thebunkerstudio.com/) studio)
* Joseph Kelley (former Director of A&R at [Billboard](https://www.billboard.com/))
* [*What Data Science Can Tell Us About Mainstream Music*](https://towardsdatascience.com/what-data-science-can-tell-us-about-mainstream-music-e56b20e00a25) by Ishan Nagpal on Medium
* 15+ years of personal experience as a sound designer, audio engineer, musician, and producer, and a lifetime love of recorded sound
