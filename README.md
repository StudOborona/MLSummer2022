# MLSummer2022

Практическая часть Машинное Обучение (ML) лето 2022

### Работа с репозиторием

1. Создать ветку от `master` для выполнения своего задания. Наименование ветки: `<author>__task_<n>`,
   например, `kovalev__task_01`
2. Выполнить задание в своей ветке
3. Создать `PR` в `master`

### Задания

- файл [Машинка теория.docx](https://docs.google.com/document/d/1Wvbh8_V136eJZkpTeUbHaM5Xh6DHuG8L/edit) (тут задания 1-10)
- файл [Методические указания к экзамену.docx](https://docs.google.com/document/d/1b3Py3FyRpE3e7IMyX-ZZj1OYbU_Cpq80/edit) (файл по ссылке "Программа экзамена" с [сайта Коротеева](https://koroteev.site/ml/#%D0%B4%D0%BB%D1%8F-%D1%81%D1%82%D1%83%D0%B4%D0%B5%D0%BD%D1%82%D0%BE%D0%B2-%D1%84%D0%B8%D0%BD%D0%B0%D0%BD%D1%81%D0%BE%D0%B2%D0%BE%D0%B3%D0%BE-%D1%83%D0%BD%D0%B8%D0%B2%D0%B5%D1%80%D1%81%D0%B8%D1%82%D0%B5%D1%82%D0%B0))

### Выполнение заданий

#### Общие этапы

1. Загрузить датасет в Python.
2. Описать набор данных и решаемую задачу.
3. Выделить целевую переменную и факторные переменные.
4. Удалить ненужные данные, проанализировать отсутствующие значения.
5. Прокомментировать количественные параметры датасета.
6. Разбить выборку на обучающую и тестовую.
7. Работа по вариантам.

#### Варианты этапов

##### Вариант 1. Очистка данных и обучение моделей.

Данный вариант предполагает фокусировку на обучении нескольких
видов моделей обучения с учителем. В зависимости от набора
данных, может предполагаться задача классификации и регрессии.
Необходимо после минимальной подготовки датасета к обучению
обучить несколько моделей и сравнить их эффективность.

##### Вариант 2. Описательный анализ и визуализация данных.

Данный вариант предполагает фокусировку на исследовании данных
и визуализации. При решении этого варианта следует провести как
можно более подробный описательный анализ данных с
использованием максимального спектра средств визуализации. При
этом следует делать значимые выводы об обнаруженных в данных
закономерностях.

##### Вариант 3. Построение модели и оптимизация гиперпараметров.

Данный вариант предполагает фокусировку на процессе улучшения
эффективности модели обучения с учителем. Студенту следует
подготовить датасет к обучению, обучить одну из моделей с учителем
со значениями гиперпараметров по умолчанию, получить значение
эффективности. После этого вручную или автоматически подобрать
значения гиперпараметров таким образом, чтобы получить
максимальный прирост эффективности.

##### Вариант 4. Выбор признаков.

Данный вариант предполагает фокусировку на улучшении модели
путем ввода новых признаков в модель. Следует подготовить модель
к обучению, обучить модель и зафиксировать начальный уровень
эффективности. Затем следует исследовать влияние исключения
существующих и введения новых признаков в модель на
эффективность. Как вариант можно рассматривать введение
полиномиальных признаков. Следует стремиться к максимальному
увеличению эффективности модели.

##### Вариант 5. Исследование влияния обучения без учителя на эффективность обучения.

Данный вариант предполагает фокусировку на использовании
методов обучения без учителя для ускорения или повышения
эффективности обучения с учителем. Следует подготовить модель к
обучению, обучить модель и зафиксировать начальный уровень
эффективности. Затем следует попробовать применить понижение
размерности, обнаружение аномалий или кластеризацию (в любой
комбинации) для трансформации исходного датасета. В конце работы
следует сделать значимый вывод об изменении скорости и
эффективности обучения с учителем.

### Требования

- python >= 3.8
- requirements.txt
