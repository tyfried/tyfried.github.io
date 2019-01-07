---
title: "Testing Syntax"
excerpt: "testing testing."
collection: reports
permalink: /reports/test
---

<img src='/images/sunesiary.png'><br/>

Sunesiary adapts a wiki towards a novel model for aggregating and refining contextual information.  The goal is to provide a neutral, trusted repository of context for helping to break down and understand controversial topics.  I have developed a [proposal](http://tyfried.github.io/files/discourse.pdf) for future study of this work in graduate school.  A proof-of-concept is available at [www.sunesiary.org](https://www.sunesiary.org).

## Motivation
The state of public discourse is unhealthy at best.  Some examples:
* The journalism industry is [under](https://issues.org/journalism-under-attack/) [siege](https://www.nytimes.com/2018/10/11/world/americas/journalists-killed.html); it also has a tendency to incentivize [entertainment over reporting](https://en.wikipedia.org/wiki/Amusing_Ourselves_to_Death).
* A [recent analysis](https://www.nature.com/articles/d41586-018-02934-x) of how true and false news spreads on Twitter found that not only did falsehoods spread more widely and at a faster rate than the truth, but that it was humans, not robots, who were more likely to spread it.
* A nontrivial percentage of peer-reviewed, quantitative research findings appear to be [false as well](https://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.0020124).[^1]

[^1]: Credit to the Community Data Science Collective, I first learned about this issue on their [blog](https://blog.communitydata.cc/a-proposal-to-mitigate-false-discovery-in-cscw-research/).

In each of these crises, I see an opportunity for an unbiased collection of contextual information to make a difference: for the news industry, a vehicle to showcase quality journalism; for social media, a home for more nuanced discussions in search of truth; and for academia, a place for the digestion of intricate concepts. What I am suggesting is not a replacement for these mediums, but rather a mechanism for placing them in their proper context.

## Model
I believe that all contextual information can roughly be categorized as
* **writings**, the creative work that we produce to try to make sense of the world;
* **statements**, the subsequent claims we derive from these writings; and
* **questions**, the unknowns arising when two or more of these statements directly contradict.

These three categories reinforce each other: writings argue towards particular statements, contradicting statements suggest a particular question, and unanswered questions inspire new writings.  Together, they form a cycle (see above) which captures how complex ideas evolve within communities of inquiry.

## Sunesiary

[Sunesiary](https://www.sunesiary.org) is a project that take this model and applies to it principles of [peer production](https://en.wikipedia.org/wiki/Peer_production) in order to understand controversial topics.  


<!-- ## Challenge
Assembling such context and sharing it with a wide audience presents a challenge. For one, context is highly subjective, and disputes over what is contextual frequently devolve into disputes over what is true. The conventional solution to this problem is to feature only that which is indisputable, or nearly so, and obscure the rest. I find this approach lacking in that humans can learn just as much from mistakes, bad ideas, and outliers as they do from the wisdom derived from such missteps. To make matters worse, the volume of contextual information for a given topic is far too overwhelming for any one individual to make sense of. Most modern attempts to manage this involve applying machine learning techniques to mine knowledge from massive data sets. These approaches fall short in their negligence of the capacity of the human brain, which can make complex insights that elude even the most expertly programmed computers. -->
