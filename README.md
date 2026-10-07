# lab02-git
Набір невеликих Python-утиліт, створений у межах лабораторної роботи 02 "Налаштування середовища розробки та Git workflow".

## Команда

| Учасник | GitHub | Роль | Модуль |
|---|---|---|---|
| Биков Олександр | IceStormSS | Team lead/Dev | calculator.py |
| Мазурик Матвтвій | matvii1212 | Developer | converter.py |

## Модулі

- `calculator.py` — додавання, віднімання, множення та ділення (з перевіркою ділення на нуль);
- `converter.py` — конвертація одиниць: км і милі, градуси Цельсія і Фаренгейта.

## Встановлення та запуск

1. Встановити Python з python.org.
2. Склонувати репозиторій: `git clone git@github.com:IceStormSS/lab02-git.git`
3. Перейти в папку проєкту: `cd lab02-git`
4. Запустити потрібний модуль: `python calculator.py` або `python converter.py`

## Git workflow

Проєкт ведеться за схемою Feature Branch Workflow: кожна функція розробляється в окремій гілці та потрапляє в `main` через Pull Request після ревʼю іншого учасника.

Повідомлення комітів написані за специфікацією Conventional Commits.
