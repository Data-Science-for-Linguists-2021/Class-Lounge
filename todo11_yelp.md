# To-do 11: Poking at Big Data (Yelp)

## Na-Rae the fake student:
- My 2-year-old ThinkPad laptop did well! It has ... RAM, which worked ok with this much data, etc. Grepping through the whole of xxx json file took...

## Sonia
- I have a 2019 MacBook Pro with 8-core Intel i9 processor and 16 GB memory. It took about 90 seconds to grep horrible or to grep scruptious on the reviews json file. Running process_reviews.py took less than half a second for up to 1000 lines, then almost 40 seconds for 1000000 lines. I tried it with the full reviews json amount of 8635403 lines and it then took over an hour. CPU usage varied between 50 and 80% and processing the full number of lines ate up pretty much all the memory it could get.

## Emily
- My computer is a 2018 MacBook Air with 16GB of memory and a dual-core intel core i5 processor. For the grep word searches it took between 2-3 minutes. For the process_reviews.py script it was super quick (about a second or so) for 1000-10,000 lines, slightly more (maybe 4-5 seconds) for 100,000 lines and then a little over a minute for 1 million lines. I then decided to try 4 million, a but  less than half, and that took about 40/45 minutes. CPU usage was pretty high, anywhere from 50 to 90, but spent most of the time hovering at an average of 70% I would say.

## Emma
- My mac is from 2015 with 16 GB of memory and a Quad-Core Intel Core i7 processor. It only took about 10 seconds to return the amount of lines that had scrumptious/horrible in them. When using only 10 lines in the FOO json, it took less than a second to process. It was still really quick with the 1000 reviews, but when it came to 1 million reviews, it took about a minute to complete. The CPU usage was really high, staying at the high 90s the entire time. Based on how long it took for a million, I was kind of too scared to go any bigger as just downloading the yelp data stressed my laptop out quite a bit. In order to undergo more computationally demanding processes, well, it would take the powers of a \~supercomputer\~.

## Abby
- I have a 2019 HP Envy with 8 GB of RAM and an AMD Ryzen 5 processor.  It took 2 minutes to do a word count on the yelp_academic_dataset_review.json (8,635 | 967332174 | 6936678061).  Each review has a review_id, user_id, review text, and date/time.  The tips file looks like it has little blurbs about a certain business from users.  It took about 20 seconds for my computer to do line counts for "horrible" reviews ( 127,047).  The "horrible" reviews themselves were mostly 1 star with a few high ratings mixed in.  "Scrumptious" took about half the time and had only 13,195 lines, mostly consisting of 4- and 5-star reviews.  It took a few seconds for FOO's of up to 100,000 to run, but as soon as FOO hit 1,000,000 reviews, my computer crapped out and I got a memory error.  My CPU at no point looked like it was working extra hard, so I'm not really sure what happened.  I need more RAM . . . 