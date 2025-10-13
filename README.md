# ML-Chatbot-using-MIND-DATSET
This project develops an AI-based chatbot that provides recommendations of personalized news stories and smart conversations based on the MIND (Microsoft News Dataset).
The chatbot is based on the combination of machine learning, natural language processing (NLP), and deep learning methods to understand the preferences of users, suggestions of the topical news articles, and communicating with the user in the contextual dialog. To conceptualize the interrelations between user engagement and news categories, the project employs the data preprocessing, feature extraction and statistical analysis.
              Project Overview

-This project aims at creating a smart chatbot that can:

-Knowing interest of user in history of clicks.

-Conducting categorical association analysis by Chi-Square test.

-Investigating the trends between the types of news and the number of users viewing them.

-Giving the context of a recommendation engine that is specific to the person.

                Key Components

-Data Preprocessing/ Cleaning.

-Raw behaviors.tsv and news.tsv files used in the MIND data are parsed and transformed into the format of raw behavior.

-Breaking down an impression log into a user-news interaction.

-Dealing with missing values, invalid impressions and inconsistent IDs.

           Feature Extraction

-Associating the record of all clicks with the news category and subcategory.

-Preparing organized data to train models and explore the data.

                Statistical Analysis

-Carrying out the Chi-Square test to establish significant associations between the user clicks and news categories.

-Calculating the user preferences by showing the number of click-through rates (CTR) by category.

-Introduction of Machine Learning and Chatbot (Future Scope).

-Development of a recommendation model based on collaborative filtering or embeddings based on NLP.

-Combining the model and a conversational chatbot (Flask or Streamlit).

             Tech Stack
-Machine Learning (Scikit-learn, TensorFlow / PyTorch for future enhancement)
-Python (Pandas, NumPy, SciPy, Matplotlib)
-Dataset: MIND Dataset
 (Microsoft News Dataset)
-NLP Tools (NLTK, SpaCy for text feature extraction)

              Analytical Insights

-Preprocessing of data turned more than 1 million user-news click records into data format.

-The Chi-Square test showed statistically significant dissimilarities in engagement in such categories as Sports, Entertainment, and Finance.

-These learnings are used to train a recommendation chatbot that is personalized.

        Future Enhancements

-Implement a news recommending API that would be enhanced with a chatbot interface.

-Better matching between users and content Use deep learning (Transformers or news embeddings).

-Use reinforcement learning to keep on updating user preferences.


Reference

Wu, C., et al. (2020). MIND: A Large-scale Dataset for News Recommendation. Microsoft Research.
