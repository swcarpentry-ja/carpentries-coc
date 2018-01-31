## How to Contribute a Blog Post to Software Carpentry

1.  If you wish to contribute a blog post,
    please work in <https://github.com/swcarpentry/website>,
    which can be viewed at <https://software-carpentry.org/blog>.
    
2.  Posts go in the `_posts` folder, which is divided up first by year,
    e.g. `2017`, and then by month, e.g. `07`. Be sure to start creating your file in
    the correct folder. 
    
3.  Posts need to be created in [Markdown](https://guides.github.com/features/mastering-markdown/) and named 
    according to this convention:
    
    `YYYY-MM-DD-filename.md`
    
    e.g. 
    
    `2017-07-10-assess_report.md`
    
4.  In order to render correctly, posts need to have a header block, which should be created like [this example](https://raw.githubusercontent.com/swcarpentry/website/gh-pages/_posts/2017/06/2017-06-19-mqu-ttt.md), e.g.

```
---
layout: post
subheadline: "Assessment"
title: "Analysis of Software Carpentry Workshop Impact"
date: 2017-07-10
time: "08:00:00"
authors: ["Kari L. Jordan"]
category: ["surveys", "workshops", "impact", "assessment"]
---
```

Separate the header block from the post proper by a new line. 
    
5.  `Subheadline` is an optional field, as is `time`, but the other fields should be filled in. If there is more than one author,
    separate the author names like this: `["Name 1", "Name 2"]`. Separate any categories the same way.
    
6.  Images should be uploaded to the appropriate year in the `files/<year>/<month>` folder. Images should be linked using 
    Markdown, and paths to the image should be relative. 
    Example: 
    ```
    ![Image Description]({{ site.filesurl }}/2017/07/myimage.jpg)
    ```
    A web link should be used for images hosted elsewhere, e.g., images you do not own, or for which you do not have rights to upload. 
    Example: 
    ``` 
    ![Image Description](https://web_address/pathway_to_full_image_filename)
    ```
    
    If you are not sure how to add images in Markdown format, look at an [existing post with a locally hosted image](https://raw.githubusercontent.com/swcarpentry/website/gh-pages/_posts/2017/06/2017-06-19-mqu-ttt.md) or [one with a web link](https://raw.githubusercontent.com/swcarpentry/website/gh-pages/_posts/2017/07/2017-07-10-assess_report.md) and copy the formatting from there.
    
7.  Once you have previewed your file, commit the Markdown file to your fork and start a Pull Request. We automatically run tests using [TravisCI](https://travis-ci.org/) on your Pull Requests. Please review your pull request a few minutes after you've submitted it to make sure those tests have passed. These tests look for valid YAML headers and make sure that the post will build properly.
