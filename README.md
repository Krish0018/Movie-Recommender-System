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
```pip install numpy```


for Pandas
```pip install pandas```


For Matplotlib
```pip install matplotlib```


For Seaborn
```pip install seaborn```


### Key Insights

For getting the visual information about ratings

```
plt.figure(figsize=(10,4))
plt.hist(df_ratings['rating'], bins=80)
plt.show()
```


<img width="461" alt="rat" src="https://user-images.githubusercontent.com/69238621/140750786-e454b488-3971-411b-85a6-125e3b02af81.PNG">


To see which movies has what average rating with total ratings

```
df_ratings.sort_values('no. of ratings',ascending=False).head()
```
<img width="600" alt="tab" src="https://user-images.githubusercontent.com/69238621/140751745-f8569fac-af55-413b-b266-4b291d2c6f34.PNG">

### How it works?
We used the highely rated movie for refernce and then ccompared with thw help of correlation. So if we choose a particular movie, then model will show you the list of other movies which are highly correlated with that particular movie
