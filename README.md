# Investor Sentiment Analysis Based on Twitter Data

In this project, built using a dataset from **Hugging Face**, I conducted several experiments to create a model capable of analyzing **investor sentiment** towards stocks based on tweets from **Twitter (X)**. The project consists of several key stages:

### Key Stages:
1. **Baseline Model**: Developed a traditional model using the **Multinomial Naive Bayes** algorithm with **TF-IDF** embeddings.
2. **Deep Learning Model (LSTM)**: Built an LSTM model with an embedding layer, using **word-level tokenization**.
3. **Deep Learning Model with Word and Character Embeddings**: Constructed an LSTM model with embeddings for both **words** and **characters**.
4. **Deep Learning Model with Stock Embeddings**: Developed an LSTM model with embeddings for **words** and for the **specific stock** referenced in the tweet.
5. **Deep Learning Model with Tweet-Length and Stock Embeddings**: Created an LSTM model with embeddings for **words**, **tweet length**, and the **specific stock** referenced in the tweet.
