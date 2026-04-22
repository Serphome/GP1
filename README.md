# Netflix EDA Project

Небольшой учебный проект по `Exploratory Data Analysis` для датасета с шоу Netflix. В ноутбуке проводится очистка данных, визуальный анализ, сравнение пользовательских рейтингов и обогащение исходного датасета внешними источниками.

## Что есть в проекте

- `GP_1_EDA_Netflix.ipynb` — основной ноутбук с анализом и визуализациями.
- `README.md` — краткое описание проекта.

## Что сделано

- удаление дубликатов и обработка пропусков;
- анализ распределения пользовательских оценок;
- анализ годов выпуска и выбросов;
- сравнение релизов 2016 и 2017 годов;
- анализ рейтинговых групп;
- добавление внешних данных из второго датасета;
- сравнение `Stranger Things` и `Breaking Bad`;
- анализ жанров и различий между рейтингами Netflix и IMDb.

## Стек

`Python`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `Jupyter Notebook` / `Google Colab`.

## Данные

Для запуска ноутбука понадобятся файлы:

- `NetflixShows.xlsx`
- `raw_titles.csv`

Источники данных:

- [1000 Netflix Shows](https://www.kaggle.com/datasets/chasewillden/netflix-shows/data)
- [The Ultimate Netflix TV Shows and Movies Dataset](https://www.kaggle.com/datasets/thedevastator/the-ultimate-netflix-tv-shows-and-movies-dataset/data?select=raw_titles.csv)


## Результат

Проект оформлен как аналитический ноутбук с графиками, промежуточными выводами и итоговыми наблюдениями по контенту Netflix, пользовательским оценкам и дополнительным метрикам из IMDb.
