# Learning Markdown language
source:

[GitLab markdown-guide handbook](https://about.gitlab.com/handbook/markdown-guide/)

[freecodecamp markdown-cheat-sheet](https://www.freecodecamp.org/news/markdown-cheat-sheet/)

## Headings

do not skip heading hierarchy levels

keep a space between hash `#` and the text next to it

jump a line between block-level markup elements

----

## Regular paragraphs

### Wrapping

if left without a blank line between, two paragraphs will wrap forming a single paragraph

### Additional blank lines

use `<br>` for additional blank lines

### Horizontal lines

more than 3 dashes will produce a horizontal lines (use 4 as standard)

----

## Emphasis: bold and italic

`This is **bold** and this is _italic_`

This is **bold** and this is _italic_

`This is both ***bold and italic***`

This is both ***bold and italic***

`This is another way to use *italic*`

This is another way to use *italic*, easier to miscomprehend

----

## Links

as always in programming - use **meaningful** names

### Inline

`[dead link checker](http://www.deadlinkchecker.com/)`

[dead link checker](http://www.deadlinkchecker.com/)

### Relative

#### current document-relative URLs look like this:

`../markdown.md/`

with `..` meaning walk out of a current file

#### root-relative URLs look like this:

/LearningMarkdown/markdown.md

it's advised to use this path representation because moving document won't break links to other pages

