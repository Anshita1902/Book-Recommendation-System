# Book-Recommendation-System

**Introduction**
In today's vast sea of literature, readers often struggle to discover books that align with their interests and preferences. As a result, there is a growing demand for personalized book recommendation systems that can assist users in finding relevant and enjoyable reading material. The objective of this project is to develop a machine learning-based book recommendation system that can suggest books tailored to the individual tastes and preferences of users.

# Data Description 
Utilised three datasets namely:

- Book data – (ISBN, Book-Title, Book-Author, Year-Of-Publication, Publisher, Image-URL-S, Image-URL-M, Image-URL-L)
- Users data - (User-ID, Location, Age)
- Ratings data - (User-ID, ISBN, Book-Rating

- **Dataset Link** https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset

- **Users** 

Contains the users.Demographic data is provided (Location, Age) if available.

- **Books**

Books are identified by their respective ISBN. Invalid ISBNs have already been removed
from the dataset. Moreover, some content-based information is given (Book-Title,
Book-Author, Year-Of-Publication, Publisher), obtained from Amazon Web
Services. Note that in the case of several authors, only the first is provided. URLs linking
to cover images are also given, appearing in three different flavors (Image-URL-S,
Image-URL-M, Image-URL-L), i.e., small, medium, large. These URLs point to the
Amazon website.

- **Ratings**

Contains the book rating information. Ratings (Book-Rating) are either explicit,
expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit,
expressed by 0.

# Machine Learning Data Pipeline
1. Data Preparation (Data Cleaning and Feature Engineering)
2. Exploratory Data Analysis
- Univariate Analysis on numeric and categorical features
- Analysis from categorical variables
3. Got top ten books as per ratings
4. Content Based Filtering
5. It uses Weighted average rating method
