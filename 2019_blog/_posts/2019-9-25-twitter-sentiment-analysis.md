---
layout: post
title: "Twitter Sentiment Analysis"
date: 2019-9-25 02:32
description: Sentiment Analysis
image: /assets/images/papers.png # Add image post (optional)
headerImage : false
tags:
- Python
- Twitter
author: vivekkaushal
category: projects
projects: true
---

This project is a simple script to gauge public sentiment about a search term -- which could be anything, a company, a person, a country etc.

### Usage

- This project uses the official Twitter API. Create a developer profile on Twitter and paste the following data in the code :

```python3
con_key = ""
con_secret = ""
access_token = ""
access_token_secret = ""
```

- Enter the search term on being prompted.

### Output

- **Sentiment :** A score on negative-positive sentiment of tweets on the search term -- scored from -1 to 1.
- **Subjectivity :** A percentage score for how subjective a tweet is, 0% implies entirely objective.

**Link to code repository:** [https://github.com/kaushalvivek/twitter-sentiment-analysis](https://github.com/kaushalvivek/twitter-sentiment-analysis)