This project aims to recommend movies according to 'movie rating correlation' and 'number of ratings' based on the IMDB Movie datasets. 

The base dataset used i.e. 'u.data' (contains users information) is a medium sized data comprising of 1,00,003 rows and 4 columns. A much larger version of the dataset is freely available on the internet. Another dataset i.e "Movie_Id_Titles" (contains the title of movies) comprises of 1682 rows and 2 columns.

I loaded the datasets, checked for their missing values and then restructured the them as per the need of the project. I performed EDA and visualized the data to get the information about correlation in the data.

Finally, based on the visualization results, I narrowed down the correlation results to include movies only with more than 100 ratings in order to get some meaningful recommendations.