# Better Than Fucking Script (BTFS)

## Содержание
1. [Проект](#проект)
   - [Краткое описание](#краткое-описание)
   - [История](#история)
   - [Особенности](#особенности)
   - [Недостатки](#недостатки)
   - [Задачи проекта](#задачи-проекта)
   - [Дорожная карта](#дорожная-карта)
   - [Техническая часть](#техническая-часть)
   - [Ответы на вопросы](#ответы-на-вопросы)
2. [Ссылки](#ссылки)
3. [Благодарности](#благодарности)

## Проект

### Краткое описание
Better Than Fucking Script (BTFS) - это комплексный фреймворк, предоставляющий инструменты для разработки собственных игровых режимов в игре Superfighters Deluxe. Он позволяет создавать персонажей, навыки, команды чата и другие игровые элементы без необходимости писать код с нуля.

### История
Проект начался в 2022 году как расширение для режима Shootout Mode. Со временем он превратился в независимый фреймворк. В 2023-2024 годах разработка приостановилась, но в конце 2024 года возобновилась с целью завершения проекта.

### Особенности
- Создание новых игровых режимов и комплексных скриптов
- Готовые компоненты для персонажей, навыков и команд чата
- Сборка вне игры с использованием MSBuild
- Контейнер для нескольких режимов с возможностью переключения

### Недостатки
1. Плохая организация кода
2. Отсутствие оптимизации
3. Несогласованный стиль кодирования
4. Отсутствие шаблонов проектирования
5. Проблемы с контролем версий

### Задачи проекта
1. Реализация универсальных компонентов
2. Создание единой системы для скриптов
3. Разработка визуального редактора "BTFS: Creative Studio"

### Дорожная карта
Проект находится в разработке. Планируется:
- Документирование
- Оптимизация кода
- Унификация стиля
- Реализация новых компонентов (Item, CustomGameover, Animation)

### Техническая часть
#### Основные компоненты
| Компонент      | Описание |
|---------------|----------|
| Callbacks     | Система управления событиями |
| Character     | Создание персонажей |
| Command       | Чат-команды |
| CommandShell  | Менеджер команд |
| Game          | Расширение GameScriptInterface |
| Global        | Утилиты и глобальные переменные |
| Mode          | Базовый класс режимов |
| Plugin        | Интеграция сторонних скриптов |
| Skill         | Навыки персонажей |

### Ответы на вопросы
#### Для чего это нужно?
Для расширения возможностей игры Superfighters Deluxe через Script API.

#### Что такое комплексный скрипт?
Скрипт, объединяющий несколько компонентов для создания сложного функционала.

#### Какие режимы можно создать?
- Режимы на основе персонажей
- RPG
- Турнирные режимы

## Ссылки
- [Superfighters Deluxe](https://www.mythologicinteractive.com)
- [Script API](https://juansero29.github.io/SFDScripts/index.html)

## Благодарности
Особая благодарность Guldrelokk за вдохновение и поддержку.
