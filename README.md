# Hacker News Pipeline

### Project completed as part of Dataquest's Data Engineering path.

-------

## Introduction
In this project, we'll work with a sequence of basic natural language processing tasks using a created pipeline class. Our goal is to understand the tech topics in 2014 by finding the top 100 keywords of Hacker News posts in 2014. 

Our input data is from Hacker News (HN), a website about computer science and entrepreneurship posts that community vote stories,  API that returns JSON data of the top stories in 2014. The list of JSON posts is in 'hn_stories_2014.json'.

We will deal with the following keys of the posts:

* created_at: A timestamp of the story's creation time.
* created_at_i: A unix epoch timestamp.
* url: The URL of the story link.
* objectID: The ID of the story.
* author: The story's author (username on HN).
* points: The number of upvotes the story had.
* title: The headline of the post.
* num_comments: The number of a comments a post has.