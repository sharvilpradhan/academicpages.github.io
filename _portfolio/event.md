---
title: "Event Timeline Detection"
excerpt: "Understanding and discovering the cause and effect relation between a given pair of sentences."
collection: portfolio
---



## Description
This project aims to understand cause and effect relation between a pair of sentences. \
For example: 1. The ball hit his head.
             2. He started crying in pain.
             
In the above pair of sentences, sentence 2 makes sense only if sentence 1 has occurred. So the correct order of these events coccurring woud be - ball hitting his head followed by him crying in pain.

## Motivation
Achieving this task can be useful to create chatbots that can understand link between events, proving beneficial in answering questions by accessing knowledge base.


## Advantage
I have used a variation of doc2vec technique to create word embedding techniques which takes into consideration the occurrence of the pair of sentences in the entire document under consideration. The traditional word2vec and SpaCy word embedding techniques consider the pair of sentences as stand-alone. So, using the inverse document frequency, I am able to associate words closer to one another while also discarding stop words or words that are extremely common and not associated to the particular sentence.


[Source code](https://github.com/sharvilpradhan/event-timeline-detection)
