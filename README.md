# foodPriceScraper
## Español

Extrae los precios de diferentes alimentos de la página web del [SISAP](http://sistemas.minag.gob.pe/sisap/portal2/mayorista/) del Ministerio de Agricultura y Riego.

Para ejecutar el script es necesario instalar la siguientes bibliotecas:
```
pip install pandas
pip install requests
pip install lxml
pip install beautifulsoup4
```

El script se debe ejecutar de la siguiente manera:
```
python foodPriceScraper.py --startDate 01/11/2017 --endDate 04/11/2017
```

Donde **startDate** es la fecha de inicio y **endDate** es la fecha de fin del intervalo de tiempo que se deseea extraer. Los registros se almacenan en un archivo de tipo CSV.

Actualmente solo extrae el precio mínimo, promedio y máximo de los siguientes alimentos:
- Papa
- Limon
- Aceite
- Ajo
- Apio
- Arroz
- Azucar
- Cebolla
- Huevos
- Leche
- Pollo
- Tomate
- Yuca
- Zanahoria

## English

Extract prices for several foods of [SISAP System](http://sistemas.minag.gob.pe/sisap/portal2/mayorista/)

To run is necessary install the following libraries:
```
pip install pandas
pip install requests
pip install lxml
pip install beautifulsoup4
```

To run the script:
```
python foodPriceScraper.py --startDate 01/11/2017 --endDate 04/11/2017

Where **startDate** is the start date and **endDate** is the end date of interval of time to query. All data between this interval is extracted into csv file.
