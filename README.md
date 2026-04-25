# tej-my_markdown-repo
Documenting is an important part of programming (it be embedded, application or HDL), In this repo i am documenting markdown syntax to the best of my knowledge - and can be used as a quick reference lookup for GitHub's markdown rendering.

<br>

**Click and Navigate :** 
- [click here](#general-text) - General Text.
- [click here](#line-break-and-horizontal) - Line break and Horizontal.
- [click here](#list--numarical-list-and-check-list) - List , Numarical list and Check list.
- [click here](#code) - Code.
- [click here](#links-and-embeddeds) - Links and Embeddeds.
- [click here](#tables) - Tables.

---
---

## General Text

### Headings
Headings in markdown are level based, think of Lower level headings are sub-topics of the Higher level headings.
- Syntax of headings start with # followed by white space and the title. note the more #-es the lower level is the heading.
    ```markdown
    # heading1
    ## heading2
    ### heading3
    and more...
    ```

### Text Bold
Bold text in markdown is achived by using 2 asterisk before and after the text that is to be rendered Bold.
- eg: **This text is rendered Bold**
- Syntax of Text Bold is
```markdown
The line below is bold
**This line is bold**
```

### Text Italic 
Italic text is markdown is achived similar to Bold but using 1 asterisk before and after.
- eg: *This text is rendered Italic*
- Syntax of Text italic
```markdown
The line below is italix
*This line is italic*
```

### Text Bold and Italic
Both Bold and Italic on an text is achived using 3 asterisk before and after.
- eg: ***This text is rendered Bold and Italic***
- Syntax of Text Bold and Italic
```markdown
The line below is Bold and Italic
***This line is both Bold and Italic***
```

### Text Monospace
Text Monospace is achived using backtick before and after. (mostly used for inline code)
- eg: `This text is rendered Monospace`
- Syntax of Text Monospace
```markdown
The line below is Text Monospace
`This line is Text Monospace`
```

### Text Strike
Text Strike is achived using 2 tilde before and after.
- eg: ~~This text is rendered strikethrough~~
- Syntax of Test strike
```markdown
The line below is Text Strike
~~This line is Text Strike~~
```

### Block Quotes
Block Quotes is achived using grater-than symbol (for first level) and 2 grater-thans (for second level).
- eg: the following is a Block Quote

> This is first level Block Quote.
>> this is second level Block Quote.
> rough, still first level Block Quote.

- Syntax for Block Quotes
```markdown
> This is first level Block Quote.
>> this is second level Block Quote.
```

---
---

## Line break and Horizontal

### Line Break
The best method for achieving an Line Break in markdown is using HTML syntax br inside < >
- eg:

below is Line Break

<br>

above is Line Break

- Syntax of Line Break
```markdown
There is an Line Break below

<br>

There is an Line Break above
```
- Note: it is best to leave a line above and below, for GitHub's markdown render engine to avoid miss-renders

### Horizontal
The syntax for Horizontal line is 3 hyphens or underscores or asterisks.
- eg:

below is Horizontal

---

above is Horizontal

- Syntax of Horizontal
```markdown
There is an Horizontal below

---

There is an horizontal above
```
- Note: level 1 Headings in GitHub automatically render an thin horizontal, the syntatically induced render is thick in comparision.
- Note: cant generate an Horizontal inside points / list.

---
---

## List , Numarical list and Check list

### Lists
Lists are generated using hyphen followed by white space, and for sub lists use tab space before the hyphen.

eg:
- list 1
- list 2
    - list 2.1
    - list 2.2
        - list 2.2.1

- Syntax for List
```markdown
- list 1
- list 2
    - list 2.1
    - list 2.2
        - list 2.2.1
```

### Numarical List
Similar to lists but we use number followed by fullstop and whitespace.

eg:
1. list 1
2. list 2
    1. list 2.1
    2. list 2.2
        1. list 2.2.1

- Sunctax for Numerical List
```markdown
1. list 1
2. list 2
    1. list 2.1
    2. list 2.2
        1. list 2.2.1
```

### Check List
Similar to Lists, for checklist we use [ ] for unchecked and [x] for checked.

eg:
- [ ] list 1
- [x] list 2
    - [x] list 2.1
    - [ ] list 2.2
        - [x] list 2.2.1

- Syntax for Checked List
```markdown
- [ ] list 1
- [x] list 2
    - [x] list 2.1
    - [ ] list 2.2
        - [x] list 2.2.1
```

---
---

## Code 

### Single/In-line Code
Single/In-Line code in markdown is achived use backtick before and after the code.
- eg: this is text `this is in-line code` this is text.
- Syntax of Single/In-line Code:
```markdown
this is text `this is in-line code` this is text.
```

### Multi-line Code
Multi-line code (also known as Fenced code block) in markdown is achived using 3 backticks before and after the code.
- eg:
```
this is a multi line code block
this is a multi line code block
```
- Syntax of Multi-line Code:
```
\```
this is a multi line code block
this is a multi line code block
\```
```

- Note: in Multi-line code we can use syntax highlighting by typing programming language name after the first/starting 3 backticks.
- Note: the \ here is for escaping purpose
- syntax highliting of markdown eg:

```
\```markdown
# this is a multi line code block
## this is a multi line code block
\```
```

## Links and Embeddeds

### Hyper Link
In markdown a Hyper link is used for many purposes, like:
> - navigating to any URL. 
>   - use the URL. 
> - navigating to Folder inside repo. 
>   - use path with / at the start. 
> - navigating to any Heading inside file. 
>   - use # followed by heading text. 

- the syntax for Hyper link is: [ text here ] followef by ( URL, Path or Heading ).
- eg: Heading navigation: [click-here](#tej-my_markdown-repo), URL navigation: [click-here](https://github.com/Chinnam-Tejesh) and Folder navigation [click-here](/resources/)

- Syntax of Hyper link
```markdown
Heading navigation: [click-here](#tej-my_markdown-repo) 
URL navigation: [click-here](https://github.com/Chinnam-Tejesh) 
Folder navigation [click-here](/resources/) 
```

### Image Embedded
Markdown supports Image embedded-ing either avilable in the repo or using URL. Syntax is: ! followerd by [ text ] followed by ( URL or Path )
- eg:
    - image inside resources folder: ![cherry blossom](/resources/image1.jpg)
    - image from URL: ![markdown logo](https://upload.wikimedia.org/wikipedia/commons/4/41/1280px_Markdown_with_White_Background.png)

- Syntax of Image Embedded
```markdown
image inside resources folder: ![cherry blossom](/resources/image1.jpg)
image from URL: ![markdown logo](https://upload.wikimedia.org/wikipedia/commons/4/41/1280px_Markdown_with_White_Background.png)
```

### Video Embedded
Markdown supports Video embedded-ing (GitHub's feature) either avilable in the repo (user assests).
- eg:
- video directly uploaded in GitHub editor

https://github.com/user-attachments/assets/4e809ad9-ec21-4f9a-9607-628c54884e1f

the above is the video, uploaded as GitHub user asset.

- Syntax of Video Embedded
```markdown
video directly uploaded in GitHub editor

https://github.com/user-attachments/assets/4e809ad9-ec21-4f9a-9607-628c54884e1f

the above is the video, uploaded as GitHub user asset.
```

### Embedded as Link
Markdown allows an Image as link, the Syntax is: [ ![ text ] followerd by ( URL or Path) ] followed by ( URL, Path or Heading )  
That is Image-embedded in text section of Hyper Link

- eg:
- video from URL:
below is video from Youtube (direct link)

[![Alt Text](https://img.youtube.com/vi/4ZhITWHsaro/0.jpg)](https://www.youtube.com/watch?v=4ZhITWHsaro)

- Syntax of Embedded as Link
```markdown
video from URL:
below is video from Youtube

[![Alt Text](https://img.youtube.com/vi/4ZhITWHsaro/0.jpg)](https://www.youtube.com/watch?v=4ZhITWHsaro)

In the above 4ZhITWHsaro is the Video ID (you can get it from value v= in youtube video URL)
```

## Tables
Tables in GitHub are known as Pipe Tables, and convienent with single text line per block.

### Table Syntax
- The Table Syntax uses the following:
    - Pipes (|) used to separate blocks in rows.
    - Dashes (-) used to separate block in columns.
    - Colons (:) used to align text accross blocks of a column.

- Examples of table:

| column 1 | column 2 | column3 |
|   ----   |   ----   |   ----  |
| block 1.1 | block 1.2 | block 1.3|
| block 2.1 | block 2.2 | block 2.3|
| block 3.1 | block 3.2| block 3.3|

- Syntax for Table is as follows
```markdown
with End boarder

| column 1 | column 2 | column3 |
|   ----   |   ----   |   ----  |
| block 1.1 | block 1.2 | block 1.3|
| block 2.1 | block 2.2 | block 2.3|
| block 3.1 | block 3.2| block 3.3|

```

### Text Alignment inside blocks
The Text Alignment in markdown tables is done per column.

- Left Alignment
For left alignment we use colon followed by 3 or more dashes. example:

| column 1 | column 2 | column3 |
| :---- | :---- | :---- |
| block one | block two | block three |
| block four | block five | block six |

- Center Alignment 
For center alignment we use colons at either ends of dashes. example:

| column 1 | column 2 | column3 |
| :----: | :----: | :----: |
| block one | block two | block three |
| block four | block five | block six |

- Right Alignment 
For right alignment we use colon at the end of dashes. example:

| column 1 | column 2 | column3 |
| ----: | ----: | ----: |
| block one | block two | block three |
| block four | block five | block six |

- Syntax for Text Alignments 
```markdown
Left Alignment

| column 1 | column 2 | column3 |
| :---- | :---- | :---- |
| block one | block two | block three |
| block four | block five | block six |


Center Alignment

| column 1 | column 2 | column3 |
| :----: | :----: | :----: |
| block one | block two | block three |
| block four | block five | block six |


Right Alignment
| column 1 | column 2 | column3 |
| ----: | ----: | ----: |
| block one | block two | block three |
| block four | block five | block six |
```

