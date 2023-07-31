# Movie-Sucess-Prediction

## Problem Statement

"Can you make a hit movie?" This project aims to answer this question by analyzing previously successful movies and building predictive models to estimate the revenue for a given movie. The project provides an interactive front-end interface hosted on Tableau, allowing users to input various movie features, such as main actor, budget, director, source material, and more. Through data analysis and machine learning, the project aims to predict how these features might impact a movie's revenue.

## Project Goals

The main objective of this project is to create a predictive model that can help big production studios (e.g., Netflix, Amazon, Universal Studios) make informed decisions about which movie projects to pursue, thus saving them time, money, and resources. Additionally, the project aims to provide a helpful tool for film students and indie directors who may not have the resources to assess the potential success of their movies. By leveraging rigorous statistical analysis, the tool can assist filmmakers in making more informed decisions about their projects.

## Data and Analysis

The project uses the Kaggle Dataset "Movie Industry," sourced from The Internet Movie Database (IMDB) using API. The dataset contains information on 6820 worldwide movies from 1980 to 2020. Initial data cleaning involved handling missing values and duplicates, and the dataset was narrowed down to include movies from the UK, US, and Canada for analysis.

Exploratory data analysis was conducted to understand the data distribution and relationships between variables. Correlation plots and summary statistics were used to gain insights into potential factors affecting movie revenue. Various machine learning models were applied, starting with multiple linear regression, and additional feature engineering was performed to capture temporal aspects. The impact of movie genre was also explored through several model iterations.

## Model Results

After feature engineering and experimentation with different models, the ElasticNet model with log-transformed budget and runtime showed the best performance, achieving an R-squared value of 61.5%. However, it's important to note that movie revenue prediction is a complex task, and the model's performance may still have room for improvement.

## Challenges and Limitations

One of the main challenges faced during the project was related to model deployment and building an interactive UI using Tableau's API Extensions. Limited availability of functionalities required the team to abandon this aspect of the project. Additionally, predicting movie revenue is a highly complex task due to the subjective nature of movies and various factors contributing to success, such as marketing efforts.

## Future Work

The project holds great potential for further development. Future work should include refining the feature engineering process, incorporating more temporal aspects, and exploring additional interactive variables. Addressing the issue of movie genre imbalance and enhancing model performance should be pursued. Additionally, web scraping can be refined to include source material as an additional feature for training the model.

Overall, the project serves as a foundation for future improvements and the development of a dedicated website to provide a valuable tool for decision-making in the film industry.
