## R Style Guide
*  Philosophy of package development (Hadley Wickham): anything that can be automated, should be automated. Do as little as possible by hand. Do as much as possible with functions. 

*  R is, at heart, more a functional programming language than an object oriented programming language. 

### 1. Write Clean Code

(1). [Google’s R Style Guide](https://google.github.io/styleguide/Rguide.html)

(2). [Hadley Wickham’s style guide](http://adv-r.had.co.nz/Style.html). Tutorial from Hadley Wickham
* Hadley Wickham. ''R packages''. O’Reilly Media. [Web Link](http://r-pkgs.had.co.nz/)
* Hadley Wickham. ''Advanced R''. [Web Link](http://adv-r.had.co.nz/)
* Garrett Grolemund and Hadley Wickham. ''R for Data Science'' [Web Link](http://r4ds.had.co.nz/)

(3). [Some simple tutorial](https://www.earthdatascience.org/courses/earth-analytics/time-series-data/write-clean-code-with-r/)

(4). Tips: 
```markdown
- Use nouns for variable names and verbs for function names.
- It’s a mistake to focus on speed until you know it’ll be a problem. 

```
### 2. Efficient Code 

(1).  While turning casual interactive tests into reproducible scripts requires a little more work up front, it pays off in four ways: Fewer bugs; Better code structure; Easier restarts; Robust code.

You can use the [editor on GitHub](https://github.com/yazhou2019/RStyleguide/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### 3. Quick R package
(1). Rstudio: New project --> New Directory --> R package

(2). Put the functions in .R/

(3). Rstudio: Build --> Install and Restart (Complete roughtly)

#### Further improvements:
```markdown
# Documentation (help)
1. write the file (before the definition of the function )
2. type the code in Rstudio (project environment)
devtools::document()
3. use help("the functions") to check if it work
# Automated checking 
devtools::check()
# Data
devtools::use_data()
```
#### Tips:
- Sometimes devtools:: does not work, we can just library(devtools) and use those functions


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List
(1). [Google’s R Style Guide](https://google.github.io/styleguide/Rguide.html)

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/yazhou2019/RStyleguide/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
