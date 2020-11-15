# wsiz-api_tests aktualizacja 2020-11-15

## Opis projektu 
* [Informacje](#informacje)
* [Technologie](#technologie)
* [Konfiguracja](#konfiguracja)

## Informacje
Projekt zwiera przykładowe testy api z wykorzystaniem aplikacji Postman
	
## Technologie
Test utworzone w:
* Postman v7.34.0
	
	
## Konfiguracja
1. Pobranie aplikacji Postman: [Postman](https://www.postman.com/ "Aplikacja Postman")
2. Pobranie aplikacji Node.js: [Node.js](https://nodejs.org/en/ "Aplikacja Node.js")
3. Pobranie aplikacji Newman:  [Newman](https://learning.postman.com/docs/running-collections/using-newman-cli/command-line-integration-with-newman/ "Aplikacja Newman")


```
* Import kolekcji [import collections]:opcja Import - > Upload Files - > wybrać plik OpenWeatherMap.postman_collection.json 
* Import zmiennych środowiska [manage environments]:klikknij ikonę ustawień Manage Environments - > Import - > wybrać plik OpenWeatherMap.postman_environment.json
```

## Tabela z opisem testów 

### [OpenWeatherMap](https://openweathermap.org/ "OpenWeatherMap")

NAZWA | OPIS 
------------ | ------------- 
GET_STATTION_BY_CITY | Sprawdzenie pogody wg miejscowości
GET_STATION_BY_ID | Pobranie danych o pogodzie wg id miejscowości
GET_STATION_LIST | Pobranie listy dostępnych stacji pogodowych
ADD_STATION | Dodanie nowej stacji
CHANGE_STATTION | Modyfikacja danych stacji pogodowej
DELETE_STATION | Usunięcie stacji pogodowej







