Привет! <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Waving%20Hand.png" alt="Waving Hand" width="45" height="45" />
Меня зовут Артем
=======================================================================================================================================

Я начинающий Python разработчик.  
На моем GitHub можно найти проекты, в которых я реализую свои идеи и обучаюсь новым технологиям.

## 💌 Контакты
* [![Mail](https://img.shields.io/badge/Email-red?logo=gmail&logoColor=white)](mailto:nirendsound@gmail.com)
* [![Telegram](https://img.shields.io/badge/Telegram-blue?logo=telegram&logoColor=white)](https://t.me/ovienrait)

## 🛠 Стек технологий
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-FF6F00?style=for-the-badge&logo=django&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-%23266999.svg?style=for-the-badge)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-303030?style=for-the-badge&logo=pytest&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI/CD-3D3D3D?style=for-the-badge&logo=git&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Linux Ubuntu](https://img.shields.io/badge/Linux_Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)

## 📂 Мои проекты

### 🍲 Кулинарная книга
Проект представляет собой онлайн-сервис для публикации рецептов в виде API приложения.

Функционал сервиса предусматривает:
- регистрацию пользователей и возможность сброса пароля
- создание публикаций с описанием рецепта и списком ингредиентов с их количеством
- добавление своих и чужих рецептов в список избранного
- возможность подписки на других авторов
- добавление рецептов в корзину с возможностью скачивания перечня ингредиентов с общим количеством в формате PDF
- фильтрацию публикаций по тегам
- настраиваемую пагинацию страниц

> Ознакомиться с проектом можно здесь:  [Кулинарный помощник](https://foodgram.3utilities.com/recipes)  
> Документация API: [ReDoc](https://foodgram.3utilities.com/api/docs/)

#### Особенности реализации
- Развёртывание проекта осуществляется посредством запуска Docker контейнеров — gateway, db, backend и frontend
- Образы для создания и запуска контейнеров запушены на DockerHub
- Запуск проекта осуществляется при помощи workflow c автодеплоем на удаленный сервер
- Реализован функционал для автоматического наполнения БД из CSV файлов при запуске

![Python](https://img.shields.io/badge/Python-3.9.13-blue)
![Django](https://img.shields.io/badge/Django-3.2.3-green)
![DjangoRestFramework](https://img.shields.io/badge/DjangoRestFramework-3.12.4-blue)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-13.10-green)
![Docker](https://img.shields.io/badge/Docker-24.0.5-blue)

**Подробнее о проекте:** 🔗 [Исходный код на GitHub](https://github.com/ovienrait/Foodgram)

---

### ✍️ Сервис отзывов на произведения
В команде реализовали REST API (DRF) для сервиса отзывов на произведения с возможностью комментирования, а также с функцией присвоения и учёта рейтинга. Для авторизации был использован Djoser (JWT-tokens) вместе с почтовым бэкендом.

Функционал сервиса предусматривает:
- аутентификацию пользователей
- публикацию пользователями текстовых отзывов
- оценку пользователями произведений по шкале от одного до десяти, формирование совокупного рейтинга для каждой работы
- комментирование оставленных пользователями отзывов
- возможность для администраторов добавлять работы, категории и жанры, организовывая свою собственную БД
- возможность управления отзывами пользователей

![Python](https://img.shields.io/badge/Python-3.9.13-blue)
![Django](https://img.shields.io/badge/Django-3.2-green)
![DjangoRestFramework](https://img.shields.io/badge/DjangoRestFramework-3.12.4-blue)

**Подробнее о проекте:** 🔗 [Исходный код на GitHub](https://github.com/ovienrait/YaMDb)

---

### 📒 Личный блог
Реализовал сервис для публикации постов и комментариев к ним с возможностью подписки на других пользователей. Сессионная авторизация. Взаимодействие с БД на основе Django ORM.
Впоследствии был произведён рефакторинг и преобразование проекта в формат REST API (DRF).

Функционал сервиса предусматривает:
- аутентификацию пользователей
- создание текстовых публикаций
- комментирование ранее созданных публикаций
- возможность подписки на других авторов
- возможность для администраторов управлять контентом пользователей

![Python](https://img.shields.io/badge/Python-3.9.13-blue)
![Django](https://img.shields.io/badge/Django-3.2.16-green)
![DjangoRestFramework](https://img.shields.io/badge/DjangoRestFramework-3.12.4-blue)

**Подробнее о проекте:** 🔗 [Исходный код на GitHub](https://github.com/ovienrait/Yatube)

---

### 🐍 Змейка
Классическая игра "Змейка", реализованная на языке Python с использованием библиотеки Pygame и принципов объектно-ориентированного программирования (ООП).  
Игрок управляет змейкой, которая растет при поедании пищи, избегая столкновений со своим телом.

**Подробнее о проекте:** 🔗 [Исходный код на GitHub](https://github.com/ovienrait/Snake)

---

## 📊 Статистика
<div>
<a href="https://github-readme-stats.vercel.app/api?username=ovienrait&hide=contribs&show_icons=true&theme=transparent&hide_title=true&hide_rank=true&include_all_commits=true">
  <img  align="left" height="130" style="margin-right: 10px" src="https://github-readme-stats.vercel.app/api?username=ovienrait&hide=contribs&show_icons=true&theme=transparent&hide_title=true&hide_rank=true&include_all_commits=true" />
</a>
<a href="https://github-readme-stats.vercel.app/api/top-langs/?username=ovienrait&layout=compact&theme=transparent&hide_title=true&hide=shell,rich+text+format">
  <img align="left" height="130" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ovienrait&layout=compact&theme=transparent&hide_title=true&hide=shell,rich+text+format" />
</a>
<a href="[https://komarev.com/ghpvc/?username=ovienrait&style=for-the-badge&label=ПРОСМОТРЫ+ПРОФИЛЯ">
  <img align="left" height="30" style="margin-top: 10px;" src="https://komarev.com/ghpvc/?username=ovienrait&style=for-the-badge&label=ПРОСМОТРЫ+ПРОФИЛЯ" />
</a>
</div>
