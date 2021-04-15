# [Goodreads Sentiment Analysis](https://github.com/Data-Science-for-Linguists-2021/Goodreads-Sentiment-Analysis)
Ahoy! Welcome to Michael's term-project guestbook. Feel free to have a look at my [code](https://github.com/Data-Science-for-Linguists-2021/Goodreads-Sentiment-Analysis/blob/main/book_scraper.py) and [analysis](https://github.com/Data-Science-for-Linguists-2021/Goodreads-Sentiment-Analysis/blob/main/analysis.ipynb) and leave a brief review.

## Section 1

### visit (Frances):
 - One strength is your code. It is very neat and easy to follow along with, as well as effective considering your data output.
 - One thing to improve is scraping reviews from more books.
 - One interesting thing that you pointed out in your code is how Goodreads labels their reviews not numerically, but with certain phrases in their html.
 > Hi Frances, thanks for your input! Goodreads in general is a very strange website with some... interesting design choices. I talk a little more about it in my updated JNB. I have also increased the amount of books scraped from 2 to 32.

### visit (Jordan):
 - Seems like you have a good base for your project here, I really liked the multi-indexing you did to keep reviews of one book together, and you seem to have done a good job web scraping.
 - My only concern would be that Na-Rae might want more out of this project besides just creating a sentiment analysis model. Maybe you could do some more analysis by genre or by the age, location, etc. of the reviewer
 - Multi-indexing looks very useful for my project, I'm gonna try implementing it.
 > Thanks for your feedback Jordan! I have expanded my dataframe somewhat to include more data for analysis (such as year of publication, genre, likes, etcetera). As for multiindexing, it is a very useful tool, but I actually ended up removing it from my data cleanup process because it just made it difficult to isolate certain review scores.

### visit (Lexy):
- The basis of your project is very interesting. I was always interested in the reviews on Goodreads because they vary so much. Your code and initial analysis also very easy to follow! I understood what you were doing at every step. Your project is also very well thought out from viewing the project plan.
- I am concerned that you may not have enough reviews to make a comprehensive sentiment analysis. You may want to include another analysis because this project is just building a model.
- I learned that Goodreads labeled in html which is strange but I also don't know much about these things.
> Hi Lexy, thanks for your feeback! I have indeed expanded my data to include more reviews (around 3000 now) and will increase the scope of my final analysis to incorporate things such as genre and review-popularity.

## Section 2

### visit (Emma):
- Your analysis notebook was super easy to follow, especially thanks to the opening commentary. I also really liked how you showed examples of the data frame, it really gave a good perspective into the data.
- I’m glad you touched on the 2,3, and 4 star reviews in terms of the negative and positive reviews, and it’ll be interesting to see how you take that further! (If 3 is truly a more neutral review, why does the classifier decide they are negative or positive?)
- Sentiment analysis!!! I’m considering doing something similar for my own project, so this was great to see how someone else is going about that!!!
> Hi Emma, thanks for your feedback! I have that same question about why 3-star reviews are classified the way they are and I'll be taking a closer look at them soon. Stay tuned!

## Section 3

### visit (Emily)
- I like the organization a lot, and I think the way you built your dataframes is informative and clear; as is the analysis section. I agree that the opening commentary was helpful and set the reader up to understand what you did.
- I wonder if your method for classifying sentiment the way you did is the best approach. I say that without quite enough knowledge to make it a full critique but I am curious.
- Wow, your scraping script looks like it was super labor intensive. As someone who also had to scrape a lot of data but used a different method I learned a lot from your approach.
> Thanks for the review Emily! Indeed, my approach to classification at the moment is *very* quick and dirty. I plan to update that section extensively for the next progress report, incorporating some of the techniques we have learned in class over the last couple of weeks.

### visit (Abby):
- Thank you for the extremely reader-friendly Jupyter Notebook and analysis.  I'm interested to see what the results are -- I've heard it said before that good reviews generally focus on the actual content of the thing (i.e. "In this book, character 1 did this thing in this place", "This restaurant served this dish and had such-and-such an atmosphere") while negative reviews focus on personal experience (i.e. "I read this book on a Greyhound bus to such-and-such a city during the Fall of 2018", "We stayed in this hotel for a destination wedding for my aunt's brother's coworker's son and we were really looking forward to it").  This project has the potential to prove or disprove whether or not that's true.
- I honestly don't have any critiques about the overall project.  I'm curious to see what will happen when you incorporate non-textual features in the analysis and whether or not they will improve accuracy.
- I didn't realize you could extract the NB's most useful features with vocabulary_.keys() - that will be helpful.  I also learned that Twilight is classified as a fantasy series . . .
> Thanks Abby. Glad to hear you liked it! I'm very intrigued by this idea of negative reviews focusing more on personal experience. It makes a ton of sense so I'll be sure to take a look at the data and see what I can find!
(As for Twilight: don't forget that old vampire stores like Dracula paved the way for the development of the modern fantasy genre. The two go hand-in-hand!)

### visit (Emma pt.2):
- I really liked seeing how your analysis since my last visit! I also seeing how thorough you were with the grid searching and the multiple ml models. That “yeehaw” comment also resonated quite a bit.
- Your analysis looks really interesting, and I’m excited to hear more about about the rest of your To-Dos (especially the differences between positive and negative reviews)!
- from string import punctuation !!!
