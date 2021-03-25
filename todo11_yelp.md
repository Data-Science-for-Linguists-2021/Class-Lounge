# To-do 11: Poking at Big Data (Yelp)

## Na-Rae the fake student:
- My 2-year-old ThinkPad laptop did well! It has ... RAM, which worked ok with this much data, etc. Grepping through the whole of xxx json file took...

## Sonia
- I have a 2019 MacBook Pro with 8-core Intel i9 processor and 16 GB memory. It took about 90 seconds to grep horrible or to grep scruptious on the reviews json file. Running process_reviews.py took less than half a second for up to 1000 lines, then almost 40 seconds for 1000000 lines. I tried it with the full reviews json amount of 8635403 lines and it then took over an hour. CPU usage varied between 50 and 80% and processing the full number of lines ate up pretty much all the memory it could get.

## Emily
- My computer is a 2018 MacBook Air with 16GB of memory and a dual-core intel core i5 processor. For the grep word searches it took between 2-3 minutes. For the process_reviews.py script it was super quick (about a second or so) for 1000-10,000 lines, slightly more (maybe 4-5 seconds) for 100,000 lines and then a little over a minute for 1 million lines. I then decided to try 4 million, a but  less than half, and that took about 40/45 minutes. CPU usage was pretty high, anywhere from 50 to 90, but spent most of the time hovering at an average of 70% I would say. 
