From https://jekyllrb.com/docs/posts/:

To create a post, create a new file in this directory (in the upper right: `Add File` --> Create new file) with the following title format:

```YEAR-MONTH-DAY-title.md```

Where YEAR is a four-digit number, MONTH and DAY are both two-digit numbers, and .md is the file extension representing the format used in the file. For example, the following are examples of valid post filenames:

```2011-12-31-new-years-eve-is-awesome.md```
```2012-09-12-how-to-write-a-blog.md```

In the contents section, proceed as follows: all blog post files must begin with front matter which is typically used to set a layout or other meta data. After the metatdata, the blog content follows with markdown syntax. Eg.:

```
---
layout: post
title:  "Welcome to Jekyll!"
---

# Welcome

**Hello world**, this is my first Jekyll blog post.

Insightful things here. 
```

To link to images, use the following syntax: 

```![backup-text](/assets/somefile.jpg)```

where somefile.jpg has been uploaded to the `assets` directory. 
