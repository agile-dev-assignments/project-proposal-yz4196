# Project Proposal: analyzing and recommending movies 
Proposal by Chris Zheng
## What and why?
I propose a project that aims to build a program that processes movie review data and optionally make recommendations to users based on their preferences. The bulk of the function of this hypothetical program is information extraction, which seeks to automate some of the more tedious aspects of finding new entertainments.

Imagine a new movie coming out, the first question many people ask about is whether the movie is good. While that information is not difficult to locate online, it is a difficult and time consuming proccess that is additionally hindered by the subjectivity of each individual. In this way automating the information extraction process is helpful. Additionally, the features of the program can be multifaceted, including automatic generation of summary for lengthy reviews, and extracting the key sentiments across multiple reviews. Of course, the program needs not be limited to movies, it can be extended to apply to  different medias such as music/video game etc.
## For whom?
The proposed program is helpful to those who have difficulty selecting a new movie to watch, or those that want to have a summarized version of the critical reception of a specific movie.
## How?
The proposed program should integrate several different features. Firstly, the program should extract relevant information about the movie from different reviews. Basic information extraction techniques, such as TF-IDF representation can be used to pull the most prevalent information from the reviews and formulate a list of keywords for the users. User reviews tend to be polarized, as such sentiment analysis can be incorporated if the polarity is not explicitly given, to give users an overview of the quality of the film.

Secondly, the program may incorporate a summarization function that provides a more succinct version of lengthy review; NLP techniques will be used to accomplish this.

Thirdly, the program can try to predict other movies that a specific user may enjoy. This may be achieved by examining past evidences of the user's preferences, and recommend based on similar users; alternatively, the program can recommend based on similarity in the extracted information of the specific movies. Either case can be accomplished via machine learning.
## Scope
One of the challenges in program like this is the availability of data. In this case, data may potentially be acquired from scrubbing sites such as IMDB. Other than that, the program mostly utilizes some techniques from NLP/machine learning, which should be doable if the participants have some level of familarity with the subject. 
