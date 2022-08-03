# How it`s work:

Главный исполняемый скрипт `main.py`

Главное меню в файле `menu.py`

Логика работы в файле `controllers.py`

---
>***ВНИМАНИЕ!!!***
>
>*Некоторые функции используют операторы соответствия match/case.*
>
>Данные операторы поддерживаются **python версии не ниже 3.10**
---

После запуска, данные из файла `todo.csv` считываются в словарь `all_task`.

Дальнейшая работа происходит с этим словарём.

Функции в контроллере принимают словарь в качестве аргумента и производят необходимые действия.

---

Структура словаря

```
{
1: {'is_done': False,
    'task': 'Task description'},
2: {'is_done': True,
    'task': 'Task description'}
}
```

Для сохранения изменений надо выбрать соответствующий пункт меню перед выходом из программы.
