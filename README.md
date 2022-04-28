# Esteban Zuniga Data Portfolio 
Data Science Portfolio

# [Project 1 Yankee Home Run Estimator: Project Overview](https://github.com/Ezuniga13/Home-Run-regression)

- Built and trainded a Linear Regression Model to predict Yankee player home runs.
- I scraped over 1000's of stats from the website [Sports-Reference](https://www.sports-reference.com) using Python, Selenium and Beautiful Soup. 
- Engineered features from coefficients using statsmodel and Python.
- Optimized Linear, Ridge, Lasso regression using Stochastic Gradient Descent.
![Main Page!](/images/hr_scatter.png)

# [Project 2 Loan Default Predictor ](https://github.com/Ezuniga13/loan-classification)

- Built and trained a logistic regression model to predict whether an applicant would default on a loan.
- Used historical data from the Lending Club dataset.
- Engineered features from a linear regression using Sci-kit Learn
- Selected features from fields such as debt-to-income ratio, income, credit score, home ownership, years of employment.
- Modeled the default risk by comparing 3 supervised classification models. (Logistic, Random Forest, Decision Tree)
- I was able to predict a default applicant depending on risk tolerance of the lender.
![Main Page!](/images/roc_curve.png)

# [Project 3 Deep Learning Sound Classification ](https://github.com/Ezuniga13/AI-sound-classification-deep-learning)
[My Article that was an Editors Pick on Data Science Weekly](https://selectfrom.dev/spectrograms-or-how-i-learned-to-stop-worrying-and-love-audio-signal-processing-for-machine-d28c022ca5ca)

- Built Convolutional Neural Network from scratch to classify whether a sound was from a cat or a dog.
- Acquired wave files of dogs and cats from Kagge.
- Viszualized Time-Domain representation of the signal by using Librosa.
- Converted Time-Domain and Frequency-Domain graphs into Spectrograms using a Fast-Fourier Transformation algorithm.
- Rebuilt the Neural Network using a pre-trained VGG-16 model as a base to improve accuracy to over 90%.
![Main Page!](/images/cat_7.png)

# [Project 4 Yelp Data Engineering  ](https://github.com/Ezuniga13/Yelp-Data-Engineeering)

- Built a fully automated data pipeline to create a 3D interactive dashboard and curated a dataframe of the best eats in NYC.
- Made Yelp API calls every 24 hours from the Business Search Endpoint and then pushed data to an AWS RDS posgres db.
- Pulled data every 24 hours from AWS database and filtered out poor performing busineesses and converted the Dataframe into a CSV file and pushed to a S3 bucket.
- Pulled data from the cloud(s3 bucket) and viszualized the data using pydeck.
-  Built web page using Streamlit.
-  Deployed app by running multiple containers using Docker.
-  ![Main Page!](/images/simple_map.png)
