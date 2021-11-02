<h1>Парсер funko.fans</h1>

*Установка и запуск:*

1. Скачать проект, установить виртуальное окружение, установить зависимости:

    ``` bash 
        python3 -m venv venv
        source venv/bin/activate
        pip install -r requirements.txt
    ```

2. Запускать нужно файл main.py `python main.py`. Далее выбираем пункт: сбор ссылок или сбор данных по собранным ссылкам:
    ```bash
    
    Выберите действие:

    1) Собираем ссылки
    2) Парсим товары по ссылкам

    funko --> 1

    ```

3. Далее нужно ввести название выходного файла и категорию товара(обычные или эксклюзивные):
    ```bash
    Введите название выходного файла --> out_links

    Выберите категорию:
    1) Обычный каталог
    2) Эксклюзивы

    funko --> 1
    ```

4. Дожидаемся окончания работы...

5. После нужно выбрать второе действие, сбор данных по ссылкам:
    ```bash
    Выберите действие:

    1) Собираем ссылки
    2) Парсим товары по ссылкам

    funko --> 2
    ```

6. Далее нужно ввести название файла с ссылками, название выходного файла и категорию:
    ```bash
    Введите название файла с ссылками --> out_links
    Введите название выходного файла --> out_data
    Переключить на русский? (y/n) --> y

    Выберите категорию:
    1) Обычный каталог
    2) Эксклюзивы

    funko --> 1
    ```

***Дожидаемся окончания работы***