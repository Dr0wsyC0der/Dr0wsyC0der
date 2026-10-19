<div align="center">

# Привет, я Алексей Епифанов 👋

### Python Backend-разработчик · IoT / Embedded-разработчик

Разрабатываю асинхронные backend-сервисы, IoT-устройства.

[![GitHub](https://img.shields.io/badge/GitHub-Dr0wsyC0der-181717?style=for-the-badge&logo=github)](https://github.com/Dr0wsyC0der)
[![Telegram](https://img.shields.io/badge/Telegram-@aIexey4ik-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/aIexey4ik)

</div>

---

## 👨‍💻 Обо мне

- 🎓 Студент **МТУСИ**, направление **15.03.04 — Автоматизация технологических процессов и производств**
- 🐍 Основное направление — **Python Backend Development**
- ⚡ Разрабатываю API и backend-сервисы с использованием **FastAPI, SQLAlchemy, PostgreSQL, Redis и asyncio**
- 🔌 Создаю **ESP32 / IoT / Embedded** системы
- 👁 Работаю с **OpenCV, NumPy и обработкой изображений в реальном времени**
- 🏆 Финалист **Акселератора МТУСИ**
- 🧠 **Яндекс Тренировки по алгоритмам**: два сезона в топе рейтинга, есть сертификаты
- 🔬 Соавтор **зарегистрированной программы для ЭВМ**
- 📍 Москва, Россия
- 💼 Открыт к **стажировкам, частичной занятости и Junior Backend-позициям**

---

## 🚀 Избранные проекты

<table>
<tr>
<td width="50%" valign="top">

### 🏠 <a href="https://github.com/Dr0wsyC0der/clickRent">ClickRent</a>

Асинхронный backend сервиса краткосрочной аренды жилья с чатом и уведомлениями в реальном времени.

**Основные возможности**

<ul>
<li>Слои routes → services → repositories, доменные исключения</li>
<li>Защита от двойного бронирования: <code>SELECT ... FOR UPDATE</code>, soft-lock с TTL</li>
<li>WebSocket-чат, уведомления и счётчик зрителей между репликами через Redis Pub/Sub</li>
<li>Кэш с версионной инвалидацией, rate limiting, распределённый лок фоновых задач</li>
<li>JWT access / refresh с ротацией</li>
<li>pytest, ruff, CI на GitHub Actions со smoke-тестом стека</li>
<li>Gunicorn + nginx, масштабирование реплик через Docker Compose</li>
</ul>

`Python` `FastAPI` `PostgreSQL` `Redis` `SQLAlchemy 2.0` `Alembic` `WebSocket` `pytest` `Docker`

</td>
<td width="50%" valign="top">

### 🖥️ <a href="https://github.com/Dr0wsyC0der/desktop-hub">ESP Widget</a>

Настольный IoT-виджет на ESP32-S3 с локальным backend и приложением для ПК.

**Основные возможности**

<ul>
<li>Прошивка на C++ / PlatformIO, интерфейс на LVGL</li>
<li>Локальный backend на aiohttp</li>
<li>Автоматическое обнаружение устройства по UDP</li>
<li>Обмен данными в реальном времени через WebSocket</li>
<li>OTA-обновление прошивки</li>
<li>Загрузка CPU / GPU / RAM, погода, расписание транспорта</li>
</ul>

`ESP32-S3` `C++` `PlatformIO` `Python` `aiohttp` `WebSocket` `OTA`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 📊 <a href="https://github.com/Dr0wsyC0der/afin-ui-backend">AFIN</a>

Платформа моделирования и анализа бизнес-процессов с ML-прогнозом задержек и объяснениями от LLM.

**Основные возможности**

<ul>
<li>REST API на FastAPI, JWT-аутентификация</li>
<li>BPMN-модели процессов: CRUD, импорт и экспорт</li>
<li>Симуляция выполнения процесса по графу модели</li>
<li>Прогнозирование задержек с LightGBM</li>
<li>Интеграция LLM-сервиса (Qwen2) для объяснений и AI-чата</li>
<li>Три сервиса в Docker Compose</li>
</ul>

🏆 **Финалист Акселератора МТУСИ**

`Python` `FastAPI` `SQLAlchemy` `LightGBM` `LLM` `httpx` `Docker`

</td>
<td width="50%" valign="top">

### 🌊 <a href="https://github.com/Dr0wsyC0der/WaveFrontLab">WaveFrontLab</a>

Анализ интерферограмм датчика волнового фронта на основе эффекта Тальбота в реальном времени.

**Основные возможности**

<ul>
<li>Сегментация и отслеживание точек интерференционной картины</li>
<li>Автоподбор параметров фильтров через Optuna</li>
<li>3D-карта искажений волнового фронта в реальном времени</li>
<li>Графический интерфейс на PyQt6</li>
</ul>

📄 Зарегистрирован в Роспатенте как программа для ЭВМ — подробности ниже ⬇️

`Python` `OpenCV` `NumPy` `PyQt6` `Computer Vision`

</td>
</tr>

</table>

---

## 🔬 Научная и инженерная деятельность

### 🌊 WaveFrontLab

Программный комплекс для анализа интерферограмм датчика волнового фронта на основе эффекта Тальбота.

- Обработка изображений и выделение интерференционной картины
- Генерация бинарных масок
- Обнаружение и отслеживание ключевых точек
- Расчёт смещений относительно начальной конфигурации
- Визуализация искажений волнового фронта

> 🏛️ **Государственная регистрация программы для ЭВМ — Роспатент**
>
> **Свидетельство № 2026666311 · зарегистрировано 29 мая 2026 года**
>
> *«Программный комплекс анализа интерферограмм датчика волнового фронта на основе эффекта Тальбота»*

Проект также связан с научно-исследовательской работой и докладом на конференции.

`Python` `OpenCV` `NumPy` `PyQt6` `Computer Vision`

---

## 🌐 Другие проекты

### 🛒 <a href="https://github.com/Dr0wsyC0der/fastapi_ecommerce">FastAPI E-commerce API</a>

Асинхронный REST API интернет-магазина: JWT access / refresh, роли buyer / seller / admin, полнотекстовый поиск PostgreSQL, корзина и заказы, миграции Alembic.

`Python` `FastAPI` `SQLAlchemy 2.0` `PostgreSQL` `asyncpg` `Alembic`

### 🌐 <a href="https://github.com/Dr0wsyC0der/afin_web">AFIN Web</a>

Презентационный сайт платформы AFIN.

`HTML` `CSS` `JavaScript`

---

## 🧰 Технологический стек

**Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square)
![Alembic](https://img.shields.io/badge/Alembic-6BA81E?style=flat-square)
![REST API](https://img.shields.io/badge/REST_API-02569B?style=flat-square)
![asyncio](https://img.shields.io/badge/asyncio-3776AB?style=flat-square)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

**DevOps и инструменты**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Embedded / IoT**

![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![PlatformIO](https://img.shields.io/badge/PlatformIO-F5822A?style=flat-square&logo=platformio&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square)

**Computer Vision и Data**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square)

---

## 🤝 Связаться со мной

Мне интересны проекты в области **Python Backend**, **IoT / Embedded** и инженерные задачи, где программное обеспечение взаимодействует с реальным миром.

- 💬 Telegram: [@aIexey4ik](https://t.me/aIexey4ik)
- 🐙 GitHub: [Dr0wsyC0der](https://github.com/Dr0wsyC0der)

<div align="center">

### Открыт к стажировкам, Junior-позициям и частичной занятости 🚀

</div>
