# To-do 10: Past Project Critiques

## Na-Rae the fake student
- Project 1: [Document Clustering](https://github.com/Data-Science-for-Linguists/Document_Clustering) by Dan Zheng
   - Strength: has a lot of code
   - Possible improvement: need more code
   - One thing I learned: providing [requirements.txt](https://github.com/Data-Science-for-Linguists/Document_Clustering/blob/master/requirements.txt) along with installation instruction for future guests was a great idea. It streamlines `pip` installation.  

- Project 2: some other project   

## Frances
- Project 1: [Spell Checker Project](https://github.com/Data-Science-for-Linguists-2019/Spell-Checker) by Ting-Wei Shen
  - Strength: This was an ambitious project with complicated code and a lot of data.
  - Possible improvement: The code is in a bunch of different files.
  - One thing I learned: [This](http://norvig.com/spell-correct.html) spell-checker model by Peter Norvig was a super interesting thing to include and provides a way for anyone looking at this project to get an idea of how to build their own spell-checker.
- Project 2: [Diminutive Suffix Productivity](https://github.com/Data-Science-for-Linguists-2020/Diminutive-Suffix-Productivity) by Juan Berríos
  - Strength: This project analyzed language from many different dialects of Spanish. Also the goal was very Lingustics oriented.
  - Possible improvement: The samples from each country were different sizes, so the conclusions could be skewed based on frequency in one dialect over another.
  - One thing I learned: I didn't realize that "statistical measure of productivity" was something that could be looked at in a case like this (diminutive suffixes).  
## Emma
- Project 1: [Arabic Learner Corpus Considerations](https://github.com/Data-Science-for-Linguists-2020/Arabic-Learner-Corpus-Considerations/blob/master/final_report.md) by Anthony Verardi
  - Strength: The researcher had a lot of familiarity with the topic and was also flexible in their approach/research question. They also focused on addressing the challenges that might have arisen when trying to use the ALC for classifying text.
  - Possible improvement: Their conclusion sounded like "yeah, it can do this thing, but not always", which is valid, but is still sort of weak.
  - One thing I learned: They organized their notebook, report, and repository cleanly, which gave me ideas for how to present my own. They also used similar classifiers that I want to use in my project, so seeing how they utilized those was helpful.  

- Project 2: [Gendered Dialogue in Animated Movies](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue) by Cassie Maz
  - Strength: They had a clear hypothesis and goal in mind while analyzing their data. Their presentation was consistent the entire document (hypothesis -> analysis -> conclusion).
  - Possible improvement: More comments in their jupyter notebook file of their analysis would have been helpful while looking through that.
  - One thing I learned: Once again, their repository gave me a good idea for how to organize my project.

## Michael
- Project 1: [Smoking Gun Classification](https://github.com/Data-Science-for-Linguists-2020/Smoking-Gun-Classification) by Sean Steinle
  - Strength: Lots of good graphs. Does a good job managing such a large and complicated dataset.
  - Possible improvement: Graphs often lack titles. This can get especially confusing when there are 2-or-more similar graphs right next to each other.
  - One thing I learned: K-means clustering is a useful technique for classifying continuous, unlabeled data. It can be used with TF-IDF values to classify an unlabeled set of linguistic data. The elbow method can be used to determine the optimal number of clusters.

- Project 2: [Analysis of Japanese Loanwords](https://github.com/Data-Science-for-Linguists-2020/Analysis-of-Japanese-Loanwords) by Lindsey Rojtas
  - Strength: Very detailed, informative notebook. Great statistical analysis, manipulation of data/categories.
  - Possible improvement: Would have been nice to see some discussion of T-tests or ANoVAs.
  - One thing I learned: Seaborn objects have a simple .savefig('FILEPATH') method for saving plots without using python's I/O functions.

## Emily
- Project 1: [Russian Rhyme](https://github.com/Data-Science-for-Linguists-2019/russian_rhyme) by David Birnbaum
  - Strength: Very well documented with a lot of useful explanations about what he did and why; the notebooks are easy to follow and very informative.
  - Possible improvement: There was an awful lot in the repo and I noticed some duplicates/things that could have been condensed to make the overall project easier to follow.
  - One thing I learned: Wow teaching computer rhymes is a complicated process! I learned about finding consonant clusters, syllable structure and many other features necessary to do ML on rhyme.

- Project 2: [Twitter Positivity Analysis](https://github.com/Data-Science-for-Linguists-2020/Twitter-Positivity-Analysis) by Natasha Kamtekar
  - Strength: She did a  good job documenting her progress as things changed and found new ways to get the data she needed (I can relate!). I also liked the use of word clouds to illustrate her findings.
  - Possible improvement: My critique, and she said it herself in the conclusion, would be that the analysis was good but probably could have been a bit more in depth.
  - One thing I learned: How to work around challenges that may arise in gathering the data, and also to save enough time for in depth analysis.

## Abby
- Project 1: [Reddit-Comment-Analysis](https://github.com/Data-Science-for-Linguists-2019/Reddit-Comment-Analysis) by Matthew Borbonus (2019)
	- Strength: Saved a lot of time and effort by choosing a project based on an already-made dataset.
	- Possible imporvement: Seemed to lose track of the goal somewhere along the line.  Final report is disorganized and doesn't really contain any useful analysis.
	- One thing I learned: Using a specific question to be answered and basing the data compilation/analysis around that will make the project much easier.  
- Project 2: [Gendered-Interaction-Online](https://github.com/Data-Science-for-Linguists-2019/Gendered-Interaction-Online) by Katie Thomas (2019)
	- Strength: Final report was extremely good and easy to follow - contained meaningful and well-explained analysis.
	- Weakness: No explanation of what the data is - I have to guess that the "Congress" section is facebook responses to posts from Congress members, but she never really clarifies.
	- One thing I learned: Don't be afraid to drop a few goals if they just don't work out (she dropped "hedging" comparison), and the results will still be interesting.

## Sonia
- Project 1: [Smoking Gun Classification](https://github.com/Data-Science-for-Linguists-2020/Smoking-Gun-Classification) by Sean Steinle
  - Strength: Plenty of text and analysis to talk the audience/reader though the process.
  - Possible improvement: I might have made clearer where the *code* or body of the project is located. It seems to be in the progress report notebooks. Maybe it's me misunderstanding something or how assignment requirements were laid out, but I would think to have files named things like `data-gather.ipynb`, `data-clean.ipynb`, `data-analyse.ipynb` (or `.py`) and then progress report files or notebooks on top of that.
  - One thing I learned: There's an `email` library with classes like `email.parser.Parser()` for parsing MIME email formats
- Project 2: [Sentiment Analysis of Russian-Language News](https://github.com/Data-Science-for-Linguists-2019/Sentiment-Analysis-of-Russian-Language-News/tree/master/code) by Patrick Stoyer
  - Strength: The project had a very clean and easy-to-understand structure to it and it was smart to save intermediate stages like the gensim models and the cleaned text pickles. Also good that he tried two different types of models and different settings for the models.
  - Possible improvement: It wasn't quite clear to me why he had a separate file to create sentiment analysis models for each news source - if they're scripts, why not specify the specific news source as a command line argument? Maybe there was something different going on in each script, but I wouldn't have thought so and wish this could have been explained.
  - One thing I learned: I hadn't seen Gensim's LDA (latent Dirichlet analysis) or LSA (latent sentiment analysis) models before, it was good to see them in action

## Jordan
- Project 1: [ESL-Article-Acquisition](https://github.com/Data-Science-for-Linguists-2019/ESL-Article-Acquisition)
	- Strength: Good use of visualizations, this project also has interesting applications for ESL education.
	- Improvement: Could have gone into much more depth, as they said in their plans for the future it would be a good idea to test for significance. They could also have included many more languages without that much effort.
	- Learned: I learned that Arabic doesn't have an indefinite article
- Project 2: [Blog-Sentiment-Analysis](https://github.com/Data-Science-for-Linguists-2019/Blog-Sentiment-Analysis)
- Strength: Great web scraping work, especially for the scale and heterogeneity of the data. Analyzing polarity was also an interesting concept, especially broken down by astrological sign
- Improvement: Since there was some sparseness in the ages of the users, maybe a system of boxes would have worked better
- Learned: I learned that using web archives to scrape data from ancient history (2004) is possible. That might come in handy in the future.

## Lexy
- Project 1: [Animated-Movie-Gendered-Dialogue](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue) by Cassie Maz (2019)
  - Strength: The presentation of the data was very easy to follow, organized, and meticulous with detail. There was also a lot of data that was included in this project and not just from Disney, but also included Dreamworks which some people may not think of looking at. I'm glad the researcher listed `old_code` so that other people trying to reproduce or potentially add to the code could see when they may have fallen into so the new research would not make those same mistakes.
  - Improvement: I may have looked to see if looking at the script of Wreck It Ralph and Wreck It Ralph: Ralph Breaks The Internet would influence the data. The second movie gets pretty meta when it comes to the Disney Princesses and their stereotypes. I would like to see if there were any changes from how their characters originally aligned with the features and where they were now, if there is any change.
  - Learned: I learned that you can Web scrape movie scripts. I think that is really cool.
- Project 2: [Blog-Sentiment-Analysis](https://github.com/Data-Science-for-Linguists-2019/Blog-Sentiment-Analysis) by Eva Bacas (2019)
  - Strength: Their presentation was also very clear. Having the file names look like code to further separate it from the prose is very helpful. They also separated out what was *About the Project* and what was *Jupyter Notebook Files*. Giving short blurbs about what each of the progress reports contain.
  - Improvement: I might have included some images in the presentation itself so people wouldn't have to click through each file or the file directory to see the findings. Also, I do not see a summary of the full findings on the main page and that would be helpful for anyone doing a quick browse to see what happened in the data, instead of reading through each of the blurbs about the progress reports.
  - Learned: I learned that a mixed effects regression model didn't work or find anything significant with the data. I do not know what this is necessarily but I figured since it is said to be better than ANOVA for what the researcher was looking into, it would work.
