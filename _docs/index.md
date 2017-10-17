---
title: Getting Started
permalink: /docs/home/
redirect_from: /docs/index.html
---

## Intro

A beginner friendly introduction to using Git version control through the **GitHub Desktop** application. Users will be able to create new **repositories**, **clone** existing repositories to a local development environment, **add** new files to a repo(make changes), create a **commit**, make comments on the commit, make a **new branch**, **push** the changes to GitHub, make a **pull request**, **merge** changes, and delete the created branch. Slightly more advanced users will also learn how to **fork** an **open source** repo,and make branches and pull requests for proposed changes to a real software project.

## Pre-requisites

* Create a GitHub account at github.com
* Familiarity with a Text Editor such as Sublime or Atom


## Writing content

### Docs

Docs are [collections](https://jekyllrb.com/docs/collections/) of pages stored under `_docs` folder. To create a new page:

**1.** Create a new Markdown as `_docs/my-page.md` and write [front matter](https://jekyllrb.com/docs/frontmatter/) & content such as:

```
---
title: My Page
permalink: /docs/my-page/
---

Hello World!
```

**2.** Add the pagename to `_data/docs.yml` file in order to list in docs navigation panel:

```
- title: My Group Title
  docs:
  - my-page
```

### Blog posts

Add a new Markdown file such as `2017-05-09-my-post.md` and write the content similar to other post examples.

### Pages

The home page is located under `index.html` file. You can change the content or design completely different welcome page for your taste. (You can use [bootstrap componenets](http://getbootstrap.com/components/))

In order to add a new page, create a new html or markdown file under root directory and link it in `_includes/topnav.html`.
