# Competitive-Valorant-Statistics

This project was our team's first experience exploring data beyond the datasets included in Sklearn.
Being the gamers we are, we wanted to look into something that would genuinely be useful for us, so we decided to look into data collected from results of thousands of competitive Valorant matches. (Valorant being an extremely popular first-person shooter game)

We have found https://www.thespike.gg/ to have the widest range of data possible, with not only a lot of competitive matches played, but also collecting statistics on the game's maps, character performance, etc. Using the **BeautifulSoup** Python library, we scraped this website to gather all the data about maps, agents (in-game characters) and per-round performances.

With the help of the **pandas** and **Matplotlib** Python libraries, our team explored and visualized the data for easier exploration. Having found no outstanding results that might suggest one strategy/map/agent being better than any other, we have decided to also employ the help of sklearn's **Linear Regression** model to look into whether winning the first round tends to lead into winning the whole match. (Spoiler alert: there was some correlation!)

_You can also see the data visualisations clearly and neatly formatted in the Nbviewer: https://nbviewer.org/github/azimovaisha/Competitive-Valorant-Statistics/blob/main/Valorant_Statistics.ipynb_
