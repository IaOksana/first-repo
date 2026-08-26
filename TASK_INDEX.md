# Task-oriented Code Index

Этот индекс отвечает не на вопрос «какие у меня есть репозитории», а на вопрос **«где у меня уже решалась похожая задача?»**.

- GitHub-ссылки открывают готовый публичный код.
- Записи вида **Drive → Colab Notebooks → имя файла** относятся к приватным ноутбукам Google Drive.
- Если указано несколько файлов, сначала открывайте первый: остальные — альтернативы или более узкие примеры.

## Быстрый поиск по типовой задаче

| Если нужно… | Где искать | Что там уже реализовано |
|---|---|---|
| Очистить и проанализировать табличные данные | **Drive → Colab Notebooks → `ДЗ10_ЯщукОксана_ЧисельніМетоди.ipynb`** | Распределения, корреляционная матрица, тепловая карта, стандартизация, нормализация |
| Построить прогноз числовой величины | **Drive → Colab Notebooks → `ДЗ10_ЯщукОксана.ipynb`** | Прогноз недвижимости: Linear Regression, Decision Tree, метрики ошибок, GridSearchCV |
| Классифицировать объекты | **Drive → Colab Notebooks → `ДЗ8_ЯщукОксана_ЧисельніМетоди.ipynb`** | QDA вручную и сравнение со sklearn |
| Подобрать гиперпараметры модели | **Drive → Colab Notebooks → `Оптимізація_гіперпараметрів.ipynb`** | GridSearchCV и Optuna для Random Forest, ROC/AUC и другие метрики |
| Сравнить несколько ML-моделей | **Drive → Colab Notebooks → `mod_05_topic_09_ensembles.ipynb`** | Baseline, Random Forest и ансамбли, SMOTE, F1 и измерение времени |
| Найти группы без готовых меток | **Drive → Colab Notebooks → `ДЗ12_ЯщукОксана_ЧисельніМетоди.ipynb`** | K-Means, Spectral Clustering, Gaussian Mixture, PCA, ARI |
| Найти/отследить птиц или дроны на видео | **Drive → Colab Notebooks → `birds_test.ipynb`, `drones_test.ipynb`** | Подготовка YOLO-датасета, обучение, инференс на видео, negative samples |
| Проанализировать текст | **Drive → Colab Notebooks → `ДЗ7_ЯщукОксана_ЧисельніМетоди.ipynb`** | Токенизация, stop words, лемматизация и самописный Naive Bayes |
| Найти близкие по смыслу слова | **Drive → Colab Notebooks → `ДЗ3_ЯщукОксана_ЧисельніМетоди.ipynb`** | Word embeddings, ближайшее слово, векторные операции, PCA |
| Обработать и кластеризовать аудио | **Drive → Colab Notebooks → `ДЗ6_ЯщукОксана_ЧисельніМетоди.ipynb`** | Librosa, спектрограммы, выравнивание длины, Spectral Clustering |
| Найти оптимальный набор/распределение ресурсов | **Drive → Colab Notebooks → `ДЗ11_ЯщукОксана_ЧисельніМетоди.ipynb`, `ДЗ9_ЯщукОксана.ipynb`** | Генетический алгоритм PyGAD и линейное программирование SciPy |
| Решить задачу последовательных решений | **Drive → Colab Notebooks → `ДЗ9_ЯщукОксана_ЧисельніМетоди.ipynb`** | FrozenLake, value function, policy iteration, оптимальная политика |
| Решить систему линейных уравнений | **Drive → Colab Notebooks → `ДЗ2_ЯщукОксана.ipynb`** | Обратная матрица и метод Крамера |
| Вычислить производную или интеграл | **Drive → Colab Notebooks → `ДЗ5_ЯщукОксана.ipynb`, `ДЗ6_ЯщукОксана.ipynb`** | SymPy, quad, прямоугольники, трапеции и метод Симпсона |
| Сжать изображение | **Drive → Colab Notebooks → `ДЗ2_ЯщукОксана_ЧисельніМетоди.ipynb`** | SVD по цветовым каналам и TruncatedSVD |
| Организовать ETL/стриминг | [goit-de-fp](https://github.com/IaOksana/goit-de-fp) | Kafka, Spark, Airflow и слои landing → bronze → silver → gold |
| Сделать API с базой данных | [goit-pythonweb-hw-02](https://github.com/IaOksana/goit-pythonweb-hw-02) | FastAPI, PostgreSQL, SQLAlchemy, Docker Compose, health check |
| Обработать много файлов | [goit-cs-hw-04](https://github.com/IaOksana/goit-cs-hw-04), [goit-cs-hw-05](https://github.com/IaOksana/goit-cs-hw-05) | Потоки/процессы, asyncio, сортировка и поиск по файлам |
| Найти кратчайший маршрут | [goit-algo-hw-06](https://github.com/IaOksana/goit-algo-hw-06) | Граф, DFS/BFS и алгоритм Дейкстры |

## Данные, статистика и визуализация

| Типовая задача | Примеры | Полезные части |
|---|---|---|
| Быстро изучить CSV/DataFrame | **Drive → `ДЗ10_ЯщукОксана_ЧисельніМетоди.ipynb`**; **Drive → `ДЗ10_ЯщукОксана.ipynb`** | `describe`, типы и пропуски, распределения, выбросы, корреляции |
| Проверить нормальность распределения | **Drive → `ДЗ8_ЯщукОксана.ipynb`** | Shapiro, Kolmogorov–Smirnov, гистограммы и симуляции |
| Посчитать расстояния между объектами | **Drive → `ДЗ4_ЯщукОксана_ЧисельніМетоди.ipynb`** | Euclidean, L1/Manhattan, cosine, cityblock; heatmaps |
| Масштабировать признаки | **Drive → `ДЗ1_ЯщукОксана_ЧисельніМетоди.ipynb`**; **Drive → `ДЗ10_ЯщукОксана_ЧисельніМетоди.ipynb`** | StandardScaler, MinMaxScaler, Normalizer |
| Визуализировать многомерные данные | **Drive → `ДЗ12_ЯщукОксана_ЧисельніМетоди.ipynb`** | Pair plots, PCA, confusion matrix |
| Смоделировать случайный процесс | **Drive → `ДЗ7_ЯщукОксана.ipynb`**; **Drive → `ДЗ8_ЯщукОксана.ipynb`** | Кубики, вероятности, случайное блуждание, моделирование цены |

## Машинное обучение

| Типовая задача | Примеры | Полезные части |
|---|---|---|
| Реализовать логистическую регрессию вручную | **Drive → `Module_1_Lecture_2_Class.ipynb`** | Sigmoid, forward/backward propagation, обновление весов, predict |
| Сделать регрессию в PyTorch | **Drive → `Copy of Tema 3_4_LogRegr_Pytorch_M.ipynb`** | Dataset, LinearModel, RMSE, обучение и градиенты |
| Полиномиальная регрессия | **Drive → `ДЗ5_ЯщукОксана_ЧисельніМетоди.ipynb`** | PolynomialFeatures и собственный gradient descent |
| Классификация QDA | **Drive → `ДЗ8_ЯщукОксана_ЧисельніМетоди.ipynb`** | Ковариационные матрицы, discriminant function, probabilities |
| Несбалансированные классы | **Drive → `mod_05_topic_09_ensembles.ipynb`** | SMOTE, кодирование категорий, F1 |
| Кластеризация | **Drive → `ДЗ1_ЯщукОксана_ЧисельніМетоди.ipynb`; `ДЗ12_ЯщукОксана_ЧисельніМетоди.ipynb`** | Spectral Clustering, K-Means, GMM, сравнение с известными классами |
| Регуляризация нейросети | **Drive → `Module_7_Lecture_14_Class.ipynb`** | L2, early stopping, dropout, batch normalization |
| Оптимизация гиперпараметров | **Drive → `Оптимізація_гіперпараметрів.ipynb`; `Module_7_Lecture_14_Class.ipynb`** | GridSearchCV, Optuna, история оптимизации, importance/slice plots |
| Готовые DL-эксперименты | [DeepLearning](https://github.com/IaOksana/DeepLearning) | Sentiment analysis, preprocessing, training/evaluation и финальные проекты |

## Computer Vision, изображения и видео

| Типовая задача | Примеры | Полезные части |
|---|---|---|
| Подготовить собственный YOLO-датасет дронов | **Drive → `drones_test.ipynb`** | Объединение датасетов, YAML, negative samples, обучение YOLO |
| Подготовить YOLO-датасет птиц из COCO | **Drive → `birds_test.ipynb`** | Конвертация COCO bounding boxes в YOLO и train/val split |
| Проверить модель на видео | **Drive → `birds_test.ipynb`; `drones_test.ipynb`** | `YOLO.predict()`, confidence threshold, сохранение результата |
| Работать с малыми дальними объектами | **Drive → `drones_test.ipynb`** | High-resolution training, tiled inference, augmentation, tracking |
| Сжать RGB-изображение | **Drive → `ДЗ2_ЯщукОксана_ЧисельніМетоди.ipynb`** | SVD отдельно по каналам |
| Загрузить и преобразовать изображение | **Drive → `ДЗ1_ЯщукОксана.ipynb`** | OpenCV, URL download, NumPy broadcasting и матричные операции |

## Тексты, NLP и поиск

| Типовая задача | Примеры | Полезные части |
|---|---|---|
| Очистить текст | **Drive → `ДЗ7_ЯщукОксана_ЧисельніМетоди.ipynb`** | Regex, токенизация, stop words, лемматизация |
| Классифицировать сообщения | тот же ноутбук | Самописный Naive Bayes и визуализация баланса классов |
| Работать с embeddings | **Drive → `ДЗ3_ЯщукОксана_ЧисельніМетоди.ipynb`** | Ближайшее слово к вектору, cross product, угол между векторами |
| Найти слова в большом тексте | [goit-algo-hw-05](https://github.com/IaOksana/goit-algo-hw-05) | Boyer–Moore, KMP, Rabin–Karp и benchmark |
| Посчитать частотность слов из URL | [goit-cs-hw-05](https://github.com/IaOksana/goit-cs-hw-05) | MapReduce и график наиболее частых слов |
| Разобрать выражение или DSL | [goit-cs-hw-01](https://github.com/IaOksana/goit-cs-hw-01) | Lexer, parser, AST и visitor/interpreter |

## Математика и оптимизация

| Типовая задача | Примеры | Полезные части |
|---|---|---|
| Векторы, матрицы и broadcasting | **Drive → `ДЗ1_ЯщукОксана.ipynb`** | Транспонирование, умножение, изменение формы и визуализация векторов |
| Система линейных уравнений | **Drive → `ДЗ2_ЯщукОксана.ipynb`** | `solve_inv_matrix`, `solve_cramer` |
| Производные и экстремумы | **Drive → `ДЗ5_ЯщукОксана.ipynb`** | SymPy `diff`, `solve`, графики |
| Численное интегрирование | **Drive → `ДЗ6_ЯщукОксана.ipynb`** | Rectangle, trapezoid, Simpson и SciPy `quad` |
| Линейное программирование | **Drive → `ДЗ9_ЯщукОксана.ipynb`**; [goit-algo-hw-10](https://github.com/IaOksana/goit-algo-hw-10) | Оптимальное распределение услуг/производства при ограничениях |
| Генетический алгоритм | **Drive → `ДЗ11_ЯщукОксана_ЧисельніМетоди.ipynb`** | Fitness function, population, crossover, mutation |
| Выдача сдачи/распределение суммы | [goit-algo-hw-09](https://github.com/IaOksana/goit-algo-hw-09) | Greedy и dynamic programming |
| Минимизировать стоимость объединений | [goit-algo-hw-08](https://github.com/IaOksana/goit-algo-hw-08) | Min-heap и optimal merge pattern |
| Оценить интеграл Монте-Карло | [goit-algo-hw-10](https://github.com/IaOksana/goit-algo-hw-10) | Monte Carlo estimator с проверкой SciPy |

## Графы, маршруты и алгоритмы

| Типовая задача | Примеры | Полезные части |
|---|---|---|
| Обойти граф | [goit-algo-hw-06](https://github.com/IaOksana/goit-algo-hw-06) | DFS и BFS |
| Найти кратчайший путь | [goit-algo-hw-06](https://github.com/IaOksana/goit-algo-hw-06), [goit-algo-fp](https://github.com/IaOksana/goit-algo-fp) | Dijkstra и визуализация |
| Сбалансированное дерево поиска | [goit-algo-hw-07](https://github.com/IaOksana/goit-algo-hw-07) | AVL/BST, вращения и обходы |
| Очередь задач | [goit-algo-hw-02](https://github.com/IaOksana/goit-algo-hw-02) | FIFO-модель обработки заявок |
| Сравнить сортировки | [goit-algo-hw-04](https://github.com/IaOksana/goit-algo-hw-04) | Insertion sort, merge sort, Timsort и timeit |
| Организовать файлы рекурсивно | [goit-algo-hw-03](https://github.com/IaOksana/goit-algo-hw-03) | Обход каталогов и сортировка по расширениям |

## Базы данных, API и веб

| Типовая задача | Примеры | Полезные части |
|---|---|---|
| Создать FastAPI + PostgreSQL | [goit-pythonweb-hw-02](https://github.com/IaOksana/goit-pythonweb-hw-02), [goit-cs-hw-02](https://github.com/IaOksana/goit-cs-hw-02) | SQLAlchemy session, templates/static, Docker, health endpoint |
| Сделать PostgreSQL CRUD CLI | [goit-cs-hw-03](https://github.com/IaOksana/goit-cs-hw-03) | Схема, seed, запросы и PrettyTable |
| Сделать MongoDB CRUD CLI | [goit-cs-hw-03](https://github.com/IaOksana/goit-cs-hw-03) | PyMongo и интерактивные команды |
| Спроектировать связанную БД | [goit-rdb-hw-04](https://github.com/IaOksana/goit-rdb-hw-04) | PK/FK, авторы, книги, пользователи и выдачи |
| Нормализовать аналитические данные | [got-rdb-fp](https://github.com/IaOksana/got-rdb-fp) | Нормализация и аналитика временных рядов |
| Написать HTTP/socket сервер без фреймворка | [goit-cs-hw-06](https://github.com/IaOksana/goit-cs-hw-06) | HTTP routing, socket receiver и MongoDB |

## Файлы, параллельность и автоматизация

| Типовая задача | Примеры | Полезные части |
|---|---|---|
| Найти ключевые слова во множестве файлов | [goit-cs-hw-04](https://github.com/IaOksana/goit-cs-hw-04) | Threading и multiprocessing версии |
| Асинхронно разложить файлы по папкам | [goit-cs-hw-05](https://github.com/IaOksana/goit-cs-hw-05) | asyncio, aiopath, aioshutil |
| Сохранить состояние приложения | [goit-pycore-hw-08](https://github.com/IaOksana/goit-pycore-hw-08) | Pickle-сериализация адресной книги |
| Запланировать ETL | [goit-de-hw-07](https://github.com/IaOksana/goit-de-hw-07), [airflow_sandbox](https://github.com/IaOksana/airflow_sandbox) | Airflow sensors, branching, trigger rules и расписания |
| Обработать поток событий | [goit-de-hw-05](https://github.com/IaOksana/goit-de-hw-05), [goit-de-hw-06](https://github.com/IaOksana/goit-de-hw-06) | Kafka producers/consumers, Spark windows, watermark и alerts |
| Построить полный data pipeline | [goit-de-fp](https://github.com/IaOksana/goit-de-fp) | Kafka → Spark → MySQL/Airflow; medallion layers |

## Прикладные утилиты

| Типовая задача | Примеры | Полезные части |
|---|---|---|
| Нормализовать телефон и контакты | [goit-pycore-hw-03](https://github.com/IaOksana/goit-pycore-hw-03), [goit-pycore-hw-07](https://github.com/IaOksana/goit-pycore-hw-07) | Regex, модели контактов, CRUD |
| Найти ближайшие дни рождения | [goit-pycore-hw-03](https://github.com/IaOksana/goit-pycore-hw-03), [goit-pycore-hw-07](https://github.com/IaOksana/goit-pycore-hw-07) | Календарная логика и перенос поздравлений |
| Проанализировать логи | [goit-pycore-hw-05](https://github.com/IaOksana/goit-pycore-hw-05) | Подсчёт уровней и фильтрация записей |
| Проверить скобки или палиндром | [goit-algo-hw-02](https://github.com/IaOksana/goit-algo-hw-02) | Stack/deque patterns |
| Провести воспроизводимый benchmark | [goit-algo-hw-04](https://github.com/IaOksana/goit-algo-hw-04), [goit-algo-hw-05](https://github.com/IaOksana/goit-algo-hw-05) | `timeit`, генерация входов и сравнение результатов |

## Дубли и пустые Colab-файлы

Эти файлы не стоит выбирать первыми при поиске решения:

- `Untitled0.ipynb`, `Untitled1.ipynb` — пустые.
- Файлы с префиксом `Copy of` обычно дублируют одноимённый ноутбук; исключение — `Copy of Tema 3_4_LogRegr_Pytorch_M.ipynb`, где хранится содержательный учебный пример PyTorch.
- Несколько версий `ДЗ3_ЯщукОксана.ipynb` практически одинаковы.
- Для полного перечня всех файлов и дат изменения см. [REPOSITORIES_INDEX.md](REPOSITORIES_INDEX.md).

_Last reviewed: 2026-08-26._
