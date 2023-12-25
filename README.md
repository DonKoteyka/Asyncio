# Решение задания к лекции «Asyncio»

Условия задания описаны в файле [здесь](https://github.com/netology-code/py-homeworks-web/tree/new/2.2-asyncio)

Чтобы запустить программу необходимо:

- Установить все необходимые библиотеки, для этого нужно открыть терминал по адресу директроии и выполнить:

```bash
pip install -r requirements.txt
```
- Подключить базу данных ```PostgreSQL``` путём создания файла ```.env```, необходимые переменные для подключения: ``` POSTGRES_PASSWORD, 
POSTGRES_USER, POSTGRES_DB```, если БД работает на порту отличном от ```5432``` , то необходимо откорректировать 
```models.py```.
- Далее запустить файл ```main.py``` с помощью команды 
```bash
python main.py
```
- Результаты выполнения можно увидеть в БД в таблице ```swapi_hero```