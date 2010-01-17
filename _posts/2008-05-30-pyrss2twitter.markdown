---
layout: post
title: PyRSS2Twitter
---

Last weekend, I wrote a python script [1] that takes in RSS feeds, and posts them to a specified twitter account. Because the script I wrote then was a total kludge and often ran into rate limiting at twitter, I scrapped it and started over. Today marks the completion of iteration 2, featuring a fully threaded approach. The direct message handling is not complete, but the basic rss posting works. If you want to check it out or contribute, hit the link. I'll probably branch it and try a version that uses an event-driven framework instead of the threading.

[1]: http://github.com/opie4624/pyrss2twitter/network "GitHub Repo"
