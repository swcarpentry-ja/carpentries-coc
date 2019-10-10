## Adhering to The Carpentries Style Guide

In contributing to The Carpentries website, handbook and other resources, remember to refer to [The Carpentries Style Guide](https://docs.carpentries.org/topic_folders/communications/resources/style-guide.html) and format your contributions accordingly. 

For example, headings should use title casing, and tools like the [Title Case Converter](https://titlecaseconverter.com/) serve as a definitive guide to formatting for Title Casing, complete with reasons for or against capitalising certain words.

Another meaningful example is spellings. Because The Carpentries is a global community-led organisation, content standardisation is important. Our Style Guide currently recommends the use of British English in all our resources across the board. More about this in the language section of our Style Guide.

## Formatting Hyperlinks

Hyperlinks on the websites for The Carpentries and its lesson programs should be formatted using [Jekyll's link formatting syntax](https://jekyllrb.com/docs/liquid/tags/#links).  This includes: 

- using `{% link %}` for pages. For example, `[Become a member organisation]({% link pages/membership.md %})`
- using `{% post %}` for blog posts. For example `[blog post]({% post _posts/2021/05/2021-05-01-blogging-from-the-future.md %})`
- not using relative paths
- not including `https://carpentries.org/` (or the respective website) in the URLs.  The `baseurl` should be defined in the website's `_config` file.
- using `{{ urlimg }}` for images.  For example, `<img src="{{ site.urlimg }}/blog/2021/05/future.png">`.  The `urlimg` should be defined in the website's `_config` file.
- using `{{ filesurl }}` for files. For example, `[Read the report]({{ site.filesurl }}/docs/2021/05/future.pdf)`


**How can you help?** 

As you read through the resources we make available on the [Data Carpentry](https://datacarpentry.org), [Library Carpentry](https://librarycarpentry.org/), [Software Carpentry](https://software-carpentry.org/) and [The Carpentries](https://carpentries.org/) websites as well as this Handbook and other resources, you can go to the appropriate repository and either:
- open an issue and report instances of these anomalies (<mark>low time requirement</mark>), or

- submit a Pull Request with edits that help standardise spellings, headings, etc (<mark>Moderate time requirement </mark>).

We are also keen on continued resource provenance, so please report any broken links as and when you come by them. [Internet Archive's Way Back Machine](https://archive.org/web/) is a powerful tool to help you view resources in broken links, and potentially find alternative/updated links to the same resources.
