# [Flüchtlingskrise Sentiment Analysis](https://github.com/Data-Science-for-Linguists-2021/Fluechtlingskrise-Sentiment-Analysis)
## Emily Martin's project

Welcome to my guestbook! Please enjoy looking around at the work I have accomplished so far :)
  Note: This is very much a work in progress

Visit (Sonia)
  - Structure was easy to follow and I admire your dedication in manually gathering 100 news articles from 2015 on the Fluechtlingskrise from that one news source
  - For the source you did scrape automatically, I couldn't find explanation of why you limited yourself to 100 articles
  - I learned more about how much work web scraping can be!
    - Thanks for stopping by Sonia! Those article links were certainly a bit of a pain. I originally thought to keep my samples the same size but you are right there is no reason to limit the number to 100 if I don't have to.

Visit (Abby)
  - Very clear and concise goals with an easy-to-understand framework.  Good topic choice - I'm genuinely interested in what you're going to find.
  - It seems like it's going to be very difficult to train a classifier on unlabeled data.
  - Beautiful soup is extremely versatile.  I've wasted a lot of time with my own web scraping by not using it.
    - Thanks for your comments! I certainly have come to appreciate beautiful soup a lot, and I would definitely recommend it as an option to anyone doing scraping.

Visit (Michael)
  - Your project plan file makes it very clear what the goals are of this project, and the project itself is just very well organized. I espeically appreciate how much effort went in to acquiring this data. I only had to scrape from one site and that was a handful. I imagine 4 sites must have been even more trying.
  - A couple of the JNB's (especially zeit.ipynb) throw a lot of text on the screen at once. This could stand to be cut down a bit (though I understand changing it might be a little difficult w/ how it's set up).
  - I am very intrigued by lemmatizers and spaCy as a whole and am curious to see if they might help with my own analysis.
      - Thanks for visiting! I agree that there is a bit more text than is probably necessary, I will make an effort to cut that down. From what I have seen of SpaCy it is super cool and super useful, I recommend!

Visit (Frances)
  - Your presentation jnb is really well organized and it’s cool to see you using spacy (since we just talked about it in class)!
  - While it’s probably useful for you to help visualize there’s a lot of text returned/printed out on the screen that takes up space.
  - The lemmatizer is so cool! It looks super useful and I might try and use it in my project too.
      - Thanks for stopping by! The lemmatizer is definitely very cool and I had a lot of fun feeding it different verb forms :)


Visit (Abby again)
  - Very nice and easy-to-understand charts in your main jupyter notebook
  - You wrote that you're pretty sure that the most useful feature, "flüchtling", isn't negative even though your classifier "thinks" it is.  Since it's the most useful feature, see if you can do a little research and see what German citizens say.  That seems like something you'd want to be sure about.
  - I've never seen *pass* in python before.  
      - Thanks for your advice! I did reach out to my German family and they confirmed that Flüchtling doesn't carry any negative connotation on it's own. On the flip-side they said they thought "migrant" (migrant) was more negative.

Visit (Emma)
  - Your topic idea is honestly so interesting, and I’m really looking forward to your presentation and final analysis! You also knew tons of information about the topic, which really helped.
  - I really don’t have anything to say here, but it looks like you still have some ideas for future analyzing which will be cool to see! Also, I see in the progress report that there might be confusion in the sentiment scores about negativity, but you have obviously recognized that, so it’ll be interesting to see how you work with that!
  - scraping for specific terms, a little bit of German :), more about SpaCy
      - Thanks for visiting! There are definitely some things that need to be tweaked, but I am hoping to clear those up soon:)

Visit (Sonia again)
  - You have a lot of ideas of questions to try out for the analysis, I especially liked the graph for the one news source that showed the evolution of their negativity/positivity rates over time. Will be good when you've got that for the other sources too to compare.
  - Maybe using articles as the level of the sentiment analysis isn't fine grained enough especially given the smaller size of your dataset, so maybe (if you were to keep going with this project lol) it would be valuable to do sentiment analysis at the sentence or paragraph level. Maybe if the two terms are used in different paragraphs of the same article, it would be a good point of comparison as to what sentiment or other conditions led to the choice of one over the other.
  - I wonder if it's just coincidence that the more right-leaning sources tended to have more restrictive data policies, not offering an API or generally not being data science-friendly. Probably would need more sources to determine that and it isn't directly related to your project, but now I'm curious if there's a pattern there
