# The Barbie Movie Review: Woman vs. Man 

## Introduction 
We chose to analyze two different reviews of the Barbie movie. One was written by a woman and the other, by a man. We chose to analyze these two reviews because we hypothesizes that the two reviewers would have different opinions of the movie. We plan on doing a polarity test of the words in both of the reviews and making a word cloud of the most commonly found words in each of the reviews. This can be used to see the difference in tone. We predicted that they would both have positive polarity but the most commonly used words would be different. 

## Data and Data Preparation
We got the text from a website, so we used `rvest` to scrape the data from two different websites. Both of the reviews individually contained around 1,000 words. The data we are analyzing is simply a review on the same movie by different people. In order to prepare for the analysis, we scraped the words from the website and and saved that as our data. In addition, we also cleared any unnecessary punctuation, numbers, white space, and turned everything into lowercase.  

## TF-IDF Analysis
As we predicted, the most commonly used words for both of the texts are different. The most commonly used word for the review written by a man is "men". On the other hand, the most commonly used word in the review written by a woman is "barbie". This is significant because the man's review was solely about the movie from a man's perspective whereas the woman's review was about the movie itself, irrespective of a perspective based on gender. 
Although at first glance, this may seem because of gender, we hypothesize that this is not entirely the case. This is because when we look at the background of the man, he is a political strategist, whereas the woman is an actual movie critic. This explains the difference in perspective. The man is writing about the movie from a societal perspective whereas the woman is writing about the movie its self and literally critiques about technicalities, etc. 

## Sentiment Analysis 
We predicted that the man's review would have an overall negative polarity whereas the woman's review would have a positive polarity. Looking at the `p2`, or the one with two words in front and two words after, the male perspective of the review had a much more negative review with the most minimum average polarity being `-1.565867` where the female perspective was `-1`. The maximum polarity for the male review was `0.5144958` and the female review was `0.7071068`.
However, when we look at the individual words themselves, the female polarity is much more extreme. The female review's maximum and minimum polarities were, respectively, `0.7715167` and `-1`. On the other hand, the male review's maximum and minimum polarities were, respectively, `0.5144958` and `-0.7504788`.


## Results 
Our hypothesis of the most common words on the two reviews would be different. We were correct that it was different but we were surprised that the most common word for the male review was "men." In addition, some of the other common words found in the male review was "patriarchy", "self-hate", and "manchild". The female review contained words such as "Gerwig" (the movie's director), "oscar", and "critic". These words display a review of the movie from the point of view of a movie critic. The words found in the male review, however, showcases the review written from a societal perspective. 
In addition, we were also surprised that the polarity of the individual words for male review was less extreme. We were expecting the male review to have a lower average polarity. However, looking at the two words before and after, this hypothesis was correct.
If we were to conduct the study again in the future, we would chose reviewers with similar backgrounds. This is because the male reviewer being a political strategist while the female reviewer was a movie critic makes the context of the review entirely different. It would make more sense in the future if both reviewers came from similar backgrounds. 

## Conclusion 
We found that the common words for both reviews were different; with the most common word for the male review being "men", and "Barbie" for the female review. Although our hypothesis was correct, we find the words to be surprising. In addition, the polarity for the individual words was different that what we had predicted. Overall, we believe that these findings can be explained by looking at the background of the reviewer. If we were to do this study again in the future, we believe reviewers coming from similar backgrounds would give us a more cohesive data. 

## Citations
Lemire, C. (n.d.). Barbie Movie Review & Film Summary (2023): Roger Ebert. movie review & film summary (2023) | Roger Ebert. https://www.rogerebert.com/reviews/barbie-movie-review-2023

Olla, A. (2023, August 1). I wept for Ken: Why men have the most to gain from watching Barbie | akin olla. The Guardian. https://www.theguardian.com/commentisfree/2023/aug/01/barbie-film-ken-ryan-gosling-patriarchy 
