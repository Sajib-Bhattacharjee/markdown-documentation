# Markdown Documentation/Cheat Sheet

---

`In detail all about the topic(Markdown).`

## Table of Contents

- [1.Markdown Files](#1markdown-files)
- [2.Markdown Headings](#2markdown-headings)
- [3.Text Styles](#3text-styles)

- [4.Syntax Highlighting](#4syntax-highlighting)
- [5.Markdown Tables](#5markdown-tables)
- [6.Links](#6links)

- [7.Images and GIFs](#7images-and-gifs)
- [8.Lists And Task](#8lists-and-task)
- [9.Horizontal Rule](#9horizontal-rule)
- [10.Comments](#10comments)
- [11.Escape Characters](#11escape-characters)

## What is Markdown?

```markdown
Markdown is a way of writing and formatting rich text using plain text formatting
syntax. Basically, it is a lightweight markup language, using which we can create
richly formatted text. The main intention behind its invention was to provide users
with a markup language, that would appeal to its readers, even in its source code
form, and thus make text formatting easier.

In this cheat sheet, I'm going discuss some of the major features of markdown along
with the code syntaxes and examples which will allow the reader to make richly formatted text articles by themselves.
```

## 1.Markdown Files

```markdown
A text file created with several syntaxes of a Markdown language is called a
Markdown File. It makes use of plain text formatting consisting of inline text symbols
for specifying how a text can be formatted.
```

#### How to open a markdown file offline?

```markdown
Markdown files are of the extension "_.md" where _ represents the file name. They
can be opened offline using certain Chrome plugins like the “Markdown Preview
Plus”. Visual Studio Code by Microso
```

#### Advantages of Markdown Files:

```markdown
Some of the advantages of Markdown are stated below:

-Richly Formatted content can be created relatively quickly.
-It has become the go-to language for creating documentation, because of its
lightweight and platform-transferrable nature. Even Github readme files are
created using Markdown, allowing them to be attractive to read(due to
formatting) as well as lightweight in nature.
```

## 2.Markdown Headings

# Heading 1

```markdown
Markup : # Heading 1
```

## Heading 2

```markdown
Markup : ## Heading 2
```

### Heading 3

    Markup :  ### Heading

#### Heading 4

    Markup :  #### Heading 4

##### Heading 5

    Markup :  ##### Heading 5

###### Heading 6

    Markup :  ###### Heading 6

## 3.Text Styles

#### Example: Common text

    Markup :  Common text

#### Example: _Emphasized text_

    Markup :  _Emphasized text_ or *Emphasized text*

#### Example: ~~Strikethrough text~~

    Markup :  ~~Strikethrough text~~

#### Example: **Strong text**

    Markup :  __Strong text__ or **Strong text**

#### Example: **_Strong emphasized text_**

    Markup :  ___Strong emphasized text___ or ***Strong emphasized text***

## 4.Syntax Highlighting

#### Example Code:

`code()`

    Markup :  `code()`

#### Example JavaScript Code:

```javascript
var specificLanguage_code = {
  data: {
    lookedUpPlatform: 1,
    query: "Kasabian+Test+Transmission",
    lookedUpItem: {
      name: "Test Transmission",
      artist: "Kasabian",
      album: "Kasabian",
      picture: null,
      link: "http://open.spotify.com/track/5jhJur5n4fasblLSCOcrTp",
    },
  },
};
```

    Markup :
             ```javascript/HTML/CSS/C/C++/markdown/...etc.
                //Executable JavaScript Code Here
             ```

```markdown
Note: All are same procedure as like HTML/CSS/C/C++/markdown/...etc.
```

## 5.Markdown Tables

#### Example Table:

| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell | Content Cell  |

```markdown
Markup:

| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell | Content Cell  |
```

#### Example Pipe:

Adding a pipe `|` in a cell :

| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell | \|            |

```
Markup:

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  |  \|
```

#### Expample: Left, right and center aligned table

| Left aligned Header | Right aligned Header | Center aligned Header |
| :------------------ | -------------------: | :-------------------: |
| Content Cell        |         Content Cell |     Content Cell      |
| Content Cell        |         Content Cell |     Content Cell      |

```
Markup:

Left aligned Header | Right aligned Header | Center aligned Header
| :--- | ---: | :---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell
```

#### Example: Link to a specific part of the page:

[Go To TOP](#TOP)

    Markup :
              [text goes here](#section_name)
              section_title<a name="section_name"></a>

## 6.Links

#### Example of Links:

```
   <!-- simple link / automatic link -->

   http://www.google.com

   <!-- markdown link syntax -->
   [title](link)
   [google](http://www.google.com)
   [studywithanis][websitelink]

   <!-- all link is here  -->

   [websitelink]: http://www.google.com
```

#### Example:

[Named Link](http://www.google.com/ "Named link title") and http://www.google.com/ or <http://example.com/>

    Markup :  [Named Link](http://www.google.com/ "Named link title") and http://www.google.com/ or <http://example.com/>

Example:

[Back to Heading-1](#heading-1 "Goto heading-1")

    Markup: [heading-1](#heading-1 "Goto heading-1")

## 7.Images and GIFs

#### Example: Image with alt.

![picture alt](http://via.placeholder.com/200x150 "Title is optional")

    Markup : ![picture alt](http://via.placeholder.com/200x150 "Title is optional")

#### Adding GIFs:

GIFs can also be added using Markdown similar to the way we add images in markdown using the HTML <img> tag.

```
  Markup:

  <img src="https://d3n0h9tb65y8q.cloudfront.net/public_assets/assets/000/002/564/original/GIF.gif?1642758263" />
```

## 8.Lists And Task

###### Example:

         * Bullet list
            * Nested bullet
              * Sub-nested bullet etc
         * Bullet list item 2

```
 Markup :
          * Bullet list
              * Nested bullet
                  * Sub-nested bullet etc
          * Bullet list item 2

-OR-

 Markup :
          - Bullet list
              - Nested bullet
                  - Sub-nested bullet etc
          - Bullet list item 2
```

###### Example:

1. A numbered list
   1. A nested numbered list
   2. Which is numbered
2. Which is numbered

```
 Markup :
         1. A numbered list
              1. A nested numbered list
              2. Which is numbered
          2. Which is numbered
```

### Task

###### Example:

- [ ] An uncompleted task
- [x] A completed task

```
 Markup :
          - [ ] An uncompleted task
          - [x] A completed task
```

#### Example:

- [ ] An uncompleted task
  - [ ] A subtask

```
 Markup:
              - [ ] An uncompleted task
              - [ ] A subtask
```

## 9.Horizontal Rule

#### Example: Horizontal Rule.

---

---

---

```markdown
Markup : - - - -
\*\*\*
\_\_\_
```

## 10.Comments

    We can add markdown comments by enclosing them within <!-- --> symbols.

```
  Markup:
  <!-- This is a comment. -->
```

## 11.Escape Characters

Markdown allows you to use backslash escapes to generate literal characters which would otherwise have special meaning in Markdown’s formating syntax.

| Name                | Markdown | Result |
| ------------------- | -------- | ------ |
| backslash           | `\\`     | \\     |
| backtick            | `` \` `` | \`     |
| asterisk            | `\*`     | \*     |
| underscore          | `\_`     | \_     |
| curly braces        | `\{\}`   | \{\}   |
| square brackets     | `\[\]`   | \[ \]  |
| parentheses         | `\(\)`   | \(\)   |
| hash mark           | `\#`     | \#     |
| plus sign           | `\+`     | \+     |
| minus sign (hyphen) | `\-`     | \-     |
| dot                 | `\.`     | \.     |
| exclamation mark    | `\!`     | \!     |

## Conclusion:

```
From the above cheat sheet, we can observe that using markdown we can format even a simple text document into rich, highly engaging content.
Markdown is used in a lot of domains including ed-tech and education fields to create highly engaging and high-quality content for the consumers at a fast pace.
With its rich list of available features, it can be used innovatively in a wide variety of ways and purposes.
```

### Created By

`-Sajib Bhattacharjee`

`Dedicated for "Zahan"`

### Thanks A Lot For Visiting...!!!
