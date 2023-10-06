# customer
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

url = "marketing_campaign.csv"
df = pd.read_csv(url,encoding = 'unicode_escape')
df.head()
