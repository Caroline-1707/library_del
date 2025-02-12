# Система управления библиотекой

## Описание

Это консольное приложение для управления библиотекой книг. Приложение позволяет добавлять, удалять, искать и отображать книги. Каждая книга содержит уникальный идентификатор, название, автора, год издания и статус.

## Функционал

- **Добавление книги**: Пользователь может добавить новую книгу с указанием названия, автора и года издания.
- **Удаление книги**: Удаление книги по уникальному идентификатору.
- **Поиск книги**: Поиск книг по названию, автору или году издания.
- **Отображение всех книг**: Вывод списка всех книг с их данными.
- **Изменение статуса книги**: Изменение статуса книги на "в наличии" или "выдана".

## Использование

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/Caroline-1707/library_del.git
   cd library_del

2. Запустите приложение:
   ```bash
   python main.py

3. Следуйте инструкциям в меню для управления библиотекой.


## Тестирование

Для запуска тестов выполните команду:
```bash
python -m unittest test_library.py
```

## Структура проекта

- main.py — основной файл приложения.
- test_library.py — файл с тестами.
- library.json — файл для хранения данных о книгах.
