---
title: "How to use Markdown"
author: "John Little"
date:  "Mar 20, 2020"
---


# My first markdown note

###### tags: `test` `hello world`

> This is a note.  See (to the right) how the note appears as a highlight?  You can use the `>` markup your any text.
>  Add your own text.  

##  Second level header

For more Markdown help see
1. Help > Markdown quick reference
2. Help > Cheatsheets > R Markdown cheat sheets
3. [R Markdown](http://rmarkdown.rstudio.com) Notebooks

### Step 1: Change the title and add a tag

Favorite fruits
- orange
    - nectarine       
- apple
- grape

Checkbox
- [x] Create my first HackMD note (this one!)
- [ ] Change its title
- [ ] Add a tag

### Step 2: Write something in Markdown

Write something else in this basic paragraph
**Everyone can structure documents with Markdown.**   _Most people love_ markdown.  ~~Some people are less enthusiastic~~. Add your own text in this paragraph.^[Inlines notes don't have to pick an identifier. ]  You can manage footnotes, citations, and bibliographies.  Learn more about citations and bibliographies in the Cheatsheet `(RStudio IDE > Help > Cheatsheets > R Markdown cheat sheet)`^[ [Browse all the RStudio Cheatsheets](https://rstudio.com/resources/cheatsheets/) ] There is more than one kind of markup for footnotes.  I like the above style.  However, you can also do use this style.[^footnote]

[^footnote]: Test, [Link](https://google.com).

- [x] **Bold**
- [ ] *Italic*
- [ ] Super^script^
- [ ] Sub~script~
- [ ] ~~Crossed~~


![](http://library.duke.edu/digitalcollections/media/jpg/ua_exhibit/med/bostocklibrary.jpg)


## BONUS: More cool markdown

Tables

| Resources          | Acronym               |
| ----------------- | -----------------------:|
| [R learning series](https://rfun.library.duke.edu)   | Rfun |       
[Center for Data & Visualization Sciences](https://library.duke.edu/data/)  | CDVS   |


- LaTeX for formulas

$$
x = {-b \pm \sqrt{b^2-4ac} \over 2a}
$$

- Inline equations

The formula for Area is ... $A = \pi*r^{2}$

- Code block with color and line numbers：

```{r}
starwars %>%
  filter(hair_color == "brown")
```

`monospacing and inline code` can also be used

