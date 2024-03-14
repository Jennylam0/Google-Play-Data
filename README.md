# Google-Play-Data
**Goal**  
Define a measure of success by the number of user downloads/installs for the app. The goal is to identify the characteristics that make an app successful.

**Datasets**  
googleplaystore.csv contain all the details of the applications on Google Play:  
• App Application name  
• Category Category the app belongs to ss  
• Rating Overall user rating of the app (as when scraped)  
• Reviews Number of user reviews for the app (as when scraped)  
• Size Size of the app (as when scraped)  
• Installs Number of user downloads/installs for the app (as when scraped)  
• Type Paid or Free  
• Price Price of the app (as when scraped)  
• Content Rating Age group the app is targeted at - Children / Mature 21+ / Adult  
• Genres An app can belong to multiple genres (apart from its main category). For example, a musical family game will belong to Music, Game, Family genres.  
• Last Updated Date when the app was last updated on Play Store (as when scraped)  
• Current Ver Current version of the app available on Play Store (as when scraped)  
• Android Ver Min required Android version (as when scraped)  

googleplaystore_user_reviews.csv contains the first most relevant 100 reviews for each app. Each review text/comment has been pre-processed and attributed with 3 new features - Sentiment, Sentiment Polarity and Sentiment Subjectivity:
• App Name of app  
• Translated_Review User review (Preprocessed and translated to English)  
• Sentiment Positive/Negative/Neutral (Preprocessed)  
• Sentiment_Polarity Sentiment polarity score  
• Sentiment_Subjectivity Sentiment subjectivity score  
