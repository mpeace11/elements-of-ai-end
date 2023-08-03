
# Rabbit Hole 

Final project for the Building AI course

## Summary

When in an academic rabbit hole, this could review your paper/data and articles you've cited in said paper and recommend more articles to cite or review based on particular criteria (dissenting opinions, supporting work, possible related future directions, etc.). It could also summarize the findings of articles to make it easier to decide which to look into. 

## Background

I want to be a neuroscience researcher. In a field this new, there is a lot of literature to wade through in a rabbit hole to determine the quality, topic, an interconnectedness to your own topic for. I expect some level of difficulty on this front and have seen it in PhD students I've worked under who were on a time crunch to graduate. A tool that can help sort and present articles in a more palatable fashion could make writing and reviewing papers much easier. The inclusion of a feature that allows for articles to be presented based on particular criteria beyond relevancy (ex. dissent, agreement, relatedness, etc.) could also prove quite useful - like a search filter. A summary feature that sums up suggested literature could streamline this process in cases where there is little time left on the clock. 

## How is it used?

I'd like this to be a viable solution for those who are inexperienced in coding, so it, in my opinion, it would be best formatted with options to input your paper, select a search filter for relevant papers, and run. The system would then return literature relevant to both the inputted paper and the search filter based upon key words (and their frequency - tf-idf) that its creator would set. Users would then be asked to rate its performance and the relevancy of returned papers to allow it to learn and adapt. This is likely to be used by people still in school or in academia, though expansions to other fields and formats could be possible if other forms of writing are accepted (in fields like business, marketing, etc, accepting powerpoints and pulling relevant data from the company could be useful). In any case, the most important thing to consider with this system is its users time constraints. In a case where there are weeks to look through relevant literature and data for a paper, that is a viable and good option. This is a solid alternative when a user is low on time or needing to filter through large numbers of articles. 

## Data sources and AI methods

First, a paper must be inputted by a user for working on. This will be what the system uses to glean subjects/key words to look for in relevant papers. After this, there are two possible ways of gathering literature for a user. The first is requiring users to submit papers of their own to use the software (beyond the paper they have inputted to work on). This means the system would be searching through its own records to draw out papers for its users. The second way would be to have the system search academic databases for papers that may or may not belong to its users. Regardless of path taken, papers are then rated by users based on relevancy so the system can learn. Either way, some data comes from the user (the inputted paper and rating of the AI's effectiveness) and some from other people (the papers being presented). 

## Challenges

The Rabbit Hole software would not solve problems with plagarism in academia, and it may encourage it. Without having looked through large numbers of papers in order to draw information for a paper, an academic short on time may resort to plagarism, or at least the regurgitation of already known information instead of the creation of new information. It also doesn't guarantee accuracy. This system involves no feature to fact-check the articles for up-to-date and correct information, so the articles being cited may be weak. 

## What next?

One first step in moving forward with this project would be to address its challenges and limitations. Features could be added to fact check information and check for plagarism in final docments written that used the AI. Additionally, a lot of work would still need to be done on the users end. The Rabbit Hole can simply draw relevant information, not determine its quality or place in the article. This is something that would still need to be done by a person (though I do not see this as a bad thing). More importantly, though, is creating it. To do this, I'd either need to learn to code or recruit someone who can.


## Acknowledgments

This idea was inspired by my own experience in research as well as those of graduate students I've worked under in finding relevant literature for research. 
