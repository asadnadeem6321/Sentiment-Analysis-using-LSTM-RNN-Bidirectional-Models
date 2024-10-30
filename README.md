Must have to import these dependencies that are following:
import joblib
import numpy as np
import pandas as pd
from keras.layers import LSTM
from keras import preprocessing
import matplotlib.pyplot as plt
import sklearn.preprocessing as pre
from keras.utils import pad_sequences
from keras.layers import Flatten, Dense
from tensorflow.keras.models import load_model 
from keras.preprocessing.text import Tokenizer
from tensorflow.keras.callbacks import EarlyStopping
from keras.layers import Embedding, Bidirectional, Dropout
