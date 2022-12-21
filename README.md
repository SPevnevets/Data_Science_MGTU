# Data_Science_MGTU

Цель создания данного проекта является разработка моделй машинного обучения для создания композиционных материалов с улучшенными характеристиками.

Данные предоставлены в виде excel-таблиц (каталог data_composite):
Таблица «X_bp.xlsx»;
Таблица «X_nup.xlsx»

Для разработки использовались библиотеки:
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn import preprocessing
from sklearn.preprocessing import StandardScaler
from sklearn.model_selection import train_test_split
from sklearn.impute import KNNImputer
from sklearn.metrics import mean_absolute_error
from sklearn.metrics import mean_squared_error
from sklearn.ensemble import RandomForestRegressor
from sklearn.linear_model import Lasso
from sklearn.model_selection import GridSearchCV

Созданы и обучены модели с помощью моделей регрессии и нейронной сети.
Выгруженные модели сохранены в каталоге:models
