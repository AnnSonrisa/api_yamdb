![example workflow](https://github.com/AnnSonrisa/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg) 

**Описание проекта YaMDb:**

1) Проект YaMDb собирает отзывы (Review)
пользователей на произведения (Titles). 
2) Категории (Category) произведений могут быть следующими: 
«Книги», «Фильмы», «Музыка». 
Список категорий может быть 
расширен администратором.
3) Произведению может быть присвоен жанр (Genre) 
из списка предустановленных. 
Новые жанры может создавать только администратор.
4) Пользователи оставляют к произведениям текстовые отзывы 
(Review) и ставят произведению оценку в диапазоне 
от одного до десяти (целое число); 
из пользовательских оценок формируется 
усреднённая оценка произведения — рейтинг 
(целое число). 
На одно произведение пользователь может 
оставить только один отзыв.
____
# Как запустить проект:
1) Клонировать репозиторий и перейти в него в командной строке:

`git clone https://github.com/AnnSonrisa/api_yamdb`

2) Cоздать и активировать виртуальное окружение:

`python -m venv venv`

`source venv/Scripts/activate`

3) Установить зависимости из файла requirements.txt:

`python -m pip install --upgrade pip`

`pip install -r requirements.txt`

4) Выполнить миграции:

`python3 manage.py migrate`

## **Разработчики группового проекта:**
- Ivashinin Ivan https://github.com/viserdi
- Britvin Pavel  https://github.com/pashwf
- Slonova Anna   https://github.com/AnnSonrisa
