# Исследование объявлений о продаже квартир

## Описание проекта
В вашем распоряжении данные сервиса Яндекс Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. Ваша задача — установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность. 
По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма. 

**Цель исследования** - Результатом работы является проведенный анализ и разработанные на его основе рекомендации.


## Используемые библиотеки
`Pandas`, `Matplotlib`, `Seaborn`, `Folium`

## Данные
Датасет представлен следующими данными: 
*    `airports_nearest` - distance to the nearest airport in meters (m)
*    `balcony` - number of balconies
*    `ceiling_height` - ceiling height in meters (m)
*    `cityCenters_nearest` - distance to the city center in meters (m)
*    `days_exposition` - number of days the ad was published (from publication to removal)
*    `first_day_exposition` - publication date
*    `floor` - floor
*    `floors_total` - total number of floors in the building
*    `is_apartment` - apartment (boolean type)
*    `kitchen_area` - kitchen area in square meters (m²)
*    `last_price` - price at the time of removal from publication
*    `living_area` - living area in square meters (m²)
*    `locality_name` - locality name
*    `open_plan` - open plan (boolean type)
*    `parks_around3000` - number of parks within a 3 km radius
*    `parks_nearest` - distance to the nearest park in meters (m)
*    `ponds_around3000` - number of ponds within a 3 km radius
*    `ponds_nearest` - distance to the nearest pond in meters (m)
*    `rooms` - number of rooms
*    `studio` - studio apartment (boolean type)
*    `total_area` - total area of the apartment in square meters (m²)
*    `total_images` - number of photos of the apartment in the ad


## Технические особенности проекта
В связи с тем, что датасет, представленный в проекте, находится под NDA, перезапустить ядро невозможно, так как путь, указанный в проекте, не будет действителен. 

## Дальнейшие планы на проект
Было бы интересно проанализировать рынок общественного питания по всей стране (или хотя бы центральным городам) и построить сводный дашборд в Yandex DataLens.
