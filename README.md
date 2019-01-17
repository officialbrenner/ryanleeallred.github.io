# DSGlossary.com

[DSglossary.com](http://www.dsglossary.com) is an open-source glossary of Data Science, Statistics, Machine Learning, and Artificial Intelligence terms maintained by [Ryan Allred](http://www.ryanleeallred.com). The site is built on [Jekyll](https://jekyllrb.com/) and [Github Pages](https://pages.github.com/). Fork the repository if you would like to contribute!

# How to use it? (Locally)

1) Fork and clone the repository.

2) From the command line navigate inside the repository and run:

```
$ bundle exec jekyll serve
```
3) Open up [localhost:4000](localhost:4000) in your web browser to view the local development version of the site.

# How to contribute definitions? (Web)

1.) Fork the repository. 

2.) Use the [`post_template.md`](link_to_post_template.md) file and edit it as follows for your post:

*   Header *(no links or formatting)* 
    *   Edit the `title`  field to match the vocabulary term.
    *   Edit the `category` to match the first letter of the vocabulary term. 
    *   Edit the `description` with the term, a '-', and a short description. 
*   Post Body (everything below the 2nd set of `---`'s. 
    *   Edit the post body with text using markdown to repeat and expand upon the description provided above. Feel free to embed images, links, and videos. (All media must be creative commons licensed.

3.) Save your work with the name format like:  `2018-11-03-algorithm.md` , with the date and vocabulary term in the file name. 

4.) Commit (upload) the .md file into the `_posts`  folder of your repo, and then create a pull request to merge with [**ryanleeallred.github.io:master**](https://github.com/ryanleeallred/ryanleeallred.github.io)

# Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/ryanleeallred/ryanleeallred.github.io.
