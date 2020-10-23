# Сообщения о ДПТ из группы "ДТП и ЧП | Санкт-Петербург"

Данные взяты из группы ВКонтакте [ДТП и ЧП | Санкт-Петербург](https://vk.com/spb_today) при помощи [*API*](https://vk.com/dev/wall.get)

## Структура поста

```json
{
    "id": 13979013,
    "from_id": -68471405,
    "owner_id": -68471405,
    "date": 1603222583,
    "marked_as_ads": 0,
    "post_type": "post",
    "text": "Паровозик из 4х машин на Пискаревском над Шафировской развязкой.",
    "signer_id": 35464517,
    "attachments": [
       ...
    ],
    "post_source": { "type": "vk" },
    "comments": { "count": 9, "can_post": 1 },
    "likes": { "count": 17, "user_likes": 0, "can_like": 1, "can_publish": 1 },
    "reposts": { "count": 0, "user_reposted": 0 },
    "views": { "count": 27063 }
}
```

## Структура датасета

| key               | type           | description                   |
|:------------------|:---------------|:------------------------------|
| id                | int64          |Id поста                       |
| text              | str            |Текст поста                    |
| date              | datetime64     |Дата публикации                |
| comments          | int64          |Количество комментариев        |
| likes             | int64          |Количество лайков              |
| reposts           | int64          |Количество репостов            |
| views             | int64          |Количество просмотров          |
| attachments_count | int64          |Количество файлов (фото/видео) |


## Пример

|       id | text                                                                                                                                                        |   comments |   likes |   reposts |   views |   attachments_count |
|---------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------:|--------:|----------:|--------:|--------------------:|
|  1946312 | На съезде с краснопутиловской на площадь победы,тетенька на джетте догнала дядю, занимают крайний правый ряд,не сильно мешают, служб нет                    |          0 |       7 |         0 |       0 |                   0 |
|  6716178 | Просто комбо...как так?две в одну припаркованную машинку...на проспекте Славы 15-13 у пятёрки                                                               |          0 |      57 |         1 |   89189 |                   0 |
|  4970956 | В 2:20 ДТП на перекрёстке Колтушского и Воейковского шоссе, две фуры. ДПС на месте. стоят до сих пор в 6.40                                                 |          0 |      38 |         1 |       0 |                   2 |
|  8993692 | На Ленинском проспекте у перекрестка с проспектом Народного Ополчения. Газель прилегла отдохнуть. Все живы! Водитель газели вылез через пассажирскую дверь! |         25 |      74 |         3 |   84722 |                   0 |
| 13483428 | На перекрёстке проспекта Юрия  Гагарина и Кузнецовской столкнулись Ауди и Рав Таёта.                                                                        |         29 |      27 |         1 |   72689 |                   2 |