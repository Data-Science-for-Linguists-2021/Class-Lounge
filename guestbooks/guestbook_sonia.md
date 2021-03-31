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

 ---

 ## Visit round 2
