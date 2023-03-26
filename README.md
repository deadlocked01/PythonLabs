# PythonLabs

Book Rating Prediction Model This repository contains code for building a book rating prediction model using machine learning. The model uses the books.csv dataset, which is available in the repository.

Dependencies The following dependencies are required to run the code:

numpy pandas seaborn scikit-learn You can install them using pip, as shown below:

Copy code pip install numpy pip install pandas pip install seaborn pip install -U scikit-learn Usage The book_rating_prediction.ipynb file contains the code for the book rating prediction model. You can run the code in a Jupyter notebook.

The notebook contains the following sections:

Loading the dataset Data preprocessing Data visualization Feature engineering Building the model Model evaluation Dataset The books.csv dataset contains information about books, including the title, author, rating, language, number of pages, and publication date. The dataset has 10,000 rows and 23 columns.

Model The book rating prediction model uses linear regression to predict the average rating of a book based on its features. The model achieves a mean squared error of 0.26 on the test data.
