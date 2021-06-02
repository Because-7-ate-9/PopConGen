# PopConGen
Building AI course project - Popular Content Generator

## Summary

By looking at the historical Top Rated content for a given social media site, we should be able to forecast how long certain types of content will remain relevant. This could be expanded to include correlating the content with current events to predict what types of content to produce and which topics or keywords should be mentioned to make it popular. 

## Background

Consumers of online content are capricious; there is no sense of loyalty, the content is often more important than the creator. A tool like this one would allow creators to stay on top of current trends without having to spend the time combing through lists of top trends or watching the content of others. There are many methods that people use in attempts to get more views/likes/retweets/etc. - clickbait titles, keyword stuffing, controversial language, the list goes on. This is an attempt to automate that process while also (hopefully) resulting in a better experience for content consumers. The more creators who use this, the less duplication of content consumers would see.

## How is it used?

Describe the process of using the solution. In what kind of situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

## Data sources and AI methods
This utility would use publically available information in the form of:
* Top content lists
* News feeds
* Hashtags

Some data could be collected via web scraping, but some may require the use of APIs such as the [Twitter API](https://developer.twitter.com/en/docs)

## Challenges

In theory, with enough ability to customize the search/prediction functions, you could target a specific person and "scoop" them by predicting what they would put out next and beat them to it. With that in mind, the tool should not allow for that level of customization.

It's also possible when major events dominate the news cycle, the tool will incorrectly recommend producing more content on it.

## What next?

The ability to expand the capabilities of the tool is essential for it to continue to be useful in an ever-evolving world:
* specify a topic or list of topics to limit the content recommendations (i.e. video games, start a TikTok challenge that will take off)
* correlate with current events
* have the system analyze existing content and only recommend things if they have not already been done
* recommend style mashups (i.e. video that recaps the day's news while giving a makeup tutorial)

## Acknowledgments

* Recommendation systems are a well-known application of Machine Learning and AI, this is just an extension of that to recommend new content to be created rather than existing content to be consumed
