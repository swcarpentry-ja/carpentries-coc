## How to Contribute a Blog Post to Data Carpentry

1.  If you wish to contribute a blog post,
    please work in <https://github.com/datacarpentry/datacarpentry.github.io>,
    which can be viewed at <http://www.datacarpentry.org/blog/>.
    
2.  Posts go in the `_posts` folder. 
    
3.  Posts need to be created in [Markdown](https://guides.github.com/features/mastering-markdown/) and named 
    according to this convention:
    
    `YYYY-MM-DD-filename.md`
    
    e.g. 
    
    `2017-07-10-assess_report.md`
    
4.  In order to render correctly, posts need to have a header block, which should be created like [this example](https://raw.githubusercontent.com/datacarpentry/datacarpentry.github.io/master/_posts/2015-01-23-genomics-hackathon.md), e.g.

```
---
layout: post
subheadline: "Lessons"
title: Data Carpentry Genomics and Asssessment Hackathon
teaser: "Announcing a Data Carpentry Genomics and Assessment Hackathon"
header:
   image_fullwidth: "light-blue-wood-texture.jpg"
categories:
   - blog
comments: true
show_meta: true
authors: ["Tracy Teal"]
---
```

Separate the header block from the post proper by a new line. 
    
5.  `Subheadline` is an optional field, as is `teaser`, but the other fields should be filled in. If there is more than one author,
    separate the author names like this: `["Name 1", "Name 2"]`. 
    
6.  Images should be uploaded to the `images` folder. Images should be linked using 
    Markdown, and paths to the image should be relative. 
    Example: 
    ```
    ![Image Description]({{ site.filesurl }}/images/myimage.jpg)
    ```
    A web link should be used for images hosted elsewhere, e.g., images you do not own, or for which you do not have rights to upload. 
    Example: 
    ``` 
    ![Image Description](https://web_address/pathway_to_full_image_filename)
    ```
    
    If you are not sure how to add images in Markdown format, look at an [existing post with a locally hosted image](https://raw.githubusercontent.com/datacarpentry/datacarpentry.github.io/master/_posts/2017-12-19-frb_carpentry.md) and copy the formatting from there.
    
7.  Once you have previewed your file, commit the Markdown file to your fork and start a Pull Request. We automatically run tests using [TravisCI](https://travis-ci.org/) on your Pull Requests. Please review your pull request a few minutes after you've submitted it to make sure those tests have passed. These tests look for valid YAML headers and make sure that the post will build properly.
