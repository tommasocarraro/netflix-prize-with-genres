# netflix-prize-with-genres

This repository contains information about the genres of the movies of the [Netflix Prize dataset](https://www.kaggle.com/netflix-inc/netflix-prize-data). 

It has been created because the original dataset comes without genres' information, that can be crucial in many machine learning and data mining applications. The information about the genres has been fetched from the IMDB database. In particular the database has been queried by movie's title and year. The Netflix dataset contains 17770 movies in total, while the correspondences with IMDB database are 12279.

The file *netflix_genres.csv* is composed of two columns: in the first column there are the identifiers of the movies of the Netflix dataset, while in the second column there are the list of the genres of the movies. The identifiers correspond to the identifiers in the *movie_titles.csv* file of the original Netflix dataset.