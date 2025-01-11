# Case Study Unsupervised Learning

- Notes
    - Data from 31. October to 1. November 2024

- Tasks: EVERYONE!!
    1. Preprocessing (missing values, duplicates, etc.) - alle Erik, Laurits
        - Convert to lowercase ✅
        - Remove URLs, mentions, and special characters, numbers (leave hashtags and emojis for now) ✅
            - Emoji Bug ✅
        - Remove stop words ✅
            - Requires download of "en_core_web_sm" model (small model is sufficient for removing stop words and lemmatization)
        - Perform stemming/lemmatization ✅
        - NER 
        - Remove Date from timestamp
        - Remove short posts ❔ (< 3 words)
    - Feature Engineering
    - Graph and Network Analysis (frindship network, graph csv) - Valentin
    - Clustering(k-means, DBSCAN etc.)
        - User activity timestamp, post frequency (how often in a specific time) - Isabell
        - Apply on the text
            - Topics Laurits, Erik
            - Sentiment Detection - Laurits
            - Word Embeddings (maybe from Hugging Face?) - Isabell
    - Dimensionality Reduction

- Visualization Ideas
    - Word Cloud with most common hastags or keywords
    - Heatmaps for user activity over time
    - Network Graph (visual graph with communities and central nodes highlighted)
