<p align="center">
  <img src="public/figma/logo.svg" width="240" alt="Кинополка" />
</p>

<p align="center">Фильмы, сериалы и аниме. На своей полке.</p>

Кинополка — платформа, которая помогает выбрать, что посмотреть, с учётом ваших вкусов и предпочтений.
Собирайте фильмы и сериалы на своей полке, узнавайте, что смотрели друзья, делитесь впечатлениями и получайте персональные рекомендации от AI-помощника.

## Возможности

| Раздел           | Возможности                                                                                                                                                                                   |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Главная          | Основная информация и различные подборки                                                                                                                                                      |
| Каталог и поиск  | Найти фильм, сериал или аниме по названию, по нужным фильтрам или через рекомендации                                                                                                          |
| Фильмы и сериалы | Посмотреть трейлер и кадры, узнать, кто снимался в фильме, прочитать рецензии и оценить фильм или отдельную серию. В разделе «Где смотреть» выбрать площадку для просмотра и получить ссылку. |
| КиноГид          | Попросить AI-помощника подобрать кино под настроение или найти что-то похожее на любимый фильм.                                                                                               |
| Подборки         | Собрать фильмы на одну тему, расположить их в нужном порядке и поделиться подборкой с друзьями. Сохранить у себя коллекции редакции и других зрителей.                                        |
| Моя полка        | Отметить, что хочется посмотреть, что уже начато и что досмотрено. Сохранить любимые фильмы в избранном и вернуться к истории просмотров.                                                     |
| Профиль и друзья | Посмотреть свою статистику и добавить друзей. На их полках можно узнать, что они недавно посмотрели, какие оценки поставили и какие фильмы собрали в подборки.                                |

## Стек

| Часть проекта | Основные технологии |
| ------------- | ------------------- |
| Frontend | React, TypeScript, Vite, React Router, Mantine, Motion, Tabler Icons |
| Backend | Node.js, TypeScript, NestJS, TypeORM, PostgreSQL 17 с расширением pgvector и индексом HNSW, Docker Compose для запуска базы |
| ML-сервис | Python, FastAPI, Uvicorn, PyTorch, Sentence Transformers, BGE-M3 для эмбеддингов размерности 1024, Psycopg 3 для работы с PostgreSQL, CUDA для ускорения на GPU |

## Скриншоты

**Главная**

<p>
  <a href="docs/screens/01%20%C2%B7%20%D0%93%D0%BB%D0%B0%D0%B2%D0%BD%D0%B0%D1%8F%20%E2%80%94%20%D0%B3%D0%BE%D1%81%D1%82%D1%8C.png"><img src="docs/screens/01%20%C2%B7%20%D0%93%D0%BB%D0%B0%D0%B2%D0%BD%D0%B0%D1%8F%20%E2%80%94%20%D0%B3%D0%BE%D1%81%D1%82%D1%8C.png" width="49%" alt="Главная страница для гостя" /></a>
  <a href="docs/screens/01%20%C2%B7%20%D0%93%D0%BB%D0%B0%D0%B2%D0%BD%D0%B0%D1%8F%20%E2%80%94%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8C.png"><img src="docs/screens/01%20%C2%B7%20%D0%93%D0%BB%D0%B0%D0%B2%D0%BD%D0%B0%D1%8F%20%E2%80%94%20%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8C.png" width="49%" alt="Главная страница после входа" /></a>
</p>

**Каталог и КиноГид**

<p>
  <a href="docs/screens/02%20%C2%B7%20%D0%9A%D0%B0%D1%82%D0%B0%D0%BB%D0%BE%D0%B3%20%D0%B8%20%D1%84%D0%B8%D0%BB%D1%8C%D1%82%D1%80%D1%8B.png"><img src="docs/screens/02%20%C2%B7%20%D0%9A%D0%B0%D1%82%D0%B0%D0%BB%D0%BE%D0%B3%20%D0%B8%20%D1%84%D0%B8%D0%BB%D1%8C%D1%82%D1%80%D1%8B.png" width="49%" alt="Каталог с фильтрами" /></a>
  <a href="docs/screens/02%20%C2%B7%20%D0%9A%D0%B0%D1%82%D0%B0%D0%BB%D0%BE%D0%B3%20%D1%81%20AI.png"><img src="docs/screens/02%20%C2%B7%20%D0%9A%D0%B0%D1%82%D0%B0%D0%BB%D0%BE%D0%B3%20%D1%81%20AI.png" width="49%" alt="Каталог с открытым КиноГидом" /></a>
</p>

**Фильмы**

<p>
  <a href="docs/screens/%D0%A4%D0%B8%D0%BB%D1%8C%D0%BC%20initial.png"><img src="docs/screens/%D0%A4%D0%B8%D0%BB%D1%8C%D0%BC%20initial.png" width="49%" alt="Страница фильма" /></a>
  <a href="docs/screens/%D0%A4%D0%B8%D0%BB%D1%8C%D0%BC%20active.png"><img src="docs/screens/%D0%A4%D0%B8%D0%BB%D1%8C%D0%BC%20active.png" width="49%" alt="Страница фильма после взаимодействия с карточкой" /></a>
</p>

<p>
  <a href="docs/screens/%D0%A4%D0%B8%D0%BB%D1%8C%D0%BC%20%D1%81%D0%BC%D0%BE%D1%82%D1%80%D0%B5%D1%82%D1%8C.png"><img src="docs/screens/%D0%A4%D0%B8%D0%BB%D1%8C%D0%BC%20%D1%81%D0%BC%D0%BE%D1%82%D1%80%D0%B5%D1%82%D1%8C.png" width="49%" alt="Окно «Где смотреть» на странице фильма" /></a>
</p>

**Сериалы и серии**

<p>
  <a href="docs/screens/%D0%A1%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B%C2%B7%20%D0%9F%D0%B5%D1%80%D0%B2%D0%BE%D0%B5%20%D0%BF%D0%BE%D1%81%D0%B5%D1%89%D0%B5%D0%BD%D0%B8%D0%B5.png"><img src="docs/screens/%D0%A1%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B%C2%B7%20%D0%9F%D0%B5%D1%80%D0%B2%D0%BE%D0%B5%20%D0%BF%D0%BE%D1%81%D0%B5%D1%89%D0%B5%D0%BD%D0%B8%D0%B5.png" width="49%" alt="Страница сериала при первом посещении" /></a>
  <a href="docs/screens/05%20%C2%B7%20%D0%A1%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B%2C%20%D0%BF%D1%80%D0%BE%D0%B4%D0%BE%D0%BB%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5.png"><img src="docs/screens/05%20%C2%B7%20%D0%A1%D0%B5%D1%80%D0%B8%D0%B0%D0%BB%D1%8B%2C%20%D0%BF%D1%80%D0%BE%D0%B4%D0%BE%D0%BB%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5.png" width="49%" alt="Страница сериала в режиме продолжения просмотра" /></a>
</p>

<p>
  <a href="docs/screens/06%20%C2%B7%20%D0%A1%D1%82%D1%80%D0%B0%D0%BD%D0%B8%D1%86%D0%B0%20%D1%81%D0%B5%D1%80%D0%B8%D0%B8.png"><img src="docs/screens/06%20%C2%B7%20%D0%A1%D1%82%D1%80%D0%B0%D0%BD%D0%B8%D1%86%D0%B0%20%D1%81%D0%B5%D1%80%D0%B8%D0%B8.png" width="49%" alt="Карточка отдельной серии" /></a>
</p>

**Подборки**

<p>
  <a href="docs/screens/08%20%C2%B7%20%D0%9F%D0%BE%D0%B4%D0%B1%D0%BE%D1%80%D0%BA%D0%B8.png"><img src="docs/screens/08%20%C2%B7%20%D0%9F%D0%BE%D0%B4%D0%B1%D0%BE%D1%80%D0%BA%D0%B8.png" width="49%" alt="Список подборок с фильтрами" /></a>
  <a href="docs/screens/09%20%C2%B7%20%D0%A1%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BF%D0%BE%D0%B4%D0%B1%D0%BE%D1%80%D0%BA%D0%B8.png"><img src="docs/screens/09%20%C2%B7%20%D0%A1%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BF%D0%BE%D0%B4%D0%B1%D0%BE%D1%80%D0%BA%D0%B8.png" width="49%" alt="Редактор новой подборки" /></a>
</p>

<p>
  <a href="docs/screens/09%20%C2%B7%20%D0%A1%D1%82%D1%80%D0%B0%D0%BD%D0%B8%D1%86%D0%B0%20%D0%BF%D0%BE%D0%B4%D0%B1%D0%BE%D1%80%D0%BA%D0%B8.png"><img src="docs/screens/09%20%C2%B7%20%D0%A1%D1%82%D1%80%D0%B0%D0%BD%D0%B8%D1%86%D0%B0%20%D0%BF%D0%BE%D0%B4%D0%B1%D0%BE%D1%80%D0%BA%D0%B8.png" width="49%" alt="Страница подборки со списком фильмов" /></a>
  <a href="docs/screens/%D0%9F%D0%BE%D0%B4%D0%B1%D0%BE%D1%80%D0%BA%D0%B8%20%D0%90%D0%BD%D0%BD%D1%8B%20%D0%9A.%20%C2%B7%20%D0%9F%D0%BE%D0%BB%D0%BA%D0%B0.png"><img src="docs/screens/%D0%9F%D0%BE%D0%B4%D0%B1%D0%BE%D1%80%D0%BA%D0%B8%20%D0%90%D0%BD%D0%BD%D1%8B%20%D0%9A.%20%C2%B7%20%D0%9F%D0%BE%D0%BB%D0%BA%D0%B0.png" width="49%" alt="Подборки Анны К." /></a>
</p>

**Профили и полки**

<p>
  <a href="docs/screens/12%20%C2%B7%20%D0%9C%D0%BE%D0%B9%20%D0%BF%D1%80%D0%BE%D1%84%D0%B8%D0%BB%D1%8C.png"><img src="docs/screens/12%20%C2%B7%20%D0%9C%D0%BE%D0%B9%20%D0%BF%D1%80%D0%BE%D1%84%D0%B8%D0%BB%D1%8C.png" width="49%" alt="Личный профиль со статистикой" /></a>
  <a href="docs/screens/12%20%C2%B7%20%D0%A7%D1%83%D0%B6%D0%BE%D0%B9%20%D0%BF%D1%80%D0%BE%D1%84%D0%B8%D0%BB%D1%8C.png"><img src="docs/screens/12%20%C2%B7%20%D0%A7%D1%83%D0%B6%D0%BE%D0%B9%20%D0%BF%D1%80%D0%BE%D1%84%D0%B8%D0%BB%D1%8C.png" width="49%" alt="Публичный профиль другого зрителя" /></a>
</p>

<p>
  <a href="docs/screens/13%20%C2%B7%D0%9C%D0%BE%D1%8F%20%D0%BF%D0%BE%D0%BB%D0%BA%D0%B0.png"><img src="docs/screens/13%20%C2%B7%D0%9C%D0%BE%D1%8F%20%D0%BF%D0%BE%D0%BB%D0%BA%D0%B0.png" width="49%" alt="Моя полка и фильтры по статусу" /></a>
  <a href="docs/screens/13%20%C2%B7%20%D0%A7%D1%83%D0%B6%D0%B0%D1%8F%20%D0%BF%D0%BE%D0%BB%D0%BA%D0%B0.png"><img src="docs/screens/13%20%C2%B7%20%D0%A7%D1%83%D0%B6%D0%B0%D1%8F%20%D0%BF%D0%BE%D0%BB%D0%BA%D0%B0.png" width="49%" alt="Полка другого зрителя" /></a>
</p>

<p>
  <a href="docs/screens/13%20%D0%98%D1%81%D1%82%D0%BE%D1%80%D0%B8%D1%8F%20%D0%BF%D1%80%D0%BE%D1%81%D0%BC%D0%BE%D1%82%D1%80%D0%B0.png"><img src="docs/screens/13%20%D0%98%D1%81%D1%82%D0%BE%D1%80%D0%B8%D1%8F%20%D0%BF%D1%80%D0%BE%D1%81%D0%BC%D0%BE%D1%82%D1%80%D0%B0.png" width="49%" alt="История просмотра" /></a>
  <a href="docs/screens/17%20%C2%B7%20%D0%A0%D0%B5%D0%B4%D0%B0%D0%BA%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BF%D1%80%D0%BE%D1%84%D0%B8%D0%BB%D1%8F.png"><img src="docs/screens/17%20%C2%B7%20%D0%A0%D0%B5%D0%B4%D0%B0%D0%BA%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BF%D1%80%D0%BE%D1%84%D0%B8%D0%BB%D1%8F.png" width="49%" alt="Форма редактирования профиля" /></a>
</p>

**Вход, регистрация и служебные страницы**

<p>
  <a href="docs/screens/18%20%C2%B7%20%D0%92%D1%85%D0%BE%D0%B4.png"><img src="docs/screens/18%20%C2%B7%20%D0%92%D1%85%D0%BE%D0%B4.png" width="49%" alt="Форма входа" /></a>
  <a href="docs/screens/19%20%C2%B7%20%D0%A0%D0%B5%D0%B3%D0%B8%D1%81%D1%82%D1%80%D0%B0%D1%86%D0%B8%D1%8F.png"><img src="docs/screens/19%20%C2%B7%20%D0%A0%D0%B5%D0%B3%D0%B8%D1%81%D1%82%D1%80%D0%B0%D1%86%D0%B8%D1%8F.png" width="49%" alt="Форма регистрации" /></a>
</p>

<p>
  <a href="docs/screens/23%20%C2%B7%20%D0%A2%D1%80%D0%B5%D0%B1%D1%83%D0%B5%D1%82%D1%81%D1%8F%20%D0%B2%D1%85%D0%BE%D0%B4.png"><img src="docs/screens/23%20%C2%B7%20%D0%A2%D1%80%D0%B5%D0%B1%D1%83%D0%B5%D1%82%D1%81%D1%8F%20%D0%B2%D1%85%D0%BE%D0%B4.png" width="49%" alt="Страница с предложением войти" /></a>
  <a href="docs/screens/24%20%C2%B7%20%D0%A1%D1%82%D1%80%D0%B0%D0%BD%D0%B8%D1%86%D0%B0%20404.png"><img src="docs/screens/24%20%C2%B7%20%D0%A1%D1%82%D1%80%D0%B0%D0%BD%D0%B8%D1%86%D0%B0%20404.png" width="49%" alt="Страница ошибки 404" /></a>
</p>

## Запуск

### Веб-приложение

```bash
npm install
npm run dev
```
