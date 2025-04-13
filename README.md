# Доска. Важное
https://miro.com/welcomeonboard/SzVlN0hlSFVLczVIenl1WWlrRFhjOHpXNlNXcW1iVkYwenM4SW1sQ29SY2RMNTAvdmxwcDVyUGM4YVY0VXFXVisyYUxhMDVYNHczVVRrQjZKWldjZDQ2TzFHRG5ka1JLbVc4M3FIVENhZS9JdTFVUitLaHlHQ1U0bkFGSkFsbXp0R2lncW1vRmFBVnlLcVJzTmdFdlNRPT0hdjE=?share_link_id=577326765906

# Описание данных

## tripdata
Скачать: https://disk.yandex.ru/d/BxYXxeP3JOZ6ew

### 20_tripdata.parquet
Данные о поездках с января 2020 по сентябрь 2021
- Divvy_Trips_2020_Q1.csv
- 202004-divvy-tripdata.csv
- 202005-divvy-tripdata.csv
- 202006-divvy-tripdata.csv
- 202007-divvy-tripdata.csv
- 202008-divvy-tripdata.csv
- 202009-divvy-tripdata.csv
- 202010-divvy-tripdata.csv
- 202011-divvy-tripdata.csv
- 202012-divvy-tripdata.csv
- 202101-divvy-tripdata.csv
- 202102-divvy-tripdata.csv
- 202103-divvy-tripdata.csv
- 202104-divvy-tripdata.csv
- 202105-divvy-tripdata.csv
- 202106-divvy-tripdata.csv
- 202107-divvy-tripdata.csv
- 202108-divvy-tripdata.csv
- 202109-divvy-tripdata.csv

8529228 строк

### 40_tripdata.parquet
Данные о поездках с октября 2021 по май 2023
- 202110-divvy-tripdata.csv
- 202111-divvy-tripdata.csv
- 202112-divvy-tripdata.csv
- 202201-divvy-tripdata.csv
- 202202-divvy-tripdata.csv
- 202203-divvy-tripdata.csv
- 202204-divvy-tripdata.csv
- 202205-divvy-tripdata.csv
- 202206-divvy-tripdata.csv
- 202207-divvy-tripdata.csv
- 202208-divvy-tripdata.csv
- 202209-divvy-publictripdata.csv
- 202210-divvy-tripdata.csv
- 202211-divvy-tripdata.csv
- 202212-divvy-tripdata.csv
- 202301-divvy-tripdata.csv
- 202302-divvy-tripdata.csv
- 202303-divvy-tripdata.csv
- 202304-divvy-tripdata.csv
- 202305-divvy-tripdata.csv

8665694 строк

### 60_tripdata.parquet
Данные о поездках с июня 2023 по февраль 2025
- 202306-divvy-tripdata.csv
- 202307-divvy-tripdata.csv
- 202308-divvy-tripdata.csv
- 202309-divvy-tripdata.csv
- 202310-divvy-tripdata.csv
- 202311-divvy-tripdata.csv
- 202312-divvy-tripdata.csv
- 202401-divvy-tripdata.csv
- 202402-divvy-tripdata.csv
- 202403-divvy-tripdata.csv
- 202404-divvy-tripdata.csv
- 202405-divvy-tripdata.csv
- 202406-divvy-tripdata.csv
- 202407-divvy-tripdata.csv
- 202408-divvy-tripdata.csv
- 202409-divvy-tripdata.csv
- 202410-divvy-tripdata.csv
- 202411-divvy-tripdata.csv
- 202412-divvy-tripdata.csv
- 202501-divvy-tripdata.csv
- 202502-divvy-tripdata.csv

9480555 строк

### Поля
- ride_id (ID поездки)
- rideable_type (тип транспортного средства)
- started_at (время начала поездки)
- ended_at (время окончания поездки)
- start_station_name (наименование станции отправления)
- start_station_id (ID станции отправления)
- end_station_name (наименования станции прибытия)
- end_station_id (ID станции прибытия)
- start_lat (широта старта)
- start_lng (долгота старта)
- end_lat (широта прибытия)
- end_lng (долгота прибытия)
- member_casual (casual купил Pass на 24 часа, member купил годовое членство [Эта информация была взята из readme старых датасетов {за 2013 год} '"Customer" is a rider who purchased a 24-Hour Pass; "Subscriber" is a rider who purchased an Annual Membership'])

## Stations
Описание станций с 2013 по 2017 года. Во все года, кроме 2015 установлена дата, на период которой описывалось состояние станции. В 2015 году это поле отсутствовало, везде в соответствующий столбец было поставлено значение года 2015

Скачать: https://disk.yandex.ru/d/aB2M0ILGae6fAg

### Поля
- id (ID станции)
- name (наименование станции)
- latitude (широта станции)
- longitude (долгота станции)
- dpcapacity (вместимость станции)
- landmark (нет в описании)
- online_date (дата появления станции в системе)
- city (нет в описании)
###
# P. S.
Никакая обработка данных кроме конкатенации не проводилась (с таблицей stations продолжу работу, надо посмотреть что там с датами)

## Trips + stations 2013 - 2019
Скачать https://disk.yandex.ru/d/2utTOPGF-gTj6Q

## Ценность поездок
Скачать https://disk.yandex.ru/d/2wP6dQf0tWGnYg

## Погода
Скачать https://disk.yandex.ru/d/6ZiR3aYGLIS86Q