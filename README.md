# Movies

Обработка наборов данных, которые можно скачать по адресу https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset

Пока что представлена обработка только следующих наборов: 
`credits.csv`
`keywords.csv`
`movies_metadata.csv`
`ratings_small.csv`

Чтобы запустить код в notebook нужно поместить указанные сеты в папку (создав ее) 'the-movies-dataset' в корне проекта
или изменить пути к наборам данных в первой ячейке notebook `movies.ipynb`.

Как только все необходимые наборы данных будут помещены в доступное место, 
нужно подгрузить библиотеки из файла requrements.txt командой
`pip install -r requirements.txt`

Когда библиотеки будут установлены, можно запускать jupyter notebook командой: 
`jupyter notebook`