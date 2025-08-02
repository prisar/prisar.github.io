---
layout: post
title:  "Video analysis with LLM"
date:   2025-08-02 00:00:00 +0000
---

Video analysis is the task of performing things like summarization, visual understanding, and intelligence. 
These tasks can be done with the help of multimodal vision language models. Right now, the models are quite good for short videos. 
But what about longer videos? Does they perform well for 6 hours of video? How to even pass long videos to LLM?

### Chunking

One common way to handle longer videos would to split the video into multiple chunks. 

### Summarize

We can then summarize the chunks to get a visual understanding of the content.

### Relevancy

For retival of chunks we need to score the chunks based on some metrics. Let's consider it to be relevancy. 

Once the chunk level is produced we can use the list to calculate the relevancy of each chanks grounded based on the user query. 
We will then sample the top K chunks.

### Generate response

The final response of the user query will be generated based on the relvant chunks.
