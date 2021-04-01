# Jordan Picone - [Restaurant Reviews, Bias, and Language](https://github.com/Data-Science-for-Linguists-2021/reviews_bias_and_language)
Visit (Emma)
- Your project seems very interesting and highlights something that a lot of people might not even consider about the food industry/ reviews of the food industry. It was surprising to see how much information came from the reviews, as well (stars, categories, hours, etc.) Also, the cuisine function was a cool way to clean up and organize the data so that it would be useful for your analysis
- This might be more stylistic, but it might be helpful to put in column labels for the final data frame in the notebook!
- Using pd.dropna() with a subset to maintain a full dataset

 Response: Thanks Emma! You're right, I need to add column names to make my code more legible.

Visit (Frances)
- The data seems to be really well transformed. The different categories you have in your dataframe seem very useful.
- The different IDs are pretty messy looking, but definitely important since that seems to be the way each restaurant/reviewer is identified, do these correspond to actual names?
- It’s very interesting how the longitude and latitude are recorded!

Response: Thanks Frances! The reviewer IDs are anonymized but the business IDs are tied to the business's homepage.

Visit(Emily)
- I am really interested to see what your findings are, I think it is a neat project. I like the way you built your dataframe and partitioned it, I think it looks neat and useful.
- I would love to see some stats, although I am sure that is something you are still working on. Do certainly types of restaurants have mostly positive reviews? Are there some cities with simply terrible restaurants? Maybe that is just my curiousity but I think it would be neat to see!
- I learned about chunking to take care of very large sets of data.

 Recomendations: Thanks Emily! Those other stats you mentioned are a good idea for me to include to give a clearer picture of the data.

Visit (Abby)
- Data is very clean and easy to understand.  The repository isn't overcrowded.
- I'm curious about the choice to not include city in the dataframe.  Like Emily said, it's important to compare all aspects of the restaurant/review.  If the goal is to do a cultural analysis of language, I think you need to compare both different restaurant types in the same city and the same restaurant type across different cities.
- This: "sent1.append([i, list(df[df['review_id'] == i]['sents']), int(df[df['review_id'] == i]['stars']), str(df[df['review_id'] == i]['restaurant'].values[0])])" is the most complicated line of code I've ever seen in my limited experience with python.  I didn't know quite how versatile dataframe indexing could be.

Response: Thanks Abby! Haha, I think my code there is probably too complicated and could be written a lot more legibly to accomplish the same thing. Data types are confusing.
