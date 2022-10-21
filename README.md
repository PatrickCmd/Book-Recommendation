# Book-Recommendation
Build state-of-the-art models for book recommendation system

Experimenting with recommendation systems as part of [project of the week at DataTalks.Club](https://github.com/DataTalksClub/project-of-the-week/blob/main/2022-10-19-recommenders-1.md)

Dataset: https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset


## Project Overview
- **Goals**: Recommend books!
- **Needs**:
    - List of books we like
    - Get recommendations of books that we have not read yet from users who like books that we like.


## Project Steps
01. **Search For Books**: Build search engine to find search books on title and find the book ids of the books we like.
02. **Create Book List**: Create a list of book ids of the books that we like
03. **Recommend Books**: Use the list of books we like to recommend that we might like that we haven't read yet. We do that by finding users who like books that we like and what other books that they like. And so we use those books as recommendations that we might like to read.
