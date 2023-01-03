---
layout: post
title:  "Day 2: Personal Website"
date:   2023-01-02
categories: personal website
---
Today I will be focusing finding and correcting issues I may have missed yesterday in my work or documentation.

Some issues I found looking around the site and the build yesterday included the following.
- [issue 1](https://github.com/e0218a/e0218a.github.io/issues/1)
- [issue2](https://github.com/e0218a/e0218a.github.io/issues/2)

In order to fix these issues, I first set up local development by following the [Jekyll quickstart guide](https://jekyllrb.com/docs/).

The quickstart guide also had instructions to set up a new blog. I reattempted this to fill in the gaps that the boilerplate quickstart guide setup that my blog yesterday didn't have.

1. Install all prerequisites.
2. Install the jekyll and bundler gems via 
3. jekyll new [your blog name here] to create a boilerplate blog
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

Tomorrow I can move onto styling and customization with a Jekyll theme.