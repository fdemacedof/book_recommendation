# book recommendation system with goodreads book rating data

## instructions

- download [Goodreads Book Datasets](https://www.kaggle.com/datasets/bahramjannesarr/goodreads-book-datasets-10m)
    [data](https://www.kaggle.com/datasets/bahramjannesarr/goodreads-book-datasets-10m/download?datasetVersionNumber=18)
- unzip and place it in a folder named *goodreads_book_data/*

## introduction

this notebook uses [Kaggle's Goodreads Book Datasets](https://www.kaggle.com/datasets/bahramjannesarr/goodreads-book-datasets-10m) in order to explore recommendation algorithms. I here implemented:

- most popular/top rated books, in order to recommend books to new users
- single value decomposition
- k-nearest neighbors

## exploration

data is comprised of: 
    - a book dataset, with information about books 
    - a ratings dataset, with user ratings on books

book rating is distributed as follows:

