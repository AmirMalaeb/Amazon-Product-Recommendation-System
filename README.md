This project is aimed at building a recommendation system to suggest products to customers based on their previous ratings. The analysis includes data preprocessing, exploratory data analysis (EDA), model building, and evaluation.

Project Files

	•	AmirMalaeb-Recommendation_Systems_Full_Code.ipynb: The Jupyter Notebook file with the full code, data analysis, and model building steps.

Project Overview

Objective

The primary objective is to build a recommendation system to recommend products to customers based on their previous ratings. This helps in enhancing customer experience and optimizing product suggestions.

Context

With the exponential growth of information, consumers often face information overload and too many choices. Recommender systems help by providing personalized product recommendations to consumers while they are browsing online. E-commerce giants like Amazon, Walmart, and Etsy use recommendation models to provide personalized suggestions to their users. Amazon’s recommendation system, for example, uses item-to-item collaborative filtering to offer accurate product recommendations.

Data

The dataset includes features related to user-product interactions such as:

	•	userId: Unique identifier for each user
	•	productId: Unique identifier for each product
	•	Rating: Rating given by the user to the product
	•	timestamp: Time of the rating (not used in this project)

Methodology

	1.	Data Preprocessing
	•	Handling missing values
	•	Transforming and encoding data
	2.	Exploratory Data Analysis (EDA)
	•	Visualizing data distributions and relationships
	•	Identifying patterns and trends
	3.	Model Building
	•	Implementing collaborative filtering techniques
	•	Building and training recommendation models using the surprise library
	4.	Model Evaluation
	•	Evaluating model performance using metrics such as RMSE and MAE
	•	Selecting the best model based on evaluation metrics

Instructions for Running the Notebook

	1.	Ensure that you have all the necessary libraries installed. It is recommended to use Google Colab to avoid issues with the surprise library.
	2.	Follow the instructions provided in the notebook, filling in the code where indicated.
	3.	Run the code cells sequentially to avoid errors.

Dependencies

To run the Jupyter Notebook, ensure you have the following Python packages installed:
pip install pandas scikit-learn matplotlib surprise
