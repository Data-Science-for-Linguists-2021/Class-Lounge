# [Goodreads Sentiment Analysis](https://github.com/Data-Science-for-Linguists-2021/Goodreads-Sentiment-Analysis)
Ahoy! Welcome to Michael's term-project guestbook. Feel free to have a look at my [code](https://github.com/Data-Science-for-Linguists-2021/Goodreads-Sentiment-Analysis/blob/main/book_scraper.py) and [analysis](https://github.com/Data-Science-for-Linguists-2021/Goodreads-Sentiment-Analysis/blob/main/analysis.ipynb) and leave a brief review.

---

### Section 1

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

---

## Section 2

### visit (Emma):
- Your analysis notebook was super easy to follow, especially thanks to the opening commentary. I also really liked how you showed examples of the data frame, it really gave a good perspective into the data.
- I’m glad you touched on the 2,3, and 4 star reviews in terms of the negative and positive reviews, and it’ll be interesting to see how you take that further! (If 3 is truly a more neutral review, why does the classifier decide they are negative or positive?)
- Sentiment analysis!!! I’m considering doing something similar for my own project, so this was great to see how someone else is going about that!!!
