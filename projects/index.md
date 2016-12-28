---
title: Projects
layout: single
author_profile: true
share: false
comments: false

header:
  image: IMG_0578.jpg
  caption: Picture taken by David Dornseifer (South Lake Tahoe, CA, US)
---

Here is a small collection of personal projects I'm working on from time to
time.


---

### Data Science & Machine Lerning
The power of statistics and the recent breakthroughs in Machine Learning,
especially in the area of deep-learning are really fascinating.   
Here I'm playing around with the technologies available like the `sklern` or
`tensorflow` libraries and see how they can be used to learn from different kind
of data and what kind of applications are possible. You can find some
IPython Notebooks (Jupyter) in this [GitHub](https://github.com/dpdornseifer/jupyter_notebooks) repository.


---

### Concurrent Python
Right now, I'm interested in how you can make python work best for you in
scale-up and scale-out scenarios and how you can get around the GIL issues if it
comes to multi-threading and CPU intensive tasks.
On github there is a small repository available [Concurrent Python](https://github.com/dpdornseifer/concurrent_python) with some `playground`
scripts to explore the behavior and measure the performance.


---

### aiogithub
While I was working on a GitHub Enterprise related project at work I noticed how
much interaction is necessary to manage repositories via the
[Git Data REST API](https://developer.github.com/v3/git/). That's why I decided
to write a library which is non-blocking (powered by aiohttp) and abstracts all
this interactions / management tasks from the user. The
[aiogithub](https://github.com/dpdornseifer/aiogithub) library is in very early
`alpha` stadium :) due to a lack of time.  
