[First tutorial that I followed](http://jmcglone.com/guides/github-pages/), [Youtube video tutorial](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB)


specify baseurl: /learn-jekyll in _config.yml and then modify blog post urls like this: {{ post.url | prepend:site.baseurl }}. You can also use {{ post.url | relative_url }} https://jekyllrb.com/docs/templates/#filters

https://byparker.com/blog/2014/clearing-up-confusion-around-baseurl/
