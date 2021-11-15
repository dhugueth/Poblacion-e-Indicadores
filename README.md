# Population and Indicators 

To access the report [click here](https://app.powerbi.com/view?r=eyJrIjoiZWNkN2NkNjctZmU0ZC00YWEzLWI5NGYtZjkxMzJkMWZhZGVjIiwidCI6ImJhYjBiNjc5LWJkNWYtNGZlOC1iNTE2LWM2YjhiMzE3Yzc4MiIsImMiOjR9)

## What was used? 

The project was developed and published using Power BI, one of the top leader in business Intelligence.

### Data

_The data used was provided for educational purposes by Power BI - Data Analysis and Business Intelligence course on the Udemy platform._

**First Part**
- [Population.xlsx](https://github.com/dhugueth/Poblacion-e-Indicadores/files/7532797/Population.xlsx)
- [Countries.xlsx](https://github.com/dhugueth/Poblacion-e-Indicadores/files/7532795/Countries.xlsx)
- [Paises.xlsx](https://github.com/dhugueth/Poblacion-e-Indicadores/files/7532796/Paises.xlsx)

**Second Part**
- [Infant death rate.xlsx](https://github.com/dhugueth/Poblacion-e-Indicadores/files/7532798/Infant%2Bdeath%2Brate.xlsx)
- [Life expectancy.xlsx](https://github.com/dhugueth/Poblacion-e-Indicadores/files/7532799/Life%2Bexpectancy.xlsx)


### Data Preparation

Modifications were made to the original data using the Power Query editor to be able to use them appropriately. 

The modifications were: 

- In some cases it was necessary to use the "Use First Row as Headers" option to accommodate the imported data.
- A conditional column was created to add a new category called "Cantidad Poblacional" 
- A conditional column was created to add a new category called "Mortalidad Infantil (Muertes cada 1000 niños)"
- A conditional column was created to add a new category called "Esperanza de Vida (Años promedio)"

## Data Modeling

It was required to relate common data between the files:

- The data named "Country" from the file Population" and "countries" were related. 
- The data named "Country code" and "Codigo pais" from the file "Population" and "countries" were related.
- The data named "Country" from the file "countries" and "Infant death rate" were related.
- The data named "Country" from the file "countries" and "Life Expectancy" were related.

![relacion de datos](https://user-images.githubusercontent.com/93662295/141716274-a53ea1b4-eb37-432b-9bae-6981036d5769.png)


## Description

This is an interactive report that analyzes the behavior of copies sold seen in millions of the video game industry.

For the data analysis, characteristics such as the year, regions, platform, video game genre and publisher were taken into account.


Different types of visualizations were used to represent data behaviors such as stacked column charts, stacked bar charts, line charts, and pie charts. Through which we can see clearly and friendly how sales had their greatest boom during 2008, being the North American region the one with the highest sales index.

Additionally, it is possible to observe that the genres of action, sports and shooter were the ones that attracted the largest number of players, with the playstation 2 and Xbox 360 the leading Console in sales.

Below you can see a snapshot of the report:

