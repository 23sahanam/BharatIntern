Movie Recommendation System using Collaborative Filtering
This project is part of my internship at Bharat Intern. It involves developing a movie recommendation system using collaborative filtering techniques. The system recommends movies to users based on their preferences and past ratings.

Table of Contents
Introduction
Dataset
Installation
Usage
Methodology
Results
Visualizations
Conclusion
Contributing


Introduction
The goal of this project is to build a recommendation system using collaborative filtering methods. Collaborative filtering leverages user interactions with items (movies in this case) to recommend items that similar users have liked. This approach can be divided into:

User-based collaborative filtering
Item-based collaborative filtering

Dataset
The dataset used in this project is from the MovieLens dataset, which contains millions of movie ratings from users but here i have used only 2 dataset from that huge dataset.

Installation
To run this project on Google Colaboratory, follow these steps:

1.Open Google Colab in your browser.

2.Upload your dataset files (ratings.csv and movies.csv) directly in the Colab environment using the files.upload() method.

3.Install necessary libraries within the Colab notebook:

python
Copy code
!pip install numpy pandas scikit-learn surprise seaborn matplotlib

Usage
Upload the datasets directly in Colab:

python
Copy code
from google.colab import files
uploaded = files.upload()
Run the Jupyter Notebook cells to see the data analysis and model training process:

Open the Collaborative_Filtering(Movie_Recommendation).ipynb notebook in Colab.
Execute the cells sequentially to run the project.

Methodology
The project follows these steps:

Data Preparation:

Load and merge the MovieLens datasets.
Clean and preprocess the data to handle missing values and correct data types.

Exploratory Data Analysis (EDA):

Visualize the distribution of ratings.
Analyze the number of ratings per movie and per user.
Examine trends in ratings over time.

Modeling:

Implement user-based collaborative filtering.
Implement item-based collaborative filtering.
Combine the predictions from both models using a weighted approach.

Evaluation:

Evaluate the model's performance using metrics like RMSE (Root Mean Squared Error) and MAE (Mean Absolute Error).
Results
The performance metrics for the recommendation system are:

RMSE: 0.8758
MAE: 0.6724
These metrics indicate the accuracy of the recommendation system in predicting user ratings.

Visualizations
Several visualizations are included to understand the data and model performance better:

Average rating over time
Number of ratings per movie
Number of ratings per user
Distribution of genres
Top Five Most viewed and rated Genres

Conclusion
This project successfully demonstrates the use of collaborative filtering to build a movie recommendation system. The weighted combination of user-based and item-based filtering improved the system's accuracy.

Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

Feel free to reach out if you have any questions or suggestions. Your feedback is always appreciated! 😊

Author: SAHANA M
Email: msahana23102004@gmail.com
LinkedIn: www.linkedin.com/in/sahana-m-26136a2b3
GitHub: https://github.com/23sahanam
