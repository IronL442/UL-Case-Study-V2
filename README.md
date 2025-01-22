# Case Study Unsupervised Learning

  ## Notes
  - Data from 31. October to 1. November 2024

  -  Tasks: EVERYONE!!
      1. Preprocessing (missing values, duplicates, etc.) - alle, Erik, Laurits
          - [x] Convert to lowercase
          - [x] Remove URLs, mentions, and special characters, numbers (leave hashtags and emojis for now)
              - [x] Emoji Bug
          - [x] Remove stop words
              - [x] Requires download of "en_core_web_sm" model (small model is sufficient for removing stop words and lemmatization)
          - [x] Perform stemming/lemmatization
          - [x] Named Entity Recognition NER
          - [x] Remove Date from timestamp
          - [x] Deal with non-english tweets
          - [x] Remove duplicate tweets 
      2. Feature Engineering
          - [ ] Word counts
          - [ ] Post frequency (identify spammers like @reginabarnes)
          - [ ] User activity timestamp, post frequency (how often in a specific time) - Isabell
      3. Graph and Network Analysis (frindship network, graph csv) - Valentin
          - [ ] Clustering(k-means, DBSCAN etc.)
              - [ ] k-means
              - [ ] DBSCAN
          - [ ] Apply on the text
              - [ ] Cluster by Topics Laurits, Erik
              - [ ] Cluster by Sentiment - Laurits
                    - [ ] Sentiment Analysis - Laurits
              - [ ] Word Embeddings (maybe from Hugging Face?) - Isabell
      4. Dimensionality Reduction
          - [ ] PCA
          - [ ] t-SNE
      - [ ] Top Most Followed Users, Users with most Tweets

  - [ ] Visualization Ideas
      - [ ] Word Cloud with most common hastags or keywords
      - [ ] Word active users
      - [ ] Most spammed tweet
      - [ ] Heatmaps for user activity over time
      - [ ] Network Graph (visual graph with communities and central nodes highlighted)
