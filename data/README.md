# Данные

В проекте используется датасет [IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)содержащий 50 000 отзывов, размеченных по сентименту (положительный / отрицательный)

- Можно загрузить датасет с Kaggle
- Можно импортировать напрямую через Hugging Face Datasets:

from datasets import load_dataset

dataset = load_dataset("imdb")
