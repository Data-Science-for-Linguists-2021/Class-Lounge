# [Linguistic Styles of Podcasts](https://github.com/Data-Science-for-Linguists-2021/Linguistic-Styles-of-Podcasts)

Visit (Sonia)
- You have a pretty good list of different podcasts from different genres that you've managed to find transcripts for
- Probably it would be good to be careful about drawing conclusions for an entire genre based on just two podcasts from that genre. You seem aware of that though
- It was interesting to see how spiders are made and what the code for that really looks like in real life
	- Reply: Thanks for your comments!  Since I didn't know what making spiders involved when we I made the project plan, I was hoping to have transcripts from a much larger variety of podcasts, but you're right that I have enough.  That being said, the genre-based plan won't be as comprehensive as originally planned.

Visit (Michael)
- I can tell you've put a lot of effort into customizing spiders to get data from a bunch of different sources, which I think will really pay off in the analysis portion!
- There's a lot going on in the spiders folder. If possible, I recommend running the spiders on your personal computer, converting the output to dataframes as part of the script, and saving said dfs as one or more csv files. Then, load up all the files and clean them all in a single jupyter notebook. This removes the need to define + run every spider in jupyter itself, which seems to flash a lot of text. 
- I like that your data includes the date of the podcast. I might implement the same in my own spider + analysis
	- Reply: Thanks for your comments!  The spider folder organization is a good idea.  I initally tried to make the data into csv files, but they never loaded correctly.  Now that I have all the transcript text I can get, I'm going to cat the dataframes into one giant dataframe and add /spiders to .gitignore.