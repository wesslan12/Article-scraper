# NLP Assignment

In this project, I used a data set containing a random sample of public Facebook posts by members of the U.S. Congress from 2017.1 The broad objective in this project was to explore what topics were discussed, and variation by party membership. The dataset contains 6752 rows and 4 columns. Each row describes a facebook message. In addition to the actual text of the post (message column), we also have three metadata columns: the document id (doc_id), the political party which the focal individual is a member of (party), and displayed screen name (screen_name). I used topic modelling and word embeddings to explore what topics were discussed and how they vary by party membership. 
#Part 1 Topic modelling

<img width="831" alt="image" src="https://github.com/wesslan12/Article-scraper/assets/82345548/3b915d16-b671-446f-ab2c-db9583e4adf4">

Overall, these six topics are pretty clear-cut. The interpretation was also made easier by considering the relative weight (probabilities) of the words within the top 15. For some topics, the is the distribution within top 10/15 is rather equal (e.g., "Opiod crisis" topic), while for others it is very unequal (e.g., "Trump" topic). In terms of general assessment, I would say that most topics appear rather distinct and interpretable.

<img width="609" alt="image" src="https://github.com/wesslan12/Article-scraper/assets/82345548/9490be5d-430b-449a-ac7f-371071bf3ce7">

Examining the climite crisis topic I would suspect that republicans talk about this less compared to democrats. Looking at the coefficient we note that such assumptions certainly appears to be the case. Republicans talk about climate related policies approximately 9 % less compared to democrats.
#Part 2 Word Embeddings
There are some meaningful differences between the republicans and the democrats in terms of the most similar words for “care”, “reform”, and “military”. In the case of energy, the democrats are talking more in terms of renewable sources and what could be interpreted as “green energy source”, the republicans on the other hand are talking about it in terms of cost. In terms of healthcare it is very clear that the democrats sees public healthcare as something beneficial (benefits) whereas the republicans focuses on costs (skyrocketing) For the other two they are more less the same. For military, the democrats are talking more in terms of their sacrifices and honoring the fallen ones, while republicans talk about the military more in terms of foreign relations and geopolitical concerns, they seem to be signaling the”readiness”, “strenght”, and “involvement” of the US military.

<img width="280" alt="image" src="https://github.com/wesslan12/Article-scraper/assets/82345548/6ea5db0e-1f3f-483c-80b9-e61b567d1dbc">

<img width="331" alt="image" src="https://github.com/wesslan12/Article-scraper/assets/82345548/843e9fcf-fdf9-421e-90c3-ec89ebb29efa">

<img width="331" alt="image" src="https://github.com/wesslan12/Article-scraper/assets/82345548/49d856d1-5c5c-4492-8de3-24b8f81f80b3">






