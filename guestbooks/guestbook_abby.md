# [Linguistic Styles of Podcasts](https://github.com/Data-Science-for-Linguists-2021/Linguistic-Styles-of-Podcasts)

Visit (Sonia)
- You have a pretty good list of different podcasts from different genres that you've managed to find transcripts for
- Probably it would be good to be careful about drawing conclusions for an entire genre based on just two podcasts from that genre. You seem aware of that though
- It was interesting to see how spiders are made and what the code for that really looks like in real life
	- Since I didn't know what making spiders involved when we I made the project plan, I was hoping to have transcripts from a much larger variety of podcasts, but you're right that I have enough.  That being said, the genre-based plan won't be as comprehensive as originally planned.

Visit (Michael)
- I can tell you've put a lot of effort into customizing spiders to get data from a bunch of different sources, which I think will really pay off in the analysis portion!
- There's a lot going on in the spiders folder. If possible, I recommend running the spiders on your personal computer, converting the output to dataframes as part of the script, and saving said dfs as one or more csv files. Then, load up all the files and clean them all in a single jupyter notebook. This removes the need to define + run every spider in jupyter itself, which seems to flash a lot of text.
- I like that your data includes the date of the podcast. I might implement the same in my own spider + analysis
	- The spider folder organization is a good idea.  I initally tried to make the data into csv files, but they never loaded correctly.  Now that I have all the transcript text I can get, I'm going to cat the dataframes into one giant dataframe and add /spiders to .gitignore.

Visit (Frances):
- You seem to have a wide variety of podcasts/types which is definitely a strength.
- Do you plan on inputting the years for This American Life?
- You say you’re going to scrape from pdfs which is very interesting, I wasn’t aware you could do that!
	- I forgot to commit my most recent changes, but after many, many hours of frustration I finally scraped the pdfs (195 of them) using something called PDF plumber.  The year and/or episode numbers weren't listed anywhere on the page for a lot of podcasts, so that's why those are missing.

Visit (Emma):
- After reading your progress report, it seems like you know what you want to do next for your analysis portion, so that’s good! I think it’ll be really cool to see then end result of your project!
- Like I said, you seem to have a good analysis idea set up, so this might be too much, but if you had time, I think it’d be pretty cool if you tried to see if a classifier could predict whether a certain podcast is a comedy, or an educational, and maybe what words were heavy indicators!
-  I don’t listen to podcasts, so I was surprised at how many categories there are!
	- Your suggestion is actually part of my plan!  Sorry if I didn't make that perfectly clear.  I'll include trying to win over non-podcast-listeners to the podcast-listener lifestyle as part of my presentation.

Visit (Emily)
- You definitely did a lot of work with customizing spiders which is impressive and I also liked the level of linguistic analysis you added to your dataframes - different POS frequencies, top bigrams, lemmas, etc.
- Maybe this is just a personal thing, but I think a few more comments would have made your data notebook a little easier to follow.
- I only just started realizing how useful defining custom functions is, so I liked looking at all, and learned a lot from, the ones you made.

Visit (Michael again)
- Everything looks much improved since I last visited. It is very easy to tell what everything is and it looks like you've put a lot of effort into cleaning/organzing your dataframes!
- I think it would be helpful to get a few more looks at the dataframe as more data is added on to it. At a certain point, enough new columns are added on that between one preview and the next, some of the middle columns get dropped. Ultimately not a big deal, but I think it makes it easier to visualize what's being added. 
- Got to say, I completely forgot about google kbands! If I have time, I'll probaably try implementing that in my own analysis to see what it can tell me about my own data.