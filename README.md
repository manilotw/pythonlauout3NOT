# Парсер книг с сайта tululu.org
Скрпит для скачивания книг, их обложек и получения данных о них

## Как установить
Срипт написан на языке Python. Для его запуска необходимо скачать нужные библиотеки, пользуясь командой:
```
$ pip install -r requirements.txt
```

## Аргументы
В работе скрипта используются аргументы:
- start_id - id, с которого начинается скачивание (по умолчанию: 1)
- end_id - id, на котором скачивание заканчивается (по умолчанию: 10)

Аргументы явлются необязательными. Запустить скрипт можно так:
```
$ python3 tululu.py
```
Но если надо скачать книги в порядке определённых id:
```
$ python3 tululu.py 24 40
```
