# Movie-Recommender-System

### About the project
This is quite interesting project.
In this projects I've only used feature engineering and correlation method to make a movie recommender.
This is content based model.

### Tool Used
Used Python for data analysis for that particular dataset. Libraries used for this project are:
Numpy
Pandas
Matplotlib
Seaborn

### Installation
for numpy
```import numpy as np```


for Pandas
```import pandas as pd```


For Matplotlib
```import matplotlib.pyplot as plt```


For Seaborn
```import seaborn as sns```


### Key Insights

For getting the visual information about ratings

```plt.figure(figsize=(10,4))
plt.hist(df_ratings['rating'], bins=80)
plt.show()```


![image] <img width="461" alt="rat" src="https://user-images.githubusercontent.com/69238621/140750786-e454b488-3971-411b-85a6-125e3b02af81.PNG">


To see which movies has what average rating with total ratings

```
df_ratings.sort_values('no. of ratings',ascending=False).head()
```

![image] <img width="600" alt="tab" src="https://user-images.githubusercontent.com/69238621/140751745-f8569fac-af55-413b-b266-4b291d2c6f34.PNG">
