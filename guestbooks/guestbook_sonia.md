# [Language identification to map language relatedness](https://github.com/Data-Science-for-Linguists-2021/languageID-relatedconfusion)
Welcome! Some quick links are to the [progress report](https://github.com/Data-Science-for-Linguists-2021/languageID-relatedconfusion/blob/main/progress_report.md) and to the walkthrough of the data gathering process in [data-explanation.ipynb](https://github.com/Data-Science-for-Linguists-2021/languageID-relatedconfusion/blob/main/data-explanation.ipynb). After gathering the data, I did machine learning in [naivebayes.ipynb](https://github.com/Data-Science-for-Linguists-2021/languageID-relatedconfusion/blob/main/naivebayes.ipynb) (scroll to the bottom to see some very preliminary results - groups of related languages).

---

## Visit round 1

### visit (Frances):
 - One thing that I thought was well done was your idea of how to chunk the text. You pointed out how sentences are difficult to mark out across different languages so I think choosing a round number of characters was really smart!
 - One thing that I noticed that you might need to improve was the disparity in your data sizes between languages. I think that you might've mentioned it in your "to do" section.
 - One thing I learned was that it can take so long for code to run! It makes sense since you have so much data to scrape, but over a day is really long.
> Yes, code anywhere in the pipeline for many machine learning-related tasks takes lots of time to run; some research I read is about code that needed to run for weeks! Creating the "chunked" subset of data helped a lot for language disparity and I use stratified sampling for the classifier. I plan to check how less-represented languages performed compared to more-represented ones.

### visit (Lexy):
 - You have such detailed and meticulous progress reports that is very easy to follow. Your findings in your data explanation file were so interesting. Your text chunking is really cool as well. Seems like a very interesting project so I can't wait to see the final product.
 - The encoding issues are a bit concerning because they could potentially negatively influence your analysis, but it seems that this is on your to-do list.
 - I learned that scraping this much data took this long and took up this much space. You definitely aren't afforded the luxury of procrastination so it is good that you are so organized!
 > Thanks! For a couple years I've wanted to do a project like this, so I'm really enjoying finally doing it. Unfortunately I've had to prioritize away from fixing the encoding display issue since it would be pretty difficult to figure out what's even causing it (browser, operating system, Jupyter, etc). Luckily the classifier and the writing anonymization still work as planned, so hopefully my analysis shouldn't be impacted

### visit (Michael):
 - Very smart using unicode to catch odd punctuation. I thought you also did a very good job filtering out unhelpful data (such as < 1 mb files).
 - One thing that wasn't very clear (at least to me) was what the raw xml files actually represented. Were they individual pages? A collection of pages? The entirety of wikipedia in that language? This could be made a little clearer in the markdown cells.
 - I didn't know that python loops had a continue statement, similar to break. After looking it up, it seems really helpful and I'm surprised I'd never heard of it! I also learned that Fiji Hindi is a thing (part of the languages excluded). Very neat.

 ---

 ## Visit round 2

 ### visit (Jordan)
 - Anonymyzing the writing systems is a great idea, without that there could be overfitting. I bet I would have missed this.
 - This is less of a critique and more of a question, do you think there's a chance that punctuation could actually improve accuracy, as different languages have different conventions for punctuation? Of course, symbols like the upside down question mark are only used in a few languages and clearing out symbols like this might not be worth the performance increase.
 - CountVectorizer seems to be a good thing to use when dealing with a massive amount of data like this, it seems more computationally efficient.

 ### visit (Emily)
 - I really love the idea of your project and I am really impressed at the amount of data you are working with and what you have accomplished with it so far! I like how much explanation you give, that made everything very easy to follow.
 - Hard to find a critique! My only thing would be, and I am sure you will do more towards this before the presentation, but the current presentation could probably benefit from some more (and larger) plots. Because there are so many languages, as you going to do some separate plots on subsections of data?
 - I learned more about handling big data as well as dealing with different writing systems, very cool!
