# Visualisation of covid-19 cases, deaths and mortality by country and ruling political party
Interactive visualisation of worldwide cases of covid. Pandemic data is coming from [European Centre for Disease Prevention and Control](https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide).

Ruling political parties are extracted from a [wikipedia page](https://en.wikipedia.org/wiki/List_of_ruling_political_parties_by_country), the list of dictatorships in the world is extracted from [this page](https://worldpopulationreview.com/countries/dictatorship-countries/); both webpages have been scraped using [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) library.

Data processing is done in a jupyter notebook.
I use Python Bokeh library to generate the plot in html format, **the result can be seen [here](...)**.

## Wishlist

- [ ] Generate an up to date visualisation every night (with github actions?)
- [ ] Include information from [health care system by country wiki page](https://en.wikipedia.org/wiki/Health_care_systems_by_country).
- [ ] Include population density for each country.
- [ ] Set up automatic statistical significance checks to unveil meaningful differences.
- [ ] Use a different colour for each country circle in the visualisation.
- [ ] Make the plot dynamic/make it an animation (showing the evolution of the values month by month since January 2020?).
