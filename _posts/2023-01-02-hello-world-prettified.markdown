---
layout: post
title:  "Day 2: Personal Website"
date:   2023-01-02
categories: personal website
---
Today I will be focusing on making my personal website cute. I will also be looking for issues I may have missed yesterday in my work or documentation.

While a site was working yesterday, local development was not setup. The first think I did was set this up to debug the issues I found from yesterday([issue 1](https://github.com/e0218a/e0218a.github.io/issues/1), [issue2](https://github.com/e0218a/e0218a.github.io/issues/2)).

[Jekyll Local Development Guide](https://jekyllrb.com/docs/)

The local development guide had instructions to set up a new blog. The steps followed were to:

1. Install all prerequisites.
2. Install the jekyll and bundler gems via 
3. jekyll new [your blog name here]
4. Substitute the posts folder with my own posts.
5. Fixing the [frontmatter](https://jekyllrb.com/docs/front-matter/) in my posts to follow the following format:
```
---
layout: post
title:  "your title here-- make sure you include quotes!!!"
date:   YYYY-MM-DD
categories: [project name here!]
---
```
6. Changing the site setting properties in /\_config.yml with my own.

Now I can move onto styling and customization.