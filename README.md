# Змейка

Классическая «Змейка» на Python и Pygame. Собирайте красные яблоки, чтобы змейка росла. За краем поля она появляется с противоположной стороны. При столкновении с собственным телом змейка возвращается в центр и снова становится короткой.

## Установка

Для команд ниже понадобится Python 3.11. Склонируйте репозиторий и перейдите в папку проекта.

```sh
git clone https://github.com/whiterli/the_snake.git
cd the_snake
```

Создайте виртуальное окружение и установите зависимости из `requirements.txt`.

**Windows (PowerShell)**

```powershell
py -3.11 -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
```

**macOS и Linux**

```sh
python3.11 -m venv .venv
./.venv/bin/python -m pip install -r requirements.txt
```

## Запуск

Выполните команду из папки проекта.

**Windows (PowerShell)**

```powershell
.\.venv\Scripts\python.exe the_snake.py
```

**macOS и Linux**

```sh
./.venv/bin/python the_snake.py
```

## Управление

Змейка движется сама. Меняйте направление стрелками на клавиатуре.

| Клавиша | Направление |
| --- | --- |
| ↑ | Вверх |
| ↓ | Вниз |
| ← | Влево |
| → | Вправо |

Разворот на 180° запрещён. Чтобы выйти из игры, закройте окно.

