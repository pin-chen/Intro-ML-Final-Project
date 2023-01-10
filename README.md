# Intro-ML-Final-Project

Competitions: https://www.kaggle.com/competitions/tabular-playground-series-aug-2022

model link: https://github.com/pin-chen/Intro-ML-Final-Project/blob/main/final_model.pickle

test data link: https://github.com/pin-chen/Intro-ML-Final-Project/blob/main/x_test.npy

### 環境: (Kaggle)

Python version: 3.7.12

AccelertorL GPU 100

Python 機器學習庫: sklearn

```
import numpy as np
import pandas as pd
import pickle
from sklearn import linear_model
from sklearn.linear_model import HuberRegressor
from sklearn.impute import SimpleImputer
from sklearn.impute import KNNImputer
import warnings
warnings.filterwarnings('ignore')
```

### Usage:

1. 將 train.csv 、 test.csv 、 sample_submission.csv 放置對應位置或更改 notebook 中的 path

2. Run all train notebook 

3. 你會拿到 modele 和 test data

4. 再將路徑交給 inference notebook 

5. Run all inference notebook 

6. 你會拿到 109550206.csv 即為答案。

### Kaggle Usage: 

如果使用 kaggle 進行，整體改動會很少。

1. import train notebook to kaggle .

2. Add dataset (https://www.kaggle.com/competitions/tabular-playground-series-aug-2022).

3. Run all train notebook.

4. Download modele, test data.

5. Upload modele, test data to kaggle be dataset.

6. import inference notebook to kaggle.

7. Add dataset about model and test data and (https://www.kaggle.com/competitions/tabular-playground-series-aug-2022).

8. Run all inference notebook.

9. Get 109550206.csv
