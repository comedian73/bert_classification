# bert_classification

BERT-подобная модель ИИ для классификации текстов.

### Задача

Дообучить BERT-подобную модель произвольным датасетом для классификации  текстов. Не менее 5 класслв.

### Что использую

* [**pandas**](https://pandas.pydata.org/) - для работы с датасетом
* [**sklearn**](https://scikit-learn.org/stable/), [**imblearn**](https://imbalanced-learn.org/stable/) - для обработки данных
* [**transformers**](https://huggingface.co/docs/transformers/index) - для загрузки токенизаторов и предобученой модели
* [**tensorflow**](https://www.tensorflow.org/?hl=ru) - для корректной работы модели и обработки входных данных
* [**datasets**](https://huggingface.co/docs/datasets/index) - для загрузки датасета с Hugging Face
* [**matplotlib**](https://matplotlib.org/), [**seaborn**](https://seaborn.pydata.org/) - для визуализации
* [**ai-forever/headline-classification**](https://huggingface.co/datasets/ai-forever/headline-classification) - датасет для обучения
* [**ai-forever/ruRoberta-large**](https://huggingface.co/ai-forever/ruRoberta-large) - предобученая модель

В результате работы получилась BERT-подобная дообученая модель, которая классифицирует текст по 6 классам (Спорт, Политика, Проишествия, Культура, Экономика, Наука).

Для просмотра кода работы по подготовки, обработки, визуализации данных и обучения модели с дольнейшим выводом примеров работы необходимо перейти в [Google Colab](https://colab.research.google.com/drive/1SyoWs4dL4X74j-anbR079FupyAA0qjyt?usp=sharing)
