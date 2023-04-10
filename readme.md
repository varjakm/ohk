[Eesti ilm] (https://airviro.klab.ee/)

| Attr  | example value | unit    | Description                 |
| ----- | ------------- | ------- | --------------------------- |
| SO2   | 0,23          | µg/m³ | Vääveldioksiid            |
| NO2   | 0,02          | µg/m³ | Lämmastikdioksiid          |
| CO    | 0,24          | mg/m³  | Süsinikoksiid              |
| O3    | 70,05         | µg/m³ | Osoon                       |
| PM10  | 8,55          | µg/m³ | Peened osakesed             |
| PM2.5 | 4,72          | µg/m³ | Eriti peened osakesed       |
| TEMP  | 9,72          | C       | Temperatuur                 |
| WD10  | 204        | deg     | Tuule suund 10 m kõrgusel  |
| WS10  | 1,56          | m/s     | Tuule kiirus 10 m kõrgusel |

| Attr  | example value | unit    | Description                 |
| ----- | ------------- | ------- | --------------------------- |
| SO2   | 0.23          | µg/m³ | Sulfur dioxide            |
| NO2   | 0.02          | µg/m³ | Nitrogen dioxide          |
| CO    | 0.24          | mg/m³  | Carbon monooxide              |
| O3    | 70.05         | µg/m³ | Ozone                       |
| PM10  | 8.55          | µg/m³ | Small particles             |
| PM2.5 | 4.72          | µg/m³ | Very small particles       |
| TEMP  | 9.72          | C       | Temperature                 |
| WD10  | 204       | deg     | Wind direction at 10 m  |
| WS10  | 1.56          | m/s     | Wind speed at 10 m |

*Using Python script to extract the data from the website for a given year and save the data as csv-file into folder air_data

*Using Python Pandas library, the csv-file was read into a dataframe (table) df

*Pandas was used to do all the processing

*In the end the tables with hourly (df_hourly), daily (df_daily), and monthly (df_monthly) average values for all columns in the dataset were obtained
and saved as CSV files into a separate folder air_data_tables

*Decided to use one programming language to avoid jumping between file formats, programming languages, tools to reduce potential confusion
