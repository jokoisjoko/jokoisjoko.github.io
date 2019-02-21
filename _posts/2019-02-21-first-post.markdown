---
layout: post
title:  "First Post in jekyll"
date:   2019-02-21 07:13:25 +0700
categories: dailyblog

---

This is the very first day i am using jekyll, tho i did create this blog for **almost 1 month** . I barely have time to learn about jekyll until today. So i am following the tutorial from [briancaffey](http://briancaffey.github.io/2016/03/17/jekyll-tutorial.html). The tutorial was written with clear explanation, tho some step need to slightly change because the new version of jekyll have some change in feature.

I need to list some of what i have learn today to track my progress, so i decided to make the content of this first post as a list of  what i have learned so far, and what i need to do in the future.

- [x] Learn how to write page, post, and some [liquid](https://help.shopify.com/en/themes/liquid/basics) basic syntac.
- [ ] Layout editing
- [ ] and more...



#### **1. How to write post, page and some [liquid](https://help.shopify.com/en/themes/liquid/basics) basic syntac.**

+ **Post**
<br>
To make a new post you need to make a new file inside post directory with following format, yyyy-mm-dd-title.MARKUP. The file itself easilly written using markdown syntac with a little configuration called **Front Matter** in the beginning of the mardown file.

```markdown
---
layout: post
title:  "Welcome to Jekyll!"
---

# Welcome

**Hello world**, this is my first Jekyll blog post.

I hope you like it!
```


+ **Page** 
<br>
You can make a new page by creating a new file inside root directory, and name it as you like. the layout itself is same as the post file, with slightly modification on  **Front Matter**  configuration.

```markdown
---
layout: page
title:  "Welcome to Jekyll!"
---

# Welcome

**This is ape**
```
