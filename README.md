# Бекенд для учебного проекта Kittygram
## Данный проект создан для того чтобы объеденить работу фронтенда и бекенда, позволяет расширить фунгкционал проекта Kittygram. 
## Kittygram учебный проект аналог Instagram в этом проекте владельцы могут постить фото, статьи и комментарии о своих питомцах. А также могут иметь подписчиков и подписываться на страницы других пользователей.

### Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/yandex-praktikum/kittygram_backend.git
```

```
cd kittygram_backend
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

* Если у вас Linux/macOS

    ```
    source env/bin/activate
    ```

* Если у вас windows

    ```
    source env/scripts/activate
    ```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```
