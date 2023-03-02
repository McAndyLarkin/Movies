# Movies

Обработка наборов данных, которые можно скачать по адресу https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset

Чтобы скопировать к себе код, в терминале зайдите в папку, где будет проект и вызовите `git clone https://github.com/McAndyLarkin/Movies.git`, все дальнейшие команды производятся изнутри новой созданной папки Movies, так что зайдите в нее.

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

Если у вас не работает pip с ошибкой типа: `zsh: command not found: pip` или подобной, значит нужно создать и активировать вирутальную среду.

На MacOS это делается так:

`python -m venv venv`

`source venv/bin/activate`

На Windows:

`venv\Scripts\activate.bat` 

После чего подгружать библиотеки

Когда библиотеки будут установлены, можно запускать jupyter notebook командой: 
`jupyter notebook`
