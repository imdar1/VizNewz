<p align="center">
  <img src="res/logo.png" />
</p>

# VizNewz
VizNewz is a sentiment analysis app, designed to help government/communities to get the latest trends from a specific region. Currently, we only support getting trends and sentiments from Jakarta as part of the Jakarta Smart City (JSC) program.

## Benefits
For the government:
- Get to know more about the community. VizNews helps the government to learn more about the public's responses to the government policies.
- Improve public services based on news from reputable sources.
- Help the government to base their decisions on data.

For public:
- Easily get the latest news for a specific category.
- Get to know more about the latest government policies and their acceptance in the community based on the results of sentiment analysis.

## How does it work?
Briefly, we perform the following operations:
- Automated News Scraper. We collect news from reputable sources (currently Kompas.com and Detik.com). Our news is updated every 24 hours.
- Jakarta Classification. Classify and filter news that is only related to the Jakarta's government.
- Topic Classification. Classify news into 9 different categories (Transportion, Health, Economy, Culture, Education, Politics, Law, Natural Disaster, and Other).
- Sentiment Analysis. Categorize each news as **positive**, **negative**, and **neutral**. 

You will be able to count sentiments and see the current trends with simple, easy to understand visualization. We also keen to improve our machine learning models to get better accuracy.


## Project Directories
- [VizNewz Android App]()
- [VizNewz Backend API](https://github.com/imdar1/news-api)
- [VizNewz Scraper & Predictor](https://github.com/marsathoriq/Scraper-Berita)
- [VizNews ML]()

## Overall Architecture Design
TBD

## Team Member
|         Member         | Student ID |         Path         | 
| :--------------------  | :--------: | :------------------: |
|  Ilham Oktovian        |  A3352996  |  Mobile Development  |
|  Erica Rubetta         |  A2342252  |  Mobile Development  |
|  Isa Mujahid D         |  C0020091  |  Cloud Computing     |
|  Nurul Chotimah        |  C1241604  |  Cloud Computing     |
|  Marsa Thoriq Ahmada   |  M0020097  |  Machine Learning      |
|  Ghiffary R            |  M0020052  |  Machine Learning      |
