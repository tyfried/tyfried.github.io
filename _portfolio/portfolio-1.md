---
title: "Idealogs"
excerpt: "A crowdsourcing website for understanding complex, controversial topics.<br/><img src='/images/sunesis.png'>"
collection: portfolio
permalink: /portfolio/idealogs
---

<img src='/images/sunesis.png'><br/>

[Idealogs](https://www.idealogs.org) is a crowdsourcing website that adapts a wiki towards a [novel model](https://www.idealogs.org/@0x2) for aggregating and refining contextual information.  The goal is to provide a neutral, trusted repository of context that improves how we interface with complex, controversial topics.  I wrote a more in-depth introduction [here](https://www.idealogs.org/@0x0). I have also developed a [proposal](http://tyfried.github.io/files/discourse.pdf) for future study of this work in graduate school.

## Motivations

* There is a [fundamental lack of context](https://en.wikipedia.org/wiki/Amusing_Ourselves_to_Death) in electronic discourse.  
* Journalism is under siege, both [figuratively](https://issues.org/journalism-under-attack/) and [literally](https://www.nytimes.com/2018/10/11/world/americas/journalists-killed.html)
* A [recent analysis](https://www.nature.com/articles/d41586-018-02934-x) of how true and false news spreads on Twitter found that not only did falsehoods spread more widely and at a faster rate than the truth, but that it was humans, not robots, who were more likely to spread it.
* A nontrivial percentage of peer-reviewed, quantitative research findings appear to be [false as well](https://blog.communitydata.cc/a-proposal-to-mitigate-false-discovery-in-cscw-research/).

## Technology Stack

Idealogs is only possible due to some incredible open source projects.

* Framework: Django.
* Caching: memcached, pylibmc
* Database: PostgreSQL
* Task management: Celery, rabbitmq
* Server: nginx + gunicorn
* Markdown: Pandoc, with help from Pandoc-Sidenote
* Typography: Tufte CSS
* HTML post-processing: Beautiful Soup, Bleach
* Diffs, Patching: Diff-Match-Patch
* Search: Elasticsearch
* Metadata: Zotero

<!-- ## Motivation

### Mistakes

The saying goes: *we learn from our mistakes*.  Yet online knowledge communities seem to focus more on broadcasting conclusions, and less the mistakes, disputes, and bad ideas that directly led to them.  This makes sense: if your goal as a community is to accumulate knowledge as efficiently as possible, then presenting errant thoughts will necessarily distract the audience away from your message.  But if your goal is to accumulate **understanding**, then these missteps require a mechanism for greater visibility.


### Discourse

The state of public discourse is unhealthy at best.  Some examples:
* Journalism is under siege, both [figuratively](https://issues.org/journalism-under-attack/) and [literally](https://www.nytimes.com/2018/10/11/world/americas/journalists-killed.html).
* A [recent analysis](https://www.nature.com/articles/d41586-018-02934-x) of how true and false news spreads on Twitter found that not only did falsehoods spread more widely and at a faster rate than the truth, but that it was humans, not robots, who were more likely to spread it.
* A nontrivial percentage of peer-reviewed, quantitative research findings appear to be [false as well](https://blog.communitydata.cc/a-proposal-to-mitigate-false-discovery-in-cscw-research/).

In each of these crises, I see an opportunity for an unbiased collection of contextual information to make a difference: for the news industry, a vehicle to showcase quality journalism; for social media, a home for more nuanced discussions in search of truth; and for academia, a place for the digestion of intricate concepts. What I am suggesting is not a replacement for these mediums, but rather a mechanism for placing them in their proper context.

## Model
I believe that all contextual information can roughly be categorized as
* **writings**, the creative work that we produce to try to make sense of the world;
* **statements**, the subsequent claims we derive from these writings; and
* **questions**, the unknowns arising when two or more of these statements directly contradict.

These three categories reinforce each other: writings argue towards particular statements, contradicting statements suggest a particular question, and unanswered questions inspire new writings.  Together, they form a cycle (see above) which captures how complex ideas evolve within communities of inquiry. -->
