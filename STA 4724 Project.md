# STA 4724 Project

# K-Nearest Neighbors(KNN)
# Cleaning and Normalizing features
import numpy as np
import pandas as pd
file_path = "/Users/matheusmsgomes/Documents/Big Data Analytics/Project/Sleep_health_and_lifestyle_dataset.csv"
df = pd.read_csv(file_path)

#Dropping Person ID columns
df = df.drop(columns=["Person ID"])


print(df.head())