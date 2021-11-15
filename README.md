Project-Plan-your-trip-with-Kayak est un notebook permettant de faire une proposition de destination pour les vacances a partir de la liste du top 35 des villes francaise.
Les villes selectionnées sont les villes ayant un taux de precipitation pour 7 jours le plus bas. 
Quand le code est lancé :
- Via l'API de "https://nominatim.openstreetmap.org/" une recuperation des coordonnées geographiques des 35 villes est faite.
- Via l'API de "https://api.openweathermap.org/" une recuperation des données meteorologiques des 35 villes via les coordonnées geographiques est faite.

Avec scrapy.Spider un spraping des informations des hotels (note, description, localisation etc...) des 35 villes est effectué.

En finalité 2 cartes interactive sont affichées : 
La premiere carte montre le top 5 des villes ou les previsons de pluie sont les plus basse.
La seconde carte montre le top 20 des hotels des 5 villes.


----------------------------------------------------------------------------------------

Project-Plan-your-trip-with-Kayak is a notebook allowing you to make a proposal for a holiday destination from the list of the top 35 French cities.
The cities selected are the cities with the lowest 7-day precipitation rate.
When the code is launched:
- Via the API of "https://nominatim.openstreetmap.org/" a retrieval of the geographical coordinates of the 35 cities is made.
- Via the API of "https://api.openweathermap.org/" a retrieval of meteorological data of 35 cities via geographic coordinates is made.

With scrapy.Spider a spraping of hotel information (rating, description, location etc ...) of the 35 cities is carried out.

Finally 2 interactive maps are displayed:
The first map shows the top 5 cities with the lowest rainfall forecast.
The second map shows the top 20 hotels in the 5 cities.
