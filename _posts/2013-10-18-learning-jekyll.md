---
layout: post
title: "Learning Jekyll"
description: ""
category: 
tags: []
---
{% include JB/setup %}
I'm still not really feeling too comfortable with Jekyll, but I'm trying to pick it up. I've been working on a few other projects on the side - I'd start writing about them here, but I'm not sure that I won't scrap this whole blog again and start from scratch.

So far I've had no luck with finding a decent Jekyll Bootstrap theme. I'm beginning to think I'll need to make my own. 

I have had some luck with upgrading Jekyll Bootstrap underneath this repository. Here is the command I used to add the upstream repository:

    git remote add topupstream git://github.com/plusjade/jekyll-bootstrap.git

Here's what I use to update the repository:

    git fetch topupstream
    git merge topupstream/master

I occasionally get stuck having to do a merge-fix commit, but that's probably more time-effective than writing a script to strip out changes in Jekyll Bootstrap that overwrite things I've removed for my GitHub pages site. 




