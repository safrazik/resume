# Markdown Resume

> Open source responsive resume in Markdown format with elegant source and output

This repository consists of the source code of [my resume](http://safrazik.github.io/resume/).
You may fork and [edit the content](https://github.com/safrazik/resume/blob/master/README.md) to make it yours!


## Forking

> NOTE: you can remove the "Powered by" message, but you are not allowed to put any other text there.

- Fork this project
- Edit `_config.yml` with your name, email and other information
- Edit `README.md` with your information
- Go to repository `Settings` and under the section `GitHub Pages` source, select `master branch`
- Now you have your own version of Markdown resume
- Create new branch or tag when you update your resume for your next career change.
- Good luck with job hunting!

## Building locally (Optional)

- install [Jekyll](http://jekyllrb.com)
- clone this project
- from the project location run `jekyll serve --watch`
- Customize [README.md](https://github.com/safrazik/resume/blob/master/README.md)
- open [localhost:4000](http://localhost:4000) to see the output
- customize `assets/_scss/*.scss` files for css customizations

## Motivation & Features

- The Source code of the resume itself should be readable and easily maintainable.
- Should be portable.
- Should `just work` on Github Pages
- No extra tools should be involved, just a markdown parser should be enough to get the HTML output.
- Should be customizable with CSS.
- Should be mobile friendly.
- The source code and the output should not have a big diffrence.
- Should be easily versionable.
- Should be **simple**!


## General Rules

- Should have as many white spaces as possible to improve clarity and readability
- Headings should be vertically aligned. Hence, use white spaces to pad them, resulting in a total of 8 characters including spaces before the heading text
  e.g:
  ```markdown
  ####    Heading h4

  ######  Heading h6

  #####   Heading h5
  ```
- Separators like horizontal rules or headings with repeating characters should have 42 characters  
  e.g:  
  ```markdown
  ==========================================
  ------------------------------------------
  ```

## The Header

### Main Header

- The header text followed by a new line and 42 repeating equal signs (`=`)
- Result is an `<h1>`

```markdown

Your Fullname
==========================================
```


### Main Title

- 4 Repeating hashes(`#`) followed by 4 spaces(` `) and title
- Result is an `<h4>`

```markdown

####    Title Excepteur sint

```

### Description and Quote

- An career summary or bio can be folllowed after the main title
- A blockquote can be used for contact information

```markdown

**Summary** Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur


> My City, My Country.
> 
> Email: myemail@example.com
> 
> Twitter: @mytwitter


```

## Sections

```markdown

------------------------------------------

    SECTION TITLE

------------------------------------------


#####   Primary Title

######  Secondary Title


- Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

- Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

- Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.


------------------------------------------


#####   Another Primary Title

######  2015


- Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

- Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


```


## Skills Section

```markdown

------------------------------------------

    SKILLS

------------------------------------------


######  Languages

- **Level of Expertise** - PHP, JavaScript, HTML5, CSS3, MySQL

- **Beginner** - Python, Ruby


######  Category Two

- **Lorem** - Ut enim ad Minim veniam, Quis nostrud exercitation, Ullamco laboris, Nisi ut aliquip ex ea commodo consequat

- **Ipsum** - Ut enim ad Minim veniam, Quis nostrud exercitation, Ullamco laboris, Nisi ut aliquip ex ea commodo consequat

```

## Complete Example

You can take [my resume](https://github.com/safrazik/resume/blob/master/README.md) as a practical example and inspiration. Good luck fork(s)!

```markdown

![Your Avatar](path/avatar.png)


Your Fullname
==========================================


####    Title Excepteur sint


**Summary** Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur


> My City, My Country.
> 
> Email: myemail@example.com
> 
> Twitter: @mytwitter


------------------------------------------

    SECTION TITLE

------------------------------------------

#####   Primary Title

######  Secondary Title


- Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

- Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

- Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.


------------------------------------------


#####   Another Primary Title

######  2015


- Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

- Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


------------------------------------------

    SKILLS

------------------------------------------


######  Languages

- **Level of Expertise** - PHP, JavaScript, HTML5, CSS3, MySQL

- **Beginner** - Python, Ruby


######  Category Two

- **Lorem** - Ut enim ad Minim veniam, Quis nostrud exercitation, Ullamco laboris, Nisi ut aliquip ex ea commodo consequat

- **Ipsum** - Ut enim ad Minim veniam, Quis nostrud exercitation, Ullamco laboris, Nisi ut aliquip ex ea commodo consequat

```
