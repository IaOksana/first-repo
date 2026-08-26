# Practical Repository Index

Практический индекс публичных репозиториев аккаунта [IaOksana](https://github.com/IaOksana). Составлен по структуре, README/описаниям, зависимостям и ключевому исходному коду каждого репозитория.

> Ищете решение конкретной задачи? Откройте [TASK_INDEX.md](TASK_INDEX.md) — там обратный индекс «задача → подходящие файлы и репозитории».

> **Security note:** в публичных `goit-de-hw-05/configs.py` и `goit-de-hw-06/configs.py` обнаружены учётные данные Kafka в открытом виде. Их следует немедленно отозвать/заменить, перенести в переменные окружения и удалить из Git history. Тестовые пароли БД в Docker Compose также лучше вынести в `.env`.

| Категория | Репозиторий | Понятное описание / что делает | Основные технологии и библиотеки | Ключевые файлы | Что можно переиспользовать | Типичные задачи |
|---|---|---|---|---|---|---|
| Python Core | [goit-pycore-hw-03](https://github.com/IaOksana/goit-pycore-hw-03) | Набор утилит: разница дат, лотерейные числа, нормализация телефонов, ближайшие дни рождения. | Python; `datetime`, `random`, `re` | `task1.py`–`task4.py` | Валидация и очистка контактных данных, календарные напоминания, генерация уникальных выборок. | CLI/CRM-утилиты, подготовка данных, планировщики поздравлений. |
| Python Core | [goit-pycore-hw-04-1](https://github.com/IaOksana/goit-pycore-hw-04-1) | Работа с текстовыми файлами, обход каталогов и простой консольный контакт-бот. | Python; `pathlib`, `sys`, `re`, Colorama | `task_1/main.py`, `task_2/main.py`, `task_3/main.py`, `task_4/main.py`, `requirements.txt` | Парсеры файлов, рекурсивный просмотр дерева каталогов, обработчик команд CRUD. | Импорт данных из файлов, файловые CLI-инструменты, прототип адресной книги. |
| Python Core | [goit-pycore-hw-05](https://github.com/IaOksana/goit-pycore-hw-05) | Замыкания и кеширование Fibonacci, генераторы чисел из текста, анализ логов, бот с обработкой ошибок. | Python; `typing`, `collections`, `re`, `sys` | `task_1/main.py`–`task_4/main.py`, `task_3/processing.py` | Мемоизация, генератор числовых значений, подсчёт и фильтрация логов, декоратор ошибок. | Анализ журналов, парсинг финансовых чисел, устойчивые консольные команды. |
| Python Core | [goit-pycore-hw-06](https://github.com/IaOksana/goit-pycore-hw-06) | Объектная модель адресной книги с именами, телефонами и записями. | Python; OOP, `collections.UserDict`, `re` | `main.py` | Классы `Field`, `Name`, `Phone`, `Record`, `AddressBook` и проверка номера. | Основа CRM/контакт-менеджера, обучение композиции и валидации моделей. |
| Python Core | [goit-pycore-hw-07](https://github.com/IaOksana/goit-pycore-hw-07) | Расширенная адресная книга: телефоны, дни рождения, команды CLI и прогноз поздравлений. | Python; OOP, `UserDict`, `datetime`, `re` | `task_1_2/address_book.py`, `task_1_2/main.py` | Готовая доменная модель контактов, birthday-логика, command parser и декоратор ошибок. | Контакт-бот, напоминания о днях рождения, CLI CRUD. |
| Python Core | [goit-pycore-hw-08](https://github.com/IaOksana/goit-pycore-hw-08) | Адресная книга с сохранением состояния между запусками. | Python; OOP, `pickle`, `datetime`, `re`, `UserDict` | `address_book.py`, `main.py` | Сериализация/восстановление книги плюс функциональность HW-07. | Локальный персональный органайзер, прототип приложения с файловым хранилищем. |
| Algorithms | [goit-algo-hw-02](https://github.com/IaOksana/goit-algo-hw-02) | Практика структур данных: очередь заявок, проверка палиндрома и симметрии скобок. | Python; `queue`, `collections.deque`, `random` | `main.py`, `task1.py`, `task2.py`, `task3.py` | Модель FIFO-обработки, deque-палиндром, стековая проверка разделителей. | Очереди сервисных заявок, проверка выражений, интервью по структурам данных. |
| Algorithms | [goit-algo-hw-03](https://github.com/IaOksana/goit-algo-hw-03) | Рекурсивные задачи: сортировка файлов по расширениям и фрактал Коха; Ханойская башня оставлена TODO. | Python; recursion, `pathlib`, `shutil`, `argparse`, `turtle` | `task1.py`, `task2.py`, `task3.py`, `hw_description.txt` | Рекурсивный обход/копирование файлов и генератор фрактала. | Организация архивов, обучение рекурсии, процедурная графика. |
| Algorithms | [goit-algo-hw-04](https://github.com/IaOksana/goit-algo-hw-04) | Экспериментальное сравнение insertion sort, merge sort и встроенного Timsort. | Python; `timeit`, `random` | `task.py`, `benchmark_results.md` | Реализации сортировок и каркас воспроизводимого бенчмарка. | Выбор алгоритма сортировки, performance-тесты, демонстрация сложности. |
| Algorithms | [goit-algo-hw-05](https://github.com/IaOksana/goit-algo-hw-05) | Хеш-таблица, бинарный поиск верхней границы и сравнение трёх алгоритмов поиска подстроки. | Python; `timeit`, `chardet`; Boyer–Moore, KMP, Rabin–Karp | `task1.py`, `task2.py`, `task3.py`, `boyer_moore.py`, `kmp.py`, `rabin_karp.py` | Хеш-таблица с delete, binary search, текстовый search benchmark. | Поиск по отсортированным данным и текстам, сравнение алгоритмов, интервью. |
| Algorithms | [goit-algo-hw-06](https://github.com/IaOksana/goit-algo-hw-06) | Модель графа, визуализация, DFS/BFS и кратчайшие пути Дейкстры. | Python; NetworkX, Matplotlib | `graph_utils.py`, `task1.py`, `task2.py`, `task3.py`, `readme.md` | Создание/рисование графа, обходы и реализация Dijkstra. | Маршрутизация, анализ сетей, транспортные/социальные графы. |
| Algorithms | [goit-algo-hw-07](https://github.com/IaOksana/goit-algo-hw-07) | AVL-дерево и операции поиска максимума, минимума и суммы значений. | Python; AVL/BST, recursion | `avl_tree.py`, `visual_tree.py`, `task1.py`–`task3.py` | Сбалансированное дерево, вращения, обходы и визуализация. | Индексирование, ordered structures, обучение деревьям и интервью. |
| Algorithms | [goit-algo-hw-08](https://github.com/IaOksana/goit-algo-hw-08) | Оптимальное объединение кабелей с минимальной суммарной стоимостью. | Python; greedy algorithm, `heapq` | `task.py`, `homeworc_desc.txt` | Мини-куча и шаблон optimal merge/Huffman-like cost. | Оптимальное пакетное объединение, планирование с приоритетами, интервью. |
| Algorithms | [goit-algo-hw-09](https://github.com/IaOksana/goit-algo-hw-09) | Сравнение жадного алгоритма и динамического программирования для выдачи сдачи. | Python; dynamic programming, greedy, `timeit` | `task.py`, `readme.md` | Два решателя coin change и их performance-бенчмарк. | Кассовые системы, размен ресурсов, выбор между greedy и DP. |
| Algorithms | [goit-algo-hw-10](https://github.com/IaOksana/goit-algo-hw-10) | Линейная оптимизация производства и вычисление интеграла методом Монте-Карло. | Python; PuLP, SciPy, NumPy, Matplotlib, `random` | `task1.py`, `task2.py`, `readme.md` | LP-модель ограниченных ресурсов и Monte Carlo estimator с проверкой через `quad`. | Оптимизация product mix, сценарный анализ, численные эксперименты. |
| Final Project | [goit-algo-fp](https://github.com/IaOksana/goit-algo-fp) | Итоговый набор алгоритмических задач: linked list, фрактал, Dijkstra, визуализация деревьев, heap, greedy/DP и Monte Carlo. | Python; NetworkX, Matplotlib, `heapq`, `turtle`, `random` | `task1/linked_list.py`, `task2.py`, `task3/`, `task4.py`–`task7.py`, `readme.md` | Коллекция самостоятельных реализаций алгоритмов и визуализаций. | Портфолио алгоритмов, подготовка к интервью, учебные демонстрации. |
| Computer Science | [goit-cs-hw-01](https://github.com/IaOksana/goit-cs-hw-01) | Арифметический интерпретатор и калькулятор, включая вариант на Assembly. | Python AST/lexer/parser; Assembly | `interpreter.py`, `calc.asm`, `calc.com` | Lexer, parser, AST, visitor/interpreter и пример низкоуровневого калькулятора. | DSL и парсеры выражений, обучение компиляторам и архитектуре компьютеров. |
| Computer Science | [goit-cs-hw-02](https://github.com/IaOksana/goit-cs-hw-02) | Контейнеризированный FastAPI health-check для PostgreSQL; также Redis в Compose. | Python, FastAPI, SQLAlchemy, PostgreSQL, Redis, Docker Compose, Jinja2 | `Computer-Systems-hw02/main.py`, `conf/db.py`, `Dockerfile`, `docker-compose.yaml` | Шаблон API + DB dependency + контейнерное окружение и health endpoint. | Стартовый web-service, проверка БД, локальная многосервисная разработка. |
| Computer Science | [goit-cs-hw-03](https://github.com/IaOksana/goit-cs-hw-03) | Два CLI-приложения для PostgreSQL task manager и MongoDB-каталога котов. | Python; psycopg2, PyMongo, Faker, PrettyTable, prompt_toolkit | `task1/main.py`, `task1/task_1.sql`, `task1/seed.py`, `task2/main.py` | SQL-схема/seed/CRUD-запросы и MongoDB CRUD CLI. | Админские CLI, сравнение реляционного и документного хранения, прототип task manager. |
| Computer Science | [goit-cs-hw-04](https://github.com/IaOksana/goit-cs-hw-04) | Сравнение многопоточного и многопроцессного поиска ключевых слов по файлам. | Python; `threading`, `multiprocessing`, queues, logging, Faker | `main_threads.py`, `main_processes.py`, `seed_txt.py` | Две параллельные архитектуры поиска и генератор тестового корпуса. | Пакетный поиск по документам, concurrency benchmarks, CPU/I/O experiments. |
| Computer Science | [goit-cs-hw-05](https://github.com/IaOksana/goit-cs-hw-05) | Асинхронная сортировка файлов и MapReduce-анализ частотности слов из URL. | Python; asyncio, aiopath, aioshutil, requests, concurrent.futures, Matplotlib | `task_1.py`, `task_2.py` | Async file organizer и локальная MapReduce pipeline с графиком top words. | Массовая обработка файлов, анализ текстов, демонстрация async и MapReduce. |
| Computer Science | [goit-cs-hw-06](https://github.com/IaOksana/goit-cs-hw-06) | Веб-приложение без фреймворка: HTTP-сервер, socket-сервер формы и MongoDB. | Python; sockets, HTTPServer, threading/multiprocessing, PyMongo, Docker | `main.py`, `docker-compose.yaml`, HTML/CSS templates | Низкоуровневый HTTP routing, приём сообщений по сокету, сохранение в MongoDB. | Обучение сетям, прототип локального form collector, понимание web stack. |
| Python Web | [goit-pythonweb-hw-01](https://github.com/IaOksana/goit-pythonweb-hw-01) | Учебные примеры Factory pattern и SOLID на транспорте и библиотеке книг. | Python 3.12, Poetry, ABC, logging; Black | `src/goit_pythonweb_hw_01/task_1.py`, `task_2.py`, `log.py`, `pyproject.toml` | Abstract Factory и разделённые интерфейсы/ответственности для library CLI. | Проектирование расширяемых сервисов, рефакторинг legacy-кода, обучение SOLID. |
| Python Web | [goit-pythonweb-hw-02](https://github.com/IaOksana/goit-pythonweb-hw-02) | Dockerized FastAPI-приложение с шаблонами и проверкой PostgreSQL. | Python, FastAPI, Uvicorn, SQLAlchemy, PostgreSQL, Jinja2, Docker Compose | `main.py`, `conf/db.py`, `templates/`, `static/`, `Dockerfile`, `docker-compose.yml` | Каркас FastAPI с templates/static, DB session dependency и health check. | MVP веб-сервиса, контейнерная разработка, readiness/health endpoints. |
| Databases | [goit-rdb-hw-02](https://github.com/IaOksana/goit-rdb-hw-02) | ER-модель реляционной базы данных в формате MySQL Workbench. | MySQL Workbench; relational modeling | `goit-rdb-hw-02.mwb`, screenshots archive | Схема, которую можно открыть и развивать в Workbench. | Проектирование ERD, нормализация, подготовка DDL. |
| Databases | [goit-rdb-hw-03](https://github.com/IaOksana/goit-rdb-hw-03) | Базовые аналитические SQL-запросы по учебной торговой базе. | MySQL; SELECT, DISTINCT, aggregate functions, filtering | `goit-rdb-hw-03.sql`, `goit-rdb-hw-03.txt` | Набор запросов выборки, AVG/MAX/MIN и фильтрации. | Ad-hoc анализ продаж/товаров, SQL-шпаргалка для базовых запросов. |
| Databases | [goit-rdb-hw-04](https://github.com/IaOksana/goit-rdb-hw-04) | DDL-модель библиотечной системы и запросы к связанным таблицам. | MySQL; DDL, PK/FK, JOIN | `goit-rdb-hw-04.sql`, `goit-rdb-hw-04.txt` | Готовая схема LibraryManagement: authors, genres, books, users, borrowed_books. | Каталог библиотеки, учебный CRUD backend, демонстрация связей и JOIN. |
| Databases | [goit-rdb-hw-05](https://github.com/IaOksana/goit-rdb-hw-05) | SQL-практика с коррелированными подзапросами, фильтрацией и JOIN. | MySQL; subqueries, JOIN, aggregation | `goit-rdb-hw-05.sql`, `goit-rdb-hw-05.txt` | Примеры альтернативных форм запросов к orders/order_details. | Отчёты по заказам, оптимизация/сравнение SQL-подходов. |
| Databases | [got-rdb-hw-07](https://github.com/IaOksana/got-rdb-hw-07) | Работа с датами, интервалами, Unix time и пользовательской SQL-функцией. | MySQL; date functions, scalar functions | `goit-rdb-hw-07.sql`, `goit-rdb-hw-07.txt` | Рецепты преобразования дат и вычисляемых функций. | Временные отчёты, ETL-преобразования дат, reusable SQL snippets. |
| Final Project | [got-rdb-fp](https://github.com/IaOksana/got-rdb-fp) | Проект базы `pandemic`: нормализация данных об инфекционных заболеваниях и аналитика. | MySQL; schema design, normalization, date arithmetic, user-defined functions | `goit-rdb-fp.sql`, `goit-rdb-fp.txt` | Нормализованная схема и запросы расчёта средних/минимальных/максимальных показателей. | Аналитика эпидемиологических временных рядов, портфолио SQL/нормализации. |
| Data Engineering | [goit-de-hw-03](https://github.com/IaOksana/goit-de-hw-03) | Анализ данных и оконные вычисления в PySpark. | Python, PySpark SQL, SparkSession, Window functions | `goit-de-hw-03.py` | Каркас локальной Spark-сессии и DataFrame transformations. | Распределённая очистка/агрегация данных, batch ETL, оконная аналитика. |
| Data Engineering | [goit-de-hw-04](https://github.com/IaOksana/goit-de-hw-04) | Отчёт по заданию Data Engineering без исходного кода в репозитории. | Документ/PDF; технологии следует уточнять по содержимому отчёта | `ДЗ4_ЯщукОксана.docx`, `ДЗ4_ЯщукОксана.pdf` | Документация и результаты выполнения; код для прямого reuse отсутствует. | Подтверждение выполненной работы; источник требований/скриншотов для восстановления проекта. |
| Data Engineering | [goit-de-hw-05](https://github.com/IaOksana/goit-de-hw-05) | Kafka pipeline датчиков: генерация температуры/влажности, обработка порогов и alert topics. | Python, kafka-python, Kafka, JSON, SASL | `admin_part.py`, `producer_part.py`, `consumer_part.py`, `listener_part.py`, `configs.py` | Producer/consumer/admin шаблоны, topic setup и alert-routing. | IoT telemetry, event-driven alerts, прототип потокового мониторинга. |
| Data Engineering | [goit-de-hw-06](https://github.com/IaOksana/goit-de-hw-06) | Streaming pipeline Kafka → Spark Structured Streaming с окнами, watermark и конфигурируемыми алертами. | Python, Kafka, PySpark Structured Streaming, CSV | `producer_part.py`, `consumer_part.py`, `listener_part.py`, `alerts_conditions.csv` | Sliding-window aggregation, watermarking, правила алертов и Kafka sinks. | Real-time sensor analytics, мониторинг телеметрии, потоковые KPI/alerts. |
| Airflow | [airflow_sandbox](https://github.com/IaOksana/airflow_sandbox) | Большой учебный sandbox Airflow с Docker, MySQL и набором DAG; содержит также примеры Spark pipeline. | Apache Airflow 2.8, Python, Docker Compose, MySQL provider, SparkSubmitOperator | `docker-compose.yaml`, `requirements.txt`, `dags/`, `.github/workflows/updateDaxs.yml` | Локальная Airflow-среда, DAG templates, sensors/operators и orchestration examples. | Оркестрация ETL, расписания batch jobs, тестирование DAG и Spark jobs. |
| Airflow | [goit-de-hw-07](https://github.com/IaOksana/goit-de-hw-07) | Airflow DAG с SQL sensor, MySQL tasks, branching и trigger rules. | Python, Apache Airflow, MySQL operators/sensors | `oi_hw.py` | Шаблон DAG с ожиданием таблицы, ветвлением и управлением финальным статусом. | Оркестрация проверок БД, условные pipeline, medal-count workflow. |
| Final Project | [goit-de-fp](https://github.com/IaOksana/goit-de-fp) | Финальный Data Engineering проект: спортивный streaming pipeline и многоступенчатый batch ETL под Airflow. | Python, Kafka, PySpark/Structured Streaming, MySQL, Airflow, SparkSubmitOperator | `fp1_*`, `fp2_landing_to_bronze.py`, `fp2_bronze_to_silver.py`, `fp2_silver_to_gold.py`, `fp2_project_solution.py` | Kafka/Spark feature pipeline и medallion layers landing→bronze→silver→gold. | ML feature generation для спортивных данных, lakehouse-style ETL, production-like orchestration. |
| Deep Learning | [DeepLearning](https://github.com/IaOksana/DeepLearning) | Набор Jupyter notebooks по ML/DL, включая sentiment analysis и итоговый проект. | Python, Jupyter, библиотеки ML/DL определяются внутри notebooks | `IO_Sentiment.ipynb`, `dz_topic_4/6/8/10/12_*.ipynb`, `final_project_*.ipynb` | Экспериментальные notebooks, preprocessing/training/evaluation workflow и sentiment baseline. | Исследование моделей, EDA, обучение/оценка нейросетей, демонстрация ML-портфолио. |
| Другое | [first-repo](https://github.com/IaOksana/first-repo) | Минимальный тестовый репозиторий для проверки Git/GitHub. | Python | `main.py` | Простой smoke test окружения и Git workflow. | Проверка clone/commit/push; теперь также центральный каталог проектов. |

## Colab / Jupyter notebooks на Google Drive

В приватной папке `Colab Notebooks` найдено **40 файлов `.ipynb`**. Ниже перечислены все названия; содержимое файлов в публичный GitHub не переносилось.

| Группа | Файл | Статус | Изменён |
|---|---|---|---|
| Defense CV | `drones_test.ipynb` | Ноутбук | 2026-05-20 |
| Defense CV | `birds_test.ipynb` | Ноутбук | 2026-05-20 |
| ML / Deep Learning | `Оптимізація_гіперпараметрів.ipynb` | Ноутбук | 2025-09-02 |
| ML / Deep Learning | `Copy of Tema 3_4_LogRegr_Pytorch_M.ipynb` | Копия | 2025-07-19 |
| ML / Deep Learning | `Copy of Tema 3_4_LogRegr_Pytorch_M.ipynb` | Копия | 2025-07-19 |
| Numerical Methods | `ДЗ8_ЯщукОксана_ЧисельніМетоди.ipynb` | Ноутбук | 2025-07-18 |
| ML / Deep Learning | `mod_05_topic_09_ensembles.ipynb` | Ноутбук | 2025-07-18 |
| ML / Deep Learning | `Module_7_Lecture_14_Class.ipynb` | Ноутбук | 2025-07-13 |
| ML / Deep Learning | `Module_1_Lecture_2_Class.ipynb` | Ноутбук | 2025-07-13 |
| ML / Deep Learning | `Module_1_Lecture_2_Class.ipynb` | Ноутбук | 2025-07-13 |
| Учебные Jupyter notebooks | `Untitled1.ipynb` | Пустой/черновик | 2025-05-27 |
| Numerical Methods | `ДЗ12_ЯщукОксана_ЧисельніМетоди.ipynb` | Ноутбук | 2025-05-04 |
| Numerical Methods | `ДЗ11_ЯщукОксана_ЧисельніМетоди.ipynb` | Ноутбук | 2025-05-04 |
| Numerical Methods | `ДЗ10_ЯщукОксана_ЧисельніМетоди.ipynb` | Ноутбук | 2025-05-03 |
| Numerical Methods | `ДЗ9_ЯщукОксана_ЧисельніМетоди.ipynb` | Ноутбук | 2025-05-03 |
| Numerical Methods | `ДЗ7_ЯщукОксана_ЧисельніМетоди.ipynb` | Ноутбук | 2025-05-01 |
| Numerical Methods | `ДЗ6_ЯщукОксана_ЧисельніМетоди.ipynb` | Ноутбук | 2025-04-29 |
| Numerical Methods | `ДЗ5_ЯщукОксана_ЧисельніМетоди.ipynb` | Ноутбук | 2025-04-28 |
| Numerical Methods | `ДЗ4_ЯщукОксана_ЧисельніМетоди.ipynb` | Ноутбук | 2025-04-27 |
| Numerical Methods | `ДЗ3_ЯщукОксана_ЧисельніМетоди.ipynb` | Ноутбук | 2025-04-27 |
| Numerical Methods | `ДЗ2_ЯщукОксана_ЧисельніМетоди.ipynb` | Ноутбук | 2025-04-27 |
| Numerical Methods | `ДЗ1_ЯщукОксана_ЧисельніМетоди.ipynb` | Ноутбук | 2025-04-27 |
| Учебные Jupyter notebooks | `ДЗ1_ЯщукОксана.ipynb` | Ноутбук | 2025-04-27 |
| Учебные Jupyter notebooks | `Copy of Untitled1.ipynb` | Копия | 2025-04-26 |
| Учебные Jupyter notebooks | `Untitled0.ipynb` | Пустой/черновик | 2025-01-30 |
| Учебные Jupyter notebooks | `ДЗ10_ЯщукОксана.ipynb` | Ноутбук | 2025-01-04 |
| Учебные Jupyter notebooks | `ДЗ9_ЯщукОксана.ipynb` | Ноутбук | 2025-01-03 |
| Учебные Jupyter notebooks | `ДЗ8_ЯщукОксана.ipynb` | Ноутбук | 2024-12-22 |
| Учебные Jupyter notebooks | `Copy of ДЗ7_ЯщукОксана.ipynb` | Копия | 2024-12-15 |
| Учебные Jupyter notebooks | `ДЗ7_ЯщукОксана.ipynb` | Ноутбук | 2024-12-15 |
| Учебные Jupyter notebooks | `ДЗ6_ЯщукОксана.ipynb` | Ноутбук | 2024-12-06 |
| Учебные Jupyter notebooks | `ДЗ5_ЯщукОксана.ipynb` | Ноутбук | 2024-12-05 |
| Учебные Jupyter notebooks | `ДЗ4_ЯщукОксана.ipynb` | Ноутбук | 2024-11-30 |
| Учебные Jupyter notebooks | `ДЗ3_ЯщукОксана.ipynb` | Ноутбук | 2024-11-30 |
| Учебные Jupyter notebooks | `Copy of ДЗ3_ЯщукОксана.ipynb` | Копия | 2024-11-30 |
| Учебные Jupyter notebooks | `ДЗ3_ЯщукОксана.ipynb` | Ноутбук | 2024-11-30 |
| Учебные Jupyter notebooks | `Copy of ДЗ2_ЯщукОксана.ipynb` | Копия | 2024-11-27 |
| Учебные Jupyter notebooks | `ДЗ2_ЯщукОксана.ipynb` | Ноутбук | 2024-11-16 |
| Учебные Jupyter notebooks | `Copy of ДЗ1_ЯщукОксана.ipynb` | Копия | 2024-11-13 |
| Учебные Jupyter notebooks | `Copy of Home work 1 - Template.ipynb` | Копия | 2024-11-12 |

Как открыть: Google Drive → `Colab Notebooks` → выбрать файл → открыть через Google Colab.

## Быстрый выбор

- **Для алгоритмического портфолио:** `goit-algo-fp`, `goit-algo-hw-06`, `goit-algo-hw-10`.
- **Для backend/web:** `goit-pythonweb-hw-02`, `goit-cs-hw-02`, `goit-cs-hw-06`.
- **Для SQL и моделирования:** `got-rdb-fp`, `goit-rdb-hw-04`, `goit-cs-hw-03`.
- **Для Data Engineering:** `goit-de-fp`, `goit-de-hw-06`, `goit-de-hw-03`.
- **Для Airflow:** `goit-de-hw-07` как компактный пример; `airflow_sandbox` как полноценная среда.
- **Для Deep Learning:** `DeepLearning`.

_Last reviewed: 2026-08-26._
