[First tutorial that I followed](http://jmcglone.com/guides/github-pages/), [Youtube video tutorial](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB)


specify baseurl: /learn-jekyll in _config.yml and then modify blog post urls like this: {{ post.url | prepend:site.baseurl }}. You can also use {{ post.url | relative_url }} [See all available filters](https://jekyllrb.com/docs/templates/#filters), [More about base URL](https://byparker.com/blog/2014/clearing-up-confusion-around-baseurl/).

We may also use the HTML base tag to modify the blog post URLs.
permalink: /learn-jekyll/:year/:month/:day/:title #This will just keep this post under /_sites/learn-jekyll/2020/06/30/.... This won't solve the username.github.io/learn-jekyll issue. The post will be available at username.github.io/learn-jekyll/learn-jekyll/...
