# Course Notes: Learning Markdown

## Course Info

* Source: [LinkedInLearning](https://www.linkedin.com/learning/me)
* Author: [Ray Villalobos](http://raybo.org/)
* Course: [Learning Markdown](https://www.linkedin.com/learning/learning-markdown)

## Resources

* Editor: [StackEdit](https://stackedit.io/)
* Image upload service: [Imgur](https://imgur.com/)
* Screen shot app: [Light Shot](https://app.prntscr.com/en/index.html)
* GFM Markdown:
  * [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown)
  * [Github Icons](https://gist.github.com/rxaviers/7360908)
* [LaTeX Table Generator](https://www.tablesgenerator.com/markdown_tables)
* [Markdown Page](https://daringfireball.net/projects/markdown)
* [MultiMarkdown](http://fletcherpenney.net/multimarkdown)
* [R Markdown](http://rmarkdown.rstudio.com/)
* [CommonMark](http://commonmark.org/)
* [Babelmark](http://johnmacfarlane.net/babelmark2) : compare implementations
* HTML Presentation: [reveal.js](http://lab.hakim.se/reveal-js)
* [Awesome Markdown](https://github.com/mundimark/awesome-markdown)

## Basic Styles

* _emphasis_
* **bold** or **bold**
* `code tagged`
* escape \*, \`, \_\_
* can use _html tags_ -- more stuff in a tag

## Paragraphs

Equivalent to html &lt;p&gt; tags - multiple returns condense down to one paragraph. For example:

After multiple returns.

```text
Tabs after return renders in a  'code' block - in html it wraps in 
\<pre\>\<code\> tags
```

Two spaces at end of line followed by crlf adds a break to the output.

## Headlines \(style one\)

### A line with equals underneath is level one headline

Level one headlines render with &lt;h1&gt; tag and adds an id attribute that can be used to build table of contents.

### A line with dashed underneath is a level two headline

Level one headlines render with &lt;h2&gt; tag and adds an id attribute that can be used to build table of contents.

## Headlines \(style two\)

Precede the headline with one \# symbol \(number of hashes indicates the level of &lt;h\_&gt; tag\).\# Headline level 1.

### Headline level 2

#### Headline level 3

**Headline level 4**

**Headline level 5**

**Headline level 6**

regular text paragraph

## Block Quote

> Using a &gt; at beginning of line will turn text into a block quote
>
> > #### Block quote inside a block quote
> >
> > two &gt;&gt; will produce a block quote withing another block quote, and a very long line of text will wrap in the block quote automatically.

## Horizonal rule

Can use '---'

Can use '\*\*\*'

Can use '\_\_\_'

## Lists

### Unordered List

**Use '\***

* item 1
* item 2
* item 3
  * item 3.a
  * item 3.b

**Use '-'**

* item a
* item b
  * item b.1
  * item b.2

**Use numbers**

1. item one \(with crlf at end to add additional vertical space\)
2. item two
3. item three
   1. item 3.1
   2. item 3.2

### Links

* [this is a link](http://www.cnn.com/) - with a title
* another way to do a link [http://www.msnbc.com](http://www.msnbc.com/)
* [mkozi.junk@gmail.com](mailto:mkozi.junk@gmail.com)

#### Term paper style links \(reference links\)

this is an example of a [link](http://www.cnn.com/)

### Image tags

#### Inline images

[![Jelly Bellies](https://camo.githubusercontent.com/7eb3bf8b2021e794ebf17746d0863fea5de381a1/687474703a2f2f7777772e7061727479657863757365732e636f6d2f696d616765732f75706c6f6164732f686f6c69646179696d616765732f62696773746f636b2d536d616c6c2d4a656c6c792d4265616e732d35353935383031322e6a7067)](https://camo.githubusercontent.com/7eb3bf8b2021e794ebf17746d0863fea5de381a1/687474703a2f2f7777772e7061727479657863757365732e636f6d2f696d616765732f75706c6f6164732f686f6c69646179696d616765732f62696773746f636b2d536d616c6c2d4a656c6c792d4265616e732d35353935383031322e6a7067)

#### Reference image link

[![Jelly Bellies Again](https://camo.githubusercontent.com/7eb3bf8b2021e794ebf17746d0863fea5de381a1/687474703a2f2f7777772e7061727479657863757365732e636f6d2f696d616765732f75706c6f6164732f686f6c69646179696d616765732f62696773746f636b2d536d616c6c2d4a656c6c792d4265616e732d35353935383031322e6a7067)](https://camo.githubusercontent.com/7eb3bf8b2021e794ebf17746d0863fea5de381a1/687474703a2f2f7777772e7061727479657863757365732e636f6d2f696d616765732f75706c6f6164732f686f6c69646179696d616765732f62696773746f636b2d536d616c6c2d4a656c6c792d4265616e732d35353935383031322e6a7067)

#### Linkable image

[![Jelly Bellies](https://camo.githubusercontent.com/7eb3bf8b2021e794ebf17746d0863fea5de381a1/687474703a2f2f7777772e7061727479657863757365732e636f6d2f696d616765732f75706c6f6164732f686f6c69646179696d616765732f62696773746f636b2d536d616c6c2d4a656c6c792d4265616e732d35353935383031322e6a7067)](http://www.cnn.com/)

## GFM Modifications

GitHub Flavored Markdown

* Ignores underscores
* Strikethrough ~~style~~: ~~style~~
*  Complete item
*  Incomplete item \(needs to be on seperate line\)
* Auto-hotlinking: [https://github.com](https://github.com/)
* Fenced codeblocks
* Tables

## Table \(GFM\)

| First Header | Second Header | left align | centered | right align |
| --- | --- | --- | --- | --- |
| content one | content two | a | 1 | zyx |
| more | stuff | bcde | **234** | long thing |
| this is really long | not so much | fg | 5678 | a |
| a |  |  |  | z |

> Written with [StackEdit](https://stackedit.io/).

